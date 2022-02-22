sphinx笔记
=======

1. 用conda install sphinx 安装sphinx，在运行时出现theme error，再conda安装对应主题
2. sphinx-quickstart 创建文档
3. 源目录与构建目录
4. 项目语言：zh_CN （汉语，默认为英语）
5. _build 构建目录（输出文件目录）
6.  forn主题
7.  清空输出文档 make clean
8.  新建的文档要在 toctree下面写 该文档名或文件路径
9.  index.rst 可以申明嵌套
10. “maxdepth”（意为“（目录层级的）最大深度”）就是 “toctree”指令的一个选项。常见问题是 内容的第一行必须缩进到与选项相同的级别 。内容 跟在选项或参数后面，它和选项/参数之间要空一行。
11. 在配置文件中更换**主题**、更换**markdown编译器**、设置文件**后缀名**
12. 默认识别rst后缀，markdown需要加插件，并且修改配置文件。[官网教程](https://www.sphinx-doc.org/zh_CN/master/usage/markdown.html#configuration)
13. 开始尝试在目录中添加文件时，重视显示文件没有写入toctree中，但实际是写了的，尝试把文件名改为英文，尝试改后缀为.rst都无法解决报错问题，最后尝试了重新开始一个sphinx-quickstart后，问题莫名其妙的解决了。
