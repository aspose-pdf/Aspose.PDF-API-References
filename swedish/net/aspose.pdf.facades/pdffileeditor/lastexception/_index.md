---
title: PdfFileEditor.LastException
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor-egenskap. Hämtar senaste inträffade undantag. Kan användas för att kontrollera orsaken till felet
type: docs
weight: 130
url: /sv/net/aspose.pdf.facades/pdffileeditor/lastexception/
---
## PdfFileEditor.LastException-egenskap

Hämtar senaste inträffade undantag. Kan användas för att kontrollera orsaken till felet.

```csharp
public Exception LastException { get; }
```

## Exempel

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

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* sammansättning [Aspose.PDF](../../../)