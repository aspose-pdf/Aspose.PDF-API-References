---
title: "Aspose::Pdf::Security::ValidationMethod enum"
linktitle: "ValidationMethod"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Security::ValidationMethod enum. Representerar en enum som definierar metoden som används för certifikatvalidering i C++."
type: docs
weight: 1700
url: /sv/cpp/aspose.pdf.security/validationmethod/
---
## ValidationMethod enum


Representerar en enum som definierar metoden som används för certifikatvalidering.

```cpp
enum class ValidationMethod
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Auto | 0 | Bestämmer automatiskt den bästa metoden för certifikatvalidering. |
| Ocsp | 1 | Använder Online Certificate Status Protocol (OCSP) för certifikatvalidering. OCSP är ett protokoll som tillhandahåller valideringsstatus för ett certifikat genom att direkt fråga den utfärdande certifikatutfärdaren (CA). |
| Crl | 2 | Validerar certifikat med hjälp av Certificate Revocation List (CRL)-metoden. |
| Alla | 3 | Använder alla tillgängliga metoder (OCSP och CRL) för certifikatvalidering. |

## Se även

* Namespace [Aspose::Pdf::Security](../)
* Library [Aspose.PDF for C++](../../)
