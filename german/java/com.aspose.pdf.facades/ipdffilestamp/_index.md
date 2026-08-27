---
title: "IPdfFileStamp"
linktitle: "IPdfFileStamp"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Schnittstelle zum Hinzufügen von Stempeln (Wasserzeichen oder Hintergrund) zu PDF-Dateien."
type: docs
weight: 320
url: /de/java/com.aspose.pdf.facades/ipdffilestamp/
---
```
public interface IPdfFileStamp
```

Schnittstelle zum Hinzufügen von Stempeln (Wasserzeichen oder Hintergrund) zu PDF-Dateien.

## Felder

| Feld | Beschreibung |
| --- | --- |
| [POS_BOTTOM_LEFT](#POS_BOTTOM_LEFT) | Untere linke Position. |
| [POS_BOTTOM_MIDDLE](#POS_BOTTOM_MIDDLE) | Untere mittlere Position. |
| [POS_BOTTOM_RIGHT](#POS_BOTTOM_RIGHT) | Untere rechte Position. |
| [POS_SIDES_LEFT](#POS_SIDES_LEFT) | Linke Position. |
| [POS_SIDES_RIGHT](#POS_SIDES_RIGHT) | Rechte Position. |
| [POS_UPPER_LEFT](#POS_UPPER_LEFT) | Obere linke Position. |
| [POS_UPPER_MIDDLE](#POS_UPPER_MIDDLE) | Obere mittlere Position. |
| [POS_UPPER_RIGHT](#POS_UPPER_RIGHT) | Obere rechte Position. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [addFooter](#addFooter-com.aspose.pdf.facades.FormattedText-float-) | Fügt den Seiten des Dokuments eine Fußzeile hinzu. |
| [addFooter](#addFooter-com.aspose.pdf.facades.FormattedText-float-float-float-) | Fügt den Seiten des Dokuments eine Fußzeile hinzu. |
| [addFooter](#addFooter-java.io.InputStream-float-) | Fügt ein Bild als Fußzeile der Seite hinzu. |
| [addFooter](#addFooter-java.io.InputStream-float-float-float-) | Fügt ein Bild als Fußzeile der Seite hinzu. |
| [addFooter](#addFooter-java.lang.String-float-) | Fügt ein Bild als Fußzeile zu den Seiten des Dokuments hinzu. |
| [addFooter](#addFooter-java.lang.String-float-float-float-) | Fügt Bild als Fußzeile der Seiten hinzu. |
| [addHeader](#addHeader-com.aspose.pdf.facades.FormattedText-float-) | Fügt Kopfzeile zur Seite hinzu. |
| [addHeader](#addHeader-com.aspose.pdf.facades.FormattedText-float-float-float-) | Fügt Kopfzeile zu den Seiten der Datei hinzu. |
| [addHeader](#addHeader-java.io.InputStream-float-) | Fügt Bild als Kopfzeile auf den Seiten hinzu. |
| [addHeader](#addHeader-java.io.InputStream-float-float-float-) | Fügt Bild oben auf der Seite hinzu. |
| [addHeader](#addHeader-java.lang.String-float-) | Fügt Bild als Kopfzeile zu den Seiten der Datei hinzu. |
| [addHeader](#addHeader-java.lang.String-float-float-float-) | Fügt Bild als Kopfzeile auf den Seiten hinzu. |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-) | Fügt Seitenzahl zur Seite hinzu. |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-float-float-) | Fügt Seitenzahl an der angegebenen Position auf der Seite hinzu. |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-int-) | Fügt Seitenzahl zu den Seiten hinzu. |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-) | Fügt Seitenzahl zu den Seiten des Dokuments hinzu. |
| [addPageNumber](#addPageNumber-java.lang.String-) | Fügt Seitenzahl zur Datei hinzu. |
| [addPageNumber](#addPageNumber-java.lang.String-float-float-) | Fügt Seitenzahl an der angegebenen Position auf der Seite hinzu. |
| [addPageNumber](#addPageNumber-java.lang.String-int-) | Fügt Seitenzahl zu den Seiten hinzu. |
| [addPageNumber](#addPageNumber-java.lang.String-int-float-float-float-float-) | Fügt Seitenzahl zu den Seiten des Dokuments hinzu. |
| [addStamp](#addStamp-com.aspose.pdf.facades.Stamp-) | Fügt Stempel zur Datei hinzu. |
| [close](#close--) | Schließt geöffnete Dateien und speichert Änderungen. |
| [dispose](#dispose--) | Veraltet. |
| [getAttachmentName](#getAttachmentName--) | Ermittelt den Namen des Anhangs, wenn das Ergebnis der Operation in HttpResponse-Objekten als Anhang gespeichert wird. |
| [getContentDisposition](#getContentDisposition--) | Ermittelt, wie der Inhalt gespeichert wird, wenn das Ergebnis der Operation in ein HttpResponse-Objekt gespeichert wird. |
| [getDocument](#getDocument--) | Ermittelt das Dokument, an dem PdfFileStamp arbeitet. |
| [getInputFile](#getInputFile--) | Ermittelt Name und Pfad der Eingabedatei. |
| [getInputStream](#getInputStream--) | Ermittelt Eingabestream. |
| [getKeepSecurity](#getKeepSecurity--) | Behält Sicherheit bei, wenn wahr. |
| [getOutputFile](#getOutputFile--) | Ermittelt Name und Pfad der Ausgabedatei. |
| [getOutputStream](#getOutputStream--) | Ermittelt Ausgabestream. |
| [getPageHeight](#getPageHeight--) | Ermittelt Höhe der ersten Seite in der Quelldatei. |
| [getPageNumberRotation](#getPageNumberRotation--) | Ermittelt Drehung der Seitenzahl. |
| [getPageWidth](#getPageWidth--) | Ermittelt Breite der ersten Seite in der Eingabedatei. |
| [getSaveOptions](#getSaveOptions--) | Ermittelt Speicheroptionen, wenn das Ergebnis als HttpResponse gespeichert wird. |
| [getStartingNumber](#getStartingNumber--) | Ermittelt oder setzt die Startnummer für die erste Seite in der Eingabedatei. |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | Legt den Namen des Anhangs fest, wenn das Ergebnis der Operation in HttpResponse-Objekten als Anhang gespeichert wird. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | Legt fest, wie Inhalte gespeichert werden, wenn das Ergebnis der Operation in ein HttpResponse-Objekt gespeichert wird. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | Legt das PDF-Dateiformat fest. |
| [setInputFile](#setInputFile-java.lang.String-) | Legt den Namen und Pfad der Eingabedatei fest. |
| [setInputStream](#setInputStream-java.io.InputStream-) | Legt den Eingabestream fest. |
| [setKeepSecurity](#setKeepSecurity-boolean-) | Sicherheit beibehalten festlegen. |
| [setOutputFile](#setOutputFile-java.lang.String-) | Legt den Namen und Pfad der Ausgabedatei fest. |
| [setOutputStream](#setOutputStream-java.io.OutputStream-) | Setzt den Ausgabestream. |
| [setPageNumberRotation](#setPageNumberRotation-float-) | Legt die Drehung der Seitenzahl fest. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Legt die Speicheroptionen fest, wenn das Ergebnis als HttpResponse gespeichert wird. |
| [setStartingNumber](#setStartingNumber-int-) | Legt die Startnummer für die erste Seite in der Eingabedatei fest. |

### POS_BOTTOM_LEFT {#POS_BOTTOM_LEFT}
```
static final int POS_BOTTOM_LEFT
```

Untere linke Position.

### POS_BOTTOM_MIDDLE {#POS_BOTTOM_MIDDLE}
```
static final int POS_BOTTOM_MIDDLE
```

Untere mittlere Position.

### POS_BOTTOM_RIGHT {#POS_BOTTOM_RIGHT}
```
static final int POS_BOTTOM_RIGHT
```

Untere rechte Position.

### POS_SIDES_LEFT {#POS_SIDES_LEFT}
```
static final int POS_SIDES_LEFT
```

Linke Position.

### POS_SIDES_RIGHT {#POS_SIDES_RIGHT}
```
static final int POS_SIDES_RIGHT
```

Rechte Position.

### POS_UPPER_LEFT {#POS_UPPER_LEFT}
```
static final int POS_UPPER_LEFT
```

Obere linke Position.

### POS_UPPER_MIDDLE {#POS_UPPER_MIDDLE}
```
static final int POS_UPPER_MIDDLE
```

Obere mittlere Position.

### POS_UPPER_RIGHT {#POS_UPPER_RIGHT}
```
static final int POS_UPPER_RIGHT
```

Obere rechte Position.

### addFooter {#addFooter-com.aspose.pdf.facades.FormattedText-float-}
Fügt den Seiten des Dokuments eine Fußzeile hinzu.

### addFooter {#addFooter-com.aspose.pdf.facades.FormattedText-float-float-float-}
Fügt den Seiten des Dokuments eine Fußzeile hinzu.

### addFooter {#addFooter-java.io.InputStream-float-}
Fügt ein Bild als Fußzeile der Seite hinzu.

### addFooter {#addFooter-java.io.InputStream-float-float-float-}
Fügt ein Bild als Fußzeile der Seite hinzu.

### addFooter {#addFooter-java.lang.String-float-}
Fügt ein Bild als Fußzeile zu den Seiten des Dokuments hinzu.

### addFooter {#addFooter-java.lang.String-float-float-float-}
Fügt Bild als Fußzeile der Seiten hinzu.

### addHeader {#addHeader-com.aspose.pdf.facades.FormattedText-float-}
Fügt Kopfzeile zur Seite hinzu.

### addHeader {#addHeader-com.aspose.pdf.facades.FormattedText-float-float-float-}
Fügt Kopfzeile zu den Seiten der Datei hinzu.

### addHeader {#addHeader-java.io.InputStream-float-}
Fügt Bild als Kopfzeile auf den Seiten hinzu.

### addHeader {#addHeader-java.io.InputStream-float-float-float-}
Fügt Bild oben auf der Seite hinzu.

### addHeader {#addHeader-java.lang.String-float-}
Fügt Bild als Kopfzeile zu den Seiten der Datei hinzu.

### addHeader {#addHeader-java.lang.String-float-float-float-}
Fügt Bild als Kopfzeile auf den Seiten hinzu.

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-}
Fügt Seitenzahl zur Seite hinzu.

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-float-float-}
Fügt Seitenzahl an der angegebenen Position auf der Seite hinzu.

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-int-}
Fügt Seitenzahl zu den Seiten hinzu.

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-}
Fügt Seitenzahl zu den Seiten des Dokuments hinzu.

### addPageNumber {#addPageNumber-java.lang.String-}
Fügt Seitenzahl zur Datei hinzu.

### addPageNumber {#addPageNumber-java.lang.String-float-float-}
Fügt Seitenzahl an der angegebenen Position auf der Seite hinzu.

### addPageNumber {#addPageNumber-java.lang.String-int-}
Fügt Seitenzahl zu den Seiten hinzu.

### addPageNumber {#addPageNumber-java.lang.String-int-float-float-float-float-}
Fügt Seitenzahl zu den Seiten des Dokuments hinzu.

### addStamp {#addStamp-com.aspose.pdf.facades.Stamp-}
Fügt Stempel zur Datei hinzu.

### close {#close--}
```
void close()
```

Schließt geöffnete Dateien und speichert Änderungen.

### dispose {#dispose--}
```
@Deprecated void dispose()
```

Veraltet.

### getAttachmentName {#getAttachmentName--}
```
String getAttachmentName()
```

Ermittelt den Namen des Anhangs, wenn das Ergebnis der Operation in HttpResponse-Objekten als Anhang gespeichert wird.

**Returns:**
String Wert

### getContentDisposition {#getContentDisposition--}
```
ContentDisposition getContentDisposition()
```

Ermittelt, wie der Inhalt gespeichert wird, wenn das Ergebnis der Operation in ein HttpResponse-Objekt gespeichert wird.

**Returns:**
ContentDisposition-Element

### getDocument {#getDocument--}
```
IDocument getDocument()
```

Ermittelt das Dokument, an dem PdfFileStamp arbeitet.

**Returns:**
IDocument‑Objekt

### getInputFile {#getInputFile--}
```
String getInputFile()
```

Ermittelt Name und Pfad der Eingabedatei.

**Returns:**
String-Objekt

### getInputStream {#getInputStream--}
```
InputStream getInputStream()
```

Ermittelt Eingabestream.

**Returns:**
InputStream‑Objekt

### getKeepSecurity {#getKeepSecurity--}
```
boolean getKeepSecurity()
```

Behält Sicherheit bei, wenn wahr.

**Returns:**
boolescher Wert

### getOutputFile {#getOutputFile--}
```
String getOutputFile()
```

Ermittelt Name und Pfad der Ausgabedatei.

**Returns:**
String-Objekt

### getOutputStream {#getOutputStream--}
```
OutputStream getOutputStream()
```

Ermittelt Ausgabestream.

**Returns:**
OutputStream-Objekt

### getPageHeight {#getPageHeight--}
```
float getPageHeight()
```

Ermittelt Höhe der ersten Seite in der Quelldatei.

**Returns:**
float-Wert

### getPageNumberRotation {#getPageNumberRotation--}
```
float getPageNumberRotation()
```

Ermittelt Drehung der Seitenzahl.

**Returns:**
float-Wert

### getPageWidth {#getPageWidth--}
```
float getPageWidth()
```

Ermittelt Breite der ersten Seite in der Eingabedatei.

**Returns:**
float-Wert

### getSaveOptions {#getSaveOptions--}
```
SaveOptions getSaveOptions()
```

Ermittelt Speicheroptionen, wenn das Ergebnis als HttpResponse gespeichert wird.

**Returns:**
SaveOptions-Objekt

### getStartingNumber {#getStartingNumber--}
```
int getStartingNumber()
```

Ermittelt oder setzt die Startnummer für die erste Seite in der Eingabedatei.

**Returns:**
int-Wert

### setAttachmentName {#setAttachmentName-java.lang.String-}
Legt den Namen des Anhangs fest, wenn das Ergebnis der Operation in HttpResponse-Objekten als Anhang gespeichert wird.

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
Legt fest, wie Inhalte gespeichert werden, wenn das Ergebnis der Operation in ein HttpResponse-Objekt gespeichert wird.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Legt das PDF-Dateiformat fest.

### setInputFile {#setInputFile-java.lang.String-}
Legt den Namen und Pfad der Eingabedatei fest.

### setInputStream {#setInputStream-java.io.InputStream-}
Legt den Eingabestream fest.

### setKeepSecurity {#setKeepSecurity-boolean-}
```
void setKeepSecurity(boolean value)
```

Sicherheit beibehalten festlegen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setOutputFile {#setOutputFile-java.lang.String-}
Legt den Namen und Pfad der Ausgabedatei fest.

### setOutputStream {#setOutputStream-java.io.OutputStream-}
Setzt den Ausgabestream.

### setPageNumberRotation {#setPageNumberRotation-float-}
```
void setPageNumberRotation(float value)
```

Legt die Drehung der Seitenzahl fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | float-Wert |

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Legt die Speicheroptionen fest, wenn das Ergebnis als HttpResponse gespeichert wird.

### setStartingNumber {#setStartingNumber-int-}
```
void setStartingNumber(int value)
```

Legt die Startnummer für die erste Seite in der Eingabedatei fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |
