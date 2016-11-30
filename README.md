# PhpDesignPatterns【PHP-23种设计模式】
## 一、 Introduction【介绍】
> 设计模式：提供了一种广泛的可重用的方式来解决我们日常编程中常常遇见的问题。设计模式并不一定就是一个类库或者第三方框架，它们更多的表现为一种思想并且广泛地应用在系统中。它们也表现为一种模式或者模板，可以在多个不同的场景下用于解决问题。设计模式可以用于加速开发，并且将很多大的想法或者设计以一种简单地方式实现。当然，虽然设计模式在开发中很有作用，但是千万要避免在不适当的场景误用它们。

----------

## 二、 Category【分类】
> 根据目的和范围，设计模式可以分为五类。
> 按照目的分为：创建设计模式，结构设计模式，以及行为设计模式。
> 按照范围分为：类的设计模式，以及对象设计模式。

----------

**1. 按照目的分，目前常见的设计模式主要有23种，根据使用目标的不同可以分为以下三大类：**


----------


 - 创建设计模式（Creational Patterns）(5种)：用于创建对象时的设计模式。更具体一点，初始化对象流程的设计模式。当程序日益复杂时，需要更加灵活地创建对象，同时减少创建时的依赖。而创建设计模式就是解决此问题的一类设计模式。
  - 单例模式【Singleton】  
  - 工厂模式【Factory】   
  - 抽象工厂模式【AbstractFactory】  
  - 建造者模式【Builder】   
  - 原型模式【Prototype】
 
 
 - 结构设计模式（Structural Patterns）(7种)：用于继承和接口时的设计模式。结构设计模式用于新类的函数方法设计，减少不必要的类定义，减少代码的冗余。
  - 适配器模式【Adapter】    
  - 桥接模式【Bridge】     
  - 合成模式【Composite】    
  - 装饰器模式【Decorator】   
  - 门面模式【Facade】    
  - 代理模式【Proxy】    
  - 享元模式【Flyweight】  


 - 行为模式（Behavioral Patterns）(11种)：用于方法实现以及对应算法的设计模式，同时也是最复杂的设计模式。行为设计模式不仅仅用于定义类的函数行为，同时也用于不同类之间的协议、通信。
  - 策略模式【Strategy】     
  - 模板方法模式【TemplateMethod】   
  - 观察者模式【Bbserver】    
  - 迭代器模式【Decorator】    
  - 责任链模式【ResponsibilityChain】    
  - 命令模式【Command】   
  - 备忘录模式【Memento】    
  - 状态模式【State】     
  - 访问者模式【Visitor】    
  - 中介者模式【Mediator】   
  - 解释器模式【Interpreter】  

----------

**2.按照范围分为：类的设计模式，以及对象设计模式**

----------


- 类的设计模式(Class patterns)：用于类的具体实现的设计模式。包含了如何设计和定义类，以及父类和子类的设计模式。

- 对象设计模式(Object patterns): 用于对象的设计模式。与类的设计模式不同，对象设计模式主要用于运行期对象的状态改变、动态行为变更等。


----------


## 三、 DesignPatternsPrinciple【设计模式原则】

### 设计模式六大原则 
 
> - 开放封闭原则：一个软件实体如类、模块和函数应该对扩展开放，对修改关闭。  
> - 里氏替换原则：所有引用基类的地方必须能透明地使用其子类的对象.  
> - 依赖倒置原则：高层模块不应该依赖低层模块，二者都应该依赖其抽象；抽象不应该依赖细节；细节应该依赖抽象。  
> - 单一职责原则：不要存在多于一个导致类变更的原因。通俗的说，即一个类只负责一项职责。  
> - 接口隔离原则：客户端不应该依赖它不需要的接口；一个类对另一个类的依赖应该建立在最小的接口上。  
> - 迪米特法则：一个对象应该对其他对象保持最少的了解。