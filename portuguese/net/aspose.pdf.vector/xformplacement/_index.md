---
title: Class XFormPlacement
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Vector.XFormPlacement. Representa a colocação do XForm. Se o XForm for exibido na página mais de 1 vez, todas as XformPlacements associadas a este XForm terão elementos gráficos comuns, mas estados gráficos diferentes.
type: docs
weight: 11260
url: /pt/net/aspose.pdf.vector/xformplacement/
---
## Classe XFormPlacement

Representa a colocação do XForm. Se o XForm for exibido na página mais de 1 vez, todas as XformPlacements associadas a este XForm terão elementos gráficos comuns, mas estados gráficos diferentes.

```csharp
public sealed class XFormPlacement : GraphicElement
```

## Propriedades

| Nome | Descrição |
| --- | --- |
| [Elements](../../aspose.pdf.vector/xformplacement/elements/) { get; } | Obtém elementos gráficos dentro deste XForm. |
| [Matrix](../../aspose.pdf.vector/graphicelement/matrix/) { get; } | Obtém a matriz do elemento gráfico. A matriz é definida quando o elemento é criado. Ela muda quando SetPosition() é chamada. |
| [Name](../../aspose.pdf.vector/xformplacement/name/) { get; } | Obtém o nome do XForm. |
| [Operators](../../aspose.pdf.vector/graphicelement/operators/) { get; } | Obtém uma coleção de operadores representando o elemento. |
| [Parent](../../aspose.pdf.vector/graphicelement/parent/) { get; } | Obtém o atual `XFormPlacement` no qual o elemento está localizado. |
| override [Position](../../aspose.pdf.vector/xformplacement/position/) { set; } |  |
| override [Rectangle](../../aspose.pdf.vector/xformplacement/rectangle/) { get; } |  |
| [SourcePage](../../aspose.pdf.vector/graphicelement/sourcepage/) { get; } | Obtém a página da qual o elemento gráfico é extraído. |
| [XForm](../../aspose.pdf.vector/xformplacement/xform/) { get; } | Obtém o XForm associado a este XFormPlacement. |

## Métodos

| Nome | Descrição |
| --- | --- |
| override [AddOnPage](../../aspose.pdf.vector/xformplacement/addonpage/)(Page) | Adiciona o elemento atual na página. Se houver muitos elementos para adicionar, é melhor usar [`AddGraphics`](../../aspose.pdf/page/addgraphics/). |
| [Dispose](../../aspose.pdf.vector/graphicelement/dispose/)() | Libera todos os recursos usados pela classe [`GraphicElement`](../graphicelement/). |
| [Remove](../../aspose.pdf.vector/graphicelement/remove/)() | Remove o elemento atual da página. Se houver muitos elementos para remover, é melhor usar [`DeleteGraphics`](../../aspose.pdf/page/deletegraphics/). |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)() | Converte o elemento em uma única imagem SVG. |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)(string) | Converte o elemento em um único arquivo de imagem SVG. |

### Veja Também

* classe [GraphicElement](../graphicelement/)
* namespace [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../)