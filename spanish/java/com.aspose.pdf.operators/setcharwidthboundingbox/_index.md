---
title: "SetCharWidthBoundingBox"
linktitle: "SetCharWidthBoundingBox"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase que representa el operador d1 (establecer el glifo y el cuadro delimitador)."
type: docs
weight: 520
url: /es/java/com.aspose.pdf.operators/setcharwidthboundingbox/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetCharWidthBoundingBox, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetCharWidthBoundingBox

```
public class SetCharWidthBoundingBox extends Operator
```

Clase que representa el operador d1 (establecer el glifo y el cuadro delimitador).

## Constructores

| Constructor | Descripción |
| --- | --- |
| [SetCharWidthBoundingBox](#SetCharWidthBoundingBox-double-double-double-double-double-double-) | Inicializa el operador SetCharWidthBoundingBox. |
| [SetCharWidthBoundingBox](#SetCharWidthBoundingBox-int-com.aspose.pdf.engine.commondata.pagecontent.operators.type3fonts.SetWidthAndBoundingInformation-) | Constructor de la clase operador. |

## Métodos

| Método | Descripción |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Acepta un objeto visitante para procesar el operador. |
| [getLlx](#getLlx--) | Coordenada horizontal inferior izquierda del rectángulo delimitador. |
| [getLly](#getLly--) | Coordenada vertical inferior izquierda del rectángulo delimitador. |
| [getUrx](#getUrx--) | Coordenada horizontal superior derecha del rectángulo delimitador. |
| [getUry](#getUry--) | Coordenada vertical superior derecha del rectángulo delimitador. |
| [getWx](#getWx--) | Desplazamiento horizontal del glifo. |
| [getWy](#getWy--) | Desplazamiento vertical del glifo. |
| [toCommand](#toCommand--) | ¡Solo para uso interno! |
| [toString](#toString--) | Devuelve la representación de texto del operador. |

### SetCharWidthBoundingBox {#SetCharWidthBoundingBox-double-double-double-double-double-double-}
```
public SetCharWidthBoundingBox(double wx, double wy, double llx, double lly, double urx, double ury)
```

Inicializa el operador SetCharWidthBoundingBox.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| wx |  | Denota el desplazamiento horizontal en la coordenada del glifo. |
| wy |  | Denota el desplazamiento vertical en la coordenada del glifo. Debe ser 0. |
| llx |  | Denota la coordenada X de la esquina inferior izquierda. |
| lly |  | Denota la coordenada Y de la esquina inferior izquierda. |
| urx |  | Denota la coordenada X de la esquina superior derecha. |
| ury |  | Denota la coordenada Y de la esquina superior derecha. |

### SetCharWidthBoundingBox {#SetCharWidthBoundingBox-int-com.aspose.pdf.engine.commondata.pagecontent.operators.type3fonts.SetWidthAndBoundingInformation-}
Constructor de la clase operador.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Acepta un objeto visitante para procesar el operador.

### getLlx {#getLlx--}
```
public double getLlx()
```

Coordenada horizontal inferior izquierda del rectángulo delimitador.

**Returns:**
valor double

### getLly {#getLly--}
```
public double getLly()
```

Coordenada vertical inferior izquierda del rectángulo delimitador.

**Returns:**
valor double

### getUrx {#getUrx--}
```
public double getUrx()
```

Coordenada horizontal superior derecha del rectángulo delimitador.

**Returns:**
valor double

### getUry {#getUry--}
```
public double getUry()
```

Coordenada vertical superior derecha del rectángulo delimitador.

**Returns:**
valor double

### getWx {#getWx--}
```
public double getWx()
```

Desplazamiento horizontal del glifo.

**Returns:**
valor double

### getWy {#getWy--}
```
public double getWy()
```

Desplazamiento vertical del glifo.

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
