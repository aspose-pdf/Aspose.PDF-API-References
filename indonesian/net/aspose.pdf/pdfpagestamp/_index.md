---
title: "Kelas PdfPageStamp"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.PdfPageStamp. Kelas ini mewakili stempel yang menggunakan halaman PDF sebagai stempel"
type: docs
weight: 8560
url: /id/net/aspose.pdf/pdfpagestamp/
---
## PdfPageStamp class

Kelas mewakili stempel yang menggunakan halaman PDF sebagai stempel.

```csharp
public sealed class PdfPageStamp : Stamp
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [PdfPageStamp](pdfpagestamp/#constructor)(Page) | Konstruktor PdfPageStamp. |
| [PdfPageStamp](pdfpagestamp/#constructor_1)(Stream, int) | Membuat stempel halaman PDF dari halaman yang ditentukan dalam dokumen dari aliran. |
| [PdfPageStamp](pdfpagestamp/#constructor_2)(string, int) | Membuat stempel halaman PDF dari halaman yang ditentukan dalam dokumen pada file yang ditentukan. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Background](../../aspose.pdf/stamp/background/) { get; set; } | Mengatur atau mengambil nilai bool yang menunjukkan konten dicap sebagai latar belakang. Jika nilai true, konten stempel diletakkan di bagian bawah. Secara default, nilai false, konten stempel diletakkan di bagian atas. |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin/) { get; set; } | Mengambil atau mengatur margin bawah stempel. |
| virtual [Height](../../aspose.pdf/stamp/height/) { get; set; } | Tinggi yang diinginkan untuk stempel pada halaman. |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment/) { get; set; } | Mengambil atau mengatur perataan horizontal stempel pada halaman. |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin/) { get; set; } | Mengambil atau mengatur margin kiri stempel. |
| [Opacity](../../aspose.pdf/stamp/opacity/) { get; set; } | Mengambil atau mengatur nilai untuk menunjukkan opasitas stempel. Nilainya dari 0.0 hingga 1.0. Secara default nilai adalah 1.0. |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity/) { get; set; } | Mengambil atau mengatur nilai untuk menunjukkan opasitas garis tepi stempel. Nilainya dari 0.0 hingga 1.0. Secara default nilai adalah 1.0. |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth/) { get; set; } | Mengambil atau mengatur nilai lebar garis tepi stempel. Secara default nilai adalah 1.0. |
| [PdfPage](../../aspose.pdf/pdfpagestamp/pdfpage/) { get; set; } | Mengambil atau mengatur halaman yang akan digunakan sebagai stempel. |
| [RightMargin](../../aspose.pdf/stamp/rightmargin/) { get; set; } | Mengambil atau mengatur margin kanan stempel. |
| [Rotate](../../aspose.pdf/stamp/rotate/) { get; set; } | Mengatur atau mengambil rotasi konten stempel sesuai nilai [`Rotation`](../rotation/). Catatan. Properti ini untuk mengatur sudut yang merupakan kelipatan 90 derajat (0, 90, 180, 270 derajat). Untuk mengatur sudut arbitrer gunakan properti RotateAngle. Jika sudut yang diatur oleh ArbitraryAngle bukan kelipatan 90 maka properti Rotate mengembalikan Rotation.None. |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle/) { get; set; } | Mengambil atau mengatur sudut rotasi stempel dalam derajat. Properti ini memungkinkan pengaturan sudut rotasi arbitrer. |
| [TopMargin](../../aspose.pdf/stamp/topmargin/) { get; set; } | Mengambil atau mengatur margin atas stempel. |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment/) { get; set; } | Mengambil atau mengatur perataan vertikal stempel pada halaman. |
| virtual [Width](../../aspose.pdf/stamp/width/) { get; set; } | Lebar yang diinginkan untuk stempel pada halaman. |
| virtual [XIndent](../../aspose.pdf/stamp/xindent/) { get; set; } | Koordinat horizontal stempel, dimulai dari kiri. |
| virtual [YIndent](../../aspose.pdf/stamp/yindent/) { get; set; } | Koordinat stempel vertikal, dimulai dari bagian bawah. |
| [Zoom](../../aspose.pdf/stamp/zoom/) { get; set; } | Faktor zoom stempel. Memungkinkan memperbesar/memperkecil stempel. Harap perhatikan bahwa pasangan properti ZoomX dan ZoomY memungkinkan mengatur faktor zoom untuk setiap sumbu secara terpisah. Pengaturan properti ini mengubah kedua properti ZoomX dan ZoomY. Jika ZoomX dan ZoomY berbeda maka properti Zoom mengembalikan nilai ZoomX. |
| [ZoomX](../../aspose.pdf/stamp/zoomx/) { get; set; } | Faktor zoom horizontal stempel. Memungkinkan memperbesar/memperkecil stempel secara horizontal. |
| [ZoomY](../../aspose.pdf/stamp/zoomy/) { get; set; } | Faktor zoom vertikal stempel. Memungkinkan memperbesar/memperkecil stempel secara vertikal. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid/)() | Mengembalikan ID stempel. |
| override [Put](../../aspose.pdf/pdfpagestamp/put/)(Page) | Letakkan stempel pada halaman yang ditentukan. |
| [setStampId](../../aspose.pdf/stamp/setstampid/)(int) | Mengatur ID stempel. |

### Lihat Juga

* class [Stamp](../stamp/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


