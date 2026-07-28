---
title: "FitBHExplicitDestination"
linktitle: "FitBHExplicitDestination"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa un destino explícito que muestra la página con la coordenada vertical superior posicionada en el borde superior de la ventana y el contenido de la página ampliado justo."
type: docs
weight: 1530
url: /es/java/com.aspose.pdf/fitbhexplicitdestination/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExplicitDestination com.aspose.pdf.FitBHExplicitDestination, com.aspose.pdf.ExplicitDestination, com.aspose.pdf.FitBHExplicitDestination

**All Implemented Interfaces:**
IAppointment

```
public final class FitBHExplicitDestination extends ExplicitDestination
```

Representa un destino explícito que muestra la página con la coordenada vertical superior posicionada en el borde superior de la ventana y el contenido de la página ampliado lo justo para que el ancho completo de su cuadro delimitador quepa dentro de la ventana. Un valor nulo para top indica que el valor actual de ese parámetro debe conservarse sin cambios.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [FitBHExplicitDestination](#FitBHExplicitDestination-com.aspose.pdf.Document-int-double-) | Crea un destino explícito remoto. |
| [FitBHExplicitDestination](#FitBHExplicitDestination-int-double-) | Crea un destino explícito remoto. |
| [FitBHExplicitDestination](#FitBHExplicitDestination-com.aspose.pdf.Page-double-) | Crea la instancia y la inicializa mediante el objeto de página DOM y el parámetro top. |

## Métodos

| Método | Descripción |
| --- | --- |
| [getTop](#getTop--) | Obtiene la coordenada vertical superior posicionada en el borde superior de la ventana. |
| [toString](#toString--) | Convierte el estado del objeto en un valor de cadena. Ejemplo: "1 FitBH 100". |

### FitBHExplicitDestination {#FitBHExplicitDestination-com.aspose.pdf.Document-int-double-}
Crea un destino explícito remoto.

### FitBHExplicitDestination {#FitBHExplicitDestination-int-double-}
```
public FitBHExplicitDestination(int pageNumber, double top)
```

Crea un destino explícito remoto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pageNumber |  | El número de página de destino del documento remoto. |
| arriba |  | La coordenada vertical superior posicionada en el borde superior de la ventana. |

### FitBHExplicitDestination {#FitBHExplicitDestination-com.aspose.pdf.Page-double-}
Crea la instancia y la inicializa mediante el objeto de página DOM y el parámetro top.

### getTop {#getTop--}
```
public double getTop()
```

Obtiene la coordenada vertical superior posicionada en el borde superior de la ventana.

**Returns:**
valor double

### toString {#toString--}
```
public String toString()
```

Convierte el estado del objeto en un valor de cadena. Ejemplo: "1 FitBH 100".

**Returns:**
Valor de cadena que representa el estado del objeto.
