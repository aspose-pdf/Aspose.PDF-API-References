---
title: "FormWeb"
linktitle: "FormWeb"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta l'interfaccia del modulo Acro."
type: docs
weight: 230
url: /it/java/com.aspose.pdf.facades/formweb/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.FormWeb, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.FormWeb, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.FormWeb

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, IForm, ISaveableFacade, Closeable, AutoCloseable

```
public final class FormWeb extends SaveableFacade implements IForm
```

Rappresenta l'interfaccia del modulo Acro.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [FormWeb](#FormWeb--) | <p> Costruttore di FormWeb senza parametri. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre> |
| [FormWeb](#FormWeb-com.aspose.pdf.IDocument-) | <p> Costruttore di FormWeb senza parametri. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre> |
| [FormWeb](#FormWeb-com.aspose.pdf.IDocument-java.io.OutputStream-) | <p> Costruttore di FormWeb senza parametri. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre> |
| [FormWeb](#FormWeb-com.aspose.pdf.IDocument-java.lang.String-) | <p> Costruttore di FormWeb senza parametri. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre> |
| [FormWeb](#FormWeb-java.io.InputStream-) | <p> Costruttore di FormWeb senza parametri. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre> |
| [FormWeb](#FormWeb-java.io.InputStream-javax.servlet.http.HttpServletResponse-) | <p> Costruttore di FormWeb senza parametri. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre> |
| [FormWeb](#FormWeb-java.io.InputStream-java.io.OutputStream-) | <p> Costruttore di FormWeb senza parametri. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre> |
| [FormWeb](#FormWeb-java.io.InputStream-java.lang.String-) | <p> Costruttore di FormWeb senza parametri. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre> |
| [FormWeb](#FormWeb-java.lang.String-) | <p> Costruttore di FormWeb senza parametri. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre> |
| [FormWeb](#FormWeb-java.lang.String-javax.servlet.http.HttpServletResponse-) | <p> Costruttore di FormWeb senza parametri. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre> |
| [FormWeb](#FormWeb-java.lang.String-java.io.OutputStream-) | <p> Costruttore di FormWeb senza parametri. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre> |
| [FormWeb](#FormWeb-java.lang.String-java.lang.String-) | <p> Costruttore di FormWeb senza parametri. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre> |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [bindPdf](#bindPdf-java.io.InputStream-java.lang.String-) | Inizializza la facciata. |
| [bindPdf](#bindPdf-java.lang.String-java.lang.String-) | Inizializza la facciata. |
| [close](#close--) | Chiude tutte le risorse aperte utilizzate da questo documento. |
| [dispose](#dispose--) | Obsoleto. |
| [exportFdf](#exportFdf-java.io.OutputStream-) | Esporta il contenuto dei campi del pdf nel flusso fdf. |
| [exportXfdf](#exportXfdf-java.io.OutputStream-) | Esporta il contenuto dei campi del pdf nel flusso xml. |
| [exportXml](#exportXml-java.io.OutputStream-) | Esporta il contenuto dei campi del pdf nel flusso xml. |
| [extractXfaData](#extractXfaData-java.io.OutputStream-) | Estrae il pacchetto dati XFA |
| [fillBarcodeField](#fillBarcodeField-java.lang.String-java.lang.String-) | Compila un campo barcode secondo il suo nome di campo completamente qualificato. |
| [fillField](#fillField-java.lang.String-boolean-) | Compila il campo casella di controllo con un valore booleano. |
| [fillField](#fillField-java.lang.String-int-) | Compila il campo radio con un valore di indice valido secondo un nome di campo completamente qualificato. |
| [fillField](#fillField-java.lang.String-java.lang.String-) | Compila il campo con un valore valido secondo un nome di campo completamente qualificato. |
| [fillField](#fillField-java.lang.String-java.lang.String:A-) | Compila un campo con selezioni multiple. Nota: solo per il campo List Box di AcroForm. |
| [fillField](#fillField-java.lang.String-java.lang.String-boolean-) | Compila il campo con il valore specificato. |
| [fillFields](#fillFields-java.lang.String:A-java.lang.String:A-java.io.OutputStream-) | Compila i campi di casella di testo con valori di testo e salva il documento. |
| [fillImageField](#fillImageField-java.lang.String-java.io.InputStream-) | Sovraccarica la funzione FillImageField. |
| [fillImageField](#fillImageField-java.lang.String-java.lang.String-) | Incolla un'immagine sul campo pulsante esistente come sua apparenza secondo il suo nome di campo completamente qualificato. |
| [flattenAllFields](#flattenAllFields--) | Appiattisce tutti i campi. |
| [flattenField](#flattenField-java.lang.String-) | Appiattisce un campo specificato con il nome di campo completamente qualificato. |
| [getAttachmentName](#getAttachmentName--) | Ottiene il nome dell'allegato quando il risultato dell'operazione viene memorizzato negli oggetti HttpResponse come allegato. |
| [getButtonOptionCurrentValue](#getButtonOptionCurrentValue-java.lang.String-) | Restituisce il valore corrente per i campi di opzione dei pulsanti radio. |
| [getButtonOptionValues](#getButtonOptionValues-java.lang.String-) | Ottiene i campi di opzione dei pulsanti radio e i valori correlati in base al nome del campo. |
| [getButtonOptionValuesInternal](#getButtonOptionValuesInternal-java.lang.String-) | Ottiene i campi di opzione dei pulsanti radio e i valori correlati in base al nome del campo. |
| [getContentDisposition](#getContentDisposition--) | Il contenuto Getshow verrà memorizzato quando il risultato dell'operazione sarà salvato nell'oggetto HttpResponse. |
| [getDestFileName](#getDestFileName--) | Obsoleto. |
| [getDestStream](#getDestStream--) | Obsoleto. |
| [getField](#getField-java.lang.String-) | Ottiene il valore del campo in base al suo nome. |
| [getFieldFacade](#getFieldFacade-java.lang.String-) | Restituisce l'oggetto FrohmFieldFacade contenente tutti gli attributi di aspetto. |
| [getFieldFlag](#getFieldFlag-java.lang.String-) | Restituisce i flag del campo. |
| [getFieldLimit](#getFieldLimit-java.lang.String-) | Ottieni la limitazione del campo di testo. |
| [getFieldNames](#getFieldNames--) | Ottiene l'elenco dei nomi dei campi nel modulo. |
| [getFieldType](#getFieldType-java.lang.String-) | Restituisce il tipo del campo. |
| [getFormSubmitButtonNames](#getFormSubmitButtonNames--) | Ottiene tutti i nomi dei pulsanti di invio del modulo. |
| [getFullFieldName](#getFullFieldName-java.lang.String-) | Ottiene il nome completo del campo in base al suo nome breve. |
| [getImportResult](#getImportResult--) | Risultato dell'ultima operazione di importazione. |
| [getResponse](#getResponse--) | Ottiene o imposta l'oggetto Response dove sarà memorizzato il risultato dell'operazione. |
| [getRichText](#getRichText-java.lang.String-) | Ottieni il valore di un campo Rich Text, includendo le informazioni di formattazione di ogni carattere. |
| [getSaveOptions](#getSaveOptions--) | Ottiene o imposta le opzioni di salvataggio quando il risultato è memorizzato come HttpResponse. |
| [getSrcFileName](#getSrcFileName--) | Obsoleto. |
| [getSrcStream](#getSrcStream--) | Ottiene lo stream di origine. |
| [getSubmitFlags](#getSubmitFlags-java.lang.String-) | Restituisce i flag di invio del pulsante di submit. |
| [importFdf](#importFdf-java.io.InputStream-) | Importa il contenuto dei campi dal file fdf e lo inserisce nel nuovo PDF. |
| [importXfdf](#importXfdf-java.io.InputStream-) | Importa il contenuto dei campi dal file xfdf (xml) e lo inserisce nel nuovo PDF. |
| [importXml](#importXml-java.io.InputStream-) | Importa il contenuto dei campi dal file xml e lo inserisce nel nuovo pdf. |
| [importXml](#importXml-java.io.InputStream-boolean-) | Importa il contenuto dei campi dal file xml e lo inserisce nel nuovo pdf. |
| [importXml](#importXml-java.lang.String-) | Importa il contenuto dei campi dal file xml e lo inserisce nel nuovo pdf. |
| [isRequiredField](#isRequiredField-java.lang.String-) | Determina se il campo è obbligatorio o meno. |
| [renameField](#renameField-java.lang.String-java.lang.String-) | Rinomina un campo. |
| [save](#save--) | <p> Salva il valore dei campi compilati e chiude il documento PDF aperto. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_Changed.pdf\"); form.fillField(\"textField\", \"new value\"); form.save(); </pre> |
| [save](#save-java.io.OutputStream-) | <p> Salva il valore dei campi compilati e chiude il documento PDF aperto. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_Changed.pdf\"); form.fillField(\"textField\", \"new value\"); form.save(); </pre> |
| [save](#save-java.lang.String-) | <p> Salva il valore dei campi compilati e chiude il documento PDF aperto. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_Changed.pdf\"); form.fillField(\"textField\", \"new value\"); form.save(); </pre> |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | Imposta il nome dell'allegato quando il risultato dell'operazione viene memorizzato negli oggetti HttpResponse come allegato. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | Imposta come il contenuto verrà memorizzato quando il risultato dell'operazione è salvato nell'oggetto HttpResponse. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | Imposta il formato del file PDF. |
| [setDestFileName](#setDestFileName-java.lang.String-) | Obsoleto. |
| [setDestStream](#setDestStream-java.io.OutputStream-) | Obsoleto. |
| [setResponse](#setResponse-javax.servlet.http.HttpServletResponse-) | Ottiene o imposta l'oggetto Response dove sarà memorizzato il risultato dell'operazione. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Ottiene o imposta le opzioni di salvataggio quando il risultato è memorizzato come HttpResponse. |
| [setSrcFileName](#setSrcFileName-java.lang.String-) | Obsoleto. |
| [setSrcStream](#setSrcStream-java.io.InputStream-) | Ottiene lo stream di origine. |
| [setXfaData](#setXfaData-java.io.InputStream-) | Sostituisce i dati XFA con il pacchetto dati specificato. |

### FormWeb {#FormWeb--}
```
public FormWeb()
```

<p> Costruttore di FormWeb senza parametri. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre>

### FormWeb {#FormWeb-com.aspose.pdf.IDocument-}
<p> Costruttore di FormWeb senza parametri. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre>

### FormWeb {#FormWeb-com.aspose.pdf.IDocument-java.io.OutputStream-}
<p> Costruttore di FormWeb senza parametri. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre>

### FormWeb {#FormWeb-com.aspose.pdf.IDocument-java.lang.String-}
<p> Costruttore di FormWeb senza parametri. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre>

### FormWeb {#FormWeb-java.io.InputStream-}
<p> Costruttore di FormWeb senza parametri. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre>

### FormWeb {#FormWeb-java.io.InputStream-javax.servlet.http.HttpServletResponse-}
<p> Costruttore di FormWeb senza parametri. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre>

### FormWeb {#FormWeb-java.io.InputStream-java.io.OutputStream-}
<p> Costruttore di FormWeb senza parametri. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre>

### FormWeb {#FormWeb-java.io.InputStream-java.lang.String-}
<p> Costruttore di FormWeb senza parametri. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre>

### FormWeb {#FormWeb-java.lang.String-}
<p> Costruttore di FormWeb senza parametri. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre>

### FormWeb {#FormWeb-java.lang.String-javax.servlet.http.HttpServletResponse-}
<p> Costruttore di FormWeb senza parametri. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre>

### FormWeb {#FormWeb-java.lang.String-java.io.OutputStream-}
<p> Costruttore di FormWeb senza parametri. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre>

### FormWeb {#FormWeb-java.lang.String-java.lang.String-}
<p> Costruttore di FormWeb senza parametri. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre>

### bindPdf {#bindPdf-java.io.InputStream-java.lang.String-}
Inizializza la facciata.

### bindPdf {#bindPdf-java.lang.String-java.lang.String-}
Inizializza la facciata.

### close {#close--}
```
public void close()
```

Chiude tutte le risorse aperte utilizzate da questo documento.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Obsoleto.

### exportFdf {#exportFdf-java.io.OutputStream-}
Esporta il contenuto dei campi del pdf nel flusso fdf.

### exportXfdf {#exportXfdf-java.io.OutputStream-}
Esporta il contenuto dei campi del pdf nel flusso xml.

### exportXml {#exportXml-java.io.OutputStream-}
Esporta il contenuto dei campi del pdf nel flusso xml.

### extractXfaData {#extractXfaData-java.io.OutputStream-}
Estrae il pacchetto dati XFA

### fillBarcodeField {#fillBarcodeField-java.lang.String-java.lang.String-}
Compila un campo barcode secondo il suo nome di campo completamente qualificato.

### fillField {#fillField-java.lang.String-boolean-}
Compila il campo casella di controllo con un valore booleano.

### fillField {#fillField-java.lang.String-int-}
Compila il campo radio con un valore di indice valido secondo un nome di campo completamente qualificato.

### fillField {#fillField-java.lang.String-java.lang.String-}
Compila il campo con un valore valido secondo un nome di campo completamente qualificato.

### fillField {#fillField-java.lang.String-java.lang.String:A-}
Compila un campo con selezioni multiple. Nota: solo per il campo List Box di AcroForm.

### fillField {#fillField-java.lang.String-java.lang.String-boolean-}
Compila il campo con il valore specificato.

### fillFields {#fillFields-java.lang.String:A-java.lang.String:A-java.io.OutputStream-}
Compila i campi di casella di testo con valori di testo e salva il documento.

### fillImageField {#fillImageField-java.lang.String-java.io.InputStream-}
Sovraccarica la funzione FillImageField.

### fillImageField {#fillImageField-java.lang.String-java.lang.String-}
Incolla un'immagine sul campo pulsante esistente come sua apparenza secondo il suo nome di campo completamente qualificato.

### flattenAllFields {#flattenAllFields--}
```
public void flattenAllFields()
```

Appiattisce tutti i campi.

### flattenField {#flattenField-java.lang.String-}
Appiattisce un campo specificato con il nome di campo completamente qualificato.

### getAttachmentName {#getAttachmentName--}
```
public String getAttachmentName()
```

Ottiene il nome dell'allegato quando il risultato dell'operazione viene memorizzato negli oggetti HttpResponse come allegato.

**Returns:**
oggetto stringa

### getButtonOptionCurrentValue {#getButtonOptionCurrentValue-java.lang.String-}
Restituisce il valore corrente per i campi di opzione dei pulsanti radio.

### getButtonOptionValues {#getButtonOptionValues-java.lang.String-}
Ottiene i campi di opzione dei pulsanti radio e i valori correlati in base al nome del campo.

### getButtonOptionValuesInternal {#getButtonOptionValuesInternal-java.lang.String-}
Ottiene i campi di opzione dei pulsanti radio e i valori correlati in base al nome del campo.

### getContentDisposition {#getContentDisposition--}
```
public ContentDisposition getContentDisposition()
```

Il contenuto Getshow verrà memorizzato quando il risultato dell'operazione sarà salvato nell'oggetto HttpResponse.

**Returns:**
Elemento ContentDisposition

### getDestFileName {#getDestFileName--}
```
@Deprecated public String getDestFileName()
```

Obsoleto.

**Returns:**
Oggetto stringa

### getDestStream {#getDestStream--}
```
@Deprecated public OutputStream getDestStream()
```

Obsoleto.

**Returns:**
oggetto OutputStream

### getField {#getField-java.lang.String-}
Ottiene il valore del campo in base al suo nome.

### getFieldFacade {#getFieldFacade-java.lang.String-}
Restituisce l'oggetto FrohmFieldFacade contenente tutti gli attributi di aspetto.

### getFieldFlag {#getFieldFlag-java.lang.String-}
Restituisce i flag del campo.

### getFieldLimit {#getFieldLimit-java.lang.String-}
Ottieni la limitazione del campo di testo.

### getFieldNames {#getFieldNames--}
```
public String [] getFieldNames()
```

Ottiene l'elenco dei nomi dei campi nel modulo.

**Returns:**
oggetto String[]

### getFieldType {#getFieldType-java.lang.String-}
Restituisce il tipo del campo.

### getFormSubmitButtonNames {#getFormSubmitButtonNames--}
```
public String [] getFormSubmitButtonNames()
```

Ottiene tutti i nomi dei pulsanti di invio del modulo.

**Returns:**
oggetto String[]

### getFullFieldName {#getFullFieldName-java.lang.String-}
Ottiene il nome completo del campo in base al suo nome breve.

### getImportResult {#getImportResult--}
```
public com.aspose.pdf.facades.AForm.FormImportResult[] getImportResult()
```

Risultato dell'ultima operazione di importazione.

**Returns:**
FormImportResult[] array

### getResponse {#getResponse--}
```
public javax.servlet.http.HttpServletResponse getResponse()
```

Ottiene o imposta l'oggetto Response dove sarà memorizzato il risultato dell'operazione.

**Returns:**
Oggetto HttpServletResponse

### getRichText {#getRichText-java.lang.String-}
Ottieni il valore di un campo Rich Text, includendo le informazioni di formattazione di ogni carattere.

### getSaveOptions {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```

Ottiene o imposta le opzioni di salvataggio quando il risultato è memorizzato come HttpResponse.

**Returns:**
oggetto SaveOptions

### getSrcFileName {#getSrcFileName--}
```
@Deprecated public String getSrcFileName()
```

Obsoleto.

**Returns:**
Oggetto stringa

### getSrcStream {#getSrcStream--}
```
public InputStream getSrcStream()
```

Ottiene lo stream di origine.

**Returns:**
Oggetto InputStream

### getSubmitFlags {#getSubmitFlags-java.lang.String-}
Restituisce i flag di invio del pulsante di submit.

### importFdf {#importFdf-java.io.InputStream-}
Importa il contenuto dei campi dal file fdf e lo inserisce nel nuovo PDF.

### importXfdf {#importXfdf-java.io.InputStream-}
Importa il contenuto dei campi dal file xfdf (xml) e lo inserisce nel nuovo PDF.

### importXml {#importXml-java.io.InputStream-}
Importa il contenuto dei campi dal file xml e lo inserisce nel nuovo pdf.

### importXml {#importXml-java.io.InputStream-boolean-}
Importa il contenuto dei campi dal file xml e lo inserisce nel nuovo pdf.

### importXml {#importXml-java.lang.String-}
Importa il contenuto dei campi dal file xml e lo inserisce nel nuovo pdf.

### isRequiredField {#isRequiredField-java.lang.String-}
Determina se il campo è obbligatorio o meno.

### renameField {#renameField-java.lang.String-java.lang.String-}
Rinomina un campo.

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
Imposta come il contenuto verrà memorizzato quando il risultato dell'operazione è salvato nell'oggetto HttpResponse.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Imposta il formato del file PDF.

### setDestFileName {#setDestFileName-java.lang.String-}
Obsoleto.

### setDestStream {#setDestStream-java.io.OutputStream-}
Obsoleto.

### setResponse {#setResponse-javax.servlet.http.HttpServletResponse-}
Ottiene o imposta l'oggetto Response dove sarà memorizzato il risultato dell'operazione.

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Ottiene o imposta le opzioni di salvataggio quando il risultato è memorizzato come HttpResponse.

### setSrcFileName {#setSrcFileName-java.lang.String-}
Obsoleto.

### setSrcStream {#setSrcStream-java.io.InputStream-}
Ottiene lo stream di origine.

### setXfaData {#setXfaData-java.io.InputStream-}
Sostituisce i dati XFA con il pacchetto dati specificato.
