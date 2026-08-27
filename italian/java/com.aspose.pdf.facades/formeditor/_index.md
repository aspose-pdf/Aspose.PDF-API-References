---
title: "FormEditor"
linktitle: "FormEditor"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Classe per la modifica dei moduli (aggiunta/eliminazione di campi ecc.)"
type: docs
weight: 200
url: /it/java/com.aspose.pdf.facades/formeditor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.FormEditor, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.FormEditor, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.FormEditor

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, IFormEditor, ISaveableFacade, Closeable, AutoCloseable

```
public final class FormEditor extends SaveableFacade implements IFormEditor
```

Classe per la modifica dei moduli (aggiunta/eliminazione di campi ecc.)

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [FormEditor](#FormEditor--) | <p> Costruttore per FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre> |
| [FormEditor](#FormEditor-com.aspose.pdf.IDocument-) | <p> Costruttore per FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre> |
| [FormEditor](#FormEditor-com.aspose.pdf.IDocument-java.io.OutputStream-) | <p> Costruttore per FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre> |
| [FormEditor](#FormEditor-com.aspose.pdf.IDocument-java.lang.String-) | <p> Costruttore per FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre> |
| [FormEditor](#FormEditor-java.io.InputStream-java.io.OutputStream-) | <p> Costruttore per FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre> |
| [FormEditor](#FormEditor-java.lang.String-java.lang.String-) | <p> Costruttore per FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre> |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [addField](#addField-com.aspose.pdf.facades.FieldType-java.lang.String-int-float-float-float-float-) | <p> Aggiungi un campo del tipo specificato al modulo. </p> <hr> <pre> FormEditor formEditor = new com.aspose.pdf.facades.FormEditor(\"PdfForm.pdf\", \"FormEditor_AddField_Text.pdf\"); formEditor.addField(FieldType.Text, \"AddedTextField\", 1, 10, 30, 110, 46); formEditor.save(); </pre> |
| [addField](#addField-com.aspose.pdf.facades.FieldType-java.lang.String-java.lang.String-int-float-float-float-float-) | Aggiungi un campo del tipo specificato al modulo. |
| [addFieldScript](#addFieldScript-java.lang.String-java.lang.String-) | Aggiungi JavaScript per un campo PushButton. |
| [addListItem](#addListItem-java.lang.String-java.lang.String-) | <p> Aggiunge un nuovo elemento alla casella di riepilogo. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", PdfForm_out.pdf\"); formEditor.addListItem(\"listBoxField\", \"Item 4 (New Item)\"); </pre> |
| [addListItem](#addListItem-java.lang.String-java.lang.String:A-) | <p> Aggiungi un nuovo elemento con valore Export al campo casella di riepilogo esistente, solo per il campo combo box AcroForm. </p> <hr> <pre> FormEditor fe = new FormEditor(\"PdfForm.pdf\", \"FormEditor_AddListItem2.pdf\"); fe.addListItem(\"listboxField\", new String[] { \"4\", \"Item4(Added)\" }); </pre> |
| [addSubmitBtn](#addSubmitBtn-java.lang.String-int-java.lang.String-java.lang.String-float-float-float-float-) | <p> Aggiungi un pulsante di invio al modulo. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_AddSubmitBtn.pdf\"); formEditor.addSubmitBtn(\"submit\", 1, \"Submit\", \"www.check.com\", 10, 200, 70, 270); </pre> |
| [close](#close--) | Chiudi l'istanza dell'oggetto |
| [copyInnerField](#copyInnerField-java.lang.String-java.lang.String-int-) | Copia un campo esistente nella stessa posizione del numero di pagina specificato. Verrà prodotto un nuovo documento, che contiene tutto ciò che il documento originale ha, eccetto il campo appena copiato. |
| [copyInnerField](#copyInnerField-java.lang.String-java.lang.String-int-float-float-) | Copia un campo esistente in una nuova posizione specificata sia dal numero di pagina sia dalle coordinate. Verrà prodotto un nuovo documento, che contiene tutto ciò che il documento originale ha, eccetto il campo appena copiato. |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-) | Copia un campo esistente da un documento PDF a un altro documento mantenendo il numero di pagina e le coordinate originali. Nota: Solo per i campi AcroForm (esclusi i radio button). |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-int-) | Copia un campo esistente da un documento PDF a un altro documento con il numero di pagina specificato e le coordinate originali. Nota: Solo per i campi AcroForm (esclusi i radio button). |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-int-float-float-) | Copia un campo esistente da un documento PDF a un altro documento con il numero di pagina e le coordinate specificati. Nota: Solo per i campi AcroForm (esclusi i radio button). |
| [decorateField](#decorateField--) | <p> Modifica gli attributi visivi di tutti i campi nel documento PDF. </p> <hr> <pre> FormEditor fe = new FormEditor(\"PdfForm.pdf\", \"FormEditor_DecorateField.pdf\"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.Green); fe.getFacade().setAlignment(FormFieldFacade.AlignRight); // decorate all fields. fe.decorateField(); </pre> |
| [decorateField](#decorateField-com.aspose.pdf.facades.FieldType-) | <p> Modifica gli attributi visivi di tutti i campi nel documento PDF. </p> <hr> <pre> FormEditor fe = new FormEditor(\"PdfForm.pdf\", \"FormEditor_DecorateField.pdf\"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.Green); fe.getFacade().setAlignment(FormFieldFacade.AlignRight); // decorate all fields. fe.decorateField(); </pre> |
| [decorateField](#decorateField-java.lang.String-) | <p> Modifica gli attributi visivi di tutti i campi nel documento PDF. </p> <hr> <pre> FormEditor fe = new FormEditor(\"PdfForm.pdf\", \"FormEditor_DecorateField.pdf\"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.Green); fe.getFacade().setAlignment(FormFieldFacade.AlignRight); // decorate all fields. fe.decorateField(); </pre> |
| [delListItem](#delListItem-java.lang.String-java.lang.String-) | <p> Elimina l'elemento dal campo elenco. </p> <hr> <pre> formEditor = new com.aspose.pdf.facades.FormEditor(\"PdfForm.pdf\", \"FormEditor_DelListItem.pdf\"); formEditor.delListItem(\"listboxField\", \"item2\"); </pre> |
| [dispose](#dispose--) | Chiudi l'istanza dell'oggetto Questo metodo è obsoleto, usa close() invece. |
| [getAttachmentName](#getAttachmentName--) | Ottiene il nome dell'allegato quando il risultato dell'operazione viene memorizzato negli oggetti HttpResponse come allegato. |
| [getContentDisposition](#getContentDisposition--) | Ottiene come il contenuto verrà memorizzato quando il risultato dell'operazione viene memorizzato nell'oggetto HttpResponse. Valore possibile: inline / attachment. Predefinito: inline. |
| [getDestFileName](#getDestFileName--) | Ottiene il nome del file di destinazione. |
| [getDestStream](#getDestStream--) | <p> Ottiene lo stream di destinazione. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setDestStream(new FileInputStream(\"OutFile.pdf\")); </pre> |
| [getDocument](#getDocument--) | Ottiene il documento {@code FormEditor} su cui sta lavorando. |
| [getExportItems](#getExportItems--) | <p> Ottiene le opzioni per la casella combinata con valori di esportazione. </p> <hr> |
| [getFacade](#getFacade--) | Ottiene gli attributi visivi del campo. |
| [getFieldAppearance](#getFieldAppearance-java.lang.String-) | Ottieni i flag del campo. |
| [getItems](#getItems--) | Ottieni gli elementi che saranno aggiunti alla casella di riepilogo o alla casella combinata appena creata. |
| [getRadioButtonItemSize](#getRadioButtonItemSize--) | Ottiene o imposta la dimensione dell'elemento del pulsante radio (quando viene aggiunto un nuovo campo pulsante radio). FormEditor formEditor = new com.aspose.pdf.facades.FormEditor(\"PdfForm.pdf\", \"FormEditor_AddField_RadioButton.pdf\"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setRadioButtonItemSize(20); formEditor.setItems(new String[] { \"First\", \"Second\", \"Third\" }); formEditor.addField(com.aspose.pdf.facades.FieldType.Radio, \"AddedRadioButtonField\", \"Second\", 1, 10, 30, 110, 130); formEditor.save(); |
| [getRadioGap](#getRadioGap--) | Ottieni il membro per registrare lo spazio tra due pulsanti radio adiacenti in pixel, il valore predefinito è 50. |
| [getRadioHoriz](#getRadioHoriz--) | <p> Ottieni il flag per indicare se i pulsanti radio sono disposti orizzontalmente o verticalmente, il valore predefinito è true. |
| [getSaveOptions](#getSaveOptions--) | Ottiene le opzioni di salvataggio quando il risultato è memorizzato come HttpResponse. Valore predefinito: PdfSaveOptions. |
| [getSrcFileName](#getSrcFileName--) | Ottiene il nome del file sorgente. |
| [getSrcStream](#getSrcStream--) | Ottiene lo stream di origine. |
| [getSubmitFlag](#getSubmitFlag--) | Ottieni i flag di invio del pulsante submit |
| [moveField](#moveField-java.lang.String-float-float-float-float-) | <p> Imposta la nuova posizione del campo. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_MoveField.pdf\"); formEditor.moveField(\"textField\", 20.5f, 20.3f, 120.6f, 40.8f); </pre> |
| [removeField](#removeField-java.lang.String-) | <p> Rimuovi il campo dal modulo. </p> <hr> <pre> FormEditr formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_RemoveField.pdf\"); formEditor.removeField(\"listboxField\"); formEditor.removeField(\"textField\"); </pre> |
| [removeFieldAction](#removeFieldAction-java.lang.String-) | <p> Rimuovi l'azione di invio del campo. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_RemoveFieldAction.pdf\"); formEditor.removeFieldAction(\"btnSubmit\"); </pre> |
| [renameField](#renameField-java.lang.String-java.lang.String-) | <p> Cambia il nome del campo. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"PdfForm_updated.pdf\"); formEditor.renameField(\"textField\", \"textField_Renamed\"); </pre> |
| [resetFacade](#resetFacade--) | Reimposta tutti gli attributi visivi a valore vuoto. |
| [resetInnerFacade](#resetInnerFacade--) | Reimposta tutti gli attributi visivi della facciata interna a valore vuoto. |
| [save](#save--) | Salva le modifiche nel file di destinazione. |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | Imposta il nome dell'allegato quando il risultato dell'operazione viene memorizzato negli oggetti HttpResponse come allegato. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | Imposta come verrà memorizzato il contenuto quando il risultato dell'operazione viene memorizzato nell'oggetto HttpResponse. Valore possibile: inline / attachment. Predefinito: inline. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | Imposta il formato del file PDF {@link PdfFormat}. Il file risultante verrà salvato nel formato di file specificato. Se questa proprietà non è specificata, il file verrà salvato nel formato PDF predefinito senza conversione. |
| [setDestFileName](#setDestFileName-java.lang.String-) | <p> Imposta il nome del file di destinazione. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setDestFileName("OutFile.pdf"); </pre> |
| [setDestStream](#setDestStream-java.io.OutputStream-) | <p> Imposta lo stream di destinazione. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setDestStream(new FileInputStream("OutFile.pdf")); </pre> |
| [setExportItems](#setExportItems-java.lang.String:A:A-) | <p> Imposta le opzioni per la casella combinata con valori di esportazione. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_Updated.pdf")); formEditor.setExportItems ( new String[][] { new String[] { "1", "Firs" }, new String[] { "2", "Second" }, new String[] { "3", "Third" } }); formEditor.addField(FieldType.ListBox, "AddedListBoxField", "Second", 1, 10, 30, 110, 130); formEditor.save(); </pre> |
| [setFacade](#setFacade-com.aspose.pdf.facades.FormFieldFacade-) | <p> Imposta gli attributi visivi del campo. </p> <hr> <pre> FormEditor fe = new FormEditor("PdfForm.pdf", "PdfForm_DecorateField_text.pdf"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.green); fe.getFacade().setAlignment(FormFieldFacade.AlignCenter); fe.setDecorateField("textField"); fe.save(); </pre> |
| [setFieldAlignment](#setFieldAlignment-java.lang.String-int-) | <p> Imposta lo stile di allineamento di un campo di testo. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_updated.pdf")); formEditor.setFieldAlignment(fieldName, FormFieldFacade.AlignCenter); </pre> |
| [setFieldAlignmentV](#setFieldAlignmentV-java.lang.String-int-) | <p> Imposta lo stile di allineamento verticale di un campo di testo. </p> <hr> <pre> FormEditor fe = new FormEditor("PdfStaticForm.pdf", "VerticalAlign.pdf"); fe.setFieldAlignmentV("form1[0].TextField[0]", FormFieldFacade.AlignBottom); </pre> |
| [setFieldAppearance](#setFieldAppearance-java.lang.String-int-) | <p> Set field flags </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm1.pdf", "FormEditor_SetFieldAppearance.pdf"); formEditor.setFieldAppearance("Name", AnnotationFlags.Hidden); formEditor.setFieldAppearance("Phone", AnnotationFlags.NoView \ | AnnotationFlags.Print); </pre> |
| [setFieldAttribute](#setFieldAttribute-java.lang.String-int-) | <p> Imposta gli attributi del campo. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_SetFieldAttribute.pdf"); formEditor.setFieldAttribute("listboxField", PropertyFlag.ReadOnly); formEditor.setFieldAttribute("textField", PropertyFlag.NoExport); </pre> |
| [setFieldCombNumber](#setFieldCombNumber-java.lang.String-int-) | <p> Imposta il numero di combs per un campo di testo a riga singola regolare (il campo è suddiviso automaticamente in tante posizioni equidistanti, o combs, quanto il valore del parametro combNumber). </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfWithAcroForm.pdf", "FormEditor_SetFieldComb.pdf")); formEditor.setFieldCombNumber("textCombField", 5); </pre> |
| [setFieldLimit](#setFieldLimit-java.lang.String-int-) | <p> Imposta il conteggio massimo di caratteri del campo di testo. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetFieldLimit.pdf"); formEditor.setFieldLimit("textField", 15); </pre> |
| [setFieldScript](#setFieldScript-java.lang.String-java.lang.String-) | Imposta JavaScript per un campo PushButton. Se esisteva JavaScript precedente, verrà sostituito da quello nuovo. |
| [setItems](#setItems-java.lang.String:A-) | <p> Imposta gli elementi che saranno aggiunti alla casella di elenco o alla casella combinata appena creata. </p> <hr> <pre> formEditor = new com.aspose.pdf.facadesFormEditor("input.pdf", "output.pdf"); formEditor.setItems(new String[] { "AAA", "BBB", "CCC" }); formEditor.addField(FieldType.ListBox, "AddedListBoxField", "BBB", 1, 10, 30, 110, 130); formEditor.save(); </pre> |
| [setRadioButtonItemSize](#setRadioButtonItemSize-double-) | Ottiene o imposta la dimensione dell'elemento del pulsante radio (quando viene aggiunto un nuovo campo pulsante radio). FormEditor formEditor = new com.aspose.pdf.facades.FormEditor(\"PdfForm.pdf\", \"FormEditor_AddField_RadioButton.pdf\"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setRadioButtonItemSize(20); formEditor.setItems(new String[] { \"First\", \"Second\", \"Third\" }); formEditor.addField(com.aspose.pdf.facades.FieldType.Radio, \"AddedRadioButtonField\", \"Second\", 1, 10, 30, 110, 130); formEditor.save(); |
| [setRadioGap](#setRadioGap-float-) | <p> Imposta il membro per registrare lo spazio tra due pulsanti radio adiacenti in pixel, il valore predefinito è 50. </p> <hr> <pre> formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setItems(new String[] { "First", "Second", "Third" }); formEditor.addField(FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130); formEditor.save(); </pre> |
| [setRadioHoriz](#setRadioHoriz-boolean-) | <p> Imposta il flag per indicare se i radio button sono disposti orizzontalmente o verticalmente, il valore predefinito è true. </p> <hr> <pre> formEditor = new com.aspose.pdf.facades.FormEditor(\"PdfForm.pdf\", \"FormEditor_AddField_RadioButton.pdf\"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setItems(new String[] { \"First\", \"Second\", \"Third\" }); formEditor.addField(FieldType.Radio, \"AddedRadioButtonField\", \"Second\", 1, 10, 30, 110, 130); formEditor.save(); </pre> |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Imposta le opzioni di salvataggio quando il risultato viene memorizzato come HttpResponse. Valore predefinito: PdfSaveOptions. |
| [setSrcFileName](#setSrcFileName-java.lang.String-) | <p> Imposta il nome del file di origine. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setSrcFileName(\"InputFile.pdf\"); </pre> |
| [setSrcStream](#setSrcStream-java.io.InputStream-) | <p> Imposta lo stream di origine. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setSrcStream(new FileInputStream(\"InFile.pdf\")); </pre> |
| [setSubmitFlag](#setSubmitFlag-java.lang.String-com.aspose.pdf.facades.SubmitFormFlag-) | <p> Imposta il flag di invio del pulsante di submit. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_SetSubmitFlag.pdf\"); formEditor.setSubmitFlag(\"btnSubmit\", SubmitFormFlag.Fdf); </pre> |
| [setSubmitFlag](#setSubmitFlag-com.aspose.pdf.facades.SubmitFormFlag-) | Imposta i flag di invio del pulsante di submit |
| [setSubmitUrl](#setSubmitUrl-java.lang.String-java.lang.String-) | <p> Imposta l'URL del pulsante. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_SetSubmitUrl.pdf\"); formEditor.setSubmitUrl(\"btnSubmit\", \"www.mysite.com\"); </pre> |
| [single2Multiple](#single2Multiple-java.lang.String-) | <p> Converti un campo di testo a riga singola in uno a più righe. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"PdfForm_updated.pdf\"); formEditor.single2Multiple(\"textField\"); </pre> |

### FormEditor {#FormEditor--}
```
public FormEditor()
```

<p> Costruttore per FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre>

### FormEditor {#FormEditor-com.aspose.pdf.IDocument-}
<p> Costruttore per FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre>

### FormEditor {#FormEditor-com.aspose.pdf.IDocument-java.io.OutputStream-}
<p> Costruttore per FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre>

### FormEditor {#FormEditor-com.aspose.pdf.IDocument-java.lang.String-}
<p> Costruttore per FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre>

### FormEditor {#FormEditor-java.io.InputStream-java.io.OutputStream-}
<p> Costruttore per FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre>

### FormEditor {#FormEditor-java.lang.String-java.lang.String-}
<p> Costruttore per FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre>

### addField {#addField-com.aspose.pdf.facades.FieldType-java.lang.String-int-float-float-float-float-}
<p> Aggiungi un campo del tipo specificato al modulo. </p> <hr> <pre> FormEditor formEditor = new com.aspose.pdf.facades.FormEditor(\"PdfForm.pdf\", \"FormEditor_AddField_Text.pdf\"); formEditor.addField(FieldType.Text, \"AddedTextField\", 1, 10, 30, 110, 46); formEditor.save(); </pre>

### addField {#addField-com.aspose.pdf.facades.FieldType-java.lang.String-java.lang.String-int-float-float-float-float-}
Aggiungi un campo del tipo specificato al modulo.

### addFieldScript {#addFieldScript-java.lang.String-java.lang.String-}
Aggiungi JavaScript per un campo PushButton.

### addListItem {#addListItem-java.lang.String-java.lang.String-}
<p> Aggiunge un nuovo elemento alla casella di riepilogo. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", PdfForm_out.pdf\"); formEditor.addListItem(\"listBoxField\", \"Item 4 (New Item)\"); </pre>

### addListItem {#addListItem-java.lang.String-java.lang.String:A-}
<p> Aggiungi un nuovo elemento con valore Export al campo casella di riepilogo esistente, solo per il campo combo box AcroForm. </p> <hr> <pre> FormEditor fe = new FormEditor(\"PdfForm.pdf\", \"FormEditor_AddListItem2.pdf\"); fe.addListItem(\"listboxField\", new String[] { \"4\", \"Item4(Added)\" }); </pre>

### addSubmitBtn {#addSubmitBtn-java.lang.String-int-java.lang.String-java.lang.String-float-float-float-float-}
<p> Aggiungi un pulsante di invio al modulo. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_AddSubmitBtn.pdf\"); formEditor.addSubmitBtn(\"submit\", 1, \"Submit\", \"www.check.com\", 10, 200, 70, 270); </pre>

### close {#close--}
```
public void close()
```

Chiudi l'istanza dell'oggetto

### copyInnerField {#copyInnerField-java.lang.String-java.lang.String-int-}
Copia un campo esistente nella stessa posizione del numero di pagina specificato. Verrà prodotto un nuovo documento, che contiene tutto ciò che il documento originale ha, eccetto il campo appena copiato.

### copyInnerField {#copyInnerField-java.lang.String-java.lang.String-int-float-float-}
Copia un campo esistente in una nuova posizione specificata sia dal numero di pagina sia dalle coordinate. Verrà prodotto un nuovo documento, che contiene tutto ciò che il documento originale ha, eccetto il campo appena copiato.

### copyOuterField {#copyOuterField-java.lang.String-java.lang.String-}
Copia un campo esistente da un documento PDF a un altro documento mantenendo il numero di pagina e le coordinate originali. Nota: Solo per i campi AcroForm (esclusi i radio button).

### copyOuterField {#copyOuterField-java.lang.String-java.lang.String-int-}
Copia un campo esistente da un documento PDF a un altro documento con il numero di pagina specificato e le coordinate originali. Nota: Solo per i campi AcroForm (esclusi i radio button).

### copyOuterField {#copyOuterField-java.lang.String-java.lang.String-int-float-float-}
Copia un campo esistente da un documento PDF a un altro documento con il numero di pagina e le coordinate specificati. Nota: Solo per i campi AcroForm (esclusi i radio button).

### decorateField {#decorateField--}
```
public void decorateField()
```

<p> Modifica gli attributi visivi di tutti i campi nel documento PDF. </p> <hr> <pre> FormEditor fe = new FormEditor(\"PdfForm.pdf\", \"FormEditor_DecorateField.pdf\"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.Green); fe.getFacade().setAlignment(FormFieldFacade.AlignRight); // decorate all fields. fe.decorateField(); </pre>

### decorateField {#decorateField-com.aspose.pdf.facades.FieldType-}
<p> Modifica gli attributi visivi di tutti i campi nel documento PDF. </p> <hr> <pre> FormEditor fe = new FormEditor(\"PdfForm.pdf\", \"FormEditor_DecorateField.pdf\"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.Green); fe.getFacade().setAlignment(FormFieldFacade.AlignRight); // decorate all fields. fe.decorateField(); </pre>

### decorateField {#decorateField-java.lang.String-}
<p> Modifica gli attributi visivi di tutti i campi nel documento PDF. </p> <hr> <pre> FormEditor fe = new FormEditor(\"PdfForm.pdf\", \"FormEditor_DecorateField.pdf\"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.Green); fe.getFacade().setAlignment(FormFieldFacade.AlignRight); // decorate all fields. fe.decorateField(); </pre>

### delListItem {#delListItem-java.lang.String-java.lang.String-}
<p> Elimina l'elemento dal campo elenco. </p> <hr> <pre> formEditor = new com.aspose.pdf.facades.FormEditor(\"PdfForm.pdf\", \"FormEditor_DelListItem.pdf\"); formEditor.delListItem(\"listboxField\", \"item2\"); </pre>

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Chiudi l'istanza dell'oggetto Questo metodo è obsoleto, usa close() invece.

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

Ottiene come il contenuto verrà memorizzato quando il risultato dell'operazione viene memorizzato nell'oggetto HttpResponse. Valore possibile: inline / attachment. Predefinito: inline.

**Returns:**
Elemento ContentDisposition @see ContentDisposition

### getDestFileName {#getDestFileName--}
```
public String getDestFileName()
```

Ottiene il nome del file di destinazione.

**Returns:**
oggetto stringa

### getDestStream {#getDestStream--}
```
public OutputStream getDestStream()
```

<p> Ottiene lo stream di destinazione. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setDestStream(new FileInputStream(\"OutFile.pdf\")); </pre>

**Returns:**
oggetto OutputStream

### getDocument {#getDocument--}
```
public IDocument getDocument()
```

Ottiene il documento {@code FormEditor} su cui sta lavorando.

**Returns:**
Oggetto IDocument

### getExportItems {#getExportItems--}
```
public String [][] getExportItems()
```

<p> Ottiene le opzioni per la casella combinata con valori di esportazione. </p> <hr>

**Returns:**
oggetto String[][]

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

Ottieni gli elementi che saranno aggiunti alla casella di riepilogo o alla casella combinata appena creata.

**Returns:**
oggetto String[]

### getRadioButtonItemSize {#getRadioButtonItemSize--}
```
public double getRadioButtonItemSize()
```

Ottiene o imposta la dimensione dell'elemento del pulsante radio (quando viene aggiunto un nuovo campo pulsante radio). FormEditor formEditor = new com.aspose.pdf.facades.FormEditor(\"PdfForm.pdf\", \"FormEditor_AddField_RadioButton.pdf\"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setRadioButtonItemSize(20); formEditor.setItems(new String[] { \"First\", \"Second\", \"Third\" }); formEditor.addField(com.aspose.pdf.facades.FieldType.Radio, \"AddedRadioButtonField\", \"Second\", 1, 10, 30, 110, 130); formEditor.save();

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

<p> Ottieni il flag per indicare se i pulsanti radio sono disposti orizzontalmente o verticalmente, il valore predefinito è true.

**Returns:**
valore booleano

### getSaveOptions {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```

Ottiene le opzioni di salvataggio quando il risultato è memorizzato come HttpResponse. Valore predefinito: PdfSaveOptions.

**Returns:**
oggetto SaveOptions

### getSrcFileName {#getSrcFileName--}
```
public String getSrcFileName()
```

Ottiene il nome del file sorgente.

**Returns:**
oggetto stringa

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
Elemento SubmitFormFlag @see SubmitFormFlag

### moveField {#moveField-java.lang.String-float-float-float-float-}
<p> Imposta la nuova posizione del campo. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_MoveField.pdf\"); formEditor.moveField(\"textField\", 20.5f, 20.3f, 120.6f, 40.8f); </pre>

### removeField {#removeField-java.lang.String-}
<p> Rimuovi il campo dal modulo. </p> <hr> <pre> FormEditr formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_RemoveField.pdf\"); formEditor.removeField(\"listboxField\"); formEditor.removeField(\"textField\"); </pre>

### removeFieldAction {#removeFieldAction-java.lang.String-}
<p> Rimuovi l'azione di invio del campo. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_RemoveFieldAction.pdf\"); formEditor.removeFieldAction(\"btnSubmit\"); </pre>

### renameField {#renameField-java.lang.String-java.lang.String-}
<p> Cambia il nome del campo. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"PdfForm_updated.pdf\"); formEditor.renameField(\"textField\", \"textField_Renamed\"); </pre>

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
@Deprecated public void save()
```

Salva le modifiche nel file di destinazione.

### setAttachmentName {#setAttachmentName-java.lang.String-}
Imposta il nome dell'allegato quando il risultato dell'operazione viene memorizzato negli oggetti HttpResponse come allegato.

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
Imposta come verrà memorizzato il contenuto quando il risultato dell'operazione viene memorizzato nell'oggetto HttpResponse. Valore possibile: inline / attachment. Predefinito: inline.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Imposta il formato del file PDF {@link PdfFormat}. Il file risultante verrà salvato nel formato di file specificato. Se questa proprietà non è specificata, il file verrà salvato nel formato PDF predefinito senza conversione.

### setDestFileName {#setDestFileName-java.lang.String-}
<p> Imposta il nome del file di destinazione. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setDestFileName("OutFile.pdf"); </pre>

### setDestStream {#setDestStream-java.io.OutputStream-}
<p> Imposta lo stream di destinazione. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setDestStream(new FileInputStream("OutFile.pdf")); </pre>

### setExportItems {#setExportItems-java.lang.String:A:A-}
<p> Imposta le opzioni per la casella combinata con valori di esportazione. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_Updated.pdf")); formEditor.setExportItems ( new String[][] { new String[] { "1", "Firs" }, new String[] { "2", "Second" }, new String[] { "3", "Third" } }); formEditor.addField(FieldType.ListBox, "AddedListBoxField", "Second", 1, 10, 30, 110, 130); formEditor.save(); </pre>

### setFacade {#setFacade-com.aspose.pdf.facades.FormFieldFacade-}
<p> Imposta gli attributi visivi del campo. </p> <hr> <pre> FormEditor fe = new FormEditor("PdfForm.pdf", "PdfForm_DecorateField_text.pdf"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.green); fe.getFacade().setAlignment(FormFieldFacade.AlignCenter); fe.setDecorateField("textField"); fe.save(); </pre>

### setFieldAlignment {#setFieldAlignment-java.lang.String-int-}
<p> Imposta lo stile di allineamento di un campo di testo. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_updated.pdf")); formEditor.setFieldAlignment(fieldName, FormFieldFacade.AlignCenter); </pre>

### setFieldAlignmentV {#setFieldAlignmentV-java.lang.String-int-}
<p> Imposta lo stile di allineamento verticale di un campo di testo. </p> <hr> <pre> FormEditor fe = new FormEditor("PdfStaticForm.pdf", "VerticalAlign.pdf"); fe.setFieldAlignmentV("form1[0].TextField[0]", FormFieldFacade.AlignBottom); </pre>

### setFieldAppearance {#setFieldAppearance-java.lang.String-int-}
<p> Imposta i flag del campo </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm1.pdf\", \"FormEditor_SetFieldAppearance.pdf\"); formEditor.setFieldAppearance(\"Name\", AnnotationFlags.Hidden); formEditor.setFieldAppearance(\"Phone\", AnnotationFlags.NoView | AnnotationFlags.Print); </pre>

### setFieldAttribute {#setFieldAttribute-java.lang.String-int-}
<p> Imposta gli attributi del campo. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_SetFieldAttribute.pdf"); formEditor.setFieldAttribute("listboxField", PropertyFlag.ReadOnly); formEditor.setFieldAttribute("textField", PropertyFlag.NoExport); </pre>

### setFieldCombNumber {#setFieldCombNumber-java.lang.String-int-}
<p> Imposta il numero di combs per un campo di testo a riga singola regolare (il campo è suddiviso automaticamente in tante posizioni equidistanti, o combs, quanto il valore del parametro combNumber). </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfWithAcroForm.pdf", "FormEditor_SetFieldComb.pdf")); formEditor.setFieldCombNumber("textCombField", 5); </pre>

### setFieldLimit {#setFieldLimit-java.lang.String-int-}
<p> Imposta il conteggio massimo di caratteri del campo di testo. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetFieldLimit.pdf"); formEditor.setFieldLimit("textField", 15); </pre>

### setFieldScript {#setFieldScript-java.lang.String-java.lang.String-}
Imposta JavaScript per un campo PushButton. Se esisteva JavaScript precedente, verrà sostituito da quello nuovo.

### setItems {#setItems-java.lang.String:A-}
<p> Imposta gli elementi che saranno aggiunti alla casella di elenco o alla casella combinata appena creata. </p> <hr> <pre> formEditor = new com.aspose.pdf.facadesFormEditor("input.pdf", "output.pdf"); formEditor.setItems(new String[] { "AAA", "BBB", "CCC" }); formEditor.addField(FieldType.ListBox, "AddedListBoxField", "BBB", 1, 10, 30, 110, 130); formEditor.save(); </pre>

### setRadioButtonItemSize {#setRadioButtonItemSize-double-}
```
public void setRadioButtonItemSize(double value)
```

Ottiene o imposta la dimensione dell'elemento del pulsante radio (quando viene aggiunto un nuovo campo pulsante radio). FormEditor formEditor = new com.aspose.pdf.facades.FormEditor(\"PdfForm.pdf\", \"FormEditor_AddField_RadioButton.pdf\"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setRadioButtonItemSize(20); formEditor.setItems(new String[] { \"First\", \"Second\", \"Third\" }); formEditor.addField(com.aspose.pdf.facades.FieldType.Radio, \"AddedRadioButtonField\", \"Second\", 1, 10, 30, 110, 130); formEditor.save();

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### setRadioGap {#setRadioGap-float-}
```
public void setRadioGap(float value)
```

<p> Imposta il membro per registrare lo spazio tra due pulsanti radio adiacenti in pixel, il valore predefinito è 50. </p> <hr> <pre> formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setItems(new String[] { "First", "Second", "Third" }); formEditor.addField(FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130); formEditor.save(); </pre>

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore float |

### setRadioHoriz {#setRadioHoriz-boolean-}
```
public void setRadioHoriz(boolean value)
```

<p> Imposta il flag per indicare se i radio button sono disposti orizzontalmente o verticalmente, il valore predefinito è true. </p> <hr> <pre> formEditor = new com.aspose.pdf.facades.FormEditor(\"PdfForm.pdf\", \"FormEditor_AddField_RadioButton.pdf\"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setItems(new String[] { \"First\", \"Second\", \"Third\" }); formEditor.addField(FieldType.Radio, \"AddedRadioButtonField\", \"Second\", 1, 10, 30, 110, 130); formEditor.save(); </pre>

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Imposta le opzioni di salvataggio quando il risultato viene memorizzato come HttpResponse. Valore predefinito: PdfSaveOptions.

### setSrcFileName {#setSrcFileName-java.lang.String-}
<p> Imposta il nome del file di origine. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setSrcFileName(\"InputFile.pdf\"); </pre>

### setSrcStream {#setSrcStream-java.io.InputStream-}
<p> Imposta lo stream di origine. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setSrcStream(new FileInputStream(\"InFile.pdf\")); </pre>

### setSubmitFlag {#setSubmitFlag-java.lang.String-com.aspose.pdf.facades.SubmitFormFlag-}
<p> Imposta il flag di invio del pulsante di submit. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_SetSubmitFlag.pdf\"); formEditor.setSubmitFlag(\"btnSubmit\", SubmitFormFlag.Fdf); </pre>

### setSubmitFlag {#setSubmitFlag-com.aspose.pdf.facades.SubmitFormFlag-}
Imposta i flag di invio del pulsante di submit

### setSubmitUrl {#setSubmitUrl-java.lang.String-java.lang.String-}
<p> Imposta l'URL del pulsante. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_SetSubmitUrl.pdf\"); formEditor.setSubmitUrl(\"btnSubmit\", \"www.mysite.com\"); </pre>

### single2Multiple {#single2Multiple-java.lang.String-}
<p> Converti un campo di testo a riga singola in uno a più righe. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"PdfForm_updated.pdf\"); formEditor.single2Multiple(\"textField\"); </pre>
