---
title: PdfXmpMetadata.GetNamespaceURIByPrefix
second_title: Aspose.PDF for .NET API Reference
description: PdfXmpMetadata-metod. Hämtar namnrymds-URI efter prefix
type: docs
weight: 170
url: /sv/net/aspose.pdf.facades/pdfxmpmetadata/getnamespaceuribyprefix/
---
## PdfXmpMetadata.GetNamespaceURIByPrefix metod

Hämtar namnrymds-URI efter prefix.

```csharp
public string GetNamespaceURIByPrefix(string prefix)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| prefix | Sträng | Prefixet. |

### Returvärde

Namnrymds-URI.

## Exempel

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
Console.WriteLine(xmp.GetNamespaceURIByPrefix("xmp"));
```

### Se Även

* klass [PdfXmpMetadata](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* sammansättning [Aspose.PDF](../../../)