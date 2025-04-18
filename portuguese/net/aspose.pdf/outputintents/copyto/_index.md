---
title: OutputIntents.CopyTo
second_title: Aspose.PDF for .NET API Reference
description: Método OutputIntents. Copia os elementos da coleção para o array, começando no arrayIndex particular no array
type: docs
weight: 70
url: /pt/net/aspose.pdf/outputintents/copyto/
---
## Método OutputIntents.CopyTo

Copia os elementos da coleção para o *array*, começando no *arrayIndex* particular no array.

```csharp
public void CopyTo(OutputIntent[] array, int arrayIndex)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| array | OutputIntent[] | O array unidimensional que é o destino dos intents de saída copiados da coleção. O array deve ter indexação baseada em zero. |
| arrayIndex | Int32 | O índice baseado em zero em *array* onde a cópia começa. |

### Exceções

| exceção | condição |
| --- | --- |
| ArgumentNullException | *array* é nulo. |
| ArgumentOutOfRangeException | *arrayIndex* é menor que 0. |
| ArgumentException | O número de elementos na fonte [`OutputIntents`](../) é maior do que o espaço disponível de *arrayIndex* até o final do *array* de destino. |

### Veja Também

* classe [OutputIntent](../../outputintent/)
* classe [OutputIntents](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)