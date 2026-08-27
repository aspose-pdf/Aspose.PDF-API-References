---
title: "TextParagraph"
linktitle: "TextParagraph"
second_title: "Referência da API Aspose.PDF para Java"
description: "<p> Representa parágrafos de texto como objeto de texto multilinha. </p> <hr> <pre> O exemplo demonstra como criar um objeto de parágrafo de texto e adicioná-lo à página Pdf. Document doc."
type: docs
weight: 5200
url: /pt/java/com.aspose.pdf/textparagraph/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextParagraph

```
public final class TextParagraph extends Object
```

<p> Representa parágrafos de texto como objeto de texto multilinha. </p> <hr> <pre> O exemplo demonstra como criar um objeto de parágrafo de texto e adicioná‑lo à página Pdf. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // cria parágrafo de texto TextParagraph paragraph = new TextParagraph(); // define o retângulo do parágrafo paragraph.setRectangle ( new Rectangle(100, 600, 200, 700)); // define opções de quebra de linha paragraph.getFormattingOptions().setWrapMode ( TextFormattingOptions.WordWrapMode.ByWords); // adiciona linhas de string paragraph.appendLine("a rápida raposa marrom pula sobre o cão preguiçoso"); paragraph.appendLine("linha2"); paragraph.appendLine("linha3"); // adiciona o parágrafo à página Pdf com o TextBuilder TextBuilder textBuilder = new TextBuilder(page); textBuilder.appendParagraph(paragraph); // salva o documento Pdf doc.save(outFile); </pre>

## Construtores

| Construtor | Descrição |
| --- | --- |
| [TextParagraph](#TextParagraph--) | Cria objeto {@code TextParagraph}. |

## Métodos

| Método | Descrição |
| --- | --- |
| [appendLine](#appendLine-java.lang.String-) | Anexa linha de texto |
| [appendLine](#appendLine-java.lang.String-float-) | Anexa linha de texto. |
| [appendLine](#appendLine-java.lang.String-com.aspose.pdf.TextState-) | Anexa linha de texto com parâmetros de estado de texto. |
| [appendLine](#appendLine-java.lang.String-com.aspose.pdf.TextState-float-) | Anexa linha de texto com parâmetros de estado de texto |
| [appendLine](#appendLine-com.aspose.pdf.TextFragment-) | Anexa linha de texto com parâmetros de estado de texto. |
| [appendLine](#appendLine-com.aspose.pdf.TextFragment-com.aspose.pdf.TextState-) | Anexa linha de texto com parâmetros de estado de texto. |
| [appendLine](#appendLine-com.aspose.pdf.TextFragment-com.aspose.pdf.TextState-float-) | Anexa linha de texto com parâmetros de estado de texto |
| [beginEdit](#beginEdit--) | Inicia a edição do TextParagraph. <p> Melhora o desempenho da população do TextParagraph. Qualquer cálculo de layout é suspenso até que o método EndEdit seja invocado. <p> Observe que a invocação do método não pode ser aninhada. </p> |
| [endEdit](#endEdit--) | Finaliza a edição do TextParagraph. <p> Melhora o desempenho da população do TextParagraph. Qualquer cálculo de layout é suspenso até que o método EndEdit seja invocado. <p> Observe que a invocação do método não pode ser aninhada. </p> |
| [getFirstLineIndent](#getFirstLineIndent--) | Obtém ou define o valor de recuo das linhas subsequentes. Se definido como um valor diferente de zero, tem vantagem sobre o valor FormattingOptions.SubsequentLinesIndent. |
| [getFormattingOptions](#getFormattingOptions--) | Obtém as opções de formatação. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | Obtém o alinhamento horizontal para o texto dentro do Rectangle do parágrafo. HorizontalAlignment.None é equivalente a HorizontalAlignment.Left. |
| [getHyphenSymbol](#getHyphenSymbol--) | Obtém o símbolo de hífen usado no processo de hifenização. O símbolo de hifenização é "-" por padrão. Para eliminar a renderização do hífen (mantendo o procedimento de quebra de linha), defina uma string vazia string.Empty para HyphenSymbol. |
| [getMargin](#getMargin--) | Obtém o preenchimento. |
| [getPosition](#getPosition--) | Obtém a posição do parágrafo. |
| [getRectangle](#getRectangle--) | Obtém o retângulo do parágrafo. |
| [getRotation](#getRotation--) | Obtém ou define o ângulo de rotação em graus. |
| [getSubsequentLinesIndent](#getSubsequentLinesIndent--) | Obtém o valor de recuo das linhas subsequentes. |
| [getTextRectangle](#getTextRectangle--) | Obtém o retângulo do texto colocado no parágrafo. |
| [getVerticalAlignment](#getVerticalAlignment--) | <p> Obtém o alinhamento vertical para o texto dentro do {@code Rectangle} do parágrafo. </p> |
| [isJustify](#isJustify--) | Obtém o valor que indica se o texto está justificado. |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Define a cor de fundo para o parágrafo de texto. |
| [setBackgroundMode](#setBackgroundMode-int-) | Define o modo de fundo para o parágrafo de texto |
| [setFirstLineIndent](#setFirstLineIndent-float-) | Obtém ou define o valor de recuo das linhas subsequentes. Se definido como um valor diferente de zero, tem vantagem sobre o valor FormattingOptions.SubsequentLinesIndent. |
| [setFormattingOptions](#setFormattingOptions-com.aspose.pdf.TextFormattingOptions-) | Define as opções de formatação. |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | Define o alinhamento horizontal para o texto dentro do Rectangle do parágrafo. HorizontalAlignment.None é equivalente a HorizontalAlignment.Left. |
| [setHyphenSymbol](#setHyphenSymbol-java.lang.String-) | Define o símbolo de hífen usado no processo de hifenização. O símbolo de hifenização é "-" por padrão. Para eliminar a renderização do hífen (mantendo o procedimento de quebra de linha), defina uma string vazia string.Empty para HyphenSymbol. |
| [setJustify](#setJustify-boolean-) | Define o valor que indica se o texto está justificado. |
| [setMargin](#setMargin-com.aspose.pdf.MarginInfo-) | Define o preenchimento. |
| [setMatrix](#setMatrix-com.aspose.pdf.Matrix-) | Define a rotação do parágrafo. |
| [setOldCodeCompatibilityMode](#setOldCodeCompatibilityMode-boolean-) | Define o modo de compatibilidade com código antigo |
| [setPosition](#setPosition-com.aspose.pdf.Position-) | Define a posição do parágrafo. |
| [setRectangle](#setRectangle-com.aspose.pdf.Rectangle-) | Define o retângulo do parágrafo. |
| [setRotation](#setRotation-double-) | Obtém ou define o ângulo de rotação em graus. |
| [setSubsequentLinesIndent](#setSubsequentLinesIndent-float-) | Define o valor de recuo das linhas subsequentes. |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Define o alinhamento vertical para o texto dentro do {@code Rectangle} do parágrafo. VerticalAlignment.None é equivalente a VerticalAlignment.Bottom. |

### TextParagraph {#TextParagraph--}
```
public TextParagraph()
```

Cria objeto {@code TextParagraph}.

### appendLine {#appendLine-java.lang.String-}
Anexa linha de texto

### appendLine {#appendLine-java.lang.String-float-}
Anexa linha de texto.

### appendLine {#appendLine-java.lang.String-com.aspose.pdf.TextState-}
Anexa linha de texto com parâmetros de estado de texto.

### appendLine {#appendLine-java.lang.String-com.aspose.pdf.TextState-float-}
Anexa linha de texto com parâmetros de estado de texto

### appendLine {#appendLine-com.aspose.pdf.TextFragment-}
Anexa linha de texto com parâmetros de estado de texto.

### appendLine {#appendLine-com.aspose.pdf.TextFragment-com.aspose.pdf.TextState-}
Anexa linha de texto com parâmetros de estado de texto.

### appendLine {#appendLine-com.aspose.pdf.TextFragment-com.aspose.pdf.TextState-float-}
Anexa linha de texto com parâmetros de estado de texto

### beginEdit {#beginEdit--}
```
public void beginEdit()
```

Inicia a edição do TextParagraph. <p> Melhora o desempenho da população do TextParagraph. Qualquer cálculo de layout é suspenso até que o método EndEdit seja invocado. <p> Observe que a invocação do método não pode ser aninhada. </p>

### endEdit {#endEdit--}
```
public void endEdit()
```

Finaliza a edição do TextParagraph. <p> Melhora o desempenho da população do TextParagraph. Qualquer cálculo de layout é suspenso até que o método EndEdit seja invocado. <p> Observe que a invocação do método não pode ser aninhada. </p>

### getFirstLineIndent {#getFirstLineIndent--}
```
public final float getFirstLineIndent()
```

Obtém ou define o valor de recuo das linhas subsequentes. Se definido como um valor diferente de zero, tem vantagem sobre o valor FormattingOptions.SubsequentLinesIndent.

**Returns:**
valor float

### getFormattingOptions {#getFormattingOptions--}
```
public TextFormattingOptions getFormattingOptions()
```

Obtém as opções de formatação.

**Returns:**
Objeto TextFormattingOptions

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

Obtém o alinhamento horizontal para o texto dentro do Rectangle do parágrafo. HorizontalAlignment.None é equivalente a HorizontalAlignment.Left.

**Returns:**
Valor HorizontalAlignment @see HorizontalAlignment

### getHyphenSymbol {#getHyphenSymbol--}
```
public String getHyphenSymbol()
```

Obtém o símbolo de hífen usado no processo de hifenização. O símbolo de hifenização é "-" por padrão. Para eliminar a renderização do hífen (mantendo o procedimento de quebra de linha), defina uma string vazia string.Empty para HyphenSymbol.

**Returns:**
valor String

### getMargin {#getMargin--}
```
public MarginInfo getMargin()
```

Obtém o preenchimento.

**Returns:**
Valor MarginInfo

### getPosition {#getPosition--}
```
public Position getPosition()
```

Obtém a posição do parágrafo.

**Returns:**
Valor da posição

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Obtém o retângulo do parágrafo.

**Returns:**
objeto Rectangle

### getRotation {#getRotation--}
```
public double getRotation()
```

Obtém ou define o ângulo de rotação em graus.

**Returns:**
valor double

### getSubsequentLinesIndent {#getSubsequentLinesIndent--}
```
public float getSubsequentLinesIndent()
```

Obtém o valor de recuo das linhas subsequentes.

**Returns:**
valor float

### getTextRectangle {#getTextRectangle--}
```
public Rectangle getTextRectangle()
```

Obtém o retângulo do texto colocado no parágrafo.

**Returns:**
objeto Rectangle

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

<p> Obtém o alinhamento vertical para o texto dentro do {@code Rectangle} do parágrafo. </p>

**Returns:**
Valor VerticalAlignment @see VerticalAlignment <hr> <p> VerticalAlignment.None é igual a VerticalAlignment.Bottom. </p>

### isJustify {#isJustify--}
```
public boolean isJustify()
```

Obtém o valor que indica se o texto está justificado.

**Returns:**
valor booleano

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Define a cor de fundo para o parágrafo de texto.

### setBackgroundMode {#setBackgroundMode-int-}
```
public void setBackgroundMode(int value)
```

Define o modo de fundo para o parágrafo de texto

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int @see TextBackgroundMode |

### setFirstLineIndent {#setFirstLineIndent-float-}
```
public final void setFirstLineIndent(float value)
```

Obtém ou define o valor de recuo das linhas subsequentes. Se definido como um valor diferente de zero, tem vantagem sobre o valor FormattingOptions.SubsequentLinesIndent.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor float |

### setFormattingOptions {#setFormattingOptions-com.aspose.pdf.TextFormattingOptions-}
Define as opções de formatação.

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
Define o alinhamento horizontal para o texto dentro do Rectangle do parágrafo. HorizontalAlignment.None é equivalente a HorizontalAlignment.Left.

### setHyphenSymbol {#setHyphenSymbol-java.lang.String-}
Define o símbolo de hífen usado no processo de hifenização. O símbolo de hifenização é "-" por padrão. Para eliminar a renderização do hífen (mantendo o procedimento de quebra de linha), defina uma string vazia string.Empty para HyphenSymbol.

### setJustify {#setJustify-boolean-}
```
public void setJustify(boolean value)
```

Define o valor que indica se o texto está justificado.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setMargin {#setMargin-com.aspose.pdf.MarginInfo-}
Define o preenchimento.

### setMatrix {#setMatrix-com.aspose.pdf.Matrix-}
Define a rotação do parágrafo.

### setOldCodeCompatibilityMode {#setOldCodeCompatibilityMode-boolean-}
```
public void setOldCodeCompatibilityMode(boolean value)
```

Define o modo de compatibilidade com código antigo

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setPosition {#setPosition-com.aspose.pdf.Position-}
Define a posição do parágrafo.

### setRectangle {#setRectangle-com.aspose.pdf.Rectangle-}
Define o retângulo do parágrafo.

### setRotation {#setRotation-double-}
```
public void setRotation(double value)
```

Obtém ou define o ângulo de rotação em graus.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### setSubsequentLinesIndent {#setSubsequentLinesIndent-float-}
```
public void setSubsequentLinesIndent(float value)
```

Define o valor de recuo das linhas subsequentes.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor float |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Define o alinhamento vertical para o texto dentro do {@code Rectangle} do parágrafo. VerticalAlignment.None é equivalente a VerticalAlignment.Bottom.
