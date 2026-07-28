---
title: "SubPathContainer"
linktitle: "SubPathContainer"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa una clase contenedora para elementos gráficos."
type: docs
weight: 10
url: /es/java/com.aspose.pdf.vector.extraction/subpathcontainer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.extraction.SubPathContainer

**All Implemented Interfaces:**
com.aspose.pdf.engine.utils.clustering.hierarchicalagglomerativeclustering.IDistanceMetric< SubPathContainer >, Comparable < SubPathContainer >

```
public class SubPathContainer extends Object implements com.aspose.pdf.engine.utils.clustering.hierarchicalagglomerativeclustering.IDistanceMetric< SubPathContainer >, Comparable < SubPathContainer >
```

Representa una clase contenedora para elementos gráficos.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [SubPathContainer](#SubPathContainer--) | Instancia una clase contenedora para elementos gráficos. |
| [SubPathContainer](#SubPathContainer-com.aspose.pdf.vector.GraphicElement-) | Instancia una clase contenedora para elementos gráficos. |
| [SubPathContainer](#SubPathContainer-int-com.aspose.pdf.vector.GraphicElement-) | Instancia una clase contenedora para elementos gráficos. |
| [SubPathContainer](#SubPathContainer-int-com.aspose.pdf.vector.GraphicElement-com.aspose.pdf.Rectangle-) | Instancia una clase contenedora para elementos gráficos. |
| [SubPathContainer](#SubPathContainer-com.aspose.pdf.Rectangle-) | Instancia una clase contenedora para elementos gráficos. |

## Métodos

| Método | Descripción |
| --- | --- |
| [calculateDistance](#calculateDistance-com.aspose.pdf.vector.extraction.SubPathContainer-com.aspose.pdf.vector.extraction.SubPathContainer-) | Calcula la distancia entre dos contenedores. |
| [compareTo](#compareTo-com.aspose.pdf.vector.extraction.SubPathContainer-) | Compara el objeto SubPathContainer actual con otro objeto SubPathContainer y devuelve un entero que indica si el objeto actual es menor, igual o mayor que el otro objeto. Los objetos se comparan por su ID numérico. |
| [distanceTo](#distanceTo-com.aspose.pdf.vector.extraction.SubPathContainer-) | Calcula la distancia entre este contenedor y otro contenedor. |
| [getGraphElement](#getGraphElement--) | Obtiene el elemento gráfico contenido. |
| [getId](#getId--) | Obtiene el Id del SubPathContainer. El Id es necesario para facilitar la depuración y la ordenación de los elementos durante el renderizado. |
| [getRect](#getRect--) | Representa un rectángulo del elemento contenido. |
| [toString](#toString--) | {@code } |

### SubPathContainer {#SubPathContainer--}
```
public SubPathContainer()
```

Instancia una clase contenedora para elementos gráficos.

### SubPathContainer {#SubPathContainer-com.aspose.pdf.vector.GraphicElement-}
Instancia una clase contenedora para elementos gráficos.

### SubPathContainer {#SubPathContainer-int-com.aspose.pdf.vector.GraphicElement-}
Instancia una clase contenedora para elementos gráficos.

### SubPathContainer {#SubPathContainer-int-com.aspose.pdf.vector.GraphicElement-com.aspose.pdf.Rectangle-}
Instancia una clase contenedora para elementos gráficos.

### SubPathContainer {#SubPathContainer-com.aspose.pdf.Rectangle-}
Instancia una clase contenedora para elementos gráficos.

### calculateDistance {#calculateDistance-com.aspose.pdf.vector.extraction.SubPathContainer-com.aspose.pdf.vector.extraction.SubPathContainer-}
Calcula la distancia entre dos contenedores.

### compareTo {#compareTo-com.aspose.pdf.vector.extraction.SubPathContainer-}
Compara el objeto SubPathContainer actual con otro objeto SubPathContainer y devuelve un entero que indica si el objeto actual es menor, igual o mayor que el otro objeto. Los objetos se comparan por su ID numérico.

### distanceTo {#distanceTo-com.aspose.pdf.vector.extraction.SubPathContainer-}
Calcula la distancia entre este contenedor y otro contenedor.

### getGraphElement {#getGraphElement--}
```
public final GraphicElement getGraphElement()
```

Obtiene el elemento gráfico contenido.

**Returns:**
Instancia de GraphicElement

### getId {#getId--}
```
public final int getId()
```

Obtiene el Id del SubPathContainer. El Id es necesario para facilitar la depuración y la ordenación de los elementos durante el renderizado.

**Returns:**
valor int

### getRect {#getRect--}
```
public final Rectangle getRect()
```

Representa un rectángulo del elemento contenido.

**Returns:**
Instancia de Rectangle

### toString {#toString--}
```
public String toString()
```

{@code }
