
编译openwrt
克隆lede
```
git clone https://github.com/coolsnowwolf/lede
```
固件更新/安装扩展包
```
./scripts/feeds update -a && ./scripts/feeds install -a
```
个性化固件
```
make menuconfig 
```
选择系统架构、子架构和路由器型号
