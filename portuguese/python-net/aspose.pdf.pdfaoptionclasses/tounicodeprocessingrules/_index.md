---
title: "ToUnicodeProcessingRules"
second_title: "Aspose.PDF para Python via .NET Referência da API"
description: "Esta classe descreve regras que podem ser usadas para resolver o erro do Adobe Preflight <br/>            \"Texto não pode ser mapeado para Unicode\"."
type: docs
weight: 20
url: /pt/python-net/aspose.pdf.pdfaoptionclasses/tounicodeprocessingrules/
---

## ToUnicodeProcessingRules class

Esta classe descreve regras que podem ser usadas para resolver o erro do Adobe Preflight <br/>            "Texto não pode ser mapeado para Unicode".

O tipo ToUnicodeProcessingRules expõe os seguintes membros:
## Construtores
| Nome | Descrição |
| :- | :- |
| ToUnicodeProcessingRules() | Construtor |
| ToUnicodeProcessingRules(remove_spaces) | Inicializa uma nova instância da classe ToUnicodeProcessingRules |
| ToUnicodeProcessingRules(remove_spaces, map_non_linked_unicodes_on_space) | Inicializa uma nova instância da classe ToUnicodeProcessingRules |
## Propriedades
| Nome | Descrição |
| :- | :- |
| remove_spaces_from_c_map_names | Algumas fontes têm mapas de códigos de caracteres ToUnicode com espaços nos nomes. Esses espaços podem gerar erros<br/>            com o mapeamento de texto Unicode. Esta flag indica a remoção de espaços dos nomes dos mapas de códigos de caracteres ToUnicode.<br/>            Por padrão, false. |
| map_non_linked_symbols_on_space | Algumas fontes não fornecem informações sobre unicodes para alguns símbolos de texto. <br/>            Essa falta de informação gera um erro "Text cannot be mapped to Unicode".<br/>            Use esta flag para mapear símbolos não vinculados para o "space" Unicode (código 32). |

### Veja Também

* namespace [aspose.pdf.pdfaoptionclasses](/pdf/python-net/aspose.pdf.pdfaoptionclasses/)
* assembly [Aspose.PDF](/pdf/python-net/)

