---
title: PdfXmpMetadata.GetPrefixByNamespaceURI
second_title: Aspose.PDF for .NET API Reference
description: PdfXmpMetadata-Methode. Holt das Präfix anhand der Namespace-URI
type: docs
weight: 180
url: /de/net/aspose.pdf.facades/pdfxmpmetadata/getprefixbynamespaceuri/
---
## PdfXmpMetadata.GetPrefixByNamespaceURI-Methode

Holt das Präfix anhand der Namespace-URI.

```csharp
public string GetPrefixByNamespaceURI(string namespaceURI)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| namespaceURI | String | Namespace-URI. |

### Rückgabewert

Der Präfixwert.

## Beispiele

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
Console.WriteLine(xmp.GetPrefixByNamespaceURI("http://ns.adobe.com/xap/1.0/"));
```

### Siehe auch

* Klasse [PdfXmpMetadata](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)