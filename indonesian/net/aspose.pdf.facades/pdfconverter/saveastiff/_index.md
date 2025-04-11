---
title: PdfConverter.SaveAsTIFF
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfConverter. Mengonversi setiap halaman dokumen pdf menjadi gambar dan menyimpan gambar ke dalam satu file TIFF
type: docs
weight: 160
url: /id/net/aspose.pdf.facades/pdfconverter/saveastiff/
---
## SaveAsTIFF(string) {#saveastiff_10}

Mengonversi setiap halaman dokumen pdf menjadi gambar dan menyimpan gambar ke dalam satu file TIFF.

```csharp
public void SaveAsTIFF(string outputFile)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputFile | String | File untuk menyimpan gambar TIFF. |

## Contoh

```csharp
[C#]
PdfConverter converter = new PdfConverter();
converter.BindPdf(@"D:\Test\test.pdf");
converter.DoConvert();
converter.SaveAsTIFF(@"D:\Test\test.tiff");	

[Visual Basic]
Dim converter As PdfConverter =  New PdfConverter() 
converter.BindPdf("D:\Test\test.pdf")
converter.DoConvert()
converter.SaveAsTIFF(@"D:\Test\test.tiff")
```

### Lihat Juga

* kelas [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, CompressionType) {#saveastiff_11}

Mengonversi setiap halaman dokumen pdf menjadi gambar dan menyimpan gambar ke dalam satu file TIFF.

```csharp
public void SaveAsTIFF(string outputFile, CompressionType compressionType)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputFile | String | File keluaran. |
| compressionType | CompressionType | Tipe kompresi. |

## Contoh

```csharp
[C#]
PdfConverter converter = new PdfConverter();
converter.BindPdf(@"D:\Test\test.pdf");
converter.DoConvert();
converter.SaveAsTIFF(@"D:\Test\test.tiff");
[Visual Basic]
Dim converter As PdfConverter =  New PdfConverter()
converter.BindPdf("D:\Test\test.pdf")
converter.DoConvert()
converter.SaveAsTIFF(@"D:\Test\test.tiff")
```

### Lihat Juga

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype/)
* kelas [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int) {#saveastiff_16}

Mengonversi setiap halaman dokumen pdf menjadi gambar dengan dimensi, dan menyimpan gambar ke dalam satu file TIFF.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputFile | String | Nama file untuk menyimpan gambar TIFF |
| imageWidth | Int32 | Lebar gambar, satuan dalam piksel. |
| imageHeight | Int32 | Tinggi gambar, satuan dalam piksel. |

### Lihat Juga

* kelas [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, PageSize) {#saveastiff_14}

Mengonversi setiap halaman dokumen pdf menjadi gambar dengan ukuran halaman dan menyimpan gambar ke dalam satu file TIFF.

```csharp
public void SaveAsTIFF(string outputFile, PageSize pageSize)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputFile | String | Nama file untuk menyimpan gambar TIFF |
| pageSize | PageSize | Ukuran halaman gambar. |

### Lihat Juga

* kelas [PageSize](../../../aspose.pdf/pagesize/)
* kelas [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, PageSize, TiffSettings) {#saveastiff_15}

Mengonversi setiap halaman dokumen pdf menjadi gambar dengan ukuran halaman dan menyimpan gambar ke dalam satu file TIFF.

```csharp
public void SaveAsTIFF(string outputFile, PageSize pageSize, TiffSettings settings)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputFile | String | Nama file untuk menyimpan gambar TIFF |
| pageSize | PageSize | Ukuran halaman gambar. |
| settings | TiffSettings | Objek pengaturan yang mendefinisikan parameter TIFF. |

### Lihat Juga

* kelas [PageSize](../../../aspose.pdf/pagesize/)
* kelas [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* kelas [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int, CompressionType) {#saveastiff_17}

Mengonversi setiap halaman dokumen pdf menjadi gambar dengan dimensi, dan menyimpan gambar ke dalam satu file TIFF.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight, 
    CompressionType compressionType)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputFile | String | Nama file untuk menyimpan gambar TIFF |
| imageWidth | Int32 | Lebar gambar, satuan dalam piksel. |
| imageHeight | Int32 | Tinggi gambar, satuan dalam piksel. |
| compressionType | CompressionType | Tipe kompresi. |

### Lihat Juga

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype/)
* kelas [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int, TiffSettings) {#saveastiff_18}

Mengonversi setiap halaman dokumen pdf menjadi gambar dengan dimensi, dan menyimpan gambar ke dalam satu file TIFF.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight, TiffSettings settings)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputFile | String | Nama file untuk menyimpan gambar TIFF |
| imageWidth | Int32 | Lebar gambar, satuan dalam piksel. |
| imageHeight | Int32 | Tinggi gambar, satuan dalam piksel. |
| settings | TiffSettings | Objek pengaturan yang mendefinisikan parameter TIFF. |

### Lihat Juga

* kelas [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* kelas [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int, TiffSettings, IIndexBitmapConverter) {#saveastiff_19}

Mengonversi setiap halaman dokumen pdf menjadi gambar dengan dimensi, dan menyimpan gambar ke dalam satu file TIFF.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight, TiffSettings settings, 
    IIndexBitmapConverter converter)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputFile | String | Nama file untuk menyimpan gambar TIFF |
| imageWidth | Int32 | Lebar gambar, satuan dalam piksel. |
| imageHeight | Int32 | Tinggi gambar, satuan dalam piksel. |
| settings | TiffSettings | Objek pengaturan yang mendefinisikan parameter TIFF. |
| converter | IIndexBitmapConverter | Konverter eksternal |

### Lihat Juga

* kelas [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter/)
* kelas [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream) {#saveastiff}

Mengonversi setiap halaman dokumen pdf menjadi gambar dan menyimpan gambar ke dalam satu aliran TIFF.

```csharp
public void SaveAsTIFF(Stream outputStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputStream | Stream | Aliran untuk menyimpan gambar TIFF. |

### Lihat Juga

* kelas [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, CompressionType) {#saveastiff_1}

Mengonversi setiap halaman dokumen pdf menjadi gambar dan menyimpan gambar ke dalam satu file TIFF.

```csharp
public void SaveAsTIFF(Stream outputStream, CompressionType compressionType)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputStream | Stream | Aliran keluaran. |
| compressionType | CompressionType | Tipe kompresi. |

### Lihat Juga

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype/)
* kelas [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, PageSize) {#saveastiff_4}

Mengonversi setiap halaman dokumen pdf menjadi gambar dengan ukuran halaman dan menyimpan gambar ke dalam satu aliran TIFF.

```csharp
public void SaveAsTIFF(Stream outputStream, PageSize pageSize)
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

## SaveAsTIFF(Stream, PageSize, TiffSettings) {#saveastiff_5}

Mengonversi setiap halaman dokumen pdf menjadi gambar dengan ukuran halaman dan menyimpan gambar ke dalam satu aliran TIFF.

```csharp
public void SaveAsTIFF(Stream outputStream, PageSize pageSize, TiffSettings settings)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputStream | Stream | Aliran untuk menyimpan gambar TIFF. |
| pageSize | PageSize | Ukuran halaman gambar. |
| settings | TiffSettings | Objek pengaturan yang mendefinisikan parameter TIFF. |

### Lihat Juga

* kelas [PageSize](../../../aspose.pdf/pagesize/)
* kelas [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* kelas [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int) {#saveastiff_6}

Mengonversi setiap halaman dokumen pdf menjadi gambar dengan dimensi, dan menyimpan gambar ke dalam satu aliran TIFF.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputStream | Stream | Aliran untuk menyimpan gambar TIFF. |
| imageWidth | Int32 | Lebar gambar, satuan dalam piksel. |
| imageHeight | Int32 | Tinggi gambar, satuan dalam piksel. |

### Lihat Juga

* kelas [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int, CompressionType) {#saveastiff_7}

Mengonversi setiap halaman dokumen pdf menjadi gambar dengan dimensi, dan menyimpan gambar ke dalam satu aliran TIFF.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight, 
    CompressionType compressionType)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputStream | Stream | Aliran untuk menyimpan gambar TIFF. |
| imageWidth | Int32 | Lebar gambar, satuan dalam piksel. |
| imageHeight | Int32 | Tinggi gambar, satuan dalam piksel. |
| compressionType | CompressionType | Tipe kompresi. |

### Lihat Juga

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype/)
* kelas [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int, TiffSettings) {#saveastiff_8}

Mengonversi setiap halaman dokumen pdf menjadi gambar dengan dimensi, dan menyimpan gambar ke dalam satu aliran TIFF.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight, TiffSettings settings)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputStream | Stream | Aliran untuk menyimpan gambar TIFF. |
| imageWidth | Int32 | Lebar gambar, satuan dalam piksel. |
| imageHeight | Int32 | Tinggi gambar, satuan dalam piksel. |
| settings | TiffSettings | Objek pengaturan yang mendefinisikan parameter TIFF. |

### Lihat Juga

* kelas [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* kelas [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int, TiffSettings, IIndexBitmapConverter) {#saveastiff_9}

Mengonversi setiap halaman dokumen pdf menjadi gambar dengan dimensi, dan menyimpan gambar ke dalam satu aliran TIFF.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight, TiffSettings settings, 
    IIndexBitmapConverter converter)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputStream | Stream | Aliran untuk menyimpan gambar TIFF. |
| imageWidth | Int32 | Lebar gambar, satuan dalam piksel. |
| imageHeight | Int32 | Tinggi gambar, satuan dalam piksel. |
| settings | TiffSettings | Objek pengaturan yang mendefinisikan parameter TIFF. |
| converter | IIndexBitmapConverter | Konverter eksternal |

### Lihat Juga

* kelas [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter/)
* kelas [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, TiffSettings) {#saveastiff_12}

Mengonversi setiap halaman dokumen pdf menjadi gambar dan menyimpan gambar ke dalam satu file TIFF.

```csharp
public void SaveAsTIFF(string outputFile, TiffSettings settings)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputFile | String | Nama file untuk menyimpan gambar TIFF |
| settings | TiffSettings | Objek pengaturan yang mendefinisikan parameter TIFF. |

### Lihat Juga

* kelas [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* kelas [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, TiffSettings, IIndexBitmapConverter) {#saveastiff_13}

Mengonversi setiap halaman dokumen pdf menjadi gambar dan menyimpan gambar ke dalam satu file TIFF.

```csharp
public void SaveAsTIFF(string outputFile, TiffSettings settings, IIndexBitmapConverter converter)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputFile | String | Nama file untuk menyimpan gambar TIFF |
| settings | TiffSettings | Objek pengaturan yang mendefinisikan parameter TIFF. |
| converter | IIndexBitmapConverter | Konverter eksternal |

### Lihat Juga

* kelas [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter/)
* kelas [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, TiffSettings) {#saveastiff_2}

Mengonversi setiap halaman dokumen pdf menjadi gambar dan menyimpan gambar ke dalam satu aliran TIFF.

```csharp
public void SaveAsTIFF(Stream outputStream, TiffSettings settings)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputStream | Stream | Aliran untuk menyimpan gambar TIFF. |
| settings | TiffSettings | Objek pengaturan yang mendefinisikan parameter TIFF. |

### Lihat Juga

* kelas [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* kelas [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, TiffSettings, IIndexBitmapConverter) {#saveastiff_3}

Mengonversi setiap halaman dokumen pdf menjadi gambar dan menyimpan gambar ke dalam satu aliran TIFF.

```csharp
public void SaveAsTIFF(Stream outputStream, TiffSettings settings, IIndexBitmapConverter converter)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputStream | Stream | Aliran untuk menyimpan gambar TIFF. |
| settings | TiffSettings | Objek pengaturan yang mendefinisikan parameter TIFF. |
| converter | IIndexBitmapConverter | Konverter eksternal |

### Lihat Juga

* kelas [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter/)
* kelas [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)