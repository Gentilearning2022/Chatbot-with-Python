# Write your code here
print("Earned amount: ")
print("Bubblegum: $202")
print("Toffee: $118")
print("Ice cream: $2250")
print("Milk chocolate: $1680")
print("Doughnut: $1075")
print("Pancake: $80")

# Calculate total income
total_income = 202 + 118 + 2250 + 1680 + 1075 + 80
print("Income: $" + str(total_income))

# Prompt user for staff expenses
staff_expenses = float(input("Staff expenses: "))

# Prompt user for other expenses
other_expenses = float(input("Other expenses: "))

# Calculate net income
net_income = total_income - (staff_expenses + other_expenses)
print("Net income: $" + str(net_income))
