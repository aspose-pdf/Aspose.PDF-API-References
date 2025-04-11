---
title: PdfContentEditor.RemoveDocumentOpenAction
second_title: Aspose.PDF for .NET API Reference
description: Método PdfContentEditor. Remove a ação de abertura do documento. Esta operação é útil ao concatenar vários documentos que usam ação 'GoTo' explícita na inicialização.
type: docs
weight: 430
url: /pt/net/aspose.pdf.facades/pdfcontenteditor/removedocumentopenaction/
---
## Método PdfContentEditor.RemoveDocumentOpenAction

Remove a ação de abertura do documento. Esta operação é útil ao concatenar vários documentos que usam ação 'GoTo' explícita na inicialização.

```csharp
public void RemoveDocumentOpenAction()
```

## Exemplos

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.RemoveDocumentOpenAction();
editor.Save("example_out.pdf");
```

### Veja Também

* classe [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)