---
title: PdfPageEditor.GetPageSize
second_title: Aspose.PDF for .NET API Reference
description: PdfPageEditor 方法。返回指定页面的页面大小
type: docs
weight: 160
url: /zh/net/aspose.pdf.facades/pdfpageeditor/getpagesize/
---
## PdfPageEditor.GetPageSize 方法

返回指定页面的页面大小。

```csharp
public PageSize GetPageSize(int page)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| page | Int32 | 页面索引。文档页面从 1 开始编号。 |

### 返回值

结果是 PageSize 的实例。使用返回对象的 Width 和 Height 属性获取页面宽度和高度。

## 示例

以下示例演示了如何使用 GetPageSize 方法：

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
PageSize size = editor.GetPageSize(1);
Console.WriteLine("Size of 1st page : " + size.Width + " x " + size.Height);
```

### 另请参阅

* 类 [PageSize](../../../aspose.pdf/pagesize/)
* 类 [PdfPageEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)