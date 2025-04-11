---
title: PdfFileEditor.LastException
second_title: Aspose.PDF for .NET API Reference
description: Propriété PdfFileEditor. Obtient la dernière exception survenue. Peut être utilisée pour vérifier la raison de l'échec
type: docs
weight: 130
url: /fr/net/aspose.pdf.facades/pdffileeditor/lastexception/
---
## Propriété PdfFileEditor.LastException

Obtient la dernière exception survenue. Peut être utilisée pour vérifier la raison de l'échec.

```csharp
public Exception LastException { get; }
```

## Exemples

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

### Voir aussi

* classe [PdfFileEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)