# 说明
一些中国域名、Fake News和轮子域名的屏蔽列表
适用于以下项目：
https://github.com/sprov065/soga
https://github.com/XrayR-project/XrayR

# Soga用法

以Root权限运行之后重启你的Soga  

```
wget https://raw.githubusercontent.com/Rakau/blockList/main/blockList -O /etc/soga/blockList
```

# XrayR用法

以Root权限运行之后，编辑/etc/XrayR/config.yml找到RuleListPath这一项，去掉#后保存重启XrayR

```
wget https://raw.githubusercontent.com/Rakau/blockList/main/blockList -O /etc/XrayR/rulelist
```
