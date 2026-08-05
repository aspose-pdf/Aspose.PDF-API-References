---
title: "TextAbsorber"
second_title: "Aspose.PDF para Python via .NET Referência da API"
description: "Representa um objeto absorvedor de texto.<br/>            Executa extração de texto e fornece acesso ao resultado via objeto [text](/pdf/python-net/aspose.pdf.text/textabsorber/)."
type: docs
weight: 320
url: /pt/python-net/aspose.pdf.text/textabsorber/
---

## TextAbsorber class

Representa um objeto absorvedor de texto.<br/>            Executa extração de texto e fornece acesso ao resultado via objeto [text](/pdf/python-net/aspose.pdf.text/textabsorber/).

O tipo TextAbsorber expõe os seguintes membros:
## Construtores
| Nome | Descrição |
| :- | :- |
| TextAbsorber() | Inicializa uma nova instância do [TextAbsorber](/pdf/python-net/aspose.pdf.text/textabsorber/). |
| TextAbsorber(extraction_options) | Inicializa uma nova instância da classe TextAbsorber |
| TextAbsorber(extraction_options, text_search_options) | Inicializa uma nova instância da classe TextAbsorber |
| TextAbsorber(text_search_options) | Inicializa uma nova instância da classe TextAbsorber |
## Propriedades
| Nome | Descrição |
| :- | :- |
| text | Obtém o texto extraído que o [TextAbsorber](/pdf/python-net/aspose.pdf.text/textabsorber/) extrai no documento ou página PDF. |
| has_errors | O valor indica se erros foram encontrados durante a extração de texto.<br/>            A busca por erros será realizada somente se TextSearchOptions.LogTextExtractionErrors = true; e pode diminuir o desempenho. |
| errors | Lista de objetos [TextExtractionError](/pdf/python-net/aspose.pdf.text/textextractionerror/). Contém informações sobre erros encontrados durante a extração de texto.<br/>            A busca por erros será realizada somente se TextSearchOptions.LogTextExtractionErrors = true; e pode diminuir o desempenho. |
| extraction_options | Obtém ou define opções de extração de texto. |
| text_search_options | Obtém ou define as opções de pesquisa de texto. |
## Métodos
| Nome | Descrição |
| :- | :- |
| visit(page) | Extrai texto na página especificada |
| visit(form) | Extrai texto no XForm especificado. |
| visit(pdf) | Extrai texto no documento especificado |

### Veja Também

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

