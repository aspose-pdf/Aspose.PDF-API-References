---
title: "SetGrayStroke"
linktitle: "SetGrayStroke"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe représentant le niveau de gris pour les opérations tracées."
type: docs
weight: 650
url: /fr/java/com.aspose.pdf.operators/setgraystroke/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetGrayStroke, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetGrayStroke, com.aspose.pdf.operators.SetColorOperator, com.aspose.pdf.operators.SetGrayStroke

```
public class SetGrayStroke extends SetColorOperator
```

Classe représentant le niveau de gris pour les opérations tracées.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [SetGrayStroke](#SetGrayStroke-double-) | Initialise l'opérateur avec la couleur spécifiée. |
| [SetGrayStroke](#SetGrayStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetGrayStrokingColor-) | Constructeur de la classe opérateur. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepte l'objet visiteur pour traiter l'opérateur. |
| [getColor](#getColor--) | Renvoie la couleur spécifiée par l'opérateur. |
| [getGray](#getGray--) | Obtient ou définit le niveau de valeur de gris. |
| [setGray](#setGray-double-) | Obtient ou définit le niveau de valeur de gris. |
| [toString](#toString--) | Renvoie la représentation texte de l'opérateur. |

### SetGrayStroke {#SetGrayStroke-double-}
```
public SetGrayStroke(double gray)
```

Initialise l'opérateur avec la couleur spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| gris |  | Le niveau de valeur de gris. |

### SetGrayStroke {#SetGrayStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetGrayStrokingColor-}
Constructeur de la classe opérateur.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accepte l'objet visiteur pour traiter l'opérateur.

### getColor {#getColor--}
```
public Color getColor()
```

Renvoie la couleur spécifiée par l'opérateur.

**Returns:**
Couleur spécifiée par l'opérateur.

### getGray {#getGray--}
```
public final double getGray()
```

Obtient ou définit le niveau de valeur de gris.

**Returns:**
valeur double

### setGray {#setGray-double-}
```
public final void setGray(double value)
```

Obtient ou définit le niveau de valeur de gris.

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
