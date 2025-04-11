---
title: Enum ValidationMethod
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Security.ValidationMethod enum. Representerar en enum som definierar metoden som används för certifikatvalidering
type: docs
weight: 10050
url: /sv/net/aspose.pdf.security/validationmethod/
---
## ValidationMethod-uppräkning

Representerar en enum som definierar metoden som används för certifikatvalidering.

```csharp
public enum ValidationMethod
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Auto | `0` | Bestämmer automatiskt den bästa metoden för certifikatvalidering. |
| Ocsp | `1` | Använder Online Certificate Status Protocol (OCSP) för certifikatvalidering. OCSP är ett protokoll som tillhandahåller valideringsstatus för ett certifikat genom att direkt fråga den utfärdande certifikatmyndigheten (CA). |
| Crl | `2` | Validerar certifikat med hjälp av metoden Certificate Revocation List (CRL). |
| All | `3` | Använder alla tillgängliga metoder (OCSP och CRL) för certifikatvalidering. |

### Se Även

* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)