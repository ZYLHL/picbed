# 关于此仓库
[English Ver.](./README_EN.md)

------

> 这是本人的图床，白嫖一时爽，一直白嫖一直爽。

## 使用（白嫖）方法
任意建一个公开的repository，往里面丢图就好了。
在要用任意一张图的时候，首先在仓库里能得到每张图对应的url
以我的这个仓库里的PCL2SETTINGS1.png这张图举例：
GitHub默认是`https://raw.githubusercontent.com/ZYLHL/picture-src/main/PCL2SETTINGS1.png`
这确实已经能直接访问，但是中国大陆（墙的原因）不行，我们需要对url的小部分做一下改动，
上述图像的地址改动之后是`https://cdn.jsdelivr.net/gh/ZYLHL/picture-src@main/PCL2SETTINGS1.png`
没错，白嫖jsDelivr对GitHub静态文件加速的cdn后，现在就可以无障碍的直接访问到每张图像了。
具体格式为：

```
https://cdn.jsdelivr.net/gh/你的GitHub用户名/你的仓库名@对应分支名/文件相对于分支的相对路径
```

