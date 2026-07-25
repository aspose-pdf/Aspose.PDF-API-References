---
title: "IPdfFileEditor.ContentsResizeValue"
linktitle: "IPdfFileEditor.ContentsResizeValue"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Valeur de la marge ou de la taille du contenu spécifiée en pourcentage des unités d'espace par défaut. Cette classe est utilisée dans ContentsResizeParameters."
type: docs
weight: 310
url: /fr/java/com.aspose.pdf.facades/ipdffileeditor.contentsresizevalue/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue

```
public static class IPdfFileEditor.ContentsResizeValue extends Object
```

Valeur de la marge ou de la taille du contenu spécifiée en pourcentage des unités d'espace par défaut. Cette classe est utilisée dans ContentsResizeParameters.

## Méthodes

| Méthode | Description |
| --- | --- |
| [auto](#auto--) | Initialise la valeur calculée automatiquement. |
| [getValue](#getValue--) | Obtient la valeur spécifiée. Utilisez la propriété Unit pour obtenir les unités de la valeur. |
| [isPercent](#isPercent--) | Renvoie vrai si la valeur est exprimée en pourcentages ; faux si la valeur est exprimée en unités par défaut. |
| [percents](#percents-double-) | Initialise la valeur en pourcentages. |
| [setPercentValue](#setPercentValue-double-) | Définit la valeur en pourcentages de la taille de la page. |
| [setUnitValue](#setUnitValue-double-) | Définit la valeur dans les unités d'espace par défaut. |
| [units](#units-double-) | Initialise la valeur dans les unités d'espace par défaut. |

### auto {#auto--}
```
public static IPdfFileEditor.ContentsResizeValue auto()
```

Initialise la valeur calculée automatiquement.

**Returns:**
Nouvelle instance de valeur.

### getValue {#getValue--}
```
public final double getValue()
```

Obtient la valeur spécifiée. Utilisez la propriété Unit pour obtenir les unités de la valeur.

**Returns:**
valeur double

### isPercent {#isPercent--}
```
public final boolean isPercent()
```

Renvoie vrai si la valeur est exprimée en pourcentages ; faux si la valeur est exprimée en unités par défaut.

**Returns:**
valeur booléenne

### percents {#percents-double-}
```
public static IPdfFileEditor.ContentsResizeValue percents(double value)
```

Initialise la valeur en pourcentages.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Valeur en pourcentages. |

**Returns:**
Nouvelle instance de valeur.

### setPercentValue {#setPercentValue-double-}
```
public final void setPercentValue(double value)
```

Définit la valeur en pourcentages de la taille de la page.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### setUnitValue {#setUnitValue-double-}
```
public final void setUnitValue(double value)
```

Définit la valeur dans les unités d'espace par défaut.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### units {#units-double-}
```
public static IPdfFileEditor.ContentsResizeValue units(double value)
```

Initialise la valeur dans les unités d'espace par défaut.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Valeur en unités. |

**Returns:**
Nouvelle instance de valeur.
