---
title: "DocumentInfo"
linktitle: "DocumentInfo"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa la información meta de un documento PDF."
type: docs
weight: 1160
url: /es/java/com.aspose.pdf/documentinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Collections.Generic.Dictionary< String , String > com.aspose.pdf.DocumentInfo, com.aspose.ms.System.Collections.Generic.Dictionary< String , String >, com.aspose.pdf.DocumentInfo

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, String >>, com.aspose.ms.System.Collections.Generic.IGenericDictionary< String, String >, com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, String >>, com.aspose.ms.System.Collections.IEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, String >>, Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String, String >>

```
public final class DocumentInfo extends com.aspose.ms.System.Collections.Generic.Dictionary< String , String >
```

Representa la información meta de un documento PDF.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [DocumentInfo](#DocumentInfo-com.aspose.pdf.IDocument-) | Inicializar la instancia de DocumentInfo. |

## Métodos

| Método | Descripción |
| --- | --- |
| [addItem](#addItem-java.lang.String-java.lang.String-) | Agrega un elemento con la clave y el valor especificados a la colección. |
| [clear](#clear--) | Borra la información del documento. |
| [clearCustomData](#clearCustomData--) | Borra solo los datos personalizados, dejando todos los demás valores predefinidos (Title, Author, etc.). |
| [get_Item](#get_Item-java.lang.String-) | Obtiene el valor asociado con la clave especificada. |
| [getAuthor](#getAuthor--) | Obtiene el autor del documento. |
| [getCreationDate](#getCreationDate--) | Obtiene la fecha de creación del documento. |
| [getCreationTimeZone](#getCreationTimeZone--) | Zona horaria de la fecha de creación en milisegundos. |
| [getCreator](#getCreator--) | Obtiene el creador del documento. |
| [getKeywords](#getKeywords--) | Obtiene las palabras clave del documento. |
| [getModDate](#getModDate--) | Obtiene la fecha de modificación del documento. |
| [getModTimeZone](#getModTimeZone--) | Zona horaria de la fecha de modificación. |
| [getProducer](#getProducer--) | Obtiene el productor del documento. |
| [getSubject](#getSubject--) | Obtiene el asunto del documento. |
| [getTitle](#getTitle--) | Obtiene el título del documento. |
| [getTrapped](#getTrapped--) | Obtiene la bandera trapped. |
| [isPredefinedKey](#isPredefinedKey-java.lang.String-) | Determina si la clave está predefinida (Title, Author, etc.), no es personalizada. |
| [remove](#remove-java.lang.String-) | Elimina el elemento con la clave especificada de la colección. |
| [set_Item](#set_Item-java.lang.String-java.lang.String-) | Establece el valor asociado con la clave especificada. |
| [setAuthor](#setAuthor-java.lang.String-) | Establece el autor del documento. |
| [setCreationDate](#setCreationDate-java.util.Date-) | Establece la fecha de creación del documento. |
| [setCreationTimeZone](#setCreationTimeZone-double-) | Zona horaria de la fecha de creación en milisegundos. |
| [setCreator](#setCreator-java.lang.String-) | Establece el creador del documento. |
| [setKeywords](#setKeywords-java.lang.String-) | Establece las palabras clave del documento. |
| [setModDate](#setModDate-java.util.Date-) | Establece la fecha de modificación del documento. |
| [setModTimeZone](#setModTimeZone-double-) | Zona horaria de la fecha de modificación. |
| [setProducer](#setProducer-java.lang.String-) | Establece el productor del documento. |
| [setSubject](#setSubject-java.lang.String-) | Establece el asunto del documento. |
| [setTitle](#setTitle-java.lang.String-) | Establece el título del documento. |
| [setTrapped](#setTrapped-java.lang.String-) | Establece la marca de atrapado. |

### DocumentInfo {#DocumentInfo-com.aspose.pdf.IDocument-}
Inicializar la instancia de DocumentInfo.

### addItem {#addItem-java.lang.String-java.lang.String-}
Agrega un elemento con la clave y el valor especificados a la colección.

### clear {#clear--}
```
public void clear()
```

Borra la información del documento.

### clearCustomData {#clearCustomData--}
```
public void clearCustomData()
```

Borra solo los datos personalizados, dejando todos los demás valores predefinidos (Title, Author, etc.).

### get_Item {#get_Item-java.lang.String-}
Obtiene el valor asociado con la clave especificada.

### getAuthor {#getAuthor--}
```
public String getAuthor()
```

Obtiene el autor del documento.

**Returns:**
valor String

### getCreationDate {#getCreationDate--}
```
public Date getCreationDate()
```

Obtiene la fecha de creación del documento.

**Returns:**
Objeto Date

### getCreationTimeZone {#getCreationTimeZone--}
```
public double getCreationTimeZone()
```

Zona horaria de la fecha de creación en milisegundos.

**Returns:**
valor double

### getCreator {#getCreator--}
```
public String getCreator()
```

Obtiene el creador del documento.

**Returns:**
valor String

### getKeywords {#getKeywords--}
```
public String getKeywords()
```

Obtiene las palabras clave del documento.

**Returns:**
valor String

### getModDate {#getModDate--}
```
public Date getModDate()
```

Obtiene la fecha de modificación del documento.

**Returns:**
Objeto Date

### getModTimeZone {#getModTimeZone--}
```
public double getModTimeZone()
```

Zona horaria de la fecha de modificación.

**Returns:**
valor double

### getProducer {#getProducer--}
```
public String getProducer()
```

Obtiene el productor del documento.

**Returns:**
valor String

### getSubject {#getSubject--}
```
public String getSubject()
```

Obtiene el asunto del documento.

**Returns:**
valor String

### getTitle {#getTitle--}
```
public String getTitle()
```

Obtiene el título del documento.

**Returns:**
valor String

### getTrapped {#getTrapped--}
```
public String getTrapped()
```

Obtiene la bandera trapped.

**Returns:**
valor String

### isPredefinedKey {#isPredefinedKey-java.lang.String-}
Determina si la clave está predefinida (Title, Author, etc.), no es personalizada.

### remove {#remove-java.lang.String-}
Elimina el elemento con la clave especificada de la colección.

### set_Item {#set_Item-java.lang.String-java.lang.String-}
Establece el valor asociado con la clave especificada.

### setAuthor {#setAuthor-java.lang.String-}
Establece el autor del documento.

### setCreationDate {#setCreationDate-java.util.Date-}
Establece la fecha de creación del documento.

### setCreationTimeZone {#setCreationTimeZone-double-}
```
public void setCreationTimeZone(double value)
```

Zona horaria de la fecha de creación en milisegundos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | en milisegundos |

### setCreator {#setCreator-java.lang.String-}
Establece el creador del documento.

### setKeywords {#setKeywords-java.lang.String-}
Establece las palabras clave del documento.

### setModDate {#setModDate-java.util.Date-}
Establece la fecha de modificación del documento.

### setModTimeZone {#setModTimeZone-double-}
```
public void setModTimeZone(double value)
```

Zona horaria de la fecha de modificación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### setProducer {#setProducer-java.lang.String-}
Establece el productor del documento.

### setSubject {#setSubject-java.lang.String-}
Establece el asunto del documento.

### setTitle {#setTitle-java.lang.String-}
Establece el título del documento.

### setTrapped {#setTrapped-java.lang.String-}
Establece la marca de atrapado.
