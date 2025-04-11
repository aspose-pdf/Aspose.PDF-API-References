---
title: PdfFileEditor.LastException
second_title: Aspose.PDF for .NET API Reference
description: Proprietà di PdfFileEditor. Ottiene l'ultima eccezione verificatasi. Può essere utilizzata per controllare il motivo del fallimento
type: docs
weight: 130
url: /it/net/aspose.pdf.facades/pdffileeditor/lastexception/
---
## Proprietà PdfFileEditor.LastException

Ottiene l'ultima eccezione verificatasi. Può essere utilizzata per controllare il motivo del fallimento.

```csharp
public Exception LastException { get; }
```

## Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
if (!pfe.TryConcatenate("file1.pdf", "file2.pdf", "file3.pdf"))
{
   Console.WriteLine("Error occured:");
   if (pfe.LastException != null)
   {
       Console.WriteLine(pfe.LastException.Message);
       if (pfe.LastException.InnerException != null)
           Console.WriteLine(pfe.LastException.InnerException.Message);
   }
}
```

### Vedi Anche

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)