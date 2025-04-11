---
title: PdfContentEditor.CreatePopup
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor metodu. PDF belgesinde açılır not oluşturur
type: docs
weight: 250
url: /tr/net/aspose.pdf.facades/pdfcontenteditor/createpopup/
---
## PdfContentEditor.CreatePopup metodu

PDF belgesinde açılır not oluşturur.

```csharp
public void CreatePopup(Rectangle rect, string contents, bool open, int page)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | Rectangle | Notun sayfadaki konumunu tanımlayan not dikdörtgeni. |
| contents | String | Notun içeriği. |
| open | Boolean | Açılır notun başlangıçta açık olarak görüntülenip görüntülenmeyeceğini belirten bir bayrak. |
| page | Int32 | Notun oluşturulacağı orijinal sayfa numarası. |

## Örnekler

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreatePopup(new System.Drawing.Rectangle(0, 0, 100, 100), "Welcome to Aspose", true, 1);
editor.Save("example_out.pdf");
```

### Ayrıca Bakınız

* sınıf [PdfContentEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)