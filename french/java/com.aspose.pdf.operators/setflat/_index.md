---
title: "SetFlat"
linktitle: "SetFlat"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe représentant l'opérateur i (définit la tolérance de planéité)."
type: docs
weight: 620
url: /fr/java/com.aspose.pdf.operators/setflat/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetFlat, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetFlat

```
public class SetFlat extends Operator
```

Classe représentant l'opérateur i (définit la tolérance de planéité).

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [SetFlat](#SetFlat-double-) | Initialise l'opérateur. |
| [SetFlat](#SetFlat-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.SetFlatnessTolerance-) | Constructeur de la classe opérateur. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepte un objet visiteur pour traiter l'opérateur. |
| [getFlatness](#getFlatness--) | Obtient la planéité. |
| [setFlatness](#setFlatness-double-) | Définit la planéité. |
| [toCommand](#toCommand--) | À usage interne uniquement ! |

### SetFlat {#SetFlat-double-}
```
public SetFlat(double flatness)
```

Initialise l'opérateur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| planéité |  | La valeur de la planéité. |

### SetFlat {#SetFlat-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.SetFlatnessTolerance-}
Constructeur de la classe opérateur.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accepte un objet visiteur pour traiter l'opérateur.

### getFlatness {#getFlatness--}
```
public double getFlatness()
```

Obtient la planéité.

**Returns:**
valeur double

### setFlatness {#setFlatness-double-}
```
public void setFlatness(double value)
```

Définit la planéité.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### toCommand {#toCommand--}
```
public com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand toCommand()
```

À usage interne uniquement !

**Returns:**
Valeur ICommand objet ICommand
