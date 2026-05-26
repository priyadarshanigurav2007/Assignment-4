# Assignment 4



#1. Display even numbers from 1–10


for i in range(1, 11):
    if i % 2 == 0:
        print(i)

#2.Add odd numbers from 1–10


sum = 0
for i in range(1, 11):
    if i % 2 != 0:
        sum += i
print("Sum of odd numbers:", sum)



#3. Fibonacci series between 0 to 50


a, b = 0, 1
print("Fibonacci series between 0 and 50:")
while a <= 50:
    print(a, end=" ")
    a, b = b, a + b






#4. Remove characters at odd index positions

string = input("Enter a string: ")

result = ""
for i in range(len(string)):
    if i % 2 == 0:
        result += string[i]

print("Result:", result)
