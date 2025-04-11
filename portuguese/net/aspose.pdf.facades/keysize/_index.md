---
title: Enum KeySize
second_title: Aspose.PDF for .NET API Reference
description: Enum KeySize do Aspose.Pdf.Facades. Define diferentes tamanhos de chave que podem ser usados para criptografar documentos pdf
type: docs
weight: 4390
url: /pt/net/aspose.pdf.facades/keysize/
---
## Enumeração KeySize

Define diferentes tamanhos de chave que podem ser usados para criptografar documentos pdf.

```csharp
public enum KeySize
```

### Valores

| Nome | Valor | Descrição |
| --- | --- | --- |
| x40 | `0` | Chave de 40 bits. Tal tamanho de chave é usado com o algoritmo RC4 e fornece um baixo nível de segurança. No entanto, versões antigas de documentos pdf podem ser criptografadas apenas com tais chaves (v. 1.3 e inferiores); |
| x128 | `1` | Chave de 128 bits. Tanto os algoritmos RC4 quanto AES podem usar tal tamanho de chave. |
| x256 | `2` | Chave de 256 bits. Tal tamanho de chave pode ser usado apenas com AES e é reconhecido nas últimas versões do Adobe Reader (a partir da v.9). |

### Veja Também

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)