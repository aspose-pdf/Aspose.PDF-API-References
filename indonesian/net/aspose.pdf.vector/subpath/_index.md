---
title: Class SubPath
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Vector.SubPath. Mewakili objek grafik vektor di halaman. Pada dasarnya, objek grafik vektor diwakili oleh dua kelompok SubPaths. Salah satunya diwakili oleh sekumpulan garis dan kurva. Yang lainnya disajikan sebagai persegi panjang dan kadang-kadang bisa membingungkan. Biasanya, ini adalah area persegi panjang yang memiliki warna, tetapi sangat sering persegi panjang ini ditempatkan di awal halaman dan mendefinisikan seluruh ruang halaman dalam warna putih. Jadi Anda mendapatkan SubPath, tetapi secara visual Anda hanya melihat teks di halaman.
type: docs
weight: 11220
url: /id/net/aspose.pdf.vector/subpath/
---
## Kelas SubPath

Mewakili objek grafik vektor di halaman. Pada dasarnya, objek grafik vektor diwakili oleh dua kelompok SubPaths. Salah satunya diwakili oleh sekumpulan garis dan kurva. Yang lainnya disajikan sebagai persegi panjang dan kadang-kadang bisa membingungkan. Biasanya, ini adalah area persegi panjang yang memiliki warna, tetapi sangat sering persegi panjang ini ditempatkan di awal halaman dan mendefinisikan seluruh ruang halaman dalam warna putih. Jadi Anda mendapatkan SubPath, tetapi secara visual Anda hanya melihat teks di halaman.

```csharp
public sealed class SubPath : GraphicElement
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Matrix](../../aspose.pdf.vector/graphicelement/matrix/) { get; } | Mendapatkan matriks elemen grafik. Matriks diatur saat elemen dibuat. Ini berubah saat SetPosition() dipanggil. |
| [Operators](../../aspose.pdf.vector/graphicelement/operators/) { get; } | Mendapatkan koleksi operator yang mewakili elemen. |
| [Parent](../../aspose.pdf.vector/graphicelement/parent/) { get; } | Mendapatkan [`XFormPlacement`](../xformplacement/) saat ini di mana elemen berada. |
| virtual [Position](../../aspose.pdf.vector/graphicelement/position/) { get; set; } | Mendapatkan atau mengatur posisi dalam ruang koordinat saat ini. Jika [`Parent`](../graphicelement/parent/) tidak !:null maka elemen memiliki ruang koordinat xForm. |
| override [Rectangle](../../aspose.pdf.vector/subpath/rectangle/) { get; } |  |
| [SourcePage](../../aspose.pdf.vector/graphicelement/sourcepage/) { get; } | Mendapatkan halaman dari mana elemen grafik diambil. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| virtual [AddOnPage](../../aspose.pdf.vector/graphicelement/addonpage/)(Page) | Menambahkan elemen saat ini di halaman. Jika ada banyak elemen yang akan ditambahkan, lebih baik gunakan [`AddGraphics`](../../aspose.pdf/page/addgraphics/). |
| [Dispose](../../aspose.pdf.vector/graphicelement/dispose/)() | Mengeluarkan semua sumber daya yang digunakan oleh kelas [`GraphicElement`](../graphicelement/). |
| [Remove](../../aspose.pdf.vector/graphicelement/remove/)() | Menghapus elemen saat ini dari halaman. Jika ada banyak elemen yang akan dihapus, lebih baik gunakan [`DeleteGraphics`](../../aspose.pdf/page/deletegraphics/). |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)() | Mengonversi elemen menjadi satu gambar SVG. |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)(string) | Mengonversi elemen menjadi satu file gambar SVG. |

### Lihat Juga

* kelas [GraphicElement](../graphicelement/)
* namespace [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../)