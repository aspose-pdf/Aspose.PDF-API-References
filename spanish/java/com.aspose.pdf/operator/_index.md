---
title: "Operator"
linktitle: "Operator"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase abstracta que representa un operador."
type: docs
weight: 3180
url: /es/java/com.aspose.pdf/operator/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator

```
public abstract class Operator extends Object
```

Clase abstracta que representa un operador.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [Operator](#Operator-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | ¡Solo para uso interno! |

## Métodos

| Método | Descripción |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Acepta el visitante IOperatorSelector que proporciona el procesamiento de operadores. |
| [createFromCommandName](#createFromCommandName-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Crea un operador por el nombre de la instancia com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand. |
| [equals](#equals-com.aspose.pdf.Operator-) | Compara esta instancia con el objeto proporcionado. |
| [getCommand](#getCommand--) | Obtiene el comando |
| [getCommandName](#getCommandName--) | Obtiene el nombre del operador. |
| [getIndex](#getIndex--) | Obtiene el índice del operador en la lista de operadores de la página. |
| [isTextShowOperator](#isTextShowOperator-com.aspose.pdf.Operator-) | Determina si el operador es el operador responsable de la salida de texto (Tj, TJ, etc). |
| [setIndex](#setIndex-int-) | Establecer el índice del operador en la lista de operadores de la página. |
| [toString](#toString--) | Traduce el comando y los parámetros a una representación de cadena. |
| [valueEquals](#valueEquals-com.aspose.pdf.Operator-) | Compara esta instancia con el objeto proporcionado. |

### Operator {#Operator-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
¡Solo para uso interno!

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Acepta el visitante IOperatorSelector que proporciona el procesamiento de operadores.

### createFromCommandName {#createFromCommandName-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
Crea un operador por el nombre de la instancia com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand.

### equals {#equals-com.aspose.pdf.Operator-}
Compara esta instancia con el objeto proporcionado.

### getCommand {#getCommand--}
```
public com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand getCommand()
```

Obtiene el comando

**Returns:**
Objeto ICommand

### getCommandName {#getCommandName--}
```
public String getCommandName()
```

Obtiene el nombre del operador.

**Returns:**
valor String

### getIndex {#getIndex--}
```
public int getIndex()
```

Obtiene el índice del operador en la lista de operadores de la página.

**Returns:**
valor int

### isTextShowOperator {#isTextShowOperator-com.aspose.pdf.Operator-}
Determina si el operador es el operador responsable de la salida de texto (Tj, TJ, etc).

### setIndex {#setIndex-int-}
```
public void setIndex(int value)
```

Establecer el índice del operador en la lista de operadores de la página.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |

### toString {#toString--}
```
public String toString()
```

Traduce el comando y los parámetros a una representación de cadena.

**Returns:**
Texto del operador

### valueEquals {#valueEquals-com.aspose.pdf.Operator-}
Compara esta instancia con el objeto proporcionado.
