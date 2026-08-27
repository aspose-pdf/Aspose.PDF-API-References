---
title: "Retângulo"
second_title: "Aspose.PDF para Python via .NET Referência da API"
description: "Classe representa retângulo."
type: docs
weight: 1320
url: /pt/python-net/aspose.pdf/rectangle/
---

## Rectangle class

Classe representa retângulo.

O tipo Retângulo expõe os seguintes membros:
## Construtores
| Nome | Descrição |
| :- | :- |
| Rectangle(llx, lly, urx, ury, normalize_coordinates) | Inicializa uma nova instância da classe Retângulo |
## Propriedades
| Nome | Descrição |
| :- | :- |
| largura | Largura do retângulo. |
| altura | Altura do retângulo. |
| llx | Coordenada X do canto inferior esquerdo. |
| lly | Coordenada Y do canto inferior esquerdo. |
| urx | Coordenada X do canto superior direito. |
| ury | Coordenada Y do canto superior direito. |
| trivial | Inicializa um retângulo trivial, ou seja, um retângulo com posição e tamanho zero. |
| is_trivial | Verifica se o retângulo é trivial, ou seja, tem tamanho e posição zero. |
| is_empty | Verifica se o retângulo está vazio. |
| is_point | Verifica se o retângulo é um ponto, ou seja, LLX é igual a URX e LLY é igual a URY. |
| empty | Retângulo vazio |
## Métodos
| Nome | Descrição |
| :- | :- |
| rotate(angle) | Gira o retângulo pelo ângulo especificado. |
| rotate(angle) | Gira o retângulo pelo ângulo especificado. |
| to_rect() | Converte o retângulo para uma instância de System.Drawing.Rectangle. Posicionamentos e tamanhos em ponto flutuante são truncados. |
| from_rect(src) | Inicializa um novo retângulo a partir da instância fornecida de System.Drawing.Rectangle. |
| parse(value) | Tenta analisar a string e extrair dela os componentes do retângulo llx, lly, urx, ury. |
| equals(other) | Verifica se os retângulos são iguais, ou seja, têm a mesma posição e tamanho. |
| near_equals(other, delta) | Verifica se os retângulos são quase iguais, ou seja, têm posição e tamanho quase os mesmos (até delta). |
| intersect(other_rect) | Intersecciona retângulos. |
| join(other_rect) | Junta retângulos. |
| is_intersect(other_rect) | Determina se este retângulo intersecta com outro retângulo. |
| contains(point) | Determina se o ponto fornecido está dentro do retângulo. |
| center() | Retorna as coordenadas do centro do retângulo. |
| clone() | Clona o objeto Rectangle. |
| to_points() | Converte o retângulo em um array de pontos ("QuadPoints"). |

### Veja Também

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

