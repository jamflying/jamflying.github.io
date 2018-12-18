---
layout: post
title:  "Maidenhead Locator System"
date:   2018-06-06 23:35:01 +0000
categories:
  - Amateur-Radio
tags:
  - ham
  - grid
  - QTH
---

梅登黑德（Maidenhead）是一个位于英国伯克郡的镇和非教区地，处在泰晤士河南岸，距离查令十字以西25.7英里（41.4千米）。

1980年4月VHF工作组在这里开了一次会，决定使用 Dr. John Morris G4ANB 的网格定位法来取代之前的QRA定位法。这就是梅登黑德网格。
1999年IARU决定，该方法的经纬度坐标应严格遵循WGS 84地心坐标。

网格定位的字符表示格式如下：

![梅登黑德网格](https://upload.wikimedia.org/wikipedia/commons/thumb/d/de/Maidenhead_Locator_System_explained.svg/640px-Maidenhead_Locator_System_explained.svg.png)

梅登黑德网格的分割方式：
* 每两个字符一对儿，经度在前、纬度在后。
* 第一对，Field，编码从A-R，分别代表了18个经度（每20度一个字母）和18个纬度（每10度一组）。
* 第二对，Square，编码从0-9，把每一个Field分成100个Square。
* 第三对，Subsquare，编码从a-x，把每个Square分成256个Subsquare。
* 第四对，Extended Square，编码从0-9，把每个Subsquare分成100个Extended Square。
* 第五对之后的没有正式定义，基本可以按照第三、第四对的规律向后推算。

在短波领域一般报告到“Square”，即4位。
在V/UHF，一般报告到Subsuqare，即6位。

为避免出现负数，这个系统定义：经度的起点在国际日期变更线，纬度的起点在南极。每一级分格的起点都是左下角。

![Field的顺序](https://upload.wikimedia.org/wikipedia/commons/thumb/9/94/Maidenhead_Locator_Map.png/640px-Maidenhead_Locator_Map.png)

![Square的顺序](https://upload.wikimedia.org/wikipedia/commons/thumb/1/1d/Maidenhead_grid_over_Europe.svg/584px-Maidenhead_grid_over_Europe.svg.png)
