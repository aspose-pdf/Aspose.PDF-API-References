---
title: "TableTRElement"
linktitle: "TableTRElement"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa o elemento de estrutura TR na estrutura lógica da tabela."
type: docs
weight: 240
url: /pt/java/com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletrelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableTRElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableTRElement, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableTRElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableTRElement

```
public final class TableTRElement extends TableChildElement
```

Representa o elemento de estrutura TR na estrutura lógica da tabela.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [TableTRElement](#TableTRElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-) | construtor apenas para uso interno |

## Métodos

| Método | Descrição |
| --- | --- |
| [createTD](#createTD--) | Cria {@link TableTHElement} e o adiciona à tabela atual. |
| [createTH](#createTH--) | Cria {@link TableTHElement} e o adiciona à tabela atual. |
| [getBackgroundColor](#getBackgroundColor--) | Obtém ou define a cor de fundo da linha. |
| [getBorder](#getBorder--) | Obtém ou define a borda da linha. |
| [getDefaultCellBorder](#getDefaultCellBorder--) | Obtém a borda padrão da célula. |
| [getDefaultCellPadding](#getDefaultCellPadding--) | Obtém ou define a margem padrão para as células da linha. |
| [getDefaultCellTextState](#getDefaultCellTextState--) | Obtém ou define o estado de texto padrão para as células da linha |
| [getFixedRowHeight](#getFixedRowHeight--) | Obtém a altura fixa da linha – a linha pode ter altura fixa. |
| [getMinRowHeight](#getMinRowHeight--) | Obtém a altura da linha. |
| [getVerticalAlignment](#getVerticalAlignment--) | Obtém ou define o alinhamento vertical. |
| [isInNewPage](#isInNewPage--) | Obtém se a linha fixa está em nova página – a página com esta propriedade deve ser impressa na página seguinte. Padrão false. |
| [isRowBroken](#isRowBroken--) | Obtém se a linha pode ser quebrada entre duas páginas. |
| [preSave](#preSave--) |  |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Obtém ou define a cor de fundo da linha. |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | Obtém ou define a borda da linha. |
| [setDefaultCellBorder](#setDefaultCellBorder-com.aspose.pdf.BorderInfo-) | Obtém a borda padrão da célula. |
| [setDefaultCellPadding](#setDefaultCellPadding-com.aspose.pdf.MarginInfo-) | Obtém ou define a margem padrão para as células da linha. |
| [setDefaultCellTextState](#setDefaultCellTextState-com.aspose.pdf.TextState-) | Obtém ou define o estado de texto padrão para as células da linha |
| [setFixedRowHeight](#setFixedRowHeight-double-) | Obtém a altura fixa da linha – a linha pode ter altura fixa. |
| [setInNewPage](#setInNewPage-boolean-) | Obtém se a linha fixa está em nova página – a página com esta propriedade deve ser impressa na página seguinte. Padrão false. |
| [setMinRowHeight](#setMinRowHeight-double-) | Obtém a altura da linha. |
| [setRowBroken](#setRowBroken-boolean-) | Obtém se a linha pode ser quebrada entre duas páginas. |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Obtém ou define o alinhamento vertical. |

### TableTRElement {#TableTRElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-}
construtor apenas para uso interno

### createTD {#createTD--}
```
public final TableTDElement createTD()
```

Cria {@link TableTHElement} e o adiciona à tabela atual.

**Returns:**
Elemento de estrutura criado.

### createTH {#createTH--}
```
public final TableTHElement createTH()
```

Cria {@link TableTHElement} e o adiciona à tabela atual.

**Returns:**
Elemento de estrutura criado.

### getBackgroundColor {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```

Obtém ou define a cor de fundo da linha.

**Returns:**
Instância de Color

### getBorder {#getBorder--}
```
public final BorderInfo getBorder()
```

Obtém ou define a borda da linha.

**Returns:**
Instância BorderInfo

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

Obtém ou define a margem padrão para as células da linha.

**Returns:**
Instância MarginInfo

### getDefaultCellTextState {#getDefaultCellTextState--}
```
public final TextState getDefaultCellTextState()
```

Obtém ou define o estado de texto padrão para as células da linha

**Returns:**
instância TextState

### getFixedRowHeight {#getFixedRowHeight--}
```
public final double getFixedRowHeight()
```

Obtém a altura fixa da linha – a linha pode ter altura fixa.

**Returns:**
valor double

### getMinRowHeight {#getMinRowHeight--}
```
public final double getMinRowHeight()
```

Obtém a altura da linha.

**Returns:**
valor double

### getVerticalAlignment {#getVerticalAlignment--}
```
public final VerticalAlignment getVerticalAlignment()
```

Obtém ou define o alinhamento vertical.

**Returns:**
Elemento VerticalAlignment

### isInNewPage {#isInNewPage--}
```
public final boolean isInNewPage()
```

Obtém se a linha fixa está em nova página – a página com esta propriedade deve ser impressa na página seguinte. Padrão false.

**Returns:**
valor booleano

### isRowBroken {#isRowBroken--}
```
public final boolean isRowBroken()
```

Obtém se a linha pode ser quebrada entre duas páginas.

**Returns:**
valor booleano

### preSave {#preSave--}
```
public void preSave()
```



### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Obtém ou define a cor de fundo da linha.

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
Obtém ou define a borda da linha.

### setDefaultCellBorder {#setDefaultCellBorder-com.aspose.pdf.BorderInfo-}
Obtém a borda padrão da célula.

### setDefaultCellPadding {#setDefaultCellPadding-com.aspose.pdf.MarginInfo-}
Obtém ou define a margem padrão para as células da linha.

### setDefaultCellTextState {#setDefaultCellTextState-com.aspose.pdf.TextState-}
Obtém ou define o estado de texto padrão para as células da linha

### setFixedRowHeight {#setFixedRowHeight-double-}
```
public final void setFixedRowHeight(double value)
```

Obtém a altura fixa da linha – a linha pode ter altura fixa.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### setInNewPage {#setInNewPage-boolean-}
```
public final void setInNewPage(boolean value)
```

Obtém se a linha fixa está em nova página – a página com esta propriedade deve ser impressa na página seguinte. Padrão false.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setMinRowHeight {#setMinRowHeight-double-}
```
public final void setMinRowHeight(double value)
```

Obtém a altura da linha.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### setRowBroken {#setRowBroken-boolean-}
```
public final void setRowBroken(boolean value)
```

Obtém se a linha pode ser quebrada entre duas páginas.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Obtém ou define o alinhamento vertical.
