---
title: XmpPdfAExtensionProperty
second_title: Aspose.PDF for Java API Reference
description: Describes a single property.
type: docs
weight: 423
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
| [getCategory()](#getCategory--) | Gets the property category. |
| [getXmlInternal(System.Xml.XmlDocument xmlDocument)](#getXmlInternal-com.aspose.ms.System.Xml.XmlDocument-) | Returns the list of xml elements that represent property in xml tree. |
| [getXml_(System.Xml.XmlDocument xmlDocument)](#getXml--com.aspose.ms.System.Xml.XmlDocument-) | Returns the list of xml elements that represent property in xml tree. |
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

### getCategory() {#getCategory--}
```
public int getCategory()
```


Gets the property category.

**Returns:**
int - int value
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
