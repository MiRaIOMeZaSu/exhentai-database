# exhentai-database
The full ExHentai Database

Status: Uploaded

# 中文介绍

众所周知，e站备份最大的难点就是元数据的备份。现在各位可能已经通过各种渠道获取到了图片资源的备份，但是元数据（tags, artists)还没有人释放出可用的资源。

然而元数据在E站也是至关重要的。e站的一大特点就是你可以通过tags 搜索你需要的资源。比如
- 通过artists tag来搜索一位画师的所有资源
- 通过character tag来搜索某一动漫人物的所有资源
- 通过female/male tag 来搜索[数据删除]的所有资源
- 等等……

所以我在听说ex站要关闭时，及时用爬虫备份了所有元数据（html 格式）。经过一个晚上的整理，现在以数据库（sqlite）的形式发布，请各位随意取用。

此数据库包含以下信息：

- 资源名
- 类别
- 上传时间
- 上传人
- 页数
- 语言
- parody
- character
- female
- male
- group
- artist
- misc

总条目数：650825

（目前一对多的tag还是以；分割的字符串，这几天有时间把它改成单独的表）

我计划过几天做个简单的搜索引擎并开放API供后续开发使用。

有了元数据之后，再整合图片资源，ex站复活指日可待啊（flag


# English

This is the full backup of the exhentai metadata. The backup finished a few hours before the website was down. 

It is a SQLite database with the following information:

- Name (title) of the work
- Category (Image Set/Non-h/Manga...)
- Upload Time
- Uploader
- Number of Pages

And tags including:

- Language
- Parody
- Character
- Female
- Male
- Group
- Artist
- Misc

You may use the database however you want (as long as it’s legal). 

# Contributions

All Contributions are welcome. I’m currently setting up an API server using this data, so if you have any suggestions, feel free to open an issue.

如果有任何建议，欢迎联系我。
