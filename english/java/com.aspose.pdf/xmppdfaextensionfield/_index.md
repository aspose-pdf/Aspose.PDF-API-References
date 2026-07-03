---
title: XmpPdfAExtensionField
linktitle: XmpPdfAExtensionField
second_title: Aspose.PDF for Java API Reference
description: This schema describes a field in a structured type. It is very similar to the PDF/A Property Value Type schema, but defines a field in a structure instead of a property. Schema.
type: docs
weight: 5690
url: /java/com.aspose.pdf/xmppdfaextensionfield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XmpPdfAExtensionObject com.aspose.pdf.XmpPdfAExtensionField, com.aspose.pdf.XmpPdfAExtensionObject, com.aspose.pdf.XmpPdfAExtensionField

```
public class XmpPdfAExtensionField extends XmpPdfAExtensionObject
```

This schema describes a field in a structured type. It is very similar to the PDF/A Property Value Type schema, but defines a field in a structure instead of a property. Schema namespace URI: http://www.aiim.org/pdfa/ns/field# Required schema namespace prefix: pdfaField.

## Constructors

| Constructor | Description |
| --- | --- |
| [XmpPdfAExtensionField](#XmpPdfAExtensionField-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | Initializes object. |

## Methods

| Method | Description |
| --- | --- |
| [getName](#getName--) | Field name. Field names must be valid XML element names. |
| [getValueType](#getValueType--) | Field value type, drawn from XMP Specification 2004, or an embedded PDF/A value type extension schema. Predefined XMP type names or names of custom types. |
| [getXml_](#getXml_-com.aspose.ms.System.Xml.XmlDocument-) | Returns the list of xml elements that represent field in xml tree. |
| [getXmlInternal](#getXmlInternal-com.aspose.ms.System.Xml.XmlDocument-) | Returns the list of xml elements that represent field in xml tree. |

### XmpPdfAExtensionField {#XmpPdfAExtensionField-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
Initializes object.

### getName {#getName--}
```
public String getName()
```

Field name. Field names must be valid XML element names.

**Returns:**
String

### getValueType {#getValueType--}
```
public String getValueType()
```

Field value type, drawn from XMP Specification 2004, or an embedded PDF/A value type extension schema. Predefined XMP type names or names of custom types.

**Returns:**
String

### getXml_ {#getXml_-com.aspose.ms.System.Xml.XmlDocument-}
Returns the list of xml elements that represent field in xml tree.

### getXmlInternal {#getXmlInternal-com.aspose.ms.System.Xml.XmlDocument-}
Returns the list of xml elements that represent field in xml tree.
