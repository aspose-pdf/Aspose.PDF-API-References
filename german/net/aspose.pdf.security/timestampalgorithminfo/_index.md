---
title: Class TimestampAlgorithmInfo
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Security.TimestampAlgorithmInfo-Klasse. Stellt eine Klasse für die Informationen über den Zeitstempel-Signaturalgorithmus dar
type: docs
weight: 10030
url: /de/net/aspose.pdf.security/timestampalgorithminfo/
---
## Klasse TimestampAlgorithmInfo

Stellt eine Klasse für die Informationen über den Zeitstempel-Signaturalgorithmus dar.

```csharp
public sealed class TimestampAlgorithmInfo : SignatureAlgorithmInfo
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
| readonly [ContentHashAlgorithm](../../aspose.pdf.security/timestampalgorithminfo/contenthashalgorithm/) | Gibt den Hash-Algorithmus zurück, der den Inhalt des Dokuments gehasht und dann mit [`DigestHashAlgorithm`](../signaturealgorithminfo/digesthashalgorithm/) signiert hat. |
| readonly [CryptographicStandard](../../aspose.pdf.security/signaturealgorithminfo/cryptographicstandard/) | Gibt den kryptografischen Standard zurück, der zum Signieren des PDF-Dokuments verwendet wird. |
| readonly [DigestHashAlgorithm](../../aspose.pdf.security/signaturealgorithminfo/digesthashalgorithm/) | Gibt den Digest-Hash-Algorithmus zurück, der für die Signatur verwendet wird. Für einen Zeitstempel ist dies der Digest-Hash-Algorithmus, mit dem der Hash des Dokumentinhalts signiert wird. |

### Siehe auch

* Klasse [SignatureAlgorithmInfo](../signaturealgorithminfo/)
* Namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* Assembly [Aspose.PDF](../../)