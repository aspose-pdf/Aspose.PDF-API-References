---
title: "PdfConverter.GetNextImage"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode PdfConverter. Menyimpan gambar ke file dengan format gambar default jpeg"
type: docs
weight: 140
url: /id/net/aspose.pdf.facades/pdfconverter/getnextimage/
---
## GetNextImage(string) {#getnextimage_9}

Menyimpan gambar ke file dengan format gambar default - jpeg.

```csharp
public void GetNextImage(string outputFile)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputFile | String | Path dan nama file untuk menyimpan gambar. |

### Lihat Juga

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, PageSize) {#getnextimage_10}

Menyimpan gambar ke file dengan ukuran halaman yang diberikan dan format gambar default - jpeg.

```csharp
public void GetNextImage(string outputFile, PageSize pageSize)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputFile | String | Path dan nama file untuk menyimpan gambar. |
| pageSize | PageSize | Ukuran halaman gambar. |

### Lihat Juga

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat) {#getnextimage_13}

Menyimpan gambar ke file dengan format gambar yang diberikan.

```csharp
public void GetNextImage(string outputFile, ImageFormat format)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputFile | String | Path dan nama file untuk menyimpan gambar. |
| format | ImageFormat | Format gambar. |

## Contoh

```csharp
[C#]
PdfConverter converter = new PdfConverter();
converter.BindPdf(@"D:\Test\test.pdf");
converter.DoConvert();
String prefix = @"D:\Test\";
String suffix = ".png";
int imageCount = 1;
while (converter.HasNextImage())
{
	converter.GetNextImage(prefix + imageCount + suffix, ImageFormat.Png);
	imageCount++;
}

[Visual Basic]
Dim converter As PdfConverter =  New PdfConverter() 
converter.BindPdf("D:\Test\test.pdf")
converter.DoConvert()
Dim prefix As String =  "D:\Test\" 
Dim suffix As String =  ".png" 
Dim imageCount As Integer =  1 
While converter.HasNextImage()
	converter.GetNextImage(prefix + imageCount + suffix, ImageFormat.Png)
	imageCount = imageCount + 1
End While
```

### Lihat Juga

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, PageSize, ImageFormat) {#getnextimage_11}

Menyimpan gambar ke file dengan Page size dan format gambar yang diberikan.

```csharp
public void GetNextImage(string outputFile, PageSize pageSize, ImageFormat format)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputFile | String | Path dan nama file untuk menyimpan gambar. |
| pageSize | PageSize | Ukuran halaman gambar. |
| format | ImageFormat | Format gambar. |

### Lihat Juga

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream) {#getnextimage}

Menyimpan gambar ke stream dengan format gambar default - jpeg.

```csharp
public void GetNextImage(Stream outputStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputStream | Stream | Stream untuk menyimpan gambar. |

### Lihat Juga

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, PageSize) {#getnextimage_1}

Menyimpan gambar ke stream dengan ukuran halaman yang diberikan.

```csharp
public void GetNextImage(Stream outputStream, PageSize pageSize)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputStream | Stream | Stream untuk menyimpan gambar. |
| pageSize | PageSize | Ukuran halaman gambar. |

### Lihat Juga

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat) {#getnextimage_4}

Menyimpan gambar ke stream dengan format gambar yang diberikan.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputStream | Stream | Stream untuk menyimpan gambar. |
| format | ImageFormat | Format gambar. |

### Lihat Juga

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, PageSize, ImageFormat) {#getnextimage_2}

Menyimpan gambar ke stream dengan ukuran halaman yang diberikan.

```csharp
public void GetNextImage(Stream outputStream, PageSize pageSize, ImageFormat format)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputStream | Stream | Stream untuk menyimpan gambar. |
| pageSize | PageSize | Ukuran halaman gambar. |
| format | ImageFormat | Format gambar. |

### Lihat Juga

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, int, int, int) {#getnextimage_17}

Menyimpan gambar ke file dengan format gambar, dimensi, dan kualitas yang diberikan.

```csharp
public void GetNextImage(string outputFile, ImageFormat format, int imageWidth, int imageHeight, 
    int quality)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputFile | String | Path dan nama file untuk menyimpan gambar. |
| format | ImageFormat | Format gambar. |
| imageWidth | Int32 | Lebar gambar, satuannya pixel. |
| imageHeight | Int32 | Tinggi gambar, satuannya pixel. |
| quality | Int32 | Kualitas file Jpeg (0~100), 0 adalah terendah dan 100 adalah tertinggi |

## Contoh

```csharp
[C#]
PdfConverter converter = new PdfConverter();
converter.BindPdf(@"D:\Test\test.pdf");
converter.DoConvert();
String prefix = @"D:\Test\";
String suffix = ".jpg";
int imageCount = 1;
while (converter.HasNextImage())
{
	converter.GetNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000, 50);
	imageCount++;
}

[Visual Basic]
Dim converter As PdfConverter =  New PdfConverter() 
converter.BindPdf("D:\Test\test.pdf")
converter.DoConvert()
Dim prefix As String =  "D:\Test\" 
Dim suffix As String =  ".jpg" 
Dim imageCount As Integer =  1 
While converter.HasNextImage()
	converter.GetNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000, 50)
	imageCount = imageCount + 1
End While
```

### Lihat Juga

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, int, int, int) {#getnextimage_8}

Menyimpan gambar ke stream dengan format gambar, dimensi, dan kualitas yang diberikan.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, int imageWidth, int imageHeight, 
    int quality)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputStream | Stream | Stream untuk menyimpan gambar. |
| format | ImageFormat | Format gambar. |
| imageWidth | Int32 | Lebar gambar, satuannya pixel. |
| imageHeight | Int32 | Tinggi gambar, satuannya pixel. |
| quality | Int32 | Kualitas file Jpeg (0~100), 0 adalah terendah dan 100 adalah tertinggi |

### Lihat Juga

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, double, double, int) {#getnextimage_14}

Menyimpan gambar ke file dengan format gambar, ukuran gambar, dan kualitas yang diberikan.

```csharp
public void GetNextImage(string outputFile, ImageFormat format, double imageWidth, 
    double imageHeight, int quality)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputFile | String | Path dan nama file untuk menyimpan gambar. |
| format | ImageFormat | Format gambar. |
| imageWidth | Double | Lebar gambar, satuannya pixel. |
| imageHeight | Double | Tinggi gambar, satuannya pixel.. |
| quality | Int32 | Kualitas file Jpeg (0~100), 0 adalah terendah dan 100 adalah tertinggi |

## Contoh

```csharp
[C#]
PdfConverter converter = new PdfConverter();
converter.BindPdf(@"D:\Test\test.pdf");
converter.DoConvert();
String prefix = @"D:\Test\";
String suffix = ".jpg";
int imageCount = 1;
float pixelX=800f;
float pixelY=600f;
while (converter.HasNextImage())
{
	converter.GetNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, pixelX, pixelY, 50);
	imageCount++;
}

[Visual Basic]
Dim converter As PdfConverter =  New PdfConverter() 
converter.BindPdf("D:\Test\test.pdf")
converter.DoConvert()
Dim prefix As String =  "D:\Test\" 
Dim suffix As String =  ".jpg" 
Dim pixelX As float =800
Dim pixelY As float=600
Dim imageCount As Integer =  1 
While converter.HasNextImage()
	converter.GetNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, pixelX, pixelY, 50)
	imageCount = imageCount + 1
End While
```

### Lihat Juga

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, double, double, int) {#getnextimage_5}

Menyimpan gambar ke stream dengan format gambar, ukuran, dan kualitas yang diberikan.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, double imageWidth, 
    double imageHeight, int quality)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputStream | Stream | Stream untuk menyimpan gambar. |
| format | ImageFormat | Format gambar. |
| imageWidth | Double | Lebar gambar, satuannya pixel. |
| imageHeight | Double | Tinggi gambar, satuannya pixel. |
| quality | Int32 | Kualitas file Jpeg (0~100), 0 adalah terendah dan 100 adalah tertinggi |

### Lihat Juga

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, int, int) {#getnextimage_16}

Menyimpan gambar ke file dengan format gambar dan dimensi yang diberikan.

```csharp
public void GetNextImage(string outputFile, ImageFormat format, int imageWidth, int imageHeight)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputFile | String | Path dan nama file untuk menyimpan gambar. |
| format | ImageFormat | Format gambar. |
| imageWidth | Int32 | Lebar gambar, satuannya pixel. |
| imageHeight | Int32 | Tinggi gambar, satuannya pixel. |

## Contoh

```csharp
[C#]
PdfConverter converter = new PdfConverter();
converter.BindPdf(@"D:\Test\test.pdf");
converter.DoConvert();
String prefix = @"D:\Test\";
String suffix = ".jpg";
int imageCount = 1;
while (converter.HasNextImage())
{
	converter.GetNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000);
	imageCount++;
}

[Visual Basic]
Dim converter As PdfConverter =  New PdfConverter() 
converter.BindPdf("D:\Test\test.pdf")
converter.DoConvert()
Dim prefix As String =  "D:\Test\" 
Dim suffix As String =  ".jpg" 
Dim imageCount As Integer =  1 
While converter.HasNextImage()
	converter.GetNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000)
	imageCount = imageCount + 1
End While
```

### Lihat Juga

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, int, int) {#getnextimage_7}

Menyimpan gambar ke stream dengan format gambar, ukuran, dan kualitas yang diberikan.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, int imageWidth, int imageHeight)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputStream | Stream | Stream untuk menyimpan gambar. |
| format | ImageFormat | Format gambar. |
| imageWidth | Int32 | Lebar gambar, satuannya pixel. |
| imageHeight | Int32 | Tinggi gambar, satuannya pixel. |

### Lihat Juga

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, int) {#getnextimage_6}

Menyimpan gambar ke stream dengan format gambar dan kualitas yang diberikan.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, int quality)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputStream | Stream | Stream untuk menyimpan gambar. |
| format | ImageFormat | Format gambar. |
| quality | Int32 | Kualitas file Jpeg (0~100), 0 adalah terendah dan 100 adalah tertinggi |

### Lihat Juga

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, PageSize, ImageFormat, int) {#getnextimage_3}

Menyimpan gambar ke stream dengan Page size, format gambar, dan kualitas.

```csharp
public void GetNextImage(Stream outputStream, PageSize pageSize, ImageFormat format, int quality)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputStream | Stream | Stream untuk menyimpan gambar. |
| pageSize | PageSize | Ukuran halaman gambar. |
| format | ImageFormat | Format gambar. |
| quality | Int32 | Kualitas file Jpeg (0~100), 0 adalah terendah dan 100 adalah tertinggi |

### Lihat Juga

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, int) {#getnextimage_15}

Menyimpan gambar ke file dengan format gambar dan kualitas yang diberikan.

```csharp
public void GetNextImage(string outputFile, ImageFormat format, int quality)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputFile | String | Path dan nama file untuk menyimpan gambar. |
| format | ImageFormat | Format gambar. |
| quality | Int32 | Kualitas file Jpeg (0~100), 0 adalah terendah dan 100 adalah tertinggi |

### Lihat Juga

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, PageSize, ImageFormat, int) {#getnextimage_12}

Menyimpan gambar ke file dengan Page size, format gambar, dan kualitas.

```csharp
public void GetNextImage(string outputFile, PageSize pageSize, ImageFormat format, int quality)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputFile | String | Path dan nama file untuk menyimpan gambar. |
| pageSize | PageSize | Ukuran halaman gambar. |
| format | ImageFormat | Format gambar. |
| quality | Int32 | Kualitas file Jpeg (0~100), 0 adalah terendah dan 100 adalah tertinggi |

### Lihat Juga

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


