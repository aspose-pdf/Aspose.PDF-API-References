---
title: "Font.IsAccessible"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Propriété Font. Obtient une indication de la présence de la police installée dans le système"
type: docs
weight: 50
url: /fr/net/aspose.pdf.text/font/isaccessible/
---
## Font.IsAccessible property

Obtient une indication indiquant si la police est présente (installée) dans le système.

```csharp
public bool IsAccessible { get; }
```

## Remarques

Certaines opérations ne sont pas disponibles avec les polices qui n'ont pas pu être trouvées dans le système.

## Exemples

L'exemple montre comment rechercher du texte sur la première page et obtenir la valeur indiquant si la police est installée dans le système.

```csharp
// Ouvrir le document
Document doc = new Document(@"D:\Tests\input.pdf");

// Créer l'objet TextFragmentAbsorber pour trouver toutes les occurrences du texte "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accepter l'absorbeur pour la première page
doc.Pages[1].Accept(absorber);

// Afficher la valeur IsSubset de la police de la première occurrence de texte
if(absorber.TextFragments[1].TextState.Font.IsAccessible)
   Console.Out.WriteLine("the font is installed in the system");
```

### Voir aussi

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [Document](../../../aspose.pdf/document/)
* class [Font](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


