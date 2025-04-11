---
title: PdfContentEditor.DeleteStamp
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor metodu. Belirtilen sayfadaki birden fazla damgayı damga indeksleri ile siler
type: docs
weight: 330
url: /tr/net/aspose.pdf.facades/pdfcontenteditor/deletestamp/
---
## PdfContentEditor.DeleteStamp metodu

Belirtilen sayfadaki birden fazla damgayı damga indeksleri ile siler.

```csharp
public void DeleteStamp(int pageNumber, int[] index)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pageNumber | Int32 | Damganın silineceği sayfa numarası. |
| index | Int32[] | Damga indeksleri. |

## Örnekler

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStamp(1, new int[] { 2, 3, 5} );
contentEditor.Save("outfile.pdf");
```

### Ayrıca Bakınız

* sınıf [PdfContentEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)