---
title: "SetColorSpaceStroke"
linktitle: "SetColorSpaceStroke"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase que representa el operador CS (establece el color para operaciones con trazo)."
type: docs
weight: 590
url: /es/java/com.aspose.pdf.operators/setcolorspacestroke/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorSpaceStroke, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorSpaceStroke

```
public class SetColorSpaceStroke extends Operator
```

Clase que representa el operador CS (establece el color para operaciones con trazo).

## Constructores

| Constructor | Descripción |
| --- | --- |
| [SetColorSpaceStroke](#SetColorSpaceStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetColorSpaceStroking-) | Constructor de la clase operador. |
| [SetColorSpaceStroke](#SetColorSpaceStroke-java.lang.String-) | Inicializa el operador. |

## Métodos

| Método | Descripción |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Acepta un objeto visitante para procesar el operador. |
| [getName](#getName--) | Obtiene el nombre del espacio de color. |
| [setName](#setName-java.lang.String-) | Establece el nombre del espacio de color. |
| [toCommand](#toCommand--) | ¡Solo para uso interno! |

### SetColorSpaceStroke {#SetColorSpaceStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetColorSpaceStroking-}
Constructor de la clase operador.

### SetColorSpaceStroke {#SetColorSpaceStroke-java.lang.String-}
Inicializa el operador.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Acepta un objeto visitante para procesar el operador.

### getName {#getName--}
```
public String getName()
```

Obtiene el nombre del espacio de color.

**Returns:**
valor String

### setName {#setName-java.lang.String-}
Establece el nombre del espacio de color.

### toCommand {#toCommand--}
```
public com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand toCommand()
```

¡Solo para uso interno!

**Returns:**
Valor ICommand objeto ICommand
