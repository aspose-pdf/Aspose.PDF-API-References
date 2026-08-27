---
title: "PdfXmpMetadata.GetXmpMetadata"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode PdfXmpMetadata. Mendapatkan XmpMetadata dari PDF masukan dalam format XML"
type: docs
weight: 190
url: /id/net/aspose.pdf.facades/pdfxmpmetadata/getxmpmetadata/
---
## GetXmpMetadata() {#getxmpmetadata}

Dapatkan XmpMetadata dari pdf input dalam format xml.

```csharp
public byte[] GetXmpMetadata()
```

### Nilai Kembalian

Byte dari XmpMetadata.

## Contoh

```csharp
PdfXmpMetadata pxm = new PdfXmpMetadata();
pxm.BindPdf("PdfFile.pdf");
byte[] data = pxm.GetXmpMetadata();
```

### Lihat Juga

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetXmpMetadata(string) {#getxmpmetadata_1}

Dapatkan bagian dari XmpMetadata pdf input sesuai dengan nama meta.

```csharp
public byte[] GetXmpMetadata(string name)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | String | Nama metadata. |

### Nilai Kembalian

Byte metadata.

## Contoh

```csharp
PdfXmpMetadata pxm = new PdfXmpMetadata();
pxm.BindPdf("PdfFile.pdf");
byte[] data = pxm.GetXmpMetadata("dc:creator");
```

### Lihat Juga

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


