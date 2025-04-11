---
title: Class Stamp
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Stamp. Kelas abstrak untuk berbagai jenis stempel yang datang sebagai keturunan
type: docs
weight: 10130
url: /id/net/aspose.pdf/stamp/
---
## Kelas Stamp

Kelas abstrak untuk berbagai jenis stempel yang datang sebagai keturunan.

```csharp
public abstract class Stamp
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Background](../../aspose.pdf/stamp/background/) { get; set; } | Mengatur atau mendapatkan nilai bool yang menunjukkan konten dicap sebagai latar belakang. Jika nilainya benar, konten stempel diletakkan di bawah. Secara default, nilainya salah, konten stempel diletakkan di atas. |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin/) { get; set; } | Mendapatkan atau mengatur margin bawah stempel. |
| virtual [Height](../../aspose.pdf/stamp/height/) { get; set; } | Tinggi yang diinginkan dari stempel di halaman. |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment/) { get; set; } | Mendapatkan atau mengatur perataan horizontal stempel di halaman. |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin/) { get; set; } | Mendapatkan atau mengatur margin kiri stempel. |
| [Opacity](../../aspose.pdf/stamp/opacity/) { get; set; } | Mendapatkan atau mengatur nilai untuk menunjukkan opasitas stempel. Nilainya dari 0.0 hingga 1.0. Secara default nilainya adalah 1.0. |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity/) { get; set; } | Mendapatkan atau mengatur nilai untuk menunjukkan opasitas garis luar stempel. Nilainya dari 0.0 hingga 1.0. Secara default nilainya adalah 1.0. |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth/) { get; set; } | Mendapatkan atau mengatur nilai lebar garis luar stempel. Secara default nilainya adalah 1.0. |
| [RightMargin](../../aspose.pdf/stamp/rightmargin/) { get; set; } | Mendapatkan atau mengatur margin kanan stempel. |
| [Rotate](../../aspose.pdf/stamp/rotate/) { get; set; } | Mengatur atau mendapatkan rotasi konten stempel sesuai dengan nilai [`Rotation`](../rotation/). Catatan. Properti ini untuk mengatur sudut yang merupakan kelipatan dari 90 derajat (0, 90, 180, 270 derajat). Untuk mengatur sudut sembarang gunakan properti RotateAngle. Jika sudut yang diatur oleh ArbitraryAngle bukan kelipatan dari 90 maka properti Rotate mengembalikan Rotation.None. |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle/) { get; set; } | Mendapatkan atau mengatur sudut rotasi stempel dalam derajat. Properti ini memungkinkan untuk mengatur sudut rotasi sembarang. |
| [TopMargin](../../aspose.pdf/stamp/topmargin/) { get; set; } | Mendapatkan atau mengatur margin atas stempel. |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment/) { get; set; } | Mendapatkan atau mengatur perataan vertikal stempel di halaman. |
| virtual [Width](../../aspose.pdf/stamp/width/) { get; set; } | Lebar yang diinginkan dari stempel di halaman. |
| virtual [XIndent](../../aspose.pdf/stamp/xindent/) { get; set; } | Koordinat horizontal stempel, dimulai dari kiri. |
| virtual [YIndent](../../aspose.pdf/stamp/yindent/) { get; set; } | Koordinat vertikal stempel, dimulai dari bawah. |
| [Zoom](../../aspose.pdf/stamp/zoom/) { get; set; } | Faktor zoom dari stempel. Memungkinkan untuk menskalakan stempel. Harap dicatat bahwa pasangan properti ZoomX dan ZoomY memungkinkan untuk mengatur faktor zoom untuk setiap sumbu secara terpisah. Pengaturan properti ini mengubah kedua properti ZoomX dan ZoomY. Jika ZoomX dan ZoomY berbeda maka properti Zoom mengembalikan nilai ZoomX. |
| [ZoomX](../../aspose.pdf/stamp/zoomx/) { get; set; } | Faktor zoom horizontal dari stempel. Memungkinkan untuk menskalakan stempel secara horizontal. |
| [ZoomY](../../aspose.pdf/stamp/zoomy/) { get; set; } | Faktor zoom vertikal dari stempel. Memungkinkan untuk menskalakan stempel secara vertikal. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid/)() | Mengembalikan ID stempel. |
| abstract [Put](../../aspose.pdf/stamp/put/)(Page) | Menambahkan stempel di halaman. |
| [setStampId](../../aspose.pdf/stamp/setstampid/)(int) | Mengatur ID stempel. |

### Lihat Juga

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)