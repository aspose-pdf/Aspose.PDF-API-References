---
title: "IPdfFileStamp"
linktitle: "IPdfFileStamp"
second_title: "Referência da API Aspose.PDF para Java"
description: "Interface para adicionar carimbos (marca d'água ou fundo) a arquivos PDF."
type: docs
weight: 320
url: /pt/java/com.aspose.pdf.facades/ipdffilestamp/
---
```
public interface IPdfFileStamp
```

Interface para adicionar carimbos (marca d'água ou fundo) a arquivos PDF.

## Campos

| Campo | Descrição |
| --- | --- |
| [POS_BOTTOM_LEFT](#POS_BOTTOM_LEFT) | Posição inferior esquerda. |
| [POS_BOTTOM_MIDDLE](#POS_BOTTOM_MIDDLE) | Posição inferior central. |
| [POS_BOTTOM_RIGHT](#POS_BOTTOM_RIGHT) | Posição inferior direita. |
| [POS_SIDES_LEFT](#POS_SIDES_LEFT) | Posição esquerda. |
| [POS_SIDES_RIGHT](#POS_SIDES_RIGHT) | Posição direita. |
| [POS_UPPER_LEFT](#POS_UPPER_LEFT) | Posição superior esquerda. |
| [POS_UPPER_MIDDLE](#POS_UPPER_MIDDLE) | Posição central superior. |
| [POS_UPPER_RIGHT](#POS_UPPER_RIGHT) | Posição superior direita. |

## Métodos

| Método | Descrição |
| --- | --- |
| [addFooter](#addFooter-com.aspose.pdf.facades.FormattedText-float-) | Adiciona rodapé às páginas do documento. |
| [addFooter](#addFooter-com.aspose.pdf.facades.FormattedText-float-float-float-) | Adiciona rodapé às páginas do documento. |
| [addFooter](#addFooter-java.io.InputStream-float-) | Adiciona imagem como rodapé da página. |
| [addFooter](#addFooter-java.io.InputStream-float-float-float-) | Adiciona imagem como rodapé da página. |
| [addFooter](#addFooter-java.lang.String-float-) | Adiciona imagem como rodapé às páginas do documento. |
| [addFooter](#addFooter-java.lang.String-float-float-float-) | Adiciona imagem como rodapé das páginas. |
| [addHeader](#addHeader-com.aspose.pdf.facades.FormattedText-float-) | Adiciona cabeçalho à página. |
| [addHeader](#addHeader-com.aspose.pdf.facades.FormattedText-float-float-float-) | Adiciona cabeçalho às páginas do arquivo. |
| [addHeader](#addHeader-java.io.InputStream-float-) | Adiciona imagem como cabeçalho nas páginas. |
| [addHeader](#addHeader-java.io.InputStream-float-float-float-) | Adiciona imagem no topo da página. |
| [addHeader](#addHeader-java.lang.String-float-) | Adiciona imagem como cabeçalho às páginas do arquivo. |
| [addHeader](#addHeader-java.lang.String-float-float-float-) | Adiciona imagem como cabeçalho nas páginas. |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-) | Adiciona número de página à página. |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-float-float-) | Adiciona número de página na posição especificada da página. |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-int-) | Adiciona número de página às páginas. |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-) | Adiciona número de página às páginas do documento. |
| [addPageNumber](#addPageNumber-java.lang.String-) | Adiciona número de página ao arquivo. |
| [addPageNumber](#addPageNumber-java.lang.String-float-float-) | Adiciona número de página na posição especificada da página. |
| [addPageNumber](#addPageNumber-java.lang.String-int-) | Adiciona número de página às páginas. |
| [addPageNumber](#addPageNumber-java.lang.String-int-float-float-float-float-) | Adiciona número de página às páginas do documento. |
| [addStamp](#addStamp-com.aspose.pdf.facades.Stamp-) | Adiciona selo ao arquivo. |
| [close](#close--) | Fecha arquivos abertos e salva as alterações. |
| [dispose](#dispose--) | Obsoleto. |
| [getAttachmentName](#getAttachmentName--) | Obtém o nome do anexo quando o resultado da operação é armazenado em objetos HttpResponse como anexo. |
| [getContentDisposition](#getContentDisposition--) | Obtém como o conteúdo será armazenado quando o resultado da operação for armazenado no objeto HttpResponse. |
| [getDocument](#getDocument--) | Obtém o documento em que o PdfFileStamp está trabalhando. |
| [getInputFile](#getInputFile--) | Obtém o nome e o caminho do arquivo de entrada. |
| [getInputStream](#getInputStream--) | Obtém o fluxo de entrada. |
| [getKeepSecurity](#getKeepSecurity--) | Mantém a segurança se verdadeiro. |
| [getOutputFile](#getOutputFile--) | Obtém o nome e o caminho do arquivo de saída. |
| [getOutputStream](#getOutputStream--) | Obtém o fluxo de saída. |
| [getPageHeight](#getPageHeight--) | Obtém a altura da primeira página no arquivo souorce. |
| [getPageNumberRotation](#getPageNumberRotation--) | Obtém a rotação do número da página. |
| [getPageWidth](#getPageWidth--) | Obtém a largura da primeira página no arquivo de entrada. |
| [getSaveOptions](#getSaveOptions--) | Obtém as opções de salvamento quando o resultado é armazenado como HttpResponse. |
| [getStartingNumber](#getStartingNumber--) | Obtém ou define o número inicial para a primeira página no arquivo de entrada. |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | Define o nome do anexo quando o resultado da operação é armazenado em objetos HttpResponse como anexo. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | Define como o conteúdo será armazenado quando o resultado da operação for armazenado no objeto HttpResponse. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | Define o formato do arquivo PDF. |
| [setInputFile](#setInputFile-java.lang.String-) | Define o nome e o caminho do arquivo de entrada. |
| [setInputStream](#setInputStream-java.io.InputStream-) | Define o fluxo de entrada. |
| [setKeepSecurity](#setKeepSecurity-boolean-) | Definir Manter Segurança |
| [setOutputFile](#setOutputFile-java.lang.String-) | Define o nome e o caminho do arquivo de saída. |
| [setOutputStream](#setOutputStream-java.io.OutputStream-) | Define ou define o fluxo de saída. |
| [setPageNumberRotation](#setPageNumberRotation-float-) | Define a rotação do número da página. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Define as opções de salvamento quando o resultado é armazenado como HttpResponse. |
| [setStartingNumber](#setStartingNumber-int-) | Define o número inicial para a primeira página no arquivo de entrada. |

### POS_BOTTOM_LEFT {#POS_BOTTOM_LEFT}
```
static final int POS_BOTTOM_LEFT
```

Posição inferior esquerda.

### POS_BOTTOM_MIDDLE {#POS_BOTTOM_MIDDLE}
```
static final int POS_BOTTOM_MIDDLE
```

Posição inferior central.

### POS_BOTTOM_RIGHT {#POS_BOTTOM_RIGHT}
```
static final int POS_BOTTOM_RIGHT
```

Posição inferior direita.

### POS_SIDES_LEFT {#POS_SIDES_LEFT}
```
static final int POS_SIDES_LEFT
```

Posição esquerda.

### POS_SIDES_RIGHT {#POS_SIDES_RIGHT}
```
static final int POS_SIDES_RIGHT
```

Posição direita.

### POS_UPPER_LEFT {#POS_UPPER_LEFT}
```
static final int POS_UPPER_LEFT
```

Posição superior esquerda.

### POS_UPPER_MIDDLE {#POS_UPPER_MIDDLE}
```
static final int POS_UPPER_MIDDLE
```

Posição central superior.

### POS_UPPER_RIGHT {#POS_UPPER_RIGHT}
```
static final int POS_UPPER_RIGHT
```

Posição superior direita.

### addFooter {#addFooter-com.aspose.pdf.facades.FormattedText-float-}
Adiciona rodapé às páginas do documento.

### addFooter {#addFooter-com.aspose.pdf.facades.FormattedText-float-float-float-}
Adiciona rodapé às páginas do documento.

### addFooter {#addFooter-java.io.InputStream-float-}
Adiciona imagem como rodapé da página.

### addFooter {#addFooter-java.io.InputStream-float-float-float-}
Adiciona imagem como rodapé da página.

### addFooter {#addFooter-java.lang.String-float-}
Adiciona imagem como rodapé às páginas do documento.

### addFooter {#addFooter-java.lang.String-float-float-float-}
Adiciona imagem como rodapé das páginas.

### addHeader {#addHeader-com.aspose.pdf.facades.FormattedText-float-}
Adiciona cabeçalho à página.

### addHeader {#addHeader-com.aspose.pdf.facades.FormattedText-float-float-float-}
Adiciona cabeçalho às páginas do arquivo.

### addHeader {#addHeader-java.io.InputStream-float-}
Adiciona imagem como cabeçalho nas páginas.

### addHeader {#addHeader-java.io.InputStream-float-float-float-}
Adiciona imagem no topo da página.

### addHeader {#addHeader-java.lang.String-float-}
Adiciona imagem como cabeçalho às páginas do arquivo.

### addHeader {#addHeader-java.lang.String-float-float-float-}
Adiciona imagem como cabeçalho nas páginas.

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-}
Adiciona número de página à página.

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-float-float-}
Adiciona número de página na posição especificada da página.

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-int-}
Adiciona número de página às páginas.

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-}
Adiciona número de página às páginas do documento.

### addPageNumber {#addPageNumber-java.lang.String-}
Adiciona número de página ao arquivo.

### addPageNumber {#addPageNumber-java.lang.String-float-float-}
Adiciona número de página na posição especificada da página.

### addPageNumber {#addPageNumber-java.lang.String-int-}
Adiciona número de página às páginas.

### addPageNumber {#addPageNumber-java.lang.String-int-float-float-float-float-}
Adiciona número de página às páginas do documento.

### addStamp {#addStamp-com.aspose.pdf.facades.Stamp-}
Adiciona selo ao arquivo.

### close {#close--}
```
void close()
```

Fecha arquivos abertos e salva as alterações.

### dispose {#dispose--}
```
@Deprecated void dispose()
```

Obsoleto.

### getAttachmentName {#getAttachmentName--}
```
String getAttachmentName()
```

Obtém o nome do anexo quando o resultado da operação é armazenado em objetos HttpResponse como anexo.

**Returns:**
valor String

### getContentDisposition {#getContentDisposition--}
```
ContentDisposition getContentDisposition()
```

Obtém como o conteúdo será armazenado quando o resultado da operação for armazenado no objeto HttpResponse.

**Returns:**
Elemento ContentDisposition

### getDocument {#getDocument--}
```
IDocument getDocument()
```

Obtém o documento em que o PdfFileStamp está trabalhando.

**Returns:**
objeto IDocument

### getInputFile {#getInputFile--}
```
String getInputFile()
```

Obtém o nome e o caminho do arquivo de entrada.

**Returns:**
Objeto String

### getInputStream {#getInputStream--}
```
InputStream getInputStream()
```

Obtém o fluxo de entrada.

**Returns:**
objeto InputStream

### getKeepSecurity {#getKeepSecurity--}
```
boolean getKeepSecurity()
```

Mantém a segurança se verdadeiro.

**Returns:**
valor booleano

### getOutputFile {#getOutputFile--}
```
String getOutputFile()
```

Obtém o nome e o caminho do arquivo de saída.

**Returns:**
Objeto String

### getOutputStream {#getOutputStream--}
```
OutputStream getOutputStream()
```

Obtém o fluxo de saída.

**Returns:**
objeto OutputStream

### getPageHeight {#getPageHeight--}
```
float getPageHeight()
```

Obtém a altura da primeira página no arquivo souorce.

**Returns:**
valor float

### getPageNumberRotation {#getPageNumberRotation--}
```
float getPageNumberRotation()
```

Obtém a rotação do número da página.

**Returns:**
valor float

### getPageWidth {#getPageWidth--}
```
float getPageWidth()
```

Obtém a largura da primeira página no arquivo de entrada.

**Returns:**
valor float

### getSaveOptions {#getSaveOptions--}
```
SaveOptions getSaveOptions()
```

Obtém as opções de salvamento quando o resultado é armazenado como HttpResponse.

**Returns:**
Objeto SaveOptions

### getStartingNumber {#getStartingNumber--}
```
int getStartingNumber()
```

Obtém ou define o número inicial para a primeira página no arquivo de entrada.

**Returns:**
valor int

### setAttachmentName {#setAttachmentName-java.lang.String-}
Define o nome do anexo quando o resultado da operação é armazenado em objetos HttpResponse como anexo.

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
Define como o conteúdo será armazenado quando o resultado da operação for armazenado no objeto HttpResponse.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Define o formato do arquivo PDF.

### setInputFile {#setInputFile-java.lang.String-}
Define o nome e o caminho do arquivo de entrada.

### setInputStream {#setInputStream-java.io.InputStream-}
Define o fluxo de entrada.

### setKeepSecurity {#setKeepSecurity-boolean-}
```
void setKeepSecurity(boolean value)
```

Definir Manter Segurança

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setOutputFile {#setOutputFile-java.lang.String-}
Define o nome e o caminho do arquivo de saída.

### setOutputStream {#setOutputStream-java.io.OutputStream-}
Define ou define o fluxo de saída.

### setPageNumberRotation {#setPageNumberRotation-float-}
```
void setPageNumberRotation(float value)
```

Define a rotação do número da página.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor float |

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Define as opções de salvamento quando o resultado é armazenado como HttpResponse.

### setStartingNumber {#setStartingNumber-int-}
```
void setStartingNumber(int value)
```

Define o número inicial para a primeira página no arquivo de entrada.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |
