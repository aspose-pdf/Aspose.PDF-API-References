---
title: "ConcatenateMatrix"
linktitle: "ConcatenateMatrix"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe représentant l'opérateur cm (concaténer la matrice à la matrice de transformation courante)."
type: docs
weight: 140
url: /fr/java/com.aspose.pdf.operators/concatenatematrix/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.ConcatenateMatrix, com.aspose.pdf.Operator, com.aspose.pdf.operators.ConcatenateMatrix

```
public class ConcatenateMatrix extends Operator
```

Classe représentant l'opérateur cm (concaténer la matrice à la matrice de transformation courante).

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ConcatenateMatrix](#ConcatenateMatrix-double-double-double-double-double-double-) | Constructeur de la classe opérateur. |
| [ConcatenateMatrix](#ConcatenateMatrix-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.ModifyCurrentTransformationMatrix-) | Constructeur de la classe opérateur. |
| [ConcatenateMatrix](#ConcatenateMatrix-com.aspose.pdf.Matrix-) | Initialise l'opérateur à l'aide d'une matrice. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepte l'objet visiteur pour traiter l'opérateur. |
| [getMatrix](#getMatrix--) | Argument de matrice de l'opérateur. |
| [setMatrix](#setMatrix-com.aspose.pdf.Matrix-) | Argument de matrice de l'opérateur. |
| [toCommand](#toCommand--) | À usage interne uniquement ! |
| [toString](#toString--) | Renvoie la représentation texte de l'opérateur. |

### ConcatenateMatrix {#ConcatenateMatrix-double-double-double-double-double-double-}
```
public ConcatenateMatrix(double a, double b, double c, double d, double e, double f)
```

Constructeur de la classe opérateur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a |  | Coefficient A |
| b |  | Coefficient B |
| c |  | Coefficient C |
| d |  | Coefficient D |
| e |  | Coefficient E |
| f |  | Coefficient F |

### ConcatenateMatrix {#ConcatenateMatrix-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.ModifyCurrentTransformationMatrix-}
Constructeur de la classe opérateur.

### ConcatenateMatrix {#ConcatenateMatrix-com.aspose.pdf.Matrix-}
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
