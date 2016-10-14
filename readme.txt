
forked from donnie4w/dom4g

golang 的xml处理库
dom4g提供xml简便的操作方法，如节点 增加，删除，查询，属性增加，修改，删除，查询等功能

基于以上基本功能，还新增了如下功能：
1、处理带有注释的xml内容，当前不将注释内容输出到dom结构中。
2、处理 带有自定义namespace的xml 命名空间
3、处理 CharData的起始元素处理。如web.xml 中的xml header处理
4、修改 path查找时出现的bug
5、处理 带有自定义namespace的xml 元素处理
6、输出时，换行符的添加
