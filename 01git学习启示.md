##### 问题一：当文件名中含有中文时，使用git status查看的时候显示的是乱码。

​			如：我的文件中含有【01git学习启示.md】文件，使用git status显示如下

![](L:\2021_4_25Git学习\images\问题一.png)

​			解决方法：git config core.quotepath false

