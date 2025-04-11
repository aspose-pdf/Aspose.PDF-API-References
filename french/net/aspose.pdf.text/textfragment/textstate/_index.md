---
title: TextFragment.TextState
second_title: Aspose.PDF for .NET API Reference
description: Propriété TextFragment. Obtient ou définit l'état du texte pour le texte que représente l'objet TextFragment
type: docs
weight: 150
url: /fr/net/aspose.pdf.text/textfragment/textstate/
---
## Propriété TextFragment.TextState

Obtient ou définit l'état du texte pour le texte que représente l'objet [`TextFragment`](../).

```csharp
public TextFragmentState TextState { get; }
```

## Remarques

Fournit un moyen de changer les propriétés suivantes du texte : Police TailleDePolice StyleDePolice CouleurDePremierPlan CouleurDeFond

## Exemples

L'exemple démontre comment changer la couleur du texte et la taille de police du texte avec l'objet `TextState`.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change foreground color of the first text occurrence
absorber.TextFragments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);

// Change font size of the first text occurrence
absorber.TextFragments[1].TextState.FontSize = 15;

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### Voir aussi

* classe [TextFragmentAbsorber](../../textfragmentabsorber/)
* classe [Document](../../../aspose.pdf/document/)
* classe [TextFragmentState](../../textfragmentstate/)
* classe [TextFragment](../)
* espace de noms [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)