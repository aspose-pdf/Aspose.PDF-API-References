---
title: PdfXmpMetadata.GetPrefixByNamespaceURI
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfXmpMetadata. تحصل على البادئة بواسطة URI المساحة
type: docs
weight: 180
url: /ar/net/aspose.pdf.facades/pdfxmpmetadata/getprefixbynamespaceuri/
---
## طريقة PdfXmpMetadata.GetPrefixByNamespaceURI

تحصل على البادئة بواسطة URI المساحة.

```csharp
public string GetPrefixByNamespaceURI(string namespaceURI)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| namespaceURI | سلسلة | URI المساحة. |

### قيمة الإرجاع

قيمة البادئة.

## أمثلة

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
Console.WriteLine(xmp.GetPrefixByNamespaceURI("http://ns.adobe.com/xap/1.0/"));
```

### انظر أيضًا

* الفئة [PdfXmpMetadata](../)
* المساحة [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* التجميع [Aspose.PDF](../../../)