---
title: "BaseParagraph"
linktitle: "BaseParagraph"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa um objeto base abstrato que pode ser adicionado à página (doc.Paragraphs.Add())."
type: docs
weight: 280
url: /pt/java/com.aspose.pdf/baseparagraph/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public abstract class BaseParagraph extends Object implements com.aspose.ms.System.ICloneable
```

Representa um objeto base abstrato que pode ser adicionado à página (doc.Paragraphs.Add()).

## Construtores

| Construtor | Descrição |
| --- | --- |
| [BaseParagraph](#BaseParagraph--) |  |

## Métodos

| Método | Descrição |
| --- | --- |
| [deepClone](#deepClone--) | Clona esta instância. Método virtual. Sempre retorna null. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | Obtém um alinhamento horizontal do parágrafo |
| [getHyperlink](#getHyperlink--) | / * / * Obtém ou define se um parágrafo é nota de rodapé. O padrão é false.(para geração de pdf) / * / * |
| [getMargin](#getMargin--) | Obtém uma margem externa para o parágrafo (para geração de pdf) |
| [getVerticalAlignment](#getVerticalAlignment--) | Obtém um alinhamento vertical do parágrafo |
| [getZIndex](#getZIndex--) | Obtém um valor int que indica a ordem Z do gráfico. Um gráfico com ZIndex maior será colocado sobre o gráfico com ZIndex menor. ZIndex pode ser negativo. Gráfico com ZIndex negativo será colocado atrás do texto na página. |
| [isFirstParagraphInColumn](#isFirstParagraphInColumn--) | Obtém ou define um valor bool que indica se este parágrafo ficará na próxima coluna. O padrão é false.(para geração de pdf) |
| [isInLineParagraph](#isInLineParagraph--) | Obtém se um parágrafo é inline. O padrão é false.(para geração de pdf) |
| [isInNewPage](#isInNewPage--) | Obtém um valor bool que força este parágrafo a ser gerado em nova página. O padrão é false. (para geração de pdf) |
| [isKeptWithNext](#isKeptWithNext--) | Obtém um valor boolean que indica se o parágrafo atual permanece na mesma página junto com o próximo parágrafo. O padrão é false. (para geração de pdf) |
| [setFirstParagraphInColumn](#setFirstParagraphInColumn-boolean-) | Obtém ou define um valor bool que indica se este parágrafo ficará na próxima coluna. O padrão é false.(para geração de pdf) |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | Define um alinhamento horizontal do parágrafo |
| [setHyperlink](#setHyperlink-com.aspose.pdf.Hyperlink-) | Define um hyperlink (para gerador de pdf). |
| [setInLineParagraph](#setInLineParagraph-boolean-) | Define que um parágrafo é inline. O padrão é false. (para geração de pdf) |
| [setInNewPage](#setInNewPage-boolean-) | Define um valor boolean que força este parágrafo a ser gerado em nova página. O padrão é false. (para geração de pdf) |
| [setKeptWithNext](#setKeptWithNext-boolean-) | Define um valor boolean que indica se o parágrafo atual permanece na mesma página junto com o próximo parágrafo. O padrão é false. (para geração de pdf) |
| [setMargin](#setMargin-com.aspose.pdf.MarginInfo-) | Define uma margem externa para o parágrafo (para geração de pdf) |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Define um alinhamento vertical do parágrafo |
| [setZIndex](#setZIndex-int-) | Define um valor int que indica a ordem Z do gráfico. Um gráfico com ZIndex maior será colocado sobre o gráfico com ZIndex menor. ZIndex pode ser negativo. Gráfico com ZIndex negativo será colocado atrás do texto na página. |

### BaseParagraph {#BaseParagraph--}
```
public BaseParagraph()
```



### deepClone {#deepClone--}
```
public Object deepClone()
```

Clona esta instância. Método virtual. Sempre retorna null.

**Returns:**
Nulo

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

Obtém um alinhamento horizontal do parágrafo

**Returns:**
Valor HorizontalAlignment @see HorizontalAlignment

### getHyperlink {#getHyperlink--}
```
public Hyperlink getHyperlink()
```

/ * / * Obtém ou define se um parágrafo é nota de rodapé. O padrão é false.(para geração de pdf) / * / *

**Returns:**
valor boolean /

### getMargin {#getMargin--}
```
public MarginInfo getMargin()
```

Obtém uma margem externa para o parágrafo (para geração de pdf)

**Returns:**
Valor MarginInfo

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

Obtém um alinhamento vertical do parágrafo

**Returns:**
Elemento VerticalAlignment @see VerticalAlignment

### getZIndex {#getZIndex--}
```
public int getZIndex()
```

Obtém um valor int que indica a ordem Z do gráfico. Um gráfico com ZIndex maior será colocado sobre o gráfico com ZIndex menor. ZIndex pode ser negativo. Gráfico com ZIndex negativo será colocado atrás do texto na página.

**Returns:**
valor int

### isFirstParagraphInColumn {#isFirstParagraphInColumn--}
```
public boolean isFirstParagraphInColumn()
```

Obtém ou define um valor bool que indica se este parágrafo ficará na próxima coluna. O padrão é false.(para geração de pdf)

**Returns:**
valor booleano

### isInLineParagraph {#isInLineParagraph--}
```
public boolean isInLineParagraph()
```

Obtém se um parágrafo é inline. O padrão é false.(para geração de pdf)

**Returns:**
valor booleano

### isInNewPage {#isInNewPage--}
```
public boolean isInNewPage()
```

Obtém um valor bool que força este parágrafo a ser gerado em nova página. O padrão é false. (para geração de pdf)

**Returns:**
valor booleano

### isKeptWithNext {#isKeptWithNext--}
```
public boolean isKeptWithNext()
```

Obtém um valor boolean que indica se o parágrafo atual permanece na mesma página junto com o próximo parágrafo. O padrão é false. (para geração de pdf)

**Returns:**
valor booleano

### setFirstParagraphInColumn {#setFirstParagraphInColumn-boolean-}
```
public void setFirstParagraphInColumn(boolean value)
```

Obtém ou define um valor bool que indica se este parágrafo ficará na próxima coluna. O padrão é false.(para geração de pdf)

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
Define um alinhamento horizontal do parágrafo

### setHyperlink {#setHyperlink-com.aspose.pdf.Hyperlink-}
Define um hyperlink (para gerador de pdf).

### setInLineParagraph {#setInLineParagraph-boolean-}
```
public void setInLineParagraph(boolean value)
```

Define que um parágrafo é inline. O padrão é false. (para geração de pdf)

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setInNewPage {#setInNewPage-boolean-}
```
public void setInNewPage(boolean value)
```

Define um valor boolean que força este parágrafo a ser gerado em nova página. O padrão é false. (para geração de pdf)

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setKeptWithNext {#setKeptWithNext-boolean-}
```
public final void setKeptWithNext(boolean value)
```

Define um valor boolean que indica se o parágrafo atual permanece na mesma página junto com o próximo parágrafo. O padrão é false. (para geração de pdf)

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setMargin {#setMargin-com.aspose.pdf.MarginInfo-}
Define uma margem externa para o parágrafo (para geração de pdf)

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Define um alinhamento vertical do parágrafo

### setZIndex {#setZIndex-int-}
```
public void setZIndex(int value)
```

Define um valor int que indica a ordem Z do gráfico. Um gráfico com ZIndex maior será colocado sobre o gráfico com ZIndex menor. ZIndex pode ser negativo. Gráfico com ZIndex negativo será colocado atrás do texto na página.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |
