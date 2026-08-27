---
title: "FontRepository.FindFont"
second_title: "Aspose.PDF för .NET API‑referens"
description: "FontRepository metod. Söker och returnerar teckensnitt med angivet teckensnittsnamn"
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

Teckensnittobjekt.

## Exempel

Exemplet visar hur man hittar ett teckensnitt och ersätter teckensnittet i texten på den första sidan.

```csharp
// Hitta teckensnitt
Font font = FontRepository.FindFont("Arial");

// Öppna dokument
Document doc = new Document(@"D:\Tests\input.pdf");

// Skapa ett TextFragmentAbsorber‑objekt för att hitta alla förekomster av texten \"hello world\"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Acceptera absorberaren för första sidan
doc.Pages[1].Accept(absorber);

// Ändra teckensnitt för den första textförekomsten
absorber.TextFragments[1].TextState.Font = font;

// Spara dokument
doc.Save(@"D:\Tests\output.pdf"); 
```

### Se även

* class [Font](../../font/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## FindFont(string, bool) {#findfont_3}

Söker och returnerar teckensnitt med angivet teckensnittsnamn, med eller utan hänsyn till skiftlägeskänslighet.

```csharp
public static Font FindFont(string fontName, bool ignoreCase)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontName | String | Teckensnittsnamn. |
| ignoreCase | Boolean | skiftlägeskänslighet |

### Returvärde

Teckensnittobjekt.

## Exempel

Exemplet visar hur man hittar ett teckensnitt och ersätter teckensnittet i texten på den första sidan.

```csharp
// Hitta teckensnitt
Font font = FontRepository.FindFont("Arial");

// Öppna dokument
Document doc = new Document(@"D:\Tests\input.pdf");

// Skapa ett TextFragmentAbsorber‑objekt för att hitta alla förekomster av texten \"hello world\"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Acceptera absorberaren för första sidan
doc.Pages[1].Accept(absorber);

// Ändra teckensnitt för den första textförekomsten
absorber.TextFragments[1].TextState.Font = font;

// Spara dokument
doc.Save(@"D:\Tests\output.pdf"); 
```

### Se även

* class [Font](../../font/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
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
| stl | FontStyles | Teckensnittsstilsvärde. |

### Returvärde

Teckensnittobjekt som motsvarar sökförfrågningsparametrar.

## Exempel

Exemplet visar hur man hittar ett teckensnitt och ersätter teckensnittet i texten på den första sidan.

```csharp
// Hitta teckensnitt
Font font = FontRepository.FindFont("Arial", FontStyle.Italic);

// Öppna dokument
Document doc = new Document(@"D:\Tests\input.pdf");

// Skapa TextFragmentAbsorber-objekt för att hitta alla "hello world"-textförekomster
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Acceptera absorberaren för första sidan
doc.Pages[1].Accept(absorber);

// Ändra teckensnitt för den första textförekomsten
absorber.TextFragments[1].TextState.Font = font;

// Spara dokument
doc.Save(@"D:\Tests\output.pdf"); 
```

### Se även

* class [Font](../../font/)
* enum [FontStyles](../../fontstyles/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## FindFont(string, FontStyles, bool) {#findfont_2}

Söker och returnerar teckensnitt med angivet teckensnittsnamn och teckensnittsstil, med eller utan hänsyn till skiftlägeskänslighet.

```csharp
public static Font FindFont(string fontFamilyName, FontStyles stl, bool ignoreCase)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontFamilyName | String | Teckensnittsfamiljens namn. |
| stl | FontStyles | Teckensnittsstilsvärde. |
| ignoreCase | Boolean | skiftlägeskänslighet |

### Returvärde

Teckensnittobjekt som motsvarar sökförfrågningsparametrar.

## Exempel

Exemplet visar hur man hittar ett teckensnitt och ersätter teckensnittet i texten på den första sidan.

```csharp
// Hitta teckensnitt
Font font = FontRepository.FindFont("Arial", FontStyle.Italic);

// Öppna dokument
Document doc = new Document(@"D:\Tests\input.pdf");

// Skapa TextFragmentAbsorber-objekt för att hitta alla "hello world"-textförekomster
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Acceptera absorberaren för första sidan
doc.Pages[1].Accept(absorber);

// Ändra teckensnitt för den första textförekomsten
absorber.TextFragments[1].TextState.Font = font;

// Spara dokument
doc.Save(@"D:\Tests\output.pdf"); 
```

### Se även

* class [Font](../../font/)
* enum [FontStyles](../../fontstyles/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


