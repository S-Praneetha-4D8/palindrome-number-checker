n=int(input())
cp=n
rev=0
while(cp>0):
    rem=cp%10
    rev=rev*10+rem
    cp=cp//10
if(rev==n):
    print(f'{n} is a palindrome number')
else:
    print(f'{n} is not a palindrome number')
