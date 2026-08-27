---
title: "Stamp.BindPdf"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode Stamp. Menetapkan file PDF dan nomor halaman yang akan digunakan sebagai stamp"
type: docs
weight: 120
url: /id/net/aspose.pdf.facades/stamp/bindpdf/
---
## BindPdf(string, int) {#bindpdf_1}

Mengatur file PDF dan nomor halaman yang akan digunakan sebagai stempel.

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
//Halaman pertama akan digunakan sebagai stamp.
stamp.BindPdf("stamp.pdf", 1);
stamp.IsBackground = true;
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### Lihat Juga

* class [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## BindPdf(Stream, int) {#bindpdf}

Mengatur file PDF dan nomor halaman yang akan digunakan sebagai stempel.

```csharp
public void BindPdf(Stream pdfStream, int pageNumber)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pdfStream | Stream | Stream yang berisi dokumen PDF. |
| pageNumber | Int32 | Indeks halaman dokumen yang akan digunakan sebagai stamp. |

## Contoh

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
//Halaman pertama akan digunakan sebagai stamp.
Stream stream = new FileStream("stamp.pdf", FileMode.Open, FileAccess.Read);
stamp.BindPdf(stream, 1);
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### Lihat Juga

* class [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


