# Bank-Locker-Authentication-Script

### Project Description:
This project demonstrates the use of variables, loops, and conditional statements in Bash scripting.
The script simulates a simple bank locker authentication system. When executed, it prompts the user to enter their username, company name, and PIN. The provided inputs are then validated against predefined credentials.
If all details match, access to the locker is granted; otherwise, access is denied.

### Steps:

The following command was used to create the script file.

<img width="607" height="62" alt="Screenshot 2026-02-04 161734" src="https://github.com/user-attachments/assets/08ff08a0-7b38-4f8a-b27f-96e4e970cff0" />

The next step was to implement the script logic as shown below.

<img width="1366" height="682" alt="Screenshot 2026-02-04 161542" src="https://github.com/user-attachments/assets/096c69c9-2820-4e16-a92f-92eac5978789" />

The script begins by defining the Bash interpreter to ensure it is executed using the correct shell environment.

Next, variables are initialized to store user input, including the username, company name, and PIN. These variables are initially set as empty strings and are later populated during execution.

A `for` loop is used to control the input flow. Based on the loop counter, conditional statements prompt the user to enter specific information:
- username on the first iteration
- company name on the second iteration
- PIN on the third iteration

Once all required inputs are collected, the script evaluates them using conditional logic. The entered values are compared against predefined credentials.

If all details match, authentication is successful and access to the locker is granted. Otherwise, the script denies access.

The following commands were used to grant execution permissions and run the script.

<img width="633" height="64" alt="Screenshot 2026-02-04 161817" src="https://github.com/user-attachments/assets/df085b59-7c77-444d-a54c-d1d828e9473e" />

After executing the script, the output was verified to confirm correct functionality.

<img width="866" height="228" alt="Screenshot 2026-02-04 161843" src="https://github.com/user-attachments/assets/be73c69c-bb2a-46f8-8760-0afadfe2df6e" />
<img width="651" height="216" alt="Screenshot 2026-02-04 161906" src="https://github.com/user-attachments/assets/c3fee4e1-9d42-422e-accf-4a22af775f75" />

### Skills Learned:

- Shell scripting basics (variables, loops, conditionals)

- User input handling in shell scripts

- Simple authentication logic





