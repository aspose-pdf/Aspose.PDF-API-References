---
title: "Formulário"
linktitle: "Formulário"
second_title: "Referência da API Aspose.PDF para Java"
description: "Classe que representa o objeto de formulário Acro."
type: docs
weight: 170
url: /pt/java/com.aspose.pdf.facades/form/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.Form, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.Form, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.Form

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, IForm, ISaveableFacade, Closeable, AutoCloseable

```
public final class Form extends SaveableFacade
```

Classe que representa o objeto de formulário Acro.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [Form](#Form--) | <p> Construtor de Form sem parâmetros. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-com.aspose.pdf.IDocument-) | <p> Construtor de Form sem parâmetros. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-com.aspose.pdf.IDocument-java.io.OutputStream-) | <p> Construtor de Form sem parâmetros. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-com.aspose.pdf.IDocument-java.lang.String-) | <p> Construtor de Form sem parâmetros. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-java.io.InputStream-) | <p> Construtor de Form sem parâmetros. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-java.io.InputStream-java.io.OutputStream-) | <p> Construtor de Form sem parâmetros. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-java.io.InputStream-java.lang.String-) | <p> Construtor de Form sem parâmetros. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-java.lang.String-) | <p> Construtor de Form sem parâmetros. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-java.lang.String-java.io.OutputStream-) | <p> Construtor de Form sem parâmetros. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-java.lang.String-java.lang.String-) | <p> Construtor de Form sem parâmetros. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |

## Métodos

| Método | Descrição |
| --- | --- |
| [bindPdf](#bindPdf-java.io.InputStream-java.lang.String-) | Inicializa a fachada. |
| [bindPdf](#bindPdf-java.lang.String-java.lang.String-) | Inicializa a fachada. |
| [close](#close--) | Fecha arquivos abertos sem quaisquer alterações. |
| [dispose](#dispose--) | Fecha todos os recursos abertos. Este método está obsoleto, use close() em vez disso. |
| [exportFdf](#exportFdf-java.io.OutputStream-) | <p> Exporta o conteúdo dos campos do pdf para o fluxo fdf. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); OutputStream stream = new FileOutputStream(\"export.fdf\"); form.exportFdf(stream); stream.close(); </pre> |
| [exportXfdf](#exportXfdf-java.io.OutputStream-) | <p> Exporta o conteúdo dos campos do pdf para o fluxo xml. O valor do campo de botão não será exportado. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); FileInputStream fs = new FileInputStream(\"export.xfdf\", FileMode.Create, FileAccess.Write); form.exportXfdf(fs); fs.close(); </pre> |
| [exportXml](#exportXml-java.io.OutputStream-) | <p> Exporta o conteúdo dos campos do pdf para o fluxo xml. O valor do campo de botão não será exportado. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\")); OutputStream fs = new FileOutputStream(\"export.xml\"); form.exportXml(fs); fs.close(); </pre> |
| [extractXfaData](#extractXfaData-java.io.OutputStream-) | Extrai o pacote de dados XFA |
| [fillBarcodeField](#fillBarcodeField-java.lang.String-java.lang.String-) | <p> Preenche um campo de código de barras de acordo com seu nome de campo totalmente qualificado. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); form.fillBarcodeField(\"textField\", \"42207252\"); </pre> |
| [fillField](#fillField-java.lang.String-boolean-) | <p> Preenche o campo de caixa de seleção com um valor booleano. Aviso: Aplicável apenas a Check Box. Observe que Facades suporta apenas nomes de campo completos e não funciona com nomes de campo parciais, ao contrário do Aspose.Pdf.Kit; Por exemplo, se o campo tem o nome completo \"Form.Subform.CheckBoxField\" você deve especificar o nome completo e não \"CheckBoxField\". Você pode usar a propriedade FieldNames para explorar os nomes de campo existentes e buscar o campo necessário pelo seu nome parcial. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); form.fillField(\"checkboxField\", true); //how to search field by its partial name: Form form = new Form(\"input.pdf\", \"output.pdf\"); for(String fieldName : form.getFieldNames()) { if (fieldName.endsWith(\"CheckBoxField\")) { System.out.println(\"Full name is: \" + fieldName); } } </pre> |
| [fillField](#fillField-java.lang.String-int-) | <p> Preenche o campo de caixa de rádio com um valor de índice válido de acordo com um nome de campo totalmente qualificado. Antes de preencher os campos, apenas o nome do campo deve ser conhecido. Enquanto o valor pode ser especificado pelo seu índice. Aviso: Aplicável apenas a campos Radio Box, Combo Box e List Box. Observe que Facades suporta apenas nomes de campo completos e não funciona com nomes de campo parciais, ao contrário do Aspose.Pdf.Kit; Por exemplo, se o campo tem o nome completo \"Form.Subform.ListBoxField\" você deve especificar o nome completo e não \"ListBoxField\". Você pode usar a propriedade FieldNames para explorar os nomes de campo existentes e buscar o campo necessário pelo seu nome parcial. </p> <hr> <pre> //1 Form form = new Form(\"PdfForm.pdf\"); form.fillField(\"listboxField\", 2); form.fillField(\"comboboxField\", 2); form.fillField(\"radiobuttonField\", 2); //2 //how to search field by its partial name: Form form = new Form(\"input.pdf\", \"output.pdf\"); for(String fieldName : form.getFieldNames()) { if (fieldName.endsWith(\"ListBoxField\")) { System.out.println(\"Full name is: \" + fieldName); } } </pre> |
| [fillField](#fillField-java.lang.String-java.lang.String-) | <p> Preenche o campo com um valor válido de acordo com um nome de campo totalmente qualificado. Antes de preencher os campos, os nomes de todos os campos e seus respectivos valores válidos devem ser conhecidos. Tanto o nome dos campos quanto os valores diferenciam maiúsculas de minúsculas. Observe que Facades suporta apenas nomes de campo completos e não funciona com nomes de campo parciais, ao contrário do Aspose.Pdf.Kit; Por exemplo, se o campo tem o nome completo \"Form.Subform.TextField\" você deve especificar o nome completo e não \"TextField\". Você pode usar a propriedade FieldNames para explorar os nomes de campo existentes e buscar o campo necessário pelo seu nome parcial. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); form.fillField(\"FirstName\", \"John\"); form.fillField(\"LastName\", \"Smith\"); //how to search field by its partial name: Form form = new Form(\"input.pdf\", \"output.pdf\"); for(String fieldName : form.getFieldNames()) { if (fieldName.endsWith(\"TextField\")) { System.out.println(\"Full name is: \" + fieldName); } } </pre> |
| [fillField](#fillField-java.lang.String-java.lang.String:A-) | <p> Preencha um campo com múltiplas seleções. Nota: apenas para campo List Box do AcroForm. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(\"PdfForm.pdf\", \"Form_Updated.pdf\"); form.fillField(\"ListBox1\", new String[] { \"Three\", \"One\" }); form.save(); </pre> |
| [fillField](#fillField-java.lang.String-java.lang.String-boolean-) | Preenche o campo com o valor especificado. |
| [fillFields](#fillFields-java.lang.String:A-java.lang.String:A-java.io.OutputStream-) | Preenche os campos de caixa de texto com valores de texto e salva o documento. |
| [fillImageField](#fillImageField-java.lang.String-java.io.InputStream-) | <p> Sobrecarga da função FillImageField. A entrada é um fluxo de imagem. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_filled.pdf\"); form.fillImageField(\"fieldName\", new FileInputStream(\"file.jpg\", FileMode.Open, FileAccess.Read)); </pre> |
| [fillImageField](#fillImageField-java.lang.String-java.lang.String-) | <p> Cola uma imagem no campo de botão existente como sua aparência de acordo com o nome de campo totalmente qualificado. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_filled.pdf\"); form.fillImageField(\"fieldName\", \"file.jpg\"); form.save(); </pre> |
| [flattenAllFields](#flattenAllFields--) | <p> Achata todos os campos. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); form.flattenAllFields(); </pre> |
| [flattenField](#flattenField-java.lang.String-) | <p> Achata um campo especificado com o nome de campo totalmente qualificado. Qualquer outro campo permanecerá inalterado. Se o fieldName for inválido, todos os campos permanecerão inalterados. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); form.flattenField(\"textField\"); </pre> |
| [getAttachmentName](#getAttachmentName--) | Obtém o nome do anexo quando o resultado da operação é armazenado em objetos HttpResponse como anexo. |
| [getButtonOptionCurrentValue](#getButtonOptionCurrentValue-java.lang.String-) | <p> Retorna o valor atual para campos de opção de botão de rádio. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); System.out.println(form.GetButtonOptionCurrentValue(\"btnField\")); </pre> |
| [getButtonOptionValues](#getButtonOptionValues-java.lang.String-) | <p> Obtém os campos de opção de botão de rádio e os valores relacionados com base no nome do campo. Este método tem significado para grupos de botões de rádio. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); java.util.Map values = form.getButtonOptionValues(\"Color\"); System.out.println(values.get(\"White\").toString()); System.out.println(values.get(\"Black\").toString()); </pre> |
| [getButtonOptionValuesInternal](#getButtonOptionValuesInternal-java.lang.String-) | <p> Obtém os campos de opções de botão de rádio e os valores relacionados com base no nome do campo. Este método tem significado para grupos de botões de rádio. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); Hashtable values = form.getButtonOptionValues("Color"); System.out.println(values["White"].toString()); System.out.println(values["Black"].toString()); </pre> |
| [getContentDisposition](#getContentDisposition--) | Obtém ou define como o conteúdo será armazenado quando o resultado da operação for armazenado no objeto HttpResponse. Valor possível: inline / attachment. Padrão: inline. |
| [getDestFileName](#getDestFileName--) | Obtém o nome do arquivo de destino. |
| [getDestStream](#getDestStream--) | Obtém ou define o fluxo de destino. |
| [getField](#getField-java.lang.String-) | <p> Obtém o valor do campo de acordo com o nome do campo. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println("Field value = " + form.getField("Field1")); </pre> |
| [getFieldFacade](#getFieldFacade-java.lang.String-) | <p> Retorna o objeto FormFieldFacade contendo todos os atributos de aparência. </p> <hr> <pre> com.aspose.pdf.facades.Form form = new com.aspose.pdf.facades.Form("form.pdf")); FormFieldFacade field = form.getFieldFacade("field1"); System.out.println("Color of field border: " + field.getBorderColor()); </pre> |
| [getFieldFlag](#getFieldFlag-java.lang.String-) | <p> Retorna as flags do campo. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); if (form.getFieldFlag("textField") == ProptyFlag.ReadOnly) { System.out.println("Field is read-only"); } </pre> |
| [getFieldLimit](#getFieldLimit-java.lang.String-) | <p> Obtém a limitação do campo de texto. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println(form.getFieldLimit("textfieldBox")); </pre> |
| [getFieldNames](#getFieldNames--) | <p> Obtém a lista de nomes de campos no formulário. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); String[] fields = form.getFieldNames(); for(String field : fields) { System.out.println(field); } </pre> |
| [getFieldType](#getFieldType-java.lang.String-) | <p> Retorna o tipo do campo. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); if (form.getFieldType("textField") == FieldType.Text) { System.out.println("Type of field is text"); } </pre> |
| [getFormSubmitButtonNames](#getFormSubmitButtonNames--) | <p> Obtém todos os nomes dos botões de envio do formulário. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); String[] submits = form.getFormSubmitButtonNames(); for(String btn : submits) { System.out.println(btn); } </pre> |
| [getFullFieldName](#getFullFieldName-java.lang.String-) | <p> Obtém o nome completo do campo de acordo com seu nome curto. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println("Full field name is : " + form.getFullFieldName("textField")); </pre> |
| [getImportResult](#getImportResult--) | Resultado da última operação de importação. Array de objetos que descrevem o resultado da importação para cada campo. |
| [getRichText](#getRichText-java.lang.String-) | <p> Obtém o valor de um campo Rich Text, incluindo as informações de formatação de cada caractere. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println(form.getRichText("txtDescriptionRTF")); </pre> |
| [getSaveOptions](#getSaveOptions--) | Obtém ou define as opções de salvamento quando o resultado é armazenado como HttpResponse. Valor padrão: PdfSaveOptions. |
| [getSrcFileName](#getSrcFileName--) | <p> Obtém o nome do arquivo de origem. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setSrcFileName("file.pdf"); </pre> |
| [getSrcStream](#getSrcStream--) | Obtém o fluxo de origem. |
| [getSubmitFlags](#getSubmitFlags-java.lang.String-) | <p> Returns the submit button's submission flags </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println( ( form.getSubmitFlags("btnSubmit") \ | SubmitFormFlag.Xfdf != 0) ? " XFDF" : " "); /// System.out.println( ( form.getSubmitFlags("btnSubmit") \ | SubmitFormFlag.Fdf != 0) ? " FDF" : " "); System.out.println( ( form.getSubmitFlags("btnSubmit") \ | SubmitFormFlag.Pdf != 0) ? " PDF" : " "); </pre> |
| [importFdf](#importFdf-java.io.InputStream-) | <p> Importa o conteúdo dos campos do arquivo fdf e os coloca no novo pdf. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_imported.pdf"); form.importFdf(new FileInputStream("data.fdf")); form.save(); </pre> |
| [importXfdf](#importXfdf-java.io.InputStream-) | <p> Importa o conteúdo dos campos do arquivo xfdf(xml) e os coloca no novo pdf. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "Form_ImportXfdf.pdf"); InputStream fs = new FileInputStream("export_old.xfdf"); form.importXfdf(fs); fs.close(); form.save(); </pre> |
| [importXml](#importXml-java.io.InputStream-) | <p> Importa o conteúdo dos campos do arquivo xml e os coloca no novo pdf. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); InputStream fs = new FileInputStream("import.xml"); form.importXml(fs); form.save("Form_Imported.pdf"); </pre> |
| [importXml](#importXml-java.io.InputStream-boolean-) | Importa o conteúdo dos campos do arquivo xml e os coloca no novo pdf. |
| [importXml](#importXml-java.lang.String-) | <p> Importa o conteúdo dos campos do arquivo xml e os coloca no novo pdf. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); form.importXml("import.xml"); form.save( "Form_Imported.pdf"); </pre> |
| [isRequiredField](#isRequiredField-java.lang.String-) | Determina se o campo é obrigatório ou não. |
| [renameField](#renameField-java.lang.String-java.lang.String-) | <p> Renomeia um campo. Tanto o campo AcroForm quanto o campo XFA são aceitos. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfFormUpdated.pdf\"); form.renameField(\"field\", \"field1\"); form.save(); </pre> |
| [save](#save--) | <p> Salva o valor dos campos preenchidos e fecha o documento Pdf aberto. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_Changed.pdf\"); form.fillField(\"textField\", \"new value\"); form.save(); </pre> |
| [save](#save-java.io.OutputStream-) | <p> Salva o valor dos campos preenchidos e fecha o documento Pdf aberto. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_Changed.pdf\"); form.fillField(\"textField\", \"new value\"); form.save(); </pre> |
| [save](#save-java.lang.String-) | <p> Salva o valor dos campos preenchidos e fecha o documento Pdf aberto. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_Changed.pdf\"); form.fillField(\"textField\", \"new value\"); form.save(); </pre> |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | Define o nome do anexo quando o resultado da operação é armazenado em objetos HttpResponse como anexo. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | Define como o conteúdo será armazenado quando o resultado da operação for armazenado em um objeto HttpResponse. Valor possível: inline / attachment. Padrão: inline. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | Define o formato do arquivo PDF. O arquivo resultante será salvo no formato de arquivo especificado. Se esta propriedade não for especificada, o arquivo será salvo no formato PDF padrão sem conversão. |
| [setDestFileName](#setDestFileName-java.lang.String-) | <p> Define o nome do arquivo de destino. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setDestFileName(\"file.pdf\"); </pre> |
| [setDestStream](#setDestStream-java.io.OutputStream-) | <p> Obtém o fluxo de destino. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setDestStream (new FileInputStream(\"file.pdf\")); </pre> |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Obtém ou define as opções de salvamento quando o resultado é armazenado como HttpResponse. Valor padrão: PdfSaveOptions. |
| [setSrcFileName](#setSrcFileName-java.lang.String-) | Define o nome do arquivo de origem. |
| [setSrcStream](#setSrcStream-java.io.InputStream-) | <p> Obtém o fluxo de origem. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setSrcStream (new FileInputStream(\"source.pdf\"))); </pre> |
| [setXfaData](#setXfaData-java.io.InputStream-) | Substitui os dados XFA pelo pacote de dados especificado. O pacote de dados pode ser extraído usando ExtractXfaData. |

### Form {#Form--}
```
public Form()
```

<p> Construtor de Form sem parâmetros. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-com.aspose.pdf.IDocument-}
<p> Construtor de Form sem parâmetros. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-com.aspose.pdf.IDocument-java.io.OutputStream-}
<p> Construtor de Form sem parâmetros. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-com.aspose.pdf.IDocument-java.lang.String-}
<p> Construtor de Form sem parâmetros. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-java.io.InputStream-}
<p> Construtor de Form sem parâmetros. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-java.io.InputStream-java.io.OutputStream-}
<p> Construtor de Form sem parâmetros. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-java.io.InputStream-java.lang.String-}
<p> Construtor de Form sem parâmetros. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-java.lang.String-}
<p> Construtor de Form sem parâmetros. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-java.lang.String-java.io.OutputStream-}
<p> Construtor de Form sem parâmetros. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-java.lang.String-java.lang.String-}
<p> Construtor de Form sem parâmetros. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### bindPdf {#bindPdf-java.io.InputStream-java.lang.String-}
Inicializa a fachada.

### bindPdf {#bindPdf-java.lang.String-java.lang.String-}
Inicializa a fachada.

### close {#close--}
```
public void close()
```

Fecha arquivos abertos sem quaisquer alterações.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Fecha todos os recursos abertos. Este método está obsoleto, use close() em vez disso.

### exportFdf {#exportFdf-java.io.OutputStream-}
<p> Exporta o conteúdo dos campos do pdf para o fluxo fdf. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); OutputStream stream = new FileOutputStream(\"export.fdf\"); form.exportFdf(stream); stream.close(); </pre>

### exportXfdf {#exportXfdf-java.io.OutputStream-}
<p> Exporta o conteúdo dos campos do pdf para o fluxo xml. O valor do campo de botão não será exportado. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); FileInputStream fs = new FileInputStream(\"export.xfdf\", FileMode.Create, FileAccess.Write); form.exportXfdf(fs); fs.close(); </pre>

### exportXml {#exportXml-java.io.OutputStream-}
<p> Exporta o conteúdo dos campos do pdf para o fluxo xml. O valor do campo de botão não será exportado. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\")); OutputStream fs = new FileOutputStream(\"export.xml\"); form.exportXml(fs); fs.close(); </pre>

### extractXfaData {#extractXfaData-java.io.OutputStream-}
Extrai o pacote de dados XFA

### fillBarcodeField {#fillBarcodeField-java.lang.String-java.lang.String-}
<p> Preenche um campo de código de barras de acordo com seu nome de campo totalmente qualificado. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); form.fillBarcodeField(\"textField\", \"42207252\"); </pre>

### fillField {#fillField-java.lang.String-boolean-}
<p> Preenche o campo de caixa de seleção com um valor booleano. Aviso: Aplicável apenas a Check Box. Observe que Facades suporta apenas nomes de campo completos e não funciona com nomes de campo parciais, ao contrário do Aspose.Pdf.Kit; Por exemplo, se o campo tem o nome completo \"Form.Subform.CheckBoxField\" você deve especificar o nome completo e não \"CheckBoxField\". Você pode usar a propriedade FieldNames para explorar os nomes de campo existentes e buscar o campo necessário pelo seu nome parcial. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); form.fillField(\"checkboxField\", true); //how to search field by its partial name: Form form = new Form(\"input.pdf\", \"output.pdf\"); for(String fieldName : form.getFieldNames()) { if (fieldName.endsWith(\"CheckBoxField\")) { System.out.println(\"Full name is: \" + fieldName); } } </pre>

### fillField {#fillField-java.lang.String-int-}
<p> Preenche o campo de caixa de rádio com um valor de índice válido de acordo com um nome de campo totalmente qualificado. Antes de preencher os campos, apenas o nome do campo deve ser conhecido. Enquanto o valor pode ser especificado pelo seu índice. Aviso: Aplicável apenas a campos Radio Box, Combo Box e List Box. Observe que Facades suporta apenas nomes de campo completos e não funciona com nomes de campo parciais, ao contrário do Aspose.Pdf.Kit; Por exemplo, se o campo tem o nome completo \"Form.Subform.ListBoxField\" você deve especificar o nome completo e não \"ListBoxField\". Você pode usar a propriedade FieldNames para explorar os nomes de campo existentes e buscar o campo necessário pelo seu nome parcial. </p> <hr> <pre> //1 Form form = new Form(\"PdfForm.pdf\"); form.fillField(\"listboxField\", 2); form.fillField(\"comboboxField\", 2); form.fillField(\"radiobuttonField\", 2); //2 //how to search field by its partial name: Form form = new Form(\"input.pdf\", \"output.pdf\"); for(String fieldName : form.getFieldNames()) { if (fieldName.endsWith(\"ListBoxField\")) { System.out.println(\"Full name is: \" + fieldName); } } </pre>

### fillField {#fillField-java.lang.String-java.lang.String-}
<p> Preenche o campo com um valor válido de acordo com um nome de campo totalmente qualificado. Antes de preencher os campos, os nomes de todos os campos e seus respectivos valores válidos devem ser conhecidos. Tanto o nome dos campos quanto os valores diferenciam maiúsculas de minúsculas. Observe que Facades suporta apenas nomes de campo completos e não funciona com nomes de campo parciais, ao contrário do Aspose.Pdf.Kit; Por exemplo, se o campo tem o nome completo \"Form.Subform.TextField\" você deve especificar o nome completo e não \"TextField\". Você pode usar a propriedade FieldNames para explorar os nomes de campo existentes e buscar o campo necessário pelo seu nome parcial. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); form.fillField(\"FirstName\", \"John\"); form.fillField(\"LastName\", \"Smith\"); //how to search field by its partial name: Form form = new Form(\"input.pdf\", \"output.pdf\"); for(String fieldName : form.getFieldNames()) { if (fieldName.endsWith(\"TextField\")) { System.out.println(\"Full name is: \" + fieldName); } } </pre>

### fillField {#fillField-java.lang.String-java.lang.String:A-}
<p> Preencha um campo com múltiplas seleções. Nota: apenas para campo List Box do AcroForm. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(\"PdfForm.pdf\", \"Form_Updated.pdf\"); form.fillField(\"ListBox1\", new String[] { \"Three\", \"One\" }); form.save(); </pre>

### fillField {#fillField-java.lang.String-java.lang.String-boolean-}
Preenche o campo com o valor especificado.

### fillFields {#fillFields-java.lang.String:A-java.lang.String:A-java.io.OutputStream-}
Preenche os campos de caixa de texto com valores de texto e salva o documento.

### fillImageField {#fillImageField-java.lang.String-java.io.InputStream-}
<p> Sobrecarga da função FillImageField. A entrada é um fluxo de imagem. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_filled.pdf\"); form.fillImageField(\"fieldName\", new FileInputStream(\"file.jpg\", FileMode.Open, FileAccess.Read)); </pre>

### fillImageField {#fillImageField-java.lang.String-java.lang.String-}
<p> Cola uma imagem no campo de botão existente como sua aparência de acordo com o nome de campo totalmente qualificado. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_filled.pdf\"); form.fillImageField(\"fieldName\", \"file.jpg\"); form.save(); </pre>

### flattenAllFields {#flattenAllFields--}
```
public void flattenAllFields()
```

<p> Achata todos os campos. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); form.flattenAllFields(); </pre>

### flattenField {#flattenField-java.lang.String-}
<p> Achata um campo especificado com o nome de campo totalmente qualificado. Qualquer outro campo permanecerá inalterado. Se o fieldName for inválido, todos os campos permanecerão inalterados. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); form.flattenField(\"textField\"); </pre>

### getAttachmentName {#getAttachmentName--}
```
public String getAttachmentName()
```

Obtém o nome do anexo quando o resultado da operação é armazenado em objetos HttpResponse como anexo.

**Returns:**
objeto string

### getButtonOptionCurrentValue {#getButtonOptionCurrentValue-java.lang.String-}
<p> Retorna o valor atual para campos de opção de botão de rádio. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); System.out.println(form.GetButtonOptionCurrentValue(\"btnField\")); </pre>

### getButtonOptionValues {#getButtonOptionValues-java.lang.String-}
<p> Obtém os campos de opção de botão de rádio e os valores relacionados com base no nome do campo. Este método tem significado para grupos de botões de rádio. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); java.util.Map values = form.getButtonOptionValues(\"Color\"); System.out.println(values.get(\"White\").toString()); System.out.println(values.get(\"Black\").toString()); </pre>

### getButtonOptionValuesInternal {#getButtonOptionValuesInternal-java.lang.String-}
<p> Obtém os campos de opções de botão de rádio e os valores relacionados com base no nome do campo. Este método tem significado para grupos de botões de rádio. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); Hashtable values = form.getButtonOptionValues("Color"); System.out.println(values["White"].toString()); System.out.println(values["Black"].toString()); </pre>

### getContentDisposition {#getContentDisposition--}
```
public ContentDisposition getContentDisposition()
```

Obtém ou define como o conteúdo será armazenado quando o resultado da operação for armazenado no objeto HttpResponse. Valor possível: inline / attachment. Padrão: inline.

**Returns:**
Elemento ContentDisposition @see ContentDisposition

### getDestFileName {#getDestFileName--}
```
@Deprecated public String getDestFileName()
```

Obtém o nome do arquivo de destino.

**Returns:**
objeto string

### getDestStream {#getDestStream--}
```
@Deprecated public OutputStream getDestStream()
```

Obtém ou define o fluxo de destino.

**Returns:**
objeto OutputStream

### getField {#getField-java.lang.String-}
<p> Obtém o valor do campo de acordo com o nome do campo. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println("Field value = " + form.getField("Field1")); </pre>

### getFieldFacade {#getFieldFacade-java.lang.String-}
<p> Retorna o objeto FormFieldFacade contendo todos os atributos de aparência. </p> <hr> <pre> com.aspose.pdf.facades.Form form = new com.aspose.pdf.facades.Form("form.pdf")); FormFieldFacade field = form.getFieldFacade("field1"); System.out.println("Color of field border: " + field.getBorderColor()); </pre>

### getFieldFlag {#getFieldFlag-java.lang.String-}
<p> Retorna as flags do campo. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); if (form.getFieldFlag("textField") == ProptyFlag.ReadOnly) { System.out.println("Field is read-only"); } </pre>

### getFieldLimit {#getFieldLimit-java.lang.String-}
<p> Obtém a limitação do campo de texto. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println(form.getFieldLimit("textfieldBox")); </pre>

### getFieldNames {#getFieldNames--}
```
public String [] getFieldNames()
```

<p> Obtém a lista de nomes de campos no formulário. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); String[] fields = form.getFieldNames(); for(String field : fields) { System.out.println(field); } </pre>

**Returns:**
Objeto String[]

### getFieldType {#getFieldType-java.lang.String-}
<p> Retorna o tipo do campo. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); if (form.getFieldType("textField") == FieldType.Text) { System.out.println("Type of field is text"); } </pre>

### getFormSubmitButtonNames {#getFormSubmitButtonNames--}
```
public String [] getFormSubmitButtonNames()
```

<p> Obtém todos os nomes dos botões de envio do formulário. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); String[] submits = form.getFormSubmitButtonNames(); for(String btn : submits) { System.out.println(btn); } </pre>

**Returns:**
Objeto String[]

### getFullFieldName {#getFullFieldName-java.lang.String-}
<p> Obtém o nome completo do campo de acordo com seu nome curto. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println("Full field name is : " + form.getFullFieldName("textField")); </pre>

### getImportResult {#getImportResult--}
```
public com.aspose.pdf.facades.AForm.FormImportResult[] getImportResult()
```

Resultado da última operação de importação. Array de objetos que descrevem o resultado da importação para cada campo.

**Returns:**
FormImportResult[] array

### getRichText {#getRichText-java.lang.String-}
<p> Obtém o valor de um campo Rich Text, incluindo as informações de formatação de cada caractere. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println(form.getRichText("txtDescriptionRTF")); </pre>

### getSaveOptions {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```

Obtém ou define as opções de salvamento quando o resultado é armazenado como HttpResponse. Valor padrão: PdfSaveOptions.

**Returns:**
Objeto SaveOptions

### getSrcFileName {#getSrcFileName--}
```
@Deprecated public String getSrcFileName()
```

<p> Obtém o nome do arquivo de origem. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setSrcFileName("file.pdf"); </pre>

**Returns:**
objeto string

### getSrcStream {#getSrcStream--}
```
public InputStream getSrcStream()
```

Obtém o fluxo de origem.

**Returns:**
objeto InputStream

### getSubmitFlags {#getSubmitFlags-java.lang.String-}
<p> Retorna os sinalizadores de envio do botão de submissão </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); System.out.println( ( form.getSubmitFlags(\"btnSubmit\") | SubmitFormFlag.Xfdf != 0) ? \" XFDF\" : \" \" ); /// System.out.println( ( form.getSubmitFlags(\"btnSubmit\") | SubmitFormFlag.Fdf != 0) ? \" FDF\" : \" \" ); System.out.println( ( form.getSubmitFlags(\"btnSubmit\") | SubmitFormFlag.Pdf != 0) ? \" PDF\" : \" \" ); </pre>

### importFdf {#importFdf-java.io.InputStream-}
<p> Importa o conteúdo dos campos do arquivo fdf e os coloca no novo pdf. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_imported.pdf"); form.importFdf(new FileInputStream("data.fdf")); form.save(); </pre>

### importXfdf {#importXfdf-java.io.InputStream-}
<p> Importa o conteúdo dos campos do arquivo xfdf(xml) e os coloca no novo pdf. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "Form_ImportXfdf.pdf"); InputStream fs = new FileInputStream("export_old.xfdf"); form.importXfdf(fs); fs.close(); form.save(); </pre>

### importXml {#importXml-java.io.InputStream-}
<p> Importa o conteúdo dos campos do arquivo xml e os coloca no novo pdf. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); InputStream fs = new FileInputStream("import.xml"); form.importXml(fs); form.save("Form_Imported.pdf"); </pre>

### importXml {#importXml-java.io.InputStream-boolean-}
Importa o conteúdo dos campos do arquivo xml e os coloca no novo pdf.

### importXml {#importXml-java.lang.String-}
<p> Importa o conteúdo dos campos do arquivo xml e os coloca no novo pdf. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); form.importXml("import.xml"); form.save( "Form_Imported.pdf"); </pre>

### isRequiredField {#isRequiredField-java.lang.String-}
Determina se o campo é obrigatório ou não.

### renameField {#renameField-java.lang.String-java.lang.String-}
<p> Renomeia um campo. Tanto o campo AcroForm quanto o campo XFA são aceitos. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfFormUpdated.pdf\"); form.renameField(\"field\", \"field1\"); form.save(); </pre>

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
Define como o conteúdo será armazenado quando o resultado da operação for armazenado em um objeto HttpResponse. Valor possível: inline / attachment. Padrão: inline.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Define o formato do arquivo PDF. O arquivo resultante será salvo no formato de arquivo especificado. Se esta propriedade não for especificada, o arquivo será salvo no formato PDF padrão sem conversão.

### setDestFileName {#setDestFileName-java.lang.String-}
<p> Define o nome do arquivo de destino. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setDestFileName(\"file.pdf\"); </pre>

### setDestStream {#setDestStream-java.io.OutputStream-}
<p> Obtém o fluxo de destino. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setDestStream (new FileInputStream(\"file.pdf\")); </pre>

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Obtém ou define as opções de salvamento quando o resultado é armazenado como HttpResponse. Valor padrão: PdfSaveOptions.

### setSrcFileName {#setSrcFileName-java.lang.String-}
Define o nome do arquivo de origem.

### setSrcStream {#setSrcStream-java.io.InputStream-}
<p> Obtém o fluxo de origem. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setSrcStream (new FileInputStream(\"source.pdf\"))); </pre>

### setXfaData {#setXfaData-java.io.InputStream-}
Substitui os dados XFA pelo pacote de dados especificado. O pacote de dados pode ser extraído usando ExtractXfaData.
