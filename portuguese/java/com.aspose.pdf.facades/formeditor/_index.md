---
title: "FormEditor"
linktitle: "FormEditor"
second_title: "Referência da API Aspose.PDF para Java"
description: "Classe para editar formulários (adicionar/excluir campos etc.)"
type: docs
weight: 200
url: /pt/java/com.aspose.pdf.facades/formeditor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.FormEditor, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.FormEditor, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.FormEditor

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, IFormEditor, ISaveableFacade, Closeable, AutoCloseable

```
public final class FormEditor extends SaveableFacade implements IFormEditor
```

Classe para editar formulários (adicionar/excluir campos etc.)

## Construtores

| Construtor | Descrição |
| --- | --- |
| [FormEditor](#FormEditor--) | <p> Construtor para FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre> |
| [FormEditor](#FormEditor-com.aspose.pdf.IDocument-) | <p> Construtor para FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre> |
| [FormEditor](#FormEditor-com.aspose.pdf.IDocument-java.io.OutputStream-) | <p> Construtor para FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre> |
| [FormEditor](#FormEditor-com.aspose.pdf.IDocument-java.lang.String-) | <p> Construtor para FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre> |
| [FormEditor](#FormEditor-java.io.InputStream-java.io.OutputStream-) | <p> Construtor para FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre> |
| [FormEditor](#FormEditor-java.lang.String-java.lang.String-) | <p> Construtor para FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre> |

## Métodos

| Método | Descrição |
| --- | --- |
| [addField](#addField-com.aspose.pdf.facades.FieldType-java.lang.String-int-float-float-float-float-) | <p> Adicionar campo do tipo especificado ao formulário. </p> <hr> <pre> FormEditor formEditor = new com.aspose.pdf.facades.FormEditor(\"PdfForm.pdf\", \"FormEditor_AddField_Text.pdf\"); formEditor.addField(FieldType.Text, \"AddedTextField\", 1, 10, 30, 110, 46); formEditor.save(); </pre> |
| [addField](#addField-com.aspose.pdf.facades.FieldType-java.lang.String-java.lang.String-int-float-float-float-float-) | Adicionar campo do tipo especificado ao formulário. |
| [addFieldScript](#addFieldScript-java.lang.String-java.lang.String-) | Adicionar JavaScript para um campo PushButton. |
| [addListItem](#addListItem-java.lang.String-java.lang.String-) | <p> Adiciona novo item à caixa de lista. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", PdfForm_out.pdf\"); formEditor.addListItem(\"listBoxField\", \"Item 4 (New Item)\"); </pre> |
| [addListItem](#addListItem-java.lang.String-java.lang.String:A-) | <p> Adicionar um novo item com valor Export ao campo de caixa de lista existente, apenas para campo combo box AcroForm. </p> <hr> <pre> FormEditor fe = new FormEditor(\"PdfForm.pdf\", \"FormEditor_AddListItem2.pdf\"); fe.addListItem(\"listboxField\", new String[] { \"4\", \"Item4(Added)\" }); </pre> |
| [addSubmitBtn](#addSubmitBtn-java.lang.String-int-java.lang.String-java.lang.String-float-float-float-float-) | <p> Adicionar botão de envio ao formulário. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_AddSubmitBtn.pdf\"); formEditor.addSubmitBtn(\"submit\", 1, \"Submit\", \"www.check.com\", 10, 200, 70, 270); </pre> |
| [close](#close--) | Fechar instância do objeto |
| [copyInnerField](#copyInnerField-java.lang.String-java.lang.String-int-) | Copia um campo existente para a mesma posição no número de página especificado. Um novo documento será gerado, contendo tudo o que o documento de origem possui, exceto o campo recém‑copiado. |
| [copyInnerField](#copyInnerField-java.lang.String-java.lang.String-int-float-float-) | Copia um campo existente para uma nova posição especificada tanto pelo número da página quanto pelas coordenadas. Um novo documento será gerado, contendo tudo o que o documento de origem possui, exceto o campo recém‑copiado. |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-) | Copia um campo existente de um documento PDF para outro documento com o número de página e coordenadas originais. Aviso: Apenas para campos AcroForm (excluindo caixa de rádio). |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-int-) | Copia um campo existente de um documento PDF para outro documento com o número de página especificado e coordenadas originais. Aviso: Apenas para campos AcroForm (excluindo caixa de rádio). |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-int-float-float-) | Copia um campo existente de um documento PDF para outro documento com o número de página e coordenadas especificados. Aviso: Apenas para campos AcroForm (excluindo caixa de rádio). |
| [decorateField](#decorateField--) | <p> Altera os atributos visuais de todos os campos no documento PDF. </p> <hr> <pre> FormEditor fe = new FormEditor(\"PdfForm.pdf\", \"FormEditor_DecorateField.pdf\"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.Green); fe.getFacade().setAlignment(FormFieldFacade.AlignRight); // decorate all fields. fe.decorateField(); </pre> |
| [decorateField](#decorateField-com.aspose.pdf.facades.FieldType-) | <p> Altera os atributos visuais de todos os campos no documento PDF. </p> <hr> <pre> FormEditor fe = new FormEditor(\"PdfForm.pdf\", \"FormEditor_DecorateField.pdf\"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.Green); fe.getFacade().setAlignment(FormFieldFacade.AlignRight); // decorate all fields. fe.decorateField(); </pre> |
| [decorateField](#decorateField-java.lang.String-) | <p> Altera os atributos visuais de todos os campos no documento PDF. </p> <hr> <pre> FormEditor fe = new FormEditor(\"PdfForm.pdf\", \"FormEditor_DecorateField.pdf\"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.Green); fe.getFacade().setAlignment(FormFieldFacade.AlignRight); // decorate all fields. fe.decorateField(); </pre> |
| [delListItem](#delListItem-java.lang.String-java.lang.String-) | <p> Excluir item do campo de lista. </p> <hr> <pre> formEditor = new com.aspose.pdf.facades.FormEditor(\"PdfForm.pdf\", \"FormEditor_DelListItem.pdf\"); formEditor.delListItem(\"listboxField\", \"item2\"); </pre> |
| [dispose](#dispose--) | Fechar instância do objeto. Este método está obsoleto, use close() em vez disso. |
| [getAttachmentName](#getAttachmentName--) | Obtém o nome do anexo quando o resultado da operação é armazenado em objetos HttpResponse como anexo. |
| [getContentDisposition](#getContentDisposition--) | Obtém como o conteúdo será armazenado quando o resultado da operação for armazenado em um objeto HttpResponse. Valor possível: inline / attachment. Padrão: inline. |
| [getDestFileName](#getDestFileName--) | Obtém o nome do arquivo de destino. |
| [getDestStream](#getDestStream--) | <p> Obtém o fluxo de destino. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setDestStream(new FileInputStream(\"OutFile.pdf\")); </pre> |
| [getDocument](#getDocument--) | Obtém o documento {@code FormEditor} em que está trabalhando. |
| [getExportItems](#getExportItems--) | <p> Obtém opções para caixa de combinação com valores de exportação. </p> <hr> |
| [getFacade](#getFacade--) | Obtém os atributos visuais do campo. |
| [getFieldAppearance](#getFieldAppearance-java.lang.String-) | Obter sinalizadores do campo. |
| [getItems](#getItems--) | Obter itens que serão adicionados à caixa de lista ou caixa de combinação recém-criada. |
| [getRadioButtonItemSize](#getRadioButtonItemSize--) | Obtém ou define o tamanho do item do botão de rádio (quando um novo campo de botão de rádio é adicionado). FormEditor formEditor = new com.aspose.pdf.facades.FormEditor(\"PdfForm.pdf\", \"FormEditor_AddField_RadioButton.pdf\"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setRadioButtonItemSize(20); formEditor.setItems(new String[] { \"First\", \"Second\", \"Third\" }); formEditor.addField(com.aspose.pdf.facades.FieldType.Radio, \"AddedRadioButtonField\", \"Second\", 1, 10, 30, 110, 130); formEditor.save(); |
| [getRadioGap](#getRadioGap--) | Obter o membro que registra o espaço entre dois botões de rádio vizinhos em pixels, o padrão é 50. |
| [getRadioHoriz](#getRadioHoriz--) | <p> Obter o sinalizador que indica se os botões de rádio são dispostos horizontalmente ou verticalmente, o valor padrão é true. |
| [getSaveOptions](#getSaveOptions--) | Obtém opções de salvamento quando o resultado é armazenado como HttpResponse. Valor padrão: PdfSaveOptions. |
| [getSrcFileName](#getSrcFileName--) | Obtém o nome do arquivo de origem. |
| [getSrcStream](#getSrcStream--) | Obtém o fluxo de origem. |
| [getSubmitFlag](#getSubmitFlag--) | Obter os sinalizadores de submissão do botão de envio. |
| [moveField](#moveField-java.lang.String-float-float-float-float-) | <p> Definir nova posição do campo. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_MoveField.pdf\"); formEditor.moveField(\"textField\", 20.5f, 20.3f, 120.6f, 40.8f); </pre> |
| [removeField](#removeField-java.lang.String-) | <p> Remover campo do formulário. </p> <hr> <pre> FormEditr formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_RemoveField.pdf\"); formEditor.removeField(\"listboxField\"); formEditor.removeField(\"textField\"); </pre> |
| [removeFieldAction](#removeFieldAction-java.lang.String-) | <p> Remover ação de envio do campo. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_RemoveFieldAction.pdf\"); formEditor.removeFieldAction(\"btnSubmit\"); </pre> |
| [renameField](#renameField-java.lang.String-java.lang.String-) | <p> Alterar o nome do campo. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"PdfForm_updated.pdf\"); formEditor.renameField(\"textField\", \"textField_Renamed\"); </pre> |
| [resetFacade](#resetFacade--) | Redefinir todos os atributos visuais para valor vazio. |
| [resetInnerFacade](#resetInnerFacade--) | Redefinir todos os atributos visuais da fachada interna para valor vazio. |
| [save](#save--) | Salva as alterações no arquivo de destino. |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | Define o nome do anexo quando o resultado da operação é armazenado em objetos HttpResponse como anexo. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | Define como o conteúdo será armazenado quando o resultado da operação for armazenado em um objeto HttpResponse. Valor possível: inline / attachment. Padrão: inline. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | Define o formato de arquivo PDF {@link PdfFormat}. O arquivo resultante será salvo no formato especificado. Se esta propriedade não for especificada, o arquivo será salvo no formato PDF padrão sem conversão. |
| [setDestFileName](#setDestFileName-java.lang.String-) | <p> Define o nome do arquivo de destino. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setDestFileName("OutFile.pdf"); </pre> |
| [setDestStream](#setDestStream-java.io.OutputStream-) | <p> Define o fluxo de destino. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setDestStream(new FileInputStream("OutFile.pdf")); </pre> |
| [setExportItems](#setExportItems-java.lang.String:A:A-) | <p> Define opções para a caixa de combinação com valores de exportação. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_Updated.pdf")); formEditor.setExportItems ( new String[][] { new String[] { "1", "Firs" }, new String[] { "2", "Second" }, new String[] { "3", "Third" } }); formEditor.addField(FieldType.ListBox, "AddedListBoxField", "Second", 1, 10, 30, 110, 130); formEditor.save(); </pre> |
| [setFacade](#setFacade-com.aspose.pdf.facades.FormFieldFacade-) | <p> Define atributos visuais do campo. </p> <hr> <pre> FormEditor fe = new FormEditor("PdfForm.pdf", "PdfForm_DecorateField_text.pdf"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.green); fe.getFacade().setAlignment(FormFieldFacade.AlignCenter); fe.setDecorateField("textField"); fe.save(); </pre> |
| [setFieldAlignment](#setFieldAlignment-java.lang.String-int-) | <p> Define o estilo de alinhamento de um campo de texto. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_updated.pdf")); formEditor.setFieldAlignment(fieldName, FormFieldFacade.AlignCenter); </pre> |
| [setFieldAlignmentV](#setFieldAlignmentV-java.lang.String-int-) | <p> Define o estilo de alinhamento vertical de um campo de texto. </p> <hr> <pre> FormEditor fe = new FormEditor("PdfStaticForm.pdf", "VerticalAlign.pdf"); fe.setFieldAlignmentV("form1[0].TextField[0]", FormFieldFacade.AlignBottom); </pre> |
| [setFieldAppearance](#setFieldAppearance-java.lang.String-int-) | <p> Set field flags </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm1.pdf", "FormEditor_SetFieldAppearance.pdf"); formEditor.setFieldAppearance("Name", AnnotationFlags.Hidden); formEditor.setFieldAppearance("Phone", AnnotationFlags.NoView \ | AnnotationFlags.Print); </pre> |
| [setFieldAttribute](#setFieldAttribute-java.lang.String-int-) | <p> Define atributos do campo. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_SetFieldAttribute.pdf"); formEditor.setFieldAttribute("listboxField", PropertyFlag.ReadOnly); formEditor.setFieldAttribute("textField", PropertyFlag.NoExport); </pre> |
| [setFieldCombNumber](#setFieldCombNumber-java.lang.String-int-) | <p> Define o número de combs para um campo de texto de linha única regular (o campo é dividido automaticamente em tantas posições igualmente espaçadas, ou combs, quanto o valor do parâmetro combNumber). </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfWithAcroForm.pdf", "FormEditor_SetFieldComb.pdf")); formEditor.setFieldCombNumber("textCombField", 5); </pre> |
| [setFieldLimit](#setFieldLimit-java.lang.String-int-) | <p> Define a contagem máxima de caracteres do campo de texto. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetFieldLimit.pdf"); formEditor.setFieldLimit("textField", 15); </pre> |
| [setFieldScript](#setFieldScript-java.lang.String-java.lang.String-) | Define JavaScript para um campo PushButton. Se houver JavaScript antigo, ele será substituído pelo novo. |
| [setItems](#setItems-java.lang.String:A-) | <p> Define itens que serão adicionados à caixa de lista ou caixa de combinação recém-criada. </p> <hr> <pre> formEditor = new com.aspose.pdf.facadesFormEditor("input.pdf", "output.pdf"); formEditor.setItems(new String[] { "AAA", "BBB", "CCC" }); formEditor.addField(FieldType.ListBox, "AddedListBoxField", "BBB", 1, 10, 30, 110, 130); formEditor.save(); </pre> |
| [setRadioButtonItemSize](#setRadioButtonItemSize-double-) | Obtém ou define o tamanho do item do botão de rádio (quando um novo campo de botão de rádio é adicionado). FormEditor formEditor = new com.aspose.pdf.facades.FormEditor(\"PdfForm.pdf\", \"FormEditor_AddField_RadioButton.pdf\"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setRadioButtonItemSize(20); formEditor.setItems(new String[] { \"First\", \"Second\", \"Third\" }); formEditor.addField(com.aspose.pdf.facades.FieldType.Radio, \"AddedRadioButtonField\", \"Second\", 1, 10, 30, 110, 130); formEditor.save(); |
| [setRadioGap](#setRadioGap-float-) | <p> Define o membro que registra o espaço entre dois botões de opção vizinhos em pixels, padrão é 50. </p> <hr> <pre> formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setItems(new String[] { "First", "Second", "Third" }); formEditor.addField(FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130); formEditor.save(); </pre> |
| [setRadioHoriz](#setRadioHoriz-boolean-) | <p> Defina a bandeira para indicar se os botões de opção são dispostos horizontalmente ou verticalmente, o valor padrão é true. </p> <hr> <pre> formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setItems(new String[] { "First", "Second", "Third" }); formEditor.addField(FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130); formEditor.save(); </pre> |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Defina as opções de salvamento quando o resultado é armazenado como HttpResponse. Valor padrão: PdfSaveOptions. |
| [setSrcFileName](#setSrcFileName-java.lang.String-) | <p> Defina o nome do arquivo de origem. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setSrcFileName("InputFile.pdf"); </pre> |
| [setSrcStream](#setSrcStream-java.io.InputStream-) | <p> Defina o fluxo de origem. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setSrcStream(new FileInputStream("InFile.pdf")); </pre> |
| [setSubmitFlag](#setSubmitFlag-java.lang.String-com.aspose.pdf.facades.SubmitFormFlag-) | <p> Defina a bandeira de envio do botão de envio. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetSubmitFlag.pdf"); formEditor.setSubmitFlag("btnSubmit", SubmitFormFlag.Fdf); </pre> |
| [setSubmitFlag](#setSubmitFlag-com.aspose.pdf.facades.SubmitFormFlag-) | Defina as bandeiras de envio do botão de envio |
| [setSubmitUrl](#setSubmitUrl-java.lang.String-java.lang.String-) | <p> Defina a URL do botão. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetSubmitUrl.pdf"); formEditor.setSubmitUrl("btnSubmit", "www.mysite.com"); </pre> |
| [single2Multiple](#single2Multiple-java.lang.String-) | <p> Altere um campo de texto de linha única para um de múltiplas linhas. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf"); formEditor.single2Multiple("textField"); </pre> |

### FormEditor {#FormEditor--}
```
public FormEditor()
```

<p> Construtor para FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre>

### FormEditor {#FormEditor-com.aspose.pdf.IDocument-}
<p> Construtor para FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre>

### FormEditor {#FormEditor-com.aspose.pdf.IDocument-java.io.OutputStream-}
<p> Construtor para FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre>

### FormEditor {#FormEditor-com.aspose.pdf.IDocument-java.lang.String-}
<p> Construtor para FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre>

### FormEditor {#FormEditor-java.io.InputStream-java.io.OutputStream-}
<p> Construtor para FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre>

### FormEditor {#FormEditor-java.lang.String-java.lang.String-}
<p> Construtor para FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre>

### addField {#addField-com.aspose.pdf.facades.FieldType-java.lang.String-int-float-float-float-float-}
<p> Adicionar campo do tipo especificado ao formulário. </p> <hr> <pre> FormEditor formEditor = new com.aspose.pdf.facades.FormEditor(\"PdfForm.pdf\", \"FormEditor_AddField_Text.pdf\"); formEditor.addField(FieldType.Text, \"AddedTextField\", 1, 10, 30, 110, 46); formEditor.save(); </pre>

### addField {#addField-com.aspose.pdf.facades.FieldType-java.lang.String-java.lang.String-int-float-float-float-float-}
Adicionar campo do tipo especificado ao formulário.

### addFieldScript {#addFieldScript-java.lang.String-java.lang.String-}
Adicionar JavaScript para um campo PushButton.

### addListItem {#addListItem-java.lang.String-java.lang.String-}
<p> Adiciona novo item à caixa de lista. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", PdfForm_out.pdf\"); formEditor.addListItem(\"listBoxField\", \"Item 4 (New Item)\"); </pre>

### addListItem {#addListItem-java.lang.String-java.lang.String:A-}
<p> Adicionar um novo item com valor Export ao campo de caixa de lista existente, apenas para campo combo box AcroForm. </p> <hr> <pre> FormEditor fe = new FormEditor(\"PdfForm.pdf\", \"FormEditor_AddListItem2.pdf\"); fe.addListItem(\"listboxField\", new String[] { \"4\", \"Item4(Added)\" }); </pre>

### addSubmitBtn {#addSubmitBtn-java.lang.String-int-java.lang.String-java.lang.String-float-float-float-float-}
<p> Adicionar botão de envio ao formulário. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_AddSubmitBtn.pdf\"); formEditor.addSubmitBtn(\"submit\", 1, \"Submit\", \"www.check.com\", 10, 200, 70, 270); </pre>

### close {#close--}
```
public void close()
```

Fechar instância do objeto

### copyInnerField {#copyInnerField-java.lang.String-java.lang.String-int-}
Copia um campo existente para a mesma posição no número de página especificado. Um novo documento será gerado, contendo tudo o que o documento de origem possui, exceto o campo recém‑copiado.

### copyInnerField {#copyInnerField-java.lang.String-java.lang.String-int-float-float-}
Copia um campo existente para uma nova posição especificada tanto pelo número da página quanto pelas coordenadas. Um novo documento será gerado, contendo tudo o que o documento de origem possui, exceto o campo recém‑copiado.

### copyOuterField {#copyOuterField-java.lang.String-java.lang.String-}
Copia um campo existente de um documento PDF para outro documento com o número de página e coordenadas originais. Aviso: Apenas para campos AcroForm (excluindo caixa de rádio).

### copyOuterField {#copyOuterField-java.lang.String-java.lang.String-int-}
Copia um campo existente de um documento PDF para outro documento com o número de página especificado e coordenadas originais. Aviso: Apenas para campos AcroForm (excluindo caixa de rádio).

### copyOuterField {#copyOuterField-java.lang.String-java.lang.String-int-float-float-}
Copia um campo existente de um documento PDF para outro documento com o número de página e coordenadas especificados. Aviso: Apenas para campos AcroForm (excluindo caixa de rádio).

### decorateField {#decorateField--}
```
public void decorateField()
```

<p> Altera os atributos visuais de todos os campos no documento PDF. </p> <hr> <pre> FormEditor fe = new FormEditor(\"PdfForm.pdf\", \"FormEditor_DecorateField.pdf\"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.Green); fe.getFacade().setAlignment(FormFieldFacade.AlignRight); // decorate all fields. fe.decorateField(); </pre>

### decorateField {#decorateField-com.aspose.pdf.facades.FieldType-}
<p> Altera os atributos visuais de todos os campos no documento PDF. </p> <hr> <pre> FormEditor fe = new FormEditor(\"PdfForm.pdf\", \"FormEditor_DecorateField.pdf\"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.Green); fe.getFacade().setAlignment(FormFieldFacade.AlignRight); // decorate all fields. fe.decorateField(); </pre>

### decorateField {#decorateField-java.lang.String-}
<p> Altera os atributos visuais de todos os campos no documento PDF. </p> <hr> <pre> FormEditor fe = new FormEditor(\"PdfForm.pdf\", \"FormEditor_DecorateField.pdf\"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.Green); fe.getFacade().setAlignment(FormFieldFacade.AlignRight); // decorate all fields. fe.decorateField(); </pre>

### delListItem {#delListItem-java.lang.String-java.lang.String-}
<p> Excluir item do campo de lista. </p> <hr> <pre> formEditor = new com.aspose.pdf.facades.FormEditor(\"PdfForm.pdf\", \"FormEditor_DelListItem.pdf\"); formEditor.delListItem(\"listboxField\", \"item2\"); </pre>

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Fechar instância do objeto. Este método está obsoleto, use close() em vez disso.

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

Obtém como o conteúdo será armazenado quando o resultado da operação for armazenado em um objeto HttpResponse. Valor possível: inline / attachment. Padrão: inline.

**Returns:**
Elemento ContentDisposition @see ContentDisposition

### getDestFileName {#getDestFileName--}
```
public String getDestFileName()
```

Obtém o nome do arquivo de destino.

**Returns:**
objeto string

### getDestStream {#getDestStream--}
```
public OutputStream getDestStream()
```

<p> Obtém o fluxo de destino. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setDestStream(new FileInputStream(\"OutFile.pdf\")); </pre>

**Returns:**
objeto OutputStream

### getDocument {#getDocument--}
```
public IDocument getDocument()
```

Obtém o documento {@code FormEditor} em que está trabalhando.

**Returns:**
objeto IDocument

### getExportItems {#getExportItems--}
```
public String [][] getExportItems()
```

<p> Obtém opções para caixa de combinação com valores de exportação. </p> <hr>

**Returns:**
Objeto String[][]

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

Obter itens que serão adicionados à caixa de lista ou caixa de combinação recém-criada.

**Returns:**
Objeto String[]

### getRadioButtonItemSize {#getRadioButtonItemSize--}
```
public double getRadioButtonItemSize()
```

Obtém ou define o tamanho do item do botão de rádio (quando um novo campo de botão de rádio é adicionado). FormEditor formEditor = new com.aspose.pdf.facades.FormEditor(\"PdfForm.pdf\", \"FormEditor_AddField_RadioButton.pdf\"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setRadioButtonItemSize(20); formEditor.setItems(new String[] { \"First\", \"Second\", \"Third\" }); formEditor.addField(com.aspose.pdf.facades.FieldType.Radio, \"AddedRadioButtonField\", \"Second\", 1, 10, 30, 110, 130); formEditor.save();

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

<p> Obter o sinalizador que indica se os botões de rádio são dispostos horizontalmente ou verticalmente, o valor padrão é true.

**Returns:**
valor booleano

### getSaveOptions {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```

Obtém opções de salvamento quando o resultado é armazenado como HttpResponse. Valor padrão: PdfSaveOptions.

**Returns:**
Objeto SaveOptions

### getSrcFileName {#getSrcFileName--}
```
public String getSrcFileName()
```

Obtém o nome do arquivo de origem.

**Returns:**
objeto string

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
Elemento SubmitFormFlag @see SubmitFormFlag

### moveField {#moveField-java.lang.String-float-float-float-float-}
<p> Definir nova posição do campo. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_MoveField.pdf\"); formEditor.moveField(\"textField\", 20.5f, 20.3f, 120.6f, 40.8f); </pre>

### removeField {#removeField-java.lang.String-}
<p> Remover campo do formulário. </p> <hr> <pre> FormEditr formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_RemoveField.pdf\"); formEditor.removeField(\"listboxField\"); formEditor.removeField(\"textField\"); </pre>

### removeFieldAction {#removeFieldAction-java.lang.String-}
<p> Remover ação de envio do campo. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_RemoveFieldAction.pdf\"); formEditor.removeFieldAction(\"btnSubmit\"); </pre>

### renameField {#renameField-java.lang.String-java.lang.String-}
<p> Alterar o nome do campo. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"PdfForm_updated.pdf\"); formEditor.renameField(\"textField\", \"textField_Renamed\"); </pre>

### resetFacade {#resetFacade--}
```
public void resetFacade()
```

Redefinir todos os atributos visuais para valor vazio.

### resetInnerFacade {#resetInnerFacade--}
```
public void resetInnerFacade()
```

Redefinir todos os atributos visuais da fachada interna para valor vazio.

### save {#save--}
```
@Deprecated public void save()
```

Salva as alterações no arquivo de destino.

### setAttachmentName {#setAttachmentName-java.lang.String-}
Define o nome do anexo quando o resultado da operação é armazenado em objetos HttpResponse como anexo.

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
Define como o conteúdo será armazenado quando o resultado da operação for armazenado em um objeto HttpResponse. Valor possível: inline / attachment. Padrão: inline.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Define o formato de arquivo PDF {@link PdfFormat}. O arquivo resultante será salvo no formato especificado. Se esta propriedade não for especificada, o arquivo será salvo no formato PDF padrão sem conversão.

### setDestFileName {#setDestFileName-java.lang.String-}
<p> Define o nome do arquivo de destino. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setDestFileName("OutFile.pdf"); </pre>

### setDestStream {#setDestStream-java.io.OutputStream-}
<p> Define o fluxo de destino. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setDestStream(new FileInputStream("OutFile.pdf")); </pre>

### setExportItems {#setExportItems-java.lang.String:A:A-}
<p> Define opções para a caixa de combinação com valores de exportação. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_Updated.pdf")); formEditor.setExportItems ( new String[][] { new String[] { "1", "Firs" }, new String[] { "2", "Second" }, new String[] { "3", "Third" } }); formEditor.addField(FieldType.ListBox, "AddedListBoxField", "Second", 1, 10, 30, 110, 130); formEditor.save(); </pre>

### setFacade {#setFacade-com.aspose.pdf.facades.FormFieldFacade-}
<p> Define atributos visuais do campo. </p> <hr> <pre> FormEditor fe = new FormEditor("PdfForm.pdf", "PdfForm_DecorateField_text.pdf"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.green); fe.getFacade().setAlignment(FormFieldFacade.AlignCenter); fe.setDecorateField("textField"); fe.save(); </pre>

### setFieldAlignment {#setFieldAlignment-java.lang.String-int-}
<p> Define o estilo de alinhamento de um campo de texto. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_updated.pdf")); formEditor.setFieldAlignment(fieldName, FormFieldFacade.AlignCenter); </pre>

### setFieldAlignmentV {#setFieldAlignmentV-java.lang.String-int-}
<p> Define o estilo de alinhamento vertical de um campo de texto. </p> <hr> <pre> FormEditor fe = new FormEditor("PdfStaticForm.pdf", "VerticalAlign.pdf"); fe.setFieldAlignmentV("form1[0].TextField[0]", FormFieldFacade.AlignBottom); </pre>

### setFieldAppearance {#setFieldAppearance-java.lang.String-int-}
<p> Defina as bandeiras do campo </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm1.pdf", "FormEditor_SetFieldAppearance.pdf"); formEditor.setFieldAppearance("Name", AnnotationFlags.Hidden); formEditor.setFieldAppearance("Phone", AnnotationFlags.NoView | AnnotationFlags.Print); </pre>

### setFieldAttribute {#setFieldAttribute-java.lang.String-int-}
<p> Define atributos do campo. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_SetFieldAttribute.pdf"); formEditor.setFieldAttribute("listboxField", PropertyFlag.ReadOnly); formEditor.setFieldAttribute("textField", PropertyFlag.NoExport); </pre>

### setFieldCombNumber {#setFieldCombNumber-java.lang.String-int-}
<p> Define o número de combs para um campo de texto de linha única regular (o campo é dividido automaticamente em tantas posições igualmente espaçadas, ou combs, quanto o valor do parâmetro combNumber). </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfWithAcroForm.pdf", "FormEditor_SetFieldComb.pdf")); formEditor.setFieldCombNumber("textCombField", 5); </pre>

### setFieldLimit {#setFieldLimit-java.lang.String-int-}
<p> Define a contagem máxima de caracteres do campo de texto. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetFieldLimit.pdf"); formEditor.setFieldLimit("textField", 15); </pre>

### setFieldScript {#setFieldScript-java.lang.String-java.lang.String-}
Define JavaScript para um campo PushButton. Se houver JavaScript antigo, ele será substituído pelo novo.

### setItems {#setItems-java.lang.String:A-}
<p> Define itens que serão adicionados à caixa de lista ou caixa de combinação recém-criada. </p> <hr> <pre> formEditor = new com.aspose.pdf.facadesFormEditor("input.pdf", "output.pdf"); formEditor.setItems(new String[] { "AAA", "BBB", "CCC" }); formEditor.addField(FieldType.ListBox, "AddedListBoxField", "BBB", 1, 10, 30, 110, 130); formEditor.save(); </pre>

### setRadioButtonItemSize {#setRadioButtonItemSize-double-}
```
public void setRadioButtonItemSize(double value)
```

Obtém ou define o tamanho do item do botão de rádio (quando um novo campo de botão de rádio é adicionado). FormEditor formEditor = new com.aspose.pdf.facades.FormEditor(\"PdfForm.pdf\", \"FormEditor_AddField_RadioButton.pdf\"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setRadioButtonItemSize(20); formEditor.setItems(new String[] { \"First\", \"Second\", \"Third\" }); formEditor.addField(com.aspose.pdf.facades.FieldType.Radio, \"AddedRadioButtonField\", \"Second\", 1, 10, 30, 110, 130); formEditor.save();

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### setRadioGap {#setRadioGap-float-}
```
public void setRadioGap(float value)
```

<p> Define o membro que registra o espaço entre dois botões de opção vizinhos em pixels, padrão é 50. </p> <hr> <pre> formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setItems(new String[] { "First", "Second", "Third" }); formEditor.addField(FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130); formEditor.save(); </pre>

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor float |

### setRadioHoriz {#setRadioHoriz-boolean-}
```
public void setRadioHoriz(boolean value)
```

<p> Defina a bandeira para indicar se os botões de opção são dispostos horizontalmente ou verticalmente, o valor padrão é true. </p> <hr> <pre> formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setItems(new String[] { "First", "Second", "Third" }); formEditor.addField(FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130); formEditor.save(); </pre>

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Defina as opções de salvamento quando o resultado é armazenado como HttpResponse. Valor padrão: PdfSaveOptions.

### setSrcFileName {#setSrcFileName-java.lang.String-}
<p> Defina o nome do arquivo de origem. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setSrcFileName("InputFile.pdf"); </pre>

### setSrcStream {#setSrcStream-java.io.InputStream-}
<p> Defina o fluxo de origem. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setSrcStream(new FileInputStream("InFile.pdf")); </pre>

### setSubmitFlag {#setSubmitFlag-java.lang.String-com.aspose.pdf.facades.SubmitFormFlag-}
<p> Defina a bandeira de envio do botão de envio. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetSubmitFlag.pdf"); formEditor.setSubmitFlag("btnSubmit", SubmitFormFlag.Fdf); </pre>

### setSubmitFlag {#setSubmitFlag-com.aspose.pdf.facades.SubmitFormFlag-}
Defina as bandeiras de envio do botão de envio

### setSubmitUrl {#setSubmitUrl-java.lang.String-java.lang.String-}
<p> Defina a URL do botão. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetSubmitUrl.pdf"); formEditor.setSubmitUrl("btnSubmit", "www.mysite.com"); </pre>

### single2Multiple {#single2Multiple-java.lang.String-}
<p> Altere um campo de texto de linha única para um de múltiplas linhas. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf"); formEditor.single2Multiple("textField"); </pre>
