---
title: Class FloatingBox
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.FloatingBox class.
type: docs
weight: 4870
url: /de/net/aspose.pdf/floatingbox/
---
## FloatingBox-Klasse

```csharp
public class FloatingBox : BaseParagraph
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [FloatingBox](floatingbox/#constructor)() | Initialisiert eine neue Instanz der `FloatingBox`-Klasse. |
| [FloatingBox](floatingbox/#constructor_1)(float, float) | Initialisiert eine neue Instanz der `FloatingBox`-Klasse mit angegebenem Breite und Höhe. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BackgroundColor](../../aspose.pdf/floatingbox/backgroundcolor/) { get; set; } | Ruft ein [`Color`](../color/) Objekt ab oder legt es fest, das die Hintergrundfarbe der Floating Box angibt. |
| [BackgroundImage](../../aspose.pdf/floatingbox/backgroundimage/) { get; set; } | Ruft das Hintergrundbild für die Seite ab oder legt es fest (nur für Generator, nicht ausgefüllt beim Lesen des Dokuments). |
| [Border](../../aspose.pdf/floatingbox/border/) { get; set; } | Ruft ein [`BorderInfo`](../borderinfo/) Objekt ab oder legt es fest, das die Randinformationen der Floating Box angibt. |
| [ColumnInfo](../../aspose.pdf/floatingbox/columninfo/) { get; set; } | Ruft eine Spalteninformation ab oder legt sie fest. |
| [Height](../../aspose.pdf/floatingbox/height/) { get; set; } | Ruft einen float-Wert ab oder legt ihn fest, der die Höhe der Floating Box angibt. |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | Ruft eine horizontale Ausrichtung des Absatzes ab oder legt sie fest. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Ruft den Fragment-Hyperlink (für PDF-Generator) ab oder legt ihn fest. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Ruft einen booleschen Wert ab oder legt ihn fest, der angibt, ob dieser Absatz in der nächsten Spalte sein wird. Standard ist false. (für PDF-Generierung) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Ruft ab oder legt fest, ob ein Absatz inline ist. Standard ist false. (für PDF-Generierung) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Ruft einen booleschen Wert ab oder legt ihn fest, der angibt, ob dieser Absatz auf einer neuen Seite generiert werden soll. Standard ist false. (für PDF-Generierung) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Ruft einen booleschen Wert ab oder legt ihn fest, der angibt, ob der aktuelle Absatz auf derselben Seite wie der nächste Absatz bleibt. Standard ist false. (für PDF-Generierung) |
| [IsNeedRepeating](../../aspose.pdf/floatingbox/isneedrepeating/) { get; set; } | Ruft einen booleschen Wert ab oder legt ihn fest, der angibt, ob der Absatz auf der nächsten Seite wiederholt werden muss. Der Standardwert ist false. Das Attribut ist nur gültig, wenn der Absatz selbst und das Objekt, auf das seine ReferenceParagraphID verweist, beide in RepeatingRows enthalten sind. |
| [Left](../../aspose.pdf/floatingbox/left/) { get; set; } | Ruft die linke Koordinate der Tabelle ab oder legt sie fest. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Ruft einen äußeren Rand für den Absatz ab oder legt ihn fest (für PDF-Generierung). |
| [Padding](../../aspose.pdf/floatingbox/padding/) { get; set; } | Ruft ein [`MarginInfo`](../margininfo/) Objekt ab oder legt es fest, das das Padding der Floating Box angibt. |
| [Paragraphs](../../aspose.pdf/floatingbox/paragraphs/) { get; set; } | Ruft eine [`Paragraphs`](./paragraphs/) Sammlung ab oder legt sie fest, die alle Absätze in der Zelle angibt. |
| [PositioningMode](../../aspose.pdf/floatingbox/positioningmode/) { get; set; } | Gibt die Variante zur Bestimmung des Standorts der FloatingBox auf der Seite an. |
| [Top](../../aspose.pdf/floatingbox/top/) { get; set; } | Ruft die obere Koordinate der Tabelle ab oder legt sie fest. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Ruft eine vertikale Ausrichtung des Absatzes ab oder legt sie fest. |
| [Width](../../aspose.pdf/floatingbox/width/) { get; set; } | Ruft einen float-Wert ab oder legt ihn fest, der die Breite der Floating Box angibt. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Ruft einen int-Wert ab oder legt ihn fest, der die Z-Reihenfolge des Graphen angibt. Ein Graph mit größerem ZIndex wird über dem Graphen mit kleinerem ZIndex platziert. ZIndex kann negativ sein. Ein Graph mit negativem ZIndex wird hinter dem Text auf der Seite platziert. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Clone](../../aspose.pdf/floatingbox/clone/)() | Klont ein neues `FloatingBox`-Objekt. Absätze in der Floating Box werden nicht geklont. |

### Siehe auch

* Klasse [BaseParagraph](../baseparagraph/)
* Namespace [Aspose.Pdf](../../aspose.pdf/)
* Assembly [Aspose.PDF](../../)