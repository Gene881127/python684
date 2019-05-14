# python684
作業
rain = input("今天會下雨嗎?")
if(rain=="Y" or rain=="y"):
    print("出門記得帶傘!") 
    
    month = int(input("請輸入月份："))
if (month>=1 and month<=3):
    print(month,"月是春天!")    
elif (month>=4 and month<=6):
    print(month,"月是夏天!")
elif (month>=7 and month<=9):
    print(month,"月是秋天!")
elif (month>=10 and month<=12):
    print(month,"月是冬天!")
else:
    print(month,"月份不在範圍內!")    
    
    income = int(input("請輸入今年收入淨額："))
print("付稅金額：",end="")
if(income >= 2000000):
    print(income*0.3, end=" 元\n")  
elif(income >= 1000000):
    print(income*0.21, end=" 元\n")
elif(income >= 600000):
    print(income * 0.13, end=" 元\n") 
elif(income >= 300000):
    print(income * 0.06, end=" 元\n") 
else:
    print(income *0, end=" 元\n")
