---
title: "PdfConverter.SaveAsTIFF"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode PdfConverter. Mengonversi setiap halaman dokumen pdf menjadi gambar dan menyimpan gambar ke satu file TIFF"
type: docs
weight: 160
url: /id/net/aspose.pdf.facades/pdfconverter/saveastiff/
---
## SaveAsTIFF(string) {#saveastiff_10}

Mengonversi setiap Page dari sebuah pdf Document menjadi gambar dan menyimpan gambar ke satu file TIFF.

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

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, CompressionType) {#saveastiff_11}

Mengonversi setiap Page dari sebuah pdf Document menjadi gambar dan menyimpan gambar ke satu file TIFF.

```csharp
public void SaveAsTIFF(string outputFile, CompressionType compressionType)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputFile | String | File output. |
| compressionType | CompressionType | Jenis kompresi. |

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
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int) {#saveastiff_16}

Mengonversi setiap Page dari sebuah pdf Document menjadi gambar dengan dimensi, dan menyimpan gambar ke satu file TIFF.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputFile | String | Nama file untuk menyimpan gambar TIFF |
| imageWidth | Int32 | Lebar gambar, satuannya pixel. |
| imageHeight | Int32 | Tinggi gambar, satuannya pixel. |

### Lihat Juga

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, PageSize) {#saveastiff_14}

Mengonversi setiap Page dari sebuah pdf Document menjadi gambar dengan Page size dan menyimpan gambar ke satu file TIFF.

```csharp
public void SaveAsTIFF(string outputFile, PageSize pageSize)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputFile | String | Nama file untuk menyimpan gambar TIFF |
| pageSize | PageSize | Ukuran halaman gambar. |

### Lihat Juga

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, PageSize, TiffSettings) {#saveastiff_15}

Mengonversi setiap Page dari sebuah pdf Document menjadi gambar dengan Page size dan menyimpan gambar ke satu file TIFF.

```csharp
public void SaveAsTIFF(string outputFile, PageSize pageSize, TiffSettings settings)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputFile | String | Nama file untuk menyimpan gambar TIFF |
| pageSize | PageSize | Ukuran halaman gambar. |
| pengaturan | TiffSettings | Objek Settings yang mendefinisikan parameter TIFF. |

### Lihat Juga

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int, CompressionType) {#saveastiff_17}

Mengonversi setiap Page dari sebuah pdf Document menjadi gambar dengan dimensi, dan menyimpan gambar ke satu file TIFF.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight, 
    CompressionType compressionType)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputFile | String | Nama file untuk menyimpan gambar TIFF |
| imageWidth | Int32 | Lebar gambar, satuannya pixel. |
| imageHeight | Int32 | Tinggi gambar, satuannya pixel. |
| compressionType | CompressionType | Jenis kompresi. |

### Lihat Juga

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int, TiffSettings) {#saveastiff_18}

Mengonversi setiap Page dari sebuah pdf Document menjadi gambar dengan dimensi, dan menyimpan gambar ke satu file TIFF.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight, TiffSettings settings)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputFile | String | Nama file untuk menyimpan gambar TIFF |
| imageWidth | Int32 | Lebar gambar, satuannya pixel. |
| imageHeight | Int32 | Tinggi gambar, satuannya pixel. |
| pengaturan | TiffSettings | Objek Settings yang mendefinisikan parameter TIFF. |

### Lihat Juga

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int, TiffSettings, IIndexBitmapConverter) {#saveastiff_19}

Mengonversi setiap Page dari sebuah pdf Document menjadi gambar dengan dimensi, dan menyimpan gambar ke satu file TIFF.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight, TiffSettings settings, 
    IIndexBitmapConverter converter)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputFile | String | Nama file untuk menyimpan gambar TIFF |
| imageWidth | Int32 | Lebar gambar, satuannya pixel. |
| imageHeight | Int32 | Tinggi gambar, satuannya pixel. |
| pengaturan | TiffSettings | Objek Settings yang mendefinisikan parameter TIFF. |
| konverter | IIndexBitmapConverter | Konverter eksternal |

### Lihat Juga

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream) {#saveastiff}

Mengonversi setiap Page dari sebuah pdf Document menjadi gambar dan menyimpan gambar ke satu stream TIFF.

```csharp
public void SaveAsTIFF(Stream outputStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputStream | Stream | Stream untuk menyimpan gambar TIFF. |

### Lihat Juga

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, CompressionType) {#saveastiff_1}

Mengonversi setiap Page dari sebuah pdf Document menjadi gambar dan menyimpan gambar ke satu file TIFF.

```csharp
public void SaveAsTIFF(Stream outputStream, CompressionType compressionType)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputStream | Stream | Stream output. |
| compressionType | CompressionType | Jenis kompresi. |

### Lihat Juga

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, PageSize) {#saveastiff_4}

Mengonversi setiap Page dari sebuah pdf Document menjadi gambar dengan Page size dan menyimpan gambar ke satu stream TIFF.

```csharp
public void SaveAsTIFF(Stream outputStream, PageSize pageSize)
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

## SaveAsTIFF(Stream, PageSize, TiffSettings) {#saveastiff_5}

Mengonversi setiap Page dari sebuah pdf Document menjadi gambar dengan Page size dan menyimpan gambar ke satu stream TIFF.

```csharp
public void SaveAsTIFF(Stream outputStream, PageSize pageSize, TiffSettings settings)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputStream | Stream | Stream untuk menyimpan gambar TIFF. |
| pageSize | PageSize | Ukuran halaman gambar. |
| pengaturan | TiffSettings | Objek Settings yang mendefinisikan parameter TIFF. |

### Lihat Juga

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int) {#saveastiff_6}

Mengonversi setiap Page dari sebuah pdf Document menjadi gambar dengan dimensi, dan menyimpan gambar ke satu stream TIFF.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight)
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

## SaveAsTIFF(Stream, int, int, CompressionType) {#saveastiff_7}

Mengonversi setiap Page dari sebuah pdf Document menjadi gambar dengan dimensi, dan menyimpan gambar ke satu stream TIFF.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight, 
    CompressionType compressionType)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputStream | Stream | Stream untuk menyimpan gambar TIFF. |
| imageWidth | Int32 | Lebar gambar, satuannya pixel. |
| imageHeight | Int32 | Tinggi gambar, satuannya pixel. |
| compressionType | CompressionType | Jenis kompresi. |

### Lihat Juga

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int, TiffSettings) {#saveastiff_8}

Mengonversi setiap Page dari sebuah pdf Document menjadi gambar dengan dimensi, dan menyimpan gambar ke satu stream TIFF.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight, TiffSettings settings)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputStream | Stream | Stream untuk menyimpan gambar TIFF. |
| imageWidth | Int32 | Lebar gambar, satuannya pixel. |
| imageHeight | Int32 | Tinggi gambar, satuannya pixel. |
| pengaturan | TiffSettings | Objek Settings yang mendefinisikan parameter TIFF. |

### Lihat Juga

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int, TiffSettings, IIndexBitmapConverter) {#saveastiff_9}

Mengonversi setiap Page dari sebuah pdf Document menjadi gambar dengan dimensi, dan menyimpan gambar ke satu stream TIFF.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight, TiffSettings settings, 
    IIndexBitmapConverter converter)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputStream | Stream | Stream untuk menyimpan gambar TIFF. |
| imageWidth | Int32 | Lebar gambar, satuannya pixel. |
| imageHeight | Int32 | Tinggi gambar, satuannya pixel. |
| pengaturan | TiffSettings | Objek Settings yang mendefinisikan parameter TIFF. |
| konverter | IIndexBitmapConverter | Konverter eksternal |

### Lihat Juga

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, TiffSettings) {#saveastiff_12}

Mengonversi setiap Page dari sebuah pdf Document menjadi gambar dengan dan menyimpan gambar ke satu file TIFF.

```csharp
public void SaveAsTIFF(string outputFile, TiffSettings settings)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputFile | String | Nama file untuk menyimpan gambar TIFF |
| pengaturan | TiffSettings | Objek Settings yang mendefinisikan parameter TIFF. |

### Lihat Juga

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, TiffSettings, IIndexBitmapConverter) {#saveastiff_13}

Mengonversi setiap Page dari sebuah pdf Document menjadi gambar dengan dan menyimpan gambar ke satu file TIFF.

```csharp
public void SaveAsTIFF(string outputFile, TiffSettings settings, IIndexBitmapConverter converter)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputFile | String | Nama file untuk menyimpan gambar TIFF |
| pengaturan | TiffSettings | Objek Settings yang mendefinisikan parameter TIFF. |
| konverter | IIndexBitmapConverter | Konverter eksternal |

### Lihat Juga

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, TiffSettings) {#saveastiff_2}

Mengonversi setiap Page dari sebuah pdf Document menjadi gambar dan menyimpan gambar ke satu stream TIFF.

```csharp
public void SaveAsTIFF(Stream outputStream, TiffSettings settings)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputStream | Stream | Stream untuk menyimpan gambar TIFF. |
| pengaturan | TiffSettings | Objek Settings yang mendefinisikan parameter TIFF. |

### Lihat Juga

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, TiffSettings, IIndexBitmapConverter) {#saveastiff_3}

Mengonversi setiap Page dari sebuah pdf Document menjadi gambar dan menyimpan gambar ke satu stream TIFF.

```csharp
public void SaveAsTIFF(Stream outputStream, TiffSettings settings, IIndexBitmapConverter converter)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputStream | Stream | Stream untuk menyimpan gambar TIFF. |
| pengaturan | TiffSettings | Objek Settings yang mendefinisikan parameter TIFF. |
| konverter | IIndexBitmapConverter | Konverter eksternal |

### Lihat Juga

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


