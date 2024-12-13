# ALEPH 2024 Hackaton MVP - Zama Track 
## Confidential public procurement processes evaluator system MVP

This repo contains the documentation and code for the MVP of the Confidential public procurement processes evaluator system.

### MVP
**This MVP will be focused on a specifically on "Open competitive bidding (or tendering)" method without the ZKP handling on the bidding process**

**Public procurement sample will focused on a process evaluating two criterias:**
**1. Cuantitative: The smaller price.**
**2. Compliance: Has demostrable experience in similar projects in the past? (yes/no)**

### System Desing
Using this will show how the system will work with more complex processes and more criterias.

#### Architecture

**dApp:** Interacts with bidders, Requesters, and the blockchain.
**Smart Contract:** Handles the procurement process, evaluation rules, and bid data.
**Zero-Knowledge Proof (ZKP):** Ensures bid data is encrypted correctly and using the latest version of the dApp.
**Fully Homomorphic Encryption (FHE):** Protects sensitive data during evaluation.
**Wallet:** Used by bidders for authentication and bid submission.
**Requesters:** Interact with the system to create, test, and approve the procurement process.
**System Administrators:** Monitor and configure the system.

#### Smart Contract & ZKP Generation Flow
The smart contract and ZKP generation work during the bidding process, including the following steps:

**Procurement Process Creation:** Requesters input data, and the system generates a smart contract automatically.
**Bidder Submission:** Bidders submit encrypted data, and ZKPs are generated to ensure the submission is valid and encrypted correctly.
**Evaluation:** The smart contract evaluates encrypted bids based on the predefined rules.
**Result Query:** Bidders query the results, which are encrypted, and the dApp decrypts and presents the outcome.

## Long-term Implementation Steps

Step 1: Set up the dApp framework (frontend & backend).

Step 2: Integrate with ZAMA FHEvm to handle encryption and smart contract generation.

Step 3: Implement the smart contract generation logic using ZAMA Solidity Developer GPT.

Step 4: Develop bid submission logic with wallet integration and ZKP generation.

Step 5: Build the evaluation logic in the smart contract.

Step 6: Deploy the smart contract and enable bidder interaction.

Step 7: Implement the auditability layer using the immutable nature of the smart contract and ZKP verification.

## MVP Implementation

Step 1: Set up the dApp framework (frontend & backend).

Step 2: Integrate with ZAMA FHEvm to handle encryption and smart contract generation.

Step 3: Develop bid submission logic with wallet integration and ZKP generation.

Step 5: Build the evaluation logic in the smart contract for the proposed MVP sample.

Step 6: Deploy the smart contract and enable bidder interaction.
Step 7: Build and run test suit.
