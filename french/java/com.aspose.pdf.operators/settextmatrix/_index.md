---
title: "SetTextMatrix"
linktitle: "SetTextMatrix"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe représentant l'opérateur Tm (définit la matrice du texte)."
type: docs
weight: 750
url: /fr/java/com.aspose.pdf.operators/settextmatrix/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.SetTextMatrix, com.aspose.pdf.Operator, com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.SetTextMatrix, com.aspose.pdf.operators.TextOperator, com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.SetTextMatrix, com.aspose.pdf.operators.TextPlaceOperator, com.aspose.pdf.operators.SetTextMatrix

```
public class SetTextMatrix extends TextPlaceOperator
```

Classe représentant l'opérateur Tm (définit la matrice du texte).

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [SetTextMatrix](#SetTextMatrix-double-double-double-double-double-double-) | Initialise l'opérateur. |
| [SetTextMatrix](#SetTextMatrix-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textpositioningoperators.SetTextMatrix-) | Initialise l'opérateur. |
| [SetTextMatrix](#SetTextMatrix-com.aspose.pdf.Matrix-) | Initialise l'opérateur à l'aide d'une matrice. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepte l'objet visiteur pour traiter l'opérateur. |
| [getMatrix](#getMatrix--) | Argument de matrice de l'opérateur. |
| [setMatrix](#setMatrix-com.aspose.pdf.Matrix-) | Argument de matrice de l'opérateur. |
| [toString](#toString--) | Renvoie la représentation texte de l'opérateur. |

### SetTextMatrix {#SetTextMatrix-double-double-double-double-double-double-}
```
public SetTextMatrix(double a, double b, double c, double d, double e, double f)
```

Initialise l'opérateur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a |  | Coefficient A |
| b |  | Coefficient B |
| c |  | Coefficient C |
| d |  | Coefficient D |
| e |  | Coefficient E |
| f |  | Coefficient F |

### SetTextMatrix {#SetTextMatrix-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textpositioningoperators.SetTextMatrix-}
Initialise l'opérateur.

### SetTextMatrix {#SetTextMatrix-com.aspose.pdf.Matrix-}
Initialise l'opérateur à l'aide d'une matrice.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accepte l'objet visiteur pour traiter l'opérateur.

### getMatrix {#getMatrix--}
```
public Matrix getMatrix()
```

Argument de matrice de l'opérateur.

**Returns:**
Objet Matrix

### setMatrix {#setMatrix-com.aspose.pdf.Matrix-}
Argument de matrice de l'opérateur.

### toString {#toString--}
```
public String toString()
```

Renvoie la représentation texte de l'opérateur.

**Returns:**
Représentation textuelle de l'opérateur.
