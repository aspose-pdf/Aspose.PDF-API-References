---
title: Class TextAbsorber
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Text.TextAbsorber. Representa um objeto absorvedor de texto. Realiza a extração de texto e fornece acesso ao resultado através do objeto [`Text`](./text/)
type: docs
weight: 10800
url: /pt/net/aspose.pdf.text/textabsorber/
---
## Classe TextAbsorber

Representa um objeto absorvedor de texto. Realiza a extração de texto e fornece acesso ao resultado através do objeto [`Text`](./text/).

```csharp
public class TextAbsorber
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [TextAbsorber](textabsorber/#constructor)() | Inicializa uma nova instância do `TextAbsorber`. |
| [TextAbsorber](textabsorber/#constructor_1)(TextExtractionOptions) | Inicializa uma nova instância do `TextAbsorber` com opções de extração. |
| [TextAbsorber](textabsorber/#constructor_3)(TextSearchOptions) | Inicializa uma nova instância do `TextAbsorber` com opções de busca de texto. |
| [TextAbsorber](textabsorber/#constructor_2)(TextExtractionOptions, TextSearchOptions) | Inicializa uma nova instância do `TextAbsorber` com opções de extração e busca de texto. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [Errors](../../aspose.pdf.text/textabsorber/errors/) { get; } | Lista de objetos [`TextExtractionError`](../textextractionerror/). Contém informações sobre erros encontrados durante a extração de texto. A busca por erros será realizada apenas se TextSearchOptions.LogTextExtractionErrors = true; E isso pode diminuir o desempenho. |
| virtual [ExtractionOptions](../../aspose.pdf.text/textabsorber/extractionoptions/) { get; set; } | Obtém ou define opções de extração de texto. |
| [HasErrors](../../aspose.pdf.text/textabsorber/haserrors/) { get; } | Valor que indica se erros foram encontrados durante a extração de texto. A busca por erros será realizada apenas se TextSearchOptions.LogTextExtractionErrors = true; E isso pode diminuir o desempenho. |
| virtual [Text](../../aspose.pdf.text/textabsorber/text/) { get; } | Obtém o texto extraído que o `TextAbsorber` extrai do documento ou página PDF. |
| virtual [TextSearchOptions](../../aspose.pdf.text/textabsorber/textsearchoptions/) { get; set; } | Obtém ou define opções de busca de texto. |

## Métodos

| Nome | Descrição |
| --- | --- |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/#visit)(Document) | Extrai texto do documento especificado |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/#visit_1)(Page) | Extrai texto da página especificada |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/#visit_2)(XForm) | Extrai texto do XForm especificado. |

## Observações

O objeto `TextAbsorber` é usado para extrair texto de um documento Pdf ou da página do documento.

## Exemplos

O exemplo demonstra como extrair texto na primeira página do documento PDF.

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text
TextAbsorber absorber = new TextAbsorber();

// accept the absorber for first page
doc.Pages[1].Accept(absorber);

// get the extracted text
string extractedText = absorber.Text;

```

### Veja Também

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)