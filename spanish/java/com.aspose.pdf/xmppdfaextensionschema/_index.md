---
title: "XmpPdfAExtensionSchema"
linktitle: "XmpPdfAExtensionSchema"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Describe el esquema de extensión XMP que proporciona PDF/A-1."
type: docs
weight: 5720
url: /es/java/com.aspose.pdf/xmppdfaextensionschema/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XmpPdfAExtensionSchema

```
public class XmpPdfAExtensionSchema extends Object
```

Describe el esquema de extensión XMP que proporciona PDF/A-1.

## Campos

| Campo | Descripción |
| --- | --- |
| [DEFAULT_EXTENSION_NAMESPACE_PREFIX](#DEFAULT_EXTENSION_NAMESPACE_PREFIX) | Prefijo de espacio de nombres de extensión predeterminado. |
| [DEFAULT_EXTENSION_NAMESPACE_URI](#DEFAULT_EXTENSION_NAMESPACE_URI) | URI de espacio de nombres de extensión predeterminado. |
| [DEFAULT_FIELD_NAMESPACE_PREFIX](#DEFAULT_FIELD_NAMESPACE_PREFIX) | Prefijo de espacio de nombres de campo predeterminado. |
| [DEFAULT_FIELD_NAMESPACE_URI](#DEFAULT_FIELD_NAMESPACE_URI) | URI de espacio de nombres de extensión predeterminado. |
| [DEFAULT_PROPERTY_NAMESPACE_PREFIX](#DEFAULT_PROPERTY_NAMESPACE_PREFIX) | Prefijo de espacio de nombres de propiedad predeterminado. |
| [DEFAULT_PROPERTY_NAMESPACE_URI](#DEFAULT_PROPERTY_NAMESPACE_URI) | URI de espacio de nombres de propiedad predeterminado. |
| [DEFAULT_SCHEMA_NAMESPACE_PREFIX](#DEFAULT_SCHEMA_NAMESPACE_PREFIX) | Prefijo de espacio de nombres de esquema predeterminado. |
| [DEFAULT_SCHEMA_NAMESPACE_URI](#DEFAULT_SCHEMA_NAMESPACE_URI) | URI de espacio de nombres de esquema predeterminado. |
| [DEFAULT_VALUE_NAMESPACE_URI](#DEFAULT_VALUE_NAMESPACE_URI) | URI de espacio de nombres de valor predeterminado. |
| [DEFAULT_VALUE_TYPE_NAMESPACE_PREFIX](#DEFAULT_VALUE_TYPE_NAMESPACE_PREFIX) | Prefijo de espacio de nombres del tipo de valor predeterminado. |
| [RDF_NAMESPACE_URI](#RDF_NAMESPACE_URI) | URI de espacio de nombres rdf predeterminado. |
| [RDF_PREFIX](#RDF_PREFIX) | Prefijo de espacio de nombres rdf predeterminado. |
| [XMLNS](#XMLNS) |  |

## Constructores

| Constructor | Descripción |
| --- | --- |
| [XmpPdfAExtensionSchema](#XmpPdfAExtensionSchema-com.aspose.pdf.XmpPdfAExtensionSchemaDescription-) | Inicializa un nuevo objeto. |

## Métodos

| Método | Descripción |
| --- | --- |
| [add](#add-com.aspose.pdf.XmpPdfAExtensionObject-) | Agrega un nuevo objeto al esquema. |
| [contains](#contains-com.aspose.pdf.XmpPdfAExtensionObject-) | Determina si el obj existe en el esquema. |
| [createDescriptionValueXml](#createDescriptionValueXml-com.aspose.ms.System.Xml.XmlDocument-) | Crea el elemento xml de descripción para el bloque de valores de propiedades. |
| [createDescriptionXml](#createDescriptionXml-com.aspose.ms.System.Xml.XmlDocument-) | Crea el elemento xml de descripción para todos los esquemas. |
| [createSchemasElement](#createSchemasElement-com.aspose.ms.System.Xml.XmlNode-) | Crea la lista de elementos de esquemas a partir del árbol xml. |
| [getDescription](#getDescription--) | Obtiene la descripción del esquema. |
| [getObjects1](#getObjects1--) | Obtiene la lista de objetos (propiedades, tipos de valor). |
| [getObjectsInternal](#getObjectsInternal--) | Obtiene la lista de objetos (propiedades, tipos de valor). |
| [getProperty](#getProperty-java.lang.String-) | Devuelve la propiedad PDF/A por su nombre. |
| [getPropertyIndex](#getPropertyIndex-java.lang.String-) | Devuelve el índice de la propiedad con el nombre dado. |
| [getSchemaXml](#getSchemaXml-com.aspose.ms.System.Xml.XmlDocument-) | Devuelve el elemento xml (etiqueta - li) que representa el esquema en el árbol xml. |
| [getValuesXml](#getValuesXml-com.aspose.ms.System.Xml.XmlDocument-com.aspose.ms.System.Xml.XmlElement-) | Obtiene los valores de las propiedades como representación del árbol xml. |
| [initializeSchemaValue](#initializeSchemaValue-com.aspose.ms.System.Xml.XmlNode-com.aspose.pdf.XmpPdfAExtensionSchema-) | Inicializa el valor de la propiedad. |
| [isPdfAExtensionPrefix](#isPdfAExtensionPrefix-java.lang.String-) | Determina si el valor del prefijo es parte de la extensión pdf-a. |
| [remove](#remove-com.aspose.pdf.XmpPdfAExtensionObject-) | Elimina el objeto del esquema. |

### DEFAULT_EXTENSION_NAMESPACE_PREFIX {#DEFAULT_EXTENSION_NAMESPACE_PREFIX}
```
public static final String DEFAULT_EXTENSION_NAMESPACE_PREFIX
```

Prefijo de espacio de nombres de extensión predeterminado.

### DEFAULT_EXTENSION_NAMESPACE_URI {#DEFAULT_EXTENSION_NAMESPACE_URI}
```
public static final String DEFAULT_EXTENSION_NAMESPACE_URI
```

URI de espacio de nombres de extensión predeterminado.

### DEFAULT_FIELD_NAMESPACE_PREFIX {#DEFAULT_FIELD_NAMESPACE_PREFIX}
```
public static final String DEFAULT_FIELD_NAMESPACE_PREFIX
```

Prefijo de espacio de nombres de campo predeterminado.

### DEFAULT_FIELD_NAMESPACE_URI {#DEFAULT_FIELD_NAMESPACE_URI}
```
public static final String DEFAULT_FIELD_NAMESPACE_URI
```

URI de espacio de nombres de extensión predeterminado.

### DEFAULT_PROPERTY_NAMESPACE_PREFIX {#DEFAULT_PROPERTY_NAMESPACE_PREFIX}
```
public static final String DEFAULT_PROPERTY_NAMESPACE_PREFIX
```

Prefijo de espacio de nombres de propiedad predeterminado.

### DEFAULT_PROPERTY_NAMESPACE_URI {#DEFAULT_PROPERTY_NAMESPACE_URI}
```
public static final String DEFAULT_PROPERTY_NAMESPACE_URI
```

URI de espacio de nombres de propiedad predeterminado.

### DEFAULT_SCHEMA_NAMESPACE_PREFIX {#DEFAULT_SCHEMA_NAMESPACE_PREFIX}
```
public static final String DEFAULT_SCHEMA_NAMESPACE_PREFIX
```

Prefijo de espacio de nombres de esquema predeterminado.

### DEFAULT_SCHEMA_NAMESPACE_URI {#DEFAULT_SCHEMA_NAMESPACE_URI}
```
public static final String DEFAULT_SCHEMA_NAMESPACE_URI
```

URI de espacio de nombres de esquema predeterminado.

### DEFAULT_VALUE_NAMESPACE_URI {#DEFAULT_VALUE_NAMESPACE_URI}
```
public static final String DEFAULT_VALUE_NAMESPACE_URI
```

URI de espacio de nombres de valor predeterminado.

### DEFAULT_VALUE_TYPE_NAMESPACE_PREFIX {#DEFAULT_VALUE_TYPE_NAMESPACE_PREFIX}
```
public static final String DEFAULT_VALUE_TYPE_NAMESPACE_PREFIX
```

Prefijo de espacio de nombres del tipo de valor predeterminado.

### RDF_NAMESPACE_URI {#RDF_NAMESPACE_URI}
```
public static final String RDF_NAMESPACE_URI
```

URI de espacio de nombres rdf predeterminado.

### RDF_PREFIX {#RDF_PREFIX}
```
public static final String RDF_PREFIX
```

Prefijo de espacio de nombres rdf predeterminado.

### XMLNS {#XMLNS}
```
public static final String XMLNS
```



### XmpPdfAExtensionSchema {#XmpPdfAExtensionSchema-com.aspose.pdf.XmpPdfAExtensionSchemaDescription-}
Inicializa un nuevo objeto.

### add {#add-com.aspose.pdf.XmpPdfAExtensionObject-}
Agrega un nuevo objeto al esquema.

### contains {#contains-com.aspose.pdf.XmpPdfAExtensionObject-}
Determina si el obj existe en el esquema.

### createDescriptionValueXml {#createDescriptionValueXml-com.aspose.ms.System.Xml.XmlDocument-}
Crea el elemento xml de descripción para el bloque de valores de propiedades.

### createDescriptionXml {#createDescriptionXml-com.aspose.ms.System.Xml.XmlDocument-}
Crea el elemento xml de descripción para todos los esquemas.

### createSchemasElement {#createSchemasElement-com.aspose.ms.System.Xml.XmlNode-}
Crea la lista de elementos de esquemas a partir del árbol xml.

### getDescription {#getDescription--}
```
public XmpPdfAExtensionSchemaDescription getDescription()
```

Obtiene la descripción del esquema.

**Returns:**
XmpPdfAExtensionSchemaDescription

### getObjects1 {#getObjects1--}
```
public List getObjects1()
```

Obtiene la lista de objetos (propiedades, tipos de valor).

**Returns:**
ArrayList

### getObjectsInternal {#getObjectsInternal--}
```
public com.aspose.ms.System.Collections.Generic.List< XmpPdfAExtensionObject > getObjectsInternal()
```

Obtiene la lista de objetos (propiedades, tipos de valor).

**Returns:**
ArrayList

### getProperty {#getProperty-java.lang.String-}
Devuelve la propiedad PDF/A por su nombre.

### getPropertyIndex {#getPropertyIndex-java.lang.String-}
Devuelve el índice de la propiedad con el nombre dado.

### getSchemaXml {#getSchemaXml-com.aspose.ms.System.Xml.XmlDocument-}
Devuelve el elemento xml (etiqueta - li) que representa el esquema en el árbol xml.

### getValuesXml {#getValuesXml-com.aspose.ms.System.Xml.XmlDocument-com.aspose.ms.System.Xml.XmlElement-}
Obtiene los valores de las propiedades como representación del árbol xml.

### initializeSchemaValue {#initializeSchemaValue-com.aspose.ms.System.Xml.XmlNode-com.aspose.pdf.XmpPdfAExtensionSchema-}
Inicializa el valor de la propiedad.

### isPdfAExtensionPrefix {#isPdfAExtensionPrefix-java.lang.String-}
Determina si el valor del prefijo es parte de la extensión pdf-a.

### remove {#remove-com.aspose.pdf.XmpPdfAExtensionObject-}
Elimina el objeto del esquema.
