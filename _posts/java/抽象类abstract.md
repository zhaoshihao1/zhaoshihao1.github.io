#抽象类
##特点：
1. 抽象类和抽象方法必须用abstract关键字修饰  
2. 抽象类不一定有抽象方法，有抽象方法的类一定是抽象类  
3. 抽象类不能实例化，只能参照多态的方式通过子类对象实例化，这叫抽象多态  
4. 抽象的子类  要么重写抽象类中的所有抽象方法要么也是抽象类

##成员特点
可以是变量也可以是常量  
有构造方法，但不能实例化，作用是用于子类访问父类数据的初始化

###例子
动物是一个抽象的名词，应该是抽象的类，里面的方法也应该是抽象的