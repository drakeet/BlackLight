####原作者是 [PeterCxy](https://github.com/PeterCxy) ，我只是 fork 了个版本，做了一些很小的小修改：


将微博作者头像、名称及 overflow menu 提到微博内容上部（哈哈，多年的梗）；

在每一条微博面板增加快捷收藏按钮（我比较怕刷屏，所以喜欢使用收藏微博）；

新增默认 key 自动填入；

调整 PersistentSearch 的展开速度，并提高公开接口方法调整这个速度；

一些尺寸微调：

修改侧滑菜单头图为长方形（原正方形）；

调小 发布微博字体的大小；

####说明

有些改动（比如我引入第三方库）虾大不同意，所以未能 PR... 所以只作为一个自己的定制版，同时大家如果觉得不错，可以自行编译安装。。。

drakeet debug 版本下载（已经使用新包名了，可以和虾大的版本同时安装同时存在）：https://github.com/drakeet/BlackLight/raw/master/app-drakeet-debug.apk

原开源地址：https://github.com/PaperAirplane-Dev-Team/BlackLight 

####截图如下

<img src="http://7xiabt.com1.z0.glb.clouddn.com/FhsWvtvR1CS9fweiVJVtta9pog0S" width="220" height="391" /> <img src="http://7xiabt.com1.z0.glb.clouddn.com/FjVJTD1qF2imUW9XziSSvvl6vDM2" width="220" height="391" /> <img src="http://7xiabt.com1.z0.glb.clouddn.com/Fk_7KR6w1DGvqrVlygYeuYTwCi73" width="220" height="391" /> <img src="http://7xiabt.com1.z0.glb.clouddn.com/Fl4A6GcSfDkU3N0JjVOUjdK-CjXc" width="220" height="391" />


##以下是原作者的 README.md 内容：


BlackLight 新浪微博客户端
---
![Logo](https://raw.githubusercontent.com/PaperAirplane-Dev-Team/BlackLight/master/art/logo.png)
[![Build Status](https://travis-ci.org/PaperAirplane-Dev-Team/BlackLight.svg?branch=master)](https://travis-ci.org/PaperAirplane-Dev-Team/BlackLight)
详细介绍请见 <http://typeblog.net/blacklight>  
Play商店 <https://play.google.com/store/apps/details?id=us.shandian.blacklight>  
源代码在GPLv3协议下发布

由于新浪微博已经不再接受新的第三方客户端申请，因此BlackLight使用“黑魔法”的方式登录微博。客户端内内置了一个可用的APP KEY。  
个人娱乐之作，勿用于任何盈利性用途。  

如果你有意加入本项目，你可以阅读我们的Wiki以及下面的内容来获得有关指导。  

使用Android Studio导入
---
1. `git clone` 本项目到本地
2. 在`Android Studio` 中执行 `Import` 并耐心等待……等待……再等待
3. 编译时请选择`app`模块，`app_snapshot`仅供自动发布之用
4. Enjoy it!

使用AIDE导入
---
1. 安装 `AIDE` 到你的手机上
2. 在其中直接clone本项目并打开即可

编译非调试版本
---
如果您想编译非调试版本，即 `Release` 版本，请在项目根目录创建 `signing.properties`

```
STORE_FILE=/path/to/your/publish/keystore
STORE_PASSWORD=your_passwd
KEY_ALIAS=your_alias
KEY_PASSWORD=your_passwd
```

然后即可使用 `gradle :app:assembleRelease`

在Chrome中运行
---
参考 <https://github.com/vladikoff/chromeos-apk/blob/master/archon.md> 配置apk运行环境

Chrome中运行效果:  
![Chrome](https://raw.githubusercontent.com/PaperAirplane-Dev-Team/BlackLight/master/art/chrome-screenshot.png)

感谢
---
四次元(@qii)  
碎星iKe(@IssacWong)


主要开发者
---
@PeterCxy  
@Harry-Chen  
@fython  
@xavieryao

纸飞机开发团队 @PaperAirplane-Dev-Team 出品
