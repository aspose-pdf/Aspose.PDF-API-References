---
title: PdfFileEditor.LastException
second_title: Aspose.PDF for .NET API Reference
description: Properti PdfFileEditor. Mendapatkan pengecualian terakhir yang terjadi. Dapat digunakan untuk memeriksa alasan kegagalan
type: docs
weight: 130
url: /id/net/aspose.pdf.facades/pdffileeditor/lastexception/
---
## Properti PdfFileEditor.LastException

Mendapatkan pengecualian terakhir yang terjadi. Dapat digunakan untuk memeriksa alasan kegagalan.

```csharp
public Exception LastException { get; }
```

## Contoh

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

### Lihat Juga

* kelas [PdfFileEditor](../)
* ruang nama [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)