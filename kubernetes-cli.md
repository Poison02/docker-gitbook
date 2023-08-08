# kubernetes-cli

## Kubernetes 命令行 kubectl

​[kubectl](https://github.com/kubernetes/kubernetes) 是 Kubernetes 自带的客户端，可以用它来直接操作 Kubernetes。使用格式有两种：kubectl \[flags]kubectl \[command]

### get <a href="#get" id="get"></a>

显示一个或多个资源

### describe <a href="#describe" id="describe"></a>

显示资源详情

### create <a href="#create" id="create"></a>

从文件或标准输入创建资源

### update <a href="#update" id="update"></a>

从文件或标准输入更新资源

### delete <a href="#delete" id="delete"></a>

通过文件名、标准输入、资源名或者 label selector 删除资源

### log <a href="#log" id="log"></a>

输出 pod 中一个容器的日志

### rolling-update <a href="#rolling-update" id="rolling-update"></a>

对指定的 replication controller 执行滚动升级

### exec <a href="#exec" id="exec"></a>

在容器内部执行命令

### port-forward <a href="#port-forward" id="port-forward"></a>

将本地端口转发到Pod

### proxy <a href="#proxy" id="proxy"></a>

为 Kubernetes API server 启动代理服务器

### run <a href="#run" id="run"></a>

在集群中使用指定镜像启动容器

### expose <a href="#expose" id="expose"></a>

将 replication controller service 或 pod 暴露为新的 kubernetes service

### label <a href="#label" id="label"></a>

更新资源的 label

### config <a href="#config" id="config"></a>

修改 kubernetes 配置文件

### cluster-info <a href="#cluster-info" id="cluster-info"></a>

显示集群信息

### api-versions <a href="#api-versions" id="api-versions"></a>

以 "组/版本" 的格式输出服务端支持的 API 版本

### version <a href="#version" id="version"></a>

输出服务端和客户端的版本信息

### help <a href="#help" id="help"></a>

显示各个命令的帮助信息
