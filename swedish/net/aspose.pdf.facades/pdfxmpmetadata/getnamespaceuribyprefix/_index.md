---
title: "PdfXmpMetadata.GetNamespaceURIByPrefix"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfXmpMetadata‑metod. Hämtar namnrymdens URI efter prefix"
type: docs
weight: 170
url: /sv/net/aspose.pdf.facades/pdfxmpmetadata/getnamespaceuribyprefix/
---
## PdfXmpMetadata.GetNamespaceURIByPrefix method

Hämtar namespace‑URI med prefix.

```csharp
public string GetNamespaceURIByPrefix(string prefix)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| prefix | String | Prefixet. |

### Returvärde

Namnrymds-URI.

## Exempel

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
Console.WriteLine(xmp.GetNamespaceURIByPrefix("xmp"));
```

### Se även

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


