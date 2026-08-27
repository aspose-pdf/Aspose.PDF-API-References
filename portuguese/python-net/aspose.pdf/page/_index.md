---
title: "Page"
second_title: "Aspose.PDF para Python via .NET Referência da API"
description: "Classe que representa página de documento PDF."
type: docs
weight: 1080
url: /pt/python-net/aspose.pdf/page/
---

## Page class

Classe que representa página de documento PDF.

O tipo Page expõe os seguintes membros:
## Propriedades
| Nome | Descrição |
| :- | :- |
| is_add_paragraphs_after_last | Obtém ou define a adição de parágrafos após o último parágrafo da página |
| background_image | Obtém ou define a imagem de fundo da página (apenas para gerador, não preenchida ao ler o documento). |
| toc_info | Obtém ou define informações do índice. |
| header | Obtém ou define o cabeçalho da página. |
| camadas | Obtém ou define a coleção de camadas. |
| rodapé | Obtém ou define o rodapé da página. |
| paragraphs | Obtém os parágrafos. |
| page_info | Obtém ou define as informações da página (somente para gerador, não preenchido ao ler o documento). |
| retângulo | Obtém ou define o retângulo da página.<br/>            Para obter: a caixa de recorte da página é retornada se especificada, caso contrário a caixa de mídia da página é retornada.<br/>            Para definir: a caixa de mídia da página é sempre definida.<br/>            Observe que esta propriedade não considera a rotação da página. Para obter o retângulo da página considerando a rotação, use ActualRect. |
| color_type | Define o tipo de cor das páginas com base nas informações obtidas dos operadores SetColor,<br/>            imagens e formulários. |
| note_line_style | Obtém ou define o estilo de linha para notas (somente para gerador, não preenchido ao ler o documento). |
| tab_order | Obtém ou define a ordem de tabulação da página. <br/>            Valores possíveis: Row, Column. Default, Manual |
| duration | Obtém ou define a duração de exibição da página. Este é o tempo em segundos que a página deve ser exibida durante a apresentação.<br/>            Retorna -1 se a duração não estiver definida. |
| contents | Obtém a coleção de operadores no fluxo de conteúdo da página.<br/>            [OperatorCollection](/pdf/python-net/aspose.pdf/operatorcollection/) |
| grupo | Obtém ou define uma classe de atributos de grupo que especifica os atributos do grupo de página para uso no modelo de imagem transparente. |
| annotations | Obtém a coleção de anotações da página.<br/>            [annotations](/pdf/python-net/aspose.pdf/page/) |
| resources | Obtém os recursos da página. O objeto Resources contém coleções de imagens, formulários e fontes.<br/>            [resources](/pdf/python-net/aspose.pdf/page/) |
| girar | Obtém ou define a rotação da página. |
| trim_box | Obtém ou define a trim box da página. |
| art_box | Obtém ou define a art box da página. |
| bleed_box | Obtém ou define a caixa de sangria da página. |
| crop_box | Obtém ou define a caixa de recorte da página. |
| media_box | Obtém ou define a caixa de mídia da página. |
| número | Obtém o número da página. |
| rotation_matrix | Obtém a matriz de transformação da página. |
| background | Obtém ou define a cor de fundo da página. |
| watermark | Obtém ou define a marca d'água da página. |
| artifacts | Obtém a coleção de artefatos na página. |
| ações | Obtém a coleção de propriedades da página. |
| fields_in_tab_order | Obtém a lista de objetos Field em ordem de tabulação nesta página. |
| user_unit | Obtém ou define o valor UserUnit. Um número positivo que indica o tamanho das unidades de espaço do usuário padrão, em múltiplos de 1 ⁄ 72 polegada.<br/>            O valor padrão é 1. Defina zero ou um valor negativo para limpar esta entrada na página. |
## Métodos
| Nome | Descrição |
| :- | :- |
| send_to(device, output) | Envia a página para processamento com o dispositivo de página fornecido. |
| send_to(device, output_file_name) | Envia a página para processamento com o dispositivo de página fornecido. |
| accept(visitor) | Aceita o objeto visitante [AnnotationSelector](/pdf/python-net/aspose.pdf.annotations/annotationselector/) que fornece funcionalidade para trabalhar com anotações. |
| accept(visitor) | Aceita o objeto visitante [TextFragmentAbsorber](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/) que fornece funcionalidade para trabalhar com objetos de texto. |
| accept(visitor) | Aceita o objeto visitante [ImagePlacementAbsorber](/pdf/python-net/aspose.pdf/imageplacementabsorber/) que fornece funcionalidade para trabalhar com objetos de posicionamento de imagem. |
| accept(visitor) | Aceita o objeto visitante [TextAbsorber](/pdf/python-net/aspose.pdf.text/textabsorber/) que fornece funcionalidade para trabalhar com objetos de texto. |
| add_image(image_stream, image_rect) | Adiciona a imagem à página e a posiciona no centro do retângulo especificado, preservando a proporção da imagem. |
| add_image(hocr, image_stream, image_rect) | Adiciona uma imagem pesquisável à página e a posiciona no centro do retângulo especificado, preservando a proporção da imagem. |
| add_image(image_stream, image_rect, image_width, image_height, save_image_proportions) | Adiciona imagem na página e a posiciona dependendo da posição do retângulo da imagem. |
| add_image(image_path, rectangle) | Adiciona uma imagem pesquisável à página e a posiciona no centro do retângulo especificado, preservando a proporção da imagem. |
| is_blank(fill_threshold_factor) | Obtém a indicação de se a página está em branco ou não. |
| get_page_rect(consider_rotation) | Retorna o retângulo da página de acordo com seu CropBox (ou MediaBox se o CropBox for nulo). |
| calculate_content_b_box() | Calcula o valor da bbox – retângulo que contém o conteúdo sem margens visíveis. |
| rotation_to_int(rotation) | Traduz o membro da enumeração de rotação para um valor inteiro. |
| int_to_rotation(rotation) | Traduz o valor inteiro para o membro correspondente da enumeração de rotação. |
| add_stamp(stamp) | Insere selo na página. O selo pode ser número de página, imagem ou texto simples, por exemplo, algum logotipo. |
| flatten() | Remove todos os campos localizados na página e coloca seus valores no lugar. |
| set_page_size(width, height) | Define o tamanho da página. |
| make_grayscale() | Converte a página para escala de cinza. |
| free_memory() | Limpa os dados em cache |
| get_notifications() | Retorna notificações sobre operações internas com o conteúdo da página. (Apenas notificações sobre eventos de parágrafo em cenários de adição de texto são suportadas atualmente.) |
| as_byte_array(resolution) | Converte a página atual em bitmap e então retorna um array de bytes. |
| as_xml() | Converte a página atual em XML com codificação UTF-8. |

### Veja Também

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

