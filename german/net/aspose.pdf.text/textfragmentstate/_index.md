---
title: Class TextFragmentState
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextFragmentState-Klasse. Stellt einen Textzustand eines Textfragmentes dar
type: docs
weight: 10970
url: /de/net/aspose.pdf.text/textfragmentstate/
---
## TextFragmentState-Klasse

Stellt einen Textzustand eines Textfragmentes dar.

```csharp
public sealed class TextFragmentState : TextState
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [TextFragmentState](textfragmentstate/)(TextFragment) | Initialisiert eine neue Instanz des `TextFragmentState`-Objekts mit dem angegebenen [`TextFragment`](../textfragment/) Objekt. Diese `TextFragmentState`-Initialisierung wird nicht unterstützt. TextFragmentState ist nur mit der [`TextState`](../textfragment/textstate/) Eigenschaft verfügbar. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| override [BackgroundColor](../../aspose.pdf.text/textfragmentstate/backgroundcolor/) { get; set; } | Setzt die Hintergrundfarbe des Textes, dargestellt durch das [`TextFragment`](../textfragment/) Objekt |
| override [CharacterSpacing](../../aspose.pdf.text/textfragmentstate/characterspacing/) { get; set; } | Ruft den Zeichenabstand des Textes ab oder setzt ihn, dargestellt durch das [`TextFragment`](../textfragment/) Objekt. |
| override [CoordinateOrigin](../../aspose.pdf.text/textfragmentstate/coordinateorigin/) { get; set; } | Ruft den Text CoordinateOrigin ab oder setzt ihn. Wenn CoordinateOrigin Descender ist, entspricht die Y-Koordinate des Textes dem tiefsten Punkt der Schriftart. Wenn CoordinateOrigin BaseLine ist, entspricht die Y-Koordinate des Textes der Grundlinie der Schriftart. Der Standardwert ist Descender. Wenn der Abstieg der Schriftart zu groß ist, kann der Text höher als andere Schriftarten gerendert werden. In diesem Fall kann CoordinateOrigin BaseLine für eine bessere Textdarstellung ausgewählt werden. |
| [DrawTextRectangleBorder](../../aspose.pdf.text/textfragmentstate/drawtextrectangleborder/) { get; set; } | Ruft ab oder setzt, ob der Textrechteckrand gezeichnet wird. |
| override [Font](../../aspose.pdf.text/textfragmentstate/font/) { get; set; } | Ruft die Schriftart des Textes ab oder setzt sie, dargestellt durch das [`TextFragment`](../textfragment/) Objekt |
| override [FontSize](../../aspose.pdf.text/textfragmentstate/fontsize/) { get; set; } | Ruft die Schriftgröße des Textes ab oder setzt sie, dargestellt durch das [`TextFragment`](../textfragment/) Objekt |
| override [FontStyle](../../aspose.pdf.text/textfragmentstate/fontstyle/) { get; set; } | Setzt den Schriftstil des Textes, dargestellt durch das [`TextFragment`](../textfragment/) Objekt |
| override [ForegroundColor](../../aspose.pdf.text/textfragmentstate/foregroundcolor/) { get; set; } | Ruft die Vordergrundfarbe des Textes ab oder setzt sie, dargestellt durch das [`TextFragment`](../textfragment/) Objekt |
| [FormattingOptions](../../aspose.pdf.text/textfragmentstate/formattingoptions/) { get; set; } | Ruft die Formatierungsoptionen ab oder setzt sie. Die Einstellung der Optionen ist nur in Generator-Szenarien wirksam. |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragmentstate/horizontalalignment/) { get; set; } | Ruft die horizontale Ausrichtung für den Text ab oder setzt sie. |
| override [HorizontalScaling](../../aspose.pdf.text/textfragmentstate/horizontalscaling/) { get; set; } | Ruft das horizontale Skalieren des Textes ab oder setzt es, dargestellt durch das [`TextFragment`](../textfragment/) Objekt. |
| override [Invisible](../../aspose.pdf.text/textfragmentstate/invisible/) { get; set; } | Ruft die Unsichtbarkeit des Textes ab oder setzt sie. |
| override [LineSpacing](../../aspose.pdf.text/textfragmentstate/linespacing/) { get; set; } | Ruft den Zeilenabstand des Textes ab oder setzt ihn. |
| override [RenderingMode](../../aspose.pdf.text/textfragmentstate/renderingmode/) { get; set; } | Ruft den Rendering-Modus des Textes ab oder setzt ihn. |
| [Rotation](../../aspose.pdf.text/textfragmentstate/rotation/) { get; set; } | Ruft den Rotationswinkel in Grad ab oder setzt ihn. |
| override [StrikeOut](../../aspose.pdf.text/textfragmentstate/strikeout/) { get; set; } | Ruft den Durchstreichungsstil für den Text ab oder setzt ihn, dargestellt durch das [`TextFragment`](../textfragment/) Objekt |
| override [StrokingColor](../../aspose.pdf.text/textfragmentstate/strokingcolor/) { get; set; } | Ruft die Farbe der Strichoperationen des [`TextFragment`](../textfragment/) Renderings ab oder setzt sie (Strichtext, Rechteckrand) |
| override [Subscript](../../aspose.pdf.text/textfragmentstate/subscript/) { get; set; } | Ruft den Tiefgestellt-Text des Textes ab oder setzt ihn, dargestellt durch das [`TextFragment`](../textfragment/) Objekt. |
| override [Superscript](../../aspose.pdf.text/textfragmentstate/superscript/) { get; set; } | Ruft den Hochgestellt-Text des Textes ab oder setzt ihn, dargestellt durch das [`TextFragment`](../textfragment/) Objekt. |
| [TabStops](../../aspose.pdf.text/textfragmentstate/tabstops/) { get; } | Ruft die Tabstopps für den Text ab. |
| override [Underline](../../aspose.pdf.text/textfragmentstate/underline/) { get; set; } | Ruft den Unterstrich für den Text ab oder setzt ihn, dargestellt durch das [`TextFragment`](../textfragment/) Objekt |
| override [WordSpacing](../../aspose.pdf.text/textfragmentstate/wordspacing/) { get; set; } | Ruft den Wortabstand des Textes ab oder setzt ihn. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [ApplyChangesFrom](../../aspose.pdf.text/textfragmentstate/applychangesfrom/)(TextState) | Wendet Einstellungen von einem anderen TextState an. |
| [IsFitRectangle](../../aspose.pdf.text/textfragmentstate/isfitrectangle/)(string, Rectangle) | Überprüft, ob der Eingabestring innerhalb des definierten Rechtecks platziert werden kann. |
| [MeasureHeight](../../aspose.pdf.text/textfragmentstate/measureheight/#measureheight)(char) | Misst die Höhe des Zeichens. (2 Methoden) |
| override [MeasureString](../../aspose.pdf.text/textfragmentstate/measurestring/)(string) | Misst den String. |

## Felder

| Name | Beschreibung |
| --- | --- |
| readonly [TabstopDefaultValue](../../aspose.pdf.text/textstate/tabstopdefaultvalue/) | Standardwert der Tabulatoren in Breiten des Leerzeichens der Standard-Schriftart. |
| readonly [TabTag](../../aspose.pdf.text/textstate/tabtag/) | Sie können dieses Tag im Text platzieren, um eine Tabulatoren zu deklarieren. |

## Bemerkungen

Bietet eine Möglichkeit, folgende Eigenschaften des Textes zu ändern: Schriftart ([`Font`](./font/) Eigenschaft) Schriftgröße ([`FontSize`](./fontsize/) Eigenschaft) Schriftstil ([`FontStyle`](./fontstyle/) Eigenschaft) Vordergrundfarbe ([`ForegroundColor`](./foregroundcolor/) Eigenschaft) Hintergrundfarbe ([`BackgroundColor`](./backgroundcolor/) Eigenschaft) Beachten Sie, dass das Ändern der `TextFragmentState`-Eigenschaften die innere [`Segments`](../textfragment/segments/) Sammlung ändern kann, da TextFragment ein aggregiertes Objekt ist und es interne Segmente neu anordnen oder sie in ein einzelnes Segment zusammenführen kann. Wenn Ihr Bedarf darin besteht, die [`Segments`](../textfragment/segments/) Sammlung unverändert zu lassen, ändern Sie bitte die inneren Segmente einzeln.

## Beispiele

Das Beispiel zeigt, wie man die Textfarbe und die Schriftgröße des Textes mit dem [`TextState`](../textstate/) Objekt ändert.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change foreground color of the first text occurrence
absorber.TextFragments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);
// Change font size of the first text occurrence
absorber.TextFragments[1].TextState.FontSize = 15;

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### Siehe auch

* Klasse [TextFragmentAbsorber](../textfragmentabsorber/)
* Klasse [Document](../../aspose.pdf/document/)
* Klasse [TextState](../textstate/)
* Namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* Assembly [Aspose.PDF](../../)