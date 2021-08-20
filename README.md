
# 自定义更改


帅气的rime的简介请看[官网](https://rime.im/)

windows平台中叫[小狼毫/weasel](https://github.com/rime/weasel)

android平台中叫[同文/trime](https://github.com/osfans/trime)


按照自身需求作了简单修改，感谢原作者[SivanLaai](https://github.com/SivanLaai/rime-pure)

主要特征说明如下

## 保留两种输入法
- [四叶草简体拼音](https://github.com/fkxxyz/rime-cloverpinyin)
- [极点五笔](https://github.com/KyleBing/rime-wubi86-jidian) 



## 简化配置 

小狼毫（windows端）
1. 备份小狼毫输入法安装目录的```data```文件夹，备份```~\AppData\Rime```文件夹(默认)
2. 文件夹```weasel\Rime```内所有文件复制到小狼毫输入法```~\AppData\Rime```目录覆盖
3. 文件夹```weasel\data```内所有文件复制到小狼毫输入法安装目录的```data```目录覆盖(此步可跳过)
4. 重新部署

同文（安卓端）
1. 备份```sdcard\rime```文件夹(默认)
2. 文件夹```trime\rime```内所有文件复制到```sdcard\rime```目录覆盖
3. 重新部署
  
## windows端

方案選單的快捷鍵更改为```ctrl+shift+space```

## Android端

为求方便，避免重复造轮子，基本是tongwenfeng.trime.yaml->reaticle.trime.yaml，
- 键位调整
  - 去掉大部分不用的键盘布局 
  - 修改数字键盘
- 新增配色
  - Reatcile

- 





# 主分支说明

## 【rime 小狼毫\trime 同文】手机/PC一站式配置【简约皮肤\拼音搜狗词库\原创trime同文 四叶草九宫格拼音\四叶草拼音\小鹤双拼\极品五笔\QQ五笔\徐码\郑码】

## 说明
- rime是一款支持多平台的开源输入法，开源所以不需要担心自己的输入数据被输入法所搜集。虽然优点这么多，但是要使得输入法好用起来门槛比较高了，主要是在词库配置优化，依赖的东西多而且复杂。**本项目的目的在于安卓手机端和Win pc端都可以从本项目一站配置好rime输入法，达到省心好用的程度**。鉴于PC端已经有很多大神有现成的设置，所以花的时间较少，主要是整理收集。

- **发现手机端的优化一直没有做的较好的优化，本次主要的工作量是在手机端**，所以从资源收集、皮肤设计、全键盘按钮设计和九宫格按键设计的每一个过程很耗费时间，有很多细节需要调整不断的修改文件和部署，有些地方不是清楚配置的地方还需要去看源码，经过一周的优化和设置，手机端已经使用起来很顺畅了。

- **目前在手机端配置了基于四叶草拼音的九宫格输入法，为了表示对原作者的劳动致敬，遂命名为四叶草九宫方案，感觉已经和之前使用的百度或者讯飞输入法感觉相当。**

- **enjoy it! 好用的话就点个赞。感谢你的使用，因为本人同时在安卓和windows端使用，所以会一直更新。**

- ![visitors](https://visitor-badge.laobi.icu/badge?page_id=SivanLaai/rime-pure)

## 包含输入方案
 - [四叶草拼音九宫格](https://github.com/SivanLaai/rime-pure) 
 - [极点五笔](https://github.com/KyleBing/rime-wubi86-jidian) 
 - [小鹤双拼](https://www.flypy.com/index.html)
 - [🍀️四叶草简体拼音](https://github.com/fkxxyz/rime-cloverpinyin)
 - 大写数字
 - 自然双拼
 - QQ86五笔（**提取自qq五笔输入法，词库较为合理，推荐使用也是本人在使用的方案**）
 - [徐码](https://www.xumax.top/)
 - [郑码](http://zmdisk.ys168.com/)


## 实用功能：
### 同文端
- 隐藏输入法：全键盘状态下按键G向上滑，九宫格状态下按[JKL]向上滑
- 编辑功能：全键盘状态下长按G，九宫格状态下按编辑键，可实现复制粘贴拷贝等功能
- 清空文本：删除键向左滑会清,空当前编辑文本
- 切换主题：空当前编辑文本长按带❖的按键切换主题
- 切换输入法：长按带✎的按键切换输入方案
- 更多设置：长按带设置符号⚙的按键，既可进入更多设置页面

## 界面预览：
### 小狼毫输入法（PC端）
- 简约现代蓝[配色：XNOM]

![Image text](https://cdn.jsdelivr.net/gh/SivanLaai/image-store-rep@master/rime/preview_blue.2lyjsr0q0cu0.png)
- 绿野仙踪绿[配色：佛振]

![Image text](https://cdn.jsdelivr.net/gh/SivanLaai/image-store-rep@master/rime/preview_green.6b8wbkfogzc0.png)
- Aqua[配色：佛振]

![Image text](https://cdn.jsdelivr.net/gh/SivanLaai/image-store-rep@master/rime/preview_blue1.1zkbreawyluo.png)
- 安卓[配色：Patricivs]

![Image text](https://cdn.jsdelivr.net/gh/SivanLaai/image-store-rep@master/rime/preview_android.752cop13gfg0.png)
- 暗堂[配色：佛振]

![Image text](https://cdn.jsdelivr.net/gh/SivanLaai/image-store-rep@master/rime/preview_dark.fn4qmzlq1i8.png)
- 孤寺[配色佛振]

![Image text](https://cdn.jsdelivr.net/gh/SivanLaai/image-store-rep@master/rime/preview_temple.eba0ht77dio.png)

### 同文输入法（安卓端）

##### 🍀️四叶草九宫输入方案
![Image text](https://cdn.jsdelivr.net/gh/SivanLaai/image-store-rep@master/rime/trime_preview_jiugong.3vyf36hha4q0.jpg)

##### 手机端支持简繁转换

![Image text](https://cdn.jsdelivr.net/gh/SivanLaai/image-store-rep@master/rime/trime_convert.5pjs6ljodh00.jpg)


#### 部分皮肤预览

##### 同文风优化版[配色：Jaaiko，键盘布局：Jaaiko]

![Image text](https://cdn.jsdelivr.net/gh/SivanLaai/image-store-rep@master/rime/trime_tongwen.3z9r9pmc5ko0.png)

##### 讯飞默认皮肤[配色：Jaaiko，键盘布局：Jaaiko]

![Image text](https://cdn.jsdelivr.net/gh/SivanLaai/image-store-rep@master/rime/trime_xunfei.5tewulxml340.png)

##### cherry机械键盘【小先生】

![Image text](https://cdn.jsdelivr.net/gh/SivanLaai/image-store-rep@master/rime/trime_cherry.6ibtk68ohb80.png)


##### 极致简约[配色：Jaaiko，键盘布局：Jaaiko]

![Image text](https://cdn.jsdelivr.net/gh/SivanLaai/image-store-rep@master/rime/trime_preview.5g84abqu3a00.png)


##### 五笔字根【佚名】

![Image text](https://cdn.jsdelivr.net/gh/SivanLaai/image-store-rep@master/rime/trime_wubizigen.58iqusedxr40.png)


##### 炫彩[键盘布局：Jaaiko]

![Image text](https://cdn.jsdelivr.net/gh/SivanLaai/image-store-rep@master/rime/trime_xuancai.5k9xzrtj80o0.png)


## 安装方法

- ~~查看安装方法~~

## 更新历史

#### 2021-08-01

 - 1.修复九宫拼音不支持简拼的情况，如输入xqw不显示结果。
 - 2.四叶草拼音去除25258个重复的词组，只保留最高频次的词组
 ```
 ./Clover四叶草拼音/clover.phrase.dict.yaml:成事在人     cheng shi zai ren       22846
 ./Clover四叶草拼音/THUOCL_chengyu.dict.yaml:成事在人    cheng shi zai ren       21
 如上所示，成事在人，在两个字典中都有频次，只保留clover.phrase.dict.yaml中22846频次的词组
 ```
 - 3.更新四叶草拼音拼音错误，例如反弹拼音为fandan，[错误修复来源@wisim](https://github.com/fkxxyz/rime-cloverpinyin/pull/85)，感谢@[spphinslove](https://github.com/SivanLaai/rime_pure/issues/32)的反馈
 - 4.四叶草拼音-汉字帧-拼音错误修改，把帧错误拼音zheng相关的词组全部修改为帧zhen
 - 修改费时费力，不易，请大家多多支持，[点击支持](https://github.com/SivanLaai/rime_pure#sparkling_heart%E6%94%AF%E6%8C%81%E8%BF%99%E4%B8%AA%E9%A1%B9%E7%9B%AE)。

#### 2021-07-29

 - 1.添加九宫格支持隐藏
 - 2.添加常用功能说明

#### 2021-06-27

 - 1.更新同文3.2.0支持
 - 2.修复小鹤双拼简繁转换问题
 - 3.自然码支持简繁转换问题

#### [以往全部历史](https://sivanlaai.github.io/pages/841d8d/)

## 相关资源
 - 小狼毫输入法：https://github.com/rime/weasel
 - 同文输入法：https://github.com/osfans/trime
 - 简繁转换opencc：https://github.com/BYVoid/OpenCC
 - 部分配色均整理自互联网，配色包含作者信息。

## 感谢
 - **感谢@[lotem](https://github.com/lotem)**
 - **感谢trime作者@[osfans](https://github.com/osfans)**
 - **感谢四叶草拼音作者@[fkxxyz](https://github.com/fkxxyz)**
 - **感谢极品五笔作者@[KyleBing](https://github.com/KyleBing)**
 - **感谢qq五笔@[qq五笔](http://qq.pinyin.cn/wubi/)**
 - **感谢opencc作者@[BYVoid](https://github.com/BYVoid)**
 - **感谢@[小鹤双拼](https://www.flypy.com/)**
 - **感谢@[郑码](http://zmdisk.ys168.com/)**
 - **感谢@[徐码](https://www.xumax.top/)**
 - **没有以上资源和各位的辛苦付出，也就没有这个项目**

## :sparkling_heart:支持这个项目

如果你正在使用这个项目并感觉良好，或只是想要支持我继续开发，你可以通过如下*任意* 方式支持我：

1. **Star** 并 分享这个项目 :rocket:
2. 通过以下二维码 一次性捐款。 一杯咖啡。:tea:

谢谢！ :heart:

| 支付宝 | 支付宝 |
| :---: | :---: |
| <img src="https://cdn.jsdelivr.net/gh/SivanLaai/image-store-rep@master/rime/a45c35cd5575760621be4b38e92f96a.48oklhe4a6g0.jpg" alt="Wechat QRcode" width=200>| <img src="https://cdn.jsdelivr.net/gh/SivanLaai/image-store-rep@master/rime/a45c35cd5575760621be4b38e92f96a.48oklhe4a6g0.jpg" alt="Alipay QRcode" width=200> |

## 许可证
[MIT](https://github.com/SivanLaai/rime_pure/blob/master/LICENSE)

Copyright (c) 2020-present SivanLaai
