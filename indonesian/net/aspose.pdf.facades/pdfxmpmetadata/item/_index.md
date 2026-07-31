---
title: "PdfXmpMetadata.Item"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Properti PdfXmpMetadata. Mendapatkan atau mengatur nilai berdasarkan kunci"
type: docs
weight: 70
url: /id/net/aspose.pdf.facades/pdfxmpmetadata/item/
---
## PdfXmpMetadata indexer (1 of 2)

Mendapatkan atau mengatur nilai berdasarkan kunci.

```csharp
public XmpValue this[string key] { get; set; }
```

| Parameter | Deskripsi |
| --- | --- |
| kunci | Nama kunci untuk mengambil/menetapkan. |

### Nilai Kembalian

Objek berdasarkan kunci

## Contoh

```csharp
PdfXmpMetadata pxm = new PdfXmpMetadata();
pxm.BindPdf("PdfFile.pdf");
Console.WriteLine(pxm["xmp:Nickname"]);
```

### Lihat Juga

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PdfXmpMetadata indexer (2 of 2)

Mendapatkan nilai metadata XMP berdasarkan kunci.

```csharp
public XmpValue this[DefaultMetadataProperties key] { get; set; }
```

| Parameter | Deskripsi |
| --- | --- |
| kunci | Kunci nilai. |

### Nilai Kembalian

Nilai dari metadata XMP.

## Contoh

```csharp
PdfXmpMetadata pxm = new PdfXmpMetadata();
pxm.BindPdf("PdfFile.pdf");
Console.WriteLine(pxm[DefaultMetadataProperties.CreatorTool]);
```

### Lihat Juga

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* enum [DefaultMetadataProperties](../../defaultmetadataproperties/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


