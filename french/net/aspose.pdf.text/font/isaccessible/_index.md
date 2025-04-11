---
title: Font.IsAccessible
second_title: Aspose.PDF for .NET API Reference
description: Propriété de la police. Indique si la police est installée dans le système
type: docs
weight: 50
url: /fr/net/aspose.pdf.text/font/isaccessible/
---
## Propriété Font.IsAccessible

Indique si la police est présente (installée) dans le système.

```csharp
public bool IsAccessible { get; }
```

## Remarques

Certaines opérations ne sont pas disponibles avec des polices qui n'ont pas pu être trouvées dans le système.

## Exemples

L'exemple démontre comment rechercher du texte sur la première page et obtenir la valeur qui indique si la police est installée dans le système.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// View font's IsSubset value of first text occurrence
if(absorber.TextFragments[1].TextState.Font.IsAccessible)
   Console.Out.WriteLine("the font is installed in the system");
```

### Voir aussi

* classe [TextFragmentAbsorber](../../textfragmentabsorber/)
* classe [Document](../../../aspose.pdf/document/)
* classe [Font](../)
* espace de noms [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)