---
title: "Classe TimestampAlgorithmInfo"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Aspose.Pdf.Security.TimestampAlgorithmInfo class. Rappresenta una classe per le informazioni sull'algoritmo di firma timestamp"
type: docs
weight: 10210
url: /it/net/aspose.pdf.security/timestampalgorithminfo/
---
## TimestampAlgorithmInfo class

Rappresenta una classe per le informazioni sull'algoritmo di firma timestamp.

```csharp
public sealed class TimestampAlgorithmInfo : SignatureAlgorithmInfo
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [SignatureName](../../aspose.pdf.security/signaturealgorithminfo/signaturename/) { get; } | Ottiene il nome del campo della firma. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [ToString](../../aspose.pdf.security/signaturealgorithminfo/tostring/)() | Converte l'oggetto informazione corrente nella sua rappresentazione stringa. |

## Campi

| Nome | Descrizione |
| --- | --- |
| readonly [AlgorithmType](../../aspose.pdf.security/signaturealgorithminfo/algorithmtype/) | Ottiene il tipo dell'algoritmo di firma utilizzato per firmare il documento PDF. |
| readonly [ContentHashAlgorithm](../../aspose.pdf.security/timestampalgorithminfo/contenthashalgorithm/) | Ottiene l'algoritmo di hash che ha hashato il contenuto del documento e poi lo ha firmato utilizzando [`DigestHashAlgorithm`](../signaturealgorithminfo/digesthashalgorithm/). |
| readonly [CryptographicStandard](../../aspose.pdf.security/signaturealgorithminfo/cryptographicstandard/) | Ottiene lo standard crittografico utilizzato per firmare il documento PDF. |
| readonly [DigestHashAlgorithm](../../aspose.pdf.security/signaturealgorithminfo/digesthashalgorithm/) | Ottiene l'algoritmo di hash digest utilizzato per la firma. Per un timestamp, questo è l'algoritmo di hash digest con cui viene firmato l'hash del contenuto del documento. |

### Vedi anche

* class [SignatureAlgorithmInfo](../signaturealgorithminfo/)
* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)


