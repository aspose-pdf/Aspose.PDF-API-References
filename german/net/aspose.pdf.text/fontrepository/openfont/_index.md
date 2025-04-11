---
title: FontRepository.OpenFont
second_title: Aspose.PDF for .NET API Reference
description: FontRepository-Methode. Öffnet Schriftart mit angegebenem Schriftstrom
type: docs
weight: 60
url: /de/net/aspose.pdf.text/fontrepository/openfont/
---
## OpenFont(Stream, FontTypes) {#openfont}

Öffnet Schriftart mit angegebenem Schriftstrom.

```csharp
public static Font OpenFont(Stream fontStream, FontTypes fontType)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontStream | Stream | Schriftstrom. |
| fontType | FontTypes | Schriftarttyp-Wert. |

### Rückgabewert

Schriftartobjekt.

## Beispiele

Das Beispiel zeigt, wie man eine Schriftart öffnet und die Schriftart des Textes der ersten Seite ersetzt.

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

### Siehe auch

* Klasse [Font](../../font/)
* Enum [FontTypes](../../fonttypes/)
* Klasse [FontRepository](../)
* Namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* Assembly [Aspose.PDF](../../../)

---

## OpenFont(string) {#openfont_1}

Öffnet Schriftart mit angegebenem Schriftdateipfad.

```csharp
public static Font OpenFont(string fontFilePath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontFilePath | String | Schriftdateipfad. |

### Rückgabewert

Schriftartobjekt.

## Beispiele

Das Beispiel zeigt, wie man eine Schriftart öffnet und die Schriftart des Textes der ersten Seite ersetzt.

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

### Siehe auch

* Klasse [Font](../../font/)
* Klasse [FontRepository](../)
* Namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* Assembly [Aspose.PDF](../../../)

---

## OpenFont(string, string) {#openfont_2}

Öffnet Schriftart mit angegebenem Schriftdateipfad und Metrikdateipfad.

```csharp
public static Font OpenFont(string fontFilePath, string metricsFilePath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontFilePath | String | Schriftdateipfad. |
| metricsFilePath | String | Schriftmetrikdateipfad. |

### Rückgabewert

Schriftartobjekt.

## Beispiele

Das Beispiel zeigt, wie man eine Type1-Schriftart mit Metriken öffnet und die Schriftart des Textes der ersten Seite ersetzt.

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

### Siehe auch

* Klasse [Font](../../font/)
* Klasse [FontRepository](../)
* Namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* Assembly [Aspose.PDF](../../../)