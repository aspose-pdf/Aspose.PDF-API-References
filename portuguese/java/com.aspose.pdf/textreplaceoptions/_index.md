---
title: "TextReplaceOptions"
linktitle: "TextReplaceOptions"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa opções de substituição de texto"
type: docs
weight: 5250
url: /pt/java/com.aspose.pdf/textreplaceoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextOptions com.aspose.pdf.TextReplaceOptions, com.aspose.pdf.TextOptions, com.aspose.pdf.TextReplaceOptions

```
public final class TextReplaceOptions extends TextOptions
```

Representa opções de substituição de texto

## Construtores

| Construtor | Descrição |
| --- | --- |
| [TextReplaceOptions](#TextReplaceOptions--) | Inicializa uma nova instância do objeto {@code TextReplaceOptions} para o ajuste padrão e escopo: ReplaceAdjustment.None e Scope.REPLACE_FIRST |
| [TextReplaceOptions](#TextReplaceOptions-int-) | Inicializa uma nova instância do objeto {@code TextReplaceOptions} para a ação especificada após a substituição. |
| [TextReplaceOptions](#TextReplaceOptions-int-com.aspose.pdf.TextReplaceOptions.Scope-) | Inicializa uma nova instância do objeto {@code TextReplaceOptions} para o ajuste padrão e escopo: ReplaceAdjustment.None e Scope.REPLACE_FIRST |
| [TextReplaceOptions](#TextReplaceOptions-com.aspose.pdf.TextReplaceOptions.Scope-) | Inicializa uma nova instância do objeto {@code TextReplaceOptions} para o ajuste padrão e escopo: ReplaceAdjustment.None e Scope.REPLACE_FIRST |

## Métodos

| Método | Descrição |
| --- | --- |
| [getAdjustmentNewLineSpacing](#getAdjustmentNewLineSpacing--) | Obtém ou define o valor do espaçamento entre linhas que é usado se o ajuste de substituição for forçado a criar uma nova linha de texto. O valor esperado é um multiplicador do tamanho da fonte do texto substituído. O padrão é 1.2. |
| [getFontSizeAdjustmentAction](#getFontSizeAdjustmentAction--) | Obtém ou define a política para ajustar o tamanho da fonte para caber dentro dos limites definidos por {@code TextReplaceOptions.Rectangle}({@link #getRectangle}/{@link #setRectangle(Rectangle)}). |
| [getLeftAdjustment](#getLeftAdjustment--) | Obtém o ajuste da posição à esquerda para o texto substituído ao usar TextReplaceOptions: - ReplaceAdjustmentAction = IsFormFillingMode; |
| [getRectangle](#getRectangle--) | Obtém uma ação que será executada após a substituição do fragmento de texto para torná-lo mais curto. |
| [getReplaceAdjustmentAction](#getReplaceAdjustmentAction--) | Obtém o escopo onde a operação de substituição de texto é aplicada |
| [getReplaceScope](#getReplaceScope--) | Define ou obtém o ajuste da posição à direita para o texto substituído ao usar TextReplaceOptions: - ReplaceAdjustmentAction = WholeWordsHyphenation; - ReplaceAdjustmentAction = IsFormFillingMode; |
| [getRightAdjustment](#getRightAdjustment--) | Obtém ou define um valor que indica se deve ignorar parágrafos distintos ao ajustar o texto na página após a substituição de texto. |
| [isIgnoreParagraphs](#isIgnoreParagraphs--) | Obtém ou define a política para ajustar o tamanho da fonte para caber dentro dos limites definidos por TextReplaceOptions.Rectangle ( getRectangle() / setRectangle(Rectangle) ). |
| [setAdjustmentNewLineSpacing](#setAdjustmentNewLineSpacing-double-) | Obtém ou define o valor do espaçamento entre linhas que é usado se o ajuste de substituição for forçado a criar uma nova linha de texto. O valor esperado é um multiplicador do tamanho da fonte do texto substituído. O padrão é 1.2. |
| [setFontSizeAdjustmentAction](#setFontSizeAdjustmentAction-com.aspose.pdf.TextReplaceOptions.FontSizeAdjustment-) | Define ou obtém o ajuste da posição à esquerda para o texto substituído ao usar TextReplaceOptions: - ReplaceAdjustmentAction = IsFormFillingMode; |
| [setIgnoreParagraphs](#setIgnoreParagraphs-boolean-) | Obtém ou define a política para ajustar o tamanho da fonte para caber dentro dos limites definidos por TextReplaceOptions.Rectangle ( getRectangle() / setRectangle(Rectangle) ). |
| [setLeftAdjustment](#setLeftAdjustment-double-) | Define uma ação que será executada após a substituição do fragmento de texto para torná-lo mais curto. |
| [setRectangle](#setRectangle-com.aspose.pdf.Rectangle-) | Obtém uma ação que será executada após a substituição do fragmento de texto para torná-lo mais curto. |
| [setReplaceAdjustmentAction](#setReplaceAdjustmentAction-int-) | Define o escopo onde a operação de substituição de texto é aplicada |
| [setReplaceScope](#setReplaceScope-com.aspose.pdf.TextReplaceOptions.Scope-) | Define o ajuste da posição à direita para o texto substituído ao usar TextReplaceOptions: - ReplaceAdjustmentAction = WholeWordsHyphenation; - ReplaceAdjustmentAction = IsFormFillingMode; |
| [setRightAdjustment](#setRightAdjustment-double-) | ajuste |

### TextReplaceOptions {#TextReplaceOptions--}
```
public TextReplaceOptions()
```

Inicializa uma nova instância do objeto {@code TextReplaceOptions} para o ajuste padrão e escopo: ReplaceAdjustment.None e Scope.REPLACE_FIRST

### TextReplaceOptions {#TextReplaceOptions-int-}
```
public TextReplaceOptions(int adjustment)
```

Inicializa uma nova instância do objeto {@code TextReplaceOptions} para a ação especificada após a substituição.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| Objeto ReplaceAdjustment. @see ReplaceAdjustment |  | Elemento FontSizeAdjustment |

### TextReplaceOptions {#TextReplaceOptions-int-com.aspose.pdf.TextReplaceOptions.Scope-}
Inicializa uma nova instância do objeto {@code TextReplaceOptions} para o ajuste padrão e escopo: ReplaceAdjustment.None e Scope.REPLACE_FIRST

### TextReplaceOptions {#TextReplaceOptions-com.aspose.pdf.TextReplaceOptions.Scope-}
Inicializa uma nova instância do objeto {@code TextReplaceOptions} para o ajuste padrão e escopo: ReplaceAdjustment.None e Scope.REPLACE_FIRST

### getAdjustmentNewLineSpacing {#getAdjustmentNewLineSpacing--}
```
public double getAdjustmentNewLineSpacing()
```

Obtém ou define o valor do espaçamento entre linhas que é usado se o ajuste de substituição for forçado a criar uma nova linha de texto. O valor esperado é um multiplicador do tamanho da fonte do texto substituído. O padrão é 1.2.

**Returns:**
valor double

### getFontSizeAdjustmentAction {#getFontSizeAdjustmentAction--}
```
public final TextReplaceOptions.FontSizeAdjustment getFontSizeAdjustmentAction()
```

Obtém ou define a política para ajustar o tamanho da fonte para caber dentro dos limites definidos por {@code TextReplaceOptions.Rectangle}({@link #getRectangle}/{@link #setRectangle(Rectangle)}).

**Returns:**
Elemento ReplaceAdjustment @see ReplaceAdjustment

### getLeftAdjustment {#getLeftAdjustment--}
```
public final double getLeftAdjustment()
```

Obtém o ajuste da posição à esquerda para o texto substituído ao usar TextReplaceOptions: - ReplaceAdjustmentAction = IsFormFillingMode;

**Returns:**
valor double

### getRectangle {#getRectangle--}
```
public final Rectangle getRectangle()
```

Obtém uma ação que será executada após a substituição do fragmento de texto para torná-lo mais curto.

**Returns:**
Instância de Rectangle

### getReplaceAdjustmentAction {#getReplaceAdjustmentAction--}
```
public int getReplaceAdjustmentAction()
```

Obtém o escopo onde a operação de substituição de texto é aplicada

**Returns:**
valor int @see Scope

### getReplaceScope {#getReplaceScope--}
```
public TextReplaceOptions.Scope getReplaceScope()
```

Define ou obtém o ajuste da posição à direita para o texto substituído ao usar TextReplaceOptions: - ReplaceAdjustmentAction = WholeWordsHyphenation; - ReplaceAdjustmentAction = IsFormFillingMode;

**Returns:**
valor booleano

### getRightAdjustment {#getRightAdjustment--}
```
public final double getRightAdjustment()
```

Obtém ou define um valor que indica se deve ignorar parágrafos distintos ao ajustar o texto na página após a substituição de texto.

**Returns:**
valor double

### isIgnoreParagraphs {#isIgnoreParagraphs--}
```
public final boolean isIgnoreParagraphs()
```

Obtém ou define a política para ajustar o tamanho da fonte para caber dentro dos limites definidos por TextReplaceOptions.Rectangle ( getRectangle() / setRectangle(Rectangle) ).

**Returns:**
TextExtractionOptions.TextFormattingMode

### setAdjustmentNewLineSpacing {#setAdjustmentNewLineSpacing-double-}
```
public void setAdjustmentNewLineSpacing(double value)
```

Obtém ou define o valor do espaçamento entre linhas que é usado se o ajuste de substituição for forçado a criar uma nova linha de texto. O valor esperado é um multiplicador do tamanho da fonte do texto substituído. O padrão é 1.2.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### setFontSizeAdjustmentAction {#setFontSizeAdjustmentAction-com.aspose.pdf.TextReplaceOptions.FontSizeAdjustment-}
Define ou obtém o ajuste da posição à esquerda para o texto substituído ao usar TextReplaceOptions: - ReplaceAdjustmentAction = IsFormFillingMode;

### setIgnoreParagraphs {#setIgnoreParagraphs-boolean-}
```
public final void setIgnoreParagraphs(boolean value)
```

Obtém ou define a política para ajustar o tamanho da fonte para caber dentro dos limites definidos por TextReplaceOptions.Rectangle ( getRectangle() / setRectangle(Rectangle) ).

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setLeftAdjustment {#setLeftAdjustment-double-}
```
public final void setLeftAdjustment(double value)
```

Define uma ação que será executada após a substituição do fragmento de texto para torná-lo mais curto.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### setRectangle {#setRectangle-com.aspose.pdf.Rectangle-}
Obtém uma ação que será executada após a substituição do fragmento de texto para torná-lo mais curto.

### setReplaceAdjustmentAction {#setReplaceAdjustmentAction-int-}
```
public void setReplaceAdjustmentAction(int value)
```

Define o escopo onde a operação de substituição de texto é aplicada

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int @see Scope |

### setReplaceScope {#setReplaceScope-com.aspose.pdf.TextReplaceOptions.Scope-}
Define o ajuste da posição à direita para o texto substituído ao usar TextReplaceOptions: - ReplaceAdjustmentAction = WholeWordsHyphenation; - ReplaceAdjustmentAction = IsFormFillingMode;

### setRightAdjustment {#setRightAdjustment-double-}
```
public final void setRightAdjustment(double value)
```

ajuste

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |
