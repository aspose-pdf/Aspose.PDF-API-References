---
title: "Classe FontRepository"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.Text.FontRepository. Effectue la recherche de polices. Recherche dans les polices installées sur le système et les polices PDF standard. Fournit également la fonctionnalité d'ouvrir des polices personnalisées."
type: docs
weight: 10720
url: /fr/net/aspose.pdf.text/fontrepository/
---
## FontRepository class

Effectue une recherche de polices. Recherche parmi les polices installées sur le système et les polices PDF standard. Fournit également la fonctionnalité d'ouvrir des polices personnalisées.

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
| static [Sources](../../aspose.pdf.text/fontrepository/sources/) { get; } | Obtient la collection des sources de police. |
| static [Substitutions](../../aspose.pdf.text/fontrepository/substitutions/) { get; } | Obtient la collection des stratégies de substitution de police. |

## Méthodes

| Nom | Description |
| --- | --- |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont)(string) | Recherche et renvoie la police avec le nom de police spécifié. |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont_3)(string, bool) | Recherche et renvoie la police avec le nom de police spécifié en ignorant ou en respectant la sensibilité à la casse. |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont_1)(string, FontStyles) | Recherche et renvoie la police avec le nom de police et le style de police spécifiés. |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont_2)(string, FontStyles, bool) | Recherche et renvoie la police avec le nom de police et le style de police spécifiés en ignorant ou en respectant la sensibilité à la casse. |
| static [LoadFonts](../../aspose.pdf.text/fontrepository/loadfonts/)() | Charge les polices installées sur le système et les polices Pdf standard. Cette méthode a été conçue pour accélérer le processus de chargement des polices. Par défaut, les polices sont chargées lors de la première requête pour n'importe quelle police. L'utilisation de cette méthode charge les polices du système et les polices Pdf standard immédiatement avant l'ouverture de tout Document Pdf. |
| static [OpenFont](../../aspose.pdf.text/fontrepository/openfont/#openfont_1)(string) | Ouvre la police avec le chemin de fichier de police spécifié. |
| static [OpenFont](../../aspose.pdf.text/fontrepository/openfont/#openfont)(Stream, FontTypes) | Ouvre la police avec le flux de police spécifié. |
| static [OpenFont](../../aspose.pdf.text/fontrepository/openfont/#openfont_2)(string, string) | Ouvre la police avec le chemin du fichier de police spécifié et le chemin du fichier de métriques. |
| static [ReloadFonts](../../aspose.pdf.text/fontrepository/reloadfonts/)() | Recharge toutes les polices spécifiées par la propriété [`Sources`](./sources/) |

## Exemples

L'exemple montre comment trouver une police et remplacer la police du texte de la première Page.

```csharp
// Trouver la police
Font font = FontRepository.FindFont("Arial");

// Ouvrir le document
Document doc = new Document(@"D:\Tests\input.pdf");

// Créer l'objet TextFragmentAbsorber pour trouver toutes les occurrences du texte "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accepter l'absorbeur pour la première page
doc.Pages[1].Accept(absorber);

// Modifier la police de la première occurrence de texte
absorber.TextFragments[1].TextState.Font = font;

// Enregistrer le document
doc.Save(@"D:\Tests\output.pdf"); 
```

### Voir aussi

* class [TextFragmentAbsorber](../textfragmentabsorber/)
* class [Document](../../aspose.pdf/document/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


