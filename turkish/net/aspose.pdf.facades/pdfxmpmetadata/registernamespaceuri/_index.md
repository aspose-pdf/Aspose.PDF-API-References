---
title: PdfXmpMetadata.RegisterNamespaceURI
second_title: Aspose.PDF for .NET API Reference
description: PdfXmpMetadata metodu. Ad alanı URI'sını kaydeder
type: docs
weight: 200
url: /tr/net/aspose.pdf.facades/pdfxmpmetadata/registernamespaceuri/
---
## PdfXmpMetadata.RegisterNamespaceURI metodu

Ad alanı URI'sını kaydeder.

```csharp
public void RegisterNamespaceURI(string prefix, string namespaceURI)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| prefix | String | Önek. |
| namespaceURI | String | Ad alanı URI'sı. |

## Örnekler

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
xmp.RegisterNamespaceURI("xmp", "http://ns.adobe.com/xap/1.0/");
```

### Ayrıca Bakınız

* sınıf [PdfXmpMetadata](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)