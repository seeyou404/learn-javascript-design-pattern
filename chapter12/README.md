# 第十二章

装饰者模式

在不改变原对象的基础上，通过对其进行封装扩展（添加属性和方法）使原有对象可以满足用户的更复杂的需求。

同样对原有对象进行扩展的还有适配器模式，所不同的是适配器进行扩展很多时候是对对象内部的重组，因此了解其自身结构是必须的。而装饰者对对象的扩展是一种良性扩展，不用了解其具体实现，只是在外部进行了一次封装扩展，这又是对原有功能完整性的一种保护。

* 1.js - 装饰者模式（对原有对象的属性与方法的添加）