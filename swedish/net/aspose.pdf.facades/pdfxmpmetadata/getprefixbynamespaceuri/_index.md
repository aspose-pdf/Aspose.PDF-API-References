---
title: "PdfXmpMetadata.GetPrefixByNamespaceURI"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfXmpMetadata metod. Hämtar prefixet via namnrymds-URI"
type: docs
weight: 180
url: /sv/net/aspose.pdf.facades/pdfxmpmetadata/getprefixbynamespaceuri/
---
## PdfXmpMetadata.GetPrefixByNamespaceURI method

Hämtar prefixet med namespace‑URI.

```csharp
public string GetPrefixByNamespaceURI(string namespaceURI)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namespaceURI | String | Namnrymds-URI. |

### Returvärde

Prefixvärdet.

## Exempel

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
Console.WriteLine(xmp.GetPrefixByNamespaceURI("http://ns.adobe.com/xap/1.0/"));
```

### Se även

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


