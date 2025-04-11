---
title: PdfContentEditor.AddDocumentAdditionalAction
second_title: Aspose.PDF for .NET API Reference
description: Método PdfContentEditor. Agrega una acción adicional para el evento del documento
type: docs
weight: 60
url: /es/net/aspose.pdf.facades/pdfcontenteditor/adddocumentadditionalaction/
---
## Método PdfContentEditor.AddDocumentAdditionalAction

Agrega una acción adicional para el evento del documento.

```csharp
public void AddDocumentAdditionalAction(string eventType, string code)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| eventType | String | Los tipos de eventos del documento. |
| code | String | El código de JavaScript. |

## Ejemplos

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.AddDocumentAdditionalAction(PdfContentEditor.DocumentClose, "app.alert('Good-bye!');");
editor.Save("example_out.pdf");
```

### Ver También

* clase [PdfContentEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)