---
title: TextFragmentState
second_title: Aspose.PDF für .NET-API-Referenz
description: Repräsentiert einen Textstatus eines Textfragments.
type: docs
weight: 7130
url: /de/net/aspose.pdf.text/textfragmentstate/
---
## TextFragmentState class

Repräsentiert einen Textstatus eines Textfragments.

```csharp
public sealed class TextFragmentState : TextState
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [TextFragmentState](textfragmentstate)(TextFragment) | Initialisiert eine neue Instanz von[`TextFragmentState`](../textfragmentstate) Objekt mit angegeben[`TextFragment`](../textfragment) Objekt. Dies[`TextFragmentState`](../textfragmentstate) Initialisierung wird nicht unterstützt. TextFragmentState ist nur mit verfügbar[`TextState`](../textfragment/textstate) Eigentum. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| override [BackgroundColor](../../aspose.pdf.text/textfragmentstate/backgroundcolor) { get; set; } | Legt die Hintergrundfarbe des Textes fest, dargestellt durch[`TextFragment`](../textfragment) Objekt |
| override [CharacterSpacing](../../aspose.pdf.text/textfragmentstate/characterspacing) { get; set; } | Ruft den Zeichenabstand des Textes ab oder legt ihn fest, dargestellt durch den[`TextFragment`](../textfragment) Objekt. |
| [DrawTextRectangleBorder](../../aspose.pdf.text/textfragmentstate/drawtextrectangleborder) { get; set; } | Ruft ab oder legt fest, ob ein Flag für gezeichneten Textrechteckrahmen angezeigt wird. |
| override [Font](../../aspose.pdf.text/textfragmentstate/font) { get; set; } | Ruft die Schriftart des Textes ab oder legt sie fest, dargestellt durch die[`TextFragment`](../textfragment) Objekt |
| override [FontSize](../../aspose.pdf.text/textfragmentstate/fontsize) { get; set; } | Ruft die Schriftgröße des Textes ab oder legt sie fest, dargestellt durch die[`TextFragment`](../textfragment) Objekt |
| override [FontStyle](../../aspose.pdf.text/textfragmentstate/fontstyle) { get; set; } | Legt den Schriftstil des Textes fest, der durch dargestellt wird[`TextFragment`](../textfragment) Objekt |
| override [ForegroundColor](../../aspose.pdf.text/textfragmentstate/foregroundcolor) { get; set; } | Ermittelt oder setzt die Vordergrundfarbe des Textes, dargestellt durch die[`TextFragment`](../textfragment) Objekt |
| [FormattingOptions](../../aspose.pdf.text/textfragmentstate/formattingoptions) { get; set; } | Ruft Formatierungsoptionen ab oder legt sie fest. Die Einstellung der Optionen ist nur in Generatorszenarien wirksam. |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragmentstate/horizontalalignment) { get; set; } | Liest oder setzt die horizontale Ausrichtung des Textes. |
| override [HorizontalScaling](../../aspose.pdf.text/textfragmentstate/horizontalscaling) { get; set; } | Holt oder setzt die horizontale Skalierung des Textes, dargestellt durch die[`TextFragment`](../textfragment) Objekt. |
| override [Invisible](../../aspose.pdf.text/textfragmentstate/invisible) { get; set; } | Holt oder setzt die Unsichtbarkeit des Textes. |
| override [LineSpacing](../../aspose.pdf.text/textfragmentstate/linespacing) { get; set; } | Liest oder setzt den Zeilenabstand des Textes. |
| override [RenderingMode](../../aspose.pdf.text/textfragmentstate/renderingmode) { get; set; } | Ruft den Darstellungsmodus des Textes ab oder legt ihn fest. |
| [Rotation](../../aspose.pdf.text/textfragmentstate/rotation) { get; set; } | Ermittelt oder setzt den Rotationswinkel in Grad. |
| override [StrikeOut](../../aspose.pdf.text/textfragmentstate/strikeout) { set; } | Legt das Durchstreichen für den Text fest, der durch dargestellt wird[`TextFragment`](../textfragment) Objekt |
| override [StrokingColor](../../aspose.pdf.text/textfragmentstate/strokingcolor) { get; set; } | Holt oder setzt Farbstreichoperationen von[`TextFragment`](../textfragment) Rendering (Strichtext, rechteckiger Rand) |
| override [Subscript](../../aspose.pdf.text/textfragmentstate/subscript) { get; set; } | Ruft den Index des Textes ab oder legt ihn fest, dargestellt durch den[`TextFragment`](../textfragment) Objekt. |
| override [Superscript](../../aspose.pdf.text/textfragmentstate/superscript) { get; set; } | Ruft den hochgestellten Text ab oder legt ihn fest, dargestellt durch den[`TextFragment`](../textfragment) Objekt. |
| [TabStops](../../aspose.pdf.text/textfragmentstate/tabstops) { get; } | Ruft Tabstopps für den Text ab. |
| override [Underline](../../aspose.pdf.text/textfragmentstate/underline) { get; set; } | Holt oder setzt Unterstreichungen für den Text, dargestellt durch die[`TextFragment`](../textfragment) Objekt |
| override [WordSpacing](../../aspose.pdf.text/textfragmentstate/wordspacing) { get; set; } | Ruft den Wortabstand des Textes ab oder setzt ihn. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [ApplyChangesFrom](../../aspose.pdf.text/textfragmentstate/applychangesfrom)(TextState) | Wendet Einstellungen von einem anderen TextState an. |
| override [MeasureString](../../aspose.pdf.text/textfragmentstate/measurestring)(string) | Misst die Zeichenfolge. |

## Felder

| Name | Beschreibung |
| --- | --- |
| readonly [TabstopDefaultValue](../../aspose.pdf.text/textstate/tabstopdefaultvalue) | Standardwert der Tabellierung in Breiten von Leerzeichen der Standardschriftart. |
| readonly [TabTag](../../aspose.pdf.text/textstate/tabtag) | Sie können dieses Tag in Text einfügen, um eine Tabellierung zu deklarieren. |

### Bemerkungen

Bietet eine Möglichkeit, die folgenden Eigenschaften des Textes zu ändern: Schriftart ([`Font`](./font) Eigenschaft) Schriftgröße ([`FontSize`](./fontsize) Eigenschaft) Schriftstil ([`FontStyle`](./fontstyle) Eigenschaft) Vordergrundfarbe ([`ForegroundColor`](./foregroundcolor) Eigenschaft) Hintergrundfarbe ([`BackgroundColor`](./backgroundcolor) Eigenschaft) Beachten Sie, dass sich ändern[`TextFragmentState`](../textfragmentstate) Eigenschaften können sich innerlich ändern[`Segments`](../textfragment/segments) Sammlung, da TextFragment ein aggregiertes Objekt ist und interne Segmente neu anordnen oder zu einem einzigen Segment zusammenführen kann. Wenn Sie die verlassen möchten[`Segments`](../textfragment/segments) Kollektion unverändert, Innensegmente bitte individuell ändern.

### Beispiele

Das Beispiel demonstriert, wie man Textfarbe und Schriftgröße des Textes mit ändert[`TextState`](../textstate) Objekt.

```csharp
// Dokument öffnen
Document doc = new Document(@"D:\Tests\input.pdf");

// TextFragmentAbsorber-Objekt erstellen, um alle "Hello World"-Textvorkommen zu finden
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Akzeptiere den Absorber für die erste Seite
doc.Pages[1].Accept(absorber);

// Vordergrundfarbe des ersten Textvorkommens ändern
absorber.TextFragments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);
// Schriftgröße des ersten Textvorkommens ändern
absorber.TextFragments[1].TextState.FontSize = 15;

// Dokument speichern
doc.Save(@"D:\Tests\output.pdf");  
```

### Siehe auch

* class [TextFragmentAbsorber](../textfragmentabsorber)
* class [Document](../../aspose.pdf/document)
* class [TextState](../textstate)
* namensraum [Aspose.Pdf.Text](../../aspose.pdf.text)
* Montage [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
