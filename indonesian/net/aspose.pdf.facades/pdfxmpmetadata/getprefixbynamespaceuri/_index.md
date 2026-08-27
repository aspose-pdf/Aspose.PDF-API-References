---
title: "PdfXmpMetadata.GetPrefixByNamespaceURI"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode PdfXmpMetadata. Mengambil awalan berdasarkan namespace URI"
type: docs
weight: 180
url: /id/net/aspose.pdf.facades/pdfxmpmetadata/getprefixbynamespaceuri/
---
## PdfXmpMetadata.GetPrefixByNamespaceURI method

Mendapatkan prefiks berdasarkan URI namespace.

```csharp
public string GetPrefixByNamespaceURI(string namespaceURI)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| namespaceURI | String | Namespace URI. |

### Nilai Kembalian

Nilai awalan.

## Contoh

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
Console.WriteLine(xmp.GetPrefixByNamespaceURI("http://ns.adobe.com/xap/1.0/"));
```

### Lihat Juga

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


