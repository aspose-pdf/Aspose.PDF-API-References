---
title: "SignatureName"
linktitle: "SignatureName"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta una classe per un nome di firma. Rappresenta un nome di firma più preciso. Utilizzato al posto dei nomi stringa. Consente di presentare firme con gli stessi nomi stringa."
type: docs
weight: 690
url: /it/java/com.aspose.pdf.facades/signaturename/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.SignatureName

```
public final class SignatureName extends Object
```

Rappresenta una classe per un nome di firma. Rappresenta un nome di firma più preciso. Utilizzato al posto dei nomi stringa. Consente di presentare firme con gli stessi nomi stringa.

## Campi

| Campo | Descrizione |
| --- | --- |
| [FullName](#FullName) | Restituisce il nome completo della firma, fornendo un identificatore unico e preciso per il campo firma. |
| [Name](#Name) | Restituisce il nome di una firma. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals](#equals-java.lang.Object-) | Determina se questa istanza e un oggetto specificato sono uguali. |
| [getSignatureDictionary](#getSignatureDictionary--) | Restituisce il dizionario della firma. |
| [hashCode](#hashCode--) | Restituisce un codice hash per questa istanza basato sulla proprietà FullName. |
| [hasSignature](#hasSignature--) | Indica se la firma è presente o meno. |
| [toString](#toString--) | Restituisce una rappresentazione stringa dell'istanza {@link SignatureName}, utilizzando principalmente il suo nome. |

### FullName {#FullName}
```
public final String FullName
```

Restituisce il nome completo della firma, fornendo un identificatore unico e preciso per il campo firma.

### Name {#Name}
```
public final String Name
```

Restituisce il nome di una firma.

### equals {#equals-java.lang.Object-}
Determina se questa istanza e un oggetto specificato sono uguali.

### getSignatureDictionary {#getSignatureDictionary--}
```
public final com.aspose.pdf.engine.data.IPdfDictionary getSignatureDictionary()
```

Restituisce il dizionario della firma.

**Returns:**
Il dizionario della firma o null se non è stato trovato.

### hashCode {#hashCode--}
```
public int hashCode()
```

Restituisce un codice hash per questa istanza basato sulla proprietà FullName.

**Returns:**
Un intero che rappresenta il codice hash della proprietà FullName.

### hasSignature {#hasSignature--}
```
public final boolean hasSignature()
```

Indica se la firma è presente o meno.

**Returns:**
valore booleano

### toString {#toString--}
```
public String toString()
```

Restituisce una rappresentazione stringa dell'istanza {@link SignatureName}, utilizzando principalmente il suo nome.

**Returns:**
Una stringa che rappresenta il nome della firma.
