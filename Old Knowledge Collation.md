**1、多数程序员都使用以下的代码风格:**

- 每条语句占一行
- 每个函数都有一个开始花括号和一个结束花括号，这两个花括号各占一行
- 函数中的语句都相对花括号进行缩进
- 与函数名称相关的圆括号周围没有空白



2、如果想用两个或更多的单词组成一个名称，通常的做法是用下划线字符将单词分开，如my_onions；或者从第二个单词开始将每个单词的第一个字母大写，如myEyeTooth.(c程序员倾向于按c语言的方式使用下划线)。

3、c++中string类型有专门的成员函数size（），返回string的字符个数

4、string对象不使用空字符来标记字符串末尾

5、 检测到EOF后，cin将两位（eofithe1failbit)都设置为1.可以通过成员函数eof（）来查看eofbit是否背设置；如果检测到EOF，则cin.eof()将返回bool值true，否则是false。同样，如果efobit或failbit背设置为1，则fail（）成员函数返回true。

6、while(!cin.fail())等同于while(cin.get()==false)等同于while(cin)