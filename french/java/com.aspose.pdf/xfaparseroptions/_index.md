---
title: "XfaParserOptions"
linktitle: "XfaParserOptions"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "classe pour gérer l'encapsulation des données associées"
type: docs
weight: 5560
url: /fr/java/com.aspose.pdf/xfaparseroptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XfaParserOptions

```
public class XfaParserOptions extends Object
```

classe pour gérer l'encapsulation des données associées

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [XfaParserOptions](#XfaParserOptions-java.awt.geom.Dimension2D-) | Initialise une nouvelle instance de la classe {@code XfaParserOptions}. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getBasePath](#getBasePath--) | Obtient ou définit le chemin de base. Valeur : le chemin de base. |
| [getEmulateRequierdGroups](#getEmulateRequierdGroups--) | Si cette propriété est vraie alors des rectangles rouges supplémentaires seront dessinés pour les Xfa "excluded groups" requis. Cette propriété a été introduite parce que l'absence d'analogies des groupes exclus lors de la conversion de la représentation Xfa des formulaires vers le standard. Elle est fausse par défaut. |
| [getPageSize](#getPageSize--) | Obtient ou définit la taille de la page. Valeur : la taille de la page. |
| [getSigned](#getSigned--) | Si cette propriété est vraie, le document sera converti en utilisant le flux de formulaire xfa (s'il existe). Si elle est fausse, le flux de formulaire xfa sera ignoré. Cette propriété a été introduite parce qu'il n'est pas clair comment calculer la somme de contrôle utilisée pour vérifier la signature. |
| [setBasePath](#setBasePath-java.net.URI-) | Obtient ou définit le chemin de base. Valeur : le chemin de base. |
| [setEmulateRequierdGroups](#setEmulateRequierdGroups-boolean-) | Si cette propriété est vraie alors des rectangles rouges supplémentaires seront dessinés pour les Xfa "excluded groups" requis. Cette propriété a été introduite parce que l'absence d'analogies des groupes exclus lors de la conversion de la représentation Xfa des formulaires vers le standard. Elle est fausse par défaut. |
| [setPageSize](#setPageSize-java.awt.geom.Dimension2D-) | Obtient ou définit la taille de la page. Valeur : la taille de la page. |
| [setSigned](#setSigned-boolean-) | Si cette propriété est vraie, le document sera converti en utilisant le flux de formulaire xfa (s'il existe). Si elle est fausse, le flux de formulaire xfa sera ignoré. Cette propriété a été introduite parce qu'il n'est pas clair comment calculer la somme de contrôle utilisée pour vérifier la signature. |

### XfaParserOptions {#XfaParserOptions-java.awt.geom.Dimension2D-}
Initialise une nouvelle instance de la classe {@code XfaParserOptions}.

### getBasePath {#getBasePath--}
```
public URI getBasePath()
```

Obtient ou définit le chemin de base. Valeur : le chemin de base.

**Returns:**
Objet URI

### getEmulateRequierdGroups {#getEmulateRequierdGroups--}
```
public boolean getEmulateRequierdGroups()
```

Si cette propriété est vraie alors des rectangles rouges supplémentaires seront dessinés pour les Xfa "excluded groups" requis. Cette propriété a été introduite parce que l'absence d'analogies des groupes exclus lors de la conversion de la représentation Xfa des formulaires vers le standard. Elle est fausse par défaut.

**Returns:**
valeur booléenne

### getPageSize {#getPageSize--}
```
public Dimension2D getPageSize()
```

Obtient ou définit la taille de la page. Valeur : la taille de la page.

**Returns:**
Objet Dimension2D

### getSigned {#getSigned--}
```
public boolean getSigned()
```

Si cette propriété est vraie, le document sera converti en utilisant le flux de formulaire xfa (s'il existe). Si elle est fausse, le flux de formulaire xfa sera ignoré. Cette propriété a été introduite parce qu'il n'est pas clair comment calculer la somme de contrôle utilisée pour vérifier la signature.

**Returns:**
valeur booléenne

### setBasePath {#setBasePath-java.net.URI-}
Obtient ou définit le chemin de base. Valeur : le chemin de base.

### setEmulateRequierdGroups {#setEmulateRequierdGroups-boolean-}
```
public void setEmulateRequierdGroups(boolean value)
```

Si cette propriété est vraie alors des rectangles rouges supplémentaires seront dessinés pour les Xfa "excluded groups" requis. Cette propriété a été introduite parce que l'absence d'analogies des groupes exclus lors de la conversion de la représentation Xfa des formulaires vers le standard. Elle est fausse par défaut.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setPageSize {#setPageSize-java.awt.geom.Dimension2D-}
Obtient ou définit la taille de la page. Valeur : la taille de la page.

### setSigned {#setSigned-boolean-}
```
public void setSigned(boolean value)
```

Si cette propriété est vraie, le document sera converti en utilisant le flux de formulaire xfa (s'il existe). Si elle est fausse, le flux de formulaire xfa sera ignoré. Cette propriété a été introduite parce qu'il n'est pas clair comment calculer la somme de contrôle utilisée pour vérifier la signature.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |
