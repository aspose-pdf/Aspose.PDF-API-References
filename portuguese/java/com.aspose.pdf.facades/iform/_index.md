---
title: "IForm"
linktitle: "IForm"
second_title: "Referência da API Aspose.PDF para Java"
description: "Classe que representa o objeto de formulário Acro."
type: docs
weight: 250
url: /pt/java/com.aspose.pdf.facades/iform/
---
```
public interface IForm extends com.aspose.ms.System.IDisposable, Closeable
```

Classe que representa o objeto de formulário Acro.

## Métodos

| Método | Descrição |
| --- | --- |
| [close](#close--) | Fecha arquivos abertos sem quaisquer alterações. |
| [exportFdf](#exportFdf-java.io.OutputStream-) | Exporta o conteúdo dos campos do pdf para o fluxo fdf. |
| [exportXfdf](#exportXfdf-java.io.OutputStream-) | Exporta o conteúdo dos campos do pdf para o fluxo xml. |
| [exportXml](#exportXml-java.io.OutputStream-) | Exporta o conteúdo dos campos do pdf para o fluxo xml. |
| [fillBarcodeField](#fillBarcodeField-java.lang.String-java.lang.String-) | Preenche um campo de código de barras de acordo com seu nome de campo totalmente qualificado. |
| [fillField](#fillField-java.lang.String-boolean-) | Preenche o campo de caixa de seleção com um valor booleano. |
| [fillField](#fillField-java.lang.String-int-) | Preenche o campo de opção com um valor de índice válido de acordo com um nome de campo totalmente qualificado. |
| [fillField](#fillField-java.lang.String-java.lang.String-) | Preenche o campo com um valor válido de acordo com um nome de campo totalmente qualificado. |
| [fillField](#fillField-java.lang.String-java.lang.String:A-) | Preencha um campo com múltiplas seleções. Nota: apenas para o campo de lista AcroForm. |
| [fillField](#fillField-java.lang.String-java.lang.String-boolean-) | FillField |
| [fillImageField](#fillImageField-java.lang.String-java.io.InputStream-) | Sobrecarga da função FillImageField. |
| [fillImageField](#fillImageField-java.lang.String-java.lang.String-) | Cola uma imagem no campo de botão existente como sua aparência de acordo com seu nome de campo totalmente qualificado. |
| [flattenAllFields](#flattenAllFields--) | Achata todos os campos. |
| [flattenField](#flattenField-java.lang.String-) | Achata um campo especificado com o nome de campo totalmente qualificado. |
| [getAttachmentName](#getAttachmentName--) | Obtém ou define o nome do anexo quando o resultado da operação é armazenado em objetos HttpResponse como anexo. |
| [getButtonOptionCurrentValue](#getButtonOptionCurrentValue-java.lang.String-) | Retorna o valor atual dos campos de opção de botão de rádio. |
| [getButtonOptionValues](#getButtonOptionValues-java.lang.String-) | Obtém os campos de opção de botão de rádio e valores relacionados com base no nome do campo. |
| [getButtonOptionValuesInternal](#getButtonOptionValuesInternal-java.lang.String-) | Obtém os campos de opção de botão de rádio e valores relacionados com base no nome do campo. |
| [getContentDisposition](#getContentDisposition--) | Obtém ou define como o conteúdo será armazenado quando o resultado da operação for armazenado em um objeto HttpResponse. |
| [getDestFileName](#getDestFileName--) | Obtém o nome do arquivo de destino. |
| [getDestStream](#getDestStream--) | Obtém o fluxo de destino. |
| [getDocument](#getDocument--) | Obtém o formulário do documento em que está trabalhando. |
| [getField](#getField-java.lang.String-) | Obtém o valor do campo de acordo com o seu nome. |
| [getFieldFacade](#getFieldFacade-java.lang.String-) | Retorna o objeto FrohmFieldFacade contendo todos os atributos de aparência. |
| [getFieldFlag](#getFieldFlag-java.lang.String-) | Retorna as flags do campo. |
| [getFieldLimit](#getFieldLimit-java.lang.String-) | Obtém a limitação do campo de texto. |
| [getFieldNames](#getFieldNames--) | Obtém a lista de nomes de campos no formulário. |
| [getFieldType](#getFieldType-java.lang.String-) | Retorna o tipo do campo. |
| [getFormSubmitButtonNames](#getFormSubmitButtonNames--) | Obtém todos os nomes dos botões de envio do formulário. |
| [getFullFieldName](#getFullFieldName-java.lang.String-) | Obtém o nome completo do campo de acordo com seu nome curto. |
| [getRichText](#getRichText-java.lang.String-) | Obtém o valor de um campo Rich Text, incluindo as informações de formatação de cada caractere. |
| [getSaveOptions](#getSaveOptions--) | Obtém ou define as opções de salvamento quando o resultado é armazenado como HttpResponse. |
| [getSrcFileName](#getSrcFileName--) | Obtém o nome do arquivo de origem. |
| [getSrcStream](#getSrcStream--) | Obtém o fluxo de origem. |
| [getSubmitFlags](#getSubmitFlags-java.lang.String-) | Retorna as flags de submissão do botão de envio. |
| [importFdf](#importFdf-java.io.InputStream-) | Importa o conteúdo dos campos do arquivo fdf e os coloca no novo pdf. |
| [importXfdf](#importXfdf-java.io.InputStream-) | Importa o conteúdo dos campos do arquivo xfdf(xml) e os coloca no novo pdf. |
| [importXml](#importXml-java.io.InputStream-) | Importa o conteúdo dos campos do arquivo xml e os coloca no novo pdf. |
| [importXml](#importXml-java.io.InputStream-boolean-) | Importa o conteúdo dos campos do arquivo xml e os coloca no novo pdf. |
| [renameField](#renameField-java.lang.String-java.lang.String-) | Renomeia um campo. |
| [save](#save--) | Salva o valor dos campos preenchidos e fecha o documento Pdf aberto. |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | Define o nome do anexo quando o resultado da operação é armazenado em objetos HttpResponse como anexo. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | Define como o conteúdo será armazenado quando o resultado da operação for armazenado no objeto HttpResponse. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | Define o formato do arquivo PDF. |
| [setDestFileName](#setDestFileName-java.lang.String-) | Define o nome do arquivo de destino. |
| [setDestStream](#setDestStream-java.io.OutputStream-) | Obtém o fluxo de destino. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Obtém ou define as opções de salvamento quando o resultado é armazenado como HttpResponse. |
| [setSrcFileName](#setSrcFileName-java.lang.String-) | Define o nome do arquivo de origem. |
| [setSrcStream](#setSrcStream-java.io.InputStream-) | Obtém o fluxo de origem. |

### close {#close--}
```
void close()
```

Fecha arquivos abertos sem quaisquer alterações.

### exportFdf {#exportFdf-java.io.OutputStream-}
Exporta o conteúdo dos campos do pdf para o fluxo fdf.

### exportXfdf {#exportXfdf-java.io.OutputStream-}
Exporta o conteúdo dos campos do pdf para o fluxo xml.

### exportXml {#exportXml-java.io.OutputStream-}
Exporta o conteúdo dos campos do pdf para o fluxo xml.

### fillBarcodeField {#fillBarcodeField-java.lang.String-java.lang.String-}
Preenche um campo de código de barras de acordo com seu nome de campo totalmente qualificado.

### fillField {#fillField-java.lang.String-boolean-}
Preenche o campo de caixa de seleção com um valor booleano.

### fillField {#fillField-java.lang.String-int-}
Preenche o campo de opção com um valor de índice válido de acordo com um nome de campo totalmente qualificado.

### fillField {#fillField-java.lang.String-java.lang.String-}
Preenche o campo com um valor válido de acordo com um nome de campo totalmente qualificado.

### fillField {#fillField-java.lang.String-java.lang.String:A-}
Preencha um campo com múltiplas seleções. Nota: apenas para o campo de lista AcroForm.

### fillField {#fillField-java.lang.String-java.lang.String-boolean-}
FillField

### fillImageField {#fillImageField-java.lang.String-java.io.InputStream-}
Sobrecarga da função FillImageField.

### fillImageField {#fillImageField-java.lang.String-java.lang.String-}
Cola uma imagem no campo de botão existente como sua aparência de acordo com seu nome de campo totalmente qualificado.

### flattenAllFields {#flattenAllFields--}
```
void flattenAllFields()
```

Achata todos os campos.

### flattenField {#flattenField-java.lang.String-}
Achata um campo especificado com o nome de campo totalmente qualificado.

### getAttachmentName {#getAttachmentName--}
```
String getAttachmentName()
```

Obtém ou define o nome do anexo quando o resultado da operação é armazenado em objetos HttpResponse como anexo.

**Returns:**
objeto string

### getButtonOptionCurrentValue {#getButtonOptionCurrentValue-java.lang.String-}
Retorna o valor atual dos campos de opção de botão de rádio.

### getButtonOptionValues {#getButtonOptionValues-java.lang.String-}
Obtém os campos de opção de botão de rádio e valores relacionados com base no nome do campo.

### getButtonOptionValuesInternal {#getButtonOptionValuesInternal-java.lang.String-}
Obtém os campos de opção de botão de rádio e valores relacionados com base no nome do campo.

### getContentDisposition {#getContentDisposition--}
```
ContentDisposition getContentDisposition()
```

Obtém ou define como o conteúdo será armazenado quando o resultado da operação for armazenado em um objeto HttpResponse.

**Returns:**
Elemento ContentDisposition

### getDestFileName {#getDestFileName--}
```
String getDestFileName()
```

Obtém o nome do arquivo de destino.

**Returns:**
Objeto String

### getDestStream {#getDestStream--}
```
OutputStream getDestStream()
```

Obtém o fluxo de destino.

**Returns:**
objeto OutputStream

### getDocument {#getDocument--}
```
IDocument getDocument()
```

Obtém o formulário do documento em que está trabalhando.

**Returns:**
objeto IDocument

### getField {#getField-java.lang.String-}
Obtém o valor do campo de acordo com o seu nome.

### getFieldFacade {#getFieldFacade-java.lang.String-}
Retorna o objeto FrohmFieldFacade contendo todos os atributos de aparência.

### getFieldFlag {#getFieldFlag-java.lang.String-}
Retorna as flags do campo.

### getFieldLimit {#getFieldLimit-java.lang.String-}
Obtém a limitação do campo de texto.

### getFieldNames {#getFieldNames--}
```
String [] getFieldNames()
```

Obtém a lista de nomes de campos no formulário.

**Returns:**
Objeto String[]

### getFieldType {#getFieldType-java.lang.String-}
Retorna o tipo do campo.

### getFormSubmitButtonNames {#getFormSubmitButtonNames--}
```
String [] getFormSubmitButtonNames()
```

Obtém todos os nomes dos botões de envio do formulário.

**Returns:**
Objeto String[]

### getFullFieldName {#getFullFieldName-java.lang.String-}
Obtém o nome completo do campo de acordo com seu nome curto.

### getRichText {#getRichText-java.lang.String-}
Obtém o valor de um campo Rich Text, incluindo as informações de formatação de cada caractere.

### getSaveOptions {#getSaveOptions--}
```
SaveOptions getSaveOptions()
```

Obtém ou define as opções de salvamento quando o resultado é armazenado como HttpResponse.

**Returns:**
Objeto SaveOptions

### getSrcFileName {#getSrcFileName--}
```
String getSrcFileName()
```

Obtém o nome do arquivo de origem.

**Returns:**
Objeto String

### getSrcStream {#getSrcStream--}
```
InputStream getSrcStream()
```

Obtém o fluxo de origem.

**Returns:**
objeto InputStream

### getSubmitFlags {#getSubmitFlags-java.lang.String-}
Retorna as flags de submissão do botão de envio.

### importFdf {#importFdf-java.io.InputStream-}
Importa o conteúdo dos campos do arquivo fdf e os coloca no novo pdf.

### importXfdf {#importXfdf-java.io.InputStream-}
Importa o conteúdo dos campos do arquivo xfdf(xml) e os coloca no novo pdf.

### importXml {#importXml-java.io.InputStream-}
Importa o conteúdo dos campos do arquivo xml e os coloca no novo pdf.

### importXml {#importXml-java.io.InputStream-boolean-}
Importa o conteúdo dos campos do arquivo xml e os coloca no novo pdf.

### renameField {#renameField-java.lang.String-java.lang.String-}
Renomeia um campo.

### save {#save--}
```
void save()
```

Salva o valor dos campos preenchidos e fecha o documento Pdf aberto.

### setAttachmentName {#setAttachmentName-java.lang.String-}
Define o nome do anexo quando o resultado da operação é armazenado em objetos HttpResponse como anexo.

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
Define como o conteúdo será armazenado quando o resultado da operação for armazenado no objeto HttpResponse.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Define o formato do arquivo PDF.

### setDestFileName {#setDestFileName-java.lang.String-}
Define o nome do arquivo de destino.

### setDestStream {#setDestStream-java.io.OutputStream-}
Obtém o fluxo de destino.

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Obtém ou define as opções de salvamento quando o resultado é armazenado como HttpResponse.

### setSrcFileName {#setSrcFileName-java.lang.String-}
Define o nome do arquivo de origem.

### setSrcStream {#setSrcStream-java.io.InputStream-}
Obtém o fluxo de origem.
