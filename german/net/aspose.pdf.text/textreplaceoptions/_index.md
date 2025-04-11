---
title: Class TextReplaceOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextReplaceOptions-Klasse. Stellt Textersetzungsoptionen dar
type: docs
weight: 11010
url: /de/net/aspose.pdf.text/textreplaceoptions/
---
## TextReplaceOptions-Klasse

Stellt Textersetzungsoptionen dar

```csharp
public sealed class TextReplaceOptions : TextOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [TextReplaceOptions](textreplaceoptions/#constructor)(ReplaceAdjustment) | Initialisiert eine neue Instanz des `TextReplaceOptions`-Objekts für die angegebene Aktion nach der Ersetzung. |
| [TextReplaceOptions](textreplaceoptions/#constructor_1)(Scope) | Initialisiert eine neue Instanz des `TextReplaceOptions`-Objekts für den angegebenen Geltungsbereich. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AdjustmentNewLineSpacing](../../aspose.pdf.text/textreplaceoptions/adjustmentnewlinespacing/) { get; set; } | Ruft den Wert des Zeilenabstands ab oder legt ihn fest, der verwendet wird, wenn die Ersetzungsanpassung gezwungen wird, eine neue Textzeile zu erstellen. Der erwartete Wert ist ein Vielfaches der Schriftgröße des ersetzten Textes. Standard ist 1,2. |
| [IgnoreParagraphs](../../aspose.pdf.text/textreplaceoptions/ignoreparagraphs/) { get; set; } | Ruft einen Wert ab oder legt ihn fest, der angibt, ob unterschiedliche Absätze bei der Anpassung des Textes auf der Seite nach der Textersetzung ignoriert werden sollen. |
| [LeftAdjustment](../../aspose.pdf.text/textreplaceoptions/leftadjustment/) { get; set; } | Legt die linke Positionsanpassung für den ersetzten Text fest oder ruft sie ab, wenn TextReplaceOptions verwendet wird: - ReplaceAdjustmentAction = IsFormFillingMode; |
| [ReplaceAdjustmentAction](../../aspose.pdf.text/textreplaceoptions/replaceadjustmentaction/) { get; set; } | Ruft eine Aktion ab oder legt sie fest, die nach der Ersetzung des Textfragmentes durch einen kürzeren ausgeführt wird. |
| [ReplaceScope](../../aspose.pdf.text/textreplaceoptions/replacescope/) { get; set; } | Ruft den Geltungsbereich ab oder legt ihn fest, in dem die Textersetzungsoperation angewendet wird. |
| [RightAdjustment](../../aspose.pdf.text/textreplaceoptions/rightadjustment/) { get; set; } | Legt die rechte Positionsanpassung für den ersetzten Text fest oder ruft sie ab, wenn TextReplaceOptions verwendet wird: - ReplaceAdjustmentAction = WholeWordsHyphenation; - ReplaceAdjustmentAction = IsFormFillingMode; |

### Siehe auch

* Klasse [TextOptions](../textoptions/)
* Namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* Assembly [Aspose.PDF](../../)