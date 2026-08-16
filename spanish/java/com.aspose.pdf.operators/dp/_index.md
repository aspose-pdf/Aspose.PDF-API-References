---
title: "DP"
linktitle: "DP"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase que representa el operador DP (designa un punto de contenido marcado)."
type: docs
weight: 190
url: /es/java/com.aspose.pdf.operators/dp/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.DP, com.aspose.pdf.Operator, com.aspose.pdf.operators.DP

```
public class DP extends Operator
```

Clase que representa el operador DP (designa un punto de contenido marcado).

## Constructores

| Constructor | Descripción |
| --- | --- |
| [DP](#DP-int-com.aspose.pdf.engine.commondata.pagecontent.operators.markedcontent.DesignateMarkedContentWithProperties-) | Constructor de la clase operador. |
| [DP](#DP-java.lang.String-) | Inicializa el operador. |
| [DP](#DP-java.lang.String-com.aspose.ms.System.Collections.Generic.Dictionary-) |  |

## Métodos

| Método | Descripción |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Acepta un objeto visitante para procesar el operador. |
| [getPropertiesDictionary](#getPropertiesDictionary--) | Obtiene el diccionario de propiedades |
| [getTag](#getTag--) | Obtiene la etiqueta de contenido marcado |
| [setPropertiesDictionary](#setPropertiesDictionary-com.aspose.ms.System.Collections.Generic.Dictionary-) | Establece el diccionario de propiedades |
| [setTag](#setTag-java.lang.String-) | Establece la etiqueta de contenido marcado |
| [toCommand](#toCommand--) | ¡Solo para uso interno! |
| [toString](#toString--) | Devuelve la representación de texto del operador. |

### DP {#DP-int-com.aspose.pdf.engine.commondata.pagecontent.operators.markedcontent.DesignateMarkedContentWithProperties-}
Constructor de la clase operador.

### DP {#DP-java.lang.String-}
Inicializa el operador.

### DP {#DP-java.lang.String-com.aspose.ms.System.Collections.Generic.Dictionary-}


### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Acepta un objeto visitante para procesar el operador.

### getPropertiesDictionary {#getPropertiesDictionary--}
```
public com.aspose.ms.System.Collections.Generic.Dictionary< String ,com.aspose.pdf.engine.commondata.pagecontent.operators.commands.CommandParameter> getPropertiesDictionary()
```

Obtiene el diccionario de propiedades

**Returns:**
IPdfDictionary valor

### getTag {#getTag--}
```
public String getTag()
```

Obtiene la etiqueta de contenido marcado

**Returns:**
valor String

### setPropertiesDictionary {#setPropertiesDictionary-com.aspose.ms.System.Collections.Generic.Dictionary-}
Establece el diccionario de propiedades

### setTag {#setTag-java.lang.String-}
Establece la etiqueta de contenido marcado

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
