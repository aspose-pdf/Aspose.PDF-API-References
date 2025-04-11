---
title: Class TimestampAlgorithmInfo
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Security.TimestampAlgorithmInfo. Representa uma classe para as informações sobre o algoritmo de assinatura de timestamp
type: docs
weight: 10030
url: /pt/net/aspose.pdf.security/timestampalgorithminfo/
---
## Classe TimestampAlgorithmInfo

Representa uma classe para as informações sobre o algoritmo de assinatura de timestamp.

```csharp
public sealed class TimestampAlgorithmInfo : SignatureAlgorithmInfo
```

## Propriedades

| Nome | Descrição |
| --- | --- |
| [SignatureName](../../aspose.pdf.security/signaturealgorithminfo/signaturename/) { get; } | Obtém o nome do campo de assinatura. |

## Métodos

| Nome | Descrição |
| --- | --- |
| override [ToString](../../aspose.pdf.security/signaturealgorithminfo/tostring/)() | Converte o objeto de informações atual em sua representação de string. |

## Campos

| Nome | Descrição |
| --- | --- |
| readonly [AlgorithmType](../../aspose.pdf.security/signaturealgorithminfo/algorithmtype/) | Obtém o tipo do algoritmo de assinatura usado para assinar o documento PDF. |
| readonly [ContentHashAlgorithm](../../aspose.pdf.security/timestampalgorithminfo/contenthashalgorithm/) | Obtém o algoritmo de hash que hasheou o conteúdo do documento e, em seguida, o assinou usando [`DigestHashAlgorithm`](../signaturealgorithminfo/digesthashalgorithm/). |
| readonly [CryptographicStandard](../../aspose.pdf.security/signaturealgorithminfo/cryptographicstandard/) | Obtém o padrão criptográfico usado para assinar o documento PDF. |
| readonly [DigestHashAlgorithm](../../aspose.pdf.security/signaturealgorithminfo/digesthashalgorithm/) | Obtém o algoritmo de hash de digestão usado para a assinatura. Para um timestamp, este é o algoritmo de hash de digestão com o qual o hash do conteúdo do documento é assinado. |

### Veja Também

* classe [SignatureAlgorithmInfo](../signaturealgorithminfo/)
* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)