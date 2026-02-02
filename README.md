# program-89
# Recursive function to print numbers from n to 0
def print_till_zero(n):
    if n < 0:  # base case for negative numbers
        return
    print(n)
    print_till_zero(n - 1)  # recursive call with n-1

# Input from user
num = int(input("Enter a number: "))

# Call the function
print_till_zero(num)
output
Enter a number: 8
8
7
6
5
4
3
2
1
0
