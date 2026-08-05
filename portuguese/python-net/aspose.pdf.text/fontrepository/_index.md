---
title: "FontRepository"
second_title: "Aspose.PDF para Python via .NET Referência da API"
description: "Executa a busca de fontes. Procura nas fontes instaladas no sistema e nas fontes padrão PDF.<br/>             Também fornece funcionalidade para abrir fontes personalizadas."
type: docs
weight: 130
url: /pt/python-net/aspose.pdf.text/fontrepository/
---

## FontRepository class

Executa a busca de fontes. Procura nas fontes instaladas no sistema e nas fontes padrão PDF.<br/>             Também fornece funcionalidade para abrir fontes personalizadas.

O tipo FontRepository expõe os seguintes membros:
## Construtores
| Nome | Descrição |
| :- | :- |
| FontRepository() | Inicializa uma nova instância da classe FontRepository |
## Propriedades
| Nome | Descrição |
| :- | :- |
| substitutions | Obtém a coleção de estratégias de substituição de fontes. |
| sources | Obtém a coleção de fontes. |
## Métodos
| Nome | Descrição |
| :- | :- |
| find_font(font_name) | Pesquisa e retorna a fonte com o nome de fonte especificado. |
| find_font(font_name, ignore_case) | Pesquisa e retorna a fonte com o nome de fonte especificado ignorando ou respeitando a sensibilidade a maiúsculas e minúsculas. |
| find_font(font_family_name, stl) | Pesquisa e retorna a fonte com o nome e o estilo de fonte especificados. |
| find_font(font_family_name, stl, ignore_case) | Pesquisa e retorna a fonte com o nome e o estilo de fonte especificados <br/>             ignorando ou respeitando a sensibilidade a maiúsculas/minúsculas. |
| open_font(font_stream, font_type) | Abre a fonte com o fluxo de fonte especificado. |
| open_font(font_file_path) | Abre a fonte com o caminho de arquivo de fonte especificado. |
| open_font(font_file_path, metrics_file_path) | Abre a fonte com o caminho de arquivo de fonte especificado. |
| load_fonts() | Carrega fontes instaladas no sistema e fontes PDF padrão. Este método foi projetado para acelerar o processo de carregamento de fontes.<br/>            Por padrão, as fontes são carregadas na primeira solicitação de qualquer fonte. O uso deste método carrega as fontes do sistema e as fontes PDF padrão<br/>            imediatamente antes de qualquer documento PDF ser aberto. |
| reload_fonts() | Recarrega todas as fontes especificadas pela propriedade [sources](/pdf/python-net/aspose.pdf.text/fontrepository/) |

### Veja Também

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

