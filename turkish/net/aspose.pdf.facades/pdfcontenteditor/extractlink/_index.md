---
title: ExtractLink
second_title: Aspose.PDF for .NET API Referansı
description: PDF belgesinde bulunan Link örnekleri koleksiyonunu çıkarır.
type: docs
weight: 370
url: /tr/net/aspose.pdf.facades/pdfcontenteditor/extractlink/
---
## PdfContentEditor.ExtractLink method

PDF belgesinde bulunan Link örnekleri koleksiyonunu çıkarır.

```csharp
public IList<Annotation> ExtractLink()
```

### Geri dönüş değeri

Link nesnelerinin toplanması

### Örnekler

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
IList links = editor.ExtractLink();
foreach (object obj in links)
{
    Link link = (Link)obj;
    // Link örneği ile çalış
}
```

### Ayrıca bakınız

* class [Annotation](../../../aspose.pdf.annotations/annotation)
* class [PdfContentEditor](../../pdfcontenteditor)
* ad alanı [Aspose.Pdf.Facades](../../pdfcontenteditor)
* toplantı [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->