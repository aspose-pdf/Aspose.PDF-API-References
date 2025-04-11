---
title: Class EcdsaAlgorithmInfo
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Security.EcdsaAlgorithmInfo. Rappresenta una classe per le informazioni sull'algoritmo di firma ECDSA
type: docs
weight: 9970
url: /it/net/aspose.pdf.security/ecdsaalgorithminfo/
---
## Classe EcdsaAlgorithmInfo

Rappresenta una classe per le informazioni sull'algoritmo di firma ECDSA.

```csharp
public sealed class EcdsaAlgorithmInfo : KeyedSignatureAlgorithmInfo
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [SignatureName](../../aspose.pdf.security/signaturealgorithminfo/signaturename/) { get; } | Ottiene il nome del campo di firma. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [ToString](../../aspose.pdf.security/signaturealgorithminfo/tostring/)() | Converte l'oggetto informativo corrente nella sua rappresentazione stringa. |

## Campi

| Nome | Descrizione |
| --- | --- |
| readonly [AlgorithmType](../../aspose.pdf.security/signaturealgorithminfo/algorithmtype/) | Ottiene il tipo dell'algoritmo di firma utilizzato per firmare il documento PDF. |
| readonly [CryptographicStandard](../../aspose.pdf.security/signaturealgorithminfo/cryptographicstandard/) | Ottiene lo standard crittografico utilizzato per firmare il documento PDF. |
| readonly [DigestHashAlgorithm](../../aspose.pdf.security/signaturealgorithminfo/digesthashalgorithm/) | Ottiene l'algoritmo di hash digest utilizzato per la firma. Per un timestamp, questo è l'algoritmo di hash digest con cui viene firmato l'hash del contenuto del documento. |
| readonly [EccName](../../aspose.pdf.security/ecdsaalgorithminfo/eccname/) | Ottiene il nome della curva ellittica utilizzata dall'ECDSA. |
| readonly [KeySize](../../aspose.pdf.security/keyedsignaturealgorithminfo/keysize/) | Ottiene la dimensione della chiave crittografica utilizzata dall'algoritmo di firma. |

### Vedi Anche

* classe [KeyedSignatureAlgorithmInfo](../keyedsignaturealgorithminfo/)
* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)