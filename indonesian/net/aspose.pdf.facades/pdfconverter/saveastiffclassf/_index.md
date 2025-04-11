---
title: PdfConverter.SaveAsTIFFClassF
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfConverter. Mengonversi setiap halaman dokumen pdf menjadi gambar dan menyimpan gambar ke dalam satu file TIFF ClassF
type: docs
weight: 170
url: /id/net/aspose.pdf.facades/pdfconverter/saveastiffclassf/
---
## SaveAsTIFFClassF(string, int, int) {#saveastiffclassf_5}

Mengonversi setiap halaman dokumen pdf menjadi gambar dan menyimpan gambar ke dalam satu file TIFF ClassF.

```csharp
public void SaveAsTIFFClassF(string outputFile, int imageWidth, int imageHeight)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputFile | String | Aliran untuk menyimpan gambar TIFF. |
| imageWidth | Int32 | Lebar gambar, satuan adalah piksel. |
| imageHeight | Int32 | Tinggi gambar, satuan adalah piksel. |

## Contoh

```csharp
[C#]
PdfConverter converter = new PdfConverter();
converter.BindPdf(@"D:\Test\test.pdf");
converter.DoConvert();
converter.SaveAsTIFFClassF(@"D:\Test\test.tiff",204,196);	

[Visual Basic]
Dim converter As PdfConverter =  New PdfConverter() 
converter.BindPdf("D:\Test\test.pdf")
converter.DoConvert()
converter.SaveAsTIFFClassF(@"D:\Test\test.tiff",204,196)
```

### Lihat Juga

* kelas [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(string, PageSize) {#saveastiffclassf_4}

Mengonversi setiap halaman dokumen pdf menjadi gambar dan menyimpan gambar ke dalam satu file TIFF ClassF.

```csharp
public void SaveAsTIFFClassF(string outputFile, PageSize pageSize)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputFile | String | Aliran untuk menyimpan gambar TIFF. |
| pageSize | PageSize | Ukuran halaman gambar. |

### Lihat Juga

* kelas [PageSize](../../../aspose.pdf/pagesize/)
* kelas [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(Stream, int, int) {#saveastiffclassf_2}

Mengonversi setiap halaman dokumen pdf menjadi gambar dan menyimpan gambar ke dalam satu aliran TIFF ClassF.

```csharp
public void SaveAsTIFFClassF(Stream outputStream, int imageWidth, int imageHeight)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputStream | Stream | Aliran untuk menyimpan gambar TIFF. |
| imageWidth | Int32 | Lebar gambar, satuan adalah piksel. |
| imageHeight | Int32 | Tinggi gambar, satuan adalah piksel. |

### Lihat Juga

* kelas [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(Stream, PageSize) {#saveastiffclassf_1}

Mengonversi setiap halaman dokumen pdf menjadi gambar dan menyimpan gambar ke dalam satu aliran TIFF ClassF.

```csharp
public void SaveAsTIFFClassF(Stream outputStream, PageSize pageSize)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputStream | Stream | Aliran untuk menyimpan gambar TIFF. |
| pageSize | PageSize | Ukuran halaman gambar. |

### Lihat Juga

* kelas [PageSize](../../../aspose.pdf/pagesize/)
* kelas [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(string) {#saveastiffclassf_3}

Mengonversi setiap halaman dokumen pdf menjadi gambar dan menyimpan gambar ke dalam satu file TIFF ClassF.

```csharp
public void SaveAsTIFFClassF(string outputFile)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputFile | String | Aliran untuk menyimpan gambar TIFF. |

## Contoh

```csharp
[C#]
PdfConverter converter = new PdfConverter();
converter.BindPdf(@"D:\Test\test.pdf");
converter.DoConvert();
converter.SaveAsTIFFClassF(@"D:\Test\test.tiff");	

[Visual Basic]
Dim converter As PdfConverter =  New PdfConverter() 
converter.BindPdf("D:\Test\test.pdf")
converter.DoConvert()
converter.SaveAsTIFFClassF(@"D:\Test\test.tiff")
```

### Lihat Juga

* kelas [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(Stream) {#saveastiffclassf}

Mengonversi setiap halaman dokumen pdf menjadi gambar dan menyimpan gambar ke dalam satu aliran TIFF ClassF.

```csharp
public void SaveAsTIFFClassF(Stream outputStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputStream | Stream | Aliran untuk menyimpan gambar TIFF. |

### Lihat Juga

* kelas [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)