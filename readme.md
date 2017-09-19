## Chrome Bookmarks

继承自 https://github.com/blainesch/alfred-chrome-bookmarks, 在原版上做少量改造，更适合自己

1. 增加一个配置变量BLACKS, 它代表搜索书签时跳过的目录名，以逗号分割。比如我的chrome 书签有 news, work, game 三个书签目录， 当我设置BLACKS="news,work"，这时遍历标签时只会搜索ganme目录了

2. 修改默认的匹配方式，改为精确匹配
