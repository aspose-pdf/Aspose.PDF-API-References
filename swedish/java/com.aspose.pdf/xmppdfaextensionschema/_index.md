---
title: "XmpPdfAExtensionSchema"
linktitle: "XmpPdfAExtensionSchema"
second_title: "Aspose.PDF för Java API-referens"
description: "Beskriver XMP-utökningens schema som tillhandahålls av PDF/A-1."
type: docs
weight: 5720
url: /sv/java/com.aspose.pdf/xmppdfaextensionschema/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XmpPdfAExtensionSchema

```
public class XmpPdfAExtensionSchema extends Object
```

Beskriver XMP-utökningens schema som tillhandahålls av PDF/A-1.

## Fält

| Fält | Beskrivning |
| --- | --- |
| [DEFAULT_EXTENSION_NAMESPACE_PREFIX](#DEFAULT_EXTENSION_NAMESPACE_PREFIX) | Standard prefix för extensionsnamnrymd. |
| [DEFAULT_EXTENSION_NAMESPACE_URI](#DEFAULT_EXTENSION_NAMESPACE_URI) | Standard URI för extensionsnamnrymd. |
| [DEFAULT_FIELD_NAMESPACE_PREFIX](#DEFAULT_FIELD_NAMESPACE_PREFIX) | Standard prefix för fältnamnrymd. |
| [DEFAULT_FIELD_NAMESPACE_URI](#DEFAULT_FIELD_NAMESPACE_URI) | Standard URI för extensionsnamnrymd. |
| [DEFAULT_PROPERTY_NAMESPACE_PREFIX](#DEFAULT_PROPERTY_NAMESPACE_PREFIX) | Standard prefix för egenskapsnamnrymd. |
| [DEFAULT_PROPERTY_NAMESPACE_URI](#DEFAULT_PROPERTY_NAMESPACE_URI) | Standard URI för egenskapsnamnrymd. |
| [DEFAULT_SCHEMA_NAMESPACE_PREFIX](#DEFAULT_SCHEMA_NAMESPACE_PREFIX) | Standard prefix för schemanamnrymd. |
| [DEFAULT_SCHEMA_NAMESPACE_URI](#DEFAULT_SCHEMA_NAMESPACE_URI) | Standard URI för schemanamnrymd. |
| [DEFAULT_VALUE_NAMESPACE_URI](#DEFAULT_VALUE_NAMESPACE_URI) | Standard URI för värdenamnrymd. |
| [DEFAULT_VALUE_TYPE_NAMESPACE_PREFIX](#DEFAULT_VALUE_TYPE_NAMESPACE_PREFIX) | Standard prefix för värdetypnamnrymd. |
| [RDF_NAMESPACE_URI](#RDF_NAMESPACE_URI) | Standard URI för rdf‑namnrymd. |
| [RDF_PREFIX](#RDF_PREFIX) | Standard prefix för rdf‑namnrymd. |
| [XMLNS](#XMLNS) |  |

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [XmpPdfAExtensionSchema](#XmpPdfAExtensionSchema-com.aspose.pdf.XmpPdfAExtensionSchemaDescription-) | Initierar ett nytt objekt. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [add](#add-com.aspose.pdf.XmpPdfAExtensionObject-) | Lägger till ett nytt objekt i schemat. |
| [contains](#contains-com.aspose.pdf.XmpPdfAExtensionObject-) | Bestämmer om obj finns i schemat. |
| [createDescriptionValueXml](#createDescriptionValueXml-com.aspose.ms.System.Xml.XmlDocument-) | Skapar beskrivningselementet xml för blocket med egenskapsvärden. |
| [createDescriptionXml](#createDescriptionXml-com.aspose.ms.System.Xml.XmlDocument-) | Skapar beskrivningselementet xml för alla scheman. |
| [createSchemasElement](#createSchemasElement-com.aspose.ms.System.Xml.XmlNode-) | Skapar listan med schemanelement från xml‑trädet. |
| [getDescription](#getDescription--) | Hämtar schemabeskrivningen. |
| [getObjects1](#getObjects1--) | Hämtar listan med objekt (egenskaper, värdetyper). |
| [getObjectsInternal](#getObjectsInternal--) | Hämtar listan med objekt (egenskaper, värdetyper). |
| [getProperty](#getProperty-java.lang.String-) | Returnerar PDF/A‑egenskapen efter dess namn. |
| [getPropertyIndex](#getPropertyIndex-java.lang.String-) | Returnerar index för egenskapen med angivet namn. |
| [getSchemaXml](#getSchemaXml-com.aspose.ms.System.Xml.XmlDocument-) | Returnerar xml-elementet (tagg - li) som representerar schemat i xml-trädet. |
| [getValuesXml](#getValuesXml-com.aspose.ms.System.Xml.XmlDocument-com.aspose.ms.System.Xml.XmlElement-) | Hämtar värdena för egenskaperna som en xml-trädrepresentation. |
| [initializeSchemaValue](#initializeSchemaValue-com.aspose.ms.System.Xml.XmlNode-com.aspose.pdf.XmpPdfAExtensionSchema-) | Initierar värdet för egenskapen. |
| [isPdfAExtensionPrefix](#isPdfAExtensionPrefix-java.lang.String-) | Avgör om prefixvärdet är en del av pdf-a‑tillägget. |
| [remove](#remove-com.aspose.pdf.XmpPdfAExtensionObject-) | Tar bort objektet från schemat. |

### DEFAULT_EXTENSION_NAMESPACE_PREFIX {#DEFAULT_EXTENSION_NAMESPACE_PREFIX}
```
public static final String DEFAULT_EXTENSION_NAMESPACE_PREFIX
```

Standard prefix för extensionsnamnrymd.

### DEFAULT_EXTENSION_NAMESPACE_URI {#DEFAULT_EXTENSION_NAMESPACE_URI}
```
public static final String DEFAULT_EXTENSION_NAMESPACE_URI
```

Standard URI för extensionsnamnrymd.

### DEFAULT_FIELD_NAMESPACE_PREFIX {#DEFAULT_FIELD_NAMESPACE_PREFIX}
```
public static final String DEFAULT_FIELD_NAMESPACE_PREFIX
```

Standard prefix för fältnamnrymd.

### DEFAULT_FIELD_NAMESPACE_URI {#DEFAULT_FIELD_NAMESPACE_URI}
```
public static final String DEFAULT_FIELD_NAMESPACE_URI
```

Standard URI för extensionsnamnrymd.

### DEFAULT_PROPERTY_NAMESPACE_PREFIX {#DEFAULT_PROPERTY_NAMESPACE_PREFIX}
```
public static final String DEFAULT_PROPERTY_NAMESPACE_PREFIX
```

Standard prefix för egenskapsnamnrymd.

### DEFAULT_PROPERTY_NAMESPACE_URI {#DEFAULT_PROPERTY_NAMESPACE_URI}
```
public static final String DEFAULT_PROPERTY_NAMESPACE_URI
```

Standard URI för egenskapsnamnrymd.

### DEFAULT_SCHEMA_NAMESPACE_PREFIX {#DEFAULT_SCHEMA_NAMESPACE_PREFIX}
```
public static final String DEFAULT_SCHEMA_NAMESPACE_PREFIX
```

Standard prefix för schemanamnrymd.

### DEFAULT_SCHEMA_NAMESPACE_URI {#DEFAULT_SCHEMA_NAMESPACE_URI}
```
public static final String DEFAULT_SCHEMA_NAMESPACE_URI
```

Standard URI för schemanamnrymd.

### DEFAULT_VALUE_NAMESPACE_URI {#DEFAULT_VALUE_NAMESPACE_URI}
```
public static final String DEFAULT_VALUE_NAMESPACE_URI
```

Standard URI för värdenamnrymd.

### DEFAULT_VALUE_TYPE_NAMESPACE_PREFIX {#DEFAULT_VALUE_TYPE_NAMESPACE_PREFIX}
```
public static final String DEFAULT_VALUE_TYPE_NAMESPACE_PREFIX
```

Standard prefix för värdetypnamnrymd.

### RDF_NAMESPACE_URI {#RDF_NAMESPACE_URI}
```
public static final String RDF_NAMESPACE_URI
```

Standard URI för rdf‑namnrymd.

### RDF_PREFIX {#RDF_PREFIX}
```
public static final String RDF_PREFIX
```

Standard prefix för rdf‑namnrymd.

### XMLNS {#XMLNS}
```
public static final String XMLNS
```



### XmpPdfAExtensionSchema {#XmpPdfAExtensionSchema-com.aspose.pdf.XmpPdfAExtensionSchemaDescription-}
Initierar ett nytt objekt.

### add {#add-com.aspose.pdf.XmpPdfAExtensionObject-}
Lägger till ett nytt objekt i schemat.

### contains {#contains-com.aspose.pdf.XmpPdfAExtensionObject-}
Bestämmer om obj finns i schemat.

### createDescriptionValueXml {#createDescriptionValueXml-com.aspose.ms.System.Xml.XmlDocument-}
Skapar beskrivningselementet xml för blocket med egenskapsvärden.

### createDescriptionXml {#createDescriptionXml-com.aspose.ms.System.Xml.XmlDocument-}
Skapar beskrivningselementet xml för alla scheman.

### createSchemasElement {#createSchemasElement-com.aspose.ms.System.Xml.XmlNode-}
Skapar listan med schemanelement från xml‑trädet.

### getDescription {#getDescription--}
```
public XmpPdfAExtensionSchemaDescription getDescription()
```

Hämtar schemabeskrivningen.

**Returns:**
XmpPdfAExtensionSchemaDescription

### getObjects1 {#getObjects1--}
```
public List getObjects1()
```

Hämtar listan med objekt (egenskaper, värdetyper).

**Returns:**
ArrayList

### getObjectsInternal {#getObjectsInternal--}
```
public com.aspose.ms.System.Collections.Generic.List< XmpPdfAExtensionObject > getObjectsInternal()
```

Hämtar listan med objekt (egenskaper, värdetyper).

**Returns:**
ArrayList

### getProperty {#getProperty-java.lang.String-}
Returnerar PDF/A‑egenskapen efter dess namn.

### getPropertyIndex {#getPropertyIndex-java.lang.String-}
Returnerar index för egenskapen med angivet namn.

### getSchemaXml {#getSchemaXml-com.aspose.ms.System.Xml.XmlDocument-}
Returnerar xml-elementet (tagg - li) som representerar schemat i xml-trädet.

### getValuesXml {#getValuesXml-com.aspose.ms.System.Xml.XmlDocument-com.aspose.ms.System.Xml.XmlElement-}
Hämtar värdena för egenskaperna som en xml-trädrepresentation.

### initializeSchemaValue {#initializeSchemaValue-com.aspose.ms.System.Xml.XmlNode-com.aspose.pdf.XmpPdfAExtensionSchema-}
Initierar värdet för egenskapen.

### isPdfAExtensionPrefix {#isPdfAExtensionPrefix-java.lang.String-}
Avgör om prefixvärdet är en del av pdf-a‑tillägget.

### remove {#remove-com.aspose.pdf.XmpPdfAExtensionObject-}
Tar bort objektet från schemat.
