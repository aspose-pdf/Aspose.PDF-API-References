---
title: FindFont
second_title: Aspose.PDF for .NET API Referansı
description: Belirtilen yazı tipi adıyla yazı tipini arar ve döndürür.
type: docs
weight: 40
url: /tr/net/aspose.pdf.text/fontrepository/findfont/
---
## FindFont(string) {#findfont}

Belirtilen yazı tipi adıyla yazı tipini arar ve döndürür.

```csharp
public static Font FindFont(string fontName)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| fontName | String | Yazı tipi adı. |

### Geri dönüş değeri

Yazı tipi nesnesi.

### Örnekler

Örnek, yazı tipinin nasıl bulunacağını ve ilk sayfa metninin yazı tipinin nasıl değiştirileceğini gösterir.

```csharp
// Yazı tipini bul
Font font = FontRepository.FindFont("Arial");

// Belgeyi aç
Document doc = new Document(@"D:\Tests\input.pdf");

// Tüm "merhaba dünya" metin oluşumlarını bulmak için TextFragmentAbsorber nesnesi oluşturun
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// İlk sayfa için emiciyi kabul et
doc.Pages[1].Accept(absorber);

// İlk metin oluşumunun yazı tipini değiştir
absorber.TextFragments[1].TextState.Font = font;

// Belgeyi kaydet
doc.Save(@"D:\Tests\output.pdf"); 
```

### Ayrıca bakınız

* class [Font](../../font)
* class [FontRepository](../../fontrepository)
* ad alanı [Aspose.Pdf.Text](../../fontrepository)
* toplantı [Aspose.PDF](../../../)

---

## FindFont(string, bool) {#findfont_3}

Büyük/küçük harf duyarlılığını yok sayarak veya dikkate alarak belirtilen yazı tipi adıyla yazı tipini arar ve döndürür.

```csharp
public static Font FindFont(string fontName, bool ignoreCase)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| fontName | String | Yazı tipi adı. |
| ignoreCase | Boolean | büyük küçük harf duyarlılığı |

### Geri dönüş değeri

Yazı tipi nesnesi.

### Örnekler

Örnek, yazı tipinin nasıl bulunacağını ve ilk sayfa metninin yazı tipinin nasıl değiştirileceğini gösterir.

```csharp
// Yazı tipini bul
Font font = FontRepository.FindFont("Arial");

// Belgeyi aç
Document doc = new Document(@"D:\Tests\input.pdf");

// Tüm "merhaba dünya" metin oluşumlarını bulmak için TextFragmentAbsorber nesnesi oluşturun
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// İlk sayfa için emiciyi kabul et
doc.Pages[1].Accept(absorber);

// İlk metin oluşumunun yazı tipini değiştir
absorber.TextFragments[1].TextState.Font = font;

// Belgeyi kaydet
doc.Save(@"D:\Tests\output.pdf"); 
```

### Ayrıca bakınız

* class [Font](../../font)
* class [FontRepository](../../fontrepository)
* ad alanı [Aspose.Pdf.Text](../../fontrepository)
* toplantı [Aspose.PDF](../../../)

---

## FindFont(string, FontStyles) {#findfont_1}

Belirtilen yazı tipi adı ve yazı tipi stili ile yazı tipini arar ve döndürür.

```csharp
public static Font FindFont(string fontFamilyName, FontStyles stl)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| fontFamilyName | String | Yazı tipi ailesi adı. |
| stl | FontStyles | Yazı tipi stili değeri. |

### Geri dönüş değeri

Arama isteği parametrelerine karşılık gelen yazı tipi nesnesi.

### Örnekler

Örnek, yazı tipinin nasıl bulunacağını ve ilk sayfa metninin yazı tipinin nasıl değiştirileceğini gösterir.

```csharp
// Yazı tipini bul
Font font = FontRepository.FindFont("Arial", FontStyle.Italic);

// Belgeyi aç
Document doc = new Document(@"D:\Tests\input.pdf");

// Tüm "merhaba dünya" metin oluşumlarını bulmak için TextFragmentAbsorber nesnesi oluşturun
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// İlk sayfa için emiciyi kabul et
doc.Pages[1].Accept(absorber);

// İlk metin oluşumunun yazı tipini değiştir
absorber.TextFragments[1].TextState.Font = font;

// Belgeyi kaydet
doc.Save(@"D:\Tests\output.pdf"); 
```

### Ayrıca bakınız

* class [Font](../../font)
* enum [FontStyles](../../fontstyles)
* class [FontRepository](../../fontrepository)
* ad alanı [Aspose.Pdf.Text](../../fontrepository)
* toplantı [Aspose.PDF](../../../)

---

## FindFont(string, FontStyles, bool) {#findfont_2}

Belirtilen yazı tipi adı ve yazı tipi stiliyle yazı tipini arar ve döndürür büyük/küçük harf duyarlılığını yok sayar veya dikkate alır.

```csharp
public static Font FindFont(string fontFamilyName, FontStyles stl, bool ignoreCase)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| fontFamilyName | String | Yazı tipi ailesi adı. |
| stl | FontStyles | Yazı tipi stili değeri. |
| ignoreCase | Boolean | büyük küçük harf duyarlılığı |

### Geri dönüş değeri

Arama isteği parametrelerine karşılık gelen yazı tipi nesnesi.

### Örnekler

Örnek, yazı tipinin nasıl bulunacağını ve ilk sayfa metninin yazı tipinin nasıl değiştirileceğini gösterir.

```csharp
// Yazı tipini bul
Font font = FontRepository.FindFont("Arial", FontStyle.Italic);

// Belgeyi aç
Document doc = new Document(@"D:\Tests\input.pdf");

// Tüm "merhaba dünya" metin oluşumlarını bulmak için TextFragmentAbsorber nesnesi oluşturun
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// İlk sayfa için emiciyi kabul et
doc.Pages[1].Accept(absorber);

// İlk metin oluşumunun yazı tipini değiştir
absorber.TextFragments[1].TextState.Font = font;

// Belgeyi kaydet
doc.Save(@"D:\Tests\output.pdf"); 
```

### Ayrıca bakınız

* class [Font](../../font)
* enum [FontStyles](../../fontstyles)
* class [FontRepository](../../fontrepository)
* ad alanı [Aspose.Pdf.Text](../../fontrepository)
* toplantı [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
