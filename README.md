# 五笔98版

## 方案描述

五笔98版方案早已无版权问题（[见此](https://github.com/yanhuacuo/98wubi-tables/blob/master/README.md)）,该档为「中州韵」通用配置文件，码表源自「至善98词库」。 

![预览](https://raw.githubusercontent.com/yanhuacuo/98WB/master/issues/%E9%A2%84%E8%A7%88.png)

![预览1](https://raw.githubusercontent.com/yanhuacuo/98WB/master/issues/%E9%A2%84%E8%A7%881.png)

## 功能特点

- 默认缀饰带声调的汉语拼音，由「opencc」组件实现，故本当的「opencc」文件夹为不可或缺的部分。

![缀音](https://raw.githubusercontent.com/yanhuacuo/98WB/master/issues/%E9%A2%84%E8%A7%882.png)

- 「 \` 」键引导的「精准造词」模式，由三组翻译器搭配实现，可由当前输入的任意单字或词组构建新词条。

![造词](https://raw.githubusercontent.com/yanhuacuo/98WB/master/issues/%E9%A2%84%E8%A7%883.png)

![造词示例 ](https://raw.githubusercontent.com/yanhuacuo/98WB/master/issues/%E9%A2%84%E8%A7%886.png)

- 「 ~ 」键引导的「以形查音」模式，同样调用「opencc」组件实现，可以查询GB18030内汉字的传统带调拼音。

![查音](https://raw.githubusercontent.com/yanhuacuo/98WB/master/issues/%E9%A2%84%E8%A7%884.png)

- 「 z 」键引导的「拼音反查」模式，临时开启拼音模式并反查五笔编码。
![反查](https://raw.githubusercontent.com/yanhuacuo/98WB/master/issues/%E5%8F%8D%E6%9F%A5.png)

- 扩展词库「 wubi98_ci.extended.dict.yaml 」可以直接批量写入词条，无需写入相应编码，如有需要也可添加词频来微调「重码」的条目。

![扩展词库](https://raw.githubusercontent.com/yanhuacuo/98WB/master/issues/%E6%89%A9%E5%B1%95%E8%AF%8D%E5%BA%93.png)

## 特别介绍

- Ctrl + Shift + H ，临时取消「汉语拼音缀饰」。
- 支持简入繁出模式。
- 方案定义文件「 wubi98_ci.schema.yam 」中，添加有取消「汉语拼音缀饰」的「注释」。
- 拼音码表，是改造过的、扩充了GB字集的拼音方案，「拼音反查」不可或缺，普通拼音方案字集没这么大。
