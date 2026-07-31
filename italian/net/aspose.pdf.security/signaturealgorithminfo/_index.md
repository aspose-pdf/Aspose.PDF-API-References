---
title: "Classe SignatureAlgorithmInfo"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Aspose.Pdf.Security.SignatureAlgorithmInfo class. Rappresenta una classe per le informazioni su un algoritmo di firma, includendo il suo tipo, lo standard crittografico e l'algoritmo di hash digest"
type: docs
weight: 10180
url: /it/net/aspose.pdf.security/signaturealgorithminfo/
---
## SignatureAlgorithmInfo class

Rappresenta una classe per le informazioni su un algoritmo di firma, includendo il suo tipo, lo standard crittografico e l'algoritmo di hash del digest.

```csharp
public abstract class SignatureAlgorithmInfo
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

### Vedi anche

* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)


