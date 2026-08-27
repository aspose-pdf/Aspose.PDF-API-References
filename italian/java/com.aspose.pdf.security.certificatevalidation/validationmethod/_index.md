---
title: "ValidationMethod"
linktitle: "ValidationMethod"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta un enum che definisce il metodo usato per la convalida del certificato."
type: docs
weight: 10
url: /it/java/com.aspose.pdf.security.certificatevalidation/validationmethod/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.security.certificatevalidation.ValidationMethod, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.security.certificatevalidation.ValidationMethod, com.aspose.ms.System.Enum, com.aspose.pdf.security.certificatevalidation.ValidationMethod

```
public final class ValidationMethod extends com.aspose.ms.System.Enum
```

Rappresenta un enum che definisce il metodo usato per la convalida del certificato.

## Campi

| Campo | Descrizione |
| --- | --- |
| [All](#All) | Utilizza tutti i metodi disponibili (OCSP e CRL) per la convalida del certificato. |
| [Auto](#Auto) | Determina automaticamente il metodo migliore per la convalida del certificato. |
| [Crl](#Crl) | Convalida i certificati utilizzando il metodo Certificate Revocation List (CRL). |
| [Ocsp](#Ocsp) | Utilizza il protocollo Online Certificate Status Protocol (OCSP) per la convalida del certificato. OCSP è un protocollo che fornisce lo stato di convalida di un certificato interrogando direttamente l'Autorità di Certificazione (CA) emittente. |

### All {#All}
```
public static final int All
```

Utilizza tutti i metodi disponibili (OCSP e CRL) per la convalida del certificato.

### Auto {#Auto}
```
public static final int Auto
```

Determina automaticamente il metodo migliore per la convalida del certificato.

### Crl {#Crl}
```
public static final int Crl
```

Convalida i certificati utilizzando il metodo Certificate Revocation List (CRL).

### Ocsp {#Ocsp}
```
public static final int Ocsp
```

Utilizza il protocollo Online Certificate Status Protocol (OCSP) per la convalida del certificato. OCSP è un protocollo che fornisce lo stato di convalida di un certificato interrogando direttamente l'Autorità di Certificazione (CA) emittente.
