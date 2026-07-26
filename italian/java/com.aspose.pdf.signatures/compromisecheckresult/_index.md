---
title: "CompromiseCheckResult"
linktitle: "CompromiseCheckResult"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta una classe per verificare la compromissione delle firme digitali del documento."
type: docs
weight: 10
url: /it/java/com.aspose.pdf.signatures/compromisecheckresult/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.signatures.CompromiseCheckResult

```
public final class CompromiseCheckResult extends Object
```

Rappresenta una classe per verificare la compromissione delle firme digitali del documento.

## Campi

| Campo | Descrizione |
| --- | --- |
| [CompromisedSignatures](#CompromisedSignatures) | Ottiene una raccolta di firme digitali identificate come compromesse. Questa proprietà contiene l'elenco di tutte le firme compromesse rilevate nel documento. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getSignaturesCoverage](#getSignaturesCoverage--) | Ottiene lo stato di copertura delle firme digitali in un documento. Se è uguale a {@code SignaturesCoverage#Undefined}, allora una delle firme è compromessa. |
| [hasCompromisedSignatures](#hasCompromisedSignatures--) | Indica se nel documento sono presenti firme digitali compromesse. Restituisce true se almeno una firma è compromessa; altrimenti, false. |

### CompromisedSignatures {#CompromisedSignatures}
```
public final List < SignatureName > CompromisedSignatures
```

Ottiene una raccolta di firme digitali identificate come compromesse. Questa proprietà contiene l'elenco di tutte le firme compromesse rilevate nel documento.

### getSignaturesCoverage {#getSignaturesCoverage--}
```
public final int getSignaturesCoverage()
```

Ottiene lo stato di copertura delle firme digitali in un documento. Se è uguale a {@code SignaturesCoverage#Undefined}, allora una delle firme è compromessa.

**Returns:**
Elemento SignaturesCoverage

### hasCompromisedSignatures {#hasCompromisedSignatures--}
```
public final boolean hasCompromisedSignatures()
```

Indica se nel documento sono presenti firme digitali compromesse. Restituisce true se almeno una firma è compromessa; altrimenti, false.

**Returns:**
valore booleano
