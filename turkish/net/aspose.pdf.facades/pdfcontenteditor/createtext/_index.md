---
title: PdfContentEditor.CreateText
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor metodu. PDF belgesinde metin notu oluşturur
type: docs
weight: 290
url: /tr/net/aspose.pdf.facades/pdfcontenteditor/createtext/
---
## PdfContentEditor.CreateText metodu

PDF belgesinde metin notu oluşturur

```csharp
public void CreateText(Rectangle rect, string title, string contents, bool open, string icon, 
    int page)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | Dikdörtgen | Notun sayfadaki konumunu tanımlayan not dikdörtgeni. |
| title | Dize | Notun başlığı. |
| contents | Dize | Notun içeriği. |
| open | Boolean | Notun başlangıçta açık olarak görüntülenip görüntülenmeyeceğini belirten bir bayrak. |
| icon | Dize | Notu görüntülemede kullanılacak bir simgenin adı. Bu değer şunlardan biri olabilir: "Yorum", "Anahtar", "Not", "Yardım", "YeniParagraf", "Paragraf", "Ekle" |
| page | Int32 | Metin notunun oluşturulacağı orijinal sayfa numarası. |

## Örnekler

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateText(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", "You are welcome to Aspose!", true, "Key", 1);
editor.Save("example_out.pdf");
```

### Ayrıca Bakınız

* sınıf [PdfContentEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)