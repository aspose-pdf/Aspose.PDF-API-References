---
title: "Stamp"
second_title: "Aspose.PDF para Python via .NET Referência da API"
description: "Classe que representa carimbo."
type: docs
weight: 410
url: /pt/python-net/aspose.pdf.facades/stamp/
---

## Stamp class

Classe que representa carimbo.

O tipo Stamp expõe os seguintes membros:
## Construtores
| Nome | Descrição |
| :- | :- |
| Stamp() | Inicializa uma nova instância da classe Stamp |
## Propriedades
| Nome | Descrição |
| :- | :- |
| stamp_id | Obtém ou define o identificador do selo. |
| qualidade | Obtém ou define a qualidade do selo de imagem em porcentagem. Valores válidos 0..100%. |
| opacidade | Obtém ou define a opacidade do selo. |
| page_number | Obtém ou define o número da página. |
| páginas | Obtém ou define um array com os números das páginas que serão afetadas pelo selo. <br/>            Se Pages = null, todas as páginas do documento são afetadas. |
| rotation | Obtém ou define a rotação do selo em graus. |
| is_background | Obtém ou define o status de fundo. Se true, o selo será colocado como fundo da página estampada.<br/>            Por padrão, é definido como false. |
| blending_space | Obtém ou define um valor BlendingColorSpace que define um espaço de cor <br/>            que é usado para realizar operações de transparência e mesclagem na página. |
## Métodos
| Nome | Descrição |
| :- | :- |
| bind_pdf(pdf_file, page_number) | Define o arquivo PDF e o número da página que será usado como selo. |
| bind_pdf(pdf_stream, page_number) | Define o arquivo PDF e o número da página que será usado como selo. |
| bind_image(image_file) | Define a imagem como um selo. |
| bind_image(image) | Define a imagem que será usada como selo. |
| bind_logo(formatted_text) | Define o texto como selo. |
| bind_text_state(text_state) | Define o estado de texto do selo. |
| set_origin(origin_x, origin_y) | Define a posição na página onde o selo será colocado. |
| set_image_size(width, height) | Define o tamanho do selo de imagem. A imagem será dimensionada de acordo com os valores especificados. |

### Veja Também

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

