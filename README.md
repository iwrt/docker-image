# iWRT-release。只上传roof格式的，用于docker镜像。
#拉取docker镜像
# 下载镜像
$ docker pull iwrt/openwrt-docker:LeS-x64
# 查看镜像信息
$ docker run --rm iwrt/openwrt-docker:LeS-x64 cat /etc/banner
