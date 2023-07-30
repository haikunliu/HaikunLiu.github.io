---
permalink: /
title: "Haikun Liu (刘海坤)"
excerpt: "Haikun Liu (刘海坤)"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
**Ph.D, Professor**

**国家“万人计划”青年拔尖人才入选者**

**湖北省杰出青年基金获得者**

[School of Computer Science and Technology](http://cs.hust.edu.cn/).

[Huazhong University of Science and Technology](https://www.hust.edu.cn/).


Brief Biography
======
I am a Professor at Huazhong University of Science and Technology (HUST), China. I obtained my Ph.D. in Huazhong University of Science and Technology in 2014, under [Dr.Hai Jin](https://scholar.google.com/citations?user=o02W0aEAAAAJ&hl=en&oi=ao). From January 2013 to January 2015, I was a Research Fellow at Nanyang Technological University (NTU), working with [Dr.Bingsheng He](https://www.comp.nus.edu.sg/~hebs/)
刘海坤，博士，华中科技大学教授，博士生导师，国家“万人计划”青年拔尖人才入选者，湖北省杰出青年基金获得者。2012年于华中科技大学计算机系统结构专业博士毕业，2013.1-2015.1在新加坡南洋理工大学任研究员。目前主要从事内存计算、虚拟化/云计算等方向的研究。近年来主持国家重点研发计划课题2项、国家自然科学基金项目3项，以及上千万的华为横向技术合作项目。在ASPLOS/ISCA/HPCA/DAC/ICS/SC/HPDC等计算机顶级国际会议以及包括IEEE TC/TCAD/TPDS、ACM TACO/ToS、《中国科学》等CCF A/B类重要国际期刊上发表论文80多篇，论文累加被谷歌学术搜索引用2300多次，单篇最高600多次。获得专利授权18项，其中美国专利4项。博士论文被评为2012年度湖北省优秀博士论文，2016年获得ACM-Wuhan新星奖，2018年获教育部高等学校科学研究优秀成果奖自然科学一等奖，2020年获国家自然科学二等奖，上海市技术发明一等奖，2022年获得华为奥林帕斯先锋奖。多次担任知名国际会议如IEEE Big Data Congress、ICA3PP、ICPADS的程序委员会领域主席，以及国际顶级会议如SC/ICDCS/Cluster/CCGrid/ISMM等著名国际会议的PC 20多次。ACM/IEEE会员，CCF高级会员、CCF高性能计算专委会委员，CCF体系结构专委会委员。

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
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
