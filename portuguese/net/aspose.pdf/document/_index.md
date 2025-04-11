---
title: Class Document
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Document. Classe que representa o documento PDF
type: docs
weight: 3780
url: /pt/net/aspose.pdf/document/
---
## Classe Documento

Classe que representa o documento PDF.

```csharp
public sealed class Document : IDisposable
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [Document](document/#constructor)() | Inicializa um documento vazio. |
| [Document](document/#constructor_1)(PdfVersion) | Inicializa um documento vazio por versão. |
| [Document](document/#constructor_2)(Stream) | Inicializa uma nova instância de Document a partir do *stream* de entrada. |
| [Document](document/#constructor_7)(string) | Apenas inicializa Document usando *nome do arquivo*. O mesmo que [`Document`](./document/). |
| [Document](document/#constructor_4)(Stream, bool) | Inicializa uma nova instância de Document a partir do *stream* de entrada. |
| [Document](document/#constructor_3)(Stream, LoadOptions) | Abre um documento existente a partir de um stream fornecendo a conversão necessária para obter o documento PDF. |
| [Document](document/#constructor_5)(Stream, string) | Inicializa uma nova instância de Document a partir do *stream* de entrada. |
| [Document](document/#constructor_9)(string, bool) | Apenas inicializa Document usando *nome do arquivo*. O mesmo que [`Document`](./document/). |
| [Document](document/#constructor_8)(string, LoadOptions) | Abre um documento existente a partir de um arquivo fornecendo as opções de conversão necessárias para obter o documento PDF. |
| [Document](document/#constructor_10)(string, string) | Inicializa uma nova instância da classe `Document` para trabalhar com documentos criptografados. |
| [Document](document/#constructor_6)(Stream, string, bool) | Inicializa uma nova instância de Document a partir do *stream* de entrada. |
| [Document](document/#constructor_11)(string, string, bool) | Inicializa uma nova instância da classe `Document` para trabalhar com documentos criptografados. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [Actions](../../aspose.pdf/document/actions/) { get; } | Obtém as ações do documento. Esta propriedade é uma instância da classe DocumentActions que permite obter definir ações BeforClosing, BeforSaving, etc. |
| [AllowReusePageContent](../../aspose.pdf/document/allowreusepagecontent/) { get; set; } | Permite mesclar conteúdos de página para otimizar o tamanho do documento. Se usado, páginas diferentes, mas duplicadas, podem referenciar o mesmo objeto de conteúdo. Observe que este modo pode causar efeitos colaterais, como a alteração do conteúdo da página quando outra página é alterada. |
| [Background](../../aspose.pdf/document/background/) { get; set; } | Obtém ou define a cor de fundo do documento. |
| [CenterWindow](../../aspose.pdf/document/centerwindow/) { get; set; } | Obtém ou define a flag que especifica se a posição da janela do documento será centralizada na tela. |
| [Collection](../../aspose.pdf/document/collection/) { get; set; } | Obtém a coleção do documento. |
| [CryptoAlgorithm](../../aspose.pdf/document/cryptoalgorithm/) { get; } | Obtém as configurações de segurança se o documento estiver criptografado. Se o documento não estiver criptografado, uma exceção correspondente será levantada no .net 1.1 ou CryptoAlgorithm será nulo para outras versões do .net. |
| [Destinations](../../aspose.pdf/document/destinations/) { get; } | Obtém a coleção de destinos. Obsoleto. Por favor, use NamedDestinations. |
| [Direction](../../aspose.pdf/document/direction/) { get; set; } | Obtém ou define a ordem de leitura do texto: L2R (da esquerda para a direita) ou R2L (da direita para a esquerda). |
| [DisableFontLicenseVerifications](../../aspose.pdf/document/disablefontlicenseverifications/) { get; set; } | Muitas operações com fontes não podem ser executadas se essas operações forem proibidas pela licença dessa fonte. Por exemplo, algumas fontes não podem ser incorporadas em documentos PDF se as regras de licença desativarem a incorporação para essa fonte. Esta flag é usada para desativar quaisquer restrições de licença para todas as fontes no documento PDF atual. Tenha cuidado ao usar esta flag. Quando ela é definida, significa que a pessoa que define esta flag assume toda a responsabilidade por possíveis violações de licença/lei. Portanto, ela assume isso por conta própria. É altamente recomendável usar esta flag apenas quando você estiver totalmente confiante de que não está infringindo a lei de direitos autorais. Por padrão, falso. |
| [DisplayDocTitle](../../aspose.pdf/document/displaydoctitle/) { get; set; } | Obtém ou define a flag que especifica se a barra de título da janela do documento deve exibir o título do documento. |
| [Duplex](../../aspose.pdf/document/duplex/) { get; set; } | Obtém ou define a opção de manuseio do modo duplex de impressão a ser usada ao imprimir o arquivo a partir da caixa de diálogo de impressão. |
| [EmbeddedFiles](../../aspose.pdf/document/embeddedfiles/) { get; } | Obtém a coleção de arquivos incorporados ao documento. |
| [EmbedStandardFonts](../../aspose.pdf/document/embedstandardfonts/) { get; set; } | Propriedade que declara que o documento deve incorporar todas as fontes padrão Type1 que têm a flag IsEmbedded definida como verdadeira. Todas as fontes PDF podem ser incorporadas ao documento simplesmente definindo a flag IsEmbedded como verdadeira, mas as fontes padrão Type1 do PDF são uma exceção a essa regra. A incorporação de fontes padrão Type1 requer muito tempo, portanto, para incorporar essas fontes, é necessário não apenas definir a flag IsEmbedded como verdadeira para a fonte especificada, mas também definir uma flag adicional no nível do documento - EmbedStandardFonts = true; Esta propriedade pode ser definida apenas uma vez para todas as fontes. Por padrão, falso. |
| [EnableObjectUnload](../../aspose.pdf/document/enableobjectunload/) { get; set; } | Obtém ou define a flag que permite que o documento seja parcialmente descarregado da memória. Isso permite diminuir o uso de memória, mas pode ter um efeito negativo no desempenho. |
| [EnableSignatureSanitization](../../aspose.pdf/document/enablesignaturesanitization/) { get; set; } | Obtém ou define a flag para gerenciar a sanitização dos campos de assinatura. Habilitado por padrão. |
| [FileName](../../aspose.pdf/document/filename/) { get; } | Nome do arquivo PDF que causou este documento |
| [FitWindow](../../aspose.pdf/document/fitwindow/) { get; set; } | Obtém ou define a flag que especifica se a janela do documento deve ser redimensionada para caber na primeira página exibida. |
| [FontUtilities](../../aspose.pdf/document/fontutilities/) { get; } | Instância de IDocumentFontUtilities |
| [Form](../../aspose.pdf/document/form/) { get; } | Obtém o Acro Form do documento. |
| [HandleSignatureChange](../../aspose.pdf/document/handlesignaturechange/) { get; set; } | Lança uma exceção se o documento for salvo com alterações e tiver assinatura |
| [HideMenubar](../../aspose.pdf/document/hidemenubar/) { get; set; } | Obtém ou define a flag que especifica se a barra de menu deve ser ocultada quando o documento estiver ativo. |
| [HideToolBar](../../aspose.pdf/document/hidetoolbar/) { get; set; } | Obtém ou define a flag que especifica se a barra de ferramentas deve ser ocultada quando o documento estiver ativo. |
| [HideWindowUI](../../aspose.pdf/document/hidewindowui/) { get; set; } | Obtém ou define a flag que especifica se os elementos da interface do usuário devem ser ocultados quando o documento estiver ativo. |
| [Id](../../aspose.pdf/document/id/) { get; } | Obtém o ID. |
| [IgnoreCorruptedObjects](../../aspose.pdf/document/ignorecorruptedobjects/) { get; set; } | Obtém ou define a flag de ignorar erros em arquivos de origem. Quando páginas do documento de origem são copiadas para o documento de destino, o processo de cópia é interrompido com uma exceção se alguns objetos nos arquivos de origem estiverem corrompidos quando esta flag for falsa. exemplo: dest.Pages.Add(src.Pages); Se esta flag for definida como verdadeira, os objetos corrompidos serão substituídos por valores vazios. Por padrão: verdadeiro. |
| [Info](../../aspose.pdf/document/info/) { get; } | Obtém informações do documento. |
| [IsEncrypted](../../aspose.pdf/document/isencrypted/) { get; } | Obtém o status de criptografia do documento. Verdadeiro se o documento estiver criptografado. |
| [IsLinearized](../../aspose.pdf/document/islinearized/) { get; set; } | Obtém ou define um valor que indica se o documento está linearizado. |
| [IsPdfaCompliant](../../aspose.pdf/document/ispdfacompliant/) { get; } | Obtém se o documento é compatível com pdfa. |
| [IsPdfUaCompliant](../../aspose.pdf/document/ispdfuacompliant/) { get; } | Obtém se o documento é compatível com pdfua. |
| [IsXrefGapsAllowed](../../aspose.pdf/document/isxrefgapsallowed/) { get; set; } | Obtém ou define se o documento é compatível com pdfa. |
| [JavaScript](../../aspose.pdf/document/javascript/) { get; } | Coleção de JavaScript do nível do documento. |
| [LogicalStructure](../../aspose.pdf/document/logicalstructure/) { get; } | Obtém a estrutura lógica do documento. |
| [Metadata](../../aspose.pdf/document/metadata/) { get; } | Metadados do documento. (Um documento PDF pode incluir informações gerais, como o título do documento, autor e datas de criação e modificação. Essas informações globais sobre o documento (em oposição ao seu conteúdo ou estrutura) são chamadas de metadados e têm a intenção de ajudar na catalogação e busca de documentos em bancos de dados externos.) |
| [NamedDestinations](../../aspose.pdf/document/nameddestinations/) { get; } | Coleção de Destinos Nomeados no documento. |
| [NonFullScreenPageMode](../../aspose.pdf/document/nonfullscreenpagemode/) { get; set; } | Obtém ou define o modo de página, especificando como exibir o documento ao sair do modo de tela cheia. |
| [OpenAction](../../aspose.pdf/document/openaction/) { get; set; } | Obtém ou define a ação realizada ao abrir o documento. |
| [OptimizeSize](../../aspose.pdf/document/optimizesize/) { get; set; } | Obtém ou define a flag de otimização. Quando páginas são adicionadas ao documento, streams de recursos iguais no arquivo resultante são mesclados em um objeto PDF se esta flag estiver definida. Isso permite diminuir o tamanho do arquivo resultante, mas pode causar uma execução mais lenta e maiores requisitos de memória. Valor padrão: falso. |
| [Outlines](../../aspose.pdf/document/outlines/) { get; } | Obtém os contornos do documento. |
| [OutputIntents](../../aspose.pdf/document/outputintents/) { get; } | Obtém a coleção de Intenções de Saída no documento. |
| [PageInfo](../../aspose.pdf/document/pageinfo/) { get; set; } | Obtém ou define as informações da página. (apenas para gerador, não preenchido ao ler o documento) |
| [PageLabels](../../aspose.pdf/document/pagelabels/) { get; } | Obtém os rótulos das páginas no documento. |
| [PageLayout](../../aspose.pdf/document/pagelayout/) { get; set; } | Obtém ou define o layout da página que deve ser usado ao abrir o documento. |
| [PageMode](../../aspose.pdf/document/pagemode/) { get; set; } | Obtém ou define o modo de página, especificando como o documento deve ser exibido ao ser aberto. |
| [Pages](../../aspose.pdf/document/pages/) { get; } | Obtém ou define a coleção de páginas do documento. Observe que as páginas são numeradas a partir de 1 na coleção. |
| [PdfFormat](../../aspose.pdf/document/pdfformat/) { get; } | Obtém o formato PDF |
| [Permissions](../../aspose.pdf/document/permissions/) { get; } | Obtém as permissões do documento. |
| [PickTrayByPdfSize](../../aspose.pdf/document/picktraybypdfsize/) { get; set; } | Obtém ou define uma flag que especifica se o tamanho da página PDF deve ser usado para selecionar a bandeja de papel de entrada. |
| [PrintScaling](../../aspose.pdf/document/printscaling/) { get; set; } | Obtém ou define a opção de escala da página que deve ser selecionada quando uma caixa de diálogo de impressão é exibida para este documento. |
| [TaggedContent](../../aspose.pdf/document/taggedcontent/) { get; } | Obtém acesso ao conteúdo TaggedPdf. |
| [Version](../../aspose.pdf/document/version/) { get; } | Obtém uma versão do PDF a partir do cabeçalho do arquivo PDF. |
| static [FileSizeLimitToMemoryLoading](../../aspose.pdf/document/filesizelimittomemoryloading/) { get; set; } | Obtém e define o limite de tamanho do arquivo para carregar um arquivo inteiro na memória. O valor é definido em megabytes. O valor padrão é 210 Mb. |
| static [IsLicensed](../../aspose.pdf/document/islicensed/) { get; } | Obtém o estado de licença do sistema. Retorna verdadeiro se o sistema estiver funcionando em modo licenciado e falso caso contrário. |

## Métodos

| Nome | Descrição |
| --- | --- |
| static [MergeDocuments](../../aspose.pdf/document/mergedocuments/#mergedocuments)(params Document[]) | Mescla documentos. |
| static [MergeDocuments](../../aspose.pdf/document/mergedocuments/#mergedocuments_3)(params string[]) | Mescla arquivos PDF. |
| static [MergeDocuments](../../aspose.pdf/document/mergedocuments/#mergedocuments_1)(MergeOptions, params Document[]) | Mescla documentos. |
| static [MergeDocuments](../../aspose.pdf/document/mergedocuments/#mergedocuments_2)(MergeOptions, params string[]) | Mescla documentos. |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml)(Stream) | Vincula xml ao documento |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml_3)(string) | Vincula xml ao documento |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml_1)(Stream, Stream) | Vincula xml/xsl ao documento |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml_4)(string, string) | Vincula xml/xsl ao documento |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml_2)(Stream, Stream, XmlReaderSettings) | Vincula xml/xsl ao documento |
| [ChangePasswords](../../aspose.pdf/document/changepasswords/)(string, string, string) | Altera as senhas do documento. Esta ação só pode ser realizada usando a senha do proprietário. |
| [Check](../../aspose.pdf/document/check/)(bool) | Valida o documento. |
| [Convert](../../aspose.pdf/document/convert/#convert_2)(PdfFormatConversionOptions) | Converte o documento usando as opções de conversão especificadas |
| [Convert](../../aspose.pdf/document/convert/#convert_3)(CallBackGetHocr, bool) | Reconhece imagens dentro do documento e adiciona strings hocr sobre elas. |
| [Convert](../../aspose.pdf/document/convert/#convert_4)(CallBackGetHocrWithPage, bool) | Reconhece imagens dentro do documento e adiciona strings hocr sobre elas. |
| [Convert](../../aspose.pdf/document/convert/#convert_5)(Stream, PdfFormat, ConvertErrorAction) | Converte o documento e salva erros no stream especificado. |
| [Convert](../../aspose.pdf/document/convert/#convert_7)(string, PdfFormat, ConvertErrorAction) | Converte o documento e salva erros no arquivo especificado. |
| [Convert](../../aspose.pdf/document/convert/#convert)(Fixup, Stream, bool, object[]) | Converte o documento aplicando o Fixup. |
| [Convert](../../aspose.pdf/document/convert/#convert_1)(Fixup, string, bool, object[]) | Converte o documento aplicando o Fixup. |
| [Convert](../../aspose.pdf/document/convert/#convert_6)(Stream, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | Converte o documento e salva erros no arquivo especificado. |
| [Convert](../../aspose.pdf/document/convert/#convert_8)(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | Converte o documento e salva erros no arquivo especificado. |
| [ConvertPageToPNGMemoryStream](../../aspose.pdf/document/convertpagetopngmemorystream/)(Page) | Converte a página para PNG para DSR, OMR, fluxo de imagem OCR. |
| [Decrypt](../../aspose.pdf/document/decrypt/)() | Descriptografa o documento. Chame então Save para obter a versão descriptografada do documento. |
| [Dispose](../../aspose.pdf/document/dispose/)() | Fecha todos os recursos usados por este documento. |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt_1)(string, string, Permissions, CryptoAlgorithm) | Criptografa o documento. Chame então Save para obter a versão criptografada do documento. |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt)(string, string, DocumentPrivilege, CryptoAlgorithm, bool) | Criptografa o documento. Chame então Save para obter a versão criptografada do documento. |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt_2)(string, string, Permissions, CryptoAlgorithm, bool) | Criptografa o documento. Chame então Save para obter a versão criptografada do documento. |
| [ExportAnnotationsToXfdf](../../aspose.pdf/document/exportannotationstoxfdf/#exportannotationstoxfdf)(Stream) | Exporta todas as anotações do documento para o stream. |
| [ExportAnnotationsToXfdf](../../aspose.pdf/document/exportannotationstoxfdf/#exportannotationstoxfdf_1)(string) | Exporta todas as anotações do documento para o arquivo XFDF |
| [Flatten](../../aspose.pdf/document/flatten/#flatten)() | Remove todos os campos do documento e coloca seus valores no lugar. |
| [Flatten](../../aspose.pdf/document/flatten/#flatten_1)(FlattenSettings) | Remove todos os campos (e anotações) do documento e coloca seus valores no lugar. |
| [FlattenTransparency](../../aspose.pdf/document/flattentransparency/)() | Substitui conteúdo transparente por gráficos raster e vetoriais não transparentes. |
| [FreeMemory](../../aspose.pdf/document/freememory/)() | Limpa a memória |
| [GetCatalogValue](../../aspose.pdf/document/getcatalogvalue/)(string) | Retorna o valor do item do dicionário de catálogo. |
| [GetObjectById](../../aspose.pdf/document/getobjectbyid/)(string) | Obtém um objeto com o ID especificado no documento. |
| [GetXmpMetadata](../../aspose.pdf/document/getxmpmetadata/)(Stream) | Obtém metadados XMP do documento. |
| [HasIncrementalUpdate](../../aspose.pdf/document/hasincrementalupdate/)() | Verifica se o documento PDF atual foi salvo com atualizações incrementais. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf/document/importannotationsfromxfdf/#importannotationsfromxfdf)(Stream) | Importa anotações do stream para o documento. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf/document/importannotationsfromxfdf/#importannotationsfromxfdf_1)(string) | Importa anotações do arquivo XFDF para o documento. |
| [IsRepairNeeded](../../aspose.pdf/document/isrepairneeded/)(out RepairOptions) | Verifica se o documento requer a chamada do método Repair. |
| [LoadFrom](../../aspose.pdf/document/loadfrom/)(string, LoadOptions) | Carrega um arquivo, convertendo-o para PDF. |
| [Merge](../../aspose.pdf/document/merge/#merge)(params Document[]) | Mescla documentos. |
| [Merge](../../aspose.pdf/document/merge/#merge_3)(params string[]) | Mescla arquivos PDF. |
| [Merge](../../aspose.pdf/document/merge/#merge_1)(MergeOptions, params Document[]) | Mescla documentos. |
| [Merge](../../aspose.pdf/document/merge/#merge_2)(MergeOptions, params string[]) | Mescla documentos. |
| [Optimize](../../aspose.pdf/document/optimize/)() | Lineariza o documento para - abrir a primeira página o mais rápido possível; - exibir a próxima página ou seguir por link para a próxima página o mais rápido possível; - exibir a página incrementalmente à medida que chega quando os dados de uma página são entregues por um canal lento (exibir os dados mais úteis primeiro); - permitir interação do usuário, como seguir um link, a ser realizada mesmo antes que a página inteira tenha sido recebida e exibida. Invocar este método não salva realmente o documento. Pelo contrário, o documento é apenas preparado para ter uma estrutura otimizada, chame então Save para obter o documento otimizado. |
| [OptimizeResources](../../aspose.pdf/document/optimizeresources/#optimizeresources)() | Otimiza recursos no documento: 1. Recursos que não são usados nas páginas do documento são removidos; 2. Recursos iguais são unidos em um objeto; 3. Objetos não utilizados são excluídos. |
| [OptimizeResources](../../aspose.pdf/document/optimizeresources/#optimizeresources_1)(OptimizationOptions) | Otimiza recursos no documento de acordo com a estratégia de otimização definida. |
| [PageNodesToBalancedTree](../../aspose.pdf/document/pagenodestobalancedtree/)(byte) | Organiza os nós da árvore de páginas em um documento em uma árvore balanceada. Somente se o documento tiver mais de nodesNumInSubtrees objetos de página, caso contrário, não faz nada. Não chame este método enquanto itera sobre os elementos Pages, isso pode dar resultados imprevisíveis |
| [ProcessParagraphs](../../aspose.pdf/document/processparagraphs/)() | Processa parágrafos para o gerador. |
| [RemoveMetadata](../../aspose.pdf/document/removemetadata/)() | Remove metadados do documento. |
| [RemovePdfaCompliance](../../aspose.pdf/document/removepdfacompliance/)() | Remove a conformidade pdfa do documento |
| [RemovePdfUaCompliance](../../aspose.pdf/document/removepdfuacompliance/)() | Remove a conformidade pdfUa do documento |
| [Repair](../../aspose.pdf/document/repair/)(RepairOptions) | Repara o documento quebrado. |
| [Save](../../aspose.pdf/document/save/#save)() | Salva o documento incrementalmente (ou seja, usando a técnica de atualização incremental). |
| [Save](../../aspose.pdf/document/save/#save_1)(SaveOptions) | Salva o documento com opções de salvamento. |
| [Save](../../aspose.pdf/document/save/#save_2)(Stream) | Armazena o documento no stream. |
| [Save](../../aspose.pdf/document/save/#save_5)(string) | Salva o documento no arquivo especificado. |
| [Save](../../aspose.pdf/document/save/#save_3)(Stream, SaveFormat) | Salva o documento com um novo nome junto com um formato de arquivo. |
| [Save](../../aspose.pdf/document/save/#save_4)(Stream, SaveOptions) | Salva o documento em um stream com opções de salvamento. |
| [Save](../../aspose.pdf/document/save/#save_6)(string, SaveFormat) | Salva o documento com um novo nome junto com um formato de arquivo. |
| [Save](../../aspose.pdf/document/save/#save_7)(string, SaveOptions) | Salva o documento com um novo nome definindo suas opções de salvamento. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_7)(CancellationToken) | Salva o documento incrementalmente (ou seja, usando a técnica de atualização incremental). |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync)(SaveOptions, CancellationToken) | Salva o documento com opções de salvamento. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_3)(Stream, CancellationToken) | Armazena o documento no stream. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_6)(string, CancellationToken) | Salva o documento no arquivo especificado. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_1)(Stream, SaveFormat, CancellationToken) | Salva o documento com um novo nome junto com um formato de arquivo. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_2)(Stream, SaveOptions, CancellationToken) | Salva o documento em um stream com opções de salvamento. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_4)(string, SaveFormat, CancellationToken) | Salva o documento com um novo nome junto com um formato de arquivo. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_5)(string, SaveOptions, CancellationToken) | Salva o documento com um novo nome definindo suas opções de salvamento. |
| [SaveXml](../../aspose.pdf/document/savexml/)(string) | Salva o documento em XML. |
| [SendTo](../../aspose.pdf/document/sendto/#sendto_2)(DocumentDevice, Stream) | Envia todo o documento para o dispositivo de documento para processamento. |
| [SendTo](../../aspose.pdf/document/sendto/#sendto_3)(DocumentDevice, string) | Envia todo o documento para o dispositivo de documento para processamento. |
| [SendTo](../../aspose.pdf/document/sendto/#sendto)(DocumentDevice, int, int, Stream) | Envia certas páginas do documento para o dispositivo de documento para processamento. |
| [SendTo](../../aspose.pdf/document/sendto/#sendto_1)(DocumentDevice, int, int, string) | Envia todo o documento para o dispositivo de documento para processamento. |
| [SetTitle](../../aspose.pdf/document/settitle/)(string) | Define o Título para o Documento PDF |
| [SetXmpMetadata](../../aspose.pdf/document/setxmpmetadata/)(Stream) | Define os metadados XMP do documento. |
| [Validate](../../aspose.pdf/document/validate/#validate)(PdfFormatConversionOptions) | Valida o documento no arquivo especificado. |
| [Validate](../../aspose.pdf/document/validate/#validate_1)(Stream, PdfFormat) | Valida o documento no arquivo especificado. |
| [Validate](../../aspose.pdf/document/validate/#validate_2)(string, PdfFormat) | Valida o documento no arquivo especificado. |
| static [Convert](../../aspose.pdf/document/convert/#convert)(Stream, LoadOptions, Stream, SaveOptions) | Converte o stream no formato de origem em stream no formato de destino. |
| static [Convert](../../aspose.pdf/document/convert/#convert_1)(Stream, LoadOptions, string, SaveOptions) | Converte o stream no formato de origem em arquivo de destino no formato de destino. |
| static [Convert](../../aspose.pdf/document/convert/#convert_2)(string, LoadOptions, Stream, SaveOptions) | Converte o arquivo de origem no formato de origem em stream no formato de destino. |
| static [Convert](../../aspose.pdf/document/convert/#convert_3)(string, LoadOptions, string, SaveOptions) | Converte o arquivo de origem no formato de origem em arquivo de destino no formato de destino. |
| static [SetDefaultFileSizeLimitToMemoryLoading](../../aspose.pdf/document/setdefaultfilesizelimittomemoryloading/)() | Define o limite de tamanho do arquivo para carregar um arquivo inteiro na memória para o valor padrão igual a 210 Mb. |

## Campos

| Nome | Descrição |
| --- | --- |
| const [DefaultNodesNumInSubtrees](../../aspose.pdf/document/defaultnodesnuminsubtrees/) |  |

## Eventos

| Nome | Descrição |
| --- | --- |
| event [FontSubstitution](../../aspose.pdf/document/fontsubstitution/) | Ocorre quando uma fonte substitui outra fonte no documento. |

## Outros Membros

| Nome | Descrição |
| --- | --- |
| delegate [CallBackGetHocr](../../aspose.pdf/document.callbackgethocr) |  |
| delegate [CallBackGetHocrWithPage](../../aspose.pdf/document.callbackgethocrwithpage) |  |
| delegate [FontSubstitutionHandler](../../aspose.pdf/document.fontsubstitutionhandler) | Representa o método que lidará com o evento FontSubstitution. |
| interface [IDocumentFontUtilities](../../aspose.pdf/document.idocumentfontutilities) | Possui funcionalidade para ajustar fontes |
| class [MergeOptions](../../aspose.pdf/document.mergeoptions) | Representa as opções para os métodos Merge. |
| class [RepairOptions](../../aspose.pdf/document.repairoptions) | Representa opções para reparar um documento PDF. |

### Veja Também

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)