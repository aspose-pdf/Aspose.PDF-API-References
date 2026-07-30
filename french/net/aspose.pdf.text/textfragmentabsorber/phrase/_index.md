---
title: "TextFragmentAbsorber.Phrase"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Propriété TextFragmentAbsorber. Obtient ou définit la phrase que le TextFragmentAbsorber recherche dans le document PDF ou la page."
type: docs
weight: 50
url: /fr/net/aspose.pdf.text/textfragmentabsorber/phrase/
---
## TextFragmentAbsorber.Phrase property

Obtient ou définit la phrase que le [`TextFragmentAbsorber`](../) recherche dans le document PDF ou la page.

```csharp
public string Phrase { get; set; }
```

## Exemples

L'exemple montre comment effectuer plusieurs recherches de texte et réaliser des remplacements de texte.

```csharp
// Ouvrir le document
Document doc = new Document(@"D:\Tests\input.pdf");

// Créer un objet TextFragmentAbsorber pour trouver toutes les occurrences du texte "hello"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello");

doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi";

// rechercher un autre mot et le remplacer
absorber.Phrase = "world";

doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "John";

// Enregistrer le document
doc.Save(@"D:\Tests\output.pdf");  
```

### Voir aussi

* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


