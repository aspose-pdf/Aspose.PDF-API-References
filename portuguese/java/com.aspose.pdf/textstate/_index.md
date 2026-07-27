---
title: "TextState"
linktitle: "TextState"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa o estado de texto de um texto"
type: docs
weight: 5340
url: /pt/java/com.aspose.pdf/textstate/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextState

```
public class TextState extends Object
```

Representa o estado de texto de um texto

## Campos

| Campo | Descrição |
| --- | --- |
| [TabstopDefaultValue](#TabstopDefaultValue) | Valor padrão de tabulação nas larguras do caractere de espaço da fonte padrão. |

## Construtores

| Construtor | Descrição |
| --- | --- |
| [TextState](#TextState--) | Cria objeto de estado de texto. |
| [TextState](#TextState-java.awt.Color-) | Cria objeto de estado de texto. |
| [TextState](#TextState-java.awt.Color-double-) | Cria objeto de estado de texto. |
| [TextState](#TextState-double-) | Cria objeto de estado de texto com especificação de tamanho de fonte. |
| [TextState](#TextState-java.lang.String-) | Cria objeto de estado de texto. |
| [TextState](#TextState-java.lang.String-boolean-boolean-) | Cria objeto de estado de texto. |
| [TextState](#TextState-java.lang.String-double-) | Cria objeto de estado de texto. |

## Métodos

| Método | Descrição |
| --- | --- |
| [applyChangesFrom](#applyChangesFrom-com.aspose.pdf.TextState-) | <p> Aplica configurações de outro textState </p> <hr> <p> Somente as propriedades que foram alteradas explicitamente serão copiadas. </p> |
| [calculateFontSize](#calculateFontSize-java.lang.String-com.aspose.pdf.Rectangle-) | Calcula o tamanho da fonte para o retângulo. |
| [getBackgroundColor](#getBackgroundColor--) | <p> Obtém a cor de fundo do texto. </p> <hr> <p> Observe que o valor não é preservado como uma característica de texto dentro do documento. O getter da propriedade BackgroundColor funciona para um objeto caso ele tenha sido definido explicitamente anteriormente com o setter BackgroundColor para esse objeto. A propriedade é usada em tempo de execução no contexto do processo atual de geração/modificação. </p> |
| [getCharacterSpacing](#getCharacterSpacing--) | Obtém o espaçamento de caracteres do texto. |
| [getCoordinateOrigin](#getCoordinateOrigin--) | Obtém ou define o CoordinateOrigin do texto. Se o CoordinateOrigin for Descender, a coordenada Y do texto corresponde ao ponto mais baixo da fonte. Se o CoordinateOrigin for BaseLine, a coordenada Y do texto corresponde à linha de base da fonte. O valor padrão é Descender. Se o valor Descent da fonte for muito grande, o texto pode ser renderizado mais alto que outras fontes. Nesse caso, o CoordinateOrigin BaseLine pode ser selecionado para melhorar a renderização do texto. |
| [getFont](#getFont--) | Obtém a fonte do texto. |
| [getfontSize](#getfontSize--) | Representa o método getfontSize |
| [getFontSize](#getFontSize--) | Obtém o tamanho da fonte do texto. |
| [getFontStyle](#getFontStyle--) | Define o estilo da fonte do texto. |
| [getForegroundColor](#getForegroundColor--) | Obtém a cor de primeiro plano do texto. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | <p> Obtém o alinhamento horizontal do texto. </p> <hr> <p> HorizontalAlignment.None é igual a HorizontalAlignment.Left. Observe que a propriedade TextState.HorizontalAlignment funciona apenas em cenários de geração de documentos novos. </p> |
| [getHorizontalScaling](#getHorizontalScaling--) | Obtém o dimensionamento horizontal do texto. |
| [getLineSpacing](#getLineSpacing--) | <p> Obtém o espaçamento entre linhas do texto. </p> |
| [getRenderingMode](#getRenderingMode--) | Obtém ou define o modo de renderização do texto. |
| [getStrokingColor](#getStrokingColor--) | Obtém ou define a cor de primeiro plano do texto. |
| [getTabTag](#getTabTag--) | <p> Você pode colocar esta tag no texto para declarar tabulação. </p> <hr> <p> Ela tem efeito apenas em conjunto com {@code TabStops}. </p> |
| [getTextHeight](#getTextHeight--) | Obtém a altura do texto. |
| [getWordSpacing](#getWordSpacing--) | Obtém o espaçamento entre palavras do texto. |
| [isInvisible](#isInvisible--) | Obtém a invisibilidade do texto. Isso basicamente reflete o estado {@code RenderingMode}({@link #getRenderingMode}/{@code #setRenderingMode(TextRenderingMode)}), exceto em alguns casos especiais (como recorte). |
| [isStrikeOut](#isStrikeOut--) | Obtém o tachado do texto, representado pelo objeto {@code TextFragment} |
| [isSubscript](#isSubscript--) | Obtém ou define o subscrito do texto. |
| [isSuperscript](#isSuperscript--) | Obtém o sobrescrito do texto. |
| [isUnderline](#isUnderline--) | Obtém o sublinhado do texto, representado pelo objeto {@code TextFragment} |
| [measureHeight](#measureHeight-char-) | Mede a altura dos caracteres. |
| [measureString](#measureString-java.lang.String-) | Mede a cadeia de caracteres. |
| [measureString](#measureString-java.lang.String-boolean-) | <p> Mede a cadeia de caracteres. </p> <hr> <p> insideLine indica que a cadeia não está terminando. Caso apenas parte da cadeia completa seja medida, insideLine deve ser true. Caso a cadeia completa seja medida, insideLine deve ser false. Em outras palavras: se insideLine = true, apenas as larguras dos caracteres são consideradas. Nenhuma transformação adicional é considerada se insideLine = false. O final da cadeia é tratado corretamente - a transformação em itálico é considerada. </p> |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Define a cor de fundo do texto. |
| [setCharacterSpacing](#setCharacterSpacing-float-) | Define o espaçamento entre caracteres do texto. |
| [setCoordinateOrigin](#setCoordinateOrigin-com.aspose.pdf.CoordinateOrigin-) | Obtém ou define o CoordinateOrigin do texto. Se o CoordinateOrigin for Descender, a coordenada Y do texto corresponde ao ponto mais baixo da fonte. Se o CoordinateOrigin for BaseLine, a coordenada Y do texto corresponde à linha de base da fonte. O valor padrão é Descender. Se o valor Descent da fonte for muito grande, o texto pode ser renderizado mais alto que outras fontes. Nesse caso, o CoordinateOrigin BaseLine pode ser selecionado para melhorar a renderização do texto. |
| [setFont](#setFont-com.aspose.pdf.Font-) | Obtém a fonte do texto. |
| [setFontSize](#setFontSize-float-) | Define o tamanho da fonte do texto. |
| [setFontSizeSuppressedUpdate](#setFontSizeSuppressedUpdate-float-) | Define o tamanho da fonte do texto com atualização suprimida. |
| [setFontStyle](#setFontStyle-int-) | Define o estilo da fonte do texto. |
| [setFontSuppressedUpdate](#setFontSuppressedUpdate-com.aspose.pdf.Font-) | Obtém a fonte do texto com atualização suprimida. |
| [setForegroundColor](#setForegroundColor-com.aspose.pdf.Color-) | Define a cor de primeiro plano do texto. |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | <p> Define o alinhamento horizontal para o texto. </p> <hr> <p> HorizontalAlignment.None é igual a HorizontalAlignment.Left. Observe que a propriedade TextState.HorizontalAlignment funciona apenas em cenários de geração de documentos novos. </p> |
| [setHorizontalScaling](#setHorizontalScaling-float-) | Define a escala horizontal do texto. |
| [setInvisible](#setInvisible-boolean-) | Define a invisibilidade do texto. Isso basicamente reflete o estado {@code RenderingMode}({@link #getRenderingMode}/{@code #setRenderingMode(TextRenderingMode)}), exceto em alguns casos especiais (como recorte). |
| [setLineSpacing](#setLineSpacing-float-) | <p> Define o espaçamento entre linhas do texto. </p> |
| [setRenderingMode](#setRenderingMode-com.aspose.pdf.TextRenderingMode-) | Obtém ou define o modo de renderização do texto. |
| [setStrikeOut](#setStrikeOut-boolean-) | Define o tachado para o texto, representado pelo objeto {@code TextFragment} |
| [setStrokingColor](#setStrokingColor-com.aspose.pdf.Color-) | Obtém ou define a cor de primeiro plano do texto. |
| [setSubscript](#setSubscript-boolean-) | Obtém ou define o subscrito do texto. |
| [setSuperscript](#setSuperscript-boolean-) | Define o sobrescrito do texto. |
| [setUnderline](#setUnderline-boolean-) | Define o sublinhado para o texto, representado pelo objeto {@code TextFragment} |
| [setWordSpacing](#setWordSpacing-float-) | Define o espaçamento entre palavras do texto. |

### TabstopDefaultValue {#TabstopDefaultValue}
```
public final float TabstopDefaultValue
```

Valor padrão de tabulação nas larguras do caractere de espaço da fonte padrão.

### TextState {#TextState--}
```
public TextState()
```

Cria objeto de estado de texto.

### TextState {#TextState-java.awt.Color-}
Cria objeto de estado de texto.

### TextState {#TextState-java.awt.Color-double-}
Cria objeto de estado de texto.

### TextState {#TextState-double-}
```
public TextState(double fontSize)
```

Cria objeto de estado de texto com especificação de tamanho de fonte.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fontSize |  | Tamanho da fonte. |

### TextState {#TextState-java.lang.String-}
Cria objeto de estado de texto.

### TextState {#TextState-java.lang.String-boolean-boolean-}
Cria objeto de estado de texto.

### TextState {#TextState-java.lang.String-double-}
Cria objeto de estado de texto.

### applyChangesFrom {#applyChangesFrom-com.aspose.pdf.TextState-}
<p> Aplica configurações de outro textState </p> <hr> <p> Somente as propriedades que foram alteradas explicitamente serão copiadas. </p>

### calculateFontSize {#calculateFontSize-java.lang.String-com.aspose.pdf.Rectangle-}
Calcula o tamanho da fonte para o retângulo.

### getBackgroundColor {#getBackgroundColor--}
```
public Color getBackgroundColor()
```

<p> Obtém a cor de fundo do texto. </p> <hr> <p> Observe que o valor não é preservado como uma característica de texto dentro do documento. O getter da propriedade BackgroundColor funciona para um objeto caso ele tenha sido definido explicitamente anteriormente com o setter BackgroundColor para esse objeto. A propriedade é usada em tempo de execução no contexto do processo atual de geração/modificação. </p>

**Returns:**
Valor da cor

### getCharacterSpacing {#getCharacterSpacing--}
```
public float getCharacterSpacing()
```

Obtém o espaçamento de caracteres do texto.

**Returns:**
valor float

### getCoordinateOrigin {#getCoordinateOrigin--}
```
public CoordinateOrigin getCoordinateOrigin()
```

Obtém ou define o CoordinateOrigin do texto. Se o CoordinateOrigin for Descender, a coordenada Y do texto corresponde ao ponto mais baixo da fonte. Se o CoordinateOrigin for BaseLine, a coordenada Y do texto corresponde à linha de base da fonte. O valor padrão é Descender. Se o valor Descent da fonte for muito grande, o texto pode ser renderizado mais alto que outras fontes. Nesse caso, o CoordinateOrigin BaseLine pode ser selecionado para melhorar a renderização do texto.

**Returns:**
elemento CoordinateOrigin

### getFont {#getFont--}
```
public Font getFont()
```

Obtém a fonte do texto.

**Returns:**
objeto Font

### getfontSize {#getfontSize--}
```
public float getfontSize()
```

Representa o método getfontSize

**Returns:**
valor float

### getFontSize {#getFontSize--}
```
public float getFontSize()
```

Obtém o tamanho da fonte do texto.

**Returns:**
valor float

### getFontStyle {#getFontStyle--}
```
public int getFontStyle()
```

Define o estilo da fonte do texto.

**Returns:**
elemento FontStyles @see FontStyles

### getForegroundColor {#getForegroundColor--}
```
public Color getForegroundColor()
```

Obtém a cor de primeiro plano do texto.

**Returns:**
Valor da cor

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

<p> Obtém o alinhamento horizontal do texto. </p> <hr> <p> HorizontalAlignment.None é igual a HorizontalAlignment.Left. Observe que a propriedade TextState.HorizontalAlignment funciona apenas em cenários de geração de documentos novos. </p>

**Returns:**
Valor HorizontalAlignment @see HorizontalAlignment

### getHorizontalScaling {#getHorizontalScaling--}
```
public float getHorizontalScaling()
```

Obtém o dimensionamento horizontal do texto.

**Returns:**
valor float

### getLineSpacing {#getLineSpacing--}
```
public float getLineSpacing()
```

<p> Obtém o espaçamento entre linhas do texto. </p>

**Returns:**
valor float <hr> <p> Observe que o valor não é preservado como uma característica de texto dentro do documento. O getter da propriedade LineSpacing funciona para um objeto caso ele tenha sido definido explicitamente anteriormente com o setter LineSpacing para esse objeto. A propriedade é usada em tempo de execução no contexto do processo atual de geração/modificação. </p>

### getRenderingMode {#getRenderingMode--}
```
public TextRenderingMode getRenderingMode()
```

Obtém ou define o modo de renderização do texto.

**Returns:**
elemento TextRenderingMode @see TextRenderingMode

### getStrokingColor {#getStrokingColor--}
```
public Color getStrokingColor()
```

Obtém ou define a cor de primeiro plano do texto.

**Returns:**
Instância de Color

### getTabTag {#getTabTag--}
```
public final String getTabTag()
```

<p> Você pode colocar esta tag no texto para declarar tabulação. </p> <hr> <p> Ela tem efeito apenas em conjunto com {@code TabStops}. </p>

**Returns:**
valor String "#$TAB"

### getTextHeight {#getTextHeight--}
```
public float getTextHeight()
```

Obtém a altura do texto.

**Returns:**
valor float

### getWordSpacing {#getWordSpacing--}
```
public float getWordSpacing()
```

Obtém o espaçamento entre palavras do texto.

**Returns:**
valor float

### isInvisible {#isInvisible--}
```
public boolean isInvisible()
```

Obtém a invisibilidade do texto. Isso basicamente reflete o estado {@code RenderingMode}({@link #getRenderingMode}/{@code #setRenderingMode(TextRenderingMode)}), exceto em alguns casos especiais (como recorte).

**Returns:**
valor booleano

### isStrikeOut {#isStrikeOut--}
```
public boolean isStrikeOut()
```

Obtém o tachado do texto, representado pelo objeto {@code TextFragment}

**Returns:**
valor booleano

### isSubscript {#isSubscript--}
```
public boolean isSubscript()
```

Obtém ou define o subscrito do texto.

**Returns:**
valor booleano

### isSuperscript {#isSuperscript--}
```
public boolean isSuperscript()
```

Obtém o sobrescrito do texto.

**Returns:**
valor booleano

### isUnderline {#isUnderline--}
```
public boolean isUnderline()
```

Obtém o sublinhado do texto, representado pelo objeto {@code TextFragment}

**Returns:**
valor booleano

### measureHeight {#measureHeight-char-}
```
public double measureHeight(char character)
```

Mede a altura dos caracteres.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| caractere |  | Caractere a medir. |

**Returns:**
Altura do caractere se pudermos obtê-la da fonte; caso contrário, 0.

### measureString {#measureString-java.lang.String-}
Mede a cadeia de caracteres.

### measureString {#measureString-java.lang.String-boolean-}
<p> Mede a cadeia de caracteres. </p> <hr> <p> insideLine indica que a cadeia não está terminando. Caso apenas parte da cadeia completa seja medida, insideLine deve ser true. Caso a cadeia completa seja medida, insideLine deve ser false. Em outras palavras: se insideLine = true, apenas as larguras dos caracteres são consideradas. Nenhuma transformação adicional é considerada se insideLine = false. O final da cadeia é tratado corretamente - a transformação em itálico é considerada. </p>

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Define a cor de fundo do texto.

### setCharacterSpacing {#setCharacterSpacing-float-}
```
public void setCharacterSpacing(float value)
```

Define o espaçamento entre caracteres do texto.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor float |

### setCoordinateOrigin {#setCoordinateOrigin-com.aspose.pdf.CoordinateOrigin-}
Obtém ou define o CoordinateOrigin do texto. Se o CoordinateOrigin for Descender, a coordenada Y do texto corresponde ao ponto mais baixo da fonte. Se o CoordinateOrigin for BaseLine, a coordenada Y do texto corresponde à linha de base da fonte. O valor padrão é Descender. Se o valor Descent da fonte for muito grande, o texto pode ser renderizado mais alto que outras fontes. Nesse caso, o CoordinateOrigin BaseLine pode ser selecionado para melhorar a renderização do texto.

### setFont {#setFont-com.aspose.pdf.Font-}
Obtém a fonte do texto.

### setFontSize {#setFontSize-float-}
```
public void setFontSize(float value)
```

Define o tamanho da fonte do texto.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor float |

### setFontSizeSuppressedUpdate {#setFontSizeSuppressedUpdate-float-}
```
public void setFontSizeSuppressedUpdate(float value)
```

Define o tamanho da fonte do texto com atualização suprimida.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor float |

### setFontStyle {#setFontStyle-int-}
```
public void setFontStyle(int value)
```

Define o estilo da fonte do texto.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor FontStyles @see FontStyles |

### setFontSuppressedUpdate {#setFontSuppressedUpdate-com.aspose.pdf.Font-}
Obtém a fonte do texto com atualização suprimida.

### setForegroundColor {#setForegroundColor-com.aspose.pdf.Color-}
Define a cor de primeiro plano do texto.

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
<p> Define o alinhamento horizontal para o texto. </p> <hr> <p> HorizontalAlignment.None é igual a HorizontalAlignment.Left. Observe que a propriedade TextState.HorizontalAlignment funciona apenas em cenários de geração de documentos novos. </p>

### setHorizontalScaling {#setHorizontalScaling-float-}
```
public void setHorizontalScaling(float value)
```

Define a escala horizontal do texto.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor float |

### setInvisible {#setInvisible-boolean-}
```
public void setInvisible(boolean value)
```

Define a invisibilidade do texto. Isso basicamente reflete o estado {@code RenderingMode}({@link #getRenderingMode}/{@code #setRenderingMode(TextRenderingMode)}), exceto em alguns casos especiais (como recorte).

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setLineSpacing {#setLineSpacing-float-}
```
public void setLineSpacing(float value)
```

<p> Define o espaçamento entre linhas do texto. </p>

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor float <hr> <p> Observe que o valor não é preservado como uma característica de texto dentro do documento. O getter da propriedade LineSpacing funciona para um objeto caso ele tenha sido definido explicitamente anteriormente com o setter LineSpacing para esse objeto. A propriedade é usada em tempo de execução no contexto do processo atual de geração/modificação. </p> |

### setRenderingMode {#setRenderingMode-com.aspose.pdf.TextRenderingMode-}
Obtém ou define o modo de renderização do texto.

### setStrikeOut {#setStrikeOut-boolean-}
```
public void setStrikeOut(boolean value)
```

Define o tachado para o texto, representado pelo objeto {@code TextFragment}

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setStrokingColor {#setStrokingColor-com.aspose.pdf.Color-}
Obtém ou define a cor de primeiro plano do texto.

### setSubscript {#setSubscript-boolean-}
```
public void setSubscript(boolean value)
```

Obtém ou define o subscrito do texto.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setSuperscript {#setSuperscript-boolean-}
```
public void setSuperscript(boolean value)
```

Define o sobrescrito do texto.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setUnderline {#setUnderline-boolean-}
```
public void setUnderline(boolean value)
```

Define o sublinhado para o texto, representado pelo objeto {@code TextFragment}

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setWordSpacing {#setWordSpacing-float-}
```
public void setWordSpacing(float value)
```

Define o espaçamento entre palavras do texto.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor float |
