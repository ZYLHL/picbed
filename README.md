# 关于此仓库

> 这是本人的直链调用公开文件的仓库。

## 使用方法

当需要使用repo里的任意一张图的时候，首先在 repo 里能获得每张图对应的URL  
### 方法1 JsDelivr
  
假如要取的这张图名称是zylhl.jpg：
repo里对应的URL是 `https://raw.githubusercontent.com/ZYLHL/picture-src/main/zylhl.jpg`  
然后我们只需要对URL中的一部分进行改动 `https://cdn.jsdelivr.net/gh/ZYLHL/picture-src@main/zylhl.jpg`  
我们便能够通过jsDelivr 覆盖全球的 CDN网络更快的访问到这张图像了。  

具体 URL 格式及释义  
`https://cdn.jsdelivr.net/gh/你的GitHub用户名/你的仓库名@对应分支名/文件相对于分支的相对路径`

### 方法2 ghproxy

假如要取的这张图名称是zylhl.jpg：
repo里对应的URL是 `https://raw.githubusercontent.com/ZYLHL/picture-src/main/zylhl.jpg`  
然后我们只需要在URL前方加入一部分 `https://ghproxy.com/raw.githubusercontent.com/ZYLHL/picture-src/main/zylhl.jpg`  
我们便能够通过ghproxy中转加速的方式更快的访问到这张图像了。  

具体 URL 格式及释义
`https://ghproxy.com/GitHub的原始链接`  

