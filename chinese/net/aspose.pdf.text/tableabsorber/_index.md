---
title: TableAbsorber
second_title: Aspose.PDF for .NET API 参考
description: 表示表元素的吸收器对象 执行搜索并通过以下方式访问搜索结果TableList./tableabsorber/tablelist集合.
type: docs
weight: 6950
url: /zh/net/aspose.pdf.text/tableabsorber/
---
## TableAbsorber class

表示表元素的吸收器对象。 执行搜索并通过以下方式访问搜索结果[`TableList`](./tablelist)集合.

```csharp
public class TableAbsorber
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [TableAbsorber](tableabsorber#constructor)() | 初始化[`TableAbsorber`](../tableabsorber). |
| [TableAbsorber](tableabsorber#constructor_1)(TextSearchOptions) | 初始化[`TableAbsorber`](../tableabsorber)带有文本搜索选项。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| virtual [TableList](../../aspose.pdf.text/tableabsorber/tablelist) { get; } | 返回包含已找到的表的只读 IList |
| virtual [TextSearchOptions](../../aspose.pdf.text/tableabsorber/textsearchoptions) { get; set; } | 获取或设置文本搜索选项。 |
| [UseFlowEngine](../../aspose.pdf.text/tableabsorber/useflowengine) { get; set; } | * 激活可用于转换表格的替代表格识别引擎的早期 alfa 版本 无边框。 尚不支持编辑表格和获取文本样式。默认值为假； |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [Remove](../../aspose.pdf.text/tableabsorber/remove)(AbsorbedTable) | 删除一个[`AbsorbedTable`](../absorbedtable)从页面. |
| [Replace](../../aspose.pdf.text/tableabsorber/replace)(Page, AbsorbedTable, Table) | 替换一个[`AbsorbedTable`](../absorbedtable)和[`Table`](../../aspose.pdf/table)在页面上。 |
| virtual [Visit](../../aspose.pdf.text/tableabsorber/visit)(Page) | 提取指定页面上的表 |

### 例子

该示例演示如何在第一个 PDF 文档页面上查找表格并替换表格单元格中的文本。

```csharp
// 打开文档
Document doc = new Document(@"D:\Tests\input.pdf");

// 创建 TableAbsorber 对象来查找表
TableAbsorber absorber = new TableAbsorber();

// 使用吸收器访问第一页
absorber.Visit(pdfDocument.Pages[1]);

// 访问页面上的第一个表格，它们的第一个单元格和其中的文本片段
TextFragment fragment = absorber.TableList[0].RowList[0].CellList[0].TextFragments[1];

// 改变单元格中第一个文本片段的文本
fragment.Text = "hi world";

// 保存文档
doc.Save(@"D:\Tests\output.pdf");  
```

### 也可以看看

* 命名空间 [Aspose.Pdf.Text](../../aspose.pdf.text)
* 部件 [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->