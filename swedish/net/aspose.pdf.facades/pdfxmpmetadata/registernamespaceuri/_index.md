---
title: PdfXmpMetadata.RegisterNamespaceURI
second_title: Aspose.PDF for .NET API Reference
description: PdfXmpMetadata-metod. Registrerar namespace URI
type: docs
weight: 200
url: /sv/net/aspose.pdf.facades/pdfxmpmetadata/registernamespaceuri/
---
## PdfXmpMetadata.RegisterNamespaceURI metod

Registrerar namespace URI.

```csharp
public void RegisterNamespaceURI(string prefix, string namespaceURI)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| prefix | Sträng | Prefixet. |
| namespaceURI | Sträng | Namespace URI. |

## Exempel

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
xmp.RegisterNamespaceURI("xmp", "http://ns.adobe.com/xap/1.0/");
```

### Se Även

* klass [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)