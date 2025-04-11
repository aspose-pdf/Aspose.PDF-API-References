---
title: FontRepository.FindFont
second_title: Aspose.PDF for .NET API Reference
description: FontRepository metodu. Belirtilen font adıyla font arar ve döndürür
type: docs
weight: 40
url: /tr/net/aspose.pdf.text/fontrepository/findfont/
---
## FindFont(string) {#findfont}

Belirtilen font adıyla font arar ve döndürür.

```csharp
public static Font FindFont(string fontName)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontName | String | Font adı. |

### Dönüş Değeri

Font nesnesi.

## Örnekler

Örnek, font bulmayı ve ilk sayfadaki metnin fontunu değiştirmeyi gösterir.

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

* sınıf [Font](../../font/)
* sınıf [FontRepository](../)
* ad alanı [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* derleme [Aspose.PDF](../../../)

---

## FindFont(string, bool) {#findfont_3}

Belirtilen font adıyla font arar ve büyük/küçük harf duyarlılığını göz ardı eder veya dikkate alır.

```csharp
public static Font FindFont(string fontName, bool ignoreCase)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontName | String | Font adı. |
| ignoreCase | Boolean | büyük/küçük harf duyarlılığı |

### Dönüş Değeri

Font nesnesi.

## Örnekler

Örnek, font bulmayı ve ilk sayfadaki metnin fontunu değiştirmeyi gösterir.

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

* sınıf [Font](../../font/)
* sınıf [FontRepository](../)
* ad alanı [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* derleme [Aspose.PDF](../../../)

---

## FindFont(string, FontStyles) {#findfont_1}

Belirtilen font adı ve font stiliyle font arar ve döndürür.

```csharp
public static Font FindFont(string fontFamilyName, FontStyles stl)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontFamilyName | String | Font aile adı. |
| stl | FontStyles | Font stil değeri. |

### Dönüş Değeri

Arama isteği parametrelerine karşılık gelen font nesnesi.

## Örnekler

Örnek, font bulmayı ve ilk sayfadaki metnin fontunu değiştirmeyi gösterir.

```csharp
// Find font
Font font = FontRepository.FindFont("Arial", FontStyle.Italic);

// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change font of the first text occurence
absorber.TextFragments[1].TextState.Font = font;

// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### Ayrıca Bakınız

* sınıf [Font](../../font/)
* enum [FontStyles](../../fontstyles/)
* sınıf [FontRepository](../)
* ad alanı [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* derleme [Aspose.PDF](../../../)

---

## FindFont(string, FontStyles, bool) {#findfont_2}

Belirtilen font adı ve font stiliyle font arar ve büyük/küçük harf duyarlılığını göz ardı eder veya dikkate alır.

```csharp
public static Font FindFont(string fontFamilyName, FontStyles stl, bool ignoreCase)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontFamilyName | String | Font aile adı. |
| stl | FontStyles | Font stil değeri. |
| ignoreCase | Boolean | büyük/küçük harf duyarlılığı |

### Dönüş Değeri

Arama isteği parametrelerine karşılık gelen font nesnesi.

## Örnekler

Örnek, font bulmayı ve ilk sayfadaki metnin fontunu değiştirmeyi gösterir.

```csharp
// Find font
Font font = FontRepository.FindFont("Arial", FontStyle.Italic);

// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change font of the first text occurence
absorber.TextFragments[1].TextState.Font = font;

// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### Ayrıca Bakınız

* sınıf [Font](../../font/)
* enum [FontStyles](../../fontstyles/)
* sınıf [FontRepository](../)
* ad alanı [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* derleme [Aspose.PDF](../../../)