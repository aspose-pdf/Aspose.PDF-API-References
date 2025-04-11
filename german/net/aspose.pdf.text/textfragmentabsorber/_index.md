---
title: Class TextFragmentAbsorber
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextFragmentAbsorber-Klasse. Stellt ein Absorberobjekt von Textfragmenten dar. Führt eine Textsuche durch und bietet Zugriff auf die Suchergebnisse über die TextFragments-Sammlung.
type: docs
weight: 10950
url: /de/net/aspose.pdf.text/textfragmentabsorber/
---
## TextFragmentAbsorber-Klasse

Stellt ein Absorberobjekt von Textfragmenten dar. Führt eine Textsuche durch und bietet Zugriff auf die Suchergebnisse über die [`TextFragments`](./textfragments/) Sammlung.

```csharp
public sealed class TextFragmentAbsorber : TextAbsorber
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor)() | Initialisiert eine neue Instanz des `TextFragmentAbsorber`, die die Suche nach allen Textsegmenten des Dokuments oder der Seite durchführt. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_6)(Regex) | Initialisiert eine neue Instanz der `TextFragmentAbsorber`-Klasse für das angegebene System.Text.RegularExpressions.Regex-Klassenobjekt. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_2)(string) | Initialisiert eine neue Instanz der `TextFragmentAbsorber`-Klasse für die angegebene Textphrase. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_1)(TextEditOptions) | Initialisiert eine neue Instanz des `TextFragmentAbsorber` mit Textbearbeitungsoptionen, die die Suche nach allen Textsegmenten des Dokuments oder der Seite durchführt. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_7)(Regex, TextEditOptions) | Initialisiert eine neue Instanz der `TextFragmentAbsorber`-Klasse für die angegebene Textphrase und Textbearbeitungsoptionen. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_8)(Regex, TextSearchOptions) | Initialisiert eine neue Instanz der `TextFragmentAbsorber`-Klasse für die angegebene Textphrase und Textsuchoptionen. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_9)(Regex[], TextSearchOptions) | Initialisiert eine neue Instanz der `TextFragmentAbsorber`-Klasse für die angegebene Textphrase und Textsuchoptionen. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_3)(string, TextEditOptions) | Initialisiert eine neue Instanz der `TextFragmentAbsorber`-Klasse für die angegebene Textphrase und Textbearbeitungsoptionen. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_4)(string, TextSearchOptions) | Initialisiert eine neue Instanz der `TextFragmentAbsorber`-Klasse für die angegebene Textphrase und Textsuchoptionen. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_5)(string, TextSearchOptions, TextEditOptions) | Initialisiert eine neue Instanz der `TextFragmentAbsorber`-Klasse für die angegebene Textphrase, Textsuchoptionen und Textbearbeitungsoptionen. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Errors](../../aspose.pdf.text/textfragmentabsorber/errors/) { get; } | Liste von [`TextExtractionError`](../textextractionerror/) Objekten. Sie enthält Informationen über Fehler, die während der Textextraktion gefunden wurden. Die Suche nach Fehlern wird nur durchgeführt, wenn TextSearchOptions.LogTextExtractionErrors = true; und kann die Leistung verringern. |
| override [ExtractionOptions](../../aspose.pdf.text/textfragmentabsorber/extractionoptions/) { get; set; } | Ruft die Textextraktionsoptionen ab oder legt sie fest. |
| [HasErrors](../../aspose.pdf.text/textfragmentabsorber/haserrors/) { get; } | Wert, der angibt, ob während der Textextraktion Fehler gefunden wurden. Die Suche nach Fehlern wird nur durchgeführt, wenn TextSearchOptions.LogTextExtractionErrors = true; und kann die Leistung verringern. |
| [Phrase](../../aspose.pdf.text/textfragmentabsorber/phrase/) { get; set; } | Ruft die Phrase ab oder legt sie fest, nach der der `TextFragmentAbsorber` im PDF-Dokument oder auf der Seite sucht. |
| [RegexResults](../../aspose.pdf.text/textfragmentabsorber/regexresults/) { get; } | Ruft ein Wörterbuch von Suchvorkommen ab, das mit der System.Text.RegularExpressions.Regex-Klasse als Schlüssel und [`TextFragment`](../textfragment/) als Wert dargestellt wird. |
| override [Text](../../aspose.pdf.text/textfragmentabsorber/text/) { get; } | Ruft den extrahierten Text ab, den der [`TextAbsorber`](../textabsorber/) im PDF-Dokument oder auf der Seite extrahiert. |
| [TextEditOptions](../../aspose.pdf.text/textfragmentabsorber/texteditoptions/) { get; set; } | Ruft die Textbearbeitungsoptionen ab oder legt sie fest. Die Optionen definieren ein spezielles Verhalten, wenn das angeforderte Symbol nicht mit der Schriftart geschrieben werden kann. |
| [TextFragments](../../aspose.pdf.text/textfragmentabsorber/textfragments/) { get; set; } | Ruft die Sammlung von Suchvorkommen ab, die mit [`TextFragment`](../textfragment/) Objekten dargestellt werden. |
| [TextReplaceOptions](../../aspose.pdf.text/textfragmentabsorber/textreplaceoptions/) { get; set; } | Ruft die Textersetzungsoptionen ab oder legt sie fest. Die Optionen definieren das Verhalten, wenn Fragmenttext durch kürzeren/längeren Text ersetzt wird. |
| [TextSearchOptions](../../aspose.pdf.text/textfragmentabsorber/textsearchoptions/) { get; set; } | Ruft die Suchoptionen ab oder legt sie fest. Die Optionen ermöglichen die Suche mit regulären Ausdrücken. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments/#applyforallfragments_2)(float) | Wendet die Schriftgröße auf alle absorbierten Textfragmente an. Es funktioniert schneller als das Durchlaufen der Fragmente, wenn alle Fragmente auf der Seite(n) absorbiert wurden. Andernfalls funktioniert es ähnlich wie beim Durchlaufen. |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments/#applyforallfragments)(Font) | Wendet die Schriftart auf alle absorbierten Textfragmente an. Es funktioniert schneller als das Durchlaufen der Fragmente, wenn alle Fragmente auf der Seite(n) absorbiert wurden. Andernfalls funktioniert es ähnlich wie beim Durchlaufen. |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments/#applyforallfragments_1)(Font, float) | Wendet Schriftart und -größe auf alle absorbierten Textfragmente an. Es funktioniert schneller als das Durchlaufen der Fragmente, wenn alle Fragmente auf der Seite(n) absorbiert wurden. Andernfalls funktioniert es ähnlich wie beim Durchlaufen. |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext/#removealltext)(Document) | Entfernt allen Text aus dem Dokument. |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext/#removealltext_1)(Page) | Entfernt allen Text von der angegebenen Seite. |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext/#removealltext_2)(Page, Rectangle) | Entfernt Text innerhalb des angegebenen Rechtecks von der angegebenen Seite. |
| [Reset](../../aspose.pdf.text/textfragmentabsorber/reset/)() | Löscht die TextFragments-Sammlung dieses `TextFragmentAbsorber`-Objekts. |
| override [Visit](../../aspose.pdf.text/textfragmentabsorber/visit/#visit)(Document) | Führt eine Suche im angegebenen Dokument durch. |
| override [Visit](../../aspose.pdf.text/textfragmentabsorber/visit/#visit_1)(Page) | Führt eine Suche auf der angegebenen Seite durch. |
| [Visit](../../aspose.pdf.text/textfragmentabsorber/visit/#visit_2)(XForm) | Führt eine Suche im angegebenen Formularobjekt durch. |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/)(XForm) | Extrahiert Text im angegebenen XForm. |

## Bemerkungen

Das `TextFragmentAbsorber`-Objekt wird im Wesentlichen in Szenarien zur Textsuche verwendet. Wenn die Suche abgeschlossen ist, werden die Vorkommen mit [`TextFragment`](../textfragment/) Objekten dargestellt, die die [`TextFragments`](./textfragments/) Sammlung enthält. Das [`TextFragment`](../textfragment/) Objekt bietet Zugriff auf den Suchvorkommens-Text, die Text-Eigenschaften und ermöglicht das Bearbeiten von Text und das Ändern des Textzustands (Schriftart, Schriftgröße, Farbe usw.).

## Beispiele

Das Beispiel zeigt, wie man Text auf der ersten Seite des PDF-Dokuments findet und den Text sowie seine Schriftart ersetzt.

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

* Klasse [TextAbsorber](../textabsorber/)
* Namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* Assembly [Aspose.PDF](../../)