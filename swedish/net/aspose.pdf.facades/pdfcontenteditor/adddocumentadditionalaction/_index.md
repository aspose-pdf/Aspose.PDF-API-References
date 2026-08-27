---
title: "PdfContentEditor.AddDocumentAdditionalAction"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfContentEditor metod. Lägger till en extra åtgärd för dokumenthändelse"
type: docs
weight: 60
url: /sv/net/aspose.pdf.facades/pdfcontenteditor/adddocumentadditionalaction/
---
## PdfContentEditor.AddDocumentAdditionalAction method

Lägger till ytterligare åtgärd för dokumenthändelse.

```csharp
public void AddDocumentAdditionalAction(string eventType, string code)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| eventType | String | Dokumenthändelsetyperna. |
| kod | String | JavaScript-koden. |

## Exempel

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.AddDocumentAdditionalAction(PdfContentEditor.DocumentClose, "app.alert('Good-bye!');");
editor.Save("example_out.pdf");
```

### Se även

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


