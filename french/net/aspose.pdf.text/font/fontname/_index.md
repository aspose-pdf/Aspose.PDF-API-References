---
title: Font.FontName
second_title: Aspose.PDF for .NET API Reference
description: Propriété de police. Obtient le nom de la police de l'objet Font
type: docs
weight: 30
url: /fr/net/aspose.pdf.text/font/fontname/
---
## Propriété Font.FontName

Obtient le nom de la police de l'objet [`Font`](../).

```csharp
public string FontName { get; }
```

## Exemples

L'exemple démontre comment rechercher du texte sur la première page et afficher le nom de la police de la première occurrence de texte.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// View font name of first text occurrence
Console.Out.WriteLine(absorber.TextFragments[1].TextState.Font.FontName); 
```

### Voir aussi

* classe [TextFragmentAbsorber](../../textfragmentabsorber/)
* classe [Document](../../../aspose.pdf/document/)
* classe [Font](../)
* espace de noms [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)