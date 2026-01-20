---
title: Aspose::Pdf::Security::ValidationMethod enum
linktitle: ValidationMethod
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Security::ValidationMethod enum. Represents an enum defined the method used for certificate validation in C++.'
type: docs
weight: 1600
url: /cpp/aspose.pdf.security/validationmethod/
---
## ValidationMethod enum


Represents an enum defined the method used for certificate validation.

```cpp
enum class ValidationMethod
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Auto | 0 | Automatically determines the best method for certificate validation. |
| Ocsp | 1 | Uses the Online Certificate Status Protocol (OCSP) for certificate validation. OCSP is a protocol that provides the validation status of a certificate by directly querying the issuing Certificate Authority (CA). |
| Crl | 2 | Validates certificates using the Certificate Revocation List (CRL) method. |
| All | 3 | Uses all available methods (OCSP and CRL) for certificate validation. |

## See Also

* Namespace [Aspose::Pdf::Security](../)
* Library [Aspose.PDF for C++](../../)
