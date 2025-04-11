---
title: PdfFileEditor.LastException
second_title: Aspose.PDF for .NET API Reference
description: خاصية PdfFileEditor. تحصل على آخر استثناء حدث. يمكن استخدامها للتحقق من سبب الفشل
type: docs
weight: 130
url: /ar/net/aspose.pdf.facades/pdffileeditor/lastexception/
---
## خاصية PdfFileEditor.LastException

تحصل على آخر استثناء حدث. يمكن استخدامها للتحقق من سبب الفشل.

```csharp
public Exception LastException { get; }
```

## أمثلة

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

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)