---
title: "PdfPageStamp"
second_title: "Aspose.PDF para Python via .NET Referência da API"
description: "Classe representa selo que usa página PDF como selo."
type: docs
weight: 1230
url: /pt/python-net/aspose.pdf/pdfpagestamp/
---

## PdfPageStamp class

Classe representa selo que usa página PDF como selo.

O tipo PdfPageStamp expõe os seguintes membros:
## Construtores
| Nome | Descrição |
| :- | :- |
| PdfPageStamp(pdf_page) | Inicializa uma nova instância da classe PdfPageStamp |
| PdfPageStamp(file_name, page_index) | Inicializa uma nova instância da classe PdfPageStamp |
| PdfPageStamp(stream, page_index) | Inicializa uma nova instância da classe PdfPageStamp |
## Propriedades
| Nome | Descrição |
| :- | :- |
| background | Define ou obtém um valor booleano que indica se o conteúdo está estampado como plano de fundo.<br/>            Se o valor for true, o conteúdo da marca será colocado na parte inferior.<br/>            Por padrão, o valor é false, o conteúdo da marca será colocado na parte superior. |
| opacidade | Obtém ou define um valor para indicar a opacidade da marca. O valor varia de 0.0 a 1.0.<br/>            Por padrão, o valor é 1.0. |
| outline_opacity | Obtém ou define um valor para indicar a opacidade do contorno da marca. O valor varia de 0.0 a 1.0.<br/>            Por padrão, o valor é 1.0. |
| outline_width | Obtém ou define um valor para a largura do contorno da marca.<br/>            Por padrão, o valor é 1.0. |
| rotate | Define ou obtém a rotação do conteúdo do selo de acordo com os valores de [Rotation](/pdf/python-net/aspose.pdf/rotation/).<br/>            Nota. Esta propriedade é para ângulos definidos que são múltiplos de 90 graus (0, 90, 180, 270 graus).<br/>            Para definir um ângulo arbitrário use a propriedade RotateAngle. <br/>            Se o ângulo definido por ArbitraryAngle não for múltiplo de 90, então a propriedade Rotate retorna Rotation.None. |
| x_indent | Coordenada horizontal do selo, começando da esquerda. |
| y_indent | Coordenada vertical do selo, começando da parte inferior. |
| horizontal_alignment | Obtém ou define o alinhamento horizontal do selo na página. |
| vertical_alignment | Obtém ou define o alinhamento vertical do selo na página. |
| left_margin | Obtém ou define a margem esquerda do selo. |
| right_margin | Obtém ou define a margem direita do selo. |
| bottom_margin | Obtém ou define a margem inferior do selo. |
| top_margin | Obtém ou define a margem superior do selo. |
| zoom_x | Fator de zoom horizontal do selo. Permite dimensionar o selo horizontalmente. |
| largura | Largura desejada do selo na página. |
| altura | Altura desejada do selo na página. |
| zoom_y | Fator de zoom vertical do selo. Permite dimensionar o selo verticalmente. |
| zoom | Fator de zoom do selo. Permite dimensionar o selo.<br/>            Observe que o par de propriedades ZoomX e ZoomY permite definir o fator de zoom para cada eixo separadamente. <br/>            Definir esta propriedade altera ambas as propriedades ZoomX e ZoomY. <br/>            Se ZoomX e ZoomY forem diferentes, então a propriedade Zoom retorna o valor de ZoomX. |
| rotate_angle | Obtém ou define o ângulo de rotação do selo em graus.<br/>            Esta propriedade permite definir um ângulo de rotação arbitrário. |
| pdf_page | Obtém ou define a página que será usada como selo. |
## Métodos
| Nome | Descrição |
| :- | :- |
| put(page) | Coloca o selo na página especificada. |
| set_stamp_id(value) | Define o Id do selo. |
| get_stamp_id() | Retorna o ID do carimbo. |

### Veja Também

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

