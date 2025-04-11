---
title: Class ThumbnailDevice
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Devices.ThumbnailDevice. Representa um dispositivo de imagem que salva páginas de documentos PDF em imagens de miniatura
type: docs
weight: 3690
url: /pt/net/aspose.pdf.devices/thumbnaildevice/
---
## Classe ThumbnailDevice

Representa um dispositivo de imagem que salva páginas de documentos PDF em imagens de miniatura.

```csharp
public sealed class ThumbnailDevice : ImageDevice
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [ThumbnailDevice](thumbnaildevice/#constructor)() | Inicializa uma nova instância da classe `ThumbnailDevice` com o tamanho padrão da imagem de miniatura (200x200 pixels). |
| [ThumbnailDevice](thumbnaildevice/#constructor_1)(int, int) | Inicializa uma nova instância da classe `ThumbnailDevice`. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype/) { get; set; } | Obtém ou define o tipo de coordenada da página (caixas Media/Crop). O valor CropBox é usado por padrão. |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode/) { get; set; } | Obtém ou define o modo de apresentação do formulário. |
| [Height](../../aspose.pdf.devices/imagedevice/height/) { get; } | Obtém a altura da imagem de saída. |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions/) { get; set; } | Obtém ou define as opções de renderização. |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution/) { get; } | Obtém a resolução da imagem. |
| [Width](../../aspose.pdf.devices/imagedevice/width/) { get; } | Obtém a largura da imagem de saída. |

## Métodos

| Nome | Descrição |
| --- | --- |
| override [Process](../../aspose.pdf.devices/thumbnaildevice/process/#process)(Page, Stream) | Converte a página em uma imagem de miniatura png e a salva no fluxo de saída. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Realiza alguma operação na página dada e salva os resultados no arquivo. |

### Veja Também

* classe [ImageDevice](../imagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)