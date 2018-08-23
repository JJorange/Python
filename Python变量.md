```python
#!/usr/bin/python
#coding:utf-8
#from __future__ import division

# shuchu
print "Hello Word!" #print hello world

#变量和赋值

a = 1
b = 0.5
c = "123"

#链式赋值
a = b = c = 1

#增量赋值
n = a * 10

#多元赋值
x,y = 1,2

#++/--
a = a + 1

a = 1
a = 0.5
a = "123"

a = 1
b = 0.5
print type(a)
print type(b)

#python 没有数字上限



#复数
a = 10 + 5j
print a

#字符串 '' "" ''' '''

print "my name is 'shuai' "
print 'my name is "shuai" '
print '''my name is "shuai", 'cute' '''

str = "abcdefg"

#下标取值法
print str[5]
#切片操作法
print str[1:5] #前闭后开区间 [1,5)
print str[:5] #前面数字省略
print str[1:] #后面数字省略
print str[:]  #字符本身
print str[1:-1] #负数代表length -n 
#print str[1:20]
#str[2] = "1" 是不行的

print "my name\nis shuai"
#字符串的拼接，字符串的重复 只有+ *
print str + "haha"
print str * 3
print type(str) #没有字符和字符串类型的区别

#len函数用于求字符串或其他有长度的数字类型的长度
print len(str)
#字符串格式化
print "my name is %s ." %" shuai"
print "nianling %d ." %20

print type(True)

#输入输出
#GetAge = raw_input("请输入你的年龄:")
#print int(GetAge) + 5

#浮点型
#float(GetAge)
#str(GetAge)

#三种除法
a = 1.0
b = 2
print a/b #传统除法

#地板除法 向下取整
print a//b

#精确除法
#乘方运算 **

# && || ! and or not
a = 1
b = 2
c = d = 4
print a != b and c == d

#[] () {} 列表List 元组tuple 字典dict
list1 = [1,0.5,"123",True,[1,2,3]]
#下标取值法
print list1[3]
#切片操作
print list1[1:-1]
list1[3] = "TestChange"
print list1

tuple1 = (1,2,3,0.5,"123")

print tuple1[1]
#元组不能被修改

#dict字典 key-value
dict1 = {"Ip":"127.0.0.1", "Host":"www.baidu.com"}
print dict1["Ip"]
print dict1["Host"]
dict1["Ip"] = 123
print dict1

```
