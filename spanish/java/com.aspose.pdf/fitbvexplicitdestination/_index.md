---
title: "FitBVExplicitDestination"
linktitle: "FitBVExplicitDestination"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa un destino explícito que muestra la página con la coordenada horizontal izquierda posicionada en el borde izquierdo de la ventana y el contenido de la página ampliado justo."
type: docs
weight: 1540
url: /es/java/com.aspose.pdf/fitbvexplicitdestination/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExplicitDestination com.aspose.pdf.FitBVExplicitDestination, com.aspose.pdf.ExplicitDestination, com.aspose.pdf.FitBVExplicitDestination

**All Implemented Interfaces:**
IAppointment

```
public final class FitBVExplicitDestination extends ExplicitDestination
```

Representa un destino explícito que muestra la página con la coordenada horizontal izquierda posicionada en el borde izquierdo de la ventana y el contenido de la página ampliado lo justo para que la altura completa de su cuadro delimitador quepa dentro de la ventana. Un valor nulo para left indica que el valor actual de ese parámetro debe conservarse sin cambios.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [FitBVExplicitDestination](#FitBVExplicitDestination-com.aspose.pdf.Document-int-double-) | Crea un destino explícito remoto. |
| [FitBVExplicitDestination](#FitBVExplicitDestination-int-double-) | Crea un destino explícito remoto. |
| [FitBVExplicitDestination](#FitBVExplicitDestination-com.aspose.pdf.Page-double-) | Crea la instancia y la inicializa mediante el objeto de página DOM y el parámetro left. |

## Métodos

| Método | Descripción |
| --- | --- |
| [getLeft](#getLeft--) | Obtiene la coordenada horizontal left posicionada en el borde izquierdo de la ventana. |
| [toString](#toString--) | Convierte el estado del objeto en un valor de cadena. Ejemplo: "1 FitBV 100". |

### FitBVExplicitDestination {#FitBVExplicitDestination-com.aspose.pdf.Document-int-double-}
Crea un destino explícito remoto.

### FitBVExplicitDestination {#FitBVExplicitDestination-int-double-}
```
public FitBVExplicitDestination(int pageNumber, double left)
```

Crea un destino explícito remoto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pageNumber |  | El número de página de destino del documento remoto. |
| izquierda |  | La coordenada horizontal left posicionada en el borde izquierdo de la ventana. |

### FitBVExplicitDestination {#FitBVExplicitDestination-com.aspose.pdf.Page-double-}
Crea la instancia y la inicializa mediante el objeto de página DOM y el parámetro left.

### getLeft {#getLeft--}
```
public double getLeft()
```

Obtiene la coordenada horizontal left posicionada en el borde izquierdo de la ventana.

**Returns:**
valor double

### toString {#toString--}
```
public String toString()
```

Convierte el estado del objeto en un valor de cadena. Ejemplo: "1 FitBV 100".

**Returns:**
Valor de cadena que representa el estado del objeto.
