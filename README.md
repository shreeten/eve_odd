# eve_odd
<br>
this is the code to find if the number is even or odd
a=int(input("Enter the number you wanna check: "))
if a%2 ==0:
    print("The given Number",a,"is Even")
elif a%2 !=0:
    print("The given number",a,"is Odd")
elif a<=0:
    print("put the appropriate number")
else:
    print("The number is neither Even nor Odd")
