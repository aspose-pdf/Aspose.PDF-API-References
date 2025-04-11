---
title: PdfContentEditor.CreateCaret
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor metodu. İmleç anotasyonu oluşturur
type: docs
weight: 130
url: /tr/net/aspose.pdf.facades/pdfcontenteditor/createcaret/
---
## PdfContentEditor.CreateCaret metodu

İmleç anotasyonu oluşturur.

```csharp
public void CreateCaret(int page, Rectangle annotRect, Rectangle caretRect, string symbol, 
    string annotContents, Color color)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sayfa | Int32 | Anotasyonun oluşturulacağı orijinal sayfa numarası. |
| annotRect | Dikdörtgen | Anotasyonun sayfadaki konumunu tanımlayan anotasyon dikdörtgeni. |
| caretRect | Dikdörtgen | Temel imlecin gerçek sınırları. |
| sembol | Dize | İmleç ile ilişkilendirilecek bir sembol. Değer şu olabilir: "P" (Paragraf), "Yok". |
| annotContents | Dize | Anotasyonun içeriği. |
| renk | Renk | Anotasyonun rengi. |

## Örnekler

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateCaret(1,
    new System.Drawing.Rectangle(50, 50, 100, 100),
    new System.Drawing.Rectangle(60, 60, 70, 70),
    "None", "Welcome to Aspose", System.Drawing.Color.Red);
editor.Save("example_out.pdf");
```

### Ayrıca Bakınız

* sınıf [PdfContentEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)