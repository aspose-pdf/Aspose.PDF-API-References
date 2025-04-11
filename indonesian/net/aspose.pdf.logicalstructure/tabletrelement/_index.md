---
title: Class TableTRElement
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.LogicalStructure.TableTRElement. Mewakili elemen struktur TR dalam struktur logis tabel
type: docs
weight: 6850
url: /id/net/aspose.pdf.logicalstructure/tabletrelement/
---
## Kelas TableTRElement

Mewakili elemen struktur TR dalam struktur logis tabel.

```csharp
public sealed class TableTRElement : TableChildElement
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [ActualText](../../aspose.pdf.logicalstructure/structureelement/actualtext/) { get; set; } | Mendapatkan atau mengatur teks aktual untuk elemen struktur. |
| [AlternativeText](../../aspose.pdf.logicalstructure/structureelement/alternativetext/) { get; set; } | Mendapatkan atau mengatur teks alternatif untuk elemen struktur. |
| [Attributes](../../aspose.pdf.logicalstructure/structureelement/attributes/) { get; } | Mendapatkan objek StructureAttributeCollection. |
| [BackgroundColor](../../aspose.pdf.logicalstructure/tabletrelement/backgroundcolor/) { get; set; } | Mendapatkan atau mengatur warna latar belakang baris. |
| [Border](../../aspose.pdf.logicalstructure/tabletrelement/border/) { get; set; } | Mendapatkan atau mengatur batas baris. |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | Mendapatkan koleksi anak dari objek Element. |
| [DefaultAttributeOwner](../../aspose.pdf.logicalstructure/structureelement/defaultattributeowner/) { get; } | Mendapatkan objek AttributeOwnerStandard. |
| [DefaultCellBorder](../../aspose.pdf.logicalstructure/tabletrelement/defaultcellborder/) { get; set; } | Mendapatkan batas sel default. |
| [DefaultCellPadding](../../aspose.pdf.logicalstructure/tabletrelement/defaultcellpadding/) { get; set; } | Mendapatkan atau mengatur margin default untuk sel baris. |
| [DefaultCellTextState](../../aspose.pdf.logicalstructure/tabletrelement/defaultcelltextstate/) { get; set; } | Mendapatkan atau mengatur status teks default untuk sel baris |
| [ExpansionText](../../aspose.pdf.logicalstructure/structureelement/expansiontext/) { get; set; } | Mendapatkan atau mengatur teks ekspansi untuk elemen struktur. |
| [FixedRowHeight](../../aspose.pdf.logicalstructure/tabletrelement/fixedrowheight/) { get; set; } | Mendapatkan tinggi baris tetap - baris dapat memiliki tinggi tetap. |
| [ID](../../aspose.pdf.logicalstructure/structureelement/id/) { get; } | Mendapatkan ID untuk elemen struktur. |
| [IsInNewPage](../../aspose.pdf.logicalstructure/tabletrelement/isinnewpage/) { get; set; } | Mendapatkan baris tetap berada di halaman baru - halaman dengan properti ini harus dicetak ke halaman berikutnya Default false. |
| [IsRowBroken](../../aspose.pdf.logicalstructure/tabletrelement/isrowbroken/) { get; set; } | Mendapatkan apakah baris dapat diputus antara dua halaman. |
| [Language](../../aspose.pdf.logicalstructure/structureelement/language/) { get; set; } | Mendapatkan atau mengatur bahasa untuk elemen struktur. |
| [MinRowHeight](../../aspose.pdf.logicalstructure/tabletrelement/minrowheight/) { get; set; } | Mendapatkan tinggi untuk baris. |
| [Page](../../aspose.pdf.logicalstructure/structureelement/page/) { get; } | Mendapatkan halaman di mana beberapa atau semua elemen anak akan dirender. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | Mendapatkan elemen induk. |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype/) { get; } | Mendapatkan tipe elemen struktur. |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title/) { get; set; } | Mendapatkan atau mengatur judul untuk elemen struktur. |
| [VerticalAlignment](../../aspose.pdf.logicalstructure/tabletrelement/verticalalignment/) { get; set; } | Mendapatkan atau mengatur perataan vertikal. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | Menambahkan Elemen ke koleksi anak. |
| [ChangeParentElement](../../aspose.pdf.logicalstructure/structureelement/changeparentelement/)(StructureElement, bool) | Mengubah elemen induk untuk elemen struktur saat ini |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | Menghapus semua anak. |
| [ClearId](../../aspose.pdf.logicalstructure/structureelement/clearid/)() | Menghapus ID untuk elemen struktur. |
| [CreateTD](../../aspose.pdf.logicalstructure/tabletrelement/createtd/)() | Membuat [`TableTHElement`](../tablethelement/) dan menambahkannya ke tabel saat ini. |
| [CreateTH](../../aspose.pdf.logicalstructure/tabletrelement/createth/)() | Membuat [`TableTHElement`](../tablethelement/) dan menambahkannya ke tabel saat ini. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | Mencari Elemen dari tipe tertentu |
| [GenerateId](../../aspose.pdf.logicalstructure/structureelement/generateid/)() | Menghasilkan ID untuk elemen struktur. |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | Menyisipkan Elemen ke koleksi anak pada indeks yang ditentukan. |
| [Remove](../../aspose.pdf.logicalstructure/structureelement/remove/)() | Menghapus: elemen dari struktur, referensi ke elemen dari objek induk, referensi ke elemen dari objek anak, objek yang sesuai dari dokumen. |
| [RemoveAndMoveItsChildObjectsToItsParent](../../aspose.pdf.logicalstructure/structureelement/removeandmoveitschildobjectstoitsparent/)(bool) | Menghapus elemen dari struktur, referensi ke elemen dari objek induk, referensi ke elemen dari objek anak, dan objek yang sesuai dari dokumen. Menyisipkan objek anak dari objek yang dihapus ke dalam koleksi objek anak induknya yang sebelumnya mulai dari indeks objek yang dihapus. |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | Menghapus anak di. |
| [SetId](../../aspose.pdf.logicalstructure/structureelement/setid/)(string) | Mengatur ID untuk elemen struktur. |
| [SetTag](../../aspose.pdf.logicalstructure/structureelement/settag/)(string) | Mengatur tag kustom untuk elemen struktur. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Annotation) | Mengikat elemen struktur ke Anotasi. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Artifact) | Mengikat elemen struktur ke Artefak. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(BDC) | Mengikat elemen struktur ke operator BDC aliran konten. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XForm) | Mengikat elemen struktur ke aliran konten XForm. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XImage) | Mengikat elemen struktur ke XImage. |
| override [ToString](../../aspose.pdf.logicalstructure/structureelement/tostring/)() | Mengembalikan string yang mewakili objek saat ini. |

### Lihat Juga

* kelas [TableChildElement](../tablechildelement/)
* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)