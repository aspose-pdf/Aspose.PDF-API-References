---
title: Class FontCollection
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.FontCollection sınıfı. Yazı tipi koleksiyonunu temsil eder
type: docs
weight: 10530
url: /tr/net/aspose.pdf.text/fontcollection/
---
## FontCollection Sınıfı

Yazı tipi koleksiyonunu temsil eder.

```csharp
public sealed class FontCollection : ICollection<Font>
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Count](../../aspose.pdf.text/fontcollection/count/) { get; } | Koleksiyonda gerçekten bulunan [`Font`](../font/) nesne elemanlarının sayısını alır. |
| [IsReadOnly](../../aspose.pdf.text/fontcollection/isreadonly/) { get; } | Koleksiyonun salt okunur olup olmadığını belirten bir değer alır. |
| [IsSynchronized](../../aspose.pdf.text/fontcollection/issynchronized/) { get; } | Koleksiyona erişimin senkronize olup olmadığını (iş parçacığı güvenli) belirten bir değer alır. |
| [Item](../../aspose.pdf.text/fontcollection/item/) { get; } | Belirtilen indeksteki yazı tipi elemanını alır. (2 indeksleyici) |
| [SyncRoot](../../aspose.pdf.text/fontcollection/syncroot/) { get; } | Koleksiyona erişimi senkronize etmek için kullanılabilecek bir nesne alır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [Add](../../aspose.pdf.text/fontcollection/add/)(Font, out string) | Yeni bir yazı tipini yazı tipi kaynaklarına ekler ve yazı tipi kaynağının otomatik olarak atanmış adını döner. |
| [Contains](../../aspose.pdf.text/fontcollection/contains/#contains)(Font) | Koleksiyonun belirli bir değeri içerip içermediğini belirler. |
| [Contains](../../aspose.pdf.text/fontcollection/contains/#contains_1)(string) | Yazı tipinin yazı tipi koleksiyonunda mevcut olup olmadığını kontrol eder. |
| [CopyTo](../../aspose.pdf.text/fontcollection/copyto/)(Font[], int) | Tüm koleksiyonu, hedef dizinin belirtilen indeksinden başlayarak uyumlu bir boyutsal diziye kopyalar. |
| [GetEnumerator](../../aspose.pdf.text/fontcollection/getenumerator/)() | Tüm koleksiyon için bir enumeratör döner. |
| [Remove](../../aspose.pdf.text/fontcollection/remove/)(Font) | Belirtilen öğeyi koleksiyondan siler. |

## Açıklamalar

`FontCollection` sınıfı tarafından temsil edilen yazı tipi koleksiyonları çeşitli senaryolarda kullanılır. Örneğin, [`Fonts`](../../aspose.pdf/resources/fonts/) özelliği ile kaynaklarda.

## Örnekler

Örnek, sayfada tanımlanan tüm yazı tiplerini gömülü hale getirmenin nasıl yapılacağını gösterir.

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

### Ayrıca Bakınız

* sınıf [Font](../font/)
* ad alanı [Aspose.Pdf.Text](../../aspose.pdf.text/)
* derleme [Aspose.PDF](../../)