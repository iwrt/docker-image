# iWRT-release。只上传roof格式的，用于docker镜像。
#拉取docker镜像
# 下载镜像(在ttyd终端输入)
一、LeS系列
$ docker pull iwrt/openwrt-docker:LeS-x64
# 查看镜像信息
$ docker run --rm iwrt/openwrt-docker:LeS-x64 cat /etc/banner

二、ImS系列
$ docker pull iwrt/openwrt-docker:ImS-x64
# 查看镜像信息
$ docker run --rm iwrt/openwrt-docker:ImS-x64 cat /etc/banner
