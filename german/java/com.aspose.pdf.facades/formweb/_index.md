---
title: "FormWeb"
linktitle: "FormWeb"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Darstellung der Acro form Interface."
type: docs
weight: 230
url: /de/java/com.aspose.pdf.facades/formweb/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.FormWeb, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.FormWeb, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.FormWeb

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, IForm, ISaveableFacade, Closeable, AutoCloseable

```
public final class FormWeb extends SaveableFacade implements IForm
```

Darstellung der Acro form Interface.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [FormWeb](#FormWeb--) | <p> Konstruktor von FormWeb ohne Parameter. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre> |
| [FormWeb](#FormWeb-com.aspose.pdf.IDocument-) | <p> Konstruktor von FormWeb ohne Parameter. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre> |
| [FormWeb](#FormWeb-com.aspose.pdf.IDocument-java.io.OutputStream-) | <p> Konstruktor von FormWeb ohne Parameter. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre> |
| [FormWeb](#FormWeb-com.aspose.pdf.IDocument-java.lang.String-) | <p> Konstruktor von FormWeb ohne Parameter. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre> |
| [FormWeb](#FormWeb-java.io.InputStream-) | <p> Konstruktor von FormWeb ohne Parameter. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre> |
| [FormWeb](#FormWeb-java.io.InputStream-javax.servlet.http.HttpServletResponse-) | <p> Konstruktor von FormWeb ohne Parameter. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre> |
| [FormWeb](#FormWeb-java.io.InputStream-java.io.OutputStream-) | <p> Konstruktor von FormWeb ohne Parameter. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre> |
| [FormWeb](#FormWeb-java.io.InputStream-java.lang.String-) | <p> Konstruktor von FormWeb ohne Parameter. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre> |
| [FormWeb](#FormWeb-java.lang.String-) | <p> Konstruktor von FormWeb ohne Parameter. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre> |
| [FormWeb](#FormWeb-java.lang.String-javax.servlet.http.HttpServletResponse-) | <p> Konstruktor von FormWeb ohne Parameter. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre> |
| [FormWeb](#FormWeb-java.lang.String-java.io.OutputStream-) | <p> Konstruktor von FormWeb ohne Parameter. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre> |
| [FormWeb](#FormWeb-java.lang.String-java.lang.String-) | <p> Konstruktor von FormWeb ohne Parameter. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre> |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [bindPdf](#bindPdf-java.io.InputStream-java.lang.String-) | Initialisiert die Fassade. |
| [bindPdf](#bindPdf-java.lang.String-java.lang.String-) | Initialisiert die Fassade. |
| [close](#close--) | Schließt alle geöffneten Ressourcen, die von diesem Dokument verwendet werden. |
| [dispose](#dispose--) | Veraltet. |
| [exportFdf](#exportFdf-java.io.OutputStream-) | Exportiert den Inhalt der Felder des PDFs in den FDF-Stream. |
| [exportXfdf](#exportXfdf-java.io.OutputStream-) | Exportiert den Inhalt der Felder des PDFs in den XML-Stream. |
| [exportXml](#exportXml-java.io.OutputStream-) | Exportiert den Inhalt der Felder des PDFs in den XML-Stream. |
| [extractXfaData](#extractXfaData-java.io.OutputStream-) | Extrahiert XFA-Datenpaket |
| [fillBarcodeField](#fillBarcodeField-java.lang.String-java.lang.String-) | Füllt ein Barcode-Feld gemäß seinem vollqualifizierten Feldnamen. |
| [fillField](#fillField-java.lang.String-boolean-) | Füllt das Kontrollkästchenfeld mit einem booleschen Wert. |
| [fillField](#fillField-java.lang.String-int-) | Füllt das Optionsfeld mit einem gültigen Indexwert gemäß einem vollqualifizierten Feldnamen. |
| [fillField](#fillField-java.lang.String-java.lang.String-) | Füllt das Feld mit einem gültigen Wert gemäß einem vollqualifizierten Feldnamen. |
| [fillField](#fillField-java.lang.String-java.lang.String:A-) | Füllt ein Feld mit mehreren Auswahlen. Hinweis: nur für AcroForm-Listenfeld. |
| [fillField](#fillField-java.lang.String-java.lang.String-boolean-) | Füllt das Feld mit dem angegebenen Wert. |
| [fillFields](#fillFields-java.lang.String:A-java.lang.String:A-java.io.OutputStream-) | Füllt die Textfeld‑Felder mit Textwerten und speichert das Dokument. |
| [fillImageField](#fillImageField-java.lang.String-java.io.InputStream-) | Überlädt die Funktion von FillImageField. |
| [fillImageField](#fillImageField-java.lang.String-java.lang.String-) | Fügt ein Bild in das vorhandene Schaltflächenfeld als dessen Darstellung gemäß seinem vollqualifizierten Feldnamen ein. |
| [flattenAllFields](#flattenAllFields--) | Flacht alle Felder ab. |
| [flattenField](#flattenField-java.lang.String-) | Flacht ein angegebenes Feld mit dem vollqualifizierten Feldnamen ab. |
| [getAttachmentName](#getAttachmentName--) | Ermittelt den Namen des Anhangs, wenn das Ergebnis der Operation in HttpResponse-Objekten als Anhang gespeichert wird. |
| [getButtonOptionCurrentValue](#getButtonOptionCurrentValue-java.lang.String-) | Gibt den aktuellen Wert für Optionsfelder von Optionsschaltern zurück. |
| [getButtonOptionValues](#getButtonOptionValues-java.lang.String-) | Ermittelt die Optionsfelder von Optionsschaltern und zugehörige Werte basierend auf dem Feldnamen. |
| [getButtonOptionValuesInternal](#getButtonOptionValuesInternal-java.lang.String-) | Ermittelt die Optionsfelder von Optionsschaltern und zugehörige Werte basierend auf dem Feldnamen. |
| [getContentDisposition](#getContentDisposition--) | Der angezeigte Inhalt wird gespeichert, wenn das Ergebnis der Operation in ein HttpResponse-Objekt gespeichert wird. |
| [getDestFileName](#getDestFileName--) | Veraltet. |
| [getDestStream](#getDestStream--) | Veraltet. |
| [getField](#getField-java.lang.String-) | Ermittelt den Wert des Feldes gemäß seinem Feldnamen. |
| [getFieldFacade](#getFieldFacade-java.lang.String-) | Gibt das FrogmFieldFacade-Objekt zurück, das alle Darstellungsattribute enthält. |
| [getFieldFlag](#getFieldFlag-java.lang.String-) | Gibt die Flags des Feldes zurück. |
| [getFieldLimit](#getFieldLimit-java.lang.String-) | Ermittelt die Beschränkung des Textfeldes. |
| [getFieldNames](#getFieldNames--) | Ermittelt die Liste der Feldnamen im Formular. |
| [getFieldType](#getFieldType-java.lang.String-) | Gibt den Typ des Feldes zurück. |
| [getFormSubmitButtonNames](#getFormSubmitButtonNames--) | Ermittelt alle Namen der Formular-Submit-Schaltflächen. |
| [getFullFieldName](#getFullFieldName-java.lang.String-) | Ermittelt den vollständigen Feldnamen gemäß seinem kurzen Feldnamen. |
| [getImportResult](#getImportResult--) | Ergebnis der letzten Importoperation. |
| [getResponse](#getResponse--) | Liest oder setzt das Response-Objekt, in dem das Ergebnis der Operation gespeichert wird. |
| [getRichText](#getRichText-java.lang.String-) | Ruft den Wert eines Rich-Text-Feldes ab, einschließlich der Formatierungsinformationen jedes Zeichens. |
| [getSaveOptions](#getSaveOptions--) | Liest oder setzt die Speicheroptionen, wenn das Ergebnis als HttpResponse gespeichert wird. |
| [getSrcFileName](#getSrcFileName--) | Veraltet. |
| [getSrcStream](#getSrcStream--) | Ermittelt den Quell-Stream. |
| [getSubmitFlags](#getSubmitFlags-java.lang.String-) | Gibt die Übermittlungsflags des Submit-Buttons zurück |
| [importFdf](#importFdf-java.io.InputStream-) | Importiert den Inhalt der Felder aus der fdf-Datei und legt ihn in das neue PDF. |
| [importXfdf](#importXfdf-java.io.InputStream-) | Importiert den Inhalt der Felder aus der xfdf(xml)-Datei und legt ihn in das neue PDF. |
| [importXml](#importXml-java.io.InputStream-) | Importiert den Inhalt der Felder aus der xml‑Datei und legt ihn in das neue PDF. |
| [importXml](#importXml-java.io.InputStream-boolean-) | Importiert den Inhalt der Felder aus der xml‑Datei und legt ihn in das neue PDF. |
| [importXml](#importXml-java.lang.String-) | Importiert den Inhalt der Felder aus der xml‑Datei und legt ihn in das neue PDF. |
| [isRequiredField](#isRequiredField-java.lang.String-) | Bestimmt, ob das Feld erforderlich ist oder nicht. |
| [renameField](#renameField-java.lang.String-java.lang.String-) | Benennt ein Feld um. |
| [save](#save--) | <p> Speichert den Wert der ausgefüllten Felder und schließt das geöffnete Pdf-Dokument. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_Changed.pdf\"); form.fillField(\"textField\", \"new value\"); form.save(); </pre> |
| [save](#save-java.io.OutputStream-) | <p> Speichert den Wert der ausgefüllten Felder und schließt das geöffnete Pdf-Dokument. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_Changed.pdf\"); form.fillField(\"textField\", \"new value\"); form.save(); </pre> |
| [save](#save-java.lang.String-) | <p> Speichert den Wert der ausgefüllten Felder und schließt das geöffnete Pdf-Dokument. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_Changed.pdf\"); form.fillField(\"textField\", \"new value\"); form.save(); </pre> |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | Legt den Namen des Anhangs fest, wenn das Ergebnis der Operation in HttpResponse-Objekten als Anhang gespeichert wird. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | Legt fest, wie Inhalte gespeichert werden, wenn das Ergebnis der Operation in ein HttpResponse-Objekt gespeichert wird. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | Legt das PDF-Dateiformat fest. |
| [setDestFileName](#setDestFileName-java.lang.String-) | Veraltet. |
| [setDestStream](#setDestStream-java.io.OutputStream-) | Veraltet. |
| [setResponse](#setResponse-javax.servlet.http.HttpServletResponse-) | Liest oder setzt das Response-Objekt, in dem das Ergebnis der Operation gespeichert wird. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Liest oder setzt die Speicheroptionen, wenn das Ergebnis als HttpResponse gespeichert wird. |
| [setSrcFileName](#setSrcFileName-java.lang.String-) | Veraltet. |
| [setSrcStream](#setSrcStream-java.io.InputStream-) | Ermittelt den Quell-Stream. |
| [setXfaData](#setXfaData-java.io.InputStream-) | Ersetzt XFA-Daten durch das angegebene Datenpaket. |

### FormWeb {#FormWeb--}
```
public FormWeb()
```

<p> Konstruktor von FormWeb ohne Parameter. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre>

### FormWeb {#FormWeb-com.aspose.pdf.IDocument-}
<p> Konstruktor von FormWeb ohne Parameter. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre>

### FormWeb {#FormWeb-com.aspose.pdf.IDocument-java.io.OutputStream-}
<p> Konstruktor von FormWeb ohne Parameter. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre>

### FormWeb {#FormWeb-com.aspose.pdf.IDocument-java.lang.String-}
<p> Konstruktor von FormWeb ohne Parameter. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre>

### FormWeb {#FormWeb-java.io.InputStream-}
<p> Konstruktor von FormWeb ohne Parameter. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre>

### FormWeb {#FormWeb-java.io.InputStream-javax.servlet.http.HttpServletResponse-}
<p> Konstruktor von FormWeb ohne Parameter. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre>

### FormWeb {#FormWeb-java.io.InputStream-java.io.OutputStream-}
<p> Konstruktor von FormWeb ohne Parameter. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre>

### FormWeb {#FormWeb-java.io.InputStream-java.lang.String-}
<p> Konstruktor von FormWeb ohne Parameter. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre>

### FormWeb {#FormWeb-java.lang.String-}
<p> Konstruktor von FormWeb ohne Parameter. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre>

### FormWeb {#FormWeb-java.lang.String-javax.servlet.http.HttpServletResponse-}
<p> Konstruktor von FormWeb ohne Parameter. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre>

### FormWeb {#FormWeb-java.lang.String-java.io.OutputStream-}
<p> Konstruktor von FormWeb ohne Parameter. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre>

### FormWeb {#FormWeb-java.lang.String-java.lang.String-}
<p> Konstruktor von FormWeb ohne Parameter. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre>

### bindPdf {#bindPdf-java.io.InputStream-java.lang.String-}
Initialisiert die Fassade.

### bindPdf {#bindPdf-java.lang.String-java.lang.String-}
Initialisiert die Fassade.

### close {#close--}
```
public void close()
```

Schließt alle geöffneten Ressourcen, die von diesem Dokument verwendet werden.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Veraltet.

### exportFdf {#exportFdf-java.io.OutputStream-}
Exportiert den Inhalt der Felder des PDFs in den FDF-Stream.

### exportXfdf {#exportXfdf-java.io.OutputStream-}
Exportiert den Inhalt der Felder des PDFs in den XML-Stream.

### exportXml {#exportXml-java.io.OutputStream-}
Exportiert den Inhalt der Felder des PDFs in den XML-Stream.

### extractXfaData {#extractXfaData-java.io.OutputStream-}
Extrahiert XFA-Datenpaket

### fillBarcodeField {#fillBarcodeField-java.lang.String-java.lang.String-}
Füllt ein Barcode-Feld gemäß seinem vollqualifizierten Feldnamen.

### fillField {#fillField-java.lang.String-boolean-}
Füllt das Kontrollkästchenfeld mit einem booleschen Wert.

### fillField {#fillField-java.lang.String-int-}
Füllt das Optionsfeld mit einem gültigen Indexwert gemäß einem vollqualifizierten Feldnamen.

### fillField {#fillField-java.lang.String-java.lang.String-}
Füllt das Feld mit einem gültigen Wert gemäß einem vollqualifizierten Feldnamen.

### fillField {#fillField-java.lang.String-java.lang.String:A-}
Füllt ein Feld mit mehreren Auswahlen. Hinweis: nur für AcroForm-Listenfeld.

### fillField {#fillField-java.lang.String-java.lang.String-boolean-}
Füllt das Feld mit dem angegebenen Wert.

### fillFields {#fillFields-java.lang.String:A-java.lang.String:A-java.io.OutputStream-}
Füllt die Textfeld‑Felder mit Textwerten und speichert das Dokument.

### fillImageField {#fillImageField-java.lang.String-java.io.InputStream-}
Überlädt die Funktion von FillImageField.

### fillImageField {#fillImageField-java.lang.String-java.lang.String-}
Fügt ein Bild in das vorhandene Schaltflächenfeld als dessen Darstellung gemäß seinem vollqualifizierten Feldnamen ein.

### flattenAllFields {#flattenAllFields--}
```
public void flattenAllFields()
```

Flacht alle Felder ab.

### flattenField {#flattenField-java.lang.String-}
Flacht ein angegebenes Feld mit dem vollqualifizierten Feldnamen ab.

### getAttachmentName {#getAttachmentName--}
```
public String getAttachmentName()
```

Ermittelt den Namen des Anhangs, wenn das Ergebnis der Operation in HttpResponse-Objekten als Anhang gespeichert wird.

**Returns:**
String‑Objekt

### getButtonOptionCurrentValue {#getButtonOptionCurrentValue-java.lang.String-}
Gibt den aktuellen Wert für Optionsfelder von Optionsschaltern zurück.

### getButtonOptionValues {#getButtonOptionValues-java.lang.String-}
Ermittelt die Optionsfelder von Optionsschaltern und zugehörige Werte basierend auf dem Feldnamen.

### getButtonOptionValuesInternal {#getButtonOptionValuesInternal-java.lang.String-}
Ermittelt die Optionsfelder von Optionsschaltern und zugehörige Werte basierend auf dem Feldnamen.

### getContentDisposition {#getContentDisposition--}
```
public ContentDisposition getContentDisposition()
```

Der angezeigte Inhalt wird gespeichert, wenn das Ergebnis der Operation in ein HttpResponse-Objekt gespeichert wird.

**Returns:**
ContentDisposition-Element

### getDestFileName {#getDestFileName--}
```
@Deprecated public String getDestFileName()
```

Veraltet.

**Returns:**
String-Objekt

### getDestStream {#getDestStream--}
```
@Deprecated public OutputStream getDestStream()
```

Veraltet.

**Returns:**
OutputStream-Objekt

### getField {#getField-java.lang.String-}
Ermittelt den Wert des Feldes gemäß seinem Feldnamen.

### getFieldFacade {#getFieldFacade-java.lang.String-}
Gibt das FrogmFieldFacade-Objekt zurück, das alle Darstellungsattribute enthält.

### getFieldFlag {#getFieldFlag-java.lang.String-}
Gibt die Flags des Feldes zurück.

### getFieldLimit {#getFieldLimit-java.lang.String-}
Ermittelt die Beschränkung des Textfeldes.

### getFieldNames {#getFieldNames--}
```
public String [] getFieldNames()
```

Ermittelt die Liste der Feldnamen im Formular.

**Returns:**
String[]-Objekt

### getFieldType {#getFieldType-java.lang.String-}
Gibt den Typ des Feldes zurück.

### getFormSubmitButtonNames {#getFormSubmitButtonNames--}
```
public String [] getFormSubmitButtonNames()
```

Ermittelt alle Namen der Formular-Submit-Schaltflächen.

**Returns:**
String[]-Objekt

### getFullFieldName {#getFullFieldName-java.lang.String-}
Ermittelt den vollständigen Feldnamen gemäß seinem kurzen Feldnamen.

### getImportResult {#getImportResult--}
```
public com.aspose.pdf.facades.AForm.FormImportResult[] getImportResult()
```

Ergebnis der letzten Importoperation.

**Returns:**
FormImportResult[] Array

### getResponse {#getResponse--}
```
public javax.servlet.http.HttpServletResponse getResponse()
```

Liest oder setzt das Response-Objekt, in dem das Ergebnis der Operation gespeichert wird.

**Returns:**
HttpServletResponse-Objekt

### getRichText {#getRichText-java.lang.String-}
Ruft den Wert eines Rich-Text-Feldes ab, einschließlich der Formatierungsinformationen jedes Zeichens.

### getSaveOptions {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```

Liest oder setzt die Speicheroptionen, wenn das Ergebnis als HttpResponse gespeichert wird.

**Returns:**
SaveOptions-Objekt

### getSrcFileName {#getSrcFileName--}
```
@Deprecated public String getSrcFileName()
```

Veraltet.

**Returns:**
String-Objekt

### getSrcStream {#getSrcStream--}
```
public InputStream getSrcStream()
```

Ermittelt den Quell-Stream.

**Returns:**
InputStream‑Objekt

### getSubmitFlags {#getSubmitFlags-java.lang.String-}
Gibt die Übermittlungsflags des Submit-Buttons zurück

### importFdf {#importFdf-java.io.InputStream-}
Importiert den Inhalt der Felder aus der fdf-Datei und legt ihn in das neue PDF.

### importXfdf {#importXfdf-java.io.InputStream-}
Importiert den Inhalt der Felder aus der xfdf(xml)-Datei und legt ihn in das neue PDF.

### importXml {#importXml-java.io.InputStream-}
Importiert den Inhalt der Felder aus der xml‑Datei und legt ihn in das neue PDF.

### importXml {#importXml-java.io.InputStream-boolean-}
Importiert den Inhalt der Felder aus der xml‑Datei und legt ihn in das neue PDF.

### importXml {#importXml-java.lang.String-}
Importiert den Inhalt der Felder aus der xml‑Datei und legt ihn in das neue PDF.

### isRequiredField {#isRequiredField-java.lang.String-}
Bestimmt, ob das Feld erforderlich ist oder nicht.

### renameField {#renameField-java.lang.String-java.lang.String-}
Benennt ein Feld um.

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
Legt fest, wie Inhalte gespeichert werden, wenn das Ergebnis der Operation in ein HttpResponse-Objekt gespeichert wird.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Legt das PDF-Dateiformat fest.

### setDestFileName {#setDestFileName-java.lang.String-}
Veraltet.

### setDestStream {#setDestStream-java.io.OutputStream-}
Veraltet.

### setResponse {#setResponse-javax.servlet.http.HttpServletResponse-}
Liest oder setzt das Response-Objekt, in dem das Ergebnis der Operation gespeichert wird.

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Liest oder setzt die Speicheroptionen, wenn das Ergebnis als HttpResponse gespeichert wird.

### setSrcFileName {#setSrcFileName-java.lang.String-}
Veraltet.

### setSrcStream {#setSrcStream-java.io.InputStream-}
Ermittelt den Quell-Stream.

### setXfaData {#setXfaData-java.io.InputStream-}
Ersetzt XFA-Daten durch das angegebene Datenpaket.
