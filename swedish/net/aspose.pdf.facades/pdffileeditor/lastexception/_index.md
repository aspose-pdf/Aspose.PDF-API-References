---
title: "PdfFileEditor.LastException"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfFileEditor-egenskap. Hämtar det senaste inträffade undantaget. Kan användas för att kontrollera orsaken till felet."
type: docs
weight: 130
url: /sv/net/aspose.pdf.facades/pdffileeditor/lastexception/
---
## PdfFileEditor.LastException property

Hämtar det senaste undantaget. Kan användas för att kontrollera orsaken till felet.

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

### Se även

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


