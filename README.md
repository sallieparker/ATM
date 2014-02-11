# JavaScript ATM Project Description:

This focus of this project is on using JavaScript and manipulating the DOM. We're most interested in your understanding of the JavaScript language and best practices.

The existing code already satisfies the following requirements:

- A user can deposit money into one of the bank accounts.
- A user can withdraw money from one of the bank accounts.
- The balance in an account can't go negative. If a user tries to withdraw more money than exists in the account, ignore the transaction.
- When the balance of the bank account is $0 the background of that bank account should be red. It should be gray when there is money in the account.
- What happens when the user wants to withdraw more money from the checking account than is in the account? These accounts have overdraft protection, so if a withdrawal can be covered by the balances in both accounts, take the checking balance down to $0 and take the rest of the withdrawal from the savings account. If the withdrawal amount is more than the combined account balance, ignore it.
- Make sure there is overdraft protection going both ways.

# Your Job:

1) Refactor the code so that it is:

  - Object-oriented (as opposed to procedural)
  - DRY
  - Follows good naming conventions

2) Comment the code to explain what it does and why you made certain design decisions.

# Instructions:

1. Clone this repository to your local machine -- ***don't fork it***.
2. Make all changes on your own branch named with your github name, and commit as necessary.
3. Zip your local folder, including the .git folder, and email to your contact at GA.