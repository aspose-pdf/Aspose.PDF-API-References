---
title: "SetColorSpace"
linktitle: "SetColorSpace"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase que representa el operador cs (establece el espacio de color para operaciones sin trazo)."
type: docs
weight: 580
url: /es/java/com.aspose.pdf.operators/setcolorspace/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorSpace, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorSpace

```
public class SetColorSpace extends Operator
```

Clase que representa el operador cs (establece el espacio de color para operaciones sin trazo).

## Constructores

| Constructor | Descripción |
| --- | --- |
| [SetColorSpace](#SetColorSpace-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetColorSpaceNonstroking-) | Constructor de la clase operador. |
| [SetColorSpace](#SetColorSpace-java.lang.String-) | Inicializa el operador. |

## Métodos

| Método | Descripción |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Acepta un objeto visitante para procesar el operador. |
| [getCommandName](#getCommandName--) | Obtiene el nombre del comando. |
| [getName](#getName--) | Obtiene el nombre del espacio de color. |
| [setName](#setName-java.lang.String-) | Establece el nombre del espacio de color. |
| [toCommand](#toCommand--) | ¡Solo para uso interno! |

### SetColorSpace {#SetColorSpace-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetColorSpaceNonstroking-}
Constructor de la clase operador.

### SetColorSpace {#SetColorSpace-java.lang.String-}
Inicializa el operador.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Acepta un objeto visitante para procesar el operador.

### getCommandName {#getCommandName--}
```
public String getCommandName()
```

Obtiene el nombre del comando.

**Returns:**
valor String

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
