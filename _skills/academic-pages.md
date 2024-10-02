---
title: "个人学术网站制作教程"
collection: skills
type: "skills"
permalink: /skills/academic-pages
date: 2024-10-01
location: "China"
---

======

# 1、修改academicpages
**1.1、各文件夹说明**： <br>
<img src='/images/blogs/skills/academicpages/各文件夹说明1.png' width="500"> <br>
<img src='/images/blogs/skills/academicpages/各文件夹说明2.png' width="500"> <br>
**1.2、简介设置**： <br>
<br> &emsp; （1）点击文件夹_pages中的about.md <br>
<img src='/images/blogs/skills/academicpages/设置about.md.png' width="500"> <br>
<br> &emsp; （2）填写个人简介 <br>
<img src='/images/blogs/skills/academicpages/个人简介.png' width="500"> <br>
<br> &emsp; （3）下面加======代表加粗，且可以添加各种各样的符号 <br>
<img src='/images/blogs/skills/academicpages/加粗.png' width="500"> <br>
**1.3、设置个人网页配置**： <br>
<br> &emsp; （1）打开_config.yml <br>
<img src='/images/blogs/skills/academicpages/打开config.png' width="500"> <br>
<br> &emsp; （2）配置左侧个人信息 <br>
<img src='/images/blogs/skills/academicpages/配置个人信息.png' width="500"> <br>
注意，如果出现上传图片无法显示的问题，可能有以下原因： <br>
1、图片无法使用，这种情况多出现于直接从网上下载的图片，如果想用的话建议截图然后保存（当然有的网图是可以的）； <br>
2、图片格式不对，可以尝试jpg、png格式，网上有的人说使用jpg格式的图片不行，但是我这里可以。 <br>
<br> &emsp; （3）编辑publication <br>
在_config.yml中： <br>
<img src='/images/blogs/skills/academicpages/配置publication.png' width="500"> <br>
publication中不同的出版物，像这个就是这样的。
<img src='/images/blogs/skills/academicpages/publication结果.png' width="500"> <br>
<br> &emsp; （4）编辑导航栏——collections <br>
找到_config.yml中的collections，复制其他的导航栏，然后改一下名字： <br>
<img src='/images/blogs/skills/academicpages/编辑导航栏collections.png' width="500"> <br>
<br> &emsp; （5）编辑导航栏——defaults <br>
找到\_config.yml中的defaults：
<img src='/images/blogs/skills/academicpages/编辑导航栏defaults.png' width="500"> <br>
复制其他的代码，然后重命名： <br>
<img src='/images/blogs/skills/academicpages/编辑导航栏defaults例子.png' width="500"> <br>
<br> &emsp; （6）编辑导航栏，使其出现 <br>
找到\_data目录，打开navigation.yml
<img src='/images/blogs/skills/academicpages/编辑navigation.png' width="500"> <br>
复制并添加导航栏： <br>
<img src='/images/blogs/skills/academicpages/复制并添加导航栏.png' width="500"> <br>
<br> &emsp; （7）新导航栏的命名 <br>
新建一个文件夹，最好是与其他的相同，如_talks、\_teaching：<br>
<img src='/images/blogs/skills/academicpages/新导航栏命名1.png' width="500"> <br>
在_pages文件夹下创建一个html或者md，如comic.html <br>
<img src='/images/blogs/skills/academicpages/新导航栏命名2.png' width="500"> <br>
comic.html的内容如下，其中的内容表示的是代码会从comic文件夹下寻找文件，然后公布： <br>
<img src='/images/blogs/skills/academicpages/新导航栏命名3.png' width="500"> <br>
公布编辑的comic，在naigation.yml中添加相应代码： <br>
<img src='/images/blogs/skills/academicpages/新导航栏命名4.png' width="500"> <br>
编辑发布内容：<br>
<img src='/images/blogs/skills/academicpages/新导航栏命名5.png' width="500"> <br>
编辑blog的设置，内容正常输入就行：<br>
<img src='/images/blogs/skills/academicpages/新导航栏命名6.png' width="500"> <br>
发布后内容如下：<br>
<img src='/images/blogs/skills/academicpages/新导航栏命名7.png' width="500"> <br>
