

进入 /etc/yum.repos.d/ 下新建nginx.repo
================================================
vim /etc/yum.repos.d/nginx.repo

================================

[nginx]
name=nginx repo
baseurl=http://nginx.org/packages/OS/OSRELEASE/$basearch/
gpgcheck=0
enabled=1

===================================

sudo yum install nginx

