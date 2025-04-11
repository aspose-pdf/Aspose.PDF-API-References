---
title: Class EcdsaAlgorithmInfo
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Security.EcdsaAlgorithmInfo-Klasse. Stellt eine Klasse für die Informationen über den ECDSA-Signaturalgorithmus dar
type: docs
weight: 9970
url: /de/net/aspose.pdf.security/ecdsaalgorithminfo/
---
## EcdsaAlgorithmInfo-Klasse

Stellt eine Klasse für die Informationen über den ECDSA-Signaturalgorithmus dar.

```csharp
public sealed class EcdsaAlgorithmInfo : KeyedSignatureAlgorithmInfo
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [SignatureName](../../aspose.pdf.security/signaturealgorithminfo/signaturename/) { get; } | Gibt den Namen des Signaturfeldes zurück. |

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
| readonly [EccName](../../aspose.pdf.security/ecdsaalgorithminfo/eccname/) | Gibt den Namen der elliptischen Kurve zurück, die von der ECDSA verwendet wird. |
| readonly [KeySize](../../aspose.pdf.security/keyedsignaturealgorithminfo/keysize/) | Gibt die Größe des kryptografischen Schlüssels zurück, der vom Signaturalgorithmus verwendet wird. |

### Siehe auch

* Klasse [KeyedSignatureAlgorithmInfo](../keyedsignaturealgorithminfo/)
* Namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* Assembly [Aspose.PDF](../../)