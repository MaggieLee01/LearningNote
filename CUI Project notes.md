* ## VS2017项目
  * ### VS中为 main()函数添加参数(即命令行参数)
在VS中向命令行添加参数，即向main()函数传递参数的方法：
左键单击 调试 → (你的)工程属性 → 配置属性 → 调试 → 命令行参数 
在输入中，如：info.txt ta.txt，使用空格区分每个参数，
现在argc = 3，argv [0] = 工程项目的名称，argv [1] = info.txt，argv [2] = ta.txt，也可以用 "" 表示一个参数，如： "I love you !"是一个参数，使用 "" 可以防止参数本身有空格被误判。
[VS中为 main()函数添加参数(即命令行参数)](https://blog.csdn.net/Alex_mercer_boy/article/details/82050197)里面有图片显示
 *### [VS2017多线程调试](https://www.jianshu.com/p/55f7038ddd62)里面有图片显示
子线程打断点之后可以进行线程的切换
## .bat文件


## C库函数

