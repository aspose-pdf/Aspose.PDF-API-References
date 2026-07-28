---
title: "FitRExplicitDestination"
linktitle: "FitRExplicitDestination"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa un destino explícito que muestra la página con su contenido ampliado lo justo necesario para ajustar el rectángulo especificado por las coordenadas izquierda, inferior, derecha y."
type: docs
weight: 1570
url: /es/java/com.aspose.pdf/fitrexplicitdestination/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExplicitDestination com.aspose.pdf.FitRExplicitDestination, com.aspose.pdf.ExplicitDestination, com.aspose.pdf.FitRExplicitDestination

**All Implemented Interfaces:**
IAppointment

```
public final class FitRExplicitDestination extends ExplicitDestination
```

Representa un destino explícito que muestra la página con su contenido ampliado lo justo para que el rectángulo especificado por las coordenadas izquierda, inferior, derecha y superior quepa completamente dentro de la ventana tanto horizontal como verticalmente. Si los factores de ampliación horizontal y vertical requeridos son diferentes, use el menor de los dos, centrando el rectángulo dentro de la ventana en la otra dimensión. Un valor nulo para cualquiera de los parámetros puede resultar en un comportamiento impredecible.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [FitRExplicitDestination](#FitRExplicitDestination-com.aspose.pdf.Document-int-double-double-double-double-) | Crea un destino explícito remoto. |
| [FitRExplicitDestination](#FitRExplicitDestination-int-double-double-double-double-) | Crea un destino explícito remoto. |
| [FitRExplicitDestination](#FitRExplicitDestination-com.aspose.pdf.Page-double-double-double-double-) | Crea la instancia y la inicializa mediante el objeto de página DOM y los parámetros visibles. |

## Métodos

| Método | Descripción |
| --- | --- |
| [getBottom](#getBottom--) | Obtiene la coordenada vertical inferior del rectángulo visible. |
| [getLeft](#getLeft--) | Obtiene la coordenada horizontal izquierda del rectángulo visible. |
| [getRight](#getRight--) | Obtiene la coordenada horizontal derecha del rectángulo visible. |
| [getTop](#getTop--) | Obtiene la coordenada vertical superior del rectángulo visible. |
| [toString](#toString--) | Convierte el estado del objeto en un valor de cadena. Ejemplo: "1 FitR 100 200 300 400". |

### FitRExplicitDestination {#FitRExplicitDestination-com.aspose.pdf.Document-int-double-double-double-double-}
Crea un destino explícito remoto.

### FitRExplicitDestination {#FitRExplicitDestination-int-double-double-double-double-}
```
public FitRExplicitDestination(int pageNumber, double left, double bottom, double right, double top)
```

Crea un destino explícito remoto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pageNumber |  | El número de página de destino del documento remoto. |
| izquierda |  | Coordenada horizontal izquierda del rectángulo visible. |
| inferior |  | Coordenada vertical inferior del rectángulo visible. |
| derecha |  | Coordenada horizontal derecha del rectángulo visible. |
| arriba |  | Coordenada vertical superior del rectángulo visible. |

### FitRExplicitDestination {#FitRExplicitDestination-com.aspose.pdf.Page-double-double-double-double-}
Crea la instancia y la inicializa mediante el objeto de página DOM y los parámetros visibles.

### getBottom {#getBottom--}
```
public double getBottom()
```

Obtiene la coordenada vertical inferior del rectángulo visible.

**Returns:**
valor double

### getLeft {#getLeft--}
```
public double getLeft()
```

Obtiene la coordenada horizontal izquierda del rectángulo visible.

**Returns:**
valor double

### getRight {#getRight--}
```
public double getRight()
```

Obtiene la coordenada horizontal derecha del rectángulo visible.

**Returns:**
valor double

### getTop {#getTop--}
```
public double getTop()
```

Obtiene la coordenada vertical superior del rectángulo visible.

**Returns:**
valor double

### toString {#toString--}
```
public String toString()
```

Convierte el estado del objeto en un valor de cadena. Ejemplo: "1 FitR 100 200 300 400".

**Returns:**
Valor de cadena que representa el estado del objeto.
