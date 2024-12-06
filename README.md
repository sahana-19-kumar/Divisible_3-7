# Divisible_3-7
num = int(input("Enter a number: "))
if num % 3 == 0 and num % 7 == 0:
    print("{num} is divisible by both 3 and 7.")
elif num % 3 == 0:
    print("{num} is divisible by 3.")
elif num % 7 == 0:
    print("{num} is divisible by 7.")
else:
    print("{num} is not divisible by 3 or 7.")
