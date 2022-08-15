---
title: FindFont
second_title: Aspose.PDF för .NET API Referens
description: Söker och returnerar teckensnitt med angivet teckensnittsnamn.
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

### Exempel

Exemplet visar hur man hittar teckensnitt och ersätter teckensnittet i texten på första sidan.

```csharp
// Hitta teckensnitt
Font font = FontRepository.FindFont("Arial");

// Öppna dokument
Document doc = new Document(@"D:\Tests\input.pdf");

// Skapa TextFragmentAbsorber-objekt för att hitta alla "hej världen" textförekomster
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Acceptera absorbenten för första sidan
doc.Pages[1].Accept(absorber);

// Ändra teckensnitt för den första textförekomsten
absorber.TextFragments[1].TextState.Font = font;

// Spara dokument
doc.Save(@"D:\Tests\output.pdf"); 
```

### Se även

* class [Font](../../font)
* class [FontRepository](../../fontrepository)
* namnutrymme [Aspose.Pdf.Text](../../fontrepository)
* hopsättning [Aspose.PDF](../../../)

---

## FindFont(string, bool) {#findfont_3}

Söker efter och returnerar teckensnitt med angivet teckensnittsnamn och ignorerar eller respekterar skiftlägeskänslighet.

```csharp
public static Font FindFont(string fontName, bool ignoreCase)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontName | String | Teckensnittsnamn. |
| ignoreCase | Boolean | skiftlägeskänslighet |

### Returvärde

Teckensnittsobjekt.

### Exempel

Exemplet visar hur man hittar teckensnitt och ersätter teckensnittet i texten på första sidan.

```csharp
// Hitta teckensnitt
Font font = FontRepository.FindFont("Arial");

// Öppna dokument
Document doc = new Document(@"D:\Tests\input.pdf");

// Skapa TextFragmentAbsorber-objekt för att hitta alla "hej världen" textförekomster
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Acceptera absorbenten för första sidan
doc.Pages[1].Accept(absorber);

// Ändra teckensnitt för den första textförekomsten
absorber.TextFragments[1].TextState.Font = font;

// Spara dokument
doc.Save(@"D:\Tests\output.pdf"); 
```

### Se även

* class [Font](../../font)
* class [FontRepository](../../fontrepository)
* namnutrymme [Aspose.Pdf.Text](../../fontrepository)
* hopsättning [Aspose.PDF](../../../)

---

## FindFont(string, FontStyles) {#findfont_1}

Söker och returnerar teckensnitt med angivet teckensnittsnamn och teckensnittsstil.

```csharp
public static Font FindFont(string fontFamilyName, FontStyles stl)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontFamilyName | String | Teckensnittets efternamn. |
| stl | FontStyles | Typsnittsstilsvärde. |

### Returvärde

Teckensnittsobjekt som motsvarar sökbegäransparametrar.

### Exempel

Exemplet visar hur man hittar teckensnitt och ersätter teckensnittet i texten på första sidan.

```csharp
// Hitta teckensnitt
Font font = FontRepository.FindFont("Arial", FontStyle.Italic);

// Öppna dokument
Document doc = new Document(@"D:\Tests\input.pdf");

// Skapa TextFragmentAbsorber-objekt för att hitta alla "hej världen" textförekomster
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Acceptera absorbenten för första sidan
doc.Pages[1].Accept(absorber);

// Ändra teckensnitt för den första textförekomsten
absorber.TextFragments[1].TextState.Font = font;

// Spara dokument
doc.Save(@"D:\Tests\output.pdf"); 
```

### Se även

* class [Font](../../font)
* enum [FontStyles](../../fontstyles)
* class [FontRepository](../../fontrepository)
* namnutrymme [Aspose.Pdf.Text](../../fontrepository)
* hopsättning [Aspose.PDF](../../../)

---

## FindFont(string, FontStyles, bool) {#findfont_2}

Söker och returnerar teckensnitt med specificerat teckensnittsnamn och teckensnittsstil ignorerar eller respekterar skiftlägeskänslighet.

```csharp
public static Font FindFont(string fontFamilyName, FontStyles stl, bool ignoreCase)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontFamilyName | String | Teckensnittets efternamn. |
| stl | FontStyles | Typsnittsstilsvärde. |
| ignoreCase | Boolean | skiftlägeskänslighet |

### Returvärde

Teckensnittsobjekt som motsvarar sökbegäransparametrar.

### Exempel

Exemplet visar hur man hittar teckensnitt och ersätter teckensnittet i texten på första sidan.

```csharp
// Hitta teckensnitt
Font font = FontRepository.FindFont("Arial", FontStyle.Italic);

// Öppna dokument
Document doc = new Document(@"D:\Tests\input.pdf");

// Skapa TextFragmentAbsorber-objekt för att hitta alla "hej världen" textförekomster
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Acceptera absorbenten för första sidan
doc.Pages[1].Accept(absorber);

// Ändra teckensnitt för den första textförekomsten
absorber.TextFragments[1].TextState.Font = font;

// Spara dokument
doc.Save(@"D:\Tests\output.pdf"); 
```

### Se även

* class [Font](../../font)
* enum [FontStyles](../../fontstyles)
* class [FontRepository](../../fontrepository)
* namnutrymme [Aspose.Pdf.Text](../../fontrepository)
* hopsättning [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
