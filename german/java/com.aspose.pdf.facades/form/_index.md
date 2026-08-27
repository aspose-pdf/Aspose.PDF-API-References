---
title: "Formular"
linktitle: "Formular"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Klasse, die ein Acro-Formularobjekt darstellt."
type: docs
weight: 170
url: /de/java/com.aspose.pdf.facades/form/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.Form, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.Form, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.Form

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, IForm, ISaveableFacade, Closeable, AutoCloseable

```
public final class Form extends SaveableFacade
```

Klasse, die ein Acro-Formularobjekt darstellt.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Form](#Form--) | <p> Konstruktor von Form ohne Parameter. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-com.aspose.pdf.IDocument-) | <p> Konstruktor von Form ohne Parameter. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-com.aspose.pdf.IDocument-java.io.OutputStream-) | <p> Konstruktor von Form ohne Parameter. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-com.aspose.pdf.IDocument-java.lang.String-) | <p> Konstruktor von Form ohne Parameter. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-java.io.InputStream-) | <p> Konstruktor von Form ohne Parameter. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-java.io.InputStream-java.io.OutputStream-) | <p> Konstruktor von Form ohne Parameter. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-java.io.InputStream-java.lang.String-) | <p> Konstruktor von Form ohne Parameter. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-java.lang.String-) | <p> Konstruktor von Form ohne Parameter. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-java.lang.String-java.io.OutputStream-) | <p> Konstruktor von Form ohne Parameter. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-java.lang.String-java.lang.String-) | <p> Konstruktor von Form ohne Parameter. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [bindPdf](#bindPdf-java.io.InputStream-java.lang.String-) | Initialisiert die Fassade. |
| [bindPdf](#bindPdf-java.lang.String-java.lang.String-) | Initialisiert die Fassade. |
| [close](#close--) | Schließt geöffnete Dateien, ohne Änderungen vorzunehmen. |
| [dispose](#dispose--) | Schließt alle geöffneten Ressourcen. Diese Methode ist veraltet, verwenden Sie stattdessen close(). |
| [exportFdf](#exportFdf-java.io.OutputStream-) | <p> Exportiert den Inhalt der Felder des PDFs in den fdf‑Stream. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); OutputStream stream = new FileOutputStream(\"export.fdf\"); form.exportFdf(stream); stream.close(); </pre> |
| [exportXfdf](#exportXfdf-java.io.OutputStream-) | <p> Exportiert den Inhalt der Felder des PDFs in den xml‑Stream. Der Wert des Button‑Feldes wird nicht exportiert. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); FileInputStream fs = new FileInputStream(\"export.xfdf\", FileMode.Create, FileAccess.Write); form.exportXfdf(fs); fs.close(); </pre> |
| [exportXml](#exportXml-java.io.OutputStream-) | <p> Exportiert den Inhalt der Felder des PDFs in den xml‑Stream. Der Wert des Button‑Feldes wird nicht exportiert. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\")); OutputStream fs = new FileOutputStream(\"export.xml\"); form.exportXml(fs); fs.close(); </pre> |
| [extractXfaData](#extractXfaData-java.io.OutputStream-) | Extrahiert XFA-Datenpaket |
| [fillBarcodeField](#fillBarcodeField-java.lang.String-java.lang.String-) | <p> Füllt ein Barcode‑Feld gemäß seinem vollqualifizierten Feldnamen. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); form.fillBarcodeField(\"textField\", \"42207252\"); </pre> |
| [fillField](#fillField-java.lang.String-boolean-) | <p> Füllt das Kontrollkästchenfeld mit einem booleschen Wert. Hinweis: Gilt nur für Check Box. Bitte beachten Sie, dass Facades nur vollständige Feldnamen unterstützt und im Gegensatz zu Aspose.Pdf.Kit nicht mit Teilfeldnamen funktioniert; Zum Beispiel, wenn das Feld den vollständigen Namen \"Form.Subform.CheckBoxField\" hat, sollten Sie den vollständigen Namen angeben und nicht \"CheckBoxField\". Sie können die Property FieldNames verwenden, um vorhandene Feldnamen zu erkunden und das gewünschte Feld über seinen Teilnamen zu suchen. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); form.fillField(\"checkboxField\", true); //wie man ein Feld über seinen Teilnamen sucht: Form form = new Form(\"input.pdf\", \"output.pdf\"); for(String fieldName : form.getFieldNames()) { if (fieldName.endsWith(\"CheckBoxField\")) { System.out.println(\"Full name is: \" + fieldName); } } </pre> |
| [fillField](#fillField-java.lang.String-int-) | <p> Füllt das Radio‑Box‑Feld mit einem gültigen Indexwert gemäß einem vollständig qualifizierten Feldnamen. Vor dem Ausfüllen der Felder muss nur der Feldname bekannt sein. Der Wert kann dabei über seinen Index angegeben werden. Hinweis: Gilt nur für Radio‑Box-, Kombinations‑Box‑ und Listen‑Box‑Felder. Bitte beachten Sie, dass Facades nur vollständige Feldnamen unterstützt und im Gegensatz zu Aspose.Pdf.Kit nicht mit Teilfeldnamen funktioniert; zum Beispiel, wenn das Feld den vollständigen Namen \"Form.Subform.ListBoxField\" hat, sollten Sie den vollständigen Namen angeben und nicht \"ListBoxField\". Sie können die Eigenschaft FieldNames verwenden, um vorhandene Feldnamen zu erkunden und das gewünschte Feld über seinen Teilnamen zu suchen. </p> <hr> <pre> //1 Form form = new Form(\"PdfForm.pdf\"); form.fillField(\"listboxField\", 2); form.fillField(\"comboboxField\", 2); form.fillField(\"radiobuttonField\", 2); //2 //how to search field by its partial name: Form form = new Form(\"input.pdf\", \"output.pdf\"); for(String fieldName : form.getFieldNames()) { if (fieldName.endsWith(\"ListBoxField\")) { System.out.println(\"Full name is: \" + fieldName); } } </pre> |
| [fillField](#fillField-java.lang.String-java.lang.String-) | <p> Füllt das Feld mit einem gültigen Wert gemäß einem vollständig qualifizierten Feldnamen. Vor dem Ausfüllen der Felder müssen alle Feldnamen und die jeweiligen gültigen Werte bekannt sein. Sowohl die Feldnamen als auch die Werte sind case‑sensitive. Bitte beachten Sie, dass Facades nur vollständige Feldnamen unterstützt und im Gegensatz zu Aspose.Pdf.Kit nicht mit Teilfeldnamen funktioniert; zum Beispiel, wenn das Feld den vollständigen Namen \"Form.Subform.TextField\" hat, sollten Sie den vollständigen Namen angeben und nicht \"TextField\". Sie können die Eigenschaft FieldNames verwenden, um vorhandene Feldnamen zu erkunden und das gewünschte Feld über seinen Teilnamen zu suchen. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); form.fillField(\"FirstName\", \"John\"); form.fillField(\"LastName\", \"Smith\"); //how to search field by its partial name: Form form = new Form(\"input.pdf\", \"output.pdf\"); for(String fieldName : form.getFieldNames()) { if (fieldName.endsWith(\"TextField\")) { System.out.println(\"Full name is: \" + fieldName); } } </pre> |
| [fillField](#fillField-java.lang.String-java.lang.String:A-) | <p> Füllt ein Feld mit mehreren Auswahlen. Hinweis: nur für AcroForm‑Listen‑Box‑Feld. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(\"PdfForm.pdf\", \"Form_Updated.pdf\"); form.fillField(\"ListBox1\", new String[] { \"Three\", \"One\" }); form.save(); </pre> |
| [fillField](#fillField-java.lang.String-java.lang.String-boolean-) | Füllt das Feld mit dem angegebenen Wert. |
| [fillFields](#fillFields-java.lang.String:A-java.lang.String:A-java.io.OutputStream-) | Füllt die Textfeld‑Felder mit Textwerten und speichert das Dokument. |
| [fillImageField](#fillImageField-java.lang.String-java.io.InputStream-) | <p> Überlädt die Funktion FillImageField. Die Eingabe ist ein Bild‑Stream. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_filled.pdf\"); form.fillImageField(\"fieldName\", new FileInputStream(\"file.jpg\", FileMode.Open, FileAccess.Read)); </pre> |
| [fillImageField](#fillImageField-java.lang.String-java.lang.String-) | <p> Fügt ein Bild in das vorhandene Schaltflächenfeld als dessen Darstellung gemäß einem vollständig qualifizierten Feldnamen ein. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_filled.pdf\"); form.fillImageField(\"fieldName\", \"file.jpg\"); form.save(); </pre> |
| [flattenAllFields](#flattenAllFields--) | <p> Flacht alle Felder ab. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); form.flattenAllFields(); </pre> |
| [flattenField](#flattenField-java.lang.String-) | <p> Flacht ein angegebenes Feld mit dem vollqualifizierten Feldnamen ab. Alle anderen Felder bleiben unveränderlich. Wenn der fieldName ungültig ist, bleiben alle Felder unveränderlich. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); form.flattenField(\"textField\"); </pre> |
| [getAttachmentName](#getAttachmentName--) | Ermittelt den Namen des Anhangs, wenn das Ergebnis der Operation in HttpResponse-Objekten als Anhang gespeichert wird. |
| [getButtonOptionCurrentValue](#getButtonOptionCurrentValue-java.lang.String-) | <p> Gibt den aktuellen Wert für Optionsfelder von Optionsschaltern zurück. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); System.out.println(form.GetButtonOptionCurrentValue(\"btnField\")); </pre> |
| [getButtonOptionValues](#getButtonOptionValues-java.lang.String-) | <p> Ermittelt die Optionsfelder von Optionsschaltern und zugehörige Werte basierend auf dem Feldnamen. Diese Methode ist für Optionsschaltergruppen von Bedeutung. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); java.util.Map values = form.getButtonOptionValues(\"Color\"); System.out.println(values.get(\"White\").toString()); System.out.println(values.get(\"Black\").toString()); </pre> |
| [getButtonOptionValuesInternal](#getButtonOptionValuesInternal-java.lang.String-) | <p> Ermittelt die Optionsfelder von Optionsschaltern und zugehörige Werte basierend auf dem Feldnamen. Diese Methode ist für Optionsschaltergruppen von Bedeutung. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); Hashtable values = form.getButtonOptionValues(\"Color\"); System.out.println(values[\"White\"].toString()); System.out.println(values[\"Black\"].toString()); </pre> |
| [getContentDisposition](#getContentDisposition--) | Liest oder legt fest, wie Inhalte gespeichert werden, wenn das Ergebnis der Operation in ein HttpResponse-Objekt gespeichert wird. Mögliche Werte: inline / attachment. Standard: inline. |
| [getDestFileName](#getDestFileName--) | Ermittelt den Ziel-Dateinamen. |
| [getDestStream](#getDestStream--) | Liest oder legt den Ziel-Stream fest. |
| [getField](#getField-java.lang.String-) | <p> Ermittelt den Wert des Feldes anhand seines Feldnamens. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); System.out.println(\"Field value = \" + form.getField(\"Field1\")); </pre> |
| [getFieldFacade](#getFieldFacade-java.lang.String-) | <p> Gibt ein FormFieldFacade-Objekt zurück, das alle Darstellungsattribute enthält. </p> <hr> <pre> com.aspose.pdf.facades.Form form = new com.aspose.pdf.facades.Form(\"form.pdf\")); FormFieldFacade field = form.getFieldFacade(\"field1\"); System.out.println(\"Color of field border: \" + field.getBorderColor()); </pre> |
| [getFieldFlag](#getFieldFlag-java.lang.String-) | <p> Gibt die Flags des Feldes zurück. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); if (form.getFieldFlag(\"textField\") == ProptyFlag.ReadOnly) { System.out.println(\"Field is read-only\"); } </pre> |
| [getFieldLimit](#getFieldLimit-java.lang.String-) | <p> Ermittelt die Begrenzung des Textfeldes. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); System.out.println(form.getFieldLimit(\"textfieldBox\")); </pre> |
| [getFieldNames](#getFieldNames--) | <p> Ermittelt die Liste der Feldnamen im Formular. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); String[] fields = form.getFieldNames(); for(String field : fields) { System.out.println(field); } </pre> |
| [getFieldType](#getFieldType-java.lang.String-) | <p> Gibt den Typ des Feldes zurück. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); if (form.getFieldType(\"textField\") == FieldType.Text) { System.out.println(\"Type of field is text\"); } </pre> |
| [getFormSubmitButtonNames](#getFormSubmitButtonNames--) | <p> Ermittelt alle Namen der Formular-Submit-Schaltflächen. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); String[] submits = form.getFormSubmitButtonNames(); for(String btn : submits) { System.out.println(btn); } </pre> |
| [getFullFieldName](#getFullFieldName-java.lang.String-) | <p> Ermittelt den vollständigen Feldnamen anhand seines kurzen Feldnamens. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); System.out.println(\"Full field name is : \" + form.getFullFieldName(\"textField\")); </pre> |
| [getImportResult](#getImportResult--) | Ergebnis der letzten Importoperation. Array von Objekten, die das Ergebnis des Imports für jedes Feld beschreiben. |
| [getRichText](#getRichText-java.lang.String-) | <p> Rufen Sie den Wert eines Rich Text Feldes ab, einschließlich der Formatierungsinformationen jedes Zeichens. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); System.out.println(form.getRichText(\"txtDescriptionRTF\")); </pre> |
| [getSaveOptions](#getSaveOptions--) | Liest oder legt die Speicheroptionen fest, wenn das Ergebnis als HttpResponse gespeichert wird. Standardwert: PdfSaveOptions. |
| [getSrcFileName](#getSrcFileName--) | <p> Liest den Quelldateinamen. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setSrcFileName(\"file.pdf\"); </pre> |
| [getSrcStream](#getSrcStream--) | Ermittelt den Quell-Stream. |
| [getSubmitFlags](#getSubmitFlags-java.lang.String-) | <p> Returns the submit button's submission flags </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println( ( form.getSubmitFlags("btnSubmit") \ | SubmitFormFlag.Xfdf != 0) ? " XFDF" : " "); /// System.out.println( ( form.getSubmitFlags("btnSubmit") \ | SubmitFormFlag.Fdf != 0) ? " FDF" : " "); System.out.println( ( form.getSubmitFlags("btnSubmit") \ | SubmitFormFlag.Pdf != 0) ? \" PDF\" : \" \" ); </pre> |
| [importFdf](#importFdf-java.io.InputStream-) | <p> Importiert den Inhalt der Felder aus der fdf‑Datei und legt ihn in das neue PDF. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_imported.pdf\"); form.importFdf(new FileInputStream(\"data.fdf\")); form.save(); </pre> |
| [importXfdf](#importXfdf-java.io.InputStream-) | <p> Importiert den Inhalt der Felder aus der xfdf(xml)-Datei und legt ihn in das neue PDF. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"Form_ImportXfdf.pdf\"); InputStream fs = new FileInputStream(\"export_old.xfdf\"); form.importXfdf(fs); fs.close(); form.save(); </pre> |
| [importXml](#importXml-java.io.InputStream-) | <p> Importiert den Inhalt der Felder aus der xml‑Datei und legt ihn in das neue PDF. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); InputStream fs = new FileInputStream(\"import.xml\"); form.importXml(fs); form.save(\"Form_Imported.pdf\"); </pre> |
| [importXml](#importXml-java.io.InputStream-boolean-) | Importiert den Inhalt der Felder aus der xml‑Datei und legt ihn in das neue PDF. |
| [importXml](#importXml-java.lang.String-) | <p> Importiert den Inhalt der Felder aus der xml‑Datei und legt ihn in das neue PDF. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); form.importXml(\"import.xml\"); form.save( \"Form_Imported.pdf\"); </pre> |
| [isRequiredField](#isRequiredField-java.lang.String-) | Bestimmt, ob das Feld erforderlich ist oder nicht. |
| [renameField](#renameField-java.lang.String-java.lang.String-) | <p> Benennt ein Feld um. Sowohl AcroForm‑Feld als auch XFA‑Feld sind zulässig. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfFormUpdated.pdf\"); form.renameField(\"field\", \"field1\"); form.save(); </pre> |
| [save](#save--) | <p> Speichert den Wert der ausgefüllten Felder und schließt das geöffnete Pdf-Dokument. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_Changed.pdf\"); form.fillField(\"textField\", \"new value\"); form.save(); </pre> |
| [save](#save-java.io.OutputStream-) | <p> Speichert den Wert der ausgefüllten Felder und schließt das geöffnete Pdf-Dokument. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_Changed.pdf\"); form.fillField(\"textField\", \"new value\"); form.save(); </pre> |
| [save](#save-java.lang.String-) | <p> Speichert den Wert der ausgefüllten Felder und schließt das geöffnete Pdf-Dokument. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_Changed.pdf\"); form.fillField(\"textField\", \"new value\"); form.save(); </pre> |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | Legt den Namen des Anhangs fest, wenn das Ergebnis der Operation in HttpResponse-Objekten als Anhang gespeichert wird. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | Legt fest, wie der Inhalt gespeichert wird, wenn das Ergebnis der Operation in ein HttpResponse-Objekt gespeichert wird. Mögliche Werte: inline / attachment. Standard: inline. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | Legt das PDF‑Dateiformat fest. Die Ergebnisdatei wird im angegebenen Dateiformat gespeichert. Wenn diese Eigenschaft nicht angegeben ist, wird die Datei im Standard‑PDF‑Format ohne Konvertierung gespeichert. |
| [setDestFileName](#setDestFileName-java.lang.String-) | <p> Legt den Zieldateinamen fest. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setDestFileName(\"file.pdf\"); </pre> |
| [setDestStream](#setDestStream-java.io.OutputStream-) | <p> Liest den Ziel‑Stream. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setDestStream (new FileInputStream(\"file.pdf\")); </pre> |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Liest oder legt die Speicheroptionen fest, wenn das Ergebnis als HttpResponse gespeichert wird. Standardwert: PdfSaveOptions. |
| [setSrcFileName](#setSrcFileName-java.lang.String-) | Legt den Quelldateinamen fest. |
| [setSrcStream](#setSrcStream-java.io.InputStream-) | <p> Liest den Quell‑Stream. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setSrcStream (new FileInputStream(\"source.pdf\"))); </pre> |
| [setXfaData](#setXfaData-java.io.InputStream-) | Ersetzt XFA‑Daten durch das angegebene Datenpaket. Das Datenpaket kann mit ExtractXfaData extrahiert werden. |

### Form {#Form--}
```
public Form()
```

<p> Konstruktor von Form ohne Parameter. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-com.aspose.pdf.IDocument-}
<p> Konstruktor von Form ohne Parameter. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-com.aspose.pdf.IDocument-java.io.OutputStream-}
<p> Konstruktor von Form ohne Parameter. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-com.aspose.pdf.IDocument-java.lang.String-}
<p> Konstruktor von Form ohne Parameter. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-java.io.InputStream-}
<p> Konstruktor von Form ohne Parameter. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-java.io.InputStream-java.io.OutputStream-}
<p> Konstruktor von Form ohne Parameter. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-java.io.InputStream-java.lang.String-}
<p> Konstruktor von Form ohne Parameter. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-java.lang.String-}
<p> Konstruktor von Form ohne Parameter. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-java.lang.String-java.io.OutputStream-}
<p> Konstruktor von Form ohne Parameter. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-java.lang.String-java.lang.String-}
<p> Konstruktor von Form ohne Parameter. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### bindPdf {#bindPdf-java.io.InputStream-java.lang.String-}
Initialisiert die Fassade.

### bindPdf {#bindPdf-java.lang.String-java.lang.String-}
Initialisiert die Fassade.

### close {#close--}
```
public void close()
```

Schließt geöffnete Dateien, ohne Änderungen vorzunehmen.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Schließt alle geöffneten Ressourcen. Diese Methode ist veraltet, verwenden Sie stattdessen close().

### exportFdf {#exportFdf-java.io.OutputStream-}
<p> Exportiert den Inhalt der Felder des PDFs in den fdf‑Stream. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); OutputStream stream = new FileOutputStream(\"export.fdf\"); form.exportFdf(stream); stream.close(); </pre>

### exportXfdf {#exportXfdf-java.io.OutputStream-}
<p> Exportiert den Inhalt der Felder des PDFs in den xml‑Stream. Der Wert des Button‑Feldes wird nicht exportiert. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); FileInputStream fs = new FileInputStream(\"export.xfdf\", FileMode.Create, FileAccess.Write); form.exportXfdf(fs); fs.close(); </pre>

### exportXml {#exportXml-java.io.OutputStream-}
<p> Exportiert den Inhalt der Felder des PDFs in den xml‑Stream. Der Wert des Button‑Feldes wird nicht exportiert. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\")); OutputStream fs = new FileOutputStream(\"export.xml\"); form.exportXml(fs); fs.close(); </pre>

### extractXfaData {#extractXfaData-java.io.OutputStream-}
Extrahiert XFA-Datenpaket

### fillBarcodeField {#fillBarcodeField-java.lang.String-java.lang.String-}
<p> Füllt ein Barcode‑Feld gemäß seinem vollqualifizierten Feldnamen. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); form.fillBarcodeField(\"textField\", \"42207252\"); </pre>

### fillField {#fillField-java.lang.String-boolean-}
<p> Füllt das Kontrollkästchenfeld mit einem booleschen Wert. Hinweis: Gilt nur für Check Box. Bitte beachten Sie, dass Facades nur vollständige Feldnamen unterstützt und im Gegensatz zu Aspose.Pdf.Kit nicht mit Teilfeldnamen funktioniert; Zum Beispiel, wenn das Feld den vollständigen Namen \"Form.Subform.CheckBoxField\" hat, sollten Sie den vollständigen Namen angeben und nicht \"CheckBoxField\". Sie können die Property FieldNames verwenden, um vorhandene Feldnamen zu erkunden und das gewünschte Feld über seinen Teilnamen zu suchen. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); form.fillField(\"checkboxField\", true); //wie man ein Feld über seinen Teilnamen sucht: Form form = new Form(\"input.pdf\", \"output.pdf\"); for(String fieldName : form.getFieldNames()) { if (fieldName.endsWith(\"CheckBoxField\")) { System.out.println(\"Full name is: \" + fieldName); } } </pre>

### fillField {#fillField-java.lang.String-int-}
<p> Füllt das Radio‑Box‑Feld mit einem gültigen Indexwert gemäß einem vollständig qualifizierten Feldnamen. Vor dem Ausfüllen der Felder muss nur der Feldname bekannt sein. Der Wert kann dabei über seinen Index angegeben werden. Hinweis: Gilt nur für Radio‑Box-, Kombinations‑Box‑ und Listen‑Box‑Felder. Bitte beachten Sie, dass Facades nur vollständige Feldnamen unterstützt und im Gegensatz zu Aspose.Pdf.Kit nicht mit Teilfeldnamen funktioniert; zum Beispiel, wenn das Feld den vollständigen Namen \"Form.Subform.ListBoxField\" hat, sollten Sie den vollständigen Namen angeben und nicht \"ListBoxField\". Sie können die Eigenschaft FieldNames verwenden, um vorhandene Feldnamen zu erkunden und das gewünschte Feld über seinen Teilnamen zu suchen. </p> <hr> <pre> //1 Form form = new Form(\"PdfForm.pdf\"); form.fillField(\"listboxField\", 2); form.fillField(\"comboboxField\", 2); form.fillField(\"radiobuttonField\", 2); //2 //how to search field by its partial name: Form form = new Form(\"input.pdf\", \"output.pdf\"); for(String fieldName : form.getFieldNames()) { if (fieldName.endsWith(\"ListBoxField\")) { System.out.println(\"Full name is: \" + fieldName); } } </pre>

### fillField {#fillField-java.lang.String-java.lang.String-}
<p> Füllt das Feld mit einem gültigen Wert gemäß einem vollständig qualifizierten Feldnamen. Vor dem Ausfüllen der Felder müssen alle Feldnamen und die jeweiligen gültigen Werte bekannt sein. Sowohl die Feldnamen als auch die Werte sind case‑sensitive. Bitte beachten Sie, dass Facades nur vollständige Feldnamen unterstützt und im Gegensatz zu Aspose.Pdf.Kit nicht mit Teilfeldnamen funktioniert; zum Beispiel, wenn das Feld den vollständigen Namen \"Form.Subform.TextField\" hat, sollten Sie den vollständigen Namen angeben und nicht \"TextField\". Sie können die Eigenschaft FieldNames verwenden, um vorhandene Feldnamen zu erkunden und das gewünschte Feld über seinen Teilnamen zu suchen. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); form.fillField(\"FirstName\", \"John\"); form.fillField(\"LastName\", \"Smith\"); //how to search field by its partial name: Form form = new Form(\"input.pdf\", \"output.pdf\"); for(String fieldName : form.getFieldNames()) { if (fieldName.endsWith(\"TextField\")) { System.out.println(\"Full name is: \" + fieldName); } } </pre>

### fillField {#fillField-java.lang.String-java.lang.String:A-}
<p> Füllt ein Feld mit mehreren Auswahlen. Hinweis: nur für AcroForm‑Listen‑Box‑Feld. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(\"PdfForm.pdf\", \"Form_Updated.pdf\"); form.fillField(\"ListBox1\", new String[] { \"Three\", \"One\" }); form.save(); </pre>

### fillField {#fillField-java.lang.String-java.lang.String-boolean-}
Füllt das Feld mit dem angegebenen Wert.

### fillFields {#fillFields-java.lang.String:A-java.lang.String:A-java.io.OutputStream-}
Füllt die Textfeld‑Felder mit Textwerten und speichert das Dokument.

### fillImageField {#fillImageField-java.lang.String-java.io.InputStream-}
<p> Überlädt die Funktion FillImageField. Die Eingabe ist ein Bild‑Stream. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_filled.pdf\"); form.fillImageField(\"fieldName\", new FileInputStream(\"file.jpg\", FileMode.Open, FileAccess.Read)); </pre>

### fillImageField {#fillImageField-java.lang.String-java.lang.String-}
<p> Fügt ein Bild in das vorhandene Schaltflächenfeld als dessen Darstellung gemäß einem vollständig qualifizierten Feldnamen ein. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_filled.pdf\"); form.fillImageField(\"fieldName\", \"file.jpg\"); form.save(); </pre>

### flattenAllFields {#flattenAllFields--}
```
public void flattenAllFields()
```

<p> Flacht alle Felder ab. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); form.flattenAllFields(); </pre>

### flattenField {#flattenField-java.lang.String-}
<p> Flacht ein angegebenes Feld mit dem vollqualifizierten Feldnamen ab. Alle anderen Felder bleiben unveränderlich. Wenn der fieldName ungültig ist, bleiben alle Felder unveränderlich. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); form.flattenField(\"textField\"); </pre>

### getAttachmentName {#getAttachmentName--}
```
public String getAttachmentName()
```

Ermittelt den Namen des Anhangs, wenn das Ergebnis der Operation in HttpResponse-Objekten als Anhang gespeichert wird.

**Returns:**
String‑Objekt

### getButtonOptionCurrentValue {#getButtonOptionCurrentValue-java.lang.String-}
<p> Gibt den aktuellen Wert für Optionsfelder von Optionsschaltern zurück. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); System.out.println(form.GetButtonOptionCurrentValue(\"btnField\")); </pre>

### getButtonOptionValues {#getButtonOptionValues-java.lang.String-}
<p> Ermittelt die Optionsfelder von Optionsschaltern und zugehörige Werte basierend auf dem Feldnamen. Diese Methode ist für Optionsschaltergruppen von Bedeutung. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); java.util.Map values = form.getButtonOptionValues(\"Color\"); System.out.println(values.get(\"White\").toString()); System.out.println(values.get(\"Black\").toString()); </pre>

### getButtonOptionValuesInternal {#getButtonOptionValuesInternal-java.lang.String-}
<p> Ermittelt die Optionsfelder von Optionsschaltern und zugehörige Werte basierend auf dem Feldnamen. Diese Methode ist für Optionsschaltergruppen von Bedeutung. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); Hashtable values = form.getButtonOptionValues(\"Color\"); System.out.println(values[\"White\"].toString()); System.out.println(values[\"Black\"].toString()); </pre>

### getContentDisposition {#getContentDisposition--}
```
public ContentDisposition getContentDisposition()
```

Liest oder legt fest, wie Inhalte gespeichert werden, wenn das Ergebnis der Operation in ein HttpResponse-Objekt gespeichert wird. Mögliche Werte: inline / attachment. Standard: inline.

**Returns:**
ContentDisposition-Element @see ContentDisposition

### getDestFileName {#getDestFileName--}
```
@Deprecated public String getDestFileName()
```

Ermittelt den Ziel-Dateinamen.

**Returns:**
String‑Objekt

### getDestStream {#getDestStream--}
```
@Deprecated public OutputStream getDestStream()
```

Liest oder legt den Ziel-Stream fest.

**Returns:**
OutputStream-Objekt

### getField {#getField-java.lang.String-}
<p> Ermittelt den Wert des Feldes anhand seines Feldnamens. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); System.out.println(\"Field value = \" + form.getField(\"Field1\")); </pre>

### getFieldFacade {#getFieldFacade-java.lang.String-}
<p> Gibt ein FormFieldFacade-Objekt zurück, das alle Darstellungsattribute enthält. </p> <hr> <pre> com.aspose.pdf.facades.Form form = new com.aspose.pdf.facades.Form(\"form.pdf\")); FormFieldFacade field = form.getFieldFacade(\"field1\"); System.out.println(\"Color of field border: \" + field.getBorderColor()); </pre>

### getFieldFlag {#getFieldFlag-java.lang.String-}
<p> Gibt die Flags des Feldes zurück. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); if (form.getFieldFlag(\"textField\") == ProptyFlag.ReadOnly) { System.out.println(\"Field is read-only\"); } </pre>

### getFieldLimit {#getFieldLimit-java.lang.String-}
<p> Ermittelt die Begrenzung des Textfeldes. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); System.out.println(form.getFieldLimit(\"textfieldBox\")); </pre>

### getFieldNames {#getFieldNames--}
```
public String [] getFieldNames()
```

<p> Ermittelt die Liste der Feldnamen im Formular. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); String[] fields = form.getFieldNames(); for(String field : fields) { System.out.println(field); } </pre>

**Returns:**
String[]-Objekt

### getFieldType {#getFieldType-java.lang.String-}
<p> Gibt den Typ des Feldes zurück. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); if (form.getFieldType(\"textField\") == FieldType.Text) { System.out.println(\"Type of field is text\"); } </pre>

### getFormSubmitButtonNames {#getFormSubmitButtonNames--}
```
public String [] getFormSubmitButtonNames()
```

<p> Ermittelt alle Namen der Formular-Submit-Schaltflächen. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); String[] submits = form.getFormSubmitButtonNames(); for(String btn : submits) { System.out.println(btn); } </pre>

**Returns:**
String[]-Objekt

### getFullFieldName {#getFullFieldName-java.lang.String-}
<p> Ermittelt den vollständigen Feldnamen anhand seines kurzen Feldnamens. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); System.out.println(\"Full field name is : \" + form.getFullFieldName(\"textField\")); </pre>

### getImportResult {#getImportResult--}
```
public com.aspose.pdf.facades.AForm.FormImportResult[] getImportResult()
```

Ergebnis der letzten Importoperation. Array von Objekten, die das Ergebnis des Imports für jedes Feld beschreiben.

**Returns:**
FormImportResult[] Array

### getRichText {#getRichText-java.lang.String-}
<p> Rufen Sie den Wert eines Rich Text Feldes ab, einschließlich der Formatierungsinformationen jedes Zeichens. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); System.out.println(form.getRichText(\"txtDescriptionRTF\")); </pre>

### getSaveOptions {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```

Liest oder legt die Speicheroptionen fest, wenn das Ergebnis als HttpResponse gespeichert wird. Standardwert: PdfSaveOptions.

**Returns:**
SaveOptions-Objekt

### getSrcFileName {#getSrcFileName--}
```
@Deprecated public String getSrcFileName()
```

<p> Liest den Quelldateinamen. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setSrcFileName(\"file.pdf\"); </pre>

**Returns:**
String‑Objekt

### getSrcStream {#getSrcStream--}
```
public InputStream getSrcStream()
```

Ermittelt den Quell-Stream.

**Returns:**
InputStream‑Objekt

### getSubmitFlags {#getSubmitFlags-java.lang.String-}
<p> Gibt die Übermittlungsflags des Absende‑Buttons zurück </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); System.out.println( ( form.getSubmitFlags(\"btnSubmit\") | SubmitFormFlag.Xfdf != 0) ? \" XFDF\" : \" \" ); /// System.out.println( ( form.getSubmitFlags(\"btnSubmit\") | SubmitFormFlag.Fdf != 0) ? \" FDF\" : \" \" ); System.out.println( ( form.getSubmitFlags(\"btnSubmit\") | SubmitFormFlag.Pdf != 0) ? \" PDF\" : \" \" ); </pre>

### importFdf {#importFdf-java.io.InputStream-}
<p> Importiert den Inhalt der Felder aus der fdf‑Datei und legt ihn in das neue PDF. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_imported.pdf\"); form.importFdf(new FileInputStream(\"data.fdf\")); form.save(); </pre>

### importXfdf {#importXfdf-java.io.InputStream-}
<p> Importiert den Inhalt der Felder aus der xfdf(xml)-Datei und legt ihn in das neue PDF. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"Form_ImportXfdf.pdf\"); InputStream fs = new FileInputStream(\"export_old.xfdf\"); form.importXfdf(fs); fs.close(); form.save(); </pre>

### importXml {#importXml-java.io.InputStream-}
<p> Importiert den Inhalt der Felder aus der xml‑Datei und legt ihn in das neue PDF. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); InputStream fs = new FileInputStream(\"import.xml\"); form.importXml(fs); form.save(\"Form_Imported.pdf\"); </pre>

### importXml {#importXml-java.io.InputStream-boolean-}
Importiert den Inhalt der Felder aus der xml‑Datei und legt ihn in das neue PDF.

### importXml {#importXml-java.lang.String-}
<p> Importiert den Inhalt der Felder aus der xml‑Datei und legt ihn in das neue PDF. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); form.importXml(\"import.xml\"); form.save( \"Form_Imported.pdf\"); </pre>

### isRequiredField {#isRequiredField-java.lang.String-}
Bestimmt, ob das Feld erforderlich ist oder nicht.

### renameField {#renameField-java.lang.String-java.lang.String-}
<p> Benennt ein Feld um. Sowohl AcroForm‑Feld als auch XFA‑Feld sind zulässig. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfFormUpdated.pdf\"); form.renameField(\"field\", \"field1\"); form.save(); </pre>

### save {#save--}
```
public void save()
```

<p> Speichert den Wert der ausgefüllten Felder und schließt das geöffnete Pdf-Dokument. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_Changed.pdf\"); form.fillField(\"textField\", \"new value\"); form.save(); </pre>

### save {#save-java.io.OutputStream-}
<p> Speichert den Wert der ausgefüllten Felder und schließt das geöffnete Pdf-Dokument. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_Changed.pdf\"); form.fillField(\"textField\", \"new value\"); form.save(); </pre>

### save {#save-java.lang.String-}
<p> Speichert den Wert der ausgefüllten Felder und schließt das geöffnete Pdf-Dokument. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_Changed.pdf\"); form.fillField(\"textField\", \"new value\"); form.save(); </pre>

### setAttachmentName {#setAttachmentName-java.lang.String-}
Legt den Namen des Anhangs fest, wenn das Ergebnis der Operation in HttpResponse-Objekten als Anhang gespeichert wird.

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
Legt fest, wie der Inhalt gespeichert wird, wenn das Ergebnis der Operation in ein HttpResponse-Objekt gespeichert wird. Mögliche Werte: inline / attachment. Standard: inline.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Legt das PDF‑Dateiformat fest. Die Ergebnisdatei wird im angegebenen Dateiformat gespeichert. Wenn diese Eigenschaft nicht angegeben ist, wird die Datei im Standard‑PDF‑Format ohne Konvertierung gespeichert.

### setDestFileName {#setDestFileName-java.lang.String-}
<p> Legt den Zieldateinamen fest. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setDestFileName(\"file.pdf\"); </pre>

### setDestStream {#setDestStream-java.io.OutputStream-}
<p> Liest den Ziel‑Stream. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setDestStream (new FileInputStream(\"file.pdf\")); </pre>

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Liest oder legt die Speicheroptionen fest, wenn das Ergebnis als HttpResponse gespeichert wird. Standardwert: PdfSaveOptions.

### setSrcFileName {#setSrcFileName-java.lang.String-}
Legt den Quelldateinamen fest.

### setSrcStream {#setSrcStream-java.io.InputStream-}
<p> Liest den Quell‑Stream. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setSrcStream (new FileInputStream(\"source.pdf\"))); </pre>

### setXfaData {#setXfaData-java.io.InputStream-}
Ersetzt XFA‑Daten durch das angegebene Datenpaket. Das Datenpaket kann mit ExtractXfaData extrahiert werden.
