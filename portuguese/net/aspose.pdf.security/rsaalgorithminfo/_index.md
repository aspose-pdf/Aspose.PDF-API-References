---
title: Class RsaAlgorithmInfo
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Security.RsaAlgorithmInfo. Representa uma classe para as informações sobre o algoritmo de assinatura RSA
type: docs
weight: 9990
url: /pt/net/aspose.pdf.security/rsaalgorithminfo/
---
## Classe RsaAlgorithmInfo

Representa uma classe para as informações sobre o algoritmo de assinatura RSA.

```csharp
public sealed class RsaAlgorithmInfo : KeyedSignatureAlgorithmInfo
```

## Propriedades

| Nome | Descrição |
| --- | --- |
| [SignatureName](../../aspose.pdf.security/signaturealgorithminfo/signaturename/) { get; } | Obtém o nome do campo de assinatura. |

## Métodos

| Nome | Descrição |
| --- | --- |
| override [ToString](../../aspose.pdf.security/signaturealgorithminfo/tostring/)() | Converte o objeto de informações atual em sua representação em string. |

## Campos

| Nome | Descrição |
| --- | --- |
| readonly [AlgorithmType](../../aspose.pdf.security/signaturealgorithminfo/algorithmtype/) | Obtém o tipo do algoritmo de assinatura usado para assinar o documento PDF. |
| readonly [CryptographicStandard](../../aspose.pdf.security/signaturealgorithminfo/cryptographicstandard/) | Obtém o padrão criptográfico usado para assinar o documento PDF. |
| readonly [DigestHashAlgorithm](../../aspose.pdf.security/signaturealgorithminfo/digesthashalgorithm/) | Obtém o algoritmo de hash de digestão usado para a assinatura. Para um timestamp, este é o algoritmo de hash de digestão com o qual o hash do conteúdo do documento é assinado. |
| readonly [KeySize](../../aspose.pdf.security/keyedsignaturealgorithminfo/keysize/) | Obtém o tamanho da chave criptográfica usada pelo algoritmo de assinatura. |

### Veja Também

* classe [KeyedSignatureAlgorithmInfo](../keyedsignaturealgorithminfo/)
* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)