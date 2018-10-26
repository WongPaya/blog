---
title: markdown 语法
date: 2018-10-25 09:46:20
tags:
---
# 标题
# 一级标题
## 二级标题
...
###### 六级标题

# 超链接 
[点我](http://www.baidu.com)跳转到百度

[链接名字](链接地址)

#图片
![http://www.baidu.com](https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1540443015737&di=857e33edb8797ac6e192365acc4136a4&imgtype=0&src=http%3A%2F%2Fimgsrc.baidu.com%2Fforum%2Fw%3D580%2Fsign%3D613d9c904136acaf59e096f44cd88d03%2F187ffd1b9d16fdfa05831947be8f8c5495ee7b39.jpg)

![图片名字](图片链接)

#图片链接
[![今天长这样](https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1540443015737&di=857e33edb8797ac6e192365acc4136a4&imgtype=0&src=http%3A%2F%2Fimgsrc.baidu.com%2Fforum%2Fw%3D580%2Fsign%3D613d9c904136acaf59e096f44cd88d03%2F187ffd1b9d16fdfa05831947be8f8c5495ee7b39.jpg)](http://www.baidu.com)

#文本修饰
*文本倾斜*

**加粗效果**
***文本加粗倾斜***
~~删除线~~

#分割线

三个或者三个以上的-或者*
---

#列表

#有序列表
1.张三
2.牛儿
3.王宝强

#无序列表
以一个 - + *开头的
- 列表一
- 列表二
- 列表三

# 表格

姓名|排行|特长
-|-|-
刘备|大哥|哭
关羽|二哥|打
张飞|三哥|骂

# 代码块
```javascript
while (alive){
    code()
    eat()
    sleep()
}
```

```css
body {
     color:yellow;
     font-size:15px;
}  
```
## 三、初始化一个博客项目
```bash
# 初始化博客项目
hexo init blog
# 切换到博客路径
cd blog
# 安装依赖包
npm install
#启动hexo服务
hexo s
```
## 四、linux常用命令
1.路径切换