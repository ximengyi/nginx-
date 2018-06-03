1.安装epel-release



rpm -ivh http://dl.fedoraproject.org/pub/epel/7/x86_64/e/epel-release-7-5.noarch.rpm
=============================================================
2.安装PHP7的rpm源


rpm -Uvh https://mirror.webtatic.com/yum/el7/webtatic-release.rpm
===============================================================
3.安装PHP7


yum install php71w
===============================================================
4 安装 cli  否则  php -v 无提示

sudo yum install php71w-cli