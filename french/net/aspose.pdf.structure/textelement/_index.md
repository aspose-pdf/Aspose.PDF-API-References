---
title: TextElement
second_title: Référence de l'API Aspose.PDF pour .NET
description: Elément de texte général de la structure logique du document.
type: docs
weight: 6420
url: /fr/net/aspose.pdf.structure/textelement/
---
## TextElement class

Elément de texte général de la structure logique du document.

```csharp
public class TextElement : Element
```

## Propriétés

| Nom | La description |
| --- | --- |
| virtual [ActualText](../../aspose.pdf.structure/element/actualtext) { get; set; } | (Facultatif ; PDF 1.4) Texte qui remplace exactement l'élément de structure et ses enfants. Ce texte de remplacement (qui doit s'appliquer à un contenu aussi petit que possible) est utile lors de l'extraction du contenu du document à l'appui de accessibilité aux utilisateurs handicapés ou à d'autres fins. |
| virtual [Alt](../../aspose.pdf.structure/element/alt) { get; set; } | (Facultatif) Une autre description de l'élément de structure et de ses enfants sous human-readableform, qui est utile lors de l'extraction du contenu du document dans le support de l'accessibilité aux utilisateurs handicapés ou à d'autres fins. |
| [Children](../../aspose.pdf.structure/element/children) { get; } | Obtient la collection d'éléments enfants. |
| virtual [E](../../aspose.pdf.structure/element/e) { get; set; } | (Facultatif ; PDF 1.5) La forme développée d'une abréviation. |
| virtual [Lang](../../aspose.pdf.structure/element/lang) { get; set; } | (Facultatif ; PDF 1.4) Un langage spécifiant le langage naturel pour tous les text dans l'élément de structure, sauf lorsqu'il est remplacé par les spécifications de langage pour les éléments structure imbriqués ou le contenu marqué. |
| [Text](../../aspose.pdf.structure/textelement/text) { get; } | Obtient la valeur de l'élément de structure de texte. |

### Voir également

* class [Element](../element)
* espace de noms [Aspose.Pdf.Structure](../../aspose.pdf.structure)
* Assemblée [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
