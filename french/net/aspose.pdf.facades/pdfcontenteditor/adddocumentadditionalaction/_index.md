---
title: PdfContentEditor.AddDocumentAdditionalAction
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfContentEditor. Ajoute une action supplémentaire pour l'événement du document
type: docs
weight: 60
url: /fr/net/aspose.pdf.facades/pdfcontenteditor/adddocumentadditionalaction/
---
## Méthode PdfContentEditor.AddDocumentAdditionalAction

Ajoute une action supplémentaire pour l'événement du document.

```csharp
public void AddDocumentAdditionalAction(string eventType, string code)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| eventType | String | Les types d'événements du document. |
| code | String | Le code JavaScript. |

## Exemples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.AddDocumentAdditionalAction(PdfContentEditor.DocumentClose, "app.alert('Good-bye!');");
editor.Save("example_out.pdf");
```

### Voir aussi

* classe [PdfContentEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)