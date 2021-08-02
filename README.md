# simple-budget-app
Educational python project. An app with some different functions like: -show balance -make deposite -transfer through spending categories
Also you can draw a diagram of all withdrawls and deposits.

Full project description:
That simple programm is able to insrantiate objects based on different budget categories like: Food, Clothing and so on.
Category class contains several methods:
-deposit:
  Accept amount and the description. Appends object to the ledger list
-withdraw:
  Similar to deposit
-get_balance:
  returns current balance
-transfer:
  transfer from one catagory to others
-check_funds:
  return false if the amount is greater, than current balance(if smaller, returns true)
-get_withdrawls:
  return total withdrawl
-create_spend_chart:
  drawing spendings chart
-get_totals:
  return totals of all categories
  
