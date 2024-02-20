# cos_project.py
principal = int(input("  inital  principal amount"))
rate = int(input("annual interest rate"))
time = int(input(" number of years:"))
n = int(input(" number of years: "))
# calculate the simple and compound interest
simple_interest = principal * (1 + rate * time)
compound_interest = principal * (1 + rate / n)
# print the results

print("yusuf & sons")
print("simple interest: {:.2f}".format(compound_interest))
print("compound interest:{:.2f}".format(compound_interest))
