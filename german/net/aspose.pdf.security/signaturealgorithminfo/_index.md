---
title: Class SignatureAlgorithmInfo
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Security.SignatureAlgorithmInfo-Klasse. Stellt eine Klasse für Informationen über einen Signaturalgorithmus dar, einschließlich seines Typs, kryptografischen Standards und Digest-Hash-Algorithmus.
type: docs
weight: 10000
url: /de/net/aspose.pdf.security/signaturealgorithminfo/
---
## SignatureAlgorithmInfo-Klasse

Stellt eine Klasse für Informationen über einen Signaturalgorithmus dar, einschließlich seines Typs, kryptografischen Standards und Digest-Hash-Algorithmus.

```csharp
public abstract class SignatureAlgorithmInfo
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

### Siehe auch

* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)