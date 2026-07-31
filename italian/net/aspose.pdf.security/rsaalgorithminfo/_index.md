---
title: "Classe RsaAlgorithmInfo"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Aspose.Pdf.Security.RsaAlgorithmInfo class. Rappresenta una classe per le informazioni sull'algoritmo di firma RSA"
type: docs
weight: 10170
url: /it/net/aspose.pdf.security/rsaalgorithminfo/
---
## RsaAlgorithmInfo class

Rappresenta una classe per le informazioni sull'algoritmo di firma RSA.

```csharp
public sealed class RsaAlgorithmInfo : KeyedSignatureAlgorithmInfo
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
| readonly [CryptographicStandard](../../aspose.pdf.security/signaturealgorithminfo/cryptographicstandard/) | Ottiene lo standard crittografico utilizzato per firmare il documento PDF. |
| readonly [DigestHashAlgorithm](../../aspose.pdf.security/signaturealgorithminfo/digesthashalgorithm/) | Ottiene l'algoritmo di hash digest utilizzato per la firma. Per un timestamp, questo è l'algoritmo di hash digest con cui viene firmato l'hash del contenuto del documento. |
| readonly [KeySize](../../aspose.pdf.security/keyedsignaturealgorithminfo/keysize/) | Ottiene la dimensione della chiave crittografica utilizzata dall'algoritmo di firma. |

### Vedi anche

* class [KeyedSignatureAlgorithmInfo](../keyedsignaturealgorithminfo/)
* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)


