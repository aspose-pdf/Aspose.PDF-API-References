---
title: "XYZExplicitDestination"
second_title: "Aspose.PDF para Python via .NET Referência da API"
description: "Representa destino explícito que exibe a página com as coordenadas (left, top) posicionadas no canto superior esquerdo da janela e o conteúdo da página ampliado pelo fator zoom. Um valor nulo para qualquer um dos parâmetros left, top ou zoom especifica que o valor atual desse parâmetro deve ser mantido inalterado. Um valor de zoom 0 tem o mesmo significado que um valor nulo."
type: docs
weight: 880
url: /pt/python-net/aspose.pdf.annotations/xyzexplicitdestination/
---

## XYZExplicitDestination class

Representa destino explícito que exibe a página com as coordenadas (left, top) posicionadas no canto superior esquerdo da janela e o conteúdo da página ampliado pelo fator zoom. Um valor nulo para qualquer um dos parâmetros left, top ou zoom especifica que o valor atual desse parâmetro deve ser mantido inalterado. Um valor de zoom 0 tem o mesmo significado que um valor nulo.

O tipo XYZExplicitDestination expõe os seguintes membros:
## Construtores
| Nome | Descrição |
| :- | :- |
| XYZExplicitDestination(page, left, top, zoom) | Inicializa uma nova instância da classe XYZExplicitDestination |
| XYZExplicitDestination(document, page_number, left, top, zoom) | Inicializa uma nova instância da classe XYZExplicitDestination |
| XYZExplicitDestination(page_number, left, top, zoom) | Inicializa uma nova instância da classe XYZExplicitDestination |
## Propriedades
| Nome | Descrição |
| :- | :- |
| página | Obtém o objeto da página de destino |
| page_number | Obtém o número da página de destino |
| left | Obtém a coordenada horizontal esquerda do canto superior esquerdo da janela. |
| top | Obtém a coordenada vertical superior do canto superior esquerdo da janela. |
| zoom | Obtém o fator de zoom. |
## Métodos
| Nome | Descrição |
| :- | :- |
| create_destination(page, left, top, zoom, consider_rotation) | Crie o destino para a localização especificada da página, considerando a rotação da página se necessário. |
| create_destination(page, type, values) | Cria instâncias das classes descendentes de ExplicitDestination. |
| create_destination(doc, page_number, type, values) | Cria instâncias das classes descendentes de ExplicitDestination. |
| create_destination(page_number, type, values) | Cria instâncias das classes descendentes de ExplicitDestination. |
| create_destination_to_upper_left_corner(page, zoom) | Crie o destino para o canto superior esquerdo da página especificada. |
| create_destination_to_upper_left_corner(page) | Crie o destino para o canto superior esquerdo da página especificada. |
| to_string() | Converte o estado do objeto em valor de string. Exemplo: "1 XYZ 100 200 3". |

### Veja Também

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

