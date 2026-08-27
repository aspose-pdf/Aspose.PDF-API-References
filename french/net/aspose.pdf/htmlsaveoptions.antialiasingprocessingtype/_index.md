---
title: "Enum HtmlSaveOptions.AntialiasingProcessingType"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Enum Aspose.Pdf.HtmlSaveOptionsAntialiasingProcessingType. Cette énumération décrit les mesures d'anticrénelage possibles pendant la conversion"
type: docs
weight: 5700
url: /fr/net/aspose.pdf/htmlsaveoptions.antialiasingprocessingtype/
---
## HtmlSaveOptions.AntialiasingProcessingType enumeration

Cette énumération décrit les mesures d'anticrénelage possibles pendant la conversion

```csharp
public enum AntialiasingProcessingType
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| NoAdditionalProcessing | `0` | Aucun traitement d'anticrénelage spécial n'est utilisé. C'est une option optimale pour la grande majorité des documents et elle ne nécessite pas de temps supplémentaire pendant la conversion |
| TryCorrectResultHtml | `1` | Dans ce cas, le convertisseur tente de détecter les zones contenant des éléments graphiques d'arrière-plan adjacents et de corriger le HTML résultant de manière appropriée. Cette option permet d'améliorer le résultat de l'exportation pour les documents contenant des arrière-plans composés de plusieurs éléments graphiques adjacents (pour ce type de documents, les rendus PDF, par ex. Acrobat Reader, essaient généralement d'adoucir les limites des éléments lors du rendu. Avec cette option, le convertisseur imite ce comportement des rendus PDF). Cette option permet d'améliorer la mise en page du résultat d'exportation pour certains documents spécifiques (qui utilisent de tels arrière-plans composés), mais elle nécessite un temps supplémentaire de traitement (généralement environ 10 à 15 % de temps additionnel). Ainsi, l'utilisation de ce mode dans le cas général n'est pas recommandée. |

### Voir aussi

* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


