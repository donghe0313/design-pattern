# 设计模式
# 
创建型模式：
单例模式
简单工厂，工厂方法和抽象工厂模式

行为型模式：
观察者模式

结构型模式：
代理模式
装饰器模式
适配器模式

#### 单例模式中，不加锁的线程安全懒汉：

如图所示：

函数静态局部变量的初始化，在汇编指令上已经自动添加线程互斥指令了

![1](https://github.com/donghe0313/design-pattern/blob/main/1.png)

![2](https://github.com/donghe0313/design-pattern/blob/main/2.png)




