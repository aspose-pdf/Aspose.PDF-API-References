---
title: "ValidationResult"
linktitle: "ValidationResult"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta il risultato di un processo di convalida per un certificato. La classe ValidationResult fornisce informazioni sull'esito della convalida di un certificato, incluso il suo."
type: docs
weight: 40
url: /it/java/com.aspose.pdf.security.certificatevalidation/validationresult/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.security.certificatevalidation.ValidationResult

```
public final class ValidationResult extends Object
```

Rappresenta il risultato di un processo di convalida per un certificato. La classe ValidationResult fornisce informazioni sull'esito della convalida di un certificato, includendo il suo stato e un messaggio che descrive eventuali problemi riscontrati durante la convalida.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ValidationResult](#ValidationResult--) | Crea un'istanza della classe {@link ValidationResult}. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getMessage](#getMessage--) | Rappresenta il messaggio associato al risultato della convalida. La proprietà Message fornisce contesto aggiuntivo o informazioni sullo stato del risultato della convalida. |
| [getStatus](#getStatus--) | Ottiene lo stato del processo di convalida per un certificato. La proprietà Status indica l'esito della convalida del certificato. I valori possibili sono definiti nell'enumerazione {@link ValidationStatus}, come Valid, Invalid o Undefined. Fornisce una visione su se il certificato ha superato i controlli di convalida o meno. |
| [setMessage](#setMessage-java.lang.String-) | Rappresenta il messaggio associato al risultato della convalida. La proprietà Message fornisce contesto aggiuntivo o informazioni sullo stato del risultato della convalida. |
| [setStatus](#setStatus-int-) | Ottiene lo stato del processo di convalida per un certificato. La proprietà Status indica l'esito della convalida del certificato. I valori possibili sono definiti nell'enumerazione {@link ValidationStatus}, come Valid, Invalid o Undefined. Fornisce una visione su se il certificato ha superato i controlli di convalida o meno. |

### ValidationResult {#ValidationResult--}
```
public ValidationResult()
```

Crea un'istanza della classe {@link ValidationResult}.

### getMessage {#getMessage--}
```
public final String getMessage()
```

Rappresenta il messaggio associato al risultato della convalida. La proprietà Message fornisce contesto aggiuntivo o informazioni sullo stato del risultato della convalida.

**Returns:**
valore String

### getStatus {#getStatus--}
```
public final int getStatus()
```

Ottiene lo stato del processo di convalida per un certificato. La proprietà Status indica l'esito della convalida del certificato. I valori possibili sono definiti nell'enumerazione {@link ValidationStatus}, come Valid, Invalid o Undefined. Fornisce una visione su se il certificato ha superato i controlli di convalida o meno.

**Returns:**
Elemento ValidationStatus

### setMessage {#setMessage-java.lang.String-}
Rappresenta il messaggio associato al risultato della convalida. La proprietà Message fornisce contesto aggiuntivo o informazioni sullo stato del risultato della convalida.

### setStatus {#setStatus-int-}
```
public final void setStatus(int value)
```

Ottiene lo stato del processo di convalida per un certificato. La proprietà Status indica l'esito della convalida del certificato. I valori possibili sono definiti nell'enumerazione {@link ValidationStatus}, come Valid, Invalid o Undefined. Fornisce una visione su se il certificato ha superato i controlli di convalida o meno.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | Elemento ValidationStatus |
