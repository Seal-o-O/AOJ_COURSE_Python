# Watch

Write a program which reads an integer SS [second] and converts it to h:m:sh:m:s where hh, mm, ss denote hours, minutes (less than 60) and seconds (less than 60) respectively.

## Input

An integer SS is given in a line.

## Output

Print hh, mm and ss separated by ':'. You do not need to put '0' for a value, which consists of a digit.

## Constraints

- 0≤S≤864000≤S≤86400

## Sample Input 1

```
46979
```

## Sample Output 1

```
13:2:59
```

```python
a=int(input())
h=a//3600
m=(a%3600)//60
s=a%60
print(h,":",m,":",s, sep='')
```

```
>>>print(1)  
1  
>>> print("Hello World")  
Hello World  
 
>>> a = 1
>>> b = 'runoob'
>>> print(a,b)
1 runoob
 
>>> print("aaa""bbb")
aaabbb
>>> print("aaa","bbb")
aaa bbb
>>> 
 
>>> print("www","runoob","com",sep=".")  # 设置间隔符
www.runoob.com
```

