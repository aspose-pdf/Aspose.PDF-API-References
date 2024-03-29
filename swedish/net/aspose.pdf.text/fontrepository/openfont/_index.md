---
title: OpenFont
second_title: Aspose.PDF för .NET API Referens
description: Öppnar teckensnitt med angiven teckensnittsström.
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
| fontStream | Stream | Fontström. |
| fontType | FontTypes | Typsnittsvärde. |

### Returvärde

Teckensnittsobjekt.

### Exempel

Exemplet visar hur man öppnar teckensnitt och ersätter teckensnitt för text på första sidan.

```csharp
// Öppna teckensnitt
using (FileStream fontStream = File.OpenRead(@"C:\WINDOWS\Fonts\arial.ttf"))
{
    Font font = FontRepository.OpenFont(fontStream, , FontTypes.TTF);

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
}
```

### Se även

* class [Font](../../font)
* enum [FontTypes](../../fonttypes)
* class [FontRepository](../../fontrepository)
* namnutrymme [Aspose.Pdf.Text](../../fontrepository)
* hopsättning [Aspose.PDF](../../../)

---

## OpenFont(string) {#openfont_1}

Öppnar teckensnitt med angiven sökväg för teckensnittsfil.

```csharp
public static Font OpenFont(string fontFilePath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontFilePath | String | Sökväg för teckensnittsfil. |

### Returvärde

Teckensnittsobjekt.

### Exempel

Exemplet visar hur man öppnar teckensnitt och ersätter teckensnitt för text på första sidan.

```csharp
// Öppna teckensnitt
Font font = FontRepository.OpenFont(@"C:\WINDOWS\Fonts\arial.ttf");

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

## OpenFont(string, string) {#openfont_2}

Öppnar teckensnitt med angiven teckensnittsfilsökväg och metrikfilsökväg.

```csharp
public static Font OpenFont(string fontFilePath, string metricsFilePath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontFilePath | String | Sökväg för teckensnittsfil. |
| metricsFilePath | String | Font metrics file patrh. |

### Returvärde

Teckensnittsobjekt.

### Exempel

Exemplet visar hur man öppnar typsnitt 1 med mätvärden och ersätter teckensnittet i texten på första sidan.

```csharp
// Öppna teckensnitt
Font font = FontRepository.OpenFont("courier.pfb", "courier.afm");

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

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
