# Introduction

[原文：Mac Gitbook 安装使用](https://blog.csdn.net/wxb880114/article/details/82078837)
环境安装
node 安装

brew install node
gitbook 安装

brew install  gitbook
Calibre 安装

https://calibre-ebook.com/download_osx

ln -s /Applications/calibre.app/Contents/MacOS/ebook-convert /usr/local/bin
 

waterwdeMacBook-Pro:myBook waterw$ gitbook pdf
info: 7 plugins are installed 
info: 6 explicitly listed 
info: loading plugin "highlight"... OK 
info: loading plugin "search"... OK 
info: loading plugin "lunr"... OK 
info: loading plugin "sharing"... OK 
info: loading plugin "fontsettings"... OK 
info: loading plugin "theme-default"... OK 
info: found 16 pages 
info: found 4 asset files 
 
InstallRequiredError: "ebook-convert" is not installed.
Install it from Calibre: https://calibre-ebook.com
Gitbook使用
Gitbook初始化
gitbook init


目录大纲编写
格式说明

[章节名称](层级目录1/层级目录2/层级目录3/...)

tips: 目录要完整

# Summary
 
* [Introduction](README.md)
* [摘要](摘要/readme.md)
* [Abstract](Abstract/readme.md)
* 第一章 绪论
    * [1.1 课题研究的目的和意义](第一章 绪论/1.1 课题研究的目的和意义/readme.md)
    * [1.2 课题的国内外研究现状](第一章 绪论/1.2 课题的国内外研究现状/readme.md)
    * [1.3 可行性分析](第一章 绪论/1.3 可行性分析/readme.md)
    * [1.4 论文拟采用的技术路线](第一章 绪论/1.4 论文拟采用的技术路线/readme.md)
    * [1.5 论文拟采用的技术路线](第一章 绪论/1.5 论文拟采用的技术路线/readme.md)
        * [1.5.1 工作安排](第一章 绪论/1.5 论文拟采用的技术路线/1.5.1 工作安排/readme.md)
        * [1.5.2 预期成果](第一章 绪论/1.5 论文拟采用的技术路线/1.5.2 预期成果/readme.md)
* 第二章 XXX理论
    * [2.1 XXX](第二章 XXX理论/2.1 XXX/readme.md)
    * [2.2 XXX](第二章 XXX理论/2.2 XXX/readme.md)
    * [2.3 XXX](第二章 XXX理论/2.3 XXX/readme.md)
    * [2.5 XXX](第一章 绪论/2.5 XXX/readme.md)
        * [2.5.1 XXX](第二章 XXX理论/2.5 XXX/2.5.1 XXX/readme.md)
        * [2.5.2 XXX](第二章 XXX理论/2.5 XXX/2.5.2 XXX/readme.md)
 
执行 gitbook init



文件目录结构



本地发布

gitbook serve




导出其他格式
gitbook pdf



 
gitbook epub
 

MarkDown 编辑器

sublimetext2 下载安装

上传github
  568  git init
  569  ls
  570  git remote add origin https://github.com/watemei/bookFirst.git
  571  git add
  572  git add .
  573  ls
  574  git status
  575  ls
  576  git commit -m "add bookFirst tp github"
  577  git push -u origin master
 
