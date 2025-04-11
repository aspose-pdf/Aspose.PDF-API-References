---
title: Class TimestampAlgorithmInfo
second_title: Aspose.PDF for .NET API Reference
description: Rappresenta una classe per l'informazione sull'algoritmo della firma temporale.
type: docs
weight: 10030
url: /it/net/aspose.pdf.security/timestampalgorithminfo/
---
## TimestampAlgorithmInfo class

Rappresenta una classe per le informazioni sull'algoritmo di firma del timestamp.

```csharp
public sealed class TimestampAlgorithmInfo : SignatureAlgorithmInfo
```

## Properties

| Name | Description |
| --- | --- |
| [SignatureName](../../aspose.pdf.security/signaturealgorithminfo/signaturename/) { get; } | Ottiene il nome del campo di firma. |

## Methods

| Name | Description |
| --- | --- |
| override [ToString](../../aspose.pdf.security/signaturealgorithminfo/tostring/)() | Converte l'oggetto informativo corrente nella sua rappresentazione stringa. |

## Fields

| Name | Description |
| --- | --- |
| readonly [AlgorithmType](../../aspose.pdf.security/signaturealgorithminfo/algorithmtype/) | Ottiene il tipo dell'algoritmo di firma utilizzato per firmare il documento PDF. |
| readonly [ContentHashAlgorithm](../../aspose.pdf.security/timestampalgorithminfo/contenthashalgorithm/) | Ottiene l'algoritmo di hash che ha effettuato l'hash del contenuto del documento e poi lo ha firmato utilizzando [`DigestHashAlgorithm`](../signaturealgorithminfo/digesthashalgorithm/). |
| readonly [CryptographicStandard](../../aspose.pdf.security/signaturealgorithminfo/cryptographicstandard/) | Ottiene lo standard crittografico utilizzato per firmare il documento PDF. |
| readonly [DigestHashAlgorithm](../../aspose.pdf.security/signaturealgorithminfo/digesthashalgorithm/) | Ottiene l'algoritmo di hash del digest utilizzato per la firma. Per un timestamp, questo è l'algoritmo di hash del digest con cui viene firmato l'hash del contenuto del documento. |

### See Also

* class [SignatureAlgorithmInfo](../signaturealgorithminfo/)
* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)