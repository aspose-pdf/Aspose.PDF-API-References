---
title: FontRepository.FindFont
second_title: Aspose.PDF for .NET API Reference
description: FontRepository-metod. Söker och returnerar teckensnitt med angivet teckensnittsnamn
type: docs
weight: 40
url: /sv/net/aspose.pdf.text/fontrepository/findfont/
---
## FindFont(string) {#findfont}

Söker och returnerar teckensnitt med angivet teckensnittsnamn.

```csharp
public static Font FindFont(string fontName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontName | String | Teckensnittsnamn. |

### Returvärde

Teckensnittsobjekt.

## Exempel

Exemplet visar hur man hittar teckensnitt och ersätter teckensnittet för texten på första sidan.

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

### Se Även

* klass [Font](../../font/)
* klass [FontRepository](../)
* namnrymd [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## FindFont(string, bool) {#findfont_3}

Söker och returnerar teckensnitt med angivet teckensnittsnamn och ignorerar eller beaktar skiftlägeskänslighet.

```csharp
public static Font FindFont(string fontName, bool ignoreCase)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontName | String | Teckensnittsnamn. |
| ignoreCase | Boolean | skiftlägeskänslighet |

### Returvärde

Teckensnittsobjekt.

## Exempel

Exemplet visar hur man hittar teckensnitt och ersätter teckensnittet för texten på första sidan.

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

### Se Även

* klass [Font](../../font/)
* klass [FontRepository](../)
* namnrymd [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## FindFont(string, FontStyles) {#findfont_1}

Söker och returnerar teckensnitt med angivet teckensnittsnamn och teckensnittsstil.

```csharp
public static Font FindFont(string fontFamilyName, FontStyles stl)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontFamilyName | String | Teckensnittsfamiljens namn. |
| stl | FontStyles | Teckensnittsstilvärde. |

### Returvärde

Teckensnittsobjekt som motsvarar sökförfrågningsparametrarna.

## Exempel

Exemplet visar hur man hittar teckensnitt och ersätter teckensnittet för texten på första sidan.

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

### Se Även

* klass [Font](../../font/)
* enum [FontStyles](../../fontstyles/)
* klass [FontRepository](../)
* namnrymd [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## FindFont(string, FontStyles, bool) {#findfont_2}

Söker och returnerar teckensnitt med angivet teckensnittsnamn och teckensnittsstil och ignorerar eller beaktar skiftlägeskänslighet.

```csharp
public static Font FindFont(string fontFamilyName, FontStyles stl, bool ignoreCase)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontFamilyName | String | Teckensnittsfamiljens namn. |
| stl | FontStyles | Teckensnittsstilvärde. |
| ignoreCase | Boolean | skiftlägeskänslighet |

### Returvärde

Teckensnittsobjekt som motsvarar sökförfrågningsparametrarna.

## Exempel

Exemplet visar hur man hittar teckensnitt och ersätter teckensnittet för texten på första sidan.

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

### Se Även

* klass [Font](../../font/)
* enum [FontStyles](../../fontstyles/)
* klass [FontRepository](../)
* namnrymd [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)