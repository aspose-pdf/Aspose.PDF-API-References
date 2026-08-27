---
title: "HtmlSaveOptions.PartsEmbeddingModes"
linktitle: "HtmlSaveOptions.PartsEmbeddingModes"
second_title: "Referência da API Aspose.PDF para Java"
description: "Este enum enumera os modos possíveis de incorporação de arquivos referenciados em HTML. Ele permite controlar se os arquivos referenciados (HTML, fontes, imagens, CSS) serão incorporados ao principal."
type: docs
weight: 2130
url: /pt/java/com.aspose.pdf/htmlsaveoptions.partsembeddingmodes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.PartsEmbeddingModes, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.PartsEmbeddingModes, com.aspose.ms.System.Enum, com.aspose.pdf.HtmlSaveOptions.PartsEmbeddingModes

```
public static final class HtmlSaveOptions.PartsEmbeddingModes extends com.aspose.ms.System.Enum
```

Este enum enumera os modos possíveis de incorporação de arquivos referenciados em HTML. Ele permite controlar se os arquivos referenciados (HTML, fontes, imagens, CSS) serão incorporados ao arquivo HTML principal ou serão gerados como entidades binárias separadas.

## Campos

| Campo | Descrição |
| --- | --- |
| [EmbedAllIntoHtml](#EmbedAllIntoHtml) | Força a incorporação de todos os arquivos referenciados (Css, Imagens, Fontes) na marcação HTML gerada (ou seja, no próprio HTML). Essa abordagem gera um único arquivo HTML, mas o tamanho total da saída se torna maior (porque a codificação Base64 dos binários está em uso) e nem todos os navegadores (especialmente os legados) processam com sucesso os binários incorporados ao HTML. Contudo, permite obter um HTML que contém todo o resultado, sem arquivos adicionais. |
| [EmbedCssOnly](#EmbedCssOnly) | Força a separação de todos os arquivos referenciados, exceto CSS (Imagens e Fontes). Ou seja, o CSS será incorporado ao HTML resultante, e todos os demais arquivos referenciados (Imagens e Fontes) serão processados como partes externas. Gera um HTML adequado para um amplo conjunto de navegadores. |
| [NoEmbedding](#NoEmbedding) | Força a separação dos arquivos referenciados (Css, Imagens, Fontes). Essa abordagem gera um conjunto de arquivos, mas o tamanho total da saída se torna menor (porque não há codificação Base64 dos binários em uso). Além disso, essa abordagem gera um HTML adequado para um amplo conjunto de navegadores. |

### EmbedAllIntoHtml {#EmbedAllIntoHtml}
```
public static final int EmbedAllIntoHtml
```

Força a incorporação de todos os arquivos referenciados (Css, Imagens, Fontes) na marcação HTML gerada (ou seja, no próprio HTML). Essa abordagem gera um único arquivo HTML, mas o tamanho total da saída se torna maior (porque a codificação Base64 dos binários está em uso) e nem todos os navegadores (especialmente os legados) processam com sucesso os binários incorporados ao HTML. Contudo, permite obter um HTML que contém todo o resultado, sem arquivos adicionais.

### EmbedCssOnly {#EmbedCssOnly}
```
public static final int EmbedCssOnly
```

Força a separação de todos os arquivos referenciados, exceto CSS (Imagens e Fontes). Ou seja, o CSS será incorporado ao HTML resultante, e todos os demais arquivos referenciados (Imagens e Fontes) serão processados como partes externas. Gera um HTML adequado para um amplo conjunto de navegadores.

### NoEmbedding {#NoEmbedding}
```
public static final int NoEmbedding
```

Força a separação dos arquivos referenciados (Css, Imagens, Fontes). Essa abordagem gera um conjunto de arquivos, mas o tamanho total da saída se torna menor (porque não há codificação Base64 dos binários em uso). Além disso, essa abordagem gera um HTML adequado para um amplo conjunto de navegadores.
