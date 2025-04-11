---
title: PdfXmpMetadata.GetNamespaceURIByPrefix
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfXmpMetadata. Mendapatkan URI namespace berdasarkan prefix
type: docs
weight: 170
url: /id/net/aspose.pdf.facades/pdfxmpmetadata/getnamespaceuribyprefix/
---
## Metode PdfXmpMetadata.GetNamespaceURIByPrefix

Mendapatkan URI namespace berdasarkan prefix.

```csharp
public string GetNamespaceURIByPrefix(string prefix)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| prefix | String | Prefix. |

### Nilai Kembali

URI namespace.

## Contoh

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
Console.WriteLine(xmp.GetNamespaceURIByPrefix("xmp"));
```

### Lihat Juga

* kelas [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)