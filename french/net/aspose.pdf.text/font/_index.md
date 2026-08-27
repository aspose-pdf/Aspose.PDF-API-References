---
title: "Classe Font"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.Text.Font. Représente un objet police"
type: docs
weight: 10690
url: /fr/net/aspose.pdf.text/font/
---
## Font class

Représente un objet police.

```csharp
public sealed class Font
```

## Propriétés

| Nom | Description |
| --- | --- |
| [BaseFont](../../aspose.pdf.text/font/basefont/) { get; } | Obtient la valeur BaseFont de l'objet police PDF. Aussi connu sous le nom de nom PostScript de la police. |
| [DecodedFontName](../../aspose.pdf.text/font/decodedfontname/) { get; } | Parfois, les polices PDF (généralement les polices chinoises/japonaises/coréennes) peuvent avoir un nom de police spécifique. Ce nom est la valeur de la propriété de police PDF "BaseFont" et parfois cette propriété peut être représentée sous forme hexadécimale. Si vous lisez ce nom directement, il peut apparaître sous une forme non lisible. Pour obtenir une forme lisible, il est nécessaire de décoder le nom de la police selon des règles spécifiques à cette police. Cette propriété renvoie le nom de police décodé, donc utilisez‑la dans les cas où vous rencontrez un [`FontName`](./fontname/) non lisible. Si la propriété [`FontName`](./fontname/) a une forme lisible, cette propriété sera identique à [`FontName`](./fontname/), vous pouvez donc l’utiliser dans tous les cas où vous devez obtenir le nom de la police sous une forme lisible. |
| [FontName](../../aspose.pdf.text/font/fontname/) { get; } | Obtient le nom de la police de l'objet `Font`. |
| [FontOptions](../../aspose.pdf.text/font/fontoptions/) { get; } | Propriétés utiles pour ajuster le comportement de la police |
| [IsAccessible](../../aspose.pdf.text/font/isaccessible/) { get; } | Obtient une indication indiquant si la police est présente (installée) dans le système. |
| [IsEmbedded](../../aspose.pdf.text/font/isembedded/) { get; set; } | Obtient ou définit une valeur indiquant si la police est incorporée. Une police basée sur IFont sera automatiquement sous‑ensemble et incorporée. |
| [IsSubset](../../aspose.pdf.text/font/issubset/) { get; set; } | Obtient ou définit une valeur indiquant si la police est un sous‑ensemble. Une police basée sur IFont sera automatiquement sous‑ensemble et incorporée. |

## Méthodes

| Nom | Description |
| --- | --- |
| [GetLastFontEmbeddingError](../../aspose.pdf.text/font/getlastfontembeddingerror/)() | Le but de cette méthode est de renvoyer la description de l’erreur si une tentative d’incorporation de la police a échoué. S’il n’y a pas d’erreur, elle renvoie une chaîne vide. |
| [MeasureString](../../aspose.pdf.text/font/measurestring/)(string, float) | Mesure la chaîne. |
| [Save](../../aspose.pdf.text/font/save/)(Stream) | Enregistre la police dans le flux. Notez que la police est enregistrée au format TTF intermédiaire destiné à être utilisé uniquement dans une copie convertie du document original. Le fichier de police n’est pas destiné à être utilisé en dehors du contexte du document original. |

## Exemples

L’exemple montre comment rechercher du texte sur la première page et modifier la police de la première occurrence trouvée.

```csharp
// Ouvrir le document
Document doc = new Document(@"D:\Tests\input.pdf");

// Créer l'objet TextFragmentAbsorber pour trouver toutes les occurrences du texte "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accepter l'absorbeur pour la première page
doc.Pages[1].Accept(absorber);

// Créer une police et la marquer pour qu’elle soit incorporée
Font font = FontRepository.FindFont("Arial");
font.IsEmbedded = true;

// Modifier la police de la première occurrence de texte
absorber.TextFragments[1].TextState.Font = font;


// Enregistrer le document
doc.Save(@"D:\Tests\output.pdf"); 
```

### Voir aussi

* class [TextFragmentAbsorber](../textfragmentabsorber/)
* class [FontRepository](../fontrepository/)
* class [Document](../../aspose.pdf/document/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


