ch=100
bg=180
ic=40
bsc=300
df=10
cname=input('enter customer name:')
Cphone=input('enter customer phn number:')
chq=int(input('enter no.of chocolates:'))
dfq=int(input('enter no.of bubble gums:'))
icq=int(input('enter no.of ice creams:'))
bscq=int(input('enter no.of biscuit packets:'))
bgq=int(input('enter no.of dark fantasy'))
bill=(ch*chq)+(bg*bgq)+(ic*icq)+(bsc*bscq)+(df*dfq)
if bill>5000:
  disc=bill*10/100
  tax=bill*10/100
elif bill>3000:
    disc=bill*8/100
    tax=bill*10/100
elif bill>2000:
    disc=bill*5/100
    tax=bill*18/100
elif bill>1000:
    disc=bill*3/1000
    tax=bill*18/100
else:
    print('invalid')
mainbill=bill-disc+tax
print('bill amount:',mainbill)

OUTPUT:
enter customer name:anusha
enter customer phn number:9393
enter no.of chocolates:5
enter no.of bubble gums:2
enter no.of ice creams:9
enter no.of biscuit packets:1
enter no.of dark fantasy:10
bill amount: 1906.7400000000002
