---
title: "TableElement"
linktitle: "TableElement"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa o elemento de estrutura Table na estrutura lógica."
type: docs
weight: 170
url: /pt/java/com.aspose.pdf.tagged.logicalstructure.elements.bls/tableelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableElement, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableElement

**All Implemented Interfaces:**
IAdjustPosition

```
public final class TableElement extends BLSElement implements IAdjustPosition
```

Representa o elemento de estrutura Table na estrutura lógica.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [TableElement](#TableElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-) | construtor apenas para uso interno |

## Métodos

| Método | Descrição |
| --- | --- |
| [adjustPosition](#adjustPosition-com.aspose.pdf.tagged.PositionSettings-) | Ajustar posição. |
| [createTBody](#createTBody--) | Cria {@link TableTHeadElement} e o adiciona à tabela atual. |
| [createTFoot](#createTFoot--) | Cria {@link TableTFootElement} e o adiciona à tabela atual. |
| [createTHead](#createTHead--) | Cria {@link TableTHeadElement} e o adiciona à tabela atual. |
| [getAlignment](#getAlignment--) | Obtém ou define o alinhamento da tabela. |
| [getBackgroundColor](#getBackgroundColor--) | Obtém ou define a cor de fundo da tabela. |
| [getBorder](#getBorder--) | Obtém ou define a borda da tabela. |
| [getBroken](#getBroken--) | Obtém ou define a quebra vertical da tabela; |
| [getColumnAdjustment](#getColumnAdjustment--) | Obtém ou define o ajuste de coluna da tabela. |
| [getColumnWidths](#getColumnWidths--) | Obtém as larguras das colunas da tabela. |
| [getCornerStyle](#getCornerStyle--) | Obtém ou define os estilos dos cantos da borda |
| [getDefaultCellBorder](#getDefaultCellBorder--) | Obtém a borda padrão da célula. |
| [getDefaultCellPadding](#getDefaultCellPadding--) | Obtém ou define o preenchimento padrão da célula. |
| [getDefaultCellTextState](#getDefaultCellTextState--) | Obtém ou define o estado de texto padrão da célula. |
| [getDefaultColumnWidth](#getDefaultColumnWidth--) | Obtém ou define a largura padrão da coluna. |
| [getLeft](#getLeft--) | Obtém ou define a coordenada esquerda da tabela. |
| [getRepeatingColumnsCount](#getRepeatingColumnsCount--) | Obtém ou define a contagem máxima de colunas da tabela. |
| [getRepeatingRowsCount](#getRepeatingRowsCount--) | Obtém a contagem de linhas iniciais repetidas em várias páginas. |
| [getRepeatingRowsStyle](#getRepeatingRowsStyle--) | Obtém o estilo para linhas repetidas. |
| [getTable](#getTable--) |  |
| [getTop](#getTop--) | Obtém ou define a coordenada superior da tabela. |
| [isBordersIncluded](#isBordersIncluded--) | Obtém ou define a borda incluída nas larguras das colunas. |
| [isBroken](#isBroken--) | Obtém ou define se a tabela está quebrada - será truncada na próxima página. |
| [preSave](#preSave--) |  |
| [setAlignment](#setAlignment-com.aspose.pdf.HorizontalAlignment-) | Obtém ou define o alinhamento da tabela. |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Obtém ou define a cor de fundo da tabela. |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | Obtém ou define a borda da tabela. |
| [setBordersIncluded](#setBordersIncluded-boolean-) | Obtém ou define a borda incluída nas larguras das colunas. |
| [setBroken](#setBroken-boolean-) | Obtém ou define se a tabela está quebrada - será truncada na próxima página. |
| [setBroken](#setBroken-int-) | Obtém ou define a quebra vertical da tabela; |
| [setColumnAdjustment](#setColumnAdjustment-com.aspose.pdf.ColumnAdjustment-) | Obtém ou define o ajuste de coluna da tabela. |
| [setColumnWidths](#setColumnWidths-java.lang.String-) | Obtém as larguras das colunas da tabela. |
| [setCornerStyle](#setCornerStyle-com.aspose.pdf.BorderCornerStyle-) | Obtém ou define os estilos dos cantos da borda |
| [setDefaultCellBorder](#setDefaultCellBorder-com.aspose.pdf.BorderInfo-) | Obtém a borda padrão da célula. |
| [setDefaultCellPadding](#setDefaultCellPadding-com.aspose.pdf.MarginInfo-) | Obtém ou define o preenchimento padrão da célula. |
| [setDefaultCellTextState](#setDefaultCellTextState-com.aspose.pdf.TextState-) | Obtém ou define o estado de texto padrão da célula. |
| [setDefaultColumnWidth](#setDefaultColumnWidth-java.lang.String-) | Obtém ou define a largura padrão da coluna. |
| [setLeft](#setLeft-float-) | Obtém ou define a coordenada esquerda da tabela. |
| [setRepeatingColumnsCount](#setRepeatingColumnsCount-int-) | Obtém ou define a contagem máxima de colunas da tabela. |
| [setRepeatingRowsCount](#setRepeatingRowsCount-int-) | Obtém a contagem de linhas iniciais repetidas em várias páginas. |
| [setRepeatingRowsStyle](#setRepeatingRowsStyle-com.aspose.pdf.TextState-) | Obtém o estilo para linhas repetidas. |
| [setTop](#setTop-float-) | Obtém ou define a coordenada superior da tabela. |

### TableElement {#TableElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-}
construtor apenas para uso interno

### adjustPosition {#adjustPosition-com.aspose.pdf.tagged.PositionSettings-}
Ajustar posição.

### createTBody {#createTBody--}
```
public final TableTBodyElement createTBody()
```

Cria {@link TableTHeadElement} e o adiciona à tabela atual.

**Returns:**
Elemento de estrutura criado.

### createTFoot {#createTFoot--}
```
public final TableTFootElement createTFoot()
```

Cria {@link TableTFootElement} e o adiciona à tabela atual.

**Returns:**
Elemento de estrutura criado.

### createTHead {#createTHead--}
```
public final TableTHeadElement createTHead()
```

Cria {@link TableTHeadElement} e o adiciona à tabela atual.

**Returns:**
Elemento de estrutura criado.

### getAlignment {#getAlignment--}
```
public final HorizontalAlignment getAlignment()
```

Obtém ou define o alinhamento da tabela.

**Returns:**
Elemento HorizontalAlignment

### getBackgroundColor {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```

Obtém ou define a cor de fundo da tabela.

**Returns:**
Instância de Color

### getBorder {#getBorder--}
```
public final BorderInfo getBorder()
```

Obtém ou define a borda da tabela.

**Returns:**
Instância BorderInfo

### getBroken {#getBroken--}
```
public final int getBroken()
```

Obtém ou define a quebra vertical da tabela;

**Returns:**
TableBroken elemento

### getColumnAdjustment {#getColumnAdjustment--}
```
public final ColumnAdjustment getColumnAdjustment()
```

Obtém ou define o ajuste de coluna da tabela.

**Returns:**
elemento ColumnAdjustment

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

Obtém ou define os estilos dos cantos da borda

**Returns:**
elemento BorderCornerStyle

### getDefaultCellBorder {#getDefaultCellBorder--}
```
public final BorderInfo getDefaultCellBorder()
```

Obtém a borda padrão da célula.

**Returns:**
Instância BorderInfo

### getDefaultCellPadding {#getDefaultCellPadding--}
```
public final MarginInfo getDefaultCellPadding()
```

Obtém ou define o preenchimento padrão da célula.

**Returns:**
Instância MarginInfo

### getDefaultCellTextState {#getDefaultCellTextState--}
```
public final TextState getDefaultCellTextState()
```

Obtém ou define o estado de texto padrão da célula.

**Returns:**
instância TextState

### getDefaultColumnWidth {#getDefaultColumnWidth--}
```
public final String getDefaultColumnWidth()
```

Obtém ou define a largura padrão da coluna.

**Returns:**
valor String

### getLeft {#getLeft--}
```
public final float getLeft()
```

Obtém ou define a coordenada esquerda da tabela.

**Returns:**
valor float

### getRepeatingColumnsCount {#getRepeatingColumnsCount--}
```
public final int getRepeatingColumnsCount()
```

Obtém ou define a contagem máxima de colunas da tabela.

**Returns:**
valor int

### getRepeatingRowsCount {#getRepeatingRowsCount--}
```
public final int getRepeatingRowsCount()
```

Obtém a contagem de linhas iniciais repetidas em várias páginas.

**Returns:**
valor int

### getRepeatingRowsStyle {#getRepeatingRowsStyle--}
```
public final TextState getRepeatingRowsStyle()
```

Obtém o estilo para linhas repetidas.

**Returns:**
instância TextState

### getTable {#getTable--}
```
public final Table getTable()
```



### getTop {#getTop--}
```
public final float getTop()
```

Obtém ou define a coordenada superior da tabela.

**Returns:**
valor float

### isBordersIncluded {#isBordersIncluded--}
```
public final boolean isBordersIncluded()
```

Obtém ou define a borda incluída nas larguras das colunas.

**Returns:**
valor booleano

### isBroken {#isBroken--}
```
public final boolean isBroken()
```

Obtém ou define se a tabela está quebrada - será truncada na próxima página.

**Returns:**
valor booleano

### preSave {#preSave--}
```
public void preSave()
```



### setAlignment {#setAlignment-com.aspose.pdf.HorizontalAlignment-}
Obtém ou define o alinhamento da tabela.

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Obtém ou define a cor de fundo da tabela.

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
Obtém ou define a borda da tabela.

### setBordersIncluded {#setBordersIncluded-boolean-}
```
public final void setBordersIncluded(boolean value)
```

Obtém ou define a borda incluída nas larguras das colunas.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setBroken {#setBroken-boolean-}
```
public final void setBroken(boolean value)
```

Obtém ou define se a tabela está quebrada - será truncada na próxima página.

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
| valor |  | TableBroken elemento |

### setColumnAdjustment {#setColumnAdjustment-com.aspose.pdf.ColumnAdjustment-}
Obtém ou define o ajuste de coluna da tabela.

### setColumnWidths {#setColumnWidths-java.lang.String-}
Obtém as larguras das colunas da tabela.

### setCornerStyle {#setCornerStyle-com.aspose.pdf.BorderCornerStyle-}
Obtém ou define os estilos dos cantos da borda

### setDefaultCellBorder {#setDefaultCellBorder-com.aspose.pdf.BorderInfo-}
Obtém a borda padrão da célula.

### setDefaultCellPadding {#setDefaultCellPadding-com.aspose.pdf.MarginInfo-}
Obtém ou define o preenchimento padrão da célula.

### setDefaultCellTextState {#setDefaultCellTextState-com.aspose.pdf.TextState-}
Obtém ou define o estado de texto padrão da célula.

### setDefaultColumnWidth {#setDefaultColumnWidth-java.lang.String-}
Obtém ou define a largura padrão da coluna.

### setLeft {#setLeft-float-}
```
public final void setLeft(float value)
```

Obtém ou define a coordenada esquerda da tabela.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor float |

### setRepeatingColumnsCount {#setRepeatingColumnsCount-int-}
```
public final void setRepeatingColumnsCount(int value)
```

Obtém ou define a contagem máxima de colunas da tabela.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |

### setRepeatingRowsCount {#setRepeatingRowsCount-int-}
```
public final void setRepeatingRowsCount(int value)
```

Obtém a contagem de linhas iniciais repetidas em várias páginas.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |

### setRepeatingRowsStyle {#setRepeatingRowsStyle-com.aspose.pdf.TextState-}
Obtém o estilo para linhas repetidas.

### setTop {#setTop-float-}
```
public final void setTop(float value)
```

Obtém ou define a coordenada superior da tabela.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor float |
