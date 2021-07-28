测试环境准备

1.连接上服务器：172.16.2.117

2.docker run -p  (自定义端口号):8888 jupyter/pyspark-notebook

例：

```shell
docker run -p 9999:8888 jupyter/pyspark-notebook
```

3.出现了如下情形：

![](./picture/image-20210728153015958.png)

4.将上述红色方框内的ip地址换为服务器地址，将端口换为自定义端口号

例：http://172.16.2.117:9999/?token=31b247bef6f86926d0d3f20def54b5041b275aac12989a6c

即可打开jupyter notebook界面。

之后即可进行pyspark操作。
