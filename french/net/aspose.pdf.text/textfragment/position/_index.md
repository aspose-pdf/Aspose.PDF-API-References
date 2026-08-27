---
title: "TextFragment.Position"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Propriété TextFragment. Obtient ou définit la position du texte représenté par l'objet TextFragment."
type: docs
weight: 90
url: /fr/net/aspose.pdf.text/textfragment/position/
---
## TextFragment.Position property

Obtient ou définit la position du texte, représenté par l'objet [`TextFragment`](../).

```csharp
public Position Position { get; set; }
```

## Exemples

L'exemple montre comment visualiser le placement d'un texte, représenté par l'objet [`TextFragment`](../).

```csharp
// Ouvrir le document
Document doc = new Document(@"D:\Tests\input.pdf");

// Créer l'objet TextFragmentAbsorber pour trouver toutes les occurrences du texte "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accepter l'absorbeur pour la première page
doc.Pages[1].Accept(absorber);

// Afficher le texte et les informations de placement de la première occurrence du texte.
TextFragment firstOccurrence = absorber.TextFragments[1];

Console.Out.WriteLine(string.Format("fragment text: {0}", firstOccurrence.Text));
Console.Out.WriteLine(string.Format("fragment X indent: {0}", firstOccurrence.Position.XIndent));
Console.Out.WriteLine(string.Format("fragment Y indent: {0}", firstOccurrence.Position.YIndent));

```

### Voir aussi

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [Document](../../../aspose.pdf/document/)
* class [TextSegment](../../textsegment/)
* class [Position](../../position/)
* class [TextFragment](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


