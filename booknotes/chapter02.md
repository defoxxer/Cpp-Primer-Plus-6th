# 第二章 开始学习 C++

## 2.1 进入c++

- C++注释以//打头，到行尾结束。

- C++也能够识别C注释，C注释包括在符号/* 和 */之间

- C++用分号隔开每一个执行语句。

- 使用 cin和 cout 进行输入和输出的程序必须包含文件 iostream。

<img width="1045" height="808" alt="图片" src="https://github.com/user-attachments/assets/6abb9acb-1d7a-4003-a94e-3af65e806142" />
<img width="740" height="195" alt="图片" src="https://github.com/user-attachments/assets/e2893b79-99c1-492f-9450-f6daa90700f2" />

```Cpp
#include <iostream>

int main() {
    using namespace std;
    cout << "Hello, World!" << endl;
    return 0;
}
```

> 双引号括起的部分是要打印的信息，为字符串；

> cout的对象属性包括一个插入运算符（<<），它可以将其右侧的信息插入到流中。

> endl是一个特殊的C++符号，表示一个重要的概念：重起一行。在输出流中插入endl将导致屏幕光标移到下一行开头。

> 换行符\n和控制符endl的差别是：endl确保程序继续运行前刷新输出（将其立即显示在屏幕上），而使用“\n”不能提供这样的保证，这意味着在有些系统中，有时可能在您输入信息后才会出现提示。

## 2.3 其他c++语句
与cout一样，cin也是一个智能对象。它可以将通过键盘输入的一系列字符（即输入）转换为接收信息的变量能够接受的形式。

> 输出时，<<运算符将字符串插入到输出流中；输入时，cin使用>>运算符从输入流中抽取字符。
