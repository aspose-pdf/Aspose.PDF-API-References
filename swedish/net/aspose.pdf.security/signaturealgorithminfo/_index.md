---
title: Class SignatureAlgorithmInfo
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Security.SignatureAlgorithmInfo klass. Representerar en klass för information om en signaturalgoritm inklusive dess typ, kryptografiska standard och digest hash-algoritm
type: docs
weight: 10000
url: /sv/net/aspose.pdf.security/signaturealgorithminfo/
---
## SignatureAlgorithmInfo klass

Representerar en klass för information om en signaturalgoritm, inklusive dess typ, kryptografiska standard och digest hash-algoritm.

```csharp
public abstract class SignatureAlgorithmInfo
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [SignatureName](../../aspose.pdf.security/signaturealgorithminfo/signaturename/) { get; } | Hämtar namnet på signaturfältet. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [ToString](../../aspose.pdf.security/signaturealgorithminfo/tostring/)() | Konverterar det aktuella informationsobjektet till dess strängrepresentation. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| readonly [AlgorithmType](../../aspose.pdf.security/signaturealgorithminfo/algorithmtype/) | Hämtar typen av signaturalgoritm som används för att signera PDF-dokumentet. |
| readonly [CryptographicStandard](../../aspose.pdf.security/signaturealgorithminfo/cryptographicstandard/) | Hämtar den kryptografiska standard som används för att signera PDF-dokumentet. |
| readonly [DigestHashAlgorithm](../../aspose.pdf.security/signaturealgorithminfo/digesthashalgorithm/) | Hämtar digest hash-algoritmen som används för signaturen. För en tidsstämpel är detta digest hash-algoritmen med vilken hash av dokumentinnehållet signeras. |

### Se Även

* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)