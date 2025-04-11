---
title: PdfContentEditor.ExtractLink
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor metodu. PDF belgesinde bulunan Link örneklerinin koleksiyonunu çıkarır
type: docs
weight: 370
url: /tr/net/aspose.pdf.facades/pdfcontenteditor/extractlink/
---
## PdfContentEditor.ExtractLink metodu

PDF belgesinde bulunan Link örneklerinin koleksiyonunu çıkarır.

```csharp
public IList<Annotation> ExtractLink()
```

### Dönüş Değeri

Link nesnelerinin koleksiyonu

## Örnekler

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

### Ayrıca Bakınız

* sınıf [Annotation](../../../aspose.pdf.annotations/annotation/)
* sınıf [PdfContentEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)