---
title: PdfFileEditor.LastException
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor property. Gets last occured exception. May be used to check the reason of failure
type: docs
weight: 130
url: /net/aspose.pdf.facades/pdffileeditor/lastexception/
---
## PdfFileEditor.LastException property

Gets last occured exception. May be used to check the reason of failure.

```csharp
public Exception LastException { get; }
```

## Examples

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

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


