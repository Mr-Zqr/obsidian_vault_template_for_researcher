---
title: obsidian安装和使用说明，针对obsidian v1.4.5的适配
date: 2023-09-18
---
# 写在更前面

非常感谢项目的原作者sheldonxxd大佬创造了如此优秀的obsidian vault，这个vault极大的提升了我的科研效率和幸福指数。而随着obsidian的更新，原vault中的一些插件不再适配，导致了vault中一些功能的缺失。原作者在obsidian1.3.5的基础上更新了精简版，我在使用过精简版后发现原版的一些功能还是十分必要且高效的，例如月总结、任务看板等，虽然原版的学习曲线较精简版略陡，但熟练使用之后对科研大有裨益。

因此我在obsidian v1.4.5更新了原版所安装的所有插件和主题，并对已经失去维护或者有功能更新导致原vault功能出现bug的插件进行修改，保持原版vault在obsidian v1.4.5环境下工作正常，并利用原vault中的导出项目功能导出了这一模板。现在将这一vault分享至github，供有需要的朋友使用。

再次感谢原作者sheldonxxd，这个项目真的太牛了。

## 2023.9.23 更新
更新生成任务甘特图的代码，带进度条
原版甘特图：
![](08-Assets/Snipaste_2023-09-23_09-33-32.jpg)
新版甘特图：
![](08-Assets/Snipaste_2023-09-23_09-32-51.jpg)

下面是原仓库的readme：

# obsidian_vault_template_for_researcher

### 写在前面

**❗本项目已停止更新**，已基于最新版的obsidian(v1.3.5)重新打造面向研究生的极简obsidian模板库，感兴趣可移步新开的另一个👉repo:[obsidian_vault_template_for_graduate_student](https://github.com/sheldonxxd/obsidian_vault_template_for_graduate_student)。


### 下载并打开vault模板库并查看说明书

1. 下载安装软件：目前 obsidian 是开源免费的跨平台软件，建议[到代码仓库下载 v0.14.6 版本安装包](https://github.com/obsidianmd/obsidian-releases/releases/tag/v0.14.6)后安装（更新的版本可能存在兼容性问题）。安装后请关闭自动更新，后续也不要更新本库其它内置插件。如需回退obsidian版本，请参考[ issue 47](https://github.com/sheldonxxd/obsidian_vault_template_for_researcher/issues/47)。

2. 建议通过git clone下载此vault模板，之后解压到一个指定位置，可以是电脑上的硬盘，也可以是移动硬盘甚至U盘，然后重命名vault。比如我把 vault 命名为 working，然后放到了移动硬盘的 projects 目录下：`X:\projects\working`。

3. 打开该模板库，注意关闭「安全模式」，关闭「自动更新」，进入到模板库中可查看 `03-Projects` 中的「黑曜石玩家指南」project，里边有非常完整的关于 `写日志`，`读文献`和`做课题项目`的工作流程操作说明。


### 黑曜石玩家指南书籍目录

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

**第四章-补充内容**

1. [[obsidian快捷键]]
2. [[obsidian第三方插件列表]]
3. [[obsidian模板库更新方法]]
4. [[python代码说明与调试方法]]
5. [[更新日志]]
6. [[结束语]]
