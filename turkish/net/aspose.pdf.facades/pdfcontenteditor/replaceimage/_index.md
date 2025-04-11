---
title: PdfContentEditor.ReplaceImage
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor metodu. Belirtilen PDF belgesinin belirtilen sayfasındaki resmi başka bir resimle değiştirir
type: docs
weight: 440
url: /tr/net/aspose.pdf.facades/pdfcontenteditor/replaceimage/
---
## PdfContentEditor.ReplaceImage metodu

Belirtilen PDF belgesinin belirtilen sayfasındaki resmi başka bir resimle değiştirir.

```csharp
public void ReplaceImage(int pageNumber, int index, string imageFile)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pageNumber | Int32 | Resmin değiştirildiği sayının numarası. |
| index | Int32 | Değiştirilmesi gereken resim nesnesinin indeksi. |
| imageFile | String | Değiştirme için kullanılacak resim dosyası. |

## Örnekler

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.ReplaceImage(1, 1, "image.jpg");
editor.Save("example_out.pdf");
```

### Ayrıca Bakınız

* sınıf [PdfContentEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)