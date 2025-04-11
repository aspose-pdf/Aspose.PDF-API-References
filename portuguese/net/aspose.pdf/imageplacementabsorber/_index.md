---
title: Class ImagePlacementAbsorber
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.ImagePlacementAbsorber. Representa um objeto absorvedor de objetos de colocação de imagem. Realiza a busca de usos de imagem e fornece acesso aos resultados da busca através da coleção ImagePlacements
type: docs
weight: 5910
url: /pt/net/aspose.pdf/imageplacementabsorber/
---
## Classe ImagePlacementAbsorber

Representa um objeto absorvedor de objetos de colocação de imagem. Realiza a busca de usos de imagem e fornece acesso aos resultados da busca através da coleção [`ImagePlacements`](./imageplacements/).

```csharp
public sealed class ImagePlacementAbsorber
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [ImagePlacementAbsorber](imageplacementabsorber/)() | O construtor padrão. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [ImagePlacements](../../aspose.pdf/imageplacementabsorber/imageplacements/) { get; } | Obtém a coleção de ocorrências de colocação de imagem que são apresentadas com objetos [`ImagePlacement`](../imageplacement/). |
| [IsReadOnlyMode](../../aspose.pdf/imageplacementabsorber/isreadonlymode/) { get; set; } | Obtém/define o modo somente leitura para a coleção de operações de análise. Pode ajudar contra exceções de falta de memória. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [Visit](../../aspose.pdf/imageplacementabsorber/visit/#visit)(Document) | Realiza a busca no documento especificado. |
| [Visit](../../aspose.pdf/imageplacementabsorber/visit/#visit_1)(Page) | Realiza a busca na página especificada. |

## Observações

O objeto `ImagePlacementAbsorber` é basicamente usado em cenários de busca de imagens. Quando a busca é concluída, as ocorrências são representadas com objetos [`ImagePlacement`](../imageplacement/) que a coleção [`ImagePlacements`](./imageplacements/) contém. O objeto [`ImagePlacement`](../imageplacement/) fornece acesso às propriedades de colocação da imagem: dimensões, resolução, etc. A rotação positiva da imagem é anti-horária, para a página, é horária. Aqui, precisamos representar o ângulo de rotação da imagem, então subtraímos o ângulo da página do ângulo da imagem.

## Exemplos

O exemplo demonstra como encontrar imagens na primeira página do documento PDF e obter as propriedades de colocação da imagem.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create ImagePlacementAbsorber object to perform image placement search
ImagePlacementAbsorber abs = new ImagePlacementAbsorber();

// Accept the absorber for first page
doc.Pages[1].Accept(abs);

// Display image placement properties for all placements
foreach (ImagePlacement imagePlacement in abs.ImagePlacements)
{     
    Console.Out.WriteLine("image width:" + imagePlacement.Rectangle.Width);
    Console.Out.WriteLine("image height:" + imagePlacement.Rectangle.Height);
    Console.Out.WriteLine("image LLX:" + imagePlacement.Rectangle.LLX);
    Console.Out.WriteLine("image LLY:" + imagePlacement.Rectangle.LLY);
    Console.Out.WriteLine("image horizontal resolution:" + imagePlacement.Resolution.X);
    Console.Out.WriteLine("image vertical resolution:" + imagePlacement.Resolution.Y);
}
```

### Veja Também

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)