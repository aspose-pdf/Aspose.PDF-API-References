---
title: Class Font
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Text.Font. Représente l'objet police
type: docs
weight: 10510
url: /fr/net/aspose.pdf.text/font/
---
## Classe Font

Représente l'objet police.

```csharp
public sealed class Font
```

## Propriétés

| Nom | Description |
| --- | --- |
| [BaseFont](../../aspose.pdf.text/font/basefont/) { get; } | Obtient la valeur BaseFont de l'objet police PDF. Également connu sous le nom de nom PostScript de la police. |
| [DecodedFontName](../../aspose.pdf.text/font/decodedfontname/) { get; } | Parfois, les polices PDF (généralement les polices chinoises/japonaises/coréennes) peuvent avoir un nom de police spécifique. Ce nom est la valeur de la propriété PDF "BaseFont" et parfois cette propriété peut être représentée sous forme hexadécimale. Si ce nom est lu directement, il peut être représenté sous une forme illisible. Pour obtenir une forme lisible, il est nécessaire de décoder le nom de la police selon des règles spécifiques à cette police. Cette propriété renvoie le nom de police décodé, donc utilisez-la pour les cas où vous rencontrez un [`FontName`](./fontname/) illisible. Si la propriété [`FontName`](./fontname/) a une forme lisible, cette propriété sera la même que [`FontName`](./fontname/), donc vous pouvez utiliser cette propriété pour tous les cas où vous avez besoin d'obtenir le nom de la police sous une forme lisible. |
| [FontName](../../aspose.pdf.text/font/fontname/) { get; } | Obtient le nom de la police de l'objet `Font`. |
| [FontOptions](../../aspose.pdf.text/font/fontoptions/) { get; } | Propriétés utiles pour ajuster le comportement de la police |
| [IsAccessible](../../aspose.pdf.text/font/isaccessible/) { get; } | Obtient une indication de la présence (installation) de la police dans le système. |
| [IsEmbedded](../../aspose.pdf.text/font/isembedded/) { get; set; } | Obtient ou définit une valeur qui indique si la police est intégrée. Les polices basées sur IFont seront automatiquement sous-ensembles et intégrées |
| [IsSubset](../../aspose.pdf.text/font/issubset/) { get; set; } | Obtient ou définit une valeur qui indique si la police est un sous-ensemble. Les polices basées sur IFont seront automatiquement sous-ensembles et intégrées |

## Méthodes

| Nom | Description |
| --- | --- |
| [GetLastFontEmbeddingError](../../aspose.pdf.text/font/getlastfontembeddingerror/)() | L'objectif de cette méthode est de renvoyer la description de l'erreur si une tentative d'intégration de la police a échoué. S'il n'y a pas de cas d'erreur, elle renvoie une chaîne vide. |
| [MeasureString](../../aspose.pdf.text/font/measurestring/)(string, float) | Mesure la chaîne. |
| [Save](../../aspose.pdf.text/font/save/)(Stream) | Enregistre la police dans le flux. Notez que la police est enregistrée au format TTF intermédiaire destiné à être utilisé uniquement dans une copie convertie du document original. Le fichier de police n'est pas destiné à être utilisé en dehors du contexte du document original. |

## Exemples

L'exemple démontre comment rechercher du texte sur la première page et changer la police de la première occurrence trouvée.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Create font and mark it to be embedded
Font font = FontRepository.FindFont("Arial");
font.IsEmbedded = true;

// Change font of the first text occurrence
absorber.TextFragments[1].TextState.Font = font;


// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### Voir aussi

* classe [TextFragmentAbsorber](../textfragmentabsorber/)
* classe [FontRepository](../fontrepository/)
* classe [Document](../../aspose.pdf/document/)
* espace de noms [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)