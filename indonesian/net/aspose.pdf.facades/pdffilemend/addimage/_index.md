---
title: PdfFileMend.AddImage
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfFileMend. Menambahkan gambar ke halaman tertentu dari dokumen PDF pada koordinat yang ditentukan
type: docs
weight: 50
url: /id/net/aspose.pdf.facades/pdffilemend/addimage/
---
## AddImage(Stream, int, float, float, float, float) {#addimage}

Menambahkan gambar ke halaman tertentu dari dokumen PDF pada koordinat yang ditentukan.

```csharp
public bool AddImage(Stream imageStream, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| imageStream | Stream | Aliran gambar masukan. |
| pageNum | Int32 | Nomor halaman yang akan menerima gambar. |
| lowerLeftX | Single | X kiri bawah dari persegi panjang gambar. |
| lowerLeftY | Single | Y kiri bawah dari persegi panjang gambar. |
| upperRightX | Single | X kanan atas dari persegi panjang gambar. |
| upperRightY | Single | Y kanan atas dari persegi panjang gambar. |

### Return Value

True jika berhasil, false jika tidak.

## Contoh

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, 1, 10, 10, 100, 100);
}
mendor.Close();
```

### Lihat Juga

* kelas [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(Stream, int, float, float, float, float, CompositingParameters) {#addimage_1}

Menambahkan gambar ke halaman tertentu dari dokumen PDF pada koordinat yang ditentukan.

```csharp
public bool AddImage(Stream imageStream, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| imageStream | Stream | Aliran gambar masukan. |
| pageNum | Int32 | Nomor halaman yang akan menerima gambar. |
| lowerLeftX | Single | X kiri bawah dari persegi panjang gambar. |
| lowerLeftY | Single | Y kiri bawah dari persegi panjang gambar. |
| upperRightX | Single | X kanan atas dari persegi panjang gambar. |
| upperRightY | Single | Y kanan atas dari persegi panjang gambar. |
| compositingParameters | CompositingParameters | Parameter komposit grafis untuk gambar. |

### Return Value

True jika berhasil, false jika tidak.

## Contoh

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply);
}
mendor.Close();
```

### Lihat Juga

* kelas [CompositingParameters](../../../aspose.pdf/compositingparameters/)
* kelas [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(Stream, int[], float, float, float, float) {#addimage_2}

Menambahkan gambar ke halaman tertentu dari dokumen PDF pada koordinat yang ditentukan.

```csharp
public bool AddImage(Stream imageStream, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| imageStream | Stream | Aliran gambar masukan. |
| pageNums | Int32[] | Nomor halaman yang akan menerima gambar. |
| lowerLeftX | Single | X kiri bawah dari persegi panjang gambar. |
| lowerLeftY | Single | Y kiri bawah dari persegi panjang gambar. |
| upperRightX | Single | X kanan atas dari persegi panjang gambar. |
| upperRightY | Single | Y kanan atas dari persegi panjang gambar. |

### Return Value

True jika berhasil, false jika tidak.

## Contoh

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, new int[]{1, 2}, 10, 10, 100, 100);
}
mendor.Close();
```

### Lihat Juga

* kelas [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(Stream, int[], float, float, float, float, CompositingParameters) {#addimage_3}

Menambahkan gambar ke halaman tertentu dari dokumen PDF pada koordinat yang ditentukan.

```csharp
public bool AddImage(Stream imageStream, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| imageStream | Stream | Aliran gambar masukan. |
| pageNums | Int32[] | Nomor halaman yang akan menerima gambar. |
| lowerLeftX | Single | X kiri bawah dari persegi panjang gambar. |
| lowerLeftY | Single | Y kiri bawah dari persegi panjang gambar. |
| upperRightX | Single | X kanan atas dari persegi panjang gambar. |
| upperRightY | Single | Y kanan atas dari persegi panjang gambar. |
| compositingParameters | CompositingParameters | Parameter komposit grafis untuk gambar. |

### Return Value

True jika berhasil, false jika tidak.

## Contoh

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, new int[]{1, 2}, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply);
}
mendor.Close();
```

### Lihat Juga

* kelas [CompositingParameters](../../../aspose.pdf/compositingparameters/)
* kelas [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, int, float, float, float, float) {#addimage_4}

Menambahkan gambar ke halaman tertentu dari dokumen PDF pada koordinat yang ditentukan.

```csharp
public bool AddImage(string imageName, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| imageName | String | Jalur file gambar masukan. |
| pageNum | Int32 | Nomor halaman yang akan menerima gambar. |
| lowerLeftX | Single | X kiri bawah dari persegi panjang gambar. |
| lowerLeftY | Single | Y kiri bawah dari persegi panjang gambar. |
| upperRightX | Single | X kanan atas dari persegi panjang gambar. |
| upperRightY | Single | Y kanan atas dari persegi panjang gambar. |

### Return Value

True jika berhasil, false jika tidak.

## Contoh

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100);
mendor.Close();
```

### Lihat Juga

* kelas [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, int, float, float, float, float, CompositingParameters) {#addimage_5}

Menambahkan gambar ke halaman tertentu dari dokumen PDF pada koordinat yang ditentukan.

```csharp
public bool AddImage(string imageName, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| imageName | String | Jalur file gambar masukan. |
| pageNum | Int32 | Nomor halaman yang akan menerima gambar. |
| lowerLeftX | Single | X kiri bawah dari persegi panjang gambar. |
| lowerLeftY | Single | Y kiri bawah dari persegi panjang gambar. |
| upperRightX | Single | X kanan atas dari persegi panjang gambar. |
| upperRightY | Single | Y kanan atas dari persegi panjang gambar. |
| compositingParameters | CompositingParameters | Parameter komposit grafis untuk gambar. |

### Return Value

True jika berhasil, false jika tidak.

## Contoh

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply));
mendor.Close();
```

### Lihat Juga

* kelas [CompositingParameters](../../../aspose.pdf/compositingparameters/)
* kelas [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, int[], float, float, float, float) {#addimage_6}

Menambahkan gambar ke halaman tertentu dari dokumen PDF pada koordinat yang ditentukan.

```csharp
public bool AddImage(string imageName, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| imageName | String | Jalur file gambar masukan. |
| pageNums | Int32[] | Nomor halaman yang akan menerima gambar. |
| lowerLeftX | Single | X kiri bawah dari persegi panjang gambar. |
| lowerLeftY | Single | Y kiri bawah dari persegi panjang gambar. |
| upperRightX | Single | X kanan atas dari persegi panjang gambar. |
| upperRightY | Single | Y kanan atas dari persegi panjang gambar. |

### Return Value

True jika berhasil, false jika tidak.

## Contoh

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100);
mendor.Close();
```

### Lihat Juga

* kelas [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, int[], float, float, float, float, CompositingParameters) {#addimage_7}

Menambahkan gambar ke halaman tertentu dari dokumen PDF pada koordinat yang ditentukan.

```csharp
public bool AddImage(string imageName, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| imageName | String | Jalur file gambar masukan. |
| pageNums | Int32[] | Nomor halaman yang akan menerima gambar. |
| lowerLeftX | Single | X kiri bawah dari persegi panjang gambar. |
| lowerLeftY | Single | Y kiri bawah dari persegi panjang gambar. |
| upperRightX | Single | X kanan atas dari persegi panjang gambar. |
| upperRightY | Single | Y kanan atas dari persegi panjang gambar. |
| compositingParameters | CompositingParameters | Parameter komposit grafis untuk gambar. |

### Return Value

True jika berhasil, false jika tidak.

## Contoh

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply));
mendor.Close();
```

### Lihat Juga

* kelas [CompositingParameters](../../../aspose.pdf/compositingparameters/)
* kelas [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)