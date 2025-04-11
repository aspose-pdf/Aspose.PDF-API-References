---
title: PdfXmpMetadata.GetPrefixByNamespaceURI
second_title: Aspose.PDF for .NET API Reference
description: PdfXmpMetadata metodu. Namespace URI ile ön eki alır
type: docs
weight: 180
url: /tr/net/aspose.pdf.facades/pdfxmpmetadata/getprefixbynamespaceuri/
---
## PdfXmpMetadata.GetPrefixByNamespaceURI metodu

Namespace URI ile ön eki alır.

```csharp
public string GetPrefixByNamespaceURI(string namespaceURI)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| namespaceURI | String | Namespace URI. |

### Dönüş Değeri

Ön ek değeri.

## Örnekler

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
Console.WriteLine(xmp.GetPrefixByNamespaceURI("http://ns.adobe.com/xap/1.0/"));
```

### Ayrıca Bakınız

* sınıf [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)