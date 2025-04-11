---
title: Class SetColor
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Operators.SetColor. Representa a classe para o operador sc que define a cor para operações não de traço
type: docs
weight: 7630
url: /pt/net/aspose.pdf.operators/setcolor/
---
## Classe SetColor

Representa a classe para o operador sc (define a cor para operações não de traço).

```csharp
public class SetColor : BasicSetColorOperator
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [SetColor](setcolor/#constructor)() | Inicializa o operador. |
| [SetColor](setcolor/#constructor_1)(double) | Define a cor para operadores de traço para os espaços de cor DeviceGray, CalGray e Indexed. |
| [SetColor](setcolor/#constructor_4)(double[]) | Construtor que permite especificar os componentes de cor. |
| [SetColor](setcolor/#constructor_2)(double, double, double) | Define a cor para o operador de traço para os espaços de cor DeviceRGB, CalRGB e Lab. |
| [SetColor](setcolor/#constructor_3)(double, double, double, double) | Define a cor para o operador não de traço para o espaço de cor CMYK. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [B](../../aspose.pdf.operators/setcolor/b/) { get; set; } | Obtém ou define o componente azul. |
| [C](../../aspose.pdf.operators/setcolor/c/) { get; set; } | Obtém ou define o componente ciano. |
| virtual [Color](../../aspose.pdf.operators/basicsetcoloroperator/color/) { get; } | Obtém o array de componentes de cor. |
| [G](../../aspose.pdf.operators/setcolor/g/) { get; set; } | Obtém ou define o componente verde. |
| [Gray](../../aspose.pdf.operators/basicsetcoloroperator/gray/) { get; } | Obtém o componente preto da cor cinza. |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Índice do operador na lista de operadores da página. |
| [K](../../aspose.pdf.operators/setcolor/k/) { get; set; } | Obtém ou define o componente preto. |
| [M](../../aspose.pdf.operators/setcolor/m/) { get; set; } | Obtém ou define o componente magenta. |
| [R](../../aspose.pdf.operators/setcolor/r/) { get; set; } | Obtém ou define o componente vermelho. |
| [Y](../../aspose.pdf.operators/setcolor/y/) { get; set; } | Obtém ou define o componente amarelo. |

## Métodos

| Nome | Descrição |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/setcolor/accept/)(IOperatorSelector) | Aceita o objeto visitante para processar o operador. |
| override [getColor](../../aspose.pdf.operators/setcolor/getcolor/)() | Retorna a cor especificada pelo operador. |
| override [ToString](../../aspose.pdf.operators/setcolor/tostring/)() | Retorna a representação em string da cor. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Compara esta instância com o objeto fornecido. |

### Veja Também

* classe [BasicSetColorOperator](../basicsetcoloroperator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)