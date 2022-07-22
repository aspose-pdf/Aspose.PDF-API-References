---
title: Heading
second_title: Aspose.PDF für .NET-API-Referenz
description: steht für Überschrift.
type: docs
weight: 3360
url: /de/net/aspose.pdf/heading/
---
## Heading class

steht für Überschrift.

```csharp
public sealed class Heading : TextFragment
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [Heading](heading)(int) | Initialisiert eine neue Instanz der Cell-Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textfragment/baselineposition) { get; set; } | Ruft Textposition für Text ab, dargestellt mit[`TextFragment`](../../aspose.pdf.text/textfragment) object. Der YIndent der Positionsstruktur stellt die Basiskoordinate des Textfragments dar. |
| [DestinationPage](../../aspose.pdf/heading/destinationpage) { get; set; } | Ruft die Zielseite ab. |
| [EndNote](../../aspose.pdf.text/textfragment/endnote) { get; set; } | Ruft die Endnote des Absatzes ab oder legt sie fest. (Nur für PDF-Generierung) |
| [FootNote](../../aspose.pdf.text/textfragment/footnote) { get; set; } | Ruft die Fußnote des Absatzes ab oder legt sie fest. (Nur für PDF-Generierung) |
| [Form](../../aspose.pdf.text/textfragment/form) { get; } | Ruft das Formularobjekt ab, das das TextFragment enthält |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragment/horizontalalignment) { get; set; } | Holt oder setzt eine horizontale Ausrichtung des Textfragments. |
| override [Hyperlink](../../aspose.pdf.text/textfragment/hyperlink) { set; } | Setzt das Fragment hyperlink |
| [IsAutoSequence](../../aspose.pdf/heading/isautosequence) { get; set; } | Ruft die Überschrift ab, die automatisch nummeriert werden soll. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn) { get; set; } | Ruft einen Bool-Wert ab oder legt ihn fest, der angibt, ob dieser Absatz in der nächsten Spalte steht. Standard ist „false“.(für PDF-Generierung) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph) { get; set; } | Ruft ab oder legt fest, dass ein Absatz inline ist. Standard ist „false“.(für PDF-Generierung) |
| [IsInList](../../aspose.pdf/heading/isinlist) { get; set; } | Ruft die Überschrift ab, die in der Toc-Liste enthalten sein sollte. |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage) { get; set; } | Ruft einen Bool-Wert ab oder legt ihn fest, der erzwingt, dass dieser Absatz auf einer neuen Seite generiert wird. Der Standardwert ist falsch. (für die PDF-Generierung) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext) { get; set; } | Ruft einen Bool-Wert ab oder legt ihn fest, der angibt, ob der aktuelle Absatz zusammen mit dem nächsten Absatz auf derselben Seite verbleibt. Der Standardwert ist „false“. (für die PDF-Generierung) |
| [Level](../../aspose.pdf/heading/level) { get; set; } | Ruft das Level ab. |
| [Margin](../../aspose.pdf/baseparagraph/margin) { get; set; } | Liest oder setzt einen Außenrand für Absatz (für PDF-Generierung) |
| [Page](../../aspose.pdf.text/textfragment/page) { get; } | Ruft Seite ab, die das TextFragment enthält |
| [Position](../../aspose.pdf.text/textfragment/position) { get; set; } | Ermittelt oder setzt die Textposition für Text, dargestellt durch[`TextFragment`](../../aspose.pdf.text/textfragment) Objekt. |
| [Rectangle](../../aspose.pdf.text/textfragment/rectangle) { get; } | Ruft Rechteck des TextFragments ab |
| [ReplaceOptions](../../aspose.pdf.text/textfragment/replaceoptions) { get; } | Ruft Textersetzungsoptionen ab. Die Optionen definieren das Verhalten, wenn Fragmenttext durch kürzeren/langen ersetzt wird. |
| [Segments](../../aspose.pdf.text/textfragment/segments) { get; set; } | Ruft Textsegmente für Strom ab[`TextFragment`](../../aspose.pdf.text/textfragment) . |
| [StartNumber](../../aspose.pdf/heading/startnumber) { get; set; } | Ruft die Startnummer der Überschrift ab. |
| [Style](../../aspose.pdf/heading/style) { get; set; } | Ruft den Stil ab oder legt ihn fest. |
| [Text](../../aspose.pdf.text/textfragment/text) { get; set; } | Holt oder setztString Textobjekt, das die[`TextFragment`](../../aspose.pdf.text/textfragment) Objekt repräsentiert. |
| [TextState](../../aspose.pdf.text/textfragment/textstate) { get; } | Ermittelt oder setzt den Textstatus für den Text, der[`TextFragment`](../../aspose.pdf.text/textfragment) Objekt repräsentiert. |
| [TocPage](../../aspose.pdf/heading/tocpage) { get; set; } | Ruft die Seite ab, die diese Überschrift enthält. |
| [Top](../../aspose.pdf/heading/top) { get; set; } | Ruft das oberste Y dieser Überschriften ab. |
| [UserLabel](../../aspose.pdf/heading/userlabel) { get; set; } | Ruft Benutzerbezeichnung ab oder legt sie fest. |
| override [VerticalAlignment](../../aspose.pdf.text/textfragment/verticalalignment) { get; set; } | Holt oder setzt eine vertikale Ausrichtung des Textfragments. |
| [WrapLinesCount](../../aspose.pdf.text/textfragment/wraplinescount) { get; set; } | Ruft die Anzahl der Umbruchzeilen für diesen Absatz ab oder legt sie fest (nur für die PDF-Generierung) |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | Ruft einen int-Wert ab oder legt ihn fest, der die Z-Reihenfolge des Diagramms angibt. Ein Graph mit größerem ZIndex wird über dem Graphen mit kleinerem ZIndex platziert. ZIndex kann negativ sein. Grafik mit negativem ZIndex wird hinter dem Text auf der Seite platziert. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Clone](../../aspose.pdf/heading/clone)() | Klonen Sie die Überschrift. |
| override [CloneWithSegments](../../aspose.pdf/heading/clonewithsegments)() | Klonen Sie die Überschrift mit allen Segmenten. |
| [IsolateTextSegments](../../aspose.pdf.text/textfragment/isolatetextsegments)(int, int) | erhält[`TextSegment`](../../aspose.pdf.text/textsegment) (s) repräsentiert einen bestimmten Teil der[`TextFragment`](../../aspose.pdf.text/textfragment) text. |

### Siehe auch

* class [TextFragment](../../aspose.pdf.text/textfragment)
* namensraum [Aspose.Pdf](../../aspose.pdf)
* Montage [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
