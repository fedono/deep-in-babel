# Babel

1. babel 是如何使用的，使用的场景有哪些
   - 日常使用 babel 都是用在转换 es6 语法到 es5 的语法
   - 可以使用 babel 来转换成 ast 来解析 
   - babel 有哪些常用的库，都是用来干什么的
        - 比如 @babel/core 生成source map 和 AST
        - @babel/parser 生成 AST
        - @babel/code-frame 用于指定传入的代码的错误的行数，这个库可真是牛逼  
        - 比如 @babel/preset 用来磨平ES6的差异
        - 工具类的 @babel/parser | @babel/runtime
2. babel 的配置选项
4. 如何来编写一个 babel 的插件