---
title: Class SubPath
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Vector.SubPath. Representa um objeto gráfico vetorial na página. Basicamente, os objetos gráficos vetoriais são representados por dois grupos de SubPaths. Um deles é representado por um conjunto de linhas e curvas. Outros são apresentados como retângulos e podem às vezes ser confundidos. Normalmente, é uma área retangular que tem uma cor, mas muito frequentemente esse retângulo é colocado no início da página e define todo o espaço da página em branco. Assim, você obtém o SubPath, mas visualmente você só vê o texto na página.
type: docs
weight: 11220
url: /pt/net/aspose.pdf.vector/subpath/
---
## Classe SubPath

Representa um objeto gráfico vetorial na página. Basicamente, os objetos gráficos vetoriais são representados por dois grupos de SubPaths. Um deles é representado por um conjunto de linhas e curvas. Outros são apresentados como retângulos e podem às vezes ser confundidos. Normalmente, é uma área retangular que tem uma cor, mas muito frequentemente esse retângulo é colocado no início da página e define todo o espaço da página em branco. Assim, você obtém o SubPath, mas visualmente você só vê o texto na página.

```csharp
public sealed class SubPath : GraphicElement
```

## Propriedades

| Nome | Descrição |
| --- | --- |
| [Matrix](../../aspose.pdf.vector/graphicelement/matrix/) { get; } | Obtém a matriz do elemento gráfico. A matriz é definida quando o elemento é criado. Ela muda quando SetPosition() é chamada. |
| [Operators](../../aspose.pdf.vector/graphicelement/operators/) { get; } | Obtém uma coleção de operadores representando o elemento. |
| [Parent](../../aspose.pdf.vector/graphicelement/parent/) { get; } | Obtém o atual [`XFormPlacement`](../xformplacement/) no qual o elemento está localizado. |
| virtual [Position](../../aspose.pdf.vector/graphicelement/position/) { get; set; } | Obtém ou define a posição no espaço de coordenadas atual. Se [`Parent`](../graphicelement/parent/) não for !:null, então o elemento tem espaço de coordenadas xForm. |
| override [Rectangle](../../aspose.pdf.vector/subpath/rectangle/) { get; } |  |
| [SourcePage](../../aspose.pdf.vector/graphicelement/sourcepage/) { get; } | Obtém a página da qual o elemento gráfico é extraído. |

## Métodos

| Nome | Descrição |
| --- | --- |
| virtual [AddOnPage](../../aspose.pdf.vector/graphicelement/addonpage/)(Page) | Adiciona o elemento atual na página. Se houver muitos elementos para adicionar, é melhor usar [`AddGraphics`](../../aspose.pdf/page/addgraphics/). |
| [Dispose](../../aspose.pdf.vector/graphicelement/dispose/)() | Libera todos os recursos usados pela classe [`GraphicElement`](../graphicelement/). |
| [Remove](../../aspose.pdf.vector/graphicelement/remove/)() | Remove o elemento atual da página. Se houver muitos elementos para remover, é melhor usar [`DeleteGraphics`](../../aspose.pdf/page/deletegraphics/). |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)() | Converte o elemento em uma única imagem SVG. |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)(string) | Converte o elemento em um único arquivo de imagem SVG. |

### Veja Também

* classe [GraphicElement](../graphicelement/)
* namespace [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../)