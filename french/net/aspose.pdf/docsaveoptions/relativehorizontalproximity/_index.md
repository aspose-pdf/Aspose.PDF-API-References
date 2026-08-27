---
title: "DocSaveOptions.RelativeHorizontalProximity"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Propriété DocSaveOptions. Dans les PDF, les mots peuvent être représentés en interne par des opérateurs qui impriment les mots en imprimant indépendamment leurs lettres ou syllabes. Ainsi, pour détecter les mots, il faut parfois détecter des groupes de caractères indépendants qui sont en fait des mots. Ce paramètre définit la largeur de l’espace entre les éléments de texte (lettres, syllabes) qui doit être considérée comme la distance entre les mots lors de la reconnaissance des mots dans le PDF source. La présence d’un espace vide d’au moins cette largeur entre les lettres signifie que les éléments textuels appartiennent à des mots différents. Il est normalisé à la taille de police 1,0, ce qui représente 100 % de la taille de police supposée des mots. ATTENTION : il n’est utilisé que dans les cas où le PDF source contient des polices spécifiques rarement utilisées pour lesquelles la valeur optimale ne peut pas être calculée à partir de la police. Ainsi, dans la grande majorité des cas, ce paramètre ne modifie rien dans le document résultant."
type: docs
weight: 120
url: /fr/net/aspose.pdf/docsaveoptions/relativehorizontalproximity/
---
## DocSaveOptions.RelativeHorizontalProximity property

Dans les PDF, les mots peuvent être représentés en interne par des opérateurs qui impriment les mots en affichant indépendamment leurs lettres ou syllabes. Ainsi, pour détecter les mots, il faut parfois identifier des groupes de caractères indépendants qui sont en réalité des mots. Ce paramètre définit la largeur de l'espace entre les éléments de texte (lettres, syllabes) qui doit être considérée comme la distance entre les mots lors de la reconnaissance des mots dans le PDF source. (la présence d'un espace vide d'au moins cette largeur entre les lettres signifie que les éléments textuels appartiennent à des mots différents). Il est normalisé à la taille de la police : 1,0 signifie 100 % de la taille de police supposée du mot. ATTENTION ! Il n'est utilisé que dans les cas où le PDF source contient des polices spécifiques rarement utilisées pour lesquelles la valeur optimale ne peut pas être calculée à partir de la police. Ainsi, dans la grande majorité des cas, ce paramètre ne modifie rien dans le document résultant.

```csharp
public float RelativeHorizontalProximity { get; set; }
```

### Voir aussi

* class [DocSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


