---
title: "EpubLoadOptions"
linktitle: "EpubLoadOptions"
second_title: "Referência da API Aspose.PDF para Java"
description: "Contém opções para carregar/importar arquivo EPUB em um documento PDF."
type: docs
weight: 1220
url: /pt/java/com.aspose.pdf/epubloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.EpubLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.EpubLoadOptions

```
public final class EpubLoadOptions extends LoadOptions
```

Contém opções para carregar/importar arquivo EPUB em um documento PDF.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [EpubLoadOptions](#EpubLoadOptions--) | Cria opções de carregamento padrão para converter arquivo EPUB em documento PDF. Tamanho de página PDF padrão - A4 300dpi 2480 × 3508. |
| [EpubLoadOptions](#EpubLoadOptions-java.awt.geom.Dimension2D-) | Cria opções de carregamento padrão para converter arquivo EPUB em documento PDF. Tamanho de página PDF padrão - A4 300dpi 2480 × 3508. |

## Métodos

| Método | Descrição |
| --- | --- |
| [getCustomCss](#getCustomCss--) | Obtém ou define o CSS personalizado a ser aplicado ao abrir o documento Epub. |
| [getEngineType](#getEngineType--) | Selecione o tipo de mecanismo para conversão EPUB para PDF. O padrão é EngineType.NEW |
| [getMargin](#getMargin--) | Obtém referência ao objeto que representa informações de margem. |
| [getMarginsAreaUsageMode](#getMarginsAreaUsageMode--) | Representa o modo de uso da área de margens – define o tratamento das instruções (se houver) de CSS do documento importado relacionadas ao uso de margens. |
| [getPageSize](#getPageSize--) | Obtém o tamanho da página de saída para importação. |
| [getPageSizeAdjustmentMode](#getPageSizeAdjustmentMode--) | ATENÇÃO! O recurso foi implementado, mas ainda não foi disponibilizado na API pública devido a um problema bloqueador na camada OSHARED revelado para o documento de exemplo. Representa o modo de uso do tamanho da página durante a conversão. Formatos (como HTML, EPUB etc.) geralmente têm design fluido, portanto, permitem ajustar o tamanho da página necessário. Mas às vezes o conteúdo tem posições horizontais ou tamanho especificados que não permitem colocar o conteúdo no tamanho de página requerido. Nesse caso, podemos definir o que deve ser feito (ou seja, quando o tamanho do conteúdo não se encaixa no tamanho de página inicial requerido do documento PDF resultante). |
| [setCustomCss](#setCustomCss-java.lang.String-) | Obtém ou define o CSS personalizado a ser aplicado ao abrir o documento Epub. |
| [setEngineType](#setEngineType-com.aspose.pdf.EpubLoadOptions.EngineType-) | Selecione o tipo de mecanismo para conversão EPUB para PDF. O padrão é EngineType.NEW |
| [setMargin](#setMargin-com.aspose.pdf.MarginInfo-) | Obtém referência ao objeto que representa informações de margem. |
| [setMarginsAreaUsageMode](#setMarginsAreaUsageMode-int-) | Representa o modo de uso da área de margens – define o tratamento das instruções (se houver) de CSS do documento importado relacionadas ao uso de margens. |
| [setPageSizeAdjustmentMode](#setPageSizeAdjustmentMode-int-) | ATENÇÃO! O recurso foi implementado, mas ainda não foi disponibilizado na API pública devido a um problema bloqueador na camada OSHARED revelado para o documento de exemplo. Representa o modo de uso do tamanho da página durante a conversão. Formatos (como HTML, EPUB etc.) geralmente têm design fluido, portanto, permitem ajustar o tamanho da página necessário. Mas às vezes o conteúdo tem posições horizontais ou tamanho especificados que não permitem colocar o conteúdo no tamanho de página requerido. Nesse caso, podemos definir o que deve ser feito (ou seja, quando o tamanho do conteúdo não se encaixa no tamanho de página inicial requerido do documento PDF resultante). |

### EpubLoadOptions {#EpubLoadOptions--}
```
public EpubLoadOptions()
```

Cria opções de carregamento padrão para converter arquivo EPUB em documento PDF. Tamanho de página PDF padrão - A4 300dpi 2480 × 3508.

### EpubLoadOptions {#EpubLoadOptions-java.awt.geom.Dimension2D-}
Cria opções de carregamento padrão para converter arquivo EPUB em documento PDF. Tamanho de página PDF padrão - A4 300dpi 2480 × 3508.

### getCustomCss {#getCustomCss--}
```
public final String getCustomCss()
```

Obtém ou define o CSS personalizado a ser aplicado ao abrir o documento Epub.

**Returns:**
valor String

### getEngineType {#getEngineType--}
```
public EpubLoadOptions.EngineType getEngineType()
```

Selecione o tipo de mecanismo para conversão EPUB para PDF. O padrão é EngineType.NEW

**Returns:**
Elemento EngineType

### getMargin {#getMargin--}
```
public MarginInfo getMargin()
```

Obtém referência ao objeto que representa informações de margem.

**Returns:**
Objeto MarginInfo

### getMarginsAreaUsageMode {#getMarginsAreaUsageMode--}
```
public int getMarginsAreaUsageMode()
```

Representa o modo de uso da área de margens – define o tratamento das instruções (se houver) de CSS do documento importado relacionadas ao uso de margens.

**Returns:**
Valor MarginsAreaUsageModes @see MarginsAreaUsageModes

### getPageSize {#getPageSize--}
```
public Dimension2D getPageSize()
```

Obtém o tamanho da página de saída para importação.

**Returns:**
Objeto Dimension2D

### getPageSizeAdjustmentMode {#getPageSizeAdjustmentMode--}
```
public int getPageSizeAdjustmentMode()
```

ATENÇÃO! O recurso foi implementado, mas ainda não foi disponibilizado na API pública devido a um problema bloqueador na camada OSHARED revelado para o documento de exemplo. Representa o modo de uso do tamanho da página durante a conversão. Formatos (como HTML, EPUB etc.) geralmente têm design fluido, portanto, permitem ajustar o tamanho da página necessário. Mas às vezes o conteúdo tem posições horizontais ou tamanho especificados que não permitem colocar o conteúdo no tamanho de página requerido. Nesse caso, podemos definir o que deve ser feito (ou seja, quando o tamanho do conteúdo não se encaixa no tamanho de página inicial requerido do documento PDF resultante).

**Returns:**
Valor PageSizeAdjustmentModes @see PageSizeAdjustmentModes

### setCustomCss {#setCustomCss-java.lang.String-}
Obtém ou define o CSS personalizado a ser aplicado ao abrir o documento Epub.

### setEngineType {#setEngineType-com.aspose.pdf.EpubLoadOptions.EngineType-}
Selecione o tipo de mecanismo para conversão EPUB para PDF. O padrão é EngineType.NEW

### setMargin {#setMargin-com.aspose.pdf.MarginInfo-}
Obtém referência ao objeto que representa informações de margem.

### setMarginsAreaUsageMode {#setMarginsAreaUsageMode-int-}
```
public void setMarginsAreaUsageMode(int marginsAreaUsageMode)
```

Representa o modo de uso da área de margens – define o tratamento das instruções (se houver) de CSS do documento importado relacionadas ao uso de margens.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| marginsAreaUsageMode |  | Valor MarginsAreaUsageModes @see MarginsAreaUsageModes |

### setPageSizeAdjustmentMode {#setPageSizeAdjustmentMode-int-}
```
public void setPageSizeAdjustmentMode(int pageSizeAdjustmentMode)
```

ATENÇÃO! O recurso foi implementado, mas ainda não foi disponibilizado na API pública devido a um problema bloqueador na camada OSHARED revelado para o documento de exemplo. Representa o modo de uso do tamanho da página durante a conversão. Formatos (como HTML, EPUB etc.) geralmente têm design fluido, portanto, permitem ajustar o tamanho da página necessário. Mas às vezes o conteúdo tem posições horizontais ou tamanho especificados que não permitem colocar o conteúdo no tamanho de página requerido. Nesse caso, podemos definir o que deve ser feito (ou seja, quando o tamanho do conteúdo não se encaixa no tamanho de página inicial requerido do documento PDF resultante).

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pageSizeAdjustmentMode |  | Valor PageSizeAdjustmentModes @see PageSizeAdjustmentModes |
