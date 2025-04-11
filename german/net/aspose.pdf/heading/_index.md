---
title: Class Heading
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Heading-Klasse. Stellt eine Überschrift dar
type: docs
weight: 5470
url: /de/net/aspose.pdf/heading/
---
## Überschrift-Klasse

Stellt eine Überschrift dar.

```csharp
public sealed class Heading : TextFragment
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Heading](heading/)(int) | Initialisiert eine neue Instanz der Cell-Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textfragment/baselineposition/) { get; set; } | Gibt die Textposition für den Text zurück, dargestellt mit dem [`TextFragment`](../../aspose.pdf.text/textfragment/) Objekt. Der YIndent der Positionsstruktur stellt die Baseline-Koordinate des Textfragments dar. |
| [DestinationPage](../../aspose.pdf/heading/destinationpage/) { get; set; } | Gibt die Zielseite zurück. |
| [EndNote](../../aspose.pdf.text/textfragment/endnote/) { get; set; } | Gibt die Fußnote des Absatzes zurück oder setzt sie. (nur für die PDF-Generierung) |
| [FootNote](../../aspose.pdf.text/textfragment/footnote/) { get; set; } | Gibt die Fußnote des Absatzes zurück oder setzt sie. (nur für die PDF-Generierung) |
| [Form](../../aspose.pdf.text/textfragment/form/) { get; } | Gibt das Formularobjekt zurück, das das TextFragment enthält |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragment/horizontalalignment/) { get; set; } | Gibt die horizontale Ausrichtung des Textfragments zurück oder setzt sie. |
| override [Hyperlink](../../aspose.pdf.text/textfragment/hyperlink/) { set; } | Setzt den Hyperlink des Fragments |
| [IsAutoSequence](../../aspose.pdf/heading/isautosequence/) { get; set; } | Gibt an, ob die Überschrift automatisch nummeriert werden soll. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Gibt einen booleschen Wert zurück oder setzt ihn, der angibt, ob dieser Absatz in der nächsten Spalte sein wird. Standard ist false. (für die PDF-Generierung) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Gibt zurück oder setzt, ob ein Absatz inline ist. Standard ist false. (für die PDF-Generierung) |
| [IsInList](../../aspose.pdf/heading/isinlist/) { get; set; } | Gibt an, ob die Überschrift in der Inhaltsverzeichnis-Liste sein soll. |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Gibt einen booleschen Wert zurück oder setzt ihn, der angibt, dass dieser Absatz auf einer neuen Seite generiert werden soll. Standard ist false. (für die PDF-Generierung) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Gibt einen booleschen Wert zurück oder setzt ihn, der angibt, ob der aktuelle Absatz auf derselben Seite wie der nächste Absatz bleibt. Standard ist false. (für die PDF-Generierung) |
| [Level](../../aspose.pdf/heading/level/) { get; set; } | Gibt die Ebene zurück. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Gibt den äußeren Rand für den Absatz zurück oder setzt ihn (für die PDF-Generierung) |
| [Page](../../aspose.pdf.text/textfragment/page/) { get; } | Gibt die Seite zurück, die das TextFragment enthält |
| [Position](../../aspose.pdf.text/textfragment/position/) { get; set; } | Gibt die Textposition für den Text zurück oder setzt sie, dargestellt mit dem [`TextFragment`](../../aspose.pdf.text/textfragment/) Objekt. |
| [Rectangle](../../aspose.pdf.text/textfragment/rectangle/) { get; } | Gibt das Rechteck des TextFragments zurück |
| [ReplaceOptions](../../aspose.pdf.text/textfragment/replaceoptions/) { get; } | Gibt die Textersetzungsoptionen zurück. Die Optionen definieren das Verhalten, wenn der Fragmenttext durch einen kürzeren/längeren Text ersetzt wird. |
| [Segments](../../aspose.pdf.text/textfragment/segments/) { get; set; } | Gibt die Textsegmente für das aktuelle [`TextFragment`](../../aspose.pdf.text/textfragment/) zurück. |
| [StartNumber](../../aspose.pdf/heading/startnumber/) { get; set; } | Gibt die Startnummer der Überschrift zurück. |
| [Style](../../aspose.pdf/heading/style/) { get; set; } | Gibt den Stil zurück oder setzt ihn. |
| [Text](../../aspose.pdf.text/textfragment/text/) { get; set; } | Gibt das String-Textobjekt zurück oder setzt es, das das [`TextFragment`](../../aspose.pdf.text/textfragment/) Objekt darstellt. |
| [TextEditOptions](../../aspose.pdf.text/textfragment/texteditoptions/) { get; set; } | Gibt die Textbearbeitungsoptionen zurück oder setzt sie. Die Optionen definieren ein spezielles Verhalten, wenn das angeforderte Symbol nicht mit der Schriftart geschrieben werden kann. |
| [TextState](../../aspose.pdf.text/textfragment/textstate/) { get; } | Gibt den Textzustand für den Text zurück, den das [`TextFragment`](../../aspose.pdf.text/textfragment/) Objekt darstellt. |
| [TocPage](../../aspose.pdf/heading/tocpage/) { get; set; } | Gibt die Seite zurück, die diese Überschrift enthält. |
| [Top](../../aspose.pdf/heading/top/) { get; set; } | Gibt die obere Y-Position dieser Überschrift zurück. |
| [UserLabel](../../aspose.pdf/heading/userlabel/) { get; set; } | Gibt das Benutzerlabel zurück oder setzt es. |
| override [VerticalAlignment](../../aspose.pdf.text/textfragment/verticalalignment/) { get; set; } | Gibt die vertikale Ausrichtung des Textfragments zurück oder setzt sie. |
| [WrapLinesCount](../../aspose.pdf.text/textfragment/wraplinescount/) { get; set; } | Gibt die Anzahl der Zeilenumbrüche für diesen Absatz zurück oder setzt sie (nur für die PDF-Generierung) |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Gibt einen int-Wert zurück oder setzt ihn, der die Z-Reihenfolge des Graphen angibt. Ein Graph mit größerem ZIndex wird über dem Graphen mit kleinerem ZIndex platziert. ZIndex kann negativ sein. Ein Graph mit negativem ZIndex wird hinter dem Text auf der Seite platziert. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Clone](../../aspose.pdf/heading/clone/)() | Klont die Überschrift. |
| override [CloneWithSegments](../../aspose.pdf/heading/clonewithsegments/)() | Klont die Überschrift mit allen Segmenten. |
| [IsolateTextSegments](../../aspose.pdf.text/textfragment/isolatetextsegments/)(int, int) | Gibt [`TextSegment`](../../aspose.pdf.text/textsegment/)(s) zurück, die den angegebenen Teil des [`TextFragment`](../../aspose.pdf.text/textfragment/) Textes darstellen. |

### Siehe auch

* Klasse [TextFragment](../../aspose.pdf.text/textfragment/)
* Namespace [Aspose.Pdf](../../aspose.pdf/)
* Assembly [Aspose.PDF](../../)