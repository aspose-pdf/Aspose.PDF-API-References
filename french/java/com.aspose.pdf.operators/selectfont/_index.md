---
title: "SelectFont"
linktitle: "SelectFont"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe représentant l'opérateur Tf (définir la police et la taille du texte)."
type: docs
weight: 470
url: /fr/java/com.aspose.pdf.operators/selectfont/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextStateOperator com.aspose.pdf.operators.SelectFont, com.aspose.pdf.Operator, com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextStateOperator com.aspose.pdf.operators.SelectFont, com.aspose.pdf.operators.TextOperator, com.aspose.pdf.operators.TextStateOperator com.aspose.pdf.operators.SelectFont, com.aspose.pdf.operators.TextStateOperator, com.aspose.pdf.operators.SelectFont

```
public class SelectFont extends TextStateOperator
```

Classe représentant l'opérateur Tf (définir la police et la taille du texte).

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [SelectFont](#SelectFont-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textstateoperators.SetTextFont-) | Constructeur de la classe opérateur. |
| [SelectFont](#SelectFont-java.lang.String-double-) | Constructeur pour le programme d'écriture. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepte l'objet visiteur pour traiter l'opérateur. |
| [getName](#getName--) | Obtient le nom de la police. |
| [getSize](#getSize--) | Obtient la taille du texte. |
| [toString](#toString--) | Renvoie la représentation texte de l'opérateur. |

### SelectFont {#SelectFont-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textstateoperators.SetTextFont-}
Constructeur de la classe opérateur.

### SelectFont {#SelectFont-java.lang.String-double-}
Constructeur pour le programme d'écriture.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accepte l'objet visiteur pour traiter l'opérateur.

### getName {#getName--}
```
public String getName()
```

Obtient le nom de la police.

**Returns:**
valeur String

### getSize {#getSize--}
```
public double getSize()
```

Obtient la taille du texte.

**Returns:**
valeur double

### toString {#toString--}
```
public String toString()
```

Renvoie la représentation texte de l'opérateur.

**Returns:**
Représentation textuelle de l'opérateur.
