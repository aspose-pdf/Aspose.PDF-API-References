---
title: GetPageBoxSize
second_title: Aspose.PDF for .NET API 参考
description: 返回文档中指定框的大小
type: docs
weight: 130
url: /zh/net/aspose.pdf.facades/pdfpageeditor/getpageboxsize/
---
## PdfPageEditor.GetPageBoxSize method

返回文档中指定框的大小。

```csharp
public Rectangle GetPageBoxSize(int page, string pageBoxName)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| page | Int32 | 页面索引。文档页从 1 开始编号。 |
| pageBoxName | String | 框类型名称。有效值为：“art”、“bleed”、“crop”、“media”、“trim”。 |

### 返回值

包含请求框的矩形。

### 例子

下面的例子演示了如何获取第一页的媒体框：

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
System.Drawing.Rectangle rect = editor.GetBoxSize(1, "media");
```

### 也可以看看

* class [PdfPageEditor](../../pdfpageeditor)
* 命名空间 [Aspose.Pdf.Facades](../../pdfpageeditor)
* 部件 [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->