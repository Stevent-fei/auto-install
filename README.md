# auto-docker

这个是一个一键自动化安装最新版本docker的脚本文件，拿来即用～

* 支持centos系统  
* 支持ubuntu系统

安装最新版docker使用方法：

```shell
1. 拉取项目
git clone https://github.com/Stevent-fei/auto-docker.git

2. 进入项目
cd auto-docker

3. centos系统执行脚本进行自动化安装docker/ubuntu系统执行脚本进行安装docker
bash docker/centos/auto-install-docker.sh
bash docker/ubuntu/auto-install-docker.sh
```

卸载docker使用方法：

```shell
centos系统直接执行uninstall-docker.sh脚本即可/ubuntu系统直接执行uninstall-docker.sh脚本即可
bash docker/centos/auto-uninstall-docker.sh
bash docker/ubuntu/auto-uninstall-docker.sh
```