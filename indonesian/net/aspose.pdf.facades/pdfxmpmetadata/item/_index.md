---
title: PdfXmpMetadata.Item
second_title: Aspose.PDF for .NET API Reference
description: Properti PdfXmpMetadata. Mengambil atau mengatur nilai berdasarkan kunci
type: docs
weight: 70
url: /id/net/aspose.pdf.facades/pdfxmpmetadata/item/
---
## PdfXmpMetadata indexer (1 dari 2)

Mengambil atau mengatur nilai berdasarkan kunci.

```csharp
public XmpValue this[string key] { get; set; }
```

| Parameter | Deskripsi |
| --- | --- |
| key | Nama kunci untuk mengambil/mengatur. |

### Nilai Kembali

Objek berdasarkan kunci

## Contoh

```csharp
PdfXmpMetadata pxm = new PdfXmpMetadata();
pxm.BindPdf("PdfFile.pdf");
Console.WriteLine(pxm["xmp:Nickname"]);
```

### Lihat Juga

* kelas [XmpValue](../../../aspose.pdf/xmpvalue/)
* kelas [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PdfXmpMetadata indexer (2 dari 2)

Mengambil nilai metadata XMP berdasarkan kunci.

```csharp
public XmpValue this[DefaultMetadataProperties key] { get; set; }
```

| Parameter | Deskripsi |
| --- | --- |
| key | Kunci dari nilai. |

### Nilai Kembali

Nilai dari metadata XMP.

## Contoh

```csharp
PdfXmpMetadata pxm = new PdfXmpMetadata();
pxm.BindPdf("PdfFile.pdf");
Console.WriteLine(pxm[DefaultMetadataProperties.CreatorTool]);
```

### Lihat Juga

* kelas [XmpValue](../../../aspose.pdf/xmpvalue/)
* enum [DefaultMetadataProperties](../../defaultmetadataproperties/)
* kelas [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)