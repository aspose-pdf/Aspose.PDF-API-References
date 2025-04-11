---
title: PdfContentEditor.AddDocumentAdditionalAction
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor-Methode. Fügt eine zusätzliche Aktion für das Dokumentereignis hinzu
type: docs
weight: 60
url: /de/net/aspose.pdf.facades/pdfcontenteditor/adddocumentadditionalaction/
---
## PdfContentEditor.AddDocumentAdditionalAction-Methode

Fügt eine zusätzliche Aktion für das Dokumentereignis hinzu.

```csharp
public void AddDocumentAdditionalAction(string eventType, string code)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| eventType | String | Die Dokumentereignistypen. |
| code | String | Der Code von JavaScript. |

## Beispiele

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.AddDocumentAdditionalAction(PdfContentEditor.DocumentClose, "app.alert('Good-bye!');");
editor.Save("example_out.pdf");
```

### Siehe auch

* Klasse [PdfContentEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)