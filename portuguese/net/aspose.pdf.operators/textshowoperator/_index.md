---
title: Class TextShowOperator
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Operators.TextShowOperator. Classe base abstrata para todos os operadores que usam para exibir texto Tj TJ etc
type: docs
weight: 7920
url: /pt/net/aspose.pdf.operators/textshowoperator/
---
## Classe TextShowOperator

Classe base abstrata para todos os operadores que usam para exibir texto (Tj, TJ, etc).

```csharp
public class TextShowOperator : TextOperator
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [TextShowOperator](textshowoperator/#constructor)() | Inicializa TextShowOperator. |
| [TextShowOperator](textshowoperator/#constructor_1)(TextProperties) | Inicializa TextShowOperator que permite passar TextProperties. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Índice do operador na lista de operadores da página. |
| virtual [Text](../../aspose.pdf.operators/textshowoperator/text/) { get; set; } | Obtém o texto que o operador exibe na página. |

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