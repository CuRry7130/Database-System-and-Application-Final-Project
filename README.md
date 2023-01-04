# Database System and Application Final Project

>  本项目为USTC2022学年夏季学期金培权老师开设的《数据库系统与应用》课程的大作业

### 简述 ###

基于Python Flask、MySQL的数据库开发，在Flask框架下实现一个简单的银行管理系统

### 运行环境 ##

- Python3.9**(配置Flask.whl与mysqlclient.whl**)
- MySQL8.0

### 启动说明 ###

- 打开MySQL，创建一个MySQL Connection（注意**此时所显示本地服务器地址与端口号并非登入系统时所用**）,导入初始的demo.sql文件

  ![launch_step1](D:\Github\Database-System-and-Application-Final-Project\pics\launch_step1.jpg)

  注：Windows系统在此处登入该链接后可能会出现**No connection established**的问题，这是由于MySQL服务默认需手动开启

  Win+R运行**services.msc**（或进入控制面板后搜索“服务”，进入“查看本地服务”）,找到**MYSQLxx**服务（其后数字视版本而定，本机使用MySQL8.0，故显示为MySQL80），双击后选择运行即可

  ![potential_problem_solution](D:\Github\Database-System-and-Application-Final-Project\pics\potential_problem_solution.jpg)

- 在db.py程序代码底部db_login函数处按**用户名、密码、服务器地址、数据库名称**依次修改参数

  ![launch_step2](D:\Github\Database-System-and-Application-Final-Project\pics\launch_step2.jpg)

- 命令行运行app.py

  ![launch_step3](D:\Github\Database-System-and-Application-Final-Project\pics\launch_step3.jpg)

- 打开浏览器，访问第二步运行db.py后所给出的本地服务器地址（指明端口），即可进入银行管理系统登录页面

  ![launch_step4](D:\Github\Database-System-and-Application-Final-Project\pics\launch_step4.jpg)

- 输入第二步里的对应信息即可成功登录










