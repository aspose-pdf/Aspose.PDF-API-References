---
title: "Matrix"
second_title: "Aspose.PDF para Python via .NET Referência da API"
description: "Classe representa matriz de transformação."
type: docs
weight: 900
url: /pt/python-net/aspose.pdf/matrix/
---

## Matrix class

Classe representa matriz de transformação.

O tipo Matrix expõe os seguintes membros:
## Construtores
| Nome | Descrição |
| :- | :- |
| Matrix() | Construtor<br/>            cria matriz padrão 1 para 1:<br/>            [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] |
| Matrix(matrix_array) | Inicializa uma nova instância da classe Matrix |
| Matrix(matrix_array) | Inicializa uma nova instância da classe Matrix |
| Matrix(matrix) | Inicializa uma nova instância da classe Matrix |
| Matrix(a, b, c, d, e, f) | Inicializa uma nova instância da classe Matrix |
## Propriedades
| Nome | Descrição |
| :- | :- |
| data | Obtém os dados da Matrix como array. |
| a | Um membro da matriz de transformação. |
| b | Membro B da matriz de transformação. |
| c | Membro C da matriz de transformação. |
| d | Membro D da matriz de transformação. |
| e | Membro E da matriz de transformação. |
| f | Membro F da matriz de transformação. |
| elementos | Elementos da matriz. |
## Métodos
| Nome | Descrição |
| :- | :- |
| rotation(alpha) | Cria matriz para o ângulo de rotação fornecido. |
| rotation(rotation) | Cria matriz para o ângulo de rotação fornecido. |
| transform(p) | Transforma ponto usando esta matriz. |
| transform(rect) | Transforma retângulo.<br/>            Se o ângulo não for 90 * N graus, então o retângulo delimitador é retornado. |
| skew(alpha, beta) | Cria matriz para o ângulo de rotação fornecido. |
| get_angle(rotation) | Traduz rotação em ângulo (graus) |
| multiply(other) | Multiplica a matriz por outra matriz. |
| add(other) | Adiciona matriz a outra matriz. |
| reverse() | Calcula a matriz inversa. |

### Veja Também

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

