---
title: "SetCharWidth"
linktitle: "SetCharWidth"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase que representa el operador d0 (establecer el ancho del glifo)."
type: docs
weight: 510
url: /es/java/com.aspose.pdf.operators/setcharwidth/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetCharWidth, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetCharWidth

```
public class SetCharWidth extends Operator
```

Clase que representa el operador d0 (establecer el ancho del glifo).

## Constructores

| Constructor | Descripción |
| --- | --- |
| [SetCharWidth](#SetCharWidth-double-double-) | Constructor. |
| [SetCharWidth](#SetCharWidth-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Constructor de la clase operador. |

## Métodos

| Método | Descripción |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Acepta un objeto visitante para procesar el operador. |
| [getWx](#getWx--) | Desplazamiento horizontal de la coordenada del glifo. |
| [getWy](#getWy--) | Desplazamiento vertical de la coordenada del glifo. |
| [toCommand](#toCommand--) | ¡Solo para uso interno! |
| [toString](#toString--) | Devuelve la representación de texto del operador. |

### SetCharWidth {#SetCharWidth-double-double-}
```
public SetCharWidth(double wx, double wy)
```

Constructor.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| wx |  | Desplazamiento horizontal del glifo. |
| wy |  | Desplazamiento vertical del glifo. |

### SetCharWidth {#SetCharWidth-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
Constructor de la clase operador.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Acepta un objeto visitante para procesar el operador.

### getWx {#getWx--}
```
public double getWx()
```

Desplazamiento horizontal de la coordenada del glifo.

**Returns:**
valor double

### getWy {#getWy--}
```
public double getWy()
```

Desplazamiento vertical de la coordenada del glifo.

**Returns:**
valor double

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
Representación textual de la representación
