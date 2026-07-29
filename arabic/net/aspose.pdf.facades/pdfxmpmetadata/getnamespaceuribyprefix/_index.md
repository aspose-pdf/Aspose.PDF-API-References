---
title: "PdfXmpMetadata.GetNamespaceURIByPrefix"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfXmpMetadata. يحصل على URI مساحة الاسم حسب البادئة"
type: docs
weight: 170
url: /ar/net/aspose.pdf.facades/pdfxmpmetadata/getnamespaceuribyprefix/
---
## PdfXmpMetadata.GetNamespaceURIByPrefix method

يحصل على URI للمساحة الاسمية حسب البادئة.

```csharp
public string GetNamespaceURIByPrefix(string prefix)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| prefix | String | البادئة. |

### قيمة الإرجاع

مساحة الاسم URI.

## أمثلة

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
Console.WriteLine(xmp.GetNamespaceURIByPrefix("xmp"));
```

### انظر أيضًا

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


