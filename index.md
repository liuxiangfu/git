
# 1	什么是git
## 1.1 分布式版本控制系统
> Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency. 

Git(读音为/gɪt/。)是一个开源的分布式版本控制系统，可以有效、高速的处理从很小到非常大的项目版本管理。 

GIT不仅仅是个版本控制系统，它也是个内容管理系统(CMS),工作管理系统等。
## 1.2 git的特性
> Git is easy to learn and has a tiny footprint with lightning fast performance. It outclasses SCM tools like Subversion, CVS, Perforce, and ClearCase with features like cheap local branching, convenient staging areas, and multiple workflows. 

Git易于学习，占用空间小，具有闪电般的快速性能。它超越了SCM工具(如Subversion、CVS、Perforce和ClearCase)，具有廉价的本地分支、便捷的暂存区域和多个工作流等特性。

 

- **直接记录快照，而非差异比较**

Git 和其它版本控制系统（包括 Subversion 和近似工具）的主要差别在于 Git 对待数据的方法。 概念上来区分，其它大部分系统以文件变更列表的方式存储信息。 这类系统（CVS、Subversion、Perforce、Bazaar 等等）将它们保存的信息看作是一组基本文件和每个文件随时间逐步累积的差异。

- **近乎所有操作都是本地执行**

在 Git 中的绝大多数操作都只需要访问本地文件和资源，一般不需要来自网络上其它计算机的信息。 如果你习惯于所有操作都有网络延时开销的集中式版本控制系统，Git 在这方面会让你感到速度之神赐给了 Git 超凡的能量。 因为你在本地磁盘上就有项目的完整历史，所以大部分操作看起来瞬间完成。

- **Git 保证完整性**

Git 中所有数据在存储前都计算校验和，然后以校验和来引用。 这意味着不可能在 Git 不知情时更改任何文件内
容或目录内容。 这个功能建构在 Git 底层，是构成 Git 哲学不可或缺的部分。 若你在传送过程中丢失信息或损坏
文件，Git 就能发现。
Git 用以计算校验和的机制叫做 SHA-1 散列（hash，哈希）。 这是一个由 40 个十六进制字符（0-9 和 a-f）组
成字符串，基于 Git 中文件的内容或目录结构计算出来。 SHA-1 哈希看起来是这样：
`24b9da6552252987aa493b52f8696cd6d3b00373`

Git 中使用这种哈希值的情况很多，你将经常看到这种哈希值。 实际上，Git 数据库中保存的信息都是以文件内
容的哈希值来索引，而不是文件名。

- **Git 一般只添加数据**

你执行的 Git 操作，几乎只往 Git 数据库中增加数据。 很难让 Git 执行任何不可逆操作，或者让它以任何方式清除数据。 同别的 VCS 一样，未提交更新时有可能丢失或弄乱修改的内容；但是一旦你提交快照到 Git 中，就难以再丢失数据特别是如果你定期的推送数据库到其它仓库。
## 1.3 git的历史

# 2.git安装

# 3.git使用

# 4.svn迁移至git

# 参考资料
1.[Git权威指南 — GotGit  ](http://www.worldhello.net/gotgit/#git)

2.[Pro Git v2](https://git-scm.com/book/zh/v2)

