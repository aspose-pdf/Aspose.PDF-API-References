---
title: "PdfXmpMetadata.RegisterNamespaceURI"
linktitle: "RegisterNamespaceURI"
articleTitle: "RegisterNamespaceURI"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfXmpMetadata method. Registers the namespace URI."
type: docs
weight: 30
url: "/net/aspose.pdf.facades/pdfxmpmetadata/registernamespaceuri/"
product_version: "26.9"
---
## PdfXmpMetadata.RegisterNamespaceURI method

Registers the namespace URI.

```csharp
public void RegisterNamespaceURI(string prefix, string namespaceURI)
```

| Parameter | Type | Description |
| --- | --- | --- |
| prefix | String | The prefix. |
| namespaceURI | String | The namespace URI. |

## Examples

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
xmp.RegisterNamespaceURI("xmp", "http://ns.adobe.com/xap/1.0/");
```

### See Also

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

