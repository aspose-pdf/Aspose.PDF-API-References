---
title: GetPrefixByNamespaceURI
second_title: Aspose.PDF لمرجع .NET API
description: يحصل على البادئة بواسطة مساحة الاسم URI.
type: docs
weight: 180
url: /ar/net/aspose.pdf.facades/pdfxmpmetadata/getprefixbynamespaceuri/
---
## PdfXmpMetadata.GetPrefixByNamespaceURI method

يحصل على البادئة بواسطة مساحة الاسم URI.

```csharp
public string GetPrefixByNamespaceURI(string namespaceURI)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| namespaceURI | String | Namespace URI. |

### قيمة الإرجاع

قيمة البادئة.

### أمثلة

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
Console.WriteLine(xmp.GetPrefixByNamespaceURI("http://ns.adobe.com/xap/1.0/ ")) ;
```

### أنظر أيضا

* class [PdfXmpMetadata](../../pdfxmpmetadata)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfxmpmetadata)
* المجسم [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
