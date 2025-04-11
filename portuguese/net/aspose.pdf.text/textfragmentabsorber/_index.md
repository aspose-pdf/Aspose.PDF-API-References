---
title: Class TextFragmentAbsorber
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Text.TextFragmentAbsorber. Representa um objeto absorvedor de fragmentos de texto. Realiza busca de texto e fornece acesso aos resultados da busca através da coleção TextFragments
type: docs
weight: 10950
url: /pt/net/aspose.pdf.text/textfragmentabsorber/
---
## Classe TextFragmentAbsorber

Representa um objeto absorvedor de fragmentos de texto. Realiza busca de texto e fornece acesso aos resultados da busca através da coleção [`TextFragments`](./textfragments/).

```csharp
public sealed class TextFragmentAbsorber : TextAbsorber
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor)() | Inicializa uma nova instância do `TextFragmentAbsorber` que realiza a busca de todos os segmentos de texto do documento ou página. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_6)(Regex) | Inicializa uma nova instância da classe `TextFragmentAbsorber` para o objeto da classe System.Text.RegularExpressions.Regex especificado. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_2)(string) | Inicializa uma nova instância da classe `TextFragmentAbsorber` para a frase de texto especificada. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_1)(TextEditOptions) | Inicializa uma nova instância do `TextFragmentAbsorber` com opções de edição de texto, que realiza a busca de todos os segmentos de texto do documento ou página. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_7)(Regex, TextEditOptions) | Inicializa uma nova instância da classe `TextFragmentAbsorber` para a frase de texto especificada e opções de edição de texto. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_8)(Regex, TextSearchOptions) | Inicializa uma nova instância da classe `TextFragmentAbsorber` para a frase de texto especificada e opções de busca de texto. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_9)(Regex[], TextSearchOptions) | Inicializa uma nova instância da classe `TextFragmentAbsorber` para a frase de texto especificada e opções de busca de texto. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_3)(string, TextEditOptions) | Inicializa uma nova instância da classe `TextFragmentAbsorber` para a frase de texto especificada e opções de edição de texto. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_4)(string, TextSearchOptions) | Inicializa uma nova instância da classe `TextFragmentAbsorber` para a frase de texto especificada e opções de busca de texto. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_5)(string, TextSearchOptions, TextEditOptions) | Inicializa uma nova instância da classe `TextFragmentAbsorber` para a frase de texto especificada, opções de busca de texto e opções de edição de texto. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [Errors](../../aspose.pdf.text/textfragmentabsorber/errors/) { get; } | Lista de objetos [`TextExtractionError`](../textextractionerror/). Contém informações sobre erros encontrados durante a extração de texto. A busca por erros será realizada apenas se TextSearchOptions.LogTextExtractionErrors = true; e isso pode diminuir o desempenho. |
| override [ExtractionOptions](../../aspose.pdf.text/textfragmentabsorber/extractionoptions/) { get; set; } | Obtém ou define opções de extração de texto. |
| [HasErrors](../../aspose.pdf.text/textfragmentabsorber/haserrors/) { get; } | Valor que indica se erros foram encontrados durante a extração de texto. A busca por erros será realizada apenas se TextSearchOptions.LogTextExtractionErrors = true; e isso pode diminuir o desempenho. |
| [Phrase](../../aspose.pdf.text/textfragmentabsorber/phrase/) { get; set; } | Obtém ou define a frase que o `TextFragmentAbsorber` busca no documento ou página PDF. |
| [RegexResults](../../aspose.pdf.text/textfragmentabsorber/regexresults/) { get; } | Obtém um dicionário de ocorrências de busca que são apresentadas com a classe System.Text.RegularExpressions.Regex como chave e [`TextFragment`](../textfragment/) como valor. |
| override [Text](../../aspose.pdf.text/textfragmentabsorber/text/) { get; } | Obtém o texto extraído que o [`TextAbsorber`](../textabsorber/) extrai no documento ou página PDF. |
| [TextEditOptions](../../aspose.pdf.text/textfragmentabsorber/texteditoptions/) { get; set; } | Obtém ou define opções de edição de texto. As opções definem um comportamento especial quando o símbolo solicitado não pode ser escrito com a fonte. |
| [TextFragments](../../aspose.pdf.text/textfragmentabsorber/textfragments/) { get; set; } | Obtém a coleção de ocorrências de busca que são apresentadas com objetos [`TextFragment`](../textfragment/). |
| [TextReplaceOptions](../../aspose.pdf.text/textfragmentabsorber/textreplaceoptions/) { get; set; } | Obtém ou define opções de substituição de texto. As opções definem o comportamento quando o texto do fragmento é substituído por um texto mais curto/longo. |
| [TextSearchOptions](../../aspose.pdf.text/textfragmentabsorber/textsearchoptions/) { get; set; } | Obtém ou define opções de busca. As opções permitem a busca usando expressões regulares. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments/#applyforallfragments_2)(float) | Aplica o tamanho da fonte para todos os fragmentos de texto que foram absorvidos. Funciona mais rápido do que percorrer os fragmentos se todos os fragmentos nas páginas foram absorvidos. Caso contrário, funciona de forma semelhante ao looping. |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments/#applyforallfragments)(Font) | Aplica a fonte para todos os fragmentos de texto que foram absorvidos. Funciona mais rápido do que percorrer os fragmentos se todos os fragmentos nas páginas foram absorvidos. Caso contrário, funciona de forma semelhante ao looping. |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments/#applyforallfragments_1)(Font, float) | Aplica a fonte e o tamanho para todos os fragmentos de texto que foram absorvidos. Funciona mais rápido do que percorrer os fragmentos se todos os fragmentos nas páginas foram absorvidos. Caso contrário, funciona de forma semelhante ao looping. |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext/#removealltext)(Document) | Remove todo o texto do documento. |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext/#removealltext_1)(Page) | Remove todo o texto da página especificada. |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext/#removealltext_2)(Page, Rectangle) | Remove o texto dentro do retângulo especificado da página especificada. |
| [Reset](../../aspose.pdf.text/textfragmentabsorber/reset/)() | Limpa a coleção TextFragments deste objeto `TextFragmentAbsorber`. |
| override [Visit](../../aspose.pdf.text/textfragmentabsorber/visit/#visit)(Document) | Realiza a busca no documento especificado. |
| override [Visit](../../aspose.pdf.text/textfragmentabsorber/visit/#visit_1)(Page) | Realiza a busca na página especificada. |
| [Visit](../../aspose.pdf.text/textfragmentabsorber/visit/#visit_2)(XForm) | Realiza a busca no objeto de formulário especificado. |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/)(XForm) | Extrai texto no XForm especificado. |

## Observações

O objeto `TextFragmentAbsorber` é basicamente usado em cenários de busca de texto. Quando a busca é concluída, as ocorrências são representadas por objetos [`TextFragment`](../textfragment/) que a coleção [`TextFragments`](./textfragments/) contém. O objeto [`TextFragment`](../textfragment/) fornece acesso ao texto da ocorrência da busca, propriedades do texto e permite editar o texto e mudar o estado do texto (fonte, tamanho da fonte, cor etc).

## Exemplos

O exemplo demonstra como encontrar texto na primeira página do documento PDF e substituir o texto e sua fonte.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Find font that will be used to change document text font
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change text and font of the first text occurrence
absorber.TextFragments[1].Text = "hi world";
absorber.TextFragments[1].TextState.Font = font;

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### Veja Também

* classe [TextAbsorber](../textabsorber/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)