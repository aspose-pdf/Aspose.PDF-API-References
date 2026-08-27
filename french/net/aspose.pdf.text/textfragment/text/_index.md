---
title: "TextFragment.Text"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Propriété TextFragment. Obtient ou définit l'objet texte de type String que représente l'objet TextFragment."
type: docs
weight: 130
url: /fr/net/aspose.pdf.text/textfragment/text/
---
## TextFragment.Text property

Obtient ou définit l'objet texte de type String que représente l'objet [`TextFragment`](../).

```csharp
public string Text { get; set; }
```

## Exemples

L'exemple montre comment rechercher un texte et remplacer la première occurrence représentée par l'objet [`TextFragment`](../).

```csharp
// Ouvrir le document
Document doc = new Document(@"D:\Tests\input.pdf");

// Créer l'objet TextFragmentAbsorber pour trouver toutes les occurrences du texte "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accepter l'absorbeur pour la première page
doc.Pages[1].Accept(absorber);

// Modifier la police de la première occurrence de texte
absorber.TextFragments[1].Text = "hi world";

// Enregistrer le document
doc.Save(@"D:\Tests\output.pdf"); 
```

### Voir aussi

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [Document](../../../aspose.pdf/document/)
* class [TextFragment](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


