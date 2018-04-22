user  nginx     服务使用的用户
worker_processes  工作进程数(与系统的核心数一致)
error_log         nginx的错误日志
pid                 nginx服务启动时候的pid
===============================================
events  worker_connections 每个进程最大连接数（nginx的每个worker的最大连接数一般调节到一万左右会满足大部分企业需求）

use      工作进程数(内核模型)
==============================
systemctl restart nginx.service    重启nginx服务
========================================================
service start nginx 启动nginx
=====================================

centos7 下yum 安装的nginx可使用以下命令
===================================
启动nginx服务

systemctl start nginx.service　
设置开机自启动

systemctl enable nginx.service
停止开机自启动


systemctl disable nginx.service
查看服务当前状态


systemctl status nginx.service
重新启动服务

systemctl restart nginx.service　

查看所有已启动的服务
systemctl list-units --type=service
