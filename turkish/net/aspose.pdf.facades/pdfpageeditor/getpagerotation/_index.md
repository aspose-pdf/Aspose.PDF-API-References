---
title: PdfPageEditor.GetPageRotation
second_title: Aspose.PDF for .NET API Reference
description: PdfPageEditor metodu. Belirtilen sayfanın döndürülmesini döndürür
type: docs
weight: 140
url: /tr/net/aspose.pdf.facades/pdfpageeditor/getpagerotation/
---
## PdfPageEditor.GetPageRotation metodu

Belirtilen sayfanın döndürülmesini döndürür.

```csharp
public int GetPageRotation(int page)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| page | Int32 | Sayfa indeksi. Belge sayfaları 1'den başlayarak numaralandırılır. |

### Dönüş Değeri

Derece cinsinden sayfa döndürülmesi.

## Örnekler

Aşağıdaki örnek, sayfa döndürülmesini nasıl alacağınızı gösterir:

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
int rotation = editor.GetPageSize(1);
Console.WriteLine("Rotation of 1st page : " + rotation + " degrees");        
```

### Ayrıca Bakınız

* sınıf [PdfPageEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)