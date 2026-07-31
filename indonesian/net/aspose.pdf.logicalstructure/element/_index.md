---
title: "Kelas Element"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.LogicalStructure.Element. Mewakili kelas dasar untuk elemen dalam struktur logis"
type: docs
weight: 6460
url: /id/net/aspose.pdf.logicalstructure/element/
---
## Element class

Mewakili kelas dasar untuk elemen dalam logical structure.

```csharp
public abstract class Element
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | Mendapatkan koleksi anak dari objek Element. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | Dapatkan elemen induk. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | Tambahkan Element ke koleksi anak. |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | Bersihkan semua anak. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | Temukan Elements dengan tipe tertentu |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | Sisipkan Element ke koleksi anak pada indeks yang ditentukan. |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | Hapus anak pada. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag_2)(Annotation) | Mengaitkan elemen struktur ke Annotation. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag)(Artifact) | Mengaitkan elemen struktur ke Artifact. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag_1)(BDC) | Mengaitkan elemen struktur ke operator BDC pada aliran konten. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag_3)(XForm) | Mengaitkan elemen struktur ke XForm pada aliran konten. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag_4)(XImage) | Mengaitkan elemen struktur ke XImage. |
| override [ToString](../../aspose.pdf.logicalstructure/element/tostring/)() | Mengembalikan string yang mewakili objek saat ini. |

### Lihat Juga

* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)


