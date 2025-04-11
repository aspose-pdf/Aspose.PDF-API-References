---
title: Class FontCollection
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Text.FontCollection. Mewakili koleksi font
type: docs
weight: 10530
url: /id/net/aspose.pdf.text/fontcollection/
---
## Kelas FontCollection

Mewakili koleksi font.

```csharp
public sealed class FontCollection : ICollection<Font>
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Count](../../aspose.pdf.text/fontcollection/count/) { get; } | Mendapatkan jumlah elemen objek [`Font`](../font/) yang sebenarnya terkandung dalam koleksi. |
| [IsReadOnly](../../aspose.pdf.text/fontcollection/isreadonly/) { get; } | Mendapatkan nilai yang menunjukkan apakah koleksi bersifat hanya-baca |
| [IsSynchronized](../../aspose.pdf.text/fontcollection/issynchronized/) { get; } | Mendapatkan nilai yang menunjukkan apakah akses ke koleksi disinkronkan (aman untuk thread). |
| [Item](../../aspose.pdf.text/fontcollection/item/) { get; } | Mendapatkan elemen font pada indeks yang ditentukan. (2 pengindeks) |
| [SyncRoot](../../aspose.pdf.text/fontcollection/syncroot/) { get; } | Mendapatkan objek yang dapat digunakan untuk menyinkronkan akses ke koleksi. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Add](../../aspose.pdf.text/fontcollection/add/)(Font, out string) | Menambahkan font baru ke sumber font dan mengembalikan nama sumber font yang ditetapkan secara otomatis. |
| [Contains](../../aspose.pdf.text/fontcollection/contains/#contains)(Font) | Menentukan apakah koleksi mengandung nilai tertentu. |
| [Contains](../../aspose.pdf.text/fontcollection/contains/#contains_1)(string) | Memeriksa apakah font ada dalam koleksi font. |
| [CopyTo](../../aspose.pdf.text/fontcollection/copyto/)(Font[], int) | Menyalin seluruh koleksi ke Array satu dimensi yang kompatibel, mulai dari indeks yang ditentukan dari array target |
| [GetEnumerator](../../aspose.pdf.text/fontcollection/getenumerator/)() | Mengembalikan enumerator untuk seluruh koleksi. |
| [Remove](../../aspose.pdf.text/fontcollection/remove/)(Font) | Menghapus item yang ditentukan dari koleksi. |

## Catatan

Koleksi font yang diwakili oleh kelas `FontCollection` digunakan dalam beberapa skenario. Misalnya, dalam sumber daya dengan properti [`Fonts`](../../aspose.pdf/resources/fonts/).

## Contoh

Contoh ini menunjukkan cara membuat semua font yang dideklarasikan di halaman sebagai tersemat.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// ensure all fonts declared on page resources are embedded
// note that if fonts are declared on form resources they are not accessible from page resources
foreach(Aspose.Pdf.Txt.Font font in doc.Pages[1].Resources.Fonts)
{
    if(!font.IsEmbedded)
        font.IsEmbedded = true;
}

doc.Save(@"D:\Tests\input.pdf");
```

### Lihat Juga

* kelas [Font](../font/)
* ruang nama [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)