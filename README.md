# docker_mirror

查找国内最快的docker镜像源，支持CentOS/Ubuntu。

Python编写，需要root权限，支持ubuntu和centos7，其他操作系统需要补充。

脚本会自动从official, aliyun, netease, ustc尝试下载centos最新的docker镜像，并计算使用的时间；按使用时间最少的镜像设置docker配置，并重启docker进程。

```
python ./docker_mirror.py
```

脚本执行后，就可以直接使用最快的docker镜像了。

