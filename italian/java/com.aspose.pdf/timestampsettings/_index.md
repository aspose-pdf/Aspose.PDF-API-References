---
title: "TimestampSettings"
linktitle: "TimestampSettings"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta le impostazioni OCSP utilizzate durante il processo di firma."
type: docs
weight: 5360
url: /it/java/com.aspose.pdf/timestampsettings/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TimestampSettings

```
public class TimestampSettings extends Object
```

Rappresenta le impostazioni OCSP utilizzate durante il processo di firma.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [TimestampSettings](#TimestampSettings-java.lang.String-java.lang.String-) | Inizializza una nuova istanza della classe {@code TimestampSettings}. |
| [TimestampSettings](#TimestampSettings-java.lang.String-java.lang.String-com.aspose.pdf.DigestHashAlgorithm-) | Inizializza una nuova istanza della classe {@code TimestampSettings}. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBasicAuthCredentials](#getBasicAuthCredentials--) | Recupera le credenziali di autenticazione di base, Username e password sono combinati in una stringa "username:password". |
| [getDigestHashAlgorithm](#getDigestHashAlgorithm--) | Recupera/imposta l'algoritmo digest per le funzioni hash interne. |
| [getServerUrl](#getServerUrl--) | Recupera l'URL del server timestamp. |
| [setBasicAuthCredentials](#setBasicAuthCredentials-java.lang.String-) | Imposta le credenziali di autenticazione di base, Username e password sono combinati in una stringa "username:password". |
| [setDigestHashAlgorithm](#setDigestHashAlgorithm-com.aspose.pdf.DigestHashAlgorithm-) | Recupera/imposta l'algoritmo digest per le funzioni hash interne. |
| [setServerUrl](#setServerUrl-java.lang.String-) | Imposta l'URL del server timestamp. |

### TimestampSettings {#TimestampSettings-java.lang.String-java.lang.String-}
Inizializza una nuova istanza della classe {@code TimestampSettings}.

### TimestampSettings {#TimestampSettings-java.lang.String-java.lang.String-com.aspose.pdf.DigestHashAlgorithm-}
Inizializza una nuova istanza della classe {@code TimestampSettings}.

### getBasicAuthCredentials {#getBasicAuthCredentials--}
```
public String getBasicAuthCredentials()
```

Recupera le credenziali di autenticazione di base, Username e password sono combinati in una stringa "username:password".

**Returns:**
valore String

### getDigestHashAlgorithm {#getDigestHashAlgorithm--}
```
public final DigestHashAlgorithm getDigestHashAlgorithm()
```

Recupera/imposta l'algoritmo digest per le funzioni hash interne.

**Returns:**
Elemento DigestHashAlgorithm @see DigestHashAlgorithm

### getServerUrl {#getServerUrl--}
```
public String getServerUrl()
```

Recupera l'URL del server timestamp.

**Returns:**
valore String

### setBasicAuthCredentials {#setBasicAuthCredentials-java.lang.String-}
Imposta le credenziali di autenticazione di base, Username e password sono combinati in una stringa "username:password".

### setDigestHashAlgorithm {#setDigestHashAlgorithm-com.aspose.pdf.DigestHashAlgorithm-}
Recupera/imposta l'algoritmo digest per le funzioni hash interne.

### setServerUrl {#setServerUrl-java.lang.String-}
Imposta l'URL del server timestamp.
