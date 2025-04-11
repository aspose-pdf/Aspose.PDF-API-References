---
title: PdfContentEditor.AddDocumentAdditionalAction
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfContentEditor. Aggiunge un'azione aggiuntiva per l'evento del documento
type: docs
weight: 60
url: /it/net/aspose.pdf.facades/pdfcontenteditor/adddocumentadditionalaction/
---
## Metodo PdfContentEditor.AddDocumentAdditionalAction

Aggiunge un'azione aggiuntiva per l'evento del documento.

```csharp
public void AddDocumentAdditionalAction(string eventType, string code)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| eventType | String | I tipi di eventi del documento. |
| code | String | Il codice di JavaScript. |

## Esempi

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.AddDocumentAdditionalAction(PdfContentEditor.DocumentClose, "app.alert('Good-bye!');");
editor.Save("example_out.pdf");
```

### Vedi Anche

* classe [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)