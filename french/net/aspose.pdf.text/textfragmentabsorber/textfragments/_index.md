---
title: TextFragments
second_title: Référence de l'API Aspose.PDF pour .NET
description: Obtient une collection doccurrences de recherche présentées avecTextFragmentaspose.pdf.text/textfragment objets.
type: docs
weight: 80
url: /fr/net/aspose.pdf.text/textfragmentabsorber/textfragments/
---
## TextFragmentAbsorber.TextFragments property

Obtient une collection d'occurrences de recherche présentées avec[`TextFragment`](../../textfragment) objets.

```csharp
public TextFragmentCollection TextFragments { get; set; }
```

### Exemples

L'exemple montre comment rechercher du texte sur la première page du document PDF et remplacer toutes les occurrences de recherche par un nouveau texte.

```csharp
// Ouvrir le document
Document doc = new Document(@"D:\Tests\input.pdf");

// Trouve la police qui sera utilisée pour changer la police du texte du document
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Crée un objet TextFragmentAbsorber pour trouver toutes les occurrences de texte "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accepte l'absorbeur pour la première page
doc.Pages[1].Accept(absorber);

// Modifier le texte de toutes les occurrences de recherche
foreach (TextFragment textFragment in absorber.TextFragments)
{
    textFragment.Text = "hi world";
}

// Enregistrer le document
doc.Save(@"D:\Tests\output.pdf");  
```

### Voir également

* class [TextFragmentCollection](../../textfragmentcollection)
* class [TextFragmentAbsorber](../../textfragmentabsorber)
* espace de noms [Aspose.Pdf.Text](../../textfragmentabsorber)
* Assemblée [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->