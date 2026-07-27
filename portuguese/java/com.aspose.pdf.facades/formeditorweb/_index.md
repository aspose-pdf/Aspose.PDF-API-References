---
title: "FormEditorWeb"
linktitle: "FormEditorWeb"
second_title: "Referência da API Aspose.PDF para Java"
description: "Classe para editar formulários (adicionar/excluir campo etc)"
type: docs
weight: 210
url: /pt/java/com.aspose.pdf.facades/formeditorweb/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.FormEditorWeb, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.FormEditorWeb, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.FormEditorWeb

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, IFormEditor, ISaveableFacade, Closeable, AutoCloseable

```
public final class FormEditorWeb extends SaveableFacade implements IFormEditor
```

Classe para editar formulários (adicionar/excluir campo etc)

## Construtores

| Construtor | Descrição |
| --- | --- |
| [FormEditorWeb](#FormEditorWeb--) | <p> Construtor para FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre> |
| [FormEditorWeb](#FormEditorWeb-com.aspose.pdf.IDocument-) | <p> Construtor para FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre> |
| [FormEditorWeb](#FormEditorWeb-com.aspose.pdf.IDocument-java.io.OutputStream-) | <p> Construtor para FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre> |
| [FormEditorWeb](#FormEditorWeb-com.aspose.pdf.IDocument-java.lang.String-) | <p> Construtor para FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre> |
| [FormEditorWeb](#FormEditorWeb-java.io.InputStream-javax.servlet.http.HttpServletResponse-) | <p> Construtor para FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre> |
| [FormEditorWeb](#FormEditorWeb-java.io.InputStream-java.io.OutputStream-) | <p> Construtor para FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre> |
| [FormEditorWeb](#FormEditorWeb-java.lang.String-javax.servlet.http.HttpServletResponse-) | <p> Construtor para FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre> |
| [FormEditorWeb](#FormEditorWeb-java.lang.String-java.lang.String-) | <p> Construtor para FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre> |

## Métodos

| Método | Descrição |
| --- | --- |
| [addField](#addField-com.aspose.pdf.facades.FieldType-java.lang.String-int-float-float-float-float-) | Adicionar campo do tipo especificado ao formulário. |
| [addField](#addField-com.aspose.pdf.facades.FieldType-java.lang.String-java.lang.String-int-float-float-float-float-) | Adicionar campo do tipo especificado ao formulário. |
| [addFieldScript](#addFieldScript-java.lang.String-java.lang.String-) | Adicionar JavaScript para um campo PushButton. |
| [addListItem](#addListItem-java.lang.String-java.lang.String-) | Adiciona um novo item à caixa de lista. |
| [addListItem](#addListItem-java.lang.String-java.lang.String:A-) | Adiciona um novo item com valor Export ao campo de caixa de lista existente, apenas para o campo de caixa de combinação AcroForm. |
| [addSubmitBtn](#addSubmitBtn-java.lang.String-int-java.lang.String-java.lang.String-float-float-float-float-) | Adiciona botão de envio no formulário. |
| [close](#close--) | Fecha todos os recursos usados por este documento. |
| [copyInnerField](#copyInnerField-java.lang.String-java.lang.String-int-) | Copia um campo existente para a mesma posição no número de página especificado. |
| [copyInnerField](#copyInnerField-java.lang.String-java.lang.String-int-float-float-) | Copia um campo existente para uma nova posição especificada tanto pelo número da página quanto pelas coordenadas. |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-) | Copia um campo existente de um documento PDF para outro documento com o número de página original e coordenadas. |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-int-) | Copia um campo existente de um documento PDF para outro documento com o número de página especificado e coordenadas originais. |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-int-float-float-) | Copia um campo existente de um documento PDF para outro documento com o número de página e coordenadas especificados. |
| [decorateField](#decorateField--) | Altera os atributos visuais de todos os campos no documento PDF. |
| [decorateField](#decorateField-com.aspose.pdf.facades.FieldType-) | Altera os atributos visuais de todos os campos com o tipo de campo especificado. |
| [decorateField](#decorateField-java.lang.String-) | Altera os atributos visuais do campo especificado. |
| [delListItem](#delListItem-java.lang.String-java.lang.String-) | Exclui item do campo de lista. |
| [dispose](#dispose--) | Obsoleto. |
| [getAttachmentName](#getAttachmentName--) | Obtém o nome do anexo quando o resultado da operação é armazenado em objetos HttpResponse como anexo. |
| [getContentDisposition](#getContentDisposition--) | Obtém como o conteúdo será armazenado quando o resultado da operação for armazenado no objeto HttpResponse. |
| [getDestFileName](#getDestFileName--) | Obsoleto. |
| [getDestStream](#getDestStream--) | Obtém o fluxo de destino. |
| [getExportItems](#getExportItems--) | Obtém opções para caixa de combinação com valores de exportação. |
| [getFacade](#getFacade--) | Obtém os atributos visuais do campo. |
| [getFieldAppearance](#getFieldAppearance-java.lang.String-) | Obter sinalizadores do campo. |
| [getItems](#getItems--) | Retorna array de itens |
| [getRadioButtonItemSize](#getRadioButtonItemSize--) | Obtém ou define o tamanho do item do botão de opção (quando um novo campo de botão de opção é adicionado). |
| [getRadioGap](#getRadioGap--) | Obter o membro que registra o espaço entre dois botões de rádio vizinhos em pixels, o padrão é 50. |
| [getRadioHoriz](#getRadioHoriz--) | Obtém a bandeira que indica se os botões de opção estão dispostos horizontalmente ou verticalmente, o valor padrão é verdadeiro. |
| [getResponse](#getResponse--) | Obtém o objeto Response onde o resultado da operação será armazenado. |
| [getSaveOptions](#getSaveOptions--) | Obtém as opções de salvamento quando o resultado é armazenado como HttpResponse. |
| [getSrcFileName](#getSrcFileName--) | Obsoleto. |
| [getSrcStream](#getSrcStream--) | Obtém o fluxo de origem. |
| [getSubmitFlag](#getSubmitFlag--) | Obter os sinalizadores de submissão do botão de envio. |
| [moveField](#moveField-java.lang.String-float-float-float-float-) | Define nova posição do campo. |
| [removeField](#removeField-java.lang.String-) | Remove o campo do formulário. |
| [removeFieldAction](#removeFieldAction-java.lang.String-) | Remove a ação de envio do campo. |
| [renameField](#renameField-java.lang.String-java.lang.String-) | Altera o nome do campo. |
| [resetFacade](#resetFacade--) | Redefine todos os atributos visuais para valor vazio. |
| [resetInnerFacade](#resetInnerFacade--) | Redefine todos os atributos visuais da fachada interna para valor vazio. |
| [save](#save--) | Salva as alterações no arquivo de destino. |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | Define o nome do anexo quando o resultado da operação é armazenado em objetos HttpResponse como anexo. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | Define como o conteúdo será armazenado quando o resultado da operação for armazenado no objeto HttpResponse. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | Define o formato de arquivo PDF PdfFormat. |
| [setDestFileName](#setDestFileName-java.lang.String-) | Obsoleto. |
| [setDestStream](#setDestStream-java.io.OutputStream-) | Define o fluxo de destino. |
| [setExportItems](#setExportItems-java.lang.String:A:A-) | Define opções para caixa de combinação com valores de exportação. |
| [setFacade](#setFacade-com.aspose.pdf.facades.FormFieldFacade-) | Define atributos visuais do campo. |
| [setFieldAlignment](#setFieldAlignment-java.lang.String-int-) | Define o estilo de alinhamento de um campo de texto. |
| [setFieldAlignmentV](#setFieldAlignmentV-java.lang.String-int-) | Define o estilo de alinhamento vertical de um campo de texto. |
| [setFieldAppearance](#setFieldAppearance-java.lang.String-int-) | Define bandeiras do campo |
| [setFieldAttribute](#setFieldAttribute-java.lang.String-int-) | Define atributos do campo. |
| [setFieldCombNumber](#setFieldCombNumber-java.lang.String-int-) | Define o número de divisões (combs) para um campo de texto de linha única regular (o campo é automaticamente dividido em tantas posições igualmente espaçadas, ou combs, quanto o valor do parâmetro combNumber). |
| [setFieldLimit](#setFieldLimit-java.lang.String-int-) | Define a contagem máxima de caracteres do campo de texto. |
| [setFieldScript](#setFieldScript-java.lang.String-java.lang.String-) | Define JavaScript para um campo PushButton. |
| [setItems](#setItems-java.lang.String:A-) | Define itens que serão adicionados à caixa de lista ou caixa de combinação recém-criada. |
| [setRadioButtonItemSize](#setRadioButtonItemSize-double-) | Obtém ou define o tamanho do item do botão de opção (quando um novo campo de botão de opção é adicionado). |
| [setRadioGap](#setRadioGap-float-) | Define o membro para registrar o espaço entre dois botões de opção vizinhos em pixels, o padrão é 50. |
| [setRadioHoriz](#setRadioHoriz-boolean-) | Define a bandeira que indica se os botões de opção estão dispostos horizontalmente ou verticalmente, o valor padrão é verdadeiro. |
| [setResponse](#setResponse-javax.servlet.http.HttpServletResponse-) | Define o objeto Response onde o resultado da operação será armazenado. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Define as opções de salvamento quando o resultado é armazenado como HttpResponse. |
| [setSrcFileName](#setSrcFileName-java.lang.String-) | Obsoleto. |
| [setSrcStream](#setSrcStream-java.io.InputStream-) | Define o fluxo de origem. |
| [setSubmitFlag](#setSubmitFlag-java.lang.String-com.aspose.pdf.facades.SubmitFormFlag-) | Define a bandeira de envio do botão de envio. |
| [setSubmitFlag](#setSubmitFlag-com.aspose.pdf.facades.SubmitFormFlag-) | Defina as bandeiras de envio do botão de envio |
| [setSubmitUrl](#setSubmitUrl-java.lang.String-java.lang.String-) | Define a URL do botão. |
| [single2Multiple](#single2Multiple-java.lang.String-) | Altera um campo de texto de linha única para um de múltiplas linhas. |

### FormEditorWeb {#FormEditorWeb--}
```
public FormEditorWeb()
```

<p> Construtor para FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre>

### FormEditorWeb {#FormEditorWeb-com.aspose.pdf.IDocument-}
<p> Construtor para FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre>

### FormEditorWeb {#FormEditorWeb-com.aspose.pdf.IDocument-java.io.OutputStream-}
<p> Construtor para FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre>

### FormEditorWeb {#FormEditorWeb-com.aspose.pdf.IDocument-java.lang.String-}
<p> Construtor para FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre>

### FormEditorWeb {#FormEditorWeb-java.io.InputStream-javax.servlet.http.HttpServletResponse-}
<p> Construtor para FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre>

### FormEditorWeb {#FormEditorWeb-java.io.InputStream-java.io.OutputStream-}
<p> Construtor para FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre>

### FormEditorWeb {#FormEditorWeb-java.lang.String-javax.servlet.http.HttpServletResponse-}
<p> Construtor para FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre>

### FormEditorWeb {#FormEditorWeb-java.lang.String-java.lang.String-}
<p> Construtor para FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre>

### addField {#addField-com.aspose.pdf.facades.FieldType-java.lang.String-int-float-float-float-float-}
Adicionar campo do tipo especificado ao formulário.

### addField {#addField-com.aspose.pdf.facades.FieldType-java.lang.String-java.lang.String-int-float-float-float-float-}
Adicionar campo do tipo especificado ao formulário.

### addFieldScript {#addFieldScript-java.lang.String-java.lang.String-}
Adicionar JavaScript para um campo PushButton.

### addListItem {#addListItem-java.lang.String-java.lang.String-}
Adiciona um novo item à caixa de lista.

### addListItem {#addListItem-java.lang.String-java.lang.String:A-}
Adiciona um novo item com valor Export ao campo de caixa de lista existente, apenas para o campo de caixa de combinação AcroForm.

### addSubmitBtn {#addSubmitBtn-java.lang.String-int-java.lang.String-java.lang.String-float-float-float-float-}
Adiciona botão de envio no formulário.

### close {#close--}
```
public void close()
```

Fecha todos os recursos usados por este documento.

### copyInnerField {#copyInnerField-java.lang.String-java.lang.String-int-}
Copia um campo existente para a mesma posição no número de página especificado.

### copyInnerField {#copyInnerField-java.lang.String-java.lang.String-int-float-float-}
Copia um campo existente para uma nova posição especificada tanto pelo número da página quanto pelas coordenadas.

### copyOuterField {#copyOuterField-java.lang.String-java.lang.String-}
Copia um campo existente de um documento PDF para outro documento com o número de página original e coordenadas.

### copyOuterField {#copyOuterField-java.lang.String-java.lang.String-int-}
Copia um campo existente de um documento PDF para outro documento com o número de página especificado e coordenadas originais.

### copyOuterField {#copyOuterField-java.lang.String-java.lang.String-int-float-float-}
Copia um campo existente de um documento PDF para outro documento com o número de página e coordenadas especificados.

### decorateField {#decorateField--}
```
public void decorateField()
```

Altera os atributos visuais de todos os campos no documento PDF.

### decorateField {#decorateField-com.aspose.pdf.facades.FieldType-}
Altera os atributos visuais de todos os campos com o tipo de campo especificado.

### decorateField {#decorateField-java.lang.String-}
Altera os atributos visuais do campo especificado.

### delListItem {#delListItem-java.lang.String-java.lang.String-}
Exclui item do campo de lista.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Obsoleto.

### getAttachmentName {#getAttachmentName--}
```
public String getAttachmentName()
```

Obtém o nome do anexo quando o resultado da operação é armazenado em objetos HttpResponse como anexo.

**Returns:**
Objeto String

### getContentDisposition {#getContentDisposition--}
```
public ContentDisposition getContentDisposition()
```

Obtém como o conteúdo será armazenado quando o resultado da operação for armazenado no objeto HttpResponse.

**Returns:**
Elemento ContentDisposition

### getDestFileName {#getDestFileName--}
```
@Deprecated public String getDestFileName()
```

Obsoleto.

**Returns:**
valor de string

### getDestStream {#getDestStream--}
```
public OutputStream getDestStream()
```

Obtém o fluxo de destino.

**Returns:**
objeto OutputStream

### getExportItems {#getExportItems--}
```
public String [][] getExportItems()
```

Obtém opções para caixa de combinação com valores de exportação.

**Returns:**
Matriz String[][]

### getFacade {#getFacade--}
```
public FormFieldFacade getFacade()
```

Obtém os atributos visuais do campo.

**Returns:**
Objeto FormFieldFacade

### getFieldAppearance {#getFieldAppearance-java.lang.String-}
Obter sinalizadores do campo.

### getItems {#getItems--}
```
public String [] getItems()
```

Retorna array de itens

**Returns:**
Objeto String[]

### getRadioButtonItemSize {#getRadioButtonItemSize--}
```
public double getRadioButtonItemSize()
```

Obtém ou define o tamanho do item do botão de opção (quando um novo campo de botão de opção é adicionado).

**Returns:**
valor double

### getRadioGap {#getRadioGap--}
```
public float getRadioGap()
```

Obter o membro que registra o espaço entre dois botões de rádio vizinhos em pixels, o padrão é 50.

**Returns:**
valor float

### getRadioHoriz {#getRadioHoriz--}
```
public boolean getRadioHoriz()
```

Obtém a bandeira que indica se os botões de opção estão dispostos horizontalmente ou verticalmente, o valor padrão é verdadeiro.

**Returns:**
valor booleano

### getResponse {#getResponse--}
```
public javax.servlet.http.HttpServletResponse getResponse()
```

Obtém o objeto Response onde o resultado da operação será armazenado.

**Returns:**
Objeto HttpServletResponse

### getSaveOptions {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```

Obtém as opções de salvamento quando o resultado é armazenado como HttpResponse.

**Returns:**
Objeto SaveOptions

### getSrcFileName {#getSrcFileName--}
```
@Deprecated public String getSrcFileName()
```

Obsoleto.

**Returns:**
valor de string

### getSrcStream {#getSrcStream--}
```
public InputStream getSrcStream()
```

Obtém o fluxo de origem.

**Returns:**
objeto InputStream

### getSubmitFlag {#getSubmitFlag--}
```
public SubmitFormFlag getSubmitFlag()
```

Obter os sinalizadores de submissão do botão de envio.

**Returns:**
Elemento SubmitFormFlag

### moveField {#moveField-java.lang.String-float-float-float-float-}
Define nova posição do campo.

### removeField {#removeField-java.lang.String-}
Remove o campo do formulário.

### removeFieldAction {#removeFieldAction-java.lang.String-}
Remove a ação de envio do campo.

### renameField {#renameField-java.lang.String-java.lang.String-}
Altera o nome do campo.

### resetFacade {#resetFacade--}
```
public void resetFacade()
```

Redefine todos os atributos visuais para valor vazio.

### resetInnerFacade {#resetInnerFacade--}
```
public void resetInnerFacade()
```

Redefine todos os atributos visuais da fachada interna para valor vazio.

### save {#save--}
```
public void save()
```

Salva as alterações no arquivo de destino.

### setAttachmentName {#setAttachmentName-java.lang.String-}
Define o nome do anexo quando o resultado da operação é armazenado em objetos HttpResponse como anexo.

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
Define como o conteúdo será armazenado quando o resultado da operação for armazenado no objeto HttpResponse.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Define o formato de arquivo PDF PdfFormat.

### setDestFileName {#setDestFileName-java.lang.String-}
Obsoleto.

### setDestStream {#setDestStream-java.io.OutputStream-}
Define o fluxo de destino.

### setExportItems {#setExportItems-java.lang.String:A:A-}
Define opções para caixa de combinação com valores de exportação.

### setFacade {#setFacade-com.aspose.pdf.facades.FormFieldFacade-}
Define atributos visuais do campo.

### setFieldAlignment {#setFieldAlignment-java.lang.String-int-}
Define o estilo de alinhamento de um campo de texto.

### setFieldAlignmentV {#setFieldAlignmentV-java.lang.String-int-}
Define o estilo de alinhamento vertical de um campo de texto.

### setFieldAppearance {#setFieldAppearance-java.lang.String-int-}
Define bandeiras do campo

### setFieldAttribute {#setFieldAttribute-java.lang.String-int-}
Define atributos do campo.

### setFieldCombNumber {#setFieldCombNumber-java.lang.String-int-}
Define o número de divisões (combs) para um campo de texto de linha única regular (o campo é automaticamente dividido em tantas posições igualmente espaçadas, ou combs, quanto o valor do parâmetro combNumber).

### setFieldLimit {#setFieldLimit-java.lang.String-int-}
Define a contagem máxima de caracteres do campo de texto.

### setFieldScript {#setFieldScript-java.lang.String-java.lang.String-}
Define JavaScript para um campo PushButton.

### setItems {#setItems-java.lang.String:A-}
Define itens que serão adicionados à caixa de lista ou caixa de combinação recém-criada.

### setRadioButtonItemSize {#setRadioButtonItemSize-double-}
```
public void setRadioButtonItemSize(double value)
```

Obtém ou define o tamanho do item do botão de opção (quando um novo campo de botão de opção é adicionado).

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### setRadioGap {#setRadioGap-float-}
```
public void setRadioGap(float value)
```

Define o membro para registrar o espaço entre dois botões de opção vizinhos em pixels, o padrão é 50.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor float |

### setRadioHoriz {#setRadioHoriz-boolean-}
```
public void setRadioHoriz(boolean value)
```

Define a bandeira que indica se os botões de opção estão dispostos horizontalmente ou verticalmente, o valor padrão é verdadeiro.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setResponse {#setResponse-javax.servlet.http.HttpServletResponse-}
Define o objeto Response onde o resultado da operação será armazenado.

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Define as opções de salvamento quando o resultado é armazenado como HttpResponse.

### setSrcFileName {#setSrcFileName-java.lang.String-}
Obsoleto.

### setSrcStream {#setSrcStream-java.io.InputStream-}
Define o fluxo de origem.

### setSubmitFlag {#setSubmitFlag-java.lang.String-com.aspose.pdf.facades.SubmitFormFlag-}
Define a bandeira de envio do botão de envio.

### setSubmitFlag {#setSubmitFlag-com.aspose.pdf.facades.SubmitFormFlag-}
Defina as bandeiras de envio do botão de envio

### setSubmitUrl {#setSubmitUrl-java.lang.String-java.lang.String-}
Define a URL do botão.

### single2Multiple {#single2Multiple-java.lang.String-}
Altera um campo de texto de linha única para um de múltiplas linhas.
