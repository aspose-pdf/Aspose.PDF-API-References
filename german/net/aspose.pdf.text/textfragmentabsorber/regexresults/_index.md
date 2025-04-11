---
title: TextFragmentAbsorber.RegexResults
second_title: Aspose.PDF for .NET API Reference
description: TextFragmentAbsorber-Eigenschaft. Gibt ein Wörterbuch von Suchvorkommen zurück, das mit der Klasse System.Text.RegularExpressions.Regex als Schlüssel und TextFragment als Wert dargestellt wird
type: docs
weight: 60
url: /de/net/aspose.pdf.text/textfragmentabsorber/regexresults/
---
## TextFragmentAbsorber.RegexResults-Eigenschaft

Gibt ein Wörterbuch von Suchvorkommen zurück, das mit der Klasse System.Text.RegularExpressions.Regex als Schlüssel und [`TextFragment`](../../textfragment/) als Wert dargestellt wird.

```csharp
public Dictionary<Regex, TextFragmentCollection> RegexResults { get; }
```

## Beispiele

Das Beispiel zeigt, wie man Text mit einem Array von regulären Ausdrücken auf der ersten Seite des PDF-Dokuments findet.

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

### Siehe auch

* Klasse [TextFragmentCollection](../../textfragmentcollection/)
* Klasse [TextFragmentAbsorber](../)
* Namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* Assembly [Aspose.PDF](../../../)