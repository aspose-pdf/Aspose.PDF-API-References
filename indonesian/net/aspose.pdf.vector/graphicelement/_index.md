---
title: "Kelas GraphicElement"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.Vector.GraphicElement. Mewakili kelas dasar untuk objek grafik pada halaman"
type: docs
weight: 11370
url: /id/net/aspose.pdf.vector/graphicelement/
---
## GraphicElement class

Mewakili kelas dasar untuk objek grafik pada halaman.

```csharp
public abstract class GraphicElement : IDisposable
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Matrix](../../aspose.pdf.vector/graphicelement/matrix/) { get; } | Mendapatkan matriks elemen grafis. Matriks ditetapkan saat elemen dibuat. Matriks berubah ketika SetPosition() dipanggil. |
| [Operators](../../aspose.pdf.vector/graphicelement/operators/) { get; } | Mendapatkan koleksi operator yang mewakili elemen. |
| [Parent](../../aspose.pdf.vector/graphicelement/parent/) { get; } | Mendapatkan [`XFormPlacement`](../xformplacement/) saat ini di mana elemen berada. |
| virtual [Position](../../aspose.pdf.vector/graphicelement/position/) { get; set; } | Mendapatkan atau mengatur posisi dalam ruang koordinat saat ini. Jika [`Parent`](./parent/) tidak !:null maka elemen memiliki ruang koordinat xForm. |
| abstract [Rectangle](../../aspose.pdf.vector/graphicelement/rectangle/) { get; } | Mendapatkan persegi panjang pembatas dari `GraphicElement`. |
| [SourcePage](../../aspose.pdf.vector/graphicelement/sourcepage/) { get; } | Mendapatkan halaman dari mana elemen grafis diekstrak. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| virtual [AddOnPage](../../aspose.pdf.vector/graphicelement/addonpage/)(Page) | Menambahkan elemen saat ini pada halaman. Jika ada banyak elemen yang akan ditambahkan, lebih baik gunakan [`AddGraphics`](../../aspose.pdf/page/addgraphics/). |
| [Dispose](../../aspose.pdf.vector/graphicelement/dispose/)() | Melepaskan semua sumber daya yang digunakan oleh kelas `GraphicElement`. |
| [Remove](../../aspose.pdf.vector/graphicelement/remove/)() | Menghapus elemen saat ini dari halaman. Jika ada banyak elemen yang harus dihapus, lebih baik gunakan [`DeleteGraphics`](../../aspose.pdf/page/deletegraphics/). |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/#savetosvg)() | Mengonversi elemen menjadi satu gambar SVG. |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/#savetosvg_1)(string) | Mengonversi elemen menjadi satu berkas gambar SVG. |

### Lihat Juga

* namespace [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../)


