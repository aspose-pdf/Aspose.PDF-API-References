---
title: PdfXmpMetadata.GetPrefixByNamespaceURI
second_title: Aspose.PDF for .NET API Reference
description: PdfXmpMetadata-metod. Hämtar prefixet efter namnrymds-URI
type: docs
weight: 180
url: /sv/net/aspose.pdf.facades/pdfxmpmetadata/getprefixbynamespaceuri/
---
## PdfXmpMetadata.GetPrefixByNamespaceURI metod

Hämtar prefixet efter namnrymds-URI.

```csharp
public string GetPrefixByNamespaceURI(string namespaceURI)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namespaceURI | Sträng | Namnrymds-URI. |

### Returvärde

Prefixvärdet.

## Exempel

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
Console.WriteLine(xmp.GetPrefixByNamespaceURI("http://ns.adobe.com/xap/1.0/"));
```

### Se Även

* klass [PdfXmpMetadata](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)