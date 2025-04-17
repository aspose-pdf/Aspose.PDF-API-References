---
title: PdfExtractor.GetNextImage
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfExtractor. Mengambil gambar berikutnya dari dokumen PDF. Catatan ExtractImage harus dipanggil sebelum menggunakan metode ini
type: docs
weight: 170
url: /id/net/aspose.pdf.facades/pdfextractor/getnextimage/
---
## GetNextImage(string) {#getnextimage_2}

Mengambil gambar berikutnya dari dokumen PDF. Catatan: ExtractImage harus dipanggil sebelum menggunakan metode ini.

```csharp
public bool GetNextImage(string outputFile)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputFile | String | File tempat gambar akan disimpan |

### Nilai Kembali

True jika gambar berhasil diekstrak

## Contoh

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf("sample.pdf");
extractor.ExtractImage();
int i = 1;
while (extractor.HasNextImage())
{
    extractor.GetNextImage("image-" + i +".pdf");
}
```

### Lihat Juga

* kelas [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat) {#getnextimage_3}

Mengambil gambar berikutnya dari dokumen PDF dengan format gambar yang diberikan. Catatan: ExtractImage harus dipanggil sebelum menggunakan metode ini.

```csharp
public bool GetNextImage(string outputFile, ImageFormat format)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputFile | String | File tempat gambar akan disimpan |
| format | ImageFormat | Format gambar. |

### Nilai Kembali

True jika gambar berhasil diekstrak

### Lihat Juga

* kelas [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat) {#getnextimage_1}

Mengambil gambar berikutnya dari file PDF dan menyimpannya ke dalam stream dengan format gambar yang diberikan.

```csharp
public bool GetNextImage(Stream outputStream, ImageFormat format)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputStream | Stream | Stream tempat data gambar akan disimpan |
| format | ImageFormat | Format gambar. |

### Nilai Kembali

True jika gambar berhasil diekstrak.

### Lihat Juga

* kelas [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream) {#getnextimage}

Mengambil gambar berikutnya dari file PDF dan menyimpannya ke dalam stream.

```csharp
public bool GetNextImage(Stream outputStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputStream | Stream | Stream tempat data gambar akan disimpan |

### Nilai Kembali

True jika gambar berhasil diekstrak.

### Lihat Juga

* kelas [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)