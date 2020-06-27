# markdown语法的学习

## 标题的使用

# 最大的标题
## 这是h2标题
### 这是h3标题
#### 这是h4标题
##### 这是h5标题

## 斜体和粗体

*斜体随时脉动回来*

### _这是另一种斜体，我就嵌套脉动回来_

**这里可以爆粗是不是**

## 列表的实现

* 无序列表1
* 无语列表2
* 无序列表3
    * 无序列表的嵌套1
    * 无序列表的嵌套2

1. 有序列表
2. 这是有序列表2
3. 有序列表3
    1. 我们来嵌套一下一个有序的列表
    2. 有序列表的嵌套

## 图片的使用
![图片的使用](./陈雪凝.jpg)

注：markdown语法是把文字自动把格式转换为HTML的格式，如果有些样式需要自己来控制的话可以用html和css代码来实现，如下：

 <img src="./陈雪凝.jpg" >

## a标签

[点击进入百度](http://baidu.com)

## 引用

> 毛泽东说过“好好学习，天天向上”

## 内联代码

通过使用 'npm install' 的方式去安装'webpack.json'包

## 代码块
代码块1
```javaScript
var http = requset('http')
var server = http.createServer(function(req, resp){
    resp.writeHead(200,{"content-Type","text/plain;charset=utf-8"})
})
server.listen(3000)
```
代码2
```java
public  static void main(String[] args){
    System.out.println("hello Word")
}

````
## 任务列表

- [x] 睡醒了要刷牙
- [x] 刷了牙要吃饭
- [x] 这是个啥子哟

## 表格
### 韦小宝本月支出

项目   |   金额
-------|--------
按摩    | 200
吃饭   | 900
蹦迪   | 1000