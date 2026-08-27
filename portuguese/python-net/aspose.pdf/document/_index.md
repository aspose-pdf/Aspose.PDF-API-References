---
title: "Document"
second_title: "Aspose.PDF para Python via .NET Referência da API"
description: "Classe que representa documento PDF"
type: docs
weight: 230
url: /pt/python-net/aspose.pdf/document/
---

## Document class

Classe que representa documento PDF

O tipo Document expõe os seguintes membros:
## Construtores
| Nome | Descrição |
| :- | :- |
| Document(input) | Inicializa uma nova instância da classe Document |
| Document(input, password, is_managed_stream) | Inicializa uma nova instância da classe Document |
| Document(input, is_managed_stream) | Inicializa uma nova instância da classe Document |
| Document(filename) | Inicializa uma nova instância da classe Document |
| Document(input, password) | Inicializa uma nova instância da classe Document |
| Document() | Inicializa um documento vazio. |
| Document(filename, options) | Inicializa uma nova instância da classe Document |
| Document(input, options) | Inicializa uma nova instância da classe Document |
| Document(filename, password) | Inicializa uma nova instância da classe Document |
| Document(filename, password, is_managed_stream) | Inicializa uma nova instância da classe Document |
## Propriedades
| Nome | Descrição |
| :- | :- |
| java_script | Coleção de JavaScript de nível de documento. |
| is_licensed | Obtém o estado licenciado do sistema. Retorna true se o sistema estiver em modo licenciado e false caso contrário. |
| page_info | Obtém ou define as informações da página.(apenas para gerador, não preenchido ao ler o documento) |
| enable_signature_sanitization | Obtém ou define a bandeira para gerenciar a sanitização de campos de assinatura. Habilitado por padrão. |
| is_pdfa_compliant | Obtém se o documento está em conformidade PDF/A. |
| is_pdf_ua_compliant | Obtém se o documento está em conformidade PDF/UA. |
| is_xref_gaps_allowed | Obtém ou define se o documento está em conformidade PDF/A. |
| named_destinations | Coleção de Destinos Nomeados no documento. |
| destinations | Obtém a coleção de destinos.<br/>            Obsoleto. Por favor, use NamedDestinations. |
| pdf_format | Obtém o formato PDF |
| embed_standard_fonts | Propriedade que declara que o documento deve incorporar todas as fontes Type1 padrão <br/>            que têm a bandeira IsEmbedded definida como true. Todas as fontes PDF podem ser incorporadas <br/>            no documento simplesmente definindo a bandeira IsEmbedded como true, mas as fontes Type1 padrão do PDF são uma exceção a essa regra.<br/>            Incorporar fontes Type1 padrão requer muito tempo, portanto, para incorporar essas fontes é necessário<br/>            não apenas definir a bandeira IsEmbedded como true para a fonte especificada, mas também definir <br/>            uma bandeira adicional no nível do documento - EmbedStandardFonts = true;<br/>            Esta propriedade pode ser definida apenas uma vez para todas as fontes.<br/>            Por padrão, false. |
| disable_font_license_verifications | Muitas operações com fontes não podem ser executadas se essas operações forem proibidas pela licença desta fonte. <br/>            Por exemplo, algumas fontes não podem ser incorporadas em um documento PDF se as regras de licença desabilitarem a incorporação para essa fonte. <br/>            Esta bandeira é usada para desabilitar quaisquer restrições de licença para todas as fontes no documento PDF atual.<br/>            Tenha cuidado ao usar esta bandeira. Quando ela está definida, significa que a pessoa que a define, <br/>            assume toda a responsabilidade por possíveis violações de licença/lei sobre si mesma. <br/>            Portanto, ele assume por seu próprio risco. <br/>            É altamente recomendável usar esta bandeira somente quando você estiver totalmente confiante de que não está infringindo <br/>            a lei de direitos autorais. <br/>            Por padrão, false. |
| font_utilities | Instância de IDocumentFontUtilities |
| collection | Obtém a coleção do documento. |
| version | Obtém uma versão do PDF a partir do cabeçalho do arquivo PDF. |
| open_action | Obtém ou define a ação executada na abertura do documento. |
| hide_tool_bar | Obtém ou define a bandeira que especifica se a barra de ferramentas deve ser ocultada quando o documento está ativo. |
| hide_menubar | Obtém ou define a bandeira que especifica se a barra de menu deve ser ocultada quando o documento está ativo. |
| hide_window_ui | Obtém ou define a bandeira que especifica se os elementos da interface do usuário devem ser ocultados quando o documento está ativo. |
| fit_window | Obtém ou define a bandeira que especifica se a janela do documento deve ser redimensionada para caber na primeira página exibida. |
| center_window | Obtém ou define a bandeira que especifica se a posição da janela do documento será centralizada na tela. |
| display_doc_title | Obtém ou define a bandeira que especifica se a barra de título da janela do documento deve exibir o título do documento. |
| páginas | Obtém ou define a coleção de páginas do documento.<br/>            Observe que as páginas são numeradas a partir de 1 na coleção. |
| outlines | Obtém os esboços do documento. |
| ações | Obtém as ações do documento. Esta propriedade é uma instância da classe DocumentActions que permite obter/definir as ações BeforClosing, BeforSaving, etc. |
| formulário | Obtém o Acro Form do documento. |
| embedded_files | Obtém a coleção de arquivos incorporados ao documento. |
| direction | Obtém ou define a ordem de leitura do texto: L2R (da esquerda para a direita) ou R2L (da direita para a esquerda). |
| page_mode | Obtém ou define o modo de página, especificando como o documento deve ser exibido ao ser aberto. |
| non_full_screen_page_mode | Obtém ou define o modo de página, especificando como exibir o documento ao sair do modo de tela cheia. |
| page_layout | Obtém ou define o layout de página que deve ser usado quando o documento for aberto. |
| duplex | Obtém ou define a opção de manipulação do modo duplex de impressão a ser usada ao imprimir o arquivo a partir da caixa de diálogo de impressão. |
| file_name | Nome do arquivo PDF que causou este documento |
| info | Obtém informações do documento. |
| metadata | Metadados do documento.<br/> (Um documento PDF pode incluir informações gerais,<br/> como o título do documento, autor, e datas de criação e modificação.<br/> Essas informações globais sobre o documento (em oposição ao seu conteúdo ou estrutura) são chamadas de metadados<br/> e destinam‑se a auxiliar na catalogação e busca de documentos em bancos de dados externos.) |
| logical_structure | Obtém a estrutura lógica do documento. |
| handle_signature_change | Lança exceção se o documento for salvo com alterações e possuir assinatura |
| crypto_algorithm | Obtém configurações de segurança se o documento estiver criptografado. <br/> Se o documento não estiver criptografado, então a exceção correspondente será lançada no .net 1.1<br/> ou CryptoAlgorithm será nulo para outras versões do .net. |
| is_linearized | Obtém ou define um valor que indica se o documento está linearizado. |
| permissions | Obtém as permissões do documento. |
| is_encrypted | Obtém o status de criptografia do documento. Verdadeiro se o documento estiver criptografado. |
| id | Obtém o ID. |
| background | Obtém ou define a cor de fundo do documento. |
| optimize_size | Obtém ou define a bandeira de otimização. Quando páginas são adicionadas ao documento, fluxos de recursos iguais no arquivo resultante são<br/> mesclados em um único objeto PDF se esta bandeira estiver definida. <br/> Isso permite diminuir o tamanho do arquivo resultante, mas pode causar execução mais lenta e maiores requisitos de memória.<br/> Valor padrão: false. |
| allow_reuse_page_content | Permite mesclar o conteúdo das páginas para otimizar o tamanho do documento. Se usado, então páginas diferentes mas duplicadas podem referenciar o <br/>            mesmo objeto de conteúdo. Observe que este modo pode causar efeitos colaterais, como alterar o conteúdo da página quando outra página é alterada. |
| ignore_corrupted_objects | Obtém ou define a bandeira de ignorar erros nos arquivos de origem. <br/>            Quando páginas do documento de origem são copiadas para o documento de destino, o processo de cópia é interrompido com exceção <br/>            se alguns objetos nos arquivos de origem estiverem corrompidos quando esta bandeira for falsa. <br/>            exemplo: dest.Pages.Add(src.Pages);<br/>            Se esta bandeira for definida como true, os objetos corrompidos serão substituídos por valores vazios.<br/>            Por padrão: true. |
| page_labels | Obtém os rótulos de página no documento. |
| enable_object_unload | Obtém ou define a bandeira que permite que o documento seja parcialmente descarregado da memória. <br/>            Isso permite reduzir o uso de memória, mas pode ter efeito negativo no desempenho. |
| tagged_content | Obtém acesso ao conteúdo TaggedPdf. |
## Métodos
| Nome | Descrição |
| :- | :- |
| save(output) | Armazena o documento em um fluxo. |
| save(output_file_name) | Salva o documento no arquivo especificado. |
| save() | Armazena o documento em um fluxo. |
| save(options) | Salva o documento com opções de salvamento. |
| save(output_file_name, format) | Salva o documento com um novo nome juntamente com um formato de arquivo. |
| save(output_stream, format) | Salva o documento com um novo nome juntamente com um formato de arquivo. |
| save(output_file_name, options) | Salva o documento com um novo nome definindo suas opções de salvamento. |
| save(output_stream, options) | Salva o documento em um fluxo com opções de salvamento. |
| export_annotations_to_xfdf(file_name) | Exporta todas as anotações do documento para um arquivo XFDF |
| export_annotations_to_xfdf(stream) | Exportar todas as anotações do documento para o fluxo. |
| send_to(device, output) | Envia todo o documento para o dispositivo de documento para processamento. |
| send_to(device, from_page, to_page, output) | Envia as páginas específicas do documento para o dispositivo de documento para processamento. |
| send_to(device, output_file_name) | Envia todo o documento para o dispositivo de documento para processamento. |
| send_to(device, from_page, to_page, output_file_name) | Envia todo o documento para o dispositivo de documento para processamento. |
| import_annotations_from_xfdf(file_name) | Importa anotações de arquivo XFDF para o documento. |
| import_annotations_from_xfdf(stream) | Importa anotações do fluxo para o documento. |
| validate(output_log_file_name, format) | Valida o documento no arquivo especificado. |
| validate(output_log_stream, format) | Valida o documento no arquivo especificado. |
| validate(options) | Valida o documento no arquivo especificado. |
| convert(output_log_file_name, format, action, transparency_action) | Converte o documento e salva os erros no arquivo especificado. |
| convert(output_log_stream, format, action, transparency_action) | Converte o documento e salva os erros no arquivo especificado. |
| convert(output_log_file_name, format, action) | Converte o documento e salva os erros no arquivo especificado. |
| convert(options) | Converte o documento usando opções de conversão especificadas |
| convert(output_log_stream, format, action) | Converte o documento e salva os erros no arquivo especificado. |
| convert(fixup, output_log, only_validation, parameters) | Converte o documento aplicando o Fixup. |
| convert(fixup, output_log, only_validation, parameters) | Converte o documento aplicando o Fixup. |
| convert(src_file_name, load_options, dst_file_name, save_options) | Converte o arquivo de origem no formato de origem em arquivo de destino no formato de destino. |
| convert(src_stream, load_options, dst_file_name, save_options) | Converte o fluxo no formato de origem em arquivo de destino no formato de destino. |
| convert(src_file_name, load_options, dst_stream, save_options) | Converte o fluxo no formato de origem em arquivo de destino no formato de destino. |
| convert(src_stream, load_options, dst_stream, save_options) | Converte o fluxo no formato de origem em arquivo de destino no formato de destino. |
| flatten() | Remove todos os campos do documento e coloca seus valores no lugar. |
| flatten(flatten_settings) | Remove todos os campos do documento e coloca seus valores no lugar. |
| encrypt(user_password, owner_password, privileges, crypto_algorithm, use_pdf20) | Criptografa o documento. Chame então Save para obter a versão criptografada do documento. |
| encrypt(user_password, owner_password, permissions, crypto_algorithm) | Criptografa o documento. Chame então Save para obter a versão criptografada do documento. |
| encrypt(user_password, owner_password, permissions, crypto_algorithm, use_pdf20) | Criptografa o documento. Chame então Save para obter a versão criptografada do documento. |
| optimize_resources() | Otimiza recursos no documento:<br/>            1. Recursos que não são usados nas páginas do documento são removidos;<br/>            2. Recursos iguais são unidos em um único objeto; <br/>            3. Objetos não utilizados são excluídos. |
| optimize_resources(strategy) | Otimiza recursos no documento de acordo com a estratégia de otimização definida. |
| bind_xml(file) | Vincula xml ao documento |
| bind_xml(xml_file, xsl_file) | Vincula xml ao documento |
| bind_xml(xml_stream, xsl_stream) | Vincula xml/xsl ao documento |
| bind_xml(stream) | Vincula xml/xsl ao documento |
| remove_pdfa_compliance() | Remove a conformidade pdfa do documento |
| remove_pdf_ua_compliance() | Remove a conformidade pdfUa do documento |
| set_title(title) | Definir título para documento PDF |
| process_paragraphs() | Processar parágrafos para o gerador. |
| remove_metadata() | Remove metadados do documento. |
| change_passwords(owner_password, new_user_password, new_owner_password) | Altera senhas do documento. Esta ação só pode ser feita usando a senha do proprietário. |
| decrypt() | Descriptografa o documento. Chame então Save para obter a versão descriptografada do documento. |
| optimize() | Linearizar documento para<br/>            - abrir a primeira página o mais rápido possível;<br/>            - exibir a página seguinte ou seguir o link para a próxima página o mais rápido possível;<br/>            - exibir a página incrementalmente à medida que chega, quando os dados de uma página são entregues por um canal lento (exibir primeiro os dados mais úteis);<br/>            - permitir que a interação do usuário, como seguir um link, seja realizada mesmo antes que a página inteira tenha sido recebida e exibida.<br/>            Invocar este método não salva realmente o documento. Pelo contrário, o documento apenas é preparado para ter uma estrutura otimizada,<br/>            chame então Save para obter o documento otimizado. |
| get_catalog_value(key) | Retorna o valor do item do dicionário de catálogo. |
| free_memory() | Limpa a memória |
| save_xml(file) | Salvar documento em XML. |
| get_object_by_id(id) | Obtém um objeto com ID especificado no documento. |
| repair() | Repara documento corrompido. |
| get_xmp_metadata(stream) | Obter metadados XMP do documento. |
| set_xmp_metadata(stream) | Definir metadados XMP do documento. |
| check(do_repair) | Valida o documento. |
| page_nodes_to_balanced_tree(nodes_num_in_subtrees) | Organiza os nós da árvore de páginas em um documento em uma árvore balanceada.<br/>            Apenas se o documento tiver mais de nodesNumInSubtrees objetos de página, caso contrário não faz nada. |

### Veja Também

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

