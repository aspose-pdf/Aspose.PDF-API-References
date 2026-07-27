---
title: "FormWeb"
linktitle: "FormWeb"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representando a interface de formulário Acro."
type: docs
weight: 230
url: /pt/java/com.aspose.pdf.facades/formweb/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.FormWeb, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.FormWeb, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.FormWeb

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, IForm, ISaveableFacade, Closeable, AutoCloseable

```
public final class FormWeb extends SaveableFacade implements IForm
```

Representando a interface de formulário Acro.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [FormWeb](#FormWeb--) | <p> Construtor de FormWeb sem parâmetros. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-com.aspose.pdf.IDocument-) | <p> Construtor de FormWeb sem parâmetros. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-com.aspose.pdf.IDocument-java.io.OutputStream-) | <p> Construtor de FormWeb sem parâmetros. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-com.aspose.pdf.IDocument-java.lang.String-) | <p> Construtor de FormWeb sem parâmetros. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-java.io.InputStream-) | <p> Construtor de FormWeb sem parâmetros. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-java.io.InputStream-javax.servlet.http.HttpServletResponse-) | <p> Construtor de FormWeb sem parâmetros. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-java.io.InputStream-java.io.OutputStream-) | <p> Construtor de FormWeb sem parâmetros. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-java.io.InputStream-java.lang.String-) | <p> Construtor de FormWeb sem parâmetros. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-java.lang.String-) | <p> Construtor de FormWeb sem parâmetros. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-java.lang.String-javax.servlet.http.HttpServletResponse-) | <p> Construtor de FormWeb sem parâmetros. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-java.lang.String-java.io.OutputStream-) | <p> Construtor de FormWeb sem parâmetros. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-java.lang.String-java.lang.String-) | <p> Construtor de FormWeb sem parâmetros. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |

## Métodos

| Método | Descrição |
| --- | --- |
| [bindPdf](#bindPdf-java.io.InputStream-java.lang.String-) | Inicializa a fachada. |
| [bindPdf](#bindPdf-java.lang.String-java.lang.String-) | Inicializa a fachada. |
| [close](#close--) | Fecha todos os recursos abertos usados por este documento. |
| [dispose](#dispose--) | Obsoleto. |
| [exportFdf](#exportFdf-java.io.OutputStream-) | Exporta o conteúdo dos campos do pdf para o fluxo fdf. |
| [exportXfdf](#exportXfdf-java.io.OutputStream-) | Exporta o conteúdo dos campos do pdf para o fluxo xml. |
| [exportXml](#exportXml-java.io.OutputStream-) | Exporta o conteúdo dos campos do pdf para o fluxo xml. |
| [extractXfaData](#extractXfaData-java.io.OutputStream-) | Extrai o pacote de dados XFA |
| [fillBarcodeField](#fillBarcodeField-java.lang.String-java.lang.String-) | Preenche um campo de código de barras de acordo com seu nome de campo totalmente qualificado. |
| [fillField](#fillField-java.lang.String-boolean-) | Preenche o campo de caixa de seleção com um valor booleano. |
| [fillField](#fillField-java.lang.String-int-) | Preenche o campo de opção com um valor de índice válido de acordo com um nome de campo totalmente qualificado. |
| [fillField](#fillField-java.lang.String-java.lang.String-) | Preenche o campo com um valor válido de acordo com um nome de campo totalmente qualificado. |
| [fillField](#fillField-java.lang.String-java.lang.String:A-) | Preencha um campo com múltiplas seleções. Nota: apenas para o campo de lista AcroForm. |
| [fillField](#fillField-java.lang.String-java.lang.String-boolean-) | Preenche o campo com o valor especificado. |
| [fillFields](#fillFields-java.lang.String:A-java.lang.String:A-java.io.OutputStream-) | Preenche os campos de caixa de texto com valores de texto e salva o documento. |
| [fillImageField](#fillImageField-java.lang.String-java.io.InputStream-) | Sobrecarga da função FillImageField. |
| [fillImageField](#fillImageField-java.lang.String-java.lang.String-) | Cola uma imagem no campo de botão existente como sua aparência de acordo com seu nome de campo totalmente qualificado. |
| [flattenAllFields](#flattenAllFields--) | Achata todos os campos. |
| [flattenField](#flattenField-java.lang.String-) | Achata um campo especificado com o nome de campo totalmente qualificado. |
| [getAttachmentName](#getAttachmentName--) | Obtém o nome do anexo quando o resultado da operação é armazenado em objetos HttpResponse como anexo. |
| [getButtonOptionCurrentValue](#getButtonOptionCurrentValue-java.lang.String-) | Retorna o valor atual dos campos de opção de botão de rádio. |
| [getButtonOptionValues](#getButtonOptionValues-java.lang.String-) | Obtém os campos de opção de botão de rádio e valores relacionados com base no nome do campo. |
| [getButtonOptionValuesInternal](#getButtonOptionValuesInternal-java.lang.String-) | Obtém os campos de opção de botão de rádio e valores relacionados com base no nome do campo. |
| [getContentDisposition](#getContentDisposition--) | O conteúdo Getshow será armazenado quando o resultado da operação for armazenado no objeto HttpResponse. |
| [getDestFileName](#getDestFileName--) | Obsoleto. |
| [getDestStream](#getDestStream--) | Obsoleto. |
| [getField](#getField-java.lang.String-) | Obtém o valor do campo de acordo com o seu nome. |
| [getFieldFacade](#getFieldFacade-java.lang.String-) | Retorna o objeto FrohmFieldFacade contendo todos os atributos de aparência. |
| [getFieldFlag](#getFieldFlag-java.lang.String-) | Retorna as flags do campo. |
| [getFieldLimit](#getFieldLimit-java.lang.String-) | Obtém a limitação do campo de texto. |
| [getFieldNames](#getFieldNames--) | Obtém a lista de nomes de campos no formulário. |
| [getFieldType](#getFieldType-java.lang.String-) | Retorna o tipo do campo. |
| [getFormSubmitButtonNames](#getFormSubmitButtonNames--) | Obtém todos os nomes dos botões de envio do formulário. |
| [getFullFieldName](#getFullFieldName-java.lang.String-) | Obtém o nome completo do campo de acordo com seu nome curto. |
| [getImportResult](#getImportResult--) | Resultado da última operação de importação. |
| [getResponse](#getResponse--) | Obtém ou define o objeto Response onde o resultado da operação será armazenado. |
| [getRichText](#getRichText-java.lang.String-) | Obtém o valor de um campo Rich Text, incluindo as informações de formatação de cada caractere. |
| [getSaveOptions](#getSaveOptions--) | Obtém ou define as opções de salvamento quando o resultado é armazenado como HttpResponse. |
| [getSrcFileName](#getSrcFileName--) | Obsoleto. |
| [getSrcStream](#getSrcStream--) | Obtém o fluxo de origem. |
| [getSubmitFlags](#getSubmitFlags-java.lang.String-) | Retorna as flags de submissão do botão de envio. |
| [importFdf](#importFdf-java.io.InputStream-) | Importa o conteúdo dos campos do arquivo fdf e os coloca no novo pdf. |
| [importXfdf](#importXfdf-java.io.InputStream-) | Importa o conteúdo dos campos do arquivo xfdf(xml) e os coloca no novo pdf. |
| [importXml](#importXml-java.io.InputStream-) | Importa o conteúdo dos campos do arquivo xml e os coloca no novo pdf. |
| [importXml](#importXml-java.io.InputStream-boolean-) | Importa o conteúdo dos campos do arquivo xml e os coloca no novo pdf. |
| [importXml](#importXml-java.lang.String-) | Importa o conteúdo dos campos do arquivo xml e os coloca no novo pdf. |
| [isRequiredField](#isRequiredField-java.lang.String-) | Determina se o campo é obrigatório ou não. |
| [renameField](#renameField-java.lang.String-java.lang.String-) | Renomeia um campo. |
| [save](#save--) | <p> Salva o valor dos campos preenchidos e fecha o documento Pdf aberto. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_Changed.pdf\"); form.fillField(\"textField\", \"new value\"); form.save(); </pre> |
| [save](#save-java.io.OutputStream-) | <p> Salva o valor dos campos preenchidos e fecha o documento Pdf aberto. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_Changed.pdf\"); form.fillField(\"textField\", \"new value\"); form.save(); </pre> |
| [save](#save-java.lang.String-) | <p> Salva o valor dos campos preenchidos e fecha o documento Pdf aberto. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_Changed.pdf\"); form.fillField(\"textField\", \"new value\"); form.save(); </pre> |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | Define o nome do anexo quando o resultado da operação é armazenado em objetos HttpResponse como anexo. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | Define como o conteúdo será armazenado quando o resultado da operação for armazenado no objeto HttpResponse. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | Define o formato do arquivo PDF. |
| [setDestFileName](#setDestFileName-java.lang.String-) | Obsoleto. |
| [setDestStream](#setDestStream-java.io.OutputStream-) | Obsoleto. |
| [setResponse](#setResponse-javax.servlet.http.HttpServletResponse-) | Obtém ou define o objeto Response onde o resultado da operação será armazenado. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Obtém ou define as opções de salvamento quando o resultado é armazenado como HttpResponse. |
| [setSrcFileName](#setSrcFileName-java.lang.String-) | Obsoleto. |
| [setSrcStream](#setSrcStream-java.io.InputStream-) | Obtém o fluxo de origem. |
| [setXfaData](#setXfaData-java.io.InputStream-) | Substitui os dados XFA pelo pacote de dados especificado. |

### FormWeb {#FormWeb--}
```
public FormWeb()
```

<p> Construtor de FormWeb sem parâmetros. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-com.aspose.pdf.IDocument-}
<p> Construtor de FormWeb sem parâmetros. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-com.aspose.pdf.IDocument-java.io.OutputStream-}
<p> Construtor de FormWeb sem parâmetros. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-com.aspose.pdf.IDocument-java.lang.String-}
<p> Construtor de FormWeb sem parâmetros. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-java.io.InputStream-}
<p> Construtor de FormWeb sem parâmetros. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-java.io.InputStream-javax.servlet.http.HttpServletResponse-}
<p> Construtor de FormWeb sem parâmetros. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-java.io.InputStream-java.io.OutputStream-}
<p> Construtor de FormWeb sem parâmetros. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-java.io.InputStream-java.lang.String-}
<p> Construtor de FormWeb sem parâmetros. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-java.lang.String-}
<p> Construtor de FormWeb sem parâmetros. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-java.lang.String-javax.servlet.http.HttpServletResponse-}
<p> Construtor de FormWeb sem parâmetros. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-java.lang.String-java.io.OutputStream-}
<p> Construtor de FormWeb sem parâmetros. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-java.lang.String-java.lang.String-}
<p> Construtor de FormWeb sem parâmetros. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### bindPdf {#bindPdf-java.io.InputStream-java.lang.String-}
Inicializa a fachada.

### bindPdf {#bindPdf-java.lang.String-java.lang.String-}
Inicializa a fachada.

### close {#close--}
```
public void close()
```

Fecha todos os recursos abertos usados por este documento.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Obsoleto.

### exportFdf {#exportFdf-java.io.OutputStream-}
Exporta o conteúdo dos campos do pdf para o fluxo fdf.

### exportXfdf {#exportXfdf-java.io.OutputStream-}
Exporta o conteúdo dos campos do pdf para o fluxo xml.

### exportXml {#exportXml-java.io.OutputStream-}
Exporta o conteúdo dos campos do pdf para o fluxo xml.

### extractXfaData {#extractXfaData-java.io.OutputStream-}
Extrai o pacote de dados XFA

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
Preenche o campo com o valor especificado.

### fillFields {#fillFields-java.lang.String:A-java.lang.String:A-java.io.OutputStream-}
Preenche os campos de caixa de texto com valores de texto e salva o documento.

### fillImageField {#fillImageField-java.lang.String-java.io.InputStream-}
Sobrecarga da função FillImageField.

### fillImageField {#fillImageField-java.lang.String-java.lang.String-}
Cola uma imagem no campo de botão existente como sua aparência de acordo com seu nome de campo totalmente qualificado.

### flattenAllFields {#flattenAllFields--}
```
public void flattenAllFields()
```

Achata todos os campos.

### flattenField {#flattenField-java.lang.String-}
Achata um campo especificado com o nome de campo totalmente qualificado.

### getAttachmentName {#getAttachmentName--}
```
public String getAttachmentName()
```

Obtém o nome do anexo quando o resultado da operação é armazenado em objetos HttpResponse como anexo.

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
public ContentDisposition getContentDisposition()
```

O conteúdo Getshow será armazenado quando o resultado da operação for armazenado no objeto HttpResponse.

**Returns:**
Elemento ContentDisposition

### getDestFileName {#getDestFileName--}
```
@Deprecated public String getDestFileName()
```

Obsoleto.

**Returns:**
Objeto String

### getDestStream {#getDestStream--}
```
@Deprecated public OutputStream getDestStream()
```

Obsoleto.

**Returns:**
objeto OutputStream

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
public String [] getFieldNames()
```

Obtém a lista de nomes de campos no formulário.

**Returns:**
Objeto String[]

### getFieldType {#getFieldType-java.lang.String-}
Retorna o tipo do campo.

### getFormSubmitButtonNames {#getFormSubmitButtonNames--}
```
public String [] getFormSubmitButtonNames()
```

Obtém todos os nomes dos botões de envio do formulário.

**Returns:**
Objeto String[]

### getFullFieldName {#getFullFieldName-java.lang.String-}
Obtém o nome completo do campo de acordo com seu nome curto.

### getImportResult {#getImportResult--}
```
public com.aspose.pdf.facades.AForm.FormImportResult[] getImportResult()
```

Resultado da última operação de importação.

**Returns:**
FormImportResult[] array

### getResponse {#getResponse--}
```
public javax.servlet.http.HttpServletResponse getResponse()
```

Obtém ou define o objeto Response onde o resultado da operação será armazenado.

**Returns:**
Objeto HttpServletResponse

### getRichText {#getRichText-java.lang.String-}
Obtém o valor de um campo Rich Text, incluindo as informações de formatação de cada caractere.

### getSaveOptions {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```

Obtém ou define as opções de salvamento quando o resultado é armazenado como HttpResponse.

**Returns:**
Objeto SaveOptions

### getSrcFileName {#getSrcFileName--}
```
@Deprecated public String getSrcFileName()
```

Obsoleto.

**Returns:**
Objeto String

### getSrcStream {#getSrcStream--}
```
public InputStream getSrcStream()
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

### importXml {#importXml-java.lang.String-}
Importa o conteúdo dos campos do arquivo xml e os coloca no novo pdf.

### isRequiredField {#isRequiredField-java.lang.String-}
Determina se o campo é obrigatório ou não.

### renameField {#renameField-java.lang.String-java.lang.String-}
Renomeia um campo.

### save {#save--}
```
public void save()
```

<p> Salva o valor dos campos preenchidos e fecha o documento Pdf aberto. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_Changed.pdf\"); form.fillField(\"textField\", \"new value\"); form.save(); </pre>

### save {#save-java.io.OutputStream-}
<p> Salva o valor dos campos preenchidos e fecha o documento Pdf aberto. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_Changed.pdf\"); form.fillField(\"textField\", \"new value\"); form.save(); </pre>

### save {#save-java.lang.String-}
<p> Salva o valor dos campos preenchidos e fecha o documento Pdf aberto. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_Changed.pdf\"); form.fillField(\"textField\", \"new value\"); form.save(); </pre>

### setAttachmentName {#setAttachmentName-java.lang.String-}
Define o nome do anexo quando o resultado da operação é armazenado em objetos HttpResponse como anexo.

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
Define como o conteúdo será armazenado quando o resultado da operação for armazenado no objeto HttpResponse.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Define o formato do arquivo PDF.

### setDestFileName {#setDestFileName-java.lang.String-}
Obsoleto.

### setDestStream {#setDestStream-java.io.OutputStream-}
Obsoleto.

### setResponse {#setResponse-javax.servlet.http.HttpServletResponse-}
Obtém ou define o objeto Response onde o resultado da operação será armazenado.

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Obtém ou define as opções de salvamento quando o resultado é armazenado como HttpResponse.

### setSrcFileName {#setSrcFileName-java.lang.String-}
Obsoleto.

### setSrcStream {#setSrcStream-java.io.InputStream-}
Obtém o fluxo de origem.

### setXfaData {#setXfaData-java.io.InputStream-}
Substitui os dados XFA pelo pacote de dados especificado.
