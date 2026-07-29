---
title: "DocumentInfo"
linktitle: "DocumentInfo"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta le meta‑informazioni di un documento PDF."
type: docs
weight: 1160
url: /it/java/com.aspose.pdf/documentinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Collections.Generic.Dictionary< String , String > com.aspose.pdf.DocumentInfo, com.aspose.ms.System.Collections.Generic.Dictionary< String , String >, com.aspose.pdf.DocumentInfo

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, String >>, com.aspose.ms.System.Collections.Generic.IGenericDictionary< String, String >, com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, String >>, com.aspose.ms.System.Collections.IEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, String >>, Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String, String >>

```
public final class DocumentInfo extends com.aspose.ms.System.Collections.Generic.Dictionary< String , String >
```

Rappresenta le meta‑informazioni di un documento PDF.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [DocumentInfo](#DocumentInfo-com.aspose.pdf.IDocument-) | Inizializza l'istanza di DocumentInfo. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [addItem](#addItem-java.lang.String-java.lang.String-) | Aggiunge un elemento con la chiave e il valore specificati nella collezione. |
| [clear](#clear--) | Cancella le informazioni del documento. |
| [clearCustomData](#clearCustomData--) | Cancella solo i dati personalizzati, lasciando tutti gli altri valori predefiniti (Title, Author, ecc.). |
| [get_Item](#get_Item-java.lang.String-) | Ottiene il valore associato alla chiave specificata. |
| [getAuthor](#getAuthor--) | Ottiene l'autore del documento. |
| [getCreationDate](#getCreationDate--) | Ottiene la data di creazione del documento. |
| [getCreationTimeZone](#getCreationTimeZone--) | Fuso orario della data di creazione in millisecondi. |
| [getCreator](#getCreator--) | Ottiene il creatore del documento. |
| [getKeywords](#getKeywords--) | Ottiene le parole chiave del documento. |
| [getModDate](#getModDate--) | Ottiene la data di modifica del documento. |
| [getModTimeZone](#getModTimeZone--) | Fuso orario della data di modifica. |
| [getProducer](#getProducer--) | Ottiene il produttore del documento. |
| [getSubject](#getSubject--) | Ottiene l'oggetto del documento. |
| [getTitle](#getTitle--) | Ottiene il titolo del documento. |
| [getTrapped](#getTrapped--) | Ottiene il flag trapped. |
| [isPredefinedKey](#isPredefinedKey-java.lang.String-) | Determina se la chiave è predefinita (Title, Author, ecc.), non personalizzata. |
| [remove](#remove-java.lang.String-) | Rimuove l'elemento con la chiave specificata dalla collezione. |
| [set_Item](#set_Item-java.lang.String-java.lang.String-) | Imposta il valore associato alla chiave specificata. |
| [setAuthor](#setAuthor-java.lang.String-) | Imposta l'autore del documento. |
| [setCreationDate](#setCreationDate-java.util.Date-) | Imposta la data di creazione del documento. |
| [setCreationTimeZone](#setCreationTimeZone-double-) | Fuso orario della data di creazione in millisecondi. |
| [setCreator](#setCreator-java.lang.String-) | Imposta il creatore del documento. |
| [setKeywords](#setKeywords-java.lang.String-) | Imposta le parole chiave del documento. |
| [setModDate](#setModDate-java.util.Date-) | Imposta la data di modifica del documento. |
| [setModTimeZone](#setModTimeZone-double-) | Fuso orario della data di modifica. |
| [setProducer](#setProducer-java.lang.String-) | Imposta il produttore del documento. |
| [setSubject](#setSubject-java.lang.String-) | Imposta l'oggetto del documento. |
| [setTitle](#setTitle-java.lang.String-) | Imposta il titolo del documento. |
| [setTrapped](#setTrapped-java.lang.String-) | Imposta il flag di trappola. |

### DocumentInfo {#DocumentInfo-com.aspose.pdf.IDocument-}
Inizializza l'istanza di DocumentInfo.

### addItem {#addItem-java.lang.String-java.lang.String-}
Aggiunge un elemento con la chiave e il valore specificati nella collezione.

### clear {#clear--}
```
public void clear()
```

Cancella le informazioni del documento.

### clearCustomData {#clearCustomData--}
```
public void clearCustomData()
```

Cancella solo i dati personalizzati, lasciando tutti gli altri valori predefiniti (Title, Author, ecc.).

### get_Item {#get_Item-java.lang.String-}
Ottiene il valore associato alla chiave specificata.

### getAuthor {#getAuthor--}
```
public String getAuthor()
```

Ottiene l'autore del documento.

**Returns:**
valore String

### getCreationDate {#getCreationDate--}
```
public Date getCreationDate()
```

Ottiene la data di creazione del documento.

**Returns:**
Oggetto Date

### getCreationTimeZone {#getCreationTimeZone--}
```
public double getCreationTimeZone()
```

Fuso orario della data di creazione in millisecondi.

**Returns:**
valore double

### getCreator {#getCreator--}
```
public String getCreator()
```

Ottiene il creatore del documento.

**Returns:**
valore String

### getKeywords {#getKeywords--}
```
public String getKeywords()
```

Ottiene le parole chiave del documento.

**Returns:**
valore String

### getModDate {#getModDate--}
```
public Date getModDate()
```

Ottiene la data di modifica del documento.

**Returns:**
Oggetto Date

### getModTimeZone {#getModTimeZone--}
```
public double getModTimeZone()
```

Fuso orario della data di modifica.

**Returns:**
valore double

### getProducer {#getProducer--}
```
public String getProducer()
```

Ottiene il produttore del documento.

**Returns:**
valore String

### getSubject {#getSubject--}
```
public String getSubject()
```

Ottiene l'oggetto del documento.

**Returns:**
valore String

### getTitle {#getTitle--}
```
public String getTitle()
```

Ottiene il titolo del documento.

**Returns:**
valore String

### getTrapped {#getTrapped--}
```
public String getTrapped()
```

Ottiene il flag trapped.

**Returns:**
valore String

### isPredefinedKey {#isPredefinedKey-java.lang.String-}
Determina se la chiave è predefinita (Title, Author, ecc.), non personalizzata.

### remove {#remove-java.lang.String-}
Rimuove l'elemento con la chiave specificata dalla collezione.

### set_Item {#set_Item-java.lang.String-java.lang.String-}
Imposta il valore associato alla chiave specificata.

### setAuthor {#setAuthor-java.lang.String-}
Imposta l'autore del documento.

### setCreationDate {#setCreationDate-java.util.Date-}
Imposta la data di creazione del documento.

### setCreationTimeZone {#setCreationTimeZone-double-}
```
public void setCreationTimeZone(double value)
```

Fuso orario della data di creazione in millisecondi.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | in millisecondi |

### setCreator {#setCreator-java.lang.String-}
Imposta il creatore del documento.

### setKeywords {#setKeywords-java.lang.String-}
Imposta le parole chiave del documento.

### setModDate {#setModDate-java.util.Date-}
Imposta la data di modifica del documento.

### setModTimeZone {#setModTimeZone-double-}
```
public void setModTimeZone(double value)
```

Fuso orario della data di modifica.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### setProducer {#setProducer-java.lang.String-}
Imposta il produttore del documento.

### setSubject {#setSubject-java.lang.String-}
Imposta l'oggetto del documento.

### setTitle {#setTitle-java.lang.String-}
Imposta il titolo del documento.

### setTrapped {#setTrapped-java.lang.String-}
Imposta il flag di trappola.
