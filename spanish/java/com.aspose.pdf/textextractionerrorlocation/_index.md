---
title: "TextExtractionErrorLocation"
linktitle: "TextExtractionErrorLocation"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa la ubicación en el documento PDF donde ha aparecido un error de extracción de texto."
type: docs
weight: 5050
url: /es/java/com.aspose.pdf/textextractionerrorlocation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextExtractionErrorLocation

```
public final class TextExtractionErrorLocation extends Object
```

Representa la ubicación en el documento PDF donde ha aparecido un error de extracción de texto.

## Métodos

| Método | Descripción |
| --- | --- |
| [getFontUsedKey](#getFontUsedKey--) | Clave (nombre) del objeto PDF Font que se utiliza para mostrar el operador que causa el error de extracción de texto. |
| [getFormKey](#getFormKey--) | Clave (nombre) del PDF Form XObject en el que se ha localizado el error de extracción de texto del flujo de contenido. No vacío si ObjectType == 'xForm'. |
| [getObjectType](#getObjectType--) | Tipo del objeto PDF (Page o xForm) en el que se ha localizado el error de extracción de texto del flujo de contenido. |
| [getOperatorIndex](#getOperatorIndex--) | Índice del operador que muestra texto en el flujo de contenido (colección de operadores) que causa el error de extracción de texto. |
| [getOperatorString](#getOperatorString--) | Operador que muestra texto que causa el error de extracción de texto. |
| [getPageNumber](#getPageNumber--) | Número de la página del documento donde se ha localizado el error de extracción de texto. |
| [getPath](#getPath--) | Ubicación del documento PDF donde apareció el error de extracción de texto. |
| [getTextStartPoint](#getTextStartPoint--) | Clave (nombre) del objeto PDF Font que se utiliza para mostrar el operador que causa el error de extracción de texto. |
| [toString](#toString--) | Devuelve la representación en cadena. |

### getFontUsedKey {#getFontUsedKey--}
```
public String getFontUsedKey()
```

Clave (nombre) del objeto PDF Font que se utiliza para mostrar el operador que causa el error de extracción de texto.

**Returns:**
valor String

### getFormKey {#getFormKey--}
```
public String getFormKey()
```

Clave (nombre) del PDF Form XObject en el que se ha localizado el error de extracción de texto del flujo de contenido. No vacío si ObjectType == 'xForm'.

**Returns:**
valor String

### getObjectType {#getObjectType--}
```
public String getObjectType()
```

Tipo del objeto PDF (Page o xForm) en el que se ha localizado el error de extracción de texto del flujo de contenido.

**Returns:**
valor String

### getOperatorIndex {#getOperatorIndex--}
```
public int getOperatorIndex()
```

Índice del operador que muestra texto en el flujo de contenido (colección de operadores) que causa el error de extracción de texto.

**Returns:**
valor int

### getOperatorString {#getOperatorString--}
```
public String getOperatorString()
```

Operador que muestra texto que causa el error de extracción de texto.

**Returns:**
valor String

### getPageNumber {#getPageNumber--}
```
public int getPageNumber()
```

Número de la página del documento donde se ha localizado el error de extracción de texto.

**Returns:**
valor int

### getPath {#getPath--}
```
public String getPath()
```

Ubicación del documento PDF donde apareció el error de extracción de texto.

**Returns:**
valor String

### getTextStartPoint {#getTextStartPoint--}
```
public Point getTextStartPoint()
```

Clave (nombre) del objeto PDF Font que se utiliza para mostrar el operador que causa el error de extracción de texto.

**Returns:**
Instancia de Point

### toString {#toString--}
```
public String toString()
```

Devuelve la representación en cadena.

**Returns:**
Representación en cadena.
