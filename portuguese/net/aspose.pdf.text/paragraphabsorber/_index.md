---
title: Class ParagraphAbsorber
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Text.ParagraphAbsorber. Representa um objeto absorvedor de objetos de estrutura de página, como seções e parágrafos. Realiza a busca por seções e parágrafos de texto e fornece acesso a retângulos e poliedros que os descrevem no espaço de coordenadas de texto. Também realiza a busca por segmentos de texto e fornece acesso aos resultados da busca através de coleções de TextFragments agrupadas por elementos de estrutura.
type: docs
weight: 10670
url: /pt/net/aspose.pdf.text/paragraphabsorber/
---
## Classe ParagraphAbsorber

Representa um objeto absorvedor de objetos de estrutura de página, como seções e parágrafos. Realiza a busca por seções e parágrafos de texto e fornece acesso a retângulos e poliedros que os descrevem no espaço de coordenadas de texto. Também realiza a busca por segmentos de texto e fornece acesso aos resultados da busca através de coleções de !:TextFragments agrupadas por elementos de estrutura.

```csharp
public class ParagraphAbsorber
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [ParagraphAbsorber](paragraphabsorber/#constructor)() | Inicializa uma nova instância do `ParagraphAbsorber` que realiza a busca por seções/parágrafos do documento ou página. |
| [ParagraphAbsorber](paragraphabsorber/#constructor_2)(int) | Inicializa uma nova instância do `ParagraphAbsorber` que realiza a busca por seções/parágrafos do documento ou página. |
| [ParagraphAbsorber](paragraphabsorber/#constructor_1)(ParagraphAbsorberOptions) | Inicializa uma nova instância do `ParagraphAbsorber` que realiza a busca por seções/parágrafos do documento ou página com os parâmetros especificados. |
| [ParagraphAbsorber](paragraphabsorber/#constructor_3)(int, ParagraphAbsorberOptions) | Inicializa uma nova instância do `ParagraphAbsorber` que realiza a busca por seções/parágrafos do documento ou página com os parâmetros especificados. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [IsMulticolumnParagraphsAllowed](../../aspose.pdf.text/paragraphabsorber/ismulticolumnparagraphsallowed/) { get; set; } | Obtém ou define o valor que indica se as linhas de texto iniciais de uma próxima seção podem ser tratadas como continuação do último parágrafo de uma seção anterior. |
| [PageMarkups](../../aspose.pdf.text/paragraphabsorber/pagemarkups/) { get; } | Obtém a coleção de [`PageMarkup`](../pagemarkup/) que foram absorvidos. |
| [ParagraphAbsorberOptions](../../aspose.pdf.text/paragraphabsorber/paragraphabsorberoptions/) { get; set; } | Obtém ou define as opções do ParagraphAbsorber. |
| [SectionsSearchDepth](../../aspose.pdf.text/paragraphabsorber/sectionssearchdepth/) { get; set; } | Obtém ou define o valor que instrui quantas vezes buscas sequenciais por elementos mais finos da estrutura serão realizadas. A profundidade de busca padrão é 3. Isso significa três buscas por seções divididas horizontalmente (cabeçalhos, parágrafos etc) e três buscas por seções divididas verticalmente (colunas). |
| [TextReplaceOptions](../../aspose.pdf.text/paragraphabsorber/textreplaceoptions/) { get; set; } | Obtém ou define as opções de substituição de texto. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [Visit](../../aspose.pdf.text/paragraphabsorber/visit/#visit)(Document) | Realiza a busca por seções e parágrafos no [`Document`](../../aspose.pdf/document/) especificado. |
| [Visit](../../aspose.pdf.text/paragraphabsorber/visit/#visit_1)(Page) | Realiza a busca na [`Page`](../../aspose.pdf/page/) especificada. |

## Observações

Quando a busca é concluída, a coleção [`PageMarkups`](./pagemarkups/) conterá objetos [`PageMarkup`](../pagemarkup/) que representam a estrutura da página por coleções de [`MarkupSection`](../markupsection/) e [`MarkupParagraph`](../markupparagraph/). O objeto [`TextFragment`](../textfragment/) fornece acesso ao texto da ocorrência da busca, propriedades do texto e permite editar o texto e mudar o estado do texto (fonte, tamanho da fonte, cor etc).

## Exemplos

O exemplo demonstra como encontrar o primeiro segmento de texto de cada parágrafo na primeira página do documento PDF e destacá-lo.

```csharp
// Open document
Document doc = new Document("input.pdf");

// Create ParagraphAbsorber object
ParagraphAbsorber absorber = new ParagraphAbsorber();

// Accept the absorber for first page
absorber.Visit(doc.Pages[1]);

// Get markup object of first page
PageMarkup markup = absorber.PageMarkups[0];

// Loop through structure elements of the page text to find first text fragment of each paragraph
foreach (MarkupSection section in markup.Sections)
{
    foreach (MarkupParagraph paragraph in section.Paragraphs)
    {
        TextFragment fragment = paragraph.Fragments[0];
        // Update text properties
        fragment.TextState.BackgroundColor = Color.LightBlue;
    }
}

// Save document
doc.Save(GetOutputPath("output.pdf"));
```

### Veja Também

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)