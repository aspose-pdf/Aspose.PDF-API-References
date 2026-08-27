---
title: "IFormEditor"
linktitle: "IFormEditor"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Klasse zum Bearbeiten von Formularen (Hinzufügen/Löschen von Feldern usw.)"
type: docs
weight: 260
url: /de/java/com.aspose.pdf.facades/iformeditor/
---
```
public interface IFormEditor extends Closeable
```

Klasse zum Bearbeiten von Formularen (Hinzufügen/Löschen von Feldern usw.)

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [addField](#addField-com.aspose.pdf.facades.FieldType-java.lang.String-int-float-float-float-float-) | Fügt ein Feld des angegebenen Typs zum Formular hinzu. |
| [addField](#addField-com.aspose.pdf.facades.FieldType-java.lang.String-java.lang.String-int-float-float-float-float-) | Fügt ein Feld des angegebenen Typs zum Formular hinzu. |
| [addListItem](#addListItem-java.lang.String-java.lang.String-) | Fügt ein neues Element zur Listbox hinzu. |
| [addListItem](#addListItem-java.lang.String-java.lang.String:A-) | Fügt ein neues Element mit Exportwert zum bestehenden Listbox-Feld hinzu, nur für das AcroForm-Combo-Box-Feld. |
| [addSubmitBtn](#addSubmitBtn-java.lang.String-int-java.lang.String-java.lang.String-float-float-float-float-) | Fügt einen Senden-Button zum Formular hinzu. |
| [close](#close--) | Schließt das Objekt |
| [copyInnerField](#copyInnerField-java.lang.String-java.lang.String-int-) | Kopiert ein vorhandenes Feld an dieselbe Position in der angegebenen Seitennummer. |
| [copyInnerField](#copyInnerField-java.lang.String-java.lang.String-int-float-float-) | Kopiert ein vorhandenes Feld an eine neue Position, die sowohl durch die Seitennummer als auch durch die Ordinaten angegeben ist. |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-) | Kopiert ein vorhandenes Feld von einem PDF-Dokument in ein anderes Dokument mit ursprünglicher Seitennummer und Ordinaten. |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-int-) | Kopiert ein vorhandenes Feld von einem PDF-Dokument in ein anderes Dokument mit angegebener Seitennummer und ursprünglichen Ordinaten. |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-int-float-float-) | Kopiert ein vorhandenes Feld von einem PDF-Dokument in ein anderes Dokument mit angegebener Seitennummer und Ordinaten. |
| [decorateField](#decorateField--) | Ändert die visuellen Attribute aller Felder im PDF-Dokument. |
| [decorateField](#decorateField-com.aspose.pdf.facades.FieldType-) | Ändert die visuellen Attribute aller Felder mit dem angegebenen Feldtyp. |
| [decorateField](#decorateField-java.lang.String-) | Ändert die visuellen Attribute des angegebenen Feldes. |
| [delListItem](#delListItem-java.lang.String-java.lang.String-) | Löscht ein Element aus dem Listenfeld. |
| [dispose](#dispose--) | Schließt das Objekt |
| [getAttachmentName](#getAttachmentName--) | Ermittelt den Namen des Anhangs, wenn das Ergebnis der Operation in HttpResponse-Objekten als Anhang gespeichert wird. |
| [getContentDisposition](#getContentDisposition--) | Ermittelt, wie der Inhalt gespeichert wird, wenn das Ergebnis der Operation in ein HttpResponse-Objekt gespeichert wird. |
| [getDestFileName](#getDestFileName--) | Ermittelt den Ziel-Dateinamen. |
| [getDestStream](#getDestStream--) | Liefert den Ziel-Stream. |
| [getDocument](#getDocument--) | Ruft das Dokument ab, an dem FormEditor arbeitet. |
| [getExportItems](#getExportItems--) | Liefert Optionen für das Kombinationsfeld mit Exportwerten. |
| [getFacade](#getFacade--) | Ermittelt die visuellen Attribute des Feldes. |
| [getItems](#getItems--) | Gibt das Element-Array zurück |
| [getRadioButtonItemSize](#getRadioButtonItemSize--) | Liefert oder setzt die Größe des Radio‑Button‑Elements (wenn ein neues Radio‑Button‑Feld hinzugefügt wird). |
| [getRadioGap](#getRadioGap--) | Ermittelt das Mitglied, das den Abstand zwischen zwei benachbarten Radio-Buttons in Pixeln speichert, Standard ist 50. |
| [getRadioHoriz](#getRadioHoriz--) | Liefert das Flag, das angibt, ob die Radio‑Buttons horizontal oder vertikal angeordnet sind; Standardwert ist true. |
| [getSaveOptions](#getSaveOptions--) | Ermittelt Speicheroptionen, wenn das Ergebnis als HttpResponse gespeichert wird. |
| [getSrcFileName](#getSrcFileName--) | Ermittelt den Namen der Quelldatei. |
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
| [setDestFileName](#setDestFileName-java.lang.String-) | Setzt den Ziel-Dateinamen. |
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
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Legt die Speicheroptionen fest, wenn das Ergebnis als HttpResponse gespeichert wird. |
| [setSrcFileName](#setSrcFileName-java.lang.String-) | Legt den Namen der Quelldatei fest. |
| [setSrcStream](#setSrcStream-java.io.InputStream-) | Legt den Quell-Stream fest. |
| [setSubmitFlag](#setSubmitFlag-java.lang.String-com.aspose.pdf.facades.SubmitFormFlag-) | Setze das Submit-Flag des Submit-Buttons. |
| [setSubmitFlag](#setSubmitFlag-com.aspose.pdf.facades.SubmitFormFlag-) | Legt die Übermittlungs-Flags des Submit-Buttons fest |
| [setSubmitUrl](#setSubmitUrl-java.lang.String-java.lang.String-) | Legt die URL des Buttons fest. |
| [single2Multiple](#single2Multiple-java.lang.String-) | Ändere ein einzeiliges Textfeld in ein mehrzeiliges. |

### addField {#addField-com.aspose.pdf.facades.FieldType-java.lang.String-int-float-float-float-float-}
Fügt ein Feld des angegebenen Typs zum Formular hinzu.

### addField {#addField-com.aspose.pdf.facades.FieldType-java.lang.String-java.lang.String-int-float-float-float-float-}
Fügt ein Feld des angegebenen Typs zum Formular hinzu.

### addListItem {#addListItem-java.lang.String-java.lang.String-}
Fügt ein neues Element zur Listbox hinzu.

### addListItem {#addListItem-java.lang.String-java.lang.String:A-}
Fügt ein neues Element mit Exportwert zum bestehenden Listbox-Feld hinzu, nur für das AcroForm-Combo-Box-Feld.

### addSubmitBtn {#addSubmitBtn-java.lang.String-int-java.lang.String-java.lang.String-float-float-float-float-}
Fügt einen Senden-Button zum Formular hinzu.

### close {#close--}
```
void close()
```

Schließt das Objekt

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
void decorateField()
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
void dispose()
```

Schließt das Objekt

### getAttachmentName {#getAttachmentName--}
```
String getAttachmentName()
```

Ermittelt den Namen des Anhangs, wenn das Ergebnis der Operation in HttpResponse-Objekten als Anhang gespeichert wird.

**Returns:**
String-Objekt

### getContentDisposition {#getContentDisposition--}
```
ContentDisposition getContentDisposition()
```

Ermittelt, wie der Inhalt gespeichert wird, wenn das Ergebnis der Operation in ein HttpResponse-Objekt gespeichert wird.

**Returns:**
ContentDisposition-Element

### getDestFileName {#getDestFileName--}
```
String getDestFileName()
```

Ermittelt den Ziel-Dateinamen.

**Returns:**
String-Wert

### getDestStream {#getDestStream--}
```
OutputStream getDestStream()
```

Liefert den Ziel-Stream.

**Returns:**
OutputStream-Objekt

### getDocument {#getDocument--}
```
IDocument getDocument()
```

Ruft das Dokument ab, an dem FormEditor arbeitet.

**Returns:**
IDocument‑Objekt

### getExportItems {#getExportItems--}
```
String [][] getExportItems()
```

Liefert Optionen für das Kombinationsfeld mit Exportwerten.

**Returns:**
String[][]-Objekt

### getFacade {#getFacade--}
```
FormFieldFacade getFacade()
```

Ermittelt die visuellen Attribute des Feldes.

**Returns:**
FormFieldFacade-Objekt

### getItems {#getItems--}
```
String [] getItems()
```

Gibt das Element-Array zurück

**Returns:**
String[]-Objekt

### getRadioButtonItemSize {#getRadioButtonItemSize--}
```
double getRadioButtonItemSize()
```

Liefert oder setzt die Größe des Radio‑Button‑Elements (wenn ein neues Radio‑Button‑Feld hinzugefügt wird).

**Returns:**
boolescher Wert

### getRadioGap {#getRadioGap--}
```
float getRadioGap()
```

Ermittelt das Mitglied, das den Abstand zwischen zwei benachbarten Radio-Buttons in Pixeln speichert, Standard ist 50.

**Returns:**
float-Wert

### getRadioHoriz {#getRadioHoriz--}
```
boolean getRadioHoriz()
```

Liefert das Flag, das angibt, ob die Radio‑Buttons horizontal oder vertikal angeordnet sind; Standardwert ist true.

**Returns:**
boolescher Wert

### getSaveOptions {#getSaveOptions--}
```
SaveOptions getSaveOptions()
```

Ermittelt Speicheroptionen, wenn das Ergebnis als HttpResponse gespeichert wird.

**Returns:**
SaveOptions-Objekt

### getSrcFileName {#getSrcFileName--}
```
String getSrcFileName()
```

Ermittelt den Namen der Quelldatei.

**Returns:**
String-Wert

### getSrcStream {#getSrcStream--}
```
InputStream getSrcStream()
```

Ermittelt den Quell-Stream.

**Returns:**
InputStream‑Objekt

### getSubmitFlag {#getSubmitFlag--}
```
SubmitFormFlag getSubmitFlag()
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
void resetFacade()
```

Setzt alle visuellen Attribute auf einen leeren Wert zurück.

### resetInnerFacade {#resetInnerFacade--}
```
void resetInnerFacade()
```

Setzt alle visuellen Attribute der inneren Fassade auf einen leeren Wert zurück.

### save {#save--}
```
void save()
```

Speichert Änderungen in die Zieldatei.

### setAttachmentName {#setAttachmentName-java.lang.String-}
Legt den Namen des Anhangs fest, wenn das Ergebnis der Operation in HttpResponse-Objekten als Anhang gespeichert wird.

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
Legt fest, wie Inhalte gespeichert werden, wenn das Ergebnis der Operation in ein HttpResponse-Objekt gespeichert wird.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Setzt das PDF‑Dateiformat PdfFormat.

### setDestFileName {#setDestFileName-java.lang.String-}
Setzt den Ziel-Dateinamen.

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
void setRadioButtonItemSize(double value)
```

Liefert oder setzt die Größe des Radio‑Button‑Elements (wenn ein neues Radio‑Button‑Feld hinzugefügt wird).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### setRadioGap {#setRadioGap-float-}
```
void setRadioGap(float value)
```

Setze das Mitglied, um den Abstand zwischen zwei benachbarten Radio-Buttons in Pixeln zu speichern, Standard ist 50.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | float-Wert |

### setRadioHoriz {#setRadioHoriz-boolean-}
```
void setRadioHoriz(boolean value)
```

Setze das Flag, um anzugeben, ob die Radio-Buttons horizontal oder vertikal angeordnet sind, Standardwert ist true.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Legt die Speicheroptionen fest, wenn das Ergebnis als HttpResponse gespeichert wird.

### setSrcFileName {#setSrcFileName-java.lang.String-}
Legt den Namen der Quelldatei fest.

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
