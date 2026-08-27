---
title: "TextStamp"
linktitle: "TextStamp"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa um selo textual."
type: docs
weight: 5320
url: /pt/java/com.aspose.pdf/textstamp/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Stamp com.aspose.pdf.TextStamp, com.aspose.pdf.Stamp, com.aspose.pdf.TextStamp

```
public class TextStamp extends Stamp
```

Representa um selo textual.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [TextStamp](#TextStamp-com.aspose.pdf.facades.FormattedText-) | Inicializa uma nova instância da classe {@code TextStamp} com o objeto formattedText |
| [TextStamp](#TextStamp-com.aspose.pdf.facades.FormattedText-com.aspose.pdf.TextState-) | Inicializa uma nova instância da classe {@code TextStamp} com o objeto formattedText |
| [TextStamp](#TextStamp-java.lang.String-) | Inicializa uma nova instância da classe {@code TextStamp}. |
| [TextStamp](#TextStamp-java.lang.String-com.aspose.pdf.TextState-) | Inicializa uma nova instância da classe TextStamp. |

## Métodos

| Método | Descrição |
| --- | --- |
| [getAutoAdjustFontSizePrecision](#getAutoAdjustFontSizePrecision--) | Ajusta automaticamente a precisão do tamanho da fonte. Valor padrão: 0.1; |
| [getAutoAdjustFontSizeToFitStampRectangle](#getAutoAdjustFontSizeToFitStampRectangle--) | Se habilitado, o tamanho da fonte será ajustado automaticamente para caber no retângulo do selo de tamanho: {@code Width}({@code Stamp#getWidth}/{@code Stamp#setWidth(double)}) e {@code Height}({@code Stamp#getHeight}/{@code Stamp#setHeight(double)}). A largura e altura padrão são derivadas do retângulo da página. |
| [getDefaultFont](#getDefaultFont--) | Retorna a fonte padrão |
| [getDefaultFontSize](#getDefaultFontSize--) | Tamanho da Fonte Padrão |
| [getDraw](#getDraw--) | Esta propriedade determina como o selo é desenhado na página. Se Draw = true, o selo é desenhado como operadores gráficos e se draw = false, o selo é desenhado como texto. |
| [getFontSize](#getFontSize--) | Tamanho real da fonte após o selo ter sido colocado. (Pode diferir do tamanho inicial da fonte fornecido através do construtor se a opção 'AutoAdjustFontSizeToFitStampRectangle' estiver habilitada.) |
| [getHeight](#getHeight--) | Altura desejada do selo na página. |
| [getMaxRowWidth](#getMaxRowWidth--) | Altura máxima da linha para a opção WordWrap. |
| [getNoCharacterBehavior](#getNoCharacterBehavior--) | Obtém ou define o modo que define o comportamento caso as fontes não contenham os caracteres solicitados. |
| [getReplacementFont](#getReplacementFont--) | Obtém ou define a fonte usada para substituição se a fonte do usuário não contiver o caractere necessário. |
| [getTextAlignment](#getTextAlignment--) | Alinhamento do texto dentro do selo. |
| [getTextState](#getTextState--) | Obtém as propriedades de texto do selo. Veja {@code TextState} para detalhes. |
| [getTreatYIndentAsBaseLine](#getTreatYIndentAsBaseLine--) | Define a origem das coordenadas para posicionar o texto. Se TreatYIndentAsBaseLine = true (padrão quando Draw = true) o valor de YIndent será tratado como linha de base do texto. Se TreatYIndentAsBaseLine = false (padrão quando Draw = false) o valor de YIndent será tratado como a parte inferior (linha de descida) do texto. |
| [getValue](#getValue--) | Obtém o valor de string que é usado como selo na página. |
| [getWidth](#getWidth--) | Largura desejada do selo na página. |
| [getWordWrapMode](#getWordWrapMode--) | Obtém ou define o modo de quebra de linha para a renderização de texto. |
| [isJustify](#isJustify--) | Define a justificação do texto. Se esta propriedade for definida como true, ambas as bordas esquerda e direita do texto são alinhadas. Valor padrão: false. |
| [isScale](#isScale--) | Define o dimensionamento do texto. Se esta propriedade for definida como true e o valor Width for especificado, o texto será dimensionado para caber na largura especificada. |
| [isWordWrap](#isWordWrap--) | Define a quebra de linha. Se esta propriedade for definida como true e o valor Width for especificado, o texto será dividido em várias linhas para caber na largura especificada. Valor padrão: false. |
| [put](#put-com.aspose.pdf.Page-) | Adiciona um selo textual na página. |
| [setAutoAdjustFontSizePrecision](#setAutoAdjustFontSizePrecision-float-) | Ajusta automaticamente a precisão do tamanho da fonte. Valor padrão: 0.1; |
| [setAutoAdjustFontSizeToFitStampRectangle](#setAutoAdjustFontSizeToFitStampRectangle-boolean-) | Se habilitado, o tamanho da fonte será ajustado automaticamente para caber no retângulo do selo de tamanho: {@code Width}({@code Stamp#getWidth}/{@code Stamp#setWidth(double)}) e {@code Height}({@code Stamp#getHeight}/{@code Stamp#setHeight(double)}). A largura e altura padrão são derivadas do retângulo da página. |
| [setDraw](#setDraw-boolean-) | Esta propriedade determina como o selo é desenhado na página. Se Draw = true, o selo é desenhado como operadores gráficos e se draw = false, o selo é desenhado como texto. |
| [setHeight](#setHeight-double-) | Altura desejada do selo na página. |
| [setJustify](#setJustify-boolean-) | Define a justificação do texto. Se esta propriedade for definida como true, ambas as bordas esquerda e direita do texto são alinhadas. Valor padrão: false. |
| [setMaxRowWidth](#setMaxRowWidth-double-) | Altura máxima da linha para a opção WordWrap. |
| [setNoCharacterBehavior](#setNoCharacterBehavior-int-) | Obtém ou define o modo que define o comportamento caso as fontes não contenham os caracteres solicitados. |
| [setReplacementFont](#setReplacementFont-com.aspose.pdf.Font-) | Obtém ou define a fonte usada para substituição se a fonte do usuário não contiver o caractere necessário. |
| [setScale](#setScale-boolean-) | Define o dimensionamento do texto. Se esta propriedade for definida como true e o valor Width for especificado, o texto será dimensionado para caber na largura especificada. |
| [setTextAlignment](#setTextAlignment-com.aspose.pdf.HorizontalAlignment-) | Alinhamento do texto dentro do selo. |
| [setTreatYIndentAsBaseLine](#setTreatYIndentAsBaseLine-boolean-) | Define a origem das coordenadas para posicionar o texto. Se TreatYIndentAsBaseLine = true (padrão quando Draw = true) o valor de YIndent será tratado como linha de base do texto. Se TreatYIndentAsBaseLine = false (padrão quando Draw = false) o valor de YIndent será tratado como a parte inferior (linha de descida) do texto. |
| [setValue](#setValue-java.lang.String-) | Define o valor de string que é usado como selo na página. |
| [setWidth](#setWidth-double-) | Largura desejada do selo na página. |
| [setWordWrap](#setWordWrap-boolean-) | Define a quebra de linha. Se esta propriedade for definida como true e o valor Width for especificado, o texto será dividido em várias linhas para caber na largura especificada. Valor padrão: false. |
| [setWordWrapMode](#setWordWrapMode-int-) | Obtém ou define o modo de quebra de linha para a renderização de texto. |

### TextStamp {#TextStamp-com.aspose.pdf.facades.FormattedText-}
Inicializa uma nova instância da classe {@code TextStamp} com o objeto formattedText

### TextStamp {#TextStamp-com.aspose.pdf.facades.FormattedText-com.aspose.pdf.TextState-}
Inicializa uma nova instância da classe {@code TextStamp} com o objeto formattedText

### TextStamp {#TextStamp-java.lang.String-}
Inicializa uma nova instância da classe {@code TextStamp}.

### TextStamp {#TextStamp-java.lang.String-com.aspose.pdf.TextState-}
Inicializa uma nova instância da classe TextStamp.

### getAutoAdjustFontSizePrecision {#getAutoAdjustFontSizePrecision--}
```
public final float getAutoAdjustFontSizePrecision()
```

Ajusta automaticamente a precisão do tamanho da fonte. Valor padrão: 0.1;

**Returns:**
valor float

### getAutoAdjustFontSizeToFitStampRectangle {#getAutoAdjustFontSizeToFitStampRectangle--}
```
public final boolean getAutoAdjustFontSizeToFitStampRectangle()
```

Se habilitado, o tamanho da fonte será ajustado automaticamente para caber no retângulo do selo de tamanho: {@code Width}({@code Stamp#getWidth}/{@code Stamp#setWidth(double)}) e {@code Height}({@code Stamp#getHeight}/{@code Stamp#setHeight(double)}). A largura e altura padrão são derivadas do retângulo da página.

**Returns:**
valor booleano

### getDefaultFont {#getDefaultFont--}
```
public static Font getDefaultFont()
```

Retorna a fonte padrão

**Returns:**
objeto com.aspose.pdf.Font

### getDefaultFontSize {#getDefaultFontSize--}
```
public static float getDefaultFontSize()
```

Tamanho da Fonte Padrão

**Returns:**
valor float

### getDraw {#getDraw--}
```
public boolean getDraw()
```

Esta propriedade determina como o selo é desenhado na página. Se Draw = true, o selo é desenhado como operadores gráficos e se draw = false, o selo é desenhado como texto.

**Returns:**
valor booleano

### getFontSize {#getFontSize--}
```
public final float getFontSize()
```

Tamanho real da fonte após o selo ter sido colocado. (Pode diferir do tamanho inicial da fonte fornecido através do construtor se a opção 'AutoAdjustFontSizeToFitStampRectangle' estiver habilitada.)

**Returns:**
valor float

### getHeight {#getHeight--}
```
public double getHeight()
```

Altura desejada do selo na página.

**Returns:**
valor double

### getMaxRowWidth {#getMaxRowWidth--}
```
public double getMaxRowWidth()
```

Altura máxima da linha para a opção WordWrap.

**Returns:**
valor double

### getNoCharacterBehavior {#getNoCharacterBehavior--}
```
public final int getNoCharacterBehavior()
```

Obtém ou define o modo que define o comportamento caso as fontes não contenham os caracteres solicitados.

**Returns:**
Elemento NoCharacterAction

### getReplacementFont {#getReplacementFont--}
```
public final Font getReplacementFont()
```

Obtém ou define a fonte usada para substituição se a fonte do usuário não contiver o caractere necessário.

**Returns:**
Instância Font

### getTextAlignment {#getTextAlignment--}
```
public HorizontalAlignment getTextAlignment()
```

Alinhamento do texto dentro do selo.

**Returns:**
Valor HorizontalAlignment @see HorizontalAlignment

### getTextState {#getTextState--}
```
public TextState getTextState()
```

Obtém as propriedades de texto do selo. Veja {@code TextState} para detalhes.

**Returns:**
Elemento TextState

### getTreatYIndentAsBaseLine {#getTreatYIndentAsBaseLine--}
```
public boolean getTreatYIndentAsBaseLine()
```

Define a origem das coordenadas para posicionar o texto. Se TreatYIndentAsBaseLine = true (padrão quando Draw = true) o valor de YIndent será tratado como linha de base do texto. Se TreatYIndentAsBaseLine = false (padrão quando Draw = false) o valor de YIndent será tratado como a parte inferior (linha de descida) do texto.

**Returns:**
valor booleano

### getValue {#getValue--}
```
public String getValue()
```

Obtém o valor de string que é usado como selo na página.

**Returns:**
valor String

### getWidth {#getWidth--}
```
public double getWidth()
```

Largura desejada do selo na página.

**Returns:**
valor double

### getWordWrapMode {#getWordWrapMode--}
```
public final int getWordWrapMode()
```

Obtém ou define o modo de quebra de linha para a renderização de texto.

**Returns:**
Elemento WordWrapMode

### isJustify {#isJustify--}
```
public boolean isJustify()
```

Define a justificação do texto. Se esta propriedade for definida como true, ambas as bordas esquerda e direita do texto são alinhadas. Valor padrão: false.

**Returns:**
valor booleano

### isScale {#isScale--}
```
public boolean isScale()
```

Define o dimensionamento do texto. Se esta propriedade for definida como true e o valor Width for especificado, o texto será dimensionado para caber na largura especificada.

**Returns:**
valor booleano

### isWordWrap {#isWordWrap--}
```
@Deprecated public boolean isWordWrap()
```

Define a quebra de linha. Se esta propriedade for definida como true e o valor Width for especificado, o texto será dividido em várias linhas para caber na largura especificada. Valor padrão: false.

**Returns:**
valor booleano @deprecated "Use WordWrapMode em vez disso."

### put {#put-com.aspose.pdf.Page-}
Adiciona um selo textual na página.

### setAutoAdjustFontSizePrecision {#setAutoAdjustFontSizePrecision-float-}
```
public final void setAutoAdjustFontSizePrecision(float value)
```

Ajusta automaticamente a precisão do tamanho da fonte. Valor padrão: 0.1;

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor float |

### setAutoAdjustFontSizeToFitStampRectangle {#setAutoAdjustFontSizeToFitStampRectangle-boolean-}
```
public final void setAutoAdjustFontSizeToFitStampRectangle(boolean value)
```

Se habilitado, o tamanho da fonte será ajustado automaticamente para caber no retângulo do selo de tamanho: {@code Width}({@code Stamp#getWidth}/{@code Stamp#setWidth(double)}) e {@code Height}({@code Stamp#getHeight}/{@code Stamp#setHeight(double)}). A largura e altura padrão são derivadas do retângulo da página.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setDraw {#setDraw-boolean-}
```
public void setDraw(boolean value)
```

Esta propriedade determina como o selo é desenhado na página. Se Draw = true, o selo é desenhado como operadores gráficos e se draw = false, o selo é desenhado como texto.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

Altura desejada do selo na página.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### setJustify {#setJustify-boolean-}
```
public void setJustify(boolean value)
```

Define a justificação do texto. Se esta propriedade for definida como true, ambas as bordas esquerda e direita do texto são alinhadas. Valor padrão: false.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setMaxRowWidth {#setMaxRowWidth-double-}
```
public void setMaxRowWidth(double value)
```

Altura máxima da linha para a opção WordWrap.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### setNoCharacterBehavior {#setNoCharacterBehavior-int-}
```
public final void setNoCharacterBehavior(int value)
```

Obtém ou define o modo que define o comportamento caso as fontes não contenham os caracteres solicitados.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | Elemento NoCharacterAction |

### setReplacementFont {#setReplacementFont-com.aspose.pdf.Font-}
Obtém ou define a fonte usada para substituição se a fonte do usuário não contiver o caractere necessário.

### setScale {#setScale-boolean-}
```
public void setScale(boolean value)
```

Define o dimensionamento do texto. Se esta propriedade for definida como true e o valor Width for especificado, o texto será dimensionado para caber na largura especificada.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setTextAlignment {#setTextAlignment-com.aspose.pdf.HorizontalAlignment-}
Alinhamento do texto dentro do selo.

### setTreatYIndentAsBaseLine {#setTreatYIndentAsBaseLine-boolean-}
```
public void setTreatYIndentAsBaseLine(boolean value)
```

Define a origem das coordenadas para posicionar o texto. Se TreatYIndentAsBaseLine = true (padrão quando Draw = true) o valor de YIndent será tratado como linha de base do texto. Se TreatYIndentAsBaseLine = false (padrão quando Draw = false) o valor de YIndent será tratado como a parte inferior (linha de descida) do texto.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setValue {#setValue-java.lang.String-}
Define o valor de string que é usado como selo na página.

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Largura desejada do selo na página.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### setWordWrap {#setWordWrap-boolean-}
```
@Deprecated public void setWordWrap(boolean value)
```

Define a quebra de linha. Se esta propriedade for definida como true e o valor Width for especificado, o texto será dividido em várias linhas para caber na largura especificada. Valor padrão: false.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano @deprecated "Use WordWrapMode em vez disso." |

### setWordWrapMode {#setWordWrapMode-int-}
```
public final void setWordWrapMode(int value)
```

Obtém ou define o modo de quebra de linha para a renderização de texto.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | Elemento WordWrapMode @see WordWrapMode |
