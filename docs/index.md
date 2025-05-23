---
icon: material/hand-wave-outline
---

# 欢迎

!!! success "本文已完稿并通过审阅，是正式版本。"

各位读者们，欢迎阅读《Linux 101》在线讲义（以下统称“本书”）。本书由中国科学技术大学 Linux 用户协会的数名优秀成员协力编写，用于配套和延展“Linux 101”校内社团活动。其面向 Linux 零基础读者，从计算机操作系统和 Linux 的起源讲起，深入浅出带领读者一步步逐渐掌握最必要的 Linux 实用知识，并在其中感悟到社区开源文化的魅力。本书旨在成为一份为有志探索和钻研 Linux 这片大陆的开拓者们准备的路引，若潜心研读则必有所获，现在就开始你的旅程吧。

**在开始之前，强烈建议先仔细研读一遍阅读指南。**

## 阅读指南 {#guidelines}

### 范围与目的 {#coverage-and-aim}

本书是一份 Linux 的基础教程，目标是引导不了解 Linux 的读者掌握基础且实用的知识并领略社区开源文化的魅力。若仔细研读完本书，你就能：

-   了解 Linux 历史和开源社区文化
-   安装 Linux 发行版并利用内置实用手册
-   在体验中亲自感受 Linux 的专业能力
-   自如地操作与配置你的 Linux 系统
-   理解 Linux 操作系统的思想
-   使用 Linux 生态高效编程开发
-   以及灵活运用其它 Linux 生态中十分流行的各类工具等等

对于偏向实用需求的计算机开发或学术研究的读者，通过阅读本书可以快速掌握高效且流行的业界开发和学界研究的工具；对于基于兴趣和探索新事物的目的而前来阅读的读者，本书则能为他们提供一个更广阔的 Linux 世界的面貌和一份快速入门的助力。

### 结构安排 {#structure}

本书包括前言、正文及附录。正文共包括 9 章，每章的内容如下：

-   第 1 章主要讲述了 Linux 的文化和生态，并提供了安装流程。
-   第 2 章提供了一个自定义 Linux 系统和利用其设立自己专属服务器的体验指南，这一部分应配合课堂分发的工具包和虚拟机使用。
-   第 3 章简单提供了基本的软件安装和文件操作知识。
-   第 4 章全面介绍了系统的进程、服务和任务，是一块丰富的核心内容，读者应反复阅读。
-   第 5 章讲解了用户和用户组、文件权限以及文件系统层次结构等系统管理员必知的文件管理核心知识。
-   第 6 章提供了网络、文本处理和脚本编程的知识，让读者能利用脚本的力量完成综合任务。
-   第 7 章简单展示了十分流行的在 Linux 环境下进行 C++ / Python 开发的方法。
-   第 8 章介绍了近年来业界十分热门的容器隔离技术和 Docker 容器管理软件。
-   第 9 章为利用脚本编程进行了进阶的说明，包括十分关键的正则表达式。

附录包括用语表和若干追加主题。其中，用语表包含了阅读全书中遇到的专业术语和用语的详细解释；每篇追加主题则包括诸多与本书极为相关的额外知识并已经进行了系统化的组织，提升读者的求知体验。

### 自主阅读与拓展阅读 {#self-reading}

在每一章的正文中，标有 \* 的段落都是自主阅读的部分。自主阅读的部分不会在配套的 Linux 101 活动的授课中提及，但通常也是有趣和重要的内容，推荐读者自行阅读。

每一章除了正文之外，还会有一篇拓展阅读专页，其与正文平级。每一章的拓展阅读专页记录了若干个与本章主题息息相关的额外知识，它通常都是正文中所提到的知识点的拓展和延申，供感兴趣和有需要的读者参阅。这些拓展阅读的编写并不完全依据本书大纲的知识结构的顺序，因此可能需要后续章节甚至是外部知识作为前置才能阅读。如果遇到这种情况，本书会在对应拓展阅读节的开头标注出所需的额外前置知识。

### 思考题 {#thinking-question}

在每一章的正文的最后，通常都会有若干道思考题。其中的一部分题目用于对本章所学内容的回顾和巩固，另一部分题目则鼓励读者通过利用互联网渠道自主寻找答案。建议读者在阅读完一章的正文后立刻尝试回答这些思考题，这么做可以有助于读者快速提升计算机的技术素养。

### 其它资料 {#extras}

-   [记号约定](notations.md)中约定了本书中常用的符号与注记形式。在研读本书的过程中可随时参考。
-   [功劳簿](credits.md)列出了所有为编写本书做出贡献的朋友们。
-   Linux 101 活动于 2020 年的直播记录视频可以在 [LUG FTP](https://ftp.lug.ustc.edu.cn/101/videos) 找到，也可以在 [YouTube](https://www.youtube.com/playlist?list=PLkqsPhn1XtD2h_o5-lY3exDRXtKBiKwkk) 上在线观看。
-   对于服务器运维等较为深入的应用场景，我们另外启动了《[Linux 201](https://201.ustclug.org/)》项目，作为本书的进阶版，可供感兴趣的读者参考。

## 联系我们 {#contact-us}

本书的成长离不开大家的帮助。本书的源代码存放在 [:fontawesome-brands-github: Linux101-docs 仓库](https://github.com/ustclug/Linux101-docs) 中，所有内容以 [:fontawesome-brands-creative-commons: CC BY-SA 4.0 协议](https://creativecommons.org/licenses/by-sa/4.0/)开放。

若您对本书有任何意见或建议，可以在本书的 GitHub 仓库中提出 Issue，也欢迎致信 ![我们](https://lug.ustc.edu.cn/static/email.png){: .img-inline }，我们重视您的想法。
