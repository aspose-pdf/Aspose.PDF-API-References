---
title: FontRepository.OpenFont
second_title: Aspose.PDF for .NET API Reference
description: FontRepository metodu. Belirtilen font akışı ile font açar
type: docs
weight: 60
url: /tr/net/aspose.pdf.text/fontrepository/openfont/
---
## OpenFont(Stream, FontTypes) {#openfont}

Belirtilen font akışı ile font açar.

```csharp
public static Font OpenFont(Stream fontStream, FontTypes fontType)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontStream | Stream | Font akışı. |
| fontType | FontTypes | Font türü değeri. |

### Dönüş Değeri

Font nesnesi.

## Örnekler

Örnek, fontun nasıl açılacağını ve ilk sayfadaki metnin fontunun nasıl değiştirileceğini gösterir.

```csharp
// Open font
using (FileStream fontStream = File.OpenRead(@"C:\WINDOWS\Fonts\arial.ttf"))
{
    Font font = FontRepository.OpenFont(fontStream, , FontTypes.TTF);

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
}
```

### Ayrıca Bakınız

* class [Font](../../font/)
* enum [FontTypes](../../fonttypes/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## OpenFont(string) {#openfont_1}

Belirtilen font dosyası yolu ile font açar.

```csharp
public static Font OpenFont(string fontFilePath)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontFilePath | String | Font dosyası yolu. |

### Dönüş Değeri

Font nesnesi.

## Örnekler

Örnek, fontun nasıl açılacağını ve ilk sayfadaki metnin fontunun nasıl değiştirileceğini gösterir.

```csharp
// Open font
Font font = FontRepository.OpenFont(@"C:\WINDOWS\Fonts\arial.ttf");

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

* class [Font](../../font/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## OpenFont(string, string) {#openfont_2}

Belirtilen font dosyası yolu ve metrik dosyası yolu ile font açar.

```csharp
public static Font OpenFont(string fontFilePath, string metricsFilePath)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontFilePath | String | Font dosyası yolu. |
| metricsFilePath | String | Font metrik dosyası yolu. |

### Dönüş Değeri

Font nesnesi.

## Örnekler

Örnek, metriklerle Type1 fontunun nasıl açılacağını ve ilk sayfadaki metnin fontunun nasıl değiştirileceğini gösterir.

```csharp
// Open font
Font font = FontRepository.OpenFont("courier.pfb", "courier.afm");

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

* class [Font](../../font/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)