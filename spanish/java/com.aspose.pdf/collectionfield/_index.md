---
title: "CollectionField"
linktitle: "CollectionField"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa una clase de campo de esquema de colección de documentos."
type: docs
weight: 620
url: /es/java/com.aspose.pdf/collectionfield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.CollectionField

```
public class CollectionField extends Object
```

Representa una clase de campo de esquema de colección de documentos.

## Métodos

| Método | Descripción |
| --- | --- |
| [getE](#getE--) | Obtiene una bandera que indica si el procesador interactivo de PDF debe proporcionar soporte para editar el valor del campo. Valor predeterminado: false |
| [getFiledType](#getFiledType--) | Obtiene el tipo de un valor de campo en una colección de esquema. Este campo describe el tipo de valor correspondiente a {@code Subtype}({@link #getSubtype}/{@link #setSubtype(int)}). |
| [getN](#getN--) | Obtiene el nombre textual del campo que debe presentarse al usuario por el procesador interactivo de PDF |
| [getO](#getO--) | Obtiene el orden relativo del nombre del campo en la interfaz de usuario. Los campos deben ser ordenados por el procesador interactivo de PDF en orden ascendente. |
| [getSubtype](#getSubtype--) | Obtiene el subtipo de un valor de campo en una colección de esquema. El subtipo del campo de colección o del campo relacionado con archivos que describe este diccionario. Esta entrada identifica el tipo de datos que debe almacenarse en el campo. |
| [getV](#getV--) | Obtiene la visibilidad inicial del campo en la interfaz de usuario. Valor predeterminado: true. |

### getE {#getE--}
```
public final boolean getE()
```

Obtiene una bandera que indica si el procesador interactivo de PDF debe proporcionar soporte para editar el valor del campo. Valor predeterminado: false

**Returns:**
valor booleano

### getFiledType {#getFiledType--}
```
public final int getFiledType()
```

Obtiene el tipo de un valor de campo en una colección de esquema. Este campo describe el tipo de valor correspondiente a {@code Subtype}({@link #getSubtype}/{@link #setSubtype(int)}).

**Returns:**
FieldValueType elemento

### getN {#getN--}
```
public final String getN()
```

Obtiene el nombre textual del campo que debe presentarse al usuario por el procesador interactivo de PDF

**Returns:**
valor String

### getO {#getO--}
```
public final Integer [] getO()
```

Obtiene el orden relativo del nombre del campo en la interfaz de usuario. Los campos deben ser ordenados por el procesador interactivo de PDF en orden ascendente.

**Returns:**
array de Integer

### getSubtype {#getSubtype--}
```
public final int getSubtype()
```

Obtiene el subtipo de un valor de campo en una colección de esquema. El subtipo del campo de colección o del campo relacionado con archivos que describe este diccionario. Esta entrada identifica el tipo de datos que debe almacenarse en el campo.

**Returns:**
CollectionFieldSubtype elemento

### getV {#getV--}
```
public final boolean getV()
```

Obtiene la visibilidad inicial del campo en la interfaz de usuario. Valor predeterminado: true.

**Returns:**
valor booleano
