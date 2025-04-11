---
title: Class TableCellElement
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.LogicalStructure.TableCellElement. Mewakili kelas dasar untuk elemen sel tabel TH dan TD dalam struktur logis
type: docs
weight: 6760
url: /id/net/aspose.pdf.logicalstructure/tablecellelement/
---
## Kelas TableCellElement

Mewakili kelas dasar untuk elemen sel tabel (TH dan TD) dalam struktur logis.

```csharp
public abstract class TableCellElement : TableChildElement, IAdjustPosition, ITextElement
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [ActualText](../../aspose.pdf.logicalstructure/structureelement/actualtext/) { get; set; } | Mendapatkan atau mengatur teks aktual untuk elemen struktur. |
| [Alignment](../../aspose.pdf.logicalstructure/tablecellelement/alignment/) { get; set; } | Mendapatkan atau mengatur perataan sel. |
| [AlternativeText](../../aspose.pdf.logicalstructure/structureelement/alternativetext/) { get; set; } | Mendapatkan atau mengatur teks alternatif untuk elemen struktur. |
| [Attributes](../../aspose.pdf.logicalstructure/structureelement/attributes/) { get; } | Mendapatkan objek StructureAttributeCollection. |
| [BackgroundColor](../../aspose.pdf.logicalstructure/tablecellelement/backgroundcolor/) { get; set; } | Mendapatkan atau mengatur warna latar belakang sel. |
| [Border](../../aspose.pdf.logicalstructure/tablecellelement/border/) { get; set; } | Mendapatkan atau mengatur batas sel. |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | Mendapatkan koleksi anak dari objek Element. |
| [ColSpan](../../aspose.pdf.logicalstructure/tablecellelement/colspan/) { get; set; } | Mendapatkan atau mengatur rentang kolom. |
| [DefaultAttributeOwner](../../aspose.pdf.logicalstructure/structureelement/defaultattributeowner/) { get; } | Mendapatkan objek AttributeOwnerStandard. |
| [DefaultCellTextState](../../aspose.pdf.logicalstructure/tablecellelement/defaultcelltextstate/) { get; set; } | Mendapatkan atau mengatur status teks sel default. |
| [ExpansionText](../../aspose.pdf.logicalstructure/structureelement/expansiontext/) { get; set; } | Mendapatkan atau mengatur teks ekspansi untuk elemen struktur. |
| [ID](../../aspose.pdf.logicalstructure/structureelement/id/) { get; } | Mendapatkan ID untuk elemen struktur. |
| [IsNoBorder](../../aspose.pdf.logicalstructure/tablecellelement/isnoborder/) { get; set; } | Mendapatkan atau mengatur apakah sel memiliki batas. |
| [IsWordWrapped](../../aspose.pdf.logicalstructure/tablecellelement/iswordwrapped/) { get; set; } | Mendapatkan atau mengatur apakah teks sel dibungkus kata. |
| [Language](../../aspose.pdf.logicalstructure/structureelement/language/) { get; set; } | Mendapatkan atau mengatur bahasa untuk elemen struktur. |
| [Margin](../../aspose.pdf.logicalstructure/tablecellelement/margin/) { get; set; } | Mendapatkan atau mengatur padding. |
| [Page](../../aspose.pdf.logicalstructure/structureelement/page/) { get; } | Mendapatkan halaman di mana beberapa atau semua elemen anak akan dirender. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | Mendapatkan elemen induk. |
| [RowSpan](../../aspose.pdf.logicalstructure/tablecellelement/rowspan/) { get; set; } | Mendapatkan atau mengatur rentang baris. |
| [StructureTextState](../../aspose.pdf.logicalstructure/tablecellelement/structuretextstate/) { get; } | Mendapatkan objek StructureTextState untuk elemen saat ini. |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype/) { get; } | Mendapatkan jenis elemen struktur. |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title/) { get; set; } | Mendapatkan atau mengatur judul untuk elemen struktur. |
| [VerticalAlignment](../../aspose.pdf.logicalstructure/tablecellelement/verticalalignment/) { get; set; } | Mendapatkan atau mengatur perataan vertikal. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [AdjustPosition](../../aspose.pdf.logicalstructure/tablecellelement/adjustposition/)(PositionSettings) |  |
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
| [SetText](../../aspose.pdf.logicalstructure/tablecellelement/settext/)(string) |  |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Annotation) | Mengikat elemen struktur ke Anotasi. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Artifact) | Mengikat elemen struktur ke Artefak. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(BDC) | Mengikat elemen struktur ke operator aliran konten BDC. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XForm) | Mengikat elemen struktur ke aliran konten XForm. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XImage) | Mengikat elemen struktur ke XImage. |
| override [ToString](../../aspose.pdf.logicalstructure/structureelement/tostring/)() | Mengembalikan string yang mewakili objek saat ini. |

### Lihat Juga

* kelas [TableChildElement](../tablechildelement/)
* antarmuka [IAdjustPosition](../../aspose.pdf.tagged/iadjustposition/)
* antarmuka [ITextElement](../itextelement/)
* ruang nama [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)