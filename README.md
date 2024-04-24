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
## Streamlit PyChain Application Screenshot