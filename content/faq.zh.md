+++
title = "常见问题"
description = "常见问题"
keywords = ["FAQ","疑问","反馈","用户"]
+++

* [1. 为什么不用云服务?](#1-为什么不用云服务)
* [2. NAS怎么样?](#2-nas怎么样)
* [3. 其他选择呢?](#3-其他选择呢)
* [4. 为什么要做Lomorage?](#4-为什么要做lomorage)
* [5. 价格](#5-价格)
* [6. 怎么想到"Lomorage"这个名字?](#6-怎么想到lomorage这个名字)
* [7. 你们的商业模式是什么?](#7-你们的商业模式是什么)
* [8. 如何设置冗余备份?](#8-如何设置冗余备份)
* [9. 支持那些文件系统?](#9-支持那些文件系统)
* [10. 为什么时间看起来不对?](#10-为什么时间看起来不对)
* [11. 如何设置冗余备份?](#11-如何设置冗余备份)
* [12. 编辑后的照片视频支持吗?](#12-编辑后的照片视频支持吗)
* [13. 什么是后台备份?](#13-什么是后台备份)

## 1. 为什么不用云服务?

我们认为数字资产的管理需要保存在本地，在本地做好备份，而云端的存储只是本地存储的一个补充，现有的云存储成本过高，国内的云存储厂商相继[停止运营](https://www.ifanr.com/app/654706):

 - 115 网盘：2016 年 3 月 4 日下线「我聊」中的「文件发送」功能，后续一直在调整。
 - 新浪微盘：2016 年 6 月 30 日开始关闭免费个人用户的存储服务。
 - 华为网盘：2016 年 6 月 30 日开始关闭。
 - 迅雷 / 金山快盘：停止快盘个人用户的存储服务，数据保留到 2016 年 6 月 30 日。
 - 360 云盘：2016 年 11 月起停止个人云盘服务，2017 年 2 月 1 日起关闭所有云盘账号并清空数据。
 - UC 云盘：2016 年 4 月 15 日开始终止网盘的存储服务，停止上传服务 / 离线资源存至网盘功能 / 视频转码服务。

 国内外的照片存储服务也相继关停:

 - [网易相册突然关停清空数据 网友照片丢失愤怒投诉：还我回忆](https://new.qq.com/omn/20190601/20190601A0N2RQ.html)
 - [Dropbox关闭备份照片应用 尝试吸引新用户失败](http://www.fromgeek.com/news/33101.html)
 - [佳能关闭Irista平台](https://camerajabber.com/canon-irista-closing-date-january-2020/)
 - [佳能公司将正式停止irista服务](https://chinese.aljazeera.net/technology/2019/11/20/free-cloud-storage-services-involve-risk-data-loss)
 
 云存储的运营成本之高，Flickr母公司SmugMug在[公开信](https://www.ifanr.com/1293604)中提到Flicker一直都在亏损，希望用户能够接受价格上涨。

 云存储的优势是使用方便，无需购买硬件，有专人来负责维护，7x24小时服务都可以用，也无需担心电费。但科技在进步，SBC单板计算机变得越来越便宜，性能越来越强大，能耗也越来越低，存储空间也越来越便宜，容量越来越大，软件也越来越智能，人们也开始更多的关心隐私了，是时候可以在自己家里运行“私有云服务”了。

## 2. NAS怎么样?

[NAS](https://baike.baidu.com/item/NAS/3465615)是一种通用的存储，您可以通过网络存储任何资料，包括照片和视频。尽管NAS试图将其操作界面做的更加简单，但其面向专业的特性导致很难将其简化。看看操作易用性最好的群晖NAS的[说明书](https://global.download.synology.com/download/Document/Software/UserGuide/Firmware/DSM/3.1/chs/Syno_UsersGuide_NAServer_chs.pdf)，您就知道，NAS对于照片视频的存储管理备份是杀鸡用牛刀，[简单的NAS不简单](https://sspai.com/post/55785)。

## 3. 其他选择呢?

也有将NAS功能简化，侧重做照片视频垂直领域的，这块国外市场的产品选择多点，国内的猫盘也算吧。

  - [猫盘](http://www.maopan.io/)
  - [ibi](https://www.amazon.com/ibi-Organize-Privately-Smartphones-Accounts/dp/B07Y9CH817/ref=cm_cr_arp_d_product_top?ie=UTF8)
  - [Monument](https://www.amazon.com/Monument-Photo-Management-Device-Automatically/dp/B01M8I40A6/ref=sr_1_3?dchild=1&keywords=ibi&qid=1588828193&sr=8-3)
  - [Kwilt3](https://www.amazon.com/Kwilt3-Personal-External-Storage-Wireless/dp/B07KQHVMJX/ref=psdc_13436301_t3_B01M8I40A6?th=1)

## 4. 为什么要做Lomorage?

我们对现有的解决方案不满意。

1. 云端存储应该作为本地备份的补充，本地需要至少一个主备和从备。
   - 我们当前支持本地冗余备份。
   - 我们机会支持远程备份（比如使用你父母家里的Lomorage存储，来远程备份）和专业的云端存储备份，比如[backblaze](https://www.backblaze.com/)。

2. 安装简单，易于使用，自动升级，零成本维护。
   - 只需要几分钟就能在树莓派上安装定制的系统镜像。
   - 支持Windows和MacOS系统。
   - 系统自动升级。

3. 软件很重要，备份管理这些珍贵的照片视频，需要非常稳定可靠的系统。
   - 我们开发者自己就是用户。
   - 我们产品的发布是按质量，而不是按时间。

4. 系统必须开放，不要对用户做任何形式的绑定，即便后续停止开发，不要给用户太多的迁移成本，用户的硬件也不至于变成电子垃圾。
   - 媒体文件按原始格式，原始尺寸存储在您的磁盘上，不丢失任何信息。
   - 无需格式化硬盘，任何闲置硬盘即插即用，支持所有常见的文件系统。
   - 媒体文件按照"YYYY/MM/DD"的日期文件格式存储在您的磁盘上，您可以很方便的将其导入到其他的系统中。
   - 如果使用树莓派，即便您不用Lomorage，它还是一个单板计算机，您可以用它做其他的[用途](https://projects.raspberrypi.org/zh-CN/projects)。

5. 除了照片的备份和管理之外，和家人一起分享美好回忆。
   - 有多少次你打开手机翻看老照片？
   - 家里堆了很多相框，找不到地方摆放？
   - 闲置在家的数码相框不想用，上传太麻烦，空间有限制？
   - 想拥有一个大的画屏放客厅，显示日期时间，艺术作品和照片？想在卧室或者书房有个小数码相框摆在桌上？无需上传，突破空间限制，WiFi连接Lomorage存储。
   - 重新利用任何空闲的屏幕，连接树莓派，搭建数码相框，通过手机来定制要显示的内容。
   - 远程将照片或视频推送到数码相框，和爷爷奶奶一起分享小孩的成长历程。

6. 独立系统并能互联互通。
   - 您可以在自己家里安装一套Lomorage系统，同时也能在父母家安装一套，两个相互独立，但也能够互相通信，互相共享存储，加密备份。

## 5. 价格

Lomorage是一个经济实用，更加灵活的解决方案，软件免费，如果您使用Windows或Mac电脑，也就无需另外购置额外的硬件，但如果想更好但利用改系统，将其作为一个7x24小时的私有云，您可以选择树莓派。即便是购买树莓派，也比市面上的方案更加经济实用。软件方面有些高级功能现在还在开发中，但基本的存储备份功能安全稳定，没有任何隐形费用，没有任何用户锁定，不泄漏隐私，为什么不试试呢？

查看[这里](/zh/compare)查看和云服务, NAS，还有其他方案的对比。

## 6. 怎么想到"Lomorage"这个名字?

"Lomorage"结合了"Lomography"和"Storage"两个单词.

## 7. 你们的商业模式是什么?

这个是一个业余的项目，做这个项目最开始的出发点是想为自己家庭的照片存储管理寻找一个更好的解决方案，家里有了小孩之后照片和视频的量爆涨，在使用过一些现有的产品后，我们想要有更好的方案，更加简单易用，更加稳定，经济实用，涵盖照片视频的备份，管理，分享和展示的一套完整方案。这一切的出发点是我们对家庭的热爱，使得我们对这个事情的投入也充满热情，我们已经业余时间做了快两年了，即便是现在没有人付钱，我们也会坚持做下去。

当前我们的投入除了时间成本外，其他的资金投入并不多，主要是apple开发者账号，域名，我们不用提供存储空间，不用提供设备，使用github来免费托管主页和提供下载链接，所以将这套系统免费提供使用对我们而言并没有太大的经济负担。

但终究所有的投入都是有成本的，需要资金的投入来让其可持续下去。我们很希望能够全职来做这个事情，更快的能开交付新功能，但当前我们还不能做到这点。如果人们觉得这个产品对他们有用，并且愿意付费，那我们会很开心，但当前的产品还是在早期阶段，只有基本的备份和分享功能，更好的方式是将其作为一个免费软件来提供大家使用。我们也不会走互联网软件的模式，将用户作为产品的一部分，我们从一开始就关心用户隐私，因为我们自己也是用户。

Peter Thiel说过: "要创建一家成功的初创公司，你的产品需要比同类产品好10倍” ，我们也相信：如果要用户买单，必须先提供有足够价值的东西。

我们计划推出更多高级的功能（比如智能搜索，远程备份，数码相框等），看看是否能提供一些用户愿意付费高级功能。数码相框本质上是一个家用屏幕，可以有放在客厅的大尺寸画屏，也可以有放在桌上的摆台，现有的数码相框没多少人用，是因为不好用，而不是因为不需要，这里面也存在很多的可能性探索出些商业模式。

## 8. 如何设置冗余备份?

如果您是在macOS上运行Lomorage服务（Windows暂时还没有支持），您可以打开LomoAgent应用程序的设置窗口，设置冗余备份。

如果您是在树莓派上运行Lomorage服务，插入新的硬盘后，打开iOS手机客户端，在设置选项卡里可以设置冗余备份。

## 9. 支持那些文件系统?

如果您在macOS或者Windows上运行Lomorage服务，您可以使用任何Windows或者macOS操作系统原生支持的文件系统。

如果您是在树莓派上运行Lomorage服务，你可以使用更多的文件系统，包括:"vfat exfat ext2 ext3 ext4 hfsplus ntfs fuseblk"。

## 10. 为什么时间看起来不对?

在系统中使用[UTC时间](https://baike.baidu.com/item/%E5%8D%8F%E8%B0%83%E4%B8%96%E7%95%8C%E6%97%B6)来存储而不是本地时间，原因是照片可能拍摄于不同的时区，用户也会离开原先的住处搬迁到另外的时区，使用UTC时间戳能简化处理，而且可以很容易的在客户端应用程序转化为本地时间。

## 11. 如何设置冗余备份?

冗余备份的方案有几种, 查看这篇[博客](/zh/blog/2019/12/24/raspberrypi-hd/)获取更多详细信息。

## 12. 编辑后的照片视频支持吗?

苹果系统中，图片编辑后，系统会存储原始文件，编辑后的文件和修改操作记录，**Lomorage只会存储编辑后的照片**。视频编辑会记录上次编辑前的视频文件，上次编辑的操作记录，**Lomorage也只会存储编辑后的视频**。

**如果您想存储编辑之前的照片或视频，再确保编辑后的视频已经备份成功后，到系统的照片应用中，撤销编辑，再上传编辑前的文件**。

注意: 老的版本iOS客户端(<0.6.10)没有支持上传编辑后的文件，如果您碰到编辑后的文件上传失败，请删除老版本的程序，再重新安装，而不要选择直接升级，这样会保证清理掉之前有问题的老数据库。

## 13. 什么是后台备份?

开启后台备份后，无需打开Lomorage APP就可以备份照片视频。

但是由于苹果平台的限制，第三方应用并不能像iCloud那样做到一直在后台备份，只能通过一些hack的方式，现在是通过两种方式来触发应用在后台运行，一种是在系统空闲时，通过后台获更新的机制来触发应用后台运行，另一种是通过地理位置的大范围的变化来触发应用后台运行，所以开启后台备份功能后会请求获取地理位置的权限，这些都只能持续很短的时间。

当手机操作讲Lomorage APP放后台后，原有的上传还是会继续，只是下次个文件上传需要等到下一次将Lomorage APP切换到前台，或者通过上述的两种Hack的方式让APP在后台继续运行。

---

> 如果您有更多的问题没有在这里找到答案，请[联系我们](/zh/contact)
