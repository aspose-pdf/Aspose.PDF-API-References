---
title: TableAbsorber.Visit
second_title: Aspose.PDF for .NET API Reference
description: TableAbsorber 方法。提取指定页面上的表格
type: docs
weight: 70
url: /zh/net/aspose.pdf.text/tableabsorber/visit/
---
## Visit(Page) {#visit_1}

提取指定页面上的表格

```csharp
public virtual void Visit(Page page)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| page | Page | Pdf 文档页面对象。 |

## 示例

该示例演示如何提取第一个 PDF 文档页面上的表格。

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TableAbsorber object to find tables
TableAbsorber absorber = new TableAbsorber();

// Visit first page with absorber
absorber.Visit(doc.Pages[1]);

// Get access to first table on page, their first cell and text fragments in it
TextFragment fragment = absorber.TableList[0].RowList[0].CellList[0].TextFragments[1];

// Change text of the first text fragment in the cell
fragment.Text = "hi world";

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### 另请参阅

* class [Page](../../../aspose.pdf/page/)
* class [TableAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## Visit(Document) {#visit}

提取指定文档中的表格。

```csharp
public void Visit(Document pdf)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pdf | Document | Pdf 文档对象。 |

## 示例

该示例演示如何提取第一个 PDF 文档页面上的表格。

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TableAbsorber object to find tables
TableAbsorber absorber = new TableAbsorber();

// Visit first page with absorber
absorber.Visit(doc);

// Get access to first table on page, their first cell and text fragments in it
TextFragment fragment = absorber.TableList[0].RowList[0].CellList[0].TextFragments[1];

// Change text of the first text fragment in the cell
fragment.Text = "hi world";

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### 另请参阅

* class [Document](../../../aspose.pdf/document/)
* class [TableAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)