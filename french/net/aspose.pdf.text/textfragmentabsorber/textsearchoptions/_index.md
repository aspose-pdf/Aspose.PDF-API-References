---
title: "TextFragmentAbsorber.TextSearchOptions"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Propriété TextFragmentAbsorber. Obtient ou définit les options de recherche. Les options permettent la recherche à l'aide d'expressions régulières"
type: docs
weight: 110
url: /fr/net/aspose.pdf.text/textfragmentabsorber/textsearchoptions/
---
## TextFragmentAbsorber.TextSearchOptions property

Obtient ou définit les options de recherche. Les options permettent la recherche en utilisant des expressions régulières.

```csharp
public TextSearchOptions TextSearchOptions { get; set; }
```

## Exemples

L'exemple montre comment effectuer une recherche de texte à l'aide d'expressions régulières.

```csharp
// Ouvrir le document
Document doc = new Document(@"D:\Tests\input.pdf");

// Créer un objet TextFragmentAbsorber
TextFragmentAbsorber absorber = new TextFragmentAbsorber();

// Faire en sorte que l'absorbeur recherche tous les mots commençant par 'h' et se terminant par 'o' à l'aide d'expressions régulières.
absorber.Phrase = @"h\w*?o";
absorber.TextSearchOptions = new TextSearchOptions(true);

// nous devrions trouver le mot "hello" et le remplacer par "Hi"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi"; 

// Enregistrer le document
doc.Save(@"D:\Tests\output.pdf"); 
```

### Voir aussi

* class [TextSearchOptions](../../textsearchoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


