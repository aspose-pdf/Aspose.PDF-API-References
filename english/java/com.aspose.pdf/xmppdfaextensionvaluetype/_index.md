---
title: XmpPdfAExtensionValueType
second_title: Aspose.PDF for Java API Reference
description: The PDF/A ValueType schema is required for all property value types which are not defined in the XMP 2004 specification i.e. for value types outside of the following list - Array types these are container types which may contain one or more fields Alt Bag Seq - Basic value types Boolean open and closed Choice Date Dimensions Integer Lang Alt Locale MIMEType ProperName Real Text Thumbnail URI URL XPath - Media Management value types AgentName RenditionClass ResourceEvent ResourceRef Version - Basic Job/Workflow value type Job - EXIF schema value types Flash CFAPattern DeviceSettings GPSCoordinate OECF/SFR Rational Schema namespace URI http//www.aiim.orgdfa/ns/type Required schema namespace prefix pdfaType
type: docs
weight: 425
url: /java/com.aspose.pdf/xmppdfaextensionvaluetype/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.XmpPdfAExtensionObject](../../com.aspose.pdf/xmppdfaextensionobject)
```
public final class XmpPdfAExtensionValueType extends XmpPdfAExtensionObject
```

The PDF/A ValueType schema is required for all property value types which are not defined in the XMP 2004 specification, i.e. for value types outside of the following list: - Array types (these are container types which may contain one or more fields): Alt, Bag, Seq - Basic value types: Boolean, (open and closed) Choice, Date, Dimensions, Integer, Lang Alt, Locale, MIMEType, ProperName, Real, Text, Thumbnail, URI, URL, XPath - Media Management value types: AgentName, RenditionClass, ResourceEvent, ResourceRef, Version - Basic Job/Workflow value type: Job - EXIF schema value types: Flash, CFAPattern, DeviceSettings, GPSCoordinate, OECF/SFR, Rational Schema namespace URI: http://www.aiim.org/pdfa/ns/type\# Required schema namespace prefix: pdfaType
## Constructors

| Constructor | Description |
| --- | --- |
| [XmpPdfAExtensionValueType(String type, String namespaceUri, String prefix, String description)](#XmpPdfAExtensionValueType-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | Initializes new object. |
## Methods

| Method | Description |
| --- | --- |
| [add(XmpPdfAExtensionField field)](#add-com.aspose.pdf.XmpPdfAExtensionField-) | Add new field. |
| [addRange(XmpPdfAExtensionField[] fields)](#addRange-com.aspose.pdf.XmpPdfAExtensionField---) | Adds the range of fields. |
| [clear()](#clear--) | Clears all fields. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDescription()](#getDescription--) | Gets the description. |
| [getFields()](#getFields--) | Gets the list of fields. |
| [getNamespaceUri()](#getNamespaceUri--) | Gets the namespace URI. |
| [getPrefix()](#getPrefix--) | Gets the prefix. |
| [getType()](#getType--) | Gets the value type. |
| [getValue()](#getValue--) | Gets the value. |
| [getXmlInternal(System.Xml.XmlDocument xmlDocument)](#getXmlInternal-com.aspose.ms.System.Xml.XmlDocument-) | Returns the list of xml elements that represent value type in xml tree. |
| [getXml_(System.Xml.XmlDocument xmlDocument)](#getXml--com.aspose.ms.System.Xml.XmlDocument-) | Returns the list of xml elements that represent field in xml tree. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(XmpPdfAExtensionField field)](#remove-com.aspose.pdf.XmpPdfAExtensionField-) | Removes the field from the list of fields. |
| [setValue(String value)](#setValue-java.lang.String-) | Sets the value. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpPdfAExtensionValueType(String type, String namespaceUri, String prefix, String description) {#XmpPdfAExtensionValueType-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
```
public XmpPdfAExtensionValueType(String type, String namespaceUri, String prefix, String description)
```


Initializes new object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | java.lang.String | The value type. |
| namespaceUri | java.lang.String | The namespace URI. |
| prefix | java.lang.String | The prefix. |
| description | java.lang.String | The description. |

### add(XmpPdfAExtensionField field) {#add-com.aspose.pdf.XmpPdfAExtensionField-}
```
public void add(XmpPdfAExtensionField field)
```


Add new field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| field | [XmpPdfAExtensionField](../../com.aspose.pdf/xmppdfaextensionfield) | The field to add. |

### addRange(XmpPdfAExtensionField[] fields) {#addRange-com.aspose.pdf.XmpPdfAExtensionField---}
```
public void addRange(XmpPdfAExtensionField[] fields)
```


Adds the range of fields.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fields | [XmpPdfAExtensionField\[\]](../../com.aspose.pdf/xmppdfaextensionfield) | The fields to add. |

### clear() {#clear--}
```
public void clear()
```


Clears all fields.

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
### getFields() {#getFields--}
```
public System.Collections.Generic.List<XmpPdfAExtensionField> getFields()
```


Gets the list of fields.

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.pdf.XmpPdfAExtensionField> - IList
### getNamespaceUri() {#getNamespaceUri--}
```
public String getNamespaceUri()
```


Gets the namespace URI.

**Returns:**
java.lang.String - String
### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


Gets the prefix.

**Returns:**
java.lang.String - String
### getType() {#getType--}
```
public String getType()
```


Gets the value type.

**Returns:**
java.lang.String - String
### getValue() {#getValue--}
```
public String getValue()
```


Gets the value.

**Returns:**
java.lang.String - String
### getXmlInternal(System.Xml.XmlDocument xmlDocument) {#getXmlInternal-com.aspose.ms.System.Xml.XmlDocument-}
```
public System.Collections.Generic.List<System.Xml.XmlElement> getXmlInternal(System.Xml.XmlDocument xmlDocument)
```


Returns the list of xml elements that represent value type in xml tree.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xmlDocument | com.aspose.ms.System.Xml.XmlDocument | The source xml document. |

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.ms.System.Xml.XmlElement> - The list of xml elements.
### getXml_(System.Xml.XmlDocument xmlDocument) {#getXml--com.aspose.ms.System.Xml.XmlDocument-}
```
public List getXml_(System.Xml.XmlDocument xmlDocument)
```


Returns the list of xml elements that represent field in xml tree.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xmlDocument | com.aspose.ms.System.Xml.XmlDocument | The source xml document. |

**Returns:**
java.util.List - The list of fields.
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




### remove(XmpPdfAExtensionField field) {#remove-com.aspose.pdf.XmpPdfAExtensionField-}
```
public void remove(XmpPdfAExtensionField field)
```


Removes the field from the list of fields.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| field | [XmpPdfAExtensionField](../../com.aspose.pdf/xmppdfaextensionfield) | The field to remove. |

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

