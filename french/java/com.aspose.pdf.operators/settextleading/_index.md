---
title: "SetTextLeading"
linktitle: "SetTextLeading"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe représentant l'opérateur TL (définit l'interligne du texte)."
type: docs
weight: 740
url: /fr/java/com.aspose.pdf.operators/settextleading/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextStateOperator com.aspose.pdf.operators.SetTextLeading, com.aspose.pdf.Operator, com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextStateOperator com.aspose.pdf.operators.SetTextLeading, com.aspose.pdf.operators.TextOperator, com.aspose.pdf.operators.TextStateOperator com.aspose.pdf.operators.SetTextLeading, com.aspose.pdf.operators.TextStateOperator, com.aspose.pdf.operators.SetTextLeading

```
public class SetTextLeading extends TextStateOperator
```

Classe représentant l'opérateur TL (définit l'interligne du texte).

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [SetTextLeading](#SetTextLeading-double-) | Constructeur pour l'opérateur de texte leadign. |
| [SetTextLeading](#SetTextLeading-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textstateoperators.SetTextLeading-) |  |

## Méthodes

| Méthode | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepte l'objet visiteur pour traiter l'opérateur. |
| [getLeading](#getLeading--) | Obtient l'interligne du texte. |
| [setLeading](#setLeading-double-) | Définit l'interligne du texte. |
| [toString](#toString--) | Produit le code texte de l'opérateur. |

### SetTextLeading {#SetTextLeading-double-}
```
public SetTextLeading(double leading)
```

Constructeur pour l'opérateur de texte leadign.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| leading |  | Interligne du texte. |

### SetTextLeading {#SetTextLeading-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textstateoperators.SetTextLeading-}


### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accepte l'objet visiteur pour traiter l'opérateur.

### getLeading {#getLeading--}
```
public double getLeading()
```

Obtient l'interligne du texte.

**Returns:**
valeur double

### setLeading {#setLeading-double-}
```
public void setLeading(double value)
```

Définit l'interligne du texte.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### toString {#toString--}
```
public String toString()
```

Produit le code texte de l'opérateur.

**Returns:**
Représentation textuelle de l'opérateur.
