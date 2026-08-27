---
title: "SetLineWidth"
linktitle: "SetLineWidth"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe représentant l'opérateur w (définit la largeur de ligne)."
type: docs
weight: 690
url: /fr/java/com.aspose.pdf.operators/setlinewidth/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetLineWidth, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetLineWidth

```
public class SetLineWidth extends Operator
```

Classe représentant l'opérateur w (définit la largeur de ligne).

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [SetLineWidth](#SetLineWidth-double-) | Initialise l'opérateur avec la valeur de largeur. |
| [SetLineWidth](#SetLineWidth-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.SetLineWidth-) | Constructeur de la classe opérateur. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepte l'objet visiteur pour traiter l'opérateur. |
| [getWidth](#getWidth--) | Obtient la largeur de la ligne. |
| [setWidth](#setWidth-double-) | Définit la largeur de la ligne. |
| [toString](#toString--) | Renvoie la représentation texte de l'opérateur. |

### SetLineWidth {#SetLineWidth-double-}
```
public SetLineWidth(double width)
```

Initialise l'opérateur avec la valeur de largeur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| largeur |  | Valeur de la largeur. |

### SetLineWidth {#SetLineWidth-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.SetLineWidth-}
Constructeur de la classe opérateur.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accepte l'objet visiteur pour traiter l'opérateur.

### getWidth {#getWidth--}
```
public double getWidth()
```

Obtient la largeur de la ligne.

**Returns:**
largeur de la ligne.

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Définit la largeur de la ligne.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | largeur de la ligne. |

### toString {#toString--}
```
public String toString()
```

Renvoie la représentation texte de l'opérateur.

**Returns:**
Représentation textuelle de l'opérateur.
