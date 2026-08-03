---
title: "TextFragmentAbsorber.RegexResults"
second_title: "Aspose.PDF för .NET API‑referens"
description: "TextFragmentAbsorber property. Hämtar en dictionary med sököccurser som presenteras med System.Text.RegularExpressions.Regex-klass som nyckel och TextFragment som värde."
type: docs
weight: 60
url: /sv/net/aspose.pdf.text/textfragmentabsorber/regexresults/
---
## TextFragmentAbsorber.RegexResults property

Hämtar en dictionary med sököccurser som presenteras med System.Text.RegularExpressions.Regex-klass som nyckel och [`TextFragment`](../../textfragment/) som värde.

```csharp
public Dictionary<Regex, TextFragmentCollection> RegexResults { get; }
```

## Exempel

Exemplet visar hur man hittar text med en array av reguljära uttryck på den första PDF-dokumentets sida.

```csharp
// Öppna dokument
Document doc = new Document(@"D:\Tests\input.pdf");

var regexes = new Regex[]
{
new Regex( @"expression1", RegexOptions.IgnoreCase),
new Regex( @"expression2", RegexOptions.IgnoreCase),
};
// Skapa ett TextFragmentAbsorber-objekt som söker alla ord som börjar med 'h' och slutar med 'o' med hjälp av reguljärt uttryck.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(regexes, new TextSearchOptions(true));
doc.Pages[1].Accept(absorber);
// Hämta resultat
var results = absorber.RegexResults;
```

### Se även

* class [TextFragmentCollection](../../textfragmentcollection/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


