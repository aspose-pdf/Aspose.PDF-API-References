---
title: "TableCellElement"
linktitle: "TableCellElement"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa uma classe base para elementos de célula de tabela (TH e TD) na estrutura lógica."
type: docs
weight: 150
url: /pt/java/com.aspose.pdf.tagged.logicalstructure.elements.bls/tablecellelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableCellElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableCellElement, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableCellElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableCellElement

**All Implemented Interfaces:**
IAdjustPosition, ITextElement

```
public abstract class TableCellElement extends TableChildElement implements ITextElement , IAdjustPosition
```

Representa uma classe base para elementos de célula de tabela (TH e TD) na estrutura lógica.

## Métodos

| Método | Descrição |
| --- | --- |
| [adjustPosition](#adjustPosition-com.aspose.pdf.tagged.PositionSettings-) | Ajustar posição. |
| [getAlignment](#getAlignment--) | Obtém ou define o alinhamento da célula. |
| [getBackgroundColor](#getBackgroundColor--) | Obtém ou define a cor de fundo da célula. |
| [getBorder](#getBorder--) | Obtém ou define a borda da célula. |
| [getCell](#getCell--) |  |
| [getColSpan](#getColSpan--) | Obtém ou define a extensão da coluna. |
| [getDefaultCellTextState](#getDefaultCellTextState--) | Obtém ou define o estado de texto padrão da célula. |
| [getMargin](#getMargin--) | Obtém ou define o preenchimento. |
| [getRowSpan](#getRowSpan--) | Obtém ou define a extensão da linha. |
| [getStructureTextState](#getStructureTextState--) | Obtém o objeto {@code /Aspose.Pdf.LogicalStructure.StructureTextState} para o elemento atual. Valor: objeto {@code /Aspose.Pdf.LogicalStructure.StructureTextState} para o elemento atual. |
| [getVerticalAlignment](#getVerticalAlignment--) | Obtém ou define o alinhamento vertical. |
| [isNoBorder](#isNoBorder--) | Obtém ou define se a célula tem borda. |
| [isWordWrapped](#isWordWrapped--) | Obtém ou define se o texto da célula está com quebra de linha. |
| [preSave](#preSave--) |  |
| [setAlignment](#setAlignment-com.aspose.pdf.HorizontalAlignment-) | Obtém ou define o alinhamento da célula. |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Obtém ou define a cor de fundo da célula. |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | Obtém ou define a borda da célula. |
| [setColSpan](#setColSpan-int-) | Obtém ou define a extensão da coluna. |
| [setDefaultCellTextState](#setDefaultCellTextState-com.aspose.pdf.TextState-) | Obtém ou define o estado de texto padrão da célula. |
| [setMargin](#setMargin-com.aspose.pdf.MarginInfo-) | Obtém ou define o preenchimento. |
| [setNoBorder](#setNoBorder-boolean-) | Obtém ou define se a célula tem borda. |
| [setRowSpan](#setRowSpan-int-) | Obtém ou define a extensão da linha. |
| [setText](#setText-java.lang.String-) | Anexa conteúdo de texto ao elemento de texto atual. |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Obtém ou define o alinhamento vertical. |
| [setWordWrapped](#setWordWrapped-boolean-) | Obtém ou define se o texto da célula está com quebra de linha. |

### adjustPosition {#adjustPosition-com.aspose.pdf.tagged.PositionSettings-}
Ajustar posição.

### getAlignment {#getAlignment--}
```
public final HorizontalAlignment getAlignment()
```

Obtém ou define o alinhamento da célula.

**Returns:**
Elemento HorizontalAlignment

### getBackgroundColor {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```

Obtém ou define a cor de fundo da célula.

**Returns:**
Instância de Color

### getBorder {#getBorder--}
```
public final BorderInfo getBorder()
```

Obtém ou define a borda da célula.

**Returns:**
Instância BorderInfo

### getCell {#getCell--}
```
public final Cell getCell()
```



### getColSpan {#getColSpan--}
```
public final int getColSpan()
```

Obtém ou define a extensão da coluna.

**Returns:**
valor int

### getDefaultCellTextState {#getDefaultCellTextState--}
```
public final TextState getDefaultCellTextState()
```

Obtém ou define o estado de texto padrão da célula.

**Returns:**
instância TextState

### getMargin {#getMargin--}
```
public final MarginInfo getMargin()
```

Obtém ou define o preenchimento.

**Returns:**
Instância MarginInfo

### getRowSpan {#getRowSpan--}
```
public final int getRowSpan()
```

Obtém ou define a extensão da linha.

**Returns:**
valor int

### getStructureTextState {#getStructureTextState--}
```
public final StructureTextState getStructureTextState()
```

Obtém o objeto {@code /Aspose.Pdf.LogicalStructure.StructureTextState} para o elemento atual. Valor: objeto {@code /Aspose.Pdf.LogicalStructure.StructureTextState} para o elemento atual.

**Returns:**
Instância de StructureTextState

### getVerticalAlignment {#getVerticalAlignment--}
```
public final VerticalAlignment getVerticalAlignment()
```

Obtém ou define o alinhamento vertical.

**Returns:**
Elemento VerticalAlignment

### isNoBorder {#isNoBorder--}
```
public final boolean isNoBorder()
```

Obtém ou define se a célula tem borda.

**Returns:**
valor booleano

### isWordWrapped {#isWordWrapped--}
```
public final boolean isWordWrapped()
```

Obtém ou define se o texto da célula está com quebra de linha.

**Returns:**
valor booleano

### preSave {#preSave--}
```
public void preSave()
```



### setAlignment {#setAlignment-com.aspose.pdf.HorizontalAlignment-}
Obtém ou define o alinhamento da célula.

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Obtém ou define a cor de fundo da célula.

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
Obtém ou define a borda da célula.

### setColSpan {#setColSpan-int-}
```
public final void setColSpan(int value)
```

Obtém ou define a extensão da coluna.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |

### setDefaultCellTextState {#setDefaultCellTextState-com.aspose.pdf.TextState-}
Obtém ou define o estado de texto padrão da célula.

### setMargin {#setMargin-com.aspose.pdf.MarginInfo-}
Obtém ou define o preenchimento.

### setNoBorder {#setNoBorder-boolean-}
```
public final void setNoBorder(boolean value)
```

Obtém ou define se a célula tem borda.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setRowSpan {#setRowSpan-int-}
```
public final void setRowSpan(int value)
```

Obtém ou define a extensão da linha.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |

### setText {#setText-java.lang.String-}
Anexa conteúdo de texto ao elemento de texto atual.

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Obtém ou define o alinhamento vertical.

### setWordWrapped {#setWordWrapped-boolean-}
```
public final void setWordWrapped(boolean value)
```

Obtém ou define se o texto da célula está com quebra de linha.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |
