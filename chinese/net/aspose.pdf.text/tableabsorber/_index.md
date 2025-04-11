---
title: Class TableAbsorber
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TableAbsorber class. 表示一个表元素的吸收器对象。执行搜索并通过 TableList 集合提供对搜索结果的访问
type: docs
weight: 10790
url: /zh/net/aspose.pdf.text/tableabsorber/
---
## TableAbsorber class

表示一个表元素的吸收器对象。执行搜索并通过 [`TableList`](./tablelist/) 集合提供对搜索结果的访问。

```csharp
public class TableAbsorber
```

## Constructors

| Name | Description |
| --- | --- |
| [TableAbsorber](tableabsorber/#constructor)() | 初始化 `TableAbsorber` 的新实例。 |
| [TableAbsorber](tableabsorber/#constructor_1)(TextSearchOptions) | 使用文本搜索选项初始化 `TableAbsorber` 的新实例。 |

## Properties

| Name | Description |
| --- | --- |
| virtual [TableList](../../aspose.pdf.text/tableabsorber/tablelist/) { get; } | 返回包含找到的表的只读 IList |
| virtual [TextSearchOptions](../../aspose.pdf.text/tableabsorber/textsearchoptions/) { get; set; } | 获取或设置文本搜索选项。 |
| [UseFlowEngine](../../aspose.pdf.text/tableabsorber/useflowengine/) { get; set; } | * 启用一种替代的表识别引擎，在许多场景中表现更佳，并且能够识别没有边框的表。尚不支持编辑表和获取文本样式。默认值为 false； |

## Methods

| Name | Description |
| --- | --- |
| [Remove](../../aspose.pdf.text/tableabsorber/remove/)(AbsorbedTable) | 从页面中移除一个 [`AbsorbedTable`](../absorbedtable/)。 |
| [Replace](../../aspose.pdf.text/tableabsorber/replace/)(Page, AbsorbedTable, Table) | 用 [`Table`](../../aspose.pdf/table/) 替换页面上的 [`AbsorbedTable`](../absorbedtable/)。 |
| [Visit](../../aspose.pdf.text/tableabsorber/visit/#visit)(Document) | 提取指定文档中的表。 |
| virtual [Visit](../../aspose.pdf.text/tableabsorber/visit/#visit_1)(Page) | 提取指定页面上的表 |

## Examples

该示例演示如何在第一个 PDF 文档页面上找到表并替换表单元格中的文本。

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TableAbsorber object to find tables
TableAbsorber absorber = new TableAbsorber();

// Visit first page with absorber
absorber.Visit(pdfDocument.Pages[1]);

// Get access to first table on page, their first cell and text fragments in it
TextFragment fragment = absorber.TableList[0].RowList[0].CellList[0].TextFragments[1];

// Change text of the first text fragment in the cell
fragment.Text = "hi world";

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### See Also

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)