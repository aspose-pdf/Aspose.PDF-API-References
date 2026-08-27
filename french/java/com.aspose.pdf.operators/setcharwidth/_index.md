---
title: "SetCharWidth"
linktitle: "SetCharWidth"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe représentant l'opérateur d0 (définir la largeur du glyphe)."
type: docs
weight: 510
url: /fr/java/com.aspose.pdf.operators/setcharwidth/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetCharWidth, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetCharWidth

```
public class SetCharWidth extends Operator
```

Classe représentant l'opérateur d0 (définir la largeur du glyphe).

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [SetCharWidth](#SetCharWidth-double-double-) | Constructeur. |
| [SetCharWidth](#SetCharWidth-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Constructeur de la classe opérateur. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepte l'objet visiteur pour traiter l'opérateur. |
| [getWx](#getWx--) | Déplacement horizontal de la coordonnée du glyphe. |
| [getWy](#getWy--) | Déplacement vertical de la coordonnée du glyphe. |
| [toCommand](#toCommand--) | À usage interne uniquement ! |
| [toString](#toString--) | Renvoie la représentation texte de l'opérateur. |

### SetCharWidth {#SetCharWidth-double-double-}
```
public SetCharWidth(double wx, double wy)
```

Constructeur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| wx |  | Déplacement horizontal du glyphe. |
| wy |  | Déplacement vertical du glyphe. |

### SetCharWidth {#SetCharWidth-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
Constructeur de la classe opérateur.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accepte l'objet visiteur pour traiter l'opérateur.

### getWx {#getWx--}
```
public double getWx()
```

Déplacement horizontal de la coordonnée du glyphe.

**Returns:**
valeur double

### getWy {#getWy--}
```
public double getWy()
```

Déplacement vertical de la coordonnée du glyphe.

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
