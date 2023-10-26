---
title: PdfXmpMetadata.RegisterNamespaceURI
second_title: Aspose.PDF for .NET API Reference
description: PdfXmpMetadata method. Registers the namespace URI
type: docs
weight: 200
url: /net/aspose.pdf.facades/pdfxmpmetadata/registernamespaceuri/
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

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


