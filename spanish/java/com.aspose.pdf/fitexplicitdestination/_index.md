---
title: "FitExplicitDestination"
linktitle: "FitExplicitDestination"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa un destino explícito que muestra la página con su contenido ampliado lo justo para que toda la página quepa dentro de la ventana tanto horizontal como verticalmente. Si el."
type: docs
weight: 1550
url: /es/java/com.aspose.pdf/fitexplicitdestination/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExplicitDestination com.aspose.pdf.FitExplicitDestination, com.aspose.pdf.ExplicitDestination, com.aspose.pdf.FitExplicitDestination

**All Implemented Interfaces:**
IAppointment

```
public final class FitExplicitDestination extends ExplicitDestination
```

Representa un destino explícito que muestra la página con su contenido ampliado lo justo para que la página completa quepa dentro de la ventana tanto horizontal como verticalmente. Si los factores de ampliación horizontal y vertical requeridos son diferentes, use el menor de los dos, centrando la página dentro de la ventana en la otra dimensión.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [FitExplicitDestination](#FitExplicitDestination-com.aspose.pdf.Document-int-) | Crea un destino explícito remoto. |
| [FitExplicitDestination](#FitExplicitDestination-int-) | Crea un destino explícito remoto. |
| [FitExplicitDestination](#FitExplicitDestination-com.aspose.pdf.Page-) | Crea un destino explícito local. |

## Métodos

| Método | Descripción |
| --- | --- |
| [toString](#toString--) | Convierte el estado del objeto en un valor de cadena. Ejemplo: "1 Fit". |

### FitExplicitDestination {#FitExplicitDestination-com.aspose.pdf.Document-int-}
Crea un destino explícito remoto.

### FitExplicitDestination {#FitExplicitDestination-int-}
```
public FitExplicitDestination(int pageNumber)
```

Crea un destino explícito remoto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pageNumber |  | El número de página de destino del documento remoto. |

### FitExplicitDestination {#FitExplicitDestination-com.aspose.pdf.Page-}
Crea un destino explícito local.

### toString {#toString--}
```
public String toString()
```

Convierte el estado del objeto en un valor de cadena. Ejemplo: "1 Fit".

**Returns:**
Valor de cadena que representa el estado del objeto.
