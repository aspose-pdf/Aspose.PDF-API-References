---
title: Page.AddImage
second_title: Aspose.PDF for .NET API Reference
description: Metode Page. Menambahkan gambar ke halaman dan menempatkannya di tengah persegi panjang yang ditentukan sambil menyimpan proporsi gambar
type: docs
weight: 350
url: /id/net/aspose.pdf/page/addimage/
---
## AddImage(Stream, Rectangle, Rectangle, bool) {#addimage}

Menambahkan gambar ke halaman dan menempatkannya di tengah persegi panjang yang ditentukan sambil menyimpan proporsi gambar.

```csharp
public void AddImage(Stream imageStream, Rectangle imageRect, Rectangle bbox = null, 
    bool autoAdjustRectangle = true)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| imageStream | Stream | Aliran gambar. |
| imageRect | Rectangle | Posisi gambar. |
| bbox | Rectangle | Bbox gambar. |
| autoAdjustRectangle | Boolean | Menyesuaikan gambar di tengah persegi panjang input. |

### Lihat Juga

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, Stream, Rectangle, Rectangle) {#addimage_3}

Menambahkan gambar yang dapat dicari ke halaman dan menempatkannya di tengah persegi panjang yang ditentukan sambil menyimpan proporsi gambar.

```csharp
public void AddImage(string hocr, Stream imageStream, Rectangle imageRect, Rectangle bbox = null)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| hocr | String | Hocr gambar. |
| imageStream | Stream | Aliran gambar. |
| imageRect | Rectangle | Posisi gambar. |
| bbox | Rectangle | Bbox gambar. |

### Lihat Juga

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(Stream, Rectangle, int, int, bool, Rectangle) {#addimage_1}

Menambahkan gambar ke halaman dan menempatkannya tergantung pada posisi persegi panjang gambar.

```csharp
public void AddImage(Stream imageStream, Rectangle imageRect, int imageWidth, int imageHeight, 
    bool saveImageProportions, Rectangle bbox = null)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| imageStream | Stream | Aliran gambar. |
| imageRect | Rectangle | Posisi default gambar di halaman. |
| imageWidth | Int32 | Lebar gambar. |
| imageHeight | Int32 | Tinggi gambar. |
| saveImageProportions | Boolean | Jika flag diatur ke true maka gambar ditempatkan di posisi persegi panjang; jika tidak, ukuran persegi panjang menjadi sama dengan ukuran gambar. |
| bbox | Rectangle | Bbox gambar. |

### Lihat Juga

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, Rectangle) {#addimage_2}

Menambahkan gambar ke halaman dan menempatkannya di tengah persegi panjang yang ditentukan sambil menyimpan proporsi gambar.

```csharp
public void AddImage(string imagePath, Rectangle rectangle)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| imagePath | String | Jalur ke gambar. |
| rectangle | Rectangle | Posisi gambar. |

### Lihat Juga

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)