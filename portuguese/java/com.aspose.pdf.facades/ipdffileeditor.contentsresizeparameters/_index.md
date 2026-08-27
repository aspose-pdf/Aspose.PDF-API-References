---
title: "IPdfFileEditor.ContentsResizeParameters"
linktitle: "IPdfFileEditor.ContentsResizeParameters"
second_title: "Referência da API Aspose.PDF para Java"
description: "Classe para especificar parâmetros de redimensionamento de página. Permite definir os seguintes parâmetros: Tamanho da página resultante (largura, altura) em unidades de espaço padrão ou em porcentagem das páginas iniciais."
type: docs
weight: 300
url: /pt/java/com.aspose.pdf.facades/ipdffileeditor.contentsresizeparameters/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters

```
public static class IPdfFileEditor.ContentsResizeParameters extends Object
```

Classe para especificar parâmetros de redimensionamento de página. Permite definir os seguintes parâmetros: tamanho da página resultante (largura, altura) em unidades de espaço padrão ou em porcentagem do tamanho da página inicial; margens esquerda, superior, inferior e direita em unidades de espaço padrão ou em porcentagem do tamanho da página inicial; alguns valores podem ser deixados nulos para cálculo automático. Esses valores serão calculados a partir do restante do tamanho da página após o cálculo dos valores explicitamente especificados. Por exemplo: se a largura da página = 100 e a nova largura da página especificada for 60 unidades, então as margens esquerda e direita são calculadas automaticamente: (100 - 60) / 2 = 15. Esta classe é usada no método ResizeContents.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [ContentsResizeParameters](#ContentsResizeParameters--) | Cria parâmetros de redimensionamento onde todos os valores são definidos como "auto". Margens e tamanho do conteúdo podem ser especificados posteriormente, se necessário. |
| [ContentsResizeParameters](#ContentsResizeParameters-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Cria parâmetros de redimensionamento onde todos os valores são definidos como "auto". Margens e tamanho do conteúdo podem ser especificados posteriormente, se necessário. |

## Métodos

| Método | Descrição |
| --- | --- |
| [contentSize](#contentSize-double-double-) | Cria parâmetros de redimensionamento com tamanho de conteúdo especificado. |
| [contentSizePercent](#contentSizePercent-double-double-) | Cria parâmetros de redimensionamento com tamanho de conteúdo especificado em porcentagem do tamanho da página inicial. As margens são calculadas automaticamente. |
| [getBottomMargin](#getBottomMargin--) | Obtém ou define a margem inferior na página resultante. |
| [getContentsHeight](#getContentsHeight--) | Obtém ou define a altura do conteúdo da página de origem na página resultante. |
| [getContentsWidth](#getContentsWidth--) | Obtém ou define a largura do conteúdo da página de origem na página resultante. |
| [getLeftMargin](#getLeftMargin--) | Obtém ou define a margem esquerda na página resultante. |
| [getRightMargin](#getRightMargin--) | Obtém ou define a margem direita na página resultante. |
| [getTopMargin](#getTopMargin--) | Obtém ou define a margem superior na página resultante. |
| [isChangeMediaBox](#isChangeMediaBox--) | Obtém se deve ajustar o MediaBox de uma página PDF durante a operação de redimensionamento. O valor padrão é {@code false}. Definir este parâmetro permite ajustar o MediaBox ao valor do CropBox durante o redimensionamento. |
| [margins](#margins-double-double-double-double-) | Cria parâmetros de redimensionamento com valor de margens especificado. O tamanho do conteúdo é calculado automaticamente. |
| [marginsPercent](#marginsPercent-double-double-double-double-) | Cria parâmetros de redimensionamento. As margens são especificadas em porcentagem do tamanho inicial da página. |
| [pageResize](#pageResize-double-double-) | Cria parâmetros de redimensionamento para redimensionamento de página. |
| [pageResizePct](#pageResizePct-double-double-) | Cria parâmetros de redimensionamento para redimensionamento de página. Novos tamanhos são especificados em porcentagem. |
| [setBottomMargin](#setBottomMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Obtém ou define a margem inferior na página resultante. |
| [setChangeMediaBox](#setChangeMediaBox-boolean-) | Define se deve ajustar o MediaBox de uma página PDF durante a operação de redimensionamento. O valor padrão é {@code false}. Definir este parâmetro permite ajustar o MediaBox ao valor do CropBox durante o redimensionamento. |
| [setContentsHeight](#setContentsHeight-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Obtém ou define a altura do conteúdo da página de origem na página resultante. |
| [setContentsWidth](#setContentsWidth-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Obtém ou define a largura do conteúdo da página de origem na página resultante. |
| [setLeftMargin](#setLeftMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Obtém ou define a margem esquerda na página resultante. |
| [setRightMargin](#setRightMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Obtém ou define a margem direita na página resultante. |
| [setTopMargin](#setTopMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Obtém ou define a margem superior na página resultante. |

### ContentsResizeParameters {#ContentsResizeParameters--}
```
public ContentsResizeParameters()
```

Cria parâmetros de redimensionamento onde todos os valores são definidos como "auto". Margens e tamanho do conteúdo podem ser especificados posteriormente, se necessário.

### ContentsResizeParameters {#ContentsResizeParameters-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
Cria parâmetros de redimensionamento onde todos os valores são definidos como "auto". Margens e tamanho do conteúdo podem ser especificados posteriormente, se necessário.

### contentSize {#contentSize-double-double-}
```
public static IPdfFileEditor.ContentsResizeParameters contentSize(double width, double height)
```

Cria parâmetros de redimensionamento com tamanho de conteúdo especificado.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| largura |  | Nova largura do conteúdo. |
| altura |  | Nova altura do conteúdo. |

**Returns:**
Retorna novos parâmetros de redimensionamento.

### contentSizePercent {#contentSizePercent-double-double-}
```
public static IPdfFileEditor.ContentsResizeParameters contentSizePercent(double width, double height)
```

Cria parâmetros de redimensionamento com tamanho de conteúdo especificado em porcentagem do tamanho da página inicial. As margens são calculadas automaticamente.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| largura |  | Nova largura do conteúdo em porcentagem. |
| altura |  | Nova altura do conteúdo em porcentagem. |

**Returns:**
Novos parâmetros de redimensionamento.

### getBottomMargin {#getBottomMargin--}
```
public IPdfFileEditor.ContentsResizeValue getBottomMargin()
```

Obtém ou define a margem inferior na página resultante.

**Returns:**
Objeto ContentsResizeValue

### getContentsHeight {#getContentsHeight--}
```
public IPdfFileEditor.ContentsResizeValue getContentsHeight()
```

Obtém ou define a altura do conteúdo da página de origem na página resultante.

**Returns:**
Objeto ContentsResizeValue

### getContentsWidth {#getContentsWidth--}
```
public IPdfFileEditor.ContentsResizeValue getContentsWidth()
```

Obtém ou define a largura do conteúdo da página de origem na página resultante.

**Returns:**
Objeto ContentsResizeValue

### getLeftMargin {#getLeftMargin--}
```
public IPdfFileEditor.ContentsResizeValue getLeftMargin()
```

Obtém ou define a margem esquerda na página resultante.

**Returns:**
Objeto ContentsResizeValue

### getRightMargin {#getRightMargin--}
```
public IPdfFileEditor.ContentsResizeValue getRightMargin()
```

Obtém ou define a margem direita na página resultante.

**Returns:**
Objeto ContentsResizeValue

### getTopMargin {#getTopMargin--}
```
public IPdfFileEditor.ContentsResizeValue getTopMargin()
```

Obtém ou define a margem superior na página resultante.

**Returns:**
Objeto ContentsResizeValue

### isChangeMediaBox {#isChangeMediaBox--}
```
public final boolean isChangeMediaBox()
```

Obtém se deve ajustar o MediaBox de uma página PDF durante a operação de redimensionamento. O valor padrão é {@code false}. Definir este parâmetro permite ajustar o MediaBox ao valor do CropBox durante o redimensionamento.

**Returns:**
se deve ajustar o MediaBox de uma página PDF durante a operação de redimensionamento.

### margins {#margins-double-double-double-double-}
```
public static IPdfFileEditor.ContentsResizeParameters margins(double left, double right, double top, double bottom)
```

Cria parâmetros de redimensionamento com valor de margens especificado. O tamanho do conteúdo é calculado automaticamente.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| esquerda |  | Margem esquerda. |
| direita |  | Margem direita. |
| superior |  | Margem superior. |
| inferior |  | Margem inferior. |

**Returns:**
Parâmetros de redimensionamento criados.

### marginsPercent {#marginsPercent-double-double-double-double-}
```
public static IPdfFileEditor.ContentsResizeParameters marginsPercent(double left, double right, double top, double bottom)
```

Cria parâmetros de redimensionamento. As margens são especificadas em porcentagem do tamanho inicial da página.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| esquerda |  | Margem esquerda (em porcentagem da largura da página). |
| direita |  | Margem direita (em porcentagem da altura da página). |
| superior |  | Margem superior (em porcentagem da altura da página). |
| inferior |  | Margem inferior (em porcentagem da altura da página). |

**Returns:**
Retorna novos parâmetros de redimensionamento.

### pageResize {#pageResize-double-double-}
```
public static IPdfFileEditor.ContentsResizeParameters pageResize(double width, double height)
```

Cria parâmetros de redimensionamento para redimensionamento de página.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| largura |  | Nova largura da página em unidades. |
| altura |  | Nova altura da página em unidades. |

**Returns:**
Novos parâmetros de redimensionamento.

### pageResizePct {#pageResizePct-double-double-}
```
public IPdfFileEditor.ContentsResizeParameters pageResizePct(double widthPct, double heightPct)
```

Cria parâmetros de redimensionamento para redimensionamento de página. Novos tamanhos são especificados em porcentagem.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| widthPct |  | Nova largura da página em porcentagem. |
| heightPct |  | Nova altura da página em porcentagem. |

**Returns:**
Novos parâmetros de redimensionamento.

### setBottomMargin {#setBottomMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
Obtém ou define a margem inferior na página resultante.

### setChangeMediaBox {#setChangeMediaBox-boolean-}
```
public final void setChangeMediaBox(boolean value)
```

Define se deve ajustar o MediaBox de uma página PDF durante a operação de redimensionamento. O valor padrão é {@code false}. Definir este parâmetro permite ajustar o MediaBox ao valor do CropBox durante o redimensionamento.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | se deve ajustar o MediaBox de uma página PDF durante a operação de redimensionamento. |

### setContentsHeight {#setContentsHeight-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
Obtém ou define a altura do conteúdo da página de origem na página resultante.

### setContentsWidth {#setContentsWidth-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
Obtém ou define a largura do conteúdo da página de origem na página resultante.

### setLeftMargin {#setLeftMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
Obtém ou define a margem esquerda na página resultante.

### setRightMargin {#setRightMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
Obtém ou define a margem direita na página resultante.

### setTopMargin {#setTopMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
Obtém ou define a margem superior na página resultante.
