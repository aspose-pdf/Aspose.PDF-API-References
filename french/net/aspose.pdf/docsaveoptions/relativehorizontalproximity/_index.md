---
title: DocSaveOptions.RelativeHorizontalProximity
second_title: Aspose.PDF for .NET API Reference
description: Propriété DocSaveOptions. Dans Pdf, les mots peuvent être représentés intérieurement par des opérateurs qui impriment des mots en imprimant indépendamment leurs lettres ou syllabes. Ainsi, pour détecter des mots, nous devons parfois détecter des groupes de caractères indépendants qui sont en fait des mots. Ce paramètre définit la largeur de l'espace entre les éléments de texte qui doivent être considérés comme la distance entre les mots lors de la reconnaissance des mots dans le PDF source. La présence d'un espace vide d'au moins cette largeur entre les lettres signifie que les éléments textuels appartiennent à des mots différents. Il est normalisé à la taille de police - 1,0 signifie 100 % de la taille de police supposée du mot. ATTENTION ! Il n'est utilisé que dans les cas où le PDF source contient des polices spécifiques rarement utilisées pour lesquelles la valeur optimale ne peut pas être calculée à partir de la police. Ainsi, dans la grande majorité des cas, ce paramètre ne change rien dans le document résultant.
type: docs
weight: 120
url: /fr/net/aspose.pdf/docsaveoptions/relativehorizontalproximity/
---
## Propriété DocSaveOptions.RelativeHorizontalProximity

Dans Pdf, les mots peuvent être représentés intérieurement par des opérateurs qui impriment des mots en imprimant indépendamment leurs lettres ou syllabes. Ainsi, pour détecter des mots, nous devons parfois détecter des groupes de caractères indépendants qui sont en fait des mots. Ce paramètre définit la largeur de l'espace entre les éléments de texte (lettres, syllabes) qui doivent être considérés comme la distance entre les mots lors de la reconnaissance des mots dans le PDF source. (La présence d'un espace vide d'au moins cette largeur entre les lettres signifie que les éléments textuels appartiennent à des mots différents). Il est normalisé à la taille de police - 1,0 signifie 100 % de la taille de police supposée du mot. ATTENTION ! Il n'est utilisé que dans les cas où le PDF source contient des polices spécifiques rarement utilisées pour lesquelles la valeur optimale ne peut pas être calculée à partir de la police. Ainsi, dans la grande majorité des cas, ce paramètre ne change rien dans le document résultant.

```csharp
public float RelativeHorizontalProximity { get; set; }
```

### Voir aussi

* classe [DocSaveOptions](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)