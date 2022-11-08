---
title: XmpPdfAExtensionField
second_title: Aspose.PDF for Java API Reference
description: This schema describes a field in a structured type.
type: docs
weight: 420
url: /java/com.aspose.pdf/xmppdfaextensionfield/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.XmpPdfAExtensionObject](../../com.aspose.pdf/xmppdfaextensionobject)
```
public class XmpPdfAExtensionField extends XmpPdfAExtensionObject
```

This schema describes a field in a structured type. It is very similar to the PDF/A Property Value Type schema, but defines a field in a structure instead of a property. Schema namespace URI: http://www.aiim.org/pdfa/ns/field\# Required schema namespace prefix: pdfaField.
## Constructors

| Constructor | Description |
| --- | --- |
| [XmpPdfAExtensionField(String name, String value, String valueType, String description)](#XmpPdfAExtensionField-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | Initializes object. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDescription()](#getDescription--) | Gets the description. |
| [getName()](#getName--) | Field name. |
| [getValue()](#getValue--) | Gets the value. |
| [getValueType()](#getValueType--) | Field value type, drawn from XMP Specification 2004, or an embedded PDF/A value type extension schema. |
| [getXmlInternal(System.Xml.XmlDocument xmlDocument)](#getXmlInternal-com.aspose.ms.System.Xml.XmlDocument-) | Returns the list of xml elements that represent field in xml tree. |
| [getXml_(System.Xml.XmlDocument xmlDocument)](#getXml--com.aspose.ms.System.Xml.XmlDocument-) | Returns the list of xml elements that represent field in xml tree. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setValue(String value)](#setValue-java.lang.String-) | Sets the value. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpPdfAExtensionField(String name, String value, String valueType, String description) {#XmpPdfAExtensionField-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
```
public XmpPdfAExtensionField(String name, String value, String valueType, String description)
```


Initializes object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The field name. |
| value | java.lang.String | The field value. |
| valueType | java.lang.String | The field value type. |
| description | java.lang.String | The field description. |

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
public String getDescription()
```


Gets the description.

**Returns:**
java.lang.String - String
### getName() {#getName--}
```
public String getName()
```


Field name. Field names must be valid XML element names.

**Returns:**
java.lang.String - String
### getValue() {#getValue--}
```
public String getValue()
```


Gets the value.

**Returns:**
java.lang.String - String
### getValueType() {#getValueType--}
```
public String getValueType()
```


Field value type, drawn from XMP Specification 2004, or an embedded PDF/A value type extension schema. Predefined XMP type names or names of custom types.

**Returns:**
java.lang.String - String
### getXmlInternal(System.Xml.XmlDocument xmlDocument) {#getXmlInternal-com.aspose.ms.System.Xml.XmlDocument-}
```
public System.Collections.Generic.List<System.Xml.XmlElement> getXmlInternal(System.Xml.XmlDocument xmlDocument)
```


Returns the list of xml elements that represent field in xml tree.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xmlDocument | com.aspose.ms.System.Xml.XmlDocument | The source xml document. |

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.ms.System.Xml.XmlElement> - The list of fields.
### getXml_(System.Xml.XmlDocument xmlDocument) {#getXml--com.aspose.ms.System.Xml.XmlDocument-}
```
public List<System.Xml.XmlElement> getXml_(System.Xml.XmlDocument xmlDocument)
```


Returns the list of xml elements that represent field in xml tree.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xmlDocument | com.aspose.ms.System.Xml.XmlDocument | The source xml document. |

**Returns:**
java.util.List<com.aspose.ms.System.Xml.XmlElement> - The list of fields.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setValue(String value) {#setValue-java.lang.String-}
```
public void setValue(String value)
```


Sets the value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String |

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

