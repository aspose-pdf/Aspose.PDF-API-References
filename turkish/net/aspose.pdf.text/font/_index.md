---
title: Class Font
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.Font sınıfı. Yazı tipi nesnesini temsil eder
type: docs
weight: 10510
url: /tr/net/aspose.pdf.text/font/
---
## Font sınıfı

Yazı tipi nesnesini temsil eder.

```csharp
public sealed class Font
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [BaseFont](../../aspose.pdf.text/font/basefont/) { get; } | PDF yazı tipi nesnesinin BaseFont değerini alır. Yazı tipinin PostScript adı olarak da bilinir. |
| [DecodedFontName](../../aspose.pdf.text/font/decodedfontname/) { get; } | Bazen PDF yazı tipleri (genellikle Çince/Japonca/Korece yazı tipleri) belirli bir yazı tipi adına sahip olabilir. Bu ad, PDF yazı tipi özelliği "BaseFont" değeridir ve bazen bu özellik onaltılık biçimde temsil edilebilir. Bu adı doğrudan okursanız, okunamaz bir biçimde temsil edilebilir. Okunabilir bir biçim elde etmek için, bu yazı tipi için belirli kurallara göre yazı tipinin adını çözmek gereklidir. Bu özellik, okunamaz bir [`FontName`](./fontname/) ile karşılaştığınız durumlar için çözülmüş yazı tipi adını döndürür. Eğer [`FontName`](./fontname/) özelliği okunabilir bir biçimdeyse, bu özellik [`FontName`](./fontname/) ile aynı olacaktır, bu nedenle yazı tipi adını okunabilir bir biçimde almak istediğiniz her durumda bu özelliği kullanabilirsiniz. |
| [FontName](../../aspose.pdf.text/font/fontname/) { get; } | `Font` nesnesinin yazı tipi adını alır. |
| [FontOptions](../../aspose.pdf.text/font/fontoptions/) { get; } | Yazı tipi davranışını ayarlamak için yararlı özellikler |
| [IsAccessible](../../aspose.pdf.text/font/isaccessible/) { get; } | Yazı tipinin sistemde mevcut (kurulu) olup olmadığını gösterir. |
| [IsEmbedded](../../aspose.pdf.text/font/isembedded/) { get; set; } | Yazı tipinin gömülü olup olmadığını gösteren bir değeri alır veya ayarlar. IFont'a dayalı yazı tipleri otomatik olarak alt küme yapılır ve gömülür. |
| [IsSubset](../../aspose.pdf.text/font/issubset/) { get; set; } | Yazı tipinin bir alt küme olup olmadığını gösteren bir değeri alır veya ayarlar. IFont'a dayalı yazı tipleri otomatik olarak alt küme yapılır ve gömülür. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [GetLastFontEmbeddingError](../../aspose.pdf.text/font/getlastfontembeddingerror/)() | Bu yöntemin amacı, yazı tipini gömmek için yapılan bir denemenin başarısız olması durumunda hata açıklamasını döndürmektir. Hata durumu yoksa boş bir dize döndürür. |
| [MeasureString](../../aspose.pdf.text/font/measurestring/)(string, float) | Dizeyi ölçer. |
| [Save](../../aspose.pdf.text/font/save/)(Stream) | Yazı tipini akışa kaydeder. Yazı tipinin yalnızca orijinal belgenin dönüştürülmüş kopyasında kullanılmak üzere ara TTF formatında kaydedildiğini unutmayın. Yazı tipi dosyası, orijinal belge bağlamı dışında kullanılmak üzere tasarlanmamıştır. |

## Örnekler

Örnek, ilk sayfadaki metni nasıl arayacağınızı ve ilk arama bulgusunun yazı tipini nasıl değiştireceğinizi gösterir.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Create font and mark it to be embedded
Font font = FontRepository.FindFont("Arial");
font.IsEmbedded = true;

// Change font of the first text occurrence
absorber.TextFragments[1].TextState.Font = font;


// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### Ayrıca Bakınız

* sınıf [TextFragmentAbsorber](../textfragmentabsorber/)
* sınıf [FontRepository](../fontrepository/)
* sınıf [Document](../../aspose.pdf/document/)
* ad alanı [Aspose.Pdf.Text](../../aspose.pdf.text/)
* derleme [Aspose.PDF](../../)