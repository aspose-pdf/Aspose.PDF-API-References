---
title: TextFragmentAbsorber
second_title: Aspose.PDF für .NET-API-Referenz
description: Stellt ein Absorberobjekt von Textfragmenten dar. Führt eine Textsuche durch und bietet Zugriff auf Suchergebnisse überTextFragments./textfragmentabsorber/textfragments Sammlung.
type: docs
weight: 7110
url: /de/net/aspose.pdf.text/textfragmentabsorber/
---
## TextFragmentAbsorber class

Stellt ein Absorberobjekt von Textfragmenten dar. Führt eine Textsuche durch und bietet Zugriff auf Suchergebnisse über[`TextFragments`](./textfragments) Sammlung.

```csharp
public sealed class TextFragmentAbsorber : TextAbsorber
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [TextFragmentAbsorber](textfragmentabsorber#constructor)() | Initialisiert eine neue Instanz von[`TextFragmentAbsorber`](../textfragmentabsorber) die eine Suche nach allen Textsegmenten des Dokuments oder der Seite durchführt. |
| [TextFragmentAbsorber](textfragmentabsorber#constructor_6)(Regex) | Initialisiert eine neue Instanz von[`TextFragmentAbsorber`](../textfragmentabsorber) Klasse für das angegebene System.Text.RegularExpressions.Regex-Klassenobjekt. |
| [TextFragmentAbsorber](textfragmentabsorber#constructor_2)(string) | Initialisiert eine neue Instanz von[`TextFragmentAbsorber`](../textfragmentabsorber) Klasse für die angegebene Textphrase. |
| [TextFragmentAbsorber](textfragmentabsorber#constructor_1)(TextEditOptions) | Initialisiert eine neue Instanz von[`TextFragmentAbsorber`](../textfragmentabsorber)mit Textbearbeitungsoptionen, die eine Suche nach allen Textsegmenten des Dokuments oder der Seite durchführt. |
| [TextFragmentAbsorber](textfragmentabsorber#constructor_7)(Regex, TextEditOptions) | Initialisiert eine neue Instanz von[`TextFragmentAbsorber`](../textfragmentabsorber) Klasse für den angegebenen Textsatz und Textbearbeitungsoptionen. |
| [TextFragmentAbsorber](textfragmentabsorber#constructor_8)(Regex, TextSearchOptions) | Initialisiert eine neue Instanz von[`TextFragmentAbsorber`](../textfragmentabsorber) Klasse für die angegebenen Textphrasen und Textsuchoptionen. |
| [TextFragmentAbsorber](textfragmentabsorber#constructor_3)(string, TextEditOptions) | Initialisiert eine neue Instanz von[`TextFragmentAbsorber`](../textfragmentabsorber) Klasse für den angegebenen Textsatz und Textbearbeitungsoptionen. |
| [TextFragmentAbsorber](textfragmentabsorber#constructor_4)(string, TextSearchOptions) | Initialisiert eine neue Instanz von[`TextFragmentAbsorber`](../textfragmentabsorber)Klasse für die angegebenen Textphrasen und Textsuchoptionen. |
| [TextFragmentAbsorber](textfragmentabsorber#constructor_5)(string, TextSearchOptions, TextEditOptions) | Initialisiert eine neue Instanz von[`TextFragmentAbsorber`](../textfragmentabsorber) Klasse für die angegebene Textphrase, Textsuchoptionen und Textbearbeitungsoptionen. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Errors](../../aspose.pdf.text/textfragmentabsorber/errors) { get; } | Liste von[`TextExtractionError`](../textextractionerror) Objekte. Es enthält Informationen über Fehler, die während der Textextraktion gefunden wurden. Die Suche nach Fehlern wird nur durchgeführt, wenn TextSearchOptions.LogTextExtractionErrors = true; Und es kann die Leistung beeinträchtigen. |
| override [ExtractionOptions](../../aspose.pdf.text/textfragmentabsorber/extractionoptions) { get; set; } | Ruft Textextraktionsoptionen ab oder legt sie fest. |
| [HasErrors](../../aspose.pdf.text/textfragmentabsorber/haserrors) { get; } | Wert gibt an, ob bei der Textextraktion Fehler gefunden wurden. Die Suche nach Fehlern wird nur durchgeführt, wenn TextSearchOptions.LogTextExtractionErrors = true; Und es kann die Leistung beeinträchtigen. |
| [Phrase](../../aspose.pdf.text/textfragmentabsorber/phrase) { get; set; } | Ruft die Phrase ab oder legt fest, dass die[`TextFragmentAbsorber`](../textfragmentabsorber) sucht im PDF-Dokument oder auf der Seite. |
| override [Text](../../aspose.pdf.text/textfragmentabsorber/text) { get; } | Ruft extrahierten Text ab, der die[`TextAbsorber`](../textabsorber) Auszüge auf dem PDF-Dokument oder der Seite. |
| [TextEditOptions](../../aspose.pdf.text/textfragmentabsorber/texteditoptions) { get; set; } | Ruft Textbearbeitungsoptionen ab oder setzt sie. Die Optionen definieren ein spezielles Verhalten, wenn angefordertes Symbol nicht mit Schriftart geschrieben werden kann. |
| [TextFragments](../../aspose.pdf.text/textfragmentabsorber/textfragments) { get; set; } | Ruft eine Sammlung von Suchvorkommen ab, die angezeigt werden[`TextFragment`](../textfragment) Objekte. |
| [TextReplaceOptions](../../aspose.pdf.text/textfragmentabsorber/textreplaceoptions) { get; set; } | Holt oder setzt Optionen zum Ersetzen von Text. Die Optionen definieren das Verhalten, wenn Fragmenttext durch kürzeren/langen ersetzt wird. |
| [TextSearchOptions](../../aspose.pdf.text/textfragmentabsorber/textsearchoptions) { get; set; } | Ruft Suchoptionen ab oder legt sie fest. Die Optionen ermöglichen die Suche mit regulären Ausdrücken. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments#applyforallfragments_2)(float) | Wendet die Schriftgröße für alle absorbierten Textfragmente an. Es funktioniert schneller als das Durchlaufen der Fragmente, wenn alle Fragmente auf der/den Seite(n) absorbiert wurden. Ansonsten funktioniert es ähnlich mit Looping. |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments#applyforallfragments)(Font) | Wendet Schriftart für alle absorbierten Textfragmente an. Es funktioniert schneller als das Durchlaufen der Fragmente, wenn alle Fragmente auf der/den Seite(n) absorbiert wurden. Ansonsten funktioniert es ähnlich mit Looping. |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments#applyforallfragments_1)(Font, float) | Wendet Schriftart und -größe auf alle absorbierten Textfragmente an. Es funktioniert schneller als das Durchlaufen der Fragmente, wenn alle Fragmente auf der/den Seite(n) absorbiert wurden. Ansonsten funktioniert es ähnlich mit Looping. |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext#removealltext)(Document) | Entfernt den gesamten Text aus dem Dokument. |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext#removealltext_1)(Page) | Entfernt den gesamten Text von der angegebenen Seite. |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext#removealltext_2)(Page, Rectangle) | Entfernt Text innerhalb des angegebenen Rechtecks von der angegebenen Seite. |
| [Reset](../../aspose.pdf.text/textfragmentabsorber/reset)() | Löscht die TextFragments-Sammlung davon[`TextFragmentAbsorber`](../textfragmentabsorber) Objekt. |
| override [Visit](../../aspose.pdf.text/textfragmentabsorber/visit#visit)(Document) | Führt eine Suche im angegebenen Dokument durch. |
| override [Visit](../../aspose.pdf.text/textfragmentabsorber/visit#visit_1)(Page) | Führt eine Suche auf der angegebenen Seite durch. |
| [Visit](../../aspose.pdf.text/textfragmentabsorber/visit#visit_2)(XForm) | Führt eine Suche nach dem angegebenen Formularobjekt durch. |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit)(XForm) | Extrahiert Text aus dem angegebenen XForm. |

### Bemerkungen

Die[`TextFragmentAbsorber`](../textfragmentabsorber) Das Objekt wird hauptsächlich im Textsuchszenario verwendet. Wenn die Suche abgeschlossen ist, werden die Vorkommen mit dargestellt[`TextFragment`](../textfragment) Objekte, die[`TextFragments`](./textfragments) Sammlung enthält. Die[`TextFragment`](../textfragment) Das Objekt bietet Zugriff auf den Text des Suchvorkommens und die Texteigenschaften und ermöglicht das Bearbeiten von Text und das Ändern des Textstatus (Schriftart, Schriftgröße, Farbe usw.).

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

* class [TextAbsorber](../textabsorber)
* namensraum [Aspose.Pdf.Text](../../aspose.pdf.text)
* Montage [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
