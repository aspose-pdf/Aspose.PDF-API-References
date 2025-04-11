---
title: PdfContentEditor.AddDocumentAdditionalAction
second_title: Aspose.PDF for .NET API Reference
description: Método PdfContentEditor. Adiciona ação adicional para evento de documento
type: docs
weight: 60
url: /pt/net/aspose.pdf.facades/pdfcontenteditor/adddocumentadditionalaction/
---
## Método PdfContentEditor.AddDocumentAdditionalAction

Adiciona ação adicional para evento de documento.

```csharp
public void AddDocumentAdditionalAction(string eventType, string code)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| eventType | String | Os tipos de eventos do documento. |
| code | String | O código de JavaScript. |

## Exemplos

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.AddDocumentAdditionalAction(PdfContentEditor.DocumentClose, "app.alert('Good-bye!');");
editor.Save("example_out.pdf");
```

### Veja Também

* classe [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)