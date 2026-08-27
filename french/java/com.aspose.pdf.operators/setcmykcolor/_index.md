---
title: "SetCMYKColor"
linktitle: "SetCMYKColor"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe représentant l'opérateur k (définir la couleur CMYK pour les opérations sans tracé)."
type: docs
weight: 530
url: /fr/java/com.aspose.pdf.operators/setcmykcolor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetCMYKColor, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetCMYKColor, com.aspose.pdf.operators.SetColorOperator, com.aspose.pdf.operators.SetCMYKColor

```
public class SetCMYKColor extends SetColorOperator
```

Classe représentant l'opérateur k (définir la couleur CMYK pour les opérations sans tracé).

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [SetCMYKColor](#SetCMYKColor-double-double-double-double-) | Initialise l'opérateur. |
| [SetCMYKColor](#SetCMYKColor-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetCMYKNonstrokingColor-) |  |

## Méthodes

| Méthode | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepte l'objet visiteur pour traiter l'opérateur. |
| [getC](#getC--) | Obtient ou définit le composant cyan. |
| [getColor](#getColor--) | Renvoie la couleur. |
| [getK](#getK--) | Obtient ou définit le composant noir. |
| [getM](#getM--) | Obtient ou définit le composant magenta. |
| [getRGBColor](#getRGBColor-double:A-double:A-) |  |
| [getY](#getY--) | Obtient ou définit le composant jaune. |
| [setC](#setC-double-) | Obtient ou définit le composant cyan. |
| [setK](#setK-double-) | Obtient ou définit le composant noir. |
| [setM](#setM-double-) | Obtient ou définit le composant magenta. |
| [setY](#setY-double-) | Obtient ou définit le composant jaune. |

### SetCMYKColor {#SetCMYKColor-double-double-double-double-}
```
public SetCMYKColor(double c, double m, double y, double k)
```

Initialise l'opérateur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| c |  | Le niveau de cyan de 0.0 à 1.0 |
| m |  | Le niveau de magenta de 0.0 à 1.0 |
| y |  | Le niveau de jaune de 0.0 à 1.0 |
| k |  | Le niveau de noir de 0.0 à 1.0 |

### SetCMYKColor {#SetCMYKColor-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetCMYKNonstrokingColor-}


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

Renvoie la couleur.

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
