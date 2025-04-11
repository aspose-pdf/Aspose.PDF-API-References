---
title: TextFragmentAbsorber.RegexResults
second_title: Aspose.PDF for .NET API Reference
description: TextFragmentAbsorber-egenskap. Hämtar en ordbok över sökförekomster som presenteras med System.Text.RegularExpressions.Regex-klass som nyckel och TextFragment som värde
type: docs
weight: 60
url: /sv/net/aspose.pdf.text/textfragmentabsorber/regexresults/
---
## TextFragmentAbsorber.RegexResults-egenskap

Hämtar en ordbok över sökförekomster som presenteras med System.Text.RegularExpressions.Regex-klass som nyckel och [`TextFragment`](../../textfragment/) som värde.

```csharp
public Dictionary<Regex, TextFragmentCollection> RegexResults { get; }
```

## Exempel

Exemplet visar hur man hittar text med en array av reguljära uttryck på den första PDF-dokumentets sida.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

var regexes = new Regex[]
{
new Regex( @"expression1", RegexOptions.IgnoreCase),
new Regex( @"expression2", RegexOptions.IgnoreCase),
};
// Create TextFragmentAbsorber object that searches all words starting 'h' and ending 'o' using regular expression.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(regexes, new TextSearchOptions(true));
doc.Pages[1].Accept(absorber);
// Get results
var results = absorber.RegexResults;
```

### Se Även

* klass [TextFragmentCollection](../../textfragmentcollection/)
* klass [TextFragmentAbsorber](../)
* namnrymd [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)