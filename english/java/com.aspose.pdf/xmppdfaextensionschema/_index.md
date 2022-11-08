---
title: XmpPdfAExtensionSchema
second_title: Aspose.PDF for Java API Reference
description: Describes the XMP extension schema which is provided by PDF/A-1.
type: docs
weight: 423
url: /java/com.aspose.pdf/xmppdfaextensionschema/
---
**Inheritance:**
java.lang.Object
```
public class XmpPdfAExtensionSchema
```

Describes the XMP extension schema which is provided by PDF/A-1.
## Constructors

| Constructor | Description |
| --- | --- |
| [XmpPdfAExtensionSchema(XmpPdfAExtensionSchemaDescription description)](#XmpPdfAExtensionSchema-com.aspose.pdf.XmpPdfAExtensionSchemaDescription-) | Initializes new object. |
## Fields

| Field | Description |
| --- | --- |
| [DEFAULT_EXTENSION_NAMESPACE_PREFIX](#DEFAULT-EXTENSION-NAMESPACE-PREFIX) | Default extension namespace prefix. |
| [DEFAULT_EXTENSION_NAMESPACE_URI](#DEFAULT-EXTENSION-NAMESPACE-URI) | Default extension namespace uri. |
| [DEFAULT_FIELD_NAMESPACE_PREFIX](#DEFAULT-FIELD-NAMESPACE-PREFIX) | Default field namespace prefix. |
| [DEFAULT_FIELD_NAMESPACE_URI](#DEFAULT-FIELD-NAMESPACE-URI) | Default extension namespace uri. |
| [DEFAULT_PROPERTY_NAMESPACE_PREFIX](#DEFAULT-PROPERTY-NAMESPACE-PREFIX) | Default property namespace prefix. |
| [DEFAULT_PROPERTY_NAMESPACE_URI](#DEFAULT-PROPERTY-NAMESPACE-URI) | Default property namespace uri. |
| [DEFAULT_SCHEMA_NAMESPACE_PREFIX](#DEFAULT-SCHEMA-NAMESPACE-PREFIX) | Default schema namespace prefix. |
| [DEFAULT_SCHEMA_NAMESPACE_URI](#DEFAULT-SCHEMA-NAMESPACE-URI) | Default schema namespace uri. |
| [DEFAULT_VALUE_NAMESPACE_URI](#DEFAULT-VALUE-NAMESPACE-URI) | Default value namespace uri. |
| [DEFAULT_VALUE_TYPE_NAMESPACE_PREFIX](#DEFAULT-VALUE-TYPE-NAMESPACE-PREFIX) | Default valie type namespace prefix. |
| [RDF_NAMESPACE_URI](#RDF-NAMESPACE-URI) | Default rdf namespace uri. |
| [RDF_PREFIX](#RDF-PREFIX) | Default rdf namespace prefix. |
## Methods

| Method | Description |
| --- | --- |
| [add(XmpPdfAExtensionObject obj)](#add-com.aspose.pdf.XmpPdfAExtensionObject-) | Adds new object into schema. |
| [contains(XmpPdfAExtensionObject obj)](#contains-com.aspose.pdf.XmpPdfAExtensionObject-) | Determines whether obj exists in schema. |
| [createDescriptionValueXml(System.Xml.XmlDocument xmlDocument)](#createDescriptionValueXml-com.aspose.ms.System.Xml.XmlDocument-) | Creates the description xml element for the block of properties values. |
| [createDescriptionXml(System.Xml.XmlDocument xmlDocument)](#createDescriptionXml-com.aspose.ms.System.Xml.XmlDocument-) | Creates the description xml element for the all schemas. |
| [createSchemasElement(System.Xml.XmlNode rootNode)](#createSchemasElement-com.aspose.ms.System.Xml.XmlNode-) | Creates the list of schemas elements from xml tree. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDescription()](#getDescription--) | Gets the schema description. |
| [getObjects1()](#getObjects1--) | Gets the list of objects (properties, value types). |
| [getObjectsInternal()](#getObjectsInternal--) | Gets the list of objects (properties, value types). |
| [getProperty(String name)](#getProperty-java.lang.String-) | Returns PDF/A property by its name. |
| [getPropertyIndex(String name)](#getPropertyIndex-java.lang.String-) | Returns index of property with given name. |
| [getSchemaXml(System.Xml.XmlDocument xmlDocument)](#getSchemaXml-com.aspose.ms.System.Xml.XmlDocument-) | Returns the xml element (tag - li) that represents schema in xml tree. |
| [getValuesXml(System.Xml.XmlDocument xmlDocument, System.Xml.XmlElement rootElement)](#getValuesXml-com.aspose.ms.System.Xml.XmlDocument-com.aspose.ms.System.Xml.XmlElement-) | Gets the values of properties as xml tree representation. |
| [hashCode()](#hashCode--) |  |
| [initializeSchemaValue(System.Xml.XmlNode node, XmpPdfAExtensionSchema schema)](#initializeSchemaValue-com.aspose.ms.System.Xml.XmlNode-com.aspose.pdf.XmpPdfAExtensionSchema-) | Initializes the value of property. |
| [isPdfAExtensionPrefix(String localName)](#isPdfAExtensionPrefix-java.lang.String-) | Determines whether prefix value is a part of pdf-a extension. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(XmpPdfAExtensionObject obj)](#remove-com.aspose.pdf.XmpPdfAExtensionObject-) | Removes the object from schema. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpPdfAExtensionSchema(XmpPdfAExtensionSchemaDescription description) {#XmpPdfAExtensionSchema-com.aspose.pdf.XmpPdfAExtensionSchemaDescription-}
```
public XmpPdfAExtensionSchema(XmpPdfAExtensionSchemaDescription description)
```


Initializes new object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| description | [XmpPdfAExtensionSchemaDescription](../../com.aspose.pdf/xmppdfaextensionschemadescription) | The schema description. |

### DEFAULT_EXTENSION_NAMESPACE_PREFIX {#DEFAULT-EXTENSION-NAMESPACE-PREFIX}
```
public static final String DEFAULT_EXTENSION_NAMESPACE_PREFIX
```


Default extension namespace prefix.

### DEFAULT_EXTENSION_NAMESPACE_URI {#DEFAULT-EXTENSION-NAMESPACE-URI}
```
public static final String DEFAULT_EXTENSION_NAMESPACE_URI
```


Default extension namespace uri.

### DEFAULT_FIELD_NAMESPACE_PREFIX {#DEFAULT-FIELD-NAMESPACE-PREFIX}
```
public static final String DEFAULT_FIELD_NAMESPACE_PREFIX
```


Default field namespace prefix.

### DEFAULT_FIELD_NAMESPACE_URI {#DEFAULT-FIELD-NAMESPACE-URI}
```
public static final String DEFAULT_FIELD_NAMESPACE_URI
```


Default extension namespace uri.

### DEFAULT_PROPERTY_NAMESPACE_PREFIX {#DEFAULT-PROPERTY-NAMESPACE-PREFIX}
```
public static final String DEFAULT_PROPERTY_NAMESPACE_PREFIX
```


Default property namespace prefix.

### DEFAULT_PROPERTY_NAMESPACE_URI {#DEFAULT-PROPERTY-NAMESPACE-URI}
```
public static final String DEFAULT_PROPERTY_NAMESPACE_URI
```


Default property namespace uri.

### DEFAULT_SCHEMA_NAMESPACE_PREFIX {#DEFAULT-SCHEMA-NAMESPACE-PREFIX}
```
public static final String DEFAULT_SCHEMA_NAMESPACE_PREFIX
```


Default schema namespace prefix.

### DEFAULT_SCHEMA_NAMESPACE_URI {#DEFAULT-SCHEMA-NAMESPACE-URI}
```
public static final String DEFAULT_SCHEMA_NAMESPACE_URI
```


Default schema namespace uri.

### DEFAULT_VALUE_NAMESPACE_URI {#DEFAULT-VALUE-NAMESPACE-URI}
```
public static final String DEFAULT_VALUE_NAMESPACE_URI
```


Default value namespace uri.

### DEFAULT_VALUE_TYPE_NAMESPACE_PREFIX {#DEFAULT-VALUE-TYPE-NAMESPACE-PREFIX}
```
public static final String DEFAULT_VALUE_TYPE_NAMESPACE_PREFIX
```


Default valie type namespace prefix.

### RDF_NAMESPACE_URI {#RDF-NAMESPACE-URI}
```
public static final String RDF_NAMESPACE_URI
```


Default rdf namespace uri.

### RDF_PREFIX {#RDF-PREFIX}
```
public static final String RDF_PREFIX
```


Default rdf namespace prefix.

### add(XmpPdfAExtensionObject obj) {#add-com.aspose.pdf.XmpPdfAExtensionObject-}
```
public void add(XmpPdfAExtensionObject obj)
```


Adds new object into schema.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | [XmpPdfAExtensionObject](../../com.aspose.pdf/xmppdfaextensionobject) | The new object. |

### contains(XmpPdfAExtensionObject obj) {#contains-com.aspose.pdf.XmpPdfAExtensionObject-}
```
public boolean contains(XmpPdfAExtensionObject obj)
```


Determines whether obj exists in schema.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | [XmpPdfAExtensionObject](../../com.aspose.pdf/xmppdfaextensionobject) | The obj to find. |

**Returns:**
boolean - True - object exists in schema; otherwise, false.
### createDescriptionValueXml(System.Xml.XmlDocument xmlDocument) {#createDescriptionValueXml-com.aspose.ms.System.Xml.XmlDocument-}
```
public static System.Xml.XmlElement createDescriptionValueXml(System.Xml.XmlDocument xmlDocument)
```


Creates the description xml element for the block of properties values.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xmlDocument | com.aspose.ms.System.Xml.XmlDocument | The source xml document. |

**Returns:**
com.aspose.ms.System.Xml.XmlElement - The description xml element.
### createDescriptionXml(System.Xml.XmlDocument xmlDocument) {#createDescriptionXml-com.aspose.ms.System.Xml.XmlDocument-}
```
public static System.Xml.XmlElement createDescriptionXml(System.Xml.XmlDocument xmlDocument)
```


Creates the description xml element for the all schemas.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xmlDocument | com.aspose.ms.System.Xml.XmlDocument | The source xml document. |

**Returns:**
com.aspose.ms.System.Xml.XmlElement - The description xml element.
### createSchemasElement(System.Xml.XmlNode rootNode) {#createSchemasElement-com.aspose.ms.System.Xml.XmlNode-}
```
public static HashDictionary<String,XmpPdfAExtensionSchema> createSchemasElement(System.Xml.XmlNode rootNode)
```


Creates the list of schemas elements from xml tree.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rootNode | com.aspose.ms.System.Xml.XmlNode | The root node for schemas elements. |

**Returns:**
[HashDictionary](../../com.aspose.pdf.engine.collections/hashdictionary) - The dictionary of schemas elements in format (key, value): schema\_prefix, schema value.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDescription() {#getDescription--}
```
public XmpPdfAExtensionSchemaDescription getDescription()
```


Gets the schema description.

**Returns:**
[XmpPdfAExtensionSchemaDescription](../../com.aspose.pdf/xmppdfaextensionschemadescription) - XmpPdfAExtensionSchemaDescription
### getObjects1() {#getObjects1--}
```
public List getObjects1()
```


Gets the list of objects (properties, value types).

**Returns:**
java.util.List - ArrayList
### getObjectsInternal() {#getObjectsInternal--}
```
public System.Collections.Generic.List<XmpPdfAExtensionObject> getObjectsInternal()
```


Gets the list of objects (properties, value types).

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.pdf.XmpPdfAExtensionObject> - ArrayList
### getProperty(String name) {#getProperty-java.lang.String-}
```
public final XmpPdfAExtensionProperty getProperty(String name)
```


Returns PDF/A property by its name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Property name. |

**Returns:**
[XmpPdfAExtensionProperty](../../com.aspose.pdf/xmppdfaextensionproperty) - XmpPdfAExtensionProperty instance The property.
### getPropertyIndex(String name) {#getPropertyIndex-java.lang.String-}
```
public final int getPropertyIndex(String name)
```


Returns index of property with given name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Property name. |

**Returns:**
int - Index of property within Objects List,
### getSchemaXml(System.Xml.XmlDocument xmlDocument) {#getSchemaXml-com.aspose.ms.System.Xml.XmlDocument-}
```
public System.Xml.XmlElement getSchemaXml(System.Xml.XmlDocument xmlDocument)
```


Returns the xml element (tag - li) that represents schema in xml tree.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xmlDocument | com.aspose.ms.System.Xml.XmlDocument | The source xml document. |

**Returns:**
com.aspose.ms.System.Xml.XmlElement - The xml element.
### getValuesXml(System.Xml.XmlDocument xmlDocument, System.Xml.XmlElement rootElement) {#getValuesXml-com.aspose.ms.System.Xml.XmlDocument-com.aspose.ms.System.Xml.XmlElement-}
```
public void getValuesXml(System.Xml.XmlDocument xmlDocument, System.Xml.XmlElement rootElement)
```


Gets the values of properties as xml tree representation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xmlDocument | com.aspose.ms.System.Xml.XmlDocument | The source xml document. |
| rootElement | com.aspose.ms.System.Xml.XmlElement | The root node of properties values list. |

### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initializeSchemaValue(System.Xml.XmlNode node, XmpPdfAExtensionSchema schema) {#initializeSchemaValue-com.aspose.ms.System.Xml.XmlNode-com.aspose.pdf.XmpPdfAExtensionSchema-}
```
public static void initializeSchemaValue(System.Xml.XmlNode node, XmpPdfAExtensionSchema schema)
```


Initializes the value of property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| node | com.aspose.ms.System.Xml.XmlNode | The current node that stores property value. |
| schema | [XmpPdfAExtensionSchema](../../com.aspose.pdf/xmppdfaextensionschema) | The schema that contains property definition. |

### isPdfAExtensionPrefix(String localName) {#isPdfAExtensionPrefix-java.lang.String-}
```
public static boolean isPdfAExtensionPrefix(String localName)
```


Determines whether prefix value is a part of pdf-a extension.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| localName | java.lang.String | The prefix value to validate. |

**Returns:**
boolean - True - prefix is a part of pdf-a extension; otherwise, false.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(XmpPdfAExtensionObject obj) {#remove-com.aspose.pdf.XmpPdfAExtensionObject-}
```
public void remove(XmpPdfAExtensionObject obj)
```


Removes the object from schema.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | [XmpPdfAExtensionObject](../../com.aspose.pdf/xmppdfaextensionobject) | The object to remove. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

