---
title: "Klass TextReplaceOptions"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Text.TextReplaceOptions-klass. Representerar alternativ för textersättning"
type: docs
weight: 11190
url: /sv/net/aspose.pdf.text/textreplaceoptions/
---
## TextReplaceOptions class

Representerar alternativ för textersättning

```csharp
public sealed class TextReplaceOptions : TextOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [TextReplaceOptions](textreplaceoptions/#constructor)(ReplaceAdjustment) | Initierar en ny instans av `TextReplaceOptions`-objektet för den angivna åtgärden efter ersättning. |
| [TextReplaceOptions](textreplaceoptions/#constructor_1)(Scope) | Initierar en ny instans av `TextReplaceOptions`-objektet för det angivna omfånget. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AdjustmentNewLineSpacing](../../aspose.pdf.text/textreplaceoptions/adjustmentnewlinespacing/) { get; set; } | Hämtar eller anger värdet för radavstånd som används om ersättningsjustering tvingas skapa en ny textrad. Det förväntade värdet är en multiplikator av teckensnittsstorleken för den ersatta texten. Standard är 1,2. |
| [FontSizeAdjustmentAction](../../aspose.pdf.text/textreplaceoptions/fontsizeadjustmentaction/) { get; set; } | Hämtar eller anger policyn för att justera teckensnittsstorleken så att den passar inom gränserna som definieras av [`Rectangle`](./rectangle/). |
| [IgnoreParagraphs](../../aspose.pdf.text/textreplaceoptions/ignoreparagraphs/) { get; set; } | Hämtar eller anger ett värde som indikerar om separata stycken ska ignoreras när text justeras på sidan efter textersättning. |
| [LeftAdjustment](../../aspose.pdf.text/textreplaceoptions/leftadjustment/) { get; set; } | Anger eller hämtar justering av vänster position för ersatt text när TextReplaceOptions används: - ReplaceAdjustmentAction = IsFormFillingMode; |
| [Rectangle](../../aspose.pdf.text/textreplaceoptions/rectangle/) { get; set; } | Hämtar eller anger rectangle för att anpassa texten efter ersättning. |
| [ReplaceAdjustmentAction](../../aspose.pdf.text/textreplaceoptions/replaceadjustmentaction/) { get; set; } | Hämtar eller anger en åtgärd som ska utföras efter ersättning av textfragment till kortare. |
| [ReplaceScope](../../aspose.pdf.text/textreplaceoptions/replacescope/) { get; set; } | Hämtar eller anger ett omfång där textersättningsoperationen tillämpas |
| [RightAdjustment](../../aspose.pdf.text/textreplaceoptions/rightadjustment/) { get; set; } | Anger eller hämtar justering av höger position för ersatt text när TextReplaceOptions används: - ReplaceAdjustmentAction = WholeWordsHyphenation; - ReplaceAdjustmentAction = IsFormFillingMode; |

### Se även

* class [TextOptions](../textoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


