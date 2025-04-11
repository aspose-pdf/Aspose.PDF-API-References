---
title: PdfContentEditor.CreateJavaScriptLink
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor metodu. PDF belgesinde JavaScript'e bir bağlantı oluşturur
type: docs
weight: 170
url: /tr/net/aspose.pdf.facades/pdfcontenteditor/createjavascriptlink/
---
## PdfContentEditor.CreateJavaScriptLink metodu

PDF belgesinde JavaScript'e bir bağlantı oluşturur.

```csharp
public void CreateJavaScriptLink(string code, Rectangle rect, int originalPage, Color color)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| code | String | JavaScript kodu. |
| rect | Rectangle | Aktif tıklama için dikdörtgen. |
| originalPage | Int32 | Bağlantı ile birlikte dikdörtgenin oluşturulacağı orijinal sayının numarası. |
| color | Color | Aktif tıklama için dikdörtgenin rengi. |

## Örnekler

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateJavaScriptLink("app.alert('welcome to aspose!');",
    new System.Drawing.Rectangle(0, 0, 100, 100), 1, System.Drawing.Color.Red });
editor.Save("example_out.pdf");
```

### Ayrıca Bakınız

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)