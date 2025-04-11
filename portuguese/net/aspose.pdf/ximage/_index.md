---
title: Class XImage
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.XImage. Classe que representa o objeto de imagem X
type: docs
weight: 11350
url: /pt/net/aspose.pdf/ximage/
---
## Classe XImage

Classe que representa o objeto de imagem X.

```csharp
public sealed class XImage
```

## Propriedades

| Nome | Descrição |
| --- | --- |
| [ContainsTransparency](../../aspose.pdf/ximage/containstransparency/) { get; } | Se a imagem contém transparência, retorna verdadeiro; caso contrário, falso. |
| [FilterType](../../aspose.pdf/ximage/filtertype/) { get; } | Obtém o tipo de filtro da imagem. |
| [Grayscaled](../../aspose.pdf/ximage/grayscaled/) { get; } | Obtém a versão em escala de cinza da imagem. |
| [Height](../../aspose.pdf/ximage/height/) { get; } | Obtém a altura da imagem. |
| [ImageMask](../../aspose.pdf/ximage/imagemask/) { get; } | Obtém um sinalizador indicando se a imagem deve ser tratada como uma máscara de imagem (veja 8.9.6, "Imagens Mascaradas"). Se este sinalizador for verdadeiro, o valor de BitsPerComponent deve ser 1 e Mask e ColorSpace não devem ser especificados; áreas não mascaradas devem ser pintadas usando a cor não traçada atual. Valor padrão: falso. |
| [Metadata](../../aspose.pdf/ximage/metadata/) { get; } | Metadados da imagem. |
| [Name](../../aspose.pdf/ximage/name/) { get; set; } | Obtém ou define o nome da imagem. Observe que, se você alterar o nome da imagem que tem referências no conteúdo da página, o documento pode se tornar incorreto. Use o método XImage.Rename neste caso. |
| [Width](../../aspose.pdf/ximage/width/) { get; } | Obtém a largura da imagem. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [AddStencilMask](../../aspose.pdf/ximage/addstencilmask/)(Stream) | Adiciona uma máscara de estêncil ao XImage. |
| [GetColorType](../../aspose.pdf/ximage/getcolortype/)() | Retorna o tipo de cor da imagem. |
| [GetNameInCollection](../../aspose.pdf/ximage/getnameincollection/)() | Retorna o nome da imagem em sua coleção. |
| [GetRawImageData](../../aspose.pdf/ximage/getrawimagedata/)() | Recupera os dados brutos da imagem da imagem de origem. |
| [IsTheSameObject](../../aspose.pdf/ximage/isthesameobject/)(XImage) | Retorna verdadeiro se ambas as imagens referenciam o mesmo objeto. |
| [Rename](../../aspose.pdf/ximage/rename/)(string) | Renomeia a imagem e substitui todas as referências à imagem pelo novo nome. |
| [Save](../../aspose.pdf/ximage/save/#save)(Stream) | Salva os dados da imagem no stream como uma imagem JPEG. |
| [Save](../../aspose.pdf/ximage/save/#save_2)(Stream, ImageFormat) | Salva a imagem no stream com o formato solicitado. |
| [Save](../../aspose.pdf/ximage/save/#save_1)(Stream, int) | Salva os dados da imagem no stream como uma imagem JPEG com a resolução especificada. |
| [Save](../../aspose.pdf/ximage/save/#save_3)(Stream, ImageFormat, int) | Salva a imagem no stream com o formato solicitado e com a resolução especificada. |
| [ToStream](../../aspose.pdf/ximage/tostream/)() | Retorna o stream da imagem original. |
| static [DetectColorType](../../aspose.pdf/ximage/detectcolortype/)(Bitmap) |  |

### Veja Também

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)