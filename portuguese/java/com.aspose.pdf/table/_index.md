---
title: "Tabela"
linktitle: "Tabela"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa uma tabela que pode ser adicionada à página."
type: docs
weight: 4790
url: /pt/java/com.aspose.pdf/table/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Table, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Table

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class Table extends BaseParagraph
```

Representa uma tabela que pode ser adicionada à página.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [Table](#Table--) | Construtor padrão |

## Métodos

| Método | Descrição |
| --- | --- |
| [deepClone](#deepClone--) | / * / * Importa um array unidimensional de dados na tabela. A importação coloca uma célula para cada item do array e / * começa a partir da linha e coluna definidas nos parâmetros. Durante a importação, se for detectado que as linhas necessárias / * ainda estão ausentes (ou seja, a tabela de destino é muito pequena para absorver todos os dados), as linhas necessárias serão criadas / * / * |
| [drawRoundedRectangle](#drawRoundedRectangle-com.aspose.pdf.GraphInfo-com.aspose.pdf.Point-com.aspose.pdf.Point-java.util.List-double-) | Adiciona operadores para retângulo. |
| [getAlignment](#getAlignment--) | Obtém o alinhamento da tabela. |
| [getBackgroundColor](#getBackgroundColor--) | Obtém a cor de fundo da tabela |
| [getBorder](#getBorder--) | Obtém a borda. |
| [getBreakText](#getBreakText--) | Obtém o texto de quebra para a tabela |
| [getBroken](#getBroken--) | Obtém ou define a quebra vertical da tabela; |
| [getColumnAdjustment](#getColumnAdjustment--) | Obtém o ajuste de coluna da tabela. |
| [getColumnWidth](#getColumnWidth-java.lang.String-) | Obter largura da coluna |
| [getColumnWidths](#getColumnWidths--) | Obtém as larguras das colunas da tabela. |
| [getCornerStyle](#getCornerStyle--) | Obtém os estilos dos cantos da borda |
| [getDefaultCellBorder](#getDefaultCellBorder--) | Obtém a borda padrão da célula; |
| [getDefaultCellPadding](#getDefaultCellPadding--) | Obtém o preenchimento padrão da célula. |
| [getDefaultCellTextState](#getDefaultCellTextState--) | Obtém o estado de texto padrão da célula. |
| [getDefaultColumnWidth](#getDefaultColumnWidth--) | Obtém a borda padrão da célula; |
| [getHeight](#getHeight--) | Obter altura. |
| [getHeight](#getHeight-com.aspose.pdf.Page-) | Obter altura. |
| [getLeft](#getLeft--) | Obtém a coordenada esquerda da tabela. |
| [getRepeatingColumnsCount](#getRepeatingColumnsCount--) | Obtém ou define a contagem máxima de colunas para a tabela |
| [getRepeatingRowsCount](#getRepeatingRowsCount--) | Obtém a contagem de primeiras linhas repetidas em várias páginas |
| [getRepeatingRowsStyle](#getRepeatingRowsStyle--) | Obtém o estilo para linhas repetidas |
| [getRows](#getRows--) | Obtém as linhas da tabela. |
| [getTop](#getTop--) | Obtém a coordenada superior da tabela. |
| [getWidth](#getWidth--) | Obter largura. |
| [isBordersIncluded](#isBordersIncluded--) | Obtém borda incluída nas larguras das colunas. |
| [isBroken](#isBroken--) | Obtém se a tabela está quebrada - será truncada para a próxima página. |
| [setAlignment](#setAlignment-com.aspose.pdf.HorizontalAlignment-) | Define o alinhamento da tabela. |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Define a cor de fundo da tabela |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | Define a borda. |
| [setBordersIncluded](#setBordersIncluded-boolean-) | Define borda incluída nas larguras das colunas. |
| [setBreakText](#setBreakText-com.aspose.pdf.TextFragment-) | Define quebra de texto para a tabela |
| [setBroken](#setBroken-boolean-) | Define se a tabela está quebrada - será truncada para a próxima página. |
| [setBroken](#setBroken-int-) | Obtém ou define a quebra vertical da tabela; |
| [setColumnAdjustment](#setColumnAdjustment-com.aspose.pdf.ColumnAdjustment-) | Define o ajuste de coluna da tabela. |
| [setColumnTextState](#setColumnTextState-int-com.aspose.pdf.TextState-) | Define a altura. |
| [setColumnWidths](#setColumnWidths-java.lang.String-) | Obtém as larguras das colunas da tabela. |
| [setCornerStyle](#setCornerStyle-com.aspose.pdf.BorderCornerStyle-) | Obtém ou define os estilos dos cantos da borda |
| [setDefaultCellBorder](#setDefaultCellBorder-com.aspose.pdf.BorderInfo-) | Obtém a borda padrão da célula; |
| [setDefaultCellPadding](#setDefaultCellPadding-com.aspose.pdf.MarginInfo-) | Define o preenchimento padrão da célula. |
| [setDefaultCellTextState](#setDefaultCellTextState-com.aspose.pdf.TextState-) | Define o estado de texto padrão da célula. |
| [setDefaultColumnWidth](#setDefaultColumnWidth-java.lang.String-) | Obtém a borda padrão da célula; |
| [setLeft](#setLeft-float-) | Define a coordenada esquerda da tabela. |
| [setRepeatingColumnsCount](#setRepeatingColumnsCount-int-) | Obtém ou define a contagem máxima de colunas para a tabela |
| [setRepeatingRowsCount](#setRepeatingRowsCount-int-) | Obtém a contagem de primeiras linhas repetidas em várias páginas |
| [setRepeatingRowsStyle](#setRepeatingRowsStyle-com.aspose.pdf.TextState-) | Obtém o estilo para linhas repetidas |
| [setTop](#setTop-float-) | Define a coordenada superior da tabela. |

### Table {#Table--}
```
public Table()
```

Construtor padrão

### deepClone {#deepClone--}
```
public Object deepClone()
```

/ * / * Importa um array unidimensional de dados na tabela. A importação coloca uma célula para cada item do array e / * começa a partir da linha e coluna definidas nos parâmetros. Durante a importação, se for detectado que as linhas necessárias / * ainda estão ausentes (ou seja, a tabela de destino é muito pequena para absorver todos os dados), as linhas necessárias serão criadas / * / *

**Returns:**
O objeto clonado

### drawRoundedRectangle {#drawRoundedRectangle-com.aspose.pdf.GraphInfo-com.aspose.pdf.Point-com.aspose.pdf.Point-java.util.List-double-}
Adiciona operadores para retângulo.

### getAlignment {#getAlignment--}
```
public final HorizontalAlignment getAlignment()
```

Obtém o alinhamento da tabela.

**Returns:**
Valor HorizontalAlignment @see HorizontalAlignment

### getBackgroundColor {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```

Obtém a cor de fundo da tabela

**Returns:**
Objeto Color

### getBorder {#getBorder--}
```
public final BorderInfo getBorder()
```

Obtém a borda.

**Returns:**
Objeto BorderInfo

### getBreakText {#getBreakText--}
```
public final TextFragment getBreakText()
```

Obtém o texto de quebra para a tabela

**Returns:**
objeto TextFragment

### getBroken {#getBroken--}
```
public final int getBroken()
```

Obtém ou define a quebra vertical da tabela;

**Returns:**
Valor TableBroken @see TableBroken

### getColumnAdjustment {#getColumnAdjustment--}
```
public final ColumnAdjustment getColumnAdjustment()
```

Obtém o ajuste de coluna da tabela.

**Returns:**
Valor ColumnAdjustment @see ColumnAdjustment

### getColumnWidth {#getColumnWidth-java.lang.String-}
Obter largura da coluna

### getColumnWidths {#getColumnWidths--}
```
public final String getColumnWidths()
```

Obtém as larguras das colunas da tabela.

**Returns:**
valor String

### getCornerStyle {#getCornerStyle--}
```
public final BorderCornerStyle getCornerStyle()
```

Obtém os estilos dos cantos da borda

**Returns:**
Valor BorderCornerStyle @see BorderCornerStyle

### getDefaultCellBorder {#getDefaultCellBorder--}
```
public final BorderInfo getDefaultCellBorder()
```

Obtém a borda padrão da célula;

**Returns:**
Objeto BorderInfo

### getDefaultCellPadding {#getDefaultCellPadding--}
```
public final MarginInfo getDefaultCellPadding()
```

Obtém o preenchimento padrão da célula.

**Returns:**
Objeto MarginInfo

### getDefaultCellTextState {#getDefaultCellTextState--}
```
public final TextState getDefaultCellTextState()
```

Obtém o estado de texto padrão da célula.

**Returns:**
Valor TextState

### getDefaultColumnWidth {#getDefaultColumnWidth--}
```
public final String getDefaultColumnWidth()
```

Obtém a borda padrão da célula;

**Returns:**
Objeto String

### getHeight {#getHeight--}
```
public double getHeight()
```

Obter altura.

**Returns:**
A altura da tabela

### getHeight {#getHeight-com.aspose.pdf.Page-}
Obter altura.

**Returns:**
A altura da tabela

### getLeft {#getLeft--}
```
public final float getLeft()
```

Obtém a coordenada esquerda da tabela.

**Returns:**
valor float

### getRepeatingColumnsCount {#getRepeatingColumnsCount--}
```
public final int getRepeatingColumnsCount()
```

Obtém ou define a contagem máxima de colunas para a tabela

**Returns:**
valor int

### getRepeatingRowsCount {#getRepeatingRowsCount--}
```
public final int getRepeatingRowsCount()
```

Obtém a contagem de primeiras linhas repetidas em várias páginas

**Returns:**
valor int

### getRepeatingRowsStyle {#getRepeatingRowsStyle--}
```
public final TextState getRepeatingRowsStyle()
```

Obtém o estilo para linhas repetidas

**Returns:**
Objeto TextState

### getRows {#getRows--}
```
public final Rows getRows()
```

Obtém as linhas da tabela.

**Returns:**
Objeto Rows

### getTop {#getTop--}
```
public final float getTop()
```

Obtém a coordenada superior da tabela.

**Returns:**
valor float

### getWidth {#getWidth--}
```
public double getWidth()
```

Obter largura.

**Returns:**
A largura da tabela

### isBordersIncluded {#isBordersIncluded--}
```
public final boolean isBordersIncluded()
```

Obtém borda incluída nas larguras das colunas.

**Returns:**
valor booleano

### isBroken {#isBroken--}
```
public final boolean isBroken()
```

Obtém se a tabela está quebrada - será truncada para a próxima página.

**Returns:**
valor booleano

### setAlignment {#setAlignment-com.aspose.pdf.HorizontalAlignment-}
Define o alinhamento da tabela.

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Define a cor de fundo da tabela

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
Define a borda.

### setBordersIncluded {#setBordersIncluded-boolean-}
```
public final void setBordersIncluded(boolean value)
```

Define borda incluída nas larguras das colunas.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setBreakText {#setBreakText-com.aspose.pdf.TextFragment-}
Define quebra de texto para a tabela

### setBroken {#setBroken-boolean-}
```
public final void setBroken(boolean value)
```

Define se a tabela está quebrada - será truncada para a próxima página.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setBroken {#setBroken-int-}
```
public final void setBroken(int value)
```

Obtém ou define a quebra vertical da tabela;

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | Valor TableBroken @see TableBroken |

### setColumnAdjustment {#setColumnAdjustment-com.aspose.pdf.ColumnAdjustment-}
Define o ajuste de coluna da tabela.

### setColumnTextState {#setColumnTextState-int-com.aspose.pdf.TextState-}
Define a altura.

### setColumnWidths {#setColumnWidths-java.lang.String-}
Obtém as larguras das colunas da tabela.

### setCornerStyle {#setCornerStyle-com.aspose.pdf.BorderCornerStyle-}
Obtém ou define os estilos dos cantos da borda

### setDefaultCellBorder {#setDefaultCellBorder-com.aspose.pdf.BorderInfo-}
Obtém a borda padrão da célula;

### setDefaultCellPadding {#setDefaultCellPadding-com.aspose.pdf.MarginInfo-}
Define o preenchimento padrão da célula.

### setDefaultCellTextState {#setDefaultCellTextState-com.aspose.pdf.TextState-}
Define o estado de texto padrão da célula.

### setDefaultColumnWidth {#setDefaultColumnWidth-java.lang.String-}
Obtém a borda padrão da célula;

### setLeft {#setLeft-float-}
```
public final void setLeft(float value)
```

Define a coordenada esquerda da tabela.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor float |

### setRepeatingColumnsCount {#setRepeatingColumnsCount-int-}
```
public final void setRepeatingColumnsCount(int value)
```

Obtém ou define a contagem máxima de colunas para a tabela

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |

### setRepeatingRowsCount {#setRepeatingRowsCount-int-}
```
public final void setRepeatingRowsCount(int value)
```

Obtém a contagem de primeiras linhas repetidas em várias páginas

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |

### setRepeatingRowsStyle {#setRepeatingRowsStyle-com.aspose.pdf.TextState-}
Obtém o estilo para linhas repetidas

### setTop {#setTop-float-}
```
public final void setTop(float value)
```

Define a coordenada superior da tabela.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor float |
