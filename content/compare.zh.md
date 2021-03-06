+++
title = "价格比较"
description = "和同类产品的价格比较"
keywords = ["价格","比较","Google Photo","iCloud", "Amazon Photo", "NAS", "Synology", "QNAP", "ibi", "Monument", "Kwilt3", "群晖", "威联通"]
+++

# 价格比较

**下面的比较主要考虑的是每个产品的最大卖点，并假设用户的主要需求是照片的备份和管理，如果您需要的功能超出那个范围，您可能需要考虑一下直接用NAS，或者如果您是专家可以使用树莓派或其他的单板计算机DIY一个。**

比如，云服务主要按不同的存储空间容量大小来定价，其他的一些功能则没有差别；而对于那些放置在自家的硬件产品，价格的差别主要在于硬件的配置，同一厂商的不同型号软件功能没有太大差异。在所有的功能中，备份是最基础的功能，其他的高级功能都是构建在这个基础上的。

Lomorage相比而言更加经济实用，也更加灵活，软件免费，如果您使用Windows或Mac电脑，也就无需另外购置额外的硬件，但如果想更好但利用改系统，将其作为一个7x24小时的私有云，您可以选择树莓派。即便是购买树莓派，也比市面上的方案更加经济实用。软件方面有些高级功能现在还在开发中，但基本的存储备份功能安全稳定，没有任何隐形费用，没有任何用户锁定，不泄漏隐私，为什么不试试呢？

## 和云服务的比较

下面的按**年费**来比较,  下面的表格的空单元格表示没有对应的选项。比如Apple iCloud只提供了5 GB, 50 GB, 200 GB and 2 TB的选项, 对Lomorage而言，现在比较难买到新的硬盘是小于500G的。Lomorage的基础功能都是免费的，所以下面的价格主要是考虑的硬件，和硬件的损耗，还有电费。

{{<table "table table-striped table-bordered">}}
|        | Lomorage | Apple iCloud |   Google Photo   | Amazon Photo | OneDrive  |  百度云    |
| -----: | -------- | ------------ | ---------------- | ------------ | --------- | --------- |
|   5 GB |          | 免费          |                  | 免费         | 免费       |           |
|  15 GB |          |              | 免费             |              |            |           |
|  50 GB |          | ¥ 72         |                  |              |           |           |
| 100 GB |          |              | ¥ 141.82         | ¥ 141.82     |           |           |
| 200 GB |          | ¥ 252        | ¥ 212.76         |              |           |           |
| 500 GB | ¥ 307    |              |                  |              |           |           |
|   1 TB | ¥ 332    |              |                  | ¥ 425.59     | ¥ 398     |           |
|   2 TB | ¥ 391    | ¥ 816        | ¥ 709.36         | ¥ 851.17     |           |   免费     |
|   3 TB | ¥ 481    |              |                  | ¥ 1276.76    |           |  ¥ 119    |
|   4 TB | ¥ 522    |              |                  | ¥ 1702.35    |           |  ¥ 249    |
|   5 TB |          |              |                  | ¥ 1702.35    |           |  ¥ 260    |
|   6 TB | ¥ 805    |              |                  | ¥ 2553.52    | ¥ 498 (1 TB/人) | ¥ 379    |
|   8 TB | ¥ 877    |              |                  | ¥ 3404.70    |           |  ¥ 498     |
{{</table>}}

因为Lomorage用户使用自己的硬盘，根据[研究报告](https://www.prosofteng.com/blog/how-long-do-hard-drives-last), 

> 通常来讲，硬盘的使用寿命是3-5年。在线备份公司BackBlaze分析他们运行的25,000个运行的硬盘的失败率得出的[结论](https://www.backblaze.com/blog/how-long-do-disk-drives-last/)。他们发现90%的硬盘都能用到3年以上，80%的硬盘都能用到4年以上。但这个和不同品牌有些关系，西部数据和日立的硬盘寿命比希捷的就长不少。

**在线备份的硬盘使用率相对比较高，一般硬盘都会超过4年的使用寿命。**下面已4年作为硬盘的使用寿命来计算，那需要至少**两块硬盘来做冗余备份**，那存储的价格就是`硬盘价格 * 2 / 4`, 树莓派通常可以用[10年以上](https://www.raspberrypi.org/forums/viewtopic.php?t=2856), 那假设像个人电脑一样每4年更新换代一次, 加上外接的供电USB分线器，设备的费用总的有`(硬盘价格 * 2 + 树莓派套装 + 供电USB分线器) / 4`,  加上每年的[¥30电费](https://www.v2ex.com/t/279166)，算下来总的费用`(硬盘价格 * 2 + 树莓派套装 + 供电USB分线器) / 4  + 30` per year.

[树莓派基础套装](https://detail.tmall.com/item.htm?spm=a230r.1.14.6.2f5f261eeGhB9s&id=601506908618&cm_id=140105335569ed55e27b&abbucket=2&skuId=4379917402113):

- 树莓派4B/2G主板
- 外壳
- USB-C电源
- 16 GB microSD Card
- 散热片
- micro HDMI线

供电USB分线器:

- [绿联usb分线器带电源供电](https://detail.tmall.com/item.htm?id=562288776006&ali_refid=a3_430620_1006:1151650521:N:aiqAvS76BytC0lZdUjIxdVOFAYSqPokT:713f58932d42a12bf6bd56654385f5fc&ali_trackid=1_713f58932d42a12bf6bd56654385f5fc&spm=a230r.1.14.1&skuId=3532332232228)

USB移动硬盘价格以支持USB 3.0接口，2.5寸的知名品牌[西部数据](https://item.jd.com/11620454466.html#crumb-wrap)价格为参考。

{{<table "table table-striped table-bordered">}}
| 单个磁盘空间   | 磁盘价格 (单盘) | 树莓派基础套装 | 供电USB分线器 | 均摊年费（按4年算） | 设备总费用 (双盘双备份) |
| ------ | ----------- | -------------------------- | ------- | ---------- | --------------------- |
| 500 GB | ¥ 299       | ¥ 383                      | ¥ 128   | ¥ 307      | ¥ 1109              |
| 1 TB   | ¥ 349       | ¥ 383                      | ¥ 128   | ¥ 332      | ¥ 1209              |
| 2 TB   | ¥ 468       | ¥ 383                      | ¥ 128   | ¥ 391      | ¥ 1447              |
| 3 TB   | ¥ 648       | ¥ 383                      | ¥ 128   | ¥ 481      | ¥ 1807              |
| 4 TB   | ¥ 729       | ¥ 383                      | ¥ 128   | ¥ 522      | ¥ 1969              |
| 6 TB   | ¥ 648 x 2   | ¥ 383                      | ¥ 128   | ¥ 805      | ¥ 3103              |
| 8 TB   | ¥ 720 x 2   | ¥ 383                      | ¥ 128   | ¥ 877      | ¥ 3391              |
{{</table>}}

## 和其他硬件产品的比较

当然将仅仅专注做照片视频备份管理的硬件和具备各种功能的NAS比较不是那么公平，但如果您需要的仅仅是照片视频备份管理，如果专有设备能做的更好，为什么要去买NAS呢？

{{<table "table table-striped table-bordered">}}
|                                       | 双盘位无盘 | 双盘位 4 TB | 单盘位 1TB |
| ------------------------------------- | ----------------- | ------------ | ----------- |
| Lomorage                              | (树莓派基础套装 + 供电USB分线器)<br /><br />¥ 511 | (树莓派基础套装 + 供电USB分线器 + 2个2TB硬盘)<br /><br /> ¥ 1447 | (树莓派基础套装 + 1个1TB硬盘)<br /><br /> ¥ 732 |
| 群晖 DS218+ | ¥ 2750          |  |             |
| 威联通 TS-231P2        | ¥ 2599             |              |             |
| My Cloud Home Duo                     |                   | ¥ 2799      |             |
| ibi - The Smart Photo Manager         |                   |              | ¥ 851.11  |
| Monument Photo Management Device      | ¥ 1205.42         |              |             |
| Kwilt3 Personal Cloud Storage Device  | ¥ 702.23          |              |             |
| 猫盘1TB         |                   |              | ¥ 599  |

{{</table>}}