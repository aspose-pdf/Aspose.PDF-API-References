---
title: PdfXmpMetadata.GetPrefixByNamespaceURI
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfXmpMetadata. Mendapatkan prefix berdasarkan namespace URI
type: docs
weight: 180
url: /id/net/aspose.pdf.facades/pdfxmpmetadata/getprefixbynamespaceuri/
---
## Metode PdfXmpMetadata.GetPrefixByNamespaceURI

Mendapatkan prefix berdasarkan namespace URI.

```csharp
public string GetPrefixByNamespaceURI(string namespaceURI)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| namespaceURI | String | Namespace URI. |

### Nilai Kembali

Nilai prefix.

## Contoh

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
Console.WriteLine(xmp.GetPrefixByNamespaceURI("http://ns.adobe.com/xap/1.0/"));
```

### Lihat Juga

* kelas [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)