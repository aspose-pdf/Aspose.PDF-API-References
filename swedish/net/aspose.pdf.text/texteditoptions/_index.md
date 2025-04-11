---
title: Class TextEditOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextEditOptions klass. Beskriver alternativ för textredigeringsoperationer
type: docs
weight: 10820
url: /sv/net/aspose.pdf.text/texteditoptions/
---
## TextEditOptions klass

Beskriver alternativ för textredigeringsoperationer.

```csharp
public sealed class TextEditOptions : TextOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [TextEditOptions](texteditoptions/#constructor)(bool) | Initierar en ny instans av `TextEditOptions`-objektet för den angivna språktransformationstillståndet. |
| [TextEditOptions](texteditoptions/#constructor_1)(FontReplace) | Initierar en ny instans av `TextEditOptions`-objektet för den angivna teckensnittsersättningsbeteendemodellen. |
| [TextEditOptions](texteditoptions/#constructor_2)(LanguageTransformation) | Initierar en ny instans av `TextEditOptions`-objektet för den angivna språktransformationbeteendemodellen. |
| [TextEditOptions](texteditoptions/#constructor_3)(NoCharacterAction) | Initierar en ny instans av `TextEditOptions`-objektet för den angivna ingen-teckenbeteendemodellen. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AllowLanguageTransformation](../../aspose.pdf.text/texteditoptions/allowlanguagetransformation/) { get; set; } | Hämtar eller ställer in värde som tillåter användning av språktransformation vid tillägg eller redigering av text. true - språktransformation kommer att tillämpas om det behövs (standardvärde). false - språktransformation kommer INTE att tillämpas. |
| [ClippingPathsProcessing](../../aspose.pdf.text/texteditoptions/clippingpathsprocessing/) { get; set; } | Hämtar läget för bearbetning av klippväg för den redigerade texten. |
| [FontReplaceBehavior](../../aspose.pdf.text/texteditoptions/fontreplacebehavior/) { get; set; } | Hämtar läget som definierar beteende för teckensnittsersättningsscenarier. |
| [LanguageTransformationBehavior](../../aspose.pdf.text/texteditoptions/languagetransformationbehavior/) { get; set; } | Hämtar läget som definierar beteende för språktransformation scenarier. |
| [NoCharacterBehavior](../../aspose.pdf.text/texteditoptions/nocharacterbehavior/) { get; set; } | Hämtar eller ställer in läget som definierar beteende om teckensnitt inte innehåller begärda tecken. |
| [ReplacementFont](../../aspose.pdf.text/texteditoptions/replacementfont/) { get; set; } | Hämtar eller ställer in teckensnitt som används för att ersätta om användarteckensnittet inte innehåller nödvändigt tecken |
| [ToAttemptGetUnderlineFromSource](../../aspose.pdf.text/texteditoptions/toattemptgetunderlinefromsource/) { get; set; } | Hämtar eller ställer in värde som tillåter sökning efter textunderstrykning på sidan av källdokumentet. (Föråldrad) Vänligen använd TextSearchOptions.SearchForTextRelatedGraphics istället för detta. |

### Se Även

* klass [TextOptions](../textoptions/)
* namnrymd [Aspose.Pdf.Text](../../aspose.pdf.text/)
* sammansättning [Aspose.PDF](../../)