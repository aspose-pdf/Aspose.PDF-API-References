---
title: "FileSpecification"
linktitle: "FileSpecification"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Klasse, die eine eingebettete Datei darstellt."
type: docs
weight: 1510
url: /de/java/com.aspose.pdf/filespecification/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FileSpecification

```
public final class FileSpecification extends Object
```

Klasse, die eine eingebettete Datei darstellt.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [FileSpecification](#FileSpecification--) | Erstellt eine neue leere Dateispezifikation. |
| [FileSpecification](#FileSpecification-java.io.InputStream-java.lang.String-) | Erstellt eine neue leere Dateispezifikation. |
| [FileSpecification](#FileSpecification-java.io.InputStream-java.lang.String-java.lang.String-) | Erstellt eine neue leere Dateispezifikation. |
| [FileSpecification](#FileSpecification-com.aspose.pdf.engine.data.IPdfPrimitive-) | Erstellt eine neue leere Dateispezifikation. |
| [FileSpecification](#FileSpecification-com.aspose.ms.System.IO.Stream-java.lang.String-) | Erstellt eine neue leere Dateispezifikation. |
| [FileSpecification](#FileSpecification-com.aspose.ms.System.IO.Stream-java.lang.String-java.lang.String-) | Erstellt eine neue leere Dateispezifikation. |
| [FileSpecification](#FileSpecification-java.lang.String-) | Erstellt eine neue leere Dateispezifikation. |
| [FileSpecification](#FileSpecification-java.lang.String-com.aspose.pdf.Annotation-) | Erstellt eine neue leere Dateispezifikation. |
| [FileSpecification](#FileSpecification-java.lang.String-java.lang.String-) | Erstellt eine neue leere Dateispezifikation. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getAFRelationship](#getAFRelationship--) | Zugehörige Datei‑Beziehung. |
| [getCollectionItem](#getCollectionItem--) | Gibt ein Sammlungs‑Element der Dateispezifikation zurück. |
| [getContents](#getContents--) | Gibt die Inhaltsdatei zurück. |
| [getContentsInternal](#getContentsInternal--) | Gibt die Inhaltsdatei zurück. |
| [getDescription](#getDescription--) | Ruft den Text ab, der mit der Dateispezifikation verknüpft ist. |
| [getEncoding](#getEncoding--) | Ruft das Kodierungsformat ab. Mögliche Werte: Zip – Datei ist mit ZIP komprimiert, None – Datei ist nicht komprimiert. |
| [getEncryptedPayload](#getEncryptedPayload--) | Ruft die verschlüsselte Nutzlast ab. |
| [getEngineDict](#getEngineDict--) | Pdf-Wörterbuch, das Informationen über die Datei enthält. Nur intern |
| [getEngineObj](#getEngineObj--) | Nur intern |
| [getFileSystem](#getFileSystem--) | Ruft den Namen des Dateisystems ab. |
| [getMIMEType](#getMIMEType--) | Ruft den Subtyp der eingebetteten Datei ab. |
| [getName](#getName--) | Ruft den Namen der Dateispezifikation ab. |
| [getParams](#getParams--) | Ruft die Dateiparameter ab. |
| [getStreamContents](#getStreamContents--) | Ruft den Inhalt der Datei als Stream ab. Der Inhalt wird nicht in den Speicher geladen, was die Speichernutzung reduziert. Dieser Stream unterstützt jedoch keine Positionsänderung und keine Length‑Eigenschaft. Wenn Sie diese Funktionen benötigen, verwenden Sie stattdessen die Contents‑Eigenschaft. |
| [getUnicodeName](#getUnicodeName--) | Ruft den Unicode‑Namen der Dateispezifikation ab. |
| [getValue](#getValue-java.lang.String-) | Ruft den anwendungsspezifischen Parameter ab. |
| [isIncludeContents](#isIncludeContents--) | Wenn true, wird der Inhalt der Datei in die Dateispezifikation aufgenommen. |
| [setAFRelationship](#setAFRelationship-com.aspose.pdf.AFRelationship-) | Zugehörige Datei‑Beziehung. |
| [setContents](#setContents-byte:A-) | Setzt den Dateiinhalt. |
| [setContents](#setContents-java.io.InputStream-) | Setzt den Dateiinhalt. |
| [setDescription](#setDescription-java.lang.String-) | Setzt den mit der Dateispezifikation verknüpften Text. |
| [setEncoding](#setEncoding-com.aspose.pdf.FileEncoding-) | Setzt das Kodierungsformat. Mögliche Werte: Zip – Datei ist mit ZIP komprimiert, None – Datei ist nicht komprimiert. |
| [setFileSystem](#setFileSystem-java.lang.String-) | Setzt den Namen des Dateisystems. |
| [setIncludeContents](#setIncludeContents-boolean-) | Wenn true, wird der Inhalt der Datei in die Dateispezifikation aufgenommen. |
| [setMIMEType](#setMIMEType-java.lang.String-) | Setzt den MIME‑Typ. |
| [setName](#setName-java.lang.String-) | Setzt den Namen der Dateispezifikation. |
| [setParams](#setParams-com.aspose.pdf.FileParams-) | Setzt die Dateiparameter. |
| [setUnicodeName](#setUnicodeName-java.lang.String-) | Setzt den Unicode‑Namen der Dateispezifikation. |
| [setValue](#setValue-java.lang.String-java.lang.String-) | Setzt den anwendungsspezifischen Parameter. |

### FileSpecification {#FileSpecification--}
```
public FileSpecification()
```

Erstellt eine neue leere Dateispezifikation.

### FileSpecification {#FileSpecification-java.io.InputStream-java.lang.String-}
Erstellt eine neue leere Dateispezifikation.

### FileSpecification {#FileSpecification-java.io.InputStream-java.lang.String-java.lang.String-}
Erstellt eine neue leere Dateispezifikation.

### FileSpecification {#FileSpecification-com.aspose.pdf.engine.data.IPdfPrimitive-}
Erstellt eine neue leere Dateispezifikation.

### FileSpecification {#FileSpecification-com.aspose.ms.System.IO.Stream-java.lang.String-}
Erstellt eine neue leere Dateispezifikation.

### FileSpecification {#FileSpecification-com.aspose.ms.System.IO.Stream-java.lang.String-java.lang.String-}
Erstellt eine neue leere Dateispezifikation.

### FileSpecification {#FileSpecification-java.lang.String-}
Erstellt eine neue leere Dateispezifikation.

### FileSpecification {#FileSpecification-java.lang.String-com.aspose.pdf.Annotation-}
Erstellt eine neue leere Dateispezifikation.

### FileSpecification {#FileSpecification-java.lang.String-java.lang.String-}
Erstellt eine neue leere Dateispezifikation.

### getAFRelationship {#getAFRelationship--}
```
public final AFRelationship getAFRelationship()
```

Zugehörige Datei‑Beziehung.

**Returns:**
AFRelationship‑Element

### getCollectionItem {#getCollectionItem--}
```
public final CollectionItem getCollectionItem()
```

Gibt ein Sammlungs‑Element der Dateispezifikation zurück.

**Returns:**
CollectionItem‑Instanz

### getContents {#getContents--}
```
public InputStream getContents()
```

Gibt die Inhaltsdatei zurück.

**Returns:**
InputStream‑Objekt

### getContentsInternal {#getContentsInternal--}
```
public com.aspose.ms.System.IO.Stream getContentsInternal()
```

Gibt die Inhaltsdatei zurück.

**Returns:**
Stream-Objekt

### getDescription {#getDescription--}
```
public String getDescription()
```

Ruft den Text ab, der mit der Dateispezifikation verknüpft ist.

**Returns:**
String Wert

### getEncoding {#getEncoding--}
```
public FileEncoding getEncoding()
```

Ruft das Kodierungsformat ab. Mögliche Werte: Zip – Datei ist mit ZIP komprimiert, None – Datei ist nicht komprimiert.

**Returns:**
int‑Wert @see FileEncoding

### getEncryptedPayload {#getEncryptedPayload--}
```
public final EncryptedPayload getEncryptedPayload()
```

Ruft die verschlüsselte Nutzlast ab.

**Returns:**
EncryptedPayload‑Instanz

### getEngineDict {#getEngineDict--}
```
public com.aspose.pdf.engine.data.IPdfDictionary getEngineDict()
```

Pdf-Wörterbuch, das Informationen über die Datei enthält. Nur intern

**Returns:**
IPdfDictionary-Objekt

### getEngineObj {#getEngineObj--}
```
public com.aspose.pdf.engine.data.IPdfObject getEngineObj()
```

Nur intern

**Returns:**
IPdfObject-Objekt

### getFileSystem {#getFileSystem--}
```
public String getFileSystem()
```

Ruft den Namen des Dateisystems ab.

**Returns:**
String Wert

### getMIMEType {#getMIMEType--}
```
public String getMIMEType()
```

Ruft den Subtyp der eingebetteten Datei ab.

**Returns:**
String-Wert

### getName {#getName--}
```
public String getName()
```

Ruft den Namen der Dateispezifikation ab.

**Returns:**
String Wert

### getParams {#getParams--}
```
public FileParams getParams()
```

Ruft die Dateiparameter ab.

**Returns:**
FileParams-Objekt

### getStreamContents {#getStreamContents--}
```
public InputStream getStreamContents()
```

Ruft den Inhalt der Datei als Stream ab. Der Inhalt wird nicht in den Speicher geladen, was die Speichernutzung reduziert. Dieser Stream unterstützt jedoch keine Positionsänderung und keine Length‑Eigenschaft. Wenn Sie diese Funktionen benötigen, verwenden Sie stattdessen die Contents‑Eigenschaft.

**Returns:**
InputStream‑Objekt

### getUnicodeName {#getUnicodeName--}
```
public String getUnicodeName()
```

Ruft den Unicode‑Namen der Dateispezifikation ab.

**Returns:**
String Wert

### getValue {#getValue-java.lang.String-}
Ruft den anwendungsspezifischen Parameter ab.

### isIncludeContents {#isIncludeContents--}
```
public boolean isIncludeContents()
```

Wenn true, wird der Inhalt der Datei in die Dateispezifikation aufgenommen.

**Returns:**
boolescher Wert

### setAFRelationship {#setAFRelationship-com.aspose.pdf.AFRelationship-}
Zugehörige Datei‑Beziehung.

### setContents {#setContents-byte:A-}
```
public void setContents(byte[] value)
```

Setzt den Dateiinhalt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | Array von Bytes |

### setContents {#setContents-java.io.InputStream-}
Setzt den Dateiinhalt.

### setDescription {#setDescription-java.lang.String-}
Setzt den mit der Dateispezifikation verknüpften Text.

### setEncoding {#setEncoding-com.aspose.pdf.FileEncoding-}
Setzt das Kodierungsformat. Mögliche Werte: Zip – Datei ist mit ZIP komprimiert, None – Datei ist nicht komprimiert.

### setFileSystem {#setFileSystem-java.lang.String-}
Setzt den Namen des Dateisystems.

### setIncludeContents {#setIncludeContents-boolean-}
```
public void setIncludeContents(boolean value)
```

Wenn true, wird der Inhalt der Datei in die Dateispezifikation aufgenommen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setMIMEType {#setMIMEType-java.lang.String-}
Setzt den MIME‑Typ.

### setName {#setName-java.lang.String-}
Setzt den Namen der Dateispezifikation.

### setParams {#setParams-com.aspose.pdf.FileParams-}
Setzt die Dateiparameter.

### setUnicodeName {#setUnicodeName-java.lang.String-}
Setzt den Unicode‑Namen der Dateispezifikation.

### setValue {#setValue-java.lang.String-java.lang.String-}
Setzt den anwendungsspezifischen Parameter.
