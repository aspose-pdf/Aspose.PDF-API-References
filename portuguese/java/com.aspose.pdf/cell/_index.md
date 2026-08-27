---
title: "Cell"
linktitle: "Cell"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa uma célula da linha da tabela."
type: docs
weight: 510
url: /pt/java/com.aspose.pdf/cell/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Cell

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class Cell extends Object implements com.aspose.ms.System.ICloneable
```

Representa uma célula da linha da tabela.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [Cell](#Cell--) | Inicializa uma nova instância da classe Cell. |
| [Cell](#Cell-com.aspose.pdf.Rectangle-) | Inicializa uma nova instância da classe Cell. |

## Métodos

| Método | Descrição |
| --- | --- |
| [deepClone](#deepClone--) | Clona a célula. |
| [getAlignment](#getAlignment--) | Obtém o alinhamento. |
| [getBackgroundColor](#getBackgroundColor--) | Obtém a cor de fundo. |
| [getBackgroundImage](#getBackgroundImage--) | Obtém ou define a imagem de fundo |
| [getBackgroundImageFile](#getBackgroundImageFile--) | Obtém o arquivo de imagem de fundo. |
| [getBorder](#getBorder--) | Obtém a borda. |
| [getColSpan](#getColSpan--) | Obtém ou define a extensão da coluna. |
| [getDefaultCellTextState](#getDefaultCellTextState--) | Obtém o estado de texto padrão da célula. |
| [getMargin](#getMargin--) | Obtém o preenchimento. |
| [getParagraphs](#getParagraphs--) | Obtém o texto formatado da célula. |
| [getRowSpan](#getRowSpan--) | Obtém a extensão da linha. |
| [getVerticalAlignment](#getVerticalAlignment--) | Obtém o alinhamento vertical. |
| [getWidth](#getWidth--) | Obtém a largura da coluna. |
| [isNoBorder](#isNoBorder--) | Obtém se a célula tem borda. |
| [isOverrideByFragment](#isOverrideByFragment--) | Define a propriedade TextState da célula, que é sobrescrita pela propriedade TextState do TextFragment. |
| [isWordWrapped](#isWordWrapped--) | Obtém se o texto da célula está com quebra de linha. |
| [setAlignment](#setAlignment-com.aspose.pdf.HorizontalAlignment-) | Define o alinhamento. |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Obtém ou define a cor de fundo. |
| [setBackgroundImage](#setBackgroundImage-com.aspose.pdf.Image-) | Obtém ou define a imagem de fundo |
| [setBackgroundImageFile](#setBackgroundImageFile-java.lang.String-) | Define o arquivo de imagem de fundo. |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | Define a borda. |
| [setColSpan](#setColSpan-int-) | Define a extensão da coluna. |
| [setDefaultCellTextState](#setDefaultCellTextState-com.aspose.pdf.TextState-) | Define o estado de texto padrão da célula. |
| [setMargin](#setMargin-com.aspose.pdf.MarginInfo-) | Define o preenchimento. |
| [setNoBorder](#setNoBorder-boolean-) | Define se a célula tem borda. |
| [setOverrideByFragment](#setOverrideByFragment-boolean-) | Define a propriedade TextState da célula, que é sobrescrita pela propriedade TextState do TextFragment. |
| [setParagraphs](#setParagraphs-com.aspose.pdf.Paragraphs-) | Define o texto formatado da célula. |
| [setRowSpan](#setRowSpan-int-) | Define a extensão da linha. |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Define o alinhamento vertical. |
| [setWidth](#setWidth-double-) | Define a largura da coluna. |
| [setWordWrapped](#setWordWrapped-boolean-) | Define se o texto da célula tem quebra de linha. |

### Cell {#Cell--}
```
public Cell()
```

Inicializa uma nova instância da classe Cell.

### Cell {#Cell-com.aspose.pdf.Rectangle-}
Inicializa uma nova instância da classe Cell.

### deepClone {#deepClone--}
```
public Object deepClone()
```

Clona a célula.

**Returns:**
O objeto clonado

### getAlignment {#getAlignment--}
```
public HorizontalAlignment getAlignment()
```

Obtém o alinhamento.

**Returns:**
Elemento HorizontalAlignment @see HorizontalAlignment

### getBackgroundColor {#getBackgroundColor--}
```
public Color getBackgroundColor()
```

Obtém a cor de fundo.

**Returns:**
Objeto Color

### getBackgroundImage {#getBackgroundImage--}
```
public final Image getBackgroundImage()
```

Obtém ou define a imagem de fundo

**Returns:**
Instância de imagem

### getBackgroundImageFile {#getBackgroundImageFile--}
```
@Deprecated public String getBackgroundImageFile()
```

Obtém o arquivo de imagem de fundo.

**Returns:**
Valor string @deprecated A propriedade foi expandida, por favor use BackgroundImage

### getBorder {#getBorder--}
```
public BorderInfo getBorder()
```

Obtém a borda.

**Returns:**
Objeto BorderInfo

### getColSpan {#getColSpan--}
```
public int getColSpan()
```

Obtém ou define a extensão da coluna.

**Returns:**
valor int

### getDefaultCellTextState {#getDefaultCellTextState--}
```
public TextState getDefaultCellTextState()
```

Obtém o estado de texto padrão da célula.

**Returns:**
Objeto TextState

### getMargin {#getMargin--}
```
public MarginInfo getMargin()
```

Obtém o preenchimento.

**Returns:**
Objeto MarginInfo

### getParagraphs {#getParagraphs--}
```
public Paragraphs getParagraphs()
```

Obtém o texto formatado da célula.

**Returns:**
Objeto Paragraphs

### getRowSpan {#getRowSpan--}
```
public int getRowSpan()
```

Obtém a extensão da linha.

**Returns:**
valor int

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

Obtém o alinhamento vertical.

**Returns:**
Elemento VerticalAlignment @see VerticalAlignment

### getWidth {#getWidth--}
```
public double getWidth()
```

Obtém a largura da coluna.

**Returns:**
valor double

### isNoBorder {#isNoBorder--}
```
public boolean isNoBorder()
```

Obtém se a célula tem borda.

**Returns:**
valor booleano

### isOverrideByFragment {#isOverrideByFragment--}
```
public final boolean isOverrideByFragment()
```

Define a propriedade TextState da célula, que é sobrescrita pela propriedade TextState do TextFragment.

**Returns:**
valor booleano

### isWordWrapped {#isWordWrapped--}
```
public boolean isWordWrapped()
```

Obtém se o texto da célula está com quebra de linha.

**Returns:**
valor booleano

### setAlignment {#setAlignment-com.aspose.pdf.HorizontalAlignment-}
Define o alinhamento.

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Obtém ou define a cor de fundo.

### setBackgroundImage {#setBackgroundImage-com.aspose.pdf.Image-}
Obtém ou define a imagem de fundo

### setBackgroundImageFile {#setBackgroundImageFile-java.lang.String-}
Define o arquivo de imagem de fundo.

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
Define a borda.

### setColSpan {#setColSpan-int-}
```
public void setColSpan(int value)
```

Define a extensão da coluna.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |

### setDefaultCellTextState {#setDefaultCellTextState-com.aspose.pdf.TextState-}
Define o estado de texto padrão da célula.

### setMargin {#setMargin-com.aspose.pdf.MarginInfo-}
Define o preenchimento.

### setNoBorder {#setNoBorder-boolean-}
```
public void setNoBorder(boolean value)
```

Define se a célula tem borda.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setOverrideByFragment {#setOverrideByFragment-boolean-}
```
public final void setOverrideByFragment(boolean value)
```

Define a propriedade TextState da célula, que é sobrescrita pela propriedade TextState do TextFragment.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setParagraphs {#setParagraphs-com.aspose.pdf.Paragraphs-}
Define o texto formatado da célula.

### setRowSpan {#setRowSpan-int-}
```
public void setRowSpan(int value)
```

Define a extensão da linha.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Define o alinhamento vertical.

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Define a largura da coluna.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### setWordWrapped {#setWordWrapped-boolean-}
```
public void setWordWrapped(boolean value)
```

Define se o texto da célula tem quebra de linha.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |
