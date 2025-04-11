---
title: Class TextElement
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Structure.TextElement. Élément de texte général de la structure logique du document
type: docs
weight: 10190
url: /fr/net/aspose.pdf.structure/textelement/
---
## Classe TextElement

Élément de texte général de la structure logique du document.

```csharp
public class TextElement : Element
```

## Propriétés

| Nom | Description |
| --- | --- |
| virtual [ActualText](../../aspose.pdf.structure/element/actualtext/) { get; set; } | (Optionnel; PDF 1.4) Texte qui est un remplacement exact pour l'élément de structure et ses enfants. Ce texte de remplacement (qui devrait s'appliquer à la plus petite portion de contenu possible) est utile lors de l'extraction du contenu du document pour soutenir l'accessibilité aux utilisateurs handicapés ou à d'autres fins. |
| virtual [Alt](../../aspose.pdf.structure/element/alt/) { get; set; } | (Optionnel) Une description alternative de l'élément de structure et de ses enfants sous une forme lisible par l'homme, qui est utile lors de l'extraction du contenu du document pour soutenir l'accessibilité aux utilisateurs handicapés ou à d'autres fins. |
| [Children](../../aspose.pdf.structure/element/children/) { get; } | Obtient la collection des éléments enfants. |
| virtual [E](../../aspose.pdf.structure/element/e/) { get; set; } | (Optionnel; PDF 1.5) La forme développée d'une abréviation. |
| virtual [Lang](../../aspose.pdf.structure/element/lang/) { get; set; } | (Optionnel; PDF 1.4) Une langue spécifiant la langue naturelle pour tout le texte dans l'élément de structure, sauf si elle est remplacée par des spécifications de langue pour des éléments de structure imbriqués ou du contenu marqué. |
| [Text](../../aspose.pdf.structure/textelement/text/) { get; } | Obtient la valeur de l'élément de structure de texte. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Remove](../../aspose.pdf.structure/element/remove/)() | Supprimer l'élément. |

### Voir aussi

* classe [Element](../element/)
* espace de noms [Aspose.Pdf.Structure](../../aspose.pdf.structure/)
* assembly [Aspose.PDF](../../)