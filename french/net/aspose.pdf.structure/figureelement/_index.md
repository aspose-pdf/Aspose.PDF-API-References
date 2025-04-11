---
title: Class FigureElement
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Structure.FigureElement. Classe représentant une figure de structure logique
type: docs
weight: 10160
url: /fr/net/aspose.pdf.structure/figureelement/
---
## Classe FigureElement

Classe représentant une figure de structure logique.

```csharp
public class FigureElement : Element
```

## Propriétés

| Nom | Description |
| --- | --- |
| virtual [ActualText](../../aspose.pdf.structure/element/actualtext/) { get; set; } | (Facultatif; PDF 1.4) Texte qui est un remplacement exact pour l'élément de structure et ses enfants. Ce texte de remplacement (qui devrait s'appliquer à la plus petite partie de contenu possible) est utile lors de l'extraction du contenu du document pour soutenir l'accessibilité aux utilisateurs handicapés ou à d'autres fins. |
| virtual [Alt](../../aspose.pdf.structure/element/alt/) { get; set; } | (Facultatif) Une description alternative de l'élément de structure et de ses enfants sous une forme lisible par l'homme, qui est utile lors de l'extraction du contenu du document pour soutenir l'accessibilité aux utilisateurs handicapés ou à d'autres fins. |
| [Children](../../aspose.pdf.structure/element/children/) { get; } | Obtient la collection des éléments enfants. |
| virtual [E](../../aspose.pdf.structure/element/e/) { get; set; } | (Facultatif; PDF 1.5) La forme développée d'une abréviation. |
| [Image](../../aspose.pdf.structure/figureelement/image/) { get; } | Obtient la valeur de l'élément de structure de figure. |
| virtual [Lang](../../aspose.pdf.structure/element/lang/) { get; set; } | (Facultatif; PDF 1.4) Une langue spécifiant la langue naturelle pour tout le texte dans l'élément de structure, sauf si elle est remplacée par des spécifications de langue pour des éléments de structure imbriqués ou du contenu marqué. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Remove](../../aspose.pdf.structure/element/remove/)() | Supprimer l'élément. |

### Voir aussi

* classe [Element](../element/)
* espace de noms [Aspose.Pdf.Structure](../../aspose.pdf.structure/)
* assembly [Aspose.PDF](../../)