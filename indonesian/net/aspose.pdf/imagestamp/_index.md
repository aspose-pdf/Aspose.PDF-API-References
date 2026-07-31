---
title: "Kelas ImageStamp"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.ImageStamp. Mewakili stempel grafis"
type: docs
weight: 6060
url: /id/net/aspose.pdf/imagestamp/
---
## ImageStamp class

Mewakili stempel grafis.

```csharp
public sealed class ImageStamp : Stamp
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [ImageStamp](imagestamp/#constructor)(Stream) | Menginisialisasi sebuah instance baru dari kelas `ImageStamp`. |
| [ImageStamp](imagestamp/#constructor_1)(string) | Membuat stempel gambar dengan gambar dalam file yang ditentukan. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AlternativeText](../../aspose.pdf/imagestamp/alternativetext/) { get; set; } | Mendapatkan atau mengatur Teks Alternatif untuk stempel gambar. |
| [Background](../../aspose.pdf/stamp/background/) { get; set; } | Mengatur atau mengambil nilai bool yang menunjukkan konten dicap sebagai latar belakang. Jika nilai true, konten stempel diletakkan di bagian bawah. Secara default, nilai false, konten stempel diletakkan di bagian atas. |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin/) { get; set; } | Mengambil atau mengatur margin bawah stempel. |
| override [Height](../../aspose.pdf/imagestamp/height/) { get; set; } | Mendapatkan atau mengatur tinggi gambar. Mengatur gambar ini memungkinkan penskalaan gambar secara vertikal. |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment/) { get; set; } | Mengambil atau mengatur perataan horizontal stempel pada halaman. |
| [Image](../../aspose.pdf/imagestamp/image/) { get; } | Mendapatkan aliran gambar yang digunakan untuk stamping. |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin/) { get; set; } | Mengambil atau mengatur margin kiri stempel. |
| [Opacity](../../aspose.pdf/stamp/opacity/) { get; set; } | Mengambil atau mengatur nilai untuk menunjukkan opasitas stempel. Nilainya dari 0.0 hingga 1.0. Secara default nilai adalah 1.0. |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity/) { get; set; } | Mengambil atau mengatur nilai untuk menunjukkan opasitas garis tepi stempel. Nilainya dari 0.0 hingga 1.0. Secara default nilai adalah 1.0. |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth/) { get; set; } | Mengambil atau mengatur nilai lebar garis tepi stempel. Secara default nilai adalah 1.0. |
| [Quality](../../aspose.pdf/imagestamp/quality/) { get; set; } | Mendapatkan atau mengatur kualitas stempel gambar dalam persen. Nilai yang valid adalah 0..100%. |
| [RightMargin](../../aspose.pdf/stamp/rightmargin/) { get; set; } | Mengambil atau mengatur margin kanan stempel. |
| [Rotate](../../aspose.pdf/stamp/rotate/) { get; set; } | Mengatur atau mengambil rotasi konten stempel sesuai nilai [`Rotation`](../rotation/). Catatan. Properti ini untuk mengatur sudut yang merupakan kelipatan 90 derajat (0, 90, 180, 270 derajat). Untuk mengatur sudut arbitrer gunakan properti RotateAngle. Jika sudut yang diatur oleh ArbitraryAngle bukan kelipatan 90 maka properti Rotate mengembalikan Rotation.None. |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle/) { get; set; } | Mengambil atau mengatur sudut rotasi stempel dalam derajat. Properti ini memungkinkan pengaturan sudut rotasi arbitrer. |
| [TopMargin](../../aspose.pdf/stamp/topmargin/) { get; set; } | Mengambil atau mengatur margin atas stempel. |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment/) { get; set; } | Mengambil atau mengatur perataan vertikal stempel pada halaman. |
| override [Width](../../aspose.pdf/imagestamp/width/) { get; set; } | Mendapatkan atau mengatur lebar gambar. Mengatur properti ini memungkinkan penskalaan gambar secara horizontal. |
| override [XIndent](../../aspose.pdf/imagestamp/xindent/) { get; set; } | Mendapatkan dan mengatur koordinat stempel horizontal, mulai dari kiri. |
| override [YIndent](../../aspose.pdf/imagestamp/yindent/) { get; set; } | Mendapatkan dan mengatur koordinat stempel vertikal, mulai dari bawah. |
| [Zoom](../../aspose.pdf/stamp/zoom/) { get; set; } | Faktor zoom stempel. Memungkinkan memperbesar/memperkecil stempel. Harap perhatikan bahwa pasangan properti ZoomX dan ZoomY memungkinkan mengatur faktor zoom untuk setiap sumbu secara terpisah. Pengaturan properti ini mengubah kedua properti ZoomX dan ZoomY. Jika ZoomX dan ZoomY berbeda maka properti Zoom mengembalikan nilai ZoomX. |
| [ZoomX](../../aspose.pdf/stamp/zoomx/) { get; set; } | Faktor zoom horizontal stempel. Memungkinkan memperbesar/memperkecil stempel secara horizontal. |
| [ZoomY](../../aspose.pdf/stamp/zoomy/) { get; set; } | Faktor zoom vertikal stempel. Memungkinkan memperbesar/memperkecil stempel secara vertikal. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid/)() | Mengembalikan ID stempel. |
| override [Put](../../aspose.pdf/imagestamp/put/)(Page) | Menambahkan stempel grafis pada halaman. |
| [setStampId](../../aspose.pdf/stamp/setstampid/)(int) | Mengatur ID stempel. |

### Lihat Juga

* class [Stamp](../stamp/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


