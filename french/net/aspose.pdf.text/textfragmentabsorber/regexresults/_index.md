---
title: TextFragmentAbsorber.RegexResults
second_title: Aspose.PDF for .NET API Reference
description: Propriété TextFragmentAbsorber. Obtient un dictionnaire des occurrences de recherche qui sont présentées avec la classe System.Text.RegularExpressions.Regex comme clé et TextFragment comme valeur
type: docs
weight: 60
url: /fr/net/aspose.pdf.text/textfragmentabsorber/regexresults/
---
## Propriété TextFragmentAbsorber.RegexResults

Obtient un dictionnaire des occurrences de recherche qui sont présentées avec la classe System.Text.RegularExpressions.Regex comme clé et [`TextFragment`](../../textfragment/) comme valeur.

```csharp
public Dictionary<Regex, TextFragmentCollection> RegexResults { get; }
```

## Exemples

L'exemple démontre comment trouver du texte avec un tableau d'expressions régulières sur la première page du document PDF.

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

### Voir aussi

* classe [TextFragmentCollection](../../textfragmentcollection/)
* classe [TextFragmentAbsorber](../)
* espace de noms [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)