---
title: TextFragmentAbsorber.TextFragmentAbsorber
second_title: Aspose.PDF for .NET API Reference
description: TextFragmentAbsorber-Konstruktor. Initialisiert eine neue Instanz des TextFragmentAbsorber, der die Suche nach allen Textsegmenten des Dokuments oder der Seite durchführt
type: docs
weight: 10
url: /de/net/aspose.pdf.text/textfragmentabsorber/textfragmentabsorber/
---
## TextFragmentAbsorber() {#constructor}

Initialisiert eine neue Instanz des [`TextFragmentAbsorber`](../), der die Suche nach allen Textsegmenten des Dokuments oder der Seite durchführt.

```csharp
public TextFragmentAbsorber()
```

## Bemerkungen

Führt eine Textsuche durch und bietet Zugriff auf die Suchergebnisse über die Sammlung [`TextFragments`](../textfragments/).

## Beispiele

Das Beispiel zeigt, wie man Text auf der ersten PDF-Dokumentseite findet und den Text ersetzt.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Find font that will be used to change document text font
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Create TextFragmentAbsorber object
TextFragmentAbsorber absorber = new TextFragmentAbsorber();

// Make the absorber to search all "hello world" text occurrences
absorber.Phrase = "hello world";

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change text of the first text occurrence
absorber.TextFragments[1].Text = "hi world";

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### Siehe auch

* Klasse [TextFragmentAbsorber](../)
* Namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* Assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(TextEditOptions) {#constructor_1}

Initialisiert eine neue Instanz des [`TextFragmentAbsorber`](../) mit Textbearbeitungsoptionen, die die Suche nach allen Textsegmenten des Dokuments oder der Seite durchführt.

```csharp
public TextFragmentAbsorber(TextEditOptions textEditOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| textEditOptions | TextEditOptions | Textbearbeitungsoptionen (Ermöglicht das Aktivieren bestimmter Bearbeitungsfunktionen). |

## Bemerkungen

Führt eine Textsuche durch und bietet Zugriff auf die Suchergebnisse über die Sammlung [`TextFragments`](../textfragments/).

## Beispiele

Das Beispiel zeigt, wie man alle Textfragmente auf der ersten PDF-Dokumentseite findet und die Schriftart für sie ersetzt.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object
TextFragmentAbsorber absorber = new TextFragmentAbsorber(new TextEditOptions(TextEditOptions.FontReplace.RemoveUnusedFonts));

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Find Courier font
Pdf.Text.Font font = FontRepository.FindFont("Courier");

// Set the font for all the text fragments
foreach (TextFragment textFragment in absorber.TextFragments)
{
    textFragment.TextState.Font = font;
}

// Save document
doc.Save(@"D:\Tests\output.pdf");
```

### Siehe auch

* Klasse [TextEditOptions](../../texteditoptions/)
* Klasse [TextFragmentAbsorber](../)
* Namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* Assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string) {#constructor_2}

Initialisiert eine neue Instanz der [`TextFragmentAbsorber`](../)-Klasse für den angegebenen Textausdruck.

```csharp
public TextFragmentAbsorber(string phrase)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| phrase | String | Ausdruck, den der [`TextFragmentAbsorber`](../) sucht |

## Bemerkungen

Führt eine Textsuche des angegebenen Ausdrucks durch und bietet Zugriff auf die Suchergebnisse über die Sammlung [`TextFragments`](../textfragments/).

## Beispiele

Das Beispiel zeigt, wie man Text auf der ersten PDF-Dokumentseite findet und den Text sowie seine Schriftart ersetzt.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Find font that will be used to change document text font
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change text and font of the first text occurrence
absorber.TextFragments[1].Text = "hi world";
absorber.TextFragments[1].TextState.Font = font;

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### Siehe auch

* Klasse [TextFragmentAbsorber](../)
* Namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* Assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex) {#constructor_6}

Initialisiert eine neue Instanz der [`TextFragmentAbsorber`](../)-Klasse für das angegebene System.Text.RegularExpressions.Regex-Klassenobjekt.

```csharp
public TextFragmentAbsorber(Regex regex)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| regex | Regex | System.Text.RegularExpressions.Regex-Klassenobjekt, das der [`TextFragmentAbsorber`](../) sucht |

## Bemerkungen

Führt eine Textsuche des angegebenen Ausdrucks durch und bietet Zugriff auf die Suchergebnisse über die Sammlung [`TextFragments`](../textfragments/).

## Beispiele

Das Beispiel zeigt, wie man Text auf der ersten PDF-Dokumentseite findet und den Text sowie seine Schriftart ersetzt.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Find font that will be used to change document text font
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Create TextAbsorber object to find all instances of the input regex
TextFragmentAbsorber absorber = new TextFragmentAbsorber(new System.Text.RegularExpressions.Regex(@"h\w*?o"));

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// we should find "hello" word and replace it with "Hi"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi";

// Save document
doc.Save(@"D:\Tests\output.pdf");
```

### Siehe auch

* Klasse [TextFragmentAbsorber](../)
* Namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* Assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextSearchOptions) {#constructor_4}

Initialisiert eine neue Instanz der [`TextFragmentAbsorber`](../)-Klasse für den angegebenen Textausdruck und die Textsuchoptionen.

```csharp
public TextFragmentAbsorber(string phrase, TextSearchOptions textSearchOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| phrase | String | Ausdruck, den der [`TextFragmentAbsorber`](../) sucht |
| textSearchOptions | TextSearchOptions | Textsuchoptionen (Ermöglicht das Aktivieren bestimmter Suchfunktionen. Zum Beispiel, Suche mit regulären Ausdrücken) |

## Bemerkungen

Führt eine Textsuche des angegebenen Ausdrucks durch und bietet Zugriff auf die Suchergebnisse über die Sammlung [`TextFragments`](../textfragments/).

## Beispiele

Das Beispiel zeigt, wie man Text mit regulären Ausdrücken auf der ersten PDF-Dokumentseite findet und den Text ersetzt.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object that searches all words starting 'h' and ending 'o' using regular expression.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(@"h\w*?o", new TextSearchOptions(true));

// we should find "hello" word and replace it with "Hi"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi"; 
 
// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### Siehe auch

* Klasse [TextSearchOptions](../../textsearchoptions/)
* Klasse [TextFragmentAbsorber](../)
* Namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* Assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex, TextSearchOptions) {#constructor_8}

Initialisiert eine neue Instanz der [`TextFragmentAbsorber`](../)-Klasse für den angegebenen Textausdruck und die Textsuchoptionen.

```csharp
public TextFragmentAbsorber(Regex regex, TextSearchOptions textSearchOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| regex | Regex | System.Text.RegularExpressions.Regex-Klassenobjekt, das der [`TextFragmentAbsorber`](../) sucht |
| textSearchOptions | TextSearchOptions | Textsuchoptionen (Ermöglicht das Aktivieren bestimmter Suchfunktionen.) |

## Bemerkungen

Führt eine Textsuche des angegebenen Ausdrucks durch und bietet Zugriff auf die Suchergebnisse über die Sammlung [`TextFragments`](../textfragments/).

## Beispiele

Das Beispiel zeigt, wie man Text mit regulären Ausdrücken auf der ersten PDF-Dokumentseite findet und den Text ersetzt.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object that searches all words starting 'h' and ending 'o' using regular expression.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(new System.Text.RegularExpressions.Regex(@"h\w*?o"), new TextSearchOptions(true));

// we should find "hello" word and replace it with "Hi"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi";

// Save document
doc.Save(@"D:\Tests\output.pdf");
```

### Siehe auch

* Klasse [TextSearchOptions](../../textsearchoptions/)
* Klasse [TextFragmentAbsorber](../)
* Namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* Assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex[], TextSearchOptions) {#constructor_9}

Initialisiert eine neue Instanz der [`TextFragmentAbsorber`](../)-Klasse für das angegebene Textausdrucksarray und die Textsuchoptionen.

```csharp
public TextFragmentAbsorber(Regex[] regexes, TextSearchOptions textSearchOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| regexes | Regex[] | Array von System.Text.RegularExpressions.Regex-Klassenobjekten, die der [`TextFragmentAbsorber`](../) sucht. |
| textSearchOptions | TextSearchOptions | Textsuchoptionen (Ermöglicht das Aktivieren bestimmter Suchfunktionen.). |

## Bemerkungen

Führt eine Textsuche des angegebenen Arrays von Ausdrücken durch und bietet Zugriff auf die Suchergebnisse über das Wörterbuch [`RegexResults`](../regexresults/).

## Beispiele

Das Beispiel zeigt, wie man Text mit einem Array von regulären Ausdrücken auf der ersten PDF-Dokumentseite findet.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

var regexes = new Regex[]
{
new Regex( @"expression1", RegexOptions.IgnoreCase),
new Regex( @"expression2", RegexOptions.IgnoreCase),
};
// Create TextFragmentAbsorber object that searches all words starting 'h' and ending 'o' using regular expression.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(regexes, new TextSearchOptions(true));
doc.Pages[1].Accept(absorber);
// Get results of 
var results = absorber.RegexResults;
```

### Siehe auch

* Klasse [TextSearchOptions](../../textsearchoptions/)
* Klasse [TextFragmentAbsorber](../)
* Namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* Assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextSearchOptions, TextEditOptions) {#constructor_5}

Initialisiert eine neue Instanz der [`TextFragmentAbsorber`](../)-Klasse für den angegebenen Textausdruck, die Textsuchoptionen und die Textbearbeitungsoptionen.

```csharp
public TextFragmentAbsorber(string phrase, TextSearchOptions textSearchOptions, 
    TextEditOptions textEditOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| phrase | String | Ausdruck, den der [`TextFragmentAbsorber`](../) sucht |
| textSearchOptions | TextSearchOptions | Textsuchoptionen (Ermöglicht das Aktivieren bestimmter Suchfunktionen. Zum Beispiel, Suche mit regulären Ausdrücken) |
| textEditOptions | TextEditOptions | Textbearbeitungsoptionen (Ermöglicht das Aktivieren bestimmter Bearbeitungsfunktionen). |

## Bemerkungen

Führt eine Textsuche des angegebenen Ausdrucks durch und bietet Zugriff auf die Suchergebnisse über die Sammlung [`TextFragments`](../textfragments/).

## Beispiele

Das Beispiel zeigt, wie man Text mit regulären Ausdrücken auf der ersten PDF-Dokumentseite findet und den Text ersetzt.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object that searches all words starting 'h' and ending 'o' using regular expression.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(@"h\w*?o", new TextSearchOptions(true));

// we should find "hello" word and replace it with "Hi"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi"; 

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### Siehe auch

* Klasse [TextSearchOptions](../../textsearchoptions/)
* Klasse [TextEditOptions](../../texteditoptions/)
* Klasse [TextFragmentAbsorber](../)
* Namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* Assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextEditOptions) {#constructor_3}

Initialisiert eine neue Instanz der [`TextFragmentAbsorber`](../)-Klasse für den angegebenen Textausdruck und die Textbearbeitungsoptionen.

```csharp
public TextFragmentAbsorber(string phrase, TextEditOptions textEditOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| phrase | String | Ausdruck, den der [`TextFragmentAbsorber`](../) sucht |
| textEditOptions | TextEditOptions | Textbearbeitungsoptionen (Ermöglicht das Aktivieren bestimmter Bearbeitungsfunktionen). |

## Bemerkungen

Führt eine Textsuche des angegebenen Ausdrucks durch und bietet Zugriff auf die Suchergebnisse über die Sammlung [`TextFragments`](../textfragments/).

### Siehe auch

* Klasse [TextEditOptions](../../texteditoptions/)
* Klasse [TextFragmentAbsorber](../)
* Namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* Assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex, TextEditOptions) {#constructor_7}

Initialisiert eine neue Instanz der [`TextFragmentAbsorber`](../)-Klasse für den angegebenen Textausdruck und die Textbearbeitungsoptionen.

```csharp
public TextFragmentAbsorber(Regex regex, TextEditOptions textEditOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| regex | Regex | System.Text.RegularExpressions.Regex-Klassenobjekt, das der [`TextFragmentAbsorber`](../) sucht |
| textEditOptions | TextEditOptions | Textbearbeitungsoptionen (Ermöglicht das Aktivieren bestimmter Bearbeitungsfunktionen). |

## Bemerkungen

Führt eine Textsuche des angegebenen Ausdrucks durch und bietet Zugriff auf die Suchergebnisse über die Sammlung [`TextFragments`](../textfragments/).

### Siehe auch

* Klasse [TextEditOptions](../../texteditoptions/)
* Klasse [TextFragmentAbsorber](../)
* Namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* Assembly [Aspose.PDF](../../../)