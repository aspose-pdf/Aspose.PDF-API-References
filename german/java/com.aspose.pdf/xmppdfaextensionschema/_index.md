---
title: "XmpPdfAExtensionSchema"
linktitle: "XmpPdfAExtensionSchema"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Beschreibt das XMP-Erweiterungsschema, das von PDF/A-1 bereitgestellt wird."
type: docs
weight: 5720
url: /de/java/com.aspose.pdf/xmppdfaextensionschema/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XmpPdfAExtensionSchema

```
public class XmpPdfAExtensionSchema extends Object
```

Beschreibt das XMP-Erweiterungsschema, das von PDF/A-1 bereitgestellt wird.

## Felder

| Feld | Beschreibung |
| --- | --- |
| [DEFAULT_EXTENSION_NAMESPACE_PREFIX](#DEFAULT_EXTENSION_NAMESPACE_PREFIX) | Standard‑Erweiterungs‑Namespace‑Präfix. |
| [DEFAULT_EXTENSION_NAMESPACE_URI](#DEFAULT_EXTENSION_NAMESPACE_URI) | Standard‑Erweiterungs‑Namespace‑URI. |
| [DEFAULT_FIELD_NAMESPACE_PREFIX](#DEFAULT_FIELD_NAMESPACE_PREFIX) | Standard‑Feld‑Namespace‑Präfix. |
| [DEFAULT_FIELD_NAMESPACE_URI](#DEFAULT_FIELD_NAMESPACE_URI) | Standard‑Erweiterungs‑Namespace‑URI. |
| [DEFAULT_PROPERTY_NAMESPACE_PREFIX](#DEFAULT_PROPERTY_NAMESPACE_PREFIX) | Standard‑Eigenschafts‑Namespace‑Präfix. |
| [DEFAULT_PROPERTY_NAMESPACE_URI](#DEFAULT_PROPERTY_NAMESPACE_URI) | Standard‑Eigenschafts‑Namespace‑URI. |
| [DEFAULT_SCHEMA_NAMESPACE_PREFIX](#DEFAULT_SCHEMA_NAMESPACE_PREFIX) | Standard‑Schema‑Namespace‑Präfix. |
| [DEFAULT_SCHEMA_NAMESPACE_URI](#DEFAULT_SCHEMA_NAMESPACE_URI) | Standard‑Schema‑Namensraum‑URI. |
| [DEFAULT_VALUE_NAMESPACE_URI](#DEFAULT_VALUE_NAMESPACE_URI) | Standard‑Wert‑Namensraum‑URI. |
| [DEFAULT_VALUE_TYPE_NAMESPACE_PREFIX](#DEFAULT_VALUE_TYPE_NAMESPACE_PREFIX) | Standard‑Typ‑Namensraum‑Präfix. |
| [RDF_NAMESPACE_URI](#RDF_NAMESPACE_URI) | Standard‑RDF‑Namensraum‑URI. |
| [RDF_PREFIX](#RDF_PREFIX) | Standard‑RDF‑Namensraum‑Präfix. |
| [XMLNS](#XMLNS) |  |

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [XmpPdfAExtensionSchema](#XmpPdfAExtensionSchema-com.aspose.pdf.XmpPdfAExtensionSchemaDescription-) | Initialisiert ein neues Objekt. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [add](#add-com.aspose.pdf.XmpPdfAExtensionObject-) | Fügt ein neues Objekt in das Schema ein. |
| [contains](#contains-com.aspose.pdf.XmpPdfAExtensionObject-) | Bestimmt, ob das Objekt im Schema existiert. |
| [createDescriptionValueXml](#createDescriptionValueXml-com.aspose.ms.System.Xml.XmlDocument-) | Erstellt das Beschreibungs‑XML‑Element für den Block der Eigenschaftswerte. |
| [createDescriptionXml](#createDescriptionXml-com.aspose.ms.System.Xml.XmlDocument-) | Erstellt das Beschreibungs‑XML‑Element für alle Schemas. |
| [createSchemasElement](#createSchemasElement-com.aspose.ms.System.Xml.XmlNode-) | Erstellt die Liste der Schema‑Elemente aus dem XML‑Baum. |
| [getDescription](#getDescription--) | Liefert die Schema‑Beschreibung. |
| [getObjects1](#getObjects1--) | Liefert die Liste der Objekte (Eigenschaften, Werttypen). |
| [getObjectsInternal](#getObjectsInternal--) | Liefert die Liste der Objekte (Eigenschaften, Werttypen). |
| [getProperty](#getProperty-java.lang.String-) | Gibt die PDF/A‑Eigenschaft anhand ihres Namens zurück. |
| [getPropertyIndex](#getPropertyIndex-java.lang.String-) | Gibt den Index der Eigenschaft mit dem angegebenen Namen zurück. |
| [getSchemaXml](#getSchemaXml-com.aspose.ms.System.Xml.XmlDocument-) | Gibt das XML‑Element (Tag – li) zurück, das das Schema im XML‑Baum darstellt. |
| [getValuesXml](#getValuesXml-com.aspose.ms.System.Xml.XmlDocument-com.aspose.ms.System.Xml.XmlElement-) | Liefert die Werte der Eigenschaften als XML‑Baumdarstellung. |
| [initializeSchemaValue](#initializeSchemaValue-com.aspose.ms.System.Xml.XmlNode-com.aspose.pdf.XmpPdfAExtensionSchema-) | Initialisiert den Wert der Eigenschaft. |
| [isPdfAExtensionPrefix](#isPdfAExtensionPrefix-java.lang.String-) | Bestimmt, ob der Präfixwert Teil der PDF‑A‑Erweiterung ist. |
| [remove](#remove-com.aspose.pdf.XmpPdfAExtensionObject-) | Entfernt das Objekt aus dem Schema. |

### DEFAULT_EXTENSION_NAMESPACE_PREFIX {#DEFAULT_EXTENSION_NAMESPACE_PREFIX}
```
public static final String DEFAULT_EXTENSION_NAMESPACE_PREFIX
```

Standard‑Erweiterungs‑Namespace‑Präfix.

### DEFAULT_EXTENSION_NAMESPACE_URI {#DEFAULT_EXTENSION_NAMESPACE_URI}
```
public static final String DEFAULT_EXTENSION_NAMESPACE_URI
```

Standard‑Erweiterungs‑Namespace‑URI.

### DEFAULT_FIELD_NAMESPACE_PREFIX {#DEFAULT_FIELD_NAMESPACE_PREFIX}
```
public static final String DEFAULT_FIELD_NAMESPACE_PREFIX
```

Standard‑Feld‑Namespace‑Präfix.

### DEFAULT_FIELD_NAMESPACE_URI {#DEFAULT_FIELD_NAMESPACE_URI}
```
public static final String DEFAULT_FIELD_NAMESPACE_URI
```

Standard‑Erweiterungs‑Namespace‑URI.

### DEFAULT_PROPERTY_NAMESPACE_PREFIX {#DEFAULT_PROPERTY_NAMESPACE_PREFIX}
```
public static final String DEFAULT_PROPERTY_NAMESPACE_PREFIX
```

Standard‑Eigenschafts‑Namespace‑Präfix.

### DEFAULT_PROPERTY_NAMESPACE_URI {#DEFAULT_PROPERTY_NAMESPACE_URI}
```
public static final String DEFAULT_PROPERTY_NAMESPACE_URI
```

Standard‑Eigenschafts‑Namespace‑URI.

### DEFAULT_SCHEMA_NAMESPACE_PREFIX {#DEFAULT_SCHEMA_NAMESPACE_PREFIX}
```
public static final String DEFAULT_SCHEMA_NAMESPACE_PREFIX
```

Standard‑Schema‑Namespace‑Präfix.

### DEFAULT_SCHEMA_NAMESPACE_URI {#DEFAULT_SCHEMA_NAMESPACE_URI}
```
public static final String DEFAULT_SCHEMA_NAMESPACE_URI
```

Standard‑Schema‑Namensraum‑URI.

### DEFAULT_VALUE_NAMESPACE_URI {#DEFAULT_VALUE_NAMESPACE_URI}
```
public static final String DEFAULT_VALUE_NAMESPACE_URI
```

Standard‑Wert‑Namensraum‑URI.

### DEFAULT_VALUE_TYPE_NAMESPACE_PREFIX {#DEFAULT_VALUE_TYPE_NAMESPACE_PREFIX}
```
public static final String DEFAULT_VALUE_TYPE_NAMESPACE_PREFIX
```

Standard‑Typ‑Namensraum‑Präfix.

### RDF_NAMESPACE_URI {#RDF_NAMESPACE_URI}
```
public static final String RDF_NAMESPACE_URI
```

Standard‑RDF‑Namensraum‑URI.

### RDF_PREFIX {#RDF_PREFIX}
```
public static final String RDF_PREFIX
```

Standard‑RDF‑Namensraum‑Präfix.

### XMLNS {#XMLNS}
```
public static final String XMLNS
```



### XmpPdfAExtensionSchema {#XmpPdfAExtensionSchema-com.aspose.pdf.XmpPdfAExtensionSchemaDescription-}
Initialisiert ein neues Objekt.

### add {#add-com.aspose.pdf.XmpPdfAExtensionObject-}
Fügt ein neues Objekt in das Schema ein.

### contains {#contains-com.aspose.pdf.XmpPdfAExtensionObject-}
Bestimmt, ob das Objekt im Schema existiert.

### createDescriptionValueXml {#createDescriptionValueXml-com.aspose.ms.System.Xml.XmlDocument-}
Erstellt das Beschreibungs‑XML‑Element für den Block der Eigenschaftswerte.

### createDescriptionXml {#createDescriptionXml-com.aspose.ms.System.Xml.XmlDocument-}
Erstellt das Beschreibungs‑XML‑Element für alle Schemas.

### createSchemasElement {#createSchemasElement-com.aspose.ms.System.Xml.XmlNode-}
Erstellt die Liste der Schema‑Elemente aus dem XML‑Baum.

### getDescription {#getDescription--}
```
public XmpPdfAExtensionSchemaDescription getDescription()
```

Liefert die Schema‑Beschreibung.

**Returns:**
XmpPdfAExtensionSchemaDescription

### getObjects1 {#getObjects1--}
```
public List getObjects1()
```

Liefert die Liste der Objekte (Eigenschaften, Werttypen).

**Returns:**
ArrayList

### getObjectsInternal {#getObjectsInternal--}
```
public com.aspose.ms.System.Collections.Generic.List< XmpPdfAExtensionObject > getObjectsInternal()
```

Liefert die Liste der Objekte (Eigenschaften, Werttypen).

**Returns:**
ArrayList

### getProperty {#getProperty-java.lang.String-}
Gibt die PDF/A‑Eigenschaft anhand ihres Namens zurück.

### getPropertyIndex {#getPropertyIndex-java.lang.String-}
Gibt den Index der Eigenschaft mit dem angegebenen Namen zurück.

### getSchemaXml {#getSchemaXml-com.aspose.ms.System.Xml.XmlDocument-}
Gibt das XML‑Element (Tag – li) zurück, das das Schema im XML‑Baum darstellt.

### getValuesXml {#getValuesXml-com.aspose.ms.System.Xml.XmlDocument-com.aspose.ms.System.Xml.XmlElement-}
Liefert die Werte der Eigenschaften als XML‑Baumdarstellung.

### initializeSchemaValue {#initializeSchemaValue-com.aspose.ms.System.Xml.XmlNode-com.aspose.pdf.XmpPdfAExtensionSchema-}
Initialisiert den Wert der Eigenschaft.

### isPdfAExtensionPrefix {#isPdfAExtensionPrefix-java.lang.String-}
Bestimmt, ob der Präfixwert Teil der PDF‑A‑Erweiterung ist.

### remove {#remove-com.aspose.pdf.XmpPdfAExtensionObject-}
Entfernt das Objekt aus dem Schema.
