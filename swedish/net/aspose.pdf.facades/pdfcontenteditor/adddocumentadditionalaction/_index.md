---
title: PdfContentEditor.AddDocumentAdditionalAction
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor-metod. Lägger till en ytterligare åtgärd för dokumenthändelse
type: docs
weight: 60
url: /sv/net/aspose.pdf.facades/pdfcontenteditor/adddocumentadditionalaction/
---
## PdfContentEditor.AddDocumentAdditionalAction metod

Lägger till en ytterligare åtgärd för dokumenthändelse.

```csharp
public void AddDocumentAdditionalAction(string eventType, string code)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| eventType | Sträng | Typer av dokumenthändelser. |
| code | Sträng | Koden för JavaScript. |

## Exempel

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.AddDocumentAdditionalAction(PdfContentEditor.DocumentClose, "app.alert('Good-bye!');");
editor.Save("example_out.pdf");
```

### Se Även

* klass [PdfContentEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* sammansättning [Aspose.PDF](../../../)