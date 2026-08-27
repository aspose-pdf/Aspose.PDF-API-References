---
title: "FormEditorWeb"
linktitle: "FormEditorWeb"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Classe per modificare i moduli (aggiunta/cancellazione di campi ecc)"
type: docs
weight: 210
url: /it/java/com.aspose.pdf.facades/formeditorweb/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.FormEditorWeb, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.FormEditorWeb, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.FormEditorWeb

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, IFormEditor, ISaveableFacade, Closeable, AutoCloseable

```
public final class FormEditorWeb extends SaveableFacade implements IFormEditor
```

Classe per modificare i moduli (aggiunta/cancellazione di campi ecc)

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [FormEditorWeb](#FormEditorWeb--) | <p> Costruttore per FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre> |
| [FormEditorWeb](#FormEditorWeb-com.aspose.pdf.IDocument-) | <p> Costruttore per FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre> |
| [FormEditorWeb](#FormEditorWeb-com.aspose.pdf.IDocument-java.io.OutputStream-) | <p> Costruttore per FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre> |
| [FormEditorWeb](#FormEditorWeb-com.aspose.pdf.IDocument-java.lang.String-) | <p> Costruttore per FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre> |
| [FormEditorWeb](#FormEditorWeb-java.io.InputStream-javax.servlet.http.HttpServletResponse-) | <p> Costruttore per FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre> |
| [FormEditorWeb](#FormEditorWeb-java.io.InputStream-java.io.OutputStream-) | <p> Costruttore per FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre> |
| [FormEditorWeb](#FormEditorWeb-java.lang.String-javax.servlet.http.HttpServletResponse-) | <p> Costruttore per FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre> |
| [FormEditorWeb](#FormEditorWeb-java.lang.String-java.lang.String-) | <p> Costruttore per FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre> |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [addField](#addField-com.aspose.pdf.facades.FieldType-java.lang.String-int-float-float-float-float-) | Aggiungi un campo del tipo specificato al modulo. |
| [addField](#addField-com.aspose.pdf.facades.FieldType-java.lang.String-java.lang.String-int-float-float-float-float-) | Aggiungi un campo del tipo specificato al modulo. |
| [addFieldScript](#addFieldScript-java.lang.String-java.lang.String-) | Aggiungi JavaScript per un campo PushButton. |
| [addListItem](#addListItem-java.lang.String-java.lang.String-) | Aggiunge un nuovo elemento alla casella di riepilogo. |
| [addListItem](#addListItem-java.lang.String-java.lang.String:A-) | Aggiunge un nuovo elemento con valore Export al campo casella di riepilogo esistente, solo per il campo casella combinata AcroForm. |
| [addSubmitBtn](#addSubmitBtn-java.lang.String-int-java.lang.String-java.lang.String-float-float-float-float-) | Aggiunge il pulsante di invio al modulo. |
| [close](#close--) | Chiude tutte le risorse utilizzate da questo documento. |
| [copyInnerField](#copyInnerField-java.lang.String-java.lang.String-int-) | Copia un campo esistente nella stessa posizione nel numero di pagina specificato. |
| [copyInnerField](#copyInnerField-java.lang.String-java.lang.String-int-float-float-) | Copia un campo esistente in una nuova posizione specificata sia dal numero di pagina che dalle coordinate. |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-) | Copia un campo esistente da un documento PDF a un altro documento con il numero di pagina originale e le coordinate. |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-int-) | Copia un campo esistente da un documento PDF a un altro documento con il numero di pagina specificato e le coordinate originali. |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-int-float-float-) | Copia un campo esistente da un documento PDF a un altro documento con il numero di pagina e le coordinate specificati. |
| [decorateField](#decorateField--) | Modifica gli attributi visivi di tutti i campi nel documento PDF. |
| [decorateField](#decorateField-com.aspose.pdf.facades.FieldType-) | Modifica gli attributi visivi di tutti i campi con il tipo di campo specificato. |
| [decorateField](#decorateField-java.lang.String-) | Modifica gli attributi visivi del campo specificato. |
| [delListItem](#delListItem-java.lang.String-java.lang.String-) | Elimina l'elemento dal campo elenco. |
| [dispose](#dispose--) | Obsoleto. |
| [getAttachmentName](#getAttachmentName--) | Ottiene il nome dell'allegato quando il risultato dell'operazione viene memorizzato negli oggetti HttpResponse come allegato. |
| [getContentDisposition](#getContentDisposition--) | Ottiene come il contenuto sarà memorizzato quando il risultato dell'operazione viene memorizzato nell'oggetto HttpResponse. |
| [getDestFileName](#getDestFileName--) | Obsoleto. |
| [getDestStream](#getDestStream--) | Ottiene lo stream di destinazione. |
| [getExportItems](#getExportItems--) | Ottiene le opzioni per la casella combinata con valori di esportazione. |
| [getFacade](#getFacade--) | Ottiene gli attributi visivi del campo. |
| [getFieldAppearance](#getFieldAppearance-java.lang.String-) | Ottieni i flag del campo. |
| [getItems](#getItems--) | Restituisce l'array di elementi |
| [getRadioButtonItemSize](#getRadioButtonItemSize--) | Ottiene o imposta la dimensione dell'elemento del pulsante radio (quando viene aggiunto un nuovo campo pulsante radio). |
| [getRadioGap](#getRadioGap--) | Ottieni il membro per registrare lo spazio tra due pulsanti radio adiacenti in pixel, il valore predefinito è 50. |
| [getRadioHoriz](#getRadioHoriz--) | Ottieni il flag che indica se i pulsanti radio sono disposti orizzontalmente o verticalmente, il valore predefinito è true. |
| [getResponse](#getResponse--) | Ottiene l'oggetto Response dove verrà memorizzato il risultato dell'operazione. |
| [getSaveOptions](#getSaveOptions--) | Ottiene le opzioni di salvataggio quando il risultato è memorizzato come HttpResponse. |
| [getSrcFileName](#getSrcFileName--) | Obsoleto. |
| [getSrcStream](#getSrcStream--) | Ottiene lo stream di origine. |
| [getSubmitFlag](#getSubmitFlag--) | Ottieni i flag di invio del pulsante submit |
| [moveField](#moveField-java.lang.String-float-float-float-float-) | Imposta la nuova posizione del campo. |
| [removeField](#removeField-java.lang.String-) | Rimuovi il campo dal modulo. |
| [removeFieldAction](#removeFieldAction-java.lang.String-) | Rimuovi l'azione di invio del campo. |
| [renameField](#renameField-java.lang.String-java.lang.String-) | Cambia il nome del campo. |
| [resetFacade](#resetFacade--) | Reimposta tutti gli attributi visivi a valore vuoto. |
| [resetInnerFacade](#resetInnerFacade--) | Reimposta tutti gli attributi visivi della facciata interna a valore vuoto. |
| [save](#save--) | Salva le modifiche nel file di destinazione. |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | Imposta il nome dell'allegato quando il risultato dell'operazione viene memorizzato negli oggetti HttpResponse come allegato. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | Imposta come il contenuto verrà memorizzato quando il risultato dell'operazione è salvato nell'oggetto HttpResponse. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | Imposta il formato file PDF PdfFormat. |
| [setDestFileName](#setDestFileName-java.lang.String-) | Obsoleto. |
| [setDestStream](#setDestStream-java.io.OutputStream-) | Imposta lo stream di destinazione. |
| [setExportItems](#setExportItems-java.lang.String:A:A-) | Imposta le opzioni per la casella combinata con valori di esportazione. |
| [setFacade](#setFacade-com.aspose.pdf.facades.FormFieldFacade-) | Imposta gli attributi visivi del campo. |
| [setFieldAlignment](#setFieldAlignment-java.lang.String-int-) | Imposta lo stile di allineamento di un campo di testo. |
| [setFieldAlignmentV](#setFieldAlignmentV-java.lang.String-int-) | Imposta lo stile di allineamento verticale di un campo di testo. |
| [setFieldAppearance](#setFieldAppearance-java.lang.String-int-) | Imposta i flag del campo |
| [setFieldAttribute](#setFieldAttribute-java.lang.String-int-) | Imposta gli attributi del campo. |
| [setFieldCombNumber](#setFieldCombNumber-java.lang.String-int-) | Imposta il numero di denti per un campo di testo a riga singola regolare (il campo è diviso automaticamente in tante posizioni equidistanti, o denti, quanto il valore del parametro combNumber). |
| [setFieldLimit](#setFieldLimit-java.lang.String-int-) | Imposta il conteggio massimo di caratteri del campo di testo. |
| [setFieldScript](#setFieldScript-java.lang.String-java.lang.String-) | Imposta JavaScript per un campo PushButton. |
| [setItems](#setItems-java.lang.String:A-) | Imposta gli elementi che saranno aggiunti alla casella di riepilogo o alla casella combinata appena creata. |
| [setRadioButtonItemSize](#setRadioButtonItemSize-double-) | Ottiene o imposta la dimensione dell'elemento del pulsante radio (quando viene aggiunto un nuovo campo pulsante radio). |
| [setRadioGap](#setRadioGap-float-) | Imposta il membro per registrare lo spazio tra due pulsanti radio adiacenti in pixel, il valore predefinito è 50. |
| [setRadioHoriz](#setRadioHoriz-boolean-) | Imposta il flag che indica se i pulsanti radio sono disposti orizzontalmente o verticalmente, il valore predefinito è true. |
| [setResponse](#setResponse-javax.servlet.http.HttpServletResponse-) | Imposta l'oggetto Response dove verrà memorizzato il risultato dell'operazione. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Imposta le opzioni di salvataggio quando il risultato è memorizzato come HttpResponse. |
| [setSrcFileName](#setSrcFileName-java.lang.String-) | Obsoleto. |
| [setSrcStream](#setSrcStream-java.io.InputStream-) | Imposta lo stream di origine. |
| [setSubmitFlag](#setSubmitFlag-java.lang.String-com.aspose.pdf.facades.SubmitFormFlag-) | Imposta il flag di invio del pulsante submit. |
| [setSubmitFlag](#setSubmitFlag-com.aspose.pdf.facades.SubmitFormFlag-) | Imposta i flag di invio del pulsante di submit |
| [setSubmitUrl](#setSubmitUrl-java.lang.String-java.lang.String-) | Imposta l'URL del pulsante. |
| [single2Multiple](#single2Multiple-java.lang.String-) | Trasforma un campo di testo a riga singola in uno a più righe. |

### FormEditorWeb {#FormEditorWeb--}
```
public FormEditorWeb()
```

<p> Costruttore per FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre>

### FormEditorWeb {#FormEditorWeb-com.aspose.pdf.IDocument-}
<p> Costruttore per FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre>

### FormEditorWeb {#FormEditorWeb-com.aspose.pdf.IDocument-java.io.OutputStream-}
<p> Costruttore per FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre>

### FormEditorWeb {#FormEditorWeb-com.aspose.pdf.IDocument-java.lang.String-}
<p> Costruttore per FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre>

### FormEditorWeb {#FormEditorWeb-java.io.InputStream-javax.servlet.http.HttpServletResponse-}
<p> Costruttore per FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre>

### FormEditorWeb {#FormEditorWeb-java.io.InputStream-java.io.OutputStream-}
<p> Costruttore per FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre>

### FormEditorWeb {#FormEditorWeb-java.lang.String-javax.servlet.http.HttpServletResponse-}
<p> Costruttore per FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre>

### FormEditorWeb {#FormEditorWeb-java.lang.String-java.lang.String-}
<p> Costruttore per FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre>

### addField {#addField-com.aspose.pdf.facades.FieldType-java.lang.String-int-float-float-float-float-}
Aggiungi un campo del tipo specificato al modulo.

### addField {#addField-com.aspose.pdf.facades.FieldType-java.lang.String-java.lang.String-int-float-float-float-float-}
Aggiungi un campo del tipo specificato al modulo.

### addFieldScript {#addFieldScript-java.lang.String-java.lang.String-}
Aggiungi JavaScript per un campo PushButton.

### addListItem {#addListItem-java.lang.String-java.lang.String-}
Aggiunge un nuovo elemento alla casella di riepilogo.

### addListItem {#addListItem-java.lang.String-java.lang.String:A-}
Aggiunge un nuovo elemento con valore Export al campo casella di riepilogo esistente, solo per il campo casella combinata AcroForm.

### addSubmitBtn {#addSubmitBtn-java.lang.String-int-java.lang.String-java.lang.String-float-float-float-float-}
Aggiunge il pulsante di invio al modulo.

### close {#close--}
```
public void close()
```

Chiude tutte le risorse utilizzate da questo documento.

### copyInnerField {#copyInnerField-java.lang.String-java.lang.String-int-}
Copia un campo esistente nella stessa posizione nel numero di pagina specificato.

### copyInnerField {#copyInnerField-java.lang.String-java.lang.String-int-float-float-}
Copia un campo esistente in una nuova posizione specificata sia dal numero di pagina che dalle coordinate.

### copyOuterField {#copyOuterField-java.lang.String-java.lang.String-}
Copia un campo esistente da un documento PDF a un altro documento con il numero di pagina originale e le coordinate.

### copyOuterField {#copyOuterField-java.lang.String-java.lang.String-int-}
Copia un campo esistente da un documento PDF a un altro documento con il numero di pagina specificato e le coordinate originali.

### copyOuterField {#copyOuterField-java.lang.String-java.lang.String-int-float-float-}
Copia un campo esistente da un documento PDF a un altro documento con il numero di pagina e le coordinate specificati.

### decorateField {#decorateField--}
```
public void decorateField()
```

Modifica gli attributi visivi di tutti i campi nel documento PDF.

### decorateField {#decorateField-com.aspose.pdf.facades.FieldType-}
Modifica gli attributi visivi di tutti i campi con il tipo di campo specificato.

### decorateField {#decorateField-java.lang.String-}
Modifica gli attributi visivi del campo specificato.

### delListItem {#delListItem-java.lang.String-java.lang.String-}
Elimina l'elemento dal campo elenco.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Obsoleto.

### getAttachmentName {#getAttachmentName--}
```
public String getAttachmentName()
```

Ottiene il nome dell'allegato quando il risultato dell'operazione viene memorizzato negli oggetti HttpResponse come allegato.

**Returns:**
Oggetto stringa

### getContentDisposition {#getContentDisposition--}
```
public ContentDisposition getContentDisposition()
```

Ottiene come il contenuto sarà memorizzato quando il risultato dell'operazione viene memorizzato nell'oggetto HttpResponse.

**Returns:**
Elemento ContentDisposition

### getDestFileName {#getDestFileName--}
```
@Deprecated public String getDestFileName()
```

Obsoleto.

**Returns:**
valore stringa

### getDestStream {#getDestStream--}
```
public OutputStream getDestStream()
```

Ottiene lo stream di destinazione.

**Returns:**
oggetto OutputStream

### getExportItems {#getExportItems--}
```
public String [][] getExportItems()
```

Ottiene le opzioni per la casella combinata con valori di esportazione.

**Returns:**
String[][] array

### getFacade {#getFacade--}
```
public FormFieldFacade getFacade()
```

Ottiene gli attributi visivi del campo.

**Returns:**
oggetto FormFieldFacade

### getFieldAppearance {#getFieldAppearance-java.lang.String-}
Ottieni i flag del campo.

### getItems {#getItems--}
```
public String [] getItems()
```

Restituisce l'array di elementi

**Returns:**
oggetto String[]

### getRadioButtonItemSize {#getRadioButtonItemSize--}
```
public double getRadioButtonItemSize()
```

Ottiene o imposta la dimensione dell'elemento del pulsante radio (quando viene aggiunto un nuovo campo pulsante radio).

**Returns:**
valore double

### getRadioGap {#getRadioGap--}
```
public float getRadioGap()
```

Ottieni il membro per registrare lo spazio tra due pulsanti radio adiacenti in pixel, il valore predefinito è 50.

**Returns:**
valore float

### getRadioHoriz {#getRadioHoriz--}
```
public boolean getRadioHoriz()
```

Ottieni il flag che indica se i pulsanti radio sono disposti orizzontalmente o verticalmente, il valore predefinito è true.

**Returns:**
valore booleano

### getResponse {#getResponse--}
```
public javax.servlet.http.HttpServletResponse getResponse()
```

Ottiene l'oggetto Response dove verrà memorizzato il risultato dell'operazione.

**Returns:**
Oggetto HttpServletResponse

### getSaveOptions {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```

Ottiene le opzioni di salvataggio quando il risultato è memorizzato come HttpResponse.

**Returns:**
oggetto SaveOptions

### getSrcFileName {#getSrcFileName--}
```
@Deprecated public String getSrcFileName()
```

Obsoleto.

**Returns:**
valore stringa

### getSrcStream {#getSrcStream--}
```
public InputStream getSrcStream()
```

Ottiene lo stream di origine.

**Returns:**
Oggetto InputStream

### getSubmitFlag {#getSubmitFlag--}
```
public SubmitFormFlag getSubmitFlag()
```

Ottieni i flag di invio del pulsante submit

**Returns:**
Elemento SubmitFormFlag

### moveField {#moveField-java.lang.String-float-float-float-float-}
Imposta la nuova posizione del campo.

### removeField {#removeField-java.lang.String-}
Rimuovi il campo dal modulo.

### removeFieldAction {#removeFieldAction-java.lang.String-}
Rimuovi l'azione di invio del campo.

### renameField {#renameField-java.lang.String-java.lang.String-}
Cambia il nome del campo.

### resetFacade {#resetFacade--}
```
public void resetFacade()
```

Reimposta tutti gli attributi visivi a valore vuoto.

### resetInnerFacade {#resetInnerFacade--}
```
public void resetInnerFacade()
```

Reimposta tutti gli attributi visivi della facciata interna a valore vuoto.

### save {#save--}
```
public void save()
```

Salva le modifiche nel file di destinazione.

### setAttachmentName {#setAttachmentName-java.lang.String-}
Imposta il nome dell'allegato quando il risultato dell'operazione viene memorizzato negli oggetti HttpResponse come allegato.

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
Imposta come il contenuto verrà memorizzato quando il risultato dell'operazione è salvato nell'oggetto HttpResponse.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Imposta il formato file PDF PdfFormat.

### setDestFileName {#setDestFileName-java.lang.String-}
Obsoleto.

### setDestStream {#setDestStream-java.io.OutputStream-}
Imposta lo stream di destinazione.

### setExportItems {#setExportItems-java.lang.String:A:A-}
Imposta le opzioni per la casella combinata con valori di esportazione.

### setFacade {#setFacade-com.aspose.pdf.facades.FormFieldFacade-}
Imposta gli attributi visivi del campo.

### setFieldAlignment {#setFieldAlignment-java.lang.String-int-}
Imposta lo stile di allineamento di un campo di testo.

### setFieldAlignmentV {#setFieldAlignmentV-java.lang.String-int-}
Imposta lo stile di allineamento verticale di un campo di testo.

### setFieldAppearance {#setFieldAppearance-java.lang.String-int-}
Imposta i flag del campo

### setFieldAttribute {#setFieldAttribute-java.lang.String-int-}
Imposta gli attributi del campo.

### setFieldCombNumber {#setFieldCombNumber-java.lang.String-int-}
Imposta il numero di denti per un campo di testo a riga singola regolare (il campo è diviso automaticamente in tante posizioni equidistanti, o denti, quanto il valore del parametro combNumber).

### setFieldLimit {#setFieldLimit-java.lang.String-int-}
Imposta il conteggio massimo di caratteri del campo di testo.

### setFieldScript {#setFieldScript-java.lang.String-java.lang.String-}
Imposta JavaScript per un campo PushButton.

### setItems {#setItems-java.lang.String:A-}
Imposta gli elementi che saranno aggiunti alla casella di riepilogo o alla casella combinata appena creata.

### setRadioButtonItemSize {#setRadioButtonItemSize-double-}
```
public void setRadioButtonItemSize(double value)
```

Ottiene o imposta la dimensione dell'elemento del pulsante radio (quando viene aggiunto un nuovo campo pulsante radio).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### setRadioGap {#setRadioGap-float-}
```
public void setRadioGap(float value)
```

Imposta il membro per registrare lo spazio tra due pulsanti radio adiacenti in pixel, il valore predefinito è 50.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore float |

### setRadioHoriz {#setRadioHoriz-boolean-}
```
public void setRadioHoriz(boolean value)
```

Imposta il flag che indica se i pulsanti radio sono disposti orizzontalmente o verticalmente, il valore predefinito è true.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setResponse {#setResponse-javax.servlet.http.HttpServletResponse-}
Imposta l'oggetto Response dove verrà memorizzato il risultato dell'operazione.

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Imposta le opzioni di salvataggio quando il risultato è memorizzato come HttpResponse.

### setSrcFileName {#setSrcFileName-java.lang.String-}
Obsoleto.

### setSrcStream {#setSrcStream-java.io.InputStream-}
Imposta lo stream di origine.

### setSubmitFlag {#setSubmitFlag-java.lang.String-com.aspose.pdf.facades.SubmitFormFlag-}
Imposta il flag di invio del pulsante submit.

### setSubmitFlag {#setSubmitFlag-com.aspose.pdf.facades.SubmitFormFlag-}
Imposta i flag di invio del pulsante di submit

### setSubmitUrl {#setSubmitUrl-java.lang.String-java.lang.String-}
Imposta l'URL del pulsante.

### single2Multiple {#single2Multiple-java.lang.String-}
Trasforma un campo di testo a riga singola in uno a più righe.
