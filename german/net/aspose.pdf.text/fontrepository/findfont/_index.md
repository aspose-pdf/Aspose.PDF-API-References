---
title: FindFont
second_title: Aspose.PDF für .NET-API-Referenz
description: Sucht und gibt die Schriftart mit dem angegebenen Schriftartnamen zurück.
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
| fontName | String | Schriftartenname. |

### Rückgabewert

Font-Objekt.

### Beispiele

Das Beispiel zeigt, wie man eine Schriftart findet und die Schriftart des Textes der ersten Seite ersetzt.

```csharp
// Schriftart suchen
Font font = FontRepository.FindFont("Arial");

// Dokument öffnen
Document doc = new Document(@"D:\Tests\input.pdf");

// TextFragmentAbsorber-Objekt erstellen, um alle "Hello World"-Textvorkommen zu finden
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Akzeptiere den Absorber für die erste Seite
doc.Pages[1].Accept(absorber);

// Schriftart des ersten Textvorkommens ändern
absorber.TextFragments[1].TextState.Font = font;

// Dokument speichern
doc.Save(@"D:\Tests\output.pdf"); 
```

### Siehe auch

* class [Font](../../font)
* class [FontRepository](../../fontrepository)
* namensraum [Aspose.Pdf.Text](../../fontrepository)
* Montage [Aspose.PDF](../../../)

---

## FindFont(string, bool) {#findfont_3}

Sucht und gibt die Schriftart mit dem angegebenen Schriftartnamen zurück, wobei die Groß-/Kleinschreibung ignoriert oder beachtet wird.

```csharp
public static Font FindFont(string fontName, bool ignoreCase)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontName | String | Schriftartenname. |
| ignoreCase | Boolean | Groß- und Kleinschreibung |

### Rückgabewert

Font-Objekt.

### Beispiele

Das Beispiel zeigt, wie man eine Schriftart findet und die Schriftart des Textes der ersten Seite ersetzt.

```csharp
// Schriftart suchen
Font font = FontRepository.FindFont("Arial");

// Dokument öffnen
Document doc = new Document(@"D:\Tests\input.pdf");

// TextFragmentAbsorber-Objekt erstellen, um alle "Hello World"-Textvorkommen zu finden
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Akzeptiere den Absorber für die erste Seite
doc.Pages[1].Accept(absorber);

// Schriftart des ersten Textvorkommens ändern
absorber.TextFragments[1].TextState.Font = font;

// Dokument speichern
doc.Save(@"D:\Tests\output.pdf"); 
```

### Siehe auch

* class [Font](../../font)
* class [FontRepository](../../fontrepository)
* namensraum [Aspose.Pdf.Text](../../fontrepository)
* Montage [Aspose.PDF](../../../)

---

## FindFont(string, FontStyles) {#findfont_1}

Sucht und gibt die Schriftart mit dem angegebenen Schriftartnamen und Schriftartstil zurück.

```csharp
public static Font FindFont(string fontFamilyName, FontStyles stl)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontFamilyName | String | Name der Schriftfamilie. |
| stl | FontStyles | Schriftstilwert. |

### Rückgabewert

Schriftartobjekt, das Suchanforderungsparametern entspricht.

### Beispiele

Das Beispiel zeigt, wie man eine Schriftart findet und die Schriftart des Textes der ersten Seite ersetzt.

```csharp
// Schriftart suchen
Font font = FontRepository.FindFont("Arial", FontStyle.Italic);

// Dokument öffnen
Document doc = new Document(@"D:\Tests\input.pdf");

// TextFragmentAbsorber-Objekt erstellen, um alle "Hello World"-Textvorkommen zu finden
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Akzeptiere den Absorber für die erste Seite
doc.Pages[1].Accept(absorber);

// Schriftart des ersten Textvorkommens ändern
absorber.TextFragments[1].TextState.Font = font;

// Dokument speichern
doc.Save(@"D:\Tests\output.pdf"); 
```

### Siehe auch

* class [Font](../../font)
* enum [FontStyles](../../fontstyles)
* class [FontRepository](../../fontrepository)
* namensraum [Aspose.Pdf.Text](../../fontrepository)
* Montage [Aspose.PDF](../../../)

---

## FindFont(string, FontStyles, bool) {#findfont_2}

Sucht und gibt die Schriftart mit dem angegebenen Schriftartnamen und Schriftartstil zurück, wobei die Groß-/Kleinschreibung ignoriert oder beachtet wird.

```csharp
public static Font FindFont(string fontFamilyName, FontStyles stl, bool ignoreCase)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontFamilyName | String | Name der Schriftfamilie. |
| stl | FontStyles | Schriftstilwert. |
| ignoreCase | Boolean | Groß- und Kleinschreibung |

### Rückgabewert

Schriftartobjekt, das Suchanforderungsparametern entspricht.

### Beispiele

Das Beispiel zeigt, wie man eine Schriftart findet und die Schriftart des Textes der ersten Seite ersetzt.

```csharp
// Schriftart suchen
Font font = FontRepository.FindFont("Arial", FontStyle.Italic);

// Dokument öffnen
Document doc = new Document(@"D:\Tests\input.pdf");

// TextFragmentAbsorber-Objekt erstellen, um alle "Hello World"-Textvorkommen zu finden
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Akzeptiere den Absorber für die erste Seite
doc.Pages[1].Accept(absorber);

// Schriftart des ersten Textvorkommens ändern
absorber.TextFragments[1].TextState.Font = font;

// Dokument speichern
doc.Save(@"D:\Tests\output.pdf"); 
```

### Siehe auch

* class [Font](../../font)
* enum [FontStyles](../../fontstyles)
* class [FontRepository](../../fontrepository)
* namensraum [Aspose.Pdf.Text](../../fontrepository)
* Montage [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
