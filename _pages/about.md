---
permalink: /
title: "个人简历 / Individual Resume"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

李懿真(2000.01)，于2018-2022年就读于吉林大学仪器科学级电气工程学院测控技术与仪器专业，获得工学学位和院级优秀毕业生称号。

目前于天津大学医学工程与转化医学研究院攻读硕士，导师为[许敏鹏教授](https://mctu.tju.edu.cn/info/1193/3489.htm)，我的研究方向主要包括基于深度学习的脑机接口模式识别、微弱时域特征脑电信号的数据增强、基于Unity的脑控游戏系统。

🎖 已获部分奖项 / Selected Awards
======
1. 2022.06  吉林大学一等奖学金、校优秀学生称号、道德风尚奖(2021-2022)
2. 2022.04  “吉林大学优秀共青团员”荣誉称号(2021-2022)
3. 2022.04  吉林大学仪器科学级电气工程学院立创杯EDA设计竞赛一等奖
4. 2021.12  吉林大学二等奖学金、学术科技奖(2020-2021)
5. 2021.12  吉林大学十佳班级集体荣誉
6. 2021.06  吉林大学“品味 心晴”微电影大赛优秀奖
7. 2021.05  “吉林大学优秀共青团员”荣誉称号(2020-2021)
8. 2021.05  吉林大学仪器科学级电气工程学院立创杯EDA设计竞赛二等奖、院级电子设计竞赛一等奖
9. 2021.04  吉林大学“挑战杯”大学生课外学术作品竞赛二等奖
10. 2021.01  吉林大学二等奖学金(2018-2019)
11. 2020.12  吉林省大学生电子设计竞赛“金花杯”三等奖
12. 2020.04  吉林大学一等奖学金、校优秀学生称号(2018-2019)
13. 2019.10  第十一届吉林省大学生数学竞赛一等奖
14. 2019.10  吉林大学大学生科技协会“优秀部员”称号
15. 2019.09  赴台湾逢甲大学暑期交流，获结业证书
16. 2019.04  “吉林大学优秀共青团员”荣誉称号(2018-2019)
17. 2019.03  吉林大学仪器科学级电气工程学院寒假社会实践一等奖


A data-driven personal website
======
Like many other Jekyll-based GitHub Pages templates, Academic Pages makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over -- just be sure to save the markdown files! Finally, you can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
