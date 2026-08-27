---
title: "PdfContentEditor.AddDocumentAdditionalAction"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo PdfContentEditor. Aggiunge un'azione aggiuntiva per l'evento del documento"
type: docs
weight: 60
url: /it/net/aspose.pdf.facades/pdfcontenteditor/adddocumentadditionalaction/
---
## PdfContentEditor.AddDocumentAdditionalAction method

Aggiunge un'azione aggiuntiva per l'evento del documento.

```csharp
public void AddDocumentAdditionalAction(string eventType, string code)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| eventType | String | I tipi di evento del documento. |
| codice | String | Il codice JavaScript. |

## Esempi

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.AddDocumentAdditionalAction(PdfContentEditor.DocumentClose, "app.alert('Good-bye!');");
editor.Save("example_out.pdf");
```

### Vedi anche

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


