---
title: "FieldSerializationResult"
linktitle: "FieldSerializationResult"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta il risultato di un processo di serializzazione di un campo modulo."
type: docs
weight: 1390
url: /it/java/com.aspose.pdf/fieldserializationresult/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FieldSerializationResult

```
public class FieldSerializationResult extends Object
```

Rappresenta il risultato di un processo di serializzazione di un campo modulo.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [FieldSerializationResult](#FieldSerializationResult--) | Inizializza una nuova istanza della classe {@link FieldSerializationResult}. |
| [FieldSerializationResult](#FieldSerializationResult-java.lang.String-) | Inizializza una nuova istanza della classe {@link FieldSerializationResult}. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getErrorMessages](#getErrorMessages--) | Recupera i messaggi di errore associati al processo di serializzazione. Valore: Un insieme di messaggi di errore. |
| [getFieldFullName](#getFieldFullName--) | Recupera il nome completo del campo. Valore: Il nome completo del campo. |
| [getFieldSerializationStatus](#getFieldSerializationStatus--) | Recupera lo stato della serializzazione del campo del modulo. Valore: Lo stato della serializzazione del campo del modulo. |
| [getWarningMessages](#getWarningMessages--) | Recupera i messaggi di avviso associati al processo di serializzazione. Valore: Un insieme di messaggi di avviso. |
| [updateStatus](#updateStatus-int-java.lang.String-) | Aggiorna lo stato della serializzazione e aggiunge un messaggio al set appropriato. |

### FieldSerializationResult {#FieldSerializationResult--}
```
public FieldSerializationResult()
```

Inizializza una nuova istanza della classe {@link FieldSerializationResult}.

### FieldSerializationResult {#FieldSerializationResult-java.lang.String-}
Inizializza una nuova istanza della classe {@link FieldSerializationResult}.

### getErrorMessages {#getErrorMessages--}
```
public final HashSet < String > getErrorMessages()
```

Recupera i messaggi di errore associati al processo di serializzazione. Valore: Un insieme di messaggi di errore.

**Returns:**
Istanza HashSet di String

### getFieldFullName {#getFieldFullName--}
```
public final String getFieldFullName()
```

Recupera il nome completo del campo. Valore: Il nome completo del campo.

**Returns:**
valore String

### getFieldSerializationStatus {#getFieldSerializationStatus--}
```
public final int getFieldSerializationStatus()
```

Recupera lo stato della serializzazione del campo del modulo. Valore: Lo stato della serializzazione del campo del modulo.

**Returns:**
Elemento FieldSerializationStatus

### getWarningMessages {#getWarningMessages--}
```
public final HashSet < String > getWarningMessages()
```

Recupera i messaggi di avviso associati al processo di serializzazione. Valore: Un insieme di messaggi di avviso.

**Returns:**
Istanza HashSet di String

### updateStatus {#updateStatus-int-java.lang.String-}
Aggiorna lo stato della serializzazione e aggiunge un messaggio al set appropriato.
