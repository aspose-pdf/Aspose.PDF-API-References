---
title: "IPdfFileEditor"
linktitle: "IPdfFileEditor"
second_title: "Referência da API Aspose.PDF para Java"
description: "Implementa operações com arquivos PDF: concatenação, divisão, extração de páginas, criação de livrinho, etc."
type: docs
weight: 290
url: /pt/java/com.aspose.pdf.facades/ipdffileeditor/
---
```
public interface IPdfFileEditor
```

Implementa operações com arquivos PDF: concatenação, divisão, extração de páginas, criação de livrinho, etc.

## Métodos

| Método | Descrição |
| --- | --- |
| [addMargins](#addMargins-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-) | Redimensiona o conteúdo da página e adiciona margens especificadas. |
| [addMargins](#addMargins-java.lang.String-java.lang.String-int:A-double-double-double-double-) | Redimensiona o conteúdo da página e adiciona margens especificadas. |
| [addMarginsPct](#addMarginsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-) | Redimensiona o conteúdo da página e adiciona margens especificadas. |
| [addMarginsPct](#addMarginsPct-java.lang.String-java.lang.String-int:A-double-double-double-double-) | Redimensiona o conteúdo da página e adiciona margens especificadas. |
| [append](#append-java.io.InputStream-java.io.InputStream:A-int-int-java.io.OutputStream-) | Anexa páginas, que são escolhidas a partir de um array de documentos em portStreams. |
| [append](#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-) | Anexa páginas, que são escolhidas de portStream dentro do intervalo de startPage a endPage, em portStream no final de firstInputStream. |
| [append](#append-java.lang.String-java.lang.String:A-int-int-java.lang.String-) | Anexa páginas, que são escolhidas dos documentos portFiles. |
| [append](#append-java.lang.String-java.lang.String-int-int-java.lang.String-) | Anexa páginas, que são escolhidas de portFile dentro do intervalo de startPage a endPage, em portFile no final de firstInputFile. |
| [concatenate](#concatenate-com.aspose.pdf.IDocument:A-com.aspose.pdf.IDocument-) | Concatena documentos. |
| [concatenate](#concatenate-java.io.InputStream:A-java.io.OutputStream-) | Concatena arquivos |
| [concatenate](#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | Mescla dois documentos Pdf em um novo documento Pdf com páginas de forma alternada e preenche os espaços vazios com páginas em branco. |
| [concatenate](#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | Concatena dois arquivos. |
| [concatenate](#concatenate-java.lang.String:A-java.lang.String-) | Concatena arquivos em um único arquivo. |
| [concatenate](#concatenate-java.lang.String-java.lang.String-java.lang.String-) | Concatena dois arquivos. |
| [concatenate](#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | Mescla dois documentos Pdf em um novo documento Pdf com páginas de forma alternada e preenche os espaços vazios com páginas em branco. |
| [delete](#delete-java.io.InputStream-int:A-java.io.OutputStream-) | Exclui páginas especificadas por um array de números do arquivo de entrada, salva como um novo arquivo Pdf. |
| [delete](#delete-java.lang.String-int:A-java.lang.String-) | Exclui páginas especificadas por um array de números do arquivo de entrada, salva como um novo arquivo Pdf. |
| [extract](#extract-java.io.InputStream-int:A-java.io.OutputStream-) | Extrai páginas especificadas por um array de números, salva como um novo arquivo Pdf. |
| [extract](#extract-java.io.InputStream-int-int-java.io.OutputStream-) | Extrai páginas do arquivo de entrada, salva como um novo arquivo Pdf. |
| [extract](#extract-java.lang.String-int:A-java.lang.String-) | Extrai páginas especificadas por um array de números, salva como um novo arquivo PDF. |
| [extract](#extract-java.lang.String-int-int-java.lang.String-) | Extrai páginas do arquivo de entrada, salva como um novo arquivo Pdf. |
| [getAllowConcatenateExceptions](#getAllowConcatenateExceptions--) | é Permitir Exceções de Concatenação |
| [getAttachmentName](#getAttachmentName--) | Obtém o nome do anexo quando o resultado da operação é armazenado em objetos HttpServletResponse como anexo. |
| [getCloseConcatenatedStreams](#getCloseConcatenatedStreams--) | Se definido como true, os streams são fechados após a operação. |
| [getContentDisposition](#getContentDisposition--) | Obtém como o conteúdo será armazenado quando o resultado da operação for armazenado no objeto HttpServletResponse. |
| [getConversionLog](#getConversionLog--) | Obtém o registro do processo de conversão. |
| [getCorruptedFileAction](#getCorruptedFileAction--) | Esta propriedade define o comportamento ao concatenar quando o processo encontra um arquivo corrompido. |
| [getIncrementalUpdates](#getIncrementalUpdates--) | Se true, atualizações incrementais são feitas durante a concatenação. |
| [getKeepFieldsUnique](#getKeepFieldsUnique--) | Se verdadeiro, os nomes dos campos serão tornados únicos quando os formulários forem concatenados. |
| [getLastException](#getLastException--) | Obtém a última exceção ocorrida. |
| [getMergeDuplicateLayers](#getMergeDuplicateLayers--) | Conteúdos opcionais de documentos concatenados com nomes iguais serão mesclados em uma única camada no documento resultante se esta propriedade for true. |
| [getMergeDuplicateOutlines](#getMergeDuplicateOutlines--) | Se true, contornos duplicados são mesclados. |
| [getOwnerPassword](#getOwnerPassword--) | Obtém a senha do proprietário se o arquivo PDF de entrada estiver criptografado. |
| [getPreserveUserRights](#getPreserveUserRights--) | Se verdadeiro, os direitos de usuário do primeiro documento são aplicados ao documento concatenado. |
| [getRemoveSignatures](#getRemoveSignatures--) | Se verdadeiro, todas as assinaturas serão removidas dos campos (os campos permanecerão); caso contrário, você pode obter assinaturas inválidas. |
| [getSaveOptions](#getSaveOptions--) | Obtém ou define as opções de salvamento quando o resultado é armazenado como HttpServletResponse. |
| [getUniqueSuffix](#getUniqueSuffix--) | Obtém o formato do sufixo que é adicionado ao nome do campo para torná-lo único quando os formulários são concatenados. |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int:A-java.io.OutputStream-) | Insere páginas de outro arquivo no arquivo PDF de entrada. |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-) | Insere páginas de outro arquivo no arquivo PDF de entrada. |
| [insert](#insert-java.lang.String-int-java.lang.String-int:A-java.lang.String-) | Insere páginas de outro arquivo no arquivo PDF de entrada. |
| [insert](#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-) | Insere páginas de outro arquivo no arquivo PDF em uma posição. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-) | Cria um livreto a partir do InputStream para outputStream. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-int:A-int:A-) | Cria um livreto personalizado a partir do firstInputStream para outputStream. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-) | Cria um livreto a partir do fluxo de entrada e salva o resultado no fluxo de saída. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int:A-int:A-) | Cria um livreto a partir do firstInputStream para outputStream. |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-) | Cria um livreto a partir do arquivo de entrada para o arquivo de saída. |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-int:A-int:A-) | Cria um livreto personalizado a partir do firstInputFile para outputFile. |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-) | Cria um livreto a partir do inputFile para outputFile. |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-) | Cria um livreto personalizado a partir do firstInputFile para outputFile. |
| [makeNUp](#makeNUp-java.io.InputStream:A-java.io.OutputStream-boolean-) | Cria um documento N-Up a partir de múltiplos fluxos PDF de entrada para outputStream. |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | Cria um documento N-Up a partir de dois fluxos PDF de entrada para outputStream. |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-) | Cria um documento N-Up a partir do fluxo de entrada e salva o resultado no fluxo de saída. |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-) | Cria um documento N-Up a partir do primeiro fluxo de entrada para o fluxo de saída. |
| [makeNUp](#makeNUp-java.lang.String:A-java.lang.String-boolean-) | Cria um documento N-Up a partir de múltiplos arquivos PDF de entrada para outputFile. |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-int-int-) | Cria um documento N-Up a partir do firstInputFile para outputFile. |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-) | Cria um documento N-Up a partir do arquivo de entrada para outputFile. |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-java.lang.String-) | Cria um documento N-Up a partir de dois arquivos PDF de entrada para outputFile. |
| [resizeContents](#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-double-double-) | Redimensiona o conteúdo das páginas do documento. |
| [resizeContents](#resizeContents-java.lang.String-java.lang.String-int:A-double-double-) | Redimensiona o conteúdo das páginas do documento. |
| [resizeContentsPct](#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-) | Redimensiona o conteúdo das páginas do documento. |
| [resizeContentsPct](#resizeContentsPct-java.lang.String-java.lang.String-int:A-double-double-) | Redimensiona o conteúdo das páginas do documento. |
| [setAllowConcatenateExceptions](#setAllowConcatenateExceptions-boolean-) | Se definido como verdadeiro, exceções são lançadas se ocorrer um erro. |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | Define o nome do anexo quando o resultado da operação é armazenado em objetos HttpServletResponse como anexo. |
| [setCloseConcatenatedStreams](#setCloseConcatenatedStreams-boolean-) | Se definido como true, os streams são fechados após a operação. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | Define como o conteúdo será armazenado quando o resultado da operação for armazenado no objeto HttpServletResponse. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | Define o formato do arquivo PDF. |
| [setCorruptedFileAction](#setCorruptedFileAction-int-) | Esta propriedade define o comportamento ao concatenar quando o processo encontra um arquivo corrompido. |
| [setIncrementalUpdates](#setIncrementalUpdates-boolean-) | Se true, atualizações incrementais são feitas durante a concatenação. |
| [setKeepFieldsUnique](#setKeepFieldsUnique-boolean-) | Se verdadeiro, os nomes dos campos serão tornados únicos quando os formulários forem concatenados. |
| [setMergeDuplicateLayers](#setMergeDuplicateLayers-boolean-) | Conteúdos opcionais de documentos concatenados com nomes iguais serão mesclados em uma única camada no documento resultante se esta propriedade for true. |
| [setMergeDuplicateOutlines](#setMergeDuplicateOutlines-boolean-) | Se true, contornos duplicados são mesclados. |
| [setOwnerPassword](#setOwnerPassword-java.lang.String-) | Define a senha do proprietário se o arquivo Pdf de entrada estiver criptografado. |
| [setPreserveUserRights](#setPreserveUserRights-boolean-) | Se verdadeiro, os direitos de usuário do primeiro documento são aplicados ao documento concatenado. |
| [setRemoveSignatures](#setRemoveSignatures-boolean-) | Se verdadeiro, todas as assinaturas serão removidas dos campos (os campos permanecerão); caso contrário, você pode obter assinaturas inválidas. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Define as opções de salvamento quando o resultado é armazenado como HttpServletResponse. |
| [setUniqueSuffix](#setUniqueSuffix-java.lang.String-) | Define o formato do sufixo que é adicionado ao nome do campo para torná-lo único quando os formulários são concatenados. |
| [splitFromFirst](#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-) | Divide do início até o local especificado e salva a parte frontal no Stream de saída. |
| [splitFromFirst](#splitFromFirst-java.lang.String-int-java.lang.String-) | Divide o arquivo Pdf da primeira página até o local especificado e salva a parte frontal como um novo arquivo. |
| [splitToBulks](#splitToBulks-java.io.InputStream-int:A:A-) | Divide o arquivo Pdf em vários documentos. Os documentos podem ser de página única ou de múltiplas páginas. |
| [splitToBulks](#splitToBulks-java.lang.String-int:A:A-) | Divide o arquivo Pdf em vários documentos. Os documentos podem ser de página única ou de múltiplas páginas. |
| [splitToEnd](#splitToEnd-java.io.InputStream-int-java.io.OutputStream-) | Divide a partir do local especificado e salva a parte traseira como um novo Stream de arquivo. |
| [splitToEnd](#splitToEnd-java.lang.String-int-java.lang.String-) | Divide a partir do local e salva a parte traseira como um novo arquivo. |
| [splitToPages](#splitToPages-java.io.InputStream-) | Divide o arquivo Pdf em documentos de página única. |
| [splitToPages](#splitToPages-java.io.InputStream-java.lang.String-) | Divida o arquivo Pdf em documentos de página única e salve-o no caminho especificado. |
| [splitToPages](#splitToPages-java.lang.String-) | Divide o arquivo PDF em documentos de página única. |
| [splitToPages](#splitToPages-java.lang.String-java.lang.String-) | Divida o arquivo Pdf em documentos de página única e salve-o no caminho especificado. |

### addMargins {#addMargins-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-}
Redimensiona o conteúdo da página e adiciona margens especificadas.

### addMargins {#addMargins-java.lang.String-java.lang.String-int:A-double-double-double-double-}
Redimensiona o conteúdo da página e adiciona margens especificadas.

### addMarginsPct {#addMarginsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-}
Redimensiona o conteúdo da página e adiciona margens especificadas.

### addMarginsPct {#addMarginsPct-java.lang.String-java.lang.String-int:A-double-double-double-double-}
Redimensiona o conteúdo da página e adiciona margens especificadas.

### append {#append-java.io.InputStream-java.io.InputStream:A-int-int-java.io.OutputStream-}
Anexa páginas, que são escolhidas a partir de um array de documentos em portStreams.

### append {#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-}
Anexa páginas, que são escolhidas de portStream dentro do intervalo de startPage a endPage, em portStream no final de firstInputStream.

### append {#append-java.lang.String-java.lang.String:A-int-int-java.lang.String-}
Anexa páginas, que são escolhidas dos documentos portFiles.

### append {#append-java.lang.String-java.lang.String-int-int-java.lang.String-}
Anexa páginas, que são escolhidas de portFile dentro do intervalo de startPage a endPage, em portFile no final de firstInputFile.

### concatenate {#concatenate-com.aspose.pdf.IDocument:A-com.aspose.pdf.IDocument-}
Concatena documentos.

### concatenate {#concatenate-java.io.InputStream:A-java.io.OutputStream-}
Concatena arquivos

### concatenate {#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
Mescla dois documentos Pdf em um novo documento Pdf com páginas de forma alternada e preenche os espaços vazios com páginas em branco.

### concatenate {#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
Concatena dois arquivos.

### concatenate {#concatenate-java.lang.String:A-java.lang.String-}
Concatena arquivos em um único arquivo.

### concatenate {#concatenate-java.lang.String-java.lang.String-java.lang.String-}
Concatena dois arquivos.

### concatenate {#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
Mescla dois documentos Pdf em um novo documento Pdf com páginas de forma alternada e preenche os espaços vazios com páginas em branco.

### delete {#delete-java.io.InputStream-int:A-java.io.OutputStream-}
Exclui páginas especificadas por um array de números do arquivo de entrada, salva como um novo arquivo Pdf.

### delete {#delete-java.lang.String-int:A-java.lang.String-}
Exclui páginas especificadas por um array de números do arquivo de entrada, salva como um novo arquivo Pdf.

### extract {#extract-java.io.InputStream-int:A-java.io.OutputStream-}
Extrai páginas especificadas por um array de números, salva como um novo arquivo Pdf.

### extract {#extract-java.io.InputStream-int-int-java.io.OutputStream-}
Extrai páginas do arquivo de entrada, salva como um novo arquivo Pdf.

### extract {#extract-java.lang.String-int:A-java.lang.String-}
Extrai páginas especificadas por um array de números, salva como um novo arquivo PDF.

### extract {#extract-java.lang.String-int-int-java.lang.String-}
Extrai páginas do arquivo de entrada, salva como um novo arquivo Pdf.

### getAllowConcatenateExceptions {#getAllowConcatenateExceptions--}
```
boolean getAllowConcatenateExceptions()
```

é Permitir Exceções de Concatenação

**Returns:**
valor booleano

### getAttachmentName {#getAttachmentName--}
```
String getAttachmentName()
```

Obtém o nome do anexo quando o resultado da operação é armazenado em objetos HttpServletResponse como anexo.

**Returns:**
valor de string

### getCloseConcatenatedStreams {#getCloseConcatenatedStreams--}
```
boolean getCloseConcatenatedStreams()
```

Se definido como true, os streams são fechados após a operação.

**Returns:**
valor booleano

### getContentDisposition {#getContentDisposition--}
```
ContentDisposition getContentDisposition()
```

Obtém como o conteúdo será armazenado quando o resultado da operação for armazenado no objeto HttpServletResponse.

**Returns:**
Elemento ContentDisposition

### getConversionLog {#getConversionLog--}
```
String getConversionLog()
```

Obtém o registro do processo de conversão.

**Returns:**
valor de string

### getCorruptedFileAction {#getCorruptedFileAction--}
```
int getCorruptedFileAction()
```

Esta propriedade define o comportamento ao concatenar quando o processo encontra um arquivo corrompido.

**Returns:**
Elemento ConcatenateCorruptedFileAction

### getIncrementalUpdates {#getIncrementalUpdates--}
```
boolean getIncrementalUpdates()
```

Se true, atualizações incrementais são feitas durante a concatenação.

**Returns:**
valor booleano

### getKeepFieldsUnique {#getKeepFieldsUnique--}
```
boolean getKeepFieldsUnique()
```

Se verdadeiro, os nomes dos campos serão tornados únicos quando os formulários forem concatenados.

**Returns:**
valor booleano

### getLastException {#getLastException--}
```
Exception getLastException()
```

Obtém a última exceção ocorrida.

**Returns:**
java.lang.Exception objeto

### getMergeDuplicateLayers {#getMergeDuplicateLayers--}
```
boolean getMergeDuplicateLayers()
```

Conteúdos opcionais de documentos concatenados com nomes iguais serão mesclados em uma única camada no documento resultante se esta propriedade for true.

**Returns:**
valor booleano

### getMergeDuplicateOutlines {#getMergeDuplicateOutlines--}
```
boolean getMergeDuplicateOutlines()
```

Se true, contornos duplicados são mesclados.

**Returns:**
valor booleano

### getOwnerPassword {#getOwnerPassword--}
```
String getOwnerPassword()
```

Obtém a senha do proprietário se o arquivo PDF de entrada estiver criptografado.

**Returns:**
valor de string

### getPreserveUserRights {#getPreserveUserRights--}
```
boolean getPreserveUserRights()
```

Se verdadeiro, os direitos de usuário do primeiro documento são aplicados ao documento concatenado.

**Returns:**
valor booleano

### getRemoveSignatures {#getRemoveSignatures--}
```
boolean getRemoveSignatures()
```

Se verdadeiro, todas as assinaturas serão removidas dos campos (os campos permanecerão); caso contrário, você pode obter assinaturas inválidas.

**Returns:**
valor booleano

### getSaveOptions {#getSaveOptions--}
```
SaveOptions getSaveOptions()
```

Obtém ou define as opções de salvamento quando o resultado é armazenado como HttpServletResponse.

**Returns:**
Objeto SaveOptions

### getUniqueSuffix {#getUniqueSuffix--}
```
String getUniqueSuffix()
```

Obtém o formato do sufixo que é adicionado ao nome do campo para torná-lo único quando os formulários são concatenados.

**Returns:**
valor de string

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int:A-java.io.OutputStream-}
Insere páginas de outro arquivo no arquivo PDF de entrada.

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-}
Insere páginas de outro arquivo no arquivo PDF de entrada.

### insert {#insert-java.lang.String-int-java.lang.String-int:A-java.lang.String-}
Insere páginas de outro arquivo no arquivo PDF de entrada.

### insert {#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-}
Insere páginas de outro arquivo no arquivo PDF em uma posição.

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-}
Cria um livreto a partir do InputStream para outputStream.

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-int:A-int:A-}
Cria um livreto personalizado a partir do firstInputStream para outputStream.

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-}
Cria um livreto a partir do fluxo de entrada e salva o resultado no fluxo de saída.

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int:A-int:A-}
Cria um livreto a partir do firstInputStream para outputStream.

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

### makeNUp {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-}
Cria um documento N-Up a partir do fluxo de entrada e salva o resultado no fluxo de saída.

### makeNUp {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-}
Cria um documento N-Up a partir do primeiro fluxo de entrada para o fluxo de saída.

### makeNUp {#makeNUp-java.lang.String:A-java.lang.String-boolean-}
Cria um documento N-Up a partir de múltiplos arquivos PDF de entrada para outputFile.

### makeNUp {#makeNUp-java.lang.String-java.lang.String-int-int-}
Cria um documento N-Up a partir do firstInputFile para outputFile.

### makeNUp {#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-}
Cria um documento N-Up a partir do arquivo de entrada para outputFile.

### makeNUp {#makeNUp-java.lang.String-java.lang.String-java.lang.String-}
Cria um documento N-Up a partir de dois arquivos PDF de entrada para outputFile.

### resizeContents {#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-double-double-}
Redimensiona o conteúdo das páginas do documento.

### resizeContents {#resizeContents-java.lang.String-java.lang.String-int:A-double-double-}
Redimensiona o conteúdo das páginas do documento.

### resizeContentsPct {#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-}
Redimensiona o conteúdo das páginas do documento.

### resizeContentsPct {#resizeContentsPct-java.lang.String-java.lang.String-int:A-double-double-}
Redimensiona o conteúdo das páginas do documento.

### setAllowConcatenateExceptions {#setAllowConcatenateExceptions-boolean-}
```
void setAllowConcatenateExceptions(boolean value)
```

Se definido como verdadeiro, exceções são lançadas se ocorrer um erro.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setAttachmentName {#setAttachmentName-java.lang.String-}
Define o nome do anexo quando o resultado da operação é armazenado em objetos HttpServletResponse como anexo.

### setCloseConcatenatedStreams {#setCloseConcatenatedStreams-boolean-}
```
void setCloseConcatenatedStreams(boolean value)
```

Se definido como true, os streams são fechados após a operação.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
Define como o conteúdo será armazenado quando o resultado da operação for armazenado no objeto HttpServletResponse.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Define o formato do arquivo PDF.

### setCorruptedFileAction {#setCorruptedFileAction-int-}
```
void setCorruptedFileAction(int value)
```

Esta propriedade define o comportamento ao concatenar quando o processo encontra um arquivo corrompido.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | Elemento ConcatenateCorruptedFileAction |

### setIncrementalUpdates {#setIncrementalUpdates-boolean-}
```
void setIncrementalUpdates(boolean value)
```

Se true, atualizações incrementais são feitas durante a concatenação.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setKeepFieldsUnique {#setKeepFieldsUnique-boolean-}
```
void setKeepFieldsUnique(boolean value)
```

Se verdadeiro, os nomes dos campos serão tornados únicos quando os formulários forem concatenados.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setMergeDuplicateLayers {#setMergeDuplicateLayers-boolean-}
```
void setMergeDuplicateLayers(boolean value)
```

Conteúdos opcionais de documentos concatenados com nomes iguais serão mesclados em uma única camada no documento resultante se esta propriedade for true.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setMergeDuplicateOutlines {#setMergeDuplicateOutlines-boolean-}
```
void setMergeDuplicateOutlines(boolean value)
```

Se true, contornos duplicados são mesclados.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setOwnerPassword {#setOwnerPassword-java.lang.String-}
Define a senha do proprietário se o arquivo Pdf de entrada estiver criptografado.

### setPreserveUserRights {#setPreserveUserRights-boolean-}
```
void setPreserveUserRights(boolean value)
```

Se verdadeiro, os direitos de usuário do primeiro documento são aplicados ao documento concatenado.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setRemoveSignatures {#setRemoveSignatures-boolean-}
```
void setRemoveSignatures(boolean value)
```

Se verdadeiro, todas as assinaturas serão removidas dos campos (os campos permanecerão); caso contrário, você pode obter assinaturas inválidas.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Define as opções de salvamento quando o resultado é armazenado como HttpServletResponse.

### setUniqueSuffix {#setUniqueSuffix-java.lang.String-}
Define o formato do sufixo que é adicionado ao nome do campo para torná-lo único quando os formulários são concatenados.

### splitFromFirst {#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-}
Divide do início até o local especificado e salva a parte frontal no Stream de saída.

### splitFromFirst {#splitFromFirst-java.lang.String-int-java.lang.String-}
Divide o arquivo Pdf da primeira página até o local especificado e salva a parte frontal como um novo arquivo.

### splitToBulks {#splitToBulks-java.io.InputStream-int:A:A-}
Divide o arquivo Pdf em vários documentos. Os documentos podem ser de página única ou de múltiplas páginas.

### splitToBulks {#splitToBulks-java.lang.String-int:A:A-}
Divide o arquivo Pdf em vários documentos. Os documentos podem ser de página única ou de múltiplas páginas.

### splitToEnd {#splitToEnd-java.io.InputStream-int-java.io.OutputStream-}
Divide a partir do local especificado e salva a parte traseira como um novo Stream de arquivo.

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
