---
title: Class GraphicElement
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Vector.GraphicElement. Mewakili kelas dasar untuk objek grafis di halaman
type: docs
weight: 11180
url: /id/net/aspose.pdf.vector/graphicelement/
---
## Kelas GraphicElement

Mewakili kelas dasar untuk objek grafis di halaman.

```csharp
public abstract class GraphicElement : IDisposable
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Matrix](../../aspose.pdf.vector/graphicelement/matrix/) { get; } | Mendapatkan matriks elemen grafis. Matriks diatur saat elemen dibuat. Ini berubah saat SetPosition() dipanggil. |
| [Operators](../../aspose.pdf.vector/graphicelement/operators/) { get; } | Mendapatkan koleksi operator yang mewakili elemen. |
| [Parent](../../aspose.pdf.vector/graphicelement/parent/) { get; } | Mendapatkan [`XFormPlacement`](../xformplacement/) saat ini di mana elemen berada. |
| virtual [Position](../../aspose.pdf.vector/graphicelement/position/) { get; set; } | Mendapatkan atau mengatur posisi dalam ruang koordinat saat ini. Jika [`Parent`](./parent/) tidak !:null maka elemen memiliki ruang koordinat xForm. |
| abstract [Rectangle](../../aspose.pdf.vector/graphicelement/rectangle/) { get; } | Mendapatkan persegi panjang batas dari `GraphicElement`. |
| [SourcePage](../../aspose.pdf.vector/graphicelement/sourcepage/) { get; } | Mendapatkan halaman dari mana elemen grafis diambil. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| virtual [AddOnPage](../../aspose.pdf.vector/graphicelement/addonpage/)(Page) | Menambahkan elemen saat ini di halaman. Jika ada banyak elemen yang akan ditambahkan, lebih baik menggunakan [`AddGraphics`](../../aspose.pdf/page/addgraphics/). |
| [Dispose](../../aspose.pdf.vector/graphicelement/dispose/)() | Membebaskan semua sumber daya yang digunakan oleh kelas `GraphicElement`. |
| [Remove](../../aspose.pdf.vector/graphicelement/remove/)() | Menghapus elemen saat ini dari halaman. Jika ada banyak elemen yang akan dihapus, lebih baik menggunakan [`DeleteGraphics`](../../aspose.pdf/page/deletegraphics/). |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/#savetosvg)() | Mengonversi elemen menjadi gambar SVG tunggal. |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/#savetosvg_1)(string) | Mengonversi elemen menjadi file gambar SVG tunggal. |

### Lihat Juga

* namespace [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../)