# CHALLENGE_18
# PyChain Ledger
## Background
You’re a fintech engineer who’s working at one of the five largest banks in the world. You were recently promoted to act as the lead developer on their decentralized finance team. Your task is to build a blockchain-based ledger system, complete with a user-friendly web interface. This ledger should allow partner banks to conduct financial transactions (that is, to transfer money between senders and receivers) and to verify the integrity of the data in the ledger.

You’ll make the following updates to the provided Python file for this Challenge, which already contains the basic `PyChain` ledger structure that you created throughout the module:

1. Create a new data class named `Record`. This class will serve as the blueprint for the financial transaction records that the blocks of the ledger will store.

2. Change the existing `Block` data class by replacing the generic `data` attribute with a `record` attribute that’s of type `Record`.

3. Create additional user input areas in the Streamlit application. These input areas will collect the relevant information for each financial record that you’ll store in the `PyChain` ledger.

4. Test your completed `PyChain` ledger.

---

## Run Locally

<span style="color:white;font-weight:100;font-size:15px">
    <b>Install Streamlit:</b>
</span>

    pip install streamlit
    
<span style="color:white;font-weight:100;font-size:15px">
    <b>Run Streamlit App:</b>
</span>

    streamlit run pychain.py

---
# Streamlit PyChain Application Screenshot

<img width="1440" alt="Screenshot 2024-04-24 at 4 56 32 PM" src="https://github.com/kimrodriguezFINTECH/CHALLENGE_18/assets/152752672/25267de3-b0b4-473b-a07d-a76e7c2510e4">

# Scenario: Adding New Blocks

<img width="723" alt="Screenshot 2024-04-24 at 4 38 11 PM" src="https://github.com/kimrodriguezFINTECH/CHALLENGE_18/assets/152752672/7f149ba8-283a-4f63-b6e3-d2c1837f619f">

# Scenario: Validating Blocks

<img width="1440" alt="Screenshot 2024-04-24 at 4 51 47 PM" src="https://github.com/kimrodriguezFINTECH/CHALLENGE_18/assets/152752672/9ca8499d-466f-4ff7-98b4-39cec19c503d">

This Streamlit Application mimics a blockchain-based ledger system that allows users to conduct financial transactions (transfer money between senders and receivers) and to verify the integrity of the data in the ledger.

To use the application, the user is prompted to enter a Sender address, Receiver address, and the Amount of crypto to send. The "PyChain Ledger" tracks and stores the transactions and the user is able to inspect each block/transaction using the "Block Inspector" drop-down menu located to the left of the application. The user is also able to evaluate the Blockchain Ledger System by clicking the "Validate Chain" button, which compares the hash of the previous block to the previous hash of the current block.
