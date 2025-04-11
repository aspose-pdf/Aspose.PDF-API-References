---
title: Class LinkElement
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.LogicalStructure.LinkElement. Mewakili elemen struktur Link dalam struktur logis
type: docs
weight: 6440
url: /id/net/aspose.pdf.logicalstructure/linkelement/
---
## Kelas LinkElement

Mewakili elemen struktur Link dalam struktur logis.

```csharp
public sealed class LinkElement : AnnotationElement, IAdjustPosition, ITextElement
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [ActualText](../../aspose.pdf.logicalstructure/structureelement/actualtext/) { get; set; } | Mendapatkan atau mengatur teks aktual untuk elemen struktur. |
| [AlternateDescriptions](../../aspose.pdf.logicalstructure/annotationelement/alternatedescriptions/) { get; set; } | Mendapatkan atau Mengatur Deskripsi Alternatif untuk anotasi. Teks yang akan ditampilkan untuk anotasi atau, jika jenis anotasi ini tidak menampilkan teks, deskripsi alternatif dari konten anotasi dalam bentuk yang dapat dibaca manusia. |
| [AlternativeText](../../aspose.pdf.logicalstructure/structureelement/alternativetext/) { get; set; } | Mendapatkan atau mengatur teks alternatif untuk elemen struktur. |
| [Attributes](../../aspose.pdf.logicalstructure/structureelement/attributes/) { get; } | Mendapatkan objek StructureAttributeCollection. |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | Mendapatkan koleksi anak dari objek Element. |
| [DefaultAttributeOwner](../../aspose.pdf.logicalstructure/structureelement/defaultattributeowner/) { get; } | Mendapatkan objek AttributeOwnerStandard. |
| [ExpansionText](../../aspose.pdf.logicalstructure/structureelement/expansiontext/) { get; set; } | Mendapatkan atau mengatur teks ekspansi untuk elemen struktur. |
| [Hyperlink](../../aspose.pdf.logicalstructure/linkelement/hyperlink/) { get; set; } | Mendapatkan atau Mengatur Hyperlink untuk Elemen Link. |
| [ID](../../aspose.pdf.logicalstructure/structureelement/id/) { get; } | Mendapatkan ID untuk elemen struktur. |
| [Language](../../aspose.pdf.logicalstructure/structureelement/language/) { get; set; } | Mendapatkan atau mengatur bahasa untuk elemen struktur. |
| [Page](../../aspose.pdf.logicalstructure/structureelement/page/) { get; } | Mendapatkan halaman di mana beberapa atau semua elemen anak akan dirender. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | Mendapatkan elemen induk. |
| [StructureTextState](../../aspose.pdf.logicalstructure/linkelement/structuretextstate/) { get; } | Mendapatkan objek StructureTextState untuk elemen saat ini. |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype/) { get; } | Mendapatkan jenis elemen struktur. |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title/) { get; set; } | Mendapatkan atau mengatur judul untuk elemen struktur. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [AdjustPosition](../../aspose.pdf.logicalstructure/linkelement/adjustposition/)(PositionSettings) |  |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | Menambahkan Elemen ke koleksi anak. |
| [ChangeParentElement](../../aspose.pdf.logicalstructure/structureelement/changeparentelement/)(StructureElement, bool) | Mengubah elemen induk untuk elemen struktur saat ini |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | Menghapus semua anak. |
| [ClearId](../../aspose.pdf.logicalstructure/structureelement/clearid/)() | Menghapus ID untuk elemen struktur. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | Mencari Elemen dari tipe tertentu |
| [GenerateId](../../aspose.pdf.logicalstructure/structureelement/generateid/)() | Menghasilkan ID untuk elemen struktur. |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | Menyisipkan Elemen ke koleksi anak pada indeks yang ditentukan. |
| [Remove](../../aspose.pdf.logicalstructure/structureelement/remove/)() | Menghapus: elemen dari struktur, referensi ke elemen tersebut dari objek induk, referensi ke elemen tersebut dari objek anak, objek yang sesuai dari dokumen. |
| [RemoveAndMoveItsChildObjectsToItsParent](../../aspose.pdf.logicalstructure/structureelement/removeandmoveitschildobjectstoitsparent/)(bool) | Menghapus elemen dari struktur, referensi ke elemen tersebut dari objek induk, referensi ke elemen tersebut dari objek anak, dan objek yang sesuai dari dokumen. Menyisipkan objek anak dari objek yang dihapus ke dalam koleksi objek anak induknya yang sebelumnya mulai dari indeks objek yang dihapus. |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | Menghapus anak pada. |
| [SetId](../../aspose.pdf.logicalstructure/structureelement/setid/)(string) | Mengatur ID untuk elemen struktur. |
| [SetTag](../../aspose.pdf.logicalstructure/structureelement/settag/)(string) | Mengatur tag kustom untuk elemen struktur. |
| [SetText](../../aspose.pdf.logicalstructure/linkelement/settext/)(string) |  |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Annotation) | Mengikat elemen struktur ke Anotasi. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Artifact) | Mengikat elemen struktur ke Artefak. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(BDC) | Mengikat elemen struktur ke operator BDC aliran konten. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XForm) | Mengikat elemen struktur ke XForm aliran konten. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XImage) | Mengikat elemen struktur ke XImage. |
| override [ToString](../../aspose.pdf.logicalstructure/structureelement/tostring/)() | Mengembalikan string yang mewakili objek saat ini. |

### Lihat Juga

* kelas [AnnotationElement](../annotationelement/)
* antarmuka [IAdjustPosition](../../aspose.pdf.tagged/iadjustposition/)
* antarmuka [ITextElement](../itextelement/)
* ruang nama [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)