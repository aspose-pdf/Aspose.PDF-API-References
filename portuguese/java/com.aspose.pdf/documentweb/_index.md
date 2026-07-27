---
title: "DocumentWeb"
linktitle: "DocumentWeb"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa a classe DocumentWeb"
type: docs
weight: 1170
url: /pt/java/com.aspose.pdf/documentweb/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.DocumentWeb

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IDocument, Closeable, AutoCloseable

```
public final class DocumentWeb extends Object implements IDocument
```

Representa a classe DocumentWeb

## Campos

| Campo | Descrição |
| --- | --- |
| [DefaultNodesNumInSubtrees](#DefaultNodesNumInSubtrees) |  |
| [FontSubstitution](#FontSubstitution) | Isso ocorre quando uma fonte substitui outra fonte no documento. |

## Construtores

| Construtor | Descrição |
| --- | --- |
| [DocumentWeb](#DocumentWeb--) | Inicializa um DocumentWeb vazio. |
| [DocumentWeb](#DocumentWeb-java.io.InputStream-) | Inicializa um DocumentWeb vazio. |
| [DocumentWeb](#DocumentWeb-java.io.InputStream-com.aspose.pdf.LoadOptions-) | Inicializa um DocumentWeb vazio. |
| [DocumentWeb](#DocumentWeb-java.io.InputStream-java.lang.String-) | Inicializa um DocumentWeb vazio. |
| [DocumentWeb](#DocumentWeb-java.lang.String-) | Inicializa um DocumentWeb vazio. |
| [DocumentWeb](#DocumentWeb-java.lang.String-com.aspose.pdf.LoadOptions-) | Inicializa um DocumentWeb vazio. |
| [DocumentWeb](#DocumentWeb-java.lang.String-java.lang.String-) | Inicializa um DocumentWeb vazio. |

## Métodos

| Método | Descrição |
| --- | --- |
| [afterImport](#afterImport--) | Enumere todas as anotações registradas e chame AfterImport para cada uma delas. |
| [bindXml](#bindXml-java.io.InputStream-) | Vincular xml ao documento |
| [bindXml](#bindXml-java.io.InputStream-java.io.InputStream-) | Vincular xml/xsl ao documento |
| [bindXml](#bindXml-java.io.InputStream-java.io.InputStream-com.aspose.ms.System.Xml.XmlReaderSettings-) | Vincular xml/xsl ao documento |
| [bindXml](#bindXml-java.lang.String-) | Vincular xml ao documento |
| [bindXml](#bindXml-java.lang.String-java.lang.String-) | Vincular xml/xsl ao documento |
| [changePasswords](#changePasswords-java.lang.String-java.lang.String-java.lang.String-) | Altera as senhas do documento. |
| [check](#check-boolean-) | Valida o documento. |
| [close](#close--) | Fecha todos os recursos usados por este documento. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-) | Converte o documento em documento pesquisável. |
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
| [decrypt](#decrypt--) | Descriptografa o documento. |
| [dispose](#dispose--) | Obsoleto. |
| [encrypt](#encrypt-int-com.aspose.pdf.CryptoAlgorithm-com.aspose.ms.System.Collections.Generic.IGenericList-) | Criptografa o documento. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.CryptoAlgorithm-boolean-) | Criptografa o documento. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | Criptografa o documento. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-) | Criptografa o documento. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-boolean-) | Criptografa o documento. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | Criptografa o documento. |
| [exportAnnotationsToXfdf](#exportAnnotationsToXfdf-java.io.OutputStream-) | Exporta todas as anotações do documento para o fluxo. |
| [exportAnnotationsToXfdf](#exportAnnotationsToXfdf-java.lang.String-) | Exporta todas as anotações do documento para um arquivo XFDF |
| [flatten](#flatten--) | Remove todos os campos (e anotações) do documento e coloca seus valores no lugar. |
| [flatten](#flatten-com.aspose.pdf.Form.FlattenSettings-) | Remove todos os campos do documento e coloca seus valores no lugar. |
| [flattenTransparency](#flattenTransparency--) | Substitui o conteúdo transparente por gráficos raster e vetoriais não transparentes. |
| [freeMemory](#freeMemory--) | Limpa a memória |
| [getAbsentFontHandler](#getAbsentFontHandler--) | Notificação sobre fontes ausentes ao processar documentos. |
| [getActions](#getActions--) | Obtém as ações do documento. |
| [getAllowReusePageContent](#getAllowReusePageContent--) | Permite mesclar o conteúdo das páginas para otimizar o tamanho do documento. |
| [getBackground](#getBackground--) | Obtém a cor de fundo do documento. |
| [getCatalogValue](#getCatalogValue-java.lang.String-) | Retorna o valor do item do dicionário de catálogo. |
| [getCollection](#getCollection--) | Obtém a coleção do documento. |
| [getCryptoAlgorithm](#getCryptoAlgorithm--) | Obtém as configurações de segurança se o documento estiver criptografado. |
| [getCustomSecurityHandler](#getCustomSecurityHandler--) | Obtém um manipulador de segurança personalizado. |
| [getDefaultCopier](#getDefaultCopier--) | Retorna o copiador usado para copiar páginas para este documento. |
| [getDestinations](#getDestinations--) | Obsoleto. |
| [getDirection](#getDirection--) | Obtém a ordem de leitura do texto: L2R (da esquerda para a direita) ou R2L (da direita para a esquerda). |
| [getDuplex](#getDuplex--) | Obtém ou define a opção de tratamento de modo duplex de impressão a ser usada ao imprimir o arquivo a partir da caixa de diálogo de impressão. |
| [getEmbeddedFiles](#getEmbeddedFiles--) | Obtém a coleção de arquivos incorporados ao documento. |
| [getEmbedStandardFonts](#getEmbedStandardFonts--) | Propriedade que declara que o documento deve incorporar todas as fontes Type1 padrão que têm a bandeira IsEmbedded definida como true. |
| [getEnableSignatureSanitization](#getEnableSignatureSanitization--) | Obtém ou define a bandeira para gerenciar a sanitização de campos de assinatura. |
| [getEngineDoc](#getEngineDoc--) | Instância de IPdfDocument usada para acessar a estrutura interna do documento. |
| [getFileName](#getFileName--) | Nome do arquivo PDF que causou este documento |
| [getFileSizeLimitToMemoryLoading](#getFileSizeLimitToMemoryLoading--) | Obtém e define o limite de tamanho de arquivo para carregar um arquivo inteiro na memória. |
| [getForm](#getForm--) | Obtém o Acro Form do documento. |
| [getId](#getId--) | Obtém o ID. |
| [getIgnoreCorruptedObjects](#getIgnoreCorruptedObjects--) | Obtém ou define a bandeira de ignorar erros nos arquivos de origem. |
| [getInfo](#getInfo--) | Obtém as informações do documento. |
| [getJavaScript](#getJavaScript--) | Coleção de JavaScript de nível de documento. |
| [getLogicalStructure](#getLogicalStructure--) | Obtém a estrutura lógica do documento. |
| [getMetadata](#getMetadata--) | Metadados do documento. |
| [getMetadataStream](#getMetadataStream--) | Somente para uso interno! |
| [getNamedDestinations](#getNamedDestinations--) | Coleção de Destinos Nomeados no documento. |
| [getNonFullScreenPageMode](#getNonFullScreenPageMode--) | Obtém o modo de página, especificando como exibir o documento ao sair do modo de tela cheia. |
| [getObjectById](#getObjectById-java.lang.String-) | Obtém um objeto com ID especificado no documento. |
| [getOpenAction](#getOpenAction--) | Obtém a ação executada na abertura do documento. |
| [getOptimizeSize](#getOptimizeSize--) | Obtém a bandeira de otimização. |
| [getOutlines](#getOutlines--) | Obtém os contornos do documento. |
| [getOutputIntents](#getOutputIntents--) | Obtém a coleção de intenções de saída no documento. |
| [getPageInfo](#getPageInfo--) | Obtém as informações da página.(apenas para gerador, não preenchido ao ler o documento) |
| [getPageLabels](#getPageLabels--) | Obtém os rótulos de página no documento. |
| [getPageLayout](#getPageLayout--) | Obtém o layout de página que será usado quando o documento for aberto. |
| [getPageMode](#getPageMode--) | Obtém o modo de página, especificando como o documento deve ser exibido ao ser aberto. |
| [getPages](#getPages--) | Obtém a coleção de páginas do documento. |
| [getPdfFormat](#getPdfFormat--) | Obtém o formato PDF. |
| [getPermissions](#getPermissions--) | Obtém as permissões do documento. |
| [getPrintScaling](#getPrintScaling--) | Obtém a opção de tratamento de dimensionamento de impressão a ser usada ao imprimir o arquivo a partir da caixa de diálogo de impressão. |
| [getTaggedContent](#getTaggedContent--) | Obtém acesso ao conteúdo TaggedPdf. |
| [getVersion](#getVersion--) | Obtém uma versão do Pdf a partir do cabeçalho do arquivo Pdf. |
| [getXmpMetadata](#getXmpMetadata-java.io.OutputStream-) | Obtenha metadados XMP do documento. |
| [hasIncrementalUpdate](#hasIncrementalUpdate--) | Verifica se o documento PDF atual foi salvo com atualizações incrementais. |
| [importAnnotationsFromXfdf](#importAnnotationsFromXfdf-java.io.InputStream-) | Importa anotações de um fluxo para o documento. |
| [importAnnotationsFromXfdf](#importAnnotationsFromXfdf-java.lang.String-) | Importa anotações do arquivo XFDF para o documento. |
| [isAbsentFontTryToSubstitute](#isAbsentFontTryToSubstitute--) | Bandeira que informa sobre a substituição de fonte ausente. |
| [isCenterWindow](#isCenterWindow--) | Obtém a flag que especifica se a posição da janela do documento será centralizada na tela. |
| [isDisableFontLicenseVerifications](#isDisableFontLicenseVerifications--) | Muitas operações com fonte não podem ser executadas se essas operações forem proibidas pela licença desta fonte. |
| [isDisplayDocTitle](#isDisplayDocTitle--) | Obtém a bandeira que especifica se a barra de título da janela do documento deve exibir o título do documento. |
| [isEnableNotificationLogging](#isEnableNotificationLogging--) | Obtém ou define um valor que indica se o registro de notificações deve ser habilitado. |
| [isEnableObjectUnload](#isEnableObjectUnload--) | Obtém ou define a bandeira que permite que o documento seja parcialmente descarregado da memória. |
| [isEncrypted](#isEncrypted--) | Obtém o status criptografado do documento. |
| [isFitWindow](#isFitWindow--) | Obtém a bandeira que especifica se a janela do documento deve ser redimensionada para caber na primeira página exibida. |
| [isHandleSignatureChange](#isHandleSignatureChange--) | Lança exceção se o documento for salvo com alterações e possuir assinatura |
| [isHideMenubar](#isHideMenubar--) | Obtém sinalizador que especifica se a barra de menu deve ser ocultada quando o documento está ativo. |
| [isHideToolBar](#isHideToolBar--) | Obtém sinalizador que especifica se a barra de ferramentas deve ser ocultada quando o documento está ativo. |
| [isHideWindowUI](#isHideWindowUI--) | Obtém ou define o sinalizador que especifica se os elementos da interface do usuário devem ser ocultados quando o documento está ativo. |
| [isLicensed](#isLicensed--) | Obtém o estado licenciado do sistema. |
| [isLinearized](#isLinearized--) | Obtém ou define um valor que indica se o documento está linearizado. |
| [isManualDisposeEnabled](#isManualDisposeEnabled--) | Por padrão, o método save fecha fluxos internos e libera recursos de memória. |
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
| [optimize](#optimize--) | Linearize o documento para - abrir a primeira página o mais rápido possível; - exibir a próxima página ou seguir o link para a próxima página o mais rápido possível; - exibir a página incrementalmente à medida que chega, quando os dados de uma página são entregues por um canal lento (exibir primeiro os dados mais úteis); - permitir que a interação do usuário, como seguir um link, seja realizada mesmo antes que a página inteira tenha sido recebida e exibida. |
| [optimizeResources](#optimizeResources--) | Otimizar recursos no documento: 1. |
| [optimizeResources](#optimizeResources-com.aspose.pdf.optimization.OptimizationOptions-) | Otimizar recursos no documento de acordo com a estratégia de otimização definida. |
| [pageNodesToBalancedTree](#pageNodesToBalancedTree--) | Organiza os nós da árvore de páginas em um documento em uma árvore balanceada. |
| [pageNodesToBalancedTree](#pageNodesToBalancedTree-byte-) | Organiza os nós da árvore de páginas em um documento em uma árvore balanceada. |
| [preSave](#preSave-com.aspose.pdf.PageCollection-com.aspose.pdf.SaveOptions-) | Método interno |
| [processParagraphs](#processParagraphs--) | Armazena o documento no gerador. |
| [removeMetadata](#removeMetadata--) | Remove metadados do documento. |
| [removePdfaCompliance](#removePdfaCompliance--) | Remover conformidade pdfa do documento |
| [removePdfUaCompliance](#removePdfUaCompliance--) | Remover conformidade pdfUa do documento |
| [repair](#repair--) | Repara documento corrompido. |
| [repair](#repair-com.aspose.pdf.Document.RepairOptions-) | Repara documento corrompido. |
| [resumeUpdate](#resumeUpdate--) | Retoma a atualização do documento |
| [save](#save--) | Salvar documento incrementalmente (por exemplo. |
| [save](#save-javax.servlet.http.HttpServletResponse-java.lang.String-com.aspose.pdf.ContentDisposition-com.aspose.pdf.SaveOptions-) | Salva o documento em um fluxo de resposta com opções de salvamento. |
| [save](#save-java.io.OutputStream-) | Armazena o documento em um fluxo. |
| [save](#save-java.io.OutputStream-com.aspose.pdf.SaveFormat-) | Salva o documento com um novo nome juntamente com um formato de arquivo. |
| [save](#save-java.io.OutputStream-com.aspose.pdf.SaveOptions-) | Salva o documento com um novo nome definindo suas opções de salvamento. |
| [save](#save-com.aspose.pdf.SaveOptions-) | Salva o documento com opções de salvamento. |
| [save](#save-com.aspose.ms.System.IO.Stream-) | Somente para uso interno |
| [save](#save-java.lang.String-) | Salva o documento no arquivo especificado. |
| [save](#save-java.lang.String-com.aspose.pdf.SaveFormat-) | Salva o documento com um novo nome juntamente com um formato de arquivo. |
| [save](#save-java.lang.String-com.aspose.pdf.SaveOptions-) | Salva o documento com um novo nome definindo suas opções de salvamento. |
| [saveIncrementally](#saveIncrementally-java.io.OutputStream-) | Salva incrementalmente o Documento PDF no fluxo especificado. |
| [saveIncrementally](#saveIncrementally-com.aspose.ms.System.IO.Stream-) | Salva incrementalmente o Documento PDF no fluxo especificado. |
| [saveIncrementally](#saveIncrementally-java.lang.String-) | Salva incrementalmente o Documento PDF no fluxo especificado. |
| [saveXml](#saveXml-java.lang.String-) | Salvar documento em XML. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.io.OutputStream-) | Envia as páginas específicas do documento para o dispositivo de documento para processamento. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.lang.String-) | Envia o documento inteiro para o dispositivo de documento para processamento. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-java.io.OutputStream-) | Envia o documento inteiro para o dispositivo de documento para processamento. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-java.lang.String-) | Envia o documento inteiro para o dispositivo de documento para processamento. |
| [setAbsentFontHandler](#setAbsentFontHandler-com.aspose.pdf.ADocument.AbsentFontHandler-) | Notificação sobre fontes ausentes ao processar documentos. |
| [setAbsentFontTryToSubstitute](#setAbsentFontTryToSubstitute-boolean-) | Definindo a flag para substituir a fonte ausente. |
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
| [setIgnoreCorruptedObjects](#setIgnoreCorruptedObjects-boolean-) | Obtém ou define a bandeira de ignorar erros nos arquivos de origem. |
| [setLinearized](#setLinearized-boolean-) | Define um valor que indica se o documento está linearizado. |
| [setManualDisposeEnabled](#setManualDisposeEnabled-boolean-) | Por padrão, o método save fecha fluxos internos e libera recursos de memória. |
| [setNonFullScreenPageMode](#setNonFullScreenPageMode-com.aspose.pdf.PageMode-) | Define o modo de página, especificando como exibir o documento ao sair do modo de tela cheia. |
| [setOpenAction](#setOpenAction-com.aspose.pdf.IAppointment-) | Define a ação executada ao abrir o documento. |
| [setOptimizeSize](#setOptimizeSize-boolean-) | Define o sinalizador de otimização. |
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

### DocumentWeb {#DocumentWeb--}
```
public DocumentWeb()
```

Inicializa um DocumentWeb vazio.

### DocumentWeb {#DocumentWeb-java.io.InputStream-}
Inicializa um DocumentWeb vazio.

### DocumentWeb {#DocumentWeb-java.io.InputStream-com.aspose.pdf.LoadOptions-}
Inicializa um DocumentWeb vazio.

### DocumentWeb {#DocumentWeb-java.io.InputStream-java.lang.String-}
Inicializa um DocumentWeb vazio.

### DocumentWeb {#DocumentWeb-java.lang.String-}
Inicializa um DocumentWeb vazio.

### DocumentWeb {#DocumentWeb-java.lang.String-com.aspose.pdf.LoadOptions-}
Inicializa um DocumentWeb vazio.

### DocumentWeb {#DocumentWeb-java.lang.String-java.lang.String-}
Inicializa um DocumentWeb vazio.

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
Altera as senhas do documento.

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
valor booleano True - se o documento foi reparado; caso contrário, false.

### close {#close--}
```
public void close()
```

Fecha todos os recursos usados por este documento.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-}
Converte o documento em documento pesquisável.

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

Descriptografa o documento.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Obsoleto.

### encrypt {#encrypt-int-com.aspose.pdf.CryptoAlgorithm-com.aspose.ms.System.Collections.Generic.IGenericList-}
Criptografa o documento.

### encrypt {#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.CryptoAlgorithm-boolean-}
Criptografa o documento.

### encrypt {#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
Criptografa o documento.

### encrypt {#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-}
Criptografa o documento.

### encrypt {#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-boolean-}
Criptografa o documento.

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
Remove todos os campos do documento e coloca seus valores no lugar.

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

Obtém as ações do documento.

**Returns:**
Objeto DocumentActionCollection

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
Objeto java.awt.Color

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

Obtém as configurações de segurança se o documento estiver criptografado.

**Returns:**
Elemento CryptoAlgorithm ou nulo

### getCustomSecurityHandler {#getCustomSecurityHandler--}
```
public com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler getCustomSecurityHandler()
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
@Deprecated public DestinationCollection getDestinations()
```

Obsoleto.

**Returns:**
Objeto DestinationCollection

### getDirection {#getDirection--}
```
public Direction getDirection()
```

Obtém a ordem de leitura do texto: L2R (da esquerda para a direita) ou R2L (da direita para a esquerda).

**Returns:**
Elemento Direction

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

Instância de IPdfDocument usada para acessar a estrutura interna do documento.

**Returns:**
Objeto IPdfDocument

### getFileName {#getFileName--}
```
public String getFileName()
```

Nome do arquivo PDF que causou este documento

**Returns:**
valor String

### getFileSizeLimitToMemoryLoading {#getFileSizeLimitToMemoryLoading--}
```
public static int getFileSizeLimitToMemoryLoading()
```

Obtém e define o limite de tamanho de arquivo para carregar um arquivo inteiro na memória.

**Returns:**
valor int

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

Obtém ou define a bandeira de ignorar erros nos arquivos de origem.

**Returns:**
valores booleanos

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

Metadados do documento.

**Returns:**
Objeto Metadata

### getMetadataStream {#getMetadataStream--}
```
public com.aspose.pdf.engine.data.types.IPdfStreamAccessor getMetadataStream()
```

Somente para uso interno!

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
Elemento PageMode

### getObjectById {#getObjectById-java.lang.String-}
Obtém um objeto com ID especificado no documento.

### getOpenAction {#getOpenAction--}
```
public IAppointment getOpenAction()
```

Obtém a ação executada na abertura do documento.

**Returns:**
Objeto IAppointment

### getOptimizeSize {#getOptimizeSize--}
```
public boolean getOptimizeSize()
```

Obtém a bandeira de otimização.

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
Elemento PageLayout

### getPageMode {#getPageMode--}
```
public PageMode getPageMode()
```

Obtém o modo de página, especificando como o documento deve ser exibido ao ser aberto.

**Returns:**
Elemento PageMode

### getPages {#getPages--}
```
public PageCollection getPages()
```

Obtém a coleção de páginas do documento.

**Returns:**
valor booleano

### getPdfFormat {#getPdfFormat--}
```
public PdfFormat getPdfFormat()
```

Obtém o formato PDF.

**Returns:**
PdfFormat

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
public ITaggedContent getTaggedContent()
```

Obtém acesso ao conteúdo TaggedPdf.

**Returns:**
Instância ITaggedContent

### getVersion {#getVersion--}
```
public String getVersion()
```

Obtém uma versão do Pdf a partir do cabeçalho do arquivo Pdf.

**Returns:**
Objeto String

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

Obtém a flag que especifica se a posição da janela do documento será centralizada na tela.

**Returns:**
valor booleano

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

Obtém a bandeira que especifica se a barra de título da janela do documento deve exibir o título do documento.

**Returns:**
valor booleano

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

Obtém o status criptografado do documento.

**Returns:**
valor booleano

### isFitWindow {#isFitWindow--}
```
public boolean isFitWindow()
```

Obtém a bandeira que especifica se a janela do documento deve ser redimensionada para caber na primeira página exibida.

**Returns:**
valor booleano

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

Obtém sinalizador que especifica se a barra de menu deve ser ocultada quando o documento está ativo.

**Returns:**
valor booleano

### isHideToolBar {#isHideToolBar--}
```
public boolean isHideToolBar()
```

Obtém sinalizador que especifica se a barra de ferramentas deve ser ocultada quando o documento está ativo.

**Returns:**
valor booleano

### isHideWindowUI {#isHideWindowUI--}
```
public boolean isHideWindowUI()
```

Obtém ou define o sinalizador que especifica se os elementos da interface do usuário devem ser ocultados quando o documento está ativo.

**Returns:**
valor booleano

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

Obtém ou define um valor que indica se o documento está linearizado.

**Returns:**
valor booleano

### isManualDisposeEnabled {#isManualDisposeEnabled--}
```
public boolean isManualDisposeEnabled()
```

Por padrão, o método save fecha fluxos internos e libera recursos de memória.

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

Linearize o documento para - abrir a primeira página o mais rápido possível; - exibir a próxima página ou seguir o link para a próxima página o mais rápido possível; - exibir a página incrementalmente à medida que chega, quando os dados de uma página são entregues por um canal lento (exibir primeiro os dados mais úteis); - permitir que a interação do usuário, como seguir um link, seja realizada mesmo antes que a página inteira tenha sido recebida e exibida.

### optimizeResources {#optimizeResources--}
```
public void optimizeResources()
```

Otimizar recursos no documento: 1.

### optimizeResources {#optimizeResources-com.aspose.pdf.optimization.OptimizationOptions-}
Otimizar recursos no documento de acordo com a estratégia de otimização definida.

### pageNodesToBalancedTree {#pageNodesToBalancedTree--}
```
public void pageNodesToBalancedTree()
```

Organiza os nós da árvore de páginas em um documento em uma árvore balanceada.

### pageNodesToBalancedTree {#pageNodesToBalancedTree-byte-}
```
public void pageNodesToBalancedTree(byte nodesNumInSubtrees)
```

Organiza os nós da árvore de páginas em um documento em uma árvore balanceada.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| nodesNumInSubtrees |  | Número desejado de subnós. O valor padrão é dez. |

### preSave {#preSave-com.aspose.pdf.PageCollection-com.aspose.pdf.SaveOptions-}
Método interno

### processParagraphs {#processParagraphs--}
```
public void processParagraphs()
```

Armazena o documento no gerador.

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

Salvar documento incrementalmente (por exemplo.

### save {#save-javax.servlet.http.HttpServletResponse-java.lang.String-com.aspose.pdf.ContentDisposition-com.aspose.pdf.SaveOptions-}
Salva o documento em um fluxo de resposta com opções de salvamento.

### save {#save-java.io.OutputStream-}
Armazena o documento em um fluxo.

### save {#save-java.io.OutputStream-com.aspose.pdf.SaveFormat-}
Salva o documento com um novo nome juntamente com um formato de arquivo.

### save {#save-java.io.OutputStream-com.aspose.pdf.SaveOptions-}
Salva o documento com um novo nome definindo suas opções de salvamento.

### save {#save-com.aspose.pdf.SaveOptions-}
Salva o documento com opções de salvamento.

### save {#save-com.aspose.ms.System.IO.Stream-}
Somente para uso interno

### save {#save-java.lang.String-}
Salva o documento no arquivo especificado.

### save {#save-java.lang.String-com.aspose.pdf.SaveFormat-}
Salva o documento com um novo nome juntamente com um formato de arquivo.

### save {#save-java.lang.String-com.aspose.pdf.SaveOptions-}
Salva o documento com um novo nome definindo suas opções de salvamento.

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
public void setAbsentFontTryToSubstitute(boolean substitute)
```

Definindo a flag para substituir a fonte ausente.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| substituir |  | valor booleano |

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

Obtém ou define a bandeira de ignorar erros nos arquivos de origem.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valores booleanos |

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

Por padrão, o método save fecha fluxos internos e libera recursos de memória.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| manualDisposeEnabled |  | Valor booleano. (Valor padrão == false) |

### setNonFullScreenPageMode {#setNonFullScreenPageMode-com.aspose.pdf.PageMode-}
Define o modo de página, especificando como exibir o documento ao sair do modo de tela cheia.

### setOpenAction {#setOpenAction-com.aspose.pdf.IAppointment-}
Define a ação executada ao abrir o documento.

### setOptimizeSize {#setOptimizeSize-boolean-}
```
public void setOptimizeSize(boolean value)
```

Define o sinalizador de otimização.

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
