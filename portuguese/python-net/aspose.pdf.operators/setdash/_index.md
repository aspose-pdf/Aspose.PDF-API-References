---
title: "SetDash"
second_title: "Aspose.PDF para Python via .NET Referência da API"
description: "Classe que representa o operador d (define o padrão de traço da linha)."
type: docs
weight: 580
url: /pt/python-net/aspose.pdf.operators/setdash/
---

## SetDash class

Classe que representa o operador d (define o padrão de traço da linha).

O tipo SetDash expõe os seguintes membros:
## Construtores
| Nome | Descrição |
| :- | :- |
| SetDash(pattern, phase) | Inicializa uma nova instância da classe SetDash |
## Propriedades
| Nome | Descrição |
| :- | :- |
| índice | Índice do operador na lista de operadores da página. |
| pattern | Padrão de traço. Os elementos da matriz devem ser números que especificam os comprimentos de traços e espaços alternados.<br/>            No caso de uma matriz com um único elemento, os comprimentos do traço e do espaço são iguais. |
| phase | Fase do traço. Antes de começar a desenhar um caminho, a matriz de traços deve ser percorrida, somando os comprimentos dos traços e dos espaços. <br/>            Quando o comprimento acumulado for igual ao valor especificado pela fase do traço, o desenho do caminho deve começar, <br/>            e a matriz de traços deve ser usada ciclicamente a partir desse ponto. |
## Métodos
| Nome | Descrição |
| :- | :- |
| accept(visitor) | Aceita objeto visitante para processar o operador. |
| is_text_show_operator(op) | Determina se o operador é o operador responsável pela saída de texto (Tj, TJ, etc) |

### Veja Também

* namespace [aspose.pdf.operators](/pdf/python-net/aspose.pdf.operators/)
* assembly [Aspose.PDF](/pdf/python-net/)

