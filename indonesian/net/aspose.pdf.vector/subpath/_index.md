---
title: "Kelas SubPath"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.Vector.SubPath. Mewakili objek grafik vektor pada halaman. Pada dasarnya objek grafik vektor direpresentasikan oleh dua grup SubPath. Salah satunya direpresentasikan oleh sekumpulan garis dan kurva. Yang lainnya ditampilkan sebagai persegi panjang dan kadang dapat membingungkan. Biasanya itu adalah area persegi panjang yang memiliki warna tetapi sangat sering persegi panjang ini ditempatkan di awal halaman dan mendefinisikan seluruh ruang halaman dengan warna putih. Jadi Anda mendapatkan SubPath tetapi secara visual Anda hanya melihat teks pada halaman."
type: docs
weight: 11410
url: /id/net/aspose.pdf.vector/subpath/
---
## SubPath class

Mewakili objek grafik vektor pada halaman. Pada dasarnya, objek grafik vektor direpresentasikan oleh dua kelompok SubPath. Salah satunya direpresentasikan oleh sekumpulan garis dan kurva. Yang lainnya ditampilkan sebagai persegi panjang dan kadang dapat membingungkan. Biasanya itu adalah area persegi panjang yang memiliki warna, tetapi sangat sering persegi panjang ini ditempatkan di awal halaman dan mendefinisikan seluruh ruang halaman dengan warna putih. Jadi Anda mendapatkan SubPath, tetapi secara visual Anda hanya melihat teks pada halaman.

```csharp
public sealed class SubPath : GraphicElement
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Matrix](../../aspose.pdf.vector/graphicelement/matrix/) { get; } | Mendapatkan matriks elemen grafis. Matriks ditetapkan saat elemen dibuat. Matriks berubah ketika SetPosition() dipanggil. |
| [Operators](../../aspose.pdf.vector/graphicelement/operators/) { get; } | Mendapatkan koleksi operator yang mewakili elemen. |
| [Parent](../../aspose.pdf.vector/graphicelement/parent/) { get; } | Mendapatkan [`XFormPlacement`](../xformplacement/) saat ini di mana elemen berada. |
| virtual [Position](../../aspose.pdf.vector/graphicelement/position/) { get; set; } | Mendapatkan atau mengatur posisi dalam ruang koordinat saat ini. Jika [`Parent`](../graphicelement/parent/) tidak !:null maka elemen memiliki ruang koordinat xForm. |
| override [Rectangle](../../aspose.pdf.vector/subpath/rectangle/) { get; } |  |
| [SourcePage](../../aspose.pdf.vector/graphicelement/sourcepage/) { get; } | Mendapatkan halaman dari mana elemen grafis diekstrak. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| virtual [AddOnPage](../../aspose.pdf.vector/graphicelement/addonpage/)(Page) | Menambahkan elemen saat ini pada halaman. Jika ada banyak elemen yang akan ditambahkan, lebih baik gunakan [`AddGraphics`](../../aspose.pdf/page/addgraphics/). |
| [Dispose](../../aspose.pdf.vector/graphicelement/dispose/)() | Melepaskan semua sumber daya yang digunakan oleh kelas [`GraphicElement`](../graphicelement/). |
| [Remove](../../aspose.pdf.vector/graphicelement/remove/)() | Menghapus elemen saat ini dari halaman. Jika ada banyak elemen yang harus dihapus, lebih baik gunakan [`DeleteGraphics`](../../aspose.pdf/page/deletegraphics/). |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)() | Mengonversi elemen menjadi satu gambar SVG. |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)(string) | Mengonversi elemen menjadi satu berkas gambar SVG. |

### Lihat Juga

* class [GraphicElement](../graphicelement/)
* namespace [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../)


