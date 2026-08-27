---
title: "Klass TimestampAlgorithmInfo"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Security.TimestampAlgorithmInfo klass. Representerar en klass för information om tidsstämpel‑signaturalgoritmen"
type: docs
weight: 10210
url: /sv/net/aspose.pdf.security/timestampalgorithminfo/
---
## TimestampAlgorithmInfo class

Representerar en klass för information om tidsstämpel-signaturalgoritmen.

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
| readonly [AlgorithmType](../../aspose.pdf.security/signaturealgorithminfo/algorithmtype/) | Hämtar typen av signaturalgoritmen som används för att signera PDF-dokumentet. |
| readonly [ContentHashAlgorithm](../../aspose.pdf.security/timestampalgorithminfo/contenthashalgorithm/) | Hämtar hash‑algoritmen som hashade dokumentets innehåll och sedan signerade det med [`DigestHashAlgorithm`](../signaturealgorithminfo/digesthashalgorithm/). |
| readonly [CryptographicStandard](../../aspose.pdf.security/signaturealgorithminfo/cryptographicstandard/) | Hämtar den kryptografiska standarden som används för att signera PDF-dokumentet. |
| readonly [DigestHashAlgorithm](../../aspose.pdf.security/signaturealgorithminfo/digesthashalgorithm/) | Hämtar digest‑hash‑algoritmen som används för signaturen. För en tidsstämpel är detta digest‑hash‑algoritmen som används för att signera hashvärdet av dokumentets innehåll. |

### Se även

* class [SignatureAlgorithmInfo](../signaturealgorithminfo/)
* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)


