---
title: "PdfFileMend.AddImage"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode PdfFileMend. Menambahkan gambar ke halaman PDF yang ditentukan pada koordinat yang ditentukan."
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
| lowerLeftX | Single | Koordinat x kiri bawah dari persegi panjang gambar. |
| lowerLeftY | Single | Koordinat y kiri bawah dari persegi panjang gambar. |
| upperRightX | Single | Koordinat x kanan atas dari persegi panjang gambar. |
| upperRightY | Single | Koordinat y kanan atas dari persegi panjang gambar. |

### Nilai Kembalian

Benar jika berhasil, salah jika tidak.

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

* class [PdfFileMend](../)
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
| lowerLeftX | Single | Koordinat x kiri bawah dari persegi panjang gambar. |
| lowerLeftY | Single | Koordinat y kiri bawah dari persegi panjang gambar. |
| upperRightX | Single | Koordinat x kanan atas dari persegi panjang gambar. |
| upperRightY | Single | Koordinat y kanan atas dari persegi panjang gambar. |
| compositingParameters | CompositingParameters | Parameter komposit grafis untuk gambar. |

### Nilai Kembalian

Benar jika berhasil, salah jika tidak.

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

* class [CompositingParameters](../../../aspose.pdf/compositingparameters/)
* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(Stream, int[], float, float, float, float) {#addimage_2}

Menambahkan gambar ke halaman-halaman tertentu dari dokumen PDF pada koordinat yang ditentukan.

```csharp
public bool AddImage(Stream imageStream, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| imageStream | Stream | Aliran gambar masukan. |
| pageNums | Int32[] | Jumlah halaman yang akan menerima gambar. |
| lowerLeftX | Single | Koordinat x kiri bawah dari persegi panjang gambar. |
| lowerLeftY | Single | Koordinat y kiri bawah dari persegi panjang gambar. |
| upperRightX | Single | Koordinat x kanan atas dari persegi panjang gambar. |
| upperRightY | Single | Koordinat y kanan atas dari persegi panjang gambar. |

### Nilai Kembalian

Benar jika berhasil, salah jika tidak.

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

* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(Stream, int[], float, float, float, float, CompositingParameters) {#addimage_3}

Menambahkan gambar ke halaman-halaman tertentu dari dokumen PDF pada koordinat yang ditentukan.

```csharp
public bool AddImage(Stream imageStream, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| imageStream | Stream | Aliran gambar masukan. |
| pageNums | Int32[] | Jumlah halaman yang akan menerima gambar. |
| lowerLeftX | Single | Koordinat x kiri bawah dari persegi panjang gambar. |
| lowerLeftY | Single | Koordinat y kiri bawah dari persegi panjang gambar. |
| upperRightX | Single | Koordinat x kanan atas dari persegi panjang gambar. |
| upperRightY | Single | Koordinat y kanan atas dari persegi panjang gambar. |
| compositingParameters | CompositingParameters | Parameter komposit grafis untuk gambar-gambar. |

### Nilai Kembalian

Benar jika berhasil, salah jika tidak.

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

* class [CompositingParameters](../../../aspose.pdf/compositingparameters/)
* class [PdfFileMend](../)
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
| lowerLeftX | Single | Koordinat x kiri bawah dari persegi panjang gambar. |
| lowerLeftY | Single | Koordinat y kiri bawah dari persegi panjang gambar. |
| upperRightX | Single | Koordinat x kanan atas dari persegi panjang gambar. |
| upperRightY | Single | Koordinat y kanan atas dari persegi panjang gambar. |

### Nilai Kembalian

Benar jika berhasil, salah jika tidak.

## Contoh

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100);
mendor.Close();
```

### Lihat Juga

* class [PdfFileMend](../)
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
| lowerLeftX | Single | Koordinat x kiri bawah dari persegi panjang gambar. |
| lowerLeftY | Single | Koordinat y kiri bawah dari persegi panjang gambar. |
| upperRightX | Single | Koordinat x kanan atas dari persegi panjang gambar. |
| upperRightY | Single | Koordinat y kanan atas dari persegi panjang gambar. |
| compositingParameters | CompositingParameters | Parameter komposit grafis untuk gambar-gambar. |

### Nilai Kembalian

Benar jika berhasil, salah jika tidak.

## Contoh

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply));
mendor.Close();
```

### Lihat Juga

* class [CompositingParameters](../../../aspose.pdf/compositingparameters/)
* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, int[], float, float, float, float) {#addimage_6}

Menambahkan gambar ke halaman-halaman tertentu dari dokumen PDF pada koordinat yang ditentukan.

```csharp
public bool AddImage(string imageName, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| imageName | String | Jalur file gambar masukan. |
| pageNums | Int32[] | Jumlah halaman yang akan menerima gambar. |
| lowerLeftX | Single | Koordinat x kiri bawah dari persegi panjang gambar. |
| lowerLeftY | Single | Koordinat y kiri bawah dari persegi panjang gambar. |
| upperRightX | Single | Koordinat x kanan atas dari persegi panjang gambar. |
| upperRightY | Single | Koordinat y kanan atas dari persegi panjang gambar. |

### Nilai Kembalian

Benar jika berhasil, salah jika tidak.

## Contoh

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100);
mendor.Close();
```

### Lihat Juga

* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, int[], float, float, float, float, CompositingParameters) {#addimage_7}

Menambahkan gambar ke halaman-halaman tertentu dari dokumen PDF pada koordinat yang ditentukan.

```csharp
public bool AddImage(string imageName, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| imageName | String | Jalur file gambar masukan. |
| pageNums | Int32[] | Jumlah halaman yang akan menerima gambar. |
| lowerLeftX | Single | Koordinat x kiri bawah dari persegi panjang gambar. |
| lowerLeftY | Single | Koordinat y kiri bawah dari persegi panjang gambar. |
| upperRightX | Single | Koordinat x kanan atas dari persegi panjang gambar. |
| upperRightY | Single | Koordinat y kanan atas dari persegi panjang gambar. |
| compositingParameters | CompositingParameters | Parameter komposit grafis untuk gambar-gambar. |

### Nilai Kembalian

Benar jika berhasil, salah jika tidak.

## Contoh

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply));
mendor.Close();
```

### Lihat Juga

* class [CompositingParameters](../../../aspose.pdf/compositingparameters/)
* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


