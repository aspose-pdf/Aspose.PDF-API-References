---
title: Class PdfPageStamp
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.PdfPageStamp. Kelas ini mewakili cap yang menggunakan halaman PDF sebagai cap
type: docs
weight: 8420
url: /id/net/aspose.pdf/pdfpagestamp/
---
## Kelas PdfPageStamp

Kelas ini mewakili cap yang menggunakan halaman PDF sebagai cap.

```csharp
public sealed class PdfPageStamp : Stamp
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [PdfPageStamp](pdfpagestamp/#constructor)(Page) | Konstruktor dari PdfPageStamp. |
| [PdfPageStamp](pdfpagestamp/#constructor_1)(Stream, int) | Membuat cap halaman Pdf dari halaman yang ditentukan dalam dokumen dari aliran. |
| [PdfPageStamp](pdfpagestamp/#constructor_2)(string, int) | Membuat cap halaman Pdf dari halaman yang ditentukan dalam dokumen di file yang ditentukan. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Background](../../aspose.pdf/stamp/background/) { get; set; } | Mengatur atau mendapatkan nilai bool yang menunjukkan konten dicap sebagai latar belakang. Jika nilainya true, konten cap diletakkan di bawah. Secara default, nilainya false, konten cap diletakkan di atas. |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin/) { get; set; } | Mendapatkan atau mengatur margin bawah cap. |
| virtual [Height](../../aspose.pdf/stamp/height/) { get; set; } | Tinggi yang diinginkan dari cap di halaman. |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment/) { get; set; } | Mendapatkan atau mengatur perataan horizontal cap di halaman. |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin/) { get; set; } | Mendapatkan atau mengatur margin kiri cap. |
| [Opacity](../../aspose.pdf/stamp/opacity/) { get; set; } | Mendapatkan atau mengatur nilai untuk menunjukkan opasitas cap. Nilai berkisar dari 0.0 hingga 1.0. Secara default, nilainya 1.0. |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity/) { get; set; } | Mendapatkan atau mengatur nilai untuk menunjukkan opasitas garis luar cap. Nilai berkisar dari 0.0 hingga 1.0. Secara default, nilainya 1.0. |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth/) { get; set; } | Mendapatkan atau mengatur nilai lebar garis luar cap. Secara default, nilainya 1.0. |
| [PdfPage](../../aspose.pdf/pdfpagestamp/pdfpage/) { get; set; } | Mendapatkan atau mengatur halaman yang akan digunakan sebagai cap. |
| [RightMargin](../../aspose.pdf/stamp/rightmargin/) { get; set; } | Mendapatkan atau mengatur margin kanan cap. |
| [Rotate](../../aspose.pdf/stamp/rotate/) { get; set; } | Mengatur atau mendapatkan rotasi konten cap sesuai dengan nilai [`Rotation`](../rotation/). Catatan. Properti ini untuk mengatur sudut yang merupakan kelipatan dari 90 derajat (0, 90, 180, 270 derajat). Untuk mengatur sudut sembarang, gunakan properti RotateAngle. Jika sudut yang diatur oleh ArbitraryAngle bukan kelipatan dari 90, maka properti Rotate mengembalikan Rotation.None. |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle/) { get; set; } | Mendapatkan atau mengatur sudut rotasi cap dalam derajat. Properti ini memungkinkan untuk mengatur sudut rotasi sembarang. |
| [TopMargin](../../aspose.pdf/stamp/topmargin/) { get; set; } | Mendapatkan atau mengatur margin atas cap. |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment/) { get; set; } | Mendapatkan atau mengatur perataan vertikal cap di halaman. |
| virtual [Width](../../aspose.pdf/stamp/width/) { get; set; } | Lebar yang diinginkan dari cap di halaman. |
| virtual [XIndent](../../aspose.pdf/stamp/xindent/) { get; set; } | Koordinat horizontal cap, dimulai dari kiri. |
| virtual [YIndent](../../aspose.pdf/stamp/yindent/) { get; set; } | Koordinat vertikal cap, dimulai dari bawah. |
| [Zoom](../../aspose.pdf/stamp/zoom/) { get; set; } | Faktor zoom dari cap. Memungkinkan untuk menskalakan cap. Harap dicatat bahwa pasangan properti ZoomX dan ZoomY memungkinkan untuk mengatur faktor zoom untuk setiap sumbu secara terpisah. Pengaturan properti ini mengubah kedua properti ZoomX dan ZoomY. Jika ZoomX dan ZoomY berbeda, maka properti Zoom mengembalikan nilai ZoomX. |
| [ZoomX](../../aspose.pdf/stamp/zoomx/) { get; set; } | Faktor zoom horizontal dari cap. Memungkinkan untuk menskalakan cap secara horizontal. |
| [ZoomY](../../aspose.pdf/stamp/zoomy/) { get; set; } | Faktor zoom vertikal dari cap. Memungkinkan untuk menskalakan cap secara vertikal. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid/)() | Mengembalikan ID cap. |
| override [Put](../../aspose.pdf/pdfpagestamp/put/)(Page) | Menempatkan cap di halaman yang ditentukan. |
| [setStampId](../../aspose.pdf/stamp/setstampid/)(int) | Mengatur ID cap. |

### Lihat Juga

* kelas [Stamp](../stamp/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)