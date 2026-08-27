---
title: "TextFragmentAbsorber"
second_title: "Aspose.PDF para Python via .NET Referência da API"
description: "Representa um objeto absorvedor de fragmentos de texto.<br/>            Executa busca de texto e fornece acesso aos resultados da busca via coleção [text_fragments](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/)."
type: docs
weight: 400
url: /pt/python-net/aspose.pdf.text/textfragmentabsorber/
---

## TextFragmentAbsorber class

Representa um objeto absorvedor de fragmentos de texto.<br/>            Executa busca de texto e fornece acesso aos resultados da busca via coleção [text_fragments](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/).

O tipo TextFragmentAbsorber expõe os seguintes membros:
## Construtores
| Nome | Descrição |
| :- | :- |
| TextFragmentAbsorber() | Inicializa uma nova instância do [TextFragmentAbsorber](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/) que realiza a busca de todos os segmentos de texto do documento ou página. |
| TextFragmentAbsorber(text_edit_options) | Inicializa uma nova instância da classe TextFragmentAbsorber |
| TextFragmentAbsorber(phrase) | Inicializa uma nova instância da classe TextFragmentAbsorber |
| TextFragmentAbsorber(phrase, text_search_options) | Inicializa uma nova instância da classe TextFragmentAbsorber |
| TextFragmentAbsorber(phrase, text_search_options, text_edit_options) | Inicializa uma nova instância da classe TextFragmentAbsorber |
| TextFragmentAbsorber(phrase, text_edit_options) | Inicializa uma nova instância da classe TextFragmentAbsorber |
## Propriedades
| Nome | Descrição |
| :- | :- |
| text | Obtém o texto extraído que o [TextAbsorber](/pdf/python-net/aspose.pdf.text/textabsorber/) extrai no documento ou página PDF. |
| has_errors | O valor indica se erros foram encontrados durante a extração de texto.<br/>            A busca por erros será realizada somente se TextSearchOptions.LogTextExtractionErrors = true; e pode diminuir o desempenho. |
| errors | Lista de objetos [TextExtractionError](/pdf/python-net/aspose.pdf.text/textextractionerror/). Contém informações sobre erros encontrados durante a extração de texto.<br/>            A busca por erros será realizada somente se TextSearchOptions.LogTextExtractionErrors = true; e pode diminuir o desempenho. |
| extraction_options | Obtém ou define opções de extração de texto. |
| text_search_options | Obtém ou define opções de pesquisa. As opções permitem pesquisa usando expressões regulares. |
| text_fragments | Obtém a coleção de ocorrências de pesquisa que são apresentadas com objetos [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/). |
| phrase | Obtém ou define a frase que o [TextFragmentAbsorber](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/) procura no documento PDF ou na página. |
| text_edit_options | Obtém ou define opções de edição de texto. As opções definem comportamento especial quando o símbolo solicitado não pode ser escrito com a fonte. |
| text_replace_options | Obtém ou define opções de substituição de texto. As opções definem o comportamento quando o texto do fragmento é substituído por um texto mais curto ou mais longo. |
## Métodos
| Nome | Descrição |
| :- | :- |
| visit(page) | Executa a pesquisa na página especificada. |
| visit(pdf) | Executa a pesquisa no documento especificado. |
| visit(x_form) | Executa a pesquisa no objeto de formulário especificado. |
| apply_for_all_fragments(font) | Aplica a fonte para todos os fragmentos de texto que foram absorvidos. Funciona mais rápido que percorrer os fragmentos se todos os fragmentos nas página(s) foram absorvidos. Caso contrário, funciona de forma semelhante ao percorrer em loop. |
| apply_for_all_fragments(font_size) | Aplica o tamanho da fonte para todos os fragmentos de texto que foram absorvidos. Funciona mais rápido que percorrer os fragmentos se todos os fragmentos nas página(s) foram absorvidos. Caso contrário, funciona de forma semelhante ao percorrer em loop. |
| apply_for_all_fragments(font, font_size) | Aplica a fonte e o tamanho para todos os fragmentos de texto que foram absorvidos. Funciona mais rápido que percorrer os fragmentos se todos os fragmentos nas página(s) foram absorvidos. Caso contrário, funciona de forma semelhante ao percorrer em loop. |
| remove_all_text(page) | Remove todo o texto da página especificada. |
| remove_all_text(page, rect) | Remove o texto dentro do retângulo especificado da página especificada. |
| remove_all_text(document) | Remove todo o texto do documento. |
| reset() | Limpa a coleção TextFragments deste objeto [TextFragmentAbsorber](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/). |

### Veja Também

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

