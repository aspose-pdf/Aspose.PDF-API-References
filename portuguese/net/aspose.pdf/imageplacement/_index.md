---
title: Class ImagePlacement
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.ImagePlacement. Representa características de uma imagem colocada na página do documento Pdf
type: docs
weight: 5900
url: /pt/net/aspose.pdf/imageplacement/
---
## Classe ImagePlacement

Representa características de uma imagem colocada na página do documento Pdf.

```csharp
public sealed class ImagePlacement
```

## Propriedades

| Nome | Descrição |
| --- | --- |
| [CompositingParameters](../../aspose.pdf/imageplacement/compositingparameters/) { get; } | Obtém os parâmetros de composição do estado gráfico ativo para a imagem colocada na página. |
| [Image](../../aspose.pdf/imageplacement/image/) { get; } | Obtém o objeto de recurso XImage relacionado. |
| [Matrix](../../aspose.pdf/imageplacement/matrix/) { get; } | Matriz de transformação atual para esta imagem. |
| [Operator](../../aspose.pdf/imageplacement/operator/) { get; } | Operador usado para exibir a imagem. |
| [Page](../../aspose.pdf/imageplacement/page/) { get; } | Obtém a página que contém a imagem. |
| [Rectangle](../../aspose.pdf/imageplacement/rectangle/) { get; } | Obtém o retângulo da Imagem. |
| [Resolution](../../aspose.pdf/imageplacement/resolution/) { get; } | Obtém a resolução da Imagem. |
| [Rotation](../../aspose.pdf/imageplacement/rotation/) { get; } | Obtém o ângulo de rotação da Imagem. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [Hide](../../aspose.pdf/imageplacement/hide/)() | Remove a imagem da página. |
| [Replace](../../aspose.pdf/imageplacement/replace/)(Stream) | Substitui a imagem na coleção por outra imagem. |
| [Save](../../aspose.pdf/imageplacement/save/#save)(Stream) | Salva a imagem com as transformações correspondentes: escalonamento, rotação e resolução. |
| [Save](../../aspose.pdf/imageplacement/save/#save_1)(Stream, ImageFormat) | Salva a imagem com as transformações correspondentes: escalonamento, rotação e resolução. |

## Observações

Quando uma imagem é colocada em uma página, ela pode ter dimensões diferentes das dimensões físicas definidas em [`Resources`](../resources/). O objeto `ImagePlacement` destina-se a fornecer informações como dimensões, resolução e assim por diante.

## Exemplos

O exemplo demonstra como encontrar imagens na primeira página do documento PDF e obter imagens como bitmaps com dimensões visíveis.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create ImagePlacementAbsorber object to perform image placement search
ImagePlacementAbsorber abs = new ImagePlacementAbsorber();

// Accept the absorber for first page
doc.Pages[1].Accept(abs);

// Retrieve images with visible dimensions
foreach (ImagePlacement imagePlacement in abs.ImagePlacements)
{
    Bitmap scaledImage;
    using (MemoryStream imageStream = new MemoryStream())
    {
        // Retrieve image from resources
        imagePlacement.Image.Save(imageStream, ImageFormat.Png);
        Bitmap resourceImage = (Bitmap) Bitmap.FromStream(imageStream);
        // Create new bitmap with actual dimensions
        scaledImage = new Bitmap(resourceImage, (int)imagePlacement.Rectangle.Width, (int)imagePlacement.Rectangle.Height);
    }
} 
```

### Veja Também

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)