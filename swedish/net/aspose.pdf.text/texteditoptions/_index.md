---
title: "Klass TextEditOptions"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Text.TextEditOptions-klass. Beskriver alternativ för textredigeringsoperationer"
type: docs
weight: 11000
url: /sv/net/aspose.pdf.text/texteditoptions/
---
## TextEditOptions class

Beskriver alternativ för textredigeringsoperationer.

```csharp
public sealed class TextEditOptions : TextOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [TextEditOptions](texteditoptions/#constructor)(bool) | Initierar en ny instans av `TextEditOptions`‑objektet för den angivna behörigheten för språktransformering. |
| [TextEditOptions](texteditoptions/#constructor_1)(FontReplace) | Initierar en ny instans av `TextEditOptions`‑objektet för det angivna läget för teckensnittsersättningsbeteende. |
| [TextEditOptions](texteditoptions/#constructor_2)(LanguageTransformation) | Initierar en ny instans av `TextEditOptions`‑objektet för det angivna läget för språktransformeringsbeteende. |
| [TextEditOptions](texteditoptions/#constructor_3)(NoCharacterAction) | Initierar en ny instans av `TextEditOptions`‑objektet för det angivna läget för beteende utan tecken. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AllowLanguageTransformation](../../aspose.pdf.text/texteditoptions/allowlanguagetransformation/) { get; set; } | Hämtar eller anger värdet som tillåter användning av språktransformering vid tillägg eller redigering av text. true – språktransformering kommer att tillämpas om nödvändigt (standardvärde). false – språktransformering kommer INTE att tillämpas. |
| [ClippingPathsProcessing](../../aspose.pdf.text/texteditoptions/clippingpathsprocessing/) { get; set; } | Hämtar läget för bearbetning av beskärningsväg för den redigerade texten. |
| [FontReplaceBehavior](../../aspose.pdf.text/texteditoptions/fontreplacebehavior/) { get; set; } | Hämtar läget som definierar beteendet för scenarier med teckensnittsersättning. |
| [LanguageTransformationBehavior](../../aspose.pdf.text/texteditoptions/languagetransformationbehavior/) { get; set; } | Hämtar läget som definierar beteendet för scenarier med språktransformering. |
| [NoCharacterBehavior](../../aspose.pdf.text/texteditoptions/nocharacterbehavior/) { get; set; } | Hämtar eller anger läget som definierar beteendet om teckensnitt inte innehåller de begärda tecknen. |
| [ReplacementFont](../../aspose.pdf.text/texteditoptions/replacementfont/) { get; set; } | Hämtar eller anger teckensnittet som används för ersättning om användarens teckensnitt inte innehåller det nödvändiga tecknet |
| [ToAttemptGetUnderlineFromSource](../../aspose.pdf.text/texteditoptions/toattemptgetunderlinefromsource/) { get; set; } | Hämtar eller anger värdet som tillåter sökning efter textunderstrykning på sidan i källdokumentet. (Föråldrad) Använd TextSearchOptions.SearchForTextRelatedGraphics istället för detta. |

### Se även

* class [TextOptions](../textoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


