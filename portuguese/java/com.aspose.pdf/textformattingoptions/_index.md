---
title: "TextFormattingOptions"
linktitle: "TextFormattingOptions"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa opções de formatação de texto"
type: docs
weight: 5080
url: /pt/java/com.aspose.pdf/textformattingoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextOptions com.aspose.pdf.TextFormattingOptions, com.aspose.pdf.TextOptions, com.aspose.pdf.TextFormattingOptions

```
public final class TextFormattingOptions extends TextOptions
```

Representa opções de formatação de texto

## Construtores

| Construtor | Descrição |
| --- | --- |
| [TextFormattingOptions](#TextFormattingOptions--) | Inicializa uma nova instância do objeto {@code TextFormattingOptions} com modo de quebra de linha indefinido. |
| [TextFormattingOptions](#TextFormattingOptions-int-) | Inicializa uma nova instância do objeto {@code TextFormattingOptions} para o modo de quebra de linha especificado. |

## Métodos

| Método | Descrição |
| --- | --- |
| [getFirstLineIndent](#getFirstLineIndent--) | Obtém ou define o valor de recuo da primeira linha. |
| [getHyphenSymbol](#getHyphenSymbol--) | <p> Obtém ou define o símbolo de hífen que é usado no processo de hifenização. </p><hr> Para eliminar a renderização do hífen (com o procedimento de quebra ainda ativo) defina uma string vazia string.Empty para HyphenSymbol. |
| [getLineSpacing](#getLineSpacing--) | Obtém o modo de espaçamento de linhas. O valor padrão é LineSpacingMode.FontSize |
| [getSubsequentLinesIndent](#getSubsequentLinesIndent--) | Obtém ou define o valor de recuo das linhas subsequentes. |
| [getWrapMode](#getWrapMode--) | Obtém o modo de quebra de linha. O valor padrão é WordWrapMode.NoWrap |
| [setFirstLineIndent](#setFirstLineIndent-float-) | Obtém ou define o valor de recuo da primeira linha. |
| [setHyphenSymbol](#setHyphenSymbol-java.lang.String-) | <p> Obtém ou define o símbolo de hífen que é usado no processo de hifenização. </p><hr> Para eliminar a renderização do hífen (com o procedimento de quebra ainda ativo) defina uma string vazia string.Empty para HyphenSymbol. |
| [setLineSpacing](#setLineSpacing-int-) | Define o modo de espaçamento de linhas. O valor padrão é LineSpacingMode.FontSize |
| [setSubsequentLinesIndent](#setSubsequentLinesIndent-float-) | Obtém ou define o valor de recuo das linhas subsequentes. |
| [setWrapMode](#setWrapMode-int-) | Define o modo de quebra de linha. O valor padrão é WordWrapMode.NoWrap |

### TextFormattingOptions {#TextFormattingOptions--}
```
public TextFormattingOptions()
```

Inicializa uma nova instância do objeto {@code TextFormattingOptions} com modo de quebra de linha indefinido.

### TextFormattingOptions {#TextFormattingOptions-int-}
```
public TextFormattingOptions(int wrapMode)
```

Inicializa uma nova instância do objeto {@code TextFormattingOptions} para o modo de quebra de linha especificado.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| wrapMode |  | Modo de quebra de linha. @see WordWrapMode |

### getFirstLineIndent {#getFirstLineIndent--}
```
public final float getFirstLineIndent()
```

Obtém ou define o valor de recuo da primeira linha.

**Returns:**
valor float

### getHyphenSymbol {#getHyphenSymbol--}
```
public final String getHyphenSymbol()
```

<p> Obtém ou define o símbolo de hífen que é usado no processo de hifenização. </p><hr> Para eliminar a renderização do hífen (com o procedimento de quebra ainda ativo) defina uma string vazia string.Empty para HyphenSymbol.

**Returns:**
valor String

### getLineSpacing {#getLineSpacing--}
```
public int getLineSpacing()
```

Obtém o modo de espaçamento de linhas. O valor padrão é LineSpacingMode.FontSize

**Returns:**
valor int @see LineSpacingMode

### getSubsequentLinesIndent {#getSubsequentLinesIndent--}
```
public float getSubsequentLinesIndent()
```

Obtém ou define o valor de recuo das linhas subsequentes.

**Returns:**
valor float

### getWrapMode {#getWrapMode--}
```
public int getWrapMode()
```

Obtém o modo de quebra de linha. O valor padrão é WordWrapMode.NoWrap

**Returns:**
valor WordWrapMode @see WordWrapMode

### setFirstLineIndent {#setFirstLineIndent-float-}
```
public final void setFirstLineIndent(float value)
```

Obtém ou define o valor de recuo da primeira linha.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor float |

### setHyphenSymbol {#setHyphenSymbol-java.lang.String-}
<p> Obtém ou define o símbolo de hífen que é usado no processo de hifenização. </p><hr> Para eliminar a renderização do hífen (com o procedimento de quebra ainda ativo) defina uma string vazia string.Empty para HyphenSymbol.

### setLineSpacing {#setLineSpacing-int-}
```
public void setLineSpacing(int value)
```

Define o modo de espaçamento de linhas. O valor padrão é LineSpacingMode.FontSize

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int @see LineSpacingMode |

### setSubsequentLinesIndent {#setSubsequentLinesIndent-float-}
```
public void setSubsequentLinesIndent(float value)
```

Obtém ou define o valor de recuo das linhas subsequentes.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor float |

### setWrapMode {#setWrapMode-int-}
```
public void setWrapMode(int value)
```

Define o modo de quebra de linha. O valor padrão é WordWrapMode.NoWrap

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor WordWrapMode @see WordWrapMode |
