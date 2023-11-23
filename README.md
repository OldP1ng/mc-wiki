# MC-Wiki
一款可以查询mcwiki的Yunzai-bot插件

#### 介绍

一款可以用来查询mcwiki的Yunzai-bot插件，适配Yunzai V3

#### 安装教程

下载此插件，并把它放入./plugins/example目录下

#### 注意事项

mc官方中文wiki迁址后，bilibili镜像wiki关闭，此插件使用的wiki是官方中文wiki，如果你有其他更好的选择，修改代码中
```
let url = `https://zh.minecraft.wiki/w/${encodeQuery}`
```
的
```
https://zh.minecraft.wiki/w/
```
可以更改查询的网站

由于会的还不是很多，所以检查查询的错误结果的方法是检测网页的height值，不改变width的话是可以用的

#### 使用说明

使用命令“#mcwiki”后面跟着想要查询的mc物品即可查询，如果非mc物品或者输入错误会提示查询不到

#### ToDo

增加使用聊天指令切换镜像站的功能，例如"#wiki设置[1-3]"，来切换fandom wiki，中文wiki，官方wiki，以及使用检测网页内的元素，来判断搜索是否有结果
