---
title: "Kelas XFormPlacement"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.Vector.XFormPlacement. Mewakili penempatan XForm. Jika XForm ditampilkan pada halaman lebih dari 1 kali, semua XFormPlacement yang terkait dengan XForm ini akan memiliki elemen grafis yang sama tetapi keadaan grafis yang berbeda."
type: docs
weight: 11450
url: /id/net/aspose.pdf.vector/xformplacement/
---
## XFormPlacement class

Mewakili penempatan XForm. Jika XForm ditampilkan pada halaman lebih dari satu kali, semua XformPlacements yang terkait dengan XForm ini akan memiliki elemen grafis yang sama, tetapi keadaan grafis yang berbeda.

```csharp
public sealed class XFormPlacement : GraphicElement
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Elements](../../aspose.pdf.vector/xformplacement/elements/) { get; } | Mendapatkan elemen grafis di dalam XForm ini. |
| [Matrix](../../aspose.pdf.vector/graphicelement/matrix/) { get; } | Mendapatkan matriks elemen grafis. Matriks ditetapkan saat elemen dibuat. Matriks berubah ketika SetPosition() dipanggil. |
| [Name](../../aspose.pdf.vector/xformplacement/name/) { get; } | Mendapatkan nama XForm. |
| [Operators](../../aspose.pdf.vector/graphicelement/operators/) { get; } | Mendapatkan koleksi operator yang mewakili elemen. |
| [Parent](../../aspose.pdf.vector/graphicelement/parent/) { get; } | Mendapatkan `XFormPlacement` saat ini di mana elemen berada. |
| override [Position](../../aspose.pdf.vector/xformplacement/position/) { set; } |  |
| override [Rectangle](../../aspose.pdf.vector/xformplacement/rectangle/) { get; } |  |
| [SourcePage](../../aspose.pdf.vector/graphicelement/sourcepage/) { get; } | Mendapatkan halaman dari mana elemen grafis diekstrak. |
| [XForm](../../aspose.pdf.vector/xformplacement/xform/) { get; } | Mendapatkan XForm yang terkait dengan XFormPlacement ini. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [AddOnPage](../../aspose.pdf.vector/xformplacement/addonpage/)(Page) | Menambahkan elemen saat ini pada halaman. Jika ada banyak elemen yang akan ditambahkan, lebih baik gunakan [`AddGraphics`](../../aspose.pdf/page/addgraphics/). |
| [Dispose](../../aspose.pdf.vector/graphicelement/dispose/)() | Melepaskan semua sumber daya yang digunakan oleh kelas [`GraphicElement`](../graphicelement/). |
| [Remove](../../aspose.pdf.vector/graphicelement/remove/)() | Menghapus elemen saat ini dari halaman. Jika ada banyak elemen yang harus dihapus, lebih baik gunakan [`DeleteGraphics`](../../aspose.pdf/page/deletegraphics/). |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)() | Mengonversi elemen menjadi satu gambar SVG. |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)(string) | Mengonversi elemen menjadi satu berkas gambar SVG. |

### Lihat Juga

* class [GraphicElement](../graphicelement/)
* namespace [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../)


