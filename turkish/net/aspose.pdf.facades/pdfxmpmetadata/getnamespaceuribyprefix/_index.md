---
title: PdfXmpMetadata.GetNamespaceURIByPrefix
second_title: Aspose.PDF for .NET API Reference
description: PdfXmpMetadata metodu. Önek ile ad alanı URI'sini alır
type: docs
weight: 170
url: /tr/net/aspose.pdf.facades/pdfxmpmetadata/getnamespaceuribyprefix/
---
## PdfXmpMetadata.GetNamespaceURIByPrefix metodu

Önek ile ad alanı URI'sini alır.

```csharp
public string GetNamespaceURIByPrefix(string prefix)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| prefix | String | Önek. |

### Dönüş Değeri

Ad alanı URI'si.

## Örnekler

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
Console.WriteLine(xmp.GetNamespaceURIByPrefix("xmp"));
```

### Ayrıca Bakınız

* sınıf [PdfXmpMetadata](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)