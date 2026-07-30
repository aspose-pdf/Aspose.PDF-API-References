---
title: "LoadOptions.DisableFontLicenseVerifications"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Propriété LoadOptions. Obtient ou définit le drapeau permettant de désactiver toutes les restrictions de licence pour toutes les polices lors du chargement du fichier. Lorsque true, cela permet d'exécuter des opérations avec une police qui sont interdites par la licence de cette police, par exemple autoriser l'intégration d'une police dans un document PDF même si les règles de licence désactivent l'intégration pour cette police. Par défaut false."
type: docs
weight: 10
url: /fr/net/aspose.pdf/loadoptions/disablefontlicenseverifications/
---
## LoadOptions.DisableFontLicenseVerifications property

Obtient ou définit le drapeau permettant de désactiver toutes les restrictions de licence pour toutes les polices lors du chargement du fichier. Lorsque `true`, autorise l’exécution d’opérations avec une police qui sont interdites par la licence de cette police, par exemple autorise l’intégration d’une police dans un document PDF même si les règles de licence désactivent l’intégration pour cette police. Par défaut `false`.

```csharp
public bool DisableFontLicenseVerifications { get; set; }
```

## Remarques

Soyez prudent lors de l'utilisation de ce drapeau. Lorsqu'il est activé, cela signifie que la personne qui le définit assume toute la responsabilité des éventuelles violations de licence ou de loi. Ainsi, il le fait à ses propres risques. Il est fortement recommandé d'utiliser ce drapeau uniquement lorsque vous êtes pleinement sûr de ne pas enfreindre la législation sur le droit d'auteur.

### Voir aussi

* class [LoadOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


