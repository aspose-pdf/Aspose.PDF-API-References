---
title: Class UnknownSignatureAlgorithmInfo
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Security.UnknownSignatureAlgorithmInfo. Rappresenta una classe per le informazioni sull'algoritmo di firma sconosciuto
type: docs
weight: 10040
url: /it/net/aspose.pdf.security/unknownsignaturealgorithminfo/
---
## Classe UnknownSignatureAlgorithmInfo

Rappresenta una classe per le informazioni sull'algoritmo di firma sconosciuto.

```csharp
public sealed class UnknownSignatureAlgorithmInfo : SignatureAlgorithmInfo
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [SignatureName](../../aspose.pdf.security/signaturealgorithminfo/signaturename/) { get; } | Ottiene il nome del campo di firma. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [ToString](../../aspose.pdf.security/signaturealgorithminfo/tostring/)() | Converte l'oggetto informazioni corrente nella sua rappresentazione stringa. |

## Campi

| Nome | Descrizione |
| --- | --- |
| readonly [AlgorithmType](../../aspose.pdf.security/signaturealgorithminfo/algorithmtype/) | Ottiene il tipo dell'algoritmo di firma utilizzato per firmare il documento PDF. |
| readonly [CryptographicStandard](../../aspose.pdf.security/signaturealgorithminfo/cryptographicstandard/) | Ottiene lo standard crittografico utilizzato per firmare il documento PDF. |
| readonly [DigestHashAlgorithm](../../aspose.pdf.security/signaturealgorithminfo/digesthashalgorithm/) | Ottiene l'algoritmo di hash del digest utilizzato per la firma. Per un timestamp, questo è l'algoritmo di hash del digest con cui viene firmato l'hash del contenuto del documento. |

### Vedi Anche

* classe [SignatureAlgorithmInfo](../signaturealgorithminfo/)
* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)