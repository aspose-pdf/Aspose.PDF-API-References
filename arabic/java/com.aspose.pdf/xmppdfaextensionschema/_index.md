---
title: "XmpPdfAExtensionSchema"
linktitle: "XmpPdfAExtensionSchema"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يصف مخطط امتداد XMP الذي توفره PDF/A-1."
type: docs
weight: 5720
url: /ar/java/com.aspose.pdf/xmppdfaextensionschema/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XmpPdfAExtensionSchema

```
public class XmpPdfAExtensionSchema extends Object
```

يصف مخطط امتداد XMP الذي توفره PDF/A-1.

## الحقول

| حقل | الوصف |
| --- | --- |
| [DEFAULT_EXTENSION_NAMESPACE_PREFIX](#DEFAULT_EXTENSION_NAMESPACE_PREFIX) | بادئة مساحة الاسم للامتداد الافتراضية. |
| [DEFAULT_EXTENSION_NAMESPACE_URI](#DEFAULT_EXTENSION_NAMESPACE_URI) | معرف URI لمساحة الاسم للامتداد الافتراضي. |
| [DEFAULT_FIELD_NAMESPACE_PREFIX](#DEFAULT_FIELD_NAMESPACE_PREFIX) | بادئة مساحة الاسم للحقل الافتراضية. |
| [DEFAULT_FIELD_NAMESPACE_URI](#DEFAULT_FIELD_NAMESPACE_URI) | معرف URI لمساحة الاسم للامتداد الافتراضي. |
| [DEFAULT_PROPERTY_NAMESPACE_PREFIX](#DEFAULT_PROPERTY_NAMESPACE_PREFIX) | بادئة مساحة الاسم للخاصية الافتراضية. |
| [DEFAULT_PROPERTY_NAMESPACE_URI](#DEFAULT_PROPERTY_NAMESPACE_URI) | معرف URI لمساحة الاسم للخاصية الافتراضية. |
| [DEFAULT_SCHEMA_NAMESPACE_PREFIX](#DEFAULT_SCHEMA_NAMESPACE_PREFIX) | بادئة مساحة الاسم للمخطط الافتراضية. |
| [DEFAULT_SCHEMA_NAMESPACE_URI](#DEFAULT_SCHEMA_NAMESPACE_URI) | معرف URI لمساحة الاسم للمخطط الافتراضي. |
| [DEFAULT_VALUE_NAMESPACE_URI](#DEFAULT_VALUE_NAMESPACE_URI) | معرف URI لمساحة الاسم للقيمة الافتراضية. |
| [DEFAULT_VALUE_TYPE_NAMESPACE_PREFIX](#DEFAULT_VALUE_TYPE_NAMESPACE_PREFIX) | بادئة مساحة الاسم لنوع القيمة الافتراضية. |
| [RDF_NAMESPACE_URI](#RDF_NAMESPACE_URI) | معرف URI لمساحة الاسم لـ rdf الافتراضية. |
| [RDF_PREFIX](#RDF_PREFIX) | بادئة مساحة الاسم لـ rdf الافتراضية. |
| [XMLNS](#XMLNS) |  |

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [XmpPdfAExtensionSchema](#XmpPdfAExtensionSchema-com.aspose.pdf.XmpPdfAExtensionSchemaDescription-) | يقوم بتهيئة كائن جديد. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [add](#add-com.aspose.pdf.XmpPdfAExtensionObject-) | يضيف كائنًا جديدًا إلى المخطط. |
| [contains](#contains-com.aspose.pdf.XmpPdfAExtensionObject-) | يحدد ما إذا كان الكائن موجودًا في المخطط. |
| [createDescriptionValueXml](#createDescriptionValueXml-com.aspose.ms.System.Xml.XmlDocument-) | ينشئ عنصر XML الوصف للكتلة من قيم الخصائص. |
| [createDescriptionXml](#createDescriptionXml-com.aspose.ms.System.Xml.XmlDocument-) | ينشئ عنصر XML الوصف لجميع المخططات. |
| [createSchemasElement](#createSchemasElement-com.aspose.ms.System.Xml.XmlNode-) | ينشئ قائمة عناصر المخططات من شجرة XML. |
| [getDescription](#getDescription--) | يحصل على وصف المخطط. |
| [getObjects1](#getObjects1--) | يحصل على قائمة الكائنات (الخصائص، أنواع القيم). |
| [getObjectsInternal](#getObjectsInternal--) | يحصل على قائمة الكائنات (الخصائص، أنواع القيم). |
| [getProperty](#getProperty-java.lang.String-) | يعيد خاصية PDF/A حسب اسمها. |
| [getPropertyIndex](#getPropertyIndex-java.lang.String-) | يعيد فهرس الخاصية بالاسم المعطى. |
| [getSchemaXml](#getSchemaXml-com.aspose.ms.System.Xml.XmlDocument-) | يعيد عنصر xml (الوسم - li) الذي يمثل المخطط في شجرة xml. |
| [getValuesXml](#getValuesXml-com.aspose.ms.System.Xml.XmlDocument-com.aspose.ms.System.Xml.XmlElement-) | يحصل على قيم الخصائص كتمثيل شجرة xml. |
| [initializeSchemaValue](#initializeSchemaValue-com.aspose.ms.System.Xml.XmlNode-com.aspose.pdf.XmpPdfAExtensionSchema-) | يُهيئ قيمة الخاصية. |
| [isPdfAExtensionPrefix](#isPdfAExtensionPrefix-java.lang.String-) | يحدد ما إذا كانت قيمة البادئة جزءًا من امتداد pdf-a. |
| [remove](#remove-com.aspose.pdf.XmpPdfAExtensionObject-) | يزيل الكائن من المخطط. |

### DEFAULT_EXTENSION_NAMESPACE_PREFIX {#DEFAULT_EXTENSION_NAMESPACE_PREFIX}
```
public static final String DEFAULT_EXTENSION_NAMESPACE_PREFIX
```

بادئة مساحة الاسم للامتداد الافتراضية.

### DEFAULT_EXTENSION_NAMESPACE_URI {#DEFAULT_EXTENSION_NAMESPACE_URI}
```
public static final String DEFAULT_EXTENSION_NAMESPACE_URI
```

معرف URI لمساحة الاسم للامتداد الافتراضي.

### DEFAULT_FIELD_NAMESPACE_PREFIX {#DEFAULT_FIELD_NAMESPACE_PREFIX}
```
public static final String DEFAULT_FIELD_NAMESPACE_PREFIX
```

بادئة مساحة الاسم للحقل الافتراضية.

### DEFAULT_FIELD_NAMESPACE_URI {#DEFAULT_FIELD_NAMESPACE_URI}
```
public static final String DEFAULT_FIELD_NAMESPACE_URI
```

معرف URI لمساحة الاسم للامتداد الافتراضي.

### DEFAULT_PROPERTY_NAMESPACE_PREFIX {#DEFAULT_PROPERTY_NAMESPACE_PREFIX}
```
public static final String DEFAULT_PROPERTY_NAMESPACE_PREFIX
```

بادئة مساحة الاسم للخاصية الافتراضية.

### DEFAULT_PROPERTY_NAMESPACE_URI {#DEFAULT_PROPERTY_NAMESPACE_URI}
```
public static final String DEFAULT_PROPERTY_NAMESPACE_URI
```

معرف URI لمساحة الاسم للخاصية الافتراضية.

### DEFAULT_SCHEMA_NAMESPACE_PREFIX {#DEFAULT_SCHEMA_NAMESPACE_PREFIX}
```
public static final String DEFAULT_SCHEMA_NAMESPACE_PREFIX
```

بادئة مساحة الاسم للمخطط الافتراضية.

### DEFAULT_SCHEMA_NAMESPACE_URI {#DEFAULT_SCHEMA_NAMESPACE_URI}
```
public static final String DEFAULT_SCHEMA_NAMESPACE_URI
```

معرف URI لمساحة الاسم للمخطط الافتراضي.

### DEFAULT_VALUE_NAMESPACE_URI {#DEFAULT_VALUE_NAMESPACE_URI}
```
public static final String DEFAULT_VALUE_NAMESPACE_URI
```

معرف URI لمساحة الاسم للقيمة الافتراضية.

### DEFAULT_VALUE_TYPE_NAMESPACE_PREFIX {#DEFAULT_VALUE_TYPE_NAMESPACE_PREFIX}
```
public static final String DEFAULT_VALUE_TYPE_NAMESPACE_PREFIX
```

بادئة مساحة الاسم لنوع القيمة الافتراضية.

### RDF_NAMESPACE_URI {#RDF_NAMESPACE_URI}
```
public static final String RDF_NAMESPACE_URI
```

معرف URI لمساحة الاسم لـ rdf الافتراضية.

### RDF_PREFIX {#RDF_PREFIX}
```
public static final String RDF_PREFIX
```

بادئة مساحة الاسم لـ rdf الافتراضية.

### XMLNS {#XMLNS}
```
public static final String XMLNS
```



### XmpPdfAExtensionSchema {#XmpPdfAExtensionSchema-com.aspose.pdf.XmpPdfAExtensionSchemaDescription-}
يقوم بتهيئة كائن جديد.

### add {#add-com.aspose.pdf.XmpPdfAExtensionObject-}
يضيف كائنًا جديدًا إلى المخطط.

### contains {#contains-com.aspose.pdf.XmpPdfAExtensionObject-}
يحدد ما إذا كان الكائن موجودًا في المخطط.

### createDescriptionValueXml {#createDescriptionValueXml-com.aspose.ms.System.Xml.XmlDocument-}
ينشئ عنصر XML الوصف للكتلة من قيم الخصائص.

### createDescriptionXml {#createDescriptionXml-com.aspose.ms.System.Xml.XmlDocument-}
ينشئ عنصر XML الوصف لجميع المخططات.

### createSchemasElement {#createSchemasElement-com.aspose.ms.System.Xml.XmlNode-}
ينشئ قائمة عناصر المخططات من شجرة XML.

### getDescription {#getDescription--}
```
public XmpPdfAExtensionSchemaDescription getDescription()
```

يحصل على وصف المخطط.

**Returns:**
XmpPdfAExtensionSchemaDescription

### getObjects1 {#getObjects1--}
```
public List getObjects1()
```

يحصل على قائمة الكائنات (الخصائص، أنواع القيم).

**Returns:**
ArrayList

### getObjectsInternal {#getObjectsInternal--}
```
public com.aspose.ms.System.Collections.Generic.List< XmpPdfAExtensionObject > getObjectsInternal()
```

يحصل على قائمة الكائنات (الخصائص، أنواع القيم).

**Returns:**
ArrayList

### getProperty {#getProperty-java.lang.String-}
يعيد خاصية PDF/A حسب اسمها.

### getPropertyIndex {#getPropertyIndex-java.lang.String-}
يعيد فهرس الخاصية بالاسم المعطى.

### getSchemaXml {#getSchemaXml-com.aspose.ms.System.Xml.XmlDocument-}
يعيد عنصر xml (الوسم - li) الذي يمثل المخطط في شجرة xml.

### getValuesXml {#getValuesXml-com.aspose.ms.System.Xml.XmlDocument-com.aspose.ms.System.Xml.XmlElement-}
يحصل على قيم الخصائص كتمثيل شجرة xml.

### initializeSchemaValue {#initializeSchemaValue-com.aspose.ms.System.Xml.XmlNode-com.aspose.pdf.XmpPdfAExtensionSchema-}
يُهيئ قيمة الخاصية.

### isPdfAExtensionPrefix {#isPdfAExtensionPrefix-java.lang.String-}
يحدد ما إذا كانت قيمة البادئة جزءًا من امتداد pdf-a.

### remove {#remove-com.aspose.pdf.XmpPdfAExtensionObject-}
يزيل الكائن من المخطط.
