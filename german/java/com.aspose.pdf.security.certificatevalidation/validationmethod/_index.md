---
title: "ValidationMethod"
linktitle: "ValidationMethod"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt ein Enum dar, das die für die Zertifikatsvalidierung verwendete Methode definiert."
type: docs
weight: 10
url: /de/java/com.aspose.pdf.security.certificatevalidation/validationmethod/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.security.certificatevalidation.ValidationMethod, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.security.certificatevalidation.ValidationMethod, com.aspose.ms.System.Enum, com.aspose.pdf.security.certificatevalidation.ValidationMethod

```
public final class ValidationMethod extends com.aspose.ms.System.Enum
```

Stellt ein Enum dar, das die für die Zertifikatsvalidierung verwendete Methode definiert.

## Felder

| Feld | Beschreibung |
| --- | --- |
| [All](#All) | Verwendet alle verfügbaren Methoden (OCSP und CRL) zur Zertifikatsvalidierung. |
| [Auto](#Auto) | Bestimmt automatisch die beste Methode zur Zertifikatsvalidierung. |
| [Crl](#Crl) | Validiert Zertifikate mithilfe der Certificate Revocation List (CRL)-Methode. |
| [Ocsp](#Ocsp) | Verwendet das Online Certificate Status Protocol (OCSP) zur Zertifikatsvalidierung. OCSP ist ein Protokoll, das den Validierungsstatus eines Zertifikats bereitstellt, indem es die ausstellende Certificate Authority (CA) direkt abfragt. |

### All {#All}
```
public static final int All
```

Verwendet alle verfügbaren Methoden (OCSP und CRL) zur Zertifikatsvalidierung.

### Auto {#Auto}
```
public static final int Auto
```

Bestimmt automatisch die beste Methode zur Zertifikatsvalidierung.

### Crl {#Crl}
```
public static final int Crl
```

Validiert Zertifikate mithilfe der Certificate Revocation List (CRL)-Methode.

### Ocsp {#Ocsp}
```
public static final int Ocsp
```

Verwendet das Online Certificate Status Protocol (OCSP) zur Zertifikatsvalidierung. OCSP ist ein Protokoll, das den Validierungsstatus eines Zertifikats bereitstellt, indem es die ausstellende Certificate Authority (CA) direkt abfragt.
