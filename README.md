ATM Simulator Project Description
This Python-based ATM Simulator mimics the real-world functionality of an Automated Teller Machine (ATM). The program allows users to perform basic banking operations like checking their balance, depositing and withdrawing money, changing their PIN, and viewing transaction history.

Features of the Project
1️⃣ ATM Card Insertion Simulation
The program starts by prompting the user to insert their ATM card and wait for a few seconds to simulate the real ATM experience.
2️⃣ PIN Authentication System
The user must enter a 4-digit PIN to access the ATM.
The program provides 5 attempts to enter the correct PIN before locking the account.
If the PIN is incorrect, the user is prompted with the remaining attempts.
3️⃣ Banking Operations
Once authenticated, users can perform the following transactions:

🔹 Balance Inquiry:

Displays the user's current account balance.
🔹 Deposit Money:

Allows the user to enter an amount to deposit, which is added to the balance.
Stores this transaction in the history.
🔹 Withdraw Money:

The user can withdraw money if their account has sufficient balance.
If the withdrawal amount exceeds the balance, an "Insufficient Balance" message is displayed.
The transaction is stored in history.
🔹 Change PIN:

The user can update their PIN after verifying the old one.
If the new PINs do not match, an error message is displayed.
🔹 View Transaction History:

Displays a list of all deposits and withdrawals made during the session.
🔹 Exit Option:

Allows the user to safely exit the ATM simulation.
Code Functionality Overview
✅ Uses time.sleep() to mimic real ATM processing delays.
✅ Implements a secure PIN validation system with a limited number of attempts.
✅ Uses functions for modularity, making the code easy to read and maintain.
✅ Includes transaction history storage for better user experience.

Use Cases
✔️ Best for beginners learning Python programming.
✔️ A good mini-project to understand banking operations in real-time applications.
✔️ Can be extended to integrate database connectivity for real-world implementation.
