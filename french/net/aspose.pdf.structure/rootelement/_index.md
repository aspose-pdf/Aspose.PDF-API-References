---
title: "Classe RootElement"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.Structure.RootElement. Élément racine de la structure"
type: docs
weight: 10350
url: /fr/net/aspose.pdf.structure/rootelement/
---
## RootElement class

Élément racine de la structure.

```csharp
public class RootElement : Element
```

## Propriétés

| Nom | Description |
| --- | --- |
| virtual [ActualText](../../aspose.pdf.structure/element/actualtext/) { get; set; } | (Facultatif ; PDF 1.4) Texte qui remplace exactement l'élément de structure et ses enfants. Ce texte de remplacement (qui doit s'appliquer à la plus petite portion de contenu possible) est utile lors de l'extraction du contenu du document pour soutenir l'accessibilité des utilisateurs en situation de handicap ou à d'autres fins. |
| virtual [Alt](../../aspose.pdf.structure/element/alt/) { get; set; } | (Facultatif) Une description alternative de l'élément de structure et de ses enfants sous forme lisible par l'homme, utile lors de l'extraction du contenu du document pour soutenir l'accessibilité des utilisateurs en situation de handicap ou à d'autres fins. |
| [Children](../../aspose.pdf.structure/element/children/) { get; } | Obtient la collection des éléments enfants. |
| virtual [E](../../aspose.pdf.structure/element/e/) { get; set; } | (Facultatif ; PDF 1.5) La forme développée d'une abréviation. |
| virtual [Lang](../../aspose.pdf.structure/element/lang/) { get; set; } | (Facultatif ; PDF 1.4) Une langue spécifiant la langue naturelle pour tout le texte dans l'élément de structure, sauf lorsqu'elle est remplacée par des spécifications de langue pour les éléments de structure imbriqués ou le contenu balisé. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Remove](../../aspose.pdf.structure/element/remove/)() | Supprimer l'élément. |

### Voir aussi

* class [Element](../element/)
* namespace [Aspose.Pdf.Structure](../../aspose.pdf.structure/)
* assembly [Aspose.PDF](../../)


