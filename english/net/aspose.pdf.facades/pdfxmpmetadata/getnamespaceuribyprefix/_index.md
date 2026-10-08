---
title: "PdfXmpMetadata.GetNamespaceURIByPrefix"
linktitle: "GetNamespaceURIByPrefix"
articleTitle: "GetNamespaceURIByPrefix"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfXmpMetadata method. Gets namespace URI by prefix."
type: docs
weight: 40
url: "/net/aspose.pdf.facades/pdfxmpmetadata/getnamespaceuribyprefix/"
product_version: "26.9"
---
## PdfXmpMetadata.GetNamespaceURIByPrefix method

Gets namespace URI by prefix.

```csharp
public string GetNamespaceURIByPrefix(string prefix)
```

| Parameter | Type | Description |
| --- | --- | --- |
| prefix | String | The prefix. |

### Return Value

Namespace URI.

## Examples

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
Console.WriteLine(xmp.GetNamespaceURIByPrefix("xmp"));
```

### See Also

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

