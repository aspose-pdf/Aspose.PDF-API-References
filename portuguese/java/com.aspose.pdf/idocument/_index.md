---
title: "IDocument"
linktitle: "IDocument"
second_title: "Referência da API Aspose.PDF para Java"
description: "interface que representa documento PDF"
type: docs
weight: 2230
url: /pt/java/com.aspose.pdf/idocument/
---
```
public interface IDocument extends com.aspose.ms.System.IDisposable, Closeable
```

interface que representa documento PDF

## Métodos

| Método | Descrição |
| --- | --- |
| [afterImport](#afterImport--) | Enumere todas as anotações registradas e chame AfterImport para cada uma delas. |
| [bindXml](#bindXml-java.io.InputStream-) | Vincular xml ao documento |
| [bindXml](#bindXml-java.lang.String-) | Vincular xml ao documento |
| [bindXml](#bindXml-java.lang.String-java.lang.String-) | Vincular xml/xsl ao documento |
| [changePasswords](#changePasswords-java.lang.String-java.lang.String-java.lang.String-) | Altera as senhas do documento. |
| [check](#check-boolean-) | Valida o documento. |
| [close](#close--) | Fecha todos os recursos usados por este documento. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-) | Converte o documento em documento pesquisável. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-) | Converte o documento em documento pesquisável e ignora erros de hochr que não podem ser convertidos. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-) | Converte o documento e salva os erros no arquivo especificado. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-boolean-) | Converte o documento e salva os erros no arquivo especificado. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocr-boolean-boolean-boolean-boolean-) | Converte o documento e salva os erros no arquivo especificado. <p> Isso permite mostrar/ocultar texto pesquisável na página. O valor padrão é FALSE. Isso permite obter a imagem original do pdf. O valor padrão é FALSE. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrWithPage-boolean-boolean-boolean-boolean-) | Converte o documento e salva os erros no arquivo especificado. <p> Isso permite mostrar/ocultar texto pesquisável na página. O valor padrão é FALSE. Isso permite obter a imagem original do pdf. O valor padrão é FALSE. |
| [convert](#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) |  |
| [convert](#convert-com.aspose.pdf.PdfFormatConversionOptions-) | Converte o documento usando opções de conversão especificadas |
| [convert](#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | Converte o documento e salva os erros no arquivo especificado. |
| [convert](#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-) | Converte o documento e salva os erros no arquivo especificado. |
| [convertInternal](#convertInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | Método interno |
| [convertWithFlatten](#convertWithFlatten-com.aspose.pdf.Document.CallBackGetHocrBase-) | Converte o documento em documento pesquisável e ignora erros de hochr que não podem ser convertidos. |
| [convertWithSkippingErrors](#convertWithSkippingErrors-com.aspose.pdf.Document.CallBackGetHocrBase-) | Converte o documento em documento pesquisável e ignora erros de hochr que não podem ser convertidos. |
| [decrypt](#decrypt--) | Descriptografa o documento. |
| [dispose](#dispose--) | Obsoleto. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.CryptoAlgorithm-boolean-) | Criptografa o documento. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-) | Criptografa o documento. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-boolean-) | Criptografa o documento. |
| [exportAnnotationsToXfdf](#exportAnnotationsToXfdf-java.lang.String-) | Exporta todas as anotações do documento para um arquivo XFDF |
| [flatten](#flatten--) | Remove todos os campos (e anotações) do documento e coloca seus valores no lugar. |
| [flatten](#flatten-com.aspose.pdf.Form.FlattenSettings-) | Remove todos os campos do documento e coloca seus valores no lugar. |
| [flattenTransparency](#flattenTransparency--) | Substitui o conteúdo transparente por gráficos raster e vetoriais não transparentes. |
| [freeMemory](#freeMemory--) | Limpa a memória |
| [getActions](#getActions--) | Obtém as ações do documento. |
| [getBackground](#getBackground--) | Obtém a cor de fundo do documento. |
| [getCatalogValue](#getCatalogValue-java.lang.String-) | Retorna o valor do item do dicionário de catálogo. |
| [getCollection](#getCollection--) | Obtém a coleção do documento. |
| [getCryptoAlgorithm](#getCryptoAlgorithm--) | Obtém as configurações de segurança se o documento estiver criptografado. |
| [getCustomSecurityHandler](#getCustomSecurityHandler--) | Obtém um manipulador de segurança personalizado. |
| [getDefaultCopier](#getDefaultCopier--) | Retorna o copiador usado para copiar páginas para este documento. |
| [getDestinations](#getDestinations--) | Obtém a coleção de destinos. |
| [getDirection](#getDirection--) | Obtém a ordem de leitura do texto: L2R (da esquerda para a direita) ou R2L (da direita para a esquerda). |
| [getDuplex](#getDuplex--) | Obtém ou define a opção de tratamento de modo duplex de impressão a ser usada ao imprimir o arquivo a partir da caixa de diálogo de impressão. |
| [getEmbeddedFiles](#getEmbeddedFiles--) | Obtém a coleção de arquivos incorporados ao documento. |
| [getEmbedStandardFonts](#getEmbedStandardFonts--) | Propriedade que declara que o documento deve incorporar todas as fontes Type1 padrão que têm a bandeira IsEmbedded definida como true. |
| [getEnableSignatureSanitization](#getEnableSignatureSanitization--) | Obtém ou define a bandeira para gerenciar a sanitização de campos de assinatura. |
| [getEngineDoc](#getEngineDoc--) | Instância de IPdfDocument usada para acessar a estrutura interna do documento. |
| [getFileName](#getFileName--) | Nome do arquivo PDF que causou este documento |
| [getForm](#getForm--) | Obtém o Acro Form do documento. |
| [getId](#getId--) | Obtém o ID. |
| [getIgnoreCorruptedObjects](#getIgnoreCorruptedObjects--) | Obtém ou define a bandeira de ignorar erros nos arquivos de origem. |
| [getInfo](#getInfo--) | Obtém as informações do documento. |
| [getLogicalStructure](#getLogicalStructure--) | Obtém a estrutura lógica do documento. |
| [getMetadata](#getMetadata--) | Metadados do documento. |
| [getMetadataStream](#getMetadataStream--) | Retorna fluxo bruto de metadados |
| [getNamedDestinations](#getNamedDestinations--) | Coleção de Destinos Nomeados no documento. |
| [getNonFullScreenPageMode](#getNonFullScreenPageMode--) | Obtém o modo de página, especificando como exibir o documento ao sair do modo de tela cheia. |
| [getObjectById](#getObjectById-java.lang.String-) | Obtém um objeto com ID especificado no documento. |
| [getOpenAction](#getOpenAction--) | Obtém a ação executada na abertura do documento. |
| [getOptimizeSize](#getOptimizeSize--) | Obtém a bandeira de otimização. |
| [getOutlines](#getOutlines--) | Obtém os contornos do documento. |
| [getPageInfo](#getPageInfo--) | Obtém as informações da página.(apenas para gerador, não preenchido ao ler o documento) |
| [getPageLabels](#getPageLabels--) | Obtém os rótulos de página no documento. |
| [getPageLayout](#getPageLayout--) | Obtém o layout de página que será usado quando o documento for aberto. |
| [getPageMode](#getPageMode--) | Obtém o modo de página, especificando como o documento deve ser exibido ao ser aberto. |
| [getPages](#getPages--) | Obtém a coleção de páginas do documento. |
| [getPdfFormat](#getPdfFormat--) |  |
| [getPermissions](#getPermissions--) | Obtém as permissões do documento. |
| [getPrintScaling](#getPrintScaling--) | Obtém a opção de tratamento de dimensionamento de impressão a ser usada ao imprimir o arquivo a partir da caixa de diálogo de impressão. |
| [getTaggedContent](#getTaggedContent--) | Obtém acesso ao conteúdo TaggedPdf. |
| [getVersion](#getVersion--) | Obtém uma versão do Pdf a partir do cabeçalho do arquivo Pdf. |
| [getXmpMetadata](#getXmpMetadata-java.io.OutputStream-) | Obtenha metadados XMP do documento. |
| [importAnnotationsFromXfdf](#importAnnotationsFromXfdf-java.lang.String-) | Importa anotações do arquivo XFDF para o documento. |
| [isAbsentFontTryToSubstitute](#isAbsentFontTryToSubstitute--) | Notificação sobre fontes ausentes ao processar documentos |
| [isCenterWindow](#isCenterWindow--) | Obtém a bandeira que especifica se a posição da janela do documento será centralizada na tela. |
| [isDisableFontLicenseVerifications](#isDisableFontLicenseVerifications--) | Muitas operações com fonte não podem ser executadas se essas operações forem proibidas pela licença desta fonte. |
| [isDisplayDocTitle](#isDisplayDocTitle--) | Obtém a bandeira que especifica se a barra de título da janela do documento deve exibir o título do documento. |
| [isEncrypted](#isEncrypted--) | Obtém o status criptografado do documento. |
| [isFitWindow](#isFitWindow--) | Obtém a bandeira que especifica se a janela do documento deve ser redimensionada para caber na primeira página exibida. |
| [isHideMenubar](#isHideMenubar--) | Obtém sinalizador que especifica se a barra de menu deve ser ocultada quando o documento está ativo. |
| [isHideToolBar](#isHideToolBar--) | Obtém sinalizador que especifica se a barra de ferramentas deve ser ocultada quando o documento está ativo. |
| [isHideWindowUI](#isHideWindowUI--) | Obtém ou define o sinalizador que especifica se os elementos da interface do usuário devem ser ocultados quando o documento está ativo. |
| [isLinearized](#isLinearized--) | Obtém ou define um valor que indica se o documento está linearizado. |
| [isManualDisposeEnabled](#isManualDisposeEnabled--) | Por padrão, o método save fecha fluxos internos e libera recursos de memória. Podemos realizar algumas operações e continuar a trabalhar com o documento após o método save se este parâmetro ManualDispose estiver habilitado. |
| [isPdfaCompliant](#isPdfaCompliant--) | Obtém se o documento está em conformidade com pdf/a. |
| [isPdfUaCompliant](#isPdfUaCompliant--) | Obtém se o documento está em conformidade com pdfua. |
| [isPickTrayByPdfSize](#isPickTrayByPdfSize--) | Obtém um sinalizador que especifica se o tamanho da página PDF deve ser usado para selecionar a bandeja de papel de entrada. |
| [isXrefGapsAllowed](#isXrefGapsAllowed--) | Obtém ou define se o documento está em conformidade com pdfa. |
| [optimize](#optimize--) | Linearize o documento para - abrir a primeira página o mais rápido possível; - exibir a página seguinte ou seguir o link para a próxima página o mais rápido possível; - exibir a página incrementalmente à medida que chega, quando os dados de uma página são entregues por um canal lento (exibir primeiro os dados mais úteis); - permitir que a interação do usuário, como seguir um link, seja realizada mesmo antes que a página inteira tenha sido recebida e exibida. |
| [optimizeResources](#optimizeResources--) | Otimizar recursos no documento: 1. |
| [optimizeResources](#optimizeResources-com.aspose.pdf.optimization.OptimizationOptions-) | Otimizar recursos no documento de acordo com a estratégia de otimização definida. |
| [pageNodesToBalancedTree](#pageNodesToBalancedTree--) | Organiza os nós da árvore de páginas em um documento em uma árvore balanceada. |
| [pageNodesToBalancedTree](#pageNodesToBalancedTree-byte-) | Organiza os nós da árvore de páginas em um documento em uma árvore balanceada. |
| [processParagraphs](#processParagraphs--) | Armazena o documento em um fluxo. |
| [removeMetadata](#removeMetadata--) | Remove metadados do documento. |
| [removePdfaCompliance](#removePdfaCompliance--) | Remover conformidade pdfa do documento |
| [removePdfUaCompliance](#removePdfUaCompliance--) | Remover conformidade pdfUa do documento |
| [repair](#repair--) | Repara documento corrompido. |
| [resumeUpdate](#resumeUpdate--) | resumeUpdate |
| [save](#save--) | Salvar documento incrementalmente (por exemplo. |
| [save](#save-java.io.OutputStream-) | Armazena o documento em um fluxo. |
| [save](#save-java.io.OutputStream-com.aspose.pdf.SaveFormat-) | Salvar documento |
| [save](#save-java.io.OutputStream-com.aspose.pdf.SaveOptions-) | Salva o documento com um novo nome definindo suas opções de salvamento. |
| [save](#save-java.lang.String-) | Salva o documento no arquivo especificado. |
| [save](#save-java.lang.String-com.aspose.pdf.SaveOptions-) | Salva o documento com um novo nome definindo suas opções de salvamento. |
| [saveIncrementally](#saveIncrementally-java.io.OutputStream-) | Salva incrementalmente o Documento PDF no fluxo especificado. |
| [saveIncrementally](#saveIncrementally-com.aspose.ms.System.IO.Stream-) | Salva incrementalmente o Documento PDF no fluxo especificado. |
| [saveIncrementally](#saveIncrementally-java.lang.String-) | Salva incrementalmente o Documento PDF no fluxo especificado. |
| [saveXml](#saveXml-java.lang.String-) | Salvar documento em XML. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.io.OutputStream-) | Envia as páginas específicas do documento para o dispositivo de documento para processamento. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.lang.String-) | Envia o documento inteiro para o dispositivo de documento para processamento. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-java.io.OutputStream-) | Envia o documento inteiro para o dispositivo de documento para processamento. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-java.lang.String-) | Envia o documento inteiro para o dispositivo de documento para processamento. |
| [setAbsentFontTryToSubstitute](#setAbsentFontTryToSubstitute-boolean-) | Definindo sinalizador para definir a fonte determinada pelo programa caso a fonte esteja ausente. |
| [setBackground](#setBackground-java.awt.Color-) | Define a cor de fundo do documento. |
| [setCenterWindow](#setCenterWindow-boolean-) | Define um sinalizador que especifica se a posição da janela do documento será centralizada na tela. |
| [setCollection](#setCollection-com.aspose.pdf.Collection-) | Define a coleção do documento. |
| [setConvertMetadataAndCatalogOnly](#setConvertMetadataAndCatalogOnly-boolean-) | Obtém o parâmetro de conversão para o conversor pdf/ua (Converte apenas Metadados e Catálogo do Documento se definido como verdadeiro). |
| [setDirection](#setDirection-com.aspose.pdf.Direction-) | Define a ordem de leitura do texto: L2R (da esquerda para a direita) ou R2L (da direita para a esquerda). |
| [setDisableFontLicenseVerifications](#setDisableFontLicenseVerifications-boolean-) | Muitas operações com fonte não podem ser executadas se essas operações forem proibidas pela licença desta fonte. |
| [setDisplayDocTitle](#setDisplayDocTitle-boolean-) | Define um sinalizador que especifica se a barra de título da janela do documento deve exibir o título do documento. |
| [setDuplex](#setDuplex-int-) | Obtém ou define a opção de tratamento de modo duplex de impressão a ser usada ao imprimir o arquivo a partir da caixa de diálogo de impressão. |
| [setEmbedStandardFonts](#setEmbedStandardFonts-boolean-) | Propriedade que declara que o documento deve incorporar todas as fontes Type1 padrão que têm a bandeira IsEmbedded definida como true. |
| [setEnableSignatureSanitization](#setEnableSignatureSanitization-boolean-) | Obtém ou define a bandeira para gerenciar a sanitização de campos de assinatura. |
| [setFitWindow](#setFitWindow-boolean-) | Define um sinalizador que especifica se a janela do documento deve ser redimensionada para caber a primeira página exibida. |
| [setHideMenubar](#setHideMenubar-boolean-) | Define um sinalizador que especifica se a barra de menu deve ser ocultada quando o documento está ativo. |
| [setHideToolBar](#setHideToolBar-boolean-) | Define um sinalizador que especifica se a barra de ferramentas deve ser ocultada quando o documento está ativo. |
| [setHideWindowUI](#setHideWindowUI-boolean-) | Define um sinalizador que especifica se os elementos da interface do usuário devem ser ocultados quando o documento está ativo. |
| [setIgnoreCorruptedObjects](#setIgnoreCorruptedObjects-boolean-) |  |
| [setLinearized](#setLinearized-boolean-) | Define um valor que indica se o documento está linearizado. |
| [setManualDisposeEnabled](#setManualDisposeEnabled-boolean-) | Por padrão, o método save fecha os fluxos internos e libera recursos de memória. Podemos realizar algumas operações e continuar trabalhando com o documento após a chamada do método save se este parâmetro ManualDispose estiver habilitado. Mas é altamente recomendado chamar o método dispose quando a instância Document não for mais necessária. |
| [setNonFullScreenPageMode](#setNonFullScreenPageMode-com.aspose.pdf.PageMode-) | Define o modo de página, especificando como exibir o documento ao sair do modo de tela cheia. |
| [setOpenAction](#setOpenAction-com.aspose.pdf.IAppointment-) | Define a ação executada ao abrir o documento. |
| [setOptimizeSize](#setOptimizeSize-boolean-) | Define o sinalizador de otimização. |
| [setPageInfo](#setPageInfo-com.aspose.pdf.PageInfo-) | Define as informações da página. (apenas para gerador, não preenchido ao ler o documento) |
| [setPageLayout](#setPageLayout-com.aspose.pdf.PageLayout-) | Define o layout da página que deve ser usado quando o documento for aberto. |
| [setPageMode](#setPageMode-com.aspose.pdf.PageMode-) | Define o modo de página, especificando como o documento deve ser exibido ao ser aberto. |
| [setPickTrayByPdfSize](#setPickTrayByPdfSize-boolean-) | Define um sinalizador que especifica se o tamanho da página PDF deve ser usado para selecionar a bandeja de papel de entrada. |
| [setPrintScaling](#setPrintScaling-int-) | Define a opção de tratamento de escala de impressão a ser usada ao imprimir o arquivo a partir da caixa de diálogo de impressão. |
| [setTitle](#setTitle-java.lang.String-) | Definir título para o documento PDF |
| [setXmpMetadata](#setXmpMetadata-java.io.InputStream-) | Definir metadados XMP do documento. |
| [setXrefGapsAllowed](#setXrefGapsAllowed-boolean-) | Obtém ou define se o documento está em conformidade com pdfa. |
| [suppressUpdate](#suppressUpdate--) | suppressUpdate |
| [updatePages](#updatePages--) | updatePages |
| [validate](#validate-java.io.OutputStream-com.aspose.pdf.PdfFormat-) | Validar documento no arquivo especificado. |
| [validate](#validate-java.lang.String-com.aspose.pdf.PdfFormat-) | Validar documento no arquivo especificado. |

### afterImport {#afterImport--}
```
void afterImport()
```

Enumere todas as anotações registradas e chame AfterImport para cada uma delas.

### bindXml {#bindXml-java.io.InputStream-}
Vincular xml ao documento

### bindXml {#bindXml-java.lang.String-}
Vincular xml ao documento

### bindXml {#bindXml-java.lang.String-java.lang.String-}
Vincular xml/xsl ao documento

### changePasswords {#changePasswords-java.lang.String-java.lang.String-java.lang.String-}
Altera as senhas do documento.

### check {#check-boolean-}
```
boolean check(boolean doRepair)
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
void close()
```

Fecha todos os recursos usados por este documento.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-}
Converte o documento em documento pesquisável.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-}
Converte o documento em documento pesquisável e ignora erros de hochr que não podem ser convertidos.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-}
Converte o documento e salva os erros no arquivo especificado.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-boolean-}
Converte o documento e salva os erros no arquivo especificado.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocr-boolean-boolean-boolean-boolean-}
Converte o documento e salva os erros no arquivo especificado. <p> Isso permite mostrar/ocultar texto pesquisável na página. O valor padrão é FALSE. Isso permite obter a imagem original do pdf. O valor padrão é FALSE.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrWithPage-boolean-boolean-boolean-boolean-}
Converte o documento e salva os erros no arquivo especificado. <p> Isso permite mostrar/ocultar texto pesquisável na página. O valor padrão é FALSE. Isso permite obter a imagem original do pdf. O valor padrão é FALSE.

### convert {#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}


### convert {#convert-com.aspose.pdf.PdfFormatConversionOptions-}
Converte o documento usando opções de conversão especificadas

### convert {#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
Converte o documento e salva os erros no arquivo especificado.

### convert {#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-}
Converte o documento e salva os erros no arquivo especificado.

### convertInternal {#convertInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
Método interno

### convertWithFlatten {#convertWithFlatten-com.aspose.pdf.Document.CallBackGetHocrBase-}
Converte o documento em documento pesquisável e ignora erros de hochr que não podem ser convertidos.

### convertWithSkippingErrors {#convertWithSkippingErrors-com.aspose.pdf.Document.CallBackGetHocrBase-}
Converte o documento em documento pesquisável e ignora erros de hochr que não podem ser convertidos.

### decrypt {#decrypt--}
```
void decrypt()
```

Descriptografa o documento.

### dispose {#dispose--}
```
@Deprecated void dispose()
```

Obsoleto.

### encrypt {#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.CryptoAlgorithm-boolean-}
Criptografa o documento.

### encrypt {#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-}
Criptografa o documento.

### encrypt {#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-boolean-}
Criptografa o documento.

### exportAnnotationsToXfdf {#exportAnnotationsToXfdf-java.lang.String-}
Exporta todas as anotações do documento para um arquivo XFDF

### flatten {#flatten--}
```
void flatten()
```

Remove todos os campos (e anotações) do documento e coloca seus valores no lugar.

### flatten {#flatten-com.aspose.pdf.Form.FlattenSettings-}
Remove todos os campos do documento e coloca seus valores no lugar.

### flattenTransparency {#flattenTransparency--}
```
void flattenTransparency()
```

Substitui o conteúdo transparente por gráficos raster e vetoriais não transparentes.

### freeMemory {#freeMemory--}
```
void freeMemory()
```

Limpa a memória

### getActions {#getActions--}
```
DocumentActionCollection getActions()
```

Obtém as ações do documento.

**Returns:**
Objeto DocumentActionCollection

### getBackground {#getBackground--}
```
Color getBackground()
```

Obtém a cor de fundo do documento.

**Returns:**
Objeto java.awt.Color

### getCatalogValue {#getCatalogValue-java.lang.String-}
Retorna o valor do item do dicionário de catálogo.

### getCollection {#getCollection--}
```
Collection getCollection()
```

Obtém a coleção do documento.

**Returns:**
Objeto Collection

### getCryptoAlgorithm {#getCryptoAlgorithm--}
```
CryptoAlgorithm getCryptoAlgorithm()
```

Obtém as configurações de segurança se o documento estiver criptografado.

**Returns:**
Elemento CryptoAlgorithm ou nulo

### getCustomSecurityHandler {#getCustomSecurityHandler--}
```
com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler getCustomSecurityHandler()
```

Obtém um manipulador de segurança personalizado.

**Returns:**
Instância ICustomSecurityHandler

### getDefaultCopier {#getDefaultCopier--}
```
Copier getDefaultCopier()
```

Retorna o copiador usado para copiar páginas para este documento.

**Returns:**
Objeto Copier

### getDestinations {#getDestinations--}
```
DestinationCollection getDestinations()
```

Obtém a coleção de destinos.

**Returns:**
Objeto DestinationCollection

### getDirection {#getDirection--}
```
Direction getDirection()
```

Obtém a ordem de leitura do texto: L2R (da esquerda para a direita) ou R2L (da direita para a esquerda).

**Returns:**
Elemento Direction

### getDuplex {#getDuplex--}
```
int getDuplex()
```

Obtém ou define a opção de tratamento de modo duplex de impressão a ser usada ao imprimir o arquivo a partir da caixa de diálogo de impressão.

**Returns:**
Elemento PrintDuplex

### getEmbeddedFiles {#getEmbeddedFiles--}
```
EmbeddedFileCollection getEmbeddedFiles()
```

Obtém a coleção de arquivos incorporados ao documento.

**Returns:**
Objeto EmbeddedFileCollection

### getEmbedStandardFonts {#getEmbedStandardFonts--}
```
boolean getEmbedStandardFonts()
```

Propriedade que declara que o documento deve incorporar todas as fontes Type1 padrão que têm a bandeira IsEmbedded definida como true.

**Returns:**
valor booleano

### getEnableSignatureSanitization {#getEnableSignatureSanitization--}
```
boolean getEnableSignatureSanitization()
```

Obtém ou define a bandeira para gerenciar a sanitização de campos de assinatura.

**Returns:**
valor booleano

### getEngineDoc {#getEngineDoc--}
```
com.aspose.pdf.engine.IPdfDocument getEngineDoc()
```

Instância de IPdfDocument usada para acessar a estrutura interna do documento.

**Returns:**
Objeto IPdfDocument

### getFileName {#getFileName--}
```
String getFileName()
```

Nome do arquivo PDF que causou este documento

**Returns:**
Objeto String

### getForm {#getForm--}
```
Form getForm()
```

Obtém o Acro Form do documento.

**Returns:**
Objeto Form

### getId {#getId--}
```
Id getId()
```

Obtém o ID.

**Returns:**
Objeto Id

### getIgnoreCorruptedObjects {#getIgnoreCorruptedObjects--}
```
boolean getIgnoreCorruptedObjects()
```

Obtém ou define a bandeira de ignorar erros nos arquivos de origem.

**Returns:**
valor booleano

### getInfo {#getInfo--}
```
DocumentInfo getInfo()
```

Obtém as informações do documento.

**Returns:**
Objeto DocumentInfo

### getLogicalStructure {#getLogicalStructure--}
```
RootElement getLogicalStructure()
```

Obtém a estrutura lógica do documento.

**Returns:**
Objeto RootElement

### getMetadata {#getMetadata--}
```
Metadata getMetadata()
```

Metadados do documento.

**Returns:**
Objeto Metadata

### getMetadataStream {#getMetadataStream--}
```
com.aspose.pdf.engine.data.types.IPdfStreamAccessor getMetadataStream()
```

Retorna fluxo bruto de metadados

**Returns:**
Objeto IPdfStreamAccessor

### getNamedDestinations {#getNamedDestinations--}
```
NamedDestinationCollection getNamedDestinations()
```

Coleção de Destinos Nomeados no documento.

**Returns:**
Instância NamedDestinationCollection

### getNonFullScreenPageMode {#getNonFullScreenPageMode--}
```
PageMode getNonFullScreenPageMode()
```

Obtém o modo de página, especificando como exibir o documento ao sair do modo de tela cheia.

**Returns:**
Elemento PageMode

### getObjectById {#getObjectById-java.lang.String-}
Obtém um objeto com ID especificado no documento.

### getOpenAction {#getOpenAction--}
```
IAppointment getOpenAction()
```

Obtém a ação executada na abertura do documento.

**Returns:**
Objeto IAppointment

### getOptimizeSize {#getOptimizeSize--}
```
boolean getOptimizeSize()
```

Obtém a bandeira de otimização.

**Returns:**
valor booleano

### getOutlines {#getOutlines--}
```
OutlineCollection getOutlines()
```

Obtém os contornos do documento.

**Returns:**
Objeto OutlineCollection

### getPageInfo {#getPageInfo--}
```
PageInfo getPageInfo()
```

Obtém as informações da página.(apenas para gerador, não preenchido ao ler o documento)

**Returns:**
As informações da página.

### getPageLabels {#getPageLabels--}
```
PageLabelCollection getPageLabels()
```

Obtém os rótulos de página no documento.

**Returns:**
Objeto PageLabelCollection

### getPageLayout {#getPageLayout--}
```
PageLayout getPageLayout()
```

Obtém o layout de página que será usado quando o documento for aberto.

**Returns:**
Elemento PageLayout

### getPageMode {#getPageMode--}
```
PageMode getPageMode()
```

Obtém o modo de página, especificando como o documento deve ser exibido ao ser aberto.

**Returns:**
Elemento PageMode

### getPages {#getPages--}
```
PageCollection getPages()
```

Obtém a coleção de páginas do documento.

**Returns:**
valor booleano

### getPdfFormat {#getPdfFormat--}
```
PdfFormat getPdfFormat()
```



**Returns:**
Elemento PdfFormat

### getPermissions {#getPermissions--}
```
int getPermissions()
```

Obtém as permissões do documento.

**Returns:**
valor int

### getPrintScaling {#getPrintScaling--}
```
int getPrintScaling()
```

Obtém a opção de tratamento de dimensionamento de impressão a ser usada ao imprimir o arquivo a partir da caixa de diálogo de impressão.

**Returns:**
Elemento PrintScaling

### getTaggedContent {#getTaggedContent--}
```
ITaggedContent getTaggedContent()
```

Obtém acesso ao conteúdo TaggedPdf.

**Returns:**
Instância ITaggedContent

### getVersion {#getVersion--}
```
String getVersion()
```

Obtém uma versão do Pdf a partir do cabeçalho do arquivo Pdf.

**Returns:**
Objeto String

### getXmpMetadata {#getXmpMetadata-java.io.OutputStream-}
Obtenha metadados XMP do documento.

### importAnnotationsFromXfdf {#importAnnotationsFromXfdf-java.lang.String-}
Importa anotações do arquivo XFDF para o documento.

### isAbsentFontTryToSubstitute {#isAbsentFontTryToSubstitute--}
```
boolean isAbsentFontTryToSubstitute()
```

Notificação sobre fontes ausentes ao processar documentos

**Returns:**
valor booleano

### isCenterWindow {#isCenterWindow--}
```
boolean isCenterWindow()
```

Obtém a bandeira que especifica se a posição da janela do documento será centralizada na tela.

**Returns:**
valor booleano

### isDisableFontLicenseVerifications {#isDisableFontLicenseVerifications--}
```
boolean isDisableFontLicenseVerifications()
```

Muitas operações com fonte não podem ser executadas se essas operações forem proibidas pela licença desta fonte.

**Returns:**
Valor booleano por padrão false.

### isDisplayDocTitle {#isDisplayDocTitle--}
```
boolean isDisplayDocTitle()
```

Obtém a bandeira que especifica se a barra de título da janela do documento deve exibir o título do documento.

**Returns:**
valor booleano

### isEncrypted {#isEncrypted--}
```
boolean isEncrypted()
```

Obtém o status criptografado do documento.

**Returns:**
valor booleano

### isFitWindow {#isFitWindow--}
```
boolean isFitWindow()
```

Obtém a bandeira que especifica se a janela do documento deve ser redimensionada para caber na primeira página exibida.

**Returns:**
valor booleano

### isHideMenubar {#isHideMenubar--}
```
boolean isHideMenubar()
```

Obtém sinalizador que especifica se a barra de menu deve ser ocultada quando o documento está ativo.

**Returns:**
valor booleano

### isHideToolBar {#isHideToolBar--}
```
boolean isHideToolBar()
```

Obtém sinalizador que especifica se a barra de ferramentas deve ser ocultada quando o documento está ativo.

**Returns:**
valor booleano

### isHideWindowUI {#isHideWindowUI--}
```
boolean isHideWindowUI()
```

Obtém ou define o sinalizador que especifica se os elementos da interface do usuário devem ser ocultados quando o documento está ativo.

**Returns:**
valor booleano

### isLinearized {#isLinearized--}
```
boolean isLinearized()
```

Obtém ou define um valor que indica se o documento está linearizado.

**Returns:**
valor booleano

### isManualDisposeEnabled {#isManualDisposeEnabled--}
```
boolean isManualDisposeEnabled()
```

Por padrão, o método save fecha fluxos internos e libera recursos de memória. Podemos realizar algumas operações e continuar a trabalhar com o documento após o método save se este parâmetro ManualDispose estiver habilitado.

**Returns:**
Valor booleano. (Valor padrão == false)

### isPdfaCompliant {#isPdfaCompliant--}
```
boolean isPdfaCompliant()
```

Obtém se o documento está em conformidade com pdf/a.

**Returns:**
valor booleano

### isPdfUaCompliant {#isPdfUaCompliant--}
```
boolean isPdfUaCompliant()
```

Obtém se o documento está em conformidade com pdfua.

**Returns:**
valor booleano

### isPickTrayByPdfSize {#isPickTrayByPdfSize--}
```
boolean isPickTrayByPdfSize()
```

Obtém um sinalizador que especifica se o tamanho da página PDF deve ser usado para selecionar a bandeja de papel de entrada.

**Returns:**
valor booleano

### isXrefGapsAllowed {#isXrefGapsAllowed--}
```
boolean isXrefGapsAllowed()
```

Obtém ou define se o documento está em conformidade com pdfa.

**Returns:**
valor booleano

### optimize {#optimize--}
```
void optimize()
```

Linearize o documento para - abrir a primeira página o mais rápido possível; - exibir a página seguinte ou seguir o link para a próxima página o mais rápido possível; - exibir a página incrementalmente à medida que chega, quando os dados de uma página são entregues por um canal lento (exibir primeiro os dados mais úteis); - permitir que a interação do usuário, como seguir um link, seja realizada mesmo antes que a página inteira tenha sido recebida e exibida.

### optimizeResources {#optimizeResources--}
```
void optimizeResources()
```

Otimizar recursos no documento: 1.

### optimizeResources {#optimizeResources-com.aspose.pdf.optimization.OptimizationOptions-}
Otimizar recursos no documento de acordo com a estratégia de otimização definida.

### pageNodesToBalancedTree {#pageNodesToBalancedTree--}
```
void pageNodesToBalancedTree()
```

Organiza os nós da árvore de páginas em um documento em uma árvore balanceada.

### pageNodesToBalancedTree {#pageNodesToBalancedTree-byte-}
```
void pageNodesToBalancedTree(byte nodesNumInSubtrees)
```

Organiza os nós da árvore de páginas em um documento em uma árvore balanceada.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| nodesNumInSubtrees |  | Número desejado de subnós. O valor padrão é dez. |

### processParagraphs {#processParagraphs--}
```
void processParagraphs()
```

Armazena o documento em um fluxo.

### removeMetadata {#removeMetadata--}
```
void removeMetadata()
```

Remove metadados do documento.

### removePdfaCompliance {#removePdfaCompliance--}
```
void removePdfaCompliance()
```

Remover conformidade pdfa do documento

### removePdfUaCompliance {#removePdfUaCompliance--}
```
void removePdfUaCompliance()
```

Remover conformidade pdfUa do documento

### repair {#repair--}
```
void repair()
```

Repara documento corrompido.

### resumeUpdate {#resumeUpdate--}
```
void resumeUpdate()
```

resumeUpdate

### save {#save--}
```
void save()
```

Salvar documento incrementalmente (por exemplo.

### save {#save-java.io.OutputStream-}
Armazena o documento em um fluxo.

### save {#save-java.io.OutputStream-com.aspose.pdf.SaveFormat-}
Salvar documento

### save {#save-java.io.OutputStream-com.aspose.pdf.SaveOptions-}
Salva o documento com um novo nome definindo suas opções de salvamento.

### save {#save-java.lang.String-}
Salva o documento no arquivo especificado.

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

### setAbsentFontTryToSubstitute {#setAbsentFontTryToSubstitute-boolean-}
```
void setAbsentFontTryToSubstitute(boolean setAbsentFontTryToSubstitute)
```

Definindo sinalizador para definir a fonte determinada pelo programa caso a fonte esteja ausente.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| setAbsentFontTryToSubstitute |  | valor booleano |

### setBackground {#setBackground-java.awt.Color-}
Define a cor de fundo do documento.

### setCenterWindow {#setCenterWindow-boolean-}
```
void setCenterWindow(boolean value)
```

Define um sinalizador que especifica se a posição da janela do documento será centralizada na tela.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setCollection {#setCollection-com.aspose.pdf.Collection-}
Define a coleção do documento.

### setConvertMetadataAndCatalogOnly {#setConvertMetadataAndCatalogOnly-boolean-}
```
void setConvertMetadataAndCatalogOnly(boolean value)
```

Obtém o parâmetro de conversão para o conversor pdf/ua (Converte apenas Metadados e Catálogo do Documento se definido como verdadeiro).

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setDirection {#setDirection-com.aspose.pdf.Direction-}
Define a ordem de leitura do texto: L2R (da esquerda para a direita) ou R2L (da direita para a esquerda).

### setDisableFontLicenseVerifications {#setDisableFontLicenseVerifications-boolean-}
```
void setDisableFontLicenseVerifications(boolean value)
```

Muitas operações com fonte não podem ser executadas se essas operações forem proibidas pela licença desta fonte.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | Valor booleano por padrão false. |

### setDisplayDocTitle {#setDisplayDocTitle-boolean-}
```
void setDisplayDocTitle(boolean value)
```

Define um sinalizador que especifica se a barra de título da janela do documento deve exibir o título do documento.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setDuplex {#setDuplex-int-}
```
void setDuplex(int value)
```

Obtém ou define a opção de tratamento de modo duplex de impressão a ser usada ao imprimir o arquivo a partir da caixa de diálogo de impressão.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | Elemento PrintDuplex |

### setEmbedStandardFonts {#setEmbedStandardFonts-boolean-}
```
void setEmbedStandardFonts(boolean value)
```

Propriedade que declara que o documento deve incorporar todas as fontes Type1 padrão que têm a bandeira IsEmbedded definida como true.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setEnableSignatureSanitization {#setEnableSignatureSanitization-boolean-}
```
void setEnableSignatureSanitization(boolean value)
```

Obtém ou define a bandeira para gerenciar a sanitização de campos de assinatura.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setFitWindow {#setFitWindow-boolean-}
```
void setFitWindow(boolean value)
```

Define um sinalizador que especifica se a janela do documento deve ser redimensionada para caber a primeira página exibida.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setHideMenubar {#setHideMenubar-boolean-}
```
void setHideMenubar(boolean value)
```

Define um sinalizador que especifica se a barra de menu deve ser ocultada quando o documento está ativo.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setHideToolBar {#setHideToolBar-boolean-}
```
void setHideToolBar(boolean value)
```

Define um sinalizador que especifica se a barra de ferramentas deve ser ocultada quando o documento está ativo.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setHideWindowUI {#setHideWindowUI-boolean-}
```
void setHideWindowUI(boolean value)
```

Define um sinalizador que especifica se os elementos da interface do usuário devem ser ocultados quando o documento está ativo.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setIgnoreCorruptedObjects {#setIgnoreCorruptedObjects-boolean-}
```
void setIgnoreCorruptedObjects(boolean value)
```



### setLinearized {#setLinearized-boolean-}
```
void setLinearized(boolean value)
```

Define um valor que indica se o documento está linearizado.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setManualDisposeEnabled {#setManualDisposeEnabled-boolean-}
```
void setManualDisposeEnabled(boolean manualDisposeEnabled)
```

Por padrão, o método save fecha os fluxos internos e libera recursos de memória. Podemos realizar algumas operações e continuar trabalhando com o documento após a chamada do método save se este parâmetro ManualDispose estiver habilitado. Mas é altamente recomendado chamar o método dispose quando a instância Document não for mais necessária.

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
void setOptimizeSize(boolean value)
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
void setPickTrayByPdfSize(boolean value)
```

Define um sinalizador que especifica se o tamanho da página PDF deve ser usado para selecionar a bandeja de papel de entrada.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setPrintScaling {#setPrintScaling-int-}
```
void setPrintScaling(int value)
```

Define a opção de tratamento de escala de impressão a ser usada ao imprimir o arquivo a partir da caixa de diálogo de impressão.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | Elemento PrintDuplex |

### setTitle {#setTitle-java.lang.String-}
Definir título para o documento PDF

### setXmpMetadata {#setXmpMetadata-java.io.InputStream-}
Definir metadados XMP do documento.

### setXrefGapsAllowed {#setXrefGapsAllowed-boolean-}
```
void setXrefGapsAllowed(boolean value)
```

Obtém ou define se o documento está em conformidade com pdfa.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### suppressUpdate {#suppressUpdate--}
```
void suppressUpdate()
```

suppressUpdate

### updatePages {#updatePages--}
```
void updatePages()
```

updatePages

### validate {#validate-java.io.OutputStream-com.aspose.pdf.PdfFormat-}
Validar documento no arquivo especificado.

### validate {#validate-java.lang.String-com.aspose.pdf.PdfFormat-}
Validar documento no arquivo especificado.
