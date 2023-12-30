# 适用于小米ax3000t的openwrt固件

## 修改说明

1.删除了部分插件 

2.有带xray的ssrplus科学上网 

3.添加ipv6支持 

4.添加了主题 

5.通过修改编译文件修复原版自编译导致set-out错误

## 使用方法

### 使用方法一

直接到Releases中下载已经编译好的固件

### 使用方法二

1：先fork这个仓库

2：到自己fork的仓库后的点击`Actions`

3：点击`Build OpenWrt`下的`Run workflow`即可开始编译

4：等待编译完成后再次进入`Actions`点击刚刚完成的一次编译

5：点击编译完成的固件即可下载

## 其他

1.默认的登录ip是`192.168.1.1`
3.默认登录密码是`password`
2.如果想修改配置可以把你的config文件替换进来
