# SBLang
一个由Python实现的简单编程语言。
## 注释
### 简介
注释只能在新的一行，由#开始。
### 用法
`#<注释内容>`
### 示例
```sblang
#这是一句注释

#这也是一句注释
#对，这还是注释
```
## new
### 简介
新建单个/多个变量。
### 用法
`new <单个变量名或用英文逗号分隔的变量名列表>`
### 示例
以下代码用来创建fo,foo,bar,buf四个变量。
```sblang
new fo
new foo,bar,buf
```
## string
### 简介
将一个字符串赋值到变量。
### 用法
`string <变量名> <字符串>`
### 示例
以下代码用来给a赋值"Hello world",给b赋值"SBLang is awesome".
```sblang
new a,b
string a Hello world
string b SBLang is awesome
```
## addkeep
### 简介
向变量添加保留字符串。  
目前支持的保留字符串有:
 - newline(\n)

### 用法
`addkeep <保留字符串名> <变量名>`
### 示例
以下代码用于给变量a赋值"hello world"并换行。
```sblang
new a
string a Hello world!
addkeep newline a
```
# 持续更新中，此文档可能不会匹配最新版本的SBLang...
