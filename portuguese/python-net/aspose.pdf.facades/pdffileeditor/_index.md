---
title: "PdfFileEditor"
second_title: "Aspose.PDF para Python via .NET Referência da API"
description: "Implementa operações de concatenação, divisão, extração de páginas e criação de folheto de arquivos PDF, etc."
type: docs
weight: 220
url: /pt/python-net/aspose.pdf.facades/pdffileeditor/
---

## PdfFileEditor class

Implementa operações com arquivos PDF: concatenação, divisão, extração de páginas, criação de livreto, etc.

O tipo PdfFileEditor expõe os seguintes membros:
## Construtores
| Nome | Descrição |
| :- | :- |
| PdfFileEditor() | Inicializa uma nova instância da classe PdfFileEditor |
## Propriedades
| Nome | Descrição |
| :- | :- |
| conversion_log | Obtém o registro do processo de conversão. |
| merge_duplicate_layers | O conteúdo opcional dos documentos concatenados com nomes iguais será mesclado em uma única camada no documento resultante se esta propriedade for verdadeira. <br/>            Caso contrário, camadas com nomes iguais serão salvas como camadas diferentes no documento resultante. |
| copy_outlines | Se verdadeiro, os contornos serão copiados. |
| copy_logical_structure | Se verdadeiro, a estrutura lógica do arquivo será copiada quando a concatenação for realizada. |
| merge_duplicate_outlines | Se verdadeiro, contornos duplicados são mesclados. |
| preserve_user_rights | Se verdadeiro, os direitos de usuário do primeiro documento são aplicados ao documento concatenado. Os direitos de usuário de todos os demais documentos são ignorados. |
| incremental_updates | Se verdadeiro, atualizações incrementais são feitas durante a concatenação. |
| optimize_size | Obtém ou define a bandeira de otimização. Fluxos de recursos iguais no arquivo resultante são mesclados em um único objeto PDF se esta bandeira estiver definida. <br/>            Isso permite diminuir o tamanho do arquivo resultante, mas pode causar execução mais lenta e maiores requisitos de memória.<br/>            Valor padrão: false. |
| corrupted_items | Array de problemas encontrados quando a concatenação foi realizada. Para cada documento corrompido passado para Concatenate() <br/>            é criada uma nova entrada CorruptedItem.<br/>            Esta propriedade pode ser usada somente quando CorruptedFileAction é ConcatenateIgnoringCorrupted. |
| corrupted_file_action | Esta propriedade define o comportamento quando o processo de concatenação encontra um arquivo corrompido.<br/>            Os valores possíveis são: StopWithError e ConcatenateIgnoringCorrupted. |
| owner_password | Define a senha do proprietário se o arquivo Pdf de entrada de origem estiver criptografado.<br/>            Esta propriedade ainda não foi implementada. |
| allow_concatenate_exceptions | Se definido como true, exceções são lançadas se ocorrer um erro. Caso contrário, exceções não são lançadas e os métodos retornam false se falharem. |
| close_concatenated_streams | Se definido como true, os streams são fechados após a operação. |
| unique_suffix | Formato do sufixo que é adicionado ao nome do campo para torná-lo único quando os formulários são concatenados.<br/>            Esta string deve conter a substring %NUM% que será substituída por números.<br/>            Por exemplo, se UniqueSuffix = "ABC%NUM%" então, para o campo "fieldName", os nomes serão:<br/>            fieldNameABC1, fieldNameABC2, fieldNameABC3 etc. |
| keep_actions | Se true, as ações serão copiadas dos documentos de origem. Valor padrão: true. |
| keep_fields_unique | Se true, os nomes dos campos serão tornados únicos quando os formulários forem concatenados.<br/>            Sufixos serão adicionados aos nomes dos campos, o modelo de sufixo pode ser especificado na propriedade UniqueSuffix. |
| remove_signatures | Se true, todas as assinaturas serão removidas dos campos (os campos permanecerão); caso contrário, você pode obter assinaturas inválidas. |
| use_disk_buffer | Se esta opção for usada, o documento de destino será salvo periodicamente em disco e concatenações subsequentes serão aplicadas a ele como atualizações incrementais. |
| concatenation_packet_size | Número de documentos concatenados antes de uma nova atualização incremental ser feita durante a concatenação quando UseDiskBuffer está definido como true. |
## Métodos
| Nome | Descrição |
| :- | :- |
| try_concatenate(first_input_file, sec_input_file, output_file) | Concatena dois arquivos. |
| try_concatenate(src, dest) | Concatena documentos. |
| try_concatenate(input_files, output_file) | Concatena arquivos em um único arquivo. |
| try_concatenate(input_stream, output_stream) | Concatena arquivos |
| try_concatenate(first_input_file, sec_input_file, blank_page_file, output_file) | Concatena dois arquivos. |
| try_concatenate(first_input_stream, sec_input_stream, blank_page_stream, output_stream) | Concatena arquivos |
| try_append(input_stream, port_streams, start_page, end_page, output_stream) | Anexa páginas, que são escolhidas a partir de um array de documentos em portStreams.<br/>            O documento resultante inclui firstInputFile e todas as páginas dos documentos portStreams no intervalo startPage até endPage. |
| try_append(input_file, port_files, start_page, end_page, output_file) | Anexa páginas, que são escolhidas dos documentos portFiles. <br/>            O documento resultante inclui firstInputFile e todas as páginas dos documentos portFiles no intervalo startPage até endPage. |
| try_insert(input_file, insert_location, port_file, page_number, output_file) | Insere páginas de outro arquivo no arquivo Pdf de entrada. |
| try_insert(input_stream, insert_location, port_stream, page_number, output_stream) | Insere páginas de outro arquivo no arquivo Pdf de entrada. |
| try_delete(input_file, page_number, output_file) | Exclui páginas especificadas por um array de números do arquivo de entrada, salva como um novo arquivo Pdf. |
| try_delete(input_stream, page_number, output_stream) | Exclui páginas especificadas por um array de números do arquivo de entrada, salva como um novo arquivo Pdf. |
| try_extract(input_file, start_page, end_page, output_file) | Extrai páginas do arquivo de entrada, salva como um novo arquivo Pdf. |
| try_extract(input_file, page_number, output_file) | Extrai páginas especificadas por um array de números, salva como um novo arquivo PDF. |
| try_extract(input_stream, page_number, output_stream) | Extrai páginas especificadas por um array de números, salva como um novo arquivo Pdf. |
| try_split_from_first(input_file, location, output_file) | Divide o arquivo Pdf da primeira página até o local especificado, e salva a parte frontal como um novo arquivo. |
| try_split_from_first(input_stream, location, output_stream) | Divide do início até o local especificado, e salva a parte frontal no Stream de saída. |
| try_split_to_end(input_file, location, output_file) | Divide a partir do local, e salva a parte traseira como um novo arquivo. |
| try_split_to_end(input_stream, location, output_stream) | Divide a partir da localização especificada e salva a parte posterior como um novo Stream de arquivo. |
| try_make_booklet(input_file, output_file) | Cria um livreto a partir do arquivo de entrada para o arquivo de saída. |
| try_make_booklet(input_stream, output_stream) | Cria um livreto a partir do InputStream para o outputStream. |
| try_make_booklet(input_file, output_file, page_size) | Cria um livreto a partir do inputFile para o outputFile. |
| try_make_booklet(input_stream, output_stream, page_size) | Cria um livreto a partir do fluxo de entrada e salva o resultado no fluxo de saída. |
| try_make_booklet(input_file, output_file, left_pages, right_pages) | Cria um livreto personalizado a partir do firstInputFile para o outputFile. |
| try_make_booklet(input_stream, output_stream, left_pages, right_pages) | Cria um livreto personalizado a partir do firstInputStream para o outputStream. |
| try_make_booklet(input_file, output_file, page_size, left_pages, right_pages) | Cria um livreto personalizado a partir do firstInputFile para o outputFile. |
| try_make_booklet(input_stream, output_stream, page_size, left_pages, right_pages) | Cria um livreto a partir do firstInputStream para o outputStream. |
| try_make_n_up(input_file, output_file, x, y) | Cria um documento N-Up a partir do firstInputFile para o outputFile. |
| try_make_n_up(input_stream, output_stream, x, y) | Cria um documento N-Up a partir do fluxo de entrada e salva o resultado no fluxo de saída. |
| try_make_n_up(input_stream, output_stream, x, y, page_size) | Cria um documento N-Up a partir do primeiro fluxo de entrada para o fluxo de saída. |
| try_make_n_up(first_input_file, second_input_file, output_file) | Cria um documento N-Up a partir do firstInputFile para o outputFile. |
| try_make_n_up(first_input_stream, second_input_stream, output_stream) | Cria um documento N-Up a partir do fluxo de entrada e salva o resultado no fluxo de saída. |
| try_make_n_up(input_files, output_file, is_sidewise) | Cria um documento N-Up a partir de vários arquivos PDF de entrada para outputFile. <br/> Cada página de outputFile conterá múltiplas páginas, que são combinadas com as páginas <br/> nos arquivos de entrada do mesmo número de página. As múltiplas páginas são empilhadas horizontalmente <br/> se isSidewise for verdadeiro e empilhadas verticalmente se isSidewise for falso. |
| try_make_n_up(input_streams, output_stream, is_sidewise) | Cria um documento N-Up a partir de vários fluxos PDF de entrada para outputStream.<br/> Cada página de outputStream conterá múltiplas páginas, que são combinadas com as páginas <br/> nos fluxos de entrada do mesmo número de página. As múltiplas páginas são empilhadas horizontalmente <br/> se isSidewise for verdadeiro e empilhadas verticalmente se isSidewise for falso. |
| try_make_n_up(input_file, output_file, x, y, page_size) | Cria um documento N-Up a partir do arquivo de entrada para outputFile. |
| try_resize_contents(source, destination, pages, parameters) | Redimensiona o conteúdo das páginas do documento. |
| try_resize_contents(source, destination, pages, new_width, new_height) | Redimensiona o conteúdo das páginas do documento. <br/> Reduz o conteúdo da página e adiciona margens.<br/> O novo tamanho do conteúdo é especificado nas unidades de espaço padrão. |
| try_resize_contents(source, destination, pages, parameters) | Redimensiona o conteúdo das páginas no documento. Se a página for reduzida, margens em branco são adicionadas ao redor da página. |
| concatenate(first_input_file, sec_input_file, output_file) | Concatena arquivos e salva o resultado no objeto HttpResposnse. |
| concatenate(first_input_stream, sec_input_stream, output_stream) | Concatena arquivos e armazena o resultado no objeto HttpResponse. |
| concatenate(src, dest) | Concatena documentos. |
| concatenate(input_files, output_file) | Concatena arquivos e salva o resultado no objeto HttpResposnse. |
| concatenate(input_stream, output_stream) | Concatena arquivos e armazena o resultado no objeto HttpResponse. |
| concatenate(first_input_file, sec_input_file, blank_page_file, output_file) | Concatena arquivos e salva o resultado no objeto HttpResposnse. |
| concatenate(first_input_stream, sec_input_stream, blank_page_stream, output_stream) | Concatena arquivos e armazena o resultado no objeto HttpResponse. |
| append(input_stream, port_streams, start_page, end_page, output_stream) | Anexa documentos ao documento de origem e salva o resultado no objeto response. |
| append(input_file, port_files, start_page, end_page, output_file) | Anexa documentos ao documento de origem e salva o resultado no objeto HttpResponse. |
| append(input_file, port_file, start_page, end_page, output_file) | Anexa documentos ao documento de origem e salva o resultado no objeto HttpResponse. |
| append(input_stream, port_stream, start_page, end_page, output_stream) | Anexa documentos ao documento de origem e salva o resultado no objeto response. |
| insert(input_file, insert_location, port_file, start_page, end_page, output_file) | Insere o conteúdo do arquivo no arquivo de origem e armazena o resultado no objeto HttpResponse. |
| insert(input_stream, insert_location, port_stream, start_page, end_page, output_stream) | Insere o documento em outro documento e armazena o resultado no objeto de resposta. |
| insert(input_file, insert_location, port_file, page_number, output_file) | Insere o conteúdo do arquivo no arquivo de origem e armazena o resultado no objeto HttpResponse. |
| insert(input_stream, insert_location, port_stream, page_number, output_stream) | Insere o documento em outro documento e armazena o resultado no objeto de resposta. |
| delete(input_file, page_number, output_file) | Exclui as páginas especificadas do documento e armazena o resultado no objeto HttpResponse. |
| delete(input_stream, page_number, output_stream) | Exclui as páginas especificadas do documento e salva o resultado no objeto HttpResponse. |
| extract(input_file, start_page, end_page, output_file) | Extrai as páginas especificadas do arquivo de origem e armazena o resultado no objeto HttpResponse. |
| extract(input_file, page_number, output_file) | Extrai as páginas especificadas do arquivo de origem e armazena o resultado no objeto HttpResponse. |
| extract(input_stream, start_page, end_page, output_stream) | Extrai as páginas especificadas do arquivo de origem e armazena o resultado no objeto HttpResponse. |
| extract(input_stream, page_number, output_stream) | Extrai as páginas especificadas do arquivo de origem e armazena o resultado no objeto HttpResponse. |
| split_from_first(input_file, location, output_file) | Divide o documento da primeira página até a localização e salva o resultado em objetos HttpResponse. |
| split_from_first(input_stream, location, output_stream) | Divide o documento do início até a localização especificada e armazena o resultado no objeto HttpResponse. |
| split_to_end(input_file, location, output_file) | Divide a partir da localização especificada e salva a parte posterior no objeto HttpResponse. |
| split_to_end(input_stream, location, output_stream) | Divide a partir da localização especificada e salva a parte posterior no objeto HttpResponse. |
| make_booklet(input_file, output_file) | Cria um livreto a partir do arquivo de origem e armazena o resultado em objetos HttpResponse. |
| make_booklet(input_stream, output_stream) | Cria folheto a partir de arquivo PDF e o armazena em HttpResponse. |
| make_booklet(input_file, output_file, page_size) | Cria um livreto a partir do arquivo de origem e armazena o resultado em objetos HttpResponse. |
| make_booklet(input_stream, output_stream, page_size) | Cria folheto a partir de arquivo PDF e o armazena em HttpResponse. |
| make_booklet(input_file, output_file, left_pages, right_pages) | Cria um livreto a partir do arquivo de origem e armazena o resultado em objetos HttpResponse. |
| make_booklet(input_stream, output_stream, left_pages, right_pages) | Cria folheto a partir de arquivo PDF e o armazena em HttpResponse. |
| make_booklet(input_file, output_file, page_size, left_pages, right_pages) | Cria um livreto a partir do arquivo de origem e armazena o resultado em objetos HttpResponse. |
| make_booklet(input_stream, output_stream, page_size, left_pages, right_pages) | Cria folheto a partir de arquivo PDF e o armazena em HttpResponse. |
| make_n_up(input_file, output_file, x, y) | Cria documento N-up e armazena o resultado no objeto HttpResponse. |
| make_n_up(input_stream, output_stream, x, y) | Cria documento N-up e armazena o resultado no objeto HttpResponse. |
| make_n_up(input_stream, output_stream, x, y, page_size) | Cria documento N-up e armazena o resultado no objeto HttpResponse. |
| make_n_up(first_input_file, second_input_file, output_file) | Cria documento N-up e armazena o resultado no objeto HttpResponse. |
| make_n_up(first_input_stream, second_input_stream, output_stream) | Cria documento N-up e armazena o resultado no objeto HttpResponse. |
| make_n_up(input_files, output_file, is_sidewise) | Cria um documento N-Up a partir de vários arquivos PDF de entrada para outputFile. <br/> Cada página de outputFile conterá múltiplas páginas, que são combinadas com as páginas <br/> nos arquivos de entrada do mesmo número de página. As múltiplas páginas são empilhadas horizontalmente <br/> se isSidewise for verdadeiro e empilhadas verticalmente se isSidewise for falso. |
| make_n_up(input_streams, output_stream, is_sidewise) | Cria um documento N-Up a partir de vários fluxos PDF de entrada para outputStream.<br/> Cada página de outputStream conterá múltiplas páginas, que são combinadas com as páginas <br/> nos fluxos de entrada do mesmo número de página. As múltiplas páginas são empilhadas horizontalmente <br/> se isSidewise for verdadeiro e empilhadas verticalmente se isSidewise for falso. |
| make_n_up(input_file, output_file, x, y, page_size) | Cria documento N-up e armazena o resultado no objeto HttpResponse. |
| split_to_pages(input_file, file_name_template) | Divide o arquivo PDF em documentos de página única. |
| split_to_pages(input_stream, file_name_template) | Divide o arquivo Pdf em documentos de página única e o salva no caminho especificado. O caminho é definido pelo modelo de nome de campo. |
| resize_contents(source, destination, pages, parameters) | Redimensiona o conteúdo das páginas no documento. Se a página for reduzida, margens em branco são adicionadas ao redor da página. O resultado é armazenado no objeto HttpResponse. |
| resize_contents(source, destination, pages, new_width, new_height) | Redimensiona o conteúdo das páginas do documento. <br/> Reduz o conteúdo da página e adiciona margens.<br/> O novo tamanho do conteúdo é especificado nas unidades de espaço padrão. |
| resize_contents(source, destination, pages, new_width, new_height) | Redimensiona o conteúdo das páginas do documento. <br/> Reduz o conteúdo da página e adiciona margens.<br/> O novo tamanho do conteúdo é especificado nas unidades de espaço padrão. |
| resize_contents(source, destination, pages, parameters) | Redimensiona o conteúdo das páginas no documento. Se a página for reduzida, margens em branco são adicionadas ao redor da página. O resultado é armazenado no objeto HttpResponse. |
| resize_contents(source, pages, parameters) | Redimensiona as páginas do documento. Margens em branco são adicionadas ao redor da página reduzida. |
| resize_contents(source, parameters) | Redimensiona as páginas do documento. Margens em branco são adicionadas ao redor da página reduzida. |
| resize_contents_pct(source, destination, pages, new_width, new_height) | Redimensiona o conteúdo das páginas do documento.<br/>            Reduz o conteúdo da página e adiciona margens.<br/>            O novo tamanho do conteúdo é especificado em porcentagens. |
| resize_contents_pct(source, destination, pages, new_width, new_height) | Redimensiona o conteúdo das páginas do documento.<br/>            Reduz o conteúdo da página e adiciona margens.<br/>            O novo tamanho do conteúdo é especificado em porcentagens. |
| add_margins(source, destination, pages, left_margin, right_margin, top_margin, bottom_margin) | Redimensiona o conteúdo da página e adiciona margens especificadas. <br/>            As margens são especificadas nas unidades de espaço padrão. |
| add_margins(source, destination, pages, left_margin, right_margin, top_margin, bottom_margin) | Redimensiona o conteúdo da página e adiciona margens especificadas. <br/>            As margens são especificadas nas unidades de espaço padrão. |
| add_margins_pct(source, destination, pages, left_margin, right_margin, top_margin, bottom_margin) | Redimensiona o conteúdo da página e adiciona margens especificadas.<br/>            As margens são especificadas em porcentagens do tamanho inicial da página. |
| add_margins_pct(source, destination, pages, left_margin, right_margin, top_margin, bottom_margin) | Redimensiona o conteúdo da página e adiciona margens especificadas.<br/>            As margens são especificadas em porcentagens do tamanho inicial da página. |
| add_page_break(src, dest, page_breaks) | Adiciona quebras de página nas páginas do documento. |
| add_page_break(src, dest, page_breaks) | Adiciona quebras de página nas páginas do documento. |
| add_page_break(src, dest, page_breaks) | Adiciona quebras de página nas páginas do documento. |

### Veja Também

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

