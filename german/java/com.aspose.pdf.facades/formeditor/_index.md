---
title: "FormEditor"
linktitle: "FormEditor"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Klasse zum Bearbeiten von Formularen (Hinzufügen/Löschen von Feldern usw.)"
type: docs
weight: 200
url: /de/java/com.aspose.pdf.facades/formeditor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.FormEditor, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.FormEditor, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.FormEditor

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, IFormEditor, ISaveableFacade, Closeable, AutoCloseable

```
public final class FormEditor extends SaveableFacade implements IFormEditor
```

Klasse zum Bearbeiten von Formularen (Hinzufügen/Löschen von Feldern usw.)

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [FormEditor](#FormEditor--) | <p> Konstruktor für FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre> |
| [FormEditor](#FormEditor-com.aspose.pdf.IDocument-) | <p> Konstruktor für FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre> |
| [FormEditor](#FormEditor-com.aspose.pdf.IDocument-java.io.OutputStream-) | <p> Konstruktor für FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre> |
| [FormEditor](#FormEditor-com.aspose.pdf.IDocument-java.lang.String-) | <p> Konstruktor für FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre> |
| [FormEditor](#FormEditor-java.io.InputStream-java.io.OutputStream-) | <p> Konstruktor für FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre> |
| [FormEditor](#FormEditor-java.lang.String-java.lang.String-) | <p> Konstruktor für FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre> |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [addField](#addField-com.aspose.pdf.facades.FieldType-java.lang.String-int-float-float-float-float-) | <p> Fügt ein Feld des angegebenen Typs zum Formular hinzu. </p> <hr> <pre> FormEditor formEditor = new com.aspose.pdf.facades.FormEditor(\"PdfForm.pdf\", \"FormEditor_AddField_Text.pdf\"); formEditor.addField(FieldType.Text, \"AddedTextField\", 1, 10, 30, 110, 46); formEditor.save(); </pre> |
| [addField](#addField-com.aspose.pdf.facades.FieldType-java.lang.String-java.lang.String-int-float-float-float-float-) | Fügt ein Feld des angegebenen Typs zum Formular hinzu. |
| [addFieldScript](#addFieldScript-java.lang.String-java.lang.String-) | Fügt JavaScript für ein PushButton-Feld hinzu. |
| [addListItem](#addListItem-java.lang.String-java.lang.String-) | <p> Fügt ein neues Element zur Listbox hinzu. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", PdfForm_out.pdf\"); formEditor.addListItem(\"listBoxField\", \"Item 4 (New Item)\"); </pre> |
| [addListItem](#addListItem-java.lang.String-java.lang.String:A-) | <p> Fügt ein neues Element mit Exportwert zum bestehenden Listbox-Feld hinzu, nur für AcroForm-Combo-Box-Feld. </p> <hr> <pre> FormEditor fe = new FormEditor(\"PdfForm.pdf\", \"FormEditor_AddListItem2.pdf\"); fe.addListItem(\"listboxField\", new String[] { \"4\", \"Item4(Added)\" }); </pre> |
| [addSubmitBtn](#addSubmitBtn-java.lang.String-int-java.lang.String-java.lang.String-float-float-float-float-) | <p> Fügt dem Formular einen Submit-Button hinzu. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_AddSubmitBtn.pdf\"); formEditor.addSubmitBtn(\"submit\", 1, \"Submit\", \"www.check.com\", 10, 200, 70, 270); </pre> |
| [close](#close--) | Objektinstanz schließen |
| [copyInnerField](#copyInnerField-java.lang.String-java.lang.String-int-) | Kopiert ein vorhandenes Feld an dieselbe Position in der angegebenen Seitennummer. Es wird ein neues Dokument erstellt, das alles enthält, was das Quelldokument hat, außer dem neu kopierten Feld. |
| [copyInnerField](#copyInnerField-java.lang.String-java.lang.String-int-float-float-) | Kopiert ein vorhandenes Feld an eine neue Position, die sowohl durch die Seitennummer als auch durch die Koordinaten angegeben ist. Es wird ein neues Dokument erstellt, das alles enthält, was das Quelldokument hat, außer dem neu kopierten Feld. |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-) | Kopiert ein vorhandenes Feld von einem PDF-Dokument in ein anderes Dokument mit ursprünglicher Seitennummer und Koordinaten. Hinweis: Nur für AcroForm-Felder (ohne Optionsfeld). |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-int-) | Kopiert ein vorhandenes Feld von einem PDF-Dokument in ein anderes Dokument mit angegebener Seitennummer und ursprünglichen Koordinaten. Hinweis: Nur für AcroForm-Felder (ohne Optionsfeld). |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-int-float-float-) | Kopiert ein vorhandenes Feld von einem PDF-Dokument in ein anderes Dokument mit angegebener Seitennummer und Koordinaten. Hinweis: Nur für AcroForm-Felder (ohne Optionsfeld). |
| [decorateField](#decorateField--) | <p> Ändert die visuellen Attribute aller Felder im PDF-Dokument. </p> <hr> <pre> FormEditor fe = new FormEditor("PdfForm.pdf", "FormEditor_DecorateField.pdf"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.Green); fe.getFacade().setAlignment(FormFieldFacade.AlignRight); // decorate all fields. fe.decorateField(); </pre> |
| [decorateField](#decorateField-com.aspose.pdf.facades.FieldType-) | <p> Ändert die visuellen Attribute aller Felder im PDF-Dokument. </p> <hr> <pre> FormEditor fe = new FormEditor("PdfForm.pdf", "FormEditor_DecorateField.pdf"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.Green); fe.getFacade().setAlignment(FormFieldFacade.AlignRight); // decorate all fields. fe.decorateField(); </pre> |
| [decorateField](#decorateField-java.lang.String-) | <p> Ändert die visuellen Attribute aller Felder im PDF-Dokument. </p> <hr> <pre> FormEditor fe = new FormEditor("PdfForm.pdf", "FormEditor_DecorateField.pdf"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.Green); fe.getFacade().setAlignment(FormFieldFacade.AlignRight); // decorate all fields. fe.decorateField(); </pre> |
| [delListItem](#delListItem-java.lang.String-java.lang.String-) | <p> Löscht ein Element aus dem Listenfeld. </p> <hr> <pre> formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_DelListItem.pdf"); formEditor.delListItem("listboxField", "item2"); </pre> |
| [dispose](#dispose--) | Objektinstanz schließen Diese Methode ist veraltet, verwenden Sie stattdessen close(). |
| [getAttachmentName](#getAttachmentName--) | Ermittelt den Namen des Anhangs, wenn das Ergebnis der Operation in HttpResponse-Objekten als Anhang gespeichert wird. |
| [getContentDisposition](#getContentDisposition--) | Ermittelt, wie der Inhalt gespeichert wird, wenn das Ergebnis der Operation in einem HttpResponse-Objekt gespeichert wird. Mögliche Werte: inline / attachment. Standard: inline. |
| [getDestFileName](#getDestFileName--) | Ermittelt den Ziel-Dateinamen. |
| [getDestStream](#getDestStream--) | <p> Ermittelt den Ziel-Stream. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setDestStream(new FileInputStream("OutFile.pdf")); </pre> |
| [getDocument](#getDocument--) | Ermittelt das Dokument, an dem {@code FormEditor} arbeitet. |
| [getExportItems](#getExportItems--) | <p> Ermittelt Optionen für das Kombinationsfeld mit Exportwerten. </p> <hr> |
| [getFacade](#getFacade--) | Ermittelt die visuellen Attribute des Feldes. |
| [getFieldAppearance](#getFieldAppearance-java.lang.String-) | Ermittelt Feld-Flags. |
| [getItems](#getItems--) | Ermittelt Elemente, die zu einer neu erstellten Listbox oder einem Kombinationsfeld hinzugefügt werden. |
| [getRadioButtonItemSize](#getRadioButtonItemSize--) | Ermittelt oder setzt die Größe des Radio-Button-Elements (wenn ein neues Radio-Button-Feld hinzugefügt wird). FormEditor formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setRadioButtonItemSize(20); formEditor.setItems(new String[] { "First", "Second", "Third" }); formEditor.addField(com.aspose.pdf.facades.FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130); formEditor.save(); |
| [getRadioGap](#getRadioGap--) | Ermittelt das Mitglied, das den Abstand zwischen zwei benachbarten Radio-Buttons in Pixeln speichert, Standard ist 50. |
| [getRadioHoriz](#getRadioHoriz--) | <p> Ermittelt das Flag, das angibt, ob die Radio-Buttons horizontal oder vertikal angeordnet sind, Standardwert ist true. |
| [getSaveOptions](#getSaveOptions--) | Ermittelt die Speicheroptionen, wenn das Ergebnis als HttpResponse gespeichert wird. Standardwert: PdfSaveOptions. |
| [getSrcFileName](#getSrcFileName--) | Ermittelt den Namen der Quelldatei. |
| [getSrcStream](#getSrcStream--) | Ermittelt den Quell-Stream. |
| [getSubmitFlag](#getSubmitFlag--) | Ermittelt die Übermittlungs-Flags des Submit-Buttons |
| [moveField](#moveField-java.lang.String-float-float-float-float-) | <p> Setzt die neue Position des Feldes. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_MoveField.pdf"); formEditor.moveField("textField", 20.5f, 20.3f, 120.6f, 40.8f); </pre> |
| [removeField](#removeField-java.lang.String-) | <p> Entfernt das Feld aus dem Formular. </p> <hr> <pre> FormEditr formEditor = new FormEditor("PdfForm.pdf", "FormEditor_RemoveField.pdf"); formEditor.removeField("listboxField"); formEditor.removeField("textField"); </pre> |
| [removeFieldAction](#removeFieldAction-java.lang.String-) | <p> Entfernt die Submit-Aktion des Feldes. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_RemoveFieldAction.pdf"); formEditor.removeFieldAction("btnSubmit"); </pre> |
| [renameField](#renameField-java.lang.String-java.lang.String-) | <p> Ändern Sie den Namen des Feldes. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"PdfForm_updated.pdf\"); formEditor.renameField(\"textField\", \"textField_Renamed\"); </pre> |
| [resetFacade](#resetFacade--) | Setzen Sie alle visuellen Attribute auf einen leeren Wert. |
| [resetInnerFacade](#resetInnerFacade--) | Setzen Sie alle visuellen Attribute der inneren Fassade auf einen leeren Wert. |
| [save](#save--) | Speichert Änderungen in die Zieldatei. |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | Legt den Namen des Anhangs fest, wenn das Ergebnis der Operation in HttpResponse-Objekten als Anhang gespeichert wird. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | Legt fest, wie der Inhalt gespeichert wird, wenn das Ergebnis der Operation in ein HttpResponse-Objekt gespeichert wird. Mögliche Werte: inline / attachment. Standard: inline. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | Legt das PDF-Dateiformat {@link PdfFormat} fest. Die Ergebnisdatei wird im angegebenen Dateiformat gespeichert. Wenn diese Eigenschaft nicht angegeben ist, wird die Datei im Standard-PDF-Format ohne Konvertierung gespeichert. |
| [setDestFileName](#setDestFileName-java.lang.String-) | <p> Legt den Namen der Zieldatei fest. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setDestFileName(\"OutFile.pdf\"); </pre> |
| [setDestStream](#setDestStream-java.io.OutputStream-) | <p> Legt den Ziel-Stream fest. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setDestStream(new FileInputStream(\"OutFile.pdf\")); </pre> |
| [setExportItems](#setExportItems-java.lang.String:A:A-) | <p> Legt Optionen für das Kombinationsfeld mit Exportwerten fest. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"PdfForm_Updated.pdf\")); formEditor.setExportItems ( new String[][] { new String[] { \"1\", \"Firs\" }, new String[] { \"2\", \"Second\" }, new String[] { \"3\", \"Third\" } }); formEditor.addField(FieldType.ListBox, \"AddedListBoxField\", \"Second\", 1, 10, 30, 110, 130); formEditor.save(); </pre> |
| [setFacade](#setFacade-com.aspose.pdf.facades.FormFieldFacade-) | <p> Legt die visuellen Attribute des Feldes fest. </p> <hr> <pre> FormEditor fe = new FormEditor(\"PdfForm.pdf\", \"PdfForm_DecorateField_text.pdf\"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.green); fe.getFacade().setAlignment(FormFieldFacade.AlignCenter); fe.setDecorateField(\"textField\"); fe.save(); </pre> |
| [setFieldAlignment](#setFieldAlignment-java.lang.String-int-) | <p> Legt den Ausrichtungsstil eines Textfeldes fest. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_updated.pdf\")); formEditor.setFieldAlignment(fieldName, FormFieldFacade.AlignCenter); </pre> |
| [setFieldAlignmentV](#setFieldAlignmentV-java.lang.String-int-) | <p> Legt den vertikalen Ausrichtungsstil eines Textfeldes fest. </p> <hr> <pre> FormEditor fe = new FormEditor(\"PdfStaticForm.pdf\", \"VerticalAlign.pdf\"); fe.setFieldAlignmentV(\"form1[0].TextField[0]\", FormFieldFacade.AlignBottom); </pre> |
| [setFieldAppearance](#setFieldAppearance-java.lang.String-int-) | <p> Set field flags </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm1.pdf", "FormEditor_SetFieldAppearance.pdf"); formEditor.setFieldAppearance("Name", AnnotationFlags.Hidden); formEditor.setFieldAppearance("Phone", AnnotationFlags.NoView \ | AnnotationFlags.Print); </pre> |
| [setFieldAttribute](#setFieldAttribute-java.lang.String-int-) | <p> Legt Attribute des Feldes fest. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"PdfForm_SetFieldAttribute.pdf\"); formEditor.setFieldAttribute(\"listboxField\", PropertyFlag.ReadOnly); formEditor.setFieldAttribute(\"textField\", PropertyFlag.NoExport); </pre> |
| [setFieldCombNumber](#setFieldCombNumber-java.lang.String-int-) | <p> Legt die Anzahl der Kästchen für ein reguläres einzeiliges Textfeld fest (das Feld wird automatisch in so viele gleichmäßig verteilte Positionen bzw. Kästchen unterteilt, wie der Wert des Parameters combNumber ist). </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfWithAcroForm.pdf\", \"FormEditor_SetFieldComb.pdf\")); formEditor.setFieldCombNumber(\"textCombField\", 5); </pre> |
| [setFieldLimit](#setFieldLimit-java.lang.String-int-) | <p> Legt die maximale Zeichenanzahl des Textfelds fest. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetFieldLimit.pdf"); formEditor.setFieldLimit("textField", 15); </pre> |
| [setFieldScript](#setFieldScript-java.lang.String-java.lang.String-) | Setzt JavaScript für ein PushButton-Feld. Wenn altes JavaScript vorhanden war, wird es durch das neue ersetzt. |
| [setItems](#setItems-java.lang.String:A-) | <p> Legt Elemente fest, die zu einer neu erstellten Listbox oder Kombobox hinzugefügt werden. </p> <hr> <pre> formEditor = new com.aspose.pdf.facadesFormEditor("input.pdf", "output.pdf"); formEditor.setItems(new String[] { "AAA", "BBB", "CCC" }); formEditor.addField(FieldType.ListBox, "AddedListBoxField", "BBB", 1, 10, 30, 110, 130); formEditor.save(); </pre> |
| [setRadioButtonItemSize](#setRadioButtonItemSize-double-) | Ermittelt oder setzt die Größe des Radio-Button-Elements (wenn ein neues Radio-Button-Feld hinzugefügt wird). FormEditor formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setRadioButtonItemSize(20); formEditor.setItems(new String[] { "First", "Second", "Third" }); formEditor.addField(com.aspose.pdf.facades.FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130); formEditor.save(); |
| [setRadioGap](#setRadioGap-float-) | <p> Legt das Mitglied fest, um den Abstand zwischen zwei benachbarten Radio-Buttons in Pixeln zu speichern, standardmäßig ist 50. </p> <hr> <pre> formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setItems(new String[] { "First", "Second", "Third" }); formEditor.addField(FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130); formEditor.save(); </pre> |
| [setRadioHoriz](#setRadioHoriz-boolean-) | <p> Legt das Flag fest, um anzugeben, ob die Radio-Buttons horizontal oder vertikal angeordnet sind, Standardwert ist true. </p> <hr> <pre> formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setItems(new String[] { "First", "Second", "Third" }); formEditor.addField(FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130); formEditor.save(); </pre> |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Legt Speicheroptionen fest, wenn das Ergebnis als HttpResponse gespeichert wird. Standardwert: PdfSaveOptions. |
| [setSrcFileName](#setSrcFileName-java.lang.String-) | <p> Legt den Namen der Quelldatei fest. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setSrcFileName("InputFile.pdf"); </pre> |
| [setSrcStream](#setSrcStream-java.io.InputStream-) | <p> Legt den Quell-Stream fest. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setSrcStream(new FileInputStream("InFile.pdf")); </pre> |
| [setSubmitFlag](#setSubmitFlag-java.lang.String-com.aspose.pdf.facades.SubmitFormFlag-) | <p> Legt das Submit-Flag des Submit-Buttons fest. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetSubmitFlag.pdf"); formEditor.setSubmitFlag("btnSubmit", SubmitFormFlag.Fdf); </pre> |
| [setSubmitFlag](#setSubmitFlag-com.aspose.pdf.facades.SubmitFormFlag-) | Legt die Übermittlungs-Flags des Submit-Buttons fest |
| [setSubmitUrl](#setSubmitUrl-java.lang.String-java.lang.String-) | <p> Legt die URL des Buttons fest. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetSubmitUrl.pdf"); formEditor.setSubmitUrl("btnSubmit", "www.mysite.com"); </pre> |
| [single2Multiple](#single2Multiple-java.lang.String-) | <p> Ändert ein einzeiliges Textfeld in ein mehrzeiliges. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf"); formEditor.single2Multiple("textField"); </pre> |

### FormEditor {#FormEditor--}
```
public FormEditor()
```

<p> Konstruktor für FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre>

### FormEditor {#FormEditor-com.aspose.pdf.IDocument-}
<p> Konstruktor für FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre>

### FormEditor {#FormEditor-com.aspose.pdf.IDocument-java.io.OutputStream-}
<p> Konstruktor für FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre>

### FormEditor {#FormEditor-com.aspose.pdf.IDocument-java.lang.String-}
<p> Konstruktor für FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre>

### FormEditor {#FormEditor-java.io.InputStream-java.io.OutputStream-}
<p> Konstruktor für FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre>

### FormEditor {#FormEditor-java.lang.String-java.lang.String-}
<p> Konstruktor für FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre>

### addField {#addField-com.aspose.pdf.facades.FieldType-java.lang.String-int-float-float-float-float-}
<p> Fügt ein Feld des angegebenen Typs zum Formular hinzu. </p> <hr> <pre> FormEditor formEditor = new com.aspose.pdf.facades.FormEditor(\"PdfForm.pdf\", \"FormEditor_AddField_Text.pdf\"); formEditor.addField(FieldType.Text, \"AddedTextField\", 1, 10, 30, 110, 46); formEditor.save(); </pre>

### addField {#addField-com.aspose.pdf.facades.FieldType-java.lang.String-java.lang.String-int-float-float-float-float-}
Fügt ein Feld des angegebenen Typs zum Formular hinzu.

### addFieldScript {#addFieldScript-java.lang.String-java.lang.String-}
Fügt JavaScript für ein PushButton-Feld hinzu.

### addListItem {#addListItem-java.lang.String-java.lang.String-}
<p> Fügt ein neues Element zur Listbox hinzu. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", PdfForm_out.pdf\"); formEditor.addListItem(\"listBoxField\", \"Item 4 (New Item)\"); </pre>

### addListItem {#addListItem-java.lang.String-java.lang.String:A-}
<p> Fügt ein neues Element mit Exportwert zum bestehenden Listbox-Feld hinzu, nur für AcroForm-Combo-Box-Feld. </p> <hr> <pre> FormEditor fe = new FormEditor(\"PdfForm.pdf\", \"FormEditor_AddListItem2.pdf\"); fe.addListItem(\"listboxField\", new String[] { \"4\", \"Item4(Added)\" }); </pre>

### addSubmitBtn {#addSubmitBtn-java.lang.String-int-java.lang.String-java.lang.String-float-float-float-float-}
<p> Fügt dem Formular einen Submit-Button hinzu. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_AddSubmitBtn.pdf\"); formEditor.addSubmitBtn(\"submit\", 1, \"Submit\", \"www.check.com\", 10, 200, 70, 270); </pre>

### close {#close--}
```
public void close()
```

Objektinstanz schließen

### copyInnerField {#copyInnerField-java.lang.String-java.lang.String-int-}
Kopiert ein vorhandenes Feld an dieselbe Position in der angegebenen Seitennummer. Es wird ein neues Dokument erstellt, das alles enthält, was das Quelldokument hat, außer dem neu kopierten Feld.

### copyInnerField {#copyInnerField-java.lang.String-java.lang.String-int-float-float-}
Kopiert ein vorhandenes Feld an eine neue Position, die sowohl durch die Seitennummer als auch durch die Koordinaten angegeben ist. Es wird ein neues Dokument erstellt, das alles enthält, was das Quelldokument hat, außer dem neu kopierten Feld.

### copyOuterField {#copyOuterField-java.lang.String-java.lang.String-}
Kopiert ein vorhandenes Feld von einem PDF-Dokument in ein anderes Dokument mit ursprünglicher Seitennummer und Koordinaten. Hinweis: Nur für AcroForm-Felder (ohne Optionsfeld).

### copyOuterField {#copyOuterField-java.lang.String-java.lang.String-int-}
Kopiert ein vorhandenes Feld von einem PDF-Dokument in ein anderes Dokument mit angegebener Seitennummer und ursprünglichen Koordinaten. Hinweis: Nur für AcroForm-Felder (ohne Optionsfeld).

### copyOuterField {#copyOuterField-java.lang.String-java.lang.String-int-float-float-}
Kopiert ein vorhandenes Feld von einem PDF-Dokument in ein anderes Dokument mit angegebener Seitennummer und Koordinaten. Hinweis: Nur für AcroForm-Felder (ohne Optionsfeld).

### decorateField {#decorateField--}
```
public void decorateField()
```

<p> Ändert die visuellen Attribute aller Felder im PDF-Dokument. </p> <hr> <pre> FormEditor fe = new FormEditor("PdfForm.pdf", "FormEditor_DecorateField.pdf"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.Green); fe.getFacade().setAlignment(FormFieldFacade.AlignRight); // decorate all fields. fe.decorateField(); </pre>

### decorateField {#decorateField-com.aspose.pdf.facades.FieldType-}
<p> Ändert die visuellen Attribute aller Felder im PDF-Dokument. </p> <hr> <pre> FormEditor fe = new FormEditor("PdfForm.pdf", "FormEditor_DecorateField.pdf"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.Green); fe.getFacade().setAlignment(FormFieldFacade.AlignRight); // decorate all fields. fe.decorateField(); </pre>

### decorateField {#decorateField-java.lang.String-}
<p> Ändert die visuellen Attribute aller Felder im PDF-Dokument. </p> <hr> <pre> FormEditor fe = new FormEditor("PdfForm.pdf", "FormEditor_DecorateField.pdf"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.Green); fe.getFacade().setAlignment(FormFieldFacade.AlignRight); // decorate all fields. fe.decorateField(); </pre>

### delListItem {#delListItem-java.lang.String-java.lang.String-}
<p> Löscht ein Element aus dem Listenfeld. </p> <hr> <pre> formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_DelListItem.pdf"); formEditor.delListItem("listboxField", "item2"); </pre>

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Objektinstanz schließen Diese Methode ist veraltet, verwenden Sie stattdessen close().

### getAttachmentName {#getAttachmentName--}
```
public String getAttachmentName()
```

Ermittelt den Namen des Anhangs, wenn das Ergebnis der Operation in HttpResponse-Objekten als Anhang gespeichert wird.

**Returns:**
String-Objekt

### getContentDisposition {#getContentDisposition--}
```
public ContentDisposition getContentDisposition()
```

Ermittelt, wie der Inhalt gespeichert wird, wenn das Ergebnis der Operation in einem HttpResponse-Objekt gespeichert wird. Mögliche Werte: inline / attachment. Standard: inline.

**Returns:**
ContentDisposition-Element @see ContentDisposition

### getDestFileName {#getDestFileName--}
```
public String getDestFileName()
```

Ermittelt den Ziel-Dateinamen.

**Returns:**
String‑Objekt

### getDestStream {#getDestStream--}
```
public OutputStream getDestStream()
```

<p> Ermittelt den Ziel-Stream. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setDestStream(new FileInputStream("OutFile.pdf")); </pre>

**Returns:**
OutputStream-Objekt

### getDocument {#getDocument--}
```
public IDocument getDocument()
```

Ermittelt das Dokument, an dem {@code FormEditor} arbeitet.

**Returns:**
IDocument‑Objekt

### getExportItems {#getExportItems--}
```
public String [][] getExportItems()
```

<p> Ermittelt Optionen für das Kombinationsfeld mit Exportwerten. </p> <hr>

**Returns:**
String[][]-Objekt

### getFacade {#getFacade--}
```
public FormFieldFacade getFacade()
```

Ermittelt die visuellen Attribute des Feldes.

**Returns:**
FormFieldFacade-Objekt

### getFieldAppearance {#getFieldAppearance-java.lang.String-}
Ermittelt Feld-Flags.

### getItems {#getItems--}
```
public String [] getItems()
```

Ermittelt Elemente, die zu einer neu erstellten Listbox oder einem Kombinationsfeld hinzugefügt werden.

**Returns:**
String[]-Objekt

### getRadioButtonItemSize {#getRadioButtonItemSize--}
```
public double getRadioButtonItemSize()
```

Ermittelt oder setzt die Größe des Radio-Button-Elements (wenn ein neues Radio-Button-Feld hinzugefügt wird). FormEditor formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setRadioButtonItemSize(20); formEditor.setItems(new String[] { "First", "Second", "Third" }); formEditor.addField(com.aspose.pdf.facades.FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130); formEditor.save();

**Returns:**
double-Wert

### getRadioGap {#getRadioGap--}
```
public float getRadioGap()
```

Ermittelt das Mitglied, das den Abstand zwischen zwei benachbarten Radio-Buttons in Pixeln speichert, Standard ist 50.

**Returns:**
float-Wert

### getRadioHoriz {#getRadioHoriz--}
```
public boolean getRadioHoriz()
```

<p> Ermittelt das Flag, das angibt, ob die Radio-Buttons horizontal oder vertikal angeordnet sind, Standardwert ist true.

**Returns:**
boolescher Wert

### getSaveOptions {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```

Ermittelt die Speicheroptionen, wenn das Ergebnis als HttpResponse gespeichert wird. Standardwert: PdfSaveOptions.

**Returns:**
SaveOptions-Objekt

### getSrcFileName {#getSrcFileName--}
```
public String getSrcFileName()
```

Ermittelt den Namen der Quelldatei.

**Returns:**
String‑Objekt

### getSrcStream {#getSrcStream--}
```
public InputStream getSrcStream()
```

Ermittelt den Quell-Stream.

**Returns:**
InputStream‑Objekt

### getSubmitFlag {#getSubmitFlag--}
```
public SubmitFormFlag getSubmitFlag()
```

Ermittelt die Übermittlungs-Flags des Submit-Buttons

**Returns:**
SubmitFormFlag-Element @see SubmitFormFlag

### moveField {#moveField-java.lang.String-float-float-float-float-}
<p> Setzt die neue Position des Feldes. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_MoveField.pdf"); formEditor.moveField("textField", 20.5f, 20.3f, 120.6f, 40.8f); </pre>

### removeField {#removeField-java.lang.String-}
<p> Entfernt das Feld aus dem Formular. </p> <hr> <pre> FormEditr formEditor = new FormEditor("PdfForm.pdf", "FormEditor_RemoveField.pdf"); formEditor.removeField("listboxField"); formEditor.removeField("textField"); </pre>

### removeFieldAction {#removeFieldAction-java.lang.String-}
<p> Entfernt die Submit-Aktion des Feldes. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_RemoveFieldAction.pdf"); formEditor.removeFieldAction("btnSubmit"); </pre>

### renameField {#renameField-java.lang.String-java.lang.String-}
<p> Ändern Sie den Namen des Feldes. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"PdfForm_updated.pdf\"); formEditor.renameField(\"textField\", \"textField_Renamed\"); </pre>

### resetFacade {#resetFacade--}
```
public void resetFacade()
```

Setzen Sie alle visuellen Attribute auf einen leeren Wert.

### resetInnerFacade {#resetInnerFacade--}
```
public void resetInnerFacade()
```

Setzen Sie alle visuellen Attribute der inneren Fassade auf einen leeren Wert.

### save {#save--}
```
@Deprecated public void save()
```

Speichert Änderungen in die Zieldatei.

### setAttachmentName {#setAttachmentName-java.lang.String-}
Legt den Namen des Anhangs fest, wenn das Ergebnis der Operation in HttpResponse-Objekten als Anhang gespeichert wird.

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
Legt fest, wie der Inhalt gespeichert wird, wenn das Ergebnis der Operation in ein HttpResponse-Objekt gespeichert wird. Mögliche Werte: inline / attachment. Standard: inline.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Legt das PDF-Dateiformat {@link PdfFormat} fest. Die Ergebnisdatei wird im angegebenen Dateiformat gespeichert. Wenn diese Eigenschaft nicht angegeben ist, wird die Datei im Standard-PDF-Format ohne Konvertierung gespeichert.

### setDestFileName {#setDestFileName-java.lang.String-}
<p> Legt den Namen der Zieldatei fest. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setDestFileName(\"OutFile.pdf\"); </pre>

### setDestStream {#setDestStream-java.io.OutputStream-}
<p> Legt den Ziel-Stream fest. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setDestStream(new FileInputStream(\"OutFile.pdf\")); </pre>

### setExportItems {#setExportItems-java.lang.String:A:A-}
<p> Legt Optionen für das Kombinationsfeld mit Exportwerten fest. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"PdfForm_Updated.pdf\")); formEditor.setExportItems ( new String[][] { new String[] { \"1\", \"Firs\" }, new String[] { \"2\", \"Second\" }, new String[] { \"3\", \"Third\" } }); formEditor.addField(FieldType.ListBox, \"AddedListBoxField\", \"Second\", 1, 10, 30, 110, 130); formEditor.save(); </pre>

### setFacade {#setFacade-com.aspose.pdf.facades.FormFieldFacade-}
<p> Legt die visuellen Attribute des Feldes fest. </p> <hr> <pre> FormEditor fe = new FormEditor(\"PdfForm.pdf\", \"PdfForm_DecorateField_text.pdf\"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.green); fe.getFacade().setAlignment(FormFieldFacade.AlignCenter); fe.setDecorateField(\"textField\"); fe.save(); </pre>

### setFieldAlignment {#setFieldAlignment-java.lang.String-int-}
<p> Legt den Ausrichtungsstil eines Textfeldes fest. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_updated.pdf\")); formEditor.setFieldAlignment(fieldName, FormFieldFacade.AlignCenter); </pre>

### setFieldAlignmentV {#setFieldAlignmentV-java.lang.String-int-}
<p> Legt den vertikalen Ausrichtungsstil eines Textfeldes fest. </p> <hr> <pre> FormEditor fe = new FormEditor(\"PdfStaticForm.pdf\", \"VerticalAlign.pdf\"); fe.setFieldAlignmentV(\"form1[0].TextField[0]\", FormFieldFacade.AlignBottom); </pre>

### setFieldAppearance {#setFieldAppearance-java.lang.String-int-}
<p> Feld-Flags setzen </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm1.pdf", "FormEditor_SetFieldAppearance.pdf"); formEditor.setFieldAppearance("Name", AnnotationFlags.Hidden); formEditor.setFieldAppearance("Phone", AnnotationFlags.NoView | AnnotationFlags.Print); </pre>

### setFieldAttribute {#setFieldAttribute-java.lang.String-int-}
<p> Legt Attribute des Feldes fest. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"PdfForm_SetFieldAttribute.pdf\"); formEditor.setFieldAttribute(\"listboxField\", PropertyFlag.ReadOnly); formEditor.setFieldAttribute(\"textField\", PropertyFlag.NoExport); </pre>

### setFieldCombNumber {#setFieldCombNumber-java.lang.String-int-}
<p> Legt die Anzahl der Kästchen für ein reguläres einzeiliges Textfeld fest (das Feld wird automatisch in so viele gleichmäßig verteilte Positionen bzw. Kästchen unterteilt, wie der Wert des Parameters combNumber ist). </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfWithAcroForm.pdf\", \"FormEditor_SetFieldComb.pdf\")); formEditor.setFieldCombNumber(\"textCombField\", 5); </pre>

### setFieldLimit {#setFieldLimit-java.lang.String-int-}
<p> Legt die maximale Zeichenanzahl des Textfelds fest. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetFieldLimit.pdf"); formEditor.setFieldLimit("textField", 15); </pre>

### setFieldScript {#setFieldScript-java.lang.String-java.lang.String-}
Setzt JavaScript für ein PushButton-Feld. Wenn altes JavaScript vorhanden war, wird es durch das neue ersetzt.

### setItems {#setItems-java.lang.String:A-}
<p> Legt Elemente fest, die zu einer neu erstellten Listbox oder Kombobox hinzugefügt werden. </p> <hr> <pre> formEditor = new com.aspose.pdf.facadesFormEditor("input.pdf", "output.pdf"); formEditor.setItems(new String[] { "AAA", "BBB", "CCC" }); formEditor.addField(FieldType.ListBox, "AddedListBoxField", "BBB", 1, 10, 30, 110, 130); formEditor.save(); </pre>

### setRadioButtonItemSize {#setRadioButtonItemSize-double-}
```
public void setRadioButtonItemSize(double value)
```

Ermittelt oder setzt die Größe des Radio-Button-Elements (wenn ein neues Radio-Button-Feld hinzugefügt wird). FormEditor formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setRadioButtonItemSize(20); formEditor.setItems(new String[] { "First", "Second", "Third" }); formEditor.addField(com.aspose.pdf.facades.FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130); formEditor.save();

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### setRadioGap {#setRadioGap-float-}
```
public void setRadioGap(float value)
```

<p> Legt das Mitglied fest, um den Abstand zwischen zwei benachbarten Radio-Buttons in Pixeln zu speichern, standardmäßig ist 50. </p> <hr> <pre> formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setItems(new String[] { "First", "Second", "Third" }); formEditor.addField(FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130); formEditor.save(); </pre>

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | float-Wert |

### setRadioHoriz {#setRadioHoriz-boolean-}
```
public void setRadioHoriz(boolean value)
```

<p> Legt das Flag fest, um anzugeben, ob die Radio-Buttons horizontal oder vertikal angeordnet sind, Standardwert ist true. </p> <hr> <pre> formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setItems(new String[] { "First", "Second", "Third" }); formEditor.addField(FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130); formEditor.save(); </pre>

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Legt Speicheroptionen fest, wenn das Ergebnis als HttpResponse gespeichert wird. Standardwert: PdfSaveOptions.

### setSrcFileName {#setSrcFileName-java.lang.String-}
<p> Legt den Namen der Quelldatei fest. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setSrcFileName("InputFile.pdf"); </pre>

### setSrcStream {#setSrcStream-java.io.InputStream-}
<p> Legt den Quell-Stream fest. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setSrcStream(new FileInputStream("InFile.pdf")); </pre>

### setSubmitFlag {#setSubmitFlag-java.lang.String-com.aspose.pdf.facades.SubmitFormFlag-}
<p> Legt das Submit-Flag des Submit-Buttons fest. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetSubmitFlag.pdf"); formEditor.setSubmitFlag("btnSubmit", SubmitFormFlag.Fdf); </pre>

### setSubmitFlag {#setSubmitFlag-com.aspose.pdf.facades.SubmitFormFlag-}
Legt die Übermittlungs-Flags des Submit-Buttons fest

### setSubmitUrl {#setSubmitUrl-java.lang.String-java.lang.String-}
<p> Legt die URL des Buttons fest. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetSubmitUrl.pdf"); formEditor.setSubmitUrl("btnSubmit", "www.mysite.com"); </pre>

### single2Multiple {#single2Multiple-java.lang.String-}
<p> Ändert ein einzeiliges Textfeld in ein mehrzeiliges. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf"); formEditor.single2Multiple("textField"); </pre>
