---
title: XmpPdfAExtensionProperty
second_title: Aspose.PDF for Java API Reference
description: Describes a single property.
type: docs
weight: 422
url: /java/com.aspose.pdf/xmppdfaextensionproperty/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.XmpPdfAExtensionObject](../../com.aspose.pdf/xmppdfaextensionobject), [com.aspose.pdf.XmpPdfAExtensionField](../../com.aspose.pdf/xmppdfaextensionfield)
```
public final class XmpPdfAExtensionProperty extends XmpPdfAExtensionField
```

Describes a single property. Schema namespace URI: http://www.aiim.org/pdfa/ns/property\# Required schema namespace prefix: pdfaProperty
## Constructors

| Constructor | Description |
| --- | --- |
| [XmpPdfAExtensionProperty(String name, String value, String valueType, int category, String description)](#XmpPdfAExtensionProperty-java.lang.String-java.lang.String-java.lang.String-int-java.lang.String-) | Initializes new object. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCategory()](#getCategory--) | Gets the property category. |
| [getClass()](#getClass--) |  |
| [getDescription()](#getDescription--) | Gets the description. |
| [getName()](#getName--) | Field name. |
| [getValue()](#getValue--) | Gets the value. |
| [getValueType()](#getValueType--) | Field value type, drawn from XMP Specification 2004, or an embedded PDF/A value type extension schema. |
| [getXmlInternal(System.Xml.XmlDocument xmlDocument)](#getXmlInternal-com.aspose.ms.System.Xml.XmlDocument-) | Returns the list of xml elements that represent property in xml tree. |
| [getXml_(System.Xml.XmlDocument xmlDocument)](#getXml--com.aspose.ms.System.Xml.XmlDocument-) | Returns the list of xml elements that represent property in xml tree. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setValue(String value)](#setValue-java.lang.String-) | Sets the value. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpPdfAExtensionProperty(String name, String value, String valueType, int category, String description) {#XmpPdfAExtensionProperty-java.lang.String-java.lang.String-java.lang.String-int-java.lang.String-}
```
public XmpPdfAExtensionProperty(String name, String value, String valueType, int category, String description)
```


Initializes new object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The property name. |
| value | java.lang.String | The property value. |
| valueType | java.lang.String | The property value type. |
| category | int | The property category. |
| description | java.lang.String | The property description. |

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
### getCategory() {#getCategory--}
```
public int getCategory()
```


Gets the property category.

**Returns:**
int - int value
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


Returns the list of xml elements that represent property in xml tree.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xmlDocument | com.aspose.ms.System.Xml.XmlDocument | The source xml document. |

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.ms.System.Xml.XmlElement> - The list of xml elements.
### getXml_(System.Xml.XmlDocument xmlDocument) {#getXml--com.aspose.ms.System.Xml.XmlDocument-}
```
public List<System.Xml.XmlElement> getXml_(System.Xml.XmlDocument xmlDocument)
```


Returns the list of xml elements that represent property in xml tree.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xmlDocument | com.aspose.ms.System.Xml.XmlDocument | The source xml document. |

**Returns:**
java.util.List<com.aspose.ms.System.Xml.XmlElement> - The list of xml elements.
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

