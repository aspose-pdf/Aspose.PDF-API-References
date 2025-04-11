---
title: OperatorCollection.Item
second_title: Aspose.PDF for .NET API Reference
description: Propriedade OperatorCollection. Obtém o operador pelo seu índice
type: docs
weight: 40
url: /pt/net/aspose.pdf/operatorcollection/item/
---
## Indexador OperatorCollection

Obtém o operador pelo seu índice.

```csharp
public override Operator this[int index] { get; set; }
```

| Parâmetro | Descrição |
| --- | --- |
| index | Índice do operador. A numeração começa a partir de 1. |

### Valor de Retorno

Operador do índice solicitado

## Exemplos

O exemplo demonstra como obter o operador do conteúdo da página pelo índice.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
Operator first = oc[1];
```

### Veja Também

* classe [Operator](../../operator/)
* classe [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)