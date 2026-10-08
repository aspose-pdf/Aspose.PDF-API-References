---
title: "PdfXmpMetadata.GetPrefixByNamespaceURI"
linktitle: "GetPrefixByNamespaceURI"
articleTitle: "GetPrefixByNamespaceURI"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfXmpMetadata method. Gets the prefix by namespace URI."
type: docs
weight: 50
url: "/net/aspose.pdf.facades/pdfxmpmetadata/getprefixbynamespaceuri/"
product_version: "26.9"
---
## PdfXmpMetadata.GetPrefixByNamespaceURI method

Gets the prefix by namespace URI.

```csharp
public string GetPrefixByNamespaceURI(string namespaceURI)
```

| Parameter | Type | Description |
| --- | --- | --- |
| namespaceURI | String | Namespace URI. |

### Return Value

The prefix value.

## Examples

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
Console.WriteLine(xmp.GetPrefixByNamespaceURI("http://ns.adobe.com/xap/1.0/"));
```

### See Also

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

