---
title: Class RsaAlgorithmInfo
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Security.RsaAlgorithmInfo-Klasse. Stellt eine Klasse für die Informationen über den RSA-Signaturalgorithmus dar
type: docs
weight: 9990
url: /de/net/aspose.pdf.security/rsaalgorithminfo/
---
## RsaAlgorithmInfo-Klasse

Stellt eine Klasse für die Informationen über den RSA-Signaturalgorithmus dar.

```csharp
public sealed class RsaAlgorithmInfo : KeyedSignatureAlgorithmInfo
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [SignatureName](../../aspose.pdf.security/signaturealgorithminfo/signaturename/) { get; } | Gibt den Namen des Signaturfelds zurück. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [ToString](../../aspose.pdf.security/signaturealgorithminfo/tostring/)() | Konvertiert das aktuelle Informationsobjekt in seine String-Darstellung. |

## Felder

| Name | Beschreibung |
| --- | --- |
| readonly [AlgorithmType](../../aspose.pdf.security/signaturealgorithminfo/algorithmtype/) | Gibt den Typ des Signaturalgorithmus zurück, der zum Signieren des PDF-Dokuments verwendet wird. |
| readonly [CryptographicStandard](../../aspose.pdf.security/signaturealgorithminfo/cryptographicstandard/) | Gibt den kryptografischen Standard zurück, der zum Signieren des PDF-Dokuments verwendet wird. |
| readonly [DigestHashAlgorithm](../../aspose.pdf.security/signaturealgorithminfo/digesthashalgorithm/) | Gibt den Digest-Hash-Algorithmus zurück, der für die Signatur verwendet wird. Für einen Zeitstempel ist dies der Digest-Hash-Algorithmus, mit dem der Hash des Dokumentinhalts signiert wird. |
| readonly [KeySize](../../aspose.pdf.security/keyedsignaturealgorithminfo/keysize/) | Gibt die Größe des kryptografischen Schlüssels zurück, der vom Signaturalgorithmus verwendet wird. |

### Siehe auch

* Klasse [KeyedSignatureAlgorithmInfo](../keyedsignaturealgorithminfo/)
* Namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* Assembly [Aspose.PDF](../../)