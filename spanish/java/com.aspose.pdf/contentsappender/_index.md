---
title: "ContentsAppender"
linktitle: "ContentsAppender"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Realiza modificaciones de contenido solo en modo APPEND. este modo permite evitar el análisis innecesario y pesado del contenido antes de que se realice algún cambio en el contenido. Solo agrega nuevo."
type: docs
weight: 800
url: /es/java/com.aspose.pdf/contentsappender/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ContentsAppender

```
public class ContentsAppender extends Object
```

Realiza modificaciones de contenido solo en modo APPEND. Este modo permite evitar el análisis innecesario y pesado del contenido antes de que se realice algún cambio. Solo agrega nuevos operadores al final o al inicio del contenido.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [ContentsAppender](#ContentsAppender-com.aspose.pdf.Page-) | Inicializa una nueva instancia del appender de contenidos con la página adjunta |
| [ContentsAppender](#ContentsAppender-com.aspose.pdf.XForm-) | Inicializa una nueva instancia del appender de contenidos con Form XObject. |

## Métodos

| Método | Descripción |
| --- | --- |
| [appendToBegin](#appendToBegin-com.aspose.ms.System.Collections.Generic.List-) | Agrega operadores al final del contenido |
| [appendToBegin](#appendToBegin-com.aspose.pdf.Operator-) | Agrega un operador al final del contenido |
| [appendToBegin](#appendToBegin-com.aspose.pdf.Operator:A-) | Agrega operadores al final del contenido |
| [appendToEnd](#appendToEnd-com.aspose.ms.System.Collections.Generic.List-) | Agrega operadores al inicio del contenido |
| [appendToEnd](#appendToEnd-com.aspose.pdf.Operator-) | Agrega un operador al inicio del contenido |
| [appendToEnd](#appendToEnd-com.aspose.pdf.Operator:A-) | Agrega operadores al inicio del contenido |
| [getBeginCode](#getBeginCode--) | Cadena que contiene operadores para insertar al inicio de la página. |
| [getBeginOperators](#getBeginOperators--) | <p> devuelve operadores de inicio </p> |
| [getEndCode](#getEndCode--) | Cadena que contiene operadores para agregar al final de la página. |
| [getEndOperators](#getEndOperators--) | <p> devuelve operadores de fin </p> |
| [resumeUpdate](#resumeUpdate--) | reanuda la actualización del documento |
| [setBeginCode](#setBeginCode-java.lang.String-) | Cadena que contiene operadores para insertar al inicio de la página. |
| [setEndCode](#setEndCode-java.lang.String-) | Cadena que contiene operadores para insertar al inicio de la página. |
| [suppressUpdate](#suppressUpdate--) | Suprime la actualización de datos de contenido. El contenido no se actualiza hasta que se llama a ResumeUpdate. |
| [updateData](#updateData--) | Esta es la nueva versión de UpdateData, que evita la decodificación del contenido existente. |
| [updateDataOld](#updateDataOld--) | Debe llamarse para aplicar los cambios |

### ContentsAppender {#ContentsAppender-com.aspose.pdf.Page-}
Inicializa una nueva instancia del appender de contenidos con la página adjunta

### ContentsAppender {#ContentsAppender-com.aspose.pdf.XForm-}
Inicializa una nueva instancia del appender de contenidos con Form XObject.

### appendToBegin {#appendToBegin-com.aspose.ms.System.Collections.Generic.List-}
Agrega operadores al final del contenido

### appendToBegin {#appendToBegin-com.aspose.pdf.Operator-}
Agrega un operador al final del contenido

### appendToBegin {#appendToBegin-com.aspose.pdf.Operator:A-}
Agrega operadores al final del contenido

### appendToEnd {#appendToEnd-com.aspose.ms.System.Collections.Generic.List-}
Agrega operadores al inicio del contenido

### appendToEnd {#appendToEnd-com.aspose.pdf.Operator-}
Agrega un operador al inicio del contenido

### appendToEnd {#appendToEnd-com.aspose.pdf.Operator:A-}
Agrega operadores al inicio del contenido

### getBeginCode {#getBeginCode--}
```
public String getBeginCode()
```

Cadena que contiene operadores para insertar al inicio de la página.

**Returns:**
Objeto String

### getBeginOperators {#getBeginOperators--}
```
public com.aspose.ms.System.Collections.Generic.List< Operator > getBeginOperators()
```

<p> devuelve operadores de inicio </p>

**Returns:**
objeto {@code List<Operator>}

### getEndCode {#getEndCode--}
```
public String getEndCode()
```

Cadena que contiene operadores para agregar al final de la página.

**Returns:**
Objeto String

### getEndOperators {#getEndOperators--}
```
public com.aspose.ms.System.Collections.Generic.List< Operator > getEndOperators()
```

<p> devuelve operadores de fin </p>

**Returns:**
objeto {@code List<Operator>}

### resumeUpdate {#resumeUpdate--}
```
public void resumeUpdate()
```

reanuda la actualización del documento

### setBeginCode {#setBeginCode-java.lang.String-}
Cadena que contiene operadores para insertar al inicio de la página.

### setEndCode {#setEndCode-java.lang.String-}
Cadena que contiene operadores para insertar al inicio de la página.

### suppressUpdate {#suppressUpdate--}
```
public void suppressUpdate()
```

Suprime la actualización de datos de contenido. El contenido no se actualiza hasta que se llama a ResumeUpdate.

### updateData {#updateData--}
```
public void updateData()
```

Esta es la nueva versión de UpdateData, que evita la decodificación del contenido existente.

### updateDataOld {#updateDataOld--}
```
public void updateDataOld()
```

Debe llamarse para aplicar los cambios
