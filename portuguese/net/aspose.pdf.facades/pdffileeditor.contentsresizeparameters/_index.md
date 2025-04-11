---
title: Class PdfFileEditor.ContentsResizeParameters
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Facades.PdfFileEditorContentsResizeParameters. Classe para especificar parâmetros de redimensionamento de página. Permite definir os seguintes parâmetros: Tamanho da página resultante (largura, altura) em unidades de espaço padrão ou em porcentagens do tamanho das páginas iniciais; Margens Esquerda, Superior, Inferior e Direita em unidades de espaço padrão ou em porcentagens do tamanho da página inicial; Alguns valores podem ser deixados nulos para cálculo automático. Esses valores serão calculados a partir do restante do tamanho da página após o cálculo dos valores explicitamente especificados. Por exemplo, se a largura da página = 100 e a nova largura da página especificada for 60 unidades, então as margens esquerda e direita são calculadas automaticamente: (100 - 60) / 2 = 15. Esta classe é usada no método ResizeContents.
type: docs
weight: 4480
url: /pt/net/aspose.pdf.facades/pdffileeditor.contentsresizeparameters/
---
## Classe PdfFileEditor.ContentsResizeParameters

Classe para especificar parâmetros de redimensionamento de página. Permite definir os seguintes parâmetros: Tamanho da página resultante (largura, altura) em unidades de espaço padrão ou em porcentagens do tamanho das páginas iniciais; Margens Esquerda, Superior, Inferior e Direita em unidades de espaço padrão ou em porcentagens do tamanho da página inicial; Alguns valores podem ser deixados nulos para cálculo automático. Esses valores serão calculados a partir do restante do tamanho da página após o cálculo dos valores explicitamente especificados. Por exemplo: se a largura da página = 100 e a nova largura da página especificada for 60 unidades, então as margens esquerda e direita são calculadas automaticamente: (100 - 60) / 2 = 15. Esta classe é usada no método ResizeContents.

```csharp
public class ContentsResizeParameters
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [ContentsResizeParameters](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/.ctor#constructor)() | Cria parâmetros de redimensionamento onde todos os valores são definidos como "auto". Mais tarde, as margens e o tamanho do conteúdo podem ser especificados, se necessário. |
| [ContentsResizeParameters](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/.ctor#constructor_1)(ContentsResizeValue, ContentsResizeValue, ContentsResizeValue, ContentsResizeValue, ContentsResizeValue, ContentsResizeValue) | Cria parâmetros de redimensionamento com valores de margem e tamanho de conteúdo especificados. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [BottomMargin](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/bottommargin) { get; set; } | Obtém ou define a margem inferior na página resultante. |
| [ContentsHeight](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentsheight) { get; set; } | Obtém ou define a altura do conteúdo da página de origem na página resultante. |
| [ContentsWidth](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentswidth) { get; set; } | Obtém ou define a largura do conteúdo da página de origem na página resultante. |
| [LeftMargin](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/leftmargin) { get; set; } | Obtém ou define a margem esquerda na página resultante. |
| [RightMargin](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/rightmargin) { get; set; } | Obtém ou define a margem direita na página resultante. |
| [TopMargin](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/topmargin) { get; set; } | Obtém ou define a margem superior na página resultante. |

## Métodos

| Nome | Descrição |
| --- | --- |
| static [ContentSize](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentsize)(double, double) | Cria parâmetros de redimensionamento com tamanho de conteúdo especificado. |
| static [ContentSizePercent](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentsizepercent)(double, double) | Cria parâmetros de redimensionamento com tamanho de conteúdo especificado em porcentagens do tamanho da página inicial. As margens são calculadas automaticamente. |
| static [Margins](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/margins)(double, double, double, double) | Cria parâmetros de redimensionamento com valores de margens especificados. O tamanho do conteúdo é calculado automaticamente. |
| static [MarginsPercent](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/marginspercent)(double, double, double, double) | Cria parâmetros de redimensionamento. As margens são especificadas em porcentagens do tamanho da página inicial. |
| static [PageResize](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/pageresize)(double, double) | Cria parâmetros de redimensionamento para redimensionamento de página. |
| static [PageResizePct](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/pageresizepct)(double, double) | Cria parâmetros de redimensionamento para redimensionamento de página. Novos tamanhos são especificados em porcentagem. |

### Veja Também

* classe [PdfFileEditor](../pdffileeditor/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)