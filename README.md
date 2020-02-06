
![](./images/logo.png)

## 一. iOS基础类面试题

### 1.1 内存管理相关

****内存管理****

* [iOS 内存分布是怎样的？有哪些区域，每个区域的作用](https://github.com/tbfungeek/iOS-Daily-Interview/issues/1)
* [谈谈iOS的内存管理方式的理解](https://github.com/tbfungeek/iOS-Daily-Interview/issues/2)
* [MRC、ARC和 Autorelease的区别](https://github.com/tbfungeek/iOS-Daily-Interview/issues/3)
* [ARC在编译时和运行时都做了哪些工作](https://github.com/tbfungeek/iOS-Daily-Interview/issues/7)
* [ARC 使用的过程中需要注意点以及遵循的原则](https://github.com/tbfungeek/iOS-Daily-Interview/issues/4)
* [ARC情况下有哪些限制](https://github.com/tbfungeek/iOS-Daily-Interview/issues/8)
* [介绍下NSZone](https://github.com/tbfungeek/iOS-Daily-Interview/issues/5)
* [说说你对assign，strong，weak，unsafe_unretained，copy的理解](https://github.com/tbfungeek/iOS-Daily-Interview/issues/6)
* [__weak 修饰的变量，是否已经被注册在了 @autoreleasePool 中？为什么？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/9)
* [ARC 的 retainCount 怎么存储的？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/10)
* [__weak 属性修饰的变量，如何实现在变量没有强引用后自动置为 nil？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/11)
* [说一下什么是 悬垂指针？什么是 野指针?](https://github.com/tbfungeek/iOS-Daily-Interview/issues/12)
* [BAD_ACCESS 在什么情况下出现?](https://github.com/tbfungeek/iOS-Daily-Interview/issues/13)
* [retain、release 的实现机制是怎样的？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/14)
* [能不能简述一下 dealloc 的实现机制？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/15)
* [在 MRC 下如何重写属性的 Setter 和 Getter?](https://github.com/tbfungeek/iOS-Daily-Interview/issues/16)
* [介绍下@property、@synthesize和@dynamic的作用](https://github.com/tbfungeek/iOS-Daily-Interview/issues/17)

****AutoReleasePool相关****

* [什么是AutoReleasePool，它都有哪几种类型](https://github.com/tbfungeek/iOS-Daily-Interview/issues/18)
* [RunLoop AutoReleasePool的创建及释放时机是怎样的](https://github.com/tbfungeek/iOS-Daily-Interview/issues/19)
* [简要介绍下 @autoreleasePool 的数据结构？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/20)
* [函数返回一个对象时，会对对象 autorelease 么？为什么？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/21)
* [自动释放池的作用是什么](https://github.com/tbfungeek/iOS-Daily-Interview/issues/22)
* [AutoreleasePool drain 和 release区别](https://github.com/tbfungeek/iOS-Daily-Interview/issues/23)

****循环引用，内存泄漏相关****

* [日常开发中有哪些可能会出现的循环引用？又该怎样解决这些问题](https://github.com/tbfungeek/iOS-Daily-Interview/issues/24)
* [内存泄漏有几种类型？有哪些排查方式](https://github.com/tbfungeek/iOS-Daily-Interview/issues/25)

### 1.2 分类扩展与协议相关

* [分类的作用有哪些?](https://github.com/tbfungeek/iOS-Daily-Interview/issues/26)
* [分类与扩展的区别?](https://github.com/tbfungeek/iOS-Daily-Interview/issues/27)
* [通过分类可以为某个类添加哪些东西?](https://github.com/tbfungeek/iOS-Daily-Interview/issues/28)
* [分类的实现原理？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/29)
* [如何给分类添加属性？关联对象以什么形式进行存储？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/30)
* [分类可不可以添加实例对象？为什么？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/31)
* [分类在编译过后，是在什么时机与原有的类合并到一起的?](https://github.com/tbfungeek/iOS-Daily-Interview/issues/32)
* [分类与宿主类有同名方法会有什么结果?](https://github.com/tbfungeek/iOS-Daily-Interview/issues/33)
* [分类与其他分类有同名方法会有什么结果?](https://github.com/tbfungeek/iOS-Daily-Interview/issues/34)
* [协议可以添加属性吗？如果可以怎么添加。](https://github.com/tbfungeek/iOS-Daily-Interview/issues/35)

### 1.3 Block 相关

* [说一下什么是Block?](https://github.com/tbfungeek/iOS-Daily-Interview/issues/36)
* [Block 和 函数指针 的区别? ](https://github.com/tbfungeek/iOS-Daily-Interview/issues/37)
* [说下Block的对不同类型变量的捕获情况 ](https://github.com/tbfungeek/iOS-Daily-Interview/issues/38)
* [Block 有几种类型？分别是什么？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/39)
* [说说你对__block的理解，以及forwarding的作用](https://github.com/tbfungeek/iOS-Daily-Interview/issues/40)
* [对不同类型的block进行copy操作结果分别是怎样的？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/41)
* [哪些情况下block会被copy到堆上？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/42)
* [__block 的解释以及在 ARC 和 MRC 下有什么不同？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/43)
* [dispatch_block_t这个有没有用过？解释一下？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/44)

### 1.4 Runtime相关

* [实例对象的数据结构？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/45)
* [类对象及元类对象的数据结构?](https://github.com/tbfungeek/iOS-Daily-Interview/issues/46)
* [Obj-C 对象、类的本质是通过什么数据结构实现的？ ](https://github.com/tbfungeek/iOS-Daily-Interview/issues/47)
* [Obj-C 中的类信息存放在哪里？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/48)
* [一个 NSObject 对象占用多少内存空间？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/49)
* [说一下对 class_rw_t 结构体的理解？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/50)
* [说一下对 class_ro_t 的理解？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/51)
* [说一下对 isa 指针的理解，对象的 isa 指针指向哪里？ isa 指针有哪两种类型？（注意区分不同对象）](https://github.com/tbfungeek/iOS-Daily-Interview/issues/52)
* [说一下 Runtime 消息解析。](https://github.com/tbfungeek/iOS-Daily-Interview/issues/53)
* [说一下 Runtime 消息转发。](https://github.com/tbfungeek/iOS-Daily-Interview/issues/54)
* [Runtime 如何实现动态添加方法和属性？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/55)
* [说一下 Method Swizzling? 说一下在实际开发中你在什么场景下使用过? ](https://github.com/tbfungeek/iOS-Daily-Interview/issues/56)
* [如何运用 Runtime 字典转模型？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/57)
* [如何运用 Runtime 进行模型的归解档？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/58)
* [在 Obj-C 中为什么叫发消息而不叫函数调用？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/59)
* [说一下 Runtime 的方法缓存？存储的形式、数据结构以及查找的过程？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/60)
* [是否了解 Type Encoding? ](https://github.com/tbfungeek/iOS-Daily-Interview/issues/61)
* [Objective-C 如何实现多重继承？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/62)
* [说说+load +initializer区别](https://github.com/tbfungeek/iOS-Daily-Interview/issues/63)
* [说说Mach O的组成结构以及每个部分的作用](https://github.com/tbfungeek/iOS-Daily-Interview/issues/64)
* [说说点击App后到main方法经过的步骤](https://github.com/tbfungeek/iOS-Daily-Interview/issues/65)
* [说说点击App后到main方法经过的步骤](https://github.com/tbfungeek/iOS-Daily-Interview/issues/65)

### 1.5 KVC KVO 相关

### 1.6 UI 相关

#### 1.6.1 生命周期相关

#### 1.6.2 渲染相关

#### 1.6.3 布局相关

#### 1.6.4 动画相关

#### 1.6.5 事件相关

### 1.7 多线程相关

### 1.8 RunLoop相关

### 1.9 其他

## 二. iOS高级面试题

### 2.1 性能优化相关

### 2.2 动态化相关

### 2.3 组件化相关

### 2.4 热修复相关


## 三. iOS三方开源库相关面试题


## 四. 通用技术相关

### 4.1 网络相关

### 4.2 设计模式相关

### 4.3 架构相关

### 4.4 数据结构/算法相关


## 五. 面试前必读材料

### 4.1 源码类

### 4.2 博客类

### 4.3 开源库

### 4.4 书籍
