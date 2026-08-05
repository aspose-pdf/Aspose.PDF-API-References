---
title: "PdfFormatConversionOptions"
second_title: "Aspose.PDF para Python via .NET Referência da API"
description: "representa conjunto de opções para converter documento PDF"
type: docs
weight: 1220
url: /pt/python-net/aspose.pdf/pdfformatconversionoptions/
---

## PdfFormatConversionOptions class

representa conjunto de opções para converter documento PDF

O tipo PdfFormatConversionOptions expõe os seguintes membros:
## Construtores
| Nome | Descrição |
| :- | :- |
| PdfFormatConversionOptions(output_log_file_name, format, action) | Inicializa uma nova instância da classe PdfFormatConversionOptions |
| PdfFormatConversionOptions(output_log_file_name, format) | Inicializa uma nova instância da classe PdfFormatConversionOptions |
| PdfFormatConversionOptions(format) | Inicializa uma nova instância da classe PdfFormatConversionOptions |
| PdfFormatConversionOptions(format, action) | Inicializa uma nova instância da classe PdfFormatConversionOptions |
| PdfFormatConversionOptions(output_log_file_name, format, action, transparency_action) | Inicializa uma nova instância da classe PdfFormatConversionOptions |
| PdfFormatConversionOptions(output_log_stream, format, action) | Inicializa uma nova instância da classe PdfFormatConversionOptions |
## Propriedades
| Nome | Descrição |
| :- | :- |
| is_async_image_streams_conversion_mode | Obtém/define a execução de fluxos de imagem no modo assíncrono. |
| is_low_memory_mode | O modo de conversão de baixa memória está habilitado |
| format | Formato PDF. |
| log_file_name | Caminho para o arquivo onde os comentários serão armazenados. |
| log_stream | Fluxo onde os comentários serão armazenados. |
| error_action | Ação para objetos que não podem ser convertidos |
| transparency_action | Ação para objetos de imagem mascarados |
| convert_soft_mask_action | Ação para imagens com máscara suave. |
| padrão | Obtém o objeto PdfFormatConversionOptions com parâmetros padrão |
| non_specification_cases | Mantém sinalizadores para controlar o processo de conversão PDF/A para casos em que o documento de origem<br/>            não corresponde à especificação PDF/A. |
| symbolic_font_encoding_strategy | Estratégia para copiar dados de codificação para fontes simbólicas se a fonte TrueType simbólica<br/>            possuir mais de uma sub‑tabela de codificação. |
| align_text | Esta bandeira controla o alinhamento de texto no documento convertido. Por padrão, a conversão de documento <br/>            não afeta o alinhamento de texto e deixa o texto como está. Mas em alguns casos a substituição de fontes<br/>            causa sobreposição de texto ou espaços extras no documento convertido. Quando esta bandeira está definida<br/>            operações especiais de alinhamento serão realizadas. Esta bandeira deve ser definida apenas para documentos<br/>            que apresentam problemas com texto sobreposto ou espaços de texto extras, pois o uso desta bandeira diminui<br/>            o desempenho e, em alguns casos, pode corromper o conteúdo do texto. |
| pua_text_processing_strategy | Estratégia para processar símbolos da área de uso privado (PUA) Unicode. |
| optimize_file_size | Obtém ou define um sinalizador que habilita/desabilita o modo de conversão especial para obter um documento PDF/A com tamanho de arquivo reduzido.<br/>            Agora esse sinalizador impacta a otimização das fontes usadas no documento PDF, possivelmente, no futuro, esse sinalizador <br/>            também será usado para ativar a otimização de outras estruturas de dados, como gráficos.  <br/>            A combinação desse sinalizador e modo pode reduzir significativamente o tamanho do arquivo, mas ao mesmo tempo pode<br/>            diminuir significativamente o desempenho da conversão. |
| exclude_fonts_strategy | Estrategia(s) para excluir fontes supérfluas e reduzir o tamanho do arquivo do documento. <br/>            Este parâmetro só tem sentido quando o sinalizador [optimize_file_size](/pdf/python-net/aspose.pdf/pdfformatconversionoptions/) está definido como verdadeiro.<br/>            Por padrão, a combinação das estratégias [None](/pdf/python-net/aspose.pdf/pdfformatconversionoptions/) e<br/>            [None](/pdf/python-net/aspose.pdf/pdfformatconversionoptions/) é usada. |
| font_embedding_options | Opções para casos em que não é possível incorporar algumas fontes ao documento PDF. |
| unicode_processing_rules | Regras para resolver problemas de mapeamento Unicode. Pode ser nulo. |
| icc_profile_file_name | Obtém ou define o nome de arquivo do perfil ICC. Caso seja nulo, o perfil ICC padrão será usado. |
| not_accessible_fonts | Esta propriedade é out-property. Ela contém todas as fontes (nomes das fontes) que não foram encontradas no computador <br/>            na última conversão PDF/A. |
| is_transfer_info | Obtém ou define se os dados de Info devem ser transferidos para Metadata ao converter para PDF 2.0. Verdadeiro por padrão. |
| align_strategy | Estratégia para alinhar texto. Este parâmetro só tem sentido quando o sinalizador [align_text](/pdf/python-net/aspose.pdf/pdfformatconversionoptions/) está definido como verdadeiro. |

### Veja Também

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

