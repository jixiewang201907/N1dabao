# 此项目基于flippy的80+o和80+打包N1 HK1 x96max的openwrt

# 默认IP及密码
默认IP 192.168.2.10  密码 password

# N1全新安装
 下载对应版本固件
 
 将固件写入U盘或TF卡 推荐写盘软件 rufu或者balenaEtcher任选其一
 
 插入U盘启动盒子，输入192.168.2.10进入后台
 
 在系统——TTYD终端——输入用户名root；密码password
 
 输入安装命令 /root/install-to-emmc.sh
 
# 自动更新说明
 固件采用自动编译，Acrions将会在每天监控上游代码是否更新，一旦检测到上游代码更加将会自动编译打包，于每天上午7时30分发布最新版固件。
