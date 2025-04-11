---
title: Class FontRepository
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Text.FontRepository. Effectue une recherche de police. Recherche dans les polices installées sur le système et les polices Pdf standard. Fournit également une fonctionnalité pour ouvrir des polices personnalisées.
type: docs
weight: 10540
url: /fr/net/aspose.pdf.text/fontrepository/
---
## Classe FontRepository

Effectue une recherche de police. Recherche dans les polices installées sur le système et les polices Pdf standard. Fournit également une fonctionnalité pour ouvrir des polices personnalisées.

```csharp
public sealed class FontRepository
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [FontRepository](fontrepository/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| static [Sources](../../aspose.pdf.text/fontrepository/sources/) { get; } | Obtient la collection de sources de polices. |
| static [Substitutions](../../aspose.pdf.text/fontrepository/substitutions/) { get; } | Obtient la collection de stratégies de substitution de polices. |

## Méthodes

| Nom | Description |
| --- | --- |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont)(string) | Recherche et retourne la police avec le nom de police spécifié. |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont_3)(string, bool) | Recherche et retourne la police avec le nom de police spécifié en ignorant ou en respectant la sensibilité à la casse. |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont_1)(string, FontStyles) | Recherche et retourne la police avec le nom de police spécifié et le style de police. |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont_2)(string, FontStyles, bool) | Recherche et retourne la police avec le nom de police spécifié et le style de police en ignorant ou en respectant la sensibilité à la casse. |
| static [LoadFonts](../../aspose.pdf.text/fontrepository/loadfonts/)() | Charge les polices installées sur le système et les polices Pdf standard. Cette méthode a été conçue pour accélérer le processus de chargement des polices. Par défaut, les polices sont chargées lors de la première demande pour une police. L'utilisation de cette méthode charge immédiatement les polices système et les polices Pdf standard avant l'ouverture de tout document Pdf. |
| static [OpenFont](../../aspose.pdf.text/fontrepository/openfont/#openfont_1)(string) | Ouvre la police avec le chemin de fichier de police spécifié. |
| static [OpenFont](../../aspose.pdf.text/fontrepository/openfont/#openfont)(Stream, FontTypes) | Ouvre la police avec le flux de police spécifié. |
| static [OpenFont](../../aspose.pdf.text/fontrepository/openfont/#openfont_2)(string, string) | Ouvre la police avec le chemin de fichier de police spécifié et le chemin de fichier de métriques. |
| static [ReloadFonts](../../aspose.pdf.text/fontrepository/reloadfonts/)() | Recharge toutes les polices spécifiées par la propriété [`Sources`](./sources/) |

## Exemples

L'exemple démontre comment trouver une police et remplacer la police du texte de la première page.

```csharp
// Find font
Font font = FontRepository.FindFont("Arial");

// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change font of the first text occurrence
absorber.TextFragments[1].TextState.Font = font;

// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### Voir aussi

* classe [TextFragmentAbsorber](../textfragmentabsorber/)
* classe [Document](../../aspose.pdf/document/)
* espace de noms [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)