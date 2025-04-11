---
title: Class BasicSetColorAndPatternOperator
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Operators.BasicSetColorAndPatternOperator. Operador base para todos os operadores de Definir Cor
type: docs
weight: 7150
url: /pt/net/aspose.pdf.operators/basicsetcolorandpatternoperator/
---
## Classe BasicSetColorAndPatternOperator

Operador base para todos os operadores de Definir Cor.

```csharp
public abstract class BasicSetColorAndPatternOperator : BasicSetColorOperator
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
| [PatternName](../../aspose.pdf.operators/basicsetcolorandpatternoperator/patternname/) { get; } | Obtém o Nome do Padrão. |
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

* classe [BasicSetColorOperator](../basicsetcoloroperator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)