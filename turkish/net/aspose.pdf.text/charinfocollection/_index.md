---
title: Class CharInfoCollection
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.CharInfoCollection sınıfı. CharInfo nesneleri koleksiyonunu temsil eder
type: docs
weight: 10450
url: /tr/net/aspose.pdf.text/charinfocollection/
---
## CharInfoCollection Sınıfı

CharInfo nesneleri koleksiyonunu temsil eder.

```csharp
public sealed class CharInfoCollection : ICollection<CharInfo>
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Count](../../aspose.pdf.text/charinfocollection/count/) { get; } | Koleksiyonda gerçekten bulunan [`CharInfo`](../charinfo/) nesne elemanlarının sayısını alır. |
| [IsReadOnly](../../aspose.pdf.text/charinfocollection/isreadonly/) { get; } | Koleksiyonun salt okunur olup olmadığını belirten bir değer alır. |
| [IsSynchronized](../../aspose.pdf.text/charinfocollection/issynchronized/) { get; } | Koleksiyona erişimin senkronize olup olmadığını (iş parçacığı güvenli) belirten bir değer alır. |
| [Item](../../aspose.pdf.text/charinfocollection/item/) { get; } | Belirtilen indeksteki CharInfo elemanını alır. |
| [SyncRoot](../../aspose.pdf.text/charinfocollection/syncroot/) { get; } | Koleksiyona erişimi senkronize etmek için kullanılabilecek bir nesne alır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [Add](../../aspose.pdf.text/charinfocollection/add/)(CharInfo) | Koleksiyon salt okunur, NotImplementedException fırlatır. |
| [Clear](../../aspose.pdf.text/charinfocollection/clear/)() | Koleksiyon salt okunur. Her zaman NotImplementedException fırlatır. |
| [Contains](../../aspose.pdf.text/charinfocollection/contains/)(CharInfo) | Koleksiyonun belirli bir değeri içerip içermediğini belirler. |
| [CopyTo](../../aspose.pdf.text/charinfocollection/copyto/)(CharInfo[], int) | Tüm koleksiyonu, hedef dizinin belirtilen indeksinden başlayarak uyumlu bir boyutsal Diziye kopyalar. |
| [GetEnumerator](../../aspose.pdf.text/charinfocollection/getenumerator/)() | Tüm koleksiyon için bir enumerator döndürür. |
| [Remove](../../aspose.pdf.text/charinfocollection/remove/)(CharInfo) | Koleksiyon salt okunur, NotImplementedException fırlatır. |

## Açıklamalar

Metin segmenti karakterlerinin konum bilgilerine erişim sağlar.

## Örnekler

Örnek, tüm karakterler arasında nasıl döngü yapılacağını ve karakterin nasıl alınacağını gösterir.

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

### Ayrıca Bakınız

* sınıf [CharInfo](../charinfo/)
* ad alanı [Aspose.Pdf.Text](../../aspose.pdf.text/)
* derleme [Aspose.PDF](../../)