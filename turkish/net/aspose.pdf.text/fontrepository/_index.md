---
title: Class FontRepository
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.FontRepository sınıfı. Yazı tipi araması yapar. Sistem kurulu yazı tiplerinde ve standart Pdf yazı tiplerinde arama yapar. Ayrıca özel yazı tiplerini açma işlevselliği sağlar.
type: docs
weight: 10540
url: /tr/net/aspose.pdf.text/fontrepository/
---
## FontRepository Sınıfı

Yazı tipi araması yapar. Sistem kurulu yazı tiplerinde ve standart Pdf yazı tiplerinde arama yapar. Ayrıca özel yazı tiplerini açma işlevselliği sağlar.

```csharp
public sealed class FontRepository
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [FontRepository](fontrepository/)() | Varsayılan yapıcı. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| static [Sources](../../aspose.pdf.text/fontrepository/sources/) { get; } | Yazı tipi kaynakları koleksiyonunu alır. |
| static [Substitutions](../../aspose.pdf.text/fontrepository/substitutions/) { get; } | Yazı tipi değiştirme stratejileri koleksiyonunu alır. |

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont)(string) | Belirtilen yazı tipi adıyla yazı tipini arar ve döndürür. |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont_3)(string, bool) | Belirtilen yazı tipi adıyla yazı tipini arar ve döndürür, büyük/küçük harf duyarlılığını göz ardı eder veya dikkate alır. |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont_1)(string, FontStyles) | Belirtilen yazı tipi adı ve yazı tipi stiliyle yazı tipini arar ve döndürür. |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont_2)(string, FontStyles, bool) | Belirtilen yazı tipi adı ve yazı tipi stiliyle yazı tipini arar ve döndürür, büyük/küçük harf duyarlılığını göz ardı eder veya dikkate alır. |
| static [LoadFonts](../../aspose.pdf.text/fontrepository/loadfonts/)() | Sistem kurulu yazı tiplerini ve standart Pdf yazı tiplerini yükler. Bu yöntem, yazı tipi yükleme sürecini hızlandırmak için tasarlanmıştır. Varsayılan olarak, yazı tipleri herhangi bir yazı tipi için ilk istekte yüklenir. Bu yöntemin kullanımı, herhangi bir Pdf belgesi açılmadan önce sistem ve standart Pdf yazı tiplerini hemen yükler. |
| static [OpenFont](../../aspose.pdf.text/fontrepository/openfont/#openfont_1)(string) | Belirtilen yazı tipi dosyası yolu ile yazı tipini açar. |
| static [OpenFont](../../aspose.pdf.text/fontrepository/openfont/#openfont)(Stream, FontTypes) | Belirtilen yazı tipi akışı ile yazı tipini açar. |
| static [OpenFont](../../aspose.pdf.text/fontrepository/openfont/#openfont_2)(string, string) | Belirtilen yazı tipi dosyası yolu ve metrik dosyası yolu ile yazı tipini açar. |
| static [ReloadFonts](../../aspose.pdf.text/fontrepository/reloadfonts/)() | [`Sources`](./sources/) özelliği ile belirtilen tüm yazı tiplerini yeniden yükler. |

## Örnekler

Örnek, yazı tipini bulmayı ve ilk sayfadaki metnin yazı tipini değiştirmeyi gösterir.

```csharp
// Find font
Font font = FontRepository.FindFont("Arial");

// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change font of the first text occurrence
absorber.TextFragments[1].TextState.Font = font;

// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### Ayrıca Bakınız

* sınıf [TextFragmentAbsorber](../textfragmentabsorber/)
* sınıf [Document](../../aspose.pdf/document/)
* ad alanı [Aspose.Pdf.Text](../../aspose.pdf.text/)
* derleme [Aspose.PDF](../../)