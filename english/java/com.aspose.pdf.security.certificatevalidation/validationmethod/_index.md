---
title: ValidationMethod
second_title: Aspose.PDF for Java API Reference
description: Represents an enum defined the method used for certificate validation.
type: docs
weight: 10
url: /java/com.aspose.pdf.security.certificatevalidation/validationmethod/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.security.certificatevalidation.ValidationMethod, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.security.certificatevalidation.ValidationMethod, com.aspose.ms.System.Enum, com.aspose.pdf.security.certificatevalidation.ValidationMethod

```
public final class ValidationMethod extends com.aspose.ms.System.Enum
```

Represents an enum defined the method used for certificate validation.

## Fields

| Field | Description |
| --- | --- |
| [All](#All) | Uses all available methods (OCSP and CRL) for certificate validation. |
| [Auto](#Auto) | Automatically determines the best method for certificate validation. |
| [Crl](#Crl) | Validates certificates using the Certificate Revocation List (CRL) method. |
| [Ocsp](#Ocsp) | Uses the Online Certificate Status Protocol (OCSP) for certificate validation. OCSP is a protocol that provides the validation status of a certificate by directly querying the issuing Certificate Authority (CA). |

### All {#All}
```
public static final int All
```

Uses all available methods (OCSP and CRL) for certificate validation.

### Auto {#Auto}
```
public static final int Auto
```

Automatically determines the best method for certificate validation.

### Crl {#Crl}
```
public static final int Crl
```

Validates certificates using the Certificate Revocation List (CRL) method.

### Ocsp {#Ocsp}
```
public static final int Ocsp
```

Uses the Online Certificate Status Protocol (OCSP) for certificate validation. OCSP is a protocol that provides the validation status of a certificate by directly querying the issuing Certificate Authority (CA).
