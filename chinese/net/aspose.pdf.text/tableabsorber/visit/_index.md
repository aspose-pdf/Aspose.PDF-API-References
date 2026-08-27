---
title: "TableAbsorber.Visit"
second_title: "Aspose.PDF for .NET API 参考"
description: "TableAbsorber 方法。提取指定页面上的表格"
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
| 页面 | 页面 | Pdf 文档页面对象。 |

## 示例

示例演示了如何在第一个 PDF 文档页面上提取表格。

```csharp
// 打开文档
Document doc = new Document(@"D:\Tests\input.pdf");

// 创建 TableAbsorber 对象以查找表格
TableAbsorber absorber = new TableAbsorber();

// 使用吸收器访问第一页
absorber.Visit(doc.Pages[1]);

// 获取页面上第一个表格的访问权限，包括其第一个单元格及其中的文本片段
TextFragment fragment = absorber.TableList[0].RowList[0].CellList[0].TextFragments[1];

// 更改单元格中第一个文本片段的文本
fragment.Text = "hi world";

// 保存文档
doc.Save(@"D:\Tests\output.pdf");  
```

### 另请参见

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
| pdf | Document | Pdf pocument 对象。 |

## 示例

示例演示了如何在第一个 PDF 文档页面上提取表格。

```csharp
// 打开文档
Document doc = new Document(@"D:\Tests\input.pdf");

// 创建 TableAbsorber 对象以查找表格
TableAbsorber absorber = new TableAbsorber();

// 使用吸收器访问第一页
absorber.Visit(doc);

// 获取页面上第一个表格的访问权限，包括其第一个单元格及其中的文本片段
TextFragment fragment = absorber.TableList[0].RowList[0].CellList[0].TextFragments[1];

// 更改单元格中第一个文本片段的文本
fragment.Text = "hi world";

// 保存文档
doc.Save(@"D:\Tests\output.pdf");  
```

### 另请参见

* class [Document](../../../aspose.pdf/document/)
* class [TableAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


