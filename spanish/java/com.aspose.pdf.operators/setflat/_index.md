---
title: "SetFlat"
linktitle: "SetFlat"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase que representa el operador i (establece la tolerancia de planitud)."
type: docs
weight: 620
url: /es/java/com.aspose.pdf.operators/setflat/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetFlat, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetFlat

```
public class SetFlat extends Operator
```

Clase que representa el operador i (establece la tolerancia de planitud).

## Constructores

| Constructor | Descripción |
| --- | --- |
| [SetFlat](#SetFlat-double-) | Inicializa el operador. |
| [SetFlat](#SetFlat-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.SetFlatnessTolerance-) | Constructor de la clase operador. |

## Métodos

| Método | Descripción |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Acepta un objeto visitante para procesar el operador. |
| [getFlatness](#getFlatness--) | Obtiene la planitud. |
| [setFlatness](#setFlatness-double-) | Establece la planitud. |
| [toCommand](#toCommand--) | ¡Solo para uso interno! |

### SetFlat {#SetFlat-double-}
```
public SetFlat(double flatness)
```

Inicializa el operador.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| planitud |  | El valor de la planitud. |

### SetFlat {#SetFlat-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.SetFlatnessTolerance-}
Constructor de la clase operador.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Acepta un objeto visitante para procesar el operador.

### getFlatness {#getFlatness--}
```
public double getFlatness()
```

Obtiene la planitud.

**Returns:**
valor double

### setFlatness {#setFlatness-double-}
```
public void setFlatness(double value)
```

Establece la planitud.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### toCommand {#toCommand--}
```
public com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand toCommand()
```

¡Solo para uso interno!

**Returns:**
Valor ICommand objeto ICommand
