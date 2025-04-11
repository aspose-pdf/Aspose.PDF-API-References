---
title: Class ParagraphAbsorber
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.ParagraphAbsorber-Klasse. Stellt ein Absorberobjekt von Seitenstrukturobjekten wie Abschnitten und Absätzen dar. Führt die Suche nach Abschnitten und Absätzen von Text durch und bietet Zugriff auf Rechtecke und Polygone, die es im Textkoordinatenraum beschreiben. Führt auch die Suche nach Textsegmenten durch und bietet Zugriff auf die Suchergebnisse über TextFragments-Sammlungen, die nach Strukturelementen gruppiert sind.
type: docs
weight: 10670
url: /de/net/aspose.pdf.text/paragraphabsorber/
---
## ParagraphAbsorber-Klasse

Stellt ein Absorberobjekt von Seitenstrukturobjekten wie Abschnitten und Absätzen dar. Führt die Suche nach Abschnitten und Absätzen von Text durch und bietet Zugriff auf Rechtecke und Polygone, die es im Textkoordinatenraum beschreiben. Führt auch die Suche nach Textsegmenten durch und bietet Zugriff auf die Suchergebnisse über !:TextFragments-Sammlungen, die nach Strukturelementen gruppiert sind.

```csharp
public class ParagraphAbsorber
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [ParagraphAbsorber](paragraphabsorber/#constructor)() | Initialisiert eine neue Instanz des `ParagraphAbsorber`, die die Suche nach Abschnitten/Absätzen des Dokuments oder der Seite durchführt. |
| [ParagraphAbsorber](paragraphabsorber/#constructor_2)(int) | Initialisiert eine neue Instanz des `ParagraphAbsorber`, die die Suche nach Abschnitten/Absätzen des Dokuments oder der Seite durchführt. |
| [ParagraphAbsorber](paragraphabsorber/#constructor_1)(ParagraphAbsorberOptions) | Initialisiert eine neue Instanz des `ParagraphAbsorber`, die die Suche nach Abschnitten/Absätzen des Dokuments oder der Seite mit den angegebenen Parametern durchführt. |
| [ParagraphAbsorber](paragraphabsorber/#constructor_3)(int, ParagraphAbsorberOptions) | Initialisiert eine neue Instanz des `ParagraphAbsorber`, die die Suche nach Abschnitten/Absätzen des Dokuments oder der Seite mit den angegebenen Parametern durchführt. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [IsMulticolumnParagraphsAllowed](../../aspose.pdf.text/paragraphabsorber/ismulticolumnparagraphsallowed/) { get; set; } | Ruft den Wert ab oder legt ihn fest, der angibt, ob die Anfangstextzeilen eines nächsten Abschnitts als Fortsetzung des letzten Absatzes eines vorherigen Abschnitts behandelt werden dürfen. |
| [PageMarkups](../../aspose.pdf.text/paragraphabsorber/pagemarkups/) { get; } | Ruft die Sammlung von [`PageMarkup`](../pagemarkup/) ab, die absorbiert wurden. |
| [ParagraphAbsorberOptions](../../aspose.pdf.text/paragraphabsorber/paragraphabsorberoptions/) { get; set; } | Ruft die ParagraphAbsorberOptions ab oder legt sie fest. |
| [SectionsSearchDepth](../../aspose.pdf.text/paragraphabsorber/sectionssearchdepth/) { get; set; } | Ruft den Wert ab oder legt ihn fest, der angibt, wie oft aufeinanderfolgende Suchen nach feineren Strukturelementen durchgeführt werden. Die Standard-Suchtiefe beträgt 3. Das bedeutet drei Suchen nach horizontal geteilten Abschnitten (Kopfzeilen, Absätze usw.) und drei Suchen nach vertikal geteilten (Spalten). |
| [TextReplaceOptions](../../aspose.pdf.text/paragraphabsorber/textreplaceoptions/) { get; set; } | Ruft die TextReplaceOptions ab oder legt sie fest. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Visit](../../aspose.pdf.text/paragraphabsorber/visit/#visit)(Document) | Führt die Suche nach Abschnitten und Absätzen im angegebenen [`Document`](../../aspose.pdf/document/) durch. |
| [Visit](../../aspose.pdf.text/paragraphabsorber/visit/#visit_1)(Page) | Führt die Suche auf der angegebenen [`Page`](../../aspose.pdf/page/) durch. |

## Anmerkungen

Wenn die Suche abgeschlossen ist, enthält die [`PageMarkups`](./pagemarkups/) Sammlung [`PageMarkup`](../pagemarkup/) Objekte, die die Seitenstruktur durch Sammlungen von [`MarkupSection`](../markupsection/) und [`MarkupParagraph`](../markupparagraph/) darstellen. Das [`TextFragment`](../textfragment/) Objekt bietet Zugriff auf den Suchvorkommen-Text, die Text-Eigenschaften und ermöglicht das Bearbeiten von Text und das Ändern des Textzustands (Schriftart, Schriftgröße, Farbe usw.).

## Beispiele

Das Beispiel zeigt, wie man das erste Textsegment jedes Absatzes auf der ersten PDF-Dokumentseite findet und hervorhebt.

```csharp
// Open document
Document doc = new Document("input.pdf");

// Create ParagraphAbsorber object
ParagraphAbsorber absorber = new ParagraphAbsorber();

// Accept the absorber for first page
absorber.Visit(doc.Pages[1]);

// Get markup object of first page
PageMarkup markup = absorber.PageMarkups[0];

// Loop through structure elements of the page text to find first text fragment of each paragraph
foreach (MarkupSection section in markup.Sections)
{
    foreach (MarkupParagraph paragraph in section.Paragraphs)
    {
        TextFragment fragment = paragraph.Fragments[0];
        // Update text properties
        fragment.TextState.BackgroundColor = Color.LightBlue;
    }
}

// Save document
doc.Save(GetOutputPath("output.pdf"));
```

### Siehe auch

* Namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* Assembly [Aspose.PDF](../../)