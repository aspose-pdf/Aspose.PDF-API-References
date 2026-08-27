---
title: "Row"
linktitle: "Row"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa uma linha da tabela."
type: docs
weight: 4330
url: /pt/java/com.aspose.pdf/row/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Row

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class Row extends Object implements com.aspose.ms.System.ICloneable
```

Representa uma linha da tabela.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [Row](#Row--) | Inicializa uma nova instância da classe Row. |

## Métodos

| Método | Descrição |
| --- | --- |
| [deepClone](#deepClone--) | Clone a linha. |
| [getBackgroundColor](#getBackgroundColor--) | Obtém a cor de fundo. |
| [getBorder](#getBorder--) | Obtém a borda. |
| [getCells](#getCells--) | Obtém o getCells() da linha. |
| [getDefaultCellBorder](#getDefaultCellBorder--) | Obtém a borda padrão da célula; |
| [getDefaultCellPadding](#getDefaultCellPadding--) | Obtém a margem padrão para row getCells() |
| [getDefaultCellTextState](#getDefaultCellTextState--) | Obtém ou define o estado de texto padrão para row getCells() Obtém o estado de texto padrão para row getCells() |
| [getFixedRowHeight](#getFixedRowHeight--) | Obtém a altura fixa da linha - a linha pode ter altura fixa; |
| [getMinRowHeight](#getMinRowHeight--) | Obtém a altura da linha; |
| [getVerticalAlignment](#getVerticalAlignment--) | Obtém ou define o alinhamento vertical. |
| [isInNewPage](#isInNewPage--) | Obtém se a linha fixa está em nova página - a página com esta propriedade deve ser impressa na próxima página Padrão false; |
| [isRowBroken](#isRowBroken--) | Obtém se a linha pode ser quebrada entre duas páginas |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Define a cor de fundo. |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | Define a borda. |
| [setCells](#setCells-com.aspose.pdf.Cells-) | Define o getCells() da linha. |
| [setDefaultCellBorder](#setDefaultCellBorder-com.aspose.pdf.BorderInfo-) | Define a borda padrão da célula; |
| [setDefaultCellPadding](#setDefaultCellPadding-com.aspose.pdf.MarginInfo-) | Define a margem padrão para row getCells() |
| [setDefaultCellTextState](#setDefaultCellTextState-com.aspose.pdf.TextState-) | Define o estado de texto padrão para row getCells() |
| [setFixedRowHeight](#setFixedRowHeight-double-) | Define a altura fixa da linha - a linha pode ter altura fixa; |
| [setInNewPage](#setInNewPage-boolean-) | Define se a linha pode ser quebrada entre duas páginas |
| [setMinRowHeight](#setMinRowHeight-double-) | Define a altura da linha; |
| [setRowBroken](#setRowBroken-boolean-) | Define se a linha pode ser quebrada entre duas páginas |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Obtém ou define o alinhamento vertical. |

### Row {#Row--}
```
public Row()
```

Inicializa uma nova instância da classe Row.

### deepClone {#deepClone--}
```
public Object deepClone()
```

Clone a linha.

**Returns:**
O objeto clonado

### getBackgroundColor {#getBackgroundColor--}
```
public Color getBackgroundColor()
```

Obtém a cor de fundo.

**Returns:**
Valor da cor

### getBorder {#getBorder--}
```
public BorderInfo getBorder()
```

Obtém a borda.

**Returns:**
Valor BorderInfo

### getCells {#getCells--}
```
public Cells getCells()
```

Obtém o getCells() da linha.

**Returns:**
Valor getCells()

### getDefaultCellBorder {#getDefaultCellBorder--}
```
public BorderInfo getDefaultCellBorder()
```

Obtém a borda padrão da célula;

**Returns:**
Valor BorderInfo

### getDefaultCellPadding {#getDefaultCellPadding--}
```
public MarginInfo getDefaultCellPadding()
```

Obtém a margem padrão para row getCells()

**Returns:**
Valor MarginInfo

### getDefaultCellTextState {#getDefaultCellTextState--}
```
public TextState getDefaultCellTextState()
```

Obtém ou define o estado de texto padrão para row getCells() Obtém o estado de texto padrão para row getCells()

**Returns:**
Valor TextState

### getFixedRowHeight {#getFixedRowHeight--}
```
public double getFixedRowHeight()
```

Obtém a altura fixa da linha - a linha pode ter altura fixa;

**Returns:**
valor double

### getMinRowHeight {#getMinRowHeight--}
```
public double getMinRowHeight()
```

Obtém a altura da linha;

**Returns:**
valor double

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

Obtém ou define o alinhamento vertical.

**Returns:**
Elemento VerticalAlignment @see VerticalAlignment

### isInNewPage {#isInNewPage--}
```
public boolean isInNewPage()
```

Obtém se a linha fixa está em nova página - a página com esta propriedade deve ser impressa na próxima página Padrão false;

**Returns:**
valor booleano

### isRowBroken {#isRowBroken--}
```
public boolean isRowBroken()
```

Obtém se a linha pode ser quebrada entre duas páginas

**Returns:**
valor booleano

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Define a cor de fundo.

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
Define a borda.

### setCells {#setCells-com.aspose.pdf.Cells-}
Define o getCells() da linha.

### setDefaultCellBorder {#setDefaultCellBorder-com.aspose.pdf.BorderInfo-}
Define a borda padrão da célula;

### setDefaultCellPadding {#setDefaultCellPadding-com.aspose.pdf.MarginInfo-}
Define a margem padrão para row getCells()

### setDefaultCellTextState {#setDefaultCellTextState-com.aspose.pdf.TextState-}
Define o estado de texto padrão para row getCells()

### setFixedRowHeight {#setFixedRowHeight-double-}
```
public void setFixedRowHeight(double value)
```

Define a altura fixa da linha - a linha pode ter altura fixa;

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### setInNewPage {#setInNewPage-boolean-}
```
public void setInNewPage(boolean value)
```

Define se a linha pode ser quebrada entre duas páginas

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setMinRowHeight {#setMinRowHeight-double-}
```
public void setMinRowHeight(double value)
```

Define a altura da linha;

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### setRowBroken {#setRowBroken-boolean-}
```
public void setRowBroken(boolean value)
```

Define se a linha pode ser quebrada entre duas páginas

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Obtém ou define o alinhamento vertical.
