## Problem Statement: Banking System Simulation

# You are tasked with developing a basic banking system program that allows users to perform various actions related to their account. Your program should incorporate appropriate control flow structures and error handling. Below are the detailed tasks and requirements:

1. Account Creation:

Input:
User's name
Initial deposit amount
Conditions:
If the initial deposit is less than $100, display a message indicating that the deposit must be at least $100.

Output:
Display a success message if the account is created.

2. Account Balance Inquiry:

Input:
No additional input required.
Output:
Display the user's account balance.

3. Withdrawal:
Input:
Withdrawal amount
Conditions:
Check if the withdrawal amount is greater than the account balance. If so, display an "insufficient funds" message.
Output:
Display a success message if the withdrawal is completed.

4. Deposit:
Input:
Deposit amount
Conditions:
If the deposit amount is less than $50, display a message indicating that the deposit must be at least $50.
Output:
Display a success message if the deposit is completed.

5. Interest Calculation:
Input:
No additional input required.
Loop:
Implement a loop to calculate and display the account balance after one year of a 5% interest rate.
Use either a for loop or a while loop.
Output:
Display the account balance after one year.

6. Menu System:
Input:
User's choice (1-6)
Control Flow:
Display a menu to the user with options to perform the above actions.
Use a switch statement or nested if-else statements to execute the chosen action.
Output:
Provide appropriate messages based on the chosen action.
Additional Considerations:

Implement error handling to handle unexpected input.
Ensure the program keeps running until the user chooses to exit.

Example:
Consider the following interactions as an example:

User chooses option 1 (Account Creation):
Input:
User's name: John Doe
Initial deposit amount: $80
Output:
Display a message: "Initial deposit must be at least $100."

User chooses option 1 again (Account Creation):
Input:
User's name: Jane Smith
Initial deposit amount: $150
Output:
Display a success message: "Account for Jane Smith created successfully."

User chooses option 2 (Account Balance Inquiry):
Output:
Display the account balance: "Your account balance is: $150."

User chooses option 3 (Withdrawal):
Input:
Withdrawal amount: $200
Output:
Display an "insufficient funds" message.

User chooses option 3 again (Withdrawal):
Input:
Withdrawal amount: $50
Output:
Display a success message: "Withdrawal of $50 successful. Your new balance is: $100."
... and so on.

Use this example to structure your program and ensure it meets the specified requirements. If you have any questions or need further clarification, feel free to ask!


## Submission Link: https://forms.gle/7Jgagnb6tRdmQyQU9