---
title: PdfXmpMetadata.RegisterNamespaceURI
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfXmpMetadata. تسجل URI مساحة الاسم
type: docs
weight: 200
url: /ar/net/aspose.pdf.facades/pdfxmpmetadata/registernamespaceuri/
---
## طريقة PdfXmpMetadata.RegisterNamespaceURI

تسجل URI مساحة الاسم.

```csharp
public void RegisterNamespaceURI(string prefix, string namespaceURI)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| prefix | String | البادئة. |
| namespaceURI | String | URI مساحة الاسم. |

## أمثلة

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
xmp.RegisterNamespaceURI("xmp", "http://ns.adobe.com/xap/1.0/");
```

### انظر أيضًا

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)