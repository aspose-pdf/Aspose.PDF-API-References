---
title: TextAbsorber
second_title: Aspose.PDF für .NET-API-Referenz
description: Stellt ein Absorberobjekt eines Textes dar. Führt eine Textextraktion durch und bietet Zugriff auf das Ergebnis überText./textabsorber/text Objekt.
type: docs
weight: 6960
url: /de/net/aspose.pdf.text/textabsorber/
---
## TextAbsorber class

Stellt ein Absorberobjekt eines Textes dar. Führt eine Textextraktion durch und bietet Zugriff auf das Ergebnis über[`Text`](./text) Objekt.

```csharp
public class TextAbsorber
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [TextAbsorber](textabsorber#constructor)() | Initialisiert eine neue Instanz von[`TextAbsorber`](../textabsorber) . |
| [TextAbsorber](textabsorber#constructor_1)(TextExtractionOptions) | Initialisiert eine neue Instanz von[`TextAbsorber`](../textabsorber) mit Extraktionsoptionen. |
| [TextAbsorber](textabsorber#constructor_3)(TextSearchOptions) | Initialisiert eine neue Instanz von[`TextAbsorber`](../textabsorber) mit Textsuchoptionen. |
| [TextAbsorber](textabsorber#constructor_2)(TextExtractionOptions, TextSearchOptions) | Initialisiert eine neue Instanz von[`TextAbsorber`](../textabsorber) mit Extraktions- und Textsuchoptionen. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Errors](../../aspose.pdf.text/textabsorber/errors) { get; } | Liste von[`TextExtractionError`](../textextractionerror) Objekte. Es enthält Informationen über Fehler, die während der Textextraktion gefunden wurden. Die Suche nach Fehlern wird nur durchgeführt, wenn TextSearchOptions.LogTextExtractionErrors = true; Und es kann die Leistung beeinträchtigen. |
| virtual [ExtractionOptions](../../aspose.pdf.text/textabsorber/extractionoptions) { get; set; } | Ruft Textextraktionsoptionen ab oder legt sie fest. |
| [HasErrors](../../aspose.pdf.text/textabsorber/haserrors) { get; } | Wert gibt an, ob bei der Textextraktion Fehler gefunden wurden. Die Suche nach Fehlern wird nur durchgeführt, wenn TextSearchOptions.LogTextExtractionErrors = true; Und es kann die Leistung beeinträchtigen. |
| virtual [Text](../../aspose.pdf.text/textabsorber/text) { get; } | Ruft extrahierten Text ab, der die[`TextAbsorber`](../textabsorber) Auszüge auf dem PDF-Dokument oder der Seite. |
| virtual [TextSearchOptions](../../aspose.pdf.text/textabsorber/textsearchoptions) { get; set; } | Ruft Textsuchoptionen ab oder legt sie fest. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit#visit)(Document) | Extrahiert Text aus dem angegebenen Dokument |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit#visit_1)(Page) | Extrahiert Text auf der angegebenen Seite |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit#visit_2)(XForm) | Extrahiert Text aus dem angegebenen XForm. |

### Bemerkungen

Die[`TextAbsorber`](../textabsorber) Objekt wird verwendet, um Text aus einem PDF-Dokument oder der Seite des Dokuments zu extrahieren.

### Beispiele

Das Beispiel zeigt, wie Text auf der ersten PDF-Dokumentseite extrahiert wird.

```csharp
// Dokument öffnen
Document doc = new Document(inFile);

// TextAbsorber-Objekt erstellen, um Text zu extrahieren
TextAbsorber absorber = new TextAbsorber();

// Akzeptiere den Absorber für die erste Seite
doc.Pages[1].Accept(absorber);

// Holen Sie sich den extrahierten Text
string extractedText = absorber.Text;

```

### Siehe auch

* namensraum [Aspose.Pdf.Text](../../aspose.pdf.text)
* Montage [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
