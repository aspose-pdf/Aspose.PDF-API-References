---
title: "PdfXmpMetadata.RegisterNamespaceURI"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfXmpMetadata. تسجل معرف URI للمساحة الاسمية"
type: docs
weight: 200
url: /ar/net/aspose.pdf.facades/pdfxmpmetadata/registernamespaceuri/
---
## PdfXmpMetadata.RegisterNamespaceURI method

يسجّل URI للمساحة الاسمية.

```csharp
public void RegisterNamespaceURI(string prefix, string namespaceURI)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| prefix | String | البادئة. |
| namespaceURI | String | معرف URI للمساحة الاسمية. |

## أمثلة

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
xmp.RegisterNamespaceURI("xmp", "http://ns.adobe.com/xap/1.0/");
```

### انظر أيضًا

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


