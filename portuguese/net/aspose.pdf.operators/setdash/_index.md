---
title: Class SetDash
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Operators.SetDash. Classe que representa o operador d para definir o padrão de traço de linha
type: docs
weight: 7690
url: /pt/net/aspose.pdf.operators/setdash/
---
## Classe SetDash

Classe que representa o operador d (define o padrão de traço de linha).

```csharp
public class SetDash : Operator
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [SetDash](setdash/)(int[], int) | Cria o operador de padrão de traço definido. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Índice do operador na lista de operadores da página. |
| [Pattern](../../aspose.pdf.operators/setdash/pattern/) { get; set; } | Padrão de traço. Os elementos do array devem ser números que especificam os comprimentos de traços e lacunas alternados. No caso de um array de um elemento, os comprimentos de traço e lacuna são iguais. |
| [Phase](../../aspose.pdf.operators/setdash/phase/) { get; set; } | Fase do traço. Antes de começar a traçar um caminho, o array de traços deve ser percorrido, somando os comprimentos de traços e lacunas. Quando o comprimento acumulado iguala o valor especificado pela fase do traço, o traçado do caminho deve começar, e o array de traços deve ser usado ciclicamente a partir desse ponto. |

## Métodos

| Nome | Descrição |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/setdash/accept/)(IOperatorSelector) | Aceita o objeto visitante para processar o operador. |
| override [ToString](../../aspose.pdf.operators/setdash/tostring/)() | Obtém a representação em string do operador. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Compara esta instância com o objeto dado. |

### Veja Também

* classe [Operator](../../aspose.pdf/operator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)