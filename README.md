# bigdata-dev-helper
大数据开发者的助手
标题：花了一天时间写了个 Hadoop 集群 构建脚本

痛点：在做大数据开发的时候需要在本地虚拟机中创建 Hadoop 集群测试环境，但是搭建一个 Hadoop 集群并不是很容易，需要配置很多东西，费时费力，有的时候还有可能出现配置错误等情况。

解决：采用 python 脚本在本地 pycharm 中一键运行脚本，在 3 分钟时间内就可以创建一个集群环境，免去了人工搭建的烦恼。

使用：

1.下载脚本

https://raw.githubusercontent.com/jackhawks/bigdata-dev-helper/main/hadoop_cluster_init_script.py
2.在脚本的同级目录，创建一个名为 packages 的目录

3.上传 jdk 和 hadoop 包到 packages 目录（因为包过大，所以不能上传到 github ）

jdk-8u212-linux-x64.tar.gz
hadoop-3.1.3.tar.gz
4.根据自己的虚拟机 dhcp ip 配置 hosts 参数

5.一键运行

全自动构建集群环境，三分钟搞定！！！
