---
title: LastException
second_title: Référence de l'API Aspose.PDF pour .NET
description: Obtient la dernière exception survenue. Peut être utilisé pour vérifier la raison de léchec.
type: docs
weight: 150
url: /fr/net/aspose.pdf.facades/pdffileeditor/lastexception/
---
## PdfFileEditor.LastException property

Obtient la dernière exception survenue. Peut être utilisé pour vérifier la raison de l'échec.

```csharp
public Exception LastException { get; }
```

### Exemples

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

### Voir également

* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
