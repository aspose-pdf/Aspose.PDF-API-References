---
title: PdfFileEditor.LastException
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor özelliği. En son meydana gelen istisnayı alır. Başarısızlık nedenini kontrol etmek için kullanılabilir.
type: docs
weight: 130
url: /tr/net/aspose.pdf.facades/pdffileeditor/lastexception/
---
## PdfFileEditor.LastException özelliği

En son meydana gelen istisnayı alır. Başarısızlık nedenini kontrol etmek için kullanılabilir.

```csharp
public Exception LastException { get; }
```

## Örnekler

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

### Ayrıca Bakınız

* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)