---
title: XmpPdfAExtensionValueType
linktitle: XmpPdfAExtensionValueType
second_title: Aspose.PDF for Java API Reference
description: 'The PDF/A ValueType schema is required for all property value types which are not defined in the XMP 2004 specification, i.e. for value types outside of the following list: -.'
type: docs
weight: 5740
url: /java/com.aspose.pdf/xmppdfaextensionvaluetype/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XmpPdfAExtensionObject com.aspose.pdf.XmpPdfAExtensionValueType, com.aspose.pdf.XmpPdfAExtensionObject, com.aspose.pdf.XmpPdfAExtensionValueType

```
public final class XmpPdfAExtensionValueType extends XmpPdfAExtensionObject
```

The PDF/A ValueType schema is required for all property value types which are not defined in the XMP 2004 specification, i.e. for value types outside of the following list: - Array types (these are container types which may contain one or more fields): Alt, Bag, Seq - Basic value types: Boolean, (open and closed) Choice, Date, Dimensions, Integer, Lang Alt, Locale, MIMEType, ProperName, Real, Text, Thumbnail, URI, URL, XPath - Media Management value types: AgentName, RenditionClass, ResourceEvent, ResourceRef, Version - Basic Job/Workflow value type: Job - EXIF schema value types: Flash, CFAPattern, DeviceSettings, GPSCoordinate, OECF/SFR, Rational Schema namespace URI: http://www.aiim.org/pdfa/ns/type# Required schema namespace prefix: pdfaType

## Constructors

| Constructor | Description |
| --- | --- |
| [XmpPdfAExtensionValueType](#XmpPdfAExtensionValueType-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | Initializes new object. |

## Methods

| Method | Description |
| --- | --- |
| [add](#add-com.aspose.pdf.XmpPdfAExtensionField-) | Add new field. |
| [addRange](#addRange-com.aspose.pdf.XmpPdfAExtensionField:A-) | Adds the range of fields. |
| [clear](#clear--) | Clears all fields. |
| [getFields](#getFields--) | Gets the list of fields. |
| [getNamespaceUri](#getNamespaceUri--) | Gets the namespace URI. |
| [getPrefix](#getPrefix--) | Gets the prefix. |
| [getType](#getType--) | Gets the value type. |
| [getXml_](#getXml_-com.aspose.ms.System.Xml.XmlDocument-) | Returns the list of xml elements that represent field in xml tree. |
| [getXmlInternal](#getXmlInternal-com.aspose.ms.System.Xml.XmlDocument-) | Returns the list of xml elements that represent value type in xml tree. |
| [remove](#remove-com.aspose.pdf.XmpPdfAExtensionField-) | Removes the field from the list of fields. |

### XmpPdfAExtensionValueType {#XmpPdfAExtensionValueType-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
Initializes new object.

### add {#add-com.aspose.pdf.XmpPdfAExtensionField-}
Add new field.

### addRange {#addRange-com.aspose.pdf.XmpPdfAExtensionField:A-}
Adds the range of fields.

### clear {#clear--}
```
public void clear()
```

Clears all fields.

### getFields {#getFields--}
```
public com.aspose.ms.System.Collections.Generic.List< XmpPdfAExtensionField > getFields()
```

Gets the list of fields.

**Returns:**
IList

### getNamespaceUri {#getNamespaceUri--}
```
public String getNamespaceUri()
```

Gets the namespace URI.

**Returns:**
String

### getPrefix {#getPrefix--}
```
public String getPrefix()
```

Gets the prefix.

**Returns:**
String

### getType {#getType--}
```
public String getType()
```

Gets the value type.

**Returns:**
String

### getXml_ {#getXml_-com.aspose.ms.System.Xml.XmlDocument-}
Returns the list of xml elements that represent field in xml tree.

### getXmlInternal {#getXmlInternal-com.aspose.ms.System.Xml.XmlDocument-}
Returns the list of xml elements that represent value type in xml tree.

### remove {#remove-com.aspose.pdf.XmpPdfAExtensionField-}
Removes the field from the list of fields.
