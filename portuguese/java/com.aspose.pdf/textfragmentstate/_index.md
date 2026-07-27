---
title: "TextFragmentState"
linktitle: "TextFragmentState"
second_title: "Referência da API Aspose.PDF para Java"
description: "<p> Representa o estado de texto de um fragmento de texto. </p> <hr> <pre> O exemplo demonstra como alterar a cor do texto e o tamanho da fonte do texto com o objeto {@code TextState}. // Open.</pre>"
type: docs
weight: 5150
url: /pt/java/com.aspose.pdf/textfragmentstate/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextState com.aspose.pdf.TextFragmentState, com.aspose.pdf.TextState, com.aspose.pdf.TextFragmentState

```
public final class TextFragmentState extends TextState
```

<p> Representa o estado de texto de um fragmento de texto. </p> <hr> <pre> O exemplo demonstra como alterar a cor do texto e o tamanho da fonte do texto com o objeto {@code TextState}. // Abrir documento Document doc = new Document("D:\\Tests\\input.pdf"); // Criar objeto TextFragmentAbsorber para encontrar todas as ocorrências de texto "hello world" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Aceitar o absorvedor na primeira página doc.getPages().get(1).accept(absorber); // Alterar a cor de primeiro plano da primeira ocorrência de texto absorber.TgetextFragments().get(1).getTextState().setForegroundColor ( java.awt.Color.RED); // Alterar o tamanho da fonte da primeira ocorrência de texto absorber.getTextFragments().get(1).getTextState().setFontSize ( 15); // Salvar documento doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Fornece uma maneira de alterar as seguintes propriedades do texto: fonte ({@code TextFragmentState.Font} property) tamanho da fonte ({@code TextFragmentState.FontSize} property) estilo da fonte ({@code TextFragmentState.FontStyle} property) cor de primeiro plano ({@code TextFragmentState.ForegroundColor} property) cor de fundo ({@code TextFragmentState.BackgroundColor} property) <p> Observe que alterar as propriedades {@code TextFragmentState} pode mudar a coleção interna {@code TextFragment.Segments}, pois TextFragment é um objeto agregado e pode reorganizar os segmentos internos ou mesclá-los em um único segmento. Se o seu requisito for deixar a coleção {@code TextFragment.Segments} inalterada, altere os segmentos internos individualmente. </p> @see TextFragmentAbsorber @see IDocument

## Construtores

| Construtor | Descrição |
| --- | --- |
| [TextFragmentState](#TextFragmentState-com.aspose.pdf.TextFragment-) | Inicializa uma nova instância do objeto {@code TextFragmentState} com o objeto {@code TextFragment} especificado. Esta inicialização de {@code TextFragmentState} não é suportada. TextFragmentState está disponível apenas com a propriedade {@code TextFragment.TextState}. |

## Métodos

| Método | Descrição |
| --- | --- |
| [applyChangesFrom](#applyChangesFrom-com.aspose.pdf.TextState-) | <p> Aplica configurações de outro textState </p> |
| [applyChangesFrom](#applyChangesFrom-com.aspose.pdf.TextState-boolean-) | Aplica configurações de outro textState |
| [getBackgroundColor](#getBackgroundColor--) | Define a cor de fundo do texto, representada pelo objeto {@code TextFragment} |
| [getCharacterSpacing](#getCharacterSpacing--) | Obtém o espaçamento de caracteres do texto, representado pelo objeto {@code TextFragment}. |
| [getCoordinateOrigin](#getCoordinateOrigin--) | Obtém ou define o CoordinateOrigin do texto. Se o CoordinateOrigin for Descender, a coordenada Y do texto corresponde ao ponto mais baixo da fonte. Se o CoordinateOrigin for BaseLine, a coordenada Y do texto corresponde à linha de base da fonte. O valor padrão é Descender. Se o valor Descent da fonte for muito grande, o texto pode ser renderizado mais alto que outras fontes. Nesse caso, o CoordinateOrigin BaseLine pode ser selecionado para melhorar a renderização do texto. |
| [getDrawTextRectangleBorder](#getDrawTextRectangleBorder--) | Obtém se a bandeira de desenho da borda do retângulo de texto está ativada. |
| [getFont](#getFont--) | Obtém a fonte do texto, representada pelo objeto {@code TextFragment} |
| [getFontSize](#getFontSize--) | Obtém o tamanho da fonte do texto, representado pelo objeto {@code TextFragment} |
| [getFontStyle](#getFontStyle--) | Define o estilo da fonte do texto, representado pelo objeto {@code TextFragment} |
| [getForegroundColor](#getForegroundColor--) | Obtém a cor de primeiro plano do texto, representada pelo objeto {@code TextFragment} |
| [getFormattingOptions](#getFormattingOptions--) | Obtém ou define opções de formatação. A definição das opções será efetiva apenas em cenários de geração. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | <p> Obtém o alinhamento horizontal do texto. </p> <hr> <p> HorizontalAlignment.None é igual a HorizontalAlignment.Left. Observe que a propriedade TextFragmentState.VerticalAlignment funciona apenas em novos cenários de geração de documentos. </p> |
| [getHorizontalScaling](#getHorizontalScaling--) | Obtém a escala horizontal do texto, representada pelo objeto {@code TextFragment}. |
| [getLineSpacing](#getLineSpacing--) | <p> Obtém o espaçamento entre linhas do texto. </p> |
| [getRenderingMode](#getRenderingMode--) | Obtém ou define o modo de renderização do texto. |
| [getRotation](#getRotation--) | Obtém ou define o ângulo de rotação em graus. |
| [getStrokingColor](#getStrokingColor--) | Obtém ou define as operações de contorno de cor da renderização {@code TextFragment} (contorno de texto, borda do retângulo) |
| [getTabStops](#getTabStops--) | <p> Obtém as tabulações para o texto. </p> <hr> <p> Observe que a propriedade Tabstops funciona apenas em novos cenários de geração de documentos. Tabstops podem ser adicionados durante a inicialização {@code TextFragment}. Tabstops devem ser construídos antes do texto. </p> |
| [getTextHeight](#getTextHeight--) | Obtém a altura do texto, representada pelo objeto {@code TextFragment} |
| [getWordSpacing](#getWordSpacing--) | Obtém o espaçamento entre palavras do texto. |
| [isFitRectangle](#isFitRectangle-java.lang.String-com.aspose.pdf.Rectangle-) | Verifica se a string de entrada pode ser colocada dentro do retângulo definido. |
| [isInvisible](#isInvisible--) | Obtém a invisibilidade do texto. |
| [isStrikeOut](#isStrikeOut--) | Obtém ou define o tachado do texto, representado pelo objeto {@link TextFragment} |
| [isSubscript](#isSubscript--) | Obtém ou define o subscrito do texto, representado pelo objeto {@code TextFragment}. |
| [isSuperscript](#isSuperscript--) | Obtém ou define o sobrescrito do texto, representado pelo objeto {@code TextFragment}. |
| [isUnderline](#isUnderline--) | Obtém ou define o sublinhado do texto, representado pelo objeto {@link TextFragment} |
| [measureHeight](#measureHeight-char-) | Mede a altura dos caracteres. |
| [measureString](#measureString-java.lang.String-) | Mede a cadeia de caracteres. |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Define a cor de fundo do texto, representado pelo objeto TextFragment |
| [setCharacterSpacing](#setCharacterSpacing-float-) | Define o espaçamento de caracteres do texto, representado pelo objeto {@code TextFragment}. |
| [setCoordinateOrigin](#setCoordinateOrigin-com.aspose.pdf.CoordinateOrigin-) | Obtém ou define o CoordinateOrigin do texto. Se o CoordinateOrigin for Descender, a coordenada Y do texto corresponde ao ponto mais baixo da fonte. Se o CoordinateOrigin for BaseLine, a coordenada Y do texto corresponde à linha de base da fonte. O valor padrão é Descender. Se o valor Descent da fonte for muito grande, o texto pode ser renderizado mais alto que outras fontes. Nesse caso, o CoordinateOrigin BaseLine pode ser selecionado para melhorar a renderização do texto. |
| [setDrawTextRectangleBorder](#setDrawTextRectangleBorder-boolean-) | Define se a bandeira de desenho da borda do retângulo de texto está ativada. |
| [setFont](#setFont-com.aspose.pdf.Font-) | Define a fonte do texto, representada pelo objeto {@code TextFragment} |
| [setFontSize](#setFontSize-float-) | Define o tamanho da fonte do texto, representado pelo objeto {@code TextFragment} |
| [setFontStyle](#setFontStyle-int-) | Define o estilo da fonte do texto, representado pelo objeto {@link TextFragment} |
| [setForegroundColor](#setForegroundColor-com.aspose.pdf.Color-) | Define a cor de primeiro plano do texto, representada pelo objeto {@code TextFragment} |
| [setFormattingOptions](#setFormattingOptions-com.aspose.pdf.TextFormattingOptions-) | Obtém ou define opções de formatação. A definição das opções será efetiva apenas em cenários de geração. |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | <p> Define o alinhamento horizontal do texto. </p> <hr> <p> HorizontalAlignment.None é igual a HorizontalAlignment.Left. Observe que a propriedade TextFragmentState.VerticalAlignment funciona apenas em cenários de geração de documentos novos. </p> |
| [setHorizontalScaling](#setHorizontalScaling-float-) | Define a escala horizontal do texto, representada pelo objeto {@code TextFragment}. |
| [setInvisible](#setInvisible-boolean-) | Define a invisibilidade do texto. |
| [setLineSpacing](#setLineSpacing-float-) | <p> Define o espaçamento entre linhas do texto. </p> |
| [setRenderingMode](#setRenderingMode-com.aspose.pdf.TextRenderingMode-) | Obtém ou define o modo de renderização do texto. |
| [setRotation](#setRotation-double-) | Obtém ou define o ângulo de rotação em graus. |
| [setStrikeOut](#setStrikeOut-boolean-) | Define o tachado para o texto, representado pelo objeto {@code TextFragment} |
| [setStrokingColor](#setStrokingColor-com.aspose.pdf.Color-) | Obtém ou define as operações de contorno de cor da renderização {@code TextFragment} (contorno de texto, borda do retângulo) |
| [setSubscript](#setSubscript-boolean-) | Obtém ou define o subscrito do texto, representado pelo objeto {@code TextFragment}. |
| [setSuperscript](#setSuperscript-boolean-) | Obtém ou define o sobrescrito do texto, representado pelo objeto {@code TextFragment}. |
| [setUnderline](#setUnderline-boolean-) | Define o sublinhado para o texto, representado pelo objeto {@code TextFragment} |
| [setWordSpacing](#setWordSpacing-float-) | Define o espaçamento entre palavras do texto. |

### TextFragmentState {#TextFragmentState-com.aspose.pdf.TextFragment-}
Inicializa uma nova instância do objeto {@code TextFragmentState} com o objeto {@code TextFragment} especificado. Esta inicialização de {@code TextFragmentState} não é suportada. TextFragmentState está disponível apenas com a propriedade {@code TextFragment.TextState}.

### applyChangesFrom {#applyChangesFrom-com.aspose.pdf.TextState-}
<p> Aplica configurações de outro textState </p>

### applyChangesFrom {#applyChangesFrom-com.aspose.pdf.TextState-boolean-}
Aplica configurações de outro textState

### getBackgroundColor {#getBackgroundColor--}
```
public Color getBackgroundColor()
```

Define a cor de fundo do texto, representada pelo objeto {@code TextFragment}

**Returns:**
objeto Color de valor

### getCharacterSpacing {#getCharacterSpacing--}
```
public float getCharacterSpacing()
```

Obtém o espaçamento de caracteres do texto, representado pelo objeto {@code TextFragment}.

**Returns:**
valor float

### getCoordinateOrigin {#getCoordinateOrigin--}
```
public CoordinateOrigin getCoordinateOrigin()
```

Obtém ou define o CoordinateOrigin do texto. Se o CoordinateOrigin for Descender, a coordenada Y do texto corresponde ao ponto mais baixo da fonte. Se o CoordinateOrigin for BaseLine, a coordenada Y do texto corresponde à linha de base da fonte. O valor padrão é Descender. Se o valor Descent da fonte for muito grande, o texto pode ser renderizado mais alto que outras fontes. Nesse caso, o CoordinateOrigin BaseLine pode ser selecionado para melhorar a renderização do texto.

**Returns:**
elemento CoordinateOrigin

### getDrawTextRectangleBorder {#getDrawTextRectangleBorder--}
```
public boolean getDrawTextRectangleBorder()
```

Obtém se a bandeira de desenho da borda do retângulo de texto está ativada.

**Returns:**
valor booleano

### getFont {#getFont--}
```
public Font getFont()
```

Obtém a fonte do texto, representada pelo objeto {@code TextFragment}

**Returns:**
Valor da fonte

### getFontSize {#getFontSize--}
```
public float getFontSize()
```

Obtém o tamanho da fonte do texto, representado pelo objeto {@code TextFragment}

**Returns:**
valor float

### getFontStyle {#getFontStyle--}
```
public int getFontStyle()
```

Define o estilo da fonte do texto, representado pelo objeto {@code TextFragment}

**Returns:**
elemento FontStyles @see FontStyles

### getForegroundColor {#getForegroundColor--}
```
public Color getForegroundColor()
```

Obtém a cor de primeiro plano do texto, representada pelo objeto {@code TextFragment}

**Returns:**
Objeto Color

### getFormattingOptions {#getFormattingOptions--}
```
public TextFormattingOptions getFormattingOptions()
```

Obtém ou define opções de formatação. A definição das opções será efetiva apenas em cenários de geração.

**Returns:**
instância de TextFormattingOptions

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

<p> Obtém o alinhamento horizontal do texto. </p> <hr> <p> HorizontalAlignment.None é igual a HorizontalAlignment.Left. Observe que a propriedade TextFragmentState.VerticalAlignment funciona apenas em novos cenários de geração de documentos. </p>

**Returns:**
Valor HorizontalAlignment @see HorizontalAlignment

### getHorizontalScaling {#getHorizontalScaling--}
```
public float getHorizontalScaling()
```

Obtém a escala horizontal do texto, representada pelo objeto {@code TextFragment}.

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
elemento TextRenderingMode

### getRotation {#getRotation--}
```
public double getRotation()
```

Obtém ou define o ângulo de rotação em graus.

**Returns:**
valor double

### getStrokingColor {#getStrokingColor--}
```
public Color getStrokingColor()
```

Obtém ou define as operações de contorno de cor da renderização {@code TextFragment} (contorno de texto, borda do retângulo)

**Returns:**
Instância de Color

### getTabStops {#getTabStops--}
```
public TabStops getTabStops()
```

<p> Obtém as tabulações para o texto. </p> <hr> <p> Observe que a propriedade Tabstops funciona apenas em novos cenários de geração de documentos. Tabstops podem ser adicionados durante a inicialização {@code TextFragment}. Tabstops devem ser construídos antes do texto. </p>

**Returns:**
objeto TabStops

### getTextHeight {#getTextHeight--}
```
public float getTextHeight()
```

Obtém a altura do texto, representada pelo objeto {@code TextFragment}

**Returns:**
valor float

### getWordSpacing {#getWordSpacing--}
```
public float getWordSpacing()
```

Obtém o espaçamento entre palavras do texto.

**Returns:**
valor float

### isFitRectangle {#isFitRectangle-java.lang.String-com.aspose.pdf.Rectangle-}
Verifica se a string de entrada pode ser colocada dentro do retângulo definido.

### isInvisible {#isInvisible--}
```
public boolean isInvisible()
```

Obtém a invisibilidade do texto.

**Returns:**
valor booleano

### isStrikeOut {#isStrikeOut--}
```
public boolean isStrikeOut()
```

Obtém ou define o tachado do texto, representado pelo objeto {@link TextFragment}

**Returns:**
valor booleano

### isSubscript {#isSubscript--}
```
public boolean isSubscript()
```

Obtém ou define o subscrito do texto, representado pelo objeto {@code TextFragment}.

**Returns:**
valor booleano

### isSuperscript {#isSuperscript--}
```
public boolean isSuperscript()
```

Obtém ou define o sobrescrito do texto, representado pelo objeto {@code TextFragment}.

**Returns:**
valor booleano

### isUnderline {#isUnderline--}
```
public boolean isUnderline()
```

Obtém ou define o sublinhado do texto, representado pelo objeto {@link TextFragment}

**Returns:**
valor booleano

### measureHeight {#measureHeight-char-}
```
public final double measureHeight(char character)
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

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Define a cor de fundo do texto, representado pelo objeto TextFragment

### setCharacterSpacing {#setCharacterSpacing-float-}
```
public void setCharacterSpacing(float value)
```

Define o espaçamento de caracteres do texto, representado pelo objeto {@code TextFragment}.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor float |

### setCoordinateOrigin {#setCoordinateOrigin-com.aspose.pdf.CoordinateOrigin-}
Obtém ou define o CoordinateOrigin do texto. Se o CoordinateOrigin for Descender, a coordenada Y do texto corresponde ao ponto mais baixo da fonte. Se o CoordinateOrigin for BaseLine, a coordenada Y do texto corresponde à linha de base da fonte. O valor padrão é Descender. Se o valor Descent da fonte for muito grande, o texto pode ser renderizado mais alto que outras fontes. Nesse caso, o CoordinateOrigin BaseLine pode ser selecionado para melhorar a renderização do texto.

### setDrawTextRectangleBorder {#setDrawTextRectangleBorder-boolean-}
```
public void setDrawTextRectangleBorder(boolean value)
```

Define se a bandeira de desenho da borda do retângulo de texto está ativada.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setFont {#setFont-com.aspose.pdf.Font-}
Define a fonte do texto, representada pelo objeto {@code TextFragment}

### setFontSize {#setFontSize-float-}
```
public void setFontSize(float value)
```

Define o tamanho da fonte do texto, representado pelo objeto {@code TextFragment}

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor float |

### setFontStyle {#setFontStyle-int-}
```
public void setFontStyle(int value)
```

Define o estilo da fonte do texto, representado pelo objeto {@link TextFragment}

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int @see FontStyles |

### setForegroundColor {#setForegroundColor-com.aspose.pdf.Color-}
Define a cor de primeiro plano do texto, representada pelo objeto {@code TextFragment}

### setFormattingOptions {#setFormattingOptions-com.aspose.pdf.TextFormattingOptions-}
Obtém ou define opções de formatação. A definição das opções será efetiva apenas em cenários de geração.

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
<p> Define o alinhamento horizontal do texto. </p> <hr> <p> HorizontalAlignment.None é igual a HorizontalAlignment.Left. Observe que a propriedade TextFragmentState.VerticalAlignment funciona apenas em cenários de geração de documentos novos. </p>

### setHorizontalScaling {#setHorizontalScaling-float-}
```
public void setHorizontalScaling(float value)
```

Define a escala horizontal do texto, representada pelo objeto {@code TextFragment}.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor float |

### setInvisible {#setInvisible-boolean-}
```
public void setInvisible(boolean value)
```

Define a invisibilidade do texto.

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

### setRotation {#setRotation-double-}
```
public void setRotation(double value)
```

Obtém ou define o ângulo de rotação em graus.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

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
Obtém ou define as operações de contorno de cor da renderização {@code TextFragment} (contorno de texto, borda do retângulo)

### setSubscript {#setSubscript-boolean-}
```
public void setSubscript(boolean value)
```

Obtém ou define o subscrito do texto, representado pelo objeto {@code TextFragment}.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setSuperscript {#setSuperscript-boolean-}
```
public void setSuperscript(boolean value)
```

Obtém ou define o sobrescrito do texto, representado pelo objeto {@code TextFragment}.

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
