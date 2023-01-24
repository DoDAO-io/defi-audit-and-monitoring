## Header
This is the course header. This will be added on top of every page. Go to [DoDAO.io](https://www.dodao.io) to know more.

 ---
 
 ## OpenZeppelin Defender
 
 
---

##### What is the main function of the Defender admin?  

- [x]  To manage smart contracts
- [ ]  To create multisignature wallets
- [ ]  To provide notifications for events within the smart contract
- [ ]  To simplify the process of smart contract development
  
Hint: NoHint
         
Explanation: The Defender admin serves as a centralized platform for managing all of our smart contracts. It offers the capability to create multi-signature wallets instantly, which can be utilized for signing transactions and proposals.

Sub Topics: No Sub-Topics
 

---

##### What kind of wallets can be created instantly using the Defender admin?  

- [ ]  Upgradeable wallets
- [ ]  Single signature wallets
- [ ]  Timelock wallets
- [x]  Multisignature wallets
  
Hint: Gnosis safe
         
Explanation: Multisignature wallets can be created instantly using defender admin.

Sub Topics: No Sub-Topics
 

---

##### What is the purpose of timelocks in the Defender admin?  

- [ ]  To manage and oversee the actions of both proposers and executors
- [x]  To delay proposals or function calls in the target contract
- [ ]  To sign transactions and proposals
- [ ]  To upgrade smart contracts
  
Hint: Delay
         
Explanation: Timelocks are smart contracts that allow for the delay of proposals or function calls in the target contract.

Sub Topics: No Sub-Topics
 

---

##### What is the main function of the defender autotask feature?  

- [ ]  To run javascript snippets on a schedule
- [ ]  To run javascript snippets in response to sentinel events
- [ ]  To integrate with third-party services
- [x]  Both A and B
  
Hint: NoHint
         
Explanation: The defender autotask feature enables users to run javascript snippets on a schedule, or trigger them in response to sentinel events or public webhooks.

Sub Topics: No Sub-Topics
 

---

##### What is the use of webhook feature in Autotasks?  

- [ ]  To run Autotasks at a specific time
- [x]  To create a secret URL for Autotasks and invoke it whenever an HTTP request is posted
- [ ]  To execute functions or multiple functions in response to a sentinel or an event
- [ ]  To provide gasless transactions for dapp users
  
Hint: NoHint
         
Explanation: Defender will create a secret URL for your Autotask, and invoke it whenever an HTTP request is posted to that endpoint. You can regenerate this URL at any time.

Sub Topics: No Sub-Topics
 

---

##### What is required for the upgradability feature to be available in the Defender admin?  

- [x]  The contract must implement the EIP-1967 standard and the deployed address should be provided
- [ ]  The contract's ABI must include the pause() and unpause() functions
- [ ]  The contract must have the “grantRole” and “RevokeRole” functions
- [ ]  The contract must be added to the admin dashboard
  
Hint: NoHint
         
Explanation: Upgradeability is only possible for contracts that implement the EIP-1967 standard, which is verified during the import process.

Sub Topics: No Sub-Topics
 

---

##### What is a batch proposal?  

- [ ]  A proposed transaction stored in a digital ledger
- [ ]  An executable program to perform multiple transactions
- [x]  A single transaction that includes multiple function calls from one or more contracts
- [ ]  An application to route transactions from one address to another
  
Hint: NoHint
         
Explanation: A batch proposal refers to a single transaction that includes multiple function calls from one or more contracts. This feature allows for the atomic execution of multiple actions.

Sub Topics: No Sub-Topics
 

---

##### Who is responsible for scheduling and canceling operations with Timelocks?  

- [x]  Proposers
- [ ]  Gnosis Safe
- [ ]  Admin
- [ ]  Executors
  
Hint: NoHint
         
Explanation: The individuals designated as proposers are responsible for scheduling and canceling operations, while executors handle the execution of these operations.

Sub Topics: No Sub-Topics
 

---

##### What is the most suitable condition for an auto-tasking code snippet?  

- [x]  The code snippet must export a handler function
- [ ]  The code snippet must be powered by AWS EC2
- [ ]  The code snippet must be powered by Google cloud
- [ ]  The code snippet must be powered by Azure
  
Hint: NoHint
         
Explanation: The code snippet must export a handler function and each auto task must be powered by AWS Lambda.

Sub Topics: No Sub-Topics
 

---

##### Which of the following is TRUE for a transaction to trigger a notification?  

- [ ]  The Transaction must directly invoke any of the selected Functions only
- [x]  Transaction must have a To, From, or Address (from the log) that matches the configured address
- [ ]  Transaction must have a To address that matches the configured address
- [ ]  The Transaction must match the Transaction Condition only in case of contract sentinel
  
Hint: NoHint
         
Explanation: Transaction must have a To, From, or Address (from the log) that matches the configured address. The transaction condition should be matched if specified.

Sub Topics: No Sub-Topics
 

---

##### What type of service does Sentinel Services provide?  

- [ ]  Custom webhooks authorisation
- [ ]  Development support for serverless computing
- [ ]  Data streaming to Datadog
- [x]  Comprehensive monitoring solution for transactions on smart contracts
  
Hint: NoHint
         
Explanation: Sentinels Services provides a comprehensive monitoring solution for transactions on smart contracts. It allows you to establish conditions on events, functions, and transaction parameters, and detect direct calls, internal transactions, and events emitted by the contracts.

Sub Topics: No Sub-Topics
 
