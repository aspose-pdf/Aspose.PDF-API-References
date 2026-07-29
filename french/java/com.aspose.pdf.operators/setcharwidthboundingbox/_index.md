---
title: "SetCharWidthBoundingBox"
linktitle: "SetCharWidthBoundingBox"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe représentant l'opérateur d1 (définir le glyphe et la boîte englobante)."
type: docs
weight: 520
url: /fr/java/com.aspose.pdf.operators/setcharwidthboundingbox/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetCharWidthBoundingBox, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetCharWidthBoundingBox

```
public class SetCharWidthBoundingBox extends Operator
```

Classe représentant l'opérateur d1 (définir le glyphe et la boîte englobante).

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [SetCharWidthBoundingBox](#SetCharWidthBoundingBox-double-double-double-double-double-double-) | Initialise l'opérateur SetCharWidthBoundingBox. |
| [SetCharWidthBoundingBox](#SetCharWidthBoundingBox-int-com.aspose.pdf.engine.commondata.pagecontent.operators.type3fonts.SetWidthAndBoundingInformation-) | Constructeur de la classe opérateur. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepte l'objet visiteur pour traiter l'opérateur. |
| [getLlx](#getLlx--) | Coordonnée horizontale du coin inférieur gauche du rectangle de délimitation. |
| [getLly](#getLly--) | Coordonnée verticale du coin inférieur gauche du rectangle de délimitation. |
| [getUrx](#getUrx--) | Coordonnée horizontale du coin supérieur droit du rectangle de délimitation. |
| [getUry](#getUry--) | Coordonnée verticale du coin supérieur droit du rectangle de délimitation. |
| [getWx](#getWx--) | Déplacement horizontal du glyphe. |
| [getWy](#getWy--) | Déplacement vertical du glyphe. |
| [toCommand](#toCommand--) | À usage interne uniquement ! |
| [toString](#toString--) | Renvoie la représentation texte de l'opérateur. |

### SetCharWidthBoundingBox {#SetCharWidthBoundingBox-double-double-double-double-double-double-}
```
public SetCharWidthBoundingBox(double wx, double wy, double llx, double lly, double urx, double ury)
```

Initialise l'opérateur SetCharWidthBoundingBox.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| wx |  | Indique le déplacement horizontal dans le système de coordonnées du glyphe. |
| wy |  | Indique le déplacement vertical dans le système de coordonnées du glyphe. Doit être 0. |
| llx |  | Indique la coordonnée X du coin inférieur gauche. |
| lly |  | Indique la coordonnée Y du coin inférieur gauche. |
| urx |  | Indique la coordonnée X du coin supérieur droit. |
| ury |  | Indique la coordonnée Y du coin supérieur droit. |

### SetCharWidthBoundingBox {#SetCharWidthBoundingBox-int-com.aspose.pdf.engine.commondata.pagecontent.operators.type3fonts.SetWidthAndBoundingInformation-}
Constructeur de la classe opérateur.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accepte l'objet visiteur pour traiter l'opérateur.

### getLlx {#getLlx--}
```
public double getLlx()
```

Coordonnée horizontale du coin inférieur gauche du rectangle de délimitation.

**Returns:**
valeur double

### getLly {#getLly--}
```
public double getLly()
```

Coordonnée verticale du coin inférieur gauche du rectangle de délimitation.

**Returns:**
valeur double

### getUrx {#getUrx--}
```
public double getUrx()
```

Coordonnée horizontale du coin supérieur droit du rectangle de délimitation.

**Returns:**
valeur double

### getUry {#getUry--}
```
public double getUry()
```

Coordonnée verticale du coin supérieur droit du rectangle de délimitation.

**Returns:**
valeur double

### getWx {#getWx--}
```
public double getWx()
```

Déplacement horizontal du glyphe.

**Returns:**
valeur double

### getWy {#getWy--}
```
public double getWy()
```

Déplacement vertical du glyphe.

**Returns:**
valeur double

### toCommand {#toCommand--}
```
public com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand toCommand()
```

À usage interne uniquement !

**Returns:**
Valeur ICommand objet ICommand

### toString {#toString--}
```
public String toString()
```

Renvoie la représentation texte de l'opérateur.

**Returns:**
Représentation textuelle de la représentation
