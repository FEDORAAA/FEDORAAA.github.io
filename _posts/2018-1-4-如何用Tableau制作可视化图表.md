---
layout: article
title:  "如何用Tableau制作可视化图表"
date:   2018-1-4 22:07:50 +0800
categories: notes_tech Jekyll
image:
  teaser: b (1).jpg
  feature: b (1).jpg
---

- Tableau支持多种数据文件格式与多种数据库，excel、mysql、oracle等方式。用户根据数据源选择连接方式，左侧连接方式自主选择。
<img src="http://img.blog.csdn.net/20160324153436306?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQv/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/Center" alt="">

第一步：选择要打开的工作簿，左侧显示工作簿名称与工作簿包含的工作表名称，将工作表拖入文本框出即可对工作表进行数据的可视化展示。
<img src="http://img.blog.csdn.net/20160324152908112?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQv/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/Center" alt="">

第二步：工作表拖入后下方显示此工作表各列详细信息，Tableau根据表格的数字类型自动转换为Tableau对应类型，abc对应文本格式，#号对应数字格式、地图对应地理位置、日历对应日期格式，用户根据需要可以把列名重命名便于后期数据处理，导入之后Tableau默认会把数字格式的列分组到度量组，其他格式分组到维度组。
<img src="http://img.blog.csdn.net/20160324152937065?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQv/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/Center" alt="">


第三步： 点击左下方转到工作表即可对工作表进行操作，维度是工作表里的非数字格式数据，度量是数字格式数据，用户根据需要根据自行组合达到用户需求。如下图所示。
<img src="http://img.blog.csdn.net/20160324153422681?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQv/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/Center" alt="">
<img src="http://img.blog.csdn.net/20160324153132474?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQv/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/Center" alt="">
