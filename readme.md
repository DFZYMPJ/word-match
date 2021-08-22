[Click me to view English version.](en.readme.md)

# 学神录 #

**发布上线，不过可以升级迭代**

集信息与娱乐于一体的小程序，提供成语接龙、热词搜索、明星游戏、扫码加书和智能问答等服务

如果你也想弄个成语匹配，学神录或许是你的不二选择！

## 特点欣赏 ##

* 自动登陆。 *获取用户的微信授权信息，自动完成注册和登陆*
* 可添加反馈。
* 查询成语关联词。
* 展示搜索热词 *展示搜索热度最高的，对每次搜索的词语热度+1*
* 搜索某个词的反义词、近义词 *按照关联度从大到小展示某个词的所有反义词、近义词*
* 对搜索结果点赞 *可以对搜索结果中的某个词点赞，其关联度+1*
* 反馈成功可以给用户发送微信通知 *微信订阅消息（通知）*
* 联系与反馈 *用户可以向系统提交反馈*
* 反馈是可以上传图片 *Bug截图*
* 支持成语接龙 *一个简(ruo)单(zhi)的成语接龙游戏。*
* 管理员可以查看所有反馈
* 可以将小程序分享给好友 *分享到微信群*
* 成语点赞功能 *增加关联度*
* 智能问答服务 *具有微信翻译、听歌、新闻、聊天、百科等技能*
* <del>发布、编辑、删除你的同学录，展示同学录的内容</del> *
* 明星游戏是一个评价明星的简单游戏，用户点击选择喜欢的明星。
* 查看排行榜，按照分数对演员展示排行榜。*
* 扫码加书，扫一下图书条形码，保存图书在背包中。
* AI卡证识别，扫码名片，获取名片上的信息并保存在卡包中。
* 课程搭配,查找附近的课程信息，选课、课程表、添加信息*

##云函数安装依赖

> npm install -save wx-server-sdk@latest

## Python Scripts
- [cyToCsv.py](./爬虫/cyToCsv.py): 成语大全字典
- [wdToCsv.py](./爬虫/wdToCsv.py): 汉字大全字典
...

## 更新日志 ##

*学神录目前不能使用，会在beta及以后版本允许正常使用。(alpha -> beta -> release)*
*学神录增加新特性，用户可以对自己喜欢的成语点赞。*
*学神录实现多词库搜索，通过拼音查找成语，单字查找成语。*
*学神录接入智能客服，提供智能问答的服务*
*同学录功能上线了！* 
*明星游戏，这是一个简单的游戏，选出你喜欢的演员，系统根据分数进行排序。*
*私人书柜，扫描书背面的条形码加入图书，查看图书信息*
*修复若干个问题，解决图书扫描获取信息失败的问题*
*新增名片识别,AI名片识别，获取名片信息保存在我的卡包*
*仅显示较大更新，并且会不定期省略，详细更新请查看[更新日志](logs.md)。*


版本号 | 日期 | 内容
:---: | :---: | :---:
0.0.2 alpha | 2021年6月1日 | 学神录诞生了！
0.3.0 alpha | 2021年6月2日 | 采集数据。
0.4.2 alpha | 2021年6月3日 | 采集数据。
0.5.3 alpha | 2021年6月4日 | 测试接口。
0.7.3 alpha | 2021年6月5日 | 调试接口。
0.8.3 alpha | 2021年6月6日 | 真机调试。
1.0.0 beta | 2021年6月7日 | 体验版发布！
1.0.1 release | 2021年6月7日 | 学神录发布了！
1.0.2 release | 2021年6月8日 | 新增特性！
1.0.3 release | 2021年6月9日 | 优化搜索！
1.0.4 alpha | 2021年6月10日| 采集饮食字典的数据。
1.0.5 alpha | 2021年6月11日| 清洗饮食字典的数据。
1.0.6 alpha | 2021年6月14日| 采集健康、电脑网络、数理化字典的数据。
1.0.7 bata |  2021年6月15日| 测试双词库搜索。
1.0.8 alpha| 2021年6月18日| 测试多词库检索!
1.0.10 alpha|2021年6月23日| 智能问答上线了！
1.1.0 beta| |2021年7月2日| 周周看开发中!
1.2.0 alpha|2021年7月6日|同学录上线了！
1.2.60 beta|2021年7月10日|明星游戏上线！
1.2.79 alpha | 2021年7月14日|测试私人书柜
1.2.8 beta | 2021年7月15日|上线扫码加书！
1.3.0 alpha| 2021年7月19|卡包体验版发布！
1.3.5787 alpha|2021年8月18日|课程搭配开发中！


## 联系我 ##

作者目前只是一个大学生，目前可能无法投入足够时间开发，爱好人士可协助本人开发！

由于某些原因，本人暂不接受捐助，但在第一可用版本发布后，会邀请人对小程序管理。

电邮地址: [dfzympj@qq.com](mailto:dfzympj@qq.com)

QQ: 1821628025  微信号: DFZYMPJ

官方论坛:[Goddess Forum](http://thegoddessforum.com)
