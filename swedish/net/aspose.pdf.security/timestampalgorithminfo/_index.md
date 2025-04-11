---
title: Class TimestampAlgorithmInfo
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Security.TimestampAlgorithmInfo klass. Representerar en klass för information om tidsstämpelsignaturalgoritmen
type: docs
weight: 10030
url: /sv/net/aspose.pdf.security/timestampalgorithminfo/
---
## TimestampAlgorithmInfo klass

Representerar en klass för information om tidsstämpelsignaturalgoritmen.

```csharp
public sealed class TimestampAlgorithmInfo : SignatureAlgorithmInfo
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
| readonly [ContentHashAlgorithm](../../aspose.pdf.security/timestampalgorithminfo/contenthashalgorithm/) | Hämtar hash-algoritmen som hashade innehållet i dokumentet och sedan signerade det med hjälp av [`DigestHashAlgorithm`](../signaturealgorithminfo/digesthashalgorithm/). |
| readonly [CryptographicStandard](../../aspose.pdf.security/signaturealgorithminfo/cryptographicstandard/) | Hämtar den kryptografiska standard som används för att signera PDF-dokumentet. |
| readonly [DigestHashAlgorithm](../../aspose.pdf.security/signaturealgorithminfo/digesthashalgorithm/) | Hämtar digest hash-algoritmen som används för signaturen. För en tidsstämpel är detta digest hash-algoritmen med vilken hash av dokumentinnehållet signeras. |

### Se Även

* klass [SignatureAlgorithmInfo](../signaturealgorithminfo/)
* namnrum [Aspose.Pdf.Security](../../aspose.pdf.security/)
* sammansättning [Aspose.PDF](../../)