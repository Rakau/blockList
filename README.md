# 说明
一些中国域名、Fake News和轮子域名的屏蔽列表

适用于以下项目：

https://github.com/sprov065/soga

https://github.com/newxrayr/XrayR

# 关于PR
本项目欢迎PR，但请了解如下说明后再Pull

1、有争议的不会合并

2、格式排版不正常的不会合并

3、主审计范围外的审计规则不注释的不会合并

4、弊大于利的不会合并

5、带有个人用途范围并且不考虑大众适用范围的不会合并


# Soga用法

以Root权限运行之后重启你的Soga  

```
wget https://raw.githubusercontent.com/Rakau/blockList/main/blockList -O /etc/soga/blockList
```

# XrayR用法

以Root权限运行之后，编辑/etc/XrayR/config.yml找到RuleListPath这一项，去掉#和无用语句后保存重启XrayR

```
wget https://raw.githubusercontent.com/Rakau/blockList/main/blockList -O /etc/XrayR/rulelist
```
