#### 20180927 第二章，学习环境配置
&emsp;&emsp;既然本书是针对青少年和零基础的朋友来学习Python语言的，那么本书的学习环境使用大家都比较熟悉的Windows操作系统（win7、win8、win10均可）。
#### 一、什么是编程语言
&emsp;&emsp;很多初学者在打算学习编程语言时都会问到这个问题，在浏览器中搜索“编程语言”会出现很多的解释，例如：汇编语言、高级编程语言、解释型语言等等。看到这些专业术语和专有名词大家都会很迷茫，编程语言到底是什么？都能做些什么。其实简单一句话概括：编程语言就是人与计算机沟通的语言。就像中国人会说汉语，德国人会说德语，那么中国人要想跟德国人沟通怎么办呢？就是把汉语翻译成德语，然后让德国人能看懂。编程语言就是程序员或编程爱好者通过人类的想法（不管是汉语、英语、德语）翻译成编程语言让计算机看懂。而Python只是编程语言中的一种。
#### 二、搭建Python语言学习环境
1、安装Python

&emsp;&emsp;安装Python实际上就是安装Python的解释器，也就是说必须要安装了Python的解释器才能使用Python语言编写程序。就像我们必须要安装微信才能通过微信聊天一样。

&emsp;&emsp;在浏览器中输入https://www.python.org/ （或者在搜索引擎中搜索Python，点击有官网标识的网址进入）在Python主页上选择download菜单，然后选择Windows选项进入下载预览页面。

&emsp;&emsp;在下载列表里： Windows x86为32位系统的下载链接； Windows x86-64为64位操作系统下载链接； web-based installer、 executable installer、 embeddable zip file分别表示web最小安装、完整版安装和可嵌入的压缩版安装。我们可以根据自己的操作系统选择64位或者32位的版本下载，如果不清楚自己操作系统是32位还是64位，那就下载X86版本的。我们选择Windows x86 executable installer（X86完整版，适用于Windows32位和64位的操作系统）进行下载。下载完成可以进行安，安装时需要注意将“add Python 3.7 to PATH”这个复选按钮选中，否则输入python命令时会提示早不到。

&emsp;&emsp;安装完成后，win7系统点击开始-运行；win8或win10系统右键点击开始-运行。输入cmd然后回车，进入命令提示符窗口。输入Python，看到图2-1所示画面，说明我们已经在Python交互模式中了。

2、打印“hello world”

&emsp;&emsp;每一门编程语言的入门书籍中，第一个程序大部分都是“hello world”，一来是庆祝我们开始学习一门新的语言；二来是向编程的前辈致敬。
在Python交互模式类似于下面的样式，需要注意的是，Python的交互模式是“>>>”形式，这是Python语言特有的。在交互模式中输入“print "hello world!"。该行命令的意思是打印（print）hello world！；需要注意的是双引号是半角形式，也就是英文的标点符号形式。
```python
print("hello world!")
```
&emsp;&emsp;輸入上面的這段命令后按回车键，如果你看到类似于图2-2的样式，说明你的第一条python语句已经成功运行了。
<center> ![image](2-2)</center>
3、关于打印命令

&emsp;&emsp;图2-2显示的是一条Python的语句，“print”是一个python的命令，翻译过来就是打印，很多人刚开始看到这条命令的时候，会以为是要打印到打印机上（包括刚学编程语言的我），但其实不是的。这条命令是告诉计算机，把print后面的内容输出到屏幕上。print命令的格式是“print”加上一对小括号“（）”然后在括号里面输入要打印出来的内容。print命令常用于调试程序、测试程序输出的内容。

4、打印练习

&emsp;&emsp;学习编程不能光看，动手练习才能学的更扎实。那么下面我们就做更多的打印练习吧。在命令行里输入以下内容，并查看结果,即使不理解为什么会输出这些结果也没关系，我们这些练习的目的是数据编程环境：
```
1、print("I will now count my chickens:")

2、print("我是一名初一的学生，我是男孩子，喜欢编程。")

3、print(5+2*12)

4、print("我的身高是：")

5、print("我的年龄是", 10+3)

6、print( "Roosters", 100 - 25 * 3 % 4)

7、print( 3 + 2 + 1 - 5 + 4 % 2 - 1 / 4 + 6)

8、print("Is it true that 3 + 2 < 5 - 7?")

9、print("What is 3 + 2?", 3 + 2)

10、print("Oh, that's why it's False.")

11、print("Is it greater?", 5 > -2)

12、print("Is it greater or equal?", 5 >= -2)

13、print("Is it less or equal?", 5 <= -2)
```

5、值得注意的地方

&emsp;&emsp;可能你在做以上练习时出现了错误提示，“SyntaxError: invalid character in identifier”，这句话的意思是“语法错误：标识符中的无效字符”，不要紧张，每个程序员都会经历很多的程序错误，即便是有多年编程经验的程序员也会经常出错。仔细核对练习的内容，确保没有缺少引号、括号、逗号等符号并且所有符号都是英文半角的。

&emsp;&emsp;千万不要去拷贝粘贴，那样并不能使你得到充分的练习，只能是白白浪费了学习的时间。

&emsp;&emsp;在练习时，不要把每道练习题前面的序号及顿号输入进去，那样的话会提示错误“SyntaxError: invalid character in identifier”

&emsp;&emsp;每次出现的错误提示不要跳过，用笔记下来并使用翻译软件查看错误语句的含义，这是一个好习惯。因为这些错误在你以后的编程学习中还会遇到。记住错误提示的内容及可能的解决办法会使你在以后编程学习中事半功倍。

6、参考结果

&emsp;&emsp;所有练习的内容输入完成并得到结果后，请查看下面的内容，看看自己是否做的正确。

```
1、I will now count my chickens:

2、我是一名初一的学生，我是男孩子，喜欢编程。

3、29

4、我的身高是：

5、我的年龄是 13

6、Roosters 97

7、6.75

8、Is it true that 3 + 2 < 5 - 7?

9、What is 3 + 2? 5

10、Oh, that's why it's False.

11、Is it greater? True

12、Is it greater or equal? True

13、Is it less or equal? False
```

7、思考练习

&emsp;&emsp;使用print命令输出一首唐诗，格式是这样的：
```
锄禾日当午，
汗滴禾下土，
谁知盘中餐，
粒粒皆辛苦。
```
##### 提示：可以在搜索引擎汇中输入类似于“python print 换行”这样的字样来查找怎样让唐诗每一句占一行。