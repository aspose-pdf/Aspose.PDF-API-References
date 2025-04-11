---
title: Class FontRepository
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.FontRepository klass. Utför teckensnittssökning. Söker i systeminstallerade teckensnitt och standard Pdf-teckensnitt. Ger också funktionalitet för att öppna anpassade teckensnitt
type: docs
weight: 10540
url: /sv/net/aspose.pdf.text/fontrepository/
---
## FontRepository klass

Utför teckensnittssökning. Söker i systeminstallerade teckensnitt och standard Pdf-teckensnitt. Ger också funktionalitet för att öppna anpassade teckensnitt.

```csharp
public sealed class FontRepository
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [FontRepository](fontrepository/)() | Standardkonstruktören. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| static [Sources](../../aspose.pdf.text/fontrepository/sources/) { get; } | Hämtar samlingen av teckensnitts källor. |
| static [Substitutions](../../aspose.pdf.text/fontrepository/substitutions/) { get; } | Hämtar samlingen av teckensnitts ersättningsstrategier. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont)(string) | Söker och returnerar teckensnitt med angivet teckensnittsnamn. |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont_3)(string, bool) | Söker och returnerar teckensnitt med angivet teckensnittsnamn och ignorerar eller beaktar skiftlägeskänslighet. |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont_1)(string, FontStyles) | Söker och returnerar teckensnitt med angivet teckensnittsnamn och teckensnittsstil. |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont_2)(string, FontStyles, bool) | Söker och returnerar teckensnitt med angivet teckensnittsnamn och teckensnittsstil och ignorerar eller beaktar skiftlägeskänslighet. |
| static [LoadFonts](../../aspose.pdf.text/fontrepository/loadfonts/)() | Laddar systeminstallerade teckensnitt och standard Pdf-teckensnitt. Denna metod är utformad för att snabba upp teckensnitts laddningsprocessen. Som standard laddas teckensnitt vid första begäran om något teckensnitt. Användning av denna metod laddar system- och standard Pdf-teckensnitt omedelbart innan något Pdf-dokument öppnas. |
| static [OpenFont](../../aspose.pdf.text/fontrepository/openfont/#openfont_1)(string) | Öppnar teckensnitt med angiven teckensnitts filväg. |
| static [OpenFont](../../aspose.pdf.text/fontrepository/openfont/#openfont)(Stream, FontTypes) | Öppnar teckensnitt med angiven teckensnittsström. |
| static [OpenFont](../../aspose.pdf.text/fontrepository/openfont/#openfont_2)(string, string) | Öppnar teckensnitt med angiven teckensnitts filväg och metrik filväg. |
| static [ReloadFonts](../../aspose.pdf.text/fontrepository/reloadfonts/)() | Laddar om alla teckensnitt som anges av egenskapen [`Sources`](./sources/) |

## Exempel

Exemplet visar hur man hittar teckensnitt och ersätter teckensnittet för texten på första sidan.

```csharp
// Find font
Font font = FontRepository.FindFont("Arial");

// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change font of the first text occurrence
absorber.TextFragments[1].TextState.Font = font;

// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### Se Även

* klass [TextFragmentAbsorber](../textfragmentabsorber/)
* klass [Document](../../aspose.pdf/document/)
* namnrymd [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)