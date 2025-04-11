---
title: OutputIntents.Item
second_title: Aspose.PDF for .NET API Reference
description: Propriedade OutputIntents. Obtém a intenção de saída no índice especificado
type: docs
weight: 30
url: /pt/net/aspose.pdf/outputintents/item/
---
## Indexador OutputIntents

Obtém a intenção de saída no *índice* especificado.

```csharp
public OutputIntent this[int index] { get; }
```

| Parâmetro | Descrição |
| --- | --- |
| index | O índice baseado em zero da intenção de saída a ser obtida. |

### Valor de Retorno

A intenção de saída no *índice* especificado.

### Exceções

| exceção | condição |
| --- | --- |
| ArgumentOutOfRangeException | *index* é menor que 0 ou *index* é igual ou maior que [`Count`](../count/). |
| InvalidOperationException | O documento que contém a coleção não tem catálogo para acessar as Intenções de Saída. |

### Veja Também

* classe [OutputIntent](../../outputintent/)
* classe [OutputIntents](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)