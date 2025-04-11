---
title: Class Stamp
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Facades.Stamp. Classe representando um carimbo
type: docs
weight: 4720
url: /pt/net/aspose.pdf.facades/stamp/
---
## Classe Stamp

Classe representando um carimbo.

```csharp
public sealed class Stamp
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [Stamp](stamp/)() | O construtor padrão. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [BlendingSpace](../../aspose.pdf.facades/stamp/blendingspace/) { get; set; } | Obtém ou define um valor BlendingColorSpace que define um espaço de cor usado para realizar operações de transparência e mesclagem na página. |
| [IsBackground](../../aspose.pdf.facades/stamp/isbackground/) { get; set; } | Obtém ou define o status de fundo. Se verdadeiro, o carimbo será colocado como fundo da página carimbada. Por padrão, é definido como falso. |
| [Opacity](../../aspose.pdf.facades/stamp/opacity/) { get; set; } | Obtém ou define a opacidade do carimbo. |
| [PageNumber](../../aspose.pdf.facades/stamp/pagenumber/) { get; set; } | Obtém ou define o número da página. |
| [Pages](../../aspose.pdf.facades/stamp/pages/) { get; set; } | Obtém ou define um array com os números das páginas que serão afetadas pelo carimbo. Se Pages = null, todas as páginas do documento são afetadas. |
| [Quality](../../aspose.pdf.facades/stamp/quality/) { get; set; } | Obtém ou define a qualidade da imagem do carimbo em porcentagem. Valores válidos de 0 a 100%. |
| [Rotation](../../aspose.pdf.facades/stamp/rotation/) { get; set; } | Obtém ou define a rotação do carimbo em graus. |
| [StampId](../../aspose.pdf.facades/stamp/stampid/) { get; set; } | Obtém ou define o identificador do carimbo. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [BindImage](../../aspose.pdf.facades/stamp/bindimage/#bindimage)(Stream) | Define a imagem que será usada como carimbo. |
| [BindImage](../../aspose.pdf.facades/stamp/bindimage/#bindimage_1)(string) | Define a imagem como um carimbo. |
| [BindLogo](../../aspose.pdf.facades/stamp/bindlogo/)(FormattedText) | Define o texto como carimbo. |
| [BindPdf](../../aspose.pdf.facades/stamp/bindpdf/#bindpdf)(Stream, int) | Define o arquivo PDF e o número da página que será usado como carimbo. |
| [BindPdf](../../aspose.pdf.facades/stamp/bindpdf/#bindpdf_1)(string, int) | Define o arquivo PDF e o número da página que será usado como carimbo. |
| [BindTextState](../../aspose.pdf.facades/stamp/bindtextstate/)(TextState) | Define o estado do texto do carimbo. |
| [SetImageSize](../../aspose.pdf.facades/stamp/setimagesize/)(float, float) | Define o tamanho do carimbo de imagem. A imagem será escalada de acordo com os valores especificados. |
| [SetOrigin](../../aspose.pdf.facades/stamp/setorigin/)(float, float) | Define a posição na página onde o carimbo será colocado. |

### Veja Também

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)