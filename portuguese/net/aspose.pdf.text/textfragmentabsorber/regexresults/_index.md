---
title: TextFragmentAbsorber.RegexResults
second_title: Aspose.PDF for .NET API Reference
description: Propriedade TextFragmentAbsorber. Obtém o dicionário de ocorrências de pesquisa que são apresentadas com a classe System.Text.RegularExpressions.Regex como chave e TextFragment como valor
type: docs
weight: 60
url: /pt/net/aspose.pdf.text/textfragmentabsorber/regexresults/
---
## Propriedade TextFragmentAbsorber.RegexResults

Obtém o dicionário de ocorrências de pesquisa que são apresentadas com a classe System.Text.RegularExpressions.Regex como chave e [`TextFragment`](../../textfragment/) como valor.

```csharp
public Dictionary<Regex, TextFragmentCollection> RegexResults { get; }
```

## Exemplos

O exemplo demonstra como encontrar texto com um array de expressões regulares na primeira página do documento PDF.

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

### Veja Também

* classe [TextFragmentCollection](../../textfragmentcollection/)
* classe [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)