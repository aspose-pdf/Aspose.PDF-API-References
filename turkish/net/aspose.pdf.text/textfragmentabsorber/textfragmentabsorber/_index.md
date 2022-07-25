---
title: TextFragmentAbsorber
second_title: Aspose.PDF for .NET API Referansı
description: Yeni bir örneğini başlatırTextFragmentAbsorberaspose.pdf.text/textfragmentabsorber belgenin veya sayfanın tüm metin bölümlerinde arama yapan.
type: docs
weight: 10
url: /tr/net/aspose.pdf.text/textfragmentabsorber/textfragmentabsorber/
---
## TextFragmentAbsorber() {#constructor}

Yeni bir örneğini başlatır[`TextFragmentAbsorber`](../../textfragmentabsorber) belgenin veya sayfanın tüm metin bölümlerinde arama yapan.

```csharp
public TextFragmentAbsorber()
```

### Notlar

Metin araması yapar ve aracılığıyla arama sonuçlarına erişim sağlar.[`TextFragments`](../textfragments) Toplamak.

### Örnekler

Örnek, ilk PDF belgesi sayfasında metnin nasıl bulunacağını ve metnin nasıl değiştirileceğini gösterir.

```csharp
// Belgeyi aç
Document doc = new Document(@"D:\Tests\input.pdf");

// Belge metni yazı tipini değiştirmek için kullanılacak yazı tipini bulun
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// TextFragmentAbsorber nesnesi oluştur
TextFragmentAbsorber absorber = new TextFragmentAbsorber();

// Emicinin tüm "merhaba dünya" metin oluşumlarını aramasını sağlayın
absorber.Phrase = "hello world";

// İlk sayfa için emiciyi kabul et
doc.Pages[1].Accept(absorber);

// İlk metin oluşumunun metnini değiştir
absorber.TextFragments[1].Text = "hi world";

// Belgeyi kaydet
doc.Save(@"D:\Tests\output.pdf");  
```

### Ayrıca bakınız

* class [TextFragmentAbsorber](../../textfragmentabsorber)
* ad alanı [Aspose.Pdf.Text](../../textfragmentabsorber)
* toplantı [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(TextEditOptions) {#constructor_1}

Yeni bir örneğini başlatır[`TextFragmentAbsorber`](../../textfragmentabsorber)belgenin veya sayfanın tüm metin bölümlerinde arama yapan metin düzenleme seçenekleriyle.

```csharp
public TextFragmentAbsorber(TextEditOptions textEditOptions)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| textEditOptions | TextEditOptions | Metin düzenleme seçenekleri (Bazı düzenleme özelliklerini açmanıza izin verir). |

### Notlar

Metin araması yapar ve aracılığıyla arama sonuçlarına erişim sağlar.[`TextFragments`](../textfragments) Toplamak.

### Örnekler

Örnek, ilk PDF belgesi sayfasındaki tüm metin parçalarının nasıl bulunacağını ve onlar için yazı tipinin nasıl değiştirileceğini gösterir.

```csharp
// Belgeyi aç
Document doc = new Document(@"D:\Tests\input.pdf");

// TextFragmentAbsorber nesnesi oluştur
TextFragmentAbsorber absorber = new TextFragmentAbsorber(new TextEditOptions(TextEditOptions.FontReplace.RemoveUnusedFonts));

// İlk sayfa için emiciyi kabul et
doc.Pages[1].Accept(absorber);

// Courier yazı tipini bul
Pdf.Text.Font font = FontRepository.FindFont("Courier");

// Tüm metin parçaları için yazı tipini ayarla
foreach (TextFragment textFragment in absorber.TextFragments)
{
    textFragment.TextState.Font = font;
}

// Belgeyi kaydet
doc.Save(@"D:\Tests\output.pdf");
```

### Ayrıca bakınız

* class [TextEditOptions](../../texteditoptions)
* class [TextFragmentAbsorber](../../textfragmentabsorber)
* ad alanı [Aspose.Pdf.Text](../../textfragmentabsorber)
* toplantı [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string) {#constructor_2}

Yeni bir örneğini başlatır[`TextFragmentAbsorber`](../../textfragmentabsorber) belirtilen metin ifadesi için sınıf.

```csharp
public TextFragmentAbsorber(string phrase)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| phrase | String | olduğu ifade[`TextFragmentAbsorber`](../../textfragmentabsorber) aramalar |

### Notlar

Belirtilen ifadenin metin aramasını gerçekleştirir ve aracılığıyla arama sonuçlarına erişim sağlar.[`TextFragments`](../textfragments) koleksiyon.

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

* class [TextFragmentAbsorber](../../textfragmentabsorber)
* ad alanı [Aspose.Pdf.Text](../../textfragmentabsorber)
* toplantı [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex) {#constructor_6}

Yeni bir örneğini başlatır[`TextFragmentAbsorber`](../../textfragmentabsorber) belirtilen System.Text.RegularExpressions.Regex sınıf nesnesi için sınıf.

```csharp
public TextFragmentAbsorber(Regex regex)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| regex | Regex | System.Text.RegularExpressions.Regex sınıfı nesnesi,[`TextFragmentAbsorber`](../../textfragmentabsorber) aramalar |

### Notlar

Belirtilen ifadenin metin aramasını gerçekleştirir ve aracılığıyla arama sonuçlarına erişim sağlar.[`TextFragments`](../textfragments) koleksiyon.

### Örnekler

Örnek, ilk PDF belgesi sayfasındaki metnin nasıl bulunacağını ve metnin ve yazı tipinin nasıl değiştirileceğini gösterir.

```csharp
// Belgeyi aç
Document doc = new Document(@"D:\Tests\input.pdf");

// Belge metni yazı tipini değiştirmek için kullanılacak yazı tipini bulun
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Giriş normal ifadesinin tüm örneklerini bulmak için TextAbsorber nesnesi oluşturun
TextFragmentAbsorber absorber = new TextFragmentAbsorber(new System.Text.RegularExpressions.Regex(@"h\w*?o"));

// İlk sayfa için emiciyi kabul et
doc.Pages[1].Accept(absorber);

// "merhaba" kelimesini bulmalı ve "Merhaba" ile değiştirmeliyiz
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi";

// Belgeyi kaydet
doc.Save(@"D:\Tests\output.pdf");
```

### Ayrıca bakınız

* class [TextFragmentAbsorber](../../textfragmentabsorber)
* ad alanı [Aspose.Pdf.Text](../../textfragmentabsorber)
* toplantı [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextSearchOptions) {#constructor_4}

Yeni bir örneğini başlatır[`TextFragmentAbsorber`](../../textfragmentabsorber)belirtilen metin ifadesi ve metin arama seçenekleri için sınıf.

```csharp
public TextFragmentAbsorber(string phrase, TextSearchOptions textSearchOptions)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| phrase | String | olduğu ifade[`TextFragmentAbsorber`](../../textfragmentabsorber) aramalar |
| textSearchOptions | TextSearchOptions | Metin arama seçenekleri (Bazı arama özelliklerini açmanıza izin verir. Örneğin, normal ifadeyle arama yapın) |

### Notlar

Belirtilen ifadenin metin aramasını gerçekleştirir ve aracılığıyla arama sonuçlarına erişim sağlar.[`TextFragments`](../textfragments) koleksiyon.

### Örnekler

Örnek, ilk PDF belgesi sayfasında normal ifadeli metnin nasıl bulunacağını ve metnin nasıl değiştirileceğini gösterir.

```csharp
// Belgeyi aç
Document doc = new Document(@"D:\Tests\input.pdf");

// Normal ifade kullanarak 'h' ile başlayan ve 'o' ile biten tüm kelimeleri arayan TextFragmentAbsorber nesnesi oluşturun.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(@"h\w*?o", new TextSearchOptions(true));

// "merhaba" kelimesini bulmalı ve "Merhaba" ile değiştirmeliyiz
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi"; 
 
// Belgeyi kaydet
doc.Save(@"D:\Tests\output.pdf");  
```

### Ayrıca bakınız

* class [TextSearchOptions](../../textsearchoptions)
* class [TextFragmentAbsorber](../../textfragmentabsorber)
* ad alanı [Aspose.Pdf.Text](../../textfragmentabsorber)
* toplantı [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex, TextSearchOptions) {#constructor_8}

Yeni bir örneğini başlatır[`TextFragmentAbsorber`](../../textfragmentabsorber) belirtilen metin ifadesi ve metin arama seçenekleri için sınıf.

```csharp
public TextFragmentAbsorber(Regex regex, TextSearchOptions textSearchOptions)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| regex | Regex | System.Text.RegularExpressions.Regex sınıfı nesnesi,[`TextFragmentAbsorber`](../../textfragmentabsorber) aramalar |
| textSearchOptions | TextSearchOptions | Metin arama seçenekleri (Bazı arama özelliklerini açmanıza izin verir.) |

### Notlar

Belirtilen ifadenin metin aramasını gerçekleştirir ve aracılığıyla arama sonuçlarına erişim sağlar.[`TextFragments`](../textfragments) koleksiyon.

### Örnekler

Örnek, ilk PDF belgesi sayfasında normal ifadeli metnin nasıl bulunacağını ve metnin nasıl değiştirileceğini gösterir.

```csharp
// Belgeyi aç
Document doc = new Document(@"D:\Tests\input.pdf");

// Normal ifade kullanarak 'h' ile başlayan ve 'o' ile biten tüm kelimeleri arayan TextFragmentAbsorber nesnesi oluşturun.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(new System.Text.RegularExpressions.Regex(@"h\w*?o"), new TextSearchOptions(true));

// "merhaba" kelimesini bulmalı ve "Merhaba" ile değiştirmeliyiz
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi";

// Belgeyi kaydet
doc.Save(@"D:\Tests\output.pdf");
```

### Ayrıca bakınız

* class [TextSearchOptions](../../textsearchoptions)
* class [TextFragmentAbsorber](../../textfragmentabsorber)
* ad alanı [Aspose.Pdf.Text](../../textfragmentabsorber)
* toplantı [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextSearchOptions, TextEditOptions) {#constructor_5}

Yeni bir örneğini başlatır[`TextFragmentAbsorber`](../../textfragmentabsorber) belirtilen metin ifadesi için sınıf, metin arama seçenekleri ve metin düzenleme seçenekleri.

```csharp
public TextFragmentAbsorber(string phrase, TextSearchOptions textSearchOptions, 
    TextEditOptions textEditOptions)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| phrase | String | olduğu ifade[`TextFragmentAbsorber`](../../textfragmentabsorber) aramalar |
| textSearchOptions | TextSearchOptions | Metin arama seçenekleri (Bazı arama özelliklerini açmanıza izin verir. Örneğin, normal ifadeyle arama yapın) |
| textEditOptions | TextEditOptions | Metin düzenleme seçenekleri (Bazı düzenleme özelliklerini açmanıza izin verir). |

### Notlar

Belirtilen ifadenin metin aramasını gerçekleştirir ve aracılığıyla arama sonuçlarına erişim sağlar.[`TextFragments`](../textfragments) koleksiyon.

### Örnekler

Örnek, ilk PDF belgesi sayfasında normal ifadeli metnin nasıl bulunacağını ve metnin nasıl değiştirileceğini gösterir.

```csharp
// Belgeyi aç
Document doc = new Document(@"D:\Tests\input.pdf");

// Normal ifade kullanarak 'h' ile başlayan ve 'o' ile biten tüm kelimeleri arayan TextFragmentAbsorber nesnesi oluşturun.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(@"h\w*?o", new TextSearchOptions(true));

// "merhaba" kelimesini bulmalı ve "Merhaba" ile değiştirmeliyiz
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi"; 

// Belgeyi kaydet
doc.Save(@"D:\Tests\output.pdf");  
```

### Ayrıca bakınız

* class [TextSearchOptions](../../textsearchoptions)
* class [TextEditOptions](../../texteditoptions)
* class [TextFragmentAbsorber](../../textfragmentabsorber)
* ad alanı [Aspose.Pdf.Text](../../textfragmentabsorber)
* toplantı [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextEditOptions) {#constructor_3}

Yeni bir örneğini başlatır[`TextFragmentAbsorber`](../../textfragmentabsorber) belirtilen metin ifadesi ve metin düzenleme seçenekleri için sınıf.

```csharp
public TextFragmentAbsorber(string phrase, TextEditOptions textEditOptions)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| phrase | String | olduğu ifade[`TextFragmentAbsorber`](../../textfragmentabsorber) aramalar |
| textEditOptions | TextEditOptions | Metin düzenleme seçenekleri (Bazı düzenleme özelliklerini açmanıza izin verir). |

### Notlar

Belirtilen ifadenin metin aramasını gerçekleştirir ve aracılığıyla arama sonuçlarına erişim sağlar.[`TextFragments`](../textfragments) koleksiyon.

### Ayrıca bakınız

* class [TextEditOptions](../../texteditoptions)
* class [TextFragmentAbsorber](../../textfragmentabsorber)
* ad alanı [Aspose.Pdf.Text](../../textfragmentabsorber)
* toplantı [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex, TextEditOptions) {#constructor_7}

Yeni bir örneğini başlatır[`TextFragmentAbsorber`](../../textfragmentabsorber) belirtilen metin ifadesi ve metin düzenleme seçenekleri için sınıf.

```csharp
public TextFragmentAbsorber(Regex regex, TextEditOptions textEditOptions)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| regex | Regex | System.Text.RegularExpressions.Regex sınıfı nesnesi,[`TextFragmentAbsorber`](../../textfragmentabsorber) aramalar |
| textEditOptions | TextEditOptions | Metin düzenleme seçenekleri (Bazı düzenleme özelliklerini açmanıza izin verir). |

### Notlar

Belirtilen ifadenin metin aramasını gerçekleştirir ve aracılığıyla arama sonuçlarına erişim sağlar.[`TextFragments`](../textfragments) koleksiyon.

### Ayrıca bakınız

* class [TextEditOptions](../../texteditoptions)
* class [TextFragmentAbsorber](../../textfragmentabsorber)
* ad alanı [Aspose.Pdf.Text](../../textfragmentabsorber)
* toplantı [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
