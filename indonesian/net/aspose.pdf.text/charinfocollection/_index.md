---
title: "Kelas CharInfoCollection"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.Text.CharInfoCollection. Mewakili koleksi objek CharInfo"
type: docs
weight: 10630
url: /id/net/aspose.pdf.text/charinfocollection/
---
## CharInfoCollection class

Mewakili koleksi objek CharInfo.

```csharp
public sealed class CharInfoCollection : ICollection<CharInfo>
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Count](../../aspose.pdf.text/charinfocollection/count/) { get; } | Mendapatkan jumlah elemen objek [`CharInfo`](../charinfo/) yang sebenarnya terdapat dalam koleksi. |
| [IsReadOnly](../../aspose.pdf.text/charinfocollection/isreadonly/) { get; } | Mendapatkan nilai yang menunjukkan apakah koleksi bersifat read-only |
| [IsSynchronized](../../aspose.pdf.text/charinfocollection/issynchronized/) { get; } | Mendapatkan nilai yang menunjukkan apakah akses ke koleksi disinkronkan (aman untuk thread). |
| [Item](../../aspose.pdf.text/charinfocollection/item/) { get; } | Mendapatkan elemen CharInfo pada indeks yang ditentukan. |
| [SyncRoot](../../aspose.pdf.text/charinfocollection/syncroot/) { get; } | Mendapatkan objek yang dapat digunakan untuk menyinkronkan akses ke koleksi. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Add](../../aspose.pdf.text/charinfocollection/add/)(CharInfo) | Koleksi bersifat read-only, melempar NotImplementedException. |
| [Clear](../../aspose.pdf.text/charinfocollection/clear/)() | Koleksi bersifat read-only. Selalu melempar NotImplementedException. |
| [Contains](../../aspose.pdf.text/charinfocollection/contains/)(CharInfo) | Menentukan apakah koleksi berisi nilai tertentu. |
| [CopyTo](../../aspose.pdf.text/charinfocollection/copyto/)(CharInfo[], int) | Menyalin seluruh koleksi ke Array satu dimensi yang kompatibel, mulai dari indeks yang ditentukan pada array target. |
| [GetEnumerator](../../aspose.pdf.text/charinfocollection/getenumerator/)() | Mengembalikan enumerator untuk seluruh koleksi. |
| [Remove](../../aspose.pdf.text/charinfocollection/remove/)(CharInfo) | Koleksi bersifat read-only, melempar NotImplementedException. |

## Catatan

Menyediakan akses ke informasi posisi karakter segmen teks.

## Contoh

Contoh ini menunjukkan cara mengiterasi semua karakter dan mengambil charact

```csharp
//buka dokumen
Document pdfDocument = new Document(inFile);
//buat objek TextFragmentAbsorber untuk mengumpulkan semua objek teks pada halaman
TextFragmentAbsorber textFragmentAbsorber = new TextFragmentAbsorber();
//terima absorber untuk semua halaman
pdfDocument.Pages[1].Accept(textFragmentAbsorber);
//dapatkan fragmen teks yang diekstrak
TextFragmentCollection textFragmentCollection = textFragmentAbsorber.TextFragments;
            
//loop melalui fragmen
foreach (TextFragment textFragment in textFragmentCollection)
{
    //loop melalui segmen
    foreach (TextSegment textSegment in textFragment.Segments)
    {
        //loop melalui karakter
        for (int i = 1; i <= textSegment.Text.Length; i++)
        {
            CharInfo charInfo = textSegment.Characters[i];

            // cetak posisi karakter dan info persegi panjang
            Console.WriteLine("XIndent : {0} ", charInfo.Position.XIndent);
            Console.WriteLine("YIndent : {0} ", charInfo.Position.YIndent);
            Console.WriteLine("Width : {0} ", charInfo.Rectangle.Width);
            Console.WriteLine("Height : {0} ", charInfo.Rectangle.Height);
        }
    }
}
```

### Lihat Juga

* class [CharInfo](../charinfo/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


