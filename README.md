# web_server
高并发web服务器，使用IO多路复用模型epoll、LT+ET Ractor模式实现，支持HTTP请求，Get请求方式。可承受并发量在9000QPS左右（虚拟机配置8核2G，线程数设置为20的情况下）。

开发环境及工具： Vscode（Windows上的Vscode下载Remote Development插件连接虚拟机），虚拟机（centos7），gcc/g++(版本需支持c11)、gdb（与gcc/g++同版本），浏览器（这里用的是Chrome）、Webbench

[详细流程图] (http://t.csdn.cn/g3pIJ) 
