---
title: Enum DigestHashAlgorithm
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.DigestHashAlgorithm Enum. Repräsentiert den Typ des Algorithmus, der Daten einem Hash zuordnet
type: docs
weight: 3720
url: /de/net/aspose.pdf/digesthashalgorithm/
---
## DigestHashAlgorithm Aufzählung

Repräsentiert den Typ des Algorithmus, der Daten einem "Hash" zuordnet

```csharp
public enum DigestHashAlgorithm
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Auto | `0` | Automatische Einstellung des Hashing-Algorithmus nach Ermessen des Signaturalgorithmus. Für EDCSA wird der Standardwert durch die Schlüssellänge bestimmt. Der Standardwert für ein nicht abgetrenntes PKCS7 ist Sha1. |
| Sha1 | `1` | SHA-1. Sichere Hash-Algorithmus 1. Es ist ein Standardwert für ein nicht abgetrenntes PKCS7. |
| Sha256 | `2` | SHA-256. Sichere Hash-Algorithmus 2. Es ist ein Standardwert für ein abgetrenntes PKCS7. |
| Sha384 | `3` | SHA-384. Sichere Hash-Algorithmus 2 |
| Sha512 | `4` | SHA-512. Sichere Hash-Algorithmus 2 |
| Sha3_256 | `5` | SHA3-256. Sichere Hash-Algorithmus 3 |
| Sha3_384 | `6` | SHA3-384. Sichere Hash-Algorithmus 3 |
| Sha3_512 | `7` | SHA3-512. Sichere Hash-Algorithmus 3 |

### Siehe auch

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)