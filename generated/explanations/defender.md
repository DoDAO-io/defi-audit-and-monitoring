## Header
This is the course header. This will be added on top of every page. Go to [DoDAO.io](https://www.dodao.io) to know more.

 ---
 
 ## OpenZeppelin Defender
 
 **Introduction to Defender**        
## Features of Defender Intro OpenZeppelin Defender provides exceptional functionality for the management of smart contracts. Its user-friendly interface allows for the management of multiple smart contracts, the creation of proposals, and the ability to upgrade  contracts within the Defender dashboard, simplifying the process of smart contract development. Additionally, Defender offers notifications for events within the smart contract, eliminating the need for constant monitoring of Etherscan for updates.  The platform's full range of features is outlined in detail below.
 
 **Defender Admin**        
# Admin
The Defender admin serves as a centralized platform for managing all of our smart contracts. It offers the capability to create multi-signature wallets instantly, which can be utilized for signing transactions and proposals. The Defender admin also enables users to perform the following actions:
**Add contract** * Contract Management
    Defender Admin allows us to import multiple contracts and manage them directly using the interface.
* Multisig wallet (Gnosis safe)
    Multisignature wallets can be created instantly and can be used to sign transactions. The threshold value can also be given while creating the Gnosis safe.
* Timelocks
    Timelocks are smart contracts that allow for the delay of proposals or function calls in the target contract. The individuals designated as proposers are responsible for scheduling and canceling operations, while executors handle the execution of these operations. The timelock contract itself 
    is assigned the admin role, allowing it to manage and oversee the actions of both proposers and executors.


**Add Proposals** The proposals can be made once the contract is added to the admin dashboard. The smart contracts can be added to the admin dashboard and proposals can be made directly using [Defender Admin API](https://docs.openzeppelin.com/defender/admin-api-reference) and [defender-admin-client](https://www.npmjs.com/package/defender-admin-client).  * Upgrades
    The Defender Admin provides a straightforward process for upgrading smart contracts. To initiate an upgrade, the next version of the contract must be deployed and its deployed address must be provided in the new implementation address field within the Defender Admin. Upgradeability is only possible for contracts that implement the EIP-1967 standard, which is verified during the import process. Additionally, contracts can be upgraded in a local environment by utilizing the "updateProxy" function, which can be accessed by installing the OpenZeppelin package.
* Modifying access control
    The Defender Admin allows for the modification of access and roles within the platform itself. For this functionality to be available, the contract must have the “grantRole” and “RevokeRole” functions. If the ABI of the contract includes these functions, Defender provides the capability to fill them using the roles that have been previously indexed in the contract. In instances where a new role needs to be added to the contract, but the function and indexing have not been established, the corresponding “bytes32” of the contract can be provided to add the new role.
* Pausing and unpausing the contract

    The OpenZeppelin platform offers the ability to pause and resume smart contracts. This feature is implemented as a precautionary measure to protect the contract from potential bugs. The OpenZeppelin Defender allows for the pausing of specific functions and provides modifiers to execute functions while in a paused state. In order to enable this feature, the contract's ABI must include the pause() and unpause() functions. The Defender Admin also includes the capability to check the status of the contract and indicate whether it is currently paused by checking for the paused() or isPaused() function in the contract's ABI.

* Admin actions

    The Defender Admin allows for custom actions to be taken through the use of the admin action feature. This includes the ability to make function calls and create batch proposals. A batch proposal refers to a single transaction that includes multiple function calls from one or more contracts. This feature allows for the atomic execution of multiple actions. To utilize this functionality, it is recommended to use a multisig wallet as the execution strategy and ensure that all batch transactions are executed on the same network.
 
 
