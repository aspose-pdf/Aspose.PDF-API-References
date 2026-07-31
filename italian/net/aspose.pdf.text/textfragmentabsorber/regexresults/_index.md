---
title: "TextFragmentAbsorber.RegexResults"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Proprietà TextFragmentAbsorber. Ottiene il dizionario delle occorrenze di ricerca presentate con la classe System.Text.RegularExpressions.Regex come chiave e TextFragment come valore"
type: docs
weight: 60
url: /it/net/aspose.pdf.text/textfragmentabsorber/regexresults/
---
## TextFragmentAbsorber.RegexResults property

Ottiene il dizionario delle occorrenze di ricerca presentate con la classe System.Text.RegularExpressions.Regex come chiave e [`TextFragment`](../../textfragment/) come valore.

```csharp
public Dictionary<Regex, TextFragmentCollection> RegexResults { get; }
```

## Esempi

L'esempio dimostra come trovare il testo con un array di espressioni regolari nella prima pagina del documento PDF.

```csharp
// Apri documento
Document doc = new Document(@"D:\Tests\input.pdf");

var regexes = new Regex[]
{
new Regex( @"expression1", RegexOptions.IgnoreCase),
new Regex( @"expression2", RegexOptions.IgnoreCase),
};
// Crea un oggetto TextFragmentAbsorber che ricerca tutte le parole che iniziano con 'h' e terminano con 'o' usando un'espressione regolare.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(regexes, new TextSearchOptions(true));
doc.Pages[1].Accept(absorber);
// Ottieni risultati
var results = absorber.RegexResults;
```

### Vedi anche

* class [TextFragmentCollection](../../textfragmentcollection/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


