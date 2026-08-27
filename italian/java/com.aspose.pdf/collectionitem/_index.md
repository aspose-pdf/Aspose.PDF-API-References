---
title: "CollectionItem"
linktitle: "CollectionItem"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta una classe di elemento della raccolta. L'elemento della raccolta contiene i dati descritti dallo schema della raccolta."
type: docs
weight: 640
url: /it/java/com.aspose.pdf/collectionitem/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.CollectionItem

```
public class CollectionItem extends Object
```

Rappresenta una classe di elemento della raccolta. L'elemento della raccolta contiene i dati descritti dallo schema della raccolta.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getAllNames](#getAllNames--) | Ottiene una raccolta di tutti i nomi dei valori dell'elemento della collezione. |
| [hasName](#hasName-java.lang.String-) | Verifica se il nome fornito esiste nell'elemento della collezione. |
| [isEmpty](#isEmpty--) | Ottiene un valore che indica se l'elemento della collezione è vuoto. |
| [tryGetDateTimeValue](#tryGetDateTimeValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-) | Tenta di ottenere il valore di tipo DateTime dall'elemento della collezione tramite il nome specificato. |
| [tryGetDoubleValue](#tryGetDoubleValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-) | Tenta di ottenere il valore double per il nome specificato dall'elemento della collezione. |
| [tryGetIntValue](#tryGetIntValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-) | Tenta di ottenere il valore intero per un nome specificato dall'elemento della collezione. |
| [tryGetTextValue](#tryGetTextValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-) | Tenta di ottenere il valore di testo con il nome specificato dall'elemento della collezione. |

### getAllNames {#getAllNames--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getAllNames()
```

Ottiene una raccolta di tutti i nomi dei valori dell'elemento della collezione.

**Returns:**
lista di String

### hasName {#hasName-java.lang.String-}
Verifica se il nome fornito esiste nell'elemento della collezione.

### isEmpty {#isEmpty--}
```
public final boolean isEmpty()
```

Ottiene un valore che indica se l'elemento della collezione è vuoto.

**Returns:**
true se l'elemento della collezione è vuoto; altrimenti, false. Questa proprietà restituisce true se l'elemento della collezione non contiene alcun valore, inclusi valori stringa, valori double, valori interi e valori data. Se uno di questi tipi di valore è presente nell'elemento della collezione, questa proprietà restituisce false.

### tryGetDateTimeValue {#tryGetDateTimeValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-}
Tenta di ottenere il valore di tipo DateTime dall'elemento della collezione tramite il nome specificato.

### tryGetDoubleValue {#tryGetDoubleValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-}
Tenta di ottenere il valore double per il nome specificato dall'elemento della collezione.

### tryGetIntValue {#tryGetIntValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-}
Tenta di ottenere il valore intero per un nome specificato dall'elemento della collezione.

### tryGetTextValue {#tryGetTextValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-}
Tenta di ottenere il valore di testo con il nome specificato dall'elemento della collezione.
