---
title: "TextFragment"
linktitle: "TextFragment"
second_title: "Referência da API Aspose.PDF para Java"
description: "<p> Representa um fragmento de texto PDF. </p> <hr> <pre> O exemplo demonstra como encontrar texto na primeira página do documento PDF e substituir o texto e sua fonte. // Open document."
type: docs
weight: 5110
url: /pt/java/com.aspose.pdf/textfragment/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.TextFragment, com.aspose.pdf.BaseParagraph, com.aspose.pdf.TextFragment

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public class TextFragment extends BaseParagraph
```

<p> Representa fragmento de texto PDF. </p> <hr> <pre> O exemplo demonstra como encontrar texto na primeira página do documento PDF e substituir o texto e sua fonte. // Abrir documento Document doc = new Document(\"input.pdf\"); // Encontrar a fonte que será usada para alterar a fonte do texto do documento Font font = FontRepository.findFont(\"Arial\"); // Criar o objeto TextFragmentAbsorber para encontrar todas as ocorrências do texto \"hello world\" TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Aceitar o absorvedor na primeira página doc.getPages().get(1).accept(absorber); // Alterar o texto e a fonte da primeira ocorrência de texto absorber.getTextFragments().get_Item(1).setText ( \"hi world\"); absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Salvar o documento doc.save(\"output.pdf\"); </pre> <hr> <pre> Em poucas palavras, o objeto {@code TextFragment} contém uma lista de objetos {@code TextSegment}. Em detalhes: O texto do documento pdf em {@code com.aspose.pdf} é representado por dois objetos básicos: {@code TextFragment} e {@code TextSegment} As diferenças entre eles são principalmente dependentes do contexto. Vamos considerar o seguinte cenário. O usuário procura o texto \"hello world\" para operar com ele, alterar suas propriedades, visualizar etc. Document doc = new Document(docFile); TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); doc.getPages().get(1).accept(absorber); </pre> A representação física do texto PDF é muito complexa. O texto \"hello world\" pode consistir em vários segmentos de texto fisicamente independentes. O modelo de texto Aspose.Pdf basicamente estabelece que o objeto {@code TextFragment} fornece um conjunto único de operações lógicas sobre o conjunto de objetos {@code TextSegment} físicos que representam a consulta do usuário. No cenário de busca de texto, {@code TextFragment} é a representação lógica do texto \"hello world\", e a coleção de objetos {@code TextSegment} representa todos os segmentos físicos que constroem o objeto de texto \"hello world\". Portanto, {@code TextFragment} está próximo da representação lógica do texto. E {@code TextSegment} está próximo da representação física do texto. Obviamente, cada objeto {@code TextSegment} pode ter sua própria fonte, cor e propriedades de posicionamento. {@code TextFragment} fornece uma maneira simples de alterar o texto com suas propriedades: definir fonte, definir tamanho da fonte, definir cor da fonte etc. Enquanto isso, os objetos {@code TextSegment} são acessíveis e os usuários podem operar com os objetos {@code TextSegment} de forma independente. <p> Observe que alterar as propriedades do TextFragment pode mudar a coleção interna {@code Segments}, pois o TextFragment é um objeto agregado e pode reorganizar os segmentos internos ou mesclá-los em um único segmento. Se sua necessidade for deixar a coleção {@code Segments} inalterada, por favor altere os segmentos internos individualmente. </p>

## Construtores

| Construtor | Descrição |
| --- | --- |
| [TextFragment](#TextFragment--) | Inicializa uma nova instância do objeto {@code TextFragment}. |
| [TextFragment](#TextFragment-java.lang.String-) | Inicializa uma nova instância do objeto {@code TextFragment}. |
| [TextFragment](#TextFragment-java.lang.String-com.aspose.pdf.TabStops-) | Inicializa uma nova instância do objeto {@code TextFragment}. |
| [TextFragment](#TextFragment-com.aspose.pdf.TabStops-) | Inicializa uma nova instância do objeto {@code TextFragment}. |

## Métodos

| Método | Descrição |
| --- | --- |
| [cloneWithSegments](#cloneWithSegments--) | Clona o fragmento com todos os segmentos. |
| [deepClone](#deepClone--) | Clona o fragmento. |
| [getBaselinePosition](#getBaselinePosition--) | Obtém a posição do texto, representada com o objeto {@code TextFragment}. O YIndent da estrutura Position representa a coordenada da linha de base do fragmento de texto. |
| [getEndNote](#getEndNote--) | Obtém a nota de fim de parágrafo.(para geração de PDF somente) |
| [getFootNote](#getFootNote--) | Obtém a nota de rodapé do parágrafo.(para geração de PDF somente) |
| [getForm](#getForm--) | Obtém o objeto de formulário que contém o TextFragment. O valor pode ser nulo caso o objeto TextFragment não pertença a um formulário. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | Obtém o alinhamento horizontal do fragmento de texto. |
| [getPage](#getPage--) | Obtém a página que contém o TextFragment. O valor pode ser nulo caso o objeto TextFragment não pertença a nenhuma página. |
| [getPosition](#getPosition--) | <p> Obtém a posição do texto, representada com o objeto {@code TextFragment}. </p> |
| [getRectangle](#getRectangle--) | Obtém o retângulo do TextFragment |
| [getReplaceOptions](#getReplaceOptions--) | Obtém as opções de substituição de texto. As opções definem o comportamento quando o texto do fragmento é substituído por um texto mais curto ou mais longo. |
| [getSegments](#getSegments--) | <p> Obtém os segmentos de texto para o {@code TextFragment} atual. </p> |
| [getText](#getText--) | <p> Obtém o objeto de texto {@code string} que o objeto {@code TextFragment} representa. </p> |
| [getTextEditOptions](#getTextEditOptions--) | Obtém ou define as opções de edição de texto. As opções definem um comportamento especial quando o símbolo solicitado não pode ser escrito com a fonte. |
| [getTextState](#getTextState--) | <p> Obtém ou define o estado do texto para o texto que o objeto {@code TextFragment} representa. </p> |
| [getVerticalAlignment](#getVerticalAlignment--) | Obtém o alinhamento vertical do fragmento de texto. |
| [getWrapLinesCount](#getWrapLinesCount--) | Obtém a contagem de linhas de quebra para este parágrafo (para geração de PDF somente) |
| [isolateTextSegments](#isolateTextSegments-int-int-) | Obtém {@code TextSegment}(s) que representam a parte especificada do texto {@code TextFragment}. |
| [setBaselinePosition](#setBaselinePosition-com.aspose.pdf.Position-) | Define a posição do texto, representada com o objeto {@code TextFragment}. O YIndent da estrutura Position representa a coordenada da linha de base do fragmento de texto. |
| [setEndNote](#setEndNote-com.aspose.pdf.Note-) | Define a nota de fim de parágrafo.(para geração de PDF somente) |
| [setFootNote](#setFootNote-com.aspose.pdf.Note-) | Define a nota de rodapé do parágrafo.(para geração de PDF somente) |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | Define um alinhamento horizontal do fragmento de texto. |
| [setHyperlink](#setHyperlink-com.aspose.pdf.Hyperlink-) | Define o hyperlink do fragmento |
| [setMarkedContentProperties](#setMarkedContentProperties-java.lang.String-int-) |  |
| [setPosition](#setPosition-com.aspose.pdf.Position-) | <p> Define a posição do texto, representada com o objeto {@code TextFragment}. </p> |
| [setRectangle](#setRectangle-com.aspose.pdf.Rectangle-) | Obtém o retângulo do TextFragment |
| [setSegments](#setSegments-com.aspose.pdf.TextSegmentCollection-) | Representa o método setSegments |
| [setText](#setText-java.lang.String-) | <p> Define o objeto de texto {@code string} que o objeto {@code TextFragment} representa. </p> |
| [setTextEditOptions](#setTextEditOptions-com.aspose.pdf.TextEditOptions-) | Obtém ou define as opções de edição de texto. As opções definem um comportamento especial quando o símbolo solicitado não pode ser escrito com a fonte. |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Define um alinhamento vertical do fragmento de texto. |
| [setWrapLinesCount](#setWrapLinesCount-int-) | Define a contagem de linhas de quebra para este parágrafo (apenas para geração de PDF) |

### TextFragment {#TextFragment--}
```
public TextFragment()
```

Inicializa uma nova instância do objeto {@code TextFragment}.

### TextFragment {#TextFragment-java.lang.String-}
Inicializa uma nova instância do objeto {@code TextFragment}.

### TextFragment {#TextFragment-java.lang.String-com.aspose.pdf.TabStops-}
Inicializa uma nova instância do objeto {@code TextFragment}.

### TextFragment {#TextFragment-com.aspose.pdf.TabStops-}
Inicializa uma nova instância do objeto {@code TextFragment}.

### cloneWithSegments {#cloneWithSegments--}
```
public Object cloneWithSegments()
```

Clona o fragmento com todos os segmentos.

**Returns:**
O objeto clonado

### deepClone {#deepClone--}
```
public Object deepClone()
```

Clona o fragmento.

**Returns:**
O objeto clonado

### getBaselinePosition {#getBaselinePosition--}
```
public Position getBaselinePosition()
```

Obtém a posição do texto, representada com o objeto {@code TextFragment}. O YIndent da estrutura Position representa a coordenada da linha de base do fragmento de texto.

**Returns:**
Valor da posição

### getEndNote {#getEndNote--}
```
public Note getEndNote()
```

Obtém a nota de fim de parágrafo.(para geração de PDF somente)

**Returns:**
Valor da nota

### getFootNote {#getFootNote--}
```
public Note getFootNote()
```

Obtém a nota de rodapé do parágrafo.(para geração de PDF somente)

**Returns:**
Valor da nota

### getForm {#getForm--}
```
public XForm getForm()
```

Obtém o objeto de formulário que contém o TextFragment. O valor pode ser nulo caso o objeto TextFragment não pertença a um formulário.

**Returns:**
Valor XForm

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

Obtém o alinhamento horizontal do fragmento de texto.

**Returns:**
Valor HorizontalAlignment @see HorizontalAlignment

### getPage {#getPage--}
```
public Page getPage()
```

Obtém a página que contém o TextFragment. O valor pode ser nulo caso o objeto TextFragment não pertença a nenhuma página.

**Returns:**
objeto Page

### getPosition {#getPosition--}
```
public Position getPosition()
```

<p> Obtém a posição do texto, representada com o objeto {@code TextFragment}. </p>

**Returns:**
Valor da posição <hr> <pre> The example demonstrates how to view placement of a text, represented by {@code TextFragment} object. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // View text and placement info of first text occurrence TextFragment firstOccurrence = absorber.getTextFragments().get_Item(1); System.out.println("fragment text: " + firstOccurrence.getText())); System.out.println("fragment X indent: "+ firstOccurrence.getPosition().getXIndent())); System.out.println("fragment Y indent: "+ firstOccurrence.getPosition().getYIndent())); </pre> @see TextFragmentAbsorber @see IDocument @see TextSegment

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Obtém o retângulo do TextFragment

**Returns:**
objeto Rectangle

### getReplaceOptions {#getReplaceOptions--}
```
public final TextReplaceOptions getReplaceOptions()
```

Obtém as opções de substituição de texto. As opções definem o comportamento quando o texto do fragmento é substituído por um texto mais curto ou mais longo.

**Returns:**
Instância de TextReplaceOptions

### getSegments {#getSegments--}
```
public TextSegmentCollection getSegments()
```

<p> Obtém os segmentos de texto para o {@code TextFragment} atual. </p>

**Returns:**
Valor da coleção TextSegmentCollection <hr> <pre> The example demonstrates how to navigate all {@code TextSegment} objects inside {@code TextFragment}. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Navigate all text segments and out their text and placement info for (TextSegment segment : ({@code Iterable<TextSegment>})absorber.getTextFragments().get_Item(1).getSegments()) { System.out.println("segment text: "+ segment.getText())); System.out.println("segment X indent: "+ segment.getPosition().getXIndent())); System.out.println("segment Y indent: "+ segment.getPosition().getYIndent())); } </pre> <hr> <p> In a few words, {@code TextSegment} objects are children of {@code TextFragment} object. Advanced users may access segments directly to perform more complex text edit scenarios. For details, please look at {@code TextFragment} object description. </p> @see TextFragmentAbsorber @see IDocument @see TextSegment

### getText {#getText--}
```
public String getText()
```

<p> Obtém o objeto de texto {@code string} que o objeto {@code TextFragment} representa. </p>

**Returns:**
Valor da string <hr> <pre> The example demonstrates how to search a text and replace first occurrence represented with {@code TextFragment} object . // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> @see TextFragmentAbsorber @see IDocument

### getTextEditOptions {#getTextEditOptions--}
```
public final TextEditOptions getTextEditOptions()
```

Obtém ou define as opções de edição de texto. As opções definem um comportamento especial quando o símbolo solicitado não pode ser escrito com a fonte.

**Returns:**
Instância de TextEditOptions

### getTextState {#getTextState--}
```
public TextFragmentState getTextState()
```

<p> Obtém ou define o estado do texto para o texto que o objeto {@code TextFragment} representa. </p>

**Returns:**
Objeto TextFragmentState <hr> <pre> The example demonstrates how to change text color and font size of the text with {@code TextState} object. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change foreground color of the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setForegroundColor(Color.RED); // Change font size of the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFontSize ( 15); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Provides a way to change following properties of the text: Font FontSize FontStyle ForegroundColor BackgroundColor </p> @see TextFragmentAbsorber @see IDocument

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

Obtém o alinhamento vertical do fragmento de texto.

**Returns:**
valor int @see VerticalAlignment

### getWrapLinesCount {#getWrapLinesCount--}
```
public int getWrapLinesCount()
```

Obtém a contagem de linhas de quebra para este parágrafo (para geração de PDF somente)

**Returns:**
valor int

### isolateTextSegments {#isolateTextSegments-int-int-}
```
public TextSegmentCollection isolateTextSegments(int startIndex, int length)
```

Obtém {@code TextSegment}(s) que representam a parte especificada do texto {@code TextFragment}.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| startIndex |  | Posição no texto a partir da qual novos {@code TextSegment}(s) começarão. |
| comprimento |  | Comprimento do texto que será isolado em {@code TextSegment}(s). |

**Returns:**
{@code TextSegmentCollection} contendo segmentos de texto que representam a substring de texto iniciando em uma posição especificada e com um comprimento especificado.

### setBaselinePosition {#setBaselinePosition-com.aspose.pdf.Position-}
Define a posição do texto, representada com o objeto {@code TextFragment}. O YIndent da estrutura Position representa a coordenada da linha de base do fragmento de texto.

### setEndNote {#setEndNote-com.aspose.pdf.Note-}
Define a nota de fim de parágrafo.(para geração de PDF somente)

### setFootNote {#setFootNote-com.aspose.pdf.Note-}
Define a nota de rodapé do parágrafo.(para geração de PDF somente)

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
Define um alinhamento horizontal do fragmento de texto.

### setHyperlink {#setHyperlink-com.aspose.pdf.Hyperlink-}
Define o hyperlink do fragmento

### setMarkedContentProperties {#setMarkedContentProperties-java.lang.String-int-}


### setPosition {#setPosition-com.aspose.pdf.Position-}
<p> Define a posição do texto, representada com o objeto {@code TextFragment}. </p>

### setRectangle {#setRectangle-com.aspose.pdf.Rectangle-}
Obtém o retângulo do TextFragment

### setSegments {#setSegments-com.aspose.pdf.TextSegmentCollection-}
Representa o método setSegments

### setText {#setText-java.lang.String-}
<p> Define o objeto de texto {@code string} que o objeto {@code TextFragment} representa. </p>

### setTextEditOptions {#setTextEditOptions-com.aspose.pdf.TextEditOptions-}
Obtém ou define as opções de edição de texto. As opções definem um comportamento especial quando o símbolo solicitado não pode ser escrito com a fonte.

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Define um alinhamento vertical do fragmento de texto.

### setWrapLinesCount {#setWrapLinesCount-int-}
```
public void setWrapLinesCount(int value)
```

Define a contagem de linhas de quebra para este parágrafo (apenas para geração de PDF)

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |
