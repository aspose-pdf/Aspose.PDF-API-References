---
title: Stamp.BindPdf
second_title: Aspose.PDF for .NET API Reference
description: Metode Stamp. Mengatur file PDF dan nomor halaman yang akan digunakan sebagai cap
type: docs
weight: 120
url: /id/net/aspose.pdf.facades/stamp/bindpdf/
---
## BindPdf(string, int) {#bindpdf_1}

Mengatur file PDF dan nomor halaman yang akan digunakan sebagai cap.

```csharp
public void BindPdf(string pdfFile, int pageNumber)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pdfFile | String | Jalur ke file PDF. |
| pageNumber | Int32 | Nomor halaman dalam file PDF |

## Contoh

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
//First page will be used as stamp.
stamp.BindPdf("stamp.pdf", 1);
stamp.IsBackground = true;
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### Lihat Juga

* kelas [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## BindPdf(Stream, int) {#bindpdf}

Mengatur file PDF dan nomor halaman yang akan digunakan sebagai cap.

```csharp
public void BindPdf(Stream pdfStream, int pageNumber)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pdfStream | Stream | Stream yang berisi dokumen PDF. |
| pageNumber | Int32 | Indeks halaman dari dokumen yang akan digunakan sebagai cap. |

## Contoh

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
//First page will be used as stamp.
Stream stream = new FileStream("stamp.pdf", FileMode.Open, FileAccess.Read);
stamp.BindPdf(stream, 1);
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### Lihat Juga

* kelas [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)