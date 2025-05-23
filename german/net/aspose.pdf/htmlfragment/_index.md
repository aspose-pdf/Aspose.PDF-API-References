---
title: Class HtmlFragment
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.HtmlFragment-Klasse. Stellt einen HTML-Fragment dar
type: docs
weight: 5520
url: /de/net/aspose.pdf/htmlfragment/
---
## HtmlFragment-Klasse

Stellt einen HTML-Fragment dar.

```csharp
public sealed class HtmlFragment : FormattedFragment
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [HtmlFragment](htmlfragment/)(string) | Initialisiert eine neue Instanz der HtmlFragment-Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | Ruft die horizontale Ausrichtung des Absatzes ab oder legt sie fest |
| [HtmlLoadOptions](../../aspose.pdf/htmlfragment/htmlloadoptions/) { get; set; } | Ruft die HtmlLoadOptions ab oder legt sie fest, die zum Laden (und Rendern) von HTML in dieser Instanz der Klasse verwendet werden. Bitte verwenden Sie es, wenn es notwendig ist, spezifische Einstellungen für den Import von HTML für diese oder jene Instanz zu verwenden (z.B. wenn diese oder jene Instanz einen spezifischen BasePath für importiertes HTML verwenden oder einen spezifischen Loader für externe Ressourcen verwenden sollte). Wenn der Parameter standardmäßig (null) ist, werden die standardmäßigen HTML-Ladeoptionen verwendet. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Ruft den Fragment-Hyperlink (für PDF-Generator) ab oder legt ihn fest. |
| [IsBreakWords](../../aspose.pdf/htmlfragment/isbreakwords/) { get; set; } | Ruft den Wortumbruch ab oder legt ihn fest |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Ruft einen booleschen Wert ab oder legt ihn fest, der angibt, ob dieser Absatz in der nächsten Spalte sein wird. Standard ist false. (für PDF-Generierung) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Ruft ab oder legt fest, ob ein Absatz inline ist. Standard ist false. (für PDF-Generierung) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Ruft einen booleschen Wert ab oder legt ihn fest, der erzwingt, dass dieser Absatz auf einer neuen Seite generiert wird. Standard ist false. (für PDF-Generierung) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Ruft einen booleschen Wert ab oder legt ihn fest, der angibt, ob der aktuelle Absatz auf derselben Seite wie der nächste Absatz bleibt. Standard ist false. (für PDF-Generierung) |
| [IsParagraphHasMargin](../../aspose.pdf/htmlfragment/isparagraphhasmargin/) { get; set; } | Ruft ab oder legt fest, ob der Absatz einen Standardabstand hat, andernfalls ist der Abstand 0 |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Ruft einen äußeren Abstand für den Absatz ab oder legt ihn fest (für PDF-Generierung) |
| [Rectangle](../../aspose.pdf/htmlfragment/rectangle/) { get; } | Ruft das Rechteck des HtmlFragment ab |
| [TextState](../../aspose.pdf/htmlfragment/textstate/) { get; set; } | Ruft die Schriftart ab oder legt sie fest |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Ruft die vertikale Ausrichtung des Absatzes ab oder legt sie fest |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Ruft einen int-Wert ab oder legt ihn fest, der die Z-Reihenfolge des Graphen angibt. Ein Graph mit größerem ZIndex wird über dem Graphen mit kleinerem ZIndex platziert. ZIndex kann negativ sein. Ein Graph mit negativem ZIndex wird hinter dem Text auf der Seite platziert. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Clone](../../aspose.pdf/htmlfragment/clone/)() | Klont den HTML-Fragment. |

### Siehe auch

* Klasse [FormattedFragment](../formattedfragment/)
* Namespace [Aspose.Pdf](../../aspose.pdf/)
* Assembly [Aspose.PDF](../../)