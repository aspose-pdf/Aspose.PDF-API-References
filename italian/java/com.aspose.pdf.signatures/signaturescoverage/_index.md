---
title: "SignaturesCoverage"
linktitle: "SignaturesCoverage"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta un enum per il livello di copertura fornito dalle firme digitali in un documento."
type: docs
weight: 40
url: /it/java/com.aspose.pdf.signatures/signaturescoverage/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.signatures.SignaturesCoverage, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.signatures.SignaturesCoverage, com.aspose.ms.System.Enum, com.aspose.pdf.signatures.SignaturesCoverage

```
public final class SignaturesCoverage extends com.aspose.ms.System.Enum
```

Rappresenta un enum per il livello di copertura fornito dalle firme digitali in un documento.

## Campi

| Campo | Descrizione |
| --- | --- |
| [EntirelySigned](#EntirelySigned) | Indica che il documento è interamente coperto da firme digitali. Questo valore segnala che tutte le parti richieste del documento sono state firmate e nessuna firma è compromessa. |
| [PartiallySigned](#PartiallySigned) | Indica che il documento è parzialmente firmato, il che significa che alcune, ma non tutte, le sue parti sono coperte da firme digitali. Questo valore è usato quando alcune parti del documento rimangono non firmate o sono escluse dalla copertura delle firme. |
| [Undefined](#Undefined) | Indica che lo stato della copertura delle firme digitali nel documento è indefinito. Questo valore è tipicamente usato quando una o più firme nel documento sono compromesse o non possono essere verificate, impedendo una valutazione definitiva della copertura delle firme del documento. |

### EntirelySigned {#EntirelySigned}
```
public static final int EntirelySigned
```

Indica che il documento è interamente coperto da firme digitali. Questo valore segnala che tutte le parti richieste del documento sono state firmate e nessuna firma è compromessa.

### PartiallySigned {#PartiallySigned}
```
public static final int PartiallySigned
```

Indica che il documento è parzialmente firmato, il che significa che alcune, ma non tutte, le sue parti sono coperte da firme digitali. Questo valore è usato quando alcune parti del documento rimangono non firmate o sono escluse dalla copertura delle firme.

### Undefined {#Undefined}
```
public static final int Undefined
```

Indica che lo stato della copertura delle firme digitali nel documento è indefinito. Questo valore è tipicamente usato quando una o più firme nel documento sono compromesse o non possono essere verificate, impedendo una valutazione definitiva della copertura delle firme del documento.
