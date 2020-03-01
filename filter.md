---
title: AdGuard规则，去网页广告，去视频广告，去启动广告，去app广告
date: 2019-09-26 13:14:21
categories: 广告过滤
tags: 原创
---
## [点击支持一下](#ganxie)
  
  #### 信仰支撑，绝无收费，绝无劫持。当然也不保证能坚持的什么时候，应该会很久。

> **主要对通用规则的补充，去网页广告，去视频广告，去启动广告，去app广告，以及处理一些通用规则的误杀，屏蔽常用国产浏览器的恶意注入，脚本解析目前适配：腾讯视频、爱奇艺、优酷，芒果TV，QQ音乐，同时支持手机网站，PC网站**，~~*有时间了再适配其他网站。*~~
<!--more-->
> 说明：不可能满足所有人，不好用可留言提意见，或者不用就是，有能力就[[*自己写规则*]](/2019/09/26/撰写-Adblock-Plus-过滤规则/) [[*自己写脚本*]](/2019/09/26/油猴脚本语法/)，没向你收费也没求你用，拒绝BB！
> **window系统上，如果想更好的过滤（视频）广告，推荐一款超好用的免费软件，[阿呆喵（点击查看官网）](http://www.admflt.com/?from=www.xuehuayu.cn)。阿呆喵 建议仅在adguard无法过滤视频广告的时候开启，同时关闭adguard（有冲突）。平时只打开adguard即可。**

1. **建议使用谷歌，火狐，Edge等\*\*纯净\*\*浏览器。其他浏览器\*\*内置的一些功能工具\*\*会影响过滤效果，不保证有效。尤其是一些有神奇功能的浏览器，没办法也不会去适配。**
2. **优酷app广告无法过滤（建议使用脚本，然后用浏览器观看）。腾讯视频、爱奇艺、网易云 等app开启规则后，建议先清理app缓存，然后重启app。**
3. **如果有无法过滤问题，或者误杀问题，可以通过查看过滤日志，点击对应日志，然后拦截或者取消拦截。也可以自己写规则，保存在‘用户过滤器’中，也可以保存在github仓库中，生成链接添加在‘自定义过滤器’中。github如何使用，请自行查找。**

---

  1. `如果不清楚打开哪些过滤规则，可查看` → [[*推荐设置*]](/2019/09/26/AdGuard推荐设置/)

  2. 如不会添加规则，请 → [[*点这里*]](/2019/09/26/AdGuard规则添加方法/) `(仅说明手机端AdGuard添加方法)`

  3. `关于开启后网速变卡问题，请查看 添加方法。` → [[*点这里*]](/2019/09/26/AdGuard规则添加方法/#4)

  4. `如有任何问题，可在下方评论说明，看到后会改。` → [[*去评论*]](#vcomment)

  5. 添加或者更新过滤器之后，因浏览器缓存问题，请重新开关adguard，然后多刷新几次页面。

  6. 仍有广告无法过滤，可自己编写规则和脚本。→ [[*自己写规则*]](/2019/09/26/撰写-Adblock-Plus-过滤规则/) [[*自己写脚本*]](/2019/09/26/油猴脚本语法/)

  7. APP启动广告并不能完全过滤，在这里推荐两款 跳过启动广告的APP【仅限安卓】
    1、 [自动跳过](https://www.coolapk.com/apk/me.angeldevil.autoskip)
    2、 [轻启动](https://www.coolapk.com/apk/com.wpengapp.lightstart)

---

- [[DNS通用规则] **点击查看**](https://raw.githubusercontent.com/niepengsmile/niepengsmile.github.io/master/adfilter/dns.txt)

  **不是DNS服务器**，`不明白的，请点上面的添加方法`
  
  `https://raw.githubusercontent.com/niepengsmile/niepengsmile.github.io/master/adfilter/dns.txt`

  `https://www.cainiaoblog.cn/adfilter/dns.txt`


- [[手机端规则] **点击查看**](https://raw.githubusercontent.com/niepengsmile/niepengsmile.github.io/master/adfilter/mob.txt)

  `https://raw.githubusercontent.com/niepengsmile/niepengsmile.github.io/master/adfilter/mob.txt`

  `https://www.cainiaoblog.cn/adfilter/mob.txt`


- [[CJX's EasyList Lite] **点击查看**](https://raw.githubusercontent.com/cjx82630/cjxlist/master/cjxlist.txt)

  大名鼎鼎的abp中国区负责人维护的手机端规则，更新周期比较长
  因用的人多，github经常会限制，一般换个时间，多刷新几次就好

  `https://raw.githubusercontent.com/cjx82630/cjxlist/master/cjxlist.txt`


- [[电脑端规则] **点击查看**](https://raw.githubusercontent.com/niepengsmile/niepengsmile.github.io/master/adfilter/pc.txt)

  `https://raw.githubusercontent.com/niepengsmile/niepengsmile.github.io/master/adfilter/pc.txt`

  `https://www.cainiaoblog.cn/adfilter/pc.txt`

- [[多功能脚本] **点击查看**](https://www.cainiaoblog.cn/adfilter/script.js)

  - 本站地址：

    `https://raw.githubusercontent.com/niepengsmile/niepengsmile.github.io/master/adfilter/script.js`

    `https://www.cainiaoblog.cn/adfilter/script.js`

    <br/>

    **由于GreasyFork自动更新总是失败，每次都要手动更新很麻烦，以后将 不定期更新。所以建议用本站地址！代码是透明的，所有人都可以查看的，全部本地运行，没有云控制之类的，没有安全问题！~~仍然担心安全问题的请耐心等待GreasyFork的更新。~~**
    说明：发现搬运之后反而收费的垃圾，屏蔽屏蔽屏蔽！
  - [[GreasyFork地址] **点击查看**](https://greasyfork.org/zh-CN/scripts/397154-cainiaoscript-author-xuehuayu-cn):

    `https://greasyfork.org/scripts/390892-cainiaoscript/code/CaiNiaoScript.user.js`

---
<span id="ganxie"></span>

### 您只需动动手，领取支付宝红包，不花一分钱，就可以支持作者做的更好，非常感谢！

### \* 红包记得及时用哦 \*。如果您不常用支付宝，可直接扫描第二张图将红包支付给我，红包额度多少就支付多少。

### 支付的时候，支付方式请选择[ \*余额宝\* ]或者[ \*花呗\* ]，然后看清楚是否有红包抵消。如果没有红包抵消请不要支付！ 再次感谢！

<img src="https://i.niupic.com/images/2019/11/14/_1678.png" alt="支付宝红包" style="display: inline-block;height:450px;" />
<img src="https://i.niupic.com/images/2020/02/10/6nZY.png" alt="支付给我" style="display: inline-block;height:450px;" />
