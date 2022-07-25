# 关于此仓库

> 这是本人的图床，白嫖一时爽，一直白嫖一直爽。

## 使用（白嫖）方法
任意建一个公开的repository，往里面丢图就行了。
当需要使用repo里的任意一张图的时候，首先在repo里能获得每张图对应的URL
假如要取的这张图名称是zylhl.jpg：
repo里对应的URL是 `https://raw.githubusercontent.com/ZYLHL/picture-src/main/zylhl.jpg`
然后我们只需要对URL中的一部分进行改动 `https://cdn.jsdelivr.net/gh/ZYLHL/picture-src@main/zylhl.jpg`
我们便能够通过jsDelivr cdn更快访问到这张图像了。
具体URL格式释义：`https://cdn.jsdelivr.net/gh/你的GitHub用户名/你的仓库名@对应分支名/文件相对于分支的相对路径`

