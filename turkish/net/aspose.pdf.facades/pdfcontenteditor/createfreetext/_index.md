---
title: PdfContentEditor.CreateFreeText
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor metodu. PDF belgesinde serbest metin notu oluşturur
type: docs
weight: 160
url: /tr/net/aspose.pdf.facades/pdfcontenteditor/createfreetext/
---
## PdfContentEditor.CreateFreeText metodu

PDF belgesinde serbest metin notu oluşturur

```csharp
public void CreateFreeText(Rectangle rect, string contents, int page)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | Rectangle | Notun sayfadaki konumunu tanımlayan not dikdörtgeni. |
| contents | String | Notun içeriği. |
| page | Int32 | Metin notunun oluşturulacağı orijinal sayfa numarası. |

## Örnekler

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateFreeText(new System.Drawing.Rectangle(0, 0, 100, 100), "Welcome to Aspose", 1);
editor.Save("example_out.pdf");
```

### Ayrıca Bakınız

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)