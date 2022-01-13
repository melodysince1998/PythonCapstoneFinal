#Banking Project By: Melody Fonville 
#Jan 2022
#Using OOP.

import random
import time

# Parent Class Responsibility: 
# Part 1:  Holds details about user
class UserAccount:
    # Construct an Account object
    def __init__(self, id, checkingBalance = 0, savingsBalance = 0, annualInterestRateSavings = 3.4):#initalizer, self variable and argeument for the user
        #creating a new property/METHOD on the object
        self.id = id
        self.checkingBalance = checkingBalance
        self.savingsBalance = savingsBalance
        self.annualInterestRateSavings = annualInterestRateSavings
 #self variable is referring to the object itself. Anything assigned to self is assigned to the oject.
    def getId(self):
        return self.id  
 
    def checkingAccountBalance(self):
        return self.checkingBalance
 
    def withdrawCheckingAccount(self, amount):
        self.checkingBalance -= amount
 
    def depositCheckingAccount(self, amount):
        self.checkingBalance += amount
        
    def savingsAccountBalance(self):
        return self.savingsBalance
 
    def withdrawSavingsAccount(self, amount):
        self.savingsBalance -= amount
 
    def depositSavingsAccount(self, amount):
        self.savingsBalance += amount

    def savingsAccountMonthlyInterest(self):
        return self.savingsBalance * self.savingsAccountMonthlyInterest()
    
    def savingsAccountAnnualInterestRate(self):
        return self.annualInterestRateSavings
 
    def savingsAccountMonthlyInterestRate(self):
        return self.annualInterestRateSavings / 12

def main():
    # Creating accounts
    accounts = []
    for i in range(1000, 9999):
        account = UserAccount(i, 0)
        accounts.append(account) #add new item to the previous on the list

    while True: # As long as the user inputs a 4 digit pin the program will continue to 
    
            # Reading id from user
            print("Welcome to the UNIVERSAL MONEY HEIST BANK.")
            id = int(input("\nEnter 4-digit account pin: "))
    
            # Loop till id is valid
            while id < 1000 or id > 9999:  #If user pin is less than 1000 greater than 9999 will print below.
                id = int(input("\nInvalid Id.. Re-enter: "))
    
            # Iterating over interface
            while True:
                
                # Printing menu
                print("\nHow can UMHB help you today?")
                print("""\n1 - View Checking Balance \t\t2 - Withdraw Checking \t\t\t3 - Deposit Checking \t\t\t\t
                        \n4 - View Savings Balance \t\t5 - Withdraw Savings \t\t\t6 - Deposit Savings \t\t\t\t
                        \n7 - Exit """)
    
                # Reading selection
                selection = int(input("\nEnter your numerical selection: "))
    
                # Getting account object
                for acc in accounts:
                    # Comparing account id
                    if acc.getId() == id:
                        accountObj = acc
                        break
    
                # View Checking Balance
                if selection == 1:
                    # Printing balance
                    print(f"\nChecking account balance: ${format(accountObj.checkingAccountBalance(), '.2f')} ")
                    time.sleep(2)
                    
    
                # Checking Withdraw
                elif selection == 2:
                    # Reading amount
                    amt = float(input("\nEnter amount to withdraw from checking: "))
                    
                    if amt < accountObj.checkingAccountBalance():
                        # Calling withdraw method
                        accountObj.withdrawCheckingAccount(amt)
                        # Printing updated balance
                        print(f"Updated checking account balance: ${format(accountObj.checkingAccountBalance(), '.2f')} ")
                        time.sleep(2)
                    else:
                        print(f"\nYour checking account balance is less than withdrawl amount: ${format(accountObj.checkingAccountBalance(), '.2f')} ")
                        time.sleep(2)
    
                # Deposit
                elif selection == 3:
                    # Reading amount
                    amt = float(input("\nEnter amount to deposit in checking: "))
                    ver_checking_deposit = input(f"Is ${format(amt, '.2f')} the correct amount to deposit, Yes or No ? ")
                    ver_checking_deposit = ver_checking_deposit.upper()
                    
                    if ver_checking_deposit == "YES":
                        # Calling deposit method
                        print("\nVerified checking account deposit.")
                        time.sleep(2)
                        accountObj.depositCheckingAccount(amt)
                        # Printing updated balance
                        print(f"\nUpdated checking account balance: ${format(accountObj.checkingAccountBalance(), '.2f')} ")
                        time.sleep(2)
                    else:
                        break
    
                # View Checking Balance
                elif selection == 4:
                    # Printing balance
                    print(f"Savings account balance: ${format(accountObj.savingsAccountBalance(), '.2f')} ")
                    time.sleep(2)
    
                # Savings Withdraw
                elif selection == 5:
                    # Reading amount
                    amt = float(input("\nEnter amount to withdraw from savings: "))
                    
                    if amt < accountObj.savingsAccountBalance():
                        # Calling withdraw method
                        accountObj.withdrawSavingsAccount(amt)
                        # Printing updated balance
                        #print(f"Updated checking account balance: ${format(accountObj.checkingAccountBalance(), '.2f')} ")
                        print(f"Updated savings account balance: ${format(accountObj.savingsAccountBalance(), '.2f')} ")
                        time.sleep(2)
                    else:
                        print(f"\nYour savings account balance is less than withdrawl amount: ${format(accountObj.savingsAccountBalance(), '.2f')} ")
                        time.sleep(2)
    
                # Savings Account Deposit
                elif selection == 6:
                    # Reading amount
                    amt = float(input("\nEnter amount to deposit in savings: "))
                    ver_savings_deposit = input(f"Is ${format(amt, '.2f')} the correct amount to withdraw, Yes or No ? ")
                    ver_savings_deposit = ver_savings_deposit.upper()
                    
                    if ver_checking_deposit == "YES":
                        print("\nVerified savings account deposit.")
                        time.sleep(2)
                        # Calling deposit method
                        accountObj.depositSavingsAccount(amt)
                        # Printing updated balance
                        print(f"Updated savings account balance: ${format(accountObj.savingsAccountBalance(), '.2f')} ")
                        time.sleep(2)
                    else:
                        break
                        
                elif selection == 7:
                    print("\nTransaction is now complete.")
                    print("Transaction number: ", random.randint(10000, 1000000))
                    print("Current Interest Rate: ", accountObj.annualInterestRateSavings)
                    print("Monthly Interest Rate: ", accountObj.annualInterestRateSavings / 12)
                    print("Thank you for choosing the UNIVERSAL MONEY HEIST BANK as your bank \n Not as great as Chase but still good enough!")
                    exit()
    
                # Any other choice
                else:
                    print("\nThat's an invalid choice.")
                    break
    
    # Main function
main()