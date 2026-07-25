---
title: "SetColor"
linktitle: "SetColor"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente la classe pour l'opérateur sc (définir la couleur pour les opérations sans tracé)."
type: docs
weight: 550
url: /fr/java/com.aspose.pdf.operators/setcolor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.BasicSetColorOperator com.aspose.pdf.operators.SetColor, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.BasicSetColorOperator com.aspose.pdf.operators.SetColor, com.aspose.pdf.operators.SetColorOperator, com.aspose.pdf.operators.BasicSetColorOperator com.aspose.pdf.operators.SetColor, com.aspose.pdf.operators.BasicSetColorOperator, com.aspose.pdf.operators.SetColor

```
public class SetColor extends BasicSetColorOperator
```

Représente la classe pour l'opérateur sc (définir la couleur pour les opérations sans tracé).

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [SetColor](#SetColor--) | Initialise l'opérateur. |
| [SetColor](#SetColor-double-) | Définir la couleur pour les opérateurs de tracé pour les espaces colorimétriques DeviceGray, CalGray et Indexed. |
| [SetColor](#SetColor-double:A-) | Constructeur qui permet de spécifier les composants de couleur. |
| [SetColor](#SetColor-double-double-double-) | Définir la couleur pour l'opérateur de tracé pour les espaces colorimétriques DeviceRGB, CalRGB et Lab. |
| [SetColor](#SetColor-double-double-double-double-) | Définir la couleur pour l'opérateur non-tracé dans l'espace colorimétrique CMYK |
| [SetColor](#SetColor-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetNonstrokingColor-) | Initialise l'opérateur. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepte l'objet visiteur pour traiter l'opérateur. |
| [getB](#getB--) | Obtient ou définit le composant bleu. Valeur: le niveau de bleu de 0,0 à 1,0 |
| [getC](#getC--) | Obtient ou définit le composant cyan. |
| [getColor](#getColor--) | Pas encore pris en charge. Retourne la couleur spécifiée par l'opérateur. |
| [getG](#getG--) | Obtient ou définit le composant vert. Valeur: le niveau de vert de 0,0 à 1,0 |
| [getK](#getK--) | Obtient ou définit le composant noir. |
| [getM](#getM--) | Obtient ou définit le composant magenta. |
| [getR](#getR--) | Obtient ou définit le composant rouge. Valeur: le niveau de rouge de 0,0 à 1,0 |
| [getY](#getY--) | Obtient ou définit le composant jaune. |
| [setB](#setB-double-) | Obtient ou définit le composant bleu. Valeur: le niveau de bleu de 0,0 à 1,0 |
| [setC](#setC-double-) | Obtient ou définit le composant cyan. |
| [setG](#setG-double-) | Obtient ou définit le composant vert. Valeur: le niveau de vert de 0,0 à 1,0 |
| [setK](#setK-double-) | Obtient ou définit le composant noir. |
| [setM](#setM-double-) | Obtient ou définit le composant magenta. |
| [setR](#setR-double-) | Obtient ou définit le composant rouge. Valeur: le niveau de rouge de 0,0 à 1,0 |
| [setY](#setY-double-) | Obtient ou définit le composant jaune. |
| [toString](#toString--) | Retourne la représentation sous forme de chaîne de la couleur. |

### SetColor {#SetColor--}
```
public SetColor()
```

Initialise l'opérateur.

### SetColor {#SetColor-double-}
```
public SetColor(double g)
```

Définir la couleur pour les opérateurs de tracé pour les espaces colorimétriques DeviceGray, CalGray et Indexed.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| g |  | Valeur de couleur. |

### SetColor {#SetColor-double:A-}
```
public SetColor(double[] color)
```

Constructeur qui permet de spécifier les composants de couleur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| couleur |  | Tableau de composants de couleur. |

### SetColor {#SetColor-double-double-double-}
```
public SetColor(double r, double g, double b)
```

Définir la couleur pour l'opérateur de tracé pour les espaces colorimétriques DeviceRGB, CalRGB et Lab.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| r |  | Composant rouge. |
| g |  | Composant vert. |
| b |  | Composant bleu. |

### SetColor {#SetColor-double-double-double-double-}
```
public SetColor(double c, double m, double y, double k)
```

Définir la couleur pour l'opérateur non-tracé dans l'espace colorimétrique CMYK

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| c |  | Composant cyan. |
| m |  | Composant magenta. |
| y |  | Composant jaune. |
| k |  | Composant noir. |

### SetColor {#SetColor-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetNonstrokingColor-}
Initialise l'opérateur.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accepte l'objet visiteur pour traiter l'opérateur.

### getB {#getB--}
```
public final double getB()
```

Obtient ou définit le composant bleu. Valeur: le niveau de bleu de 0,0 à 1,0

**Returns:**
valeur réalisable

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

Pas encore pris en charge. Retourne la couleur spécifiée par l'opérateur.

**Returns:**
Couleur de l'opérateur.

### getG {#getG--}
```
public final double getG()
```

Obtient ou définit le composant vert. Valeur: le niveau de vert de 0,0 à 1,0

**Returns:**
valeur réalisable

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

### getR {#getR--}
```
public final double getR()
```

Obtient ou définit le composant rouge. Valeur: le niveau de rouge de 0,0 à 1,0

**Returns:**
valeur réalisable

### getY {#getY--}
```
public final double getY()
```

Obtient ou définit le composant jaune.

**Returns:**
valeur réalisable

### setB {#setB-double-}
```
public final void setB(double value)
```

Obtient ou définit le composant bleu. Valeur: le niveau de bleu de 0,0 à 1,0

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur réalisable |

### setC {#setC-double-}
```
public final void setC(double value)
```

Obtient ou définit le composant cyan.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur réalisable |

### setG {#setG-double-}
```
public final void setG(double value)
```

Obtient ou définit le composant vert. Valeur: le niveau de vert de 0,0 à 1,0

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

### setR {#setR-double-}
```
public final void setR(double value)
```

Obtient ou définit le composant rouge. Valeur: le niveau de rouge de 0,0 à 1,0

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

### toString {#toString--}
```
public String toString()
```

Retourne la représentation sous forme de chaîne de la couleur.

**Returns:**
Représentation sous forme de chaîne de la couleur.
