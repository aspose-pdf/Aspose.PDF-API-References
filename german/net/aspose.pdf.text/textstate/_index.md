---
title: Class TextState
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextState-Klasse. Stellt einen Textzustand eines Textes dar
type: docs
weight: 11070
url: /de/net/aspose.pdf.text/textstate/
---
## TextState-Klasse

Stellt einen Textzustand eines Textes dar

```csharp
public class TextState
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [TextState](textstate/#constructor)() | Erstellt ein Textzustandsobjekt. |
| [TextState](textstate/#constructor_2)(Color) | Erstellt ein Textzustandsobjekt mit Angabe der Vordergrundfarbe. |
| [TextState](textstate/#constructor_1)(double) | Erstellt ein Textzustandsobjekt mit Angabe der Schriftgröße. |
| [TextState](textstate/#constructor_4)(string) | Erstellt ein Textzustandsobjekt mit Angabe der Schriftfamilie. |
| [TextState](textstate/#constructor_3)(Color, double) | Erstellt ein Textzustandsobjekt mit Angabe der Vordergrundfarbe und Schriftgröße. |
| [TextState](textstate/#constructor_6)(string, double) | Erstellt ein Textzustandsobjekt mit Angabe der Schriftfamilie und Schriftgröße. |
| [TextState](textstate/#constructor_5)(string, bool, bool) | Erstellt ein Textzustandsobjekt mit Angabe der Schriftfamilie und Schriftstil. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| virtual [BackgroundColor](../../aspose.pdf.text/textstate/backgroundcolor/) { get; set; } | Legt die Hintergrundfarbe des Textes fest. |
| virtual [CharacterSpacing](../../aspose.pdf.text/textstate/characterspacing/) { get; set; } | Ruft den Zeichenabstand des Textes ab oder legt ihn fest. |
| virtual [CoordinateOrigin](../../aspose.pdf.text/textstate/coordinateorigin/) { get; set; } | Ruft den Text-Koordinatenursprung ab oder legt ihn fest. Wenn der Koordinatenursprung Descender ist, entspricht die Y-Koordinate des Textes dem tiefsten Punkt der Schriftart. Wenn der Koordinatenursprung BaseLine ist, entspricht die Y-Koordinate des Textes der Grundlinie der Schriftart. Der Standardwert ist Descender. Wenn der Abwärtswert der Schriftart zu groß ist, kann der Text höher als andere Schriftarten gerendert werden. In diesem Fall kann der Koordinatenursprung BaseLine für eine bessere Textdarstellung ausgewählt werden. |
| virtual [Font](../../aspose.pdf.text/textstate/font/) { get; set; } | Ruft die Schriftart des Textes ab oder legt sie fest. |
| virtual [FontSize](../../aspose.pdf.text/textstate/fontsize/) { get; set; } | Ruft die Schriftgröße des Textes ab oder legt sie fest. |
| virtual [FontStyle](../../aspose.pdf.text/textstate/fontstyle/) { get; set; } | Legt den Schriftstil des Textes fest. |
| virtual [ForegroundColor](../../aspose.pdf.text/textstate/foregroundcolor/) { get; set; } | Ruft die Vordergrundfarbe des Textes ab oder legt sie fest. |
| virtual [HorizontalAlignment](../../aspose.pdf.text/textstate/horizontalalignment/) { get; set; } | Ruft die horizontale Ausrichtung für den Text ab oder legt sie fest. |
| virtual [HorizontalScaling](../../aspose.pdf.text/textstate/horizontalscaling/) { get; set; } | Ruft die horizontale Skalierung des Textes ab oder legt sie fest. |
| virtual [Invisible](../../aspose.pdf.text/textstate/invisible/) { get; set; } | Ruft die Unsichtbarkeit des Textes ab oder legt sie fest. Dies spiegelt im Wesentlichen den Zustand des [`RenderingMode`](./renderingmode/) wider, mit Ausnahme einiger Sonderfälle (wie Clipping). |
| virtual [LineSpacing](../../aspose.pdf.text/textstate/linespacing/) { get; set; } | Ruft den Zeilenabstand des Textes ab oder legt ihn fest. |
| virtual [RenderingMode](../../aspose.pdf.text/textstate/renderingmode/) { get; set; } | Ruft den Rendermodus des Textes ab oder legt ihn fest. |
| virtual [StrikeOut](../../aspose.pdf.text/textstate/strikeout/) { get; set; } | Ruft den Durchstreichungsstil für den Text ab oder legt ihn fest, dargestellt durch das [`TextSegment`](../textsegment/) Objekt |
| virtual [StrokingColor](../../aspose.pdf.text/textstate/strokingcolor/) { get; set; } | Ruft die Vordergrundfarbe des Textes ab oder legt sie fest. |
| virtual [Subscript](../../aspose.pdf.text/textstate/subscript/) { get; set; } | Ruft den Tiefgestellt-Text des Textes ab oder legt ihn fest. |
| virtual [Superscript](../../aspose.pdf.text/textstate/superscript/) { get; set; } | Ruft den Hochgestellt-Text des Textes ab oder legt ihn fest. |
| virtual [Underline](../../aspose.pdf.text/textstate/underline/) { get; set; } | Ruft den Unterstrich für den Text ab oder legt ihn fest, dargestellt durch das [`TextFragment`](../textfragment/) Objekt |
| virtual [WordSpacing](../../aspose.pdf.text/textstate/wordspacing/) { get; set; } | Ruft den Wortabstand des Textes ab oder legt ihn fest. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [ApplyChangesFrom](../../aspose.pdf.text/textstate/applychangesfrom/)(TextState) | Wendet Einstellungen von einem anderen TextState an. |
| [MeasureHeight](../../aspose.pdf.text/textstate/measureheight/)(char) | Misst die Zeichenhöhe. |
| virtual [MeasureString](../../aspose.pdf.text/textstate/measurestring/)(string) | Misst den String. |

## Felder

| Name | Beschreibung |
| --- | --- |
| readonly [TabstopDefaultValue](../../aspose.pdf.text/textstate/tabstopdefaultvalue/) | Standardwert der Tabulatoren in Breiten des Leerzeichens der Standard-Schriftart. |
| readonly [TabTag](../../aspose.pdf.text/textstate/tabtag/) | Sie können dieses Tag im Text platzieren, um eine Tabulatoren zu deklarieren. |

### Siehe auch

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)