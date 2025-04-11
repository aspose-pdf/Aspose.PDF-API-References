---
title: PdfFileEditor.LastException
second_title: Aspose.PDF for .NET API Reference
description: Propriedade PdfFileEditor. Obtém a última exceção ocorrida. Pode ser usada para verificar a razão da falha
type: docs
weight: 130
url: /pt/net/aspose.pdf.facades/pdffileeditor/lastexception/
---
## Propriedade PdfFileEditor.LastException

Obtém a última exceção ocorrida. Pode ser usada para verificar a razão da falha.

```csharp
public Exception LastException { get; }
```

## Exemplos

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

### Veja Também

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)