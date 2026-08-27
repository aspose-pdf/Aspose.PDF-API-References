---
title: "FormEditorWeb"
linktitle: "FormEditorWeb"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Klasse zum Bearbeiten von Formularen (Hinzufügen/Löschen von Feldern usw.)"
type: docs
weight: 210
url: /de/java/com.aspose.pdf.facades/formeditorweb/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.FormEditorWeb, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.FormEditorWeb, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.FormEditorWeb

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, IFormEditor, ISaveableFacade, Closeable, AutoCloseable

```
public final class FormEditorWeb extends SaveableFacade implements IFormEditor
```

Klasse zum Bearbeiten von Formularen (Hinzufügen/Löschen von Feldern usw.)

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [FormEditorWeb](#FormEditorWeb--) | <p> Konstruktor für FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre> |
| [FormEditorWeb](#FormEditorWeb-com.aspose.pdf.IDocument-) | <p> Konstruktor für FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre> |
| [FormEditorWeb](#FormEditorWeb-com.aspose.pdf.IDocument-java.io.OutputStream-) | <p> Konstruktor für FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre> |
| [FormEditorWeb](#FormEditorWeb-com.aspose.pdf.IDocument-java.lang.String-) | <p> Konstruktor für FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre> |
| [FormEditorWeb](#FormEditorWeb-java.io.InputStream-javax.servlet.http.HttpServletResponse-) | <p> Konstruktor für FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre> |
| [FormEditorWeb](#FormEditorWeb-java.io.InputStream-java.io.OutputStream-) | <p> Konstruktor für FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre> |
| [FormEditorWeb](#FormEditorWeb-java.lang.String-javax.servlet.http.HttpServletResponse-) | <p> Konstruktor für FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre> |
| [FormEditorWeb](#FormEditorWeb-java.lang.String-java.lang.String-) | <p> Konstruktor für FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre> |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [addField](#addField-com.aspose.pdf.facades.FieldType-java.lang.String-int-float-float-float-float-) | Fügt ein Feld des angegebenen Typs zum Formular hinzu. |
| [addField](#addField-com.aspose.pdf.facades.FieldType-java.lang.String-java.lang.String-int-float-float-float-float-) | Fügt ein Feld des angegebenen Typs zum Formular hinzu. |
| [addFieldScript](#addFieldScript-java.lang.String-java.lang.String-) | Fügt JavaScript für ein PushButton-Feld hinzu. |
| [addListItem](#addListItem-java.lang.String-java.lang.String-) | Fügt ein neues Element zur Listbox hinzu. |
| [addListItem](#addListItem-java.lang.String-java.lang.String:A-) | Fügt ein neues Element mit Exportwert zum bestehenden Listbox-Feld hinzu, nur für das AcroForm-Combo-Box-Feld. |
| [addSubmitBtn](#addSubmitBtn-java.lang.String-int-java.lang.String-java.lang.String-float-float-float-float-) | Fügt einen Senden-Button zum Formular hinzu. |
| [close](#close--) | Schließt alle von diesem Dokument verwendeten Ressourcen. |
| [copyInnerField](#copyInnerField-java.lang.String-java.lang.String-int-) | Kopiert ein vorhandenes Feld an dieselbe Position in der angegebenen Seitennummer. |
| [copyInnerField](#copyInnerField-java.lang.String-java.lang.String-int-float-float-) | Kopiert ein vorhandenes Feld an eine neue Position, die sowohl durch die Seitennummer als auch durch die Ordinaten angegeben ist. |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-) | Kopiert ein vorhandenes Feld von einem PDF-Dokument in ein anderes Dokument mit ursprünglicher Seitennummer und Ordinaten. |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-int-) | Kopiert ein vorhandenes Feld von einem PDF-Dokument in ein anderes Dokument mit angegebener Seitennummer und ursprünglichen Ordinaten. |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-int-float-float-) | Kopiert ein vorhandenes Feld von einem PDF-Dokument in ein anderes Dokument mit angegebener Seitennummer und Ordinaten. |
| [decorateField](#decorateField--) | Ändert die visuellen Attribute aller Felder im PDF-Dokument. |
| [decorateField](#decorateField-com.aspose.pdf.facades.FieldType-) | Ändert die visuellen Attribute aller Felder mit dem angegebenen Feldtyp. |
| [decorateField](#decorateField-java.lang.String-) | Ändert die visuellen Attribute des angegebenen Feldes. |
| [delListItem](#delListItem-java.lang.String-java.lang.String-) | Löscht ein Element aus dem Listenfeld. |
| [dispose](#dispose--) | Veraltet. |
| [getAttachmentName](#getAttachmentName--) | Ermittelt den Namen des Anhangs, wenn das Ergebnis der Operation in HttpResponse-Objekten als Anhang gespeichert wird. |
| [getContentDisposition](#getContentDisposition--) | Ermittelt, wie der Inhalt gespeichert wird, wenn das Ergebnis der Operation in ein HttpResponse-Objekt gespeichert wird. |
| [getDestFileName](#getDestFileName--) | Veraltet. |
| [getDestStream](#getDestStream--) | Liefert den Ziel-Stream. |
| [getExportItems](#getExportItems--) | Liefert Optionen für das Kombinationsfeld mit Exportwerten. |
| [getFacade](#getFacade--) | Ermittelt die visuellen Attribute des Feldes. |
| [getFieldAppearance](#getFieldAppearance-java.lang.String-) | Ermittelt Feld-Flags. |
| [getItems](#getItems--) | Gibt das Element-Array zurück |
| [getRadioButtonItemSize](#getRadioButtonItemSize--) | Liefert oder setzt die Größe des Radio‑Button‑Elements (wenn ein neues Radio‑Button‑Feld hinzugefügt wird). |
| [getRadioGap](#getRadioGap--) | Ermittelt das Mitglied, das den Abstand zwischen zwei benachbarten Radio-Buttons in Pixeln speichert, Standard ist 50. |
| [getRadioHoriz](#getRadioHoriz--) | Liefert das Flag, das angibt, ob die Radio‑Buttons horizontal oder vertikal angeordnet sind; Standardwert ist true. |
| [getResponse](#getResponse--) | Liefert das Response‑Objekt, in dem das Ergebnis der Operation gespeichert wird. |
| [getSaveOptions](#getSaveOptions--) | Ermittelt Speicheroptionen, wenn das Ergebnis als HttpResponse gespeichert wird. |
| [getSrcFileName](#getSrcFileName--) | Veraltet. |
| [getSrcStream](#getSrcStream--) | Ermittelt den Quell-Stream. |
| [getSubmitFlag](#getSubmitFlag--) | Ermittelt die Übermittlungs-Flags des Submit-Buttons |
| [moveField](#moveField-java.lang.String-float-float-float-float-) | Setzt die neue Position des Feldes. |
| [removeField](#removeField-java.lang.String-) | Entfernt das Feld aus dem Formular. |
| [removeFieldAction](#removeFieldAction-java.lang.String-) | Entfernt die Submit‑Aktion des Feldes. |
| [renameField](#renameField-java.lang.String-java.lang.String-) | Ändert den Namen des Feldes. |
| [resetFacade](#resetFacade--) | Setzt alle visuellen Attribute auf einen leeren Wert zurück. |
| [resetInnerFacade](#resetInnerFacade--) | Setzt alle visuellen Attribute der inneren Fassade auf einen leeren Wert zurück. |
| [save](#save--) | Speichert Änderungen in die Zieldatei. |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | Legt den Namen des Anhangs fest, wenn das Ergebnis der Operation in HttpResponse-Objekten als Anhang gespeichert wird. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | Legt fest, wie Inhalte gespeichert werden, wenn das Ergebnis der Operation in ein HttpResponse-Objekt gespeichert wird. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | Setzt das PDF‑Dateiformat PdfFormat. |
| [setDestFileName](#setDestFileName-java.lang.String-) | Veraltet. |
| [setDestStream](#setDestStream-java.io.OutputStream-) | Setzt den Ziel‑Stream. |
| [setExportItems](#setExportItems-java.lang.String:A:A-) | Setzt Optionen für das Kombinationsfeld mit Exportwerten. |
| [setFacade](#setFacade-com.aspose.pdf.facades.FormFieldFacade-) | Setzt die visuellen Attribute des Feldes. |
| [setFieldAlignment](#setFieldAlignment-java.lang.String-int-) | Setzt den Ausrichtungsstil eines Textfeldes. |
| [setFieldAlignmentV](#setFieldAlignmentV-java.lang.String-int-) | Setzt den vertikalen Ausrichtungsstil eines Textfeldes. |
| [setFieldAppearance](#setFieldAppearance-java.lang.String-int-) | Setzt Feld‑Flags |
| [setFieldAttribute](#setFieldAttribute-java.lang.String-int-) | Setzt Attribute des Feldes. |
| [setFieldCombNumber](#setFieldCombNumber-java.lang.String-int-) | Setzt die Anzahl der Kämme für ein reguläres einzeiliges Textfeld (das Feld wird automatisch in so viele gleichmäßig verteilte Positionen bzw. Kämme unterteilt, wie der Wert des Parameters combNumber ist). |
| [setFieldLimit](#setFieldLimit-java.lang.String-int-) | Setzt die maximale Zeichenanzahl des Textfeldes. |
| [setFieldScript](#setFieldScript-java.lang.String-java.lang.String-) | Setze JavaScript für ein PushButton-Feld. |
| [setItems](#setItems-java.lang.String:A-) | Legt Elemente fest, die zu einer neu erstellten Listbox oder Kombobox hinzugefügt werden. |
| [setRadioButtonItemSize](#setRadioButtonItemSize-double-) | Liefert oder setzt die Größe des Radio‑Button‑Elements (wenn ein neues Radio‑Button‑Feld hinzugefügt wird). |
| [setRadioGap](#setRadioGap-float-) | Setze das Mitglied, um den Abstand zwischen zwei benachbarten Radio-Buttons in Pixeln zu speichern, Standard ist 50. |
| [setRadioHoriz](#setRadioHoriz-boolean-) | Setze das Flag, um anzugeben, ob die Radio-Buttons horizontal oder vertikal angeordnet sind, Standardwert ist true. |
| [setResponse](#setResponse-javax.servlet.http.HttpServletResponse-) | Legt das Response-Objekt fest, in dem das Ergebnis der Operation gespeichert wird. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Legt die Speicheroptionen fest, wenn das Ergebnis als HttpResponse gespeichert wird. |
| [setSrcFileName](#setSrcFileName-java.lang.String-) | Veraltet. |
| [setSrcStream](#setSrcStream-java.io.InputStream-) | Legt den Quell-Stream fest. |
| [setSubmitFlag](#setSubmitFlag-java.lang.String-com.aspose.pdf.facades.SubmitFormFlag-) | Setze das Submit-Flag des Submit-Buttons. |
| [setSubmitFlag](#setSubmitFlag-com.aspose.pdf.facades.SubmitFormFlag-) | Legt die Übermittlungs-Flags des Submit-Buttons fest |
| [setSubmitUrl](#setSubmitUrl-java.lang.String-java.lang.String-) | Legt die URL des Buttons fest. |
| [single2Multiple](#single2Multiple-java.lang.String-) | Ändere ein einzeiliges Textfeld in ein mehrzeiliges. |

### FormEditorWeb {#FormEditorWeb--}
```
public FormEditorWeb()
```

<p> Konstruktor für FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre>

### FormEditorWeb {#FormEditorWeb-com.aspose.pdf.IDocument-}
<p> Konstruktor für FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre>

### FormEditorWeb {#FormEditorWeb-com.aspose.pdf.IDocument-java.io.OutputStream-}
<p> Konstruktor für FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre>

### FormEditorWeb {#FormEditorWeb-com.aspose.pdf.IDocument-java.lang.String-}
<p> Konstruktor für FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre>

### FormEditorWeb {#FormEditorWeb-java.io.InputStream-javax.servlet.http.HttpServletResponse-}
<p> Konstruktor für FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre>

### FormEditorWeb {#FormEditorWeb-java.io.InputStream-java.io.OutputStream-}
<p> Konstruktor für FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre>

### FormEditorWeb {#FormEditorWeb-java.lang.String-javax.servlet.http.HttpServletResponse-}
<p> Konstruktor für FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre>

### FormEditorWeb {#FormEditorWeb-java.lang.String-java.lang.String-}
<p> Konstruktor für FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre>

### addField {#addField-com.aspose.pdf.facades.FieldType-java.lang.String-int-float-float-float-float-}
Fügt ein Feld des angegebenen Typs zum Formular hinzu.

### addField {#addField-com.aspose.pdf.facades.FieldType-java.lang.String-java.lang.String-int-float-float-float-float-}
Fügt ein Feld des angegebenen Typs zum Formular hinzu.

### addFieldScript {#addFieldScript-java.lang.String-java.lang.String-}
Fügt JavaScript für ein PushButton-Feld hinzu.

### addListItem {#addListItem-java.lang.String-java.lang.String-}
Fügt ein neues Element zur Listbox hinzu.

### addListItem {#addListItem-java.lang.String-java.lang.String:A-}
Fügt ein neues Element mit Exportwert zum bestehenden Listbox-Feld hinzu, nur für das AcroForm-Combo-Box-Feld.

### addSubmitBtn {#addSubmitBtn-java.lang.String-int-java.lang.String-java.lang.String-float-float-float-float-}
Fügt einen Senden-Button zum Formular hinzu.

### close {#close--}
```
public void close()
```

Schließt alle von diesem Dokument verwendeten Ressourcen.

### copyInnerField {#copyInnerField-java.lang.String-java.lang.String-int-}
Kopiert ein vorhandenes Feld an dieselbe Position in der angegebenen Seitennummer.

### copyInnerField {#copyInnerField-java.lang.String-java.lang.String-int-float-float-}
Kopiert ein vorhandenes Feld an eine neue Position, die sowohl durch die Seitennummer als auch durch die Ordinaten angegeben ist.

### copyOuterField {#copyOuterField-java.lang.String-java.lang.String-}
Kopiert ein vorhandenes Feld von einem PDF-Dokument in ein anderes Dokument mit ursprünglicher Seitennummer und Ordinaten.

### copyOuterField {#copyOuterField-java.lang.String-java.lang.String-int-}
Kopiert ein vorhandenes Feld von einem PDF-Dokument in ein anderes Dokument mit angegebener Seitennummer und ursprünglichen Ordinaten.

### copyOuterField {#copyOuterField-java.lang.String-java.lang.String-int-float-float-}
Kopiert ein vorhandenes Feld von einem PDF-Dokument in ein anderes Dokument mit angegebener Seitennummer und Ordinaten.

### decorateField {#decorateField--}
```
public void decorateField()
```

Ändert die visuellen Attribute aller Felder im PDF-Dokument.

### decorateField {#decorateField-com.aspose.pdf.facades.FieldType-}
Ändert die visuellen Attribute aller Felder mit dem angegebenen Feldtyp.

### decorateField {#decorateField-java.lang.String-}
Ändert die visuellen Attribute des angegebenen Feldes.

### delListItem {#delListItem-java.lang.String-java.lang.String-}
Löscht ein Element aus dem Listenfeld.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Veraltet.

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

Ermittelt, wie der Inhalt gespeichert wird, wenn das Ergebnis der Operation in ein HttpResponse-Objekt gespeichert wird.

**Returns:**
ContentDisposition-Element

### getDestFileName {#getDestFileName--}
```
@Deprecated public String getDestFileName()
```

Veraltet.

**Returns:**
String-Wert

### getDestStream {#getDestStream--}
```
public OutputStream getDestStream()
```

Liefert den Ziel-Stream.

**Returns:**
OutputStream-Objekt

### getExportItems {#getExportItems--}
```
public String [][] getExportItems()
```

Liefert Optionen für das Kombinationsfeld mit Exportwerten.

**Returns:**
String[][]-Array

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

Gibt das Element-Array zurück

**Returns:**
String[]-Objekt

### getRadioButtonItemSize {#getRadioButtonItemSize--}
```
public double getRadioButtonItemSize()
```

Liefert oder setzt die Größe des Radio‑Button‑Elements (wenn ein neues Radio‑Button‑Feld hinzugefügt wird).

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

Liefert das Flag, das angibt, ob die Radio‑Buttons horizontal oder vertikal angeordnet sind; Standardwert ist true.

**Returns:**
boolescher Wert

### getResponse {#getResponse--}
```
public javax.servlet.http.HttpServletResponse getResponse()
```

Liefert das Response‑Objekt, in dem das Ergebnis der Operation gespeichert wird.

**Returns:**
HttpServletResponse-Objekt

### getSaveOptions {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```

Ermittelt Speicheroptionen, wenn das Ergebnis als HttpResponse gespeichert wird.

**Returns:**
SaveOptions-Objekt

### getSrcFileName {#getSrcFileName--}
```
@Deprecated public String getSrcFileName()
```

Veraltet.

**Returns:**
String-Wert

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
SubmitFormFlag-Element

### moveField {#moveField-java.lang.String-float-float-float-float-}
Setzt die neue Position des Feldes.

### removeField {#removeField-java.lang.String-}
Entfernt das Feld aus dem Formular.

### removeFieldAction {#removeFieldAction-java.lang.String-}
Entfernt die Submit‑Aktion des Feldes.

### renameField {#renameField-java.lang.String-java.lang.String-}
Ändert den Namen des Feldes.

### resetFacade {#resetFacade--}
```
public void resetFacade()
```

Setzt alle visuellen Attribute auf einen leeren Wert zurück.

### resetInnerFacade {#resetInnerFacade--}
```
public void resetInnerFacade()
```

Setzt alle visuellen Attribute der inneren Fassade auf einen leeren Wert zurück.

### save {#save--}
```
public void save()
```

Speichert Änderungen in die Zieldatei.

### setAttachmentName {#setAttachmentName-java.lang.String-}
Legt den Namen des Anhangs fest, wenn das Ergebnis der Operation in HttpResponse-Objekten als Anhang gespeichert wird.

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
Legt fest, wie Inhalte gespeichert werden, wenn das Ergebnis der Operation in ein HttpResponse-Objekt gespeichert wird.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Setzt das PDF‑Dateiformat PdfFormat.

### setDestFileName {#setDestFileName-java.lang.String-}
Veraltet.

### setDestStream {#setDestStream-java.io.OutputStream-}
Setzt den Ziel‑Stream.

### setExportItems {#setExportItems-java.lang.String:A:A-}
Setzt Optionen für das Kombinationsfeld mit Exportwerten.

### setFacade {#setFacade-com.aspose.pdf.facades.FormFieldFacade-}
Setzt die visuellen Attribute des Feldes.

### setFieldAlignment {#setFieldAlignment-java.lang.String-int-}
Setzt den Ausrichtungsstil eines Textfeldes.

### setFieldAlignmentV {#setFieldAlignmentV-java.lang.String-int-}
Setzt den vertikalen Ausrichtungsstil eines Textfeldes.

### setFieldAppearance {#setFieldAppearance-java.lang.String-int-}
Setzt Feld‑Flags

### setFieldAttribute {#setFieldAttribute-java.lang.String-int-}
Setzt Attribute des Feldes.

### setFieldCombNumber {#setFieldCombNumber-java.lang.String-int-}
Setzt die Anzahl der Kämme für ein reguläres einzeiliges Textfeld (das Feld wird automatisch in so viele gleichmäßig verteilte Positionen bzw. Kämme unterteilt, wie der Wert des Parameters combNumber ist).

### setFieldLimit {#setFieldLimit-java.lang.String-int-}
Setzt die maximale Zeichenanzahl des Textfeldes.

### setFieldScript {#setFieldScript-java.lang.String-java.lang.String-}
Setze JavaScript für ein PushButton-Feld.

### setItems {#setItems-java.lang.String:A-}
Legt Elemente fest, die zu einer neu erstellten Listbox oder Kombobox hinzugefügt werden.

### setRadioButtonItemSize {#setRadioButtonItemSize-double-}
```
public void setRadioButtonItemSize(double value)
```

Liefert oder setzt die Größe des Radio‑Button‑Elements (wenn ein neues Radio‑Button‑Feld hinzugefügt wird).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### setRadioGap {#setRadioGap-float-}
```
public void setRadioGap(float value)
```

Setze das Mitglied, um den Abstand zwischen zwei benachbarten Radio-Buttons in Pixeln zu speichern, Standard ist 50.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | float-Wert |

### setRadioHoriz {#setRadioHoriz-boolean-}
```
public void setRadioHoriz(boolean value)
```

Setze das Flag, um anzugeben, ob die Radio-Buttons horizontal oder vertikal angeordnet sind, Standardwert ist true.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setResponse {#setResponse-javax.servlet.http.HttpServletResponse-}
Legt das Response-Objekt fest, in dem das Ergebnis der Operation gespeichert wird.

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Legt die Speicheroptionen fest, wenn das Ergebnis als HttpResponse gespeichert wird.

### setSrcFileName {#setSrcFileName-java.lang.String-}
Veraltet.

### setSrcStream {#setSrcStream-java.io.InputStream-}
Legt den Quell-Stream fest.

### setSubmitFlag {#setSubmitFlag-java.lang.String-com.aspose.pdf.facades.SubmitFormFlag-}
Setze das Submit-Flag des Submit-Buttons.

### setSubmitFlag {#setSubmitFlag-com.aspose.pdf.facades.SubmitFormFlag-}
Legt die Übermittlungs-Flags des Submit-Buttons fest

### setSubmitUrl {#setSubmitUrl-java.lang.String-java.lang.String-}
Legt die URL des Buttons fest.

### single2Multiple {#single2Multiple-java.lang.String-}
Ändere ein einzeiliges Textfeld in ein mehrzeiliges.
