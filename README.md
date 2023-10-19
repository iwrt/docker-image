# iWRT-release。只上传roof格式的，用于docker镜像。
#拉取docker镜像
# 下载镜像(在ttyd终端输入)
一、LeS系列
$ docker pull iwrt/openwrt-docker:LeS-x64

# 查看镜像信息
$ docker run --rm iwrt/openwrt-docker:OpR-x64 cat /etc/banner

$ docker  images
$ docker run --rm -it iwrt/openwrt-docker:OpR-x64
$ docker run -d -p 85:80 iwrt/openwrt-docker:OpR-x64

二、OpR系列
$ docker pull iwrt/openwrt-docker:OpR-x64
# 查看镜像信息
$ docker run --rm iwrt/openwrt-docker:OpR-x64 cat /etc/banner
