---
title: "Font.IsEmbedded"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Propriété Font. Obtient ou définit une valeur indiquant si la police est incorporée. Font basé sur IFont sera automatiquement sous-ensemble et incorporé"
type: docs
weight: 60
url: /fr/net/aspose.pdf.text/font/isembedded/
---
## Font.IsEmbedded property

Obtient ou définit une valeur indiquant si la police est incorporée. Une police basée sur IFont sera automatiquement sous‑ensemble et incorporée.

```csharp
public bool IsEmbedded { get; set; }
```

## Exemples

L'exemple suivant montre comment trouver une police, la marquer comme incorporée, rechercher du texte sur la page du document et remplacer la police du texte.

```csharp
// Créer une police et la marquer pour qu’elle soit incorporée
Font font = FontRepository.FindFont("Arial");
font.IsEmbedded = true;

// ouvrir le document
Document doc = new Document(@"D:\Tests\input.pdf");

// Créer un objet TextFragmentAbsorber pour trouver toutes les occurrences de texte "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
// accepter l'absorbeur pour la première page
doc.Pages[1].Accept(absorber);

// Modifier la police de la première occurrence de texte
absorber.TextFragments[1].TextState.Font = font;

// enregistrez le document
doc.Save(@"D:\Tests\output.pdf"); 
```

### Voir aussi

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [FontRepository](../../fontrepository/)
* class [Document](../../../aspose.pdf/document/)
* class [Font](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


