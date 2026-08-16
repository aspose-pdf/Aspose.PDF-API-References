---
title: "FileSpecification"
linktitle: "FileSpecification"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase que representa un archivo incrustado."
type: docs
weight: 1510
url: /es/java/com.aspose.pdf/filespecification/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FileSpecification

```
public final class FileSpecification extends Object
```

Clase que representa un archivo incrustado.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [FileSpecification](#FileSpecification--) | Crea una nueva especificación de archivo vacía. |
| [FileSpecification](#FileSpecification-java.io.InputStream-java.lang.String-) | Crea una nueva especificación de archivo vacía. |
| [FileSpecification](#FileSpecification-java.io.InputStream-java.lang.String-java.lang.String-) | Crea una nueva especificación de archivo vacía. |
| [FileSpecification](#FileSpecification-com.aspose.pdf.engine.data.IPdfPrimitive-) | Crea una nueva especificación de archivo vacía. |
| [FileSpecification](#FileSpecification-com.aspose.ms.System.IO.Stream-java.lang.String-) | Crea una nueva especificación de archivo vacía. |
| [FileSpecification](#FileSpecification-com.aspose.ms.System.IO.Stream-java.lang.String-java.lang.String-) | Crea una nueva especificación de archivo vacía. |
| [FileSpecification](#FileSpecification-java.lang.String-) | Crea una nueva especificación de archivo vacía. |
| [FileSpecification](#FileSpecification-java.lang.String-com.aspose.pdf.Annotation-) | Crea una nueva especificación de archivo vacía. |
| [FileSpecification](#FileSpecification-java.lang.String-java.lang.String-) | Crea una nueva especificación de archivo vacía. |

## Métodos

| Método | Descripción |
| --- | --- |
| [getAFRelationship](#getAFRelationship--) | Relación de archivo asociada. |
| [getCollectionItem](#getCollectionItem--) | Obtiene un elemento de colección de la especificación de archivo. |
| [getContents](#getContents--) | Obtiene el archivo de contenido. |
| [getContentsInternal](#getContentsInternal--) | Obtiene el archivo de contenido. |
| [getDescription](#getDescription--) | Obtiene el texto asociado con la especificación del archivo. |
| [getEncoding](#getEncoding--) | Obtiene el formato de codificación. Valores posibles: Zip - el archivo está comprimido con ZIP, None - el archivo no está comprimido. |
| [getEncryptedPayload](#getEncryptedPayload--) | Obtiene la carga útil cifrada. |
| [getEngineDict](#getEngineDict--) | Diccionario PDF que contiene información sobre el archivo. Solo interno |
| [getEngineObj](#getEngineObj--) | Solo interno |
| [getFileSystem](#getFileSystem--) | Obtiene el nombre del sistema de archivos. |
| [getMIMEType](#getMIMEType--) | Obtiene el subtipo del archivo incrustado |
| [getName](#getName--) | Obtiene el nombre de la especificación del archivo. |
| [getParams](#getParams--) | Obtiene los parámetros del archivo. |
| [getStreamContents](#getStreamContents--) | Obtiene el contenido del archivo como flujo. El contenido no se carga en memoria, lo que permite reducir el uso de memoria. Pero este flujo no admite posicionamiento ni la propiedad Length. Si necesita estas funciones, utilice la propiedad Contents en su lugar. |
| [getUnicodeName](#getUnicodeName--) | Obtiene el nombre Unicode de la especificación del archivo. |
| [getValue](#getValue-java.lang.String-) | Obtiene el parámetro específico de la aplicación. |
| [isIncludeContents](#isIncludeContents--) | Si es verdadero, el contenido del archivo se incluirá en la especificación del archivo. |
| [setAFRelationship](#setAFRelationship-com.aspose.pdf.AFRelationship-) | Relación de archivo asociada. |
| [setContents](#setContents-byte:A-) | Establece el contenido del archivo. |
| [setContents](#setContents-java.io.InputStream-) | Establece el contenido del archivo. |
| [setDescription](#setDescription-java.lang.String-) | Establece el texto asociado con la especificación del archivo. |
| [setEncoding](#setEncoding-com.aspose.pdf.FileEncoding-) | Establece el formato de codificación. Valores posibles: Zip - el archivo está comprimido con ZIP, None - el archivo no está comprimido. |
| [setFileSystem](#setFileSystem-java.lang.String-) | Establece el nombre del sistema de archivos. |
| [setIncludeContents](#setIncludeContents-boolean-) | Si es verdadero, el contenido del archivo se incluirá en la especificación del archivo. |
| [setMIMEType](#setMIMEType-java.lang.String-) | Establece el MIMEType. |
| [setName](#setName-java.lang.String-) | Establece el nombre de la especificación del archivo. |
| [setParams](#setParams-com.aspose.pdf.FileParams-) | Establece los parámetros del archivo. |
| [setUnicodeName](#setUnicodeName-java.lang.String-) | Establece el nombre Unicode de la especificación del archivo. |
| [setValue](#setValue-java.lang.String-java.lang.String-) | Establece el parámetro específico de la aplicación. |

### FileSpecification {#FileSpecification--}
```
public FileSpecification()
```

Crea una nueva especificación de archivo vacía.

### FileSpecification {#FileSpecification-java.io.InputStream-java.lang.String-}
Crea una nueva especificación de archivo vacía.

### FileSpecification {#FileSpecification-java.io.InputStream-java.lang.String-java.lang.String-}
Crea una nueva especificación de archivo vacía.

### FileSpecification {#FileSpecification-com.aspose.pdf.engine.data.IPdfPrimitive-}
Crea una nueva especificación de archivo vacía.

### FileSpecification {#FileSpecification-com.aspose.ms.System.IO.Stream-java.lang.String-}
Crea una nueva especificación de archivo vacía.

### FileSpecification {#FileSpecification-com.aspose.ms.System.IO.Stream-java.lang.String-java.lang.String-}
Crea una nueva especificación de archivo vacía.

### FileSpecification {#FileSpecification-java.lang.String-}
Crea una nueva especificación de archivo vacía.

### FileSpecification {#FileSpecification-java.lang.String-com.aspose.pdf.Annotation-}
Crea una nueva especificación de archivo vacía.

### FileSpecification {#FileSpecification-java.lang.String-java.lang.String-}
Crea una nueva especificación de archivo vacía.

### getAFRelationship {#getAFRelationship--}
```
public final AFRelationship getAFRelationship()
```

Relación de archivo asociada.

**Returns:**
Elemento AFRelationship

### getCollectionItem {#getCollectionItem--}
```
public final CollectionItem getCollectionItem()
```

Obtiene un elemento de colección de la especificación de archivo.

**Returns:**
Instancia CollectionItem

### getContents {#getContents--}
```
public InputStream getContents()
```

Obtiene el archivo de contenido.

**Returns:**
Objeto InputStream

### getContentsInternal {#getContentsInternal--}
```
public com.aspose.ms.System.IO.Stream getContentsInternal()
```

Obtiene el archivo de contenido.

**Returns:**
objeto Stream

### getDescription {#getDescription--}
```
public String getDescription()
```

Obtiene el texto asociado con la especificación del archivo.

**Returns:**
valor String

### getEncoding {#getEncoding--}
```
public FileEncoding getEncoding()
```

Obtiene el formato de codificación. Valores posibles: Zip - el archivo está comprimido con ZIP, None - el archivo no está comprimido.

**Returns:**
valor int @see FileEncoding

### getEncryptedPayload {#getEncryptedPayload--}
```
public final EncryptedPayload getEncryptedPayload()
```

Obtiene la carga útil cifrada.

**Returns:**
Instancia EncryptedPayload

### getEngineDict {#getEngineDict--}
```
public com.aspose.pdf.engine.data.IPdfDictionary getEngineDict()
```

Diccionario PDF que contiene información sobre el archivo. Solo interno

**Returns:**
Objeto IPdfDictionary

### getEngineObj {#getEngineObj--}
```
public com.aspose.pdf.engine.data.IPdfObject getEngineObj()
```

Solo interno

**Returns:**
Objeto IPdfObject

### getFileSystem {#getFileSystem--}
```
public String getFileSystem()
```

Obtiene el nombre del sistema de archivos.

**Returns:**
valor String

### getMIMEType {#getMIMEType--}
```
public String getMIMEType()
```

Obtiene el subtipo del archivo incrustado

**Returns:**
valor de cadena

### getName {#getName--}
```
public String getName()
```

Obtiene el nombre de la especificación del archivo.

**Returns:**
valor String

### getParams {#getParams--}
```
public FileParams getParams()
```

Obtiene los parámetros del archivo.

**Returns:**
objeto FileParams

### getStreamContents {#getStreamContents--}
```
public InputStream getStreamContents()
```

Obtiene el contenido del archivo como flujo. El contenido no se carga en memoria, lo que permite reducir el uso de memoria. Pero este flujo no admite posicionamiento ni la propiedad Length. Si necesita estas funciones, utilice la propiedad Contents en su lugar.

**Returns:**
Objeto InputStream

### getUnicodeName {#getUnicodeName--}
```
public String getUnicodeName()
```

Obtiene el nombre Unicode de la especificación del archivo.

**Returns:**
valor String

### getValue {#getValue-java.lang.String-}
Obtiene el parámetro específico de la aplicación.

### isIncludeContents {#isIncludeContents--}
```
public boolean isIncludeContents()
```

Si es verdadero, el contenido del archivo se incluirá en la especificación del archivo.

**Returns:**
valor booleano

### setAFRelationship {#setAFRelationship-com.aspose.pdf.AFRelationship-}
Relación de archivo asociada.

### setContents {#setContents-byte:A-}
```
public void setContents(byte[] value)
```

Establece el contenido del archivo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | matriz de bytes |

### setContents {#setContents-java.io.InputStream-}
Establece el contenido del archivo.

### setDescription {#setDescription-java.lang.String-}
Establece el texto asociado con la especificación del archivo.

### setEncoding {#setEncoding-com.aspose.pdf.FileEncoding-}
Establece el formato de codificación. Valores posibles: Zip - el archivo está comprimido con ZIP, None - el archivo no está comprimido.

### setFileSystem {#setFileSystem-java.lang.String-}
Establece el nombre del sistema de archivos.

### setIncludeContents {#setIncludeContents-boolean-}
```
public void setIncludeContents(boolean value)
```

Si es verdadero, el contenido del archivo se incluirá en la especificación del archivo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setMIMEType {#setMIMEType-java.lang.String-}
Establece el MIMEType.

### setName {#setName-java.lang.String-}
Establece el nombre de la especificación del archivo.

### setParams {#setParams-com.aspose.pdf.FileParams-}
Establece los parámetros del archivo.

### setUnicodeName {#setUnicodeName-java.lang.String-}
Establece el nombre Unicode de la especificación del archivo.

### setValue {#setValue-java.lang.String-java.lang.String-}
Establece el parámetro específico de la aplicación.
