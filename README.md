---
title: obsidian安装和使用说明
date: 2022-03-13 09:57:43
---

# obsidian_vault_template_for_researcher

### 写在前面

从接触到使用 obsidian 已经有一段时间了，感觉这个工具用好了应该对搞科研有较大帮助。软件界面如下：

![obsidian界面概览](https://sheldon-notes.oss-cn-shanghai.aliyuncs.com/img/image-20211120145712338.png)

- 2022年3月13日：使用了obsidian大半年之后，还是觉得很好用。但这并不是因为它的花里胡哨的「关系图谱」或者其它非常fancy的一些插件和主题效果，而是因为自己**一直在写养成了习惯**。目前使用频率最高的仍然是结合 zotero 写「文献阅读笔记」和「写日志」。在使用过程中，发现各种碎片信息需要定期整合并输出，然后**分享有用的东西给别人**。只有这样积累资料和笔记才不至于陷入「囤积症」的窘境。为了完善「收集（草稿）→整理（小结）→输出（发布）」的闭环，我完善了更为丰富的自定义笔记导出功能。


### 下载并打开vault模板库并查看说明书

1. 下载安装软件：目前 obsidian 是开源免费的跨平台软件，可以直接到[官网](https://obsidian.md/download)下载安装包后安装。

2. 下载了vault模板之后，解压到一个指定位置，可以是电脑上的硬盘，也可以是移动硬盘甚至U盘，然后重命名vault。比如我把 vault 命名为 working，然后放到了移动硬盘的 projects 目录下：`X:\projects\working`。

3. 打开该模板库，注意关闭「安全模式」，关闭obsidian最新版提供的「实时预览」功能，进入到模板库中可查看 `03-Projects` 中的「黑曜石玩家指南」project，里边有非常完整的关于 `写日志`，`读文献`和`做课题项目`的工作流程操作说明。



### 更新日志

#### 2022年3月31日（v1.4）

- 通过新版obsidian实时阅览模式兼容性测试，增加和删除了部分插件。
- 增加 front-matter 中 destination 对于 shortlink 的支持，参考[[obsidian撰写草稿#front-matter]]。
- 增加[[相册模板]]，可用于个人收藏重要的照片于`05-Life/01-Album`目录下，具体操作可参考[[obsidian新建个人相片集]]。
- 按照`写日志`，`读文献`和`做课题`的三大 workflow对quickAdd命令进行了分组。
- 修改了导出项目未包含02-Reading目录的bug。
- 大致回顾梳理了《黑曜石玩家指南》并作小幅度的修改。

#### 2022年3月29日（v1.3）

**重要提示**：此版本对文件目录做出了重大调整，使用之前版本的用户不能直接通过复制粘贴到现有库的方式实现升级，建议先了解模板库中的教程再进行操作。

- 完善了`写日志`，`读文献`和`做课题项目`的三大 workflow所需的相关功能
- 撰写了详细的使用教程《黑曜石玩家指南》并内置库中。


#### 2022年3月13日（v1.2）

- 增加笔记自定义导出为word和html的功能（带参考文献，以及嵌入多媒体），方便分享
- 修改更新 readme 文档关于【自定义导出】和【升级】的内容
- 调整了[[阅读清单]]的说明和query和文献阅读笔记模板[[Mdnotes Default Template]]

### 注意事项

1. 由于对部分插件主题做了源代码级别的修改，请不要自行升级此模板库内的插件和主题，以免相关配置丢失（此类情况在更新 templater、dataview 等插件时容易遇见）。


### 黑曜石玩家指南书籍目录

**序言** 

1. [[决定写obsidan教程]]
2. [[一鼓作气之后]]
3. [[结束这场战斗吧]]

**第一章-obsidian入门** 

1. [[软件下载安装]]
2. [[zotero-obsidian联动配置]]
3. [[开箱写日志]]
4. [[obsidian撰写草稿]]
5. [[使用手机撰写日志]]
6. [[每周定期汇总小结]]
7. [[在obsidian中写幻灯片]]
8. [[本章小结-恭喜入门obsidian]]

**第二章-obsidian读文献**

1. [[当期文献速览]] 
2. [[入库文献泛读]] 
3. [[进一步阅读原文]] 
4. [[解析文章骨架]] 
5. [[重要综述如何阅读]] 
6. [[阶段性文献阅读小结]] 
7. [[主题阅读与比较阅读]] 
8. [[跟踪领域内大牛]] 
9. [[本章小结-恭喜习得内功]]

**第三章-obsidian做课题**

1. [[新建课题项目]] 
2. [[规范的实验记录]] 
3. [[整理实验方法]] 
4. [[试剂耗材仪器建卡管理]] 
5. [[工作小结与周汇报]] 
6.  [[撰写论文草稿]] 
7.  [[完整导出项目]]
8.  [[本章小结-祝您科研精进]]

**附录**

1. [[obsidian快捷键]]
2. [[obsidian第三方插件列表]]
3. [[obsidian主题界面布局说明]]
4. [[obsidian新建个人相片集]]