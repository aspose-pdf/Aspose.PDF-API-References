---
title: "XmpPdfAExtensionSchema"
linktitle: "XmpPdfAExtensionSchema"
second_title: "Aspose.PDF for Java API Referansı"
description: "PDF/A-1 tarafından sağlanan XMP uzantı şemasını tanımlar."
type: docs
weight: 5720
url: /tr/java/com.aspose.pdf/xmppdfaextensionschema/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XmpPdfAExtensionSchema

```
public class XmpPdfAExtensionSchema extends Object
```

PDF/A-1 tarafından sağlanan XMP uzantı şemasını tanımlar.

## Alanlar

| Alan | Açıklama |
| --- | --- |
| [DEFAULT_EXTENSION_NAMESPACE_PREFIX](#DEFAULT_EXTENSION_NAMESPACE_PREFIX) | Varsayılan uzantı ad alanı öneki. |
| [DEFAULT_EXTENSION_NAMESPACE_URI](#DEFAULT_EXTENSION_NAMESPACE_URI) | Varsayılan uzantı ad alanı uri'si. |
| [DEFAULT_FIELD_NAMESPACE_PREFIX](#DEFAULT_FIELD_NAMESPACE_PREFIX) | Varsayılan alan ad alanı öneki. |
| [DEFAULT_FIELD_NAMESPACE_URI](#DEFAULT_FIELD_NAMESPACE_URI) | Varsayılan uzantı ad alanı uri'si. |
| [DEFAULT_PROPERTY_NAMESPACE_PREFIX](#DEFAULT_PROPERTY_NAMESPACE_PREFIX) | Varsayılan özellik ad alanı öneki. |
| [DEFAULT_PROPERTY_NAMESPACE_URI](#DEFAULT_PROPERTY_NAMESPACE_URI) | Varsayılan özellik ad alanı uri'si. |
| [DEFAULT_SCHEMA_NAMESPACE_PREFIX](#DEFAULT_SCHEMA_NAMESPACE_PREFIX) | Varsayılan şema ad alanı öneki. |
| [DEFAULT_SCHEMA_NAMESPACE_URI](#DEFAULT_SCHEMA_NAMESPACE_URI) | Varsayılan şema ad alanı uri'si. |
| [DEFAULT_VALUE_NAMESPACE_URI](#DEFAULT_VALUE_NAMESPACE_URI) | Varsayılan değer ad alanı uri'si. |
| [DEFAULT_VALUE_TYPE_NAMESPACE_PREFIX](#DEFAULT_VALUE_TYPE_NAMESPACE_PREFIX) | Varsayılan değer tipi ad alanı öneki. |
| [RDF_NAMESPACE_URI](#RDF_NAMESPACE_URI) | Varsayılan rdf ad alanı uri'si. |
| [RDF_PREFIX](#RDF_PREFIX) | Varsayılan rdf ad alanı öneki. |
| [XMLNS](#XMLNS) |  |

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [XmpPdfAExtensionSchema](#XmpPdfAExtensionSchema-com.aspose.pdf.XmpPdfAExtensionSchemaDescription-) | Yeni nesneyi başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [add](#add-com.aspose.pdf.XmpPdfAExtensionObject-) | Şemaya yeni nesne ekler. |
| [contains](#contains-com.aspose.pdf.XmpPdfAExtensionObject-) | Nesnenin şemada mevcut olup olmadığını belirler. |
| [createDescriptionValueXml](#createDescriptionValueXml-com.aspose.ms.System.Xml.XmlDocument-) | Özellik değerleri bloğu için açıklama xml öğesini oluşturur. |
| [createDescriptionXml](#createDescriptionXml-com.aspose.ms.System.Xml.XmlDocument-) | Tüm şemalar için açıklama xml öğesini oluşturur. |
| [createSchemasElement](#createSchemasElement-com.aspose.ms.System.Xml.XmlNode-) | Xml ağacından şema öğeleri listesini oluşturur. |
| [getDescription](#getDescription--) | Şema açıklamasını alır. |
| [getObjects1](#getObjects1--) | Nesnelerin (özellikler, değer tipleri) listesini alır. |
| [getObjectsInternal](#getObjectsInternal--) | Nesnelerin (özellikler, değer tipleri) listesini alır. |
| [getProperty](#getProperty-java.lang.String-) | PDF/A özelliğini adından döndürür. |
| [getPropertyIndex](#getPropertyIndex-java.lang.String-) | Verilen adla özelliğin dizinini döndürür. |
| [getSchemaXml](#getSchemaXml-com.aspose.ms.System.Xml.XmlDocument-) | XML ağacında şemayı temsil eden xml öğesini (etiket - li) döndürür. |
| [getValuesXml](#getValuesXml-com.aspose.ms.System.Xml.XmlDocument-com.aspose.ms.System.Xml.XmlElement-) | Özelliklerin değerlerini xml ağaç temsili olarak alır. |
| [initializeSchemaValue](#initializeSchemaValue-com.aspose.ms.System.Xml.XmlNode-com.aspose.pdf.XmpPdfAExtensionSchema-) | Özelliğin değerini başlatır. |
| [isPdfAExtensionPrefix](#isPdfAExtensionPrefix-java.lang.String-) | Önek değerinin pdf-a uzantısının bir parçası olup olmadığını belirler. |
| [remove](#remove-com.aspose.pdf.XmpPdfAExtensionObject-) | Nesneyi şemadan kaldırır. |

### DEFAULT_EXTENSION_NAMESPACE_PREFIX {#DEFAULT_EXTENSION_NAMESPACE_PREFIX}
```
public static final String DEFAULT_EXTENSION_NAMESPACE_PREFIX
```

Varsayılan uzantı ad alanı öneki.

### DEFAULT_EXTENSION_NAMESPACE_URI {#DEFAULT_EXTENSION_NAMESPACE_URI}
```
public static final String DEFAULT_EXTENSION_NAMESPACE_URI
```

Varsayılan uzantı ad alanı uri'si.

### DEFAULT_FIELD_NAMESPACE_PREFIX {#DEFAULT_FIELD_NAMESPACE_PREFIX}
```
public static final String DEFAULT_FIELD_NAMESPACE_PREFIX
```

Varsayılan alan ad alanı öneki.

### DEFAULT_FIELD_NAMESPACE_URI {#DEFAULT_FIELD_NAMESPACE_URI}
```
public static final String DEFAULT_FIELD_NAMESPACE_URI
```

Varsayılan uzantı ad alanı uri'si.

### DEFAULT_PROPERTY_NAMESPACE_PREFIX {#DEFAULT_PROPERTY_NAMESPACE_PREFIX}
```
public static final String DEFAULT_PROPERTY_NAMESPACE_PREFIX
```

Varsayılan özellik ad alanı öneki.

### DEFAULT_PROPERTY_NAMESPACE_URI {#DEFAULT_PROPERTY_NAMESPACE_URI}
```
public static final String DEFAULT_PROPERTY_NAMESPACE_URI
```

Varsayılan özellik ad alanı uri'si.

### DEFAULT_SCHEMA_NAMESPACE_PREFIX {#DEFAULT_SCHEMA_NAMESPACE_PREFIX}
```
public static final String DEFAULT_SCHEMA_NAMESPACE_PREFIX
```

Varsayılan şema ad alanı öneki.

### DEFAULT_SCHEMA_NAMESPACE_URI {#DEFAULT_SCHEMA_NAMESPACE_URI}
```
public static final String DEFAULT_SCHEMA_NAMESPACE_URI
```

Varsayılan şema ad alanı uri'si.

### DEFAULT_VALUE_NAMESPACE_URI {#DEFAULT_VALUE_NAMESPACE_URI}
```
public static final String DEFAULT_VALUE_NAMESPACE_URI
```

Varsayılan değer ad alanı uri'si.

### DEFAULT_VALUE_TYPE_NAMESPACE_PREFIX {#DEFAULT_VALUE_TYPE_NAMESPACE_PREFIX}
```
public static final String DEFAULT_VALUE_TYPE_NAMESPACE_PREFIX
```

Varsayılan değer tipi ad alanı öneki.

### RDF_NAMESPACE_URI {#RDF_NAMESPACE_URI}
```
public static final String RDF_NAMESPACE_URI
```

Varsayılan rdf ad alanı uri'si.

### RDF_PREFIX {#RDF_PREFIX}
```
public static final String RDF_PREFIX
```

Varsayılan rdf ad alanı öneki.

### XMLNS {#XMLNS}
```
public static final String XMLNS
```



### XmpPdfAExtensionSchema {#XmpPdfAExtensionSchema-com.aspose.pdf.XmpPdfAExtensionSchemaDescription-}
Yeni nesneyi başlatır.

### add {#add-com.aspose.pdf.XmpPdfAExtensionObject-}
Şemaya yeni nesne ekler.

### contains {#contains-com.aspose.pdf.XmpPdfAExtensionObject-}
Nesnenin şemada mevcut olup olmadığını belirler.

### createDescriptionValueXml {#createDescriptionValueXml-com.aspose.ms.System.Xml.XmlDocument-}
Özellik değerleri bloğu için açıklama xml öğesini oluşturur.

### createDescriptionXml {#createDescriptionXml-com.aspose.ms.System.Xml.XmlDocument-}
Tüm şemalar için açıklama xml öğesini oluşturur.

### createSchemasElement {#createSchemasElement-com.aspose.ms.System.Xml.XmlNode-}
Xml ağacından şema öğeleri listesini oluşturur.

### getDescription {#getDescription--}
```
public XmpPdfAExtensionSchemaDescription getDescription()
```

Şema açıklamasını alır.

**Returns:**
XmpPdfAExtensionSchemaDescription

### getObjects1 {#getObjects1--}
```
public List getObjects1()
```

Nesnelerin (özellikler, değer tipleri) listesini alır.

**Returns:**
ArrayList

### getObjectsInternal {#getObjectsInternal--}
```
public com.aspose.ms.System.Collections.Generic.List< XmpPdfAExtensionObject > getObjectsInternal()
```

Nesnelerin (özellikler, değer tipleri) listesini alır.

**Returns:**
ArrayList

### getProperty {#getProperty-java.lang.String-}
PDF/A özelliğini adından döndürür.

### getPropertyIndex {#getPropertyIndex-java.lang.String-}
Verilen adla özelliğin dizinini döndürür.

### getSchemaXml {#getSchemaXml-com.aspose.ms.System.Xml.XmlDocument-}
XML ağacında şemayı temsil eden xml öğesini (etiket - li) döndürür.

### getValuesXml {#getValuesXml-com.aspose.ms.System.Xml.XmlDocument-com.aspose.ms.System.Xml.XmlElement-}
Özelliklerin değerlerini xml ağaç temsili olarak alır.

### initializeSchemaValue {#initializeSchemaValue-com.aspose.ms.System.Xml.XmlNode-com.aspose.pdf.XmpPdfAExtensionSchema-}
Özelliğin değerini başlatır.

### isPdfAExtensionPrefix {#isPdfAExtensionPrefix-java.lang.String-}
Önek değerinin pdf-a uzantısının bir parçası olup olmadığını belirler.

### remove {#remove-com.aspose.pdf.XmpPdfAExtensionObject-}
Nesneyi şemadan kaldırır.
