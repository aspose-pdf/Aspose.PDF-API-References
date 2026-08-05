---
title: "ImageCompressionOptions"
second_title: "Aspose.PDF para Python via .NET Referência da API"
description: "Classe contém conjunto de opções para compressão de imagem."
type: docs
weight: 10
url: /pt/python-net/aspose.pdf.optimization/imagecompressionoptions/
---

## ImageCompressionOptions class

Classe contém conjunto de opções para compressão de imagem.

O tipo ImageCompressionOptions expõe os seguintes membros:
## Construtores
| Nome | Descrição |
| :- | :- |
| ImageCompressionOptions() | Inicializa uma nova instância da classe ImageCompressionOptions |
## Propriedades
| Nome | Descrição |
| :- | :- |
| compress_images | Se esta flag estiver definida como true, as imagens serão comprimidas no documento. O nível de compressão é especificado com a propriedade ImageQuality. |
| resize_images | Se esta flag estiver definida como true e CompressImages for true, as imagens serão redimensionadas se a resolução da imagem for maior que o parâmetro MaxResolution especificado. |
| image_quality | Especifica o nível de compressão de imagem quando a flag CompressIamges é usada. |
| max_resolution | Especifica a resolução máxima das imagens. Se a imagem tiver resolução maior, ela será redimensionada. |
| version | Versão do algoritmo de compressão. Valores possíveis são: 1. compressão padrão, 2. fast (compressão aprimorada que é mais rápida que a padrão, mas pode não ser aplicável a todas as imagens), 3. mixed (compressão padrão é aplicada a imagens que não podem ser comprimidas por um algoritmo mais rápido, isso pode proporcionar a melhor compressão, porém mais lenta que o algoritmo \"fast\". A versão \"Fast\" não é aplicável ao redimensionamento de imagens (o método padrão será usado). O padrão é \"Standard\".) |
| codificação | Obtém ou define a codificação usada para armazenar imagens. |

### Veja Também

* namespace [aspose.pdf.optimization](/pdf/python-net/aspose.pdf.optimization/)
* assembly [Aspose.PDF](/pdf/python-net/)

