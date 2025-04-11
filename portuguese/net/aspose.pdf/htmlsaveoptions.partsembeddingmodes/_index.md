---
title: Enum HtmlSaveOptions.PartsEmbeddingModes
second_title: Aspose.PDF for .NET API Reference
description: Enum HtmlSaveOptionsPartsEmbeddingModes do Aspose.Pdf. Este enum enumera os possíveis modos de incorporação de arquivos referenciados em HTML. Ele permite controlar se os arquivos referenciados (HTML, Fonts, Images, CSSes) serão incorporados no arquivo HTML principal ou serão gerados como entidades binárias separadas.
type: docs
weight: 5710
url: /pt/net/aspose.pdf/htmlsaveoptions.partsembeddingmodes/
---
## Enumeração HtmlSaveOptions.PartsEmbeddingModes

Este enum enumera os possíveis modos de incorporação de arquivos referenciados em HTML. Ele permite controlar se os arquivos referenciados (HTML, Fonts, Images, CSSes) serão incorporados no arquivo HTML principal ou serão gerados como entidades binárias separadas.

```csharp
public enum PartsEmbeddingModes
```

### Valores

| Nome | Valor | Descrição |
| --- | --- | --- |
| EmbedAllIntoHtml | `0` | Impõe a incorporação de todos os arquivos referenciados (Css, Images, Fonts) na marcação HTML gerada (ou seja, no próprio HTML). Essa abordagem gera um arquivo HTML, mas o tamanho total da saída se torna maior (porque a codificação Base64 de binários está em uso) e nem todos os navegadores (especialmente os legados) processam com sucesso binários incorporados no HTML. Mas permite obter HTML que contém todo o resultado, sem arquivos adicionais. |
| EmbedCssOnly | `1` | Impõe a separação de todos os arquivos referenciados, exceto CSS (Images e Fonts). Ou seja, o CSS será incorporado no HTML resultante, e todos os outros arquivos referenciados (Images e Fonts) serão processados como partes externas. Gera HTML que é adequado para um amplo conjunto de navegadores. |
| NoEmbedding | `2` | Impõe a separação dos arquivos referenciados (Css, Images, Fonts). Essa abordagem gera um conjunto de arquivos, mas o tamanho total da saída se torna menor (porque não há codificação Base64 de binários em uso). Além disso, essa abordagem gera HTML que é adequado para um amplo conjunto de navegadores. |

### Veja Também

* classe [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)