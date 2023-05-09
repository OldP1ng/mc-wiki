# MC-Wiki
一款可以查询mcwiki的Yunzai-bot插件

#### 介绍

一款可以用来查询mcwiki的Yunzai-bot插件，适配Yunzai V3

#### 安装教程

下载此插件，并把它放入./plugins/example目录下

#### 注意事项

本插件使用的wiki是bilibili的镜像站，是为了保证国内的访问速度，如果你有其他更好的选择，修改代码中
```
let url = `https://wiki.biligame.com/mc/${encodeQuery}`
```
的
```
https://wiki.biligame.com/mc/
```
可以更改查询的网站

由于会的还不是很多，所以检查查询的错误结果的方法是检测网页的height值，不改变width的话是可以用的
其他网站我没有试过能不能不更改直接使用

#### 使用说明

使用命令“#wiki”后面跟着想要查询的mc物品即可查询，如果非mc物品或者输入错误会提示查询不到

#### 参与贡献

圈圈

（初学者写的第一个插件，还有很多不足的地方，在多多学习中）
