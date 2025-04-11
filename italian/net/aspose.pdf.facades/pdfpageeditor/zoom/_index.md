---
title: PdfPageEditor.Zoom
second_title: Aspose.PDF for .NET API Reference
description: Proprietà PdfPageEditor. Ottiene o imposta il coefficiente di zoom. Il valore 1.0 corrisponde a 100. Il valore predefinito è 1.0.  Il seguente esempio dimostra come cambiare lo zoom delle pagine del documento
type: docs
weight: 110
url: /it/net/aspose.pdf.facades/pdfpageeditor/zoom/
---
## Proprietà PdfPageEditor.Zoom

Ottiene o imposta il coefficiente di zoom. Il valore 1.0 corrisponde al 100%. Il valore predefinito è 1.0.  Il seguente esempio dimostra come cambiare lo zoom delle pagine del documento.

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
editor.Zoom = 0.5f;
```

```csharp
public float Zoom { get; set; }
```

### Vedi Anche

* classe [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)