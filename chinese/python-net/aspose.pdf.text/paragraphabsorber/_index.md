---
title: "ParagraphAbsorber"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "表示页面结构对象（如章节和段落）的吸收器对象。<br/>            执行对文本章节和段落的搜索，并提供对描述其在文本坐标空间中的矩形和多边形的访问。<br/>            同时执行文本片段搜索，并通过按结构元素分组的 TextFragments 集合提供对搜索结果的访问。"
type: docs
weight: 240
url: /zh/python-net/aspose.pdf.text/paragraphabsorber/
---

## ParagraphAbsorber class

表示页面结构对象（如章节和段落）的吸收器对象。<br/>            执行对文本章节和段落的搜索，并提供对描述其在文本坐标空间中的矩形和多边形的访问。<br/>            同时执行文本片段搜索，并通过按结构元素分组的 TextFragments 集合提供对搜索结果的访问。

ParagraphAbsorber 类型公开以下成员：
## 构造函数
| 名称 | 描述 |
| :- | :- |
| ParagraphAbsorber() | 初始化 [ParagraphAbsorber](/pdf/python-net/aspose.pdf.text/paragraphabsorber/) 的新实例，该实例执行文档或页面的章节/段落搜索。 |
| ParagraphAbsorber(sections_search_depth) | 初始化 ParagraphAbsorber 类的新实例 |
## 属性
| 名称 | 描述 |
| :- | :- |
| page_markups | 获取已吸收的 [PageMarkup](/pdf/python-net/aspose.pdf.text/pagemarkup/) 集合。 |
| sections_search_depth | 获取或设置指示将执行多少次顺序搜索以查找更细的结构元素的值。<br/>            默认搜索深度为 3。<br/>            这意味着对水平划分的章节（标题、段落等）进行三次搜索，对垂直划分的章节（列）也进行三次搜索。 |
| is_multicolumn_paragraphs_allowed | 获取或设置指示是否可以将下一节的起始文本行视为前一节最后一个段落的延续的值。 |
## 方法
| 名称 | 描述 |
| :- | :- |
| visit(doc) | 在指定的 [Document](/pdf/python-net/aspose.pdf/document/) 上执行章节和段落搜索。 |
| visit(page) | 在指定的 [Page](/pdf/python-net/aspose.pdf/page/) 上执行搜索。 |

### 另请参阅

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

