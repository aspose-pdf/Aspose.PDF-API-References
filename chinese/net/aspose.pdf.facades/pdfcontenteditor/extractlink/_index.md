---
title: ExtractLink
second_title: Aspose.PDF for .NET API 参考
description: 提取 PDF 文档中包含的链接实例的集合
type: docs
weight: 370
url: /zh/net/aspose.pdf.facades/pdfcontenteditor/extractlink/
---
## PdfContentEditor.ExtractLink method

提取 PDF 文档中包含的链接实例的集合。

```csharp
public IList<Annotation> ExtractLink()
```

### 返回值

Link 对象的集合

### 例子

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
IList links = editor.ExtractLink();
foreach (object obj in links)
{
    Link link = (Link)obj;
    // 使用 Link 实例
}
```

### 也可以看看

* class [Annotation](../../../aspose.pdf.annotations/annotation)
* class [PdfContentEditor](../../pdfcontenteditor)
* 命名空间 [Aspose.Pdf.Facades](../../pdfcontenteditor)
* 部件 [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
