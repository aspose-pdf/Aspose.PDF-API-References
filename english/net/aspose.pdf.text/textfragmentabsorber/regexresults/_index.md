---
title: TextFragmentAbsorber.RegexResults
second_title: Aspose.PDF for .NET API Reference
description: TextFragmentAbsorber property. Gets dictionary of search occurrences that are presented with System.Text.RegularExpressions.Regex class as key and TextFragment as value
type: docs
weight: 60
url: /net/aspose.pdf.text/textfragmentabsorber/regexresults/
---
## TextFragmentAbsorber.RegexResults property

Gets dictionary of search occurrences that are presented with System.Text.RegularExpressions.Regex class as key and [`TextFragment`](../../textfragment/) as value.

```csharp
public Dictionary<Regex, TextFragmentCollection> RegexResults { get; }
```

## Examples

The example demonstrates how to find text with array of regular expressions on the first PDF document page.

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

### See Also

* class [TextFragmentCollection](../../textfragmentcollection/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


