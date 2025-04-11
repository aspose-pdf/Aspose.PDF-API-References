---
title: PdfXmpMetadata.GetNamespaceURIByPrefix
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfXmpMetadata. تحصل على URI المساحة الاسمية بواسطة البادئة
type: docs
weight: 170
url: /ar/net/aspose.pdf.facades/pdfxmpmetadata/getnamespaceuribyprefix/
---
## طريقة PdfXmpMetadata.GetNamespaceURIByPrefix

تحصل على URI المساحة الاسمية بواسطة البادئة.

```csharp
public string GetNamespaceURIByPrefix(string prefix)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| prefix | String | البادئة. |

### قيمة الإرجاع

URI المساحة الاسمية.

## أمثلة

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
Console.WriteLine(xmp.GetNamespaceURIByPrefix("xmp"));
```

### انظر أيضًا

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)