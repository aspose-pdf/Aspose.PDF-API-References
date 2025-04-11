---
title: Font.IsEmbedded
second_title: Aspose.PDF for .NET API Reference
description: Propriété de la police. Obtient ou définit une valeur qui indique si la police est intégrée. La police basée sur IFont sera automatiquement sous-ensemble et intégrée
type: docs
weight: 60
url: /fr/net/aspose.pdf.text/font/isembedded/
---
## Propriété Font.IsEmbedded

Obtient ou définit une valeur qui indique si la police est intégrée. La police basée sur IFont sera automatiquement sous-ensemble et intégrée

```csharp
public bool IsEmbedded { get; set; }
```

## Exemples

L'exemple suivant démontre comment trouver une police, la marquer comme intégrée, rechercher du texte sur la page du document et remplacer la police de texte.

```csharp
// Create font and mark it to be embedded
Font font = FontRepository.FindFont("Arial");
font.IsEmbedded = true;

// open document
Document doc = new Document(@"D:\Tests\input.pdf");

// create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
// accept the absorber for first page
doc.Pages[1].Accept(absorber);

// change font for the first text occurrence
absorber.TextFragments[1].TextState.Font = font;

// save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### Voir aussi

* classe [TextFragmentAbsorber](../../textfragmentabsorber/)
* classe [FontRepository](../../fontrepository/)
* classe [Document](../../../aspose.pdf/document/)
* classe [Font](../)
* espace de noms [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)