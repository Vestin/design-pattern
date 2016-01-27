# design-pattern

##设计原则
* 封装变化。
* 针对接口编程，而不是针对实现编程。
* 多用组合，少用继承。
* 为交互对象之间的松耦合设计而努力。
* 开放-关闭原则（对扩展开放，对修改关闭）。
* 依赖倒置原则（要依赖抽象，不要依赖具体类）。
  指导方针，帮助避免违反依赖倒置原则：
  - 变量不可以持有具体类的引用。
  - 不要让类派生自具体类。
  - 不要覆盖基类中已实现的方法。
* 最少知识原则（Least Knowledge,只和朋友交谈)。
  就任何对象而言，在该对象的方法内，我们只应该调用属于以下范围的方法：
  - 该对象本身
  - 被当作方法的参数而传递进来的对象
  - 此方法所创建或实例化的任何对象
  - 对象的任何组件
* Hollywood principle："Don't call me; I'll call you."
  - [read more](http://www.tuicool.com/articles/2ma2aa)
* 单一职责原则（Single responsibility principle）（一个类应该只有一个引起变化的原因）

//TODO
Some pattern goes here