---
title: "SaveOptions.MarginPartStyle"
linktitle: "SaveOptions.MarginPartStyle"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente les informations d'une partie de la marge (haut, bas, côté gauche ou côté droit)."
type: docs
weight: 4420
url: /fr/java/com.aspose.pdf/saveoptions.marginpartstyle/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions.MarginPartStyle

```
public static class SaveOptions.MarginPartStyle extends Object
```

Représente les informations d'une partie de la marge (haut, bas, côté gauche ou côté droit).

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [MarginPartStyle](#MarginPartStyle-boolean-) | Crée une instance de la classe MarginPartStyle et initialise sa valeur en points |
| [MarginPartStyle](#MarginPartStyle-int-) | Crée une instance de la classe MarginPartStyle et définit sa valeur en points |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getValueInPoints](#getValueInPoints--) | Représente la marge en points. Doit être un nombre supérieur à zéro. |
| [isAuto](#isAuto--) | Obtient ou définit une valeur indiquant si cette instance est automatique. Valeur : {@code true} si cette instance est automatique ; sinon, {@code false}. |
| [setAuto](#setAuto-boolean-) | Obtient ou définit une valeur indiquant si cette instance est automatique. Valeur : {@code true} si cette instance est automatique ; sinon, {@code false}. |
| [setValueInPoints](#setValueInPoints-int-) | Représente la marge en points. Doit être un nombre supérieur à zéro. |

### MarginPartStyle {#MarginPartStyle-boolean-}
```
public MarginPartStyle(boolean isAuto)
```

Crée une instance de la classe MarginPartStyle et initialise sa valeur en points

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| isAuto |  | Marquer la marge comme automatique |

### MarginPartStyle {#MarginPartStyle-int-}
```
public MarginPartStyle(int valueInPoints)
```

Crée une instance de la classe MarginPartStyle et définit sa valeur en points

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valueInPoints |  | Valeur entière en points |

### getValueInPoints {#getValueInPoints--}
```
public final int getValueInPoints()
```

Représente la marge en points. Doit être un nombre supérieur à zéro.

**Returns:**
valeur int

### isAuto {#isAuto--}
```
public final boolean isAuto()
```

Obtient ou définit une valeur indiquant si cette instance est automatique. Valeur : {@code true} si cette instance est automatique ; sinon, {@code false}.

**Returns:**
valeur booléenne

### setAuto {#setAuto-boolean-}
```
public final void setAuto(boolean value)
```

Obtient ou définit une valeur indiquant si cette instance est automatique. Valeur : {@code true} si cette instance est automatique ; sinon, {@code false}.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setValueInPoints {#setValueInPoints-int-}
```
public final void setValueInPoints(int value)
```

Représente la marge en points. Doit être un nombre supérieur à zéro.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |
