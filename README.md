# chatserver
可以工作在nginx tcp负载均衡环境中的集群聊天服务器和客户端源码 基于muduo库实现 redis mysql

编译方式
cd build
rm -rf *
cmake ..
make
cd ../bin
./ChatServer ip port

需要配置nginx tcp的负载均衡
需要启动redis服务
需要启动mysql


功能实现：

用户首页面：

![image](https://github.com/user-attachments/assets/1e8809c1-258b-4a7d-8013-8c577000b233)

登录成功页面：

![image](https://github.com/user-attachments/assets/b84cf78a-6e97-4880-8f92-a61a0fbdffa3)



