---
title: "FileSpecification"
linktitle: "FileSpecification"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Classe che rappresenta un file incorporato."
type: docs
weight: 1510
url: /it/java/com.aspose.pdf/filespecification/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FileSpecification

```
public final class FileSpecification extends Object
```

Classe che rappresenta un file incorporato.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [FileSpecification](#FileSpecification--) | Crea una nuova specifica di file vuota. |
| [FileSpecification](#FileSpecification-java.io.InputStream-java.lang.String-) | Crea una nuova specifica di file vuota. |
| [FileSpecification](#FileSpecification-java.io.InputStream-java.lang.String-java.lang.String-) | Crea una nuova specifica di file vuota. |
| [FileSpecification](#FileSpecification-com.aspose.pdf.engine.data.IPdfPrimitive-) | Crea una nuova specifica di file vuota. |
| [FileSpecification](#FileSpecification-com.aspose.ms.System.IO.Stream-java.lang.String-) | Crea una nuova specifica di file vuota. |
| [FileSpecification](#FileSpecification-com.aspose.ms.System.IO.Stream-java.lang.String-java.lang.String-) | Crea una nuova specifica di file vuota. |
| [FileSpecification](#FileSpecification-java.lang.String-) | Crea una nuova specifica di file vuota. |
| [FileSpecification](#FileSpecification-java.lang.String-com.aspose.pdf.Annotation-) | Crea una nuova specifica di file vuota. |
| [FileSpecification](#FileSpecification-java.lang.String-java.lang.String-) | Crea una nuova specifica di file vuota. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getAFRelationship](#getAFRelationship--) | Relazione del file associato. |
| [getCollectionItem](#getCollectionItem--) | Restituisce un elemento della collezione della specifica di file. |
| [getContents](#getContents--) | Restituisce il file di contenuti. |
| [getContentsInternal](#getContentsInternal--) | Restituisce il file di contenuti. |
| [getDescription](#getDescription--) | Ottiene il testo associato alla specifica del file. |
| [getEncoding](#getEncoding--) | Ottiene il formato di codifica. Valori possibili: Zip - il file è compresso con ZIP, None - il file non è compresso. |
| [getEncryptedPayload](#getEncryptedPayload--) | Ottiene il payload crittografato. |
| [getEngineDict](#getEngineDict--) | Dizionario PDF contenente informazioni sul file. Solo interno |
| [getEngineObj](#getEngineObj--) | Solo interno |
| [getFileSystem](#getFileSystem--) | Ottiene il nome del file system. |
| [getMIMEType](#getMIMEType--) | Ottiene il sottotipo del file incorporato |
| [getName](#getName--) | Ottiene il nome della specifica del file. |
| [getParams](#getParams--) | Ottiene i parametri del file. |
| [getStreamContents](#getStreamContents--) | Ottiene il contenuto del file come stream. Il contenuto non viene caricato in memoria, il che consente di ridurre l'utilizzo della memoria. Tuttavia questo stream non supporta il posizionamento e la proprietà Length. Se hai bisogno di queste funzionalità, utilizza invece la proprietà Contents. |
| [getUnicodeName](#getUnicodeName--) | Ottiene il nome Unicode della specifica del file. |
| [getValue](#getValue-java.lang.String-) | Ottiene il parametro specifico dell'applicazione. |
| [isIncludeContents](#isIncludeContents--) | Se vero, il contenuto del file sarà incluso nella specifica del file. |
| [setAFRelationship](#setAFRelationship-com.aspose.pdf.AFRelationship-) | Relazione del file associato. |
| [setContents](#setContents-byte:A-) | Imposta il contenuto del file. |
| [setContents](#setContents-java.io.InputStream-) | Imposta il contenuto del file. |
| [setDescription](#setDescription-java.lang.String-) | Imposta il testo associato alla specifica del file. |
| [setEncoding](#setEncoding-com.aspose.pdf.FileEncoding-) | Imposta il formato di codifica. Valori possibili: Zip - il file è compresso con ZIP, None - il file non è compresso. |
| [setFileSystem](#setFileSystem-java.lang.String-) | Imposta il nome del file system. |
| [setIncludeContents](#setIncludeContents-boolean-) | Se vero, il contenuto del file sarà incluso nella specifica del file. |
| [setMIMEType](#setMIMEType-java.lang.String-) | Imposta il MIMEType. |
| [setName](#setName-java.lang.String-) | Imposta il nome della specifica del file. |
| [setParams](#setParams-com.aspose.pdf.FileParams-) | Imposta i parametri del file. |
| [setUnicodeName](#setUnicodeName-java.lang.String-) | Imposta il nome Unicode della specifica del file. |
| [setValue](#setValue-java.lang.String-java.lang.String-) | Imposta il parametro specifico dell'applicazione. |

### FileSpecification {#FileSpecification--}
```
public FileSpecification()
```

Crea una nuova specifica di file vuota.

### FileSpecification {#FileSpecification-java.io.InputStream-java.lang.String-}
Crea una nuova specifica di file vuota.

### FileSpecification {#FileSpecification-java.io.InputStream-java.lang.String-java.lang.String-}
Crea una nuova specifica di file vuota.

### FileSpecification {#FileSpecification-com.aspose.pdf.engine.data.IPdfPrimitive-}
Crea una nuova specifica di file vuota.

### FileSpecification {#FileSpecification-com.aspose.ms.System.IO.Stream-java.lang.String-}
Crea una nuova specifica di file vuota.

### FileSpecification {#FileSpecification-com.aspose.ms.System.IO.Stream-java.lang.String-java.lang.String-}
Crea una nuova specifica di file vuota.

### FileSpecification {#FileSpecification-java.lang.String-}
Crea una nuova specifica di file vuota.

### FileSpecification {#FileSpecification-java.lang.String-com.aspose.pdf.Annotation-}
Crea una nuova specifica di file vuota.

### FileSpecification {#FileSpecification-java.lang.String-java.lang.String-}
Crea una nuova specifica di file vuota.

### getAFRelationship {#getAFRelationship--}
```
public final AFRelationship getAFRelationship()
```

Relazione del file associato.

**Returns:**
Elemento AFRelationship

### getCollectionItem {#getCollectionItem--}
```
public final CollectionItem getCollectionItem()
```

Restituisce un elemento della collezione della specifica di file.

**Returns:**
Istanza CollectionItem

### getContents {#getContents--}
```
public InputStream getContents()
```

Restituisce il file di contenuti.

**Returns:**
Oggetto InputStream

### getContentsInternal {#getContentsInternal--}
```
public com.aspose.ms.System.IO.Stream getContentsInternal()
```

Restituisce il file di contenuti.

**Returns:**
oggetto Stream

### getDescription {#getDescription--}
```
public String getDescription()
```

Ottiene il testo associato alla specifica del file.

**Returns:**
valore String

### getEncoding {#getEncoding--}
```
public FileEncoding getEncoding()
```

Ottiene il formato di codifica. Valori possibili: Zip - il file è compresso con ZIP, None - il file non è compresso.

**Returns:**
valore int @see FileEncoding

### getEncryptedPayload {#getEncryptedPayload--}
```
public final EncryptedPayload getEncryptedPayload()
```

Ottiene il payload crittografato.

**Returns:**
Istanza EncryptedPayload

### getEngineDict {#getEngineDict--}
```
public com.aspose.pdf.engine.data.IPdfDictionary getEngineDict()
```

Dizionario PDF contenente informazioni sul file. Solo interno

**Returns:**
oggetto IPdfDictionary

### getEngineObj {#getEngineObj--}
```
public com.aspose.pdf.engine.data.IPdfObject getEngineObj()
```

Solo interno

**Returns:**
Oggetto IPdfObject

### getFileSystem {#getFileSystem--}
```
public String getFileSystem()
```

Ottiene il nome del file system.

**Returns:**
valore String

### getMIMEType {#getMIMEType--}
```
public String getMIMEType()
```

Ottiene il sottotipo del file incorporato

**Returns:**
valore stringa

### getName {#getName--}
```
public String getName()
```

Ottiene il nome della specifica del file.

**Returns:**
valore String

### getParams {#getParams--}
```
public FileParams getParams()
```

Ottiene i parametri del file.

**Returns:**
oggetto FileParams

### getStreamContents {#getStreamContents--}
```
public InputStream getStreamContents()
```

Ottiene il contenuto del file come stream. Il contenuto non viene caricato in memoria, il che consente di ridurre l'utilizzo della memoria. Tuttavia questo stream non supporta il posizionamento e la proprietà Length. Se hai bisogno di queste funzionalità, utilizza invece la proprietà Contents.

**Returns:**
Oggetto InputStream

### getUnicodeName {#getUnicodeName--}
```
public String getUnicodeName()
```

Ottiene il nome Unicode della specifica del file.

**Returns:**
valore String

### getValue {#getValue-java.lang.String-}
Ottiene il parametro specifico dell'applicazione.

### isIncludeContents {#isIncludeContents--}
```
public boolean isIncludeContents()
```

Se vero, il contenuto del file sarà incluso nella specifica del file.

**Returns:**
valore booleano

### setAFRelationship {#setAFRelationship-com.aspose.pdf.AFRelationship-}
Relazione del file associato.

### setContents {#setContents-byte:A-}
```
public void setContents(byte[] value)
```

Imposta il contenuto del file.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | array di byte |

### setContents {#setContents-java.io.InputStream-}
Imposta il contenuto del file.

### setDescription {#setDescription-java.lang.String-}
Imposta il testo associato alla specifica del file.

### setEncoding {#setEncoding-com.aspose.pdf.FileEncoding-}
Imposta il formato di codifica. Valori possibili: Zip - il file è compresso con ZIP, None - il file non è compresso.

### setFileSystem {#setFileSystem-java.lang.String-}
Imposta il nome del file system.

### setIncludeContents {#setIncludeContents-boolean-}
```
public void setIncludeContents(boolean value)
```

Se vero, il contenuto del file sarà incluso nella specifica del file.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setMIMEType {#setMIMEType-java.lang.String-}
Imposta il MIMEType.

### setName {#setName-java.lang.String-}
Imposta il nome della specifica del file.

### setParams {#setParams-com.aspose.pdf.FileParams-}
Imposta i parametri del file.

### setUnicodeName {#setUnicodeName-java.lang.String-}
Imposta il nome Unicode della specifica del file.

### setValue {#setValue-java.lang.String-java.lang.String-}
Imposta il parametro specifico dell'applicazione.
