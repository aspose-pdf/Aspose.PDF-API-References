---
title: Class XFormPlacement
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Vector.XFormPlacement. Mewakili penempatan XForm. Jika XForm ditampilkan di halaman lebih dari 1 kali, semua XformPlacements yang terkait dengan XForm ini akan memiliki elemen grafis yang sama tetapi keadaan grafis yang berbeda
type: docs
weight: 11260
url: /id/net/aspose.pdf.vector/xformplacement/
---
## Kelas XFormPlacement

Mewakili penempatan XForm. Jika XForm ditampilkan di halaman lebih dari 1 kali, semua XformPlacements yang terkait dengan XForm ini akan memiliki elemen grafis yang sama, tetapi keadaan grafis yang berbeda.

```csharp
public sealed class XFormPlacement : GraphicElement
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Elements](../../aspose.pdf.vector/xformplacement/elements/) { get; } | Mendapatkan elemen grafis di dalam XForm ini. |
| [Matrix](../../aspose.pdf.vector/graphicelement/matrix/) { get; } | Mendapatkan matriks elemen grafis. Matriks diatur saat elemen dibuat. Ini berubah saat SetPosition() dipanggil. |
| [Name](../../aspose.pdf.vector/xformplacement/name/) { get; } | Mendapatkan nama dari XForm. |
| [Operators](../../aspose.pdf.vector/graphicelement/operators/) { get; } | Mendapatkan koleksi operator yang mewakili elemen. |
| [Parent](../../aspose.pdf.vector/graphicelement/parent/) { get; } | Mendapatkan `XFormPlacement` saat ini di mana elemen berada. |
| override [Position](../../aspose.pdf.vector/xformplacement/position/) { set; } |  |
| override [Rectangle](../../aspose.pdf.vector/xformplacement/rectangle/) { get; } |  |
| [SourcePage](../../aspose.pdf.vector/graphicelement/sourcepage/) { get; } | Mendapatkan halaman dari mana elemen grafis diambil. |
| [XForm](../../aspose.pdf.vector/xformplacement/xform/) { get; } | Mendapatkan XForm yang terkait dengan XFormPlacement ini. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [AddOnPage](../../aspose.pdf.vector/xformplacement/addonpage/)(Page) | Menambahkan elemen saat ini di halaman. Jika ada banyak elemen yang akan ditambahkan, lebih baik gunakan [`AddGraphics`](../../aspose.pdf/page/addgraphics/). |
| [Dispose](../../aspose.pdf.vector/graphicelement/dispose/)() | Membebaskan semua sumber daya yang digunakan oleh kelas [`GraphicElement`](../graphicelement/). |
| [Remove](../../aspose.pdf.vector/graphicelement/remove/)() | Menghapus elemen saat ini dari halaman. Jika ada banyak elemen yang akan dihapus, lebih baik gunakan [`DeleteGraphics`](../../aspose.pdf/page/deletegraphics/). |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)() | Mengonversi elemen menjadi gambar SVG tunggal. |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)(string) | Mengonversi elemen menjadi file gambar SVG tunggal. |

### Lihat Juga

* kelas [GraphicElement](../graphicelement/)
* namespace [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../)