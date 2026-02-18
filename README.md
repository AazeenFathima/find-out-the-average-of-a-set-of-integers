# find-out-the-average-of-a-set-of-integers

count = int(input("Enter the count of numbers: "))
i = 0
sum = 0
for i in range(count):
    x = int(input("Enter an integer: "))
    sum = sum + x
avg = sum/count
print(" The average is: ", avg)


OUTPUT :
Enter the count of numbers: 3
Enter an integer: 10
Enter an integer: 20
Enter an integer: 30
The average is:  20.0
