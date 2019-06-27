# Growth-kingdom
 Contract: 0x466ecbf785165f2b5e2d5c1c49a80eb17fd36c3a
gkd 3.0（正在开发中）：智能经济的分布式网络
gkd使用数字身份和区块链技术对资产进行数字化，并利用智能合约实现自主管理的数字资产，从而在分散的网络中创建“智能经济”。



gkd 2.x：参考模板
gkd采用持续改进和发展的模式。我们相信，区块链技术的研究和开发将在未来几年保持持续转型。从2017年到2020年中期（估计），gkd 2.x仍将得到支持，新包装的兼容性将得以保持。

可以在下面看到指向基本C＃参考实现的链接：

gkd：核心实施（分支机构master-2.x）
gkd-vm：虚拟机（分支机构master-2.x）
gkd-cli：命令行界面（分支master-2.x）
gkd-plugins：插件（分支master-2.x）
gkd-devpack-dotnet：用于.NET的gkdContract编译器和开发包（分支master-2.x）
gkd 1.x被称为Antshares，代码的根源可以在当前的存储库中找到。

支持的平台
我们已经支持以下平台：

CentOS 7
搬运工人
macOS 10 +
红帽企业Linux 7.0 +
Ubuntu 14.04，Ubuntu 14.10，Ubuntu 15.04，Ubuntu 15.10，Ubuntu 16.04，Ubuntu 16.10
Windows 7 SP1 +，Windows Server 2008 R2 +
我们将来会支持以下平台：

Debian的
Fedora的
FreeBSD的
Linux Mint
OpenSUSE系统
Oracle Linux
发展
要在Windows上开始为gkd构建对等应用程序，您需要下载Visual Studio 2017，安装.NET Framework 4.7 Developer Pack和.NET Core SDK。

如果您需要在Linux或macOS上进行开发，只需安装.NET Core SDK即可。

要将gkd SDK安装到项目中，请在程序包管理器控制台中运行以下命令：

PM> Install-Package gkd


应该与您的应用程序一起使用，除非您希望夜间程序包可能开始为计算机上的其他应用程序恢复。

如何贡献
您可以通过问题和PR为gkd做出贡献。简单地为您遇到的问题提交问题是一种很好的贡献方式。非常感谢贡献实施。

我们使用并推荐以下工作流程：

为您的工作创建一个问题。
您可以跳过此步骤进行微不足道的更改。
如果有主题，请重复使用该主题的现有问题。
如果是这种情况，请清楚地说明您将继续实施它。您可以请求将问题分配给您。注意：问题文件管理器和实现者不必是同一个人。
在GitHub上创建存储库的个人分支（如果您还没有）。
从master（git checkout -b mybranch）创建一个分支。
命名分支，以便清楚地传达您的意图，例如issue-123或githubhandle-issue。
分支很有用，因为它们将您的更改与上游的传入更改隔离开来。它们还允许您从同一个fork创建多个PR。
制作并提交您的更改。
添加与您的更改相对应的新测试（如果适用）。
使用您的更改构建存储库。
确保构建是干净的。
确保测试全部通过，包括新测试。
针对上游存储库的主分支创建拉取请求（PR）。
在GitHub上将更改推送到fork。
注意：您的PR可以包含大量提交。一旦您的更改被接受，您将被要求在合并PR之前将您的提交压缩为一个或一些适当数量的提交。

执照
gkd项目根据MIT许可证获得许可。
