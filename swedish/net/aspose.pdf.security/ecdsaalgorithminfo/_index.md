---
title: Class EcdsaAlgorithmInfo
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Security.EcdsaAlgorithmInfo klass. Representerar en klass för information om ECDSA-signaturalgoritmen
type: docs
weight: 9970
url: /sv/net/aspose.pdf.security/ecdsaalgorithminfo/
---
## EcdsaAlgorithmInfo klass

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
| readonly [AlgorithmType](../../aspose.pdf.security/signaturealgorithminfo/algorithmtype/) | Hämtar typen av signaturalgoritm som används för att signera PDF-dokumentet. |
| readonly [CryptographicStandard](../../aspose.pdf.security/signaturealgorithminfo/cryptographicstandard/) | Hämtar den kryptografiska standard som används för att signera PDF-dokumentet. |
| readonly [DigestHashAlgorithm](../../aspose.pdf.security/signaturealgorithminfo/digesthashalgorithm/) | Hämtar digest hash-algoritmen som används för signaturen. För en tidsstämpel är detta digest hash-algoritmen med vilken hash av dokumentinnehållet signeras. |
| readonly [EccName](../../aspose.pdf.security/ecdsaalgorithminfo/eccname/) | Hämtar namnet på den elliptiska kurvan som används av ECDSA. |
| readonly [KeySize](../../aspose.pdf.security/keyedsignaturealgorithminfo/keysize/) | Hämtar storleken på den kryptografiska nyckeln som används av signaturalgoritmen. |

### Se Även

* klass [KeyedSignatureAlgorithmInfo](../keyedsignaturealgorithminfo/)
* namnrum [Aspose.Pdf.Security](../../aspose.pdf.security/)
* sammansättning [Aspose.PDF](../../)