---
title: PdfContentEditor.ExtractLink
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor 方法。提取 PDF 文档中包含的 Link 实例集合
type: docs
weight: 370
url: /zh/net/aspose.pdf.facades/pdfcontenteditor/extractlink/
---
## PdfContentEditor.ExtractLink 方法

提取 PDF 文档中包含的 Link 实例集合。

```csharp
public IList<Annotation> ExtractLink()
```

### 返回值

Link 对象的集合

## 示例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
IList links = editor.ExtractLink();
foreach (object obj in links)
{
    Link link = (Link)obj;
    // work with Link instance
}
```

### 另请参阅

* class [Annotation](../../../aspose.pdf.annotations/annotation/)
* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)