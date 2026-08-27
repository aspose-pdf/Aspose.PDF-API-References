---
title: "TextFragmentAbsorber.RegexResults"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Propriété TextFragmentAbsorber. Obtient un dictionnaire des occurrences de recherche présentées avec la classe System.Text.RegularExpressions.Regex comme clé et TextFragment comme valeur."
type: docs
weight: 60
url: /fr/net/aspose.pdf.text/textfragmentabsorber/regexresults/
---
## TextFragmentAbsorber.RegexResults property

Obtient un dictionnaire des occurrences de recherche présentées avec la classe System.Text.RegularExpressions.Regex comme clé et [`TextFragment`](../../textfragment/) comme valeur.

```csharp
public Dictionary<Regex, TextFragmentCollection> RegexResults { get; }
```

## Exemples

L'exemple montre comment trouver du texte avec un tableau d'expressions régulières sur la première page du document PDF.

```csharp
// Ouvrir le document
Document doc = new Document(@"D:\Tests\input.pdf");

var regexes = new Regex[]
{
new Regex( @"expression1", RegexOptions.IgnoreCase),
new Regex( @"expression2", RegexOptions.IgnoreCase),
};
// Créer un objet TextFragmentAbsorber qui recherche tous les mots commençant par 'h' et se terminant par 'o' en utilisant une expression régulière.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(regexes, new TextSearchOptions(true));
doc.Pages[1].Accept(absorber);
// Obtenir les résultats
var results = absorber.RegexResults;
```

### Voir aussi

* class [TextFragmentCollection](../../textfragmentcollection/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


