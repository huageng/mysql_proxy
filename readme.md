一个简单的mysql代理（转发mysql执行语句）：
    打成jar包：mysql_proxy.jar，然后执行
        java -cp mysql_proxy.jar mysql.custom.proxy.MysqlProxyServer proxy_host proxy_port
        proxy_host:被代理的mysql服务host
        proxy_port:被代理的mysql服务的端口