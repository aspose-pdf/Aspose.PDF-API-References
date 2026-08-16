---
title: "SetLineCap"
linktitle: "SetLineCap"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase que representa el operador J (establece el estilo de extremo de línea)."
type: docs
weight: 670
url: /es/java/com.aspose.pdf.operators/setlinecap/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetLineCap, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetLineCap

```
public class SetLineCap extends Operator
```

Clase que representa el operador J (establece el estilo de extremo de línea).

## Constructores

| Constructor | Descripción |
| --- | --- |
| [SetLineCap](#SetLineCap-int-) |  |
| [SetLineCap](#SetLineCap-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.SetLineCapStyle-) |  |

## Métodos

| Método | Descripción |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Acepta un objeto visitante para procesar el operador. |
| [getCap](#getCap--) | Obtiene el estilo de los extremos de línea. |
| [setCap](#setCap-int-) | Establece el estilo de los extremos de línea. |

### SetLineCap {#SetLineCap-int-}
```
public SetLineCap(int cap)
```



**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| extremo |  |  |

### SetLineCap {#SetLineCap-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.SetLineCapStyle-}


### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Acepta un objeto visitante para procesar el operador.

### getCap {#getCap--}
```
public final int getCap()
```

Obtiene el estilo de los extremos de línea.

**Returns:**
valor int

### setCap {#setCap-int-}
```
public final void setCap(int value)
```

Establece el estilo de los extremos de línea.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |
