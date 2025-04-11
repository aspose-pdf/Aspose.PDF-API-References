---
title: FontRepository.OpenFont
second_title: Aspose.PDF for .NET API Reference
description: FontRepository-metod. Öppnar teckensnitt med angiven teckensnittsström
type: docs
weight: 60
url: /sv/net/aspose.pdf.text/fontrepository/openfont/
---
## OpenFont(Stream, FontTypes) {#openfont}

Öppnar teckensnitt med angiven teckensnittsström.

```csharp
public static Font OpenFont(Stream fontStream, FontTypes fontType)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontStream | Stream | Teckensnittsström. |
| fontType | FontTypes | Värde för teckensnittstyp. |

### Returvärde

Teckensnittsobjekt.

## Exempel

Exemplet visar hur man öppnar teckensnitt och ersätter teckensnittet för texten på första sidan.

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

### Se Även

* klass [Font](../../font/)
* enum [FontTypes](../../fonttypes/)
* klass [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## OpenFont(string) {#openfont_1}

Öppnar teckensnitt med angiven teckensnittsfilväg.

```csharp
public static Font OpenFont(string fontFilePath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontFilePath | String | Teckensnittsfilväg. |

### Returvärde

Teckensnittsobjekt.

## Exempel

Exemplet visar hur man öppnar teckensnitt och ersätter teckensnittet för texten på första sidan.

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

### Se Även

* klass [Font](../../font/)
* klass [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## OpenFont(string, string) {#openfont_2}

Öppnar teckensnitt med angiven teckensnittsfilväg och metrikfilväg.

```csharp
public static Font OpenFont(string fontFilePath, string metricsFilePath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontFilePath | String | Teckensnittsfilväg. |
| metricsFilePath | String | Teckensnittsmetrikfilväg. |

### Returvärde

Teckensnittsobjekt.

## Exempel

Exemplet visar hur man öppnar Type1-teckensnitt med metrik och ersätter teckensnittet för texten på första sidan.

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

### Se Även

* klass [Font](../../font/)
* klass [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)