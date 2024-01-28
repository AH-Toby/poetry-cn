 # MANIFEST.in文件

[官网解释](https://docs.python.org/2/distutils/sourcedist.html)

有时候我们想自己打包并发布一个pip包，包内的module和packages自然有setuptools帮助我们去找到并打包到最后的成包里。但是我们可能想打包一些其他的东西，这个时候我们就可以使用MANIFEST.in文件。

一言以蔽之，当运行python setup.py sdist时，会查阅MANIFEST.in文件，并且将里面约定的文件打包到最后的包里。什么要，什么不要，都可以用MANIFEST特定的语法来规范。语法如下：

![img](https://gitee.com/toywang/image-storage/raw/master/image-storage/840bbf6989525d9cbba23136d1433bcb.png)

