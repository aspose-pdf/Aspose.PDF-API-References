---
title: Class TextParagraph
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Text.TextParagraph. Representa parágrafos de texto como um objeto de texto multilinha
type: docs
weight: 10990
url: /pt/net/aspose.pdf.text/textparagraph/
---
## Classe TextParagraph

Representa parágrafos de texto como um objeto de texto multilinha.

```csharp
public sealed class TextParagraph
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [TextParagraph](textparagraph/)() | O construtor padrão. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [FirstLineIndent](../../aspose.pdf.text/textparagraph/firstlineindent/) { get; set; } | Obtém ou define o valor de recuo das linhas subsequentes. Se definido como um valor diferente de zero, tem uma vantagem sobre o valor FormattingOptions.SubsequentLinesIndent. |
| [FormattingOptions](../../aspose.pdf.text/textparagraph/formattingoptions/) { get; set; } | Obtém ou define as opções de formatação. |
| [HorizontalAlignment](../../aspose.pdf.text/textparagraph/horizontalalignment/) { get; set; } | Obtém ou define o alinhamento horizontal para o texto dentro do [`Rectangle`](./rectangle/) do parágrafo. |
| [Justify](../../aspose.pdf.text/textparagraph/justify/) { get; set; } | Obtém ou define o valor se o texto é justificado. |
| [Margin](../../aspose.pdf.text/textparagraph/margin/) { get; set; } | Obtém ou define o preenchimento. |
| [Position](../../aspose.pdf.text/textparagraph/position/) { get; set; } | Obtém ou define a posição do parágrafo. |
| [Rectangle](../../aspose.pdf.text/textparagraph/rectangle/) { get; set; } | Obtém ou define o retângulo do parágrafo. |
| [Rotation](../../aspose.pdf.text/textparagraph/rotation/) { get; set; } | Obtém ou define o ângulo de rotação em graus. |
| [SubsequentLinesIndent](../../aspose.pdf.text/textparagraph/subsequentlinesindent/) { get; set; } | Obtém ou define o valor de recuo das linhas subsequentes. Se definido como um valor diferente de zero, tem uma vantagem sobre o valor FormattingOptions.SubsequentLinesIndent. |
| [TextRectangle](../../aspose.pdf.text/textparagraph/textrectangle/) { get; } | Obtém o retângulo do texto colocado no parágrafo. |
| [VerticalAlignment](../../aspose.pdf.text/textparagraph/verticalalignment/) { get; set; } | Obtém ou define o alinhamento vertical para o texto dentro do [`Rectangle`](./rectangle/) do parágrafo. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_3)(string) | Anexa linha de texto |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline)(TextFragment) | Anexa linha de texto com parâmetros de estado de texto. |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_6)(string, float) | Anexa linha de texto. |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_4)(string, TextState) | Anexa linha de texto com parâmetros de estado de texto. |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_1)(TextFragment, TextState) | Anexa linha de texto com parâmetros de estado de texto. |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_5)(string, TextState, float) | Anexa linha de texto com parâmetros de estado de texto |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_2)(TextFragment, TextState, float) | Anexa linha de texto com parâmetros de estado de texto |
| [BeginEdit](../../aspose.pdf.text/textparagraph/beginedit/)() | Inicia a edição do TextParagraph. |
| [EndEdit](../../aspose.pdf.text/textparagraph/endedit/)() | Termina a edição do TextParagraph. |

## Exemplos

O exemplo demonstra como criar um objeto de parágrafo de texto e anexá-lo à página do Pdf.

```csharp
Document doc = new Document(inFile);

Page page = (Page)doc.Pages[1];

// create text paragraph
TextParagraph paragraph = new TextParagraph();
           
// set the paragraph rectangle
paragraph.Rectangle = new Rectangle(100, 600, 200, 700);

// set word wrapping options
paragraph.FormattingOptions.WrapMode = TextFormattingOptions.WordWrapMode.ByWords;

// append string lines
paragraph.AppendLine("the quick brown fox jumps over the lazy dog");
paragraph.AppendLine("line2");
paragraph.AppendLine("line3");

// append the paragraph to the Pdf page with the TextBuilder
TextBuilder textBuilder = new TextBuilder(page);
textBuilder.AppendParagraph(paragraph);

// save Pdf document
doc.Save(outFile);
```

### Veja Também

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)