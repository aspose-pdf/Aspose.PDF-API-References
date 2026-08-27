---
title: "FontRepository.OpenFont"
second_title: "Aspose.PDF för .NET API‑referens"
description: "FontRepository-metoden. Öppnar teckensnitt med angiven fontström."
type: docs
weight: 60
url: /sv/net/aspose.pdf.text/fontrepository/openfont/
---
## OpenFont(Stream, FontTypes) {#openfont}

Öppnar teckensnitt med angivet teckensnittström.

```csharp
public static Font OpenFont(Stream fontStream, FontTypes fontType)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontStream | Stream | Fontström. |
| fontType | FontTypes | Värde för fonttyp. |

### Returvärde

Teckensnittobjekt.

## Exempel

Exemplet visar hur man öppnar ett teckensnitt och ersätter teckensnittet för texten på den första sidan.

```csharp
// Öppna teckensnitt
using (FileStream fontStream = File.OpenRead(@"C:\WINDOWS\Fonts\arial.ttf"))
{
    Font font = FontRepository.OpenFont(fontStream, , FontTypes.TTF);

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
}
```

### Se även

* class [Font](../../font/)
* enum [FontTypes](../../fonttypes/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## OpenFont(string) {#openfont_1}

Öppnar teckensnitt med angiven sökväg till teckensnittsfilen.

```csharp
public static Font OpenFont(string fontFilePath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontFilePath | String | Sökväg till fontfil. |

### Returvärde

Teckensnittobjekt.

## Exempel

Exemplet visar hur man öppnar ett teckensnitt och ersätter teckensnittet för texten på den första sidan.

```csharp
// Öppna teckensnitt
Font font = FontRepository.OpenFont(@"C:\WINDOWS\Fonts\arial.ttf");

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

## OpenFont(string, string) {#openfont_2}

Öppnar teckensnitt med angiven sökväg till teckensnittsfilen och sökväg till metrikfilen.

```csharp
public static Font OpenFont(string fontFilePath, string metricsFilePath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontFilePath | String | Sökväg till fontfil. |
| metricsFilePath | String | Sökväg till fontmetrikfil. |

### Returvärde

Teckensnittobjekt.

## Exempel

Exemplet visar hur man öppnar Type1-teckensnitt med metrik och ersätter teckensnittet för texten på den första sidan.

```csharp
// Öppna teckensnitt
Font font = FontRepository.OpenFont("courier.pfb", "courier.afm");

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


