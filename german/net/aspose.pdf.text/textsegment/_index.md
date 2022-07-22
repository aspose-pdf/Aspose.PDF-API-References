---
title: TextSegment
second_title: Aspose.PDF für .NET-API-Referenz
description: Stellt ein Segment des PDF-Textes dar.
type: docs
weight: 7210
url: /de/net/aspose.pdf.text/textsegment/
---
## TextSegment class

Stellt ein Segment des PDF-Textes dar.

```csharp
public sealed class TextSegment
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [TextSegment](textsegment#constructor)() | Erstellt ein TextSegment-Objekt. |
| [TextSegment](textsegment#constructor_1)(string) | Erstellt ein TextSegment-Objekt. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textsegment/baselineposition) { get; set; } | Ruft Textposition für Text ab, dargestellt mit[`TextSegment`](../textsegment) object. Der YIndent der Positionsstruktur stellt die Basiskoordinate des Textsegments dar. |
| [Characters](../../aspose.pdf.text/textsegment/characters) { get; } | Ruft eine Sammlung von CharInfo-Objekten ab, die Informationen zu Zeichen im Textsegment darstellen. |
| [EndCharIndex](../../aspose.pdf.text/textsegment/endcharindex) { get; } | Ruft den Endzeichenindex des aktuellen Segments im Show-Text-Operator-Segment (Tj, TJ) ab. |
| [Hyperlink](../../aspose.pdf.text/textsegment/hyperlink) { get; set; } | Holt oder setzt den Segment-Hyperlink (für PDF-Generator). |
| [Position](../../aspose.pdf.text/textsegment/position) { get; set; } | Ruft Textposition für Text ab, dargestellt mit[`TextSegment`](../textsegment) Objekt. |
| [Rectangle](../../aspose.pdf.text/textsegment/rectangle) { get; } | Ruft Rechteck von TextSegment ab |
| [StartCharIndex](../../aspose.pdf.text/textsegment/startcharindex) { get; } | Ruft den Anfangszeichenindex des aktuellen Segments im Segment des Anzeigetextoperators (Tj, TJ) ab. |
| [Text](../../aspose.pdf.text/textsegment/text) { get; set; } | Holt oder setztString Textobjekt, das die[`TextSegment`](../textsegment) Objekt repräsentiert. |
| [TextEditOptions](../../aspose.pdf.text/textsegment/texteditoptions) { get; set; } | Ruft Textbearbeitungsoptionen ab oder setzt sie. Die Optionen definieren ein spezielles Verhalten, wenn angefordertes Symbol nicht mit Schriftart geschrieben werden kann. |
| [TextState](../../aspose.pdf.text/textsegment/textstate) { get; set; } | Ermittelt oder setzt den Textstatus für den Text, der[`TextSegment`](../textsegment) Objekt repräsentiert. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [MyHtmlEncode](../../aspose.pdf.text/textsegment/myhtmlencode)(string) | Kodiert Zeichenfolge als html. |

### Bemerkungen

In wenigen Worten,[`TextSegment`](../textsegment) Objekte sind Kinder von[`TextFragment`](../textfragment) Objekt. Im Detail: Text des PDF-Dokuments inPdf wird durch zwei grundlegende Objekte dargestellt:[`TextFragment`](../textfragment) und[`TextSegment`](../textsegment) Die Unterschiede zwischen ihnen sind größtenteils kontextabhängig. Betrachten wir folgendes Szenario. Der Benutzer sucht nach dem Text „Hello World“, um damit zu arbeiten, seine Eigenschaften zu ändern, umzusehen usw. Physikalisch ist die Darstellung von PDF-Texten sehr komplex. Der Text "Hallo Welt" kann aus mehreren physikalisch unabhängigen Textsegmenten bestehen. Das Aspose.Pdf-Textmodell stellt dies grundsätzlich her[`TextFragment`](../textfragment) object bietet eine einzelne logische Operation, die über physisch gesetzt wird[`TextSegment`](../textsegment) Objektsatz, der die Abfrage des Benutzers darstellt. Im Textsuchszenario[`TextFragment`](../textfragment) ist eine logische "Hallo Welt"-Textdarstellung, und[`TextSegment`](../textsegment)Die Objektsammlung stellt alle physischen Segmente dar, die das Textobjekt „Hallo Welt“ bilden. Also,[`TextFragment`](../textfragment) ist der logischen Textdarstellung nahe. Und[`TextSegment`](../textsegment) ist nah an der physischen Textdarstellung. Offensichtlich jeder[`TextSegment`](../textsegment) Objekt kann seine eigene Schriftart, Farbgebung und Positionierungseigenschaften haben. [`TextFragment`](../textfragment) bietet eine einfache Möglichkeit, Text mit seinen Eigenschaften zu ändern: Schriftart festlegen, Schriftgröße festlegen, Schriftfarbe festlegen usw. Inzwischen[`TextSegment`](../textsegment) Objekte sind zugänglich und Benutzer können damit arbeiten[`TextSegment`](../textsegment) Objekte unabhängig.

```csharp
Document doc = new Document(docFile);
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
doc.Pages[1].Accept(absorber);
```

### Beispiele

Das Beispiel demonstriert, wie man Textfarbe und Schriftgröße des Textes mit ändert[`TextState`](./textstate) Gegenstand von[`TextSegment`](../textsegment) Objekt.

```csharp
// Dokument öffnen
Document doc = new Document(@"D:\Tests\input.pdf");

// TextFragmentAbsorber-Objekt erstellen, um alle "Hello World"-Textvorkommen zu finden
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Akzeptiere den Absorber für die erste Seite
doc.Pages[1].Accept(absorber);

// Vordergrundfarbe des ersten Textsegments des ersten Textvorkommens ändern
absorber.TextFragments[1].Segments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);
// Schriftgröße des ersten Textsegments des ersten Textvorkommens ändern
absorber.TextFragments[1].Segments[1].TextState.FontSize = 15;

// Dokument speichern
doc.Save(@"D:\Tests\output.pdf");  
```

### Siehe auch

* namensraum [Aspose.Pdf.Text](../../aspose.pdf.text)
* Montage [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
