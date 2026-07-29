---
title: "SetRGBColorStroke"
linktitle: "SetRGBColorStroke"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe représentant l'opérateur RG (définit la couleur RVB pour les opérateurs tracés)."
type: docs
weight: 720
url: /fr/java/com.aspose.pdf.operators/setrgbcolorstroke/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetRGBColorStroke, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetRGBColorStroke, com.aspose.pdf.operators.SetColorOperator, com.aspose.pdf.operators.SetRGBColorStroke

```
public class SetRGBColorStroke extends SetColorOperator
```

Classe représentant l'opérateur RG (définit la couleur RVB pour les opérateurs tracés).

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [SetRGBColorStroke](#SetRGBColorStroke-java.awt.Color-) | Initialise l'opérateur avec une couleur. |
| [SetRGBColorStroke](#SetRGBColorStroke-double-double-double-) | Constructeur pour le programme d'écriture. |
| [SetRGBColorStroke](#SetRGBColorStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetRGBStrokingColor-) | Constructeur de la classe opérateur. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepte l'objet visiteur pour traiter l'opérateur. |
| [getB](#getB--) | Obtient ou définit le composant bleu. Valeur: le niveau de bleu de 0,0 à 1,0 |
| [getCMYKColor](#getCMYKColor-double:A-double:A-) |  |
| [getColor](#getColor--) | Renvoie la couleur spécifiée par l'opérateur. |
| [getG](#getG--) | Obtient ou définit le composant vert. Valeur: le niveau de vert de 0,0 à 1,0 |
| [getR](#getR--) | Obtient ou définit le composant rouge. Valeur: le niveau de rouge de 0,0 à 1,0 |
| [setB](#setB-double-) | Obtient ou définit le composant bleu. Valeur: le niveau de bleu de 0,0 à 1,0 |
| [setG](#setG-double-) | Obtient ou définit le composant vert. Valeur: le niveau de vert de 0,0 à 1,0 |
| [setR](#setR-double-) | Obtient ou définit le composant rouge. Valeur: le niveau de rouge de 0,0 à 1,0 |
| [toString](#toString--) | Renvoie la représentation texte de l'opérateur. |

### SetRGBColorStroke {#SetRGBColorStroke-java.awt.Color-}
Initialise l'opérateur avec une couleur.

### SetRGBColorStroke {#SetRGBColorStroke-double-double-double-}
```
public SetRGBColorStroke(double r, double g, double b)
```

Constructeur pour le programme d'écriture.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| r |  | Le niveau de rouge de 0,0 à 1,0 |
| g |  | Le niveau de vert de 0,0 à 1,0 |
| b |  | Le niveau de bleu de 0,0 à 1,0 |

### SetRGBColorStroke {#SetRGBColorStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetRGBStrokingColor-}
Constructeur de la classe opérateur.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accepte l'objet visiteur pour traiter l'opérateur.

### getB {#getB--}
```
public final double getB()
```

Obtient ou définit le composant bleu. Valeur: le niveau de bleu de 0,0 à 1,0

**Returns:**
valeur réalisable

### getCMYKColor {#getCMYKColor-double:A-double:A-}
```
public void getCMYKColor(double[] rgb, double[] cmykOut)
```



**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rgb |  |  |
| cmykOut |  |  |

### getColor {#getColor--}
```
public Color getColor()
```

Renvoie la couleur spécifiée par l'opérateur.

**Returns:**
Couleur spécifiée par l'opérateur.

### getG {#getG--}
```
public final double getG()
```

Obtient ou définit le composant vert. Valeur: le niveau de vert de 0,0 à 1,0

**Returns:**
valeur réalisable

### getR {#getR--}
```
public final double getR()
```

Obtient ou définit le composant rouge. Valeur: le niveau de rouge de 0,0 à 1,0

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

### setG {#setG-double-}
```
public final void setG(double value)
```

Obtient ou définit le composant vert. Valeur: le niveau de vert de 0,0 à 1,0

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

### toString {#toString--}
```
public String toString()
```

Renvoie la représentation texte de l'opérateur.

**Returns:**
Représentation textuelle de l'opérateur.
