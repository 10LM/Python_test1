# Python_test1
### my first test   
*number=input("enter a number:")  # 判断一个数和一百的大小  
if number>100:  
 print("number is more then 100")  
else:  
 print('number is no more then 100')*
 
 *#  -*- coding: utf-8 -*-
amount=float(input("please enter a number:")) #输入总的数量  
inrate=float(input("please enter rate:")) #输入数率  
period=int(input("please enter period:")) #输入要查看的年限  
i = 0 #初始利息总和  
year = 1 #初始化年限为1  
while year<=period: #当年限小于等于输入年数时循环  
 i = amount+amount\*inrate #当前的利息总和  
 year = year+1  
 print("the{} {:.2f}".format(year,i)) #打印输出，format字符串格式化  
 amount=i #利滚利模型*  
 
 
*N=8#求八个数的平均数  
SUM=0  
Average=0  
count=0  
while count<N:  
 number=float(input())  
 SUM=SUM+number  
 count=count+1  
 Average=SUM/N  
print("SUM{},aVERAGE{:.2f},CONUT{}".format(SUM,Average,count))*


*# -*- coding: utf-8 -*-#华氏摄氏温度转变  
inputtemputer=float(input("请输入现在的温度："))  
F=inputtemputer*1.8+32  
print(" 现在的华氏温度是{}".format(F))*  


>>> data = ("shiyanlou", "China", "Python")  #元组拆封与元组封装  
>>> name, country, language = data  
>>> name  
'shiyanlou'  
>>> country  
'China'  
>>> language  
'Python'  
