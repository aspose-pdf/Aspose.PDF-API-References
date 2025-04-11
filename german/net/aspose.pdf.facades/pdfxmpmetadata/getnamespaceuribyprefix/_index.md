---
title: PdfXmpMetadata.GetNamespaceURIByPrefix
second_title: Aspose.PDF for .NET API Reference
description: PdfXmpMetadata-Methode. Ruft den Namespace-URI nach Präfix ab
type: docs
weight: 170
url: /de/net/aspose.pdf.facades/pdfxmpmetadata/getnamespaceuribyprefix/
---
## PdfXmpMetadata.GetNamespaceURIByPrefix-Methode

Ruft den Namespace-URI nach Präfix ab.

```csharp
public string GetNamespaceURIByPrefix(string prefix)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| prefix | String | Das Präfix. |

### Rückgabewert

Namespace-URI.

## Beispiele

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
Console.WriteLine(xmp.GetNamespaceURIByPrefix("xmp"));
```

### Siehe auch

* Klasse [PdfXmpMetadata](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)