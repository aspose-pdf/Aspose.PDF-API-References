---
title: TextFragmentAbsorber
second_title: Aspose.PDF for .NET API Referansı
description: Metin parçalarının bir emici nesnesini temsil eder. Metin araması gerçekleştirir ve aracılığıyla arama sonuçlarına erişim sağlar.TextFragments./textfragmentabsorber/textfragments koleksiyon.
type: docs
weight: 7110
url: /tr/net/aspose.pdf.text/textfragmentabsorber/
---
## TextFragmentAbsorber class

Metin parçalarının bir emici nesnesini temsil eder. Metin araması gerçekleştirir ve aracılığıyla arama sonuçlarına erişim sağlar.[`TextFragments`](./textfragments) koleksiyon.

```csharp
public sealed class TextFragmentAbsorber : TextAbsorber
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [TextFragmentAbsorber](textfragmentabsorber#constructor)() | Yeni bir örneğini başlatır[`TextFragmentAbsorber`](../textfragmentabsorber) belgenin veya sayfanın tüm metin bölümlerinde arama yapan. |
| [TextFragmentAbsorber](textfragmentabsorber#constructor_6)(Regex) | Yeni bir örneğini başlatır[`TextFragmentAbsorber`](../textfragmentabsorber) belirtilen System.Text.RegularExpressions.Regex sınıf nesnesi için sınıf. |
| [TextFragmentAbsorber](textfragmentabsorber#constructor_2)(string) | Yeni bir örneğini başlatır[`TextFragmentAbsorber`](../textfragmentabsorber) belirtilen metin ifadesi için sınıf. |
| [TextFragmentAbsorber](textfragmentabsorber#constructor_1)(TextEditOptions) | Yeni bir örneğini başlatır[`TextFragmentAbsorber`](../textfragmentabsorber)belgenin veya sayfanın tüm metin bölümlerinde arama yapan metin düzenleme seçenekleriyle. |
| [TextFragmentAbsorber](textfragmentabsorber#constructor_7)(Regex, TextEditOptions) | Yeni bir örneğini başlatır[`TextFragmentAbsorber`](../textfragmentabsorber) belirtilen metin ifadesi ve metin düzenleme seçenekleri için sınıf. |
| [TextFragmentAbsorber](textfragmentabsorber#constructor_8)(Regex, TextSearchOptions) | Yeni bir örneğini başlatır[`TextFragmentAbsorber`](../textfragmentabsorber) belirtilen metin ifadesi ve metin arama seçenekleri için sınıf. |
| [TextFragmentAbsorber](textfragmentabsorber#constructor_3)(string, TextEditOptions) | Yeni bir örneğini başlatır[`TextFragmentAbsorber`](../textfragmentabsorber) belirtilen metin ifadesi ve metin düzenleme seçenekleri için sınıf. |
| [TextFragmentAbsorber](textfragmentabsorber#constructor_4)(string, TextSearchOptions) | Yeni bir örneğini başlatır[`TextFragmentAbsorber`](../textfragmentabsorber)belirtilen metin ifadesi ve metin arama seçenekleri için sınıf. |
| [TextFragmentAbsorber](textfragmentabsorber#constructor_5)(string, TextSearchOptions, TextEditOptions) | Yeni bir örneğini başlatır[`TextFragmentAbsorber`](../textfragmentabsorber) belirtilen metin ifadesi için sınıf, metin arama seçenekleri ve metin düzenleme seçenekleri. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Errors](../../aspose.pdf.text/textfragmentabsorber/errors) { get; } | Listesi[`TextExtractionError`](../textextractionerror) nesneler. Metin çıkarma sırasında bulunan hatalarla ilgili bilgileri içerir. Hata arama, yalnızca TextSearchOptions.LogTextExtraksiyonErrors = true; Ve performansı düşürebilir. |
| override [ExtractionOptions](../../aspose.pdf.text/textfragmentabsorber/extractionoptions) { get; set; } | Metin çıkarma seçeneklerini alır veya ayarlar. |
| [HasErrors](../../aspose.pdf.text/textfragmentabsorber/haserrors) { get; } | Değer, metin çıkarma sırasında hataların bulunup bulunmadığını gösterir. Hata arama, yalnızca TextSearchOptions.LogTextExtraksiyonErrors = true; Ve performansı düşürebilir. |
| [Phrase](../../aspose.pdf.text/textfragmentabsorber/phrase) { get; set; } | Şu ifadeyi alır veya ayarlar:[`TextFragmentAbsorber`](../textfragmentabsorber) PDF belgesinde veya sayfasında arama yapar. |
| override [Text](../../aspose.pdf.text/textfragmentabsorber/text) { get; } | [`TextAbsorber`](../textabsorber) PDF belgesinden veya sayfasından alıntılar. |
| [TextEditOptions](../../aspose.pdf.text/textfragmentabsorber/texteditoptions) { get; set; } | Metin düzenleme seçeneklerini alır veya ayarlar. Seçenekler, istenen sembol font ile yazılamadığında özel davranışı tanımlar. |
| [TextFragments](../../aspose.pdf.text/textfragmentabsorber/textfragments) { get; set; } | İle sunulan arama olaylarının koleksiyonunu alır[`TextFragment`](../textfragment) nesneler. |
| [TextReplaceOptions](../../aspose.pdf.text/textfragmentabsorber/textreplaceoptions) { get; set; } | Metin değiştirme seçeneklerini alır veya ayarlar. Seçenekler, parça metni daha kısa/uzun olarak değiştirildiğinde davranışı tanımlar. |
| [TextSearchOptions](../../aspose.pdf.text/textfragmentabsorber/textsearchoptions) { get; set; } | Arama seçeneklerini alır veya ayarlar. Seçenekler, normal ifadeler kullanarak aramayı etkinleştirir. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments#applyforallfragments_2)(float) | Emilen tüm metin parçaları için yazı tipi boyutunu uygular. Sayfa(lar)daki tüm parçalar emilmişse, parçalar arasında döngü yapmaktan daha hızlı çalışır. Aksi takdirde looping. ile benzer şekilde çalışır. |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments#applyforallfragments)(Font) | Emilen tüm metin parçaları için yazı tipini uygular. Sayfa(lar)daki tüm parçalar emilmişse, parçalar arasında döngü yapmaktan daha hızlı çalışır. Aksi takdirde looping. ile benzer şekilde çalışır. |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments#applyforallfragments_1)(Font, float) | Emilen tüm metin parçaları için yazı tipini ve boyutunu uygular. Sayfa(lar)daki tüm parçalar emilmişse, parçalar arasında döngü yapmaktan daha hızlı çalışır. Aksi takdirde looping. ile benzer şekilde çalışır. |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext#removealltext)(Document) | Belgedeki tüm metni kaldırır. |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext#removealltext_1)(Page) | Belirtilen sayfadaki tüm metni kaldırır. |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext#removealltext_2)(Page, Rectangle) | Belirtilen dikdörtgenin içindeki metni belirtilen sayfadan kaldırır. |
| [Reset](../../aspose.pdf.text/textfragmentabsorber/reset)() | Bunun TextFragments koleksiyonunu temizler[`TextFragmentAbsorber`](../textfragmentabsorber) nesne. |
| override [Visit](../../aspose.pdf.text/textfragmentabsorber/visit#visit)(Document) | Belirtilen belge üzerinde arama yapar. |
| override [Visit](../../aspose.pdf.text/textfragmentabsorber/visit#visit_1)(Page) | Belirtilen sayfada arama yapar. |
| [Visit](../../aspose.pdf.text/textfragmentabsorber/visit#visit_2)(XForm) | Belirtilen form nesnesinde arama yapar. |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit)(XForm) | Belirtilen XForm'daki metni ayıklar. |

### Notlar

[`TextFragmentAbsorber`](../textfragmentabsorber) nesne temel olarak metin arama senaryosunda kullanılır. Arama tamamlandığında, oluşumlar şu şekilde gösterilir:[`TextFragment`](../textfragment) olan nesneler[`TextFragments`](./textfragments) koleksiyon şunları içerir. [`TextFragment`](../textfragment) nesne, arama oluşum metnine, metin özelliklerine erişim sağlar ve metni düzenlemeye ve metin durumunu (yazı tipi, yazı tipi boyutu, renk vb.) değiştirmeye izin verir.

### Örnekler

Örnek, ilk PDF belgesi sayfasındaki metnin nasıl bulunacağını ve metnin ve yazı tipinin nasıl değiştirileceğini gösterir.

```csharp
// Belgeyi aç
Document doc = new Document(@"D:\Tests\input.pdf");

// Belge metni yazı tipini değiştirmek için kullanılacak yazı tipini bulun
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Tüm "merhaba dünya" metin oluşumlarını bulmak için TextFragmentAbsorber nesnesi oluşturun
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// İlk sayfa için emiciyi kabul et
doc.Pages[1].Accept(absorber);

// İlk metin oluşumunun metnini ve yazı tipini değiştirin
absorber.TextFragments[1].Text = "hi world";
absorber.TextFragments[1].TextState.Font = font;

// Belgeyi kaydet
doc.Save(@"D:\Tests\output.pdf");  
```

### Ayrıca bakınız

* class [TextAbsorber](../textabsorber)
* ad alanı [Aspose.Pdf.Text](../../aspose.pdf.text)
* toplantı [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
