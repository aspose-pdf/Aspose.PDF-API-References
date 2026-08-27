---
title: "类 TableAbsorber"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Text.TableAbsorber 类。表示表元素的吸收器对象。执行搜索并通过 TableList 集合提供对搜索结果的访问"
type: docs
weight: 10970
url: /zh/net/aspose.pdf.text/tableabsorber/
---
## TableAbsorber class

表示表元素的吸收器对象。执行搜索并通过 [`TableList`](./tablelist/) 集合提供对搜索结果的访问。

```csharp
public class TableAbsorber
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [TableAbsorber](tableabsorber/#constructor)() | 初始化 `TableAbsorber` 的新实例。 |
| [TableAbsorber](tableabsorber/#constructor_1)(TextSearchOptions) | 使用文本搜索选项初始化 `TableAbsorber` 的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| virtual [TableList](../../aspose.pdf.text/tableabsorber/tablelist/) { get; } | 返回只读 IList，包含已找到的表格 |
| virtual [TextSearchOptions](../../aspose.pdf.text/tableabsorber/textsearchoptions/) { get; set; } | 获取或设置文本搜索选项。 |
| [UseFlowEngine](../../aspose.pdf.text/tableabsorber/useflowengine/) { get; set; } | * 启用一种在多种场景下更优且能够识别无边框表格的替代表格识别引擎。当前尚不支持编辑表格和获取文本样式。默认值为 false; |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Remove](../../aspose.pdf.text/tableabsorber/remove/)(AbsorbedTable) | 从页面中移除一个 [`AbsorbedTable`](../absorbedtable/)。 |
| [Replace](../../aspose.pdf.text/tableabsorber/replace/)(Page, AbsorbedTable, Table) | 在页面上将一个 [`AbsorbedTable`](../absorbedtable/) 替换为 [`Table`](../../aspose.pdf/table/)。 |
| [Visit](../../aspose.pdf.text/tableabsorber/visit/#visit)(Document) | 提取指定文档中的表格。 |
| virtual [Visit](../../aspose.pdf.text/tableabsorber/visit/#visit_1)(Page) | 提取指定页面上的表格 |

## 示例

此示例演示如何在第一个 PDF 文档页面上查找表格并替换表格单元格中的文本。

```csharp
// 打开文档
Document doc = new Document(@"D:\Tests\input.pdf");

// 创建 TableAbsorber 对象以查找表格
TableAbsorber absorber = new TableAbsorber();

// 使用吸收器访问第一页
absorber.Visit(pdfDocument.Pages[1]);

// 获取页面上第一个表格的访问权限，包括其第一个单元格及其中的文本片段
TextFragment fragment = absorber.TableList[0].RowList[0].CellList[0].TextFragments[1];

// 更改单元格中第一个文本片段的文本
fragment.Text = "hi world";

// 保存文档
doc.Save(@"D:\Tests\output.pdf");  
```

### 另请参见

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


