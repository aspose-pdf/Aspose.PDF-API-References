---
title: Class TextFragment
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextFragment-Klasse. Stellt einen Fragment von Pdf-Text dar
type: docs
weight: 10940
url: /de/net/aspose.pdf.text/textfragment/
---
## TextFragment-Klasse

Stellt einen Fragment von Pdf-Text dar.

```csharp
public class TextFragment : BaseParagraph
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [TextFragment](textfragment/#constructor)() | Initialisiert eine neue Instanz des `TextFragment`-Objekts. |
| [TextFragment](textfragment/#constructor_2)(string) | Erstellt ein `TextFragment`-Objekt mit einem einzelnen [`TextSegment`](../textsegment/) Objekt darin. Gibt den Textstring im Segment an. |
| [TextFragment](textfragment/#constructor_1)(TabStops) | Initialisiert eine neue Instanz des `TextFragment`-Objekts mit vordefinierten [`TabStops`](../tabstops/) Positionen. |
| [TextFragment](textfragment/#constructor_3)(string, TabStops) | Erstellt ein `TextFragment`-Objekt mit einem einzelnen [`TextSegment`](../textsegment/) Objekt darin und vordefinierten [`TabStops`](../tabstops/) Positionen. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textfragment/baselineposition/) { get; set; } | Gibt die Textposition für den Text zurück, der mit dem `TextFragment`-Objekt dargestellt wird. Der YIndent der Positionsstruktur stellt die Baseline-Koordinate des Textfragments dar. |
| [EndNote](../../aspose.pdf.text/textfragment/endnote/) { get; set; } | Ruft die Fußnote des Absatzes ab oder legt sie fest. (nur für die PDF-Generierung) |
| [FootNote](../../aspose.pdf.text/textfragment/footnote/) { get; set; } | Ruft die Fußnote des Absatzes ab oder legt sie fest. (nur für die PDF-Generierung) |
| [Form](../../aspose.pdf.text/textfragment/form/) { get; } | Ruft das Formularobjekt ab, das das TextFragment enthält |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragment/horizontalalignment/) { get; set; } | Ruft die horizontale Ausrichtung des Textfragments ab oder legt sie fest. |
| override [Hyperlink](../../aspose.pdf.text/textfragment/hyperlink/) { set; } | Legt den Hyperlink des Fragments fest |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Ruft einen booleschen Wert ab oder legt ihn fest, der angibt, ob dieser Absatz in der nächsten Spalte steht. Standard ist falsch. (für die PDF-Generierung) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Ruft ab oder legt fest, ob ein Absatz inline ist. Standard ist falsch. (für die PDF-Generierung) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Ruft einen booleschen Wert ab oder legt ihn fest, der diesen Absatz zwingt, auf einer neuen Seite zu generieren. Standard ist falsch. (für die PDF-Generierung) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Ruft einen booleschen Wert ab oder legt ihn fest, der angibt, ob der aktuelle Absatz auf derselben Seite wie der nächste Absatz bleibt. Standard ist falsch. (für die PDF-Generierung) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Ruft den äußeren Rand für den Absatz ab oder legt ihn fest (für die PDF-Generierung) |
| [Page](../../aspose.pdf.text/textfragment/page/) { get; } | Ruft die Seite ab, die das TextFragment enthält |
| [Position](../../aspose.pdf.text/textfragment/position/) { get; set; } | Ruft die Textposition für den Text ab, der mit dem `TextFragment`-Objekt dargestellt wird. |
| [Rectangle](../../aspose.pdf.text/textfragment/rectangle/) { get; } | Ruft das Rechteck des TextFragments ab |
| [ReplaceOptions](../../aspose.pdf.text/textfragment/replaceoptions/) { get; } | Ruft die Textersetzungsoptionen ab. Die Optionen definieren das Verhalten, wenn der Fragmenttext durch einen kürzeren/längeren Text ersetzt wird. |
| [Segments](../../aspose.pdf.text/textfragment/segments/) { get; set; } | Ruft die Textsegmente für das aktuelle `TextFragment` ab. |
| [Text](../../aspose.pdf.text/textfragment/text/) { get; set; } | Ruft das String-Textobjekt ab oder legt es fest, das das `TextFragment`-Objekt darstellt. |
| [TextEditOptions](../../aspose.pdf.text/textfragment/texteditoptions/) { get; set; } | Ruft die Textbearbeitungsoptionen ab oder legt sie fest. Die Optionen definieren ein spezielles Verhalten, wenn das angeforderte Symbol nicht mit der Schriftart geschrieben werden kann. |
| [TextState](../../aspose.pdf.text/textfragment/textstate/) { get; } | Ruft den Textzustand für den Text ab, den das `TextFragment`-Objekt darstellt. |
| override [VerticalAlignment](../../aspose.pdf.text/textfragment/verticalalignment/) { get; set; } | Ruft die vertikale Ausrichtung des Textfragments ab oder legt sie fest. |
| [WrapLinesCount](../../aspose.pdf.text/textfragment/wraplinescount/) { get; set; } | Ruft die Anzahl der umgebrochenen Zeilen für diesen Absatz ab oder legt sie fest (nur für die PDF-Generierung) |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Ruft einen int-Wert ab oder legt ihn fest, der die Z-Reihenfolge des Graphen angibt. Ein Graph mit größerem ZIndex wird über dem Graphen mit kleinerem ZIndex platziert. ZIndex kann negativ sein. Ein Graph mit negativem ZIndex wird hinter dem Text auf der Seite platziert. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Clone](../../aspose.pdf.text/textfragment/clone/)() | Klont das Fragment. |
| virtual [CloneWithSegments](../../aspose.pdf.text/textfragment/clonewithsegments/)() | Klont das Fragment mit allen Segmenten. |
| [IsolateTextSegments](../../aspose.pdf.text/textfragment/isolatetextsegments/)(int, int) | Ruft [`TextSegment`](../textsegment/)(s) ab, die den angegebenen Teil des `TextFragment`-Texts darstellen. |

## Anmerkungen

In wenigen Worten enthält das `TextFragment`-Objekt eine Liste von [`TextSegment`](../textsegment/) Objekten. Im Detail: Der Text des PDF-Dokuments wird in PDF durch zwei grundlegende Objekte dargestellt: `TextFragment` und [`TextSegment`](../textsegment/). Die Unterschiede zwischen ihnen sind größtenteils kontextabhängig. Betrachten wir folgendes Szenario. Der Benutzer sucht nach dem Text "hello world", um damit zu arbeiten, seine Eigenschaften zu ändern, etc.

```csharp
Document doc = new Document(docFile);
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
doc.Pages[1].Accept(absorber);
```

Die physikalische Darstellung des PDF-Texts ist sehr komplex. Der Text "hello world" kann aus mehreren physikalisch unabhängigen Textsegmenten bestehen. Das Aspose.Pdf-Textmodell legt grundsätzlich fest, dass das `TextFragment`-Objekt eine einzige logische Operation über die physikalischen [`TextSegment`](../textsegment/) Objekte bereitstellt, die die Abfrage des Benutzers darstellen. Im Textsuchszenario ist das `TextFragment` die logische Darstellung des Textes "hello world", und die Sammlung der [`TextSegment`](../textsegment/) Objekte stellt alle physikalischen Segmente dar, die das Textobjekt "hello world" konstruieren. Daher ist das `TextFragment` nahe an der logischen Textdarstellung. Und [`TextSegment`](../textsegment/) ist nahe an der physikalischen Textdarstellung. Offensichtlich kann jedes [`TextSegment`](../textsegment/) Objekt seine eigene Schriftart, Farbgebung und Positionierungseigenschaften haben. Das `TextFragment` bietet eine einfache Möglichkeit, den Text mit seinen Eigenschaften zu ändern: Schriftart festlegen, Schriftgröße festlegen, Schriftfarbe festlegen usw. In der Zwischenzeit sind die [`TextSegment`](../textsegment/) Objekte zugänglich und die Benutzer können unabhängig mit den [`TextSegment`](../textsegment/) Objekten arbeiten. Beachten Sie, dass die Änderung der Eigenschaften des TextFragments die innere [`Segments`](./segments/) Sammlung ändern kann, da das TextFragment ein aggregiertes Objekt ist und es interne Segmente neu anordnen oder sie zu einem einzigen Segment zusammenführen kann. Wenn Ihre Anforderung darin besteht, die [`Segments`](./segments/) Sammlung unverändert zu lassen, ändern Sie bitte die inneren Segmente einzeln.

## Beispiele

Das Beispiel zeigt, wie man Text auf der ersten Seite des PDF-Dokuments findet und den Text und seine Schriftart ersetzt.

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

* Klasse [BaseParagraph](../../aspose.pdf/baseparagraph/)
* Namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* Assembly [Aspose.PDF](../../)