---
title: FontRepository.FindFont
second_title: Aspose.PDF for .NET API Reference
description: FontRepository-Methode. Sucht und gibt die Schriftart mit dem angegebenen Schriftartnamen zurück
type: docs
weight: 40
url: /de/net/aspose.pdf.text/fontrepository/findfont/
---
## FindFont(string) {#findfont}

Sucht und gibt die Schriftart mit dem angegebenen Schriftartnamen zurück.

```csharp
public static Font FindFont(string fontName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontName | String | Schriftartname. |

### Rückgabewert

Schriftartobjekt.

## Beispiele

Das Beispiel zeigt, wie man eine Schriftart findet und die Schriftart des Textes der ersten Seite ersetzt.

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

### Siehe auch

* Klasse [Font](../../font/)
* Klasse [FontRepository](../)
* Namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* Assembly [Aspose.PDF](../../../)

---

## FindFont(string, bool) {#findfont_3}

Sucht und gibt die Schriftart mit dem angegebenen Schriftartnamen zurück, wobei die Groß- und Kleinschreibung ignoriert oder beachtet wird.

```csharp
public static Font FindFont(string fontName, bool ignoreCase)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontName | String | Schriftartname. |
| ignoreCase | Boolean | Groß- und Kleinschreibung |

### Rückgabewert

Schriftartobjekt.

## Beispiele

Das Beispiel zeigt, wie man eine Schriftart findet und die Schriftart des Textes der ersten Seite ersetzt.

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

### Siehe auch

* Klasse [Font](../../font/)
* Klasse [FontRepository](../)
* Namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* Assembly [Aspose.PDF](../../../)

---

## FindFont(string, FontStyles) {#findfont_1}

Sucht und gibt die Schriftart mit dem angegebenen Schriftartnamen und Schriftstil zurück.

```csharp
public static Font FindFont(string fontFamilyName, FontStyles stl)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontFamilyName | String | Schriftfamilienname. |
| stl | FontStyles | Schriftstilwert. |

### Rückgabewert

Schriftartobjekt, das den Suchanfrageparametern entspricht.

## Beispiele

Das Beispiel zeigt, wie man eine Schriftart findet und die Schriftart des Textes der ersten Seite ersetzt.

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

### Siehe auch

* Klasse [Font](../../font/)
* Enum [FontStyles](../../fontstyles/)
* Klasse [FontRepository](../)
* Namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* Assembly [Aspose.PDF](../../../)

---

## FindFont(string, FontStyles, bool) {#findfont_2}

Sucht und gibt die Schriftart mit dem angegebenen Schriftartnamen und Schriftstil zurück, wobei die Groß- und Kleinschreibung ignoriert oder beachtet wird.

```csharp
public static Font FindFont(string fontFamilyName, FontStyles stl, bool ignoreCase)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontFamilyName | String | Schriftfamilienname. |
| stl | FontStyles | Schriftstilwert. |
| ignoreCase | Boolean | Groß- und Kleinschreibung |

### Rückgabewert

Schriftartobjekt, das den Suchanfrageparametern entspricht.

## Beispiele

Das Beispiel zeigt, wie man eine Schriftart findet und die Schriftart des Textes der ersten Seite ersetzt.

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

### Siehe auch

* Klasse [Font](../../font/)
* Enum [FontStyles](../../fontstyles/)
* Klasse [FontRepository](../)
* Namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* Assembly [Aspose.PDF](../../../)