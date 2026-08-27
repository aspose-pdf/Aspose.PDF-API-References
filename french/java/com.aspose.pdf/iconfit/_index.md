---
title: "IconFit"
linktitle: "IconFit"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Décrit comment l'icône de l'annotation widget doit être affichée à l'intérieur de son rectangle d'annotation."
type: docs
weight: 2210
url: /fr/java/com.aspose.pdf/iconfit/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.IconFit

```
public final class IconFit extends Object
```

Décrit comment l'icône de l'annotation widget doit être affichée à l'intérieur de son rectangle d'annotation.

## Méthodes

| Méthode | Description |
| --- | --- |
| [getLeftoverBottom](#getLeftoverBottom--) | Obtient l'espace à allouer en bas de l'icône. |
| [getLeftoverLeft](#getLeftoverLeft--) | Obtient l'espace à allouer à gauche de l'icône. |
| [getScalingMode](#getScalingMode--) | Le type de mise à l'échelle qui doit être utilisé. |
| [getScalingReason](#getScalingReason--) | Obtient la raison de mise à l'échelle. |
| [isSpreadOnBorder](#isSpreadOnBorder--) | Si vrai, indique que l'apparence du bouton doit être mise à l'échelle pour s'adapter entièrement aux limites de l'annotation sans tenir compte de l'épaisseur de la bordure. |
| [nameToScalingMode](#nameToScalingMode-java.lang.String-) | Convertit le nom du mode de mise à l'échelle en objet ScalingMode. |
| [nameToScalingReason](#nameToScalingReason-java.lang.String-) | Convertit le nom de la raison de mise à l'échelle en objet ScalingReason. |
| [scalingModeToName](#scalingModeToName-int-) | Convertit l'objet mode de mise à l'échelle en nom. |
| [scalingReasonToName](#scalingReasonToName-int-) | Convertit l'objet ScalingReason en nom. |
| [setLeftoverBottom](#setLeftoverBottom-double-) | Définit l'espace à allouer en bas de l'icône. |
| [setLeftoverLeft](#setLeftoverLeft-double-) | Définit l'espace à allouer à gauche de l'icône. |
| [setScalingMode](#setScalingMode-int-) | Le type de mise à l'échelle qui doit être utilisé. |
| [setScalingReason](#setScalingReason-int-) | Définit la raison de mise à l'échelle. |
| [setSpreadOnBorder](#setSpreadOnBorder-boolean-) | Si vrai, indique que l'apparence du bouton doit être mise à l'échelle pour s'adapter entièrement aux limites de l'annotation sans tenir compte de l'épaisseur de la bordure. |

### getLeftoverBottom {#getLeftoverBottom--}
```
public double getLeftoverBottom()
```

Obtient l'espace à allouer en bas de l'icône.

**Returns:**
espace à allouer en bas

### getLeftoverLeft {#getLeftoverLeft--}
```
public double getLeftoverLeft()
```

Obtient l'espace à allouer à gauche de l'icône.

**Returns:**
espace à allouer à gauche de l'icône.

### getScalingMode {#getScalingMode--}
```
public int getScalingMode()
```

Le type de mise à l'échelle qui doit être utilisé.

**Returns:**
Valeur ScalingMode @see ScalingMode

### getScalingReason {#getScalingReason--}
```
public int getScalingReason()
```

Obtient la raison de mise à l'échelle.

**Returns:**
Valeur ScalingReason @see ScalingReason

### isSpreadOnBorder {#isSpreadOnBorder--}
```
public boolean isSpreadOnBorder()
```

Si vrai, indique que l'apparence du bouton doit être mise à l'échelle pour s'adapter entièrement aux limites de l'annotation sans tenir compte de l'épaisseur de la bordure.

**Returns:**
valeur booléenne

### nameToScalingMode {#nameToScalingMode-java.lang.String-}
Convertit le nom du mode de mise à l'échelle en objet ScalingMode.

### nameToScalingReason {#nameToScalingReason-java.lang.String-}
Convertit le nom de la raison de mise à l'échelle en objet ScalingReason.

### scalingModeToName {#scalingModeToName-int-}
```
public static String scalingModeToName(int mode)
```

Convertit l'objet mode de mise à l'échelle en nom.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| mode |  | Objet du mode de mise à l'échelle. |

**Returns:**
Nom du mode de mise à l'échelle.

### scalingReasonToName {#scalingReasonToName-int-}
```
public static String scalingReasonToName(int reason)
```

Convertit l'objet ScalingReason en nom.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| raison |  | Objet de raison de mise à l'échelle à convertir. |

**Returns:**
Nom de la raison de mise à l'échelle.

### setLeftoverBottom {#setLeftoverBottom-double-}
```
public void setLeftoverBottom(double value)
```

Définit l'espace à allouer en bas de l'icône.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | espace à allouer en bas |

### setLeftoverLeft {#setLeftoverLeft-double-}
```
public void setLeftoverLeft(double value)
```

Définit l'espace à allouer à gauche de l'icône.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | espace à allouer à gauche de l'icône. |

### setScalingMode {#setScalingMode-int-}
```
public void setScalingMode(int value)
```

Le type de mise à l'échelle qui doit être utilisé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Valeur ScalingMode @see ScalingMode |

### setScalingReason {#setScalingReason-int-}
```
public void setScalingReason(int value)
```

Définit la raison de mise à l'échelle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Valeur ScalingReason @see ScalingReason |

### setSpreadOnBorder {#setSpreadOnBorder-boolean-}
```
public void setSpreadOnBorder(boolean value)
```

Si vrai, indique que l'apparence du bouton doit être mise à l'échelle pour s'adapter entièrement aux limites de l'annotation sans tenir compte de l'épaisseur de la bordure.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |
