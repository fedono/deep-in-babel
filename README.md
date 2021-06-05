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
   - babel 集成的package 
        - @babel/cli 直接使用命令行来转换文件，从 es6 转换到 es5
        - @babel/polyfill 
        - @babel/plugin-transform-runtime  这个一般是用来干嘛的，好像是线上直接转换的，一般在线上 sandbox 这种会用到，如一些 jsbin 这种平台，引入 transform-runtime 来达到现在转换 es6/jsx 这种代码的
        - @babel/register 在应用的入口引入，将当前应用的 ES6 转换到 es5
        - @babel/standalone 在 html 文件中直接引入，会自动转换代码
2. babel 的配置选项
4. 如何来编写一个 babel 的插件

