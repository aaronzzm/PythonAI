#python基础
---
##数据类型
###数字类型
####种类类型:
    >1.整数       int   6/2 = 3.0  6//2=3 
    >2.小数       float  
    >3.boolean    bool  0 为false 非0为true  空对象为false bool([])  

###序列
####种类类型:
   >1. 字符串   ""
   >2. 元组    ()
   >3. 列表    []
####公共特性
   >1.都可以用下标访问,比如 "hello Word"[0] ,(1,2,3,5)[1],["qq","ww","ee"][2]
   
### 集合
  set  表示方式: {}
#### 特性
  >1.无序
  >2.集合内的数据不重复
##### 常用操作
  求差集:  {1,2,3,4,5}-{4,5}
  求交集： {1,2,3,4,5}&{4,5}
  求并集： {1,2,3,4,5} | {1,2,3}
  定义空的集合 ： set() , 看长度len(set())  ,看类型 type(set())
   