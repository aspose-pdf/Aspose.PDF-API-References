---
title: "XYZExplicitDestination"
linktitle: "XYZExplicitDestination"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "<p> Representa el destino explícito que muestra la página con las coordenadas (izquierda, arriba) posicionadas en la esquina superior izquierda de la ventana y el contenido de la página."
type: docs
weight: 5800
url: /es/java/com.aspose.pdf/xyzexplicitdestination/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExplicitDestination com.aspose.pdf.XYZExplicitDestination, com.aspose.pdf.ExplicitDestination, com.aspose.pdf.XYZExplicitDestination

**All Implemented Interfaces:**
IAppointment

```
public final class XYZExplicitDestination extends ExplicitDestination
```

<p> Representa un destino explícito que muestra la página con las coordenadas (izquierda, arriba) posicionadas en la esquina superior izquierda de la ventana y el contenido de la página ampliado por el factor de zoom. Un valor nulo para cualquiera de los parámetros izquierda, arriba o zoom indica que el valor actual de ese parámetro debe mantenerse sin cambios. Un valor de zoom de 0 tiene el mismo significado que un valor nulo. </p> <hr> <p> Document doc = new Document("example.pdf"); XYZExplicitDestination dest = (XYZExplicitDestination)doc.getOutlines().get_Item(1).getDestination(); String left = dest.getLeft(); String top = dest.getTop(); String zoom = dest.getZoom(); </p>

## Constructores

| Constructor | Descripción |
| --- | --- |
| [XYZExplicitDestination](#XYZExplicitDestination-com.aspose.pdf.IDocument-int-double-double-double-) | Crea un destino explícito remoto. |
| [XYZExplicitDestination](#XYZExplicitDestination-int-double-double-double-) | Crea un destino explícito remoto. |
| [XYZExplicitDestination](#XYZExplicitDestination-com.aspose.pdf.Page-double-double-double-) | Crea la instancia y la inicializa mediante el objeto de página DOM y los parámetros visibles. |

## Métodos

| Método | Descripción |
| --- | --- |
| [createDestination](#createDestination-com.aspose.pdf.Page-double-double-double-boolean-) | Crea el destino a la ubicación especificada de la página considerando la rotación de la página si es necesario. |
| [createDestinationToUpperLeftCorner](#createDestinationToUpperLeftCorner-com.aspose.pdf.Page-) | Crea el destino a la página especificada. |
| [createDestinationToUpperLeftCorner](#createDestinationToUpperLeftCorner-com.aspose.pdf.Page-double-) | Crea el destino a la esquina superior izquierda de la página especificada. |
| [getLeft](#getLeft--) | Obtiene la coordenada horizontal izquierda de la esquina superior izquierda de la ventana. |
| [getTop](#getTop--) | Obtiene la coordenada vertical superior de la esquina superior izquierda de la ventana. |
| [getZoom](#getZoom--) | Obtiene el factor de zoom. |
| [toString](#toString--) | Convierte el estado del objeto en un valor de cadena. Ejemplo: "1 XYZ 100 200 3". |

### XYZExplicitDestination {#XYZExplicitDestination-com.aspose.pdf.IDocument-int-double-double-double-}
Crea un destino explícito remoto.

### XYZExplicitDestination {#XYZExplicitDestination-int-double-double-double-}
```
public XYZExplicitDestination(int pageNumber, double left, double top, double zoom)
```

Crea un destino explícito remoto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pageNumber |  | El número de página de destino del documento remoto. |
| izquierda |  | Coordenada horizontal izquierda de la esquina superior izquierda de la ventana. |
| arriba |  | Coordenada vertical superior de la esquina superior izquierda de la ventana. |
| zoom |  | Factor de zoom. |

### XYZExplicitDestination {#XYZExplicitDestination-com.aspose.pdf.Page-double-double-double-}
Crea la instancia y la inicializa mediante el objeto de página DOM y los parámetros visibles.

### createDestination {#createDestination-com.aspose.pdf.Page-double-double-double-boolean-}
Crea el destino a la ubicación especificada de la página considerando la rotación de la página si es necesario.

### createDestinationToUpperLeftCorner {#createDestinationToUpperLeftCorner-com.aspose.pdf.Page-}
Crea el destino a la página especificada.

### createDestinationToUpperLeftCorner {#createDestinationToUpperLeftCorner-com.aspose.pdf.Page-double-}
Crea el destino a la esquina superior izquierda de la página especificada.

### getLeft {#getLeft--}
```
public double getLeft()
```

Obtiene la coordenada horizontal izquierda de la esquina superior izquierda de la ventana.

**Returns:**
doble

### getTop {#getTop--}
```
public double getTop()
```

Obtiene la coordenada vertical superior de la esquina superior izquierda de la ventana.

**Returns:**
doble

### getZoom {#getZoom--}
```
public double getZoom()
```

Obtiene el factor de zoom.

**Returns:**
doble

### toString {#toString--}
```
public String toString()
```

Convierte el estado del objeto en un valor de cadena. Ejemplo: "1 XYZ 100 200 3".

**Returns:**
Valor de cadena que representa el estado del objeto.
