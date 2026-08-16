---
title: "GraphicsAbsorber"
linktitle: "GraphicsAbsorber"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa un objeto absorbente de elementos gráficos. Realiza búsquedas de gráficos y proporciona acceso a los resultados de búsqueda a través de {@code GraphicsAbsorber.Elements}({@link."
type: docs
weight: 30
url: /es/java/com.aspose.pdf.vector/graphicsabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.GraphicsAbsorber

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable

```
public class GraphicsAbsorber extends Object implements com.aspose.ms.System.IDisposable
```

Representa un objeto absorbente de elementos gráficos. Realiza la búsqueda de gráficos y proporciona acceso a los resultados de la búsqueda a través de la colección {@code GraphicsAbsorber.Elements}({@link GraphicsAbsorber#getElements}).

## Constructores

| Constructor | Descripción |
| --- | --- |
| [GraphicsAbsorber](#GraphicsAbsorber--) |  |

## Métodos

| Método | Descripción |
| --- | --- |
| [dispose](#dispose--) | Libera todos los recursos utilizados por la clase {@link GraphicsAbsorber}. |
| [getElements](#getElements--) | Obtiene la colección de ocurrencias de búsqueda que se presentan con objetos {@link GraphicElement}. |
| [resumeUpdate](#resumeUpdate--) | Reanuda la actualización de Page#getContents y todos @link XForm#getContents. Fue realizado para aumentar el rendimiento, vea también. |
| [suppressUpdate](#suppressUpdate--) | Suprime la actualización de Page#getContents y todos @link XForm#getContents. Fue realizado para aumentar el rendimiento, vea también. |
| [visit](#visit-com.aspose.pdf.Page-) | Realiza la búsqueda en la página especificada. |

### GraphicsAbsorber {#GraphicsAbsorber--}
```
public GraphicsAbsorber()
```



### dispose {#dispose--}
```
public final void dispose()
```

Libera todos los recursos utilizados por la clase {@link GraphicsAbsorber}.

### getElements {#getElements--}
```
public final GraphicElementCollection getElements()
```

Obtiene la colección de ocurrencias de búsqueda que se presentan con objetos {@link GraphicElement}.

**Returns:**
Instancia de GraphicElementCollection

### resumeUpdate {#resumeUpdate--}
```
public final void resumeUpdate()
```

Reanuda la actualización de Page#getContents y todos @link XForm#getContents. Fue realizado para aumentar el rendimiento, vea también.

### suppressUpdate {#suppressUpdate--}
```
public final void suppressUpdate()
```

Suprime la actualización de Page#getContents y todos @link XForm#getContents. Fue realizado para aumentar el rendimiento, vea también.

### visit {#visit-com.aspose.pdf.Page-}
Realiza la búsqueda en la página especificada.
