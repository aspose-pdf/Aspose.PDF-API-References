---
title: "TextFragment.TextState"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Propriété TextFragment. Obtient ou définit l'état du texte pour le texte que représente l'objet TextFragment."
type: docs
weight: 150
url: /fr/net/aspose.pdf.text/textfragment/textstate/
---
## TextFragment.TextState property

Obtient ou définit l'état du texte pour le texte que représente l'objet [`TextFragment`](../).

```csharp
public TextFragmentState TextState { get; }
```

## Remarques

Fournit un moyen de modifier les propriétés suivantes du texte : Font FontSize FontStyle ForegroundColor BackgroundColor

## Exemples

L'exemple montre comment changer la couleur du texte et la taille de la police du texte avec l'objet `TextState`.

```csharp
// Ouvrir le document
Document doc = new Document(@"D:\Tests\input.pdf");

// Créer l'objet TextFragmentAbsorber pour trouver toutes les occurrences du texte "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accepter l'absorbeur pour la première page
doc.Pages[1].Accept(absorber);

// Modifier la couleur de premier plan de la première occurrence du texte
absorber.TextFragments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);

// Modifier la taille de police de la première occurrence du texte
absorber.TextFragments[1].TextState.FontSize = 15;

// Enregistrer le document
doc.Save(@"D:\Tests\output.pdf");  
```

### Voir aussi

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [Document](../../../aspose.pdf/document/)
* class [TextFragmentState](../../textfragmentstate/)
* class [TextFragment](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


