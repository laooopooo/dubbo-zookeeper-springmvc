# dubbo-zookeeper-springmvc
使用dubbo发布服务，netty启动容器，springmvc提供restful接口

1.dubbo-common 提供公共接口；

2.dubbo-provide是服务提供者（接口的实现）；

3.dubbo-consumer是服务器消费者（接口的调用）；

4.zookeeper管理注册中心；

5.springmvc写restful接口；

6.netty提供容器服务器(这里也可以是一个web的程序)，客户端的请求由spring的DispatcherServlet处理；
