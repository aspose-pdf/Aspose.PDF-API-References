---
title: "Form"
linktitle: "Form"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Classe che rappresenta l'oggetto del modulo Acro."
type: docs
weight: 170
url: /it/java/com.aspose.pdf.facades/form/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.Form, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.Form, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.Form

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, IForm, ISaveableFacade, Closeable, AutoCloseable

```
public final class Form extends SaveableFacade
```

Classe che rappresenta l'oggetto del modulo Acro.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Form](#Form--) | <p> Costruttore di Form senza parametri. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( "file.pdf"); </pre> |
| [Form](#Form-com.aspose.pdf.IDocument-) | <p> Costruttore di Form senza parametri. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( "file.pdf"); </pre> |
| [Form](#Form-com.aspose.pdf.IDocument-java.io.OutputStream-) | <p> Costruttore di Form senza parametri. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( "file.pdf"); </pre> |
| [Form](#Form-com.aspose.pdf.IDocument-java.lang.String-) | <p> Costruttore di Form senza parametri. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( "file.pdf"); </pre> |
| [Form](#Form-java.io.InputStream-) | <p> Costruttore di Form senza parametri. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( "file.pdf"); </pre> |
| [Form](#Form-java.io.InputStream-java.io.OutputStream-) | <p> Costruttore di Form senza parametri. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( "file.pdf"); </pre> |
| [Form](#Form-java.io.InputStream-java.lang.String-) | <p> Costruttore di Form senza parametri. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( "file.pdf"); </pre> |
| [Form](#Form-java.lang.String-) | <p> Costruttore di Form senza parametri. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( "file.pdf"); </pre> |
| [Form](#Form-java.lang.String-java.io.OutputStream-) | <p> Costruttore di Form senza parametri. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( "file.pdf"); </pre> |
| [Form](#Form-java.lang.String-java.lang.String-) | <p> Costruttore di Form senza parametri. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( "file.pdf"); </pre> |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [bindPdf](#bindPdf-java.io.InputStream-java.lang.String-) | Inizializza la facciata. |
| [bindPdf](#bindPdf-java.lang.String-java.lang.String-) | Inizializza la facciata. |
| [close](#close--) | Chiude i file aperti senza apportare modifiche. |
| [dispose](#dispose--) | Chiude tutte le risorse aperte. Questo metodo è obsoleto, usa close() al suo posto. |
| [exportFdf](#exportFdf-java.io.OutputStream-) | <p> Esporta il contenuto dei campi del pdf nello stream fdf. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); OutputStream stream = new FileOutputStream("export.fdf"); form.exportFdf(stream); stream.close(); </pre> |
| [exportXfdf](#exportXfdf-java.io.OutputStream-) | <p> Esporta il contenuto dei campi del pdf nello stream xml. Il valore del campo pulsante non verrà esportato. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); FileInputStream fs = new FileInputStream("export.xfdf", FileMode.Create, FileAccess.Write); form.exportXfdf(fs); fs.close(); </pre> |
| [exportXml](#exportXml-java.io.OutputStream-) | <p> Esporta il contenuto dei campi del pdf nello stream xml. Il valore del campo pulsante non verrà esportato. </p> <hr> <pre> Form form = new Form("PdfForm.pdf")); OutputStream fs = new FileOutputStream("export.xml"); form.exportXml(fs); fs.close(); </pre> |
| [extractXfaData](#extractXfaData-java.io.OutputStream-) | Estrae il pacchetto dati XFA |
| [fillBarcodeField](#fillBarcodeField-java.lang.String-java.lang.String-) | <p> Compila un campo barcode secondo il suo nome di campo completamente qualificato. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); form.fillBarcodeField("textField", "42207252"); </pre> |
| [fillField](#fillField-java.lang.String-boolean-) | <p> Compila il campo casella di controllo con un valore booleano. Nota: Applicabile solo alle caselle di controllo. Si prega di notare che Facades supporta solo i nomi di campo completi e non funziona con nomi di campo parziali, a differenza di Aspose.Pdf.Kit; ad esempio, se il campo ha il nome completo "Form.Subform.CheckBoxField" è necessario specificare il nome completo e non "CheckBoxField". È possibile utilizzare la proprietà FieldNames per esplorare i nomi dei campi esistenti e cercare il campo richiesto per nome parziale. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); form.fillField("checkboxField", true); //how to search field by its partial name: Form form = new Form("input.pdf", "output.pdf"); for(String fieldName : form.getFieldNames()) { if (fieldName.endsWith("CheckBoxField")) { System.out.println("Full name is: " + fieldName); } } </pre> |
| [fillField](#fillField-java.lang.String-int-) | <p> Compila il campo radio box con un valore indice valido secondo un nome campo completamente qualificato. Prima di compilare i campi, è necessario conoscere solo il nome del campo. Il valore può essere specificato tramite il suo indice. Nota: si applica solo ai campi Radio Box, Combo Box e List Box. Si prega di notare che Facades supporta solo nomi di campo completi e non funziona con nomi di campo parziali, a differenza di Aspose.Pdf.Kit; Ad esempio, se il campo ha il nome completo \"Form.Subform.ListBoxField\" è necessario specificare il nome completo e non \"ListBoxField\". È possibile utilizzare la proprietà FieldNames per esplorare i nomi dei campi esistenti e cercare il campo richiesto per nome parziale. </p> <hr> <pre> //1 Form form = new Form("PdfForm.pdf"); form.fillField("listboxField", 2); form.fillField("comboboxField", 2); form.fillField("radiobuttonField", 2); //2 //how to search field by its partial name: Form form = new Form("input.pdf", "output.pdf"); for(String fieldName : form.getFieldNames()) { if (fieldName.endsWith("ListBoxField")) { System.out.println("Full name is: " + fieldName); } } </pre> |
| [fillField](#fillField-java.lang.String-java.lang.String-) | <p> Compila il campo con un valore valido secondo un nome campo completamente qualificato. Prima di compilare i campi, è necessario conoscere tutti i nomi dei campi e i relativi valori validi. Sia i nomi dei campi che i valori sono sensibili al maiuscolo/minuscolo. Si prega di notare che Facades supporta solo nomi di campo completi e non funziona con nomi di campo parziali, a differenza di Aspose.Pdf.Kit; Ad esempio, se il campo ha il nome completo \"Form.Subform.TextField\" è necessario specificare il nome completo e non \"TextField\". È possibile utilizzare la proprietà FieldNames per esplorare i nomi dei campi esistenti e cercare il campo richiesto per nome parziale. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); form.fillField("FirstName", "John"); form.fillField("LastName", "Smith"); //how to search field by its partial name: Form form = new Form("input.pdf", "output.pdf"); for(String fieldName : form.getFieldNames()) { if (fieldName.endsWith("TextField")) { System.out.println("Full name is: " + fieldName); } } </pre> |
| [fillField](#fillField-java.lang.String-java.lang.String:A-) | <p> Compila un campo con selezioni multiple. Nota: solo per il campo List Box di AcroForm. </p> <hr> <pre> Form form = new com.aspose.pdf.Form("PdfForm.pdf", "Form_Updated.pdf"); form.fillField("ListBox1", new String[] { "Three", "One" }); form.save(); </pre> |
| [fillField](#fillField-java.lang.String-java.lang.String-boolean-) | Compila il campo con il valore specificato. |
| [fillFields](#fillFields-java.lang.String:A-java.lang.String:A-java.io.OutputStream-) | Compila i campi di casella di testo con valori di testo e salva il documento. |
| [fillImageField](#fillImageField-java.lang.String-java.io.InputStream-) | <p> Sovraccarica la funzione FillImageField. L'input è un flusso di immagine. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_filled.pdf"); form.fillImageField("fieldName", new FileInputStream("file.jpg", FileMode.Open, FileAccess.Read)); </pre> |
| [fillImageField](#fillImageField-java.lang.String-java.lang.String-) | <p> Incolla un'immagine sul campo pulsante esistente come sua apparenza secondo il nome campo completamente qualificato. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_filled.pdf"); form.fillImageField("fieldName", "file.jpg"); form.save(); </pre> |
| [flattenAllFields](#flattenAllFields--) | <p> Appiattisce tutti i campi. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); form.flattenAllFields(); </pre> |
| [flattenField](#flattenField-java.lang.String-) | <p> Appiattisce un campo specificato con il nome campo completamente qualificato. Qualsiasi altro campo rimarrà invariato. Se il fieldName è non valido, tutti i campi rimarranno invariati. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); form.flattenField("textField"); </pre> |
| [getAttachmentName](#getAttachmentName--) | Ottiene il nome dell'allegato quando il risultato dell'operazione viene memorizzato negli oggetti HttpResponse come allegato. |
| [getButtonOptionCurrentValue](#getButtonOptionCurrentValue-java.lang.String-) | <p> Restituisce il valore corrente per i campi opzione dei pulsanti radio. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println(form.GetButtonOptionCurrentValue("btnField")); </pre> |
| [getButtonOptionValues](#getButtonOptionValues-java.lang.String-) | <p> Ottiene i campi opzione dei pulsanti radio e i valori correlati in base al nome del campo. Questo metodo è significativo per i gruppi di pulsanti radio. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); java.util.Map values = form.getButtonOptionValues("Color"); System.out.println(values.get("White").toString()); System.out.println(values.get("Black").toString()); </pre> |
| [getButtonOptionValuesInternal](#getButtonOptionValuesInternal-java.lang.String-) | <p> Ottiene i campi di opzione del pulsante radio e i valori correlati in base al nome del campo. Questo metodo è significativo per i gruppi di pulsanti radio. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); Hashtable values = form.getButtonOptionValues("Color"); System.out.println(values["White"].toString()); System.out.println(values["Black"].toString()); </pre> |
| [getContentDisposition](#getContentDisposition--) | Ottiene o imposta come il contenuto verrà memorizzato quando il risultato dell'operazione viene salvato nell'oggetto HttpResponse. Valore possibile: inline / attachment. Predefinito: inline. |
| [getDestFileName](#getDestFileName--) | Ottiene il nome del file di destinazione. |
| [getDestStream](#getDestStream--) | Ottiene o imposta lo stream di destinazione. |
| [getField](#getField-java.lang.String-) | <p> Ottiene il valore del campo in base al suo nome. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println("Field value = " + form.getField("Field1")); </pre> |
| [getFieldFacade](#getFieldFacade-java.lang.String-) | <p> Restituisce l'oggetto FormFieldFacade contenente tutti gli attributi di aspetto. </p> <hr> <pre> com.aspose.pdf.facades.Form form = new com.aspose.pdf.facades.Form("form.pdf")); FormFieldFacade field = form.getFieldFacade("field1"); System.out.println("Color of field border: " + field.getBorderColor()); </pre> |
| [getFieldFlag](#getFieldFlag-java.lang.String-) | <p> Restituisce i flag del campo. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); if (form.getFieldFlag("textField") == ProptyFlag.ReadOnly) { System.out.println("Field is read-only"); } </pre> |
| [getFieldLimit](#getFieldLimit-java.lang.String-) | <p> Ottiene il limite del campo di testo. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println(form.getFieldLimit("textfieldBox")); </pre> |
| [getFieldNames](#getFieldNames--) | <p> Ottiene l'elenco dei nomi dei campi nel modulo. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); String[] fields = form.getFieldNames(); for(String field : fields) { System.out.println(field); } </pre> |
| [getFieldType](#getFieldType-java.lang.String-) | <p> Restituisce il tipo del campo. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); if (form.getFieldType("textField") == FieldType.Text) { System.out.println("Type of field is text"); } </pre> |
| [getFormSubmitButtonNames](#getFormSubmitButtonNames--) | <p> Ottiene tutti i nomi dei pulsanti di invio del modulo. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); String[] submits = form.getFormSubmitButtonNames(); for(String btn : submits) { System.out.println(btn); } </pre> |
| [getFullFieldName](#getFullFieldName-java.lang.String-) | <p> Ottiene il nome completo del campo in base al suo nome breve. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println("Full field name is : " + form.getFullFieldName("textField")); </pre> |
| [getImportResult](#getImportResult--) | Risultato dell'ultima operazione di importazione. Array di oggetti che descrivono il risultato dell'importazione per ciascun campo. |
| [getRichText](#getRichText-java.lang.String-) | <p> Ottiene il valore di un campo Rich Text, includendo le informazioni di formattazione di ogni carattere. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println(form.getRichText("txtDescriptionRTF")); </pre> |
| [getSaveOptions](#getSaveOptions--) | Ottiene o imposta le opzioni di salvataggio quando il risultato è memorizzato come HttpResponse. Valore predefinito: PdfSaveOptions. |
| [getSrcFileName](#getSrcFileName--) | <p> Ottiene il nome del file sorgente. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setSrcFileName("file.pdf"); </pre> |
| [getSrcStream](#getSrcStream--) | Ottiene lo stream di origine. |
| [getSubmitFlags](#getSubmitFlags-java.lang.String-) | <p> Returns the submit button's submission flags </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println( ( form.getSubmitFlags("btnSubmit") \ | SubmitFormFlag.Xfdf != 0) ? " XFDF" : " "); /// System.out.println( ( form.getSubmitFlags("btnSubmit") \ | SubmitFormFlag.Fdf != 0) ? " FDF" : " "); System.out.println( ( form.getSubmitFlags("btnSubmit") \ | SubmitFormFlag.Pdf != 0) ? " PDF" : " "); </pre> |
| [importFdf](#importFdf-java.io.InputStream-) | <p> Importa il contenuto dei campi dal file fdf e lo inserisce nel nuovo pdf. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_imported.pdf"); form.importFdf(new FileInputStream("data.fdf")); form.save(); </pre> |
| [importXfdf](#importXfdf-java.io.InputStream-) | <p> Importa il contenuto dei campi dal file xfdf(xml) e lo inserisce nel nuovo pdf. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "Form_ImportXfdf.pdf"); InputStream fs = new FileInputStream("export_old.xfdf"); form.importXfdf(fs); fs.close(); form.save(); </pre> |
| [importXml](#importXml-java.io.InputStream-) | <p> Importa il contenuto dei campi dal file xml e lo inserisce nel nuovo pdf. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); InputStream fs = new FileInputStream("import.xml"); form.importXml(fs); form.save("Form_Imported.pdf"); </pre> |
| [importXml](#importXml-java.io.InputStream-boolean-) | Importa il contenuto dei campi dal file xml e lo inserisce nel nuovo pdf. |
| [importXml](#importXml-java.lang.String-) | <p> Importa il contenuto dei campi dal file xml e lo inserisce nel nuovo pdf. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); form.importXml("import.xml"); form.save( "Form_Imported.pdf"); </pre> |
| [isRequiredField](#isRequiredField-java.lang.String-) | Determina se il campo è obbligatorio o meno. |
| [renameField](#renameField-java.lang.String-java.lang.String-) | <p> Rinomina un campo. Sia un campo AcroForm sia un campo XFA va bene. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfFormUpdated.pdf\"); form.renameField(\"field\", \"field1\"); form.save(); </pre> |
| [save](#save--) | <p> Salva il valore dei campi compilati e chiude il documento PDF aperto. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_Changed.pdf\"); form.fillField(\"textField\", \"new value\"); form.save(); </pre> |
| [save](#save-java.io.OutputStream-) | <p> Salva il valore dei campi compilati e chiude il documento PDF aperto. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_Changed.pdf\"); form.fillField(\"textField\", \"new value\"); form.save(); </pre> |
| [save](#save-java.lang.String-) | <p> Salva il valore dei campi compilati e chiude il documento PDF aperto. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_Changed.pdf\"); form.fillField(\"textField\", \"new value\"); form.save(); </pre> |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | Imposta il nome dell'allegato quando il risultato dell'operazione viene memorizzato negli oggetti HttpResponse come allegato. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | Imposta come verrà memorizzato il contenuto quando il risultato dell'operazione viene memorizzato nell'oggetto HttpResponse. Valore possibile: inline / attachment. Predefinito: inline. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | Imposta il formato del file PDF. Il file risultante verrà salvato nel formato specificato. Se questa proprietà non è specificata, il file verrà salvato nel formato PDF predefinito senza conversione. |
| [setDestFileName](#setDestFileName-java.lang.String-) | <p> Imposta il nome del file di destinazione. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setDestFileName(\"file.pdf\"); </pre> |
| [setDestStream](#setDestStream-java.io.OutputStream-) | <p> Ottiene lo stream di destinazione. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setDestStream (new FileInputStream(\"file.pdf\")); </pre> |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Ottiene o imposta le opzioni di salvataggio quando il risultato è memorizzato come HttpResponse. Valore predefinito: PdfSaveOptions. |
| [setSrcFileName](#setSrcFileName-java.lang.String-) | Imposta il nome del file di origine. |
| [setSrcStream](#setSrcStream-java.io.InputStream-) | <p> Ottiene lo stream di origine. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setSrcStream (new FileInputStream(\"source.pdf\"))); </pre> |
| [setXfaData](#setXfaData-java.io.InputStream-) | Sostituisce i dati XFA con il pacchetto dati specificato. Il pacchetto dati può essere estratto usando ExtractXfaData. |

### Form {#Form--}
```
public Form()
```

<p> Costruttore di Form senza parametri. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( "file.pdf"); </pre>

### Form {#Form-com.aspose.pdf.IDocument-}
<p> Costruttore di Form senza parametri. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( "file.pdf"); </pre>

### Form {#Form-com.aspose.pdf.IDocument-java.io.OutputStream-}
<p> Costruttore di Form senza parametri. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( "file.pdf"); </pre>

### Form {#Form-com.aspose.pdf.IDocument-java.lang.String-}
<p> Costruttore di Form senza parametri. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( "file.pdf"); </pre>

### Form {#Form-java.io.InputStream-}
<p> Costruttore di Form senza parametri. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( "file.pdf"); </pre>

### Form {#Form-java.io.InputStream-java.io.OutputStream-}
<p> Costruttore di Form senza parametri. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( "file.pdf"); </pre>

### Form {#Form-java.io.InputStream-java.lang.String-}
<p> Costruttore di Form senza parametri. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( "file.pdf"); </pre>

### Form {#Form-java.lang.String-}
<p> Costruttore di Form senza parametri. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( "file.pdf"); </pre>

### Form {#Form-java.lang.String-java.io.OutputStream-}
<p> Costruttore di Form senza parametri. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( "file.pdf"); </pre>

### Form {#Form-java.lang.String-java.lang.String-}
<p> Costruttore di Form senza parametri. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( "file.pdf"); </pre>

### bindPdf {#bindPdf-java.io.InputStream-java.lang.String-}
Inizializza la facciata.

### bindPdf {#bindPdf-java.lang.String-java.lang.String-}
Inizializza la facciata.

### close {#close--}
```
public void close()
```

Chiude i file aperti senza apportare modifiche.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Chiude tutte le risorse aperte. Questo metodo è obsoleto, usa close() al suo posto.

### exportFdf {#exportFdf-java.io.OutputStream-}
<p> Esporta il contenuto dei campi del pdf nello stream fdf. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); OutputStream stream = new FileOutputStream("export.fdf"); form.exportFdf(stream); stream.close(); </pre>

### exportXfdf {#exportXfdf-java.io.OutputStream-}
<p> Esporta il contenuto dei campi del pdf nello stream xml. Il valore del campo pulsante non verrà esportato. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); FileInputStream fs = new FileInputStream("export.xfdf", FileMode.Create, FileAccess.Write); form.exportXfdf(fs); fs.close(); </pre>

### exportXml {#exportXml-java.io.OutputStream-}
<p> Esporta il contenuto dei campi del pdf nello stream xml. Il valore del campo pulsante non verrà esportato. </p> <hr> <pre> Form form = new Form("PdfForm.pdf")); OutputStream fs = new FileOutputStream("export.xml"); form.exportXml(fs); fs.close(); </pre>

### extractXfaData {#extractXfaData-java.io.OutputStream-}
Estrae il pacchetto dati XFA

### fillBarcodeField {#fillBarcodeField-java.lang.String-java.lang.String-}
<p> Compila un campo barcode secondo il suo nome di campo completamente qualificato. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); form.fillBarcodeField("textField", "42207252"); </pre>

### fillField {#fillField-java.lang.String-boolean-}
<p> Compila il campo casella di controllo con un valore booleano. Nota: Applicabile solo alle caselle di controllo. Si prega di notare che Facades supporta solo i nomi di campo completi e non funziona con nomi di campo parziali, a differenza di Aspose.Pdf.Kit; ad esempio, se il campo ha il nome completo "Form.Subform.CheckBoxField" è necessario specificare il nome completo e non "CheckBoxField". È possibile utilizzare la proprietà FieldNames per esplorare i nomi dei campi esistenti e cercare il campo richiesto per nome parziale. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); form.fillField("checkboxField", true); //how to search field by its partial name: Form form = new Form("input.pdf", "output.pdf"); for(String fieldName : form.getFieldNames()) { if (fieldName.endsWith("CheckBoxField")) { System.out.println("Full name is: " + fieldName); } } </pre>

### fillField {#fillField-java.lang.String-int-}
<p> Compila il campo radio box con un valore indice valido secondo un nome campo completamente qualificato. Prima di compilare i campi, è necessario conoscere solo il nome del campo. Il valore può essere specificato tramite il suo indice. Nota: si applica solo ai campi Radio Box, Combo Box e List Box. Si prega di notare che Facades supporta solo nomi di campo completi e non funziona con nomi di campo parziali, a differenza di Aspose.Pdf.Kit; Ad esempio, se il campo ha il nome completo \"Form.Subform.ListBoxField\" è necessario specificare il nome completo e non \"ListBoxField\". È possibile utilizzare la proprietà FieldNames per esplorare i nomi dei campi esistenti e cercare il campo richiesto per nome parziale. </p> <hr> <pre> //1 Form form = new Form("PdfForm.pdf"); form.fillField("listboxField", 2); form.fillField("comboboxField", 2); form.fillField("radiobuttonField", 2); //2 //how to search field by its partial name: Form form = new Form("input.pdf", "output.pdf"); for(String fieldName : form.getFieldNames()) { if (fieldName.endsWith("ListBoxField")) { System.out.println("Full name is: " + fieldName); } } </pre>

### fillField {#fillField-java.lang.String-java.lang.String-}
<p> Compila il campo con un valore valido secondo un nome campo completamente qualificato. Prima di compilare i campi, è necessario conoscere tutti i nomi dei campi e i relativi valori validi. Sia i nomi dei campi che i valori sono sensibili al maiuscolo/minuscolo. Si prega di notare che Facades supporta solo nomi di campo completi e non funziona con nomi di campo parziali, a differenza di Aspose.Pdf.Kit; Ad esempio, se il campo ha il nome completo \"Form.Subform.TextField\" è necessario specificare il nome completo e non \"TextField\". È possibile utilizzare la proprietà FieldNames per esplorare i nomi dei campi esistenti e cercare il campo richiesto per nome parziale. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); form.fillField("FirstName", "John"); form.fillField("LastName", "Smith"); //how to search field by its partial name: Form form = new Form("input.pdf", "output.pdf"); for(String fieldName : form.getFieldNames()) { if (fieldName.endsWith("TextField")) { System.out.println("Full name is: " + fieldName); } } </pre>

### fillField {#fillField-java.lang.String-java.lang.String:A-}
<p> Compila un campo con selezioni multiple. Nota: solo per il campo List Box di AcroForm. </p> <hr> <pre> Form form = new com.aspose.pdf.Form("PdfForm.pdf", "Form_Updated.pdf"); form.fillField("ListBox1", new String[] { "Three", "One" }); form.save(); </pre>

### fillField {#fillField-java.lang.String-java.lang.String-boolean-}
Compila il campo con il valore specificato.

### fillFields {#fillFields-java.lang.String:A-java.lang.String:A-java.io.OutputStream-}
Compila i campi di casella di testo con valori di testo e salva il documento.

### fillImageField {#fillImageField-java.lang.String-java.io.InputStream-}
<p> Sovraccarica la funzione FillImageField. L'input è un flusso di immagine. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_filled.pdf"); form.fillImageField("fieldName", new FileInputStream("file.jpg", FileMode.Open, FileAccess.Read)); </pre>

### fillImageField {#fillImageField-java.lang.String-java.lang.String-}
<p> Incolla un'immagine sul campo pulsante esistente come sua apparenza secondo il nome campo completamente qualificato. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_filled.pdf"); form.fillImageField("fieldName", "file.jpg"); form.save(); </pre>

### flattenAllFields {#flattenAllFields--}
```
public void flattenAllFields()
```

<p> Appiattisce tutti i campi. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); form.flattenAllFields(); </pre>

### flattenField {#flattenField-java.lang.String-}
<p> Appiattisce un campo specificato con il nome campo completamente qualificato. Qualsiasi altro campo rimarrà invariato. Se il fieldName è non valido, tutti i campi rimarranno invariati. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); form.flattenField("textField"); </pre>

### getAttachmentName {#getAttachmentName--}
```
public String getAttachmentName()
```

Ottiene il nome dell'allegato quando il risultato dell'operazione viene memorizzato negli oggetti HttpResponse come allegato.

**Returns:**
oggetto stringa

### getButtonOptionCurrentValue {#getButtonOptionCurrentValue-java.lang.String-}
<p> Restituisce il valore corrente per i campi opzione dei pulsanti radio. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println(form.GetButtonOptionCurrentValue("btnField")); </pre>

### getButtonOptionValues {#getButtonOptionValues-java.lang.String-}
<p> Ottiene i campi opzione dei pulsanti radio e i valori correlati in base al nome del campo. Questo metodo è significativo per i gruppi di pulsanti radio. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); java.util.Map values = form.getButtonOptionValues("Color"); System.out.println(values.get("White").toString()); System.out.println(values.get("Black").toString()); </pre>

### getButtonOptionValuesInternal {#getButtonOptionValuesInternal-java.lang.String-}
<p> Ottiene i campi di opzione del pulsante radio e i valori correlati in base al nome del campo. Questo metodo è significativo per i gruppi di pulsanti radio. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); Hashtable values = form.getButtonOptionValues("Color"); System.out.println(values["White"].toString()); System.out.println(values["Black"].toString()); </pre>

### getContentDisposition {#getContentDisposition--}
```
public ContentDisposition getContentDisposition()
```

Ottiene o imposta come il contenuto verrà memorizzato quando il risultato dell'operazione viene salvato nell'oggetto HttpResponse. Valore possibile: inline / attachment. Predefinito: inline.

**Returns:**
Elemento ContentDisposition @see ContentDisposition

### getDestFileName {#getDestFileName--}
```
@Deprecated public String getDestFileName()
```

Ottiene il nome del file di destinazione.

**Returns:**
oggetto stringa

### getDestStream {#getDestStream--}
```
@Deprecated public OutputStream getDestStream()
```

Ottiene o imposta lo stream di destinazione.

**Returns:**
oggetto OutputStream

### getField {#getField-java.lang.String-}
<p> Ottiene il valore del campo in base al suo nome. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println("Field value = " + form.getField("Field1")); </pre>

### getFieldFacade {#getFieldFacade-java.lang.String-}
<p> Restituisce l'oggetto FormFieldFacade contenente tutti gli attributi di aspetto. </p> <hr> <pre> com.aspose.pdf.facades.Form form = new com.aspose.pdf.facades.Form("form.pdf")); FormFieldFacade field = form.getFieldFacade("field1"); System.out.println("Color of field border: " + field.getBorderColor()); </pre>

### getFieldFlag {#getFieldFlag-java.lang.String-}
<p> Restituisce i flag del campo. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); if (form.getFieldFlag("textField") == ProptyFlag.ReadOnly) { System.out.println("Field is read-only"); } </pre>

### getFieldLimit {#getFieldLimit-java.lang.String-}
<p> Ottiene il limite del campo di testo. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println(form.getFieldLimit("textfieldBox")); </pre>

### getFieldNames {#getFieldNames--}
```
public String [] getFieldNames()
```

<p> Ottiene l'elenco dei nomi dei campi nel modulo. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); String[] fields = form.getFieldNames(); for(String field : fields) { System.out.println(field); } </pre>

**Returns:**
oggetto String[]

### getFieldType {#getFieldType-java.lang.String-}
<p> Restituisce il tipo del campo. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); if (form.getFieldType("textField") == FieldType.Text) { System.out.println("Type of field is text"); } </pre>

### getFormSubmitButtonNames {#getFormSubmitButtonNames--}
```
public String [] getFormSubmitButtonNames()
```

<p> Ottiene tutti i nomi dei pulsanti di invio del modulo. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); String[] submits = form.getFormSubmitButtonNames(); for(String btn : submits) { System.out.println(btn); } </pre>

**Returns:**
oggetto String[]

### getFullFieldName {#getFullFieldName-java.lang.String-}
<p> Ottiene il nome completo del campo in base al suo nome breve. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println("Full field name is : " + form.getFullFieldName("textField")); </pre>

### getImportResult {#getImportResult--}
```
public com.aspose.pdf.facades.AForm.FormImportResult[] getImportResult()
```

Risultato dell'ultima operazione di importazione. Array di oggetti che descrivono il risultato dell'importazione per ciascun campo.

**Returns:**
FormImportResult[] array

### getRichText {#getRichText-java.lang.String-}
<p> Ottiene il valore di un campo Rich Text, includendo le informazioni di formattazione di ogni carattere. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println(form.getRichText("txtDescriptionRTF")); </pre>

### getSaveOptions {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```

Ottiene o imposta le opzioni di salvataggio quando il risultato è memorizzato come HttpResponse. Valore predefinito: PdfSaveOptions.

**Returns:**
oggetto SaveOptions

### getSrcFileName {#getSrcFileName--}
```
@Deprecated public String getSrcFileName()
```

<p> Ottiene il nome del file sorgente. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setSrcFileName("file.pdf"); </pre>

**Returns:**
oggetto stringa

### getSrcStream {#getSrcStream--}
```
public InputStream getSrcStream()
```

Ottiene lo stream di origine.

**Returns:**
Oggetto InputStream

### getSubmitFlags {#getSubmitFlags-java.lang.String-}
<p> Restituisce i flag di invio del pulsante submit </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); System.out.println( ( form.getSubmitFlags(\"btnSubmit\") | SubmitFormFlag.Xfdf != 0) ? \" XFDF\" : \" \" ); /// System.out.println( ( form.getSubmitFlags(\"btnSubmit\") | SubmitFormFlag.Fdf != 0) ? \" FDF\" : \" \" ); System.out.println( ( form.getSubmitFlags(\"btnSubmit\") | SubmitFormFlag.Pdf != 0) ? \" PDF\" : \" \" ); </pre>

### importFdf {#importFdf-java.io.InputStream-}
<p> Importa il contenuto dei campi dal file fdf e lo inserisce nel nuovo pdf. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_imported.pdf"); form.importFdf(new FileInputStream("data.fdf")); form.save(); </pre>

### importXfdf {#importXfdf-java.io.InputStream-}
<p> Importa il contenuto dei campi dal file xfdf(xml) e lo inserisce nel nuovo pdf. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "Form_ImportXfdf.pdf"); InputStream fs = new FileInputStream("export_old.xfdf"); form.importXfdf(fs); fs.close(); form.save(); </pre>

### importXml {#importXml-java.io.InputStream-}
<p> Importa il contenuto dei campi dal file xml e lo inserisce nel nuovo pdf. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); InputStream fs = new FileInputStream("import.xml"); form.importXml(fs); form.save("Form_Imported.pdf"); </pre>

### importXml {#importXml-java.io.InputStream-boolean-}
Importa il contenuto dei campi dal file xml e lo inserisce nel nuovo pdf.

### importXml {#importXml-java.lang.String-}
<p> Importa il contenuto dei campi dal file xml e lo inserisce nel nuovo pdf. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); form.importXml("import.xml"); form.save( "Form_Imported.pdf"); </pre>

### isRequiredField {#isRequiredField-java.lang.String-}
Determina se il campo è obbligatorio o meno.

### renameField {#renameField-java.lang.String-java.lang.String-}
<p> Rinomina un campo. Sia un campo AcroForm sia un campo XFA va bene. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfFormUpdated.pdf\"); form.renameField(\"field\", \"field1\"); form.save(); </pre>

### save {#save--}
```
public void save()
```

<p> Salva il valore dei campi compilati e chiude il documento PDF aperto. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_Changed.pdf\"); form.fillField(\"textField\", \"new value\"); form.save(); </pre>

### save {#save-java.io.OutputStream-}
<p> Salva il valore dei campi compilati e chiude il documento PDF aperto. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_Changed.pdf\"); form.fillField(\"textField\", \"new value\"); form.save(); </pre>

### save {#save-java.lang.String-}
<p> Salva il valore dei campi compilati e chiude il documento PDF aperto. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_Changed.pdf\"); form.fillField(\"textField\", \"new value\"); form.save(); </pre>

### setAttachmentName {#setAttachmentName-java.lang.String-}
Imposta il nome dell'allegato quando il risultato dell'operazione viene memorizzato negli oggetti HttpResponse come allegato.

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
Imposta come verrà memorizzato il contenuto quando il risultato dell'operazione viene memorizzato nell'oggetto HttpResponse. Valore possibile: inline / attachment. Predefinito: inline.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Imposta il formato del file PDF. Il file risultante verrà salvato nel formato specificato. Se questa proprietà non è specificata, il file verrà salvato nel formato PDF predefinito senza conversione.

### setDestFileName {#setDestFileName-java.lang.String-}
<p> Imposta il nome del file di destinazione. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setDestFileName(\"file.pdf\"); </pre>

### setDestStream {#setDestStream-java.io.OutputStream-}
<p> Ottiene lo stream di destinazione. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setDestStream (new FileInputStream(\"file.pdf\")); </pre>

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Ottiene o imposta le opzioni di salvataggio quando il risultato è memorizzato come HttpResponse. Valore predefinito: PdfSaveOptions.

### setSrcFileName {#setSrcFileName-java.lang.String-}
Imposta il nome del file di origine.

### setSrcStream {#setSrcStream-java.io.InputStream-}
<p> Ottiene lo stream di origine. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setSrcStream (new FileInputStream(\"source.pdf\"))); </pre>

### setXfaData {#setXfaData-java.io.InputStream-}
Sostituisce i dati XFA con il pacchetto dati specificato. Il pacchetto dati può essere estratto usando ExtractXfaData.
