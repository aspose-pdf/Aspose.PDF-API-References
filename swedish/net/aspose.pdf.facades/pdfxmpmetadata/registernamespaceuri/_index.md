---
title: "PdfXmpMetadata.RegisterNamespaceURI"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfXmpMetadata metod. Registrerar namnrymdens URI"
type: docs
weight: 200
url: /sv/net/aspose.pdf.facades/pdfxmpmetadata/registernamespaceuri/
---
## PdfXmpMetadata.RegisterNamespaceURI method

Registrerar namespace‑URI.

```csharp
public void RegisterNamespaceURI(string prefix, string namespaceURI)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| prefix | String | Prefixet. |
| namespaceURI | String | Namnrummets URI. |

## Exempel

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
xmp.RegisterNamespaceURI("xmp", "http://ns.adobe.com/xap/1.0/");
```

### Se även

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


