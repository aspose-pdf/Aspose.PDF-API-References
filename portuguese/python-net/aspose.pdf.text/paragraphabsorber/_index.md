---
title: "ParagraphAbsorber"
second_title: "Aspose.PDF para Python via .NET Referência da API"
description: "Representa um objeto absorvedor de objetos de estrutura de página, como seções e parágrafos.<br/>            Executa busca por seções e parágrafos de texto e fornece acesso a retângulos e polígonos que os descrevem no espaço de coordenadas do texto. <br/>            Também executa busca de segmentos de texto e fornece acesso aos resultados da busca via coleções de TextFragments agrupadas por elementos de estrutura."
type: docs
weight: 240
url: /pt/python-net/aspose.pdf.text/paragraphabsorber/
---

## ParagraphAbsorber class

Representa um objeto absorvedor de objetos de estrutura de página, como seções e parágrafos.<br/>            Executa busca por seções e parágrafos de texto e fornece acesso a retângulos e polígonos que os descrevem no espaço de coordenadas do texto. <br/>            Também executa busca de segmentos de texto e fornece acesso aos resultados da busca via coleções de TextFragments agrupadas por elementos de estrutura.

O tipo ParagraphAbsorber expõe os seguintes membros:
## Construtores
| Nome | Descrição |
| :- | :- |
| ParagraphAbsorber() | Inicializa uma nova instância do [ParagraphAbsorber](/pdf/python-net/aspose.pdf.text/paragraphabsorber/) que realiza a busca por seções/parágrafos do documento ou página. |
| ParagraphAbsorber(sections_search_depth) | Inicializa uma nova instância da classe ParagraphAbsorber |
## Propriedades
| Nome | Descrição |
| :- | :- |
| page_markups | Obtém a coleção de [PageMarkup](/pdf/python-net/aspose.pdf.text/pagemarkup/) que foram absorvidas. |
| sections_search_depth | Obtém ou define o valor que indica quantas vezes buscas sequenciais por elementos mais finos da estrutura serão realizadas.<br/>            A profundidade de busca padrão é 3.<br/>            Isso significa três buscas por seções divididas horizontalmente (cabeçalhos, parágrafos etc.) e três buscas por seções divididas verticalmente (colunas). |
| is_multicolumn_paragraphs_allowed | Obtém ou define o valor que indica se as linhas de texto iniciais de uma próxima seção podem ser tratadas como continuação do último parágrafo de uma seção anterior. |
## Métodos
| Nome | Descrição |
| :- | :- |
| visit(doc) | Realiza a busca por seções e parágrafos no [Document](/pdf/python-net/aspose.pdf/document/) especificado. |
| visit(page) | Executa pesquisa na [Página](/pdf/python-net/aspose.pdf/page/) especificada. |

### Veja Também

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

