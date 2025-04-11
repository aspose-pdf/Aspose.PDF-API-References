---
title: TextFragmentAbsorber.RegexResults
second_title: Aspose.PDF for .NET API Reference
description: Proprietà di TextFragmentAbsorber. Ottiene un dizionario delle occorrenze di ricerca presentate con la classe System.Text.RegularExpressions.Regex come chiave e TextFragment come valore
type: docs
weight: 60
url: /it/net/aspose.pdf.text/textfragmentabsorber/regexresults/
---
## Proprietà TextFragmentAbsorber.RegexResults

Ottiene un dizionario delle occorrenze di ricerca presentate con la classe System.Text.RegularExpressions.Regex come chiave e [`TextFragment`](../../textfragment/) come valore.

```csharp
public Dictionary<Regex, TextFragmentCollection> RegexResults { get; }
```

## Esempi

L'esempio dimostra come trovare testo con un array di espressioni regolari nella prima pagina del documento PDF.

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

### Vedi Anche

* classe [TextFragmentCollection](../../textfragmentcollection/)
* classe [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)