---
title: "HtmlFragment"
linktitle: "HtmlFragment"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa um fragmento HTML."
type: docs
weight: 1950
url: /pt/java/com.aspose.pdf/htmlfragment/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.FormattedFragment com.aspose.pdf.HtmlFragment, com.aspose.pdf.BaseParagraph, com.aspose.pdf.FormattedFragment com.aspose.pdf.HtmlFragment, com.aspose.pdf.FormattedFragment, com.aspose.pdf.HtmlFragment

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class HtmlFragment extends FormattedFragment
```

Representa um fragmento HTML.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [HtmlFragment](#HtmlFragment-java.lang.String-) | Inicializa uma nova instância da classe HtmlFragment. |

## Métodos

| Método | Descrição |
| --- | --- |
| [deepClone](#deepClone--) | Clona fragmento html. |
| [getHtmlLoadOptions](#getHtmlLoadOptions--) | Obtém HtmlLoadOptions que serão usados para carregar (e renderizar) HTML nesta instância da classe. Use-o quando for necessário usar uma configuração específica para importação de HTML para esta ou aquela instância (por exemplo, quando esta ou aquela instância deve usar um BasePath específico para HTML importado ou deve usar um carregador específico de recursos externos). Se o parâmetro for o padrão (null), então serão usadas as opções padrão de carregamento de HTML. |
| [getRectangle](#getRectangle--) | Obtém o retângulo do HtmlFragment |
| [getTextState](#getTextState--) | Obtém ou define a font |
| [isBreakWords](#isBreakWords--) | Obtém ou define a quebra de palavras |
| [isParagraphHasMargin](#isParagraphHasMargin--) | Obtém ou define se o parágrafo tem margem padrão; caso contrário, a margem é 0 |
| [setBreakWords](#setBreakWords-boolean-) | Obtém ou define a quebra de palavras |
| [setHtmlLoadOptions](#setHtmlLoadOptions-com.aspose.pdf.HtmlLoadOptions-) | Define HtmlLoadOptions que serão usados para carregar (e renderizar) HTML nesta instância da classe. Use-o quando for necessário usar uma configuração específica para importação de HTML para esta ou aquela instância (por exemplo, quando esta ou aquela instância deve usar um BasePath específico para HTML importado ou deve usar um carregador específico de recursos externos). Se o parâmetro for o padrão (null), então serão usadas as opções padrão de carregamento de HTML. |
| [setParagraphHasMargin](#setParagraphHasMargin-boolean-) | Obtém ou define se o parágrafo tem margem padrão; caso contrário, a margem é 0 |
| [setTextState](#setTextState-com.aspose.pdf.TextState-) | Obtém ou define a font |

### HtmlFragment {#HtmlFragment-java.lang.String-}
Inicializa uma nova instância da classe HtmlFragment.

### deepClone {#deepClone--}
```
public Object deepClone()
```

Clona fragmento html.

**Returns:**
Objeto de fragmento html clonado.

### getHtmlLoadOptions {#getHtmlLoadOptions--}
```
public HtmlLoadOptions getHtmlLoadOptions()
```

Obtém HtmlLoadOptions que serão usados para carregar (e renderizar) HTML nesta instância da classe. Use-o quando for necessário usar uma configuração específica para importação de HTML para esta ou aquela instância (por exemplo, quando esta ou aquela instância deve usar um BasePath específico para HTML importado ou deve usar um carregador específico de recursos externos). Se o parâmetro for o padrão (null), então serão usadas as opções padrão de carregamento de HTML.

**Returns:**
Valor de HtmlLoadOptions

### getRectangle {#getRectangle--}
```
public final Rectangle2D.Float getRectangle()
```

Obtém o retângulo do HtmlFragment

**Returns:**
java.awt.geom.Rectangle2D.Float instance

### getTextState {#getTextState--}
```
public TextState getTextState()
```

Obtém ou define a font

**Returns:**
Objeto TextState

### isBreakWords {#isBreakWords--}
```
public final boolean isBreakWords()
```

Obtém ou define a quebra de palavras

**Returns:**
valor booleano

### isParagraphHasMargin {#isParagraphHasMargin--}
```
public final boolean isParagraphHasMargin()
```

Obtém ou define se o parágrafo tem margem padrão; caso contrário, a margem é 0

**Returns:**
valor booleano

### setBreakWords {#setBreakWords-boolean-}
```
public final void setBreakWords(boolean value)
```

Obtém ou define a quebra de palavras

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setHtmlLoadOptions {#setHtmlLoadOptions-com.aspose.pdf.HtmlLoadOptions-}
Define HtmlLoadOptions que serão usados para carregar (e renderizar) HTML nesta instância da classe. Use-o quando for necessário usar uma configuração específica para importação de HTML para esta ou aquela instância (por exemplo, quando esta ou aquela instância deve usar um BasePath específico para HTML importado ou deve usar um carregador específico de recursos externos). Se o parâmetro for o padrão (null), então serão usadas as opções padrão de carregamento de HTML.

### setParagraphHasMargin {#setParagraphHasMargin-boolean-}
```
public final void setParagraphHasMargin(boolean value)
```

Obtém ou define se o parágrafo tem margem padrão; caso contrário, a margem é 0

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setTextState {#setTextState-com.aspose.pdf.TextState-}
Obtém ou define a font
