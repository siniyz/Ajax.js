# Ajax.js
封装了Ajax操作的简易工具

这里采用单例模式封装成一个对象，即只有一个全局的变量将其赋值给Ajax，该对象有一个request方法。request有两个参数，第一个为请求的url(必要的)，字符串类型，第二个opt为配置参数(可选的)，对象类型。
