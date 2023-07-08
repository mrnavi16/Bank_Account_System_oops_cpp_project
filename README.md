# Bank_Account_System_oops_cpp_project :-

Note: Understanding the question (oops, c++)

Q-1) The Account department of the compnay needs an object oriented solution to maintain the
account details of its clients. Each account has an account title (name of account holder), serial
number, a unique account number and a balance. Transactions that can be made are credit and
debit. The debit function also needs to ensure that the withdrawn amount does not exceed to
available balance in the account of a client. At the end of year the bank credits each account with

aninterest and the amount of interests a function of the type of account (to be discussed below).

There could be two distinct types of accounts in the department, Plus account and freedom
account. A Plus account requires clients to maintain a minimum balance and applies a fixed
interest of x9 at the end of each year. The percentage of interest is determined at the start of

each year.

The freedom account does not require any minimum balance but charges a fixed fee for every
transaction (debit, credit) that is performed. So every time a transaction is performed the fee is
deducted from the balance. The interest on freedom accounts is a fixed amount (not a

percentage) that is determined at the start of each year. This amount is added to the balance as

an interest.

You need to provide classes to implement the functionality discussed above. You may define a
dass Account and inherit PlusAccount and FreedomAccount from Account. Function
overriding/polymorphism may also be handy. After defining the classes in this hierarchy, write a
program with an array of 10 pointers to Accounts. Create 5 accounts using dynammic memory
allocation by getting user choice for the type of account. For the first account, perform some

transactions like debit, credit, interest and finally display the balance in this account
