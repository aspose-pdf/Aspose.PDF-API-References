---
title: "Kelas FontCollection"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.Text.FontCollection. Mewakili koleksi font"
type: docs
weight: 10710
url: /id/net/aspose.pdf.text/fontcollection/
---
## FontCollection class

Mewakili koleksi font.

```csharp
public sealed class FontCollection : ICollection<Font>
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Count](../../aspose.pdf.text/fontcollection/count/) { get; } | Mendapatkan jumlah elemen objek [`Font`](../font/) yang sebenarnya terdapat dalam koleksi. |
| [IsReadOnly](../../aspose.pdf.text/fontcollection/isreadonly/) { get; } | Mendapatkan nilai yang menunjukkan apakah koleksi bersifat read-only |
| [IsSynchronized](../../aspose.pdf.text/fontcollection/issynchronized/) { get; } | Mendapatkan nilai yang menunjukkan apakah akses ke koleksi disinkronkan (aman untuk thread). |
| [Item](../../aspose.pdf.text/fontcollection/item/) { get; } | Mendapatkan elemen font pada indeks yang ditentukan. (2 indexer) |
| [SyncRoot](../../aspose.pdf.text/fontcollection/syncroot/) { get; } | Mendapatkan objek yang dapat digunakan untuk menyinkronkan akses ke koleksi. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Add](../../aspose.pdf.text/fontcollection/add/)(Font, out string) | Menambahkan font baru ke sumber daya font dan mengembalikan nama yang secara otomatis diberikan untuk sumber daya font. |
| [Contains](../../aspose.pdf.text/fontcollection/contains/#contains)(Font) | Menentukan apakah koleksi berisi nilai tertentu. |
| [Contains](../../aspose.pdf.text/fontcollection/contains/#contains_1)(string) | Memeriksa apakah font ada dalam koleksi font. |
| [CopyTo](../../aspose.pdf.text/fontcollection/copyto/)(Font[], int) | Menyalin seluruh koleksi ke Array satu dimensi yang kompatibel, mulai dari indeks yang ditentukan pada array target. |
| [GetEnumerator](../../aspose.pdf.text/fontcollection/getenumerator/)() | Mengembalikan enumerator untuk seluruh koleksi. |
| [Remove](../../aspose.pdf.text/fontcollection/remove/)(Font) | Menghapus item yang ditentukan dari koleksi. |

## Catatan

Koleksi font yang diwakili oleh kelas `FontCollection` digunakan dalam beberapa skenario. Misalnya, dalam sumber daya dengan properti [`Fonts`](../../aspose.pdf/resources/fonts/).

## Contoh

Contoh ini menunjukkan cara menjadikan semua font yang dideklarasikan pada halaman sebagai tersemat.

```csharp
// Buka dokumen
Document doc = new Document(@"D:\Tests\input.pdf");

// pastikan semua font yang dideklarasikan pada sumber daya halaman tersemat
// catatan bahwa jika font dideklarasikan pada sumber daya formulir, mereka tidak dapat diakses dari sumber daya halaman
foreach(Aspose.Pdf.Txt.Font font in doc.Pages[1].Resources.Fonts)
{
    if(!font.IsEmbedded)
        font.IsEmbedded = true;
}

doc.Save(@"D:\Tests\input.pdf");
```

### Lihat Juga

* class [Font](../font/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


