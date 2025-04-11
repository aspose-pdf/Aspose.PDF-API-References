---
title: Class TableElement
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.LogicalStructure.TableElement. Mewakili elemen struktur Tabel dalam struktur logis
type: docs
weight: 6780
url: /id/net/aspose.pdf.logicalstructure/tableelement/
---
## Kelas TableElement

Mewakili elemen struktur Tabel dalam struktur logis.

```csharp
public sealed class TableElement : BLSElement, IAdjustPosition
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [ActualText](../../aspose.pdf.logicalstructure/structureelement/actualtext/) { get; set; } | Mendapatkan atau mengatur teks aktual untuk elemen struktur. |
| [Alignment](../../aspose.pdf.logicalstructure/tableelement/alignment/) { get; set; } | Mendapatkan atau mengatur perataan tabel. |
| [AlternativeText](../../aspose.pdf.logicalstructure/structureelement/alternativetext/) { get; set; } | Mendapatkan atau mengatur teks alternatif untuk elemen struktur. |
| [Attributes](../../aspose.pdf.logicalstructure/structureelement/attributes/) { get; } | Mendapatkan objek StructureAttributeCollection. |
| [BackgroundColor](../../aspose.pdf.logicalstructure/tableelement/backgroundcolor/) { get; set; } | Mendapatkan atau mengatur warna latar belakang tabel. |
| [Border](../../aspose.pdf.logicalstructure/tableelement/border/) { get; set; } | Mendapatkan atau mengatur batas tabel. |
| [Broken](../../aspose.pdf.logicalstructure/tableelement/broken/) { get; set; } | Mendapatkan atau mengatur tabel vertikal yang terputus; |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | Mendapatkan koleksi anak dari objek Elemen. |
| [ColumnAdjustment](../../aspose.pdf.logicalstructure/tableelement/columnadjustment/) { get; set; } | Mendapatkan atau mengatur penyesuaian kolom tabel. |
| [ColumnWidths](../../aspose.pdf.logicalstructure/tableelement/columnwidths/) { get; set; } | Mendapatkan lebar kolom tabel. |
| [CornerStyle](../../aspose.pdf.logicalstructure/tableelement/cornerstyle/) { get; set; } | Mendapatkan atau mengatur gaya sudut batas |
| [DefaultAttributeOwner](../../aspose.pdf.logicalstructure/structureelement/defaultattributeowner/) { get; } | Mendapatkan objek AttributeOwnerStandard. |
| [DefaultCellBorder](../../aspose.pdf.logicalstructure/tableelement/defaultcellborder/) { get; set; } | Mendapatkan batas sel default. |
| [DefaultCellPadding](../../aspose.pdf.logicalstructure/tableelement/defaultcellpadding/) { get; set; } | Mendapatkan atau mengatur padding sel default. |
| [DefaultCellTextState](../../aspose.pdf.logicalstructure/tableelement/defaultcelltextstate/) { get; set; } | Mendapatkan atau mengatur status teks sel default. |
| [DefaultColumnWidth](../../aspose.pdf.logicalstructure/tableelement/defaultcolumnwidth/) { get; set; } | Mendapatkan atau mengatur lebar kolom default. |
| [ExpansionText](../../aspose.pdf.logicalstructure/structureelement/expansiontext/) { get; set; } | Mendapatkan atau mengatur teks ekspansi untuk elemen struktur. |
| [ID](../../aspose.pdf.logicalstructure/structureelement/id/) { get; } | Mendapatkan ID untuk elemen struktur. |
| [IsBordersIncluded](../../aspose.pdf.logicalstructure/tableelement/isbordersincluded/) { get; set; } | Mendapatkan atau mengatur batas yang termasuk dalam lebar kolom. |
| [IsBroken](../../aspose.pdf.logicalstructure/tableelement/isbroken/) { get; set; } | Mendapatkan atau mengatur apakah tabel terputus - akan dipotong untuk halaman berikutnya. |
| [Language](../../aspose.pdf.logicalstructure/structureelement/language/) { get; set; } | Mendapatkan atau mengatur bahasa untuk elemen struktur. |
| [Left](../../aspose.pdf.logicalstructure/tableelement/left/) { get; set; } | Mendapatkan atau mengatur koordinat kiri tabel. |
| [Page](../../aspose.pdf.logicalstructure/structureelement/page/) { get; } | Mendapatkan halaman di mana beberapa atau semua elemen anak akan dirender. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | Mendapatkan elemen induk. |
| [RepeatingColumnsCount](../../aspose.pdf.logicalstructure/tableelement/repeatingcolumnscount/) { get; set; } | Mendapatkan atau mengatur jumlah kolom maksimum untuk tabel. |
| [RepeatingRowsCount](../../aspose.pdf.logicalstructure/tableelement/repeatingrowscount/) { get; set; } | Mendapatkan jumlah baris pertama yang diulang untuk beberapa halaman. |
| [RepeatingRowsStyle](../../aspose.pdf.logicalstructure/tableelement/repeatingrowsstyle/) { get; set; } | Mendapatkan gaya untuk baris yang diulang. |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype/) { get; } | Mendapatkan tipe elemen struktur. |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title/) { get; set; } | Mendapatkan atau mengatur judul untuk elemen struktur. |
| [Top](../../aspose.pdf.logicalstructure/tableelement/top/) { get; set; } | Mendapatkan atau mengatur koordinat atas tabel. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [AdjustPosition](../../aspose.pdf.logicalstructure/tableelement/adjustposition/)(PositionSettings) |  |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | Menambahkan Elemen ke koleksi anak. |
| [ChangeParentElement](../../aspose.pdf.logicalstructure/structureelement/changeparentelement/)(StructureElement, bool) | Mengubah elemen induk untuk elemen struktur saat ini |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | Menghapus semua anak. |
| [ClearId](../../aspose.pdf.logicalstructure/structureelement/clearid/)() | Menghapus ID untuk elemen struktur. |
| [CreateTBody](../../aspose.pdf.logicalstructure/tableelement/createtbody/)() | Membuat [`TableTHeadElement`](../tabletheadelement/) dan menambahkannya ke tabel saat ini. |
| [CreateTFoot](../../aspose.pdf.logicalstructure/tableelement/createtfoot/)() | Membuat [`TableTFootElement`](../tabletfootelement/) dan menambahkannya ke tabel saat ini. |
| [CreateTHead](../../aspose.pdf.logicalstructure/tableelement/createthead/)() | Membuat [`TableTHeadElement`](../tabletheadelement/) dan menambahkannya ke tabel saat ini. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | Mencari Elemen dari tipe tertentu |
| [GenerateId](../../aspose.pdf.logicalstructure/structureelement/generateid/)() | Menghasilkan ID untuk elemen struktur. |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | Menyisipkan Elemen ke koleksi anak pada indeks yang ditentukan. |
| [Remove](../../aspose.pdf.logicalstructure/structureelement/remove/)() | Menghapus: elemen dari struktur, referensi ke elemen dari objek induk, referensi ke elemen dari objek anak, objek yang sesuai dari dokumen. |
| [RemoveAndMoveItsChildObjectsToItsParent](../../aspose.pdf.logicalstructure/structureelement/removeandmoveitschildobjectstoitsparent/)(bool) | Menghapus elemen dari struktur, referensi ke elemen dari objek induk, referensi ke elemen dari objek anak, dan objek yang sesuai dari dokumen. Menyisipkan objek anak dari objek yang dihapus ke dalam koleksi objek anak induknya yang sebelumnya mulai dari indeks objek yang dihapus. |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | Menghapus anak pada. |
| [SetId](../../aspose.pdf.logicalstructure/structureelement/setid/)(string) | Mengatur ID untuk elemen struktur. |
| [SetTag](../../aspose.pdf.logicalstructure/structureelement/settag/)(string) | Mengatur tag kustom untuk elemen struktur. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Annotation) | Mengikat elemen struktur ke Anotasi. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Artifact) | Mengikat elemen struktur ke Artefak. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(BDC) | Mengikat elemen struktur ke operator BDC aliran konten. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XForm) | Mengikat elemen struktur ke XForm aliran konten. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XImage) | Mengikat elemen struktur ke XImage. |
| override [ToString](../../aspose.pdf.logicalstructure/structureelement/tostring/)() | Mengembalikan string yang mewakili objek saat ini. |

### Lihat Juga

* kelas [BLSElement](../blselement/)
* antarmuka [IAdjustPosition](../../aspose.pdf.tagged/iadjustposition/)
* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)