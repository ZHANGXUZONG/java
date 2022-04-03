# hellow-world

public class HelloWorld {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		System.out.println("Hello world!");
	}

}

首先前面应该要加Package
public作为访问修饰符(access modifier)用于控制其他部分对这段的访问级别
class表明该java程序中所有内容都包含在类中

如果代码输入正确，会得到一个类字节码文件.class
使用 java CLASSNAME 可以运行该文件

运行已编译程序将从指定类中main方法（函数）开始执行
类的源文件必须包含main

package FirstSample;

public class First {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
     System.out.print("We");System.out.println("We will not use 'Hello,World!'");

	}

}

如果需要输出不换行，则可以通过print而不是printkln来实现
