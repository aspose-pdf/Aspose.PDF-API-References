---
title: "IForm"
linktitle: "IForm"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Classe che rappresenta l'oggetto del modulo Acro."
type: docs
weight: 250
url: /it/java/com.aspose.pdf.facades/iform/
---
```
public interface IForm extends com.aspose.ms.System.IDisposable, Closeable
```

Classe che rappresenta l'oggetto del modulo Acro.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [close](#close--) | Chiude i file aperti senza apportare modifiche. |
| [exportFdf](#exportFdf-java.io.OutputStream-) | Esporta il contenuto dei campi del pdf nel flusso fdf. |
| [exportXfdf](#exportXfdf-java.io.OutputStream-) | Esporta il contenuto dei campi del pdf nel flusso xml. |
| [exportXml](#exportXml-java.io.OutputStream-) | Esporta il contenuto dei campi del pdf nel flusso xml. |
| [fillBarcodeField](#fillBarcodeField-java.lang.String-java.lang.String-) | Compila un campo barcode secondo il suo nome di campo completamente qualificato. |
| [fillField](#fillField-java.lang.String-boolean-) | Compila il campo casella di controllo con un valore booleano. |
| [fillField](#fillField-java.lang.String-int-) | Compila il campo radio con un valore di indice valido secondo un nome di campo completamente qualificato. |
| [fillField](#fillField-java.lang.String-java.lang.String-) | Compila il campo con un valore valido secondo un nome di campo completamente qualificato. |
| [fillField](#fillField-java.lang.String-java.lang.String:A-) | Compila un campo con selezioni multiple. Nota: solo per il campo List Box di AcroForm. |
| [fillField](#fillField-java.lang.String-java.lang.String-boolean-) | FillField |
| [fillImageField](#fillImageField-java.lang.String-java.io.InputStream-) | Sovraccarica la funzione FillImageField. |
| [fillImageField](#fillImageField-java.lang.String-java.lang.String-) | Incolla un'immagine sul campo pulsante esistente come sua apparenza secondo il suo nome di campo completamente qualificato. |
| [flattenAllFields](#flattenAllFields--) | Appiattisce tutti i campi. |
| [flattenField](#flattenField-java.lang.String-) | Appiattisce un campo specificato con il nome di campo completamente qualificato. |
| [getAttachmentName](#getAttachmentName--) | Ottiene o imposta il nome dell'allegato quando il risultato dell'operazione viene memorizzato negli oggetti HttpResponse come allegato. |
| [getButtonOptionCurrentValue](#getButtonOptionCurrentValue-java.lang.String-) | Restituisce il valore corrente per i campi di opzione dei pulsanti radio. |
| [getButtonOptionValues](#getButtonOptionValues-java.lang.String-) | Ottiene i campi di opzione dei pulsanti radio e i valori correlati in base al nome del campo. |
| [getButtonOptionValuesInternal](#getButtonOptionValuesInternal-java.lang.String-) | Ottiene i campi di opzione dei pulsanti radio e i valori correlati in base al nome del campo. |
| [getContentDisposition](#getContentDisposition--) | Ottiene o imposta come il contenuto verrà memorizzato quando il risultato dell'operazione viene memorizzato nell'oggetto HttpResponse. |
| [getDestFileName](#getDestFileName--) | Ottiene il nome del file di destinazione. |
| [getDestStream](#getDestStream--) | Ottiene lo stream di destinazione. |
| [getDocument](#getDocument--) | Ottiene il documento Form su cui si sta lavorando. |
| [getField](#getField-java.lang.String-) | Ottiene il valore del campo in base al suo nome. |
| [getFieldFacade](#getFieldFacade-java.lang.String-) | Restituisce l'oggetto FrohmFieldFacade contenente tutti gli attributi di aspetto. |
| [getFieldFlag](#getFieldFlag-java.lang.String-) | Restituisce i flag del campo. |
| [getFieldLimit](#getFieldLimit-java.lang.String-) | Ottieni la limitazione del campo di testo. |
| [getFieldNames](#getFieldNames--) | Ottiene l'elenco dei nomi dei campi nel modulo. |
| [getFieldType](#getFieldType-java.lang.String-) | Restituisce il tipo del campo. |
| [getFormSubmitButtonNames](#getFormSubmitButtonNames--) | Ottiene tutti i nomi dei pulsanti di invio del modulo. |
| [getFullFieldName](#getFullFieldName-java.lang.String-) | Ottiene il nome completo del campo in base al suo nome breve. |
| [getRichText](#getRichText-java.lang.String-) | Ottieni il valore di un campo Rich Text, includendo le informazioni di formattazione di ogni carattere. |
| [getSaveOptions](#getSaveOptions--) | Ottiene o imposta le opzioni di salvataggio quando il risultato è memorizzato come HttpResponse. |
| [getSrcFileName](#getSrcFileName--) | Ottiene il nome del file sorgente. |
| [getSrcStream](#getSrcStream--) | Ottiene lo stream di origine. |
| [getSubmitFlags](#getSubmitFlags-java.lang.String-) | Restituisce i flag di invio del pulsante di submit. |
| [importFdf](#importFdf-java.io.InputStream-) | Importa il contenuto dei campi dal file fdf e lo inserisce nel nuovo PDF. |
| [importXfdf](#importXfdf-java.io.InputStream-) | Importa il contenuto dei campi dal file xfdf (xml) e lo inserisce nel nuovo PDF. |
| [importXml](#importXml-java.io.InputStream-) | Importa il contenuto dei campi dal file xml e lo inserisce nel nuovo pdf. |
| [importXml](#importXml-java.io.InputStream-boolean-) | Importa il contenuto dei campi dal file xml e lo inserisce nel nuovo pdf. |
| [renameField](#renameField-java.lang.String-java.lang.String-) | Rinomina un campo. |
| [save](#save--) | Salva il valore dei campi compilati e chiude il documento Pdf aperto. |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | Imposta il nome dell'allegato quando il risultato dell'operazione viene memorizzato negli oggetti HttpResponse come allegato. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | Imposta come il contenuto verrà memorizzato quando il risultato dell'operazione è salvato nell'oggetto HttpResponse. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | Imposta il formato del file PDF. |
| [setDestFileName](#setDestFileName-java.lang.String-) | Imposta il nome del file di destinazione. |
| [setDestStream](#setDestStream-java.io.OutputStream-) | Ottiene lo stream di destinazione. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Ottiene o imposta le opzioni di salvataggio quando il risultato è memorizzato come HttpResponse. |
| [setSrcFileName](#setSrcFileName-java.lang.String-) | Imposta il nome del file di origine. |
| [setSrcStream](#setSrcStream-java.io.InputStream-) | Ottiene lo stream di origine. |

### close {#close--}
```
void close()
```

Chiude i file aperti senza apportare modifiche.

### exportFdf {#exportFdf-java.io.OutputStream-}
Esporta il contenuto dei campi del pdf nel flusso fdf.

### exportXfdf {#exportXfdf-java.io.OutputStream-}
Esporta il contenuto dei campi del pdf nel flusso xml.

### exportXml {#exportXml-java.io.OutputStream-}
Esporta il contenuto dei campi del pdf nel flusso xml.

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
FillField

### fillImageField {#fillImageField-java.lang.String-java.io.InputStream-}
Sovraccarica la funzione FillImageField.

### fillImageField {#fillImageField-java.lang.String-java.lang.String-}
Incolla un'immagine sul campo pulsante esistente come sua apparenza secondo il suo nome di campo completamente qualificato.

### flattenAllFields {#flattenAllFields--}
```
void flattenAllFields()
```

Appiattisce tutti i campi.

### flattenField {#flattenField-java.lang.String-}
Appiattisce un campo specificato con il nome di campo completamente qualificato.

### getAttachmentName {#getAttachmentName--}
```
String getAttachmentName()
```

Ottiene o imposta il nome dell'allegato quando il risultato dell'operazione viene memorizzato negli oggetti HttpResponse come allegato.

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
ContentDisposition getContentDisposition()
```

Ottiene o imposta come il contenuto verrà memorizzato quando il risultato dell'operazione viene memorizzato nell'oggetto HttpResponse.

**Returns:**
Elemento ContentDisposition

### getDestFileName {#getDestFileName--}
```
String getDestFileName()
```

Ottiene il nome del file di destinazione.

**Returns:**
Oggetto stringa

### getDestStream {#getDestStream--}
```
OutputStream getDestStream()
```

Ottiene lo stream di destinazione.

**Returns:**
oggetto OutputStream

### getDocument {#getDocument--}
```
IDocument getDocument()
```

Ottiene il documento Form su cui si sta lavorando.

**Returns:**
Oggetto IDocument

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
String [] getFieldNames()
```

Ottiene l'elenco dei nomi dei campi nel modulo.

**Returns:**
oggetto String[]

### getFieldType {#getFieldType-java.lang.String-}
Restituisce il tipo del campo.

### getFormSubmitButtonNames {#getFormSubmitButtonNames--}
```
String [] getFormSubmitButtonNames()
```

Ottiene tutti i nomi dei pulsanti di invio del modulo.

**Returns:**
oggetto String[]

### getFullFieldName {#getFullFieldName-java.lang.String-}
Ottiene il nome completo del campo in base al suo nome breve.

### getRichText {#getRichText-java.lang.String-}
Ottieni il valore di un campo Rich Text, includendo le informazioni di formattazione di ogni carattere.

### getSaveOptions {#getSaveOptions--}
```
SaveOptions getSaveOptions()
```

Ottiene o imposta le opzioni di salvataggio quando il risultato è memorizzato come HttpResponse.

**Returns:**
oggetto SaveOptions

### getSrcFileName {#getSrcFileName--}
```
String getSrcFileName()
```

Ottiene il nome del file sorgente.

**Returns:**
Oggetto stringa

### getSrcStream {#getSrcStream--}
```
InputStream getSrcStream()
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

### renameField {#renameField-java.lang.String-java.lang.String-}
Rinomina un campo.

### save {#save--}
```
void save()
```

Salva il valore dei campi compilati e chiude il documento Pdf aperto.

### setAttachmentName {#setAttachmentName-java.lang.String-}
Imposta il nome dell'allegato quando il risultato dell'operazione viene memorizzato negli oggetti HttpResponse come allegato.

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
Imposta come il contenuto verrà memorizzato quando il risultato dell'operazione è salvato nell'oggetto HttpResponse.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Imposta il formato del file PDF.

### setDestFileName {#setDestFileName-java.lang.String-}
Imposta il nome del file di destinazione.

### setDestStream {#setDestStream-java.io.OutputStream-}
Ottiene lo stream di destinazione.

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Ottiene o imposta le opzioni di salvataggio quando il risultato è memorizzato come HttpResponse.

### setSrcFileName {#setSrcFileName-java.lang.String-}
Imposta il nome del file di origine.

### setSrcStream {#setSrcStream-java.io.InputStream-}
Ottiene lo stream di origine.
