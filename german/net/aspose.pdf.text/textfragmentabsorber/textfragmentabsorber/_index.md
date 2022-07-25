---
title: TextFragmentAbsorber
second_title: Aspose.PDF für .NET-API-Referenz
description: Initialisiert eine neue Instanz vonTextFragmentAbsorberaspose.pdf.text/textfragmentabsorber die eine Suche nach allen Textsegmenten des Dokuments oder der Seite durchführt.
type: docs
weight: 10
url: /de/net/aspose.pdf.text/textfragmentabsorber/textfragmentabsorber/
---
## TextFragmentAbsorber() {#constructor}

Initialisiert eine neue Instanz von[`TextFragmentAbsorber`](../../textfragmentabsorber) die eine Suche nach allen Textsegmenten des Dokuments oder der Seite durchführt.

```csharp
public TextFragmentAbsorber()
```

### Bemerkungen

Führt eine Textsuche durch und bietet Zugriff auf Suchergebnisse über[`TextFragments`](../textfragments) Sammlung.

### Beispiele

Das Beispiel zeigt, wie Sie Text auf der ersten PDF-Dokumentseite finden und den Text ersetzen.

```csharp
// Dokument öffnen
Document doc = new Document(@"D:\Tests\input.pdf");

// Schriftart finden, die verwendet wird, um die Schriftart des Dokumenttexts zu ändern
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// TextFragmentAbsorber-Objekt erstellen
TextFragmentAbsorber absorber = new TextFragmentAbsorber();

// Lassen Sie den Absorber alle "Hello World"-Textvorkommen durchsuchen
absorber.Phrase = "hello world";

// Akzeptiere den Absorber für die erste Seite
doc.Pages[1].Accept(absorber);

// Text des ersten Textvorkommens ändern
absorber.TextFragments[1].Text = "hi world";

// Dokument speichern
doc.Save(@"D:\Tests\output.pdf");  
```

### Siehe auch

* class [TextFragmentAbsorber](../../textfragmentabsorber)
* namensraum [Aspose.Pdf.Text](../../textfragmentabsorber)
* Montage [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(TextEditOptions) {#constructor_1}

Initialisiert eine neue Instanz von[`TextFragmentAbsorber`](../../textfragmentabsorber)mit Textbearbeitungsoptionen, die eine Suche nach allen Textsegmenten des Dokuments oder der Seite durchführt.

```csharp
public TextFragmentAbsorber(TextEditOptions textEditOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| textEditOptions | TextEditOptions | Textbearbeitungsoptionen (Ermöglicht das Aktivieren einiger Bearbeitungsfunktionen). |

### Bemerkungen

Führt eine Textsuche durch und bietet Zugriff auf Suchergebnisse über[`TextFragments`](../textfragments) Sammlung.

### Beispiele

Das Beispiel zeigt, wie alle Textfragmente auf der ersten PDF-Dokumentseite gefunden und die Schriftart für sie ersetzt werden.

```csharp
// Dokument öffnen
Document doc = new Document(@"D:\Tests\input.pdf");

// TextFragmentAbsorber-Objekt erstellen
TextFragmentAbsorber absorber = new TextFragmentAbsorber(new TextEditOptions(TextEditOptions.FontReplace.RemoveUnusedFonts));

// Akzeptiere den Absorber für die erste Seite
doc.Pages[1].Accept(absorber);

// Courier-Schriftart finden
Pdf.Text.Font font = FontRepository.FindFont("Courier");

// Legen Sie die Schriftart für alle Textfragmente fest
foreach (TextFragment textFragment in absorber.TextFragments)
{
    textFragment.TextState.Font = font;
}

// Dokument speichern
doc.Save(@"D:\Tests\output.pdf");
```

### Siehe auch

* class [TextEditOptions](../../texteditoptions)
* class [TextFragmentAbsorber](../../textfragmentabsorber)
* namensraum [Aspose.Pdf.Text](../../textfragmentabsorber)
* Montage [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string) {#constructor_2}

Initialisiert eine neue Instanz von[`TextFragmentAbsorber`](../../textfragmentabsorber) Klasse für die angegebene Textphrase.

```csharp
public TextFragmentAbsorber(string phrase)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| phrase | String | Satz, dass die[`TextFragmentAbsorber`](../../textfragmentabsorber) sucht |

### Bemerkungen

Führt eine Textsuche nach dem angegebenen Ausdruck durch und bietet Zugriff auf Suchergebnisse über[`TextFragments`](../textfragments) Sammlung.

### Beispiele

Das Beispiel zeigt, wie Sie Text auf der ersten PDF-Dokumentseite finden und den Text und seine Schriftart ersetzen.

```csharp
// Dokument öffnen
Document doc = new Document(@"D:\Tests\input.pdf");

// Schriftart finden, die verwendet wird, um die Schriftart des Dokumenttexts zu ändern
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// TextFragmentAbsorber-Objekt erstellen, um alle "Hello World"-Textvorkommen zu finden
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Akzeptiere den Absorber für die erste Seite
doc.Pages[1].Accept(absorber);

// Text und Schriftart des ersten Textvorkommens ändern
absorber.TextFragments[1].Text = "hi world";
absorber.TextFragments[1].TextState.Font = font;

// Dokument speichern
doc.Save(@"D:\Tests\output.pdf");  
```

### Siehe auch

* class [TextFragmentAbsorber](../../textfragmentabsorber)
* namensraum [Aspose.Pdf.Text](../../textfragmentabsorber)
* Montage [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex) {#constructor_6}

Initialisiert eine neue Instanz von[`TextFragmentAbsorber`](../../textfragmentabsorber) Klasse für das angegebene System.Text.RegularExpressions.Regex-Klassenobjekt.

```csharp
public TextFragmentAbsorber(Regex regex)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| regex | Regex | System.Text.RegularExpressions.Regex-Klassenobjekt, das die[`TextFragmentAbsorber`](../../textfragmentabsorber) sucht |

### Bemerkungen

Führt eine Textsuche nach dem angegebenen Ausdruck durch und bietet Zugriff auf Suchergebnisse über[`TextFragments`](../textfragments) Sammlung.

### Beispiele

Das Beispiel zeigt, wie Sie Text auf der ersten PDF-Dokumentseite finden und den Text und seine Schriftart ersetzen.

```csharp
// Dokument öffnen
Document doc = new Document(@"D:\Tests\input.pdf");

// Schriftart finden, die verwendet wird, um die Schriftart des Dokumenttexts zu ändern
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// TextAbsorber-Objekt erstellen, um alle Instanzen der Eingabe-Regex zu finden
TextFragmentAbsorber absorber = new TextFragmentAbsorber(new System.Text.RegularExpressions.Regex(@"h\w*?o"));

// Akzeptiere den Absorber für die erste Seite
doc.Pages[1].Accept(absorber);

// Wir sollten das Wort "Hallo" finden und es durch "Hi" ersetzen
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi";

// Dokument speichern
doc.Save(@"D:\Tests\output.pdf");
```

### Siehe auch

* class [TextFragmentAbsorber](../../textfragmentabsorber)
* namensraum [Aspose.Pdf.Text](../../textfragmentabsorber)
* Montage [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextSearchOptions) {#constructor_4}

Initialisiert eine neue Instanz von[`TextFragmentAbsorber`](../../textfragmentabsorber)Klasse für die angegebenen Textphrasen und Textsuchoptionen.

```csharp
public TextFragmentAbsorber(string phrase, TextSearchOptions textSearchOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| phrase | String | Satz, dass die[`TextFragmentAbsorber`](../../textfragmentabsorber) sucht |
| textSearchOptions | TextSearchOptions | Textsuchoptionen (Ermöglicht das Aktivieren einiger Suchfunktionen. Zum Beispiel Suche mit regulären Ausdrücken) |

### Bemerkungen

Führt eine Textsuche nach dem angegebenen Ausdruck durch und bietet Zugriff auf Suchergebnisse über[`TextFragments`](../textfragments) Sammlung.

### Beispiele

Das Beispiel zeigt, wie man Text mit regulären Ausdrücken auf der ersten PDF-Dokumentseite findet und den Text ersetzt.

```csharp
// Dokument öffnen
Document doc = new Document(@"D:\Tests\input.pdf");

// TextFragmentAbsorber-Objekt erstellen, das alle Wörter sucht, die mit „h“ beginnen und mit „o“ enden, indem ein regulärer Ausdruck verwendet wird.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(@"h\w*?o", new TextSearchOptions(true));

// Wir sollten das Wort "Hallo" finden und es durch "Hi" ersetzen
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi"; 
 
// Dokument speichern
doc.Save(@"D:\Tests\output.pdf");  
```

### Siehe auch

* class [TextSearchOptions](../../textsearchoptions)
* class [TextFragmentAbsorber](../../textfragmentabsorber)
* namensraum [Aspose.Pdf.Text](../../textfragmentabsorber)
* Montage [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex, TextSearchOptions) {#constructor_8}

Initialisiert eine neue Instanz von[`TextFragmentAbsorber`](../../textfragmentabsorber) Klasse für die angegebenen Textphrasen und Textsuchoptionen.

```csharp
public TextFragmentAbsorber(Regex regex, TextSearchOptions textSearchOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| regex | Regex | System.Text.RegularExpressions.Regex-Klassenobjekt, das die[`TextFragmentAbsorber`](../../textfragmentabsorber) sucht |
| textSearchOptions | TextSearchOptions | Textsuchoptionen (Ermöglicht das Aktivieren einiger Suchfunktionen.) |

### Bemerkungen

Führt eine Textsuche nach dem angegebenen Ausdruck durch und bietet Zugriff auf Suchergebnisse über[`TextFragments`](../textfragments) Sammlung.

### Beispiele

Das Beispiel zeigt, wie Sie Text mit regulären Ausdrücken auf der ersten PDF-Dokumentseite finden und den Text ersetzen.

```csharp
// Dokument öffnen
Document doc = new Document(@"D:\Tests\input.pdf");

// TextFragmentAbsorber-Objekt erstellen, das alle Wörter sucht, die mit „h“ beginnen und mit „o“ enden, indem ein regulärer Ausdruck verwendet wird.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(new System.Text.RegularExpressions.Regex(@"h\w*?o"), new TextSearchOptions(true));

// Wir sollten das Wort "Hallo" finden und es durch "Hi" ersetzen
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi";

// Dokument speichern
doc.Save(@"D:\Tests\output.pdf");
```

### Siehe auch

* class [TextSearchOptions](../../textsearchoptions)
* class [TextFragmentAbsorber](../../textfragmentabsorber)
* namensraum [Aspose.Pdf.Text](../../textfragmentabsorber)
* Montage [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextSearchOptions, TextEditOptions) {#constructor_5}

Initialisiert eine neue Instanz von[`TextFragmentAbsorber`](../../textfragmentabsorber) Klasse für die angegebene Textphrase, Textsuchoptionen und Textbearbeitungsoptionen.

```csharp
public TextFragmentAbsorber(string phrase, TextSearchOptions textSearchOptions, 
    TextEditOptions textEditOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| phrase | String | Satz, dass die[`TextFragmentAbsorber`](../../textfragmentabsorber) sucht |
| textSearchOptions | TextSearchOptions | Textsuchoptionen (Ermöglicht das Aktivieren einiger Suchfunktionen. Zum Beispiel Suche mit regulären Ausdrücken) |
| textEditOptions | TextEditOptions | Textbearbeitungsoptionen (Ermöglicht das Aktivieren einiger Bearbeitungsfunktionen). |

### Bemerkungen

Führt eine Textsuche nach dem angegebenen Ausdruck durch und bietet Zugriff auf Suchergebnisse über[`TextFragments`](../textfragments) Sammlung.

### Beispiele

Das Beispiel zeigt, wie man Text mit regulären Ausdrücken auf der ersten PDF-Dokumentseite findet und den Text ersetzt.

```csharp
// Dokument öffnen
Document doc = new Document(@"D:\Tests\input.pdf");

// TextFragmentAbsorber-Objekt erstellen, das alle Wörter sucht, die mit „h“ beginnen und mit „o“ enden, indem ein regulärer Ausdruck verwendet wird.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(@"h\w*?o", new TextSearchOptions(true));

// Wir sollten das Wort "Hallo" finden und es durch "Hi" ersetzen
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi"; 

// Dokument speichern
doc.Save(@"D:\Tests\output.pdf");  
```

### Siehe auch

* class [TextSearchOptions](../../textsearchoptions)
* class [TextEditOptions](../../texteditoptions)
* class [TextFragmentAbsorber](../../textfragmentabsorber)
* namensraum [Aspose.Pdf.Text](../../textfragmentabsorber)
* Montage [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextEditOptions) {#constructor_3}

Initialisiert eine neue Instanz von[`TextFragmentAbsorber`](../../textfragmentabsorber) Klasse für den angegebenen Textsatz und Textbearbeitungsoptionen.

```csharp
public TextFragmentAbsorber(string phrase, TextEditOptions textEditOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| phrase | String | Satz, dass die[`TextFragmentAbsorber`](../../textfragmentabsorber) sucht |
| textEditOptions | TextEditOptions | Textbearbeitungsoptionen (Ermöglicht das Aktivieren einiger Bearbeitungsfunktionen). |

### Bemerkungen

Führt eine Textsuche nach dem angegebenen Ausdruck durch und bietet Zugriff auf Suchergebnisse über[`TextFragments`](../textfragments) Sammlung.

### Siehe auch

* class [TextEditOptions](../../texteditoptions)
* class [TextFragmentAbsorber](../../textfragmentabsorber)
* namensraum [Aspose.Pdf.Text](../../textfragmentabsorber)
* Montage [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex, TextEditOptions) {#constructor_7}

Initialisiert eine neue Instanz von[`TextFragmentAbsorber`](../../textfragmentabsorber) Klasse für den angegebenen Textsatz und Textbearbeitungsoptionen.

```csharp
public TextFragmentAbsorber(Regex regex, TextEditOptions textEditOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| regex | Regex | System.Text.RegularExpressions.Regex-Klassenobjekt, das die[`TextFragmentAbsorber`](../../textfragmentabsorber) sucht |
| textEditOptions | TextEditOptions | Textbearbeitungsoptionen (Ermöglicht das Aktivieren einiger Bearbeitungsfunktionen). |

### Bemerkungen

Führt eine Textsuche nach dem angegebenen Ausdruck durch und bietet Zugriff auf Suchergebnisse über[`TextFragments`](../textfragments) Sammlung.

### Siehe auch

* class [TextEditOptions](../../texteditoptions)
* class [TextFragmentAbsorber](../../textfragmentabsorber)
* namensraum [Aspose.Pdf.Text](../../textfragmentabsorber)
* Montage [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
