---
title: TextFragment
second_title: Aspose.PDF für .NET-API-Referenz
description: Stellt ein Fragment des PDF-Textes dar.
type: docs
weight: 7100
url: /de/net/aspose.pdf.text/textfragment/
---
## TextFragment class

Stellt ein Fragment des PDF-Textes dar.

```csharp
public class TextFragment : BaseParagraph
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [TextFragment](textfragment#constructor)() | Initialisiert eine neue Instanz von[`TextFragment`](../textfragment) Objekt. |
| [TextFragment](textfragment#constructor_2)(string) | erstellt[`TextFragment`](../textfragment) Objekt mit Single[`TextSegment`](../textsegment) Objekt drin. Gibt die Textzeichenfolge innerhalb des Segments an. |
| [TextFragment](textfragment#constructor_1)(TabStops) | Initialisiert eine neue Instanz von[`TextFragment`](../textfragment) Objekt mit vordefinierten[`TabStops`](../tabstops) Positionen. |
| [TextFragment](textfragment#constructor_3)(string, TabStops) | erstellt[`TextFragment`](../textfragment) Objekt mit Single[`TextSegment`](../textsegment) Objekt innerhalb und vordefiniert[`TabStops`](../tabstops) Positionen. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textfragment/baselineposition) { get; set; } | Ruft Textposition für Text ab, dargestellt mit[`TextFragment`](../textfragment) object. Der YIndent der Positionsstruktur stellt die Basiskoordinate des Textfragments dar. |
| [EndNote](../../aspose.pdf.text/textfragment/endnote) { get; set; } | Ruft die Endnote des Absatzes ab oder legt sie fest. (Nur für PDF-Generierung) |
| [FootNote](../../aspose.pdf.text/textfragment/footnote) { get; set; } | Ruft die Fußnote des Absatzes ab oder legt sie fest. (Nur für PDF-Generierung) |
| [Form](../../aspose.pdf.text/textfragment/form) { get; } | Ruft das Formularobjekt ab, das das TextFragment enthält |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragment/horizontalalignment) { get; set; } | Holt oder setzt eine horizontale Ausrichtung des Textfragments. |
| override [Hyperlink](../../aspose.pdf.text/textfragment/hyperlink) { set; } | Setzt das Fragment hyperlink |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn) { get; set; } | Ruft einen Bool-Wert ab oder legt ihn fest, der angibt, ob dieser Absatz in der nächsten Spalte steht. Standard ist „false“.(für PDF-Generierung) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph) { get; set; } | Ruft ab oder legt fest, dass ein Absatz inline ist. Standard ist „false“.(für PDF-Generierung) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage) { get; set; } | Ruft einen Bool-Wert ab oder legt ihn fest, der erzwingt, dass dieser Absatz auf einer neuen Seite generiert wird. Der Standardwert ist falsch. (für die PDF-Generierung) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext) { get; set; } | Ruft einen Bool-Wert ab oder legt ihn fest, der angibt, ob der aktuelle Absatz zusammen mit dem nächsten Absatz auf derselben Seite verbleibt. Der Standardwert ist „false“. (für die PDF-Generierung) |
| [Margin](../../aspose.pdf/baseparagraph/margin) { get; set; } | Liest oder setzt einen Außenrand für Absatz (für PDF-Generierung) |
| [Page](../../aspose.pdf.text/textfragment/page) { get; } | Ruft Seite ab, die das TextFragment enthält |
| [Position](../../aspose.pdf.text/textfragment/position) { get; set; } | Ermittelt oder setzt die Textposition für Text, dargestellt durch[`TextFragment`](../textfragment) Objekt. |
| [Rectangle](../../aspose.pdf.text/textfragment/rectangle) { get; } | Ruft Rechteck des TextFragments ab |
| [ReplaceOptions](../../aspose.pdf.text/textfragment/replaceoptions) { get; } | Ruft Textersetzungsoptionen ab. Die Optionen definieren das Verhalten, wenn Fragmenttext durch kürzeren/langen ersetzt wird. |
| [Segments](../../aspose.pdf.text/textfragment/segments) { get; set; } | Ruft Textsegmente für Strom ab[`TextFragment`](../textfragment) . |
| [Text](../../aspose.pdf.text/textfragment/text) { get; set; } | Holt oder setztString Textobjekt, das die[`TextFragment`](../textfragment) Objekt repräsentiert. |
| [TextState](../../aspose.pdf.text/textfragment/textstate) { get; } | Ermittelt oder setzt den Textstatus für den Text, der[`TextFragment`](../textfragment) Objekt repräsentiert. |
| override [VerticalAlignment](../../aspose.pdf.text/textfragment/verticalalignment) { get; set; } | Holt oder setzt eine vertikale Ausrichtung des Textfragments. |
| [WrapLinesCount](../../aspose.pdf.text/textfragment/wraplinescount) { get; set; } | Ruft die Anzahl der Umbruchzeilen für diesen Absatz ab oder legt sie fest (nur für die PDF-Generierung) |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | Ruft einen int-Wert ab oder legt ihn fest, der die Z-Reihenfolge des Diagramms angibt. Ein Graph mit größerem ZIndex wird über dem Graphen mit kleinerem ZIndex platziert. ZIndex kann negativ sein. Grafik mit negativem ZIndex wird hinter dem Text auf der Seite platziert. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Clone](../../aspose.pdf.text/textfragment/clone)() | Klonen Sie das Fragment. |
| virtual [CloneWithSegments](../../aspose.pdf.text/textfragment/clonewithsegments)() | Klonen Sie das Fragment mit allen Segmenten. |
| [IsolateTextSegments](../../aspose.pdf.text/textfragment/isolatetextsegments)(int, int) | erhält[`TextSegment`](../textsegment) (s) repräsentiert einen bestimmten Teil der[`TextFragment`](../textfragment) text. |

### Bemerkungen

In wenigen Worten,[`TextFragment`](../textfragment) Objekt enthält Liste von[`TextSegment`](../textsegment) Objekte. Im Detail: Text des PDF-Dokuments inPdf wird durch zwei grundlegende Objekte dargestellt:[`TextFragment`](../textfragment) und[`TextSegment`](../textsegment) Die Unterschiede zwischen ihnen sind größtenteils kontextabhängig. Betrachten wir folgendes Szenario. Der Benutzer sucht nach dem Text „Hello World“, um damit zu arbeiten, seine Eigenschaften zu ändern, umzusehen usw. Physikalisch ist die Darstellung von PDF-Texten sehr komplex. Der Text "Hallo Welt" kann aus mehreren physikalisch unabhängigen Textsegmenten bestehen. Das Aspose.Pdf-Textmodell stellt dies grundsätzlich her[`TextFragment`](../textfragment) object bietet eine einzelne logische Operation, die über physisch gesetzt wird[`TextSegment`](../textsegment) Objektsatz, der die Abfrage des Benutzers darstellt. Im Textsuchszenario[`TextFragment`](../textfragment) ist eine logische "Hallo Welt"-Textdarstellung, und[`TextSegment`](../textsegment)Die Objektsammlung stellt alle physischen Segmente dar, die das Textobjekt „Hallo Welt“ bilden. Also,[`TextFragment`](../textfragment) ist der logischen Textdarstellung nahe. Und[`TextSegment`](../textsegment) ist nah an der physischen Textdarstellung. Offensichtlich jeder[`TextSegment`](../textsegment) Objekt kann seine eigene Schriftart, Farbgebung und Positionierungseigenschaften haben. [`TextFragment`](../textfragment) bietet eine einfache Möglichkeit, Text mit seinen Eigenschaften zu ändern: Schriftart festlegen, Schriftgröße festlegen, Schriftfarbe festlegen usw. Inzwischen[`TextSegment`](../textsegment) Objekte sind zugänglich und Benutzer können damit arbeiten[`TextSegment`](../textsegment) Objekte unabhängig. Beachten Sie, dass das Ändern von TextFragment-Eigenschaften innere ändern kann[`Segments`](./segments) Sammlung, da TextFragment ein aggregiertes Objekt ist und interne Segmente neu anordnen oder zu einem einzigen Segment zusammenführen kann. Wenn Sie die verlassen möchten[`Segments`](./segments)Kollektion unverändert, Innensegmente bitte individuell ändern.

```csharp
Document doc = new Document(docFile);
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
doc.Pages[1].Accept(absorber);
```

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

* class [BaseParagraph](../../aspose.pdf/baseparagraph)
* namensraum [Aspose.Pdf.Text](../../aspose.pdf.text)
* Montage [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
