jdtools(jar or dex tools)
=======

Toolkit for confuse the .class or .dex files, making it difficult to read for cracker, and so on...

jdtools contains some compment

- [merger](https://github.com/noverguo/jdtools/tree/master/merger) is a tools to combine multiple methods into one, so that to ease restrictions android 65k method of quantity, and increasing the difficulty of analysis.    

Other project will be added in subsequent.


this tools has used some lib:
  - [asm](http://asm.ow2.org/) lib to edit the bytecode. 
  - [gson](http://code.google.com/p/google-gson/) lib to operate json.
  - [dex2jar](http://code.google.com/p/dex2jar/) tools to assembly jar to dex or disassembling dex to jar.


=======
一个用于操作.class或.dex文件的工具集，让破解的人更加难以阅读等等，请留意后续更新。

jdtools包含了多个组件

- [merger](https://github.com/noverguo/jdtools/tree/master/merger) 是一个把多个方法合并成一个的工具，因而可以用来突破adnroid dex方法数量的65K(65536)的限制，同时也加大了分析的难度。

其它组件会后续不断地更新。

这个工具用了一些库：
  - [asm](http://asm.ow2.org/) 一个操作bytecode的库
  - [gson](http://code.google.com/p/google-gson/) 一个操作json的库
  - [dex2jar](http://code.google.com/p/dex2jar/) 一个用于jar和dex之前相互转换的工具


