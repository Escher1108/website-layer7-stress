# website-layer7-stress
无防御网站测压，攻击力85%，瞬间让服务器负载.

### 使用教程：

```shell
#运行环境
所有Linux系统，建议Debian

#依赖环境
python2

#下载
git clone https://github.com/lzhen186/mymusic.git

#使用
python2 l7.py <URL>
Example：Python2 l7.py https://example.com
```

### 使用说明： ###

测试站点套用了CF CDN，国内使用的腾讯云CDN,但是还是透了，以下是效果：![](https://github.com/Escher1108/website-layer7-stress/blob/main/images/2.png)

### 使用声明: ###

该代码只能对无防御站点进行测压，具体效果主要是看攻击目标性能，本代码所造成的责任本人不负责！！！