---
title: "PdfXmpMetadata.GetPrefixByNamespaceURI"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfXmpMetadata. تُعيد البادئة حسب مساحة الاسم URI"
type: docs
weight: 180
url: /ar/net/aspose.pdf.facades/pdfxmpmetadata/getprefixbynamespaceuri/
---
## PdfXmpMetadata.GetPrefixByNamespaceURI method

يحصل على البادئة حسب URI للمساحة الاسمية.

```csharp
public string GetPrefixByNamespaceURI(string namespaceURI)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| namespaceURI | String | مساحة الاسم URI. |

### قيمة الإرجاع

قيمة البادئة.

## أمثلة

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
Console.WriteLine(xmp.GetPrefixByNamespaceURI("http://ns.adobe.com/xap/1.0/"));
```

### انظر أيضًا

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


