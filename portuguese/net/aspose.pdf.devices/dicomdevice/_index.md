---
title: Class DicomDevice
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Devices.DicomDevice. Representa um dispositivo de imagem que ajuda a salvar páginas de documentos PDF no formato Dicom
type: docs
weight: 3560
url: /pt/net/aspose.pdf.devices/dicomdevice/
---
## Classe DicomDevice

Representa um dispositivo de imagem que ajuda a salvar páginas de documentos PDF no formato Dicom.

```csharp
public sealed class DicomDevice : ImageDevice
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [DicomDevice](dicomdevice/#constructor)() | Inicializa uma nova instância da classe `DicomDevice` com resolução padrão. |
| [DicomDevice](dicomdevice/#constructor_2)(PageSize) | Inicializa uma nova instância da classe `DicomDevice` com o tamanho de página fornecido, com resolução padrão (=150). |
| [DicomDevice](dicomdevice/#constructor_1)(Resolution) | Inicializa uma nova instância da classe `DicomDevice`. Resolução para o arquivo de imagem resultante, veja a classe [`Resolution`](../resolution/). |
| [DicomDevice](dicomdevice/#constructor_4)(int, int) | Inicializa uma nova instância da classe `DicomDevice` com as dimensões da imagem fornecidas, com resolução padrão (=150). |
| [DicomDevice](dicomdevice/#constructor_3)(PageSize, Resolution) | Inicializa uma nova instância da classe `DicomDevice` com o tamanho de página e a resolução fornecidos. |
| [DicomDevice](dicomdevice/#constructor_5)(int, int, Resolution) | Inicializa uma nova instância da classe `DicomDevice` com as dimensões da imagem e a resolução fornecidas. |

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
| override [Process](../../aspose.pdf.devices/dicomdevice/process/#process)(Page, Stream) | Converte a página em Dicom e a salva no fluxo de saída. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Realiza alguma operação na página dada e salva os resultados no arquivo. |

### Veja Também

* classe [ImageDevice](../imagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)