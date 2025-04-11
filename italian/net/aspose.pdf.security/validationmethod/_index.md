---
title: Enum ValidationMethod
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Securità.ValidationMethod enum. Rappresenta un'enumerazione definita del metodo utilizzato per la validazione dei certificati.
type: docs
weight: 10050
url: /it/net/aspose.pdf.security/validationmethod/
---
## Enumerazione ValidationMethod

Rappresenta un enum definito il metodo utilizzato per la validazione del certificato.

```csharp
public enum ValidationMethod
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Auto | `0` | Determina automaticamente il miglior metodo per la validazione del certificato. |
| Ocsp | `1` | Utilizza il Protocollo di Stato del Certificato Online (OCSP) per la validazione del certificato. OCSP è un protocollo che fornisce lo stato di validazione di un certificato interrogando direttamente l'Autorità di Certificazione (CA) emittente. |
| Crl | `2` | Valida i certificati utilizzando il metodo della Lista di Revoca dei Certificati (CRL). |
| All | `3` | Utilizza tutti i metodi disponibili (OCSP e CRL) per la validazione del certificato. |

### Vedi Anche

* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)