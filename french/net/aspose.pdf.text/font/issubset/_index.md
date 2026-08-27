---
title: "Font.IsSubset"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Propriété Font. Obtient ou définit une valeur indiquant si la police est un sous-ensemble. Font basé sur IFont sera automatiquement sous-ensemble et incorporé"
type: docs
weight: 70
url: /fr/net/aspose.pdf.text/font/issubset/
---
## Font.IsSubset property

Obtient ou définit une valeur indiquant si la police est un sous‑ensemble. Une police basée sur IFont sera automatiquement sous‑ensemble et incorporée.

```csharp
public bool IsSubset { get; set; }
```

## Exemples

L'exemple montre comment rechercher du texte sur la première page et obtenir la valeur indiquant si la police est un sous-ensemble.

```csharp
// Ouvrir le document
Document doc = new Document(@"D:\Tests\input.pdf");

// Créer l'objet TextFragmentAbsorber pour trouver toutes les occurrences du texte "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accepter l'absorbeur pour la première page
doc.Pages[1].Accept(absorber);

// Afficher la valeur IsSubset de la police de la première occurrence de texte
if(absorber.TextFragments[1].TextState.Font.IsSubset)
   Console.Out.WriteLine("the font is a subset");
```

### Voir aussi

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [Document](../../../aspose.pdf/document/)
* class [Font](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


