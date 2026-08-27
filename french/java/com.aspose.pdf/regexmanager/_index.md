---
title: "RegexManager"
linktitle: "RegexManager"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Fournit un wrapper pour les opérations d'expressions régulières avec des paramètres de délai d'attente configurables."
type: docs
weight: 4130
url: /fr/java/com.aspose.pdf/regexmanager/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.RegexManager

```
public class RegexManager extends Object
```

Fournit un wrapper pour les opérations d'expressions régulières avec des paramètres de délai d'attente configurables.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [RegexManager](#RegexManager--) |  |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getMatchTimeout](#getMatchTimeout--) | Obtient ou définit le délai d'attente pour les opérations Regex dans toute la bibliothèque. La valeur par défaut est de 1000 ms. Valeur : un {@link double} représentant la durée d'attente par défaut. |
| [setMatchTimeout](#setMatchTimeout-int-) | Obtient ou définit le délai d'attente pour les opérations Regex dans toute la bibliothèque. La valeur par défaut est de 1000 ms. Valeur : |

### RegexManager {#RegexManager--}
```
public RegexManager()
```



### getMatchTimeout {#getMatchTimeout--}
```
public static int getMatchTimeout()
```

Obtient ou définit le délai d'attente pour les opérations Regex dans toute la bibliothèque. La valeur par défaut est de 1000 ms. Valeur : un {@link double} représentant la durée d'attente par défaut.

**Returns:**
valeur int

### setMatchTimeout {#setMatchTimeout-int-}
```
public static void setMatchTimeout(int value)
```

Obtient ou définit le délai d'attente pour les opérations Regex dans toute la bibliothèque. La valeur par défaut est de 1000 ms. Valeur :

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Un représentant la durée d'attente par défaut en millisecondes. |
