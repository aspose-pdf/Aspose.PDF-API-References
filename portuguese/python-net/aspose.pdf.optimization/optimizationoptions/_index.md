---
title: "OptimizationOptions"
second_title: "Aspose.PDF para Python via .NET Referência da API"
description: "Classe que descreve o algoritmo de otimização de documento.<br/>            Instância desta classe pode ser usada como parâmetro do método OptimizeResources()."
type: docs
weight: 20
url: /pt/python-net/aspose.pdf.optimization/optimizationoptions/
---

## OptimizationOptions class

Classe que descreve o algoritmo de otimização de documento.<br/>            Instância desta classe pode ser usada como parâmetro do método OptimizeResources().

O tipo OptimizationOptions expõe os seguintes membros:
## Construtores
| Nome | Descrição |
| :- | :- |
| OptimizationOptions() | Inicializa uma nova instância da classe OptimizationOptions |
## Propriedades
| Nome | Descrição |
| :- | :- |
| link_duplcate_streams | Se esta flag for definida como true, os fluxos de recurso serão analisados. Se fluxos duplicados forem encontrados (ou seja, se o conteúdo do fluxo for igual), então esses fluxos serão armazenados como um único objeto. <br/>            Isso permite reduzir o tamanho do documento em alguns casos (por exemplo, quando o mesmo documento foi concatenado várias vezes). |
| allow_reuse_page_content | Se true, o conteúdo das páginas será reutilizado quando o documento for otimizado para páginas iguais. |
| remove_unused_streams | Se esta flag for definida como true, cada recurso será verificado quanto ao uso. Se o recurso nunca for usado, ele será removido.<br/>            Isso pode reduzir o tamanho do documento, por exemplo, quando páginas foram extraídas do documento. |
| remove_unused_objects | Se esta flag for definida como true, todos os objetos do documento serão verificados e os objetos não utilizados (ou seja, objetos que não têm nenhuma referência) serão removidos do documento. |
| image_compression_options | Conjunto de opções que descrevem se as imagens no documento serão comprimidas e os parâmetros da compressão. |
| compress_images | Se esta flag estiver definida como true, as imagens serão comprimidas no documento. O nível de compressão é especificado com a propriedade ImageQuality. |
| resize_images | Se esta flag estiver definida como true e CompressImages for true, as imagens serão redimensionadas se a resolução da imagem for maior que o parâmetro MaxResolution especificado. |
| image_quality | Especifica o nível de compressão de imagem quando a flag CompressIamges é usada. |
| max_resoultion | Especifica a resolução máxima das imagens. Se a imagem tiver resolução maior, ela será redimensionada. |
| unembed_fonts | Faça com que as fontes não sejam incorporadas se definido como true. |
| subset_fonts | As fontes serão convertidas em subconjuntos se definidas como true. |
| remove_private_info | Remova informações privadas (informações de peça de página). |
| image_encoding | Codificação de imagem que será usada. |
## Métodos
| Nome | Descrição |
| :- | :- |
| all() | Cria estratégia de otimização com todas as opções ativadas.<br/>            Observe que são ativadas apenas opções que não alteram nenhuma funcionalidade do documento.<br/>            Ou seja, compressão de imagem e desincorporação de fontes não serão habilitadas (e podem ser incorporadas manualmente). |

### Veja Também

* namespace [aspose.pdf.optimization](/pdf/python-net/aspose.pdf.optimization/)
* assembly [Aspose.PDF](/pdf/python-net/)

