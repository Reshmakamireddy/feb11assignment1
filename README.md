sno=int(input('Enter sno:'))
sname=input('Enter name:')
s1=int(input ('s1 marks:'))
s2=int(input('s2 marks:'))
s3=int(input('s3 marks:'))
s4=int(input('s4 marks:'))
s5=int(input('s5 marks:'))
s6=int(input('s6 marks:'))
total=s1+s2+s3+s4+s5+s6
avg=total/6
if avg>91:
    print('o-Grade')
elif avg>=81:
    print('A-Grade')
elif avg>=71:
    print('B-Grade')
elif avg>=60:
    print('C-Grade')
elif avg>=50:
    print('D-Grade')
elif avg>=40:
    print('pass')
else:
    print('fail')

Output:-
Enter sno:1
Enter name:reshma
s1 marks:92
s2 marks:95
s3 marks:96
s4 marks:89
s5 marks:97
s6 marks:91
o-Grade

