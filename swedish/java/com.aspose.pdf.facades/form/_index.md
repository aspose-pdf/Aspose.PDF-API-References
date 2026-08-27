---
title: "Formulär"
linktitle: "Formulär"
second_title: "Aspose.PDF för Java API-referens"
description: "Klass som representerar Acro-formulärobjekt."
type: docs
weight: 170
url: /sv/java/com.aspose.pdf.facades/form/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.Form, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.Form, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.Form

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, IForm, ISaveableFacade, Closeable, AutoCloseable

```
public final class Form extends SaveableFacade
```

Klass som representerar Acro-formulärobjekt.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [Form](#Form--) | <p> Konstruktor för Form utan parametrar. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-com.aspose.pdf.IDocument-) | <p> Konstruktor för Form utan parametrar. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-com.aspose.pdf.IDocument-java.io.OutputStream-) | <p> Konstruktor för Form utan parametrar. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-com.aspose.pdf.IDocument-java.lang.String-) | <p> Konstruktor för Form utan parametrar. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-java.io.InputStream-) | <p> Konstruktor för Form utan parametrar. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-java.io.InputStream-java.io.OutputStream-) | <p> Konstruktor för Form utan parametrar. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-java.io.InputStream-java.lang.String-) | <p> Konstruktor för Form utan parametrar. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-java.lang.String-) | <p> Konstruktor för Form utan parametrar. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-java.lang.String-java.io.OutputStream-) | <p> Konstruktor för Form utan parametrar. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-java.lang.String-java.lang.String-) | <p> Konstruktor för Form utan parametrar. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [bindPdf](#bindPdf-java.io.InputStream-java.lang.String-) | Initierar fasaden. |
| [bindPdf](#bindPdf-java.lang.String-java.lang.String-) | Initierar fasaden. |
| [close](#close--) | Stänger öppna filer utan några ändringar. |
| [dispose](#dispose--) | Stänger alla öppna resurser. Denna metod är föråldrad, använd close() istället. |
| [exportFdf](#exportFdf-java.io.OutputStream-) | <p> Exporterar innehållet i fälten i pdf till fdf-strömmen. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); OutputStream stream = new FileOutputStream(\"export.fdf\"); form.exportFdf(stream); stream.close(); </pre> |
| [exportXfdf](#exportXfdf-java.io.OutputStream-) | <p> Exporterar innehållet i fälten i pdf till xml-strömmen. Värdet för knappfältet kommer inte att exporteras. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); FileInputStream fs = new FileInputStream(\"export.xfdf\", FileMode.Create, FileAccess.Write); form.exportXfdf(fs); fs.close(); </pre> |
| [exportXml](#exportXml-java.io.OutputStream-) | <p> Exporterar innehållet i fälten i pdf till xml-strömmen. Värdet för knappfältet kommer inte att exporteras. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\")); OutputStream fs = new FileOutputStream(\"export.xml\"); form.exportXml(fs); fs.close(); </pre> |
| [extractXfaData](#extractXfaData-java.io.OutputStream-) | Extraherar XFA-datapaket |
| [fillBarcodeField](#fillBarcodeField-java.lang.String-java.lang.String-) | <p> Fyll ett streckkodsfält enligt dess fullständigt kvalificerade fältnamn. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); form.fillBarcodeField(\"textField\", \"42207252\"); </pre> |
| [fillField](#fillField-java.lang.String-boolean-) | <p> Fyller kryssrutan med ett booleskt värde. Obs: Gäller endast för kryssruta. Observera att Facades endast stödjer fullständiga fältnamn och fungerar inte med partiella fältnamn i kontrast till Aspose.Pdf.Kit; Till exempel, om fältet har det fullständiga namnet \"Form.Subform.CheckBoxField\" bör du ange det fullständiga namnet och inte \"CheckBoxField\". Du kan använda egenskapen FieldNames för att utforska befintliga fältnamn och söka efter önskat fält med dess partiella namn. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); form.fillField(\"checkboxField\", true); //how to search field by its partial name: Form form = new Form(\"input.pdf\", \"output.pdf\"); for(String fieldName : form.getFieldNames()) { if (fieldName.endsWith(\"CheckBoxField\")) { System.out.println(\"Full name is: \" + fieldName); } } </pre> |
| [fillField](#fillField-java.lang.String-int-) | <p> Fyll radio‑box‑fältet med ett giltigt indexvärde enligt ett fullständigt kvalificerat fältnamn. Innan fälten fylls i måste endast fältets namn vara känt. Värdet kan specificeras med dess index. Observera: Detta gäller endast Radio Box-, Combo Box- och List Box-fält. Observera att Facades endast stöder fullständiga fältnamn och inte fungerar med partiella fältnamn i motsats till Aspose.Pdf.Kit; Till exempel, om ett fält har det fullständiga namnet \"Form.Subform.ListBoxField\" ska du ange hela namnet och inte \"ListBoxField\". Du kan använda egenskapen FieldNames för att utforska befintliga fältnamn och söka efter önskat fält med dess partiella namn. </p> <hr> <pre> //1 Form form = new Form(\"PdfForm.pdf\"); form.fillField(\"listboxField\", 2); form.fillField(\"comboboxField\", 2); form.fillField(\"radiobuttonField\", 2); //2 //hur man söker efter fält med dess partiella namn: Form form = new Form(\"input.pdf\", \"output.pdf\"); for(String fieldName : form.getFieldNames()) { if (fieldName.endsWith(\"ListBoxField\")) { System.out.println(\"Fullständigt namn är: \" + fieldName); } } </pre> |
| [fillField](#fillField-java.lang.String-java.lang.String-) | <p> Fyll fältet med ett giltigt värde enligt ett fullständigt kvalificerat fältnamn. Innan fälten fylls i måste varje fältnamns namn och dess motsvarande giltiga värden vara kända. Både fältens namn och värden är skiftlägeskänsliga. Observera att Facades endast stöder fullständiga fältnamn och inte fungerar med partiella fältnamn i motsats till Aspose.Pdf.Kit; Till exempel, om ett fält har det fullständiga namnet \"Form.Subform.TextField\" ska du ange hela namnet och inte \"TextField\". Du kan använda egenskapen FieldNames för att utforska befintliga fältnamn och söka efter önskat fält med dess partiella namn. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); form.fillField(\"FirstName\", \"John\"); form.fillField(\"LastName\", \"Smith\"); //hur man söker efter fält med dess partiella namn: Form form = new Form(\"input.pdf\", \"output.pdf\"); for(String fieldName : form.getFieldNames()) { if (fieldName.endsWith(\"TextField\")) { System.out.println(\"Fullständigt namn är: \" + fieldName); } } </pre> |
| [fillField](#fillField-java.lang.String-java.lang.String:A-) | <p> Fyll ett fält med flera val. Obs: endast för AcroForm List Box-fält. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(\"PdfForm.pdf\", \"Form_Updated.pdf\"); form.fillField(\"ListBox1\", new String[] { \"Three\", \"One\" }); form.save(); </pre> |
| [fillField](#fillField-java.lang.String-java.lang.String-boolean-) | Fyller fältet med angivet värde. |
| [fillFields](#fillFields-java.lang.String:A-java.lang.String:A-java.io.OutputStream-) | Fyller textrutefälten med textvärden och sparar dokumentet. |
| [fillImageField](#fillImageField-java.lang.String-java.io.InputStream-) | <p> Överlagrar funktionen FillImageField. Inmatningen är en bildström. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_filled.pdf\"); form.fillImageField(\"fieldName\", new FileInputStream(\"file.jpg\", FileMode.Open, FileAccess.Read)); </pre> |
| [fillImageField](#fillImageField-java.lang.String-java.lang.String-) | <p> Klistrar in en bild på det befintliga knappfältet som dess utseende enligt dess fullständigt kvalificerade fältnamn. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_filled.pdf\"); form.fillImageField(\"fieldName\", \"file.jpg\"); form.save(); </pre> |
| [flattenAllFields](#flattenAllFields--) | <p> Plattar till alla fält. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); form.flattenAllFields(); </pre> |
| [flattenField](#flattenField-java.lang.String-) | <p> Plattar till ett specificerat fält med det fullständigt kvalificerade fältnamnet. Alla andra fält förblir oföränderliga. Om fieldName är ogiltigt, kommer alla fält att förbli oföränderliga. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); form.flattenField("textField"); </pre> |
| [getAttachmentName](#getAttachmentName--) | Hämtar namn på bilagan när resultatet av operationen lagras i HttpResponse-objekt som bilaga. |
| [getButtonOptionCurrentValue](#getButtonOptionCurrentValue-java.lang.String-) | <p> Returnerar det aktuella värdet för radioknappsalternativfält. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println(form.GetButtonOptionCurrentValue("btnField")); </pre> |
| [getButtonOptionValues](#getButtonOptionValues-java.lang.String-) | <p> Hämtar radioknappsalternativfälten och relaterade värden baserat på fältnamnet. Denna metod är relevant för radioknappsgupper. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); java.util.Map values = form.getButtonOptionValues("Color"); System.out.println(values.get("White").toString()); System.out.println(values.get("Black").toString()); </pre> |
| [getButtonOptionValuesInternal](#getButtonOptionValuesInternal-java.lang.String-) | <p> Hämtar radioknappsalternativfälten och relaterade värden baserat på fältnamnet. Denna metod är relevant för radioknappsgupper. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); Hashtable values = form.getButtonOptionValues("Color"); System.out.println(values["White"].toString()); System.out.println(values["Black"].toString()); </pre> |
| [getContentDisposition](#getContentDisposition--) | Hämtar eller anger hur innehållet ska lagras när resultatet av operationen lagras i HttpResponse-objektet. Möjligt värde: inline / attachment. Standard: inline. |
| [getDestFileName](#getDestFileName--) | Hämtar destinationsfilens namn. |
| [getDestStream](#getDestStream--) | Hämtar eller anger destinationsström. |
| [getField](#getField-java.lang.String-) | <p> Hämtar fältets värde enligt dess fältnamn. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println("Field value = " + form.getField("Field1")); </pre> |
| [getFieldFacade](#getFieldFacade-java.lang.String-) | <p> Returnerar FormFieldFacade-objekt som innehåller alla utseendeattribut. </p> <hr> <pre> com.aspose.pdf.facades.Form form = new com.aspose.pdf.facades.Form("form.pdf")); FormFieldFacade field = form.getFieldFacade("field1"); System.out.println("Color of field border: " + field.getBorderColor()); </pre> |
| [getFieldFlag](#getFieldFlag-java.lang.String-) | <p> Returnerar flaggor för fältet. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); if (form.getFieldFlag("textField") == ProptyFlag.ReadOnly) { System.out.println("Field is read-only"); } </pre> |
| [getFieldLimit](#getFieldLimit-java.lang.String-) | <p> Hämta begränsningen för textfältet. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println(form.getFieldLimit("textfieldBox")); </pre> |
| [getFieldNames](#getFieldNames--) | <p> Hämtar en lista med fältnamn på formuläret. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); String[] fields = form.getFieldNames(); for(String field : fields) { System.out.println(field); } </pre> |
| [getFieldType](#getFieldType-java.lang.String-) | <p> Returnerar fälttypen. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); if (form.getFieldType("textField") == FieldType.Text) { System.out.println("Type of field is text"); } </pre> |
| [getFormSubmitButtonNames](#getFormSubmitButtonNames--) | <p> Hämtar alla namn på formulärets submit-knappar. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); String[] submits = form.getFormSubmitButtonNames(); for(String btn : submits) { System.out.println(btn); } </pre> |
| [getFullFieldName](#getFullFieldName-java.lang.String-) | <p> Hämtar det fullständiga fältnamnet enligt dess korta fältnamn. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println("Full field name is : " + form.getFullFieldName("textField")); </pre> |
| [getImportResult](#getImportResult--) | Resultat av den senaste importoperationen. En array av objekt som beskriver importresultatet för varje fält. |
| [getRichText](#getRichText-java.lang.String-) | <p> Hämta värdet för ett Rich Text-fält, inklusive formateringsinformationen för varje tecken. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); System.out.println(form.getRichText(\"txtDescriptionRTF\")); </pre> |
| [getSaveOptions](#getSaveOptions--) | Hämtar eller anger sparaalternativ när resultatet lagras som HttpResponse. Standardvärde: PdfSaveOptions. |
| [getSrcFileName](#getSrcFileName--) | <p> Hämtar källfilens namn. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setSrcFileName(\"file.pdf\"); </pre> |
| [getSrcStream](#getSrcStream--) | Hämtar källström. |
| [getSubmitFlags](#getSubmitFlags-java.lang.String-) | <p> Returns the submit button's submission flags </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println( ( form.getSubmitFlags("btnSubmit") \ | SubmitFormFlag.Xfdf != 0) ? " XFDF" : " "); /// System.out.println( ( form.getSubmitFlags("btnSubmit") \ | SubmitFormFlag.Fdf != 0) ? " FDF" : " "); System.out.println( ( form.getSubmitFlags("btnSubmit") \ | SubmitFormFlag.Pdf != 0) ? \" PDF\" : \" \" ); </pre> |
| [importFdf](#importFdf-java.io.InputStream-) | <p> Importerar fältens innehåll från fdf-filen och placerar dem i den nya pdf-filen. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_imported.pdf\"); form.importFdf(new FileInputStream(\"data.fdf\")); form.save(); </pre> |
| [importXfdf](#importXfdf-java.io.InputStream-) | <p> Importerar fältens innehåll från xfdf(xml)-filen och placerar dem i den nya pdf-filen. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"Form_ImportXfdf.pdf\"); InputStream fs = new FileInputStream(\"export_old.xfdf\"); form.importXfdf(fs); fs.close(); form.save(); </pre> |
| [importXml](#importXml-java.io.InputStream-) | <p> Importerar fältens innehåll från xml-filen och placerar dem i den nya pdf-filen. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); InputStream fs = new FileInputStream(\"import.xml\"); form.importXml(fs); form.save(\"Form_Imported.pdf\"); </pre> |
| [importXml](#importXml-java.io.InputStream-boolean-) | Importerar fältens innehåll från xml-filen och placerar dem i den nya pdf-filen. |
| [importXml](#importXml-java.lang.String-) | <p> Importerar fältens innehåll från xml-filen och placerar dem i den nya pdf-filen. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); form.importXml(\"import.xml\"); form.save( \"Form_Imported.pdf\"); </pre> |
| [isRequiredField](#isRequiredField-java.lang.String-) | Avgör om fältet är obligatoriskt eller inte. |
| [renameField](#renameField-java.lang.String-java.lang.String-) | <p> Byter namn på ett fält. Antingen AcroForm-fält eller XFA-fält är OK. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfFormUpdated.pdf\"); form.renameField(\"field\", \"field1\"); form.save(); </pre> |
| [save](#save--) | <p> Sparar värdet för de ifyllda fälten och stänger det öppnade Pdf-dokumentet. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_Changed.pdf\"); form.fillField(\"textField\", \"new value\"); form.save(); </pre> |
| [save](#save-java.io.OutputStream-) | <p> Sparar värdet för de ifyllda fälten och stänger det öppnade Pdf-dokumentet. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_Changed.pdf\"); form.fillField(\"textField\", \"new value\"); form.save(); </pre> |
| [save](#save-java.lang.String-) | <p> Sparar värdet för de ifyllda fälten och stänger det öppnade Pdf-dokumentet. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_Changed.pdf\"); form.fillField(\"textField\", \"new value\"); form.save(); </pre> |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | Ställer in namn på bilagan när resultatet av operationen lagras i HttpResponse-objekt som bilaga. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | Ställer in hur innehållet ska lagras när resultatet av operationen lagras i ett HttpResponse-objekt. Möjligt värde: inline / attachment. Standard: inline. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | Ställer in PDF-filformat. Resultatfilen sparas i angivet filformat. Om denna egenskap inte anges sparas filen i standard PDF-format utan konvertering. |
| [setDestFileName](#setDestFileName-java.lang.String-) | <p> Ställer in destinationsfilens namn. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setDestFileName(\"file.pdf\"); </pre> |
| [setDestStream](#setDestStream-java.io.OutputStream-) | <p> Hämtar destinationsström. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setDestStream (new FileInputStream(\"file.pdf\")); </pre> |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Hämtar eller anger sparaalternativ när resultatet lagras som HttpResponse. Standardvärde: PdfSaveOptions. |
| [setSrcFileName](#setSrcFileName-java.lang.String-) | Ställer in källfilens namn. |
| [setSrcStream](#setSrcStream-java.io.InputStream-) | <p> Hämtar källström. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setSrcStream (new FileInputStream(\"source.pdf\"))); </pre> |
| [setXfaData](#setXfaData-java.io.InputStream-) | Ersätter XFA-data med angivet datapaket. Datapaketet kan extraheras med hjälp av ExtractXfaData. |

### Form {#Form--}
```
public Form()
```

<p> Konstruktor för Form utan parametrar. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-com.aspose.pdf.IDocument-}
<p> Konstruktor för Form utan parametrar. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-com.aspose.pdf.IDocument-java.io.OutputStream-}
<p> Konstruktor för Form utan parametrar. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-com.aspose.pdf.IDocument-java.lang.String-}
<p> Konstruktor för Form utan parametrar. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-java.io.InputStream-}
<p> Konstruktor för Form utan parametrar. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-java.io.InputStream-java.io.OutputStream-}
<p> Konstruktor för Form utan parametrar. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-java.io.InputStream-java.lang.String-}
<p> Konstruktor för Form utan parametrar. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-java.lang.String-}
<p> Konstruktor för Form utan parametrar. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-java.lang.String-java.io.OutputStream-}
<p> Konstruktor för Form utan parametrar. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-java.lang.String-java.lang.String-}
<p> Konstruktor för Form utan parametrar. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### bindPdf {#bindPdf-java.io.InputStream-java.lang.String-}
Initierar fasaden.

### bindPdf {#bindPdf-java.lang.String-java.lang.String-}
Initierar fasaden.

### close {#close--}
```
public void close()
```

Stänger öppna filer utan några ändringar.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Stänger alla öppna resurser. Denna metod är föråldrad, använd close() istället.

### exportFdf {#exportFdf-java.io.OutputStream-}
<p> Exporterar innehållet i fälten i pdf till fdf-strömmen. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); OutputStream stream = new FileOutputStream(\"export.fdf\"); form.exportFdf(stream); stream.close(); </pre>

### exportXfdf {#exportXfdf-java.io.OutputStream-}
<p> Exporterar innehållet i fälten i pdf till xml-strömmen. Värdet för knappfältet kommer inte att exporteras. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); FileInputStream fs = new FileInputStream(\"export.xfdf\", FileMode.Create, FileAccess.Write); form.exportXfdf(fs); fs.close(); </pre>

### exportXml {#exportXml-java.io.OutputStream-}
<p> Exporterar innehållet i fälten i pdf till xml-strömmen. Värdet för knappfältet kommer inte att exporteras. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\")); OutputStream fs = new FileOutputStream(\"export.xml\"); form.exportXml(fs); fs.close(); </pre>

### extractXfaData {#extractXfaData-java.io.OutputStream-}
Extraherar XFA-datapaket

### fillBarcodeField {#fillBarcodeField-java.lang.String-java.lang.String-}
<p> Fyll ett streckkodsfält enligt dess fullständigt kvalificerade fältnamn. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); form.fillBarcodeField(\"textField\", \"42207252\"); </pre>

### fillField {#fillField-java.lang.String-boolean-}
<p> Fyller kryssrutan med ett booleskt värde. Obs: Gäller endast för kryssruta. Observera att Facades endast stödjer fullständiga fältnamn och fungerar inte med partiella fältnamn i kontrast till Aspose.Pdf.Kit; Till exempel, om fältet har det fullständiga namnet \"Form.Subform.CheckBoxField\" bör du ange det fullständiga namnet och inte \"CheckBoxField\". Du kan använda egenskapen FieldNames för att utforska befintliga fältnamn och söka efter önskat fält med dess partiella namn. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); form.fillField(\"checkboxField\", true); //how to search field by its partial name: Form form = new Form(\"input.pdf\", \"output.pdf\"); for(String fieldName : form.getFieldNames()) { if (fieldName.endsWith(\"CheckBoxField\")) { System.out.println(\"Full name is: \" + fieldName); } } </pre>

### fillField {#fillField-java.lang.String-int-}
<p> Fyll radio‑box‑fältet med ett giltigt indexvärde enligt ett fullständigt kvalificerat fältnamn. Innan fälten fylls i måste endast fältets namn vara känt. Värdet kan specificeras med dess index. Observera: Detta gäller endast Radio Box-, Combo Box- och List Box-fält. Observera att Facades endast stöder fullständiga fältnamn och inte fungerar med partiella fältnamn i motsats till Aspose.Pdf.Kit; Till exempel, om ett fält har det fullständiga namnet \"Form.Subform.ListBoxField\" ska du ange hela namnet och inte \"ListBoxField\". Du kan använda egenskapen FieldNames för att utforska befintliga fältnamn och söka efter önskat fält med dess partiella namn. </p> <hr> <pre> //1 Form form = new Form(\"PdfForm.pdf\"); form.fillField(\"listboxField\", 2); form.fillField(\"comboboxField\", 2); form.fillField(\"radiobuttonField\", 2); //2 //hur man söker efter fält med dess partiella namn: Form form = new Form(\"input.pdf\", \"output.pdf\"); for(String fieldName : form.getFieldNames()) { if (fieldName.endsWith(\"ListBoxField\")) { System.out.println(\"Fullständigt namn är: \" + fieldName); } } </pre>

### fillField {#fillField-java.lang.String-java.lang.String-}
<p> Fyll fältet med ett giltigt värde enligt ett fullständigt kvalificerat fältnamn. Innan fälten fylls i måste varje fältnamns namn och dess motsvarande giltiga värden vara kända. Både fältens namn och värden är skiftlägeskänsliga. Observera att Facades endast stöder fullständiga fältnamn och inte fungerar med partiella fältnamn i motsats till Aspose.Pdf.Kit; Till exempel, om ett fält har det fullständiga namnet \"Form.Subform.TextField\" ska du ange hela namnet och inte \"TextField\". Du kan använda egenskapen FieldNames för att utforska befintliga fältnamn och söka efter önskat fält med dess partiella namn. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); form.fillField(\"FirstName\", \"John\"); form.fillField(\"LastName\", \"Smith\"); //hur man söker efter fält med dess partiella namn: Form form = new Form(\"input.pdf\", \"output.pdf\"); for(String fieldName : form.getFieldNames()) { if (fieldName.endsWith(\"TextField\")) { System.out.println(\"Fullständigt namn är: \" + fieldName); } } </pre>

### fillField {#fillField-java.lang.String-java.lang.String:A-}
<p> Fyll ett fält med flera val. Obs: endast för AcroForm List Box-fält. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(\"PdfForm.pdf\", \"Form_Updated.pdf\"); form.fillField(\"ListBox1\", new String[] { \"Three\", \"One\" }); form.save(); </pre>

### fillField {#fillField-java.lang.String-java.lang.String-boolean-}
Fyller fältet med angivet värde.

### fillFields {#fillFields-java.lang.String:A-java.lang.String:A-java.io.OutputStream-}
Fyller textrutefälten med textvärden och sparar dokumentet.

### fillImageField {#fillImageField-java.lang.String-java.io.InputStream-}
<p> Överlagrar funktionen FillImageField. Inmatningen är en bildström. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_filled.pdf\"); form.fillImageField(\"fieldName\", new FileInputStream(\"file.jpg\", FileMode.Open, FileAccess.Read)); </pre>

### fillImageField {#fillImageField-java.lang.String-java.lang.String-}
<p> Klistrar in en bild på det befintliga knappfältet som dess utseende enligt dess fullständigt kvalificerade fältnamn. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_filled.pdf\"); form.fillImageField(\"fieldName\", \"file.jpg\"); form.save(); </pre>

### flattenAllFields {#flattenAllFields--}
```
public void flattenAllFields()
```

<p> Plattar till alla fält. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); form.flattenAllFields(); </pre>

### flattenField {#flattenField-java.lang.String-}
<p> Plattar till ett specificerat fält med det fullständigt kvalificerade fältnamnet. Alla andra fält förblir oföränderliga. Om fieldName är ogiltigt, kommer alla fält att förbli oföränderliga. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); form.flattenField("textField"); </pre>

### getAttachmentName {#getAttachmentName--}
```
public String getAttachmentName()
```

Hämtar namn på bilagan när resultatet av operationen lagras i HttpResponse-objekt som bilaga.

**Returns:**
string‑objekt

### getButtonOptionCurrentValue {#getButtonOptionCurrentValue-java.lang.String-}
<p> Returnerar det aktuella värdet för radioknappsalternativfält. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println(form.GetButtonOptionCurrentValue("btnField")); </pre>

### getButtonOptionValues {#getButtonOptionValues-java.lang.String-}
<p> Hämtar radioknappsalternativfälten och relaterade värden baserat på fältnamnet. Denna metod är relevant för radioknappsgupper. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); java.util.Map values = form.getButtonOptionValues("Color"); System.out.println(values.get("White").toString()); System.out.println(values.get("Black").toString()); </pre>

### getButtonOptionValuesInternal {#getButtonOptionValuesInternal-java.lang.String-}
<p> Hämtar radioknappsalternativfälten och relaterade värden baserat på fältnamnet. Denna metod är relevant för radioknappsgupper. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); Hashtable values = form.getButtonOptionValues("Color"); System.out.println(values["White"].toString()); System.out.println(values["Black"].toString()); </pre>

### getContentDisposition {#getContentDisposition--}
```
public ContentDisposition getContentDisposition()
```

Hämtar eller anger hur innehållet ska lagras när resultatet av operationen lagras i HttpResponse-objektet. Möjligt värde: inline / attachment. Standard: inline.

**Returns:**
ContentDisposition-element @see ContentDisposition

### getDestFileName {#getDestFileName--}
```
@Deprecated public String getDestFileName()
```

Hämtar destinationsfilens namn.

**Returns:**
string‑objekt

### getDestStream {#getDestStream--}
```
@Deprecated public OutputStream getDestStream()
```

Hämtar eller anger destinationsström.

**Returns:**
OutputStream objekt

### getField {#getField-java.lang.String-}
<p> Hämtar fältets värde enligt dess fältnamn. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println("Field value = " + form.getField("Field1")); </pre>

### getFieldFacade {#getFieldFacade-java.lang.String-}
<p> Returnerar FormFieldFacade-objekt som innehåller alla utseendeattribut. </p> <hr> <pre> com.aspose.pdf.facades.Form form = new com.aspose.pdf.facades.Form("form.pdf")); FormFieldFacade field = form.getFieldFacade("field1"); System.out.println("Color of field border: " + field.getBorderColor()); </pre>

### getFieldFlag {#getFieldFlag-java.lang.String-}
<p> Returnerar flaggor för fältet. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); if (form.getFieldFlag("textField") == ProptyFlag.ReadOnly) { System.out.println("Field is read-only"); } </pre>

### getFieldLimit {#getFieldLimit-java.lang.String-}
<p> Hämta begränsningen för textfältet. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println(form.getFieldLimit("textfieldBox")); </pre>

### getFieldNames {#getFieldNames--}
```
public String [] getFieldNames()
```

<p> Hämtar en lista med fältnamn på formuläret. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); String[] fields = form.getFieldNames(); for(String field : fields) { System.out.println(field); } </pre>

**Returns:**
String[] objekt

### getFieldType {#getFieldType-java.lang.String-}
<p> Returnerar fälttypen. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); if (form.getFieldType("textField") == FieldType.Text) { System.out.println("Type of field is text"); } </pre>

### getFormSubmitButtonNames {#getFormSubmitButtonNames--}
```
public String [] getFormSubmitButtonNames()
```

<p> Hämtar alla namn på formulärets submit-knappar. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); String[] submits = form.getFormSubmitButtonNames(); for(String btn : submits) { System.out.println(btn); } </pre>

**Returns:**
String[] objekt

### getFullFieldName {#getFullFieldName-java.lang.String-}
<p> Hämtar det fullständiga fältnamnet enligt dess korta fältnamn. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println("Full field name is : " + form.getFullFieldName("textField")); </pre>

### getImportResult {#getImportResult--}
```
public com.aspose.pdf.facades.AForm.FormImportResult[] getImportResult()
```

Resultat av den senaste importoperationen. En array av objekt som beskriver importresultatet för varje fält.

**Returns:**
FormImportResult[] array

### getRichText {#getRichText-java.lang.String-}
<p> Hämta värdet för ett Rich Text-fält, inklusive formateringsinformationen för varje tecken. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); System.out.println(form.getRichText(\"txtDescriptionRTF\")); </pre>

### getSaveOptions {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```

Hämtar eller anger sparaalternativ när resultatet lagras som HttpResponse. Standardvärde: PdfSaveOptions.

**Returns:**
SaveOptions-objekt

### getSrcFileName {#getSrcFileName--}
```
@Deprecated public String getSrcFileName()
```

<p> Hämtar källfilens namn. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setSrcFileName(\"file.pdf\"); </pre>

**Returns:**
string‑objekt

### getSrcStream {#getSrcStream--}
```
public InputStream getSrcStream()
```

Hämtar källström.

**Returns:**
InputStream-objekt

### getSubmitFlags {#getSubmitFlags-java.lang.String-}
<p> Returnerar inlämningsknappens inskickningsflaggor </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); System.out.println( ( form.getSubmitFlags(\"btnSubmit\") | SubmitFormFlag.Xfdf != 0) ? \" XFDF\" : \" \" ); /// System.out.println( ( form.getSubmitFlags(\"btnSubmit\") | SubmitFormFlag.Fdf != 0) ? \" FDF\" : \" \" ); System.out.println( ( form.getSubmitFlags(\"btnSubmit\") | SubmitFormFlag.Pdf != 0) ? \" PDF\" : \" \" ); </pre>

### importFdf {#importFdf-java.io.InputStream-}
<p> Importerar fältens innehåll från fdf-filen och placerar dem i den nya pdf-filen. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_imported.pdf\"); form.importFdf(new FileInputStream(\"data.fdf\")); form.save(); </pre>

### importXfdf {#importXfdf-java.io.InputStream-}
<p> Importerar fältens innehåll från xfdf(xml)-filen och placerar dem i den nya pdf-filen. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"Form_ImportXfdf.pdf\"); InputStream fs = new FileInputStream(\"export_old.xfdf\"); form.importXfdf(fs); fs.close(); form.save(); </pre>

### importXml {#importXml-java.io.InputStream-}
<p> Importerar fältens innehåll från xml-filen och placerar dem i den nya pdf-filen. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); InputStream fs = new FileInputStream(\"import.xml\"); form.importXml(fs); form.save(\"Form_Imported.pdf\"); </pre>

### importXml {#importXml-java.io.InputStream-boolean-}
Importerar fältens innehåll från xml-filen och placerar dem i den nya pdf-filen.

### importXml {#importXml-java.lang.String-}
<p> Importerar fältens innehåll från xml-filen och placerar dem i den nya pdf-filen. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); form.importXml(\"import.xml\"); form.save( \"Form_Imported.pdf\"); </pre>

### isRequiredField {#isRequiredField-java.lang.String-}
Avgör om fältet är obligatoriskt eller inte.

### renameField {#renameField-java.lang.String-java.lang.String-}
<p> Byter namn på ett fält. Antingen AcroForm-fält eller XFA-fält är OK. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfFormUpdated.pdf\"); form.renameField(\"field\", \"field1\"); form.save(); </pre>

### save {#save--}
```
public void save()
```

<p> Sparar värdet för de ifyllda fälten och stänger det öppnade Pdf-dokumentet. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_Changed.pdf\"); form.fillField(\"textField\", \"new value\"); form.save(); </pre>

### save {#save-java.io.OutputStream-}
<p> Sparar värdet för de ifyllda fälten och stänger det öppnade Pdf-dokumentet. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_Changed.pdf\"); form.fillField(\"textField\", \"new value\"); form.save(); </pre>

### save {#save-java.lang.String-}
<p> Sparar värdet för de ifyllda fälten och stänger det öppnade Pdf-dokumentet. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_Changed.pdf\"); form.fillField(\"textField\", \"new value\"); form.save(); </pre>

### setAttachmentName {#setAttachmentName-java.lang.String-}
Ställer in namn på bilagan när resultatet av operationen lagras i HttpResponse-objekt som bilaga.

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
Ställer in hur innehållet ska lagras när resultatet av operationen lagras i ett HttpResponse-objekt. Möjligt värde: inline / attachment. Standard: inline.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Ställer in PDF-filformat. Resultatfilen sparas i angivet filformat. Om denna egenskap inte anges sparas filen i standard PDF-format utan konvertering.

### setDestFileName {#setDestFileName-java.lang.String-}
<p> Ställer in destinationsfilens namn. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setDestFileName(\"file.pdf\"); </pre>

### setDestStream {#setDestStream-java.io.OutputStream-}
<p> Hämtar destinationsström. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setDestStream (new FileInputStream(\"file.pdf\")); </pre>

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Hämtar eller anger sparaalternativ när resultatet lagras som HttpResponse. Standardvärde: PdfSaveOptions.

### setSrcFileName {#setSrcFileName-java.lang.String-}
Ställer in källfilens namn.

### setSrcStream {#setSrcStream-java.io.InputStream-}
<p> Hämtar källström. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setSrcStream (new FileInputStream(\"source.pdf\"))); </pre>

### setXfaData {#setXfaData-java.io.InputStream-}
Ersätter XFA-data med angivet datapaket. Datapaketet kan extraheras med hjälp av ExtractXfaData.
