---
title: Class ImageStamp
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.ImageStamp. Mewakili stempel grafis
type: docs
weight: 5930
url: /id/net/aspose.pdf/imagestamp/
---
## Kelas ImageStamp

Mewakili stempel grafis.

```csharp
public sealed class ImageStamp : Stamp
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [ImageStamp](imagestamp/#constructor)(Stream) | Menginisialisasi instance baru dari kelas `ImageStamp`. |
| [ImageStamp](imagestamp/#constructor_1)(string) | Membuat stempel gambar dari gambar dalam file yang ditentukan. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AlternativeText](../../aspose.pdf/imagestamp/alternativetext/) { get; set; } | Mendapatkan atau mengatur Teks Alternatif untuk stempel gambar. |
| [Background](../../aspose.pdf/stamp/background/) { get; set; } | Mengatur atau mendapatkan nilai bool yang menunjukkan konten dicap sebagai latar belakang. Jika nilainya true, konten stempel diletakkan di bawah. Secara default, nilainya false, konten stempel diletakkan di atas. |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin/) { get; set; } | Mendapatkan atau mengatur margin bawah stempel. |
| override [Height](../../aspose.pdf/imagestamp/height/) { get; set; } | Mendapatkan atau mengatur tinggi gambar. Mengatur gambar ini memungkinkan untuk menskalakan gambar secara vertikal. |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment/) { get; set; } | Mendapatkan atau mengatur penyelarasan horizontal stempel di halaman. |
| [Image](../../aspose.pdf/imagestamp/image/) { get; } | Mendapatkan aliran gambar yang digunakan untuk pencap. |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin/) { get; set; } | Mendapatkan atau mengatur margin kiri stempel. |
| [Opacity](../../aspose.pdf/stamp/opacity/) { get; set; } | Mendapatkan atau mengatur nilai untuk menunjukkan opasitas stempel. Nilai berkisar dari 0.0 hingga 1.0. Secara default, nilainya 1.0. |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity/) { get; set; } | Mendapatkan atau mengatur nilai untuk menunjukkan opasitas garis luar stempel. Nilai berkisar dari 0.0 hingga 1.0. Secara default, nilainya 1.0. |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth/) { get; set; } | Mendapatkan atau mengatur nilai lebar garis luar stempel. Secara default, nilainya 1.0. |
| [Quality](../../aspose.pdf/imagestamp/quality/) { get; set; } | Mendapatkan atau mengatur kualitas stempel gambar dalam persen. Nilai yang valid adalah 0..100%. |
| [RightMargin](../../aspose.pdf/stamp/rightmargin/) { get; set; } | Mendapatkan atau mengatur margin kanan stempel. |
| [Rotate](../../aspose.pdf/stamp/rotate/) { get; set; } | Mengatur atau mendapatkan rotasi konten stempel sesuai dengan nilai [`Rotation`](../rotation/). Catatan. Properti ini untuk mengatur sudut yang merupakan kelipatan dari 90 derajat (0, 90, 180, 270 derajat). Untuk mengatur sudut sembarang, gunakan properti RotateAngle. Jika sudut yang diatur oleh ArbitraryAngle bukan kelipatan dari 90, maka properti Rotate mengembalikan Rotation.None. |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle/) { get; set; } | Mendapatkan atau mengatur sudut rotasi stempel dalam derajat. Properti ini memungkinkan untuk mengatur sudut rotasi sembarang. |
| [TopMargin](../../aspose.pdf/stamp/topmargin/) { get; set; } | Mendapatkan atau mengatur margin atas stempel. |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment/) { get; set; } | Mendapatkan atau mengatur penyelarasan vertikal stempel di halaman. |
| override [Width](../../aspose.pdf/imagestamp/width/) { get; set; } | Mendapatkan atau mengatur lebar gambar. Mengatur properti ini memungkinkan untuk menskalakan gambar secara horizontal. |
| override [XIndent](../../aspose.pdf/imagestamp/xindent/) { get; set; } | Mendapatkan dan mengatur koordinat horizontal stempel, dimulai dari kiri. |
| override [YIndent](../../aspose.pdf/imagestamp/yindent/) { get; set; } | Mendapatkan dan mengatur koordinat vertikal stempel, dimulai dari bawah. |
| [Zoom](../../aspose.pdf/stamp/zoom/) { get; set; } | Faktor zoom dari stempel. Memungkinkan untuk menskalakan stempel. Harap dicatat bahwa pasangan properti ZoomX dan ZoomY memungkinkan untuk mengatur faktor zoom untuk setiap sumbu secara terpisah. Pengaturan properti ini mengubah kedua properti ZoomX dan ZoomY. Jika ZoomX dan ZoomY berbeda, maka properti Zoom mengembalikan nilai ZoomX. |
| [ZoomX](../../aspose.pdf/stamp/zoomx/) { get; set; } | Faktor zoom horizontal dari stempel. Memungkinkan untuk menskalakan stempel secara horizontal. |
| [ZoomY](../../aspose.pdf/stamp/zoomy/) { get; set; } | Faktor zoom vertikal dari stempel. Memungkinkan untuk menskalakan stempel secara vertikal. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid/)() | Mengembalikan ID stempel. |
| override [Put](../../aspose.pdf/imagestamp/put/)(Page) | Menambahkan stempel grafis di halaman. |
| [setStampId](../../aspose.pdf/stamp/setstampid/)(int) | Mengatur ID stempel. |

### Lihat Juga

* kelas [Stamp](../stamp/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)