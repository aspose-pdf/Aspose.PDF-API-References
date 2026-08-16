---
title: "Formulario"
linktitle: "Formulario"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase que representa un objeto de formulario Acro."
type: docs
weight: 170
url: /es/java/com.aspose.pdf.facades/form/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.Form, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.Form, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.Form

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, IForm, ISaveableFacade, Closeable, AutoCloseable

```
public final class Form extends SaveableFacade
```

Clase que representa un objeto de formulario Acro.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [Form](#Form--) | <p> Constructor de Form sin parámetros. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-com.aspose.pdf.IDocument-) | <p> Constructor de Form sin parámetros. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-com.aspose.pdf.IDocument-java.io.OutputStream-) | <p> Constructor de Form sin parámetros. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-com.aspose.pdf.IDocument-java.lang.String-) | <p> Constructor de Form sin parámetros. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-java.io.InputStream-) | <p> Constructor de Form sin parámetros. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-java.io.InputStream-java.io.OutputStream-) | <p> Constructor de Form sin parámetros. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-java.io.InputStream-java.lang.String-) | <p> Constructor de Form sin parámetros. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-java.lang.String-) | <p> Constructor de Form sin parámetros. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-java.lang.String-java.io.OutputStream-) | <p> Constructor de Form sin parámetros. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-java.lang.String-java.lang.String-) | <p> Constructor de Form sin parámetros. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |

## Métodos

| Método | Descripción |
| --- | --- |
| [bindPdf](#bindPdf-java.io.InputStream-java.lang.String-) | Inicializa la fachada. |
| [bindPdf](#bindPdf-java.lang.String-java.lang.String-) | Inicializa la fachada. |
| [close](#close--) | Cierra los archivos abiertos sin realizar cambios. |
| [dispose](#dispose--) | Cierra todos los recursos abiertos. Este método está obsoleto, use close() en su lugar. |
| [exportFdf](#exportFdf-java.io.OutputStream-) | <p> Exporta el contenido de los campos del pdf al flujo fdf. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); OutputStream stream = new FileOutputStream(\"export.fdf\"); form.exportFdf(stream); stream.close(); </pre> |
| [exportXfdf](#exportXfdf-java.io.OutputStream-) | <p> Exporta el contenido de los campos del pdf al flujo xml. El valor del campo de botón no se exportará. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); FileInputStream fs = new FileInputStream(\"export.xfdf\", FileMode.Create, FileAccess.Write); form.exportXfdf(fs); fs.close(); </pre> |
| [exportXml](#exportXml-java.io.OutputStream-) | <p> Exporta el contenido de los campos del pdf al flujo xml. El valor del campo de botón no se exportará. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\")); OutputStream fs = new FileOutputStream(\"export.xml\"); form.exportXml(fs); fs.close(); </pre> |
| [extractXfaData](#extractXfaData-java.io.OutputStream-) | Extrae el paquete de datos XFA |
| [fillBarcodeField](#fillBarcodeField-java.lang.String-java.lang.String-) | <p> Rellena un campo de código de barras según su nombre de campo totalmente calificado. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); form.fillBarcodeField(\"textField\", \"42207252\"); </pre> |
| [fillField](#fillField-java.lang.String-boolean-) | <p> Rellena el campo de casilla de verificación con un valor booleano. Aviso: Solo se aplica a Check Box. Tenga en cuenta que Facades admite solo nombres de campo completos y no funciona con nombres de campo parciales, a diferencia de Aspose.Pdf.Kit; por ejemplo, si el campo tiene el nombre completo \"Form.Subform.CheckBoxField\" debe especificar el nombre completo y no \"CheckBoxField\". Puede usar la propiedad FieldNames para explorar los nombres de campo existentes y buscar el campo requerido por su nombre parcial. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); form.fillField(\"checkboxField\", true); //how to search field by its partial name: Form form = new Form(\"input.pdf\", \"output.pdf\"); for(String fieldName : form.getFieldNames()) { if (fieldName.endsWith(\"CheckBoxField\")) { System.out.println(\"Full name is: \" + fieldName); } } </pre> |
| [fillField](#fillField-java.lang.String-int-) | <p> Rellena el campo de caja de radio con un valor de índice válido según un nombre de campo totalmente calificado. Antes de rellenar los campos, solo se debe conocer el nombre del campo. Mientras el valor puede especificarse por su índice. Aviso: Solo se aplica a campos de Caja de Radio, Caja Combinada y Caja de Lista. Tenga en cuenta que Facades admite solo nombres de campo completos y no funciona con nombres de campo parciales, a diferencia de Aspose.Pdf.Kit; Por ejemplo, si el campo tiene el nombre completo \"Form.Subform.ListBoxField\" debe especificar el nombre completo y no \"ListBoxField\". Puede usar la propiedad FieldNames para explorar los nombres de campo existentes y buscar el campo requerido por su nombre parcial. </p> <hr> <pre> //1 Form form = new Form("PdfForm.pdf"); form.fillField("listboxField", 2); form.fillField("comboboxField", 2); form.fillField("radiobuttonField", 2); //2 //how to search field by its partial name: Form form = new Form("input.pdf", "output.pdf"); for(String fieldName : form.getFieldNames()) { if (fieldName.endsWith("ListBoxField")) { System.out.println("Full name is: " + fieldName); } } </pre> |
| [fillField](#fillField-java.lang.String-java.lang.String-) | <p> Rellena el campo con un valor válido según un nombre de campo totalmente calificado. Antes de rellenar los campos, se deben conocer los nombres de todos los campos y sus valores válidos correspondientes. Tanto el nombre del campo como los valores distinguen entre mayúsculas y minúsculas. Tenga en cuenta que Facades admite solo nombres de campo completos y no funciona con nombres de campo parciales, a diferencia de Aspose.Pdf.Kit; Por ejemplo, si el campo tiene el nombre completo \"Form.Subform.TextField\" debe especificar el nombre completo y no \"TextField\". Puede usar la propiedad FieldNames para explorar los nombres de campo existentes y buscar el campo requerido por su nombre parcial. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); form.fillField("FirstName", "John"); form.fillField("LastName", "Smith"); //how to search field by its partial name: Form form = new Form("input.pdf", "output.pdf"); for(String fieldName : form.getFieldNames()) { if (fieldName.endsWith("TextField")) { System.out.println("Full name is: " + fieldName); } } </pre> |
| [fillField](#fillField-java.lang.String-java.lang.String:A-) | <p> Rellena un campo con múltiples selecciones. Nota: solo para el campo de Caja de Lista AcroForm. </p> <hr> <pre> Form form = new com.aspose.pdf.Form("PdfForm.pdf", "Form_Updated.pdf"); form.fillField("ListBox1", new String[] { "Three", "One" }); form.save(); </pre> |
| [fillField](#fillField-java.lang.String-java.lang.String-boolean-) | Rellena el campo con el valor especificado. |
| [fillFields](#fillFields-java.lang.String:A-java.lang.String:A-java.io.OutputStream-) | Rellena los campos de cuadro de texto con valores de texto y guarda el documento. |
| [fillImageField](#fillImageField-java.lang.String-java.io.InputStream-) | <p> Sobrecarga de la función FillImageField. La entrada es un flujo de imagen. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_filled.pdf"); form.fillImageField("fieldName", new FileInputStream("file.jpg", FileMode.Open, FileAccess.Read)); </pre> |
| [fillImageField](#fillImageField-java.lang.String-java.lang.String-) | <p> Pega una imagen en el campo de botón existente como su apariencia según su nombre de campo totalmente calificado. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_filled.pdf"); form.fillImageField("fieldName", "file.jpg"); form.save(); </pre> |
| [flattenAllFields](#flattenAllFields--) | <p> Aplana todos los campos. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); form.flattenAllFields(); </pre> |
| [flattenField](#flattenField-java.lang.String-) | <p> Aplana un campo especificado con el nombre de campo totalmente calificado. Cualquier otro campo permanecerá inalterable. Si el fieldName es inválido, todos los campos permanecerán inalterables. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); form.flattenField("textField"); </pre> |
| [getAttachmentName](#getAttachmentName--) | Obtiene el nombre del adjunto cuando el resultado de la operación se almacena en objetos HttpResponse como adjunto. |
| [getButtonOptionCurrentValue](#getButtonOptionCurrentValue-java.lang.String-) | <p> Devuelve el valor actual para los campos de opción de botón de radio. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println(form.GetButtonOptionCurrentValue("btnField")); </pre> |
| [getButtonOptionValues](#getButtonOptionValues-java.lang.String-) | <p> Obtiene los campos de opción de botón de radio y los valores relacionados según el nombre del campo. Este método tiene sentido para grupos de botones de radio. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); java.util.Map values = form.getButtonOptionValues("Color"); System.out.println(values.get("White").toString()); System.out.println(values.get("Black").toString()); </pre> |
| [getButtonOptionValuesInternal](#getButtonOptionValuesInternal-java.lang.String-) | <p> Obtiene los campos de opciones de botones de radio y los valores relacionados según el nombre del campo. Este método tiene sentido para grupos de botones de radio. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); Hashtable values = form.getButtonOptionValues("Color"); System.out.println(values["White"].toString()); System.out.println(values["Black"].toString()); </pre> |
| [getContentDisposition](#getContentDisposition--) | Obtiene o establece cómo se almacenará el contenido cuando el resultado de la operación se almacene en un objeto HttpResponse. Valor posible: inline / attachment. Predeterminado: inline. |
| [getDestFileName](#getDestFileName--) | Obtiene el nombre del archivo de destino. |
| [getDestStream](#getDestStream--) | Obtiene o establece el flujo de destino. |
| [getField](#getField-java.lang.String-) | <p> Obtiene el valor del campo según su nombre. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println("Field value = " + form.getField("Field1")); </pre> |
| [getFieldFacade](#getFieldFacade-java.lang.String-) | <p> Devuelve un objeto FormFieldFacade que contiene todos los atributos de apariencia. </p> <hr> <pre> com.aspose.pdf.facades.Form form = new com.aspose.pdf.facades.Form("form.pdf")); FormFieldFacade field = form.getFieldFacade("field1"); System.out.println("Color of field border: " + field.getBorderColor()); </pre> |
| [getFieldFlag](#getFieldFlag-java.lang.String-) | <p> Devuelve los indicadores del campo. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); if (form.getFieldFlag("textField") == ProptyFlag.ReadOnly) { System.out.println("Field is read-only"); } </pre> |
| [getFieldLimit](#getFieldLimit-java.lang.String-) | <p> Obtiene la limitación del campo de texto. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println(form.getFieldLimit("textfieldBox")); </pre> |
| [getFieldNames](#getFieldNames--) | <p> Obtiene la lista de nombres de campos en el formulario. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); String[] fields = form.getFieldNames(); for(String field : fields) { System.out.println(field); } </pre> |
| [getFieldType](#getFieldType-java.lang.String-) | <p> Devuelve el tipo de campo. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); if (form.getFieldType("textField") == FieldType.Text) { System.out.println("Type of field is text"); } </pre> |
| [getFormSubmitButtonNames](#getFormSubmitButtonNames--) | <p> Obtiene todos los nombres de los botones de envío del formulario. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); String[] submits = form.getFormSubmitButtonNames(); for(String btn : submits) { System.out.println(btn); } </pre> |
| [getFullFieldName](#getFullFieldName-java.lang.String-) | <p> Obtiene el nombre completo del campo según su nombre corto. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println("Full field name is : " + form.getFullFieldName("textField")); </pre> |
| [getImportResult](#getImportResult--) | Resultado de la última operación de importación. Matriz de objetos que describen el resultado de la importación para cada campo. |
| [getRichText](#getRichText-java.lang.String-) | <p> Obtiene el valor de un campo de texto enriquecido, incluyendo la información de formato de cada carácter. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println(form.getRichText("txtDescriptionRTF")); </pre> |
| [getSaveOptions](#getSaveOptions--) | Obtiene o establece las opciones de guardado cuando el resultado se almacena como HttpResponse. Valor predeterminado: PdfSaveOptions. |
| [getSrcFileName](#getSrcFileName--) | <p> Obtiene el nombre del archivo fuente. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setSrcFileName("file.pdf"); </pre> |
| [getSrcStream](#getSrcStream--) | Obtiene el flujo de origen. |
| [getSubmitFlags](#getSubmitFlags-java.lang.String-) | <p> Returns the submit button's submission flags </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println( ( form.getSubmitFlags("btnSubmit") \ | SubmitFormFlag.Xfdf != 0) ? " XFDF" : " "); /// System.out.println( ( form.getSubmitFlags("btnSubmit") \ | SubmitFormFlag.Fdf != 0) ? " FDF" : " "); System.out.println( ( form.getSubmitFlags("btnSubmit") \ | SubmitFormFlag.Pdf != 0) ? " PDF" : " "); </pre> |
| [importFdf](#importFdf-java.io.InputStream-) | <p> Importa el contenido de los campos del archivo fdf y los coloca en el nuevo pdf. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_imported.pdf"); form.importFdf(new FileInputStream("data.fdf")); form.save(); </pre> |
| [importXfdf](#importXfdf-java.io.InputStream-) | <p> Importa el contenido de los campos del archivo xfdf(xml) y los coloca en el nuevo pdf. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "Form_ImportXfdf.pdf"); InputStream fs = new FileInputStream("export_old.xfdf"); form.importXfdf(fs); fs.close(); form.save(); </pre> |
| [importXml](#importXml-java.io.InputStream-) | <p> Importa el contenido de los campos del archivo xml y los coloca en el nuevo pdf. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); InputStream fs = new FileInputStream("import.xml"); form.importXml(fs); form.save("Form_Imported.pdf"); </pre> |
| [importXml](#importXml-java.io.InputStream-boolean-) | Importa el contenido de los campos del archivo xml y los coloca en el nuevo pdf. |
| [importXml](#importXml-java.lang.String-) | <p> Importa el contenido de los campos del archivo xml y los coloca en el nuevo pdf. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); form.importXml("import.xml"); form.save( "Form_Imported.pdf"); </pre> |
| [isRequiredField](#isRequiredField-java.lang.String-) | Determina si el campo es obligatorio o no. |
| [renameField](#renameField-java.lang.String-java.lang.String-) | <p> Renombra un campo. Ya sea un campo AcroForm o XFA está bien. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfFormUpdated.pdf\"); form.renameField(\"field\", \"field1\"); form.save(); </pre> |
| [save](#save--) | <p> Guarda el valor de los campos rellenados y cierra el documento PDF abierto. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_Changed.pdf\"); form.fillField(\"textField\", \"new value\"); form.save(); </pre> |
| [save](#save-java.io.OutputStream-) | <p> Guarda el valor de los campos rellenados y cierra el documento PDF abierto. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_Changed.pdf\"); form.fillField(\"textField\", \"new value\"); form.save(); </pre> |
| [save](#save-java.lang.String-) | <p> Guarda el valor de los campos rellenados y cierra el documento PDF abierto. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_Changed.pdf\"); form.fillField(\"textField\", \"new value\"); form.save(); </pre> |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | Establece el nombre del adjunto cuando el resultado de la operación se almacena en objetos HttpResponse como adjunto. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | Establece cómo se almacenará el contenido cuando el resultado de la operación se almacena en un objeto HttpResponse. Valor posible: inline / attachment. Predeterminado: inline. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | Establece el formato de archivo PDF. El archivo resultante se guardará en el formato de archivo especificado. Si esta propiedad no se especifica, el archivo se guardará en el formato PDF predeterminado sin conversión. |
| [setDestFileName](#setDestFileName-java.lang.String-) | <p> Establece el nombre del archivo de destino. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setDestFileName(\"file.pdf\"); </pre> |
| [setDestStream](#setDestStream-java.io.OutputStream-) | <p> Obtiene la secuencia de destino. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setDestStream (new FileInputStream(\"file.pdf\")); </pre> |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Obtiene o establece las opciones de guardado cuando el resultado se almacena como HttpResponse. Valor predeterminado: PdfSaveOptions. |
| [setSrcFileName](#setSrcFileName-java.lang.String-) | Establece el nombre del archivo de origen. |
| [setSrcStream](#setSrcStream-java.io.InputStream-) | <p> Obtiene la secuencia de origen. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setSrcStream (new FileInputStream(\"source.pdf\"))); </pre> |
| [setXfaData](#setXfaData-java.io.InputStream-) | Reemplaza los datos XFA con el paquete de datos especificado. El paquete de datos puede extraerse usando ExtractXfaData. |

### Form {#Form--}
```
public Form()
```

<p> Constructor de Form sin parámetros. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-com.aspose.pdf.IDocument-}
<p> Constructor de Form sin parámetros. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-com.aspose.pdf.IDocument-java.io.OutputStream-}
<p> Constructor de Form sin parámetros. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-com.aspose.pdf.IDocument-java.lang.String-}
<p> Constructor de Form sin parámetros. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-java.io.InputStream-}
<p> Constructor de Form sin parámetros. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-java.io.InputStream-java.io.OutputStream-}
<p> Constructor de Form sin parámetros. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-java.io.InputStream-java.lang.String-}
<p> Constructor de Form sin parámetros. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-java.lang.String-}
<p> Constructor de Form sin parámetros. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-java.lang.String-java.io.OutputStream-}
<p> Constructor de Form sin parámetros. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-java.lang.String-java.lang.String-}
<p> Constructor de Form sin parámetros. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### bindPdf {#bindPdf-java.io.InputStream-java.lang.String-}
Inicializa la fachada.

### bindPdf {#bindPdf-java.lang.String-java.lang.String-}
Inicializa la fachada.

### close {#close--}
```
public void close()
```

Cierra los archivos abiertos sin realizar cambios.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Cierra todos los recursos abiertos. Este método está obsoleto, use close() en su lugar.

### exportFdf {#exportFdf-java.io.OutputStream-}
<p> Exporta el contenido de los campos del pdf al flujo fdf. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); OutputStream stream = new FileOutputStream(\"export.fdf\"); form.exportFdf(stream); stream.close(); </pre>

### exportXfdf {#exportXfdf-java.io.OutputStream-}
<p> Exporta el contenido de los campos del pdf al flujo xml. El valor del campo de botón no se exportará. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); FileInputStream fs = new FileInputStream(\"export.xfdf\", FileMode.Create, FileAccess.Write); form.exportXfdf(fs); fs.close(); </pre>

### exportXml {#exportXml-java.io.OutputStream-}
<p> Exporta el contenido de los campos del pdf al flujo xml. El valor del campo de botón no se exportará. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\")); OutputStream fs = new FileOutputStream(\"export.xml\"); form.exportXml(fs); fs.close(); </pre>

### extractXfaData {#extractXfaData-java.io.OutputStream-}
Extrae el paquete de datos XFA

### fillBarcodeField {#fillBarcodeField-java.lang.String-java.lang.String-}
<p> Rellena un campo de código de barras según su nombre de campo totalmente calificado. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); form.fillBarcodeField(\"textField\", \"42207252\"); </pre>

### fillField {#fillField-java.lang.String-boolean-}
<p> Rellena el campo de casilla de verificación con un valor booleano. Aviso: Solo se aplica a Check Box. Tenga en cuenta que Facades admite solo nombres de campo completos y no funciona con nombres de campo parciales, a diferencia de Aspose.Pdf.Kit; por ejemplo, si el campo tiene el nombre completo \"Form.Subform.CheckBoxField\" debe especificar el nombre completo y no \"CheckBoxField\". Puede usar la propiedad FieldNames para explorar los nombres de campo existentes y buscar el campo requerido por su nombre parcial. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); form.fillField(\"checkboxField\", true); //how to search field by its partial name: Form form = new Form(\"input.pdf\", \"output.pdf\"); for(String fieldName : form.getFieldNames()) { if (fieldName.endsWith(\"CheckBoxField\")) { System.out.println(\"Full name is: \" + fieldName); } } </pre>

### fillField {#fillField-java.lang.String-int-}
<p> Rellena el campo de caja de radio con un valor de índice válido según un nombre de campo totalmente calificado. Antes de rellenar los campos, solo se debe conocer el nombre del campo. Mientras el valor puede especificarse por su índice. Aviso: Solo se aplica a campos de Caja de Radio, Caja Combinada y Caja de Lista. Tenga en cuenta que Facades admite solo nombres de campo completos y no funciona con nombres de campo parciales, a diferencia de Aspose.Pdf.Kit; Por ejemplo, si el campo tiene el nombre completo \"Form.Subform.ListBoxField\" debe especificar el nombre completo y no \"ListBoxField\". Puede usar la propiedad FieldNames para explorar los nombres de campo existentes y buscar el campo requerido por su nombre parcial. </p> <hr> <pre> //1 Form form = new Form("PdfForm.pdf"); form.fillField("listboxField", 2); form.fillField("comboboxField", 2); form.fillField("radiobuttonField", 2); //2 //how to search field by its partial name: Form form = new Form("input.pdf", "output.pdf"); for(String fieldName : form.getFieldNames()) { if (fieldName.endsWith("ListBoxField")) { System.out.println("Full name is: " + fieldName); } } </pre>

### fillField {#fillField-java.lang.String-java.lang.String-}
<p> Rellena el campo con un valor válido según un nombre de campo totalmente calificado. Antes de rellenar los campos, se deben conocer los nombres de todos los campos y sus valores válidos correspondientes. Tanto el nombre del campo como los valores distinguen entre mayúsculas y minúsculas. Tenga en cuenta que Facades admite solo nombres de campo completos y no funciona con nombres de campo parciales, a diferencia de Aspose.Pdf.Kit; Por ejemplo, si el campo tiene el nombre completo \"Form.Subform.TextField\" debe especificar el nombre completo y no \"TextField\". Puede usar la propiedad FieldNames para explorar los nombres de campo existentes y buscar el campo requerido por su nombre parcial. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); form.fillField("FirstName", "John"); form.fillField("LastName", "Smith"); //how to search field by its partial name: Form form = new Form("input.pdf", "output.pdf"); for(String fieldName : form.getFieldNames()) { if (fieldName.endsWith("TextField")) { System.out.println("Full name is: " + fieldName); } } </pre>

### fillField {#fillField-java.lang.String-java.lang.String:A-}
<p> Rellena un campo con múltiples selecciones. Nota: solo para el campo de Caja de Lista AcroForm. </p> <hr> <pre> Form form = new com.aspose.pdf.Form("PdfForm.pdf", "Form_Updated.pdf"); form.fillField("ListBox1", new String[] { "Three", "One" }); form.save(); </pre>

### fillField {#fillField-java.lang.String-java.lang.String-boolean-}
Rellena el campo con el valor especificado.

### fillFields {#fillFields-java.lang.String:A-java.lang.String:A-java.io.OutputStream-}
Rellena los campos de cuadro de texto con valores de texto y guarda el documento.

### fillImageField {#fillImageField-java.lang.String-java.io.InputStream-}
<p> Sobrecarga de la función FillImageField. La entrada es un flujo de imagen. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_filled.pdf"); form.fillImageField("fieldName", new FileInputStream("file.jpg", FileMode.Open, FileAccess.Read)); </pre>

### fillImageField {#fillImageField-java.lang.String-java.lang.String-}
<p> Pega una imagen en el campo de botón existente como su apariencia según su nombre de campo totalmente calificado. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_filled.pdf"); form.fillImageField("fieldName", "file.jpg"); form.save(); </pre>

### flattenAllFields {#flattenAllFields--}
```
public void flattenAllFields()
```

<p> Aplana todos los campos. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); form.flattenAllFields(); </pre>

### flattenField {#flattenField-java.lang.String-}
<p> Aplana un campo especificado con el nombre de campo totalmente calificado. Cualquier otro campo permanecerá inalterable. Si el fieldName es inválido, todos los campos permanecerán inalterables. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); form.flattenField("textField"); </pre>

### getAttachmentName {#getAttachmentName--}
```
public String getAttachmentName()
```

Obtiene el nombre del adjunto cuando el resultado de la operación se almacena en objetos HttpResponse como adjunto.

**Returns:**
objeto string

### getButtonOptionCurrentValue {#getButtonOptionCurrentValue-java.lang.String-}
<p> Devuelve el valor actual para los campos de opción de botón de radio. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println(form.GetButtonOptionCurrentValue("btnField")); </pre>

### getButtonOptionValues {#getButtonOptionValues-java.lang.String-}
<p> Obtiene los campos de opción de botón de radio y los valores relacionados según el nombre del campo. Este método tiene sentido para grupos de botones de radio. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); java.util.Map values = form.getButtonOptionValues("Color"); System.out.println(values.get("White").toString()); System.out.println(values.get("Black").toString()); </pre>

### getButtonOptionValuesInternal {#getButtonOptionValuesInternal-java.lang.String-}
<p> Obtiene los campos de opciones de botones de radio y los valores relacionados según el nombre del campo. Este método tiene sentido para grupos de botones de radio. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); Hashtable values = form.getButtonOptionValues("Color"); System.out.println(values["White"].toString()); System.out.println(values["Black"].toString()); </pre>

### getContentDisposition {#getContentDisposition--}
```
public ContentDisposition getContentDisposition()
```

Obtiene o establece cómo se almacenará el contenido cuando el resultado de la operación se almacene en un objeto HttpResponse. Valor posible: inline / attachment. Predeterminado: inline.

**Returns:**
Elemento ContentDisposition @see ContentDisposition

### getDestFileName {#getDestFileName--}
```
@Deprecated public String getDestFileName()
```

Obtiene el nombre del archivo de destino.

**Returns:**
objeto string

### getDestStream {#getDestStream--}
```
@Deprecated public OutputStream getDestStream()
```

Obtiene o establece el flujo de destino.

**Returns:**
Objeto OutputStream

### getField {#getField-java.lang.String-}
<p> Obtiene el valor del campo según su nombre. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println("Field value = " + form.getField("Field1")); </pre>

### getFieldFacade {#getFieldFacade-java.lang.String-}
<p> Devuelve un objeto FormFieldFacade que contiene todos los atributos de apariencia. </p> <hr> <pre> com.aspose.pdf.facades.Form form = new com.aspose.pdf.facades.Form("form.pdf")); FormFieldFacade field = form.getFieldFacade("field1"); System.out.println("Color of field border: " + field.getBorderColor()); </pre>

### getFieldFlag {#getFieldFlag-java.lang.String-}
<p> Devuelve los indicadores del campo. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); if (form.getFieldFlag("textField") == ProptyFlag.ReadOnly) { System.out.println("Field is read-only"); } </pre>

### getFieldLimit {#getFieldLimit-java.lang.String-}
<p> Obtiene la limitación del campo de texto. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println(form.getFieldLimit("textfieldBox")); </pre>

### getFieldNames {#getFieldNames--}
```
public String [] getFieldNames()
```

<p> Obtiene la lista de nombres de campos en el formulario. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); String[] fields = form.getFieldNames(); for(String field : fields) { System.out.println(field); } </pre>

**Returns:**
Objeto String[]

### getFieldType {#getFieldType-java.lang.String-}
<p> Devuelve el tipo de campo. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); if (form.getFieldType("textField") == FieldType.Text) { System.out.println("Type of field is text"); } </pre>

### getFormSubmitButtonNames {#getFormSubmitButtonNames--}
```
public String [] getFormSubmitButtonNames()
```

<p> Obtiene todos los nombres de los botones de envío del formulario. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); String[] submits = form.getFormSubmitButtonNames(); for(String btn : submits) { System.out.println(btn); } </pre>

**Returns:**
Objeto String[]

### getFullFieldName {#getFullFieldName-java.lang.String-}
<p> Obtiene el nombre completo del campo según su nombre corto. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println("Full field name is : " + form.getFullFieldName("textField")); </pre>

### getImportResult {#getImportResult--}
```
public com.aspose.pdf.facades.AForm.FormImportResult[] getImportResult()
```

Resultado de la última operación de importación. Matriz de objetos que describen el resultado de la importación para cada campo.

**Returns:**
Matriz FormImportResult[]

### getRichText {#getRichText-java.lang.String-}
<p> Obtiene el valor de un campo de texto enriquecido, incluyendo la información de formato de cada carácter. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println(form.getRichText("txtDescriptionRTF")); </pre>

### getSaveOptions {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```

Obtiene o establece las opciones de guardado cuando el resultado se almacena como HttpResponse. Valor predeterminado: PdfSaveOptions.

**Returns:**
Objeto SaveOptions

### getSrcFileName {#getSrcFileName--}
```
@Deprecated public String getSrcFileName()
```

<p> Obtiene el nombre del archivo fuente. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setSrcFileName("file.pdf"); </pre>

**Returns:**
objeto string

### getSrcStream {#getSrcStream--}
```
public InputStream getSrcStream()
```

Obtiene el flujo de origen.

**Returns:**
Objeto InputStream

### getSubmitFlags {#getSubmitFlags-java.lang.String-}
<p> Devuelve las banderas de envío del botón de envío </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); System.out.println( ( form.getSubmitFlags(\"btnSubmit\") | SubmitFormFlag.Xfdf != 0) ? \" XFDF\" : \" \" ); /// System.out.println( ( form.getSubmitFlags(\"btnSubmit\") | SubmitFormFlag.Fdf != 0) ? \" FDF\" : \" \" ); System.out.println( ( form.getSubmitFlags(\"btnSubmit\") | SubmitFormFlag.Pdf != 0) ? \" PDF\" : \" \" ); </pre>

### importFdf {#importFdf-java.io.InputStream-}
<p> Importa el contenido de los campos del archivo fdf y los coloca en el nuevo pdf. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_imported.pdf"); form.importFdf(new FileInputStream("data.fdf")); form.save(); </pre>

### importXfdf {#importXfdf-java.io.InputStream-}
<p> Importa el contenido de los campos del archivo xfdf(xml) y los coloca en el nuevo pdf. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "Form_ImportXfdf.pdf"); InputStream fs = new FileInputStream("export_old.xfdf"); form.importXfdf(fs); fs.close(); form.save(); </pre>

### importXml {#importXml-java.io.InputStream-}
<p> Importa el contenido de los campos del archivo xml y los coloca en el nuevo pdf. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); InputStream fs = new FileInputStream("import.xml"); form.importXml(fs); form.save("Form_Imported.pdf"); </pre>

### importXml {#importXml-java.io.InputStream-boolean-}
Importa el contenido de los campos del archivo xml y los coloca en el nuevo pdf.

### importXml {#importXml-java.lang.String-}
<p> Importa el contenido de los campos del archivo xml y los coloca en el nuevo pdf. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); form.importXml("import.xml"); form.save( "Form_Imported.pdf"); </pre>

### isRequiredField {#isRequiredField-java.lang.String-}
Determina si el campo es obligatorio o no.

### renameField {#renameField-java.lang.String-java.lang.String-}
<p> Renombra un campo. Ya sea un campo AcroForm o XFA está bien. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfFormUpdated.pdf\"); form.renameField(\"field\", \"field1\"); form.save(); </pre>

### save {#save--}
```
public void save()
```

<p> Guarda el valor de los campos rellenados y cierra el documento PDF abierto. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_Changed.pdf\"); form.fillField(\"textField\", \"new value\"); form.save(); </pre>

### save {#save-java.io.OutputStream-}
<p> Guarda el valor de los campos rellenados y cierra el documento PDF abierto. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_Changed.pdf\"); form.fillField(\"textField\", \"new value\"); form.save(); </pre>

### save {#save-java.lang.String-}
<p> Guarda el valor de los campos rellenados y cierra el documento PDF abierto. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_Changed.pdf\"); form.fillField(\"textField\", \"new value\"); form.save(); </pre>

### setAttachmentName {#setAttachmentName-java.lang.String-}
Establece el nombre del adjunto cuando el resultado de la operación se almacena en objetos HttpResponse como adjunto.

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
Establece cómo se almacenará el contenido cuando el resultado de la operación se almacena en un objeto HttpResponse. Valor posible: inline / attachment. Predeterminado: inline.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Establece el formato de archivo PDF. El archivo resultante se guardará en el formato de archivo especificado. Si esta propiedad no se especifica, el archivo se guardará en el formato PDF predeterminado sin conversión.

### setDestFileName {#setDestFileName-java.lang.String-}
<p> Establece el nombre del archivo de destino. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setDestFileName(\"file.pdf\"); </pre>

### setDestStream {#setDestStream-java.io.OutputStream-}
<p> Obtiene la secuencia de destino. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setDestStream (new FileInputStream(\"file.pdf\")); </pre>

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Obtiene o establece las opciones de guardado cuando el resultado se almacena como HttpResponse. Valor predeterminado: PdfSaveOptions.

### setSrcFileName {#setSrcFileName-java.lang.String-}
Establece el nombre del archivo de origen.

### setSrcStream {#setSrcStream-java.io.InputStream-}
<p> Obtiene la secuencia de origen. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setSrcStream (new FileInputStream(\"source.pdf\"))); </pre>

### setXfaData {#setXfaData-java.io.InputStream-}
Reemplaza los datos XFA con el paquete de datos especificado. El paquete de datos puede extraerse usando ExtractXfaData.
