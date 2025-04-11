---
title: Class TextSegment
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextSegment-Klasse. Stellt ein Segment von Pdf-Text dar
type: docs
weight: 11050
url: /de/net/aspose.pdf.text/textsegment/
---
## TextSegment-Klasse

Stellt ein Segment von Pdf-Text dar.

```csharp
public sealed class TextSegment
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [TextSegment](textsegment/#constructor)() | Erstellt ein TextSegment-Objekt. |
| [TextSegment](textsegment/#constructor_1)(string) | Erstellt ein TextSegment-Objekt. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textsegment/baselineposition/) { get; set; } | Ruft die Textposition für den Text ab, der mit dem `TextSegment`-Objekt dargestellt wird. Der YIndent der Positionsstruktur stellt die Baseline-Koordinate des Textsegments dar. |
| [Characters](../../aspose.pdf.text/textsegment/characters/) { get; } | Ruft die Sammlung von CharInfo-Objekten ab, die Informationen über die Zeichen im Textsegment darstellen. |
| [EndCharIndex](../../aspose.pdf.text/textsegment/endcharindex/) { get; } | Ruft den Endzeichenindex des aktuellen Segments im Show-Text-Operator (Tj, TJ) ab. |
| [Hyperlink](../../aspose.pdf.text/textsegment/hyperlink/) { get; set; } | Ruft den Segmenthyperlink (für den PDF-Generator) ab oder setzt ihn. |
| [Position](../../aspose.pdf.text/textsegment/position/) { get; set; } | Ruft die Textposition für den Text ab, der mit dem `TextSegment`-Objekt dargestellt wird. |
| [Rectangle](../../aspose.pdf.text/textsegment/rectangle/) { get; } | Ruft das Rechteck des TextSegments ab. |
| [StartCharIndex](../../aspose.pdf.text/textsegment/startcharindex/) { get; } | Ruft den Startzeichenindex des aktuellen Segments im Show-Text-Operator (Tj, TJ) ab. |
| [Text](../../aspose.pdf.text/textsegment/text/) { get; set; } | Ruft das String-Textobjekt ab oder setzt es, das das `TextSegment`-Objekt darstellt. |
| [TextEditOptions](../../aspose.pdf.text/textsegment/texteditoptions/) { get; set; } | Ruft die Textbearbeitungsoptionen ab oder setzt sie. Die Optionen definieren ein spezielles Verhalten, wenn das angeforderte Symbol nicht mit der Schriftart geschrieben werden kann. |
| [TextState](../../aspose.pdf.text/textsegment/textstate/) { get; set; } | Ruft den Textzustand für den Text ab, den das `TextSegment`-Objekt darstellt. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [MyHtmlEncode](../../aspose.pdf.text/textsegment/myhtmlencode/)(string) | Kodiert einen String als HTML. |

## Bemerkungen

In wenigen Worten sind `TextSegment`-Objekte Kinder des [`TextFragment`](../textfragment/) Objekts. Im Detail: Der Text eines PDF-Dokuments wird in Pdf durch zwei grundlegende Objekte dargestellt: [`TextFragment`](../textfragment/) und `TextSegment`. Die Unterschiede zwischen ihnen sind größtenteils kontextabhängig. Betrachten wir folgendes Szenario. Der Benutzer sucht nach dem Text "hello world", um damit zu arbeiten, seine Eigenschaften zu ändern, zu suchen usw.

```csharp
Document doc = new Document(docFile);
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
doc.Pages[1].Accept(absorber);
```

Die physische Darstellung von PDF-Text ist sehr komplex. Der Text "hello world" kann aus mehreren physisch unabhängigen Textsegmenten bestehen. Das Aspose.Pdf-Textmodell legt grundsätzlich fest, dass das [`TextFragment`](../textfragment/) Objekt eine einzelne logische Operation über die physischen `TextSegment`-Objekte bereitstellt, die die Abfrage des Benutzers darstellen. Im Textsuchszenario ist das [`TextFragment`](../textfragment/) die logische Darstellung des Textes "hello world", und die Sammlung von `TextSegment`-Objekten stellt alle physischen Segmente dar, die das Textobjekt "hello world" konstruieren. Daher ist das [`TextFragment`](../textfragment/) nahe an der logischen Textdarstellung. Und `TextSegment` ist nahe an der physischen Textdarstellung. Offensichtlich kann jedes `TextSegment`-Objekt seine eigene Schriftart, Farb- und Positionierungseigenschaften haben. Das [`TextFragment`](../textfragment/) bietet eine einfache Möglichkeit, den Text mit seinen Eigenschaften zu ändern: Schriftart festlegen, Schriftgröße festlegen, Schriftfarbe festlegen usw. In der Zwischenzeit sind `TextSegment`-Objekte zugänglich und Benutzer können unabhängig mit `TextSegment`-Objekten arbeiten.

## Beispiele

Das Beispiel zeigt, wie man die Textfarbe und die Schriftgröße des Textes mit dem [`TextState`](./textstate/) Objekt des `TextSegment`-Objekts ändert.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change foreground color of the first text segment of the first text occurrence
absorber.TextFragments[1].Segments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);
// Change font size of the first text segment of the first text occurrence
absorber.TextFragments[1].Segments[1].TextState.FontSize = 15;

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### Siehe auch

* Namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* Assembly [Aspose.PDF](../../)