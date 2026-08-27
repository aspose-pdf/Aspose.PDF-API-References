---
title: "SetLineCap"
linktitle: "SetLineCap"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe représentant l'opérateur J (définit le style de terminaison de ligne)."
type: docs
weight: 670
url: /fr/java/com.aspose.pdf.operators/setlinecap/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetLineCap, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetLineCap

```
public class SetLineCap extends Operator
```

Classe représentant l'opérateur J (définit le style de terminaison de ligne).

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [SetLineCap](#SetLineCap-int-) |  |
| [SetLineCap](#SetLineCap-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.SetLineCapStyle-) |  |

## Méthodes

| Méthode | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepte l'objet visiteur pour traiter l'opérateur. |
| [getCap](#getCap--) | Obtient le style des caps de ligne. |
| [setCap](#setCap-int-) | Définit le style des caps de ligne. |

### SetLineCap {#SetLineCap-int-}
```
public SetLineCap(int cap)
```



**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| cap |  |  |

### SetLineCap {#SetLineCap-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.SetLineCapStyle-}


### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accepte l'objet visiteur pour traiter l'opérateur.

### getCap {#getCap--}
```
public final int getCap()
```

Obtient le style des caps de ligne.

**Returns:**
valeur int

### setCap {#setCap-int-}
```
public final void setCap(int value)
```

Définit le style des caps de ligne.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |
