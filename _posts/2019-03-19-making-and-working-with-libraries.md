# making and working with libraries in c++

链接库让我们开发变得模块化，变得有层次化，学会在 VS 2017 下建立静态库，有助于合作开发项目。

大学学计算机，很多课程开发的时候需要几个同学进行合作，那么对项目的分工就比较重要，利用静态库的思想和 `github`  提供的仓库，可以完美分配任务。

1. 建立项目

   在常规属性那里配置为静态链接库。

2. 完善库

   也就是编程，头文件写声明， `cpp` 文件写实现。

3. 调用

   在另一个项目中，配置 `include` 路径，然后添加引入静态库，完成。