---
title: Enum HtmlSaveOptions.AntialiasingProcessingType
second_title: Aspose.PDF for .NET API Reference
description: Enum Aspose.Pdf.HtmlSaveOptionsAntialiasingProcessingType. Cet enum décrit les mesures d'anticrénelage possibles lors de la conversion
type: docs
weight: 5570
url: /fr/net/aspose.pdf/htmlsaveoptions.antialiasingprocessingtype/
---
## Énumération HtmlSaveOptions.AntialiasingProcessingType

Cet enum décrit les mesures d'anticrénelage possibles lors de la conversion

```csharp
public enum AntialiasingProcessingType
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| NoAdditionalProcessing | `0` | aucun traitement d'anticrénelage spécial en cours d'utilisation. C'est une option optimale pour la grande majorité des documents et cela ne nécessite pas de temps supplémentaire lors de la conversion |
| TryCorrectResultHtml | `1` | Dans ce cas, le convertisseur essaie de détecter les endroits avec des éléments graphiques de fond adjacents et de corriger le HTML résultant de manière pertinente. Cette option permet d'améliorer le résultat de l'exportation pour les documents qui contiennent des arrière-plans construits à partir de plusieurs éléments graphiques adjacents (pour ce type de documents, les rendus PDF, par exemple Acrobat Reader, essaient généralement de lisser les frontières des éléments lors du rendu. Avec cette option, le convertisseur imite ce comportement des rendus PDF. Cette option permet d'améliorer la mise en page du résultat de l'exportation pour certains documents spécifiques (qui utilisent de tels arrière-plans composés), mais elle nécessite un temps de traitement supplémentaire (généralement environ 10-15 % de temps supplémentaire). Donc, l'utilisation de ce mode dans le cas général n'est pas recommandée. |

### Voir aussi

* classe [HtmlSaveOptions](../htmlsaveoptions/)
* espace de noms [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)