---
title: "Do"
linktitle: "Do"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase que representa el operador Do (Invoca XObject)."
type: docs
weight: 180
url: /es/java/com.aspose.pdf.operators/do/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.Do, com.aspose.pdf.Operator, com.aspose.pdf.operators.Do

```
public class Do extends Operator
```

Clase que representa el operador Do (Invoca XObject).

## Constructores

| Constructor | Descripción |
| --- | --- |
| [Do](#Do--) | Construye un nuevo operador Do. Se utiliza para recuperar todos los operadores Do, es decir, sin comprobar sus nombres de argumento. |
| [Do](#Do-int-com.aspose.pdf.engine.commondata.pagecontent.operators.xobjects.PaintXObject-) | Construye un nuevo operador Do. Se utiliza para recuperar todos los operadores Do, es decir, sin comprobar sus nombres de argumento. |
| [Do](#Do-java.lang.String-) | Construye un nuevo operador Do. Se utiliza para recuperar todos los operadores Do, es decir, sin comprobar sus nombres de argumento. |

## Métodos

| Método | Descripción |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Acepta un objeto visitante para procesar el operador. |
| [getCommandName](#getCommandName--) | Obtiene el nombre del comando |
| [getName](#getName--) | Obtiene el nombre del argumento XObject del operador. |
| [setName](#setName-java.lang.String-) | Establece el nombre del argumento XObject del operador. |
| [toCommand](#toCommand--) | ¡Solo para uso interno! |
| [toString](#toString--) | Devuelve la representación de texto del operador. |

### Do {#Do--}
```
public Do()
```

Construye un nuevo operador Do. Se utiliza para recuperar todos los operadores Do, es decir, sin comprobar sus nombres de argumento.

### Do {#Do-int-com.aspose.pdf.engine.commondata.pagecontent.operators.xobjects.PaintXObject-}
Construye un nuevo operador Do. Se utiliza para recuperar todos los operadores Do, es decir, sin comprobar sus nombres de argumento.

### Do {#Do-java.lang.String-}
Construye un nuevo operador Do. Se utiliza para recuperar todos los operadores Do, es decir, sin comprobar sus nombres de argumento.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Acepta un objeto visitante para procesar el operador.

### getCommandName {#getCommandName--}
```
public String getCommandName()
```

Obtiene el nombre del comando

**Returns:**
valor String

### getName {#getName--}
```
public String getName()
```

Obtiene el nombre del argumento XObject del operador.

**Returns:**
valor String

### setName {#setName-java.lang.String-}
Establece el nombre del argumento XObject del operador.

### toCommand {#toCommand--}
```
public com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand toCommand()
```

¡Solo para uso interno!

**Returns:**
Valor ICommand objeto ICommand

### toString {#toString--}
```
public String toString()
```

Devuelve la representación de texto del operador.

**Returns:**
Representación textual del operador.
