---
title: "FitBExplicitDestination"
linktitle: "FitBExplicitDestination"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa un destino explícito que muestra la página con su contenido ampliado justo lo suficiente para que su cuadro delimitador quepa completamente dentro de la ventana tanto horizontalmente como."
type: docs
weight: 1520
url: /es/java/com.aspose.pdf/fitbexplicitdestination/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExplicitDestination com.aspose.pdf.FitBExplicitDestination, com.aspose.pdf.ExplicitDestination, com.aspose.pdf.FitBExplicitDestination

**All Implemented Interfaces:**
IAppointment

```
public final class FitBExplicitDestination extends ExplicitDestination
```

Representa un destino explícito que muestra la página con su contenido ampliado lo justo para que su cuadro delimitador quepa completamente dentro de la ventana tanto horizontal como verticalmente. Si los factores de ampliación horizontal y vertical requeridos son diferentes, use el menor de los dos, centrando el cuadro delimitador dentro de la ventana en la otra dimensión.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [FitBExplicitDestination](#FitBExplicitDestination-com.aspose.pdf.Document-int-) | Crea un destino explícito remoto. |
| [FitBExplicitDestination](#FitBExplicitDestination-int-) | Crea un destino explícito remoto. |
| [FitBExplicitDestination](#FitBExplicitDestination-com.aspose.pdf.Page-) | Crea la instancia y la inicializa mediante el objeto de página DOM. |

## Métodos

| Método | Descripción |
| --- | --- |
| [toString](#toString--) | Convierte el estado del objeto en un valor de cadena. Ejemplo: "1 FitB". |

### FitBExplicitDestination {#FitBExplicitDestination-com.aspose.pdf.Document-int-}
Crea un destino explícito remoto.

### FitBExplicitDestination {#FitBExplicitDestination-int-}
```
public FitBExplicitDestination(int pageNumber)
```

Crea un destino explícito remoto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pageNumber |  | El número de página de destino del documento remoto. |

### FitBExplicitDestination {#FitBExplicitDestination-com.aspose.pdf.Page-}
Crea la instancia y la inicializa mediante el objeto de página DOM.

### toString {#toString--}
```
public String toString()
```

Convierte el estado del objeto en un valor de cadena. Ejemplo: "1 FitB".

**Returns:**
Valor de cadena que representa el estado del objeto.
