---
title: "IFormEditor"
linktitle: "IFormEditor"
second_title: "Referência da API Aspose.PDF para Java"
description: "Classe para editar formulários (adicionar/excluir campos etc.)"
type: docs
weight: 260
url: /pt/java/com.aspose.pdf.facades/iformeditor/
---
```
public interface IFormEditor extends Closeable
```

Classe para editar formulários (adicionar/excluir campos etc.)

## Métodos

| Método | Descrição |
| --- | --- |
| [addField](#addField-com.aspose.pdf.facades.FieldType-java.lang.String-int-float-float-float-float-) | Adicionar campo do tipo especificado ao formulário. |
| [addField](#addField-com.aspose.pdf.facades.FieldType-java.lang.String-java.lang.String-int-float-float-float-float-) | Adicionar campo do tipo especificado ao formulário. |
| [addListItem](#addListItem-java.lang.String-java.lang.String-) | Adiciona um novo item à caixa de lista. |
| [addListItem](#addListItem-java.lang.String-java.lang.String:A-) | Adiciona um novo item com valor Export ao campo de caixa de lista existente, apenas para o campo de caixa de combinação AcroForm. |
| [addSubmitBtn](#addSubmitBtn-java.lang.String-int-java.lang.String-java.lang.String-float-float-float-float-) | Adiciona botão de envio no formulário. |
| [close](#close--) | Fecha o objeto |
| [copyInnerField](#copyInnerField-java.lang.String-java.lang.String-int-) | Copia um campo existente para a mesma posição no número de página especificado. |
| [copyInnerField](#copyInnerField-java.lang.String-java.lang.String-int-float-float-) | Copia um campo existente para uma nova posição especificada tanto pelo número da página quanto pelas coordenadas. |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-) | Copia um campo existente de um documento PDF para outro documento com o número de página original e coordenadas. |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-int-) | Copia um campo existente de um documento PDF para outro documento com o número de página especificado e coordenadas originais. |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-int-float-float-) | Copia um campo existente de um documento PDF para outro documento com o número de página e coordenadas especificados. |
| [decorateField](#decorateField--) | Altera os atributos visuais de todos os campos no documento PDF. |
| [decorateField](#decorateField-com.aspose.pdf.facades.FieldType-) | Altera os atributos visuais de todos os campos com o tipo de campo especificado. |
| [decorateField](#decorateField-java.lang.String-) | Altera os atributos visuais do campo especificado. |
| [delListItem](#delListItem-java.lang.String-java.lang.String-) | Exclui item do campo de lista. |
| [dispose](#dispose--) | Fecha o objeto |
| [getAttachmentName](#getAttachmentName--) | Obtém o nome do anexo quando o resultado da operação é armazenado em objetos HttpResponse como anexo. |
| [getContentDisposition](#getContentDisposition--) | Obtém como o conteúdo será armazenado quando o resultado da operação for armazenado no objeto HttpResponse. |
| [getDestFileName](#getDestFileName--) | Obtém o nome do arquivo de destino. |
| [getDestStream](#getDestStream--) | Obtém o fluxo de destino. |
| [getDocument](#getDocument--) | Obtém o documento em que o FormEditor está trabalhando. |
| [getExportItems](#getExportItems--) | Obtém opções para caixa de combinação com valores de exportação. |
| [getFacade](#getFacade--) | Obtém os atributos visuais do campo. |
| [getItems](#getItems--) | Retorna array de itens |
| [getRadioButtonItemSize](#getRadioButtonItemSize--) | Obtém ou define o tamanho do item do botão de opção (quando um novo campo de botão de opção é adicionado). |
| [getRadioGap](#getRadioGap--) | Obter o membro que registra o espaço entre dois botões de rádio vizinhos em pixels, o padrão é 50. |
| [getRadioHoriz](#getRadioHoriz--) | Obtém a bandeira que indica se os botões de opção estão dispostos horizontalmente ou verticalmente, o valor padrão é verdadeiro. |
| [getSaveOptions](#getSaveOptions--) | Obtém as opções de salvamento quando o resultado é armazenado como HttpResponse. |
| [getSrcFileName](#getSrcFileName--) | Obtém o nome do arquivo de origem. |
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
| [setDestFileName](#setDestFileName-java.lang.String-) | Define o nome do arquivo de destino. |
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
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Define as opções de salvamento quando o resultado é armazenado como HttpResponse. |
| [setSrcFileName](#setSrcFileName-java.lang.String-) | Define o nome do arquivo de origem. |
| [setSrcStream](#setSrcStream-java.io.InputStream-) | Define o fluxo de origem. |
| [setSubmitFlag](#setSubmitFlag-java.lang.String-com.aspose.pdf.facades.SubmitFormFlag-) | Define a bandeira de envio do botão de envio. |
| [setSubmitFlag](#setSubmitFlag-com.aspose.pdf.facades.SubmitFormFlag-) | Defina as bandeiras de envio do botão de envio |
| [setSubmitUrl](#setSubmitUrl-java.lang.String-java.lang.String-) | Define a URL do botão. |
| [single2Multiple](#single2Multiple-java.lang.String-) | Altera um campo de texto de linha única para um de múltiplas linhas. |

### addField {#addField-com.aspose.pdf.facades.FieldType-java.lang.String-int-float-float-float-float-}
Adicionar campo do tipo especificado ao formulário.

### addField {#addField-com.aspose.pdf.facades.FieldType-java.lang.String-java.lang.String-int-float-float-float-float-}
Adicionar campo do tipo especificado ao formulário.

### addListItem {#addListItem-java.lang.String-java.lang.String-}
Adiciona um novo item à caixa de lista.

### addListItem {#addListItem-java.lang.String-java.lang.String:A-}
Adiciona um novo item com valor Export ao campo de caixa de lista existente, apenas para o campo de caixa de combinação AcroForm.

### addSubmitBtn {#addSubmitBtn-java.lang.String-int-java.lang.String-java.lang.String-float-float-float-float-}
Adiciona botão de envio no formulário.

### close {#close--}
```
void close()
```

Fecha o objeto

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
void decorateField()
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
void dispose()
```

Fecha o objeto

### getAttachmentName {#getAttachmentName--}
```
String getAttachmentName()
```

Obtém o nome do anexo quando o resultado da operação é armazenado em objetos HttpResponse como anexo.

**Returns:**
Objeto String

### getContentDisposition {#getContentDisposition--}
```
ContentDisposition getContentDisposition()
```

Obtém como o conteúdo será armazenado quando o resultado da operação for armazenado no objeto HttpResponse.

**Returns:**
Elemento ContentDisposition

### getDestFileName {#getDestFileName--}
```
String getDestFileName()
```

Obtém o nome do arquivo de destino.

**Returns:**
valor de string

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

Obtém o documento em que o FormEditor está trabalhando.

**Returns:**
objeto IDocument

### getExportItems {#getExportItems--}
```
String [][] getExportItems()
```

Obtém opções para caixa de combinação com valores de exportação.

**Returns:**
Objeto String[][]

### getFacade {#getFacade--}
```
FormFieldFacade getFacade()
```

Obtém os atributos visuais do campo.

**Returns:**
Objeto FormFieldFacade

### getItems {#getItems--}
```
String [] getItems()
```

Retorna array de itens

**Returns:**
Objeto String[]

### getRadioButtonItemSize {#getRadioButtonItemSize--}
```
double getRadioButtonItemSize()
```

Obtém ou define o tamanho do item do botão de opção (quando um novo campo de botão de opção é adicionado).

**Returns:**
valor booleano

### getRadioGap {#getRadioGap--}
```
float getRadioGap()
```

Obter o membro que registra o espaço entre dois botões de rádio vizinhos em pixels, o padrão é 50.

**Returns:**
valor float

### getRadioHoriz {#getRadioHoriz--}
```
boolean getRadioHoriz()
```

Obtém a bandeira que indica se os botões de opção estão dispostos horizontalmente ou verticalmente, o valor padrão é verdadeiro.

**Returns:**
valor booleano

### getSaveOptions {#getSaveOptions--}
```
SaveOptions getSaveOptions()
```

Obtém as opções de salvamento quando o resultado é armazenado como HttpResponse.

**Returns:**
Objeto SaveOptions

### getSrcFileName {#getSrcFileName--}
```
String getSrcFileName()
```

Obtém o nome do arquivo de origem.

**Returns:**
valor de string

### getSrcStream {#getSrcStream--}
```
InputStream getSrcStream()
```

Obtém o fluxo de origem.

**Returns:**
objeto InputStream

### getSubmitFlag {#getSubmitFlag--}
```
SubmitFormFlag getSubmitFlag()
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
void resetFacade()
```

Redefine todos os atributos visuais para valor vazio.

### resetInnerFacade {#resetInnerFacade--}
```
void resetInnerFacade()
```

Redefine todos os atributos visuais da fachada interna para valor vazio.

### save {#save--}
```
void save()
```

Salva as alterações no arquivo de destino.

### setAttachmentName {#setAttachmentName-java.lang.String-}
Define o nome do anexo quando o resultado da operação é armazenado em objetos HttpResponse como anexo.

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
Define como o conteúdo será armazenado quando o resultado da operação for armazenado no objeto HttpResponse.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Define o formato de arquivo PDF PdfFormat.

### setDestFileName {#setDestFileName-java.lang.String-}
Define o nome do arquivo de destino.

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
void setRadioButtonItemSize(double value)
```

Obtém ou define o tamanho do item do botão de opção (quando um novo campo de botão de opção é adicionado).

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### setRadioGap {#setRadioGap-float-}
```
void setRadioGap(float value)
```

Define o membro para registrar o espaço entre dois botões de opção vizinhos em pixels, o padrão é 50.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor float |

### setRadioHoriz {#setRadioHoriz-boolean-}
```
void setRadioHoriz(boolean value)
```

Define a bandeira que indica se os botões de opção estão dispostos horizontalmente ou verticalmente, o valor padrão é verdadeiro.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Define as opções de salvamento quando o resultado é armazenado como HttpResponse.

### setSrcFileName {#setSrcFileName-java.lang.String-}
Define o nome do arquivo de origem.

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
