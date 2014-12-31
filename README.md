lfsbook
=======

####说明
折腾lfs+git+latex手册

####条件 
安装tex(文章里面会提到)
mactex:https://tug.org/mactex/
最小化安装https://tug.org/mactex/morepackages.html
安装两个包：

+ basic tex 是tex的各种命令行工具

+ Additions tex图形化工具 包括tex的包管理器 一个tex编辑器等等

依赖包：（Additions 下载完毕后 使用tex live utility 软件下载）

tex路径bug
解决texstdio mac下xeletex的bug
ln -s /usr/local/bin/xdvipdfmx /usr/texbin/xdvipdfmx 

####编译方法：
bash make_mac.sh

