---
title: "SetCMYKColorStroke"
linktitle: "SetCMYKColorStroke"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe représentant l'opérateur K (définir la couleur CMYK pour les opérations de tracé)."
type: docs
weight: 540
url: /fr/java/com.aspose.pdf.operators/setcmykcolorstroke/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetCMYKColorStroke, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetCMYKColorStroke, com.aspose.pdf.operators.SetColorOperator, com.aspose.pdf.operators.SetCMYKColorStroke

```
public class SetCMYKColorStroke extends SetColorOperator
```

Classe représentant l'opérateur K (définir la couleur CMYK pour les opérations de tracé).

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [SetCMYKColorStroke](#SetCMYKColorStroke-double-double-double-double-) | Initialise l'opérateur. |
| [SetCMYKColorStroke](#SetCMYKColorStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetCMYKStrokingColor-) | Constructeur de la classe opérateur. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepte l'objet visiteur pour traiter l'opérateur. |
| [getC](#getC--) | Obtient ou définit le composant cyan. |
| [getColor](#getColor--) | Renvoie la couleur RGB |
| [getK](#getK--) | Obtient ou définit le composant noir. |
| [getM](#getM--) | Obtient ou définit le composant magenta. |
| [getRGBColor](#getRGBColor-double:A-double:A-) |  |
| [getY](#getY--) | Obtient ou définit le composant jaune. |
| [setC](#setC-double-) | Obtient ou définit le composant cyan. |
| [setK](#setK-double-) | Obtient ou définit le composant noir. |
| [setM](#setM-double-) | Obtient ou définit le composant magenta. |
| [setY](#setY-double-) | Obtient ou définit le composant jaune. |

### SetCMYKColorStroke {#SetCMYKColorStroke-double-double-double-double-}
```
public SetCMYKColorStroke(double c, double m, double y, double k)
```

Initialise l'opérateur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| c |  | Le niveau de cyan de 0.0 à 1.0 |
| m |  | Le niveau de magenta de 0.0 à 1.0 |
| y |  | Le niveau de jaune de 0.0 à 1.0 |
| k |  | Le niveau de noir de 0.0 à 1.0 |

### SetCMYKColorStroke {#SetCMYKColorStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetCMYKStrokingColor-}
Constructeur de la classe opérateur.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accepte l'objet visiteur pour traiter l'opérateur.

### getC {#getC--}
```
public final double getC()
```

Obtient ou définit le composant cyan.

**Returns:**
valeur réalisable

### getColor {#getColor--}
```
public Color getColor()
```

Renvoie la couleur RGB

**Returns:**
Couleur spécifiée par l'opérateur.

### getK {#getK--}
```
public final double getK()
```

Obtient ou définit le composant noir.

**Returns:**
valeur réalisable

### getM {#getM--}
```
public final double getM()
```

Obtient ou définit le composant magenta.

**Returns:**
valeur réalisable

### getRGBColor {#getRGBColor-double:A-double:A-}
```
public void getRGBColor(double[] cmyk, double[] rgbOut)
```



**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| cmyk |  |  |
| rgbOut |  |  |

### getY {#getY--}
```
public final double getY()
```

Obtient ou définit le composant jaune.

**Returns:**
valeur réalisable

### setC {#setC-double-}
```
public final void setC(double value)
```

Obtient ou définit le composant cyan.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur réalisable |

### setK {#setK-double-}
```
public final void setK(double value)
```

Obtient ou définit le composant noir.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur réalisable |

### setM {#setM-double-}
```
public final void setM(double value)
```

Obtient ou définit le composant magenta.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur réalisable |

### setY {#setY-double-}
```
public final void setY(double value)
```

Obtient ou définit le composant jaune.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur réalisable |
