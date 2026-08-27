---
title: "Font.FontName"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Propriété Font. Obtient le nom de police de l'objet Font"
type: docs
weight: 30
url: /fr/net/aspose.pdf.text/font/fontname/
---
## Font.FontName property

Obtient le nom de police de l'objet [`Font`](../).

```csharp
public string FontName { get; }
```

## Exemples

L'exemple montre comment rechercher du texte sur la première page et afficher le nom de police de la première occurrence de texte.

```csharp
// Ouvrir le document
Document doc = new Document(@"D:\Tests\input.pdf");

// Créer l'objet TextFragmentAbsorber pour trouver toutes les occurrences du texte "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accepter l'absorbeur pour la première page
doc.Pages[1].Accept(absorber);

// Afficher le nom de police de la première occurrence de texte
Console.Out.WriteLine(absorber.TextFragments[1].TextState.Font.FontName); 
```

### Voir aussi

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [Document](../../../aspose.pdf/document/)
* class [Font](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


