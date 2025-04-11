---
title: Class BasicSetColorOperator
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Operators.BasicSetColorOperator. Classe base para operadores de definição de cor
type: docs
weight: 7160
url: /pt/net/aspose.pdf.operators/basicsetcoloroperator/
---
## Classe BasicSetColorOperator

Classe base para operadores de definição de cor.

```csharp
public abstract class BasicSetColorOperator : SetColorOperator
```

## Propriedades

| Nome | Descrição |
| --- | --- |
| [B](../../aspose.pdf.operators/basicsetcoloroperator/b/) { get; } | Obtém o componente vermelho da cor |
| [C](../../aspose.pdf.operators/basicsetcoloroperator/c/) { get; } | Obtém o componente ciano da cor CMYK. |
| virtual [Color](../../aspose.pdf.operators/basicsetcoloroperator/color/) { get; } | Obtém o array de componentes de cor. |
| [G](../../aspose.pdf.operators/basicsetcoloroperator/g/) { get; } | Obtém o componente verde da cor |
| [Gray](../../aspose.pdf.operators/basicsetcoloroperator/gray/) { get; } | Obtém o componente preto da cor cinza. |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Índice do operador na lista de operadores da página. |
| [K](../../aspose.pdf.operators/basicsetcoloroperator/k/) { get; } | Obtém o componente preto da cor CMYK. |
| [M](../../aspose.pdf.operators/basicsetcoloroperator/m/) { get; } | Obtém o componente magenta da cor CMYK. |
| [R](../../aspose.pdf.operators/basicsetcoloroperator/r/) { get; } | Obtém o componente vermelho da cor |
| [Y](../../aspose.pdf.operators/basicsetcoloroperator/y/) { get; } | Obtém o componente amarelo da cor CMYK. |

## Métodos

| Nome | Descrição |
| --- | --- |
| abstract [Accept](../../aspose.pdf/operator/accept/)(IOperatorSelector) | Aceita o visitante IOperatorSelector que fornece o processamento de operadores. |
| abstract [getColor](../../aspose.pdf.operators/setcoloroperator/getcolor/)() | Retorna a cor especificada pelo operador. |
| override [ToString](../../aspose.pdf/operator/tostring/)() | Retorna o texto do operador e seus parâmetros. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Compara esta instância com o objeto fornecido. |

### Veja Também

* classe [SetColorOperator](../setcoloroperator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)