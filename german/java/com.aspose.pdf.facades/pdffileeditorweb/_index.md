---
title: "PdfFileEditorWeb"
linktitle: "PdfFileEditorWeb"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt die Klasse PdfFileEditorWeb dar, die Operationen mit PDF‑Dateien implementiert: Zusammenführen, Aufteilen, Seiten extrahieren, Heft erstellen usw."
type: docs
weight: 480
url: /de/java/com.aspose.pdf.facades/pdffileeditorweb/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.PdfFileEditorWeb

**All Implemented Interfaces:**
IPdfFileEditor

```
public final class PdfFileEditorWeb extends Object implements IPdfFileEditor
```

Stellt die Klasse PdfFileEditorWeb dar, die Operationen mit PDF‑Dateien implementiert: Zusammenführen, Aufteilen, Seiten extrahieren, Heft erstellen usw.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PdfFileEditorWeb](#PdfFileEditorWeb--) | Konstruktor von PdfFileEditorWeb. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [addMargins](#addMargins-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-) | Ändert die Größe des Seiteninhalts und fügt angegebene Ränder hinzu. |
| [addMargins](#addMargins-java.lang.String-java.lang.String-int:A-double-double-double-double-) | Ändert die Größe des Seiteninhalts und fügt angegebene Ränder hinzu. |
| [addMarginsPct](#addMarginsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-) | Ändert die Größe des Seiteninhalts und fügt angegebene Ränder hinzu. |
| [addMarginsPct](#addMarginsPct-java.lang.String-java.lang.String-int:A-double-double-double-double-) | Ändert die Größe des Seiteninhalts und fügt angegebene Ränder hinzu. |
| [addPageBreak](#addPageBreak-com.aspose.pdf.Document-com.aspose.pdf.Document-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | Fügt Seitenumbrüche in die Dokumentseiten ein. |
| [addPageBreak](#addPageBreak-com.aspose.pdf.IDocument-com.aspose.pdf.IDocument-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | Fügt Seitenumbrüche in die Dokumentseiten ein. |
| [addPageBreak](#addPageBreak-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | Fügt Seitenumbrüche in die Dokumentseiten ein. |
| [addPageBreak](#addPageBreak-java.lang.String-java.lang.String-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | Fügt Seitenumbrüche in die Dokumentseiten ein. |
| [append](#append-java.io.InputStream-java.io.InputStream:A-int-int-javax.servlet.http.HttpServletResponse-) | Fügt Dokumente zum Quelldokument hinzu und speichert das Ergebnis im Antwortobjekt. |
| [append](#append-java.io.InputStream-java.io.InputStream:A-int-int-java.io.OutputStream-) | Fügt Seiten an, die aus einem Array von Dokumenten in portStreams ausgewählt werden. |
| [append](#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-) | Fügt Seiten an, die aus portStream im Bereich von startPage bis endPage ausgewählt werden, in portStream am Ende von firstInputStream. |
| [append](#append-java.lang.String-java.lang.String:A-int-int-javax.servlet.http.HttpServletResponse-) | Fügt Dokumente zum Quelldokument hinzu und speichert das Ergebnis im HttpServletResponse-Objekt. |
| [append](#append-java.lang.String-java.lang.String:A-int-int-java.lang.String-) | Fügt Seiten an, die aus portFiles-Dokumenten ausgewählt werden. |
| [append](#append-java.lang.String-java.lang.String-int-int-java.lang.String-) | Fügt Seiten an, die aus portFile im Bereich von startPage bis endPage ausgewählt werden, in portFile am Ende von firstInputFile. |
| [concatenate](#concatenate-com.aspose.pdf.IDocument:A-com.aspose.pdf.IDocument-) | Verkettet Dokumente. |
| [concatenate](#concatenate-java.io.InputStream:A-javax.servlet.http.HttpServletResponse-) | Verkettet Dateien und speichert das Ergebnis im HttpServletResponse-Objekt. |
| [concatenate](#concatenate-java.io.InputStream:A-java.io.OutputStream-) | Verkettet Dateien |
| [concatenate](#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | Fügt zwei PDF-Dokumente zu einem neuen PDF-Dokument zusammen, wobei die Seiten abwechselnd angeordnet werden, und füllt leere Stellen mit leeren Seiten. |
| [concatenate](#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | Verkettet zwei Dateien. |
| [concatenate](#concatenate-java.lang.String:A-javax.servlet.http.HttpServletResponse-) | Verkettet Dateien und speichert das Ergebnis im HttpResposnse-Objekt. |
| [concatenate](#concatenate-java.lang.String:A-java.lang.String-) | Verkettet Dateien zu einer Datei. |
| [concatenate](#concatenate-java.lang.String-java.lang.String-java.lang.String-) | Verkettet zwei Dateien. |
| [concatenate](#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | Fügt zwei PDF-Dokumente zu einem neuen PDF-Dokument zusammen, wobei die Seiten abwechselnd angeordnet werden, und füllt leere Stellen mit leeren Seiten. |
| [createArrayWithExclusion](#createArrayWithExclusion-int-int-) |  |
| [delete](#delete-java.io.InputStream-int:A-javax.servlet.http.HttpServletResponse-) | Löscht angegebene Seiten aus dem Dokument und speichert das Ergebnis im HttpServletResponse-Objekt. |
| [delete](#delete-java.io.InputStream-int:A-java.io.OutputStream-) | Löscht Seiten, die durch ein Zahlenarray angegeben sind, aus der Eingabedatei und speichert sie als neue PDF-Datei. |
| [delete](#delete-java.lang.String-int:A-javax.servlet.http.HttpServletResponse-) | Löscht angegebene Seiten aus dem Dokument und legt das Ergebnis im HttpServletResponse-Objekt ab. |
| [delete](#delete-java.lang.String-int:A-java.lang.String-) | Löscht Seiten, die durch ein Zahlenarray angegeben sind, aus der Eingabedatei und speichert sie als neue PDF-Datei. |
| [extract](#extract-java.io.InputStream-int:A-javax.servlet.http.HttpServletResponse-) | Extrahiert angegebene Seiten aus der Quelldatei und legt das Ergebnis im HttpServletResponse-Objekt ab. |
| [extract](#extract-java.io.InputStream-int:A-java.io.OutputStream-) | Extrahiert Seiten, die durch ein Zahlenarray angegeben sind, und speichert sie als neue PDF-Datei. |
| [extract](#extract-java.io.InputStream-int-int-java.io.OutputStream-) | Extrahiert Seiten aus der Eingabedatei und speichert sie als neue PDF-Datei. |
| [extract](#extract-java.lang.String-int:A-javax.servlet.http.HttpServletResponse-) | Extrahiert die angegebenen Seiten aus der Quelldatei und speichert das Ergebnis in einem HttpServletResponse-Objekt. |
| [extract](#extract-java.lang.String-int:A-java.lang.String-) | Extrahiert Seiten, die durch ein Zahlenarray angegeben sind, und speichert sie als neue PDF-Datei. |
| [extract](#extract-java.lang.String-int-int-java.lang.String-) | Extrahiert Seiten aus der Eingabedatei und speichert sie als neue PDF-Datei. |
| [getAllowConcatenateExceptions](#getAllowConcatenateExceptions--) | Veraltet. Diese Eigenschaft ist veraltet und kann nicht verwendet werden, um Ausnahmen zu werfen. |
| [getAttachmentName](#getAttachmentName--) | Ermittelt den Namen des Anhangs, wenn das Ergebnis der Operation in HttpServletResponse-Objekten als Anhang gespeichert wird. |
| [getCloseConcatenatedStreams](#getCloseConcatenatedStreams--) | Wenn auf true gesetzt, werden Streams nach der Operation geschlossen. |
| [getConcatenationPacketSize](#getConcatenationPacketSize--) | Anzahl der Dokumente, die zusammengeführt wurden, bevor während der Zusammenführung ein neues inkrementelles Update erstellt wurde, wenn UseDiskBuffer auf true gesetzt ist. |
| [getContentDisposition](#getContentDisposition--) | Ermittelt, wie der Inhalt gespeichert wird, wenn das Ergebnis der Operation in ein HttpServletResponse-Objekt gespeichert wird. |
| [getConversionLog](#getConversionLog--) | Ermittelt das Protokoll des Konvertierungsprozesses. |
| [getCopyLogicalStructure](#getCopyLogicalStructure--) | Wenn true, wird die logische Struktur der Datei bei der Zusammenführung kopiert. |
| [getCopyOutlines](#getCopyOutlines--) | Wenn true, werden Gliederungen kopiert. |
| [getCorruptedFileAction](#getCorruptedFileAction--) | Diese Eigenschaft definiert das Verhalten, wenn der Verkettungsprozess auf eine beschädigte Datei trifft. |
| [getCorruptedItems](#getCorruptedItems--) | Array der aufgetretenen Probleme, die bei der Verkettung aufgetreten sind. |
| [getCustomProgressConcatenationHandler](#getCustomProgressConcatenationHandler--) | Darstellung des internen Prozessors für Fortschrittsereignisse, der während der Zusammenführung arbeitet und Zusammenführungsereignisse interner Zusammenführungsstufen in den Code des externen Kunden übersetzt. |
| [getIncrementalUpdates](#getIncrementalUpdates--) | Wenn true, werden während der Zusammenführung inkrementelle Updates durchgeführt. |
| [getKeepActions](#getKeepActions--) | Wenn true, werden Aktionen aus den Quelldokumenten kopiert. |
| [getKeepFieldsUnique](#getKeepFieldsUnique--) | Wenn true, werden Feldnamen eindeutig gemacht, wenn Formulare zusammengeführt werden. |
| [getLastException](#getLastException--) | Ermittelt die zuletzt aufgetretene Ausnahme. |
| [getMergeDuplicateLayers](#getMergeDuplicateLayers--) | Optionale Inhalte von zusammengeführten Dokumenten mit gleichen Namen werden in einem Layer im resultierenden Dokument zusammengeführt, wenn diese Eigenschaft true ist. |
| [getMergeDuplicateOutlines](#getMergeDuplicateOutlines--) | Wenn true, werden doppelte Gliederungen zusammengeführt. |
| [getOptimizeSize](#getOptimizeSize--) | Liest oder setzt Optimierungs-Flag. |
| [getOwnerPassword](#getOwnerPassword--) | Liefert das Passwort des Eigentümers, wenn die Quell‑Pdf‑Datei verschlüsselt ist. |
| [getPreserveUserRights](#getPreserveUserRights--) | Wenn true, werden die Benutzerrechte des ersten Dokuments auf das zusammengeführte Dokument angewendet. |
| [getRemoveSignatures](#getRemoveSignatures--) | Wenn true, werden alle Signaturen aus den Feldern entfernt (Felder bleiben erhalten); andernfalls können ungültige Signaturen entstehen. |
| [getSaveOptions](#getSaveOptions--) | Liest oder setzt Speicheroptionen, wenn das Ergebnis als HttpServletResponse gespeichert wird. |
| [getUniqueSuffix](#getUniqueSuffix--) | Ermittelt das Format des Suffixes, das dem Feldnamen hinzugefügt wird, um ihn eindeutig zu machen, wenn Formulare zusammengeführt werden. |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int:A-javax.servlet.http.HttpServletResponse-) | Fügt ein Dokument in ein anderes Dokument ein und speichert das Ergebnis in einem Antwortobjekt. |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int:A-java.io.OutputStream-) | Fügt Seiten aus einer anderen Datei in die Eingabe‑Pdf‑Datei ein. |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-) | Fügt Seiten aus einer anderen Datei in die Eingabe‑Pdf‑Datei ein. |
| [insert](#insert-java.lang.String-int-java.lang.String-int:A-javax.servlet.http.HttpServletResponse-) | Fügt den Inhalt einer Datei in die Quelldatei ein und speichert das Ergebnis in einem HttpServletResponse-Objekt. |
| [insert](#insert-java.lang.String-int-java.lang.String-int:A-java.lang.String-) | Fügt Seiten aus einer anderen Datei in die Eingabe‑Pdf‑Datei ein. |
| [insert](#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-) | Fügt Seiten aus einer anderen Datei an einer Position in die Pdf‑Datei ein. |
| [isTryMergeAdjacentSameBackgroundImages](#isTryMergeAdjacentSameBackgroundImages--) | Manchmal enthalten PDFs Hintergrundbilder (von Seiten oder Tabellenzellen), die aus mehreren gleichen Kachel‑Hintergrundbildern bestehen, die nebeneinander platziert sind. |
| [isUseDiskBuffer](#isUseDiskBuffer--) | Wenn diese Option verwendet wird, wird das Zieldokument periodisch auf der Festplatte gespeichert und weitere Zusammenführungen werden als inkrementelle Updates darauf angewendet. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-) | Erstellt ein Heft aus dem InputStream und schreibt es in outputStream. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-int:A-int:A-) | Erstellt ein angepasstes Heft aus dem firstInputStream und schreibt es in outputStream. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-) | Erstellt ein Heft aus dem Eingabestream und speichert das Ergebnis in outputStream. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int:A-int:A-) | Erstellt ein Heft aus dem firstInputStream und schreibt es in outputStream. |
| [makeBooklet](#makeBooklet-java.io.InputStream-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-) | Erstellt ein Heft aus der Quelldatei und speichert das Ergebnis in HttpServletResponse. |
| [makeBooklet](#makeBooklet-java.io.InputStream-com.aspose.pdf.PageSize-int:A-int:A-javax.servlet.http.HttpServletResponse-) | Erstellt ein Heft aus einer PDF-Datei und speichert es in HttpServletResponse. |
| [makeBooklet](#makeBooklet-java.lang.String-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-) | Erstellt ein Heft aus der Quelldatei und speichert das Ergebnis in HttpServletResponse-Objekten. |
| [makeBooklet](#makeBooklet-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-javax.servlet.http.HttpServletResponse-) | Erstellt ein Heft aus der Quelldatei und speichert das Ergebnis in HttpServletResponse-Objekten. |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-) | Erstellt ein Heft aus der Eingabedatei und schreibt es in die Ausgabedatei. |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-int:A-int:A-) | Erstellt ein angepasstes Heft aus dem firstInputFile und schreibt es in outputFile. |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-) | Erstellt ein Heft aus dem inputFile und schreibt es in outputFile. |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-) | Erstellt ein angepasstes Heft aus dem firstInputFile und schreibt es in outputFile. |
| [makeNUp](#makeNUp-java.io.InputStream:A-java.io.OutputStream-boolean-) | Erstellt ein N‑Up‑Dokument aus den mehreren Eingabe‑PDF‑Streams und schreibt es in outputStream. |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | Erstellt ein N‑Up‑Dokument aus den beiden Eingabe‑PDF‑Streams und schreibt es in outputStream. |
| [makeNUp](#makeNUp-java.io.InputStream-int-int-javax.servlet.http.HttpServletResponse-) | Erstellt ein N-up-Dokument und speichert das Ergebnis in HttpServletResponse. |
| [makeNUp](#makeNUp-java.io.InputStream-int-int-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-) | Erstellt ein N-up-Dokument und speichert das Ergebnis in einem HttpServletResponse-Objekt. |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-) | Erstellt ein N‑Up‑Dokument aus dem Eingabestream und speichert das Ergebnis in outputStream. |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-) | Erstellt ein N‑Up‑Dokument aus dem ersten Eingabestream und schreibt es in outputStream. |
| [makeNUp](#makeNUp-java.lang.String:A-java.lang.String-boolean-) | Erstellt ein N‑Up‑Dokument aus den mehreren Eingabe‑PDF‑Dateien und schreibt es in outputFile. |
| [makeNUp](#makeNUp-java.lang.String-int-int-javax.servlet.http.HttpServletResponse-) | Erstellt ein N-up-Dokument und speichert das Ergebnis in HttpServletResponse. |
| [makeNUp](#makeNUp-java.lang.String-int-int-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-) | Erstellt ein N-up-Dokument und speichert das Ergebnis in einem HttpServletResponse-Objekt. |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-int-int-) | Erstellt ein N‑Up‑Dokument aus dem firstInputFile und schreibt es in outputFile. |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-) | Erstellt ein N‑Up‑Dokument aus der Eingabedatei und schreibt es in outputFile. |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-java.lang.String-) | Erstellt ein N‑Up‑Dokument aus den beiden Eingabe‑PDF‑Dateien und schreibt es in outputFile. |
| [resizeContents](#resizeContents-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Ändert die Größe der Dokumentseiten. |
| [resizeContents](#resizeContents-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Ändert die Größe der Dokumentseiten. |
| [resizeContents](#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-double-double-) | Ändert die Größe des Inhalts von Dokumentseiten. |
| [resizeContents](#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Ändert die Größe des Inhalts von Seiten des Dokuments. |
| [resizeContents](#resizeContents-com.aspose.ms.System.IO.Stream-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-javax.servlet.http.HttpServletResponse-) | Ändert die Größe des Inhalts von Seiten im Dokument. |
| [resizeContents](#resizeContents-java.lang.String-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-javax.servlet.http.HttpServletResponse-) | Ändert die Größe des Inhalts von Seiten im Dokument. |
| [resizeContents](#resizeContents-java.lang.String-java.lang.String-int:A-double-double-) | Ändert die Größe des Inhalts von Dokumentseiten. |
| [resizeContents](#resizeContents-java.lang.String-java.lang.String-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Ändert die Größe des Inhalts von Seiten im Dokument. |
| [resizeContentsPct](#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-) | Ändert die Größe des Inhalts von Dokumentseiten. |
| [resizeContentsPct](#resizeContentsPct-java.lang.String-java.lang.String-int:A-double-double-) | Ändert die Größe des Inhalts von Dokumentseiten. |
| [resizeContentsWithNormalization](#resizeContentsWithNormalization-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Ändert die Größe der Dokumentseiten. |
| [resizeContentsWithNormalization](#resizeContentsWithNormalization-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Ändert die Größe der Dokumentseiten. |
| [setAllowConcatenateExceptions](#setAllowConcatenateExceptions-boolean-) | Veraltet. Diese Eigenschaft ist veraltet und kann nicht verwendet werden, um Ausnahmen zu werfen. |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | Legt den Namen des Anhangs fest, wenn das Ergebnis der Operation in HttpServletResponse-Objekten als Anhang gespeichert wird. |
| [setCloseConcatenatedStreams](#setCloseConcatenatedStreams-boolean-) | Wenn auf true gesetzt, werden Streams nach der Operation geschlossen. |
| [setConcatenationPacketSize](#setConcatenationPacketSize-int-) | Anzahl der Dokumente, die zusammengeführt wurden, bevor während der Zusammenführung ein neues inkrementelles Update erstellt wurde, wenn UseDiskBuffer auf true gesetzt ist. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | Legt fest, wie Inhalte gespeichert werden, wenn das Ergebnis der Operation in ein HttpServletResponse‑Objekt gespeichert wird. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | Legt das PDF-Dateiformat fest. |
| [setCopyLogicalStructure](#setCopyLogicalStructure-boolean-) | Wenn true, wird die logische Struktur der Datei bei der Zusammenführung kopiert. |
| [setCopyOutlines](#setCopyOutlines-boolean-) | Wenn true, werden Gliederungen kopiert. |
| [setCorruptedFileAction](#setCorruptedFileAction-int-) | Diese Eigenschaft definiert das Verhalten, wenn der Verkettungsprozess auf eine beschädigte Datei trifft. |
| [setCustomProgressConcatenationHandler](#setCustomProgressConcatenationHandler-com.aspose.pdf.facades.PdfFileEditor.ConcatenationProgressHandler-) | Darstellung des internen Prozessors für Fortschrittsereignisse, der während der Zusammenführung arbeitet und Zusammenführungsereignisse interner Zusammenführungsstufen in den Code des externen Kunden übersetzt. |
| [setIncrementalUpdates](#setIncrementalUpdates-boolean-) | Wenn true, werden während der Zusammenführung inkrementelle Updates durchgeführt. |
| [setKeepActions](#setKeepActions-boolean-) | Wenn true, werden Aktionen aus den Quelldokumenten kopiert. |
| [setKeepFieldsUnique](#setKeepFieldsUnique-boolean-) | Wenn true, werden Feldnamen eindeutig gemacht, wenn Formulare zusammengeführt werden. |
| [setMergeDuplicateLayers](#setMergeDuplicateLayers-boolean-) | Optionale Inhalte von zusammengeführten Dokumenten mit gleichen Namen werden in einem Layer im resultierenden Dokument zusammengeführt, wenn diese Eigenschaft true ist. |
| [setMergeDuplicateOutlines](#setMergeDuplicateOutlines-boolean-) | Wenn true, werden doppelte Gliederungen zusammengeführt. |
| [setOptimizeSize](#setOptimizeSize-boolean-) | Liest oder setzt Optimierungs-Flag. |
| [setOwnerPassword](#setOwnerPassword-java.lang.String-) | Setzt das Passwort des Eigentümers, wenn die Quell‑Eingabe‑Pdf‑Datei verschlüsselt ist. |
| [setPreserveUserRights](#setPreserveUserRights-boolean-) | Wenn true, werden die Benutzerrechte des ersten Dokuments auf das zusammengeführte Dokument angewendet. |
| [setRemoveSignatures](#setRemoveSignatures-boolean-) | Wenn true, werden alle Signaturen aus den Feldern entfernt (Felder bleiben erhalten); andernfalls können ungültige Signaturen entstehen. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Setzt Speicheroptionen, wenn das Ergebnis als HttpServletResponse gespeichert wird. |
| [setTryMergeAdjacentSameBackgroundImages](#setTryMergeAdjacentSameBackgroundImages-boolean-) | Manchmal enthalten PDFs Hintergrundbilder (von Seiten oder Tabellenzellen), die aus mehreren gleichen Kachel‑Hintergrundbildern bestehen, die nebeneinander platziert sind. |
| [setUniqueSuffix](#setUniqueSuffix-java.lang.String-) | Setzt das Format des Suffixes, das dem Feldnamen hinzugefügt wird, um ihn eindeutig zu machen, wenn Formulare zusammengeführt werden. |
| [setUseDiskBuffer](#setUseDiskBuffer-boolean-) | Wenn diese Option verwendet wird, wird das Zieldokument periodisch auf der Festplatte gespeichert und weitere Zusammenführungen werden als inkrementelle Updates darauf angewendet. |
| [splitFromFirst](#splitFromFirst-java.io.InputStream-int-javax.servlet.http.HttpServletResponse-) | Teilt das Dokument vom Anfang bis zum angegebenen Ort und speichert das Ergebnis in einem HttpServletResponse-Objekt. |
| [splitFromFirst](#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-) | Teilt vom Anfang bis zum angegebenen Ort,und speichert den vorderen Teil im Ausgabe‑Stream. |
| [splitFromFirst](#splitFromFirst-java.lang.String-int-javax.servlet.http.HttpServletResponse-) | Teilt das Dokument von der ersten Seite bis zum Ort und speichert das Ergebnis in HttpServletResponse-Objekten. |
| [splitFromFirst](#splitFromFirst-java.lang.String-int-java.lang.String-) | Teilt die Pdf‑Datei von der ersten Seite bis zum angegebenen Ort,und speichert den vorderen Teil als neue Datei. |
| [splitToBulks](#splitToBulks-java.io.InputStream-int:A:A-) | Teilt die Pdf‑Datei in mehrere Dokumente. Die Dokumente können einseitig oder mehrseitig sein. |
| [splitToBulks](#splitToBulks-java.lang.String-int:A:A-) | Teilt die Pdf‑Datei in mehrere Dokumente. Die Dokumente können einseitig oder mehrseitig sein. |
| [splitToEnd](#splitToEnd-java.io.InputStream-int-javax.servlet.http.HttpServletResponse-) | Teilt ab dem angegebenen Ort und speichert den hinteren Teil in einem HttpServletResponse-Objekt. |
| [splitToEnd](#splitToEnd-java.io.InputStream-int-java.io.OutputStream-) | Teilt vom angegebenen Ort, und speichert den hinteren Teil als neue Datei‑Stream. |
| [splitToEnd](#splitToEnd-java.lang.String-int-javax.servlet.http.HttpServletResponse-) | Teilt ab dem angegebenen Ort und speichert den hinteren Teil in einem HttpServletResponse-Objekt. |
| [splitToEnd](#splitToEnd-java.lang.String-int-java.lang.String-) | Teilt vom Ort, und speichert den hinteren Teil als neue Datei. |
| [splitToPages](#splitToPages-java.io.InputStream-) | Teilt die Pdf‑Datei in einseitige Dokumente. |
| [splitToPages](#splitToPages-java.io.InputStream-java.lang.String-) | Teilt die Pdf‑Datei in einseitige Dokumente und speichert sie im angegebenen Pfad. |
| [splitToPages](#splitToPages-java.lang.String-) | Teilt die PDF‑Datei in einseitige Dokumente. |
| [splitToPages](#splitToPages-java.lang.String-java.lang.String-) | Teilt die Pdf‑Datei in einseitige Dokumente und speichert sie im angegebenen Pfad. |

### PdfFileEditorWeb {#PdfFileEditorWeb--}
```
public PdfFileEditorWeb()
```

Konstruktor von PdfFileEditorWeb.

### addMargins {#addMargins-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-}
Ändert die Größe des Seiteninhalts und fügt angegebene Ränder hinzu.

### addMargins {#addMargins-java.lang.String-java.lang.String-int:A-double-double-double-double-}
Ändert die Größe des Seiteninhalts und fügt angegebene Ränder hinzu.

### addMarginsPct {#addMarginsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-}
Ändert die Größe des Seiteninhalts und fügt angegebene Ränder hinzu.

### addMarginsPct {#addMarginsPct-java.lang.String-java.lang.String-int:A-double-double-double-double-}
Ändert die Größe des Seiteninhalts und fügt angegebene Ränder hinzu.

### addPageBreak {#addPageBreak-com.aspose.pdf.Document-com.aspose.pdf.Document-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
Fügt Seitenumbrüche in die Dokumentseiten ein.

### addPageBreak {#addPageBreak-com.aspose.pdf.IDocument-com.aspose.pdf.IDocument-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
Fügt Seitenumbrüche in die Dokumentseiten ein.

### addPageBreak {#addPageBreak-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
Fügt Seitenumbrüche in die Dokumentseiten ein.

### addPageBreak {#addPageBreak-java.lang.String-java.lang.String-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
Fügt Seitenumbrüche in die Dokumentseiten ein.

### append {#append-java.io.InputStream-java.io.InputStream:A-int-int-javax.servlet.http.HttpServletResponse-}
Fügt Dokumente zum Quelldokument hinzu und speichert das Ergebnis im Antwortobjekt.

### append {#append-java.io.InputStream-java.io.InputStream:A-int-int-java.io.OutputStream-}
Fügt Seiten an, die aus einem Array von Dokumenten in portStreams ausgewählt werden.

### append {#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-}
Fügt Seiten an, die aus portStream im Bereich von startPage bis endPage ausgewählt werden, in portStream am Ende von firstInputStream.

### append {#append-java.lang.String-java.lang.String:A-int-int-javax.servlet.http.HttpServletResponse-}
Fügt Dokumente zum Quelldokument hinzu und speichert das Ergebnis im HttpServletResponse-Objekt.

### append {#append-java.lang.String-java.lang.String:A-int-int-java.lang.String-}
Fügt Seiten an, die aus portFiles-Dokumenten ausgewählt werden.

### append {#append-java.lang.String-java.lang.String-int-int-java.lang.String-}
Fügt Seiten an, die aus portFile im Bereich von startPage bis endPage ausgewählt werden, in portFile am Ende von firstInputFile.

### concatenate {#concatenate-com.aspose.pdf.IDocument:A-com.aspose.pdf.IDocument-}
Verkettet Dokumente.

### concatenate {#concatenate-java.io.InputStream:A-javax.servlet.http.HttpServletResponse-}
Verkettet Dateien und speichert das Ergebnis im HttpServletResponse-Objekt.

### concatenate {#concatenate-java.io.InputStream:A-java.io.OutputStream-}
Verkettet Dateien

### concatenate {#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
Fügt zwei PDF-Dokumente zu einem neuen PDF-Dokument zusammen, wobei die Seiten abwechselnd angeordnet werden, und füllt leere Stellen mit leeren Seiten.

### concatenate {#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
Verkettet zwei Dateien.

### concatenate {#concatenate-java.lang.String:A-javax.servlet.http.HttpServletResponse-}
Verkettet Dateien und speichert das Ergebnis im HttpResposnse-Objekt.

### concatenate {#concatenate-java.lang.String:A-java.lang.String-}
Verkettet Dateien zu einer Datei.

### concatenate {#concatenate-java.lang.String-java.lang.String-java.lang.String-}
Verkettet zwei Dateien.

### concatenate {#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
Fügt zwei PDF-Dokumente zu einem neuen PDF-Dokument zusammen, wobei die Seiten abwechselnd angeordnet werden, und füllt leere Stellen mit leeren Seiten.

### createArrayWithExclusion {#createArrayWithExclusion-int-int-}
```
public static Integer [] createArrayWithExclusion(int n, int y)
```



### delete {#delete-java.io.InputStream-int:A-javax.servlet.http.HttpServletResponse-}
Löscht angegebene Seiten aus dem Dokument und speichert das Ergebnis im HttpServletResponse-Objekt.

### delete {#delete-java.io.InputStream-int:A-java.io.OutputStream-}
Löscht Seiten, die durch ein Zahlenarray angegeben sind, aus der Eingabedatei und speichert sie als neue PDF-Datei.

### delete {#delete-java.lang.String-int:A-javax.servlet.http.HttpServletResponse-}
Löscht angegebene Seiten aus dem Dokument und legt das Ergebnis im HttpServletResponse-Objekt ab.

### delete {#delete-java.lang.String-int:A-java.lang.String-}
Löscht Seiten, die durch ein Zahlenarray angegeben sind, aus der Eingabedatei und speichert sie als neue PDF-Datei.

### extract {#extract-java.io.InputStream-int:A-javax.servlet.http.HttpServletResponse-}
Extrahiert angegebene Seiten aus der Quelldatei und legt das Ergebnis im HttpServletResponse-Objekt ab.

### extract {#extract-java.io.InputStream-int:A-java.io.OutputStream-}
Extrahiert Seiten, die durch ein Zahlenarray angegeben sind, und speichert sie als neue PDF-Datei.

### extract {#extract-java.io.InputStream-int-int-java.io.OutputStream-}
Extrahiert Seiten aus der Eingabedatei und speichert sie als neue PDF-Datei.

### extract {#extract-java.lang.String-int:A-javax.servlet.http.HttpServletResponse-}
Extrahiert die angegebenen Seiten aus der Quelldatei und speichert das Ergebnis in einem HttpServletResponse-Objekt.

### extract {#extract-java.lang.String-int:A-java.lang.String-}
Extrahiert Seiten, die durch ein Zahlenarray angegeben sind, und speichert sie als neue PDF-Datei.

### extract {#extract-java.lang.String-int-int-java.lang.String-}
Extrahiert Seiten aus der Eingabedatei und speichert sie als neue PDF-Datei.

### getAllowConcatenateExceptions {#getAllowConcatenateExceptions--}
```
@Deprecated public boolean getAllowConcatenateExceptions()
```

Veraltet. Diese Eigenschaft ist veraltet und kann nicht verwendet werden, um Ausnahmen zu werfen.

**Returns:**
Boolescher Wert

### getAttachmentName {#getAttachmentName--}
```
public String getAttachmentName()
```

Ermittelt den Namen des Anhangs, wenn das Ergebnis der Operation in HttpServletResponse-Objekten als Anhang gespeichert wird.

**Returns:**
String-Wert

### getCloseConcatenatedStreams {#getCloseConcatenatedStreams--}
```
public boolean getCloseConcatenatedStreams()
```

Wenn auf true gesetzt, werden Streams nach der Operation geschlossen.

**Returns:**
boolescher Wert

### getConcatenationPacketSize {#getConcatenationPacketSize--}
```
public final int getConcatenationPacketSize()
```

Anzahl der Dokumente, die zusammengeführt wurden, bevor während der Zusammenführung ein neues inkrementelles Update erstellt wurde, wenn UseDiskBuffer auf true gesetzt ist.

**Returns:**
int-Wert

### getContentDisposition {#getContentDisposition--}
```
public ContentDisposition getContentDisposition()
```

Ermittelt, wie der Inhalt gespeichert wird, wenn das Ergebnis der Operation in ein HttpServletResponse-Objekt gespeichert wird.

**Returns:**
ContentDisposition-Element

### getConversionLog {#getConversionLog--}
```
public String getConversionLog()
```

Ermittelt das Protokoll des Konvertierungsprozesses.

**Returns:**
String-Wert

### getCopyLogicalStructure {#getCopyLogicalStructure--}
```
public boolean getCopyLogicalStructure()
```

Wenn true, wird die logische Struktur der Datei bei der Zusammenführung kopiert.

**Returns:**
boolescher Wert

### getCopyOutlines {#getCopyOutlines--}
```
public boolean getCopyOutlines()
```

Wenn true, werden Gliederungen kopiert.

**Returns:**
boolescher Wert

### getCorruptedFileAction {#getCorruptedFileAction--}
```
public int getCorruptedFileAction()
```

Diese Eigenschaft definiert das Verhalten, wenn der Verkettungsprozess auf eine beschädigte Datei trifft.

**Returns:**
ConcatenateCorruptedFileAction Element

### getCorruptedItems {#getCorruptedItems--}
```
public PdfFileEditor.CorruptedItem [] getCorruptedItems()
```

Array der aufgetretenen Probleme, die bei der Verkettung aufgetreten sind.

**Returns:**
PdfFileEditor.CorruptedItem-Array

### getCustomProgressConcatenationHandler {#getCustomProgressConcatenationHandler--}
```
public PdfFileEditor.ConcatenationProgressHandler getCustomProgressConcatenationHandler()
```

Darstellung des internen Prozessors für Fortschrittsereignisse, der während der Zusammenführung arbeitet und Zusammenführungsereignisse interner Zusammenführungsstufen in den Code des externen Kunden übersetzt.

**Returns:**
Instanz von ConcatenationProgressHandler

### getIncrementalUpdates {#getIncrementalUpdates--}
```
public boolean getIncrementalUpdates()
```

Wenn true, werden während der Zusammenführung inkrementelle Updates durchgeführt.

**Returns:**
boolescher Wert

### getKeepActions {#getKeepActions--}
```
public final boolean getKeepActions()
```

Wenn true, werden Aktionen aus den Quelldokumenten kopiert.

**Returns:**
boolescher Wert

### getKeepFieldsUnique {#getKeepFieldsUnique--}
```
public boolean getKeepFieldsUnique()
```

Wenn true, werden Feldnamen eindeutig gemacht, wenn Formulare zusammengeführt werden.

**Returns:**
boolescher Wert

### getLastException {#getLastException--}
```
public final RuntimeException getLastException()
```

Ermittelt die zuletzt aufgetretene Ausnahme.

**Returns:**
java.lang.Exception-Objekt

### getMergeDuplicateLayers {#getMergeDuplicateLayers--}
```
public boolean getMergeDuplicateLayers()
```

Optionale Inhalte von zusammengeführten Dokumenten mit gleichen Namen werden in einem Layer im resultierenden Dokument zusammengeführt, wenn diese Eigenschaft true ist.

**Returns:**
boolescher Wert

### getMergeDuplicateOutlines {#getMergeDuplicateOutlines--}
```
public boolean getMergeDuplicateOutlines()
```

Wenn true, werden doppelte Gliederungen zusammengeführt.

**Returns:**
boolescher Wert

### getOptimizeSize {#getOptimizeSize--}
```
public boolean getOptimizeSize()
```

Liest oder setzt Optimierungs-Flag.

**Returns:**
boolescher Wert

### getOwnerPassword {#getOwnerPassword--}
```
public String getOwnerPassword()
```

Liefert das Passwort des Eigentümers, wenn die Quell‑Pdf‑Datei verschlüsselt ist.

**Returns:**
String-Objekt

### getPreserveUserRights {#getPreserveUserRights--}
```
public boolean getPreserveUserRights()
```

Wenn true, werden die Benutzerrechte des ersten Dokuments auf das zusammengeführte Dokument angewendet.

**Returns:**
boolescher Wert

### getRemoveSignatures {#getRemoveSignatures--}
```
public boolean getRemoveSignatures()
```

Wenn true, werden alle Signaturen aus den Feldern entfernt (Felder bleiben erhalten); andernfalls können ungültige Signaturen entstehen.

**Returns:**
boolescher Wert

### getSaveOptions {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```

Liest oder setzt Speicheroptionen, wenn das Ergebnis als HttpServletResponse gespeichert wird.

**Returns:**
SaveOptions-Objekt

### getUniqueSuffix {#getUniqueSuffix--}
```
public String getUniqueSuffix()
```

Ermittelt das Format des Suffixes, das dem Feldnamen hinzugefügt wird, um ihn eindeutig zu machen, wenn Formulare zusammengeführt werden.

**Returns:**
String-Objekt

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int:A-javax.servlet.http.HttpServletResponse-}
Fügt ein Dokument in ein anderes Dokument ein und speichert das Ergebnis in einem Antwortobjekt.

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int:A-java.io.OutputStream-}
Fügt Seiten aus einer anderen Datei in die Eingabe‑Pdf‑Datei ein.

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-}
Fügt Seiten aus einer anderen Datei in die Eingabe‑Pdf‑Datei ein.

### insert {#insert-java.lang.String-int-java.lang.String-int:A-javax.servlet.http.HttpServletResponse-}
Fügt den Inhalt einer Datei in die Quelldatei ein und speichert das Ergebnis in einem HttpServletResponse-Objekt.

### insert {#insert-java.lang.String-int-java.lang.String-int:A-java.lang.String-}
Fügt Seiten aus einer anderen Datei in die Eingabe‑Pdf‑Datei ein.

### insert {#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-}
Fügt Seiten aus einer anderen Datei an einer Position in die Pdf‑Datei ein.

### isTryMergeAdjacentSameBackgroundImages {#isTryMergeAdjacentSameBackgroundImages--}
```
public boolean isTryMergeAdjacentSameBackgroundImages()
```

Manchmal enthalten PDFs Hintergrundbilder (von Seiten oder Tabellenzellen), die aus mehreren gleichen Kachel‑Hintergrundbildern bestehen, die nebeneinander platziert sind.

**Returns:**
boolescher Wert

### isUseDiskBuffer {#isUseDiskBuffer--}
```
public final boolean isUseDiskBuffer()
```

Wenn diese Option verwendet wird, wird das Zieldokument periodisch auf der Festplatte gespeichert und weitere Zusammenführungen werden als inkrementelle Updates darauf angewendet.

**Returns:**
boolescher Wert

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-}
Erstellt ein Heft aus dem InputStream und schreibt es in outputStream.

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-int:A-int:A-}
Erstellt ein angepasstes Heft aus dem firstInputStream und schreibt es in outputStream.

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-}
Erstellt ein Heft aus dem Eingabestream und speichert das Ergebnis in outputStream.

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int:A-int:A-}
Erstellt ein Heft aus dem firstInputStream und schreibt es in outputStream.

### makeBooklet {#makeBooklet-java.io.InputStream-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-}
Erstellt ein Heft aus der Quelldatei und speichert das Ergebnis in HttpServletResponse.

### makeBooklet {#makeBooklet-java.io.InputStream-com.aspose.pdf.PageSize-int:A-int:A-javax.servlet.http.HttpServletResponse-}
Erstellt ein Heft aus einer PDF-Datei und speichert es in HttpServletResponse.

### makeBooklet {#makeBooklet-java.lang.String-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-}
Erstellt ein Heft aus der Quelldatei und speichert das Ergebnis in HttpServletResponse-Objekten.

### makeBooklet {#makeBooklet-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-javax.servlet.http.HttpServletResponse-}
Erstellt ein Heft aus der Quelldatei und speichert das Ergebnis in HttpServletResponse-Objekten.

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

### makeNUp {#makeNUp-java.io.InputStream-int-int-javax.servlet.http.HttpServletResponse-}
Erstellt ein N-up-Dokument und speichert das Ergebnis in HttpServletResponse.

### makeNUp {#makeNUp-java.io.InputStream-int-int-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-}
Erstellt ein N-up-Dokument und speichert das Ergebnis in einem HttpServletResponse-Objekt.

### makeNUp {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-}
Erstellt ein N‑Up‑Dokument aus dem Eingabestream und speichert das Ergebnis in outputStream.

### makeNUp {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-}
Erstellt ein N‑Up‑Dokument aus dem ersten Eingabestream und schreibt es in outputStream.

### makeNUp {#makeNUp-java.lang.String:A-java.lang.String-boolean-}
Erstellt ein N‑Up‑Dokument aus den mehreren Eingabe‑PDF‑Dateien und schreibt es in outputFile.

### makeNUp {#makeNUp-java.lang.String-int-int-javax.servlet.http.HttpServletResponse-}
Erstellt ein N-up-Dokument und speichert das Ergebnis in HttpServletResponse.

### makeNUp {#makeNUp-java.lang.String-int-int-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-}
Erstellt ein N-up-Dokument und speichert das Ergebnis in einem HttpServletResponse-Objekt.

### makeNUp {#makeNUp-java.lang.String-java.lang.String-int-int-}
Erstellt ein N‑Up‑Dokument aus dem firstInputFile und schreibt es in outputFile.

### makeNUp {#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-}
Erstellt ein N‑Up‑Dokument aus der Eingabedatei und schreibt es in outputFile.

### makeNUp {#makeNUp-java.lang.String-java.lang.String-java.lang.String-}
Erstellt ein N‑Up‑Dokument aus den beiden Eingabe‑PDF‑Dateien und schreibt es in outputFile.

### resizeContents {#resizeContents-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Ändert die Größe der Dokumentseiten.

### resizeContents {#resizeContents-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Ändert die Größe der Dokumentseiten.

### resizeContents {#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-double-double-}
Ändert die Größe des Inhalts von Dokumentseiten.

### resizeContents {#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Ändert die Größe des Inhalts von Seiten des Dokuments.

### resizeContents {#resizeContents-com.aspose.ms.System.IO.Stream-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-javax.servlet.http.HttpServletResponse-}
Ändert die Größe des Inhalts von Seiten im Dokument.

### resizeContents {#resizeContents-java.lang.String-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-javax.servlet.http.HttpServletResponse-}
Ändert die Größe des Inhalts von Seiten im Dokument.

### resizeContents {#resizeContents-java.lang.String-java.lang.String-int:A-double-double-}
Ändert die Größe des Inhalts von Dokumentseiten.

### resizeContents {#resizeContents-java.lang.String-java.lang.String-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Ändert die Größe des Inhalts von Seiten im Dokument.

### resizeContentsPct {#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-}
Ändert die Größe des Inhalts von Dokumentseiten.

### resizeContentsPct {#resizeContentsPct-java.lang.String-java.lang.String-int:A-double-double-}
Ändert die Größe des Inhalts von Dokumentseiten.

### resizeContentsWithNormalization {#resizeContentsWithNormalization-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Ändert die Größe der Dokumentseiten.

### resizeContentsWithNormalization {#resizeContentsWithNormalization-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Ändert die Größe der Dokumentseiten.

### setAllowConcatenateExceptions {#setAllowConcatenateExceptions-boolean-}
```
@Deprecated public void setAllowConcatenateExceptions(boolean value)
```

Veraltet. Diese Eigenschaft ist veraltet und kann nicht verwendet werden, um Ausnahmen zu werfen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | Boolescher Wert |

### setAttachmentName {#setAttachmentName-java.lang.String-}
Legt den Namen des Anhangs fest, wenn das Ergebnis der Operation in HttpServletResponse-Objekten als Anhang gespeichert wird.

### setCloseConcatenatedStreams {#setCloseConcatenatedStreams-boolean-}
```
public void setCloseConcatenatedStreams(boolean value)
```

Wenn auf true gesetzt, werden Streams nach der Operation geschlossen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setConcatenationPacketSize {#setConcatenationPacketSize-int-}
```
public final void setConcatenationPacketSize(int value)
```

Anzahl der Dokumente, die zusammengeführt wurden, bevor während der Zusammenführung ein neues inkrementelles Update erstellt wurde, wenn UseDiskBuffer auf true gesetzt ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
Legt fest, wie Inhalte gespeichert werden, wenn das Ergebnis der Operation in ein HttpServletResponse‑Objekt gespeichert wird.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Legt das PDF-Dateiformat fest.

### setCopyLogicalStructure {#setCopyLogicalStructure-boolean-}
```
public void setCopyLogicalStructure(boolean value)
```

Wenn true, wird die logische Struktur der Datei bei der Zusammenführung kopiert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setCopyOutlines {#setCopyOutlines-boolean-}
```
public void setCopyOutlines(boolean value)
```

Wenn true, werden Gliederungen kopiert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setCorruptedFileAction {#setCorruptedFileAction-int-}
```
public void setCorruptedFileAction(int value)
```

Diese Eigenschaft definiert das Verhalten, wenn der Verkettungsprozess auf eine beschädigte Datei trifft.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | ConcatenateCorruptedFileAction Element |

### setCustomProgressConcatenationHandler {#setCustomProgressConcatenationHandler-com.aspose.pdf.facades.PdfFileEditor.ConcatenationProgressHandler-}
Darstellung des internen Prozessors für Fortschrittsereignisse, der während der Zusammenführung arbeitet und Zusammenführungsereignisse interner Zusammenführungsstufen in den Code des externen Kunden übersetzt.

### setIncrementalUpdates {#setIncrementalUpdates-boolean-}
```
public void setIncrementalUpdates(boolean value)
```

Wenn true, werden während der Zusammenführung inkrementelle Updates durchgeführt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setKeepActions {#setKeepActions-boolean-}
```
public final void setKeepActions(boolean value)
```

Wenn true, werden Aktionen aus den Quelldokumenten kopiert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setKeepFieldsUnique {#setKeepFieldsUnique-boolean-}
```
public void setKeepFieldsUnique(boolean value)
```

Wenn true, werden Feldnamen eindeutig gemacht, wenn Formulare zusammengeführt werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setMergeDuplicateLayers {#setMergeDuplicateLayers-boolean-}
```
public void setMergeDuplicateLayers(boolean value)
```

Optionale Inhalte von zusammengeführten Dokumenten mit gleichen Namen werden in einem Layer im resultierenden Dokument zusammengeführt, wenn diese Eigenschaft true ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setMergeDuplicateOutlines {#setMergeDuplicateOutlines-boolean-}
```
public void setMergeDuplicateOutlines(boolean value)
```

Wenn true, werden doppelte Gliederungen zusammengeführt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setOptimizeSize {#setOptimizeSize-boolean-}
```
public void setOptimizeSize(boolean value)
```

Liest oder setzt Optimierungs-Flag.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setOwnerPassword {#setOwnerPassword-java.lang.String-}
Setzt das Passwort des Eigentümers, wenn die Quell‑Eingabe‑Pdf‑Datei verschlüsselt ist.

### setPreserveUserRights {#setPreserveUserRights-boolean-}
```
public void setPreserveUserRights(boolean value)
```

Wenn true, werden die Benutzerrechte des ersten Dokuments auf das zusammengeführte Dokument angewendet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setRemoveSignatures {#setRemoveSignatures-boolean-}
```
public void setRemoveSignatures(boolean value)
```

Wenn true, werden alle Signaturen aus den Feldern entfernt (Felder bleiben erhalten); andernfalls können ungültige Signaturen entstehen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Setzt Speicheroptionen, wenn das Ergebnis als HttpServletResponse gespeichert wird.

### setTryMergeAdjacentSameBackgroundImages {#setTryMergeAdjacentSameBackgroundImages-boolean-}
```
public void setTryMergeAdjacentSameBackgroundImages(boolean tryMergeAdjacentSameBackgroundImages)
```

Manchmal enthalten PDFs Hintergrundbilder (von Seiten oder Tabellenzellen), die aus mehreren gleichen Kachel‑Hintergrundbildern bestehen, die nebeneinander platziert sind.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| tryMergeAdjacentSameBackgroundImages |  | boolescher Wert |

### setUniqueSuffix {#setUniqueSuffix-java.lang.String-}
Setzt das Format des Suffixes, das dem Feldnamen hinzugefügt wird, um ihn eindeutig zu machen, wenn Formulare zusammengeführt werden.

### setUseDiskBuffer {#setUseDiskBuffer-boolean-}
```
public final void setUseDiskBuffer(boolean value)
```

Wenn diese Option verwendet wird, wird das Zieldokument periodisch auf der Festplatte gespeichert und weitere Zusammenführungen werden als inkrementelle Updates darauf angewendet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### splitFromFirst {#splitFromFirst-java.io.InputStream-int-javax.servlet.http.HttpServletResponse-}
Teilt das Dokument vom Anfang bis zum angegebenen Ort und speichert das Ergebnis in einem HttpServletResponse-Objekt.

### splitFromFirst {#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-}
Teilt vom Anfang bis zum angegebenen Ort,und speichert den vorderen Teil im Ausgabe‑Stream.

### splitFromFirst {#splitFromFirst-java.lang.String-int-javax.servlet.http.HttpServletResponse-}
Teilt das Dokument von der ersten Seite bis zum Ort und speichert das Ergebnis in HttpServletResponse-Objekten.

### splitFromFirst {#splitFromFirst-java.lang.String-int-java.lang.String-}
Teilt die Pdf‑Datei von der ersten Seite bis zum angegebenen Ort,und speichert den vorderen Teil als neue Datei.

### splitToBulks {#splitToBulks-java.io.InputStream-int:A:A-}
Teilt die Pdf‑Datei in mehrere Dokumente. Die Dokumente können einseitig oder mehrseitig sein.

### splitToBulks {#splitToBulks-java.lang.String-int:A:A-}
Teilt die Pdf‑Datei in mehrere Dokumente. Die Dokumente können einseitig oder mehrseitig sein.

### splitToEnd {#splitToEnd-java.io.InputStream-int-javax.servlet.http.HttpServletResponse-}
Teilt ab dem angegebenen Ort und speichert den hinteren Teil in einem HttpServletResponse-Objekt.

### splitToEnd {#splitToEnd-java.io.InputStream-int-java.io.OutputStream-}
Teilt vom angegebenen Ort, und speichert den hinteren Teil als neue Datei‑Stream.

### splitToEnd {#splitToEnd-java.lang.String-int-javax.servlet.http.HttpServletResponse-}
Teilt ab dem angegebenen Ort und speichert den hinteren Teil in einem HttpServletResponse-Objekt.

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
