---
title: RemoveDocumentOpenAction
second_title: Aspose.PDF per .NET API Reference
description: Rimuove lazione aperta dal documento. Questa operazione è utile quando si concatenano più documenti che utilizzano lazione esplicita Vai a allavvio.
type: docs
weight: 430
url: /it/net/aspose.pdf.facades/pdfcontenteditor/removedocumentopenaction/
---
## PdfContentEditor.RemoveDocumentOpenAction method

Rimuove l'azione aperta dal documento. Questa operazione è utile quando si concatenano più documenti che utilizzano l'azione esplicita "Vai a" all'avvio.

```csharp
public void RemoveDocumentOpenAction()
```

### Esempi

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.RemoveDocumentOpenAction();
editor.Save("example_out.pdf");
```

### Guarda anche

* class [PdfContentEditor](../../pdfcontenteditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfcontenteditor)
* assemblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
