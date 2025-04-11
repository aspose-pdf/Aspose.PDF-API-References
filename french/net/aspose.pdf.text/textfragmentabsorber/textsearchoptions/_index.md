---
title: TextFragmentAbsorber.TextSearchOptions
second_title: Aspose.PDF for .NET API Reference
description: Propriété TextFragmentAbsorber. Obtient ou définit les options de recherche. Les options permettent la recherche à l'aide d'expressions régulières
type: docs
weight: 110
url: /fr/net/aspose.pdf.text/textfragmentabsorber/textsearchoptions/
---
## Propriété TextFragmentAbsorber.TextSearchOptions

Obtient ou définit les options de recherche. Les options permettent la recherche à l'aide d'expressions régulières.

```csharp
public TextSearchOptions TextSearchOptions { get; set; }
```

## Exemples

L'exemple démontre comment effectuer une recherche de texte à l'aide d'une expression régulière.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object
TextFragmentAbsorber absorber = new TextFragmentAbsorber();

// make the absorber to search all words starting 'h' and ending 'o' using regular expression.
absorber.Phrase = @"h\w*?o";
absorber.TextSearchOptions = new TextSearchOptions(true);

// we should find "hello" word and replace it with "Hi"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi"; 

// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### Voir aussi

* classe [TextSearchOptions](../../textsearchoptions/)
* classe [TextFragmentAbsorber](../)
* espace de noms [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)