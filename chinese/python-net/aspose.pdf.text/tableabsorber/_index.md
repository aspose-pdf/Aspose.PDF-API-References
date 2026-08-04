---
title: "TableAbsorber"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "表示表格元素的吸收器对象。<br/>            执行搜索并通过 [table_list](/pdf/python-net/aspose.pdf.text/tableabsorber/) 集合提供对搜索结果的访问。"
type: docs
weight: 310
url: /zh/python-net/aspose.pdf.text/tableabsorber/
---

## TableAbsorber class

表示表格元素的吸收器对象。<br/>            执行搜索并通过 [table_list](/pdf/python-net/aspose.pdf.text/tableabsorber/) 集合提供对搜索结果的访问。

TableAbsorber 类型公开以下成员：
## 构造函数
| 名称 | 描述 |
| :- | :- |
| TableAbsorber(text_search_options) | 初始化 TableAbsorber 类的新实例。 |
| TableAbsorber() | 初始化一个新的 [TableAbsorber](/pdf/python-net/aspose.pdf.text/tableabsorber/) 实例。 |
## 属性
| 名称 | 描述 |
| :- | :- |
| text_search_options | 获取或设置文本搜索选项。 |
| table_list | 返回只读 IList，包含找到的表格 |
| use_flow_engine | * 激活一个早期的 alfa 版替代表格识别引擎，可用于转换无边框的表格。<br/>            目前不支持编辑表格和获取文本样式。默认值为 false; |
## 方法
| 名称 | 描述 |
| :- | :- |
| visit(page) | 提取指定页面上的表格 |
| remove(table) | 从页面中移除一个 [AbsorbedTable](/pdf/python-net/aspose.pdf.text/absorbedtable/)。 |
| replace(page, old_table, new_table) | 在页面上将 [AbsorbedTable](/pdf/python-net/aspose.pdf.text/absorbedtable/) 替换为 [Table](/pdf/python-net/aspose.pdf/table/)。 |

### 另请参阅

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

