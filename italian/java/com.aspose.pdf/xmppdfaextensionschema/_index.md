---
title: "XmpPdfAExtensionSchema"
linktitle: "XmpPdfAExtensionSchema"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Descrive lo schema di estensione XMP fornito da PDF/A-1."
type: docs
weight: 5720
url: /it/java/com.aspose.pdf/xmppdfaextensionschema/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XmpPdfAExtensionSchema

```
public class XmpPdfAExtensionSchema extends Object
```

Descrive lo schema di estensione XMP fornito da PDF/A-1.

## Campi

| Campo | Descrizione |
| --- | --- |
| [DEFAULT_EXTENSION_NAMESPACE_PREFIX](#DEFAULT_EXTENSION_NAMESPACE_PREFIX) | Prefisso predefinito dello spazio dei nomi di estensione. |
| [DEFAULT_EXTENSION_NAMESPACE_URI](#DEFAULT_EXTENSION_NAMESPACE_URI) | URI predefinito dello spazio dei nomi di estensione. |
| [DEFAULT_FIELD_NAMESPACE_PREFIX](#DEFAULT_FIELD_NAMESPACE_PREFIX) | Prefisso predefinito dello spazio dei nomi del campo. |
| [DEFAULT_FIELD_NAMESPACE_URI](#DEFAULT_FIELD_NAMESPACE_URI) | URI predefinito dello spazio dei nomi di estensione. |
| [DEFAULT_PROPERTY_NAMESPACE_PREFIX](#DEFAULT_PROPERTY_NAMESPACE_PREFIX) | Prefisso predefinito dello spazio dei nomi della proprietà. |
| [DEFAULT_PROPERTY_NAMESPACE_URI](#DEFAULT_PROPERTY_NAMESPACE_URI) | URI predefinito dello spazio dei nomi della proprietà. |
| [DEFAULT_SCHEMA_NAMESPACE_PREFIX](#DEFAULT_SCHEMA_NAMESPACE_PREFIX) | Prefisso predefinito dello spazio dei nomi dello schema. |
| [DEFAULT_SCHEMA_NAMESPACE_URI](#DEFAULT_SCHEMA_NAMESPACE_URI) | URI predefinito dello spazio dei nomi dello schema. |
| [DEFAULT_VALUE_NAMESPACE_URI](#DEFAULT_VALUE_NAMESPACE_URI) | URI predefinito dello spazio dei nomi del valore. |
| [DEFAULT_VALUE_TYPE_NAMESPACE_PREFIX](#DEFAULT_VALUE_TYPE_NAMESPACE_PREFIX) | Prefisso predefinito dello spazio dei nomi del tipo di valore. |
| [RDF_NAMESPACE_URI](#RDF_NAMESPACE_URI) | URI predefinito dello spazio dei nomi RDF. |
| [RDF_PREFIX](#RDF_PREFIX) | Prefisso predefinito dello spazio dei nomi RDF. |
| [XMLNS](#XMLNS) |  |

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [XmpPdfAExtensionSchema](#XmpPdfAExtensionSchema-com.aspose.pdf.XmpPdfAExtensionSchemaDescription-) | Inizializza un nuovo oggetto. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [add](#add-com.aspose.pdf.XmpPdfAExtensionObject-) | Aggiunge un nuovo oggetto nello schema. |
| [contains](#contains-com.aspose.pdf.XmpPdfAExtensionObject-) | Determina se l'oggetto esiste nello schema. |
| [createDescriptionValueXml](#createDescriptionValueXml-com.aspose.ms.System.Xml.XmlDocument-) | Crea l'elemento XML di descrizione per il blocco dei valori delle proprietà. |
| [createDescriptionXml](#createDescriptionXml-com.aspose.ms.System.Xml.XmlDocument-) | Crea l'elemento XML di descrizione per tutti gli schemi. |
| [createSchemasElement](#createSchemasElement-com.aspose.ms.System.Xml.XmlNode-) | Crea l'elenco degli elementi degli schemi dall'albero XML. |
| [getDescription](#getDescription--) | Ottiene la descrizione dello schema. |
| [getObjects1](#getObjects1--) | Ottiene l'elenco degli oggetti (proprietà, tipi di valore). |
| [getObjectsInternal](#getObjectsInternal--) | Ottiene l'elenco degli oggetti (proprietà, tipi di valore). |
| [getProperty](#getProperty-java.lang.String-) | Restituisce la proprietà PDF/A per il suo nome. |
| [getPropertyIndex](#getPropertyIndex-java.lang.String-) | Restituisce l'indice della proprietà con il nome specificato. |
| [getSchemaXml](#getSchemaXml-com.aspose.ms.System.Xml.XmlDocument-) | Restituisce l'elemento xml (tag - li) che rappresenta lo schema nell'albero xml. |
| [getValuesXml](#getValuesXml-com.aspose.ms.System.Xml.XmlDocument-com.aspose.ms.System.Xml.XmlElement-) | Ottiene i valori delle proprietà come rappresentazione ad albero xml. |
| [initializeSchemaValue](#initializeSchemaValue-com.aspose.ms.System.Xml.XmlNode-com.aspose.pdf.XmpPdfAExtensionSchema-) | Inizializza il valore della proprietà. |
| [isPdfAExtensionPrefix](#isPdfAExtensionPrefix-java.lang.String-) | Determina se il valore del prefisso fa parte dell'estensione pdf-a. |
| [remove](#remove-com.aspose.pdf.XmpPdfAExtensionObject-) | Rimuove l'oggetto dallo schema. |

### DEFAULT_EXTENSION_NAMESPACE_PREFIX {#DEFAULT_EXTENSION_NAMESPACE_PREFIX}
```
public static final String DEFAULT_EXTENSION_NAMESPACE_PREFIX
```

Prefisso predefinito dello spazio dei nomi di estensione.

### DEFAULT_EXTENSION_NAMESPACE_URI {#DEFAULT_EXTENSION_NAMESPACE_URI}
```
public static final String DEFAULT_EXTENSION_NAMESPACE_URI
```

URI predefinito dello spazio dei nomi di estensione.

### DEFAULT_FIELD_NAMESPACE_PREFIX {#DEFAULT_FIELD_NAMESPACE_PREFIX}
```
public static final String DEFAULT_FIELD_NAMESPACE_PREFIX
```

Prefisso predefinito dello spazio dei nomi del campo.

### DEFAULT_FIELD_NAMESPACE_URI {#DEFAULT_FIELD_NAMESPACE_URI}
```
public static final String DEFAULT_FIELD_NAMESPACE_URI
```

URI predefinito dello spazio dei nomi di estensione.

### DEFAULT_PROPERTY_NAMESPACE_PREFIX {#DEFAULT_PROPERTY_NAMESPACE_PREFIX}
```
public static final String DEFAULT_PROPERTY_NAMESPACE_PREFIX
```

Prefisso predefinito dello spazio dei nomi della proprietà.

### DEFAULT_PROPERTY_NAMESPACE_URI {#DEFAULT_PROPERTY_NAMESPACE_URI}
```
public static final String DEFAULT_PROPERTY_NAMESPACE_URI
```

URI predefinito dello spazio dei nomi della proprietà.

### DEFAULT_SCHEMA_NAMESPACE_PREFIX {#DEFAULT_SCHEMA_NAMESPACE_PREFIX}
```
public static final String DEFAULT_SCHEMA_NAMESPACE_PREFIX
```

Prefisso predefinito dello spazio dei nomi dello schema.

### DEFAULT_SCHEMA_NAMESPACE_URI {#DEFAULT_SCHEMA_NAMESPACE_URI}
```
public static final String DEFAULT_SCHEMA_NAMESPACE_URI
```

URI predefinito dello spazio dei nomi dello schema.

### DEFAULT_VALUE_NAMESPACE_URI {#DEFAULT_VALUE_NAMESPACE_URI}
```
public static final String DEFAULT_VALUE_NAMESPACE_URI
```

URI predefinito dello spazio dei nomi del valore.

### DEFAULT_VALUE_TYPE_NAMESPACE_PREFIX {#DEFAULT_VALUE_TYPE_NAMESPACE_PREFIX}
```
public static final String DEFAULT_VALUE_TYPE_NAMESPACE_PREFIX
```

Prefisso predefinito dello spazio dei nomi del tipo di valore.

### RDF_NAMESPACE_URI {#RDF_NAMESPACE_URI}
```
public static final String RDF_NAMESPACE_URI
```

URI predefinito dello spazio dei nomi RDF.

### RDF_PREFIX {#RDF_PREFIX}
```
public static final String RDF_PREFIX
```

Prefisso predefinito dello spazio dei nomi RDF.

### XMLNS {#XMLNS}
```
public static final String XMLNS
```



### XmpPdfAExtensionSchema {#XmpPdfAExtensionSchema-com.aspose.pdf.XmpPdfAExtensionSchemaDescription-}
Inizializza un nuovo oggetto.

### add {#add-com.aspose.pdf.XmpPdfAExtensionObject-}
Aggiunge un nuovo oggetto nello schema.

### contains {#contains-com.aspose.pdf.XmpPdfAExtensionObject-}
Determina se l'oggetto esiste nello schema.

### createDescriptionValueXml {#createDescriptionValueXml-com.aspose.ms.System.Xml.XmlDocument-}
Crea l'elemento XML di descrizione per il blocco dei valori delle proprietà.

### createDescriptionXml {#createDescriptionXml-com.aspose.ms.System.Xml.XmlDocument-}
Crea l'elemento XML di descrizione per tutti gli schemi.

### createSchemasElement {#createSchemasElement-com.aspose.ms.System.Xml.XmlNode-}
Crea l'elenco degli elementi degli schemi dall'albero XML.

### getDescription {#getDescription--}
```
public XmpPdfAExtensionSchemaDescription getDescription()
```

Ottiene la descrizione dello schema.

**Returns:**
XmpPdfAExtensionSchemaDescription

### getObjects1 {#getObjects1--}
```
public List getObjects1()
```

Ottiene l'elenco degli oggetti (proprietà, tipi di valore).

**Returns:**
ArrayList

### getObjectsInternal {#getObjectsInternal--}
```
public com.aspose.ms.System.Collections.Generic.List< XmpPdfAExtensionObject > getObjectsInternal()
```

Ottiene l'elenco degli oggetti (proprietà, tipi di valore).

**Returns:**
ArrayList

### getProperty {#getProperty-java.lang.String-}
Restituisce la proprietà PDF/A per il suo nome.

### getPropertyIndex {#getPropertyIndex-java.lang.String-}
Restituisce l'indice della proprietà con il nome specificato.

### getSchemaXml {#getSchemaXml-com.aspose.ms.System.Xml.XmlDocument-}
Restituisce l'elemento xml (tag - li) che rappresenta lo schema nell'albero xml.

### getValuesXml {#getValuesXml-com.aspose.ms.System.Xml.XmlDocument-com.aspose.ms.System.Xml.XmlElement-}
Ottiene i valori delle proprietà come rappresentazione ad albero xml.

### initializeSchemaValue {#initializeSchemaValue-com.aspose.ms.System.Xml.XmlNode-com.aspose.pdf.XmpPdfAExtensionSchema-}
Inizializza il valore della proprietà.

### isPdfAExtensionPrefix {#isPdfAExtensionPrefix-java.lang.String-}
Determina se il valore del prefisso fa parte dell'estensione pdf-a.

### remove {#remove-com.aspose.pdf.XmpPdfAExtensionObject-}
Rimuove l'oggetto dallo schema.
