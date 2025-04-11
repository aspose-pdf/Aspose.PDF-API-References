---
title: Class TextSegment
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Text.TextSegment. Representa segmento de texto Pdf
type: docs
weight: 11050
url: /pt/net/aspose.pdf.text/textsegment/
---
## Classe TextSegment

Representa segmento de texto Pdf.

```csharp
public sealed class TextSegment
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [TextSegment](textsegment/#constructor)() | Cria objeto TextSegment. |
| [TextSegment](textsegment/#constructor_1)(string) | Cria objeto TextSegment. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textsegment/baselineposition/) { get; set; } | Obtém a posição do texto para o texto, representado com o objeto `TextSegment`. O YIndent da estrutura Position representa a coordenada da linha de base do segmento de texto. |
| [Characters](../../aspose.pdf.text/textsegment/characters/) { get; } | Obtém a coleção de objetos CharInfo que representam informações sobre os caracteres no segmento de texto. |
| [EndCharIndex](../../aspose.pdf.text/textsegment/endcharindex/) { get; } | Obtém o índice do caractere final do segmento atual no operador de texto exibido (Tj, TJ). |
| [Hyperlink](../../aspose.pdf.text/textsegment/hyperlink/) { get; set; } | Obtém ou define o hyperlink do segmento (para gerador de pdf). |
| [Position](../../aspose.pdf.text/textsegment/position/) { get; set; } | Obtém a posição do texto para o texto, representado com o objeto `TextSegment`. |
| [Rectangle](../../aspose.pdf.text/textsegment/rectangle/) { get; } | Obtém o retângulo do TextSegment |
| [StartCharIndex](../../aspose.pdf.text/textsegment/startcharindex/) { get; } | Obtém o índice do caractere inicial do segmento atual no operador de texto exibido (Tj, TJ). |
| [Text](../../aspose.pdf.text/textsegment/text/) { get; set; } | Obtém ou define o objeto de texto String que o objeto `TextSegment` representa. |
| [TextEditOptions](../../aspose.pdf.text/textsegment/texteditoptions/) { get; set; } | Obtém ou define opções de edição de texto. As opções definem um comportamento especial quando o símbolo solicitado não pode ser escrito com a fonte. |
| [TextState](../../aspose.pdf.text/textsegment/textstate/) { get; set; } | Obtém ou define o estado do texto para o texto que o objeto `TextSegment` representa. |

## Métodos

| Nome | Descrição |
| --- | --- |
| static [MyHtmlEncode](../../aspose.pdf.text/textsegment/myhtmlencode/)(string) | Codifica a string como html. |

## Observações

Em poucas palavras, os objetos `TextSegment` são filhos do objeto [`TextFragment`](../textfragment/). Em detalhes: O texto do documento pdf em Pdf é representado por dois objetos básicos: [`TextFragment`](../textfragment/) e `TextSegment`. As diferenças entre eles são principalmente dependentes do contexto. Vamos considerar o seguinte cenário. O usuário busca o texto "hello world" para operar com ele, alterar suas propriedades, visualizar etc.

```csharp
Document doc = new Document(docFile);
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
doc.Pages[1].Accept(absorber);
```

A representação física do texto pdf é muito complexa. O texto "hello world" pode consistir em vários segmentos de texto fisicamente independentes. O modelo de texto Aspose.Pdf basicamente estabelece que o objeto [`TextFragment`](../textfragment/) fornece um conjunto de operações lógicas sobre o conjunto de objetos `TextSegment` físicos que representam a consulta do usuário. No cenário de busca de texto, o [`TextFragment`](../textfragment/) é a representação lógica do texto "hello world", e a coleção de objetos `TextSegment` representa todos os segmentos físicos que constroem o objeto de texto "hello world". Portanto, o [`TextFragment`](../textfragment/) está próximo da representação lógica do texto. E o `TextSegment` está próximo da representação física do texto. Obviamente, cada objeto `TextSegment` pode ter sua própria fonte, coloração, propriedades de posicionamento. O [`TextFragment`](../textfragment/) fornece uma maneira simples de alterar o texto com suas propriedades: definir fonte, definir tamanho da fonte, definir cor da fonte etc. Enquanto isso, os objetos `TextSegment` são acessíveis e os usuários podem operar com os objetos `TextSegment` de forma independente.

## Exemplos

O exemplo demonstra como alterar a cor do texto e o tamanho da fonte do texto com o objeto [`TextState`](./textstate/) do objeto `TextSegment`.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change foreground color of the first text segment of the first text occurrence
absorber.TextFragments[1].Segments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);
// Change font size of the first text segment of the first text occurrence
absorber.TextFragments[1].Segments[1].TextState.FontSize = 15;

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### Veja Também

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)