---
title: Class DsaAlgorithmInfo
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Security.DsaAlgorithmInfo. Rappresenta una classe per le informazioni sull'algoritmo di firma DSA
type: docs
weight: 9960
url: /it/net/aspose.pdf.security/dsaalgorithminfo/
---
## Classe DsaAlgorithmInfo

Rappresenta una classe per le informazioni sull'algoritmo di firma DSA.

```csharp
public sealed class DsaAlgorithmInfo : KeyedSignatureAlgorithmInfo
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
| readonly [AlgorithmType](../../aspose.pdf.security/signaturealgorithminfo/algorithmtype/) | Ottiene il tipo di algoritmo di firma utilizzato per firmare il documento PDF. |
| readonly [CryptographicStandard](../../aspose.pdf.security/signaturealgorithminfo/cryptographicstandard/) | Ottiene lo standard crittografico utilizzato per firmare il documento PDF. |
| readonly [DigestHashAlgorithm](../../aspose.pdf.security/signaturealgorithminfo/digesthashalgorithm/) | Ottiene l'algoritmo di hash del digest utilizzato per la firma. Per un timestamp, questo è l'algoritmo di hash del digest con cui viene firmato l'hash del contenuto del documento. |
| readonly [KeySize](../../aspose.pdf.security/keyedsignaturealgorithminfo/keysize/) | Ottiene la dimensione della chiave crittografica utilizzata dall'algoritmo di firma. |

### Vedi Anche

* classe [KeyedSignatureAlgorithmInfo](../keyedsignaturealgorithminfo/)
* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)