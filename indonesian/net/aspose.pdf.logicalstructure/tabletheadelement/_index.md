---
title: Class TableTHeadElement
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.LogicalStructure.TableTHeadElement. Mewakili elemen struktur THead dalam struktur logis tabel
type: docs
weight: 6840
url: /id/net/aspose.pdf.logicalstructure/tabletheadelement/
---
## Kelas TableTHeadElement

Mewakili elemen struktur THead dalam struktur logis tabel.

```csharp
public sealed class TableTHeadElement : TableRowCollectionElement
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [ActualText](../../aspose.pdf.logicalstructure/structureelement/actualtext/) { get; set; } | Mengambil atau menetapkan teks aktual untuk elemen struktur. |
| [AlternativeText](../../aspose.pdf.logicalstructure/structureelement/alternativetext/) { get; set; } | Mengambil atau menetapkan teks alternatif untuk elemen struktur. |
| [Attributes](../../aspose.pdf.logicalstructure/structureelement/attributes/) { get; } | Mengambil objek StructureAttributeCollection. |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | Mengambil koleksi anak dari objek Element. |
| [DefaultAttributeOwner](../../aspose.pdf.logicalstructure/structureelement/defaultattributeowner/) { get; } | Mengambil objek AttributeOwnerStandard. |
| [ExpansionText](../../aspose.pdf.logicalstructure/structureelement/expansiontext/) { get; set; } | Mengambil atau menetapkan teks ekspansi untuk elemen struktur. |
| [ID](../../aspose.pdf.logicalstructure/structureelement/id/) { get; } | Mengambil ID untuk elemen struktur. |
| [Language](../../aspose.pdf.logicalstructure/structureelement/language/) { get; set; } | Mengambil atau menetapkan bahasa untuk elemen struktur. |
| [Page](../../aspose.pdf.logicalstructure/structureelement/page/) { get; } | Mengambil halaman di mana beberapa atau semua elemen anak akan dirender. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | Mengambil elemen induk. |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype/) { get; } | Mengambil tipe elemen struktur. |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title/) { get; set; } | Mengambil atau menetapkan judul untuk elemen struktur. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | Menambahkan Elemen ke koleksi anak. |
| [ChangeParentElement](../../aspose.pdf.logicalstructure/structureelement/changeparentelement/)(StructureElement, bool) | Mengubah elemen induk untuk elemen struktur saat ini |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | Menghapus semua anak. |
| [ClearId](../../aspose.pdf.logicalstructure/structureelement/clearid/)() | Menghapus ID untuk elemen struktur. |
| virtual [CreateTR](../../aspose.pdf.logicalstructure/tablerowcollectionelement/createtr/)() | Membuat [`TableTRElement`](../tabletrelement/) dan menambahkannya ke tabel saat ini. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | Mencari Elemen dari tipe tertentu |
| [GenerateId](../../aspose.pdf.logicalstructure/structureelement/generateid/)() | Menghasilkan ID untuk elemen struktur. |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | Menyisipkan Elemen ke koleksi anak pada indeks yang ditentukan. |
| [Remove](../../aspose.pdf.logicalstructure/structureelement/remove/)() | Menghapus: elemen dari struktur, referensi ke elemen dari objek induk, referensi ke elemen dari objek anak, objek yang sesuai dari dokumen. |
| [RemoveAndMoveItsChildObjectsToItsParent](../../aspose.pdf.logicalstructure/structureelement/removeandmoveitschildobjectstoitsparent/)(bool) | Menghapus elemen dari struktur, referensi ke elemen dari objek induk, referensi ke elemen dari objek anak, dan objek yang sesuai dari dokumen. Menyisipkan objek anak dari objek yang dihapus ke dalam koleksi objek anak induknya yang sebelumnya mulai dari indeks objek yang dihapus. |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | Menghapus anak pada. |
| [SetId](../../aspose.pdf.logicalstructure/structureelement/setid/)(string) | Menetapkan ID untuk elemen struktur. |
| [SetTag](../../aspose.pdf.logicalstructure/structureelement/settag/)(string) | Menetapkan tag kustom untuk elemen struktur. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Annotation) | Mengikat elemen struktur ke Annotation. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Artifact) | Mengikat elemen struktur ke Artifact. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(BDC) | Mengikat elemen struktur ke operator BDC aliran konten. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XForm) | Mengikat elemen struktur ke XForm aliran konten. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XImage) | Mengikat elemen struktur ke XImage. |
| override [ToString](../../aspose.pdf.logicalstructure/structureelement/tostring/)() | Mengembalikan string yang mewakili objek saat ini. |

### Lihat Juga

* kelas [TableRowCollectionElement](../tablerowcollectionelement/)
* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)