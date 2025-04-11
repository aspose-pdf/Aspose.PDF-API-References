---
title: Class TextStateOperator
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Operators.TextStateOperator. Classe base abstrata para operadores que alteram o estado atual do texto Tc Tf TL etc
type: docs
weight: 7930
url: /pt/net/aspose.pdf.operators/textstateoperator/
---
## Classe TextStateOperator

Classe base abstrata para operadores que alteram o estado atual do texto (Tc, Tf, TL, etc).

```csharp
public class TextStateOperator : TextOperator
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [TextStateOperator](textstateoperator/#constructor)() | Inicializa TextStateOperator. |
| [TextStateOperator](textstateoperator/#constructor_1)(TextProperties) | Inicializa TextStateOperator que permite passar TextProperties. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Índice do operador na lista de operadores da página. |

## Métodos

| Nome | Descrição |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/textoperator/accept/)(IOperatorSelector) | Aceita objeto visitante para processar o operador. |
| override [ToString](../../aspose.pdf/operator/tostring/)() | Retorna o texto do operador e seus parâmetros. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Compara esta instância com o objeto dado. |

### Veja Também

* classe [TextOperator](../textoperator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)