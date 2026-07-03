---
title: XmpPdfAExtensionSchema
linktitle: XmpPdfAExtensionSchema
second_title: Aspose.PDF for Java API Reference
description: Describes the XMP extension schema which is provided by PDF/A-1.
type: docs
weight: 5720
url: /java/com.aspose.pdf/xmppdfaextensionschema/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XmpPdfAExtensionSchema

```
public class XmpPdfAExtensionSchema extends Object
```

Describes the XMP extension schema which is provided by PDF/A-1.

## Fields

| Field | Description |
| --- | --- |
| [DEFAULT_EXTENSION_NAMESPACE_PREFIX](#DEFAULT_EXTENSION_NAMESPACE_PREFIX) | Default extension namespace prefix. |
| [DEFAULT_EXTENSION_NAMESPACE_URI](#DEFAULT_EXTENSION_NAMESPACE_URI) | Default extension namespace uri. |
| [DEFAULT_FIELD_NAMESPACE_PREFIX](#DEFAULT_FIELD_NAMESPACE_PREFIX) | Default field namespace prefix. |
| [DEFAULT_FIELD_NAMESPACE_URI](#DEFAULT_FIELD_NAMESPACE_URI) | Default extension namespace uri. |
| [DEFAULT_PROPERTY_NAMESPACE_PREFIX](#DEFAULT_PROPERTY_NAMESPACE_PREFIX) | Default property namespace prefix. |
| [DEFAULT_PROPERTY_NAMESPACE_URI](#DEFAULT_PROPERTY_NAMESPACE_URI) | Default property namespace uri. |
| [DEFAULT_SCHEMA_NAMESPACE_PREFIX](#DEFAULT_SCHEMA_NAMESPACE_PREFIX) | Default schema namespace prefix. |
| [DEFAULT_SCHEMA_NAMESPACE_URI](#DEFAULT_SCHEMA_NAMESPACE_URI) | Default schema namespace uri. |
| [DEFAULT_VALUE_NAMESPACE_URI](#DEFAULT_VALUE_NAMESPACE_URI) | Default value namespace uri. |
| [DEFAULT_VALUE_TYPE_NAMESPACE_PREFIX](#DEFAULT_VALUE_TYPE_NAMESPACE_PREFIX) | Default valie type namespace prefix. |
| [RDF_NAMESPACE_URI](#RDF_NAMESPACE_URI) | Default rdf namespace uri. |
| [RDF_PREFIX](#RDF_PREFIX) | Default rdf namespace prefix. |
| [XMLNS](#XMLNS) |  |

## Constructors

| Constructor | Description |
| --- | --- |
| [XmpPdfAExtensionSchema](#XmpPdfAExtensionSchema-com.aspose.pdf.XmpPdfAExtensionSchemaDescription-) | Initializes new object. |

## Methods

| Method | Description |
| --- | --- |
| [add](#add-com.aspose.pdf.XmpPdfAExtensionObject-) | Adds new object into schema. |
| [contains](#contains-com.aspose.pdf.XmpPdfAExtensionObject-) | Determines whether obj exists in schema. |
| [createDescriptionValueXml](#createDescriptionValueXml-com.aspose.ms.System.Xml.XmlDocument-) | Creates the description xml element for the block of properties values. |
| [createDescriptionXml](#createDescriptionXml-com.aspose.ms.System.Xml.XmlDocument-) | Creates the description xml element for the all schemas. |
| [createSchemasElement](#createSchemasElement-com.aspose.ms.System.Xml.XmlNode-) | Creates the list of schemas elements from xml tree. |
| [getDescription](#getDescription--) | Gets the schema description. |
| [getObjects1](#getObjects1--) | Gets the list of objects (properties, value types). |
| [getObjectsInternal](#getObjectsInternal--) | Gets the list of objects (properties, value types). |
| [getProperty](#getProperty-java.lang.String-) | Returns PDF/A property by its name. |
| [getPropertyIndex](#getPropertyIndex-java.lang.String-) | Returns index of property with given name. |
| [getSchemaXml](#getSchemaXml-com.aspose.ms.System.Xml.XmlDocument-) | Returns the xml element (tag - li) that represents schema in xml tree. |
| [getValuesXml](#getValuesXml-com.aspose.ms.System.Xml.XmlDocument-com.aspose.ms.System.Xml.XmlElement-) | Gets the values of properties as xml tree representation. |
| [initializeSchemaValue](#initializeSchemaValue-com.aspose.ms.System.Xml.XmlNode-com.aspose.pdf.XmpPdfAExtensionSchema-) | Initializes the value of property. |
| [isPdfAExtensionPrefix](#isPdfAExtensionPrefix-java.lang.String-) | Determines whether prefix value is a part of pdf-a extension. |
| [remove](#remove-com.aspose.pdf.XmpPdfAExtensionObject-) | Removes the object from schema. |

### DEFAULT_EXTENSION_NAMESPACE_PREFIX {#DEFAULT_EXTENSION_NAMESPACE_PREFIX}
```
public static final String DEFAULT_EXTENSION_NAMESPACE_PREFIX
```

Default extension namespace prefix.

### DEFAULT_EXTENSION_NAMESPACE_URI {#DEFAULT_EXTENSION_NAMESPACE_URI}
```
public static final String DEFAULT_EXTENSION_NAMESPACE_URI
```

Default extension namespace uri.

### DEFAULT_FIELD_NAMESPACE_PREFIX {#DEFAULT_FIELD_NAMESPACE_PREFIX}
```
public static final String DEFAULT_FIELD_NAMESPACE_PREFIX
```

Default field namespace prefix.

### DEFAULT_FIELD_NAMESPACE_URI {#DEFAULT_FIELD_NAMESPACE_URI}
```
public static final String DEFAULT_FIELD_NAMESPACE_URI
```

Default extension namespace uri.

### DEFAULT_PROPERTY_NAMESPACE_PREFIX {#DEFAULT_PROPERTY_NAMESPACE_PREFIX}
```
public static final String DEFAULT_PROPERTY_NAMESPACE_PREFIX
```

Default property namespace prefix.

### DEFAULT_PROPERTY_NAMESPACE_URI {#DEFAULT_PROPERTY_NAMESPACE_URI}
```
public static final String DEFAULT_PROPERTY_NAMESPACE_URI
```

Default property namespace uri.

### DEFAULT_SCHEMA_NAMESPACE_PREFIX {#DEFAULT_SCHEMA_NAMESPACE_PREFIX}
```
public static final String DEFAULT_SCHEMA_NAMESPACE_PREFIX
```

Default schema namespace prefix.

### DEFAULT_SCHEMA_NAMESPACE_URI {#DEFAULT_SCHEMA_NAMESPACE_URI}
```
public static final String DEFAULT_SCHEMA_NAMESPACE_URI
```

Default schema namespace uri.

### DEFAULT_VALUE_NAMESPACE_URI {#DEFAULT_VALUE_NAMESPACE_URI}
```
public static final String DEFAULT_VALUE_NAMESPACE_URI
```

Default value namespace uri.

### DEFAULT_VALUE_TYPE_NAMESPACE_PREFIX {#DEFAULT_VALUE_TYPE_NAMESPACE_PREFIX}
```
public static final String DEFAULT_VALUE_TYPE_NAMESPACE_PREFIX
```

Default valie type namespace prefix.

### RDF_NAMESPACE_URI {#RDF_NAMESPACE_URI}
```
public static final String RDF_NAMESPACE_URI
```

Default rdf namespace uri.

### RDF_PREFIX {#RDF_PREFIX}
```
public static final String RDF_PREFIX
```

Default rdf namespace prefix.

### XMLNS {#XMLNS}
```
public static final String XMLNS
```



### XmpPdfAExtensionSchema {#XmpPdfAExtensionSchema-com.aspose.pdf.XmpPdfAExtensionSchemaDescription-}
Initializes new object.

### add {#add-com.aspose.pdf.XmpPdfAExtensionObject-}
Adds new object into schema.

### contains {#contains-com.aspose.pdf.XmpPdfAExtensionObject-}
Determines whether obj exists in schema.

### createDescriptionValueXml {#createDescriptionValueXml-com.aspose.ms.System.Xml.XmlDocument-}
Creates the description xml element for the block of properties values.

### createDescriptionXml {#createDescriptionXml-com.aspose.ms.System.Xml.XmlDocument-}
Creates the description xml element for the all schemas.

### createSchemasElement {#createSchemasElement-com.aspose.ms.System.Xml.XmlNode-}
Creates the list of schemas elements from xml tree.

### getDescription {#getDescription--}
```
public XmpPdfAExtensionSchemaDescription getDescription()
```

Gets the schema description.

**Returns:**
XmpPdfAExtensionSchemaDescription

### getObjects1 {#getObjects1--}
```
public List getObjects1()
```

Gets the list of objects (properties, value types).

**Returns:**
ArrayList

### getObjectsInternal {#getObjectsInternal--}
```
public com.aspose.ms.System.Collections.Generic.List< XmpPdfAExtensionObject > getObjectsInternal()
```

Gets the list of objects (properties, value types).

**Returns:**
ArrayList

### getProperty {#getProperty-java.lang.String-}
Returns PDF/A property by its name.

### getPropertyIndex {#getPropertyIndex-java.lang.String-}
Returns index of property with given name.

### getSchemaXml {#getSchemaXml-com.aspose.ms.System.Xml.XmlDocument-}
Returns the xml element (tag - li) that represents schema in xml tree.

### getValuesXml {#getValuesXml-com.aspose.ms.System.Xml.XmlDocument-com.aspose.ms.System.Xml.XmlElement-}
Gets the values of properties as xml tree representation.

### initializeSchemaValue {#initializeSchemaValue-com.aspose.ms.System.Xml.XmlNode-com.aspose.pdf.XmpPdfAExtensionSchema-}
Initializes the value of property.

### isPdfAExtensionPrefix {#isPdfAExtensionPrefix-java.lang.String-}
Determines whether prefix value is a part of pdf-a extension.

### remove {#remove-com.aspose.pdf.XmpPdfAExtensionObject-}
Removes the object from schema.
