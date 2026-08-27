---
title: "PdfConverter.SaveAsTIFFClassF"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode PdfConverter. Mengonversi setiap halaman dokumen pdf menjadi gambar dan menyimpan gambar ke satu file TIFF ClassF."
type: docs
weight: 170
url: /id/net/aspose.pdf.facades/pdfconverter/saveastiffclassf/
---
## SaveAsTIFFClassF(string, int, int) {#saveastiffclassf_5}

Mengonversi setiap Page dari sebuah pdf Document menjadi gambar dan menyimpan gambar ke satu file TIFF ClassF.

```csharp
public void SaveAsTIFFClassF(string outputFile, int imageWidth, int imageHeight)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputFile | String | Stream untuk menyimpan gambar TIFF. |
| imageWidth | Int32 | Lebar gambar, satuannya pixel. |
| imageHeight | Int32 | Tinggi gambar, satuannya pixel. |

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

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(string, PageSize) {#saveastiffclassf_4}

Mengonversi setiap Page dari sebuah pdf Document menjadi gambar dan menyimpan gambar ke satu file TIFF ClassF.

```csharp
public void SaveAsTIFFClassF(string outputFile, PageSize pageSize)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputFile | String | Stream untuk menyimpan gambar TIFF. |
| pageSize | PageSize | Ukuran halaman gambar. |

### Lihat Juga

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(Stream, int, int) {#saveastiffclassf_2}

Mengonversi setiap Page dari sebuah pdf Document menjadi gambar dan menyimpan gambar ke satu stream TIFF ClassF.

```csharp
public void SaveAsTIFFClassF(Stream outputStream, int imageWidth, int imageHeight)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputStream | Stream | Stream untuk menyimpan gambar TIFF. |
| imageWidth | Int32 | Lebar gambar, satuannya pixel. |
| imageHeight | Int32 | Tinggi gambar, satuannya pixel. |

### Lihat Juga

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(Stream, PageSize) {#saveastiffclassf_1}

Mengonversi setiap Page dari sebuah pdf Document menjadi gambar dan menyimpan gambar ke satu stream TIFF ClassF.

```csharp
public void SaveAsTIFFClassF(Stream outputStream, PageSize pageSize)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputStream | Stream | Stream untuk menyimpan gambar TIFF. |
| pageSize | PageSize | Ukuran halaman gambar. |

### Lihat Juga

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(string) {#saveastiffclassf_3}

Mengonversi setiap Page dari sebuah pdf Document menjadi gambar dan menyimpan gambar ke satu file TIFF ClassF.

```csharp
public void SaveAsTIFFClassF(string outputFile)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputFile | String | Stream untuk menyimpan gambar TIFF. |

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

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(Stream) {#saveastiffclassf}

Mengonversi setiap Page dari sebuah pdf Document menjadi gambar dan menyimpan gambar ke satu stream TIFF ClassF.

```csharp
public void SaveAsTIFFClassF(Stream outputStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputStream | Stream | Stream untuk menyimpan gambar TIFF. |

### Lihat Juga

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


