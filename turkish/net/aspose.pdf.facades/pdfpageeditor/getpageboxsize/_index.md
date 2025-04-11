---
title: PdfPageEditor.GetPageBoxSize
second_title: Aspose.PDF for .NET API Reference
description: PdfPageEditor metodu. Belirtilen kutunun boyutunu döndürür
type: docs
weight: 130
url: /tr/net/aspose.pdf.facades/pdfpageeditor/getpageboxsize/
---
## PdfPageEditor.GetPageBoxSize metodu

Belirtilen kutunun boyutunu döndürür.

```csharp
public Rectangle GetPageBoxSize(int page, string pageBoxName)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| page | Int32 | Sayfa indeksi. Belge sayfaları 1'den başlayarak numaralandırılır. |
| pageBoxName | String | Kutunun tür adı. Geçerli değerler: "art", "bleed", "crop", "media", "trim". |

### Dönüş Değeri

İstenen kutuyu içeren dikdörtgen.

## Örnekler

Aşağıdaki örnek, 1. sayfanın medya kutusunu nasıl alacağınızı gösterir:

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
System.Drawing.Rectangle rect = editor.GetBoxSize(1, "media");
```

### Ayrıca Bakınız

* sınıf [PdfPageEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)