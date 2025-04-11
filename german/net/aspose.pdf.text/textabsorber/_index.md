---
title: Class TextAbsorber
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextAbsorber-Klasse. Stellt ein Absorberobjekt eines Textes dar. Führt die Textextraktion durch und bietet Zugriff auf das Ergebnis über das [`Text`](./text/) Objekt
type: docs
weight: 10800
url: /de/net/aspose.pdf.text/textabsorber/
---
## TextAbsorber-Klasse

Stellt ein Absorberobjekt eines Textes dar. Führt die Textextraktion durch und bietet Zugriff auf das Ergebnis über das [`Text`](./text/) Objekt.

```csharp
public class TextAbsorber
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [TextAbsorber](textabsorber/#constructor)() | Initialisiert eine neue Instanz des `TextAbsorber`. |
| [TextAbsorber](textabsorber/#constructor_1)(TextExtractionOptions) | Initialisiert eine neue Instanz des `TextAbsorber` mit Extraktionsoptionen. |
| [TextAbsorber](textabsorber/#constructor_3)(TextSearchOptions) | Initialisiert eine neue Instanz des `TextAbsorber` mit Textsuchoptionen. |
| [TextAbsorber](textabsorber/#constructor_2)(TextExtractionOptions, TextSearchOptions) | Initialisiert eine neue Instanz des `TextAbsorber` mit Extraktions- und Textsuchoptionen. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Errors](../../aspose.pdf.text/textabsorber/errors/) { get; } | Liste von [`TextExtractionError`](../textextractionerror/) Objekten. Sie enthält Informationen über Fehler, die während der Textextraktion gefunden wurden. Die Fehlersuche wird nur durchgeführt, wenn TextSearchOptions.LogTextExtractionErrors = true; und kann die Leistung verringern. |
| virtual [ExtractionOptions](../../aspose.pdf.text/textabsorber/extractionoptions/) { get; set; } | Ruft die Textextraktionsoptionen ab oder legt sie fest. |
| [HasErrors](../../aspose.pdf.text/textabsorber/haserrors/) { get; } | Wert, der angibt, ob während der Textextraktion Fehler gefunden wurden. Die Fehlersuche wird nur durchgeführt, wenn TextSearchOptions.LogTextExtractionErrors = true; und kann die Leistung verringern. |
| virtual [Text](../../aspose.pdf.text/textabsorber/text/) { get; } | Ruft den extrahierten Text ab, den der `TextAbsorber` aus dem PDF-Dokument oder der Seite extrahiert. |
| virtual [TextSearchOptions](../../aspose.pdf.text/textabsorber/textsearchoptions/) { get; set; } | Ruft die Textsuchoptionen ab oder legt sie fest. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/#visit)(Document) | Extrahiert Text im angegebenen Dokument |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/#visit_1)(Page) | Extrahiert Text auf der angegebenen Seite |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/#visit_2)(XForm) | Extrahiert Text im angegebenen XForm. |

## Bemerkungen

Das `TextAbsorber`-Objekt wird verwendet, um Text aus einem PDF-Dokument oder der Seite des Dokuments zu extrahieren.

## Beispiele

Das Beispiel zeigt, wie man Text auf der ersten Seite des PDF-Dokuments extrahiert.

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text
TextAbsorber absorber = new TextAbsorber();

// accept the absorber for first page
doc.Pages[1].Accept(absorber);

// get the extracted text
string extractedText = absorber.Text;

```

### Siehe auch

* Namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* Assembly [Aspose.PDF](../../)