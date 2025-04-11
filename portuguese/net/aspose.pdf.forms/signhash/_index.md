---
title: Delegate SignHash
second_title: Aspose.PDF for .NET API Reference
description: Delegado para assinar customizadamente o hash do documento
type: docs
weight: 5260
url: /pt/net/aspose.pdf.forms/signhash/
---
## Delegado SignHash

Delegado para assinar customizadamente o hash do documento.

```csharp
public delegate byte[] SignHash(byte[] hash, DigestHashAlgorithm digestHashAlgorithm);
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| hash | Byte[] | Hash de entrada do documento. |
| digestHashAlgorithm | DigestHashAlgorithm | O algoritmo de digestão usado para criar o hash. O valor nunca será igual a Auto. |

### Valor de Retorno

Assinatura de saída.

## Observações

Observe que, independentemente de a assinatura digital ser destacada ou não, o argumento hash será sempre o hash final a ser assinado.

### Veja Também

* enum [DigestHashAlgorithm](../../aspose.pdf/digesthashalgorithm/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)