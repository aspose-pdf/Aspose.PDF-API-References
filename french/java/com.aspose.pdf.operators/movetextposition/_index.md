---
title: "MoveTextPosition"
linktitle: "MoveTextPosition"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe représentant l'opérateur Td (déplacer la position du texte)."
type: docs
weight: 390
url: /fr/java/com.aspose.pdf.operators/movetextposition/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.MoveTextPosition, com.aspose.pdf.Operator, com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.MoveTextPosition, com.aspose.pdf.operators.TextOperator, com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.MoveTextPosition, com.aspose.pdf.operators.TextPlaceOperator, com.aspose.pdf.operators.MoveTextPosition

```
public class MoveTextPosition extends TextPlaceOperator
```

Classe représentant l'opérateur Td (déplacer la position du texte).

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [MoveTextPosition](#MoveTextPosition-double-double-) | Initialise l'opérateur. |
| [MoveTextPosition](#MoveTextPosition-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textpositioningoperators.MoveToNextLine-) | Initialise l'opérateur. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepte l'objet visiteur pour traiter l'opérateur. |
| [getX](#getX--) | Coordonnée X de la position du texte. |
| [getY](#getY--) | Coordonnée Y de la position du texte. |
| [setX](#setX-double-) | Coordonnée X de la position du texte. |
| [setY](#setY-double-) | Coordonnée Y de la position du texte. |
| [toString](#toString--) | Renvoie la représentation texte de l'opérateur. |

### MoveTextPosition {#MoveTextPosition-double-double-}
```
public MoveTextPosition(double x, double y)
```

Initialise l'opérateur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x |  | Coordonnée X de la position du texte. |
| y |  | Coordonnée Y de la position du texte. |

### MoveTextPosition {#MoveTextPosition-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textpositioningoperators.MoveToNextLine-}
Initialise l'opérateur.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accepte l'objet visiteur pour traiter l'opérateur.

### getX {#getX--}
```
public double getX()
```

Coordonnée X de la position du texte.

**Returns:**
valeur double

### getY {#getY--}
```
public double getY()
```

Coordonnée Y de la position du texte.

**Returns:**
valeur double

### setX {#setX-double-}
```
public void setX(double value)
```

Coordonnée X de la position du texte.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### setY {#setY-double-}
```
public void setY(double value)
```

Coordonnée Y de la position du texte.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### toString {#toString--}
```
public String toString()
```

Renvoie la représentation texte de l'opérateur.

**Returns:**
Représentation textuelle de l'opérateur.
