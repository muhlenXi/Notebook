#### 7、说说你对 @class 、#include、#import 的理解？

`@class 类名` 向前声明某个类，有以下作用：

* 告诉编译器有一个叫 `类名` 的类。
* 可以减少类的使用者所引入的头文件的数量。
* 可以解决两个类互相引用的问题。

*--- Effective Objective-C 2.0 Second*