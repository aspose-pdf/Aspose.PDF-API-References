---
title: "IPdfFileEditor"
linktitle: "IPdfFileEditor"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Implementiert Operationen mit PDF-Dateien: Zusammenführen, Aufteilen, Extrahieren von Seiten, Erstellen eines Booklets usw."
type: docs
weight: 290
url: /de/java/com.aspose.pdf.facades/ipdffileeditor/
---
```
public interface IPdfFileEditor
```

Implementiert Operationen mit PDF-Dateien: Zusammenführen, Aufteilen, Extrahieren von Seiten, Erstellen eines Booklets usw.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [addMargins](#addMargins-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-) | Ändert die Größe des Seiteninhalts und fügt angegebene Ränder hinzu. |
| [addMargins](#addMargins-java.lang.String-java.lang.String-int:A-double-double-double-double-) | Ändert die Größe des Seiteninhalts und fügt angegebene Ränder hinzu. |
| [addMarginsPct](#addMarginsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-) | Ändert die Größe des Seiteninhalts und fügt angegebene Ränder hinzu. |
| [addMarginsPct](#addMarginsPct-java.lang.String-java.lang.String-int:A-double-double-double-double-) | Ändert die Größe des Seiteninhalts und fügt angegebene Ränder hinzu. |
| [append](#append-java.io.InputStream-java.io.InputStream:A-int-int-java.io.OutputStream-) | Fügt Seiten an, die aus einem Array von Dokumenten in portStreams ausgewählt werden. |
| [append](#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-) | Fügt Seiten an, die aus portStream im Bereich von startPage bis endPage ausgewählt werden, in portStream am Ende von firstInputStream. |
| [append](#append-java.lang.String-java.lang.String:A-int-int-java.lang.String-) | Fügt Seiten an, die aus portFiles-Dokumenten ausgewählt werden. |
| [append](#append-java.lang.String-java.lang.String-int-int-java.lang.String-) | Fügt Seiten an, die aus portFile im Bereich von startPage bis endPage ausgewählt werden, in portFile am Ende von firstInputFile. |
| [concatenate](#concatenate-com.aspose.pdf.IDocument:A-com.aspose.pdf.IDocument-) | Verkettet Dokumente. |
| [concatenate](#concatenate-java.io.InputStream:A-java.io.OutputStream-) | Verkettet Dateien |
| [concatenate](#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | Fügt zwei PDF-Dokumente zu einem neuen PDF-Dokument zusammen, wobei die Seiten abwechselnd angeordnet werden, und füllt leere Stellen mit leeren Seiten. |
| [concatenate](#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | Verkettet zwei Dateien. |
| [concatenate](#concatenate-java.lang.String:A-java.lang.String-) | Verkettet Dateien zu einer Datei. |
| [concatenate](#concatenate-java.lang.String-java.lang.String-java.lang.String-) | Verkettet zwei Dateien. |
| [concatenate](#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | Fügt zwei PDF-Dokumente zu einem neuen PDF-Dokument zusammen, wobei die Seiten abwechselnd angeordnet werden, und füllt leere Stellen mit leeren Seiten. |
| [delete](#delete-java.io.InputStream-int:A-java.io.OutputStream-) | Löscht Seiten, die durch ein Zahlenarray angegeben sind, aus der Eingabedatei und speichert sie als neue PDF-Datei. |
| [delete](#delete-java.lang.String-int:A-java.lang.String-) | Löscht Seiten, die durch ein Zahlenarray angegeben sind, aus der Eingabedatei und speichert sie als neue PDF-Datei. |
| [extract](#extract-java.io.InputStream-int:A-java.io.OutputStream-) | Extrahiert Seiten, die durch ein Zahlenarray angegeben sind, und speichert sie als neue PDF-Datei. |
| [extract](#extract-java.io.InputStream-int-int-java.io.OutputStream-) | Extrahiert Seiten aus der Eingabedatei und speichert sie als neue PDF-Datei. |
| [extract](#extract-java.lang.String-int:A-java.lang.String-) | Extrahiert Seiten, die durch ein Zahlenarray angegeben sind, und speichert sie als neue PDF-Datei. |
| [extract](#extract-java.lang.String-int-int-java.lang.String-) | Extrahiert Seiten aus der Eingabedatei und speichert sie als neue PDF-Datei. |
| [getAllowConcatenateExceptions](#getAllowConcatenateExceptions--) | ist Allow Concatenate Exceptions |
| [getAttachmentName](#getAttachmentName--) | Ermittelt den Namen des Anhangs, wenn das Ergebnis der Operation in HttpServletResponse-Objekten als Anhang gespeichert wird. |
| [getCloseConcatenatedStreams](#getCloseConcatenatedStreams--) | Wenn auf true gesetzt, werden Streams nach der Operation geschlossen. |
| [getContentDisposition](#getContentDisposition--) | Ermittelt, wie der Inhalt gespeichert wird, wenn das Ergebnis der Operation in ein HttpServletResponse-Objekt gespeichert wird. |
| [getConversionLog](#getConversionLog--) | Ermittelt das Protokoll des Konvertierungsprozesses. |
| [getCorruptedFileAction](#getCorruptedFileAction--) | Diese Eigenschaft definiert das Verhalten, wenn der Verkettungsprozess auf eine beschädigte Datei trifft. |
| [getIncrementalUpdates](#getIncrementalUpdates--) | Wenn true, werden während der Zusammenführung inkrementelle Updates durchgeführt. |
| [getKeepFieldsUnique](#getKeepFieldsUnique--) | Wenn true, werden Feldnamen eindeutig gemacht, wenn Formulare zusammengeführt werden. |
| [getLastException](#getLastException--) | Liefert die zuletzt aufgetretene Ausnahme. |
| [getMergeDuplicateLayers](#getMergeDuplicateLayers--) | Optionale Inhalte von zusammengeführten Dokumenten mit gleichen Namen werden in einem Layer im resultierenden Dokument zusammengeführt, wenn diese Eigenschaft true ist. |
| [getMergeDuplicateOutlines](#getMergeDuplicateOutlines--) | Wenn true, werden doppelte Gliederungen zusammengeführt. |
| [getOwnerPassword](#getOwnerPassword--) | Liefert das Passwort des Eigentümers, wenn die Quell‑Pdf‑Datei verschlüsselt ist. |
| [getPreserveUserRights](#getPreserveUserRights--) | Wenn true, werden die Benutzerrechte des ersten Dokuments auf das zusammengeführte Dokument angewendet. |
| [getRemoveSignatures](#getRemoveSignatures--) | Wenn true, werden alle Signaturen aus den Feldern entfernt (Felder bleiben erhalten); andernfalls können ungültige Signaturen entstehen. |
| [getSaveOptions](#getSaveOptions--) | Liest oder setzt Speicheroptionen, wenn das Ergebnis als HttpServletResponse gespeichert wird. |
| [getUniqueSuffix](#getUniqueSuffix--) | Ermittelt das Format des Suffixes, das dem Feldnamen hinzugefügt wird, um ihn eindeutig zu machen, wenn Formulare zusammengeführt werden. |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int:A-java.io.OutputStream-) | Fügt Seiten aus einer anderen Datei in die Eingabe‑Pdf‑Datei ein. |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-) | Fügt Seiten aus einer anderen Datei in die Eingabe‑Pdf‑Datei ein. |
| [insert](#insert-java.lang.String-int-java.lang.String-int:A-java.lang.String-) | Fügt Seiten aus einer anderen Datei in die Eingabe‑Pdf‑Datei ein. |
| [insert](#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-) | Fügt Seiten aus einer anderen Datei an einer Position in die Pdf‑Datei ein. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-) | Erstellt ein Heft aus dem InputStream und schreibt es in outputStream. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-int:A-int:A-) | Erstellt ein angepasstes Heft aus dem firstInputStream und schreibt es in outputStream. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-) | Erstellt ein Heft aus dem Eingabestream und speichert das Ergebnis in outputStream. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int:A-int:A-) | Erstellt ein Heft aus dem firstInputStream und schreibt es in outputStream. |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-) | Erstellt ein Heft aus der Eingabedatei und schreibt es in die Ausgabedatei. |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-int:A-int:A-) | Erstellt ein angepasstes Heft aus dem firstInputFile und schreibt es in outputFile. |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-) | Erstellt ein Heft aus dem inputFile und schreibt es in outputFile. |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-) | Erstellt ein angepasstes Heft aus dem firstInputFile und schreibt es in outputFile. |
| [makeNUp](#makeNUp-java.io.InputStream:A-java.io.OutputStream-boolean-) | Erstellt ein N‑Up‑Dokument aus den mehreren Eingabe‑PDF‑Streams und schreibt es in outputStream. |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | Erstellt ein N‑Up‑Dokument aus den beiden Eingabe‑PDF‑Streams und schreibt es in outputStream. |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-) | Erstellt ein N‑Up‑Dokument aus dem Eingabestream und speichert das Ergebnis in outputStream. |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-) | Erstellt ein N‑Up‑Dokument aus dem ersten Eingabestream und schreibt es in outputStream. |
| [makeNUp](#makeNUp-java.lang.String:A-java.lang.String-boolean-) | Erstellt ein N‑Up‑Dokument aus den mehreren Eingabe‑PDF‑Dateien und schreibt es in outputFile. |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-int-int-) | Erstellt ein N‑Up‑Dokument aus dem firstInputFile und schreibt es in outputFile. |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-) | Erstellt ein N‑Up‑Dokument aus der Eingabedatei und schreibt es in outputFile. |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-java.lang.String-) | Erstellt ein N‑Up‑Dokument aus den beiden Eingabe‑PDF‑Dateien und schreibt es in outputFile. |
| [resizeContents](#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-double-double-) | Ändert die Größe des Inhalts von Dokumentseiten. |
| [resizeContents](#resizeContents-java.lang.String-java.lang.String-int:A-double-double-) | Ändert die Größe des Inhalts von Dokumentseiten. |
| [resizeContentsPct](#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-) | Ändert die Größe des Inhalts von Dokumentseiten. |
| [resizeContentsPct](#resizeContentsPct-java.lang.String-java.lang.String-int:A-double-double-) | Ändert die Größe des Inhalts von Dokumentseiten. |
| [setAllowConcatenateExceptions](#setAllowConcatenateExceptions-boolean-) | Wenn auf true gesetzt, werden Ausnahmen ausgelöst, wenn ein Fehler auftritt. |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | Legt den Namen des Anhangs fest, wenn das Ergebnis der Operation in HttpServletResponse-Objekten als Anhang gespeichert wird. |
| [setCloseConcatenatedStreams](#setCloseConcatenatedStreams-boolean-) | Wenn auf true gesetzt, werden Streams nach der Operation geschlossen. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | Legt fest, wie Inhalte gespeichert werden, wenn das Ergebnis der Operation in ein HttpServletResponse‑Objekt gespeichert wird. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | Legt das PDF-Dateiformat fest. |
| [setCorruptedFileAction](#setCorruptedFileAction-int-) | Diese Eigenschaft definiert das Verhalten, wenn der Verkettungsprozess auf eine beschädigte Datei trifft. |
| [setIncrementalUpdates](#setIncrementalUpdates-boolean-) | Wenn true, werden während der Zusammenführung inkrementelle Updates durchgeführt. |
| [setKeepFieldsUnique](#setKeepFieldsUnique-boolean-) | Wenn true, werden Feldnamen eindeutig gemacht, wenn Formulare zusammengeführt werden. |
| [setMergeDuplicateLayers](#setMergeDuplicateLayers-boolean-) | Optionale Inhalte von zusammengeführten Dokumenten mit gleichen Namen werden in einem Layer im resultierenden Dokument zusammengeführt, wenn diese Eigenschaft true ist. |
| [setMergeDuplicateOutlines](#setMergeDuplicateOutlines-boolean-) | Wenn true, werden doppelte Gliederungen zusammengeführt. |
| [setOwnerPassword](#setOwnerPassword-java.lang.String-) | Setzt das Passwort des Eigentümers, wenn die Quell‑Eingabe‑Pdf‑Datei verschlüsselt ist. |
| [setPreserveUserRights](#setPreserveUserRights-boolean-) | Wenn true, werden die Benutzerrechte des ersten Dokuments auf das zusammengeführte Dokument angewendet. |
| [setRemoveSignatures](#setRemoveSignatures-boolean-) | Wenn true, werden alle Signaturen aus den Feldern entfernt (Felder bleiben erhalten); andernfalls können ungültige Signaturen entstehen. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Setzt Speicheroptionen, wenn das Ergebnis als HttpServletResponse gespeichert wird. |
| [setUniqueSuffix](#setUniqueSuffix-java.lang.String-) | Setzt das Format des Suffixes, das dem Feldnamen hinzugefügt wird, um ihn eindeutig zu machen, wenn Formulare zusammengeführt werden. |
| [splitFromFirst](#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-) | Teilt vom Anfang bis zum angegebenen Ort,und speichert den vorderen Teil im Ausgabe‑Stream. |
| [splitFromFirst](#splitFromFirst-java.lang.String-int-java.lang.String-) | Teilt die Pdf‑Datei von der ersten Seite bis zum angegebenen Ort,und speichert den vorderen Teil als neue Datei. |
| [splitToBulks](#splitToBulks-java.io.InputStream-int:A:A-) | Teilt die Pdf‑Datei in mehrere Dokumente. Die Dokumente können einseitig oder mehrseitig sein. |
| [splitToBulks](#splitToBulks-java.lang.String-int:A:A-) | Teilt die Pdf‑Datei in mehrere Dokumente. Die Dokumente können einseitig oder mehrseitig sein. |
| [splitToEnd](#splitToEnd-java.io.InputStream-int-java.io.OutputStream-) | Teilt vom angegebenen Ort, und speichert den hinteren Teil als neue Datei‑Stream. |
| [splitToEnd](#splitToEnd-java.lang.String-int-java.lang.String-) | Teilt vom Ort, und speichert den hinteren Teil als neue Datei. |
| [splitToPages](#splitToPages-java.io.InputStream-) | Teilt die Pdf‑Datei in einseitige Dokumente. |
| [splitToPages](#splitToPages-java.io.InputStream-java.lang.String-) | Teilt die Pdf‑Datei in einseitige Dokumente und speichert sie im angegebenen Pfad. |
| [splitToPages](#splitToPages-java.lang.String-) | Teilt die PDF‑Datei in einseitige Dokumente. |
| [splitToPages](#splitToPages-java.lang.String-java.lang.String-) | Teilt die Pdf‑Datei in einseitige Dokumente und speichert sie im angegebenen Pfad. |

### addMargins {#addMargins-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-}
Ändert die Größe des Seiteninhalts und fügt angegebene Ränder hinzu.

### addMargins {#addMargins-java.lang.String-java.lang.String-int:A-double-double-double-double-}
Ändert die Größe des Seiteninhalts und fügt angegebene Ränder hinzu.

### addMarginsPct {#addMarginsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-}
Ändert die Größe des Seiteninhalts und fügt angegebene Ränder hinzu.

### addMarginsPct {#addMarginsPct-java.lang.String-java.lang.String-int:A-double-double-double-double-}
Ändert die Größe des Seiteninhalts und fügt angegebene Ränder hinzu.

### append {#append-java.io.InputStream-java.io.InputStream:A-int-int-java.io.OutputStream-}
Fügt Seiten an, die aus einem Array von Dokumenten in portStreams ausgewählt werden.

### append {#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-}
Fügt Seiten an, die aus portStream im Bereich von startPage bis endPage ausgewählt werden, in portStream am Ende von firstInputStream.

### append {#append-java.lang.String-java.lang.String:A-int-int-java.lang.String-}
Fügt Seiten an, die aus portFiles-Dokumenten ausgewählt werden.

### append {#append-java.lang.String-java.lang.String-int-int-java.lang.String-}
Fügt Seiten an, die aus portFile im Bereich von startPage bis endPage ausgewählt werden, in portFile am Ende von firstInputFile.

### concatenate {#concatenate-com.aspose.pdf.IDocument:A-com.aspose.pdf.IDocument-}
Verkettet Dokumente.

### concatenate {#concatenate-java.io.InputStream:A-java.io.OutputStream-}
Verkettet Dateien

### concatenate {#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
Fügt zwei PDF-Dokumente zu einem neuen PDF-Dokument zusammen, wobei die Seiten abwechselnd angeordnet werden, und füllt leere Stellen mit leeren Seiten.

### concatenate {#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
Verkettet zwei Dateien.

### concatenate {#concatenate-java.lang.String:A-java.lang.String-}
Verkettet Dateien zu einer Datei.

### concatenate {#concatenate-java.lang.String-java.lang.String-java.lang.String-}
Verkettet zwei Dateien.

### concatenate {#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
Fügt zwei PDF-Dokumente zu einem neuen PDF-Dokument zusammen, wobei die Seiten abwechselnd angeordnet werden, und füllt leere Stellen mit leeren Seiten.

### delete {#delete-java.io.InputStream-int:A-java.io.OutputStream-}
Löscht Seiten, die durch ein Zahlenarray angegeben sind, aus der Eingabedatei und speichert sie als neue PDF-Datei.

### delete {#delete-java.lang.String-int:A-java.lang.String-}
Löscht Seiten, die durch ein Zahlenarray angegeben sind, aus der Eingabedatei und speichert sie als neue PDF-Datei.

### extract {#extract-java.io.InputStream-int:A-java.io.OutputStream-}
Extrahiert Seiten, die durch ein Zahlenarray angegeben sind, und speichert sie als neue PDF-Datei.

### extract {#extract-java.io.InputStream-int-int-java.io.OutputStream-}
Extrahiert Seiten aus der Eingabedatei und speichert sie als neue PDF-Datei.

### extract {#extract-java.lang.String-int:A-java.lang.String-}
Extrahiert Seiten, die durch ein Zahlenarray angegeben sind, und speichert sie als neue PDF-Datei.

### extract {#extract-java.lang.String-int-int-java.lang.String-}
Extrahiert Seiten aus der Eingabedatei und speichert sie als neue PDF-Datei.

### getAllowConcatenateExceptions {#getAllowConcatenateExceptions--}
```
boolean getAllowConcatenateExceptions()
```

ist Allow Concatenate Exceptions

**Returns:**
boolescher Wert

### getAttachmentName {#getAttachmentName--}
```
String getAttachmentName()
```

Ermittelt den Namen des Anhangs, wenn das Ergebnis der Operation in HttpServletResponse-Objekten als Anhang gespeichert wird.

**Returns:**
String-Wert

### getCloseConcatenatedStreams {#getCloseConcatenatedStreams--}
```
boolean getCloseConcatenatedStreams()
```

Wenn auf true gesetzt, werden Streams nach der Operation geschlossen.

**Returns:**
boolescher Wert

### getContentDisposition {#getContentDisposition--}
```
ContentDisposition getContentDisposition()
```

Ermittelt, wie der Inhalt gespeichert wird, wenn das Ergebnis der Operation in ein HttpServletResponse-Objekt gespeichert wird.

**Returns:**
ContentDisposition-Element

### getConversionLog {#getConversionLog--}
```
String getConversionLog()
```

Ermittelt das Protokoll des Konvertierungsprozesses.

**Returns:**
String-Wert

### getCorruptedFileAction {#getCorruptedFileAction--}
```
int getCorruptedFileAction()
```

Diese Eigenschaft definiert das Verhalten, wenn der Verkettungsprozess auf eine beschädigte Datei trifft.

**Returns:**
ConcatenateCorruptedFileAction Element

### getIncrementalUpdates {#getIncrementalUpdates--}
```
boolean getIncrementalUpdates()
```

Wenn true, werden während der Zusammenführung inkrementelle Updates durchgeführt.

**Returns:**
boolescher Wert

### getKeepFieldsUnique {#getKeepFieldsUnique--}
```
boolean getKeepFieldsUnique()
```

Wenn true, werden Feldnamen eindeutig gemacht, wenn Formulare zusammengeführt werden.

**Returns:**
boolescher Wert

### getLastException {#getLastException--}
```
Exception getLastException()
```

Liefert die zuletzt aufgetretene Ausnahme.

**Returns:**
java.lang.Exception-Objekt

### getMergeDuplicateLayers {#getMergeDuplicateLayers--}
```
boolean getMergeDuplicateLayers()
```

Optionale Inhalte von zusammengeführten Dokumenten mit gleichen Namen werden in einem Layer im resultierenden Dokument zusammengeführt, wenn diese Eigenschaft true ist.

**Returns:**
boolescher Wert

### getMergeDuplicateOutlines {#getMergeDuplicateOutlines--}
```
boolean getMergeDuplicateOutlines()
```

Wenn true, werden doppelte Gliederungen zusammengeführt.

**Returns:**
boolescher Wert

### getOwnerPassword {#getOwnerPassword--}
```
String getOwnerPassword()
```

Liefert das Passwort des Eigentümers, wenn die Quell‑Pdf‑Datei verschlüsselt ist.

**Returns:**
String-Wert

### getPreserveUserRights {#getPreserveUserRights--}
```
boolean getPreserveUserRights()
```

Wenn true, werden die Benutzerrechte des ersten Dokuments auf das zusammengeführte Dokument angewendet.

**Returns:**
boolescher Wert

### getRemoveSignatures {#getRemoveSignatures--}
```
boolean getRemoveSignatures()
```

Wenn true, werden alle Signaturen aus den Feldern entfernt (Felder bleiben erhalten); andernfalls können ungültige Signaturen entstehen.

**Returns:**
boolescher Wert

### getSaveOptions {#getSaveOptions--}
```
SaveOptions getSaveOptions()
```

Liest oder setzt Speicheroptionen, wenn das Ergebnis als HttpServletResponse gespeichert wird.

**Returns:**
SaveOptions-Objekt

### getUniqueSuffix {#getUniqueSuffix--}
```
String getUniqueSuffix()
```

Ermittelt das Format des Suffixes, das dem Feldnamen hinzugefügt wird, um ihn eindeutig zu machen, wenn Formulare zusammengeführt werden.

**Returns:**
String-Wert

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int:A-java.io.OutputStream-}
Fügt Seiten aus einer anderen Datei in die Eingabe‑Pdf‑Datei ein.

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-}
Fügt Seiten aus einer anderen Datei in die Eingabe‑Pdf‑Datei ein.

### insert {#insert-java.lang.String-int-java.lang.String-int:A-java.lang.String-}
Fügt Seiten aus einer anderen Datei in die Eingabe‑Pdf‑Datei ein.

### insert {#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-}
Fügt Seiten aus einer anderen Datei an einer Position in die Pdf‑Datei ein.

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-}
Erstellt ein Heft aus dem InputStream und schreibt es in outputStream.

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-int:A-int:A-}
Erstellt ein angepasstes Heft aus dem firstInputStream und schreibt es in outputStream.

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-}
Erstellt ein Heft aus dem Eingabestream und speichert das Ergebnis in outputStream.

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int:A-int:A-}
Erstellt ein Heft aus dem firstInputStream und schreibt es in outputStream.

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-}
Erstellt ein Heft aus der Eingabedatei und schreibt es in die Ausgabedatei.

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-int:A-int:A-}
Erstellt ein angepasstes Heft aus dem firstInputFile und schreibt es in outputFile.

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-}
Erstellt ein Heft aus dem inputFile und schreibt es in outputFile.

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-}
Erstellt ein angepasstes Heft aus dem firstInputFile und schreibt es in outputFile.

### makeNUp {#makeNUp-java.io.InputStream:A-java.io.OutputStream-boolean-}
Erstellt ein N‑Up‑Dokument aus den mehreren Eingabe‑PDF‑Streams und schreibt es in outputStream.

### makeNUp {#makeNUp-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
Erstellt ein N‑Up‑Dokument aus den beiden Eingabe‑PDF‑Streams und schreibt es in outputStream.

### makeNUp {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-}
Erstellt ein N‑Up‑Dokument aus dem Eingabestream und speichert das Ergebnis in outputStream.

### makeNUp {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-}
Erstellt ein N‑Up‑Dokument aus dem ersten Eingabestream und schreibt es in outputStream.

### makeNUp {#makeNUp-java.lang.String:A-java.lang.String-boolean-}
Erstellt ein N‑Up‑Dokument aus den mehreren Eingabe‑PDF‑Dateien und schreibt es in outputFile.

### makeNUp {#makeNUp-java.lang.String-java.lang.String-int-int-}
Erstellt ein N‑Up‑Dokument aus dem firstInputFile und schreibt es in outputFile.

### makeNUp {#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-}
Erstellt ein N‑Up‑Dokument aus der Eingabedatei und schreibt es in outputFile.

### makeNUp {#makeNUp-java.lang.String-java.lang.String-java.lang.String-}
Erstellt ein N‑Up‑Dokument aus den beiden Eingabe‑PDF‑Dateien und schreibt es in outputFile.

### resizeContents {#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-double-double-}
Ändert die Größe des Inhalts von Dokumentseiten.

### resizeContents {#resizeContents-java.lang.String-java.lang.String-int:A-double-double-}
Ändert die Größe des Inhalts von Dokumentseiten.

### resizeContentsPct {#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-}
Ändert die Größe des Inhalts von Dokumentseiten.

### resizeContentsPct {#resizeContentsPct-java.lang.String-java.lang.String-int:A-double-double-}
Ändert die Größe des Inhalts von Dokumentseiten.

### setAllowConcatenateExceptions {#setAllowConcatenateExceptions-boolean-}
```
void setAllowConcatenateExceptions(boolean value)
```

Wenn auf true gesetzt, werden Ausnahmen ausgelöst, wenn ein Fehler auftritt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setAttachmentName {#setAttachmentName-java.lang.String-}
Legt den Namen des Anhangs fest, wenn das Ergebnis der Operation in HttpServletResponse-Objekten als Anhang gespeichert wird.

### setCloseConcatenatedStreams {#setCloseConcatenatedStreams-boolean-}
```
void setCloseConcatenatedStreams(boolean value)
```

Wenn auf true gesetzt, werden Streams nach der Operation geschlossen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
Legt fest, wie Inhalte gespeichert werden, wenn das Ergebnis der Operation in ein HttpServletResponse‑Objekt gespeichert wird.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Legt das PDF-Dateiformat fest.

### setCorruptedFileAction {#setCorruptedFileAction-int-}
```
void setCorruptedFileAction(int value)
```

Diese Eigenschaft definiert das Verhalten, wenn der Verkettungsprozess auf eine beschädigte Datei trifft.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | ConcatenateCorruptedFileAction Element |

### setIncrementalUpdates {#setIncrementalUpdates-boolean-}
```
void setIncrementalUpdates(boolean value)
```

Wenn true, werden während der Zusammenführung inkrementelle Updates durchgeführt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setKeepFieldsUnique {#setKeepFieldsUnique-boolean-}
```
void setKeepFieldsUnique(boolean value)
```

Wenn true, werden Feldnamen eindeutig gemacht, wenn Formulare zusammengeführt werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setMergeDuplicateLayers {#setMergeDuplicateLayers-boolean-}
```
void setMergeDuplicateLayers(boolean value)
```

Optionale Inhalte von zusammengeführten Dokumenten mit gleichen Namen werden in einem Layer im resultierenden Dokument zusammengeführt, wenn diese Eigenschaft true ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setMergeDuplicateOutlines {#setMergeDuplicateOutlines-boolean-}
```
void setMergeDuplicateOutlines(boolean value)
```

Wenn true, werden doppelte Gliederungen zusammengeführt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setOwnerPassword {#setOwnerPassword-java.lang.String-}
Setzt das Passwort des Eigentümers, wenn die Quell‑Eingabe‑Pdf‑Datei verschlüsselt ist.

### setPreserveUserRights {#setPreserveUserRights-boolean-}
```
void setPreserveUserRights(boolean value)
```

Wenn true, werden die Benutzerrechte des ersten Dokuments auf das zusammengeführte Dokument angewendet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setRemoveSignatures {#setRemoveSignatures-boolean-}
```
void setRemoveSignatures(boolean value)
```

Wenn true, werden alle Signaturen aus den Feldern entfernt (Felder bleiben erhalten); andernfalls können ungültige Signaturen entstehen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Setzt Speicheroptionen, wenn das Ergebnis als HttpServletResponse gespeichert wird.

### setUniqueSuffix {#setUniqueSuffix-java.lang.String-}
Setzt das Format des Suffixes, das dem Feldnamen hinzugefügt wird, um ihn eindeutig zu machen, wenn Formulare zusammengeführt werden.

### splitFromFirst {#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-}
Teilt vom Anfang bis zum angegebenen Ort,und speichert den vorderen Teil im Ausgabe‑Stream.

### splitFromFirst {#splitFromFirst-java.lang.String-int-java.lang.String-}
Teilt die Pdf‑Datei von der ersten Seite bis zum angegebenen Ort,und speichert den vorderen Teil als neue Datei.

### splitToBulks {#splitToBulks-java.io.InputStream-int:A:A-}
Teilt die Pdf‑Datei in mehrere Dokumente. Die Dokumente können einseitig oder mehrseitig sein.

### splitToBulks {#splitToBulks-java.lang.String-int:A:A-}
Teilt die Pdf‑Datei in mehrere Dokumente. Die Dokumente können einseitig oder mehrseitig sein.

### splitToEnd {#splitToEnd-java.io.InputStream-int-java.io.OutputStream-}
Teilt vom angegebenen Ort, und speichert den hinteren Teil als neue Datei‑Stream.

### splitToEnd {#splitToEnd-java.lang.String-int-java.lang.String-}
Teilt vom Ort, und speichert den hinteren Teil als neue Datei.

### splitToPages {#splitToPages-java.io.InputStream-}
Teilt die Pdf‑Datei in einseitige Dokumente.

### splitToPages {#splitToPages-java.io.InputStream-java.lang.String-}
Teilt die Pdf‑Datei in einseitige Dokumente und speichert sie im angegebenen Pfad.

### splitToPages {#splitToPages-java.lang.String-}
Teilt die PDF‑Datei in einseitige Dokumente.

### splitToPages {#splitToPages-java.lang.String-java.lang.String-}
Teilt die Pdf‑Datei in einseitige Dokumente und speichert sie im angegebenen Pfad.
