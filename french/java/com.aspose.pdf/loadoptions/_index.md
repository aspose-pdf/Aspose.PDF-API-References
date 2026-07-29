---
title: "LoadOptions"
linktitle: "LoadOptions"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Le type LoadOptions contient le niveau d'abstraction sur les options de chargement individuelles."
type: docs
weight: 2790
url: /fr/java/com.aspose.pdf/loadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions

```
public abstract class LoadOptions extends Object
```

Le type LoadOptions contient le niveau d'abstraction sur les options de chargement individuelles.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [LoadOptions](#LoadOptions--) |  |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getLoadFormat](#getLoadFormat--) | Représente le format de fichier décrit par {@code LoadOptions}. |
| [getWarningHandler](#getWarningHandler--) | Rappel pour gérer les avertissements générés. Le WarningHandler renvoie l'élément d'énumération ReturnAction spécifiant soit Continue, soit Abort. Continue est l'action par défaut et l'opération de chargement se poursuit, cependant l'utilisateur peut également renvoyer Abort, auquel cas l'opération de chargement doit s'arrêter. |
| [isDisableFontLicenseVerifications](#isDisableFontLicenseVerifications--) | Obtient ou définit le drapeau permettant de désactiver toutes les restrictions de licence pour toutes les polices lors du chargement du fichier. Lorsque {@code }, cela permet d'exécuter des opérations avec une police qui sont interdites par la licence de cette police, par exemple autorise l'intégration d'une police dans un document PDF même si les règles de licence désactivent l'intégration pour cette police. Par défaut {@code }. Soyez prudent lors de l'utilisation de ce drapeau. Lorsqu'il est activé, cela signifie que la personne qui le définit assume toute la responsabilité des éventuelles violations de licence ou de loi. Il le fait à ses propres risques. Il est fortement recommandé de n'utiliser ce drapeau que lorsque vous êtes pleinement convaincu de ne pas enfreindre la loi sur le droit d'auteur. |
| [setDisableFontLicenseVerifications](#setDisableFontLicenseVerifications-boolean-) | Obtient ou définit le drapeau permettant de désactiver toutes les restrictions de licence pour toutes les polices lors du chargement du fichier. Lorsque {@code }, cela permet d'exécuter des opérations avec une police qui sont interdites par la licence de cette police, par exemple autorise l'intégration d'une police dans un document PDF même si les règles de licence désactivent l'intégration pour cette police. Par défaut {@code }. Soyez prudent lors de l'utilisation de ce drapeau. Lorsqu'il est activé, cela signifie que la personne qui le définit assume toute la responsabilité des éventuelles violations de licence ou de loi. Il le fait à ses propres risques. Il est fortement recommandé de n'utiliser ce drapeau que lorsque vous êtes pleinement convaincu de ne pas enfreindre la loi sur le droit d'auteur. |
| [setWarningHandler](#setWarningHandler-com.aspose.pdf.WarningCallback-) | Rappel pour gérer les avertissements générés. Le WarningHandler renvoie l'élément d'énumération ReturnAction spécifiant soit Continue, soit Abort. Continue est l'action par défaut et l'opération de chargement se poursuit, cependant l'utilisateur peut également renvoyer Abort, auquel cas l'opération de chargement doit s'arrêter. |

### LoadOptions {#LoadOptions--}
```
public LoadOptions()
```



### getLoadFormat {#getLoadFormat--}
```
public LoadFormat getLoadFormat()
```

Représente le format de fichier décrit par {@code LoadOptions}.

**Returns:**
Élément LoadFormat @see LoadFormat

### getWarningHandler {#getWarningHandler--}
```
public WarningCallback getWarningHandler()
```

Rappel pour gérer les avertissements générés. Le WarningHandler renvoie l'élément d'énumération ReturnAction spécifiant soit Continue, soit Abort. Continue est l'action par défaut et l'opération de chargement se poursuit, cependant l'utilisateur peut également renvoyer Abort, auquel cas l'opération de chargement doit s'arrêter.

**Returns:**
Valeur IWarningCallback

### isDisableFontLicenseVerifications {#isDisableFontLicenseVerifications--}
```
public final boolean isDisableFontLicenseVerifications()
```

Obtient ou définit le drapeau permettant de désactiver toutes les restrictions de licence pour toutes les polices lors du chargement du fichier. Lorsque {@code }, cela permet d'exécuter des opérations avec une police qui sont interdites par la licence de cette police, par exemple autorise l'intégration d'une police dans un document PDF même si les règles de licence désactivent l'intégration pour cette police. Par défaut {@code }. Soyez prudent lors de l'utilisation de ce drapeau. Lorsqu'il est activé, cela signifie que la personne qui le définit assume toute la responsabilité des éventuelles violations de licence ou de loi. Il le fait à ses propres risques. Il est fortement recommandé de n'utiliser ce drapeau que lorsque vous êtes pleinement convaincu de ne pas enfreindre la loi sur le droit d'auteur.

**Returns:**
valeur booléenne

### setDisableFontLicenseVerifications {#setDisableFontLicenseVerifications-boolean-}
```
public final void setDisableFontLicenseVerifications(boolean value)
```

Obtient ou définit le drapeau permettant de désactiver toutes les restrictions de licence pour toutes les polices lors du chargement du fichier. Lorsque {@code }, cela permet d'exécuter des opérations avec une police qui sont interdites par la licence de cette police, par exemple autorise l'intégration d'une police dans un document PDF même si les règles de licence désactivent l'intégration pour cette police. Par défaut {@code }. Soyez prudent lors de l'utilisation de ce drapeau. Lorsqu'il est activé, cela signifie que la personne qui le définit assume toute la responsabilité des éventuelles violations de licence ou de loi. Il le fait à ses propres risques. Il est fortement recommandé de n'utiliser ce drapeau que lorsque vous êtes pleinement convaincu de ne pas enfreindre la loi sur le droit d'auteur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setWarningHandler {#setWarningHandler-com.aspose.pdf.WarningCallback-}
Rappel pour gérer les avertissements générés. Le WarningHandler renvoie l'élément d'énumération ReturnAction spécifiant soit Continue, soit Abort. Continue est l'action par défaut et l'opération de chargement se poursuit, cependant l'utilisateur peut également renvoyer Abort, auquel cas l'opération de chargement doit s'arrêter.
