---
title: "XmpPdfAExtensionSchema"
linktitle: "XmpPdfAExtensionSchema"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Menjelaskan skema ekstensi XMP yang disediakan oleh PDF/A-1."
type: docs
weight: 5720
url: /id/java/com.aspose.pdf/xmppdfaextensionschema/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XmpPdfAExtensionSchema

```
public class XmpPdfAExtensionSchema extends Object
```

Menjelaskan skema ekstensi XMP yang disediakan oleh PDF/A-1.

## Fields

| Field | Deskripsi |
| --- | --- |
| [DEFAULT_EXTENSION_NAMESPACE_PREFIX](#DEFAULT_EXTENSION_NAMESPACE_PREFIX) | Prefiks ruang nama ekstensi default. |
| [DEFAULT_EXTENSION_NAMESPACE_URI](#DEFAULT_EXTENSION_NAMESPACE_URI) | URI ruang nama ekstensi default. |
| [DEFAULT_FIELD_NAMESPACE_PREFIX](#DEFAULT_FIELD_NAMESPACE_PREFIX) | Prefiks ruang nama bidang default. |
| [DEFAULT_FIELD_NAMESPACE_URI](#DEFAULT_FIELD_NAMESPACE_URI) | URI ruang nama ekstensi default. |
| [DEFAULT_PROPERTY_NAMESPACE_PREFIX](#DEFAULT_PROPERTY_NAMESPACE_PREFIX) | Prefiks ruang nama properti default. |
| [DEFAULT_PROPERTY_NAMESPACE_URI](#DEFAULT_PROPERTY_NAMESPACE_URI) | URI ruang nama properti default. |
| [DEFAULT_SCHEMA_NAMESPACE_PREFIX](#DEFAULT_SCHEMA_NAMESPACE_PREFIX) | Prefiks ruang nama skema default. |
| [DEFAULT_SCHEMA_NAMESPACE_URI](#DEFAULT_SCHEMA_NAMESPACE_URI) | URI ruang nama skema default. |
| [DEFAULT_VALUE_NAMESPACE_URI](#DEFAULT_VALUE_NAMESPACE_URI) | URI ruang nama nilai default. |
| [DEFAULT_VALUE_TYPE_NAMESPACE_PREFIX](#DEFAULT_VALUE_TYPE_NAMESPACE_PREFIX) | Prefiks ruang nama tipe valie default. |
| [RDF_NAMESPACE_URI](#RDF_NAMESPACE_URI) | URI ruang nama rdf default. |
| [RDF_PREFIX](#RDF_PREFIX) | Prefiks ruang nama rdf default. |
| [XMLNS](#XMLNS) |  |

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [XmpPdfAExtensionSchema](#XmpPdfAExtensionSchema-com.aspose.pdf.XmpPdfAExtensionSchemaDescription-) | Menginisialisasi objek baru. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [add](#add-com.aspose.pdf.XmpPdfAExtensionObject-) | Menambahkan objek baru ke dalam skema. |
| [contains](#contains-com.aspose.pdf.XmpPdfAExtensionObject-) | Menentukan apakah obj ada dalam skema. |
| [createDescriptionValueXml](#createDescriptionValueXml-com.aspose.ms.System.Xml.XmlDocument-) | Membuat elemen xml deskripsi untuk blok nilai properti. |
| [createDescriptionXml](#createDescriptionXml-com.aspose.ms.System.Xml.XmlDocument-) | Membuat elemen xml deskripsi untuk semua skema. |
| [createSchemasElement](#createSchemasElement-com.aspose.ms.System.Xml.XmlNode-) | Membuat daftar elemen skema dari pohon xml. |
| [getDescription](#getDescription--) | Mendapatkan deskripsi skema. |
| [getObjects1](#getObjects1--) | Mendapatkan daftar objek (properti, tipe nilai). |
| [getObjectsInternal](#getObjectsInternal--) | Mendapatkan daftar objek (properti, tipe nilai). |
| [getProperty](#getProperty-java.lang.String-) | Mengembalikan properti PDF/A berdasarkan namanya. |
| [getPropertyIndex](#getPropertyIndex-java.lang.String-) | Mengembalikan indeks properti dengan nama yang diberikan. |
| [getSchemaXml](#getSchemaXml-com.aspose.ms.System.Xml.XmlDocument-) | Mengembalikan elemen xml (tag - li) yang mewakili skema dalam pohon xml. |
| [getValuesXml](#getValuesXml-com.aspose.ms.System.Xml.XmlDocument-com.aspose.ms.System.Xml.XmlElement-) | Mendapatkan nilai properti sebagai representasi pohon xml. |
| [initializeSchemaValue](#initializeSchemaValue-com.aspose.ms.System.Xml.XmlNode-com.aspose.pdf.XmpPdfAExtensionSchema-) | Menginisialisasi nilai properti. |
| [isPdfAExtensionPrefix](#isPdfAExtensionPrefix-java.lang.String-) | Menentukan apakah nilai prefiks merupakan bagian dari ekstensi pdf-a. |
| [remove](#remove-com.aspose.pdf.XmpPdfAExtensionObject-) | Menghapus objek dari skema. |

### DEFAULT_EXTENSION_NAMESPACE_PREFIX {#DEFAULT_EXTENSION_NAMESPACE_PREFIX}
```
public static final String DEFAULT_EXTENSION_NAMESPACE_PREFIX
```

Prefiks ruang nama ekstensi default.

### DEFAULT_EXTENSION_NAMESPACE_URI {#DEFAULT_EXTENSION_NAMESPACE_URI}
```
public static final String DEFAULT_EXTENSION_NAMESPACE_URI
```

URI ruang nama ekstensi default.

### DEFAULT_FIELD_NAMESPACE_PREFIX {#DEFAULT_FIELD_NAMESPACE_PREFIX}
```
public static final String DEFAULT_FIELD_NAMESPACE_PREFIX
```

Prefiks ruang nama bidang default.

### DEFAULT_FIELD_NAMESPACE_URI {#DEFAULT_FIELD_NAMESPACE_URI}
```
public static final String DEFAULT_FIELD_NAMESPACE_URI
```

URI ruang nama ekstensi default.

### DEFAULT_PROPERTY_NAMESPACE_PREFIX {#DEFAULT_PROPERTY_NAMESPACE_PREFIX}
```
public static final String DEFAULT_PROPERTY_NAMESPACE_PREFIX
```

Prefiks ruang nama properti default.

### DEFAULT_PROPERTY_NAMESPACE_URI {#DEFAULT_PROPERTY_NAMESPACE_URI}
```
public static final String DEFAULT_PROPERTY_NAMESPACE_URI
```

URI ruang nama properti default.

### DEFAULT_SCHEMA_NAMESPACE_PREFIX {#DEFAULT_SCHEMA_NAMESPACE_PREFIX}
```
public static final String DEFAULT_SCHEMA_NAMESPACE_PREFIX
```

Prefiks ruang nama skema default.

### DEFAULT_SCHEMA_NAMESPACE_URI {#DEFAULT_SCHEMA_NAMESPACE_URI}
```
public static final String DEFAULT_SCHEMA_NAMESPACE_URI
```

URI ruang nama skema default.

### DEFAULT_VALUE_NAMESPACE_URI {#DEFAULT_VALUE_NAMESPACE_URI}
```
public static final String DEFAULT_VALUE_NAMESPACE_URI
```

URI ruang nama nilai default.

### DEFAULT_VALUE_TYPE_NAMESPACE_PREFIX {#DEFAULT_VALUE_TYPE_NAMESPACE_PREFIX}
```
public static final String DEFAULT_VALUE_TYPE_NAMESPACE_PREFIX
```

Prefiks ruang nama tipe valie default.

### RDF_NAMESPACE_URI {#RDF_NAMESPACE_URI}
```
public static final String RDF_NAMESPACE_URI
```

URI ruang nama rdf default.

### RDF_PREFIX {#RDF_PREFIX}
```
public static final String RDF_PREFIX
```

Prefiks ruang nama rdf default.

### XMLNS {#XMLNS}
```
public static final String XMLNS
```



### XmpPdfAExtensionSchema {#XmpPdfAExtensionSchema-com.aspose.pdf.XmpPdfAExtensionSchemaDescription-}
Menginisialisasi objek baru.

### add {#add-com.aspose.pdf.XmpPdfAExtensionObject-}
Menambahkan objek baru ke dalam skema.

### contains {#contains-com.aspose.pdf.XmpPdfAExtensionObject-}
Menentukan apakah obj ada dalam skema.

### createDescriptionValueXml {#createDescriptionValueXml-com.aspose.ms.System.Xml.XmlDocument-}
Membuat elemen xml deskripsi untuk blok nilai properti.

### createDescriptionXml {#createDescriptionXml-com.aspose.ms.System.Xml.XmlDocument-}
Membuat elemen xml deskripsi untuk semua skema.

### createSchemasElement {#createSchemasElement-com.aspose.ms.System.Xml.XmlNode-}
Membuat daftar elemen skema dari pohon xml.

### getDescription {#getDescription--}
```
public XmpPdfAExtensionSchemaDescription getDescription()
```

Mendapatkan deskripsi skema.

**Returns:**
XmpPdfAExtensionSchemaDescription

### getObjects1 {#getObjects1--}
```
public List getObjects1()
```

Mendapatkan daftar objek (properti, tipe nilai).

**Returns:**
ArrayList

### getObjectsInternal {#getObjectsInternal--}
```
public com.aspose.ms.System.Collections.Generic.List< XmpPdfAExtensionObject > getObjectsInternal()
```

Mendapatkan daftar objek (properti, tipe nilai).

**Returns:**
ArrayList

### getProperty {#getProperty-java.lang.String-}
Mengembalikan properti PDF/A berdasarkan namanya.

### getPropertyIndex {#getPropertyIndex-java.lang.String-}
Mengembalikan indeks properti dengan nama yang diberikan.

### getSchemaXml {#getSchemaXml-com.aspose.ms.System.Xml.XmlDocument-}
Mengembalikan elemen xml (tag - li) yang mewakili skema dalam pohon xml.

### getValuesXml {#getValuesXml-com.aspose.ms.System.Xml.XmlDocument-com.aspose.ms.System.Xml.XmlElement-}
Mendapatkan nilai properti sebagai representasi pohon xml.

### initializeSchemaValue {#initializeSchemaValue-com.aspose.ms.System.Xml.XmlNode-com.aspose.pdf.XmpPdfAExtensionSchema-}
Menginisialisasi nilai properti.

### isPdfAExtensionPrefix {#isPdfAExtensionPrefix-java.lang.String-}
Menentukan apakah nilai prefiks merupakan bagian dari ekstensi pdf-a.

### remove {#remove-com.aspose.pdf.XmpPdfAExtensionObject-}
Menghapus objek dari skema.
