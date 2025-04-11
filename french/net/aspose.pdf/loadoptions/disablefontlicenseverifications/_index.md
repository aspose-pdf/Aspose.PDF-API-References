---
title: LoadOptions.DisableFontLicenseVerifications
second_title: Aspose.PDF for .NET API Reference
description: Propriété LoadOptions. Obtient ou définit un indicateur pour désactiver toutes les restrictions de licence pour toutes les polices lors du chargement du fichier. Lorsque vrai, permet d'exécuter des opérations avec des polices qui sont interdites par une licence de cette police, par exemple permet d'incorporer une police dans un document PDF même si les règles de licence interdisent l'incorporation de cette police. Par défaut faux
type: docs
weight: 10
url: /fr/net/aspose.pdf/loadoptions/disablefontlicenseverifications/
---
## Propriété LoadOptions.DisableFontLicenseVerifications

Obtient ou définit un indicateur pour désactiver toutes les restrictions de licence pour toutes les polices lors du chargement du fichier. Lorsque `true`, permet d'exécuter des opérations avec des polices qui sont interdites par une licence de cette police, par exemple permet d'incorporer une police dans un document PDF même si les règles de licence interdisent l'incorporation de cette police. Par défaut `false`.

```csharp
public bool DisableFontLicenseVerifications { get; set; }
```

## Remarques

Soyez prudent lorsque vous utilisez cet indicateur. Lorsqu'il est défini, cela signifie que la personne qui définit cet indicateur prend l'entière responsabilité des violations possibles de licence/droit sur elle-même. Elle le fait à ses propres risques. Il est fortement recommandé d'utiliser cet indicateur uniquement lorsque vous êtes pleinement convaincu que vous ne violez pas la loi sur le droit d'auteur.

### Voir aussi

* classe [LoadOptions](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)