---
title: "TextSegment"
linktitle: "TextSegment"
second_title: "Referência da API Aspose.PDF para Java"
description: "<p> Representa um segmento de texto PDF. </p> <hr> <pre> O exemplo demonstra como alterar a cor do texto e o tamanho da fonte do texto com o objeto {@code TextState} de {@code."
type: docs
weight: 5300
url: /pt/java/com.aspose.pdf/textsegment/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextSegment

```
public final class TextSegment extends Object
```

<p> Representa um segmento de texto PDF. </p> <hr> <pre> O exemplo demonstra como alterar a cor do texto e o tamanho da fonte do texto com o objeto {@code TextState} do objeto {@code TextSegment}. // Abrir documento Document doc = new Document("D:\\Tests\\input.pdf"); // Criar objeto TextFragmentAbsorber para encontrar todas as ocorrências de texto "hello world" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Aceitar o absorvedor na primeira página doc.getPages().get(1).accept(absorber); // Alterar a cor de primeiro plano do primeiro segmento de texto da primeira ocorrência de texto absorber.getTextFragments().get(1).getSegments().get(1).getTextState().setForegroundColor ( java.awt.Color.RED); // Alterar o tamanho da fonte do primeiro segmento de texto da primeira ocorrência de texto absorber.getTextFragments().get(1).getSegments().get_Item(1).getTextState().setFontSize ( 15); // Salvar documento doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <pre> Em poucas palavras, objetos {@code TextSegment} são filhos do objeto {@code TextFragment}. Em detalhes: O texto de um documento PDF em {@code Aspose.Pdf} é representado por dois objetos básicos: {@code TextFragment} e {@code TextSegment} As diferenças entre eles dependem principalmente do contexto. Vamos considerar o seguinte cenário. O usuário procura o texto "hello world" para operar com ele, alterar suas propriedades, aparência etc. Document doc = new Document(docFile); TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); doc.getPages().get(1).accept(absorber); </pre> <p> A representação física do texto PDF é muito complexa. O texto "hello world" pode consistir em vários segmentos de texto fisicamente independentes. O modelo de texto Aspose.PDF basicamente estabelece que o objeto {@code TextFragment} fornece um conjunto único de operações lógicas sobre o conjunto de objetos {@code TextSegment} físicos que representam a consulta do usuário. No cenário de busca de texto, {@code TextFragment} é a representação lógica do texto "hello world", e a coleção de objetos {@code TextSegment} representa todos os segmentos físicos que constroem o objeto de texto "hello world". Portanto, {@code TextFragment} está próximo da representação lógica do texto. E {@code TextSegment} está próximo da representação física do texto. Obviamente, cada objeto {@code TextSegment} pode ter sua própria fonte, coloração e propriedades de posicionamento. {@code TextFragment} fornece uma maneira simples de alterar o texto com suas propriedades: definir fonte, definir tamanho da fonte, definir cor da fonte etc. Enquanto isso, objetos {@code TextSegment} são acessíveis e os usuários podem operar com objetos {@code TextSegment} de forma independente. </p>

## Construtores

| Construtor | Descrição |
| --- | --- |
| [TextSegment](#TextSegment--) | <p> Cria objeto TextSegment. </p> <hr> <pre> O exemplo demonstra como criar um objeto fragmento de texto, adicionar um segmento de texto à coleção de fragmentos de texto e anexá‑lo à página Pdf. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // create text fragment TextFragment tf = new TextFragment(\"main text\"); tf.setPosition ( new Position(100, 600)); // set it's text properties tf.getTextState().setFontSize ( 5); tf.getTextState().setFont ( FontRepository.FindFont(\"TimesNewRoman\")); tf.getTextState().setBackgroundColor ( Color.GRAY); tf.getTextState().setForegroundColor ( Color.RED); // add one more segment to text fragment's Segments collection TextSegment segment2 = new TextSegment(); segment2.setText ( \"another segment\"); tf.getSegments().add(segment2); // create TextBuilder object TextBuilder builder = new TextBuilder(page); // append the text fragment to the Pdf page builder.appendText(tf); //save document doc.save(outFile); </pre> |
| [TextSegment](#TextSegment-java.lang.String-) | <p> Cria objeto TextSegment. </p> <hr> <pre> O exemplo demonstra como criar um objeto fragmento de texto, adicionar um segmento de texto à coleção de fragmentos de texto e anexá‑lo à página Pdf. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // create text fragment TextFragment tf = new TextFragment(\"main text\"); tf.setPosition ( new Position(100, 600)); // set it's text properties tf.getTextState().setFontSize ( 5); tf.getTextState().setFont ( FontRepository.FindFont(\"TimesNewRoman\")); tf.getTextState().setBackgroundColor ( Color.GRAY); tf.getTextState().setForegroundColor ( Color.RED); // add one more segment to text fragment's Segments collection TextSegment segment2 = new TextSegment(); segment2.setText ( \"another segment\"); tf.getSegments().add(segment2); // create TextBuilder object TextBuilder builder = new TextBuilder(page); // append the text fragment to the Pdf page builder.appendText(tf); //save document doc.save(outFile); </pre> |

## Métodos

| Método | Descrição |
| --- | --- |
| [getBaselinePosition](#getBaselinePosition--) | Obtém a posição do texto, representada com o objeto {@code TextSegment}. O YIndent da estrutura Position representa a coordenada da linha de base do segmento de texto. |
| [getCharacters](#getCharacters--) | Obtém a coleção de objetos CharInfo que representam informações sobre os caracteres no segmento de texto. |
| [getEndCharIndex](#getEndCharIndex--) | Obtém o índice do caractere final do segmento atual no operador de exibição de texto (Tj, TJ). |
| [getHyperlink](#getHyperlink--) | Obtém ou define o hyperlink do segmento (para gerador de pdf). |
| [getPosition](#getPosition--) | Obtém a posição do texto, representada com o objeto {@code TextSegment}. |
| [getRectangle](#getRectangle--) | Obtém o retângulo do TextSegment |
| [getStartCharIndex](#getStartCharIndex--) | Obtém o índice do caractere inicial do segmento atual no operador de exibição de texto (Tj, TJ). |
| [getText](#getText--) | Obtém o objeto de texto {@code string} que o objeto {@code TextSegment} representa. |
| [getTextEditOptions](#getTextEditOptions--) | Obtém opções de edição de texto. As opções definem comportamento especial quando o símbolo solicitado não pode ser escrito com a fonte. |
| [getTextState](#getTextState--) | <p> Obtém ou define o estado do texto para o texto que o objeto {@code TextSegment} representa. </p> <hr> <p> Fornece uma maneira de alterar as seguintes propriedades do texto: Font FontSize FontStyle ForegroundColor BackgroundColor </p> |
| [setBaselinePosition](#setBaselinePosition-com.aspose.pdf.Position-) | Define a posição do texto, representada com o objeto {@code TextSegment}. O YIndent da estrutura Position representa a coordenada da linha de base do segmento de texto. |
| [setHyperlink](#setHyperlink-com.aspose.pdf.Hyperlink-) | Obtém ou define o hyperlink do segmento (para gerador de pdf). |
| [setPosition](#setPosition-com.aspose.pdf.Position-) | Define a posição do texto, representada com o objeto {@code TextSegment}. |
| [setText](#setText-java.lang.String-) | Define o objeto de texto {@code string} que o objeto {@code TextSegment} representa. |
| [setTextEditOptions](#setTextEditOptions-com.aspose.pdf.TextEditOptions-) | Define opções de edição de texto. As opções definem comportamento especial quando o símbolo solicitado não pode ser escrito com a fonte. |
| [setTextState](#setTextState-com.aspose.pdf.TextState-) | <p> Define o estado do texto para o texto que o objeto {@code TextSegment} representa. </p> <hr> <p> Fornece uma maneira de alterar as seguintes propriedades do texto: Font FontSize FontStyle ForegroundColor BackgroundColor </p> |
| [setTextSuppressedUpdate](#setTextSuppressedUpdate-java.lang.String-) | Define o objeto de texto {@code string} que o objeto {@code TextSegment} representa com atualização suprimida. |

### TextSegment {#TextSegment--}
```
public TextSegment()
```

<p> Cria objeto TextSegment. </p> <hr> <pre> O exemplo demonstra como criar um objeto fragmento de texto, adicionar um segmento de texto à coleção de fragmentos de texto e anexá‑lo à página Pdf. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // create text fragment TextFragment tf = new TextFragment(\"main text\"); tf.setPosition ( new Position(100, 600)); // set it's text properties tf.getTextState().setFontSize ( 5); tf.getTextState().setFont ( FontRepository.FindFont(\"TimesNewRoman\")); tf.getTextState().setBackgroundColor ( Color.GRAY); tf.getTextState().setForegroundColor ( Color.RED); // add one more segment to text fragment's Segments collection TextSegment segment2 = new TextSegment(); segment2.setText ( \"another segment\"); tf.getSegments().add(segment2); // create TextBuilder object TextBuilder builder = new TextBuilder(page); // append the text fragment to the Pdf page builder.appendText(tf); //save document doc.save(outFile); </pre>

### TextSegment {#TextSegment-java.lang.String-}
<p> Cria objeto TextSegment. </p> <hr> <pre> O exemplo demonstra como criar um objeto fragmento de texto, adicionar um segmento de texto à coleção de fragmentos de texto e anexá‑lo à página Pdf. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // create text fragment TextFragment tf = new TextFragment(\"main text\"); tf.setPosition ( new Position(100, 600)); // set it's text properties tf.getTextState().setFontSize ( 5); tf.getTextState().setFont ( FontRepository.FindFont(\"TimesNewRoman\")); tf.getTextState().setBackgroundColor ( Color.GRAY); tf.getTextState().setForegroundColor ( Color.RED); // add one more segment to text fragment's Segments collection TextSegment segment2 = new TextSegment(); segment2.setText ( \"another segment\"); tf.getSegments().add(segment2); // create TextBuilder object TextBuilder builder = new TextBuilder(page); // append the text fragment to the Pdf page builder.appendText(tf); //save document doc.save(outFile); </pre>

### getBaselinePosition {#getBaselinePosition--}
```
public Position getBaselinePosition()
```

Obtém a posição do texto, representada com o objeto {@code TextSegment}. O YIndent da estrutura Position representa a coordenada da linha de base do segmento de texto.

**Returns:**
Valor da posição

### getCharacters {#getCharacters--}
```
public CharInfoCollection getCharacters()
```

Obtém a coleção de objetos CharInfo que representam informações sobre os caracteres no segmento de texto.

**Returns:**
Objeto CharInfoCollection

### getEndCharIndex {#getEndCharIndex--}
```
public int getEndCharIndex()
```

Obtém o índice do caractere final do segmento atual no operador de exibição de texto (Tj, TJ).

**Returns:**
valor int

### getHyperlink {#getHyperlink--}
```
public Hyperlink getHyperlink()
```

Obtém ou define o hyperlink do segmento (para gerador de pdf).

**Returns:**
Objeto Hyperlink

### getPosition {#getPosition--}
```
public Position getPosition()
```

Obtém a posição do texto, representada com o objeto {@code TextSegment}.

**Returns:**
Valor da posição

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Obtém o retângulo do TextSegment

**Returns:**
objeto Rectangle

### getStartCharIndex {#getStartCharIndex--}
```
public int getStartCharIndex()
```

Obtém o índice do caractere inicial do segmento atual no operador de exibição de texto (Tj, TJ).

**Returns:**
valor int

### getText {#getText--}
```
public String getText()
```

Obtém o objeto de texto {@code string} que o objeto {@code TextSegment} representa.

**Returns:**
valor String

### getTextEditOptions {#getTextEditOptions--}
```
public TextEditOptions getTextEditOptions()
```

Obtém opções de edição de texto. As opções definem comportamento especial quando o símbolo solicitado não pode ser escrito com a fonte.

**Returns:**
Valor TextEditOptions

### getTextState {#getTextState--}
```
public TextState getTextState()
```

<p> Obtém ou define o estado do texto para o texto que o objeto {@code TextSegment} representa. </p> <hr> <p> Fornece uma maneira de alterar as seguintes propriedades do texto: Font FontSize FontStyle ForegroundColor BackgroundColor </p>

**Returns:**
Valor TextState

### setBaselinePosition {#setBaselinePosition-com.aspose.pdf.Position-}
Define a posição do texto, representada com o objeto {@code TextSegment}. O YIndent da estrutura Position representa a coordenada da linha de base do segmento de texto.

### setHyperlink {#setHyperlink-com.aspose.pdf.Hyperlink-}
Obtém ou define o hyperlink do segmento (para gerador de pdf).

### setPosition {#setPosition-com.aspose.pdf.Position-}
Define a posição do texto, representada com o objeto {@code TextSegment}.

### setText {#setText-java.lang.String-}
Define o objeto de texto {@code string} que o objeto {@code TextSegment} representa.

### setTextEditOptions {#setTextEditOptions-com.aspose.pdf.TextEditOptions-}
Define opções de edição de texto. As opções definem comportamento especial quando o símbolo solicitado não pode ser escrito com a fonte.

### setTextState {#setTextState-com.aspose.pdf.TextState-}
<p> Define o estado do texto para o texto que o objeto {@code TextSegment} representa. </p> <hr> <p> Fornece uma maneira de alterar as seguintes propriedades do texto: Font FontSize FontStyle ForegroundColor BackgroundColor </p>

### setTextSuppressedUpdate {#setTextSuppressedUpdate-java.lang.String-}
Define o objeto de texto {@code string} que o objeto {@code TextSegment} representa com atualização suprimida.
