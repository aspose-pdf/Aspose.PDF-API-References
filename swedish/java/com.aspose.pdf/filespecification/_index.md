---
title: "FileSpecification"
linktitle: "FileSpecification"
second_title: "Aspose.PDF för Java API-referens"
description: "Klass som representerar en inbäddad fil."
type: docs
weight: 1510
url: /sv/java/com.aspose.pdf/filespecification/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FileSpecification

```
public final class FileSpecification extends Object
```

Klass som representerar en inbäddad fil.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [FileSpecification](#FileSpecification--) | Skapa en ny tom filspecifikation. |
| [FileSpecification](#FileSpecification-java.io.InputStream-java.lang.String-) | Skapa en ny tom filspecifikation. |
| [FileSpecification](#FileSpecification-java.io.InputStream-java.lang.String-java.lang.String-) | Skapa en ny tom filspecifikation. |
| [FileSpecification](#FileSpecification-com.aspose.pdf.engine.data.IPdfPrimitive-) | Skapa en ny tom filspecifikation. |
| [FileSpecification](#FileSpecification-com.aspose.ms.System.IO.Stream-java.lang.String-) | Skapa en ny tom filspecifikation. |
| [FileSpecification](#FileSpecification-com.aspose.ms.System.IO.Stream-java.lang.String-java.lang.String-) | Skapa en ny tom filspecifikation. |
| [FileSpecification](#FileSpecification-java.lang.String-) | Skapa en ny tom filspecifikation. |
| [FileSpecification](#FileSpecification-java.lang.String-com.aspose.pdf.Annotation-) | Skapa en ny tom filspecifikation. |
| [FileSpecification](#FileSpecification-java.lang.String-java.lang.String-) | Skapa en ny tom filspecifikation. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getAFRelationship](#getAFRelationship--) | Associerad filrelation. |
| [getCollectionItem](#getCollectionItem--) | Hämtar ett samlingsobjekt av filspecifikationen. |
| [getContents](#getContents--) | Hämtar innehållsfil. |
| [getContentsInternal](#getContentsInternal--) | Hämtar innehållsfil. |
| [getDescription](#getDescription--) | Hämtar text som är associerad med filspecifikationen. |
| [getEncoding](#getEncoding--) | Hämtar kodningsformat. Möjliga värden: Zip – filen är komprimerad med ZIP, None – filen är inte komprimerad. |
| [getEncryptedPayload](#getEncryptedPayload--) | Hämtar krypterad nyttolast. |
| [getEngineDict](#getEngineDict--) | Pdf-ordbok som innehåller information om filen. Endast intern. |
| [getEngineObj](#getEngineObj--) | Endast intern |
| [getFileSystem](#getFileSystem--) | Hämtar namn på filsystemet. |
| [getMIMEType](#getMIMEType--) | Hämtar undertypen för den inbäddade filen |
| [getName](#getName--) | Hämtar filspecifikationsnamnet. |
| [getParams](#getParams--) | Hämtar filparametrar. |
| [getStreamContents](#getStreamContents--) | Hämtar innehållet i filen som en ström. Innehållet laddas inte in i minnet, vilket möjliggör minskad minnesanvändning. Men denna ström stöder inte positionering och Length‑egenskapen. Om du behöver dessa funktioner, använd egenskapen Contents istället. |
| [getUnicodeName](#getUnicodeName--) | Hämtar filspecifikationens Unicode‑namn. |
| [getValue](#getValue-java.lang.String-) | Hämtar programspecifik parameter. |
| [isIncludeContents](#isIncludeContents--) | Om true, inkluderas filens innehåll i filspecifikationen. |
| [setAFRelationship](#setAFRelationship-com.aspose.pdf.AFRelationship-) | Associerad filrelation. |
| [setContents](#setContents-byte:A-) | Ställer in innehållsfilen. |
| [setContents](#setContents-java.io.InputStream-) | Ställer in innehållsfilen. |
| [setDescription](#setDescription-java.lang.String-) | Ställer in text som är associerad med filspecifikationen. |
| [setEncoding](#setEncoding-com.aspose.pdf.FileEncoding-) | Ställer in kodningsformat. Möjliga värden: Zip – filen är komprimerad med ZIP, None – filen är inte komprimerad. |
| [setFileSystem](#setFileSystem-java.lang.String-) | Ställer in namn på filsystemet. |
| [setIncludeContents](#setIncludeContents-boolean-) | Om true, inkluderas filens innehåll i filspecifikationen. |
| [setMIMEType](#setMIMEType-java.lang.String-) | Ställer in MIME‑typ. |
| [setName](#setName-java.lang.String-) | Ställer in filspecifikationsnamn. |
| [setParams](#setParams-com.aspose.pdf.FileParams-) | Ställer in filparametrar. |
| [setUnicodeName](#setUnicodeName-java.lang.String-) | Ställer in filspecifikationens Unicode‑namn. |
| [setValue](#setValue-java.lang.String-java.lang.String-) | Ställer in programspecifik parameter. |

### FileSpecification {#FileSpecification--}
```
public FileSpecification()
```

Skapa en ny tom filspecifikation.

### FileSpecification {#FileSpecification-java.io.InputStream-java.lang.String-}
Skapa en ny tom filspecifikation.

### FileSpecification {#FileSpecification-java.io.InputStream-java.lang.String-java.lang.String-}
Skapa en ny tom filspecifikation.

### FileSpecification {#FileSpecification-com.aspose.pdf.engine.data.IPdfPrimitive-}
Skapa en ny tom filspecifikation.

### FileSpecification {#FileSpecification-com.aspose.ms.System.IO.Stream-java.lang.String-}
Skapa en ny tom filspecifikation.

### FileSpecification {#FileSpecification-com.aspose.ms.System.IO.Stream-java.lang.String-java.lang.String-}
Skapa en ny tom filspecifikation.

### FileSpecification {#FileSpecification-java.lang.String-}
Skapa en ny tom filspecifikation.

### FileSpecification {#FileSpecification-java.lang.String-com.aspose.pdf.Annotation-}
Skapa en ny tom filspecifikation.

### FileSpecification {#FileSpecification-java.lang.String-java.lang.String-}
Skapa en ny tom filspecifikation.

### getAFRelationship {#getAFRelationship--}
```
public final AFRelationship getAFRelationship()
```

Associerad filrelation.

**Returns:**
AFRelationship‑element

### getCollectionItem {#getCollectionItem--}
```
public final CollectionItem getCollectionItem()
```

Hämtar ett samlingsobjekt av filspecifikationen.

**Returns:**
CollectionItem‑instans

### getContents {#getContents--}
```
public InputStream getContents()
```

Hämtar innehållsfil.

**Returns:**
InputStream-objekt

### getContentsInternal {#getContentsInternal--}
```
public com.aspose.ms.System.IO.Stream getContentsInternal()
```

Hämtar innehållsfil.

**Returns:**
Strömobjekt

### getDescription {#getDescription--}
```
public String getDescription()
```

Hämtar text som är associerad med filspecifikationen.

**Returns:**
String värde

### getEncoding {#getEncoding--}
```
public FileEncoding getEncoding()
```

Hämtar kodningsformat. Möjliga värden: Zip – filen är komprimerad med ZIP, None – filen är inte komprimerad.

**Returns:**
int‑värde @see FileEncoding

### getEncryptedPayload {#getEncryptedPayload--}
```
public final EncryptedPayload getEncryptedPayload()
```

Hämtar krypterad nyttolast.

**Returns:**
EncryptedPayload‑instans

### getEngineDict {#getEngineDict--}
```
public com.aspose.pdf.engine.data.IPdfDictionary getEngineDict()
```

Pdf-ordbok som innehåller information om filen. Endast intern.

**Returns:**
IPdfDictionary‑objekt

### getEngineObj {#getEngineObj--}
```
public com.aspose.pdf.engine.data.IPdfObject getEngineObj()
```

Endast intern

**Returns:**
IPdfObject‑objekt

### getFileSystem {#getFileSystem--}
```
public String getFileSystem()
```

Hämtar namn på filsystemet.

**Returns:**
String värde

### getMIMEType {#getMIMEType--}
```
public String getMIMEType()
```

Hämtar undertypen för den inbäddade filen

**Returns:**
strängvärde

### getName {#getName--}
```
public String getName()
```

Hämtar filspecifikationsnamnet.

**Returns:**
String värde

### getParams {#getParams--}
```
public FileParams getParams()
```

Hämtar filparametrar.

**Returns:**
FileParams‑objekt

### getStreamContents {#getStreamContents--}
```
public InputStream getStreamContents()
```

Hämtar innehållet i filen som en ström. Innehållet laddas inte in i minnet, vilket möjliggör minskad minnesanvändning. Men denna ström stöder inte positionering och Length‑egenskapen. Om du behöver dessa funktioner, använd egenskapen Contents istället.

**Returns:**
InputStream-objekt

### getUnicodeName {#getUnicodeName--}
```
public String getUnicodeName()
```

Hämtar filspecifikationens Unicode‑namn.

**Returns:**
String värde

### getValue {#getValue-java.lang.String-}
Hämtar programspecifik parameter.

### isIncludeContents {#isIncludeContents--}
```
public boolean isIncludeContents()
```

Om true, inkluderas filens innehåll i filspecifikationen.

**Returns:**
booleskt värde

### setAFRelationship {#setAFRelationship-com.aspose.pdf.AFRelationship-}
Associerad filrelation.

### setContents {#setContents-byte:A-}
```
public void setContents(byte[] value)
```

Ställer in innehållsfilen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | byte‑array |

### setContents {#setContents-java.io.InputStream-}
Ställer in innehållsfilen.

### setDescription {#setDescription-java.lang.String-}
Ställer in text som är associerad med filspecifikationen.

### setEncoding {#setEncoding-com.aspose.pdf.FileEncoding-}
Ställer in kodningsformat. Möjliga värden: Zip – filen är komprimerad med ZIP, None – filen är inte komprimerad.

### setFileSystem {#setFileSystem-java.lang.String-}
Ställer in namn på filsystemet.

### setIncludeContents {#setIncludeContents-boolean-}
```
public void setIncludeContents(boolean value)
```

Om true, inkluderas filens innehåll i filspecifikationen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setMIMEType {#setMIMEType-java.lang.String-}
Ställer in MIME‑typ.

### setName {#setName-java.lang.String-}
Ställer in filspecifikationsnamn.

### setParams {#setParams-com.aspose.pdf.FileParams-}
Ställer in filparametrar.

### setUnicodeName {#setUnicodeName-java.lang.String-}
Ställer in filspecifikationens Unicode‑namn.

### setValue {#setValue-java.lang.String-java.lang.String-}
Ställer in programspecifik parameter.
