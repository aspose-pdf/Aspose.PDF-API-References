---
title: "Documento"
linktitle: "Documento"
second_title: "Referência da API Aspose.PDF para Java"
description: "Classe que representa um documento PDF."
type: docs
weight: 1060
url: /pt/java/com.aspose.pdf/document/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Document

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IDocument, Closeable, AutoCloseable

```
public final class Document extends Object implements IDocument
```

Classe que representa um documento PDF.

## Campos

| Campo | Descrição |
| --- | --- |
| [DefaultNodesNumInSubtrees](#DefaultNodesNumInSubtrees) |  |
| [FontSubstitution](#FontSubstitution) | Isso ocorre quando uma fonte substitui outra fonte no documento. |

## Construtores

| Construtor | Descrição |
| --- | --- |
| [Document](#Document--) | Inicializa um documento vazio. |
| [Document](#Document-byte:A-) | Inicializa uma nova instância de Document a partir do array de bytes {@code input}. |
| [Document](#Document-java.io.InputStream-) | Inicializa um documento vazio. |
| [Document](#Document-java.io.InputStream-boolean-) | Inicializa um documento vazio. |
| [Document](#Document-java.io.InputStream-com.aspose.pdf.engine.security.CertificateEncryptionOptions-) | Inicializa um documento vazio. |
| [Document](#Document-java.io.InputStream-com.aspose.pdf.engine.security.CertificateEncryptionOptions-boolean-) | Inicializa um documento vazio. |
| [Document](#Document-java.io.InputStream-com.aspose.pdf.LoadOptions-) | Inicializa um documento vazio. |
| [Document](#Document-java.io.InputStream-java.lang.String-) | Inicializa um documento vazio. |
| [Document](#Document-java.io.InputStream-java.lang.String-boolean-) | Inicializa um documento vazio. |
| [Document](#Document-java.io.InputStream-java.lang.String-boolean-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | Inicializa um documento vazio. |
| [Document](#Document-java.io.InputStream-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | Inicializa um documento vazio. |
| [Document](#Document-com.aspose.pdf.PdfVersion-) | Inicializa um documento vazio. |
| [Document](#Document-com.aspose.ms.System.IO.Stream-) | Inicializa um documento vazio. |
| [Document](#Document-com.aspose.ms.System.IO.Stream-com.aspose.pdf.LoadOptions-) | Inicializa um documento vazio. |
| [Document](#Document-com.aspose.ms.System.IO.Stream-java.lang.String-) | Inicializa um documento vazio. |
| [Document](#Document-com.aspose.ms.System.IO.Stream-java.lang.String-boolean-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | Inicializa um documento vazio. |
| [Document](#Document-com.aspose.ms.System.IO.Stream-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | Inicializa um documento vazio. |
| [Document](#Document-java.lang.String-) | Inicializa um documento vazio. |
| [Document](#Document-java.lang.String-boolean-) | Inicializa um documento vazio. |
| [Document](#Document-java.lang.String-com.aspose.pdf.engine.security.CertificateEncryptionOptions-) | Inicializa um documento vazio. |
| [Document](#Document-java.lang.String-com.aspose.pdf.engine.security.CertificateEncryptionOptions-boolean-) | Inicializa um documento vazio. |
| [Document](#Document-java.lang.String-com.aspose.pdf.LoadOptions-) | Inicializa um documento vazio. |
| [Document](#Document-java.lang.String-java.lang.String-) | Inicializa um documento vazio. |
| [Document](#Document-java.lang.String-java.lang.String-boolean-) | Inicializa um documento vazio. |
| [Document](#Document-java.lang.String-java.lang.String-boolean-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | Inicializa um documento vazio. |
| [Document](#Document-java.lang.String-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | Inicializa um documento vazio. |

## Métodos

| Método | Descrição |
| --- | --- |
| [afterImport](#afterImport--) | Enumere todas as anotações registradas e chame AfterImport para cada uma delas. |
| [bindXml](#bindXml-java.io.InputStream-) | Vincular xml ao documento |
| [bindXml](#bindXml-java.io.InputStream-java.io.InputStream-) | Vincular xml/xsl ao documento |
| [bindXml](#bindXml-java.io.InputStream-java.io.InputStream-com.aspose.ms.System.Xml.XmlReaderSettings-) | Vincular xml/xsl ao documento |
| [bindXml](#bindXml-java.lang.String-) | Vincular xml ao documento |
| [bindXml](#bindXml-java.lang.String-java.lang.String-) | Vincular xml/xsl ao documento |
| [changePasswords](#changePasswords-java.lang.String-java.lang.String-java.lang.String-) | Altera as senhas do documento. Esta ação só pode ser feita usando a senha do proprietário. |
| [check](#check-boolean-) | Valida o documento. |
| [close](#close--) | Fecha todos os recursos usados por este documento. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-) | Reconhece imagens dentro do documento e adiciona strings hocr sobre ele. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-) | Converte o documento e salva os erros no arquivo especificado. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-) | Converte o documento e salva os erros no arquivo especificado. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-boolean-) | Converte o documento e salva os erros no arquivo especificado. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocr-boolean-boolean-boolean-boolean-) | Converte o documento e salva os erros no arquivo especificado. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrWithPage-boolean-boolean-boolean-boolean-) | Converte o documento e salva os erros no arquivo especificado. |
| [convert](#convert-com.aspose.pdf.Fixup-java.io.OutputStream-) | Converte o documento aplicando o Fixup. |
| [convert](#convert-com.aspose.pdf.Fixup-java.io.OutputStream-boolean-java.lang.Object:A-) | Converte o documento aplicando o Fixup. |
| [convert](#convert-com.aspose.pdf.Fixup-java.lang.String-) | Converte o documento aplicando o Fixup. |
| [convert](#convert-com.aspose.pdf.Fixup-java.lang.String-boolean-java.lang.Object:A-) | Converte o documento aplicando o Fixup. |
| [convert](#convert-java.io.InputStream-com.aspose.pdf.LoadOptions-java.io.OutputStream-com.aspose.pdf.SaveOptions-) | Converte o fluxo no formato de origem para o fluxo no formato de destino. |
| [convert](#convert-java.io.InputStream-com.aspose.pdf.LoadOptions-java.lang.String-com.aspose.pdf.SaveOptions-) | Converte o fluxo no formato de origem para o arquivo de destino no formato de destino. |
| [convert](#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | Converte o documento e salva erros no fluxo especificado. |
| [convert](#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-) | Converte o documento e salva os erros no arquivo especificado. |
| [convert](#convert-com.aspose.pdf.PdfFormatConversionOptions-) | Converte o documento usando opções de conversão especificadas |
| [convert](#convert-java.lang.String-com.aspose.pdf.LoadOptions-java.io.OutputStream-com.aspose.pdf.SaveOptions-) | Converte o arquivo de origem no formato de origem para o fluxo no formato de destino. |
| [convert](#convert-java.lang.String-com.aspose.pdf.LoadOptions-java.lang.String-com.aspose.pdf.SaveOptions-) | Converte o arquivo de origem no formato de origem para o arquivo de destino no formato de destino. |
| [convert](#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | Converte o documento e salva os erros no arquivo especificado. |
| [convert](#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-) | Converte o documento e salva os erros no arquivo especificado. |
| [convertInternal](#convertInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | Converte o documento e salva erros no fluxo especificado. |
| [convertPageToPNGMemoryStream](#convertPageToPNGMemoryStream-com.aspose.pdf.Page-) | Converte a página para PNG para fluxo de imagem DSR, OMR, OCR. |
| [convertWithFlatten](#convertWithFlatten-com.aspose.pdf.Document.CallBackGetHocrBase-) | Converte o documento em documento pesquisável e ignora erros de hochr que não podem ser convertidos. |
| [convertWithSkippingErrors](#convertWithSkippingErrors-com.aspose.pdf.Document.CallBackGetHocrBase-) | Converte o documento em documento pesquisável e ignora erros de hochr que não podem ser convertidos. |
| [decrypt](#decrypt--) | Descriptografa o documento. Chame Save em seguida para obter a versão descriptografada do documento. |
| [dispose](#dispose--) | Fecha todos os recursos usados por este documento. Este método está obsoleto, use close() em vez disso. |
| [encrypt](#encrypt-int-com.aspose.pdf.CryptoAlgorithm-com.aspose.ms.System.Collections.Generic.IGenericList-) | Criptografa o documento. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.CryptoAlgorithm-boolean-) | Criptografa o documento. Chame Save em seguida para obter a versão criptografada do documento. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | Criptografa o documento. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-) | Criptografa o documento. Chame Save em seguida para obter a versão criptografada do documento. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-boolean-) | Criptografa o documento. Chame Save em seguida para obter a versão criptografada do documento. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | Criptografa o documento. |
| [exportAnnotationsToXfdf](#exportAnnotationsToXfdf-java.io.OutputStream-) | Exporta todas as anotações do documento para o fluxo. |
| [exportAnnotationsToXfdf](#exportAnnotationsToXfdf-java.lang.String-) | Exporta todas as anotações do documento para um arquivo XFDF |
| [flatten](#flatten--) | Remove todos os campos (e anotações) do documento e coloca seus valores no lugar. |
| [flatten](#flatten-com.aspose.pdf.Form.FlattenSettings-) | Remove todos os campos (e anotações) do documento e coloca seus valores no lugar. |
| [flattenTransparency](#flattenTransparency--) | Substitui o conteúdo transparente por gráficos raster e vetoriais não transparentes. |
| [freeMemory](#freeMemory--) | Limpa a memória |
| [getAbsentFontHandler](#getAbsentFontHandler--) | Notificação sobre fontes ausentes ao processar documentos. |
| [getActions](#getActions--) | <p> Obtém as ações do documento. Esta propriedade é uma instância da classe DocumentActions que permite obter/definir as ações BeforClosing, BeforSaving, etc. </p> |
| [getAllowReusePageContent](#getAllowReusePageContent--) | Permite mesclar o conteúdo das páginas para otimizar o tamanho do documento. |
| [getBackground](#getBackground--) | Obtém a cor de fundo do documento. |
| [getCatalogValue](#getCatalogValue-java.lang.String-) | Retorna o valor do item do dicionário de catálogo. |
| [getCollection](#getCollection--) | Obtém a coleção do documento. |
| [getCryptoAlgorithm](#getCryptoAlgorithm--) | Obtém as configurações de segurança se o documento estiver criptografado. Se o documento não estiver criptografado, a exceção correspondente será lançada no .net 1.1 ou CryptoAlgorithm será nulo em outras versões do .net. |
| [getCustomSecurityHandler](#getCustomSecurityHandler--) | Obtém um manipulador de segurança personalizado. |
| [getDefaultCopier](#getDefaultCopier--) | Retorna o copiador usado para copiar páginas para este documento. |
| [getDestinations](#getDestinations--) | Obtém a coleção de destinos. |
| [getDirection](#getDirection--) | Obtém a ordem de leitura do texto: L2R (da esquerda para a direita) ou R2L (da direita para a esquerda). |
| [getDuplex](#getDuplex--) | Obtém ou define a opção de tratamento de modo duplex de impressão a ser usada ao imprimir o arquivo a partir da caixa de diálogo de impressão. |
| [getEmbeddedFiles](#getEmbeddedFiles--) | Obtém a coleção de arquivos incorporados ao documento. |
| [getEmbedStandardFonts](#getEmbedStandardFonts--) | Propriedade que declara que o documento deve incorporar todas as fontes Type1 padrão que têm a bandeira IsEmbedded definida como true. |
| [getEnableSignatureSanitization](#getEnableSignatureSanitization--) | Obtém ou define a bandeira para gerenciar a sanitização de campos de assinatura. |
| [getEngineDoc](#getEngineDoc--) | Instância de IPdfDocument usada para acessar a estrutura interna do documento. Apenas interno. |
| [getFileName](#getFileName--) | Nome do arquivo PDF que causou este documento |
| [getFileSizeLimitToMemoryLoading](#getFileSizeLimitToMemoryLoading--) | Obtém e define o limite de tamanho de arquivo para carregar um arquivo inteiro na memória. |
| [getFontUtilities](#getFontUtilities--) | Instância de IDocumentFontUtilities |
| [getForm](#getForm--) | Obtém o Acro Form do documento. |
| [getId](#getId--) | Obtém o ID. |
| [getIgnoreCorruptedObjects](#getIgnoreCorruptedObjects--) | Obtém ou define a bandeira de ignorar erros em arquivos de origem. Quando páginas do documento de origem são copiadas para o documento de destino, o processo de cópia é interrompido com exceção se alguns objetos nos arquivos de origem estiverem corrompidos quando esta bandeira for falsa. exemplo: dest.Pages.Add(src.Pages); Se esta bandeira for definida como true, os objetos corrompidos serão substituídos por valores vazios. Por padrão: true. |
| [getInfo](#getInfo--) | Obtém as informações do documento. |
| [getJavaScript](#getJavaScript--) | Coleção de JavaScript de nível de documento. |
| [getLogicalStructure](#getLogicalStructure--) | Obtém a estrutura lógica do documento. |
| [getMetadata](#getMetadata--) | Metadados do documento. (Um documento PDF pode incluir informações gerais, como o título, autor e datas de criação e modificação do documento. Essas informações globais sobre o documento (em oposição ao seu conteúdo ou estrutura) são chamadas de metadados e destinam‑se a auxiliar na catalogação e pesquisa de documentos em bancos de dados externos.) |
| [getMetadataStream](#getMetadataStream--) | Retorna fluxo bruto de metadados |
| [getNamedDestinations](#getNamedDestinations--) | Coleção de Destinos Nomeados no documento. |
| [getNonFullScreenPageMode](#getNonFullScreenPageMode--) | Obtém o modo de página, especificando como exibir o documento ao sair do modo de tela cheia. |
| [getObjectById](#getObjectById-java.lang.String-) | Obtém um objeto com ID especificado no documento. |
| [getOpenAction](#getOpenAction--) | <p> Obtém a ação executada ao abrir o documento. </p> <hr> <pre> Exemplo demonstra como obter a bandeira CenterWindow: Document document = new Document(\"sample.pdf\"); IAppointment value = document.getOpenAction(); </pre> |
| [getOptimizeSize](#getOptimizeSize--) | Obtém a bandeira de otimização. Quando páginas são adicionadas ao documento, fluxos de recursos iguais no arquivo resultante são mesclados em um único objeto PDF se esta bandeira estiver definida. Isso permite diminuir o tamanho do arquivo resultante, mas pode causar execução mais lenta e maiores requisitos de memória. Valor padrão: false. |
| [getOutlines](#getOutlines--) | Obtém os contornos do documento. |
| [getOutputIntents](#getOutputIntents--) | Obtém a coleção de intenções de saída no documento. |
| [getPageInfo](#getPageInfo--) | Obtém as informações da página.(apenas para gerador, não preenchido ao ler o documento) |
| [getPageLabels](#getPageLabels--) | Obtém os rótulos de página no documento. |
| [getPageLayout](#getPageLayout--) | Obtém o layout de página que será usado quando o documento for aberto. |
| [getPageMode](#getPageMode--) | Obtém o modo de página, especificando como o documento deve ser exibido ao ser aberto. |
| [getPages](#getPages--) | <p> Obtém a coleção de páginas do documento. Observe que as páginas são numeradas a partir de 1 na coleção. </p> |
| [getPdfFormat](#getPdfFormat--) | Obtém o formato pdfa |
| [getPermissions](#getPermissions--) | Obtém as permissões do documento. |
| [getPrintScaling](#getPrintScaling--) | Obtém a opção de tratamento de dimensionamento de impressão a ser usada ao imprimir o arquivo a partir da caixa de diálogo de impressão. |
| [getTaggedContent](#getTaggedContent--) | Obtém acesso ao conteúdo TaggedPdf. O exemplo demonstra como usar conteúdo marcado para criar um novo documento com cabeçalho, parágrafos e imagens. // Cria novo documento Document document = new Document(); // Obtém o conteúdo marcado ITaggedContent taggedContent = document.getTaggedContent(); // Define o idioma do documento taggedContent.setLanguage(\"en-US\"); // Define o título do documento PDF taggedContent.setTitle(\"Example document\"); // Cria e adiciona Seção SectElement sect = taggedContent.createSectElement(); taggedContent.getRootElement().appendChild(sect); // Cria Cabeçalho HeaderElement h1 = taggedContent.createHeaderElement(1); h1.setText(\"The Header\"); sect.appendChild(h1); // Cria parágrafo ParagraphElement p = taggedContent.createParagraphElement(); p.setTag(\"Paragraph\"); p.setText(\"The text of paragraph.\"); sect.appendChild(p); // Cria ilustração IllustrationElement figure1 = taggedContent.createFigureElement(); sect.appendChild(figure1); figure1.setAlternativeText(\"Figure 1\"); figure1.setTitle(\"Image 1\"); figure1.setTag(\"Fig\"); figure1.setImage(\"path/of/image.jpg\"); // Salva documento document.save(\"example.pdf\"); |
| [getVersion](#getVersion--) | Obtém uma versão do Pdf a partir do cabeçalho do arquivo Pdf. |
| [getXmpMetadata](#getXmpMetadata-java.io.OutputStream-) | Obtenha metadados XMP do documento. |
| [hasIncrementalUpdate](#hasIncrementalUpdate--) | Verifica se o documento PDF atual foi salvo com atualizações incrementais. |
| [importAnnotationsFromXfdf](#importAnnotationsFromXfdf-java.io.InputStream-) | Importa anotações de um fluxo para o documento. |
| [importAnnotationsFromXfdf](#importAnnotationsFromXfdf-java.lang.String-) | Importa anotações do arquivo XFDF para o documento. |
| [isAbsentFontTryToSubstitute](#isAbsentFontTryToSubstitute--) | Bandeira que informa sobre a substituição de fonte ausente. |
| [isCenterWindow](#isCenterWindow--) | <p> Obtém a bandeira que especifica se a posição da janela do documento será centralizada na tela. </p> |
| [isDisableFontLicenseVerifications](#isDisableFontLicenseVerifications--) | Muitas operações com fonte não podem ser executadas se essas operações forem proibidas pela licença desta fonte. |
| [isDisplayDocTitle](#isDisplayDocTitle--) | <p> Obtém a bandeira que especifica se a barra de título da janela do documento deve exibir o título do documento. </p> |
| [isEnableNotificationLogging](#isEnableNotificationLogging--) | Obtém ou define um valor que indica se o registro de notificações deve ser habilitado. |
| [isEnableObjectUnload](#isEnableObjectUnload--) | Obtém ou define a bandeira que permite que o documento seja parcialmente descarregado da memória. |
| [isEncrypted](#isEncrypted--) | Obtém o status de criptografia do documento. Verdadeiro se o documento estiver criptografado. |
| [isFitWindow](#isFitWindow--) | <p> Obtém a bandeira que especifica se a janela do documento deve ser redimensionada para caber a primeira página exibida. </p> |
| [isHandleSignatureChange](#isHandleSignatureChange--) | Lança exceção se o documento for salvo com alterações e possuir assinatura |
| [isHideMenubar](#isHideMenubar--) | <p> Obtém a bandeira que especifica se a barra de menu deve ser ocultada quando o documento estiver ativo. </p> |
| [isHideToolBar](#isHideToolBar--) | <p> Obtém a bandeira que especifica se a barra de ferramentas deve ser ocultada quando o documento estiver ativo. </p> |
| [isHideWindowUI](#isHideWindowUI--) | <p> Obtém a bandeira que especifica se os elementos da interface do usuário devem ser ocultados quando o documento estiver ativo. </p> |
| [isLicensed](#isLicensed--) | Obtém o estado licenciado do sistema. |
| [isLinearized](#isLinearized--) | Obtém um valor que indica se o documento está linearizado. |
| [isManualDisposeEnabled](#isManualDisposeEnabled--) | Por padrão, o método save fecha fluxos internos e libera recursos de memória. Podemos fazer algumas operações e continuar a trabalhar com o documento após o método save se este parâmetro ManualDispose estiver habilitado. |
| [isPdfaCompliant](#isPdfaCompliant--) | Obtém se o documento está em conformidade pdfa. |
| [isPdfUaCompliant](#isPdfUaCompliant--) | Obtém se o documento está em conformidade com pdfua. |
| [isPickTrayByPdfSize](#isPickTrayByPdfSize--) | Obtém um sinalizador que especifica se o tamanho da página PDF deve ser usado para selecionar a bandeja de papel de entrada. |
| [isRepairNeeded](#isRepairNeeded-com.aspose.pdf.Document.RepairOptions:A-) | Verifica se o documento requer chamada ao método Repair. |
| [isSkippedPdfaCompliantValidationBeforeSave](#isSkippedPdfaCompliantValidationBeforeSave--) | Por padrão, o processo de validação pdfa é necessário para atualizar ou remover dados compatíveis com pdfa se algumas regras foram violadas. |
| [isXrefGapsAllowed](#isXrefGapsAllowed--) | Obtém ou define se o documento está em conformidade com pdfa. |
| [loadFrom](#loadFrom-java.lang.String-com.aspose.pdf.LoadOptions-) | Carrega um arquivo, convertendo-o para PDF. |
| [merge](#merge-com.aspose.pdf.ADocument.MergeOptions-com.aspose.pdf.Document...-) | Mescla documentos. |
| [merge](#merge-com.aspose.pdf.ADocument.MergeOptions-java.lang.String...-) | Mescla documentos. |
| [merge](#merge-com.aspose.pdf.Document...-) | Mescla documentos. |
| [merge](#merge-java.lang.String...-) | Mescla arquivos pdf. |
| [mergeDocuments](#mergeDocuments-com.aspose.pdf.ADocument.MergeOptions-com.aspose.pdf.Document...-) | Mescla documentos. |
| [mergeDocuments](#mergeDocuments-com.aspose.pdf.ADocument.MergeOptions-java.lang.String...-) | Mescla documentos. |
| [mergeDocuments](#mergeDocuments-com.aspose.pdf.Document...-) | Mescla documentos. |
| [mergeDocuments](#mergeDocuments-java.lang.String...-) | Mescla arquivos pdf. |
| [optimize](#optimize--) | Linearizar o documento para - abrir a primeira página o mais rápido possível; - exibir a próxima página ou seguir o link para a próxima página o mais rápido possível; - exibir a página incrementalmente à medida que chega, quando os dados de uma página são entregues por um canal lento (exibir primeiro os dados mais úteis); - permitir que a interação do usuário, como seguir um link, seja realizada mesmo antes que a página inteira tenha sido recebida e exibida. Invocar este método não salva realmente o documento. Pelo contrário, o documento apenas é preparado para ter uma estrutura otimizada; chame então Save para obter o documento otimizado. |
| [optimizeResources](#optimizeResources--) | Otimizar recursos no documento: 1. Recursos que não são usados nas páginas do documento são removidos; 2. Recursos iguais são juntados em um único objeto; 3. Objetos não utilizados são excluídos. |
| [optimizeResources](#optimizeResources-com.aspose.pdf.optimization.OptimizationOptions-) | Otimizar recursos no documento: 1. Recursos que não são usados nas páginas do documento são removidos; 2. Recursos iguais são juntados em um único objeto; 3. Objetos não utilizados são excluídos. |
| [pageNodesToBalancedTree](#pageNodesToBalancedTree--) | Organiza os nós da árvore de páginas em um documento em uma árvore balanceada. Apenas se o documento tiver mais do que nodesNumInSubtrees objetos de página, caso contrário não faz nada. |
| [pageNodesToBalancedTree](#pageNodesToBalancedTree-byte-) | Organiza os nós da árvore de páginas em um documento em uma árvore balanceada. Apenas se o documento tiver mais do que nodesNumInSubtrees objetos de página, caso contrário não faz nada. |
| [preSave](#preSave-com.aspose.pdf.PageCollection-com.aspose.pdf.SaveOptions-) | Método interno |
| [processParagraphs](#processParagraphs--) | Armazena o documento em um fluxo. |
| [removeMetadata](#removeMetadata--) | Remove metadados do documento. |
| [removePdfaCompliance](#removePdfaCompliance--) | Remover conformidade pdfa do documento |
| [removePdfUaCompliance](#removePdfUaCompliance--) | Remover conformidade pdfUa do documento |
| [repair](#repair--) | Repara documento corrompido. |
| [repair](#repair-com.aspose.pdf.Document.RepairOptions-) | Repara documento corrompido. |
| [resumeUpdate](#resumeUpdate--) | Retoma a atualização do documento |
| [save](#save--) | <p> Salvar o documento incrementalmente (ou seja, usando a técnica de atualização incremental). </p> <hr> <p> Para salvar o documento incrementalmente devemos abrir o arquivo do documento para escrita. Portanto, Document não deve ser inicializado com InputStream, mas com o caminho para o arquivo, como no trecho de código a seguir: Document doc = new Document(\"document.pdf\"); // faça algumas alterações e salve o documento incrementalmente doc.save(); </p> Caso o documento tenha sido inicializado com InputStream, escrever no InputStream é impossível, portanto recomendamos usar os métodos separados \"save\" para salvar o documento ou \"saveIncrementally\" para salvar o documento incrementalmente. |
| [save](#save-java.io.OutputStream-) | <p> Salvar o documento incrementalmente (ou seja, usando a técnica de atualização incremental). </p> <hr> <p> Para salvar o documento incrementalmente devemos abrir o arquivo do documento para escrita. Portanto, Document não deve ser inicializado com InputStream, mas com o caminho para o arquivo, como no trecho de código a seguir: Document doc = new Document(\"document.pdf\"); // faça algumas alterações e salve o documento incrementalmente doc.save(); </p> Caso o documento tenha sido inicializado com InputStream, escrever no InputStream é impossível, portanto recomendamos usar os métodos separados \"save\" para salvar o documento ou \"saveIncrementally\" para salvar o documento incrementalmente. |
| [save](#save-java.io.OutputStream-com.aspose.pdf.SaveFormat-) | <p> Salvar o documento incrementalmente (ou seja, usando a técnica de atualização incremental). </p> <hr> <p> Para salvar o documento incrementalmente devemos abrir o arquivo do documento para escrita. Portanto, Document não deve ser inicializado com InputStream, mas com o caminho para o arquivo, como no trecho de código a seguir: Document doc = new Document(\"document.pdf\"); // faça algumas alterações e salve o documento incrementalmente doc.save(); </p> Caso o documento tenha sido inicializado com InputStream, escrever no InputStream é impossível, portanto recomendamos usar os métodos separados \"save\" para salvar o documento ou \"saveIncrementally\" para salvar o documento incrementalmente. |
| [save](#save-java.io.OutputStream-com.aspose.pdf.SaveOptions-) | <p> Salvar o documento incrementalmente (ou seja, usando a técnica de atualização incremental). </p> <hr> <p> Para salvar o documento incrementalmente devemos abrir o arquivo do documento para escrita. Portanto, Document não deve ser inicializado com InputStream, mas com o caminho para o arquivo, como no trecho de código a seguir: Document doc = new Document(\"document.pdf\"); // faça algumas alterações e salve o documento incrementalmente doc.save(); </p> Caso o documento tenha sido inicializado com InputStream, escrever no InputStream é impossível, portanto recomendamos usar os métodos separados \"save\" para salvar o documento ou \"saveIncrementally\" para salvar o documento incrementalmente. |
| [save](#save-com.aspose.pdf.SaveOptions-) | <p> Salvar o documento incrementalmente (ou seja, usando a técnica de atualização incremental). </p> <hr> <p> Para salvar o documento incrementalmente devemos abrir o arquivo do documento para escrita. Portanto, Document não deve ser inicializado com InputStream, mas com o caminho para o arquivo, como no trecho de código a seguir: Document doc = new Document(\"document.pdf\"); // faça algumas alterações e salve o documento incrementalmente doc.save(); </p> Caso o documento tenha sido inicializado com InputStream, escrever no InputStream é impossível, portanto recomendamos usar os métodos separados \"save\" para salvar o documento ou \"saveIncrementally\" para salvar o documento incrementalmente. |
| [save](#save-com.aspose.ms.System.IO.Stream-) | <p> Salvar o documento incrementalmente (ou seja, usando a técnica de atualização incremental). </p> <hr> <p> Para salvar o documento incrementalmente devemos abrir o arquivo do documento para escrita. Portanto, Document não deve ser inicializado com InputStream, mas com o caminho para o arquivo, como no trecho de código a seguir: Document doc = new Document(\"document.pdf\"); // faça algumas alterações e salve o documento incrementalmente doc.save(); </p> Caso o documento tenha sido inicializado com InputStream, escrever no InputStream é impossível, portanto recomendamos usar os métodos separados \"save\" para salvar o documento ou \"saveIncrementally\" para salvar o documento incrementalmente. |
| [save](#save-java.lang.String-) | <p> Salvar o documento incrementalmente (ou seja, usando a técnica de atualização incremental). </p> <hr> <p> Para salvar o documento incrementalmente devemos abrir o arquivo do documento para escrita. Portanto, Document não deve ser inicializado com InputStream, mas com o caminho para o arquivo, como no trecho de código a seguir: Document doc = new Document(\"document.pdf\"); // faça algumas alterações e salve o documento incrementalmente doc.save(); </p> Caso o documento tenha sido inicializado com InputStream, escrever no InputStream é impossível, portanto recomendamos usar os métodos separados \"save\" para salvar o documento ou \"saveIncrementally\" para salvar o documento incrementalmente. |
| [save](#save-java.lang.String-com.aspose.pdf.SaveFormat-) | <p> Salvar o documento incrementalmente (ou seja, usando a técnica de atualização incremental). </p> <hr> <p> Para salvar o documento incrementalmente devemos abrir o arquivo do documento para escrita. Portanto, Document não deve ser inicializado com InputStream, mas com o caminho para o arquivo, como no trecho de código a seguir: Document doc = new Document(\"document.pdf\"); // faça algumas alterações e salve o documento incrementalmente doc.save(); </p> Caso o documento tenha sido inicializado com InputStream, escrever no InputStream é impossível, portanto recomendamos usar os métodos separados \"save\" para salvar o documento ou \"saveIncrementally\" para salvar o documento incrementalmente. |
| [save](#save-java.lang.String-com.aspose.pdf.SaveOptions-) | <p> Salvar o documento incrementalmente (ou seja, usando a técnica de atualização incremental). </p> <hr> <p> Para salvar o documento incrementalmente devemos abrir o arquivo do documento para escrita. Portanto, Document não deve ser inicializado com InputStream, mas com o caminho para o arquivo, como no trecho de código a seguir: Document doc = new Document(\"document.pdf\"); // faça algumas alterações e salve o documento incrementalmente doc.save(); </p> Caso o documento tenha sido inicializado com InputStream, escrever no InputStream é impossível, portanto recomendamos usar os métodos separados \"save\" para salvar o documento ou \"saveIncrementally\" para salvar o documento incrementalmente. |
| [saveIncrementally](#saveIncrementally-java.io.OutputStream-) | Salva incrementalmente o Documento PDF no fluxo especificado. |
| [saveIncrementally](#saveIncrementally-com.aspose.ms.System.IO.Stream-) | Salva incrementalmente o Documento PDF no fluxo especificado. |
| [saveIncrementally](#saveIncrementally-java.lang.String-) | Salva incrementalmente o Documento PDF no fluxo especificado. |
| [saveXml](#saveXml-java.lang.String-) | Salvar documento em XML. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.io.OutputStream-) | Envia as páginas específicas do documento para o dispositivo de documento para processamento. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.lang.String-) | Envia o documento inteiro para o dispositivo de documento para processamento. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-java.io.OutputStream-) | Envia o documento inteiro para o dispositivo de documento para processamento. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-java.lang.String-) | Envia o documento inteiro para o dispositivo de documento para processamento. |
| [setAbsentFontHandler](#setAbsentFontHandler-com.aspose.pdf.ADocument.AbsentFontHandler-) | Notificação sobre fontes ausentes ao processar documentos. |
| [setAbsentFontTryToSubstitute](#setAbsentFontTryToSubstitute-boolean-) | Definindo sinalizador para definir a fonte determinada pelo programa em caso de ausência de fonte. |
| [setAllowReusePageContent](#setAllowReusePageContent-boolean-) | Permite mesclar o conteúdo das páginas para otimizar o tamanho do documento. |
| [setBackground](#setBackground-java.awt.Color-) | Define a cor de fundo do documento. |
| [setCenterWindow](#setCenterWindow-boolean-) | Define o sinalizador que especifica se a posição da janela do documento será centralizada na tela. |
| [setCollection](#setCollection-com.aspose.pdf.Collection-) | Define a coleção do documento. |
| [setConvertMetadataAndCatalogOnly](#setConvertMetadataAndCatalogOnly-boolean-) | Obtém o parâmetro de conversão para o conversor pdf/ua (Converte apenas Metadados e Catálogo do Documento se definido como verdadeiro). |
| [setDefaultFileSizeLimitToMemoryLoading](#setDefaultFileSizeLimitToMemoryLoading--) | Define o limite de tamanho de arquivo para carregar um arquivo inteiro na memória com o valor padrão de 210 Mb. |
| [setDirection](#setDirection-com.aspose.pdf.Direction-) | Define a ordem de leitura do texto: L2R (da esquerda para a direita) ou R2L (da direita para a esquerda). |
| [setDisableFontLicenseVerifications](#setDisableFontLicenseVerifications-boolean-) | Muitas operações com fonte não podem ser executadas se essas operações forem proibidas pela licença desta fonte. |
| [setDisplayDocTitle](#setDisplayDocTitle-boolean-) | Define um sinalizador que especifica se a barra de título da janela do documento deve exibir o título do documento. |
| [setDuplex](#setDuplex-int-) | Obtém ou define a opção de tratamento de modo duplex de impressão a ser usada ao imprimir o arquivo a partir da caixa de diálogo de impressão. |
| [setEmbedStandardFonts](#setEmbedStandardFonts-boolean-) | Propriedade que declara que o documento deve incorporar todas as fontes Type1 padrão que têm a bandeira IsEmbedded definida como true. |
| [setEnableNotificationLogging](#setEnableNotificationLogging-boolean-) | Obtém ou define um valor que indica se o registro de notificações deve ser habilitado. |
| [setEnableObjectUnload](#setEnableObjectUnload-boolean-) | Obtém ou define a bandeira que permite que o documento seja parcialmente descarregado da memória. |
| [setEnableSignatureSanitization](#setEnableSignatureSanitization-boolean-) | Obtém ou define a bandeira para gerenciar a sanitização de campos de assinatura. |
| [setFileSizeLimitToMemoryLoading](#setFileSizeLimitToMemoryLoading-int-) | Obtém e define o limite de tamanho de arquivo para carregar um arquivo inteiro na memória. |
| [setFitWindow](#setFitWindow-boolean-) | Define um sinalizador que especifica se a janela do documento deve ser redimensionada para caber a primeira página exibida. |
| [setHandleSignatureChange](#setHandleSignatureChange-boolean-) | Lança exceção se o documento for salvo com alterações e possuir assinatura |
| [setHideMenubar](#setHideMenubar-boolean-) | Define um sinalizador que especifica se a barra de menu deve ser ocultada quando o documento está ativo. |
| [setHideToolBar](#setHideToolBar-boolean-) | Define um sinalizador que especifica se a barra de ferramentas deve ser ocultada quando o documento está ativo. |
| [setHideWindowUI](#setHideWindowUI-boolean-) | Define um sinalizador que especifica se os elementos da interface do usuário devem ser ocultados quando o documento está ativo. |
| [setIgnoreCorruptedObjects](#setIgnoreCorruptedObjects-boolean-) | Obtém ou define a bandeira de ignorar erros em arquivos de origem. Quando páginas do documento de origem são copiadas para o documento de destino, o processo de cópia é interrompido com exceção se alguns objetos nos arquivos de origem estiverem corrompidos quando esta bandeira for falsa. exemplo: dest.Pages.Add(src.Pages); Se esta bandeira for definida como true, os objetos corrompidos serão substituídos por valores vazios. Por padrão: true. |
| [setLinearized](#setLinearized-boolean-) | Define um valor que indica se o documento está linearizado. |
| [setManualDisposeEnabled](#setManualDisposeEnabled-boolean-) | Por padrão, o método save fecha fluxos internos e libera recursos de memória. Podemos fazer algumas operações e continuar a trabalhar com o documento após o método save ser chamado se este parâmetro ManualDispose estiver habilitado. Mas é altamente recomendado chamar o método dispose quando a instância Document não for mais necessária. |
| [setNonFullScreenPageMode](#setNonFullScreenPageMode-com.aspose.pdf.PageMode-) | Define o modo de página, especificando como exibir o documento ao sair do modo de tela cheia. |
| [setOpenAction](#setOpenAction-com.aspose.pdf.IAppointment-) | <p> Define a ação executada na abertura do documento. <p> |
| [setOptimizeSize](#setOptimizeSize-boolean-) | Define o sinalizador de otimização. Quando páginas são adicionadas ao documento, fluxos de recursos iguais no arquivo resultante são mesclados em um único objeto PDF se este sinalizador estiver definido. Isso permite diminuir o tamanho do arquivo resultante, mas pode causar execução mais lenta e maior consumo de memória. Valor padrão: false. |
| [setPageInfo](#setPageInfo-com.aspose.pdf.PageInfo-) | Define as informações da página. (apenas para gerador, não preenchido ao ler o documento) |
| [setPageLayout](#setPageLayout-com.aspose.pdf.PageLayout-) | Define o layout da página que deve ser usado quando o documento for aberto. |
| [setPageMode](#setPageMode-com.aspose.pdf.PageMode-) | Define o modo de página, especificando como o documento deve ser exibido ao ser aberto. |
| [setPickTrayByPdfSize](#setPickTrayByPdfSize-boolean-) | Define um sinalizador que especifica se o tamanho da página PDF deve ser usado para selecionar a bandeja de papel de entrada. |
| [setPrintScaling](#setPrintScaling-int-) | Define a opção de tratamento de escala de impressão a ser usada ao imprimir o arquivo a partir da caixa de diálogo de impressão. |
| [setSkipPdfaCompliantValidationBeforeSave](#setSkipPdfaCompliantValidationBeforeSave-boolean-) | Por padrão, o processo de validação pdfa é necessário para atualizar ou remover pdfa se algumas regras foram violadas. |
| [setTitle](#setTitle-java.lang.String-) | Definir título para o documento PDF |
| [setXmpMetadata](#setXmpMetadata-java.io.InputStream-) | Definir metadados XMP do documento. |
| [setXrefGapsAllowed](#setXrefGapsAllowed-boolean-) | Obtém ou define se o documento está em conformidade com pdfa. |
| [suppressUpdate](#suppressUpdate--) | Suprime a atualização dos dados de conteúdo para todas as páginas. O conteúdo não é atualizado até que ResumeUpdate seja chamado. |
| [updatePages](#updatePages--) | updatePages |
| [validate](#validate-java.io.OutputStream-com.aspose.pdf.PdfFormat-) | Validar documento no arquivo especificado. |
| [validate](#validate-com.aspose.pdf.PdfFormatConversionOptions-) | Validar documento no arquivo especificado. |
| [validate](#validate-java.lang.String-com.aspose.pdf.PdfFormat-) | Validar documento no arquivo especificado. |

### DefaultNodesNumInSubtrees {#DefaultNodesNumInSubtrees}
```
public static final byte DefaultNodesNumInSubtrees
```



### FontSubstitution {#FontSubstitution}
```
public final PdfEvent <com.aspose.pdf.ADocument.FontSubstitutionHandler> FontSubstitution
```

Isso ocorre quando uma fonte substitui outra fonte no documento.

### Document {#Document--}
```
public Document()
```

Inicializa um documento vazio.

### Document {#Document-byte:A-}
```
public Document(byte[] input)
```

Inicializa uma nova instância de Document a partir do array de bytes {@code input}.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| entrada |  | array de bytes com documento pdf. |

### Document {#Document-java.io.InputStream-}
Inicializa um documento vazio.

### Document {#Document-java.io.InputStream-boolean-}
Inicializa um documento vazio.

### Document {#Document-java.io.InputStream-com.aspose.pdf.engine.security.CertificateEncryptionOptions-}
Inicializa um documento vazio.

### Document {#Document-java.io.InputStream-com.aspose.pdf.engine.security.CertificateEncryptionOptions-boolean-}
Inicializa um documento vazio.

### Document {#Document-java.io.InputStream-com.aspose.pdf.LoadOptions-}
Inicializa um documento vazio.

### Document {#Document-java.io.InputStream-java.lang.String-}
Inicializa um documento vazio.

### Document {#Document-java.io.InputStream-java.lang.String-boolean-}
Inicializa um documento vazio.

### Document {#Document-java.io.InputStream-java.lang.String-boolean-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
Inicializa um documento vazio.

### Document {#Document-java.io.InputStream-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
Inicializa um documento vazio.

### Document {#Document-com.aspose.pdf.PdfVersion-}
Inicializa um documento vazio.

### Document {#Document-com.aspose.ms.System.IO.Stream-}
Inicializa um documento vazio.

### Document {#Document-com.aspose.ms.System.IO.Stream-com.aspose.pdf.LoadOptions-}
Inicializa um documento vazio.

### Document {#Document-com.aspose.ms.System.IO.Stream-java.lang.String-}
Inicializa um documento vazio.

### Document {#Document-com.aspose.ms.System.IO.Stream-java.lang.String-boolean-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
Inicializa um documento vazio.

### Document {#Document-com.aspose.ms.System.IO.Stream-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
Inicializa um documento vazio.

### Document {#Document-java.lang.String-}
Inicializa um documento vazio.

### Document {#Document-java.lang.String-boolean-}
Inicializa um documento vazio.

### Document {#Document-java.lang.String-com.aspose.pdf.engine.security.CertificateEncryptionOptions-}
Inicializa um documento vazio.

### Document {#Document-java.lang.String-com.aspose.pdf.engine.security.CertificateEncryptionOptions-boolean-}
Inicializa um documento vazio.

### Document {#Document-java.lang.String-com.aspose.pdf.LoadOptions-}
Inicializa um documento vazio.

### Document {#Document-java.lang.String-java.lang.String-}
Inicializa um documento vazio.

### Document {#Document-java.lang.String-java.lang.String-boolean-}
Inicializa um documento vazio.

### Document {#Document-java.lang.String-java.lang.String-boolean-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
Inicializa um documento vazio.

### Document {#Document-java.lang.String-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
Inicializa um documento vazio.

### afterImport {#afterImport--}
```
public void afterImport()
```

Enumere todas as anotações registradas e chame AfterImport para cada uma delas.

### bindXml {#bindXml-java.io.InputStream-}
Vincular xml ao documento

### bindXml {#bindXml-java.io.InputStream-java.io.InputStream-}
Vincular xml/xsl ao documento

### bindXml {#bindXml-java.io.InputStream-java.io.InputStream-com.aspose.ms.System.Xml.XmlReaderSettings-}
Vincular xml/xsl ao documento

### bindXml {#bindXml-java.lang.String-}
Vincular xml ao documento

### bindXml {#bindXml-java.lang.String-java.lang.String-}
Vincular xml/xsl ao documento

### changePasswords {#changePasswords-java.lang.String-java.lang.String-java.lang.String-}
Altera as senhas do documento. Esta ação só pode ser feita usando a senha do proprietário.

### check {#check-boolean-}
```
public boolean check(boolean doRepair)
```

Valida o documento.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| doRepair |  | Se verdadeiro, os problemas encontrados serão reparados. |

**Returns:**
valor booleano

### close {#close--}
```
public void close()
```

Fecha todos os recursos usados por este documento.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-}
Reconhece imagens dentro do documento e adiciona strings hocr sobre ele.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-}
Converte o documento e salva os erros no arquivo especificado.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-}
Converte o documento e salva os erros no arquivo especificado.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-boolean-}
Converte o documento e salva os erros no arquivo especificado.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocr-boolean-boolean-boolean-boolean-}
Converte o documento e salva os erros no arquivo especificado.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrWithPage-boolean-boolean-boolean-boolean-}
Converte o documento e salva os erros no arquivo especificado.

### convert {#convert-com.aspose.pdf.Fixup-java.io.OutputStream-}
Converte o documento aplicando o Fixup.

### convert {#convert-com.aspose.pdf.Fixup-java.io.OutputStream-boolean-java.lang.Object:A-}
Converte o documento aplicando o Fixup.

### convert {#convert-com.aspose.pdf.Fixup-java.lang.String-}
Converte o documento aplicando o Fixup.

### convert {#convert-com.aspose.pdf.Fixup-java.lang.String-boolean-java.lang.Object:A-}
Converte o documento aplicando o Fixup.

### convert {#convert-java.io.InputStream-com.aspose.pdf.LoadOptions-java.io.OutputStream-com.aspose.pdf.SaveOptions-}
Converte o fluxo no formato de origem para o fluxo no formato de destino.

### convert {#convert-java.io.InputStream-com.aspose.pdf.LoadOptions-java.lang.String-com.aspose.pdf.SaveOptions-}
Converte o fluxo no formato de origem para o arquivo de destino no formato de destino.

### convert {#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
Converte o documento e salva erros no fluxo especificado.

### convert {#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-}
Converte o documento e salva os erros no arquivo especificado.

### convert {#convert-com.aspose.pdf.PdfFormatConversionOptions-}
Converte o documento usando opções de conversão especificadas

### convert {#convert-java.lang.String-com.aspose.pdf.LoadOptions-java.io.OutputStream-com.aspose.pdf.SaveOptions-}
Converte o arquivo de origem no formato de origem para o fluxo no formato de destino.

### convert {#convert-java.lang.String-com.aspose.pdf.LoadOptions-java.lang.String-com.aspose.pdf.SaveOptions-}
Converte o arquivo de origem no formato de origem para o arquivo de destino no formato de destino.

### convert {#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
Converte o documento e salva os erros no arquivo especificado.

### convert {#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-}
Converte o documento e salva os erros no arquivo especificado.

### convertInternal {#convertInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
Converte o documento e salva erros no fluxo especificado.

### convertPageToPNGMemoryStream {#convertPageToPNGMemoryStream-com.aspose.pdf.Page-}
Converte a página para PNG para fluxo de imagem DSR, OMR, OCR.

### convertWithFlatten {#convertWithFlatten-com.aspose.pdf.Document.CallBackGetHocrBase-}
Converte o documento em documento pesquisável e ignora erros de hochr que não podem ser convertidos.

### convertWithSkippingErrors {#convertWithSkippingErrors-com.aspose.pdf.Document.CallBackGetHocrBase-}
Converte o documento em documento pesquisável e ignora erros de hochr que não podem ser convertidos.

### decrypt {#decrypt--}
```
public void decrypt()
```

Descriptografa o documento. Chame Save em seguida para obter a versão descriptografada do documento.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Fecha todos os recursos usados por este documento. Este método está obsoleto, use close() em vez disso.

### encrypt {#encrypt-int-com.aspose.pdf.CryptoAlgorithm-com.aspose.ms.System.Collections.Generic.IGenericList-}
Criptografa o documento.

### encrypt {#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.CryptoAlgorithm-boolean-}
Criptografa o documento. Chame Save em seguida para obter a versão criptografada do documento.

### encrypt {#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
Criptografa o documento.

### encrypt {#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-}
Criptografa o documento. Chame Save em seguida para obter a versão criptografada do documento.

### encrypt {#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-boolean-}
Criptografa o documento. Chame Save em seguida para obter a versão criptografada do documento.

### encrypt {#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
Criptografa o documento.

### exportAnnotationsToXfdf {#exportAnnotationsToXfdf-java.io.OutputStream-}
Exporta todas as anotações do documento para o fluxo.

### exportAnnotationsToXfdf {#exportAnnotationsToXfdf-java.lang.String-}
Exporta todas as anotações do documento para um arquivo XFDF

### flatten {#flatten--}
```
public void flatten()
```

Remove todos os campos (e anotações) do documento e coloca seus valores no lugar.

### flatten {#flatten-com.aspose.pdf.Form.FlattenSettings-}
Remove todos os campos (e anotações) do documento e coloca seus valores no lugar.

### flattenTransparency {#flattenTransparency--}
```
public void flattenTransparency()
```

Substitui o conteúdo transparente por gráficos raster e vetoriais não transparentes.

### freeMemory {#freeMemory--}
```
public void freeMemory()
```

Limpa a memória

### getAbsentFontHandler {#getAbsentFontHandler--}
```
public com.aspose.pdf.ADocument.AbsentFontHandler getAbsentFontHandler()
```

Notificação sobre fontes ausentes ao processar documentos.

**Returns:**
instância de ADocument.AbsentFontHandler

### getActions {#getActions--}
```
public DocumentActionCollection getActions()
```

<p> Obtém as ações do documento. Esta propriedade é uma instância da classe DocumentActions que permite obter/definir as ações BeforClosing, BeforSaving, etc. </p>

**Returns:**
Objeto DocumentActionCollection <hr> <pre> Este exemplo demonstra como obter a ação após a abertura do documento: Document document = new Document(\"PdfWithOpenAction.pdf\"); DocumentActionCollection actions = document.getActions(); PdfAction afterSavingAction = actions.getAfterSaving(); </pre>

### getAllowReusePageContent {#getAllowReusePageContent--}
```
public boolean getAllowReusePageContent()
```

Permite mesclar o conteúdo das páginas para otimizar o tamanho do documento.

**Returns:**
valor booleano

### getBackground {#getBackground--}
```
public Color getBackground()
```

Obtém a cor de fundo do documento.

**Returns:**
Objeto Color

### getCatalogValue {#getCatalogValue-java.lang.String-}
Retorna o valor do item do dicionário de catálogo.

### getCollection {#getCollection--}
```
public Collection getCollection()
```

Obtém a coleção do documento.

**Returns:**
Objeto Collection

### getCryptoAlgorithm {#getCryptoAlgorithm--}
```
public CryptoAlgorithm getCryptoAlgorithm()
```

Obtém as configurações de segurança se o documento estiver criptografado. Se o documento não estiver criptografado, a exceção correspondente será lançada no .net 1.1 ou CryptoAlgorithm será nulo em outras versões do .net.

**Returns:**
Elemento CryptoAlgorithm @see CryptoAlgorithm

### getCustomSecurityHandler {#getCustomSecurityHandler--}
```
public final com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler getCustomSecurityHandler()
```

Obtém um manipulador de segurança personalizado.

**Returns:**
Instância ICustomSecurityHandler

### getDefaultCopier {#getDefaultCopier--}
```
public Copier getDefaultCopier()
```

Retorna o copiador usado para copiar páginas para este documento.

**Returns:**
Objeto Copier

### getDestinations {#getDestinations--}
```
public DestinationCollection getDestinations()
```

Obtém a coleção de destinos.

**Returns:**
Elemento DestinationCollection

### getDirection {#getDirection--}
```
public Direction getDirection()
```

Obtém a ordem de leitura do texto: L2R (da esquerda para a direita) ou R2L (da direita para a esquerda).

**Returns:**
Elemento Direction @see Direction

### getDuplex {#getDuplex--}
```
public int getDuplex()
```

Obtém ou define a opção de tratamento de modo duplex de impressão a ser usada ao imprimir o arquivo a partir da caixa de diálogo de impressão.

**Returns:**
Elemento PrintDuplex

### getEmbeddedFiles {#getEmbeddedFiles--}
```
public EmbeddedFileCollection getEmbeddedFiles()
```

Obtém a coleção de arquivos incorporados ao documento.

**Returns:**
Objeto EmbeddedFileCollection

### getEmbedStandardFonts {#getEmbedStandardFonts--}
```
public boolean getEmbedStandardFonts()
```

Propriedade que declara que o documento deve incorporar todas as fontes Type1 padrão que têm a bandeira IsEmbedded definida como true.

**Returns:**
valor booleano

### getEnableSignatureSanitization {#getEnableSignatureSanitization--}
```
public final boolean getEnableSignatureSanitization()
```

Obtém ou define a bandeira para gerenciar a sanitização de campos de assinatura.

**Returns:**
valor booleano

### getEngineDoc {#getEngineDoc--}
```
public com.aspose.pdf.engine.IPdfDocument getEngineDoc()
```

Instância de IPdfDocument usada para acessar a estrutura interna do documento. Apenas interno.

**Returns:**
Objeto IPdfDocument

### getFileName {#getFileName--}
```
public String getFileName()
```

Nome do arquivo PDF que causou este documento

**Returns:**
Objeto String

### getFileSizeLimitToMemoryLoading {#getFileSizeLimitToMemoryLoading--}
```
public static int getFileSizeLimitToMemoryLoading()
```

Obtém e define o limite de tamanho de arquivo para carregar um arquivo inteiro na memória.

**Returns:**
valor int

### getFontUtilities {#getFontUtilities--}
```
public Document.IDocumentFontUtilities getFontUtilities()
```

Instância de IDocumentFontUtilities

**Returns:**
Instância de IDocumentFontUtilities

### getForm {#getForm--}
```
public Form getForm()
```

Obtém o Acro Form do documento.

**Returns:**
Objeto Form

### getId {#getId--}
```
public Id getId()
```

Obtém o ID.

**Returns:**
Objeto Id

### getIgnoreCorruptedObjects {#getIgnoreCorruptedObjects--}
```
public boolean getIgnoreCorruptedObjects()
```

Obtém ou define a bandeira de ignorar erros em arquivos de origem. Quando páginas do documento de origem são copiadas para o documento de destino, o processo de cópia é interrompido com exceção se alguns objetos nos arquivos de origem estiverem corrompidos quando esta bandeira for falsa. exemplo: dest.Pages.Add(src.Pages); Se esta bandeira for definida como true, os objetos corrompidos serão substituídos por valores vazios. Por padrão: true.

**Returns:**
valor booleano

### getInfo {#getInfo--}
```
public DocumentInfo getInfo()
```

Obtém as informações do documento.

**Returns:**
Objeto DocumentInfo

### getJavaScript {#getJavaScript--}
```
public JavaScriptCollection getJavaScript()
```

Coleção de JavaScript de nível de documento.

**Returns:**
Objeto JavaScriptCollection

### getLogicalStructure {#getLogicalStructure--}
```
public RootElement getLogicalStructure()
```

Obtém a estrutura lógica do documento.

**Returns:**
Objeto RootElement

### getMetadata {#getMetadata--}
```
public Metadata getMetadata()
```

Metadados do documento. (Um documento PDF pode incluir informações gerais, como o título, autor e datas de criação e modificação do documento. Essas informações globais sobre o documento (em oposição ao seu conteúdo ou estrutura) são chamadas de metadados e destinam‑se a auxiliar na catalogação e pesquisa de documentos em bancos de dados externos.)

**Returns:**
Objeto Metadata

### getMetadataStream {#getMetadataStream--}
```
public com.aspose.pdf.engine.data.types.IPdfStreamAccessor getMetadataStream()
```

Retorna fluxo bruto de metadados

**Returns:**
Objeto IPdfStreamAccessor

### getNamedDestinations {#getNamedDestinations--}
```
public NamedDestinationCollection getNamedDestinations()
```

Coleção de Destinos Nomeados no documento.

**Returns:**
Instância NamedDestinationCollection

### getNonFullScreenPageMode {#getNonFullScreenPageMode--}
```
public PageMode getNonFullScreenPageMode()
```

Obtém o modo de página, especificando como exibir o documento ao sair do modo de tela cheia.

**Returns:**
Elemento PageMode @see PageMode

### getObjectById {#getObjectById-java.lang.String-}
Obtém um objeto com ID especificado no documento.

### getOpenAction {#getOpenAction--}
```
public IAppointment getOpenAction()
```

<p> Obtém a ação executada ao abrir o documento. </p> <hr> <pre> Exemplo demonstra como obter a bandeira CenterWindow: Document document = new Document(\"sample.pdf\"); IAppointment value = document.getOpenAction(); </pre>

**Returns:**
Objeto IAppointment

### getOptimizeSize {#getOptimizeSize--}
```
public boolean getOptimizeSize()
```

Obtém a bandeira de otimização. Quando páginas são adicionadas ao documento, fluxos de recursos iguais no arquivo resultante são mesclados em um único objeto PDF se esta bandeira estiver definida. Isso permite diminuir o tamanho do arquivo resultante, mas pode causar execução mais lenta e maiores requisitos de memória. Valor padrão: false.

**Returns:**
valor booleano

### getOutlines {#getOutlines--}
```
public OutlineCollection getOutlines()
```

Obtém os contornos do documento.

**Returns:**
Objeto OutlineCollection

### getOutputIntents {#getOutputIntents--}
```
public final OutputIntents getOutputIntents()
```

Obtém a coleção de intenções de saída no documento.

**Returns:**
Instância OutputIntents

### getPageInfo {#getPageInfo--}
```
public PageInfo getPageInfo()
```

Obtém as informações da página.(apenas para gerador, não preenchido ao ler o documento)

**Returns:**
As informações da página.

### getPageLabels {#getPageLabels--}
```
public PageLabelCollection getPageLabels()
```

Obtém os rótulos de página no documento.

**Returns:**
Objeto PageLabelCollection

### getPageLayout {#getPageLayout--}
```
public PageLayout getPageLayout()
```

Obtém o layout de página que será usado quando o documento for aberto.

**Returns:**
Elemento PageLayout @see PageLayout

### getPageMode {#getPageMode--}
```
public PageMode getPageMode()
```

Obtém o modo de página, especificando como o documento deve ser exibido ao ser aberto.

**Returns:**
Elemento PageMode @see PageMode

### getPages {#getPages--}
```
public PageCollection getPages()
```

<p> Obtém a coleção de páginas do documento. Observe que as páginas são numeradas a partir de 1 na coleção. </p>

**Returns:**
Objeto PageCollection <hr> <pre> Exemplo abaixo demonstra como operar com as páginas do documento: Como obter o número de páginas e como obter o retângulo da página inicial do documento. Document document = new Document("sample.pdf"); PageCollection pages = document.getPages(); System.out.println("Document contains " + pages.size()); Page page = pages.get_Item(1); Rectangle rect = page.getRect(); </pre>

### getPdfFormat {#getPdfFormat--}
```
public PdfFormat getPdfFormat()
```

Obtém o formato pdfa

**Returns:**
Elemento PdfFormat @see PdfFormat

### getPermissions {#getPermissions--}
```
public int getPermissions()
```

Obtém as permissões do documento.

**Returns:**
valor int

### getPrintScaling {#getPrintScaling--}
```
public int getPrintScaling()
```

Obtém a opção de tratamento de dimensionamento de impressão a ser usada ao imprimir o arquivo a partir da caixa de diálogo de impressão.

**Returns:**
Elemento PrintScaling

### getTaggedContent {#getTaggedContent--}
```
public final ITaggedContent getTaggedContent()
```

Obtém acesso ao conteúdo TaggedPdf. O exemplo demonstra como usar conteúdo marcado para criar um novo documento com cabeçalho, parágrafos e imagens. // Cria novo documento Document document = new Document(); // Obtém o conteúdo marcado ITaggedContent taggedContent = document.getTaggedContent(); // Define o idioma do documento taggedContent.setLanguage(\"en-US\"); // Define o título do documento PDF taggedContent.setTitle(\"Example document\"); // Cria e adiciona Seção SectElement sect = taggedContent.createSectElement(); taggedContent.getRootElement().appendChild(sect); // Cria Cabeçalho HeaderElement h1 = taggedContent.createHeaderElement(1); h1.setText(\"The Header\"); sect.appendChild(h1); // Cria parágrafo ParagraphElement p = taggedContent.createParagraphElement(); p.setTag(\"Paragraph\"); p.setText(\"The text of paragraph.\"); sect.appendChild(p); // Cria ilustração IllustrationElement figure1 = taggedContent.createFigureElement(); sect.appendChild(figure1); figure1.setAlternativeText(\"Figure 1\"); figure1.setTitle(\"Image 1\"); figure1.setTag(\"Fig\"); figure1.setImage(\"path/of/image.jpg\"); // Salva documento document.save(\"example.pdf\");

**Returns:**
Instância ITaggedContent

### getVersion {#getVersion--}
```
public String getVersion()
```

Obtém uma versão do Pdf a partir do cabeçalho do arquivo Pdf.

**Returns:**
valor String

### getXmpMetadata {#getXmpMetadata-java.io.OutputStream-}
Obtenha metadados XMP do documento.

### hasIncrementalUpdate {#hasIncrementalUpdate--}
```
public final boolean hasIncrementalUpdate()
```

Verifica se o documento PDF atual foi salvo com atualizações incrementais.

**Returns:**
verdadeiro se o documento PDF tem atualizações incrementais; caso contrário, falso.

### importAnnotationsFromXfdf {#importAnnotationsFromXfdf-java.io.InputStream-}
Importa anotações de um fluxo para o documento.

### importAnnotationsFromXfdf {#importAnnotationsFromXfdf-java.lang.String-}
Importa anotações do arquivo XFDF para o documento.

### isAbsentFontTryToSubstitute {#isAbsentFontTryToSubstitute--}
```
public boolean isAbsentFontTryToSubstitute()
```

Bandeira que informa sobre a substituição de fonte ausente.

**Returns:**
valor booleano

### isCenterWindow {#isCenterWindow--}
```
public boolean isCenterWindow()
```

<p> Obtém a bandeira que especifica se a posição da janela do documento será centralizada na tela. </p>

**Returns:**
valor booleano <hr> <pre> Exemplo demonstra como obter a flag CenterWindow: Document document = new Document("sample.pdf"); boolean value = document.isCenterWindow(); </pre>

### isDisableFontLicenseVerifications {#isDisableFontLicenseVerifications--}
```
public final boolean isDisableFontLicenseVerifications()
```

Muitas operações com fonte não podem ser executadas se essas operações forem proibidas pela licença desta fonte.

**Returns:**
Valor booleano por padrão false.

### isDisplayDocTitle {#isDisplayDocTitle--}
```
public boolean isDisplayDocTitle()
```

<p> Obtém a bandeira que especifica se a barra de título da janela do documento deve exibir o título do documento. </p>

**Returns:**
valor booleano <hr> <pre> Exemplo demonstra como obter a flag DisplayDocTitle: Document document = new Document("sample.pdf"); boolean value = document.isDisplayDocTitle(); </pre>

### isEnableNotificationLogging {#isEnableNotificationLogging--}
```
public final boolean isEnableNotificationLogging()
```

Obtém ou define um valor que indica se o registro de notificações deve ser habilitado.

**Returns:**
valor booleano

### isEnableObjectUnload {#isEnableObjectUnload--}
```
public boolean isEnableObjectUnload()
```

Obtém ou define a bandeira que permite que o documento seja parcialmente descarregado da memória.

**Returns:**
valor booleano

### isEncrypted {#isEncrypted--}
```
public boolean isEncrypted()
```

Obtém o status de criptografia do documento. Verdadeiro se o documento estiver criptografado.

**Returns:**
valor booleano

### isFitWindow {#isFitWindow--}
```
public boolean isFitWindow()
```

<p> Obtém a bandeira que especifica se a janela do documento deve ser redimensionada para caber a primeira página exibida. </p>

**Returns:**
valor booleano <hr> <pre> Exemplo demonstra como obter a flag FitWindow: Document document = new Document("sample.pdf"); boolean value = document.isFitWindow(); </pre>

### isHandleSignatureChange {#isHandleSignatureChange--}
```
public final boolean isHandleSignatureChange()
```

Lança exceção se o documento for salvo com alterações e possuir assinatura

**Returns:**
valor booleano

### isHideMenubar {#isHideMenubar--}
```
public boolean isHideMenubar()
```

<p> Obtém a bandeira que especifica se a barra de menu deve ser ocultada quando o documento estiver ativo. </p>

**Returns:**
valor booleano <hr> <pre> Exemplo demonstra como obter a flag HideMenubar: Document document = new Document("sample.pdf"); boolean value = document.isHideMenubar(); </pre>

### isHideToolBar {#isHideToolBar--}
```
public boolean isHideToolBar()
```

<p> Obtém a bandeira que especifica se a barra de ferramentas deve ser ocultada quando o documento estiver ativo. </p>

**Returns:**
valor booleano <hr> <pre> Exemplo demonstra como obter a flag HideToolBar: Document document = new Document("sample.pdf"); boolean value = document.isHideToolBar(); </pre>

### isHideWindowUI {#isHideWindowUI--}
```
public boolean isHideWindowUI()
```

<p> Obtém a bandeira que especifica se os elementos da interface do usuário devem ser ocultados quando o documento estiver ativo. </p>

**Returns:**
valor booleano <hr> <pre> Exemplo demonstra como obter a flag HideWindowUI: Document document = new Document("sample.pdf"); boolean value = document.isHideWindowUI(); </pre>

### isLicensed {#isLicensed--}
```
public static boolean isLicensed()
```

Obtém o estado licenciado do sistema.

**Returns:**
valor booleano

### isLinearized {#isLinearized--}
```
public boolean isLinearized()
```

Obtém um valor que indica se o documento está linearizado.

**Returns:**
valor booleano

### isManualDisposeEnabled {#isManualDisposeEnabled--}
```
public boolean isManualDisposeEnabled()
```

Por padrão, o método save fecha fluxos internos e libera recursos de memória. Podemos fazer algumas operações e continuar a trabalhar com o documento após o método save se este parâmetro ManualDispose estiver habilitado.

**Returns:**
Valor booleano. (Valor padrão == false)

### isPdfaCompliant {#isPdfaCompliant--}
```
public boolean isPdfaCompliant()
```

Obtém se o documento está em conformidade pdfa.

**Returns:**
valor booleano

### isPdfUaCompliant {#isPdfUaCompliant--}
```
public boolean isPdfUaCompliant()
```

Obtém se o documento está em conformidade com pdfua.

**Returns:**
valor booleano

### isPickTrayByPdfSize {#isPickTrayByPdfSize--}
```
public final boolean isPickTrayByPdfSize()
```

Obtém um sinalizador que especifica se o tamanho da página PDF deve ser usado para selecionar a bandeja de papel de entrada.

**Returns:**
valor booleano

### isRepairNeeded {#isRepairNeeded-com.aspose.pdf.Document.RepairOptions:A-}
Verifica se o documento requer chamada ao método Repair.

### isSkippedPdfaCompliantValidationBeforeSave {#isSkippedPdfaCompliantValidationBeforeSave--}
```
public boolean isSkippedPdfaCompliantValidationBeforeSave()
```

Por padrão, o processo de validação pdfa é necessário para atualizar ou remover dados compatíveis com pdfa se algumas regras foram violadas.

**Returns:**
valor booleano

### isXrefGapsAllowed {#isXrefGapsAllowed--}
```
public boolean isXrefGapsAllowed()
```

Obtém ou define se o documento está em conformidade com pdfa.

**Returns:**
valor booleano

### loadFrom {#loadFrom-java.lang.String-com.aspose.pdf.LoadOptions-}
Carrega um arquivo, convertendo-o para PDF.

### merge {#merge-com.aspose.pdf.ADocument.MergeOptions-com.aspose.pdf.Document...-}
Mescla documentos.

### merge {#merge-com.aspose.pdf.ADocument.MergeOptions-java.lang.String...-}
Mescla documentos.

### merge {#merge-com.aspose.pdf.Document...-}
Mescla documentos.

### merge {#merge-java.lang.String...-}
Mescla arquivos pdf.

### mergeDocuments {#mergeDocuments-com.aspose.pdf.ADocument.MergeOptions-com.aspose.pdf.Document...-}
Mescla documentos.

### mergeDocuments {#mergeDocuments-com.aspose.pdf.ADocument.MergeOptions-java.lang.String...-}
Mescla documentos.

### mergeDocuments {#mergeDocuments-com.aspose.pdf.Document...-}
Mescla documentos.

### mergeDocuments {#mergeDocuments-java.lang.String...-}
Mescla arquivos pdf.

### optimize {#optimize--}
```
public void optimize()
```

Linearizar o documento para - abrir a primeira página o mais rápido possível; - exibir a próxima página ou seguir o link para a próxima página o mais rápido possível; - exibir a página incrementalmente à medida que chega, quando os dados de uma página são entregues por um canal lento (exibir primeiro os dados mais úteis); - permitir que a interação do usuário, como seguir um link, seja realizada mesmo antes que a página inteira tenha sido recebida e exibida. Invocar este método não salva realmente o documento. Pelo contrário, o documento apenas é preparado para ter uma estrutura otimizada; chame então Save para obter o documento otimizado.

### optimizeResources {#optimizeResources--}
```
public void optimizeResources()
```

Otimizar recursos no documento: 1. Recursos que não são usados nas páginas do documento são removidos; 2. Recursos iguais são juntados em um único objeto; 3. Objetos não utilizados são excluídos.

### optimizeResources {#optimizeResources-com.aspose.pdf.optimization.OptimizationOptions-}
Otimizar recursos no documento: 1. Recursos que não são usados nas páginas do documento são removidos; 2. Recursos iguais são juntados em um único objeto; 3. Objetos não utilizados são excluídos.

### pageNodesToBalancedTree {#pageNodesToBalancedTree--}
```
public void pageNodesToBalancedTree()
```

Organiza os nós da árvore de páginas em um documento em uma árvore balanceada. Apenas se o documento tiver mais do que nodesNumInSubtrees objetos de página, caso contrário não faz nada.

### pageNodesToBalancedTree {#pageNodesToBalancedTree-byte-}
```
public void pageNodesToBalancedTree(byte nodesNumInSubtrees)
```

Organiza os nós da árvore de páginas em um documento em uma árvore balanceada. Apenas se o documento tiver mais do que nodesNumInSubtrees objetos de página, caso contrário não faz nada.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| nodesNumInSubtrees |  | Número desejado de subnós. |

### preSave {#preSave-com.aspose.pdf.PageCollection-com.aspose.pdf.SaveOptions-}
Método interno

### processParagraphs {#processParagraphs--}
```
public void processParagraphs()
```

Armazena o documento em um fluxo.

### removeMetadata {#removeMetadata--}
```
public void removeMetadata()
```

Remove metadados do documento.

### removePdfaCompliance {#removePdfaCompliance--}
```
public void removePdfaCompliance()
```

Remover conformidade pdfa do documento

### removePdfUaCompliance {#removePdfUaCompliance--}
```
public void removePdfUaCompliance()
```

Remover conformidade pdfUa do documento

### repair {#repair--}
```
public void repair()
```

Repara documento corrompido.

### repair {#repair-com.aspose.pdf.Document.RepairOptions-}
Repara documento corrompido.

### resumeUpdate {#resumeUpdate--}
```
public void resumeUpdate()
```

Retoma a atualização do documento

### save {#save--}
```
public void save()
```

<p> Salvar o documento incrementalmente (ou seja, usando a técnica de atualização incremental). </p> <hr> <p> Para salvar o documento incrementalmente devemos abrir o arquivo do documento para escrita. Portanto, Document não deve ser inicializado com InputStream, mas com o caminho para o arquivo, como no trecho de código a seguir: Document doc = new Document(\"document.pdf\"); // faça algumas alterações e salve o documento incrementalmente doc.save(); </p> Caso o documento tenha sido inicializado com InputStream, escrever no InputStream é impossível, portanto recomendamos usar os métodos separados \"save\" para salvar o documento ou \"saveIncrementally\" para salvar o documento incrementalmente.

### save {#save-java.io.OutputStream-}
<p> Salvar o documento incrementalmente (ou seja, usando a técnica de atualização incremental). </p> <hr> <p> Para salvar o documento incrementalmente devemos abrir o arquivo do documento para escrita. Portanto, Document não deve ser inicializado com InputStream, mas com o caminho para o arquivo, como no trecho de código a seguir: Document doc = new Document(\"document.pdf\"); // faça algumas alterações e salve o documento incrementalmente doc.save(); </p> Caso o documento tenha sido inicializado com InputStream, escrever no InputStream é impossível, portanto recomendamos usar os métodos separados \"save\" para salvar o documento ou \"saveIncrementally\" para salvar o documento incrementalmente.

### save {#save-java.io.OutputStream-com.aspose.pdf.SaveFormat-}
<p> Salvar o documento incrementalmente (ou seja, usando a técnica de atualização incremental). </p> <hr> <p> Para salvar o documento incrementalmente devemos abrir o arquivo do documento para escrita. Portanto, Document não deve ser inicializado com InputStream, mas com o caminho para o arquivo, como no trecho de código a seguir: Document doc = new Document(\"document.pdf\"); // faça algumas alterações e salve o documento incrementalmente doc.save(); </p> Caso o documento tenha sido inicializado com InputStream, escrever no InputStream é impossível, portanto recomendamos usar os métodos separados \"save\" para salvar o documento ou \"saveIncrementally\" para salvar o documento incrementalmente.

### save {#save-java.io.OutputStream-com.aspose.pdf.SaveOptions-}
<p> Salvar o documento incrementalmente (ou seja, usando a técnica de atualização incremental). </p> <hr> <p> Para salvar o documento incrementalmente devemos abrir o arquivo do documento para escrita. Portanto, Document não deve ser inicializado com InputStream, mas com o caminho para o arquivo, como no trecho de código a seguir: Document doc = new Document(\"document.pdf\"); // faça algumas alterações e salve o documento incrementalmente doc.save(); </p> Caso o documento tenha sido inicializado com InputStream, escrever no InputStream é impossível, portanto recomendamos usar os métodos separados \"save\" para salvar o documento ou \"saveIncrementally\" para salvar o documento incrementalmente.

### save {#save-com.aspose.pdf.SaveOptions-}
<p> Salvar o documento incrementalmente (ou seja, usando a técnica de atualização incremental). </p> <hr> <p> Para salvar o documento incrementalmente devemos abrir o arquivo do documento para escrita. Portanto, Document não deve ser inicializado com InputStream, mas com o caminho para o arquivo, como no trecho de código a seguir: Document doc = new Document(\"document.pdf\"); // faça algumas alterações e salve o documento incrementalmente doc.save(); </p> Caso o documento tenha sido inicializado com InputStream, escrever no InputStream é impossível, portanto recomendamos usar os métodos separados \"save\" para salvar o documento ou \"saveIncrementally\" para salvar o documento incrementalmente.

### save {#save-com.aspose.ms.System.IO.Stream-}
<p> Salvar o documento incrementalmente (ou seja, usando a técnica de atualização incremental). </p> <hr> <p> Para salvar o documento incrementalmente devemos abrir o arquivo do documento para escrita. Portanto, Document não deve ser inicializado com InputStream, mas com o caminho para o arquivo, como no trecho de código a seguir: Document doc = new Document(\"document.pdf\"); // faça algumas alterações e salve o documento incrementalmente doc.save(); </p> Caso o documento tenha sido inicializado com InputStream, escrever no InputStream é impossível, portanto recomendamos usar os métodos separados \"save\" para salvar o documento ou \"saveIncrementally\" para salvar o documento incrementalmente.

### save {#save-java.lang.String-}
<p> Salvar o documento incrementalmente (ou seja, usando a técnica de atualização incremental). </p> <hr> <p> Para salvar o documento incrementalmente devemos abrir o arquivo do documento para escrita. Portanto, Document não deve ser inicializado com InputStream, mas com o caminho para o arquivo, como no trecho de código a seguir: Document doc = new Document(\"document.pdf\"); // faça algumas alterações e salve o documento incrementalmente doc.save(); </p> Caso o documento tenha sido inicializado com InputStream, escrever no InputStream é impossível, portanto recomendamos usar os métodos separados \"save\" para salvar o documento ou \"saveIncrementally\" para salvar o documento incrementalmente.

### save {#save-java.lang.String-com.aspose.pdf.SaveFormat-}
<p> Salvar o documento incrementalmente (ou seja, usando a técnica de atualização incremental). </p> <hr> <p> Para salvar o documento incrementalmente devemos abrir o arquivo do documento para escrita. Portanto, Document não deve ser inicializado com InputStream, mas com o caminho para o arquivo, como no trecho de código a seguir: Document doc = new Document(\"document.pdf\"); // faça algumas alterações e salve o documento incrementalmente doc.save(); </p> Caso o documento tenha sido inicializado com InputStream, escrever no InputStream é impossível, portanto recomendamos usar os métodos separados \"save\" para salvar o documento ou \"saveIncrementally\" para salvar o documento incrementalmente.

### save {#save-java.lang.String-com.aspose.pdf.SaveOptions-}
<p> Salvar o documento incrementalmente (ou seja, usando a técnica de atualização incremental). </p> <hr> <p> Para salvar o documento incrementalmente devemos abrir o arquivo do documento para escrita. Portanto, Document não deve ser inicializado com InputStream, mas com o caminho para o arquivo, como no trecho de código a seguir: Document doc = new Document(\"document.pdf\"); // faça algumas alterações e salve o documento incrementalmente doc.save(); </p> Caso o documento tenha sido inicializado com InputStream, escrever no InputStream é impossível, portanto recomendamos usar os métodos separados \"save\" para salvar o documento ou \"saveIncrementally\" para salvar o documento incrementalmente.

### saveIncrementally {#saveIncrementally-java.io.OutputStream-}
Salva incrementalmente o Documento PDF no fluxo especificado.

### saveIncrementally {#saveIncrementally-com.aspose.ms.System.IO.Stream-}
Salva incrementalmente o Documento PDF no fluxo especificado.

### saveIncrementally {#saveIncrementally-java.lang.String-}
Salva incrementalmente o Documento PDF no fluxo especificado.

### saveXml {#saveXml-java.lang.String-}
Salvar documento em XML.

### sendTo {#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.io.OutputStream-}
Envia as páginas específicas do documento para o dispositivo de documento para processamento.

### sendTo {#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.lang.String-}
Envia o documento inteiro para o dispositivo de documento para processamento.

### sendTo {#sendTo-com.aspose.pdf.devices.DocumentDevice-java.io.OutputStream-}
Envia o documento inteiro para o dispositivo de documento para processamento.

### sendTo {#sendTo-com.aspose.pdf.devices.DocumentDevice-java.lang.String-}
Envia o documento inteiro para o dispositivo de documento para processamento.

### setAbsentFontHandler {#setAbsentFontHandler-com.aspose.pdf.ADocument.AbsentFontHandler-}
Notificação sobre fontes ausentes ao processar documentos.

### setAbsentFontTryToSubstitute {#setAbsentFontTryToSubstitute-boolean-}
```
public void setAbsentFontTryToSubstitute(boolean setAbsentFontTryToSubstitute)
```

Definindo sinalizador para definir a fonte determinada pelo programa em caso de ausência de fonte.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| setAbsentFontTryToSubstitute |  |  |

### setAllowReusePageContent {#setAllowReusePageContent-boolean-}
```
public void setAllowReusePageContent(boolean value)
```

Permite mesclar o conteúdo das páginas para otimizar o tamanho do documento.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setBackground {#setBackground-java.awt.Color-}
Define a cor de fundo do documento.

### setCenterWindow {#setCenterWindow-boolean-}
```
public void setCenterWindow(boolean value)
```

Define o sinalizador que especifica se a posição da janela do documento será centralizada na tela.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setCollection {#setCollection-com.aspose.pdf.Collection-}
Define a coleção do documento.

### setConvertMetadataAndCatalogOnly {#setConvertMetadataAndCatalogOnly-boolean-}
```
public final void setConvertMetadataAndCatalogOnly(boolean value)
```

Obtém o parâmetro de conversão para o conversor pdf/ua (Converte apenas Metadados e Catálogo do Documento se definido como verdadeiro).

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setDefaultFileSizeLimitToMemoryLoading {#setDefaultFileSizeLimitToMemoryLoading--}
```
public static void setDefaultFileSizeLimitToMemoryLoading()
```

Define o limite de tamanho de arquivo para carregar um arquivo inteiro na memória com o valor padrão de 210 Mb.

### setDirection {#setDirection-com.aspose.pdf.Direction-}
Define a ordem de leitura do texto: L2R (da esquerda para a direita) ou R2L (da direita para a esquerda).

### setDisableFontLicenseVerifications {#setDisableFontLicenseVerifications-boolean-}
```
public final void setDisableFontLicenseVerifications(boolean value)
```

Muitas operações com fonte não podem ser executadas se essas operações forem proibidas pela licença desta fonte.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | Valor booleano por padrão false. |

### setDisplayDocTitle {#setDisplayDocTitle-boolean-}
```
public void setDisplayDocTitle(boolean value)
```

Define um sinalizador que especifica se a barra de título da janela do documento deve exibir o título do documento.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setDuplex {#setDuplex-int-}
```
public void setDuplex(int value)
```

Obtém ou define a opção de tratamento de modo duplex de impressão a ser usada ao imprimir o arquivo a partir da caixa de diálogo de impressão.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | Elemento PrintDuplex |

### setEmbedStandardFonts {#setEmbedStandardFonts-boolean-}
```
public void setEmbedStandardFonts(boolean value)
```

Propriedade que declara que o documento deve incorporar todas as fontes Type1 padrão que têm a bandeira IsEmbedded definida como true.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setEnableNotificationLogging {#setEnableNotificationLogging-boolean-}
```
public final void setEnableNotificationLogging(boolean value)
```

Obtém ou define um valor que indica se o registro de notificações deve ser habilitado.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setEnableObjectUnload {#setEnableObjectUnload-boolean-}
```
public void setEnableObjectUnload(boolean value)
```

Obtém ou define a bandeira que permite que o documento seja parcialmente descarregado da memória.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setEnableSignatureSanitization {#setEnableSignatureSanitization-boolean-}
```
public final void setEnableSignatureSanitization(boolean value)
```

Obtém ou define a bandeira para gerenciar a sanitização de campos de assinatura.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setFileSizeLimitToMemoryLoading {#setFileSizeLimitToMemoryLoading-int-}
```
public static void setFileSizeLimitToMemoryLoading(int value)
```

Obtém e define o limite de tamanho de arquivo para carregar um arquivo inteiro na memória.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |

### setFitWindow {#setFitWindow-boolean-}
```
public void setFitWindow(boolean value)
```

Define um sinalizador que especifica se a janela do documento deve ser redimensionada para caber a primeira página exibida.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setHandleSignatureChange {#setHandleSignatureChange-boolean-}
```
public final void setHandleSignatureChange(boolean value)
```

Lança exceção se o documento for salvo com alterações e possuir assinatura

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setHideMenubar {#setHideMenubar-boolean-}
```
public void setHideMenubar(boolean value)
```

Define um sinalizador que especifica se a barra de menu deve ser ocultada quando o documento está ativo.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setHideToolBar {#setHideToolBar-boolean-}
```
public void setHideToolBar(boolean value)
```

Define um sinalizador que especifica se a barra de ferramentas deve ser ocultada quando o documento está ativo.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setHideWindowUI {#setHideWindowUI-boolean-}
```
public void setHideWindowUI(boolean value)
```

Define um sinalizador que especifica se os elementos da interface do usuário devem ser ocultados quando o documento está ativo.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setIgnoreCorruptedObjects {#setIgnoreCorruptedObjects-boolean-}
```
public void setIgnoreCorruptedObjects(boolean value)
```

Obtém ou define a bandeira de ignorar erros em arquivos de origem. Quando páginas do documento de origem são copiadas para o documento de destino, o processo de cópia é interrompido com exceção se alguns objetos nos arquivos de origem estiverem corrompidos quando esta bandeira for falsa. exemplo: dest.Pages.Add(src.Pages); Se esta bandeira for definida como true, os objetos corrompidos serão substituídos por valores vazios. Por padrão: true.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setLinearized {#setLinearized-boolean-}
```
public void setLinearized(boolean value)
```

Define um valor que indica se o documento está linearizado.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setManualDisposeEnabled {#setManualDisposeEnabled-boolean-}
```
public void setManualDisposeEnabled(boolean manualDisposeEnabled)
```

Por padrão, o método save fecha fluxos internos e libera recursos de memória. Podemos fazer algumas operações e continuar a trabalhar com o documento após o método save ser chamado se este parâmetro ManualDispose estiver habilitado. Mas é altamente recomendado chamar o método dispose quando a instância Document não for mais necessária.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| manualDisposeEnabled |  | Valor booleano. (Valor padrão == false) |

### setNonFullScreenPageMode {#setNonFullScreenPageMode-com.aspose.pdf.PageMode-}
Define o modo de página, especificando como exibir o documento ao sair do modo de tela cheia.

### setOpenAction {#setOpenAction-com.aspose.pdf.IAppointment-}
<p> Define a ação executada na abertura do documento. <p>

### setOptimizeSize {#setOptimizeSize-boolean-}
```
public void setOptimizeSize(boolean value)
```

Define o sinalizador de otimização. Quando páginas são adicionadas ao documento, fluxos de recursos iguais no arquivo resultante são mesclados em um único objeto PDF se este sinalizador estiver definido. Isso permite diminuir o tamanho do arquivo resultante, mas pode causar execução mais lenta e maior consumo de memória. Valor padrão: false.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setPageInfo {#setPageInfo-com.aspose.pdf.PageInfo-}
Define as informações da página. (apenas para gerador, não preenchido ao ler o documento)

### setPageLayout {#setPageLayout-com.aspose.pdf.PageLayout-}
Define o layout da página que deve ser usado quando o documento for aberto.

### setPageMode {#setPageMode-com.aspose.pdf.PageMode-}
Define o modo de página, especificando como o documento deve ser exibido ao ser aberto.

### setPickTrayByPdfSize {#setPickTrayByPdfSize-boolean-}
```
public final void setPickTrayByPdfSize(boolean value)
```

Define um sinalizador que especifica se o tamanho da página PDF deve ser usado para selecionar a bandeja de papel de entrada.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setPrintScaling {#setPrintScaling-int-}
```
public void setPrintScaling(int value)
```

Define a opção de tratamento de escala de impressão a ser usada ao imprimir o arquivo a partir da caixa de diálogo de impressão.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | Elemento PrintDuplex |

### setSkipPdfaCompliantValidationBeforeSave {#setSkipPdfaCompliantValidationBeforeSave-boolean-}
```
public void setSkipPdfaCompliantValidationBeforeSave(boolean pdfaCompliantValidationBeforeSave)
```

Por padrão, o processo de validação pdfa é necessário para atualizar ou remover pdfa se algumas regras foram violadas.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pdfaCompliantValidationBeforeSave |  | valor booleano |

### setTitle {#setTitle-java.lang.String-}
Definir título para o documento PDF

### setXmpMetadata {#setXmpMetadata-java.io.InputStream-}
Definir metadados XMP do documento.

### setXrefGapsAllowed {#setXrefGapsAllowed-boolean-}
```
public void setXrefGapsAllowed(boolean value)
```

Obtém ou define se o documento está em conformidade com pdfa.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### suppressUpdate {#suppressUpdate--}
```
public void suppressUpdate()
```

Suprime a atualização dos dados de conteúdo para todas as páginas. O conteúdo não é atualizado até que ResumeUpdate seja chamado.

### updatePages {#updatePages--}
```
public void updatePages()
```

updatePages

### validate {#validate-java.io.OutputStream-com.aspose.pdf.PdfFormat-}
Validar documento no arquivo especificado.

### validate {#validate-com.aspose.pdf.PdfFormatConversionOptions-}
Validar documento no arquivo especificado.

### validate {#validate-java.lang.String-com.aspose.pdf.PdfFormat-}
Validar documento no arquivo especificado.
