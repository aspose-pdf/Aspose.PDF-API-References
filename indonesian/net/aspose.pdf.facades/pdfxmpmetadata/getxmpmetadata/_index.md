---
title: PdfXmpMetadata.GetXmpMetadata
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfXmpMetadata. Dapatkan XmpMetadata dari pdf input dalam format xml
type: docs
weight: 190
url: /id/net/aspose.pdf.facades/pdfxmpmetadata/getxmpmetadata/
---
## GetXmpMetadata() {#getxmpmetadata}

Dapatkan XmpMetadata dari pdf input dalam format xml.

```csharp
public byte[] GetXmpMetadata()
```

### Return Value

Byte dari XmpMetadata.

## Contoh

```csharp
PdfXmpMetadata pxm = new PdfXmpMetadata();
pxm.BindPdf("PdfFile.pdf");
byte[] data = pxm.GetXmpMetadata();
```

### Lihat Juga

* kelas [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetXmpMetadata(string) {#getxmpmetadata_1}

Dapatkan bagian dari XmpMetadata dari pdf input sesuai dengan nama meta.

```csharp
public byte[] GetXmpMetadata(string name)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | String | Nama metadata. |

### Return Value

Byte dari metadata.

## Contoh

```csharp
PdfXmpMetadata pxm = new PdfXmpMetadata();
pxm.BindPdf("PdfFile.pdf");
byte[] data = pxm.GetXmpMetadata("dc:creator");
```

### Lihat Juga

* kelas [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)