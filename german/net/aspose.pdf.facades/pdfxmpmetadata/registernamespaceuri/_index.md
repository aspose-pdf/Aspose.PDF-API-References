---
title: PdfXmpMetadata.RegisterNamespaceURI
second_title: Aspose.PDF for .NET API Reference
description: PdfXmpMetadata-Methode. Registriert die Namespace-URI
type: docs
weight: 200
url: /de/net/aspose.pdf.facades/pdfxmpmetadata/registernamespaceuri/
---
## PdfXmpMetadata.RegisterNamespaceURI-Methode

Registriert die Namespace-URI.

```csharp
public void RegisterNamespaceURI(string prefix, string namespaceURI)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| prefix | String | Das Präfix. |
| namespaceURI | String | Die Namespace-URI. |

## Beispiele

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
xmp.RegisterNamespaceURI("xmp", "http://ns.adobe.com/xap/1.0/");
```

### Siehe auch

* Klasse [PdfXmpMetadata](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)