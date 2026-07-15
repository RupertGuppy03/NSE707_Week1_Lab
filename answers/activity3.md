## 1. What happens if the opening balance is negative?
the balance will displaty a negative balance, there is no logic preventing this

## 2. What happens if a deposit amount is negative?
then the balance will decrease, there is no logiv prventing a deposit amount from being negative

## 3. What happens if a withdrawal amount is greater than the balance?
the program allows this to happen even though the actual balance may not be enough to cover this withdrawal 

## 4. Is the transaction fee calculation clearly documented?
no, it is not clearly documented becasue it is not displayed in the output

## 5. Is the class easy to test?
no beasue there are not any functions to prevent otherwise incorrect outputs to be displayed. e.g, there is no logic preventing the balance from being negative so we cant easily tst this

## 6. What functional requirements are missing?
- the program should reject negative amounts from deposits
- the program should not allow the balance to be less than 0


## 7. What non-functional quality attributes are relevant?
- reliability, nothing to handle bad output without breaking
- maintainability, no code is documented with comments expalining what each funtion does
- testability, the program is currently hard to test becasue there is no sound logic to test