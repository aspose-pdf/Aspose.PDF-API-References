---
title: PdfContentEditor.AddDocumentAdditionalAction
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor metodu. Belge olayı için ek eylem ekler
type: docs
weight: 60
url: /tr/net/aspose.pdf.facades/pdfcontenteditor/adddocumentadditionalaction/
---
## PdfContentEditor.AddDocumentAdditionalAction metodu

Belge olayı için ek eylem ekler.

```csharp
public void AddDocumentAdditionalAction(string eventType, string code)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| eventType | String | Belge olayı türleri. |
| code | String | JavaScript kodu. |

## Örnekler

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.AddDocumentAdditionalAction(PdfContentEditor.DocumentClose, "app.alert('Good-bye!');");
editor.Save("example_out.pdf");
```

### Ayrıca Bakınız

* sınıf [PdfContentEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)