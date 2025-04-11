---
title: Class GraphicElement
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Vector.GraphicElement. Representa a classe base para objetos gráficos na página
type: docs
weight: 11180
url: /pt/net/aspose.pdf.vector/graphicelement/
---
## Classe GraphicElement

Representa a classe base para objetos gráficos na página.

```csharp
public abstract class GraphicElement : IDisposable
```

## Propriedades

| Nome | Descrição |
| --- | --- |
| [Matrix](../../aspose.pdf.vector/graphicelement/matrix/) { get; } | Obtém a matriz do elemento gráfico. A matriz é definida quando o elemento é criado. Ela muda quando SetPosition() é chamada. |
| [Operators](../../aspose.pdf.vector/graphicelement/operators/) { get; } | Obtém uma coleção de operadores representando o elemento. |
| [Parent](../../aspose.pdf.vector/graphicelement/parent/) { get; } | Obtém o atual [`XFormPlacement`](../xformplacement/) no qual o elemento está localizado. |
| virtual [Position](../../aspose.pdf.vector/graphicelement/position/) { get; set; } | Obtém ou define a posição no espaço de coordenadas atual. Se [`Parent`](./parent/) não for !:null, então o elemento tem espaço de coordenadas xForm. |
| abstract [Rectangle](../../aspose.pdf.vector/graphicelement/rectangle/) { get; } | Obtém o retângulo delimitador do `GraphicElement`. |
| [SourcePage](../../aspose.pdf.vector/graphicelement/sourcepage/) { get; } | Obtém a página da qual o elemento gráfico é extraído. |

## Métodos

| Nome | Descrição |
| --- | --- |
| virtual [AddOnPage](../../aspose.pdf.vector/graphicelement/addonpage/)(Page) | Adiciona o elemento atual na página. Se houver muitos elementos para adicionar, é melhor usar [`AddGraphics`](../../aspose.pdf/page/addgraphics/). |
| [Dispose](../../aspose.pdf.vector/graphicelement/dispose/)() | Libera todos os recursos usados pela classe `GraphicElement`. |
| [Remove](../../aspose.pdf.vector/graphicelement/remove/)() | Remove o elemento atual da página. Se houver muitos elementos para remover, é melhor usar [`DeleteGraphics`](../../aspose.pdf/page/deletegraphics/). |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/#savetosvg)() | Converte o elemento em uma única imagem SVG. |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/#savetosvg_1)(string) | Converte o elemento em um único arquivo de imagem SVG. |

### Veja Também

* namespace [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../)