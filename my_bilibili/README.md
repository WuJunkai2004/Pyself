![](https://github.com/WuJunkai2004/Pyself/raw/master/my_image/bilibili.png)
# A python module for bilibili.com  
#### Edit by Wu Junkai  
#### wujunkai20041123@outlook.com  
### introduce  
This is a module for [bilibili.com](https://www.bilibili.com).  
It was edited in python IDLE.  
### init  
you can init it like this.  
```
import my_bilibili as my
foo=my.bilibili()
```
### search
　　The function is running depend on [search.bilibili.com](https://search.bilibili.com). you must give a str as keywords. Others including kind , page and so on.  
This is a table for search's  values.
 
 | variable | type | remark | 
 | --- | --- | --- |
 | keyword | str | 写了也没用 | 
 | kind | str | `all`,`video`,`bangumi`,`pgc`,`live`,`article`,... |
 | page| int | 页数 | 
 | order| str | 下周再整理 | 
 | duration| int | `0`:`全部时长`;`1`:`10分钟以下`;`2`:`10-30分钟`;`3`:`30-60分钟`;`4`:`60分钟以上` | 

##### example 1
```
for i in foo.search('鬼灭之刃',kind='bangumi'):
    print(i)
```
##### example 2
```
for i in foo.search('鬼灭之刃',kind='video',page=2):
    print(i)
```

### ranking
　　building...
