# 维格小程序 - 字符串的查找替换

选择一列，对符合查找条件的内容进行批量替换



## **🎨 功能介绍**

本小程序可以根据关键字，查找当前视图下所选列中的内容，并替换成想要的文本

例如：研发人员小明用维格表管理产品内展示的文案，有一天，产品经理灵光一闪，并经产品内部评审后决定更名部分产品文案，并给小明下达了更新配置表的文案需求。小明看着数千条文案，陷入了抓狂状态，但为了完成任务，只好查找关键字后再一个个改...

> 注意：本小程序是基于视图的文本查找替换，只会影响当前视图下的记录



## **🚀 快速上手（现成模板）**

为了让大家可以快速体验到这款小程序的用途，这里已经提前做好了一个维格表模板，包含两个例子，浏览器打开即可体验

> 体验地址：https://vika.cn/share/shr9mvdoxzSN5um0CGtns

使用方法非常简单，由于本小程序只对当前视图下的记录生效。

你需要先选择一个视图，筛选出你需要批量查找替换的记录

![img](https://vikadata.feishu.cn/space/api/box/stream/download/asynccode/?code=M2ZlOTk2ZjExNTcyYTZlY2MwZTU4ODU4M2ViN2U3N2RfdXhqTWgzSFlrRmRWaW9sVEdyQjB2cHh4dXVTMjhQSWRfVG9rZW46Ym94Y242VFFMZWFQMWlsdHo1Y1lBdjdCblliXzE2NDMwMTYzMTU6MTY0MzAxOTkxNV9WNA)

选择一列，输入要查找的关键字和替换文本

![img](https://vikadata.feishu.cn/space/api/box/stream/download/asynccode/?code=NjBiMzE4ZTJlNzkxZWQyZmQzNTAyZTkzMWQwNjhjYzZfeHFCTU90cTZvRXRCeVFYQ2FiYlh6elREWHVJNTJiZjdfVG9rZW46Ym94Y25uRU0yYWpnc2FSZWZHdHVhVUtsYUhnXzE2NDMwMTYzMTU6MTY0MzAxOTkxNV9WNA)

点击「预览」可以看到匹配的记录，方便你进行内容替换的确认

![img](https://vikadata.feishu.cn/space/api/box/stream/download/asynccode/?code=NjkzOTkzY2Y4MDRhMmNkZTY1NTZhY2IyMmYxZTE3OGRfeVRHZVRoMm5nbkJqWEhUeE1qMUdlbWNzZnYyek00SWVfVG9rZW46Ym94Y24wSUlWNWRDZ3U1WE11amZBSFlSVXNkXzE2NDMwMTYzMTU6MTY0MzAxOTkxNV9WNA)

 

点击「全部替换」将匹配记录更新为替换后的记录

![img](https://vikadata.feishu.cn/space/api/box/stream/download/asynccode/?code=NjI2ZWYxNWM2MjRlODRhNDQzYjg0N2RhZDYxYjhkNzJfWkQ1WWJoTHo4WHNMSVRQZDEwS0FXcUtRQ1M1YVpPeklfVG9rZW46Ym94Y25Zb0VURTVRR040c2tCWlc0N2FuSURoXzE2NDMwMTYzMTU6MTY0MzAxOTkxNV9WNA)





## **🙋‍♂️ 常见问题**

**1、目前支持哪些字段类型？**

目前支持单行文本、多行文本、网址、邮箱、电话的字段类型

**2、使用这个小程序会将该列所有匹配内容都替换掉吗？**

只会替换该视图下所选择列的匹配内容

**3、为什么我点击不了「全部替换」**

为了避免误触等造成原数据破坏，需要先对匹配结果进行确认，先点击「预览」，才可以点击「全部替换」哟～

**4、替换的数据如何恢复？**

点击表格左上方的撤回按钮，或者使用快捷键<kbd>Ctrl+Z</kbd>（Windows）、<kbd>Command+Z</kbd>（MacOS）均可进行撤回操作



## 🌈 动手党的天堂

如果你是一名编程人员或者是对开发维格小程序感兴趣的爱好者，欢迎访问GitHub的项目库，查找替换小程序的代码已经开源了哦~

👉 [Github：vikadata-widget-find-and-replace](https://github.com/Niko030303/vikadata-widget-find-and-replace)

如果你在开发小程序的过程中遇到阻碍，希望得到更多的帮助与启发，或者想要学习一下其他开发者的作品，欢迎访问维格官方的项目宝藏库：

👉 [Github：awesome-vikadata](https://github.com/vikadata/awesome-vikadata)

PS：如果你也有关于维格表小程序的项目开源，欢迎给我们提交PR，我们会将优秀作品收录到官方宝藏库，独乐乐不如众乐乐😍😍😍



## **🤟 建议与反馈**

如果你在使用过程中发现有缺陷，欢迎在下方评论，我们会尽量及时修复。

如果你对这个小程序有新的想法，也欢迎在下方留言，我们一起探讨改进~



## 🥂 讨论交流

在日常使用中或者二次开发过程中有疑问或者新想法，欢迎前往官方社区的小程序主页留言评论给我~

👉 [点我跳转「字符串查找替换」的主页](https://bbs.vika.cn/article/)



## 🎯 更新日志

v0.1.2 - 2022年1月20日

- 【调整】预览结果部分的UI优化，转为使用react-table渲染，增加分页功能
- 【新增】用户初次进入表格和未点击「预览」时，「全部替换」按钮置灰
- 【调整】字段下拉框调整为仅显示「单行文本、多行文本、网址、邮箱、电话」
- 【新增】字段下拉框新增搜索功能

v0.1.0 - 2021年12月13日

- 【初始化】发布首个版本，用户可以实现对单列（String）内容的批量查找替换

## 😍 更多有趣的维格小程序

如果你喜欢学习、折腾各种维格小程序，可以看看维格官方的宝藏库，里面收集有大量的小程序项目、vika API项目：

👉 [awesome-vikadata](https://github.com/vikadata/awesome-vikadata)

