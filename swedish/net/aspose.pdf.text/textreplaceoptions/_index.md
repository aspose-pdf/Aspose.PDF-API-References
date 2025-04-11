---
title: Class TextReplaceOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextReplaceOptions klass. Representerar alternativ för textbyte
type: docs
weight: 11010
url: /sv/net/aspose.pdf.text/textreplaceoptions/
---
## TextReplaceOptions klass

Representerar alternativ för textbyte

```csharp
public sealed class TextReplaceOptions : TextOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [TextReplaceOptions](textreplaceoptions/#constructor)(ReplaceAdjustment) | Initierar en ny instans av `TextReplaceOptions`-objektet för den angivna åtgärden efter byte. |
| [TextReplaceOptions](textreplaceoptions/#constructor_1)(Scope) | Initierar en ny instans av `TextReplaceOptions`-objektet för den angivna omfattningen. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AdjustmentNewLineSpacing](../../aspose.pdf.text/textreplaceoptions/adjustmentnewlinespacing/) { get; set; } | Hämtar eller ställer in värdet för radavstånd som används om bytejustering tvingas att skapa en ny rad text. Det förväntade värdet är en multiplikator av teckenstorleken för den ersatta texten. Standard är 1.2. |
| [IgnoreParagraphs](../../aspose.pdf.text/textreplaceoptions/ignoreparagraphs/) { get; set; } | Hämtar eller ställer in ett värde som indikerar om distinkta stycken ska ignoreras när texten justeras på sidan efter textbyte. |
| [LeftAdjustment](../../aspose.pdf.text/textreplaceoptions/leftadjustment/) { get; set; } | Ställer in eller hämtar vänster positionsjustering för ersatt text när TextReplaceOptions används: - ReplaceAdjustmentAction = IsFormFillingMode; |
| [ReplaceAdjustmentAction](../../aspose.pdf.text/textreplaceoptions/replaceadjustmentaction/) { get; set; } | Hämtar eller ställer in en åtgärd som kommer att utföras efter byte av textfragment till mer kort. |
| [ReplaceScope](../../aspose.pdf.text/textreplaceoptions/replacescope/) { get; set; } | Hämtar eller ställer in en omfattning där textbyteoperationen tillämpas |
| [RightAdjustment](../../aspose.pdf.text/textreplaceoptions/rightadjustment/) { get; set; } | Ställer in eller hämtar höger positionsjustering för ersatt text när TextReplaceOptions används: - ReplaceAdjustmentAction = WholeWordsHyphenation; - ReplaceAdjustmentAction = IsFormFillingMode; |

### Se Även

* klass [TextOptions](../textoptions/)
* namnrymd [Aspose.Pdf.Text](../../aspose.pdf.text/)
* samling [Aspose.PDF](../../)