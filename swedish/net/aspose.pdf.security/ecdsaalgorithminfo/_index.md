---
title: "Klass EcdsaAlgorithmInfo"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Security.EcdsaAlgorithmInfo-klass. Representerar en klass för information om ECDSA‑signaturalgoritmen."
type: docs
weight: 10130
url: /sv/net/aspose.pdf.security/ecdsaalgorithminfo/
---
## EcdsaAlgorithmInfo class

Representerar en klass för information om ECDSA-signaturalgoritmen.

```csharp
public sealed class EcdsaAlgorithmInfo : KeyedSignatureAlgorithmInfo
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
| readonly [CryptographicStandard](../../aspose.pdf.security/signaturealgorithminfo/cryptographicstandard/) | Hämtar den kryptografiska standarden som används för att signera PDF-dokumentet. |
| readonly [DigestHashAlgorithm](../../aspose.pdf.security/signaturealgorithminfo/digesthashalgorithm/) | Hämtar digest‑hash‑algoritmen som används för signaturen. För en tidsstämpel är detta digest‑hash‑algoritmen som används för att signera hashvärdet av dokumentets innehåll. |
| readonly [EccName](../../aspose.pdf.security/ecdsaalgorithminfo/eccname/) | Hämtar namnet på den elliptiska kurvan som används av ECDSA. |
| readonly [KeySize](../../aspose.pdf.security/keyedsignaturealgorithminfo/keysize/) | Hämtar storleken på den kryptografiska nyckeln som används av signaturalgoritmen. |

### Se även

* class [KeyedSignatureAlgorithmInfo](../keyedsignaturealgorithminfo/)
* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)


