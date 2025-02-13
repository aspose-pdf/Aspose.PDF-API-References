---
title: Enum ValidationMethod
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Security.ValidationMethod enum. Represents an enum defined the method used for certificate validation
type: docs
weight: 9060
url: /net/aspose.pdf.security/validationmethod/
---
## ValidationMethod enumeration

Represents an enum defined the method used for certificate validation.

```csharp
public enum ValidationMethod
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Auto | `0` | Automatically determines the best method for certificate validation. |
| Ocsp | `1` | Uses the Online Certificate Status Protocol (OCSP) for certificate validation. OCSP is a protocol that provides the validation status of a certificate by directly querying the issuing Certificate Authority (CA). |
| Crl | `2` | Validates certificates using the Certificate Revocation List (CRL) method. |
| All | `3` | Uses all available methods (OCSP and CRL) for certificate validation. |

### See Also

* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)


