---
title: "PdfFileEditorWeb"
linktitle: "PdfFileEditorWeb"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa a classe PdfFileEditorWeb que implementa operações com arquivos PDF: concatenação, divisão, extração de páginas, criação de livrinho, etc."
type: docs
weight: 480
url: /pt/java/com.aspose.pdf.facades/pdffileeditorweb/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.PdfFileEditorWeb

**All Implemented Interfaces:**
IPdfFileEditor

```
public final class PdfFileEditorWeb extends Object implements IPdfFileEditor
```

Representa a classe PdfFileEditorWeb que implementa operações com arquivos PDF: concatenação, divisão, extração de páginas, criação de livrinho, etc.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [PdfFileEditorWeb](#PdfFileEditorWeb--) | Construtor de PdfFileEditorWeb. |

## Métodos

| Método | Descrição |
| --- | --- |
| [addMargins](#addMargins-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-) | Redimensiona o conteúdo da página e adiciona margens especificadas. |
| [addMargins](#addMargins-java.lang.String-java.lang.String-int:A-double-double-double-double-) | Redimensiona o conteúdo da página e adiciona margens especificadas. |
| [addMarginsPct](#addMarginsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-) | Redimensiona o conteúdo da página e adiciona margens especificadas. |
| [addMarginsPct](#addMarginsPct-java.lang.String-java.lang.String-int:A-double-double-double-double-) | Redimensiona o conteúdo da página e adiciona margens especificadas. |
| [addPageBreak](#addPageBreak-com.aspose.pdf.Document-com.aspose.pdf.Document-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | Adiciona quebras de página nas páginas do documento. |
| [addPageBreak](#addPageBreak-com.aspose.pdf.IDocument-com.aspose.pdf.IDocument-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | Adiciona quebras de página nas páginas do documento. |
| [addPageBreak](#addPageBreak-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | Adiciona quebras de página nas páginas do documento. |
| [addPageBreak](#addPageBreak-java.lang.String-java.lang.String-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | Adiciona quebras de página nas páginas do documento. |
| [append](#append-java.io.InputStream-java.io.InputStream:A-int-int-javax.servlet.http.HttpServletResponse-) | Anexa documentos ao documento de origem e salva o resultado no objeto de resposta. |
| [append](#append-java.io.InputStream-java.io.InputStream:A-int-int-java.io.OutputStream-) | Anexa páginas, que são escolhidas a partir de um array de documentos em portStreams. |
| [append](#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-) | Anexa páginas, que são escolhidas de portStream dentro do intervalo de startPage a endPage, em portStream no final de firstInputStream. |
| [append](#append-java.lang.String-java.lang.String:A-int-int-javax.servlet.http.HttpServletResponse-) | Anexa documentos ao documento de origem e salva o resultado no objeto HttpServletResponse. |
| [append](#append-java.lang.String-java.lang.String:A-int-int-java.lang.String-) | Anexa páginas, que são escolhidas dos documentos portFiles. |
| [append](#append-java.lang.String-java.lang.String-int-int-java.lang.String-) | Anexa páginas, que são escolhidas de portFile dentro do intervalo de startPage a endPage, em portFile no final de firstInputFile. |
| [concatenate](#concatenate-com.aspose.pdf.IDocument:A-com.aspose.pdf.IDocument-) | Concatena documentos. |
| [concatenate](#concatenate-java.io.InputStream:A-javax.servlet.http.HttpServletResponse-) | Concatena arquivos e armazena o resultado no objeto HttpServletResponse. |
| [concatenate](#concatenate-java.io.InputStream:A-java.io.OutputStream-) | Concatena arquivos |
| [concatenate](#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | Mescla dois documentos Pdf em um novo documento Pdf com páginas de forma alternada e preenche os espaços vazios com páginas em branco. |
| [concatenate](#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | Concatena dois arquivos. |
| [concatenate](#concatenate-java.lang.String:A-javax.servlet.http.HttpServletResponse-) | Concatena arquivos e salva reslt no objeto HttpResposnse. |
| [concatenate](#concatenate-java.lang.String:A-java.lang.String-) | Concatena arquivos em um único arquivo. |
| [concatenate](#concatenate-java.lang.String-java.lang.String-java.lang.String-) | Concatena dois arquivos. |
| [concatenate](#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | Mescla dois documentos Pdf em um novo documento Pdf com páginas de forma alternada e preenche os espaços vazios com páginas em branco. |
| [createArrayWithExclusion](#createArrayWithExclusion-int-int-) |  |
| [delete](#delete-java.io.InputStream-int:A-javax.servlet.http.HttpServletResponse-) | Exclui páginas especificadas do documento e salva o resultado no objeto HttpServletResponse. |
| [delete](#delete-java.io.InputStream-int:A-java.io.OutputStream-) | Exclui páginas especificadas por um array de números do arquivo de entrada, salva como um novo arquivo Pdf. |
| [delete](#delete-java.lang.String-int:A-javax.servlet.http.HttpServletResponse-) | Exclui páginas especificadas do documento e armazena o resultado no objeto HttpServletResponse. |
| [delete](#delete-java.lang.String-int:A-java.lang.String-) | Exclui páginas especificadas por um array de números do arquivo de entrada, salva como um novo arquivo Pdf. |
| [extract](#extract-java.io.InputStream-int:A-javax.servlet.http.HttpServletResponse-) | Extrai páginas especificadas do arquivo de origem e armazena o resultado no objeto HttpServletResponse. |
| [extract](#extract-java.io.InputStream-int:A-java.io.OutputStream-) | Extrai páginas especificadas por um array de números, salva como um novo arquivo Pdf. |
| [extract](#extract-java.io.InputStream-int-int-java.io.OutputStream-) | Extrai páginas do arquivo de entrada, salva como um novo arquivo Pdf. |
| [extract](#extract-java.lang.String-int:A-javax.servlet.http.HttpServletResponse-) | Extrai páginas especificadas do arquivo de origem e armazena o resultado no objeto HttpServletResponse. |
| [extract](#extract-java.lang.String-int:A-java.lang.String-) | Extrai páginas especificadas por um array de números, salva como um novo arquivo PDF. |
| [extract](#extract-java.lang.String-int-int-java.lang.String-) | Extrai páginas do arquivo de entrada, salva como um novo arquivo Pdf. |
| [getAllowConcatenateExceptions](#getAllowConcatenateExceptions--) | Obsoleto. Esta propriedade está obsoleta e não pode ser usada para permitir lançar exceções. |
| [getAttachmentName](#getAttachmentName--) | Obtém o nome do anexo quando o resultado da operação é armazenado em objetos HttpServletResponse como anexo. |
| [getCloseConcatenatedStreams](#getCloseConcatenatedStreams--) | Se definido como true, os streams são fechados após a operação. |
| [getConcatenationPacketSize](#getConcatenationPacketSize--) | Número de documentos concatenados antes de uma nova atualização incremental ser feita durante a concatenação quando UseDiskBuffer está definido como true. |
| [getContentDisposition](#getContentDisposition--) | Obtém como o conteúdo será armazenado quando o resultado da operação for armazenado no objeto HttpServletResponse. |
| [getConversionLog](#getConversionLog--) | Obtém o registro do processo de conversão. |
| [getCopyLogicalStructure](#getCopyLogicalStructure--) | Se true, a estrutura lógica do arquivo é copiada quando a concatenação é realizada. |
| [getCopyOutlines](#getCopyOutlines--) | Se true, os contornos serão copiados. |
| [getCorruptedFileAction](#getCorruptedFileAction--) | Esta propriedade define o comportamento ao concatenar quando o processo encontra um arquivo corrompido. |
| [getCorruptedItems](#getCorruptedItems--) | Array de problemas encontrados quando a concatenação foi realizada. |
| [getCustomProgressConcatenationHandler](#getCustomProgressConcatenationHandler--) | Representação do processador interno de eventos de progresso que funciona durante a concatenação e traduz eventos de concatenação das etapas internas de concatenação para o código externo do cliente. |
| [getIncrementalUpdates](#getIncrementalUpdates--) | Se true, atualizações incrementais são feitas durante a concatenação. |
| [getKeepActions](#getKeepActions--) | Se true, as ações serão copiadas dos documentos de origem. |
| [getKeepFieldsUnique](#getKeepFieldsUnique--) | Se verdadeiro, os nomes dos campos serão tornados únicos quando os formulários forem concatenados. |
| [getLastException](#getLastException--) | Obtém a última exceção ocorrida. |
| [getMergeDuplicateLayers](#getMergeDuplicateLayers--) | Conteúdos opcionais de documentos concatenados com nomes iguais serão mesclados em uma única camada no documento resultante se esta propriedade for true. |
| [getMergeDuplicateOutlines](#getMergeDuplicateOutlines--) | Se true, contornos duplicados são mesclados. |
| [getOptimizeSize](#getOptimizeSize--) | Obtém ou define a bandeira de otimização. |
| [getOwnerPassword](#getOwnerPassword--) | Obtém a senha do proprietário se o arquivo PDF de entrada estiver criptografado. |
| [getPreserveUserRights](#getPreserveUserRights--) | Se verdadeiro, os direitos de usuário do primeiro documento são aplicados ao documento concatenado. |
| [getRemoveSignatures](#getRemoveSignatures--) | Se verdadeiro, todas as assinaturas serão removidas dos campos (os campos permanecerão); caso contrário, você pode obter assinaturas inválidas. |
| [getSaveOptions](#getSaveOptions--) | Obtém ou define as opções de salvamento quando o resultado é armazenado como HttpServletResponse. |
| [getUniqueSuffix](#getUniqueSuffix--) | Obtém o formato do sufixo que é adicionado ao nome do campo para torná-lo único quando os formulários são concatenados. |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int:A-javax.servlet.http.HttpServletResponse-) | Insere o documento em outro documento e armazena o resultado no objeto de resposta. |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int:A-java.io.OutputStream-) | Insere páginas de outro arquivo no arquivo PDF de entrada. |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-) | Insere páginas de outro arquivo no arquivo PDF de entrada. |
| [insert](#insert-java.lang.String-int-java.lang.String-int:A-javax.servlet.http.HttpServletResponse-) | Insere o conteúdo do arquivo no arquivo de origem e armazena o resultado no objeto HttpServletResponse. |
| [insert](#insert-java.lang.String-int-java.lang.String-int:A-java.lang.String-) | Insere páginas de outro arquivo no arquivo PDF de entrada. |
| [insert](#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-) | Insere páginas de outro arquivo no arquivo PDF em uma posição. |
| [isTryMergeAdjacentSameBackgroundImages](#isTryMergeAdjacentSameBackgroundImages--) | Às vezes, PDFs contêm imagens de fundo (de páginas ou células de tabela) construídas a partir de várias imagens de fundo em mosaico iguais colocadas próximas umas das outras. |
| [isUseDiskBuffer](#isUseDiskBuffer--) | Se esta opção for usada, o documento de destino será salvo no disco periodicamente e concatenações subsequentes serão aplicadas a ele como atualizações incrementais. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-) | Cria um livreto a partir do InputStream para outputStream. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-int:A-int:A-) | Cria um livreto personalizado a partir do firstInputStream para outputStream. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-) | Cria um livreto a partir do fluxo de entrada e salva o resultado no fluxo de saída. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int:A-int:A-) | Cria um livreto a partir do firstInputStream para outputStream. |
| [makeBooklet](#makeBooklet-java.io.InputStream-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-) | Cria um livreto a partir do arquivo de origem e armazena o resultado no HttpServletResponse. |
| [makeBooklet](#makeBooklet-java.io.InputStream-com.aspose.pdf.PageSize-int:A-int:A-javax.servlet.http.HttpServletResponse-) | Cria um livreto a partir de um arquivo PDF e o armazena no HttpServletResponse. |
| [makeBooklet](#makeBooklet-java.lang.String-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-) | Cria um livreto a partir do arquivo de origem e armazena o resultado nos objetos HttpServletResponse. |
| [makeBooklet](#makeBooklet-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-javax.servlet.http.HttpServletResponse-) | Cria um livreto a partir do arquivo de origem e armazena o resultado nos objetos HttpServletResponse. |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-) | Cria um livreto a partir do arquivo de entrada para o arquivo de saída. |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-int:A-int:A-) | Cria um livreto personalizado a partir do firstInputFile para outputFile. |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-) | Cria um livreto a partir do inputFile para outputFile. |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-) | Cria um livreto personalizado a partir do firstInputFile para outputFile. |
| [makeNUp](#makeNUp-java.io.InputStream:A-java.io.OutputStream-boolean-) | Cria um documento N-Up a partir de múltiplos fluxos PDF de entrada para outputStream. |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | Cria um documento N-Up a partir de dois fluxos PDF de entrada para outputStream. |
| [makeNUp](#makeNUp-java.io.InputStream-int-int-javax.servlet.http.HttpServletResponse-) | Cria um documento N-up e armazena o resultado no HttpServletResponse. |
| [makeNUp](#makeNUp-java.io.InputStream-int-int-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-) | Cria um documento N-up e armazena o resultado no objeto HttpServletResponse. |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-) | Cria um documento N-Up a partir do fluxo de entrada e salva o resultado no fluxo de saída. |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-) | Cria um documento N-Up a partir do primeiro fluxo de entrada para o fluxo de saída. |
| [makeNUp](#makeNUp-java.lang.String:A-java.lang.String-boolean-) | Cria um documento N-Up a partir de múltiplos arquivos PDF de entrada para outputFile. |
| [makeNUp](#makeNUp-java.lang.String-int-int-javax.servlet.http.HttpServletResponse-) | Cria um documento N-up e armazena o resultado no HttpServletResponse. |
| [makeNUp](#makeNUp-java.lang.String-int-int-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-) | Cria um documento N-up e armazena o resultado no objeto HttpServletResponse. |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-int-int-) | Cria um documento N-Up a partir do firstInputFile para outputFile. |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-) | Cria um documento N-Up a partir do arquivo de entrada para outputFile. |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-java.lang.String-) | Cria um documento N-Up a partir de dois arquivos PDF de entrada para outputFile. |
| [resizeContents](#resizeContents-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Redimensiona páginas do documento. |
| [resizeContents](#resizeContents-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Redimensiona páginas do documento. |
| [resizeContents](#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-double-double-) | Redimensiona o conteúdo das páginas do documento. |
| [resizeContents](#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Redimensiona o conteúdo das páginas do documento. |
| [resizeContents](#resizeContents-com.aspose.ms.System.IO.Stream-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-javax.servlet.http.HttpServletResponse-) | Redimensiona o conteúdo das páginas no documento. |
| [resizeContents](#resizeContents-java.lang.String-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-javax.servlet.http.HttpServletResponse-) | Redimensiona o conteúdo das páginas no documento. |
| [resizeContents](#resizeContents-java.lang.String-java.lang.String-int:A-double-double-) | Redimensiona o conteúdo das páginas do documento. |
| [resizeContents](#resizeContents-java.lang.String-java.lang.String-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Redimensiona o conteúdo das páginas no documento. |
| [resizeContentsPct](#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-) | Redimensiona o conteúdo das páginas do documento. |
| [resizeContentsPct](#resizeContentsPct-java.lang.String-java.lang.String-int:A-double-double-) | Redimensiona o conteúdo das páginas do documento. |
| [resizeContentsWithNormalization](#resizeContentsWithNormalization-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Redimensiona páginas do documento. |
| [resizeContentsWithNormalization](#resizeContentsWithNormalization-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Redimensiona páginas do documento. |
| [setAllowConcatenateExceptions](#setAllowConcatenateExceptions-boolean-) | Obsoleto. Esta propriedade está obsoleta e não pode ser usada para permitir lançar exceções. |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | Define o nome do anexo quando o resultado da operação é armazenado em objetos HttpServletResponse como anexo. |
| [setCloseConcatenatedStreams](#setCloseConcatenatedStreams-boolean-) | Se definido como true, os streams são fechados após a operação. |
| [setConcatenationPacketSize](#setConcatenationPacketSize-int-) | Número de documentos concatenados antes de uma nova atualização incremental ser feita durante a concatenação quando UseDiskBuffer está definido como true. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | Define como o conteúdo será armazenado quando o resultado da operação for armazenado no objeto HttpServletResponse. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | Define o formato do arquivo PDF. |
| [setCopyLogicalStructure](#setCopyLogicalStructure-boolean-) | Se true, a estrutura lógica do arquivo é copiada quando a concatenação é realizada. |
| [setCopyOutlines](#setCopyOutlines-boolean-) | Se true, os contornos serão copiados. |
| [setCorruptedFileAction](#setCorruptedFileAction-int-) | Esta propriedade define o comportamento ao concatenar quando o processo encontra um arquivo corrompido. |
| [setCustomProgressConcatenationHandler](#setCustomProgressConcatenationHandler-com.aspose.pdf.facades.PdfFileEditor.ConcatenationProgressHandler-) | Representação do processador interno de eventos de progresso que funciona durante a concatenação e traduz eventos de concatenação das etapas internas de concatenação para o código externo do cliente. |
| [setIncrementalUpdates](#setIncrementalUpdates-boolean-) | Se true, atualizações incrementais são feitas durante a concatenação. |
| [setKeepActions](#setKeepActions-boolean-) | Se true, as ações serão copiadas dos documentos de origem. |
| [setKeepFieldsUnique](#setKeepFieldsUnique-boolean-) | Se verdadeiro, os nomes dos campos serão tornados únicos quando os formulários forem concatenados. |
| [setMergeDuplicateLayers](#setMergeDuplicateLayers-boolean-) | Conteúdos opcionais de documentos concatenados com nomes iguais serão mesclados em uma única camada no documento resultante se esta propriedade for true. |
| [setMergeDuplicateOutlines](#setMergeDuplicateOutlines-boolean-) | Se true, contornos duplicados são mesclados. |
| [setOptimizeSize](#setOptimizeSize-boolean-) | Obtém ou define a bandeira de otimização. |
| [setOwnerPassword](#setOwnerPassword-java.lang.String-) | Define a senha do proprietário se o arquivo Pdf de entrada estiver criptografado. |
| [setPreserveUserRights](#setPreserveUserRights-boolean-) | Se verdadeiro, os direitos de usuário do primeiro documento são aplicados ao documento concatenado. |
| [setRemoveSignatures](#setRemoveSignatures-boolean-) | Se verdadeiro, todas as assinaturas serão removidas dos campos (os campos permanecerão); caso contrário, você pode obter assinaturas inválidas. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Define as opções de salvamento quando o resultado é armazenado como HttpServletResponse. |
| [setTryMergeAdjacentSameBackgroundImages](#setTryMergeAdjacentSameBackgroundImages-boolean-) | Às vezes, PDFs contêm imagens de fundo (de páginas ou células de tabela) construídas a partir de várias imagens de fundo em mosaico iguais colocadas próximas umas das outras. |
| [setUniqueSuffix](#setUniqueSuffix-java.lang.String-) | Define o formato do sufixo que é adicionado ao nome do campo para torná-lo único quando os formulários são concatenados. |
| [setUseDiskBuffer](#setUseDiskBuffer-boolean-) | Se esta opção for usada, o documento de destino será salvo no disco periodicamente e concatenações subsequentes serão aplicadas a ele como atualizações incrementais. |
| [splitFromFirst](#splitFromFirst-java.io.InputStream-int-javax.servlet.http.HttpServletResponse-) | Divide o documento do início até o local especificado e armazena o resultado no objeto HttpServletResponse. |
| [splitFromFirst](#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-) | Divide do início até o local especificado e salva a parte frontal no Stream de saída. |
| [splitFromFirst](#splitFromFirst-java.lang.String-int-javax.servlet.http.HttpServletResponse-) | Divide o documento da primeira página até o local e salva o resultado nos objetos HttpServletResponse. |
| [splitFromFirst](#splitFromFirst-java.lang.String-int-java.lang.String-) | Divide o arquivo Pdf da primeira página até o local especificado e salva a parte frontal como um novo arquivo. |
| [splitToBulks](#splitToBulks-java.io.InputStream-int:A:A-) | Divide o arquivo Pdf em vários documentos. Os documentos podem ser de página única ou de múltiplas páginas. |
| [splitToBulks](#splitToBulks-java.lang.String-int:A:A-) | Divide o arquivo Pdf em vários documentos. Os documentos podem ser de página única ou de múltiplas páginas. |
| [splitToEnd](#splitToEnd-java.io.InputStream-int-javax.servlet.http.HttpServletResponse-) | Divide a partir do local especificado e salva a parte posterior no objeto HttpServletResponse. |
| [splitToEnd](#splitToEnd-java.io.InputStream-int-java.io.OutputStream-) | Divide a partir do local especificado e salva a parte traseira como um novo Stream de arquivo. |
| [splitToEnd](#splitToEnd-java.lang.String-int-javax.servlet.http.HttpServletResponse-) | Divide a partir do local especificado e salva a parte posterior no objeto HttpServletResponse. |
| [splitToEnd](#splitToEnd-java.lang.String-int-java.lang.String-) | Divide a partir do local e salva a parte traseira como um novo arquivo. |
| [splitToPages](#splitToPages-java.io.InputStream-) | Divide o arquivo Pdf em documentos de página única. |
| [splitToPages](#splitToPages-java.io.InputStream-java.lang.String-) | Divida o arquivo Pdf em documentos de página única e salve-o no caminho especificado. |
| [splitToPages](#splitToPages-java.lang.String-) | Divide o arquivo PDF em documentos de página única. |
| [splitToPages](#splitToPages-java.lang.String-java.lang.String-) | Divida o arquivo Pdf em documentos de página única e salve-o no caminho especificado. |

### PdfFileEditorWeb {#PdfFileEditorWeb--}
```
public PdfFileEditorWeb()
```

Construtor de PdfFileEditorWeb.

### addMargins {#addMargins-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-}
Redimensiona o conteúdo da página e adiciona margens especificadas.

### addMargins {#addMargins-java.lang.String-java.lang.String-int:A-double-double-double-double-}
Redimensiona o conteúdo da página e adiciona margens especificadas.

### addMarginsPct {#addMarginsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-}
Redimensiona o conteúdo da página e adiciona margens especificadas.

### addMarginsPct {#addMarginsPct-java.lang.String-java.lang.String-int:A-double-double-double-double-}
Redimensiona o conteúdo da página e adiciona margens especificadas.

### addPageBreak {#addPageBreak-com.aspose.pdf.Document-com.aspose.pdf.Document-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
Adiciona quebras de página nas páginas do documento.

### addPageBreak {#addPageBreak-com.aspose.pdf.IDocument-com.aspose.pdf.IDocument-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
Adiciona quebras de página nas páginas do documento.

### addPageBreak {#addPageBreak-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
Adiciona quebras de página nas páginas do documento.

### addPageBreak {#addPageBreak-java.lang.String-java.lang.String-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
Adiciona quebras de página nas páginas do documento.

### append {#append-java.io.InputStream-java.io.InputStream:A-int-int-javax.servlet.http.HttpServletResponse-}
Anexa documentos ao documento de origem e salva o resultado no objeto de resposta.

### append {#append-java.io.InputStream-java.io.InputStream:A-int-int-java.io.OutputStream-}
Anexa páginas, que são escolhidas a partir de um array de documentos em portStreams.

### append {#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-}
Anexa páginas, que são escolhidas de portStream dentro do intervalo de startPage a endPage, em portStream no final de firstInputStream.

### append {#append-java.lang.String-java.lang.String:A-int-int-javax.servlet.http.HttpServletResponse-}
Anexa documentos ao documento de origem e salva o resultado no objeto HttpServletResponse.

### append {#append-java.lang.String-java.lang.String:A-int-int-java.lang.String-}
Anexa páginas, que são escolhidas dos documentos portFiles.

### append {#append-java.lang.String-java.lang.String-int-int-java.lang.String-}
Anexa páginas, que são escolhidas de portFile dentro do intervalo de startPage a endPage, em portFile no final de firstInputFile.

### concatenate {#concatenate-com.aspose.pdf.IDocument:A-com.aspose.pdf.IDocument-}
Concatena documentos.

### concatenate {#concatenate-java.io.InputStream:A-javax.servlet.http.HttpServletResponse-}
Concatena arquivos e armazena o resultado no objeto HttpServletResponse.

### concatenate {#concatenate-java.io.InputStream:A-java.io.OutputStream-}
Concatena arquivos

### concatenate {#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
Mescla dois documentos Pdf em um novo documento Pdf com páginas de forma alternada e preenche os espaços vazios com páginas em branco.

### concatenate {#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
Concatena dois arquivos.

### concatenate {#concatenate-java.lang.String:A-javax.servlet.http.HttpServletResponse-}
Concatena arquivos e salva reslt no objeto HttpResposnse.

### concatenate {#concatenate-java.lang.String:A-java.lang.String-}
Concatena arquivos em um único arquivo.

### concatenate {#concatenate-java.lang.String-java.lang.String-java.lang.String-}
Concatena dois arquivos.

### concatenate {#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
Mescla dois documentos Pdf em um novo documento Pdf com páginas de forma alternada e preenche os espaços vazios com páginas em branco.

### createArrayWithExclusion {#createArrayWithExclusion-int-int-}
```
public static Integer [] createArrayWithExclusion(int n, int y)
```



### delete {#delete-java.io.InputStream-int:A-javax.servlet.http.HttpServletResponse-}
Exclui páginas especificadas do documento e salva o resultado no objeto HttpServletResponse.

### delete {#delete-java.io.InputStream-int:A-java.io.OutputStream-}
Exclui páginas especificadas por um array de números do arquivo de entrada, salva como um novo arquivo Pdf.

### delete {#delete-java.lang.String-int:A-javax.servlet.http.HttpServletResponse-}
Exclui páginas especificadas do documento e armazena o resultado no objeto HttpServletResponse.

### delete {#delete-java.lang.String-int:A-java.lang.String-}
Exclui páginas especificadas por um array de números do arquivo de entrada, salva como um novo arquivo Pdf.

### extract {#extract-java.io.InputStream-int:A-javax.servlet.http.HttpServletResponse-}
Extrai páginas especificadas do arquivo de origem e armazena o resultado no objeto HttpServletResponse.

### extract {#extract-java.io.InputStream-int:A-java.io.OutputStream-}
Extrai páginas especificadas por um array de números, salva como um novo arquivo Pdf.

### extract {#extract-java.io.InputStream-int-int-java.io.OutputStream-}
Extrai páginas do arquivo de entrada, salva como um novo arquivo Pdf.

### extract {#extract-java.lang.String-int:A-javax.servlet.http.HttpServletResponse-}
Extrai páginas especificadas do arquivo de origem e armazena o resultado no objeto HttpServletResponse.

### extract {#extract-java.lang.String-int:A-java.lang.String-}
Extrai páginas especificadas por um array de números, salva como um novo arquivo PDF.

### extract {#extract-java.lang.String-int-int-java.lang.String-}
Extrai páginas do arquivo de entrada, salva como um novo arquivo Pdf.

### getAllowConcatenateExceptions {#getAllowConcatenateExceptions--}
```
@Deprecated public boolean getAllowConcatenateExceptions()
```

Obsoleto. Esta propriedade está obsoleta e não pode ser usada para permitir lançar exceções.

**Returns:**
Valor booleano

### getAttachmentName {#getAttachmentName--}
```
public String getAttachmentName()
```

Obtém o nome do anexo quando o resultado da operação é armazenado em objetos HttpServletResponse como anexo.

**Returns:**
valor de string

### getCloseConcatenatedStreams {#getCloseConcatenatedStreams--}
```
public boolean getCloseConcatenatedStreams()
```

Se definido como true, os streams são fechados após a operação.

**Returns:**
valor booleano

### getConcatenationPacketSize {#getConcatenationPacketSize--}
```
public final int getConcatenationPacketSize()
```

Número de documentos concatenados antes de uma nova atualização incremental ser feita durante a concatenação quando UseDiskBuffer está definido como true.

**Returns:**
valor int

### getContentDisposition {#getContentDisposition--}
```
public ContentDisposition getContentDisposition()
```

Obtém como o conteúdo será armazenado quando o resultado da operação for armazenado no objeto HttpServletResponse.

**Returns:**
Elemento ContentDisposition

### getConversionLog {#getConversionLog--}
```
public String getConversionLog()
```

Obtém o registro do processo de conversão.

**Returns:**
valor de string

### getCopyLogicalStructure {#getCopyLogicalStructure--}
```
public boolean getCopyLogicalStructure()
```

Se true, a estrutura lógica do arquivo é copiada quando a concatenação é realizada.

**Returns:**
valor booleano

### getCopyOutlines {#getCopyOutlines--}
```
public boolean getCopyOutlines()
```

Se true, os contornos serão copiados.

**Returns:**
valor booleano

### getCorruptedFileAction {#getCorruptedFileAction--}
```
public int getCorruptedFileAction()
```

Esta propriedade define o comportamento ao concatenar quando o processo encontra um arquivo corrompido.

**Returns:**
Elemento ConcatenateCorruptedFileAction

### getCorruptedItems {#getCorruptedItems--}
```
public PdfFileEditor.CorruptedItem [] getCorruptedItems()
```

Array de problemas encontrados quando a concatenação foi realizada.

**Returns:**
Array PdfFileEditor.CorruptedItem

### getCustomProgressConcatenationHandler {#getCustomProgressConcatenationHandler--}
```
public PdfFileEditor.ConcatenationProgressHandler getCustomProgressConcatenationHandler()
```

Representação do processador interno de eventos de progresso que funciona durante a concatenação e traduz eventos de concatenação das etapas internas de concatenação para o código externo do cliente.

**Returns:**
ConcatenationProgressHandler instância

### getIncrementalUpdates {#getIncrementalUpdates--}
```
public boolean getIncrementalUpdates()
```

Se true, atualizações incrementais são feitas durante a concatenação.

**Returns:**
valor booleano

### getKeepActions {#getKeepActions--}
```
public final boolean getKeepActions()
```

Se true, as ações serão copiadas dos documentos de origem.

**Returns:**
valor booleano

### getKeepFieldsUnique {#getKeepFieldsUnique--}
```
public boolean getKeepFieldsUnique()
```

Se verdadeiro, os nomes dos campos serão tornados únicos quando os formulários forem concatenados.

**Returns:**
valor booleano

### getLastException {#getLastException--}
```
public final RuntimeException getLastException()
```

Obtém a última exceção ocorrida.

**Returns:**
java.lang.Exception objeto

### getMergeDuplicateLayers {#getMergeDuplicateLayers--}
```
public boolean getMergeDuplicateLayers()
```

Conteúdos opcionais de documentos concatenados com nomes iguais serão mesclados em uma única camada no documento resultante se esta propriedade for true.

**Returns:**
valor booleano

### getMergeDuplicateOutlines {#getMergeDuplicateOutlines--}
```
public boolean getMergeDuplicateOutlines()
```

Se true, contornos duplicados são mesclados.

**Returns:**
valor booleano

### getOptimizeSize {#getOptimizeSize--}
```
public boolean getOptimizeSize()
```

Obtém ou define a bandeira de otimização.

**Returns:**
valor booleano

### getOwnerPassword {#getOwnerPassword--}
```
public String getOwnerPassword()
```

Obtém a senha do proprietário se o arquivo PDF de entrada estiver criptografado.

**Returns:**
Objeto String

### getPreserveUserRights {#getPreserveUserRights--}
```
public boolean getPreserveUserRights()
```

Se verdadeiro, os direitos de usuário do primeiro documento são aplicados ao documento concatenado.

**Returns:**
valor booleano

### getRemoveSignatures {#getRemoveSignatures--}
```
public boolean getRemoveSignatures()
```

Se verdadeiro, todas as assinaturas serão removidas dos campos (os campos permanecerão); caso contrário, você pode obter assinaturas inválidas.

**Returns:**
valor booleano

### getSaveOptions {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```

Obtém ou define as opções de salvamento quando o resultado é armazenado como HttpServletResponse.

**Returns:**
Objeto SaveOptions

### getUniqueSuffix {#getUniqueSuffix--}
```
public String getUniqueSuffix()
```

Obtém o formato do sufixo que é adicionado ao nome do campo para torná-lo único quando os formulários são concatenados.

**Returns:**
Objeto String

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int:A-javax.servlet.http.HttpServletResponse-}
Insere o documento em outro documento e armazena o resultado no objeto de resposta.

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int:A-java.io.OutputStream-}
Insere páginas de outro arquivo no arquivo PDF de entrada.

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-}
Insere páginas de outro arquivo no arquivo PDF de entrada.

### insert {#insert-java.lang.String-int-java.lang.String-int:A-javax.servlet.http.HttpServletResponse-}
Insere o conteúdo do arquivo no arquivo de origem e armazena o resultado no objeto HttpServletResponse.

### insert {#insert-java.lang.String-int-java.lang.String-int:A-java.lang.String-}
Insere páginas de outro arquivo no arquivo PDF de entrada.

### insert {#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-}
Insere páginas de outro arquivo no arquivo PDF em uma posição.

### isTryMergeAdjacentSameBackgroundImages {#isTryMergeAdjacentSameBackgroundImages--}
```
public boolean isTryMergeAdjacentSameBackgroundImages()
```

Às vezes, PDFs contêm imagens de fundo (de páginas ou células de tabela) construídas a partir de várias imagens de fundo em mosaico iguais colocadas próximas umas das outras.

**Returns:**
valor booleano

### isUseDiskBuffer {#isUseDiskBuffer--}
```
public final boolean isUseDiskBuffer()
```

Se esta opção for usada, o documento de destino será salvo no disco periodicamente e concatenações subsequentes serão aplicadas a ele como atualizações incrementais.

**Returns:**
valor booleano

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-}
Cria um livreto a partir do InputStream para outputStream.

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-int:A-int:A-}
Cria um livreto personalizado a partir do firstInputStream para outputStream.

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-}
Cria um livreto a partir do fluxo de entrada e salva o resultado no fluxo de saída.

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int:A-int:A-}
Cria um livreto a partir do firstInputStream para outputStream.

### makeBooklet {#makeBooklet-java.io.InputStream-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-}
Cria um livreto a partir do arquivo de origem e armazena o resultado no HttpServletResponse.

### makeBooklet {#makeBooklet-java.io.InputStream-com.aspose.pdf.PageSize-int:A-int:A-javax.servlet.http.HttpServletResponse-}
Cria um livreto a partir de um arquivo PDF e o armazena no HttpServletResponse.

### makeBooklet {#makeBooklet-java.lang.String-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-}
Cria um livreto a partir do arquivo de origem e armazena o resultado nos objetos HttpServletResponse.

### makeBooklet {#makeBooklet-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-javax.servlet.http.HttpServletResponse-}
Cria um livreto a partir do arquivo de origem e armazena o resultado nos objetos HttpServletResponse.

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-}
Cria um livreto a partir do arquivo de entrada para o arquivo de saída.

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-int:A-int:A-}
Cria um livreto personalizado a partir do firstInputFile para outputFile.

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-}
Cria um livreto a partir do inputFile para outputFile.

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-}
Cria um livreto personalizado a partir do firstInputFile para outputFile.

### makeNUp {#makeNUp-java.io.InputStream:A-java.io.OutputStream-boolean-}
Cria um documento N-Up a partir de múltiplos fluxos PDF de entrada para outputStream.

### makeNUp {#makeNUp-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
Cria um documento N-Up a partir de dois fluxos PDF de entrada para outputStream.

### makeNUp {#makeNUp-java.io.InputStream-int-int-javax.servlet.http.HttpServletResponse-}
Cria um documento N-up e armazena o resultado no HttpServletResponse.

### makeNUp {#makeNUp-java.io.InputStream-int-int-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-}
Cria um documento N-up e armazena o resultado no objeto HttpServletResponse.

### makeNUp {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-}
Cria um documento N-Up a partir do fluxo de entrada e salva o resultado no fluxo de saída.

### makeNUp {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-}
Cria um documento N-Up a partir do primeiro fluxo de entrada para o fluxo de saída.

### makeNUp {#makeNUp-java.lang.String:A-java.lang.String-boolean-}
Cria um documento N-Up a partir de múltiplos arquivos PDF de entrada para outputFile.

### makeNUp {#makeNUp-java.lang.String-int-int-javax.servlet.http.HttpServletResponse-}
Cria um documento N-up e armazena o resultado no HttpServletResponse.

### makeNUp {#makeNUp-java.lang.String-int-int-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-}
Cria um documento N-up e armazena o resultado no objeto HttpServletResponse.

### makeNUp {#makeNUp-java.lang.String-java.lang.String-int-int-}
Cria um documento N-Up a partir do firstInputFile para outputFile.

### makeNUp {#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-}
Cria um documento N-Up a partir do arquivo de entrada para outputFile.

### makeNUp {#makeNUp-java.lang.String-java.lang.String-java.lang.String-}
Cria um documento N-Up a partir de dois arquivos PDF de entrada para outputFile.

### resizeContents {#resizeContents-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Redimensiona páginas do documento.

### resizeContents {#resizeContents-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Redimensiona páginas do documento.

### resizeContents {#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-double-double-}
Redimensiona o conteúdo das páginas do documento.

### resizeContents {#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Redimensiona o conteúdo das páginas do documento.

### resizeContents {#resizeContents-com.aspose.ms.System.IO.Stream-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-javax.servlet.http.HttpServletResponse-}
Redimensiona o conteúdo das páginas no documento.

### resizeContents {#resizeContents-java.lang.String-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-javax.servlet.http.HttpServletResponse-}
Redimensiona o conteúdo das páginas no documento.

### resizeContents {#resizeContents-java.lang.String-java.lang.String-int:A-double-double-}
Redimensiona o conteúdo das páginas do documento.

### resizeContents {#resizeContents-java.lang.String-java.lang.String-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Redimensiona o conteúdo das páginas no documento.

### resizeContentsPct {#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-}
Redimensiona o conteúdo das páginas do documento.

### resizeContentsPct {#resizeContentsPct-java.lang.String-java.lang.String-int:A-double-double-}
Redimensiona o conteúdo das páginas do documento.

### resizeContentsWithNormalization {#resizeContentsWithNormalization-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Redimensiona páginas do documento.

### resizeContentsWithNormalization {#resizeContentsWithNormalization-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Redimensiona páginas do documento.

### setAllowConcatenateExceptions {#setAllowConcatenateExceptions-boolean-}
```
@Deprecated public void setAllowConcatenateExceptions(boolean value)
```

Obsoleto. Esta propriedade está obsoleta e não pode ser usada para permitir lançar exceções.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | Valor booleano |

### setAttachmentName {#setAttachmentName-java.lang.String-}
Define o nome do anexo quando o resultado da operação é armazenado em objetos HttpServletResponse como anexo.

### setCloseConcatenatedStreams {#setCloseConcatenatedStreams-boolean-}
```
public void setCloseConcatenatedStreams(boolean value)
```

Se definido como true, os streams são fechados após a operação.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setConcatenationPacketSize {#setConcatenationPacketSize-int-}
```
public final void setConcatenationPacketSize(int value)
```

Número de documentos concatenados antes de uma nova atualização incremental ser feita durante a concatenação quando UseDiskBuffer está definido como true.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
Define como o conteúdo será armazenado quando o resultado da operação for armazenado no objeto HttpServletResponse.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Define o formato do arquivo PDF.

### setCopyLogicalStructure {#setCopyLogicalStructure-boolean-}
```
public void setCopyLogicalStructure(boolean value)
```

Se true, a estrutura lógica do arquivo é copiada quando a concatenação é realizada.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setCopyOutlines {#setCopyOutlines-boolean-}
```
public void setCopyOutlines(boolean value)
```

Se true, os contornos serão copiados.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setCorruptedFileAction {#setCorruptedFileAction-int-}
```
public void setCorruptedFileAction(int value)
```

Esta propriedade define o comportamento ao concatenar quando o processo encontra um arquivo corrompido.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | Elemento ConcatenateCorruptedFileAction |

### setCustomProgressConcatenationHandler {#setCustomProgressConcatenationHandler-com.aspose.pdf.facades.PdfFileEditor.ConcatenationProgressHandler-}
Representação do processador interno de eventos de progresso que funciona durante a concatenação e traduz eventos de concatenação das etapas internas de concatenação para o código externo do cliente.

### setIncrementalUpdates {#setIncrementalUpdates-boolean-}
```
public void setIncrementalUpdates(boolean value)
```

Se true, atualizações incrementais são feitas durante a concatenação.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setKeepActions {#setKeepActions-boolean-}
```
public final void setKeepActions(boolean value)
```

Se true, as ações serão copiadas dos documentos de origem.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setKeepFieldsUnique {#setKeepFieldsUnique-boolean-}
```
public void setKeepFieldsUnique(boolean value)
```

Se verdadeiro, os nomes dos campos serão tornados únicos quando os formulários forem concatenados.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setMergeDuplicateLayers {#setMergeDuplicateLayers-boolean-}
```
public void setMergeDuplicateLayers(boolean value)
```

Conteúdos opcionais de documentos concatenados com nomes iguais serão mesclados em uma única camada no documento resultante se esta propriedade for true.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setMergeDuplicateOutlines {#setMergeDuplicateOutlines-boolean-}
```
public void setMergeDuplicateOutlines(boolean value)
```

Se true, contornos duplicados são mesclados.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setOptimizeSize {#setOptimizeSize-boolean-}
```
public void setOptimizeSize(boolean value)
```

Obtém ou define a bandeira de otimização.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setOwnerPassword {#setOwnerPassword-java.lang.String-}
Define a senha do proprietário se o arquivo Pdf de entrada estiver criptografado.

### setPreserveUserRights {#setPreserveUserRights-boolean-}
```
public void setPreserveUserRights(boolean value)
```

Se verdadeiro, os direitos de usuário do primeiro documento são aplicados ao documento concatenado.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setRemoveSignatures {#setRemoveSignatures-boolean-}
```
public void setRemoveSignatures(boolean value)
```

Se verdadeiro, todas as assinaturas serão removidas dos campos (os campos permanecerão); caso contrário, você pode obter assinaturas inválidas.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Define as opções de salvamento quando o resultado é armazenado como HttpServletResponse.

### setTryMergeAdjacentSameBackgroundImages {#setTryMergeAdjacentSameBackgroundImages-boolean-}
```
public void setTryMergeAdjacentSameBackgroundImages(boolean tryMergeAdjacentSameBackgroundImages)
```

Às vezes, PDFs contêm imagens de fundo (de páginas ou células de tabela) construídas a partir de várias imagens de fundo em mosaico iguais colocadas próximas umas das outras.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| tryMergeAdjacentSameBackgroundImages |  | valor booleano |

### setUniqueSuffix {#setUniqueSuffix-java.lang.String-}
Define o formato do sufixo que é adicionado ao nome do campo para torná-lo único quando os formulários são concatenados.

### setUseDiskBuffer {#setUseDiskBuffer-boolean-}
```
public final void setUseDiskBuffer(boolean value)
```

Se esta opção for usada, o documento de destino será salvo no disco periodicamente e concatenações subsequentes serão aplicadas a ele como atualizações incrementais.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### splitFromFirst {#splitFromFirst-java.io.InputStream-int-javax.servlet.http.HttpServletResponse-}
Divide o documento do início até o local especificado e armazena o resultado no objeto HttpServletResponse.

### splitFromFirst {#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-}
Divide do início até o local especificado e salva a parte frontal no Stream de saída.

### splitFromFirst {#splitFromFirst-java.lang.String-int-javax.servlet.http.HttpServletResponse-}
Divide o documento da primeira página até o local e salva o resultado nos objetos HttpServletResponse.

### splitFromFirst {#splitFromFirst-java.lang.String-int-java.lang.String-}
Divide o arquivo Pdf da primeira página até o local especificado e salva a parte frontal como um novo arquivo.

### splitToBulks {#splitToBulks-java.io.InputStream-int:A:A-}
Divide o arquivo Pdf em vários documentos. Os documentos podem ser de página única ou de múltiplas páginas.

### splitToBulks {#splitToBulks-java.lang.String-int:A:A-}
Divide o arquivo Pdf em vários documentos. Os documentos podem ser de página única ou de múltiplas páginas.

### splitToEnd {#splitToEnd-java.io.InputStream-int-javax.servlet.http.HttpServletResponse-}
Divide a partir do local especificado e salva a parte posterior no objeto HttpServletResponse.

### splitToEnd {#splitToEnd-java.io.InputStream-int-java.io.OutputStream-}
Divide a partir do local especificado e salva a parte traseira como um novo Stream de arquivo.

### splitToEnd {#splitToEnd-java.lang.String-int-javax.servlet.http.HttpServletResponse-}
Divide a partir do local especificado e salva a parte posterior no objeto HttpServletResponse.

### splitToEnd {#splitToEnd-java.lang.String-int-java.lang.String-}
Divide a partir do local e salva a parte traseira como um novo arquivo.

### splitToPages {#splitToPages-java.io.InputStream-}
Divide o arquivo Pdf em documentos de página única.

### splitToPages {#splitToPages-java.io.InputStream-java.lang.String-}
Divida o arquivo Pdf em documentos de página única e salve-o no caminho especificado.

### splitToPages {#splitToPages-java.lang.String-}
Divide o arquivo PDF em documentos de página única.

### splitToPages {#splitToPages-java.lang.String-java.lang.String-}
Divida o arquivo Pdf em documentos de página única e salve-o no caminho especificado.
