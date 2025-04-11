---
title: Class ImageDevice
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Devices.ImageDevice. Uma classe abstrata para dispositivos de imagem
type: docs
weight: 3610
url: /pt/net/aspose.pdf.devices/imagedevice/
---
## Classe ImageDevice

Uma classe abstrata para dispositivos de imagem.

```csharp
public abstract class ImageDevice : PageDevice
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [ImageDevice](imagedevice/#constructor)() | Inicializador abstrato para descendentes de `ImageDevice`, define a resolução para 150x150. |
| [ImageDevice](imagedevice/#constructor_2)(PageSize) | Inicializa uma nova instância da classe [`JpegDevice`](../jpegdevice/) com as dimensões da imagem fornecidas e resolução padrão (=150). |
| [ImageDevice](imagedevice/#constructor_1)(Resolution) | Inicializador abstrato para descendentes de `ImageDevice`. Resolução para o arquivo de imagem resultante, veja a classe [`Resolution`](./resolution/). |
| [ImageDevice](imagedevice/#constructor_4)(int, int) | Inicializa uma nova instância da classe [`JpegDevice`](../jpegdevice/) com as dimensões da imagem fornecidas e resolução padrão (=150). |
| [ImageDevice](imagedevice/#constructor_3)(PageSize, Resolution) | Inicializa uma nova instância da classe [`JpegDevice`](../jpegdevice/) com as dimensões da imagem fornecidas e resolução. |
| [ImageDevice](imagedevice/#constructor_5)(int, int, Resolution) | Inicializa uma nova instância da classe [`JpegDevice`](../jpegdevice/) com as dimensões da imagem fornecidas e resolução. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype/) { get; set; } | Obtém ou define o tipo de coordenada da página (caixas Media/Crop). O valor CropBox é usado por padrão. |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode/) { get; set; } | Obtém ou define o modo de apresentação do formulário. |
| [Height](../../aspose.pdf.devices/imagedevice/height/) { get; } | Obtém a altura da saída da imagem. |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions/) { get; set; } | Obtém ou define as opções de renderização. |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution/) { get; } | Obtém a resolução da imagem. |
| [Width](../../aspose.pdf.devices/imagedevice/width/) { get; } | Obtém a largura da saída da imagem. |

## Métodos

| Nome | Descrição |
| --- | --- |
| abstract [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, Stream) | Realiza alguma operação na página dada, por exemplo, converte a página em uma imagem gráfica. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Realiza alguma operação na página dada e salva os resultados no arquivo. |

### Veja Também

* classe [PageDevice](../pagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)