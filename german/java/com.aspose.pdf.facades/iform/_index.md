---
title: "IForm"
linktitle: "IForm"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Klasse, die ein Acro-Formularobjekt darstellt."
type: docs
weight: 250
url: /de/java/com.aspose.pdf.facades/iform/
---
```
public interface IForm extends com.aspose.ms.System.IDisposable, Closeable
```

Klasse, die ein Acro-Formularobjekt darstellt.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [close](#close--) | Schließt geöffnete Dateien, ohne Änderungen vorzunehmen. |
| [exportFdf](#exportFdf-java.io.OutputStream-) | Exportiert den Inhalt der Felder des PDFs in den FDF-Stream. |
| [exportXfdf](#exportXfdf-java.io.OutputStream-) | Exportiert den Inhalt der Felder des PDFs in den XML-Stream. |
| [exportXml](#exportXml-java.io.OutputStream-) | Exportiert den Inhalt der Felder des PDFs in den XML-Stream. |
| [fillBarcodeField](#fillBarcodeField-java.lang.String-java.lang.String-) | Füllt ein Barcode-Feld gemäß seinem vollqualifizierten Feldnamen. |
| [fillField](#fillField-java.lang.String-boolean-) | Füllt das Kontrollkästchenfeld mit einem booleschen Wert. |
| [fillField](#fillField-java.lang.String-int-) | Füllt das Optionsfeld mit einem gültigen Indexwert gemäß einem vollqualifizierten Feldnamen. |
| [fillField](#fillField-java.lang.String-java.lang.String-) | Füllt das Feld mit einem gültigen Wert gemäß einem vollqualifizierten Feldnamen. |
| [fillField](#fillField-java.lang.String-java.lang.String:A-) | Füllt ein Feld mit mehreren Auswahlen. Hinweis: nur für AcroForm-Listenfeld. |
| [fillField](#fillField-java.lang.String-java.lang.String-boolean-) | FillField |
| [fillImageField](#fillImageField-java.lang.String-java.io.InputStream-) | Überlädt die Funktion von FillImageField. |
| [fillImageField](#fillImageField-java.lang.String-java.lang.String-) | Fügt ein Bild in das vorhandene Schaltflächenfeld als dessen Darstellung gemäß seinem vollqualifizierten Feldnamen ein. |
| [flattenAllFields](#flattenAllFields--) | Flacht alle Felder ab. |
| [flattenField](#flattenField-java.lang.String-) | Flacht ein angegebenes Feld mit dem vollqualifizierten Feldnamen ab. |
| [getAttachmentName](#getAttachmentName--) | Liest oder setzt den Namen des Anhangs, wenn das Ergebnis der Operation in HttpResponse-Objekten als Anhang gespeichert wird. |
| [getButtonOptionCurrentValue](#getButtonOptionCurrentValue-java.lang.String-) | Gibt den aktuellen Wert für Optionsfelder von Optionsschaltern zurück. |
| [getButtonOptionValues](#getButtonOptionValues-java.lang.String-) | Ermittelt die Optionsfelder von Optionsschaltern und zugehörige Werte basierend auf dem Feldnamen. |
| [getButtonOptionValuesInternal](#getButtonOptionValuesInternal-java.lang.String-) | Ermittelt die Optionsfelder von Optionsschaltern und zugehörige Werte basierend auf dem Feldnamen. |
| [getContentDisposition](#getContentDisposition--) | Liest oder setzt, wie der Inhalt gespeichert wird, wenn das Ergebnis der Operation in einem HttpResponse-Objekt gespeichert wird. |
| [getDestFileName](#getDestFileName--) | Ermittelt den Ziel-Dateinamen. |
| [getDestStream](#getDestStream--) | Liefert den Ziel-Stream. |
| [getDocument](#getDocument--) | Liest das Dokument, an dem das Formular arbeitet. |
| [getField](#getField-java.lang.String-) | Ermittelt den Wert des Feldes gemäß seinem Feldnamen. |
| [getFieldFacade](#getFieldFacade-java.lang.String-) | Gibt das FrogmFieldFacade-Objekt zurück, das alle Darstellungsattribute enthält. |
| [getFieldFlag](#getFieldFlag-java.lang.String-) | Gibt die Flags des Feldes zurück. |
| [getFieldLimit](#getFieldLimit-java.lang.String-) | Ermittelt die Beschränkung des Textfeldes. |
| [getFieldNames](#getFieldNames--) | Ermittelt die Liste der Feldnamen im Formular. |
| [getFieldType](#getFieldType-java.lang.String-) | Gibt den Typ des Feldes zurück. |
| [getFormSubmitButtonNames](#getFormSubmitButtonNames--) | Ermittelt alle Namen der Formular-Submit-Schaltflächen. |
| [getFullFieldName](#getFullFieldName-java.lang.String-) | Ermittelt den vollständigen Feldnamen gemäß seinem kurzen Feldnamen. |
| [getRichText](#getRichText-java.lang.String-) | Ruft den Wert eines Rich-Text-Feldes ab, einschließlich der Formatierungsinformationen jedes Zeichens. |
| [getSaveOptions](#getSaveOptions--) | Liest oder setzt die Speicheroptionen, wenn das Ergebnis als HttpResponse gespeichert wird. |
| [getSrcFileName](#getSrcFileName--) | Liest den Quelldateinamen. |
| [getSrcStream](#getSrcStream--) | Ermittelt den Quell-Stream. |
| [getSubmitFlags](#getSubmitFlags-java.lang.String-) | Gibt die Übermittlungsflags des Submit-Buttons zurück |
| [importFdf](#importFdf-java.io.InputStream-) | Importiert den Inhalt der Felder aus der fdf-Datei und legt ihn in das neue PDF. |
| [importXfdf](#importXfdf-java.io.InputStream-) | Importiert den Inhalt der Felder aus der xfdf(xml)-Datei und legt ihn in das neue PDF. |
| [importXml](#importXml-java.io.InputStream-) | Importiert den Inhalt der Felder aus der xml‑Datei und legt ihn in das neue PDF. |
| [importXml](#importXml-java.io.InputStream-boolean-) | Importiert den Inhalt der Felder aus der xml‑Datei und legt ihn in das neue PDF. |
| [renameField](#renameField-java.lang.String-java.lang.String-) | Benennt ein Feld um. |
| [save](#save--) | Speichert die Werte der ausgefüllten Felder und schließt das geöffnete PDF-Dokument. |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | Legt den Namen des Anhangs fest, wenn das Ergebnis der Operation in HttpResponse-Objekten als Anhang gespeichert wird. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | Legt fest, wie Inhalte gespeichert werden, wenn das Ergebnis der Operation in ein HttpResponse-Objekt gespeichert wird. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | Legt das PDF-Dateiformat fest. |
| [setDestFileName](#setDestFileName-java.lang.String-) | Setzt den Ziel-Dateinamen. |
| [setDestStream](#setDestStream-java.io.OutputStream-) | Liefert den Ziel-Stream. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Liest oder setzt die Speicheroptionen, wenn das Ergebnis als HttpResponse gespeichert wird. |
| [setSrcFileName](#setSrcFileName-java.lang.String-) | Legt den Quelldateinamen fest. |
| [setSrcStream](#setSrcStream-java.io.InputStream-) | Ermittelt den Quell-Stream. |

### close {#close--}
```
void close()
```

Schließt geöffnete Dateien, ohne Änderungen vorzunehmen.

### exportFdf {#exportFdf-java.io.OutputStream-}
Exportiert den Inhalt der Felder des PDFs in den FDF-Stream.

### exportXfdf {#exportXfdf-java.io.OutputStream-}
Exportiert den Inhalt der Felder des PDFs in den XML-Stream.

### exportXml {#exportXml-java.io.OutputStream-}
Exportiert den Inhalt der Felder des PDFs in den XML-Stream.

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
FillField

### fillImageField {#fillImageField-java.lang.String-java.io.InputStream-}
Überlädt die Funktion von FillImageField.

### fillImageField {#fillImageField-java.lang.String-java.lang.String-}
Fügt ein Bild in das vorhandene Schaltflächenfeld als dessen Darstellung gemäß seinem vollqualifizierten Feldnamen ein.

### flattenAllFields {#flattenAllFields--}
```
void flattenAllFields()
```

Flacht alle Felder ab.

### flattenField {#flattenField-java.lang.String-}
Flacht ein angegebenes Feld mit dem vollqualifizierten Feldnamen ab.

### getAttachmentName {#getAttachmentName--}
```
String getAttachmentName()
```

Liest oder setzt den Namen des Anhangs, wenn das Ergebnis der Operation in HttpResponse-Objekten als Anhang gespeichert wird.

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
ContentDisposition getContentDisposition()
```

Liest oder setzt, wie der Inhalt gespeichert wird, wenn das Ergebnis der Operation in einem HttpResponse-Objekt gespeichert wird.

**Returns:**
ContentDisposition-Element

### getDestFileName {#getDestFileName--}
```
String getDestFileName()
```

Ermittelt den Ziel-Dateinamen.

**Returns:**
String-Objekt

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

Liest das Dokument, an dem das Formular arbeitet.

**Returns:**
IDocument‑Objekt

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
String [] getFieldNames()
```

Ermittelt die Liste der Feldnamen im Formular.

**Returns:**
String[]-Objekt

### getFieldType {#getFieldType-java.lang.String-}
Gibt den Typ des Feldes zurück.

### getFormSubmitButtonNames {#getFormSubmitButtonNames--}
```
String [] getFormSubmitButtonNames()
```

Ermittelt alle Namen der Formular-Submit-Schaltflächen.

**Returns:**
String[]-Objekt

### getFullFieldName {#getFullFieldName-java.lang.String-}
Ermittelt den vollständigen Feldnamen gemäß seinem kurzen Feldnamen.

### getRichText {#getRichText-java.lang.String-}
Ruft den Wert eines Rich-Text-Feldes ab, einschließlich der Formatierungsinformationen jedes Zeichens.

### getSaveOptions {#getSaveOptions--}
```
SaveOptions getSaveOptions()
```

Liest oder setzt die Speicheroptionen, wenn das Ergebnis als HttpResponse gespeichert wird.

**Returns:**
SaveOptions-Objekt

### getSrcFileName {#getSrcFileName--}
```
String getSrcFileName()
```

Liest den Quelldateinamen.

**Returns:**
String-Objekt

### getSrcStream {#getSrcStream--}
```
InputStream getSrcStream()
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

### renameField {#renameField-java.lang.String-java.lang.String-}
Benennt ein Feld um.

### save {#save--}
```
void save()
```

Speichert die Werte der ausgefüllten Felder und schließt das geöffnete PDF-Dokument.

### setAttachmentName {#setAttachmentName-java.lang.String-}
Legt den Namen des Anhangs fest, wenn das Ergebnis der Operation in HttpResponse-Objekten als Anhang gespeichert wird.

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
Legt fest, wie Inhalte gespeichert werden, wenn das Ergebnis der Operation in ein HttpResponse-Objekt gespeichert wird.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Legt das PDF-Dateiformat fest.

### setDestFileName {#setDestFileName-java.lang.String-}
Setzt den Ziel-Dateinamen.

### setDestStream {#setDestStream-java.io.OutputStream-}
Liefert den Ziel-Stream.

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Liest oder setzt die Speicheroptionen, wenn das Ergebnis als HttpResponse gespeichert wird.

### setSrcFileName {#setSrcFileName-java.lang.String-}
Legt den Quelldateinamen fest.

### setSrcStream {#setSrcStream-java.io.InputStream-}
Ermittelt den Quell-Stream.
