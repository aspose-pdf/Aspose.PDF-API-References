---
title: "TextFragmentAbsorber.TextFragments"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Propriété TextFragmentAbsorber. Obtient une collection d'occurrences de recherche présentées avec des objets TextFragment."
type: docs
weight: 90
url: /fr/net/aspose.pdf.text/textfragmentabsorber/textfragments/
---
## TextFragmentAbsorber.TextFragments property

Obtient une collection d'occurrences de recherche présentées avec des objets [`TextFragment`](../../textfragment/).

```csharp
public TextFragmentCollection TextFragments { get; set; }
```

## Exemples

L'exemple montre comment trouver du texte sur la première page du document PDF et remplacer toutes les occurrences de recherche par du nouveau texte.

```csharp
// Ouvrir le document
Document doc = new Document(@"D:\Tests\input.pdf");

// Trouver la police qui sera utilisée pour modifier la police du texte du document
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Créer l'objet TextFragmentAbsorber pour trouver toutes les occurrences du texte "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accepter l'absorbeur pour la première page
doc.Pages[1].Accept(absorber);

// Modifier le texte de toutes les occurrences de recherche
foreach (TextFragment textFragment in absorber.TextFragments)
{
    textFragment.Text = "hi world";
}

// Enregistrer le document
doc.Save(@"D:\Tests\output.pdf");  
```

### Voir aussi

* class [TextFragmentCollection](../../textfragmentcollection/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


