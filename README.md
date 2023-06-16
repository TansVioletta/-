# Weather-management-center-system——天气数据管理中心系统 
##
## idc文件目录下包含了三个文件夹，分别为：c、ini和sql
### c：             
   >crtsurfdata.cpp：生成全国气象站点观测的分钟数据；<br><br>
   >obtcodetodb.cpp：把全国站点参数数据保存到数据库T_ZHOBTCODE表中；<br><br>
   >obtmindtodb.cpp：把全国站点分钟观测数据入库到T_ZHOBTMIND表中；<br><br>
   >makefile：编译指令的程序；<br><br>
   >start.sh：启动程序的shell脚本；<br><br>
   >killall.sh：结束程序的shell脚本。<br><br>
### ini：
   >stocode.ini：存放天气数据的文档<br><br>
### sql:
   >存放了一些重要的MySQL数据表<br><br>
## public文件目录下包含了项目所需要使用的文件和三个文件夹，文件夹分别为：db、ini和socket
   >_cmpublic.h：此程序是开发框架公用头文件，包含了应用开发常用的头文件；<br><br>
   >_ftp.cpp：此程序是开发框架的ftp客户端工具的类的定义文件；<br><br>
   >_ftp.h：此程序是开发框架的ftp客户端工具的类的声明文件；<br><br>
   >_public.cpp，此程序是开发框架公用函数和类的定义文件；<br><br>
   >_public.h，此程序是开发框架公用函数和类的声明文件；<br><br>
   >ftplib.c：此程序是ftp协议所需要使用公用函数和类的定义文件；<br><br>
   >ftplib.h：此程序是ftp协议所需要使用公用函数和类的声明文件；<br><br>
### db：
   >_mysql.cpp：此程序是开发框架的C/C++操作mysql数据库的定义文件；<br><br>
   >_mysql.h：此程序是开发框架的C/C++操作MySQL数据库的声明文件；<br><br>
   >blobtofile.cpp：此程序演示开发框架操作MySQL数据库（提取BLOB字段内容到图片文件中）；<br><br>
   >createtable.cpp：此程序演示开发框架操作MySQL数据库（创建表）；<br><br>
   >deletetable.cpp：此程序演示开发框架操作MySQL数据库（删除表中的记录）；<br><br>
   >filetoblob.cpp：此程序演示开发框架操作MySQL数据库（把图片文件存入BLOB字段）；<br><br>
   >inserttable.cpp：此程序演示开发框架操作MySQL数据库（向表中插入5条记录）；<br><br>
   >selecttable.cpp：此程序演示开发框架操作MySQL数据库（查询表中的记录）；<br><br>
   >updatetable.cpp：此程序演示开发框架操作MySQL数据库（修改表中的记录）；<br><br>
   >makefile：编译指令的程序。<br><br>
### ini：
   >hssms.ini：存放hssms连接数据库路径的文档<br><br>
### socket:
   >demo01.cpp：此程序用于演示socket通讯的客户端；<br><br>
   >demo02.cpp：此程序用于演示socket通讯的服务端；<br><br>
   >demo03.cpp：此程序用于演示粘包的socket客户端；<br><br>
   >demo04.cpp：此程序用于演示粘包的socket服务端；<br><br>
   >demo05.cpp：此程序用于演示不粘包的socket客户端；<br><br>
   >demo06.cpp：此程序用于演示不粘包的socket服务端；<br><br>
   >demo07.cpp：此程序用于演示采用TcpClient类实现socket通讯的客户端；<br><br>
   >demo08.cpp：此程序用于演示采用TcpServer类实现socket通讯的服务端；<br><br>
   >demo10.cpp：此程序演示采用开发框架的CTcpServer类实现socket通讯多进程的服务端；<br><br>
   >demo11.cpp：此程序用于演示网银APP软件的客户端；<br><br>
   >demo12.cpp：此程序用于演示网银APP软件的服务端；<br><br>
   >demo13.cpp：此程序用于演示网银APP软件的客户端，增加了心跳报文；<br><br>
   >demo14.cpp：此程序用于演示网银APP软件的服务端，增加了心跳报文；<br><br>
   >demo20.cpp：此程序演示采用开发框架的CTcpServer类实现socket通讯多线程的服务端；<br><br>
   >demo26.cpp：此程序演示HTTP协议，接收http请求报文；<br><br>
   >demo27.cpp：此程序用于演示HTTP客户端；<br><br>
   >demo28.cpp：此程序演示基于HTTP协议的数据访问接口的简单实现；<br><br>
   >demo31.cpp：此程序是网络通信的客户端程序，用于演示异步通信（多进程）的效率；<br><br>
   >demo32.cpp：此程序是网络通信的服务端程序，用于演示同步通信的效率；<br><br>
   >demo33.cpp：此程序是网络通信的客户端程序，用于演示异步通信（poll）效率；<br><br>
   >makefile：编译指令的程序。<br><br>
## tools文件目录下包含了两个个文件夹，分别为：c和ini
### c：
   >_tools.h：此程序是开发框架的通用模块开发的公共函数声明文件；<br><br>
   >_tools.cpp：此程序是开发框架的通用模块开发的公共函数定义文件；<br><br>
   >checkproc.cpp：此程序是用于演示守护进程；<br><br>
   >deletefiles.cpp：此程序是用于演示超时文件删除；<br><br>
   >dminingmysql.cpp：次程序是数据中心的公共功能模块，用于从MySQL数据库源表抽取数据，生成xml文件；<br><br>
   > execsql.cpp：此程序是一个工具程序，用于执行一个sql脚本文件；<br><br>
   > fileserver.cpp：此程序是用于演示文件传输的服务端；<br><br>
   > ftpgetfiles.cpp：此程序是用于演示采用ftp协议，实现文件下载的客户端；<br><br>
   > ftpputfiles.cpp：此程序是用于演示采用ftp协议，实现文件上传的客户端；<br><br>
   > gzipfiles.cpp：此程序是用于演示压缩文件；<br><br>
   > procctl.cpp：此程序是用于演示调度进程；<br><br>
   > tcpgetfiles.cpp：此程序是用于演示采用tcp协议，实现文件下载的客户端；<br><br>
   > tcpputfiles.cpp：此程序是用于演示采用tcp协议，实现文件上传的客户端；<br><br>
   > xmltodb.cpp：次程序是数据中心的公共功能模块，用于把xml文件入库到MySQL的表中；<br><br>
   > makefile：编译指令的程序；<br><br>

......持续开发中
