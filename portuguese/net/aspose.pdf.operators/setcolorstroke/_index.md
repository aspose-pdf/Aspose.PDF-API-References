---
title: Class SetColorStroke
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Operators.SetColorStroke. Classe que representa o operador SC para definir a cor dos operadores de contorno.
type: docs
weight: 7680
url: /pt/net/aspose.pdf.operators/setcolorstroke/
---
## Classe SetColorStroke

Classe que representa o operador SC para definir a cor dos operadores de contorno.

```csharp
public class SetColorStroke : BasicSetColorOperator
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [SetColorStroke](setcolorstroke/#constructor)() | Inicializa o operador. |
| [SetColorStroke](setcolorstroke/#constructor_1)(double) | Define a cor para os operadores de contorno para os espaços de cores DeviceGray, CalGray e Indexed. |
| [SetColorStroke](setcolorstroke/#constructor_4)(double[]) | Construtor que permite definir os componentes de cor. |
| [SetColorStroke](setcolorstroke/#constructor_2)(double, double, double) | Define a cor para o operador de contorno para os espaços de cores DeviceRGB, CalRGB e Lab. |
| [SetColorStroke](setcolorstroke/#constructor_3)(double, double, double, double) | Define a cor para o operador de contorno para o espaço de cores CMYK. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [B](../../aspose.pdf.operators/setcolorstroke/b/) { get; set; } | Obtém ou define o componente azul. |
| [C](../../aspose.pdf.operators/setcolorstroke/c/) { get; set; } | Obtém ou define o componente ciano. |
| virtual [Color](../../aspose.pdf.operators/basicsetcoloroperator/color/) { get; } | Obtém o array de componentes de cor. |
| [G](../../aspose.pdf.operators/setcolorstroke/g/) { get; set; } | Obtém ou define o componente verde. |
| [Gray](../../aspose.pdf.operators/basicsetcoloroperator/gray/) { get; } | Obtém o componente preto da cor cinza. |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Índice do operador na lista de operadores da página. |
| [K](../../aspose.pdf.operators/setcolorstroke/k/) { get; set; } | Obtém ou define o componente preto. |
| [M](../../aspose.pdf.operators/setcolorstroke/m/) { get; set; } | Obtém ou define o componente magenta. |
| [R](../../aspose.pdf.operators/setcolorstroke/r/) { get; set; } | Obtém ou define o componente vermelho. |
| [Y](../../aspose.pdf.operators/setcolorstroke/y/) { get; set; } | Obtém ou define o componente amarelo. |

## Métodos

| Nome | Descrição |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/setcolorstroke/accept/)(IOperatorSelector) | Aceita o objeto visitante para processar o operador. |
| override [getColor](../../aspose.pdf.operators/setcolorstroke/getcolor/)() | Retorna a cor especificada pelo operador. |
| override [ToString](../../aspose.pdf/operator/tostring/)() | Retorna o texto do operador e seus parâmetros. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Compara esta instância com o objeto fornecido. |

### Veja Também

* classe [BasicSetColorOperator](../basicsetcoloroperator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)