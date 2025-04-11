---
title: Class CharInfoCollection
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Text.CharInfoCollection. Mewakili koleksi objek CharInfo
type: docs
weight: 10450
url: /id/net/aspose.pdf.text/charinfocollection/
---
## Kelas CharInfoCollection

Mewakili koleksi objek CharInfo.

```csharp
public sealed class CharInfoCollection : ICollection<CharInfo>
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Count](../../aspose.pdf.text/charinfocollection/count/) { get; } | Mendapatkan jumlah elemen objek [`CharInfo`](../charinfo/) yang sebenarnya terdapat dalam koleksi. |
| [IsReadOnly](../../aspose.pdf.text/charinfocollection/isreadonly/) { get; } | Mendapatkan nilai yang menunjukkan apakah koleksi bersifat hanya-baca |
| [IsSynchronized](../../aspose.pdf.text/charinfocollection/issynchronized/) { get; } | Mendapatkan nilai yang menunjukkan apakah akses ke koleksi disinkronkan (aman untuk thread). |
| [Item](../../aspose.pdf.text/charinfocollection/item/) { get; } | Mendapatkan elemen CharInfo pada indeks yang ditentukan. |
| [SyncRoot](../../aspose.pdf.text/charinfocollection/syncroot/) { get; } | Mendapatkan objek yang dapat digunakan untuk menyinkronkan akses ke koleksi. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Add](../../aspose.pdf.text/charinfocollection/add/)(CharInfo) | Koleksi bersifat hanya-baca, melempar NotImplementedException. |
| [Clear](../../aspose.pdf.text/charinfocollection/clear/)() | Koleksi bersifat hanya-baca. Selalu melempar NotImplementedException. |
| [Contains](../../aspose.pdf.text/charinfocollection/contains/)(CharInfo) | Menentukan apakah koleksi mengandung nilai tertentu. |
| [CopyTo](../../aspose.pdf.text/charinfocollection/copyto/)(CharInfo[], int) | Menyalin seluruh koleksi ke Array satu dimensi yang kompatibel, mulai dari indeks yang ditentukan dari array target |
| [GetEnumerator](../../aspose.pdf.text/charinfocollection/getenumerator/)() | Mengembalikan enumerator untuk seluruh koleksi. |
| [Remove](../../aspose.pdf.text/charinfocollection/remove/)(CharInfo) | Koleksi bersifat hanya-baca, melempar NotImplementedException. |

## Catatan

Memberikan akses ke informasi pemposisian karakter segmen teks.

## Contoh

Contoh ini menunjukkan cara untuk mengiterasi semua karakter dan mengambil karakter

```csharp
//open document
Document pdfDocument = new Document(inFile);
//create TextFragmentAbsorber object to collect all the text objects of the page
TextFragmentAbsorber textFragmentAbsorber = new TextFragmentAbsorber();
//accept the absorber for all the pages
pdfDocument.Pages[1].Accept(textFragmentAbsorber);
//get the extracted text fragments
TextFragmentCollection textFragmentCollection = textFragmentAbsorber.TextFragments;
            
//loop through the fragments
foreach (TextFragment textFragment in textFragmentCollection)
{
    //loop through the segments
    foreach (TextSegment textSegment in textFragment.Segments)
    {
        //loop through the characters
        for (int i = 1; i <= textSegment.Text.Length; i++)
        {
            CharInfo charInfo = textSegment.Characters[i];

            // print character position and rectangle info
            Console.WriteLine("XIndent : {0} ", charInfo.Position.XIndent);
            Console.WriteLine("YIndent : {0} ", charInfo.Position.YIndent);
            Console.WriteLine("Width : {0} ", charInfo.Rectangle.Width);
            Console.WriteLine("Height : {0} ", charInfo.Rectangle.Height);
        }
    }
}
```

### Lihat Juga

* kelas [CharInfo](../charinfo/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)