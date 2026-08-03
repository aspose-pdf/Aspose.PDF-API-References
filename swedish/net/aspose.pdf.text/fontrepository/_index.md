---
title: "Klass FontRepository"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Text.FontRepository-klass. Utför teckensnittssökning. Söker i systeminstallerade teckensnitt och standard‑Pdf‑teckensnitt. Tillhandahåller också funktionalitet för att öppna anpassade teckensnitt."
type: docs
weight: 10720
url: /sv/net/aspose.pdf.text/fontrepository/
---
## FontRepository class

Utför teckensnittssökning. Söker i systeminstallerade teckensnitt och standard‑Pdf‑teckensnitt. Tillhandahåller också funktionalitet för att öppna anpassade teckensnitt.

```csharp
public sealed class FontRepository
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [FontRepository](fontrepository/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| static [Sources](../../aspose.pdf.text/fontrepository/sources/) { get; } | Hämtar samling av teckensnittskällor. |
| static [Substitutions](../../aspose.pdf.text/fontrepository/substitutions/) { get; } | Hämtar samling av teckensnittssubstitutionsstrategier. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont)(string) | Söker och returnerar teckensnitt med angivet teckensnittsnamn. |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont_3)(string, bool) | Söker och returnerar teckensnitt med angivet teckensnittsnamn, med eller utan hänsyn till skiftlägeskänslighet. |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont_1)(string, FontStyles) | Söker och returnerar teckensnitt med angivet teckensnittsnamn och teckensnittsstil. |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont_2)(string, FontStyles, bool) | Söker och returnerar teckensnitt med angivet teckensnittsnamn och teckensnittsstil, med eller utan hänsyn till skiftlägeskänslighet. |
| static [LoadFonts](../../aspose.pdf.text/fontrepository/loadfonts/)() | Laddar systeminstallerade teckensnitt och standard‑Pdf‑teckensnitt. Denna metod är utformad för att snabba upp teckensnittsladdningsprocessen. Som standard laddas teckensnitt vid första begäran om något teckensnitt. Användning av denna metod laddar system‑ och standard‑Pdf‑teckensnitt omedelbart innan något Pdf‑dokument öppnas. |
| static [OpenFont](../../aspose.pdf.text/fontrepository/openfont/#openfont_1)(string) | Öppnar teckensnitt med angiven sökväg till teckensnittsfilen. |
| static [OpenFont](../../aspose.pdf.text/fontrepository/openfont/#openfont)(Stream, FontTypes) | Öppnar teckensnitt med angivet teckensnittström. |
| static [OpenFont](../../aspose.pdf.text/fontrepository/openfont/#openfont_2)(string, string) | Öppnar teckensnitt med angiven sökväg till teckensnittsfilen och sökväg till metrikfilen. |
| static [ReloadFonts](../../aspose.pdf.text/fontrepository/reloadfonts/)() | Laddar om alla teckensnitt som anges av egenskapen [`Sources`](./sources/) |

## Exempel

Exemplet visar hur man hittar ett teckensnitt och ersätter teckensnittet i texten på den första sidan.

```csharp
// Hitta teckensnitt
Font font = FontRepository.FindFont("Arial");

// Öppna dokument
Document doc = new Document(@"D:\Tests\input.pdf");

// Skapa ett TextFragmentAbsorber‑objekt för att hitta alla förekomster av texten \"hello world\"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Acceptera absorberaren för första sidan
doc.Pages[1].Accept(absorber);

// Ändra teckensnitt för den första textförekomsten
absorber.TextFragments[1].TextState.Font = font;

// Spara dokument
doc.Save(@"D:\Tests\output.pdf"); 
```

### Se även

* class [TextFragmentAbsorber](../textfragmentabsorber/)
* class [Document](../../aspose.pdf/document/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


