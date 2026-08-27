---
title: "Enum ValidationMethod"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Enum Aspose.Pdf.Security.ValidationMethod. Rappresenta un enum che definisce il metodo utilizzato per la convalida del certificato."
type: docs
weight: 10230
url: /it/net/aspose.pdf.security/validationmethod/
---
## ValidationMethod enumeration

Rappresenta un enum che definisce il metodo usato per la convalida del certificato.

```csharp
public enum ValidationMethod
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Auto | `0` | Determina automaticamente il metodo migliore per la convalida del certificato. |
| Ocsp | `1` | Utilizza il Online Certificate Status Protocol (OCSP) per la convalida del certificato. OCSP è un protocollo che fornisce lo stato di convalida di un certificato interrogando direttamente l'Autorità di Certificazione (CA) emittente. |
| Crl | `2` | Convalida i certificati utilizzando il metodo Certificate Revocation List (CRL). |
| All | `3` | Utilizza tutti i metodi disponibili (OCSP e CRL) per la convalida del certificato. |

### Vedi anche

* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)


