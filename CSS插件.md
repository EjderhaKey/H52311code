stylus插件使用
    npm i stylus -g
    在stly文件中 stylus -w -m stly文件位置
    (stylus -w -m ./css/a.styl)






less插件使用
方式一：需要引入地址 很慢 不推荐
    引入CSSlink
    <link rel="stylesheet/less" href="LECSS目标地址">
    引入script
    <script src="https://cdn.jsdelivr.net/npm/less" ></script>

方式二：
    全局下载less
    npm i less -g
    lessc 当前less文件 需要转换后的文件
    (lessc a.less a.css)



sass插件使用
vscode中插件  Live Sass Compiler
在scss中 使用Live Sass Compiler (右下角点击快捷插件)


