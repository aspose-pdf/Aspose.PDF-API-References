---
title: "PdfContentEditor.AddDocumentAdditionalAction"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode PdfContentEditor. Ajoute une action supplémentaire pour l'événement du document"
type: docs
weight: 60
url: /fr/net/aspose.pdf.facades/pdfcontenteditor/adddocumentadditionalaction/
---
## PdfContentEditor.AddDocumentAdditionalAction method

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

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


