---
title: "StructureTextState"
linktitle: "StructureTextState"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa as configurações de estado de texto para Elementos de Estrutura de Texto e TaggedContent (ITextElement, ITaggedContent)"
type: docs
weight: 120
url: /pt/java/com.aspose.pdf.tagged.logicalstructure.elements/structuretextstate/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.StructureTextState

```
public class StructureTextState extends Object
```

Representa as configurações de estado de texto para Elementos de Estrutura de Texto e TaggedContent (ITextElement, ITaggedContent)

## Construtores

| Construtor | Descrição |
| --- | --- |
| [StructureTextState](#StructureTextState--) | Construtor padrão |

## Métodos

| Método | Descrição |
| --- | --- |
| [createTextState](#createTextState--) | Criar estado de texto |
| [getBackgroundColor](#getBackgroundColor--) | Obtém ou define a cor de fundo do texto. Pode ser nulo. Use null para herdar a propriedade {@code BackgroundColor} do elemento de estrutura pai. |
| [getCharacterSpacing](#getCharacterSpacing--) | Obtém ou define o espaçamento entre caracteres do texto. Pode ser nulo. Use null para herdar a propriedade {@code CharacterSpacing} do elemento de estrutura pai. |
| [getFont](#getFont--) | Obtém ou define a fonte do texto. Pode ser nulo. Use null para herdar a propriedade {@code Font} do elemento de estrutura pai. |
| [getFontSize](#getFontSize--) | Obtém ou define o tamanho da fonte do texto. Pode ser nulo. Use null para herdar a propriedade {@code FontSize} do elemento de estrutura pai. |
| [getFontStyle](#getFontStyle--) | Obtém ou define o estilo da fonte do texto. Pode ser nulo. Use null para herdar a propriedade {@code FontStyle} do elemento de estrutura pai. |
| [getForegroundColor](#getForegroundColor--) | Obtém ou define a cor de primeiro plano do texto. Pode ser nulo. Use null para herdar a propriedade {@code ForegroundColor} do elemento de estrutura pai. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | Obtém ou define um alinhamento horizontal do parágrafo |
| [getHorizontalScaling](#getHorizontalScaling--) | Obtém ou define a escala horizontal do texto. Pode ser nulo. Use null para herdar a propriedade {@code HorizontalScaling} do elemento de estrutura pai. |
| [getLineSpacing](#getLineSpacing--) | Obtém ou define o espaçamento entre linhas do texto. Pode ser nulo. Use null para herdar a propriedade {@code LineSpacing} do elemento de estrutura pai. |
| [getMarginInfo](#getMarginInfo--) | Obtém ou define a margem para o elemento de estrutura de bloco. |
| [getStrikeOut](#getStrikeOut--) | Obtém ou define o tachado do texto. Pode ser nulo. Use null para herdar a propriedade {@code StrikeOut} do elemento de estrutura pai. |
| [getSubscript](#getSubscript--) | Obtém ou define o subscrito do texto. Pode ser nulo. Use null para herdar a propriedade {@code Subscript} do elemento de estrutura pai. |
| [getSuperscript](#getSuperscript--) | Obtém ou define o sobrescrito do texto. Pode ser nulo. Use null para herdar a propriedade {@code Superscript} do elemento de estrutura pai. |
| [getUnderline](#getUnderline--) | Obtém ou define o sublinhado do texto. Pode ser nulo. Use null para herdar a propriedade {@code Underline} do elemento de estrutura pai. |
| [getVerticalAlignment](#getVerticalAlignment--) | Obtém ou define um alinhamento vertical do parágrafo |
| [getWordSpacing](#getWordSpacing--) | Obtém ou define o espaçamento entre palavras do texto. Pode ser nulo. Use null para herdar a propriedade {@code WordSpacing} do elemento de estrutura pai. |
| [isFirstParagraphInColumn](#isFirstParagraphInColumn--) | Obtém ou define um valor booleano que indica se este parágrafo ficará na próxima coluna. O padrão é falso. |
| [isInLineParagraph](#isInLineParagraph--) | Obtém ou define se o parágrafo está em linha. O padrão é falso. |
| [isInNewPage](#isInNewPage--) | Obtém ou define um valor booleano que força este parágrafo a ser gerado em uma nova página. O padrão é falso. |
| [isKeptWithNext](#isKeptWithNext--) | Obtém ou define um valor booleano que indica se o parágrafo atual permanece na mesma página junto com o próximo parágrafo. O padrão é falso. |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Obtém ou define a cor de fundo do texto. Pode ser nulo. Use null para herdar a propriedade {@code BackgroundColor} do elemento de estrutura pai. |
| [setCharacterSpacing](#setCharacterSpacing-com.aspose.ms.System.Nullable-) | Obtém ou define o espaçamento entre caracteres do texto. |
| [setFont](#setFont-com.aspose.pdf.Font-) | Obtém ou define a fonte do texto. Pode ser nulo. Use null para herdar a propriedade {@code Font} do elemento de estrutura pai. |
| [setFontSize](#setFontSize-com.aspose.ms.System.Nullable-) | Obtém ou define o tamanho da fonte do texto. |
| [setFontStyle](#setFontStyle-com.aspose.ms.System.Nullable-) | Obtém ou define o estilo da fonte do texto. |
| [setForegroundColor](#setForegroundColor-com.aspose.pdf.Color-) | Obtém ou define a cor de primeiro plano do texto. Pode ser nulo. Use null para herdar a propriedade {@code ForegroundColor} do elemento de estrutura pai. |
| [setHorizontalScaling](#setHorizontalScaling-com.aspose.ms.System.Nullable-) | Obtém ou define a escala horizontal do texto. |
| [setLineSpacing](#setLineSpacing-com.aspose.ms.System.Nullable-) | Obtém ou define o espaçamento entre linhas do texto. |
| [setMarginInfo](#setMarginInfo-com.aspose.pdf.MarginInfo-) | Obtém ou define a margem para o elemento de estrutura de bloco. |
| [setStrikeOut](#setStrikeOut-com.aspose.ms.System.Nullable-) | Obtém ou define o tachado do texto. |
| [setSubscript](#setSubscript-com.aspose.ms.System.Nullable-) | Obtém ou define o subscrito do texto. |
| [setSuperscript](#setSuperscript-com.aspose.ms.System.Nullable-) | Obtém ou define o sobrescrito do texto. |
| [setUnderline](#setUnderline-com.aspose.ms.System.Nullable-) | Obtém ou define o sublinhado do texto. |
| [setWordSpacing](#setWordSpacing-com.aspose.ms.System.Nullable-) | Obtém ou define o espaçamento entre palavras do texto. |
| [update](#update-com.aspose.pdf.tagged.logicalstructure.elements.StructureTextState-) | Atualizar elementos |

### StructureTextState {#StructureTextState--}
```
public StructureTextState()
```

Construtor padrão

### createTextState {#createTextState--}
```
public final TextState createTextState()
```

Criar estado de texto

**Returns:**
instância TextState

### getBackgroundColor {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```

Obtém ou define a cor de fundo do texto. Pode ser nulo. Use null para herdar a propriedade {@code BackgroundColor} do elemento de estrutura pai.

**Returns:**
Instância de Color

### getCharacterSpacing {#getCharacterSpacing--}
```
public final com.aspose.ms.System.Nullable< Float > getCharacterSpacing()
```

Obtém ou define o espaçamento entre caracteres do texto. Pode ser nulo. Use null para herdar a propriedade {@code CharacterSpacing} do elemento de estrutura pai.

**Returns:**
Array de float

### getFont {#getFont--}
```
public final Font getFont()
```

Obtém ou define a fonte do texto. Pode ser nulo. Use null para herdar a propriedade {@code Font} do elemento de estrutura pai.

**Returns:**
Instância Font

### getFontSize {#getFontSize--}
```
public final com.aspose.ms.System.Nullable< Float > getFontSize()
```

Obtém ou define o tamanho da fonte do texto. Pode ser nulo. Use null para herdar a propriedade {@code FontSize} do elemento de estrutura pai.

**Returns:**
Array de float

### getFontStyle {#getFontStyle--}
```
public final com.aspose.ms.System.Nullable< Integer > getFontStyle()
```

Obtém ou define o estilo da fonte do texto. Pode ser nulo. Use null para herdar a propriedade {@code FontStyle} do elemento de estrutura pai.

**Returns:**
Array de inteiro

### getForegroundColor {#getForegroundColor--}
```
public final Color getForegroundColor()
```

Obtém ou define a cor de primeiro plano do texto. Pode ser nulo. Use null para herdar a propriedade {@code ForegroundColor} do elemento de estrutura pai.

**Returns:**
Instância de Color

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public final com.aspose.ms.System.Nullable< HorizontalAlignment > getHorizontalAlignment()
```

Obtém ou define um alinhamento horizontal do parágrafo

**Returns:**
Elemento HorizontalAlignment

### getHorizontalScaling {#getHorizontalScaling--}
```
public final com.aspose.ms.System.Nullable< Float > getHorizontalScaling()
```

Obtém ou define a escala horizontal do texto. Pode ser nulo. Use null para herdar a propriedade {@code HorizontalScaling} do elemento de estrutura pai.

**Returns:**
Array de float

### getLineSpacing {#getLineSpacing--}
```
public final com.aspose.ms.System.Nullable< Float > getLineSpacing()
```

Obtém ou define o espaçamento entre linhas do texto. Pode ser nulo. Use null para herdar a propriedade {@code LineSpacing} do elemento de estrutura pai.

**Returns:**
Array de float

### getMarginInfo {#getMarginInfo--}
```
@Deprecated public final MarginInfo getMarginInfo()
```

Obtém ou define a margem para o elemento de estrutura de bloco.

**Returns:**
Instância de MarginInfo @deprecated Use IAdjustPosition.AdjustPosition(PositionSettings positionSettings) método para definir as configurações de posição

### getStrikeOut {#getStrikeOut--}
```
public final com.aspose.ms.System.Nullable< Boolean > getStrikeOut()
```

Obtém ou define o tachado do texto. Pode ser nulo. Use null para herdar a propriedade {@code StrikeOut} do elemento de estrutura pai.

**Returns:**
Array de booleano

### getSubscript {#getSubscript--}
```
public final com.aspose.ms.System.Nullable< Boolean > getSubscript()
```

Obtém ou define o subscrito do texto. Pode ser nulo. Use null para herdar a propriedade {@code Subscript} do elemento de estrutura pai.

**Returns:**
Array de booleano

### getSuperscript {#getSuperscript--}
```
public final com.aspose.ms.System.Nullable< Boolean > getSuperscript()
```

Obtém ou define o sobrescrito do texto. Pode ser nulo. Use null para herdar a propriedade {@code Superscript} do elemento de estrutura pai.

**Returns:**
Array de booleano

### getUnderline {#getUnderline--}
```
public final com.aspose.ms.System.Nullable< Boolean > getUnderline()
```

Obtém ou define o sublinhado do texto. Pode ser nulo. Use null para herdar a propriedade {@code Underline} do elemento de estrutura pai.

**Returns:**
Array de booleano

### getVerticalAlignment {#getVerticalAlignment--}
```
public final com.aspose.ms.System.Nullable< VerticalAlignment > getVerticalAlignment()
```

Obtém ou define um alinhamento vertical do parágrafo

**Returns:**
Elemento VerticalAlignment

### getWordSpacing {#getWordSpacing--}
```
public final com.aspose.ms.System.Nullable< Float > getWordSpacing()
```

Obtém ou define o espaçamento entre palavras do texto. Pode ser nulo. Use null para herdar a propriedade {@code WordSpacing} do elemento de estrutura pai.

**Returns:**
Array de float

### isFirstParagraphInColumn {#isFirstParagraphInColumn--}
```
public final com.aspose.ms.System.Nullable< Boolean > isFirstParagraphInColumn()
```

Obtém ou define um valor booleano que indica se este parágrafo ficará na próxima coluna. O padrão é falso.

**Returns:**
Valor booleano

### isInLineParagraph {#isInLineParagraph--}
```
public final com.aspose.ms.System.Nullable< Boolean > isInLineParagraph()
```

Obtém ou define se o parágrafo está em linha. O padrão é falso.

**Returns:**
Valor booleano

### isInNewPage {#isInNewPage--}
```
public final com.aspose.ms.System.Nullable< Boolean > isInNewPage()
```

Obtém ou define um valor booleano que força este parágrafo a ser gerado em uma nova página. O padrão é falso.

**Returns:**
Valor booleano

### isKeptWithNext {#isKeptWithNext--}
```
public final com.aspose.ms.System.Nullable< Boolean > isKeptWithNext()
```

Obtém ou define um valor booleano que indica se o parágrafo atual permanece na mesma página junto com o próximo parágrafo. O padrão é falso.

**Returns:**
Valor booleano

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Obtém ou define a cor de fundo do texto. Pode ser nulo. Use null para herdar a propriedade {@code BackgroundColor} do elemento de estrutura pai.

### setCharacterSpacing {#setCharacterSpacing-com.aspose.ms.System.Nullable-}
Obtém ou define o espaçamento entre caracteres do texto.

### setFont {#setFont-com.aspose.pdf.Font-}
Obtém ou define a fonte do texto. Pode ser nulo. Use null para herdar a propriedade {@code Font} do elemento de estrutura pai.

### setFontSize {#setFontSize-com.aspose.ms.System.Nullable-}
Obtém ou define o tamanho da fonte do texto.

### setFontStyle {#setFontStyle-com.aspose.ms.System.Nullable-}
Obtém ou define o estilo da fonte do texto.

### setForegroundColor {#setForegroundColor-com.aspose.pdf.Color-}
Obtém ou define a cor de primeiro plano do texto. Pode ser nulo. Use null para herdar a propriedade {@code ForegroundColor} do elemento de estrutura pai.

### setHorizontalScaling {#setHorizontalScaling-com.aspose.ms.System.Nullable-}
Obtém ou define a escala horizontal do texto.

### setLineSpacing {#setLineSpacing-com.aspose.ms.System.Nullable-}
Obtém ou define o espaçamento entre linhas do texto.

### setMarginInfo {#setMarginInfo-com.aspose.pdf.MarginInfo-}
Obtém ou define a margem para o elemento de estrutura de bloco.

### setStrikeOut {#setStrikeOut-com.aspose.ms.System.Nullable-}
Obtém ou define o tachado do texto.

### setSubscript {#setSubscript-com.aspose.ms.System.Nullable-}
Obtém ou define o subscrito do texto.

### setSuperscript {#setSuperscript-com.aspose.ms.System.Nullable-}
Obtém ou define o sobrescrito do texto.

### setUnderline {#setUnderline-com.aspose.ms.System.Nullable-}
Obtém ou define o sublinhado do texto.

### setWordSpacing {#setWordSpacing-com.aspose.ms.System.Nullable-}
Obtém ou define o espaçamento entre palavras do texto.

### update {#update-com.aspose.pdf.tagged.logicalstructure.elements.StructureTextState-}
Atualizar elementos
