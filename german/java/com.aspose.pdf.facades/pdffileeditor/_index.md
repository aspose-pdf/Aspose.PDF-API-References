---
title: "PdfFileEditor"
linktitle: "PdfFileEditor"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Implementiert Operationen mit PDF-Dateien: Zusammenführen, Aufteilen, Extrahieren von Seiten, Erstellen eines Booklets usw."
type: docs
weight: 410
url: /de/java/com.aspose.pdf.facades/pdffileeditor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.PdfFileEditor

**All Implemented Interfaces:**
IPdfFileEditor

```
public final class PdfFileEditor extends Object implements IPdfFileEditor
```

Implementiert Operationen mit PDF-Dateien: Zusammenführen, Aufteilen, Extrahieren von Seiten, Erstellen eines Booklets usw.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PdfFileEditor](#PdfFileEditor--) | PdfFileEditor Konstruktor. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [addMargins](#addMargins-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-) | <p> Ändert die Größe des Seiteninhalts und fügt angegebene Ränder hinzu. Die Ränder werden in Standardabstandseinheiten angegeben. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InmputStream src = new FileInputStream("input.pdf"); OutputStream dest = new FileInputStream("output.pdf"); fileEditor.addMargins(src, dest, //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 10 units 10, //right margin is 5 units 5, //top margin is 5 units 5, //bottom margin is 5 units 5); dest.Close(); </pre> |
| [addMargins](#addMargins-java.lang.String-java.lang.String-int:A-double-double-double-double-) | <p> Ändert die Größe des Seiteninhalts und fügt angegebene Ränder hinzu. Die Ränder werden in Standardabstandseinheiten angegeben. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.addMargins("input.pdf", "output.pdf", //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 10 units 10, //right margin is 5 units 5, //top margin is 5 units 5, //bottom margin is 5 units 5); </pre> |
| [addMarginsPct](#addMarginsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-) | <p> Ändert die Größe des Seiteninhalts und fügt angegebene Ränder hinzu. Die Ränder werden in Prozent der ursprünglichen Seitengröße angegeben. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InmputStream src = new FileInputStream("input.pdf"); OutputStream dest = new FileInputStream("output.pdf"); fileEditor.addMarginsPct(src, dest, //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 15% of page width 15, //right margin is 10% of page width 10, //top margin is 20% of page width 20, //bottom margin is 5% of page width 5); dest.close(); </pre> |
| [addMarginsPct](#addMarginsPct-java.lang.String-java.lang.String-int:A-double-double-double-double-) | <p> Ändert die Größe des Seiteninhalts und fügt die angegebenen Ränder hinzu. Die Ränder werden in Prozent der ursprünglichen Seitengröße angegeben. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.addMarginsPct("input.pdf", "output.pdf", //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 15% of page width 15, //right margin is 10% of page width 10, //top margin is 20% of page width 20, //bottom margin is 5% of page width 5); </pre> |
| [addPageBreak](#addPageBreak-com.aspose.pdf.Document-com.aspose.pdf.Document-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | Fügt Seitenumbrüche in die Dokumentseiten ein. |
| [addPageBreak](#addPageBreak-com.aspose.pdf.IDocument-com.aspose.pdf.IDocument-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | Fügt Seitenumbrüche in die Dokumentseiten ein. |
| [addPageBreak](#addPageBreak-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | Fügt Seitenumbrüche in die Dokumentseiten ein. |
| [addPageBreak](#addPageBreak-java.lang.String-java.lang.String-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | Fügt Seitenumbrüche in die Dokumentseiten ein. |
| [append](#append-java.io.InputStream-java.io.InputStream:A-int-int-java.io.OutputStream-) | <p> Fügt Seiten an, die aus einem Array von Dokumenten in portStreams ausgewählt werden. Das Ergebnisdokument enthält firstInputFile und alle Seiten der portStreams-Dokumente im Bereich startPage bis endPage. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream instream = new FileInputStream("input.pdf"); InputStream stream1 = new FileInputStream("file1.pdf"); InputStream stream2 = new FileInputStream("file2.pdf"); OtputStream outstream = new FileOutputStream("outfile.pdf"); fileEditor.append(instream, new InputStream[] { stream1, stream2}, 3, 5, outstream); </pre> |
| [append](#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-) | <p> Fügt Seiten an, die aus portStream im Bereich von startPage bis endPage ausgewählt werden, in portStream am Ende von firstInputStream. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream instream = new FileInputStream("input.pdf"); InputStream stream1 = new FileInputStream("file1.pdf"); OutputStream outstream = new FileOutputStream("outfile.pdf"); fileEditor.append(instream, stream1, 3, 5, outstream); </pre> |
| [append](#append-java.lang.String-java.lang.String:A-int-int-java.lang.String-) | <p> Fügt Seiten an, die aus den portFiles-Dokumenten ausgewählt werden. Das Ergebnisdokument enthält firstInputFile und alle Seiten der portFiles-Dokumente im Bereich startPage bis endPage. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.append("input.pdf", new string[] { "file1.pdf", "file2.pdf"}, 3, 5, "outfile.pdf"); </pre> |
| [append](#append-java.lang.String-java.lang.String-int-int-java.lang.String-) | <p> Fügt Seiten an, die aus portFile im Bereich von startPage bis endPage ausgewählt werden, in portFile am Ende von firstInputFile. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.append("input.pdf", "file1.pdf", 3, 5, "outfile.pdf"); </pre> |
| [concatenate](#concatenate-com.aspose.pdf.IDocument:A-com.aspose.pdf.IDocument-) | Verkettet Dokumente. |
| [concatenate](#concatenate-java.io.InputStream:A-java.io.OutputStream-) | <p> Verkettet Dateien </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream stream1 = new FileInputStream("file1.pdf"); InputStream stream2 = new FileInputStream("file2.pdf"); OutputStream outstream = new FileOutputStream("outfile.pdf"); fileEditor.concatenate(new Stream[] { stream1, stream2 } , outstream); </pre> |
| [concatenate](#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | <p> Fügt zwei Pdf-Dokumente zu einem neuen Pdf-Dokument zusammen, wobei die Seiten abwechselnd angeordnet werden, und füllt die leeren Stellen mit leeren Seiten. z.B.: document1 hat 5 Seiten: p1, p2, p3, p4, p5. document2 hat 3 Seiten: p1', p2', p3'. Das Zusammenführen der beiden Pdf-Dokumente erzeugt das Ergebnisdokument mit den Seiten: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream stream1 = new FileInputStream(\"file1.pdf\"); InputStream stream2 = new FileInputStream(\"file2.pdf\"); InputStream blank = new FileInputStream(\"blank.pdf\"); OutputStream outstream = new FileOutputStream(\"outfile.pdf\"); fileEditor.concatenate(new Stream[] { stream1, stream2, blank } , outstream); </pre> |
| [concatenate](#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | <p> Verkettet zwei Dateien. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream stream1 = new FileInputStream(\"file1.pdf\"); InputStream stream2 = new FileInputStream(\"file2.pdf\"); OutputStream outstream = new FileOutputStream(\"outfile.pdf\"); fileEditor.concatenate(stream1, stream2, outstream); </pre> |
| [concatenate](#concatenate-java.lang.String:A-java.lang.String-) | <p> Verkettet Dateien zu einer Datei. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.concatenate(new String[] { \"src1.pdf\", \"src2.pdf\" }, \"dest.pdf\"); </pre> |
| [concatenate](#concatenate-java.lang.String-java.lang.String-java.lang.String-) | <p> Verkettet zwei Dateien. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.concatenate(\"file1.pdf\", \"file2.pdf\", \"outfile.pdf\"); </pre> |
| [concatenate](#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | <p> Fügt zwei Pdf-Dokumente zu einem neuen Pdf-Dokument zusammen, wobei die Seiten abwechselnd angeordnet werden, und füllt die leeren Stellen mit leeren Seiten. z.B.: document1 hat 5 Seiten: p1, p2, p3, p4, p5. document2 hat 3 Seiten: p1', p2', p3'. Das Zusammenführen der beiden Pdf-Dokumente erzeugt das Ergebnisdokument mit den Seiten: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.concatenate(\"src1.pdf\", \"src2.pdf\", \"blank.pdf\", \"dest.pdf\"); </pre> |
| [createArrayWithExclusion](#createArrayWithExclusion-int-int-) |  |
| [delete](#delete-java.io.InputStream-int:A-java.io.OutputStream-) | <p> Löscht Seiten, die durch ein Zahlenarray angegeben sind, aus der Eingabedatei und speichert sie als neue Pdf-Datei. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream intputStream = new FileInputStream(\"input.pdf\"); OutputStream outputStream = new FileInputStream(\"output.pdf\"); pfe.Delete(inputStream, new int[] { 2, 3 }, outputStream); </pre> |
| [delete](#delete-java.lang.String-int:A-java.lang.String-) | <p> Löscht Seiten, die durch ein Zahlenarray angegeben sind, aus der Eingabedatei und speichert sie als neue Pdf-Datei. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.delete(\"input.pdf\", new int[] { 2, 3 }, \"out.pdf\"); </pre> |
| [extract](#extract-java.io.InputStream-int:A-java.io.OutputStream-) | <p> Extrahiert Seiten, die durch ein Zahlenarray angegeben sind, und speichert sie als neue Pdf-Datei. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream(\"file1.pdf\"); OutputStream outStream = new FileInputStream(\"out.pdf\"); pfe.extract(sourceStream, new int[] { 3, 5, 8 }, outStream); </pre> |
| [extract](#extract-java.io.InputStream-int-int-java.io.OutputStream-) | <p> Extrahiert Seiten aus der Eingabedatei und speichert sie als neue Pdf-Datei. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream(\"file1.pdf\"); OutputStream outStream = new FileOutputStream(\"out.pdf\"); pfe.extract(sourceStream, 1, 3, 6, outStream); </pre> |
| [extract](#extract-java.lang.String-int:A-java.lang.String-) | <p> Extrahiert Seiten, die durch ein Zahlenarray angegeben sind, und speichert sie als neue PDF-Datei. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.extract("input.pdf", new int[] { 3, 5, 7 }, "output.pdf"); </pre> |
| [extract](#extract-java.lang.String-int-int-java.lang.String-) | <p> Extrahiert Seiten aus der Eingabedatei und speichert sie als neue PDF-Datei. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.Extract("input.pdf", 3, 7, "output.pdf"); </pre> |
| [getAllowConcatenateExceptions](#getAllowConcatenateExceptions--) | <p> Wenn auf true gesetzt, werden Ausnahmen ausgelöst, wenn ein Fehler auftritt. Andernfalls werden keine Ausnahmen ausgelöst und die Methoden geben false zurück, wenn sie fehlschlagen. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.setAllowConcatenatedException (true); </pre> |
| [getAttachmentName](#getAttachmentName--) | Ermittelt den Namen des Anhangs, wenn das Ergebnis der Operation in HttpServletResponse-Objekten als Anhang gespeichert wird. |
| [getCloseConcatenatedStreams](#getCloseConcatenatedStreams--) | Wenn auf true gesetzt, werden Streams nach der Operation geschlossen. |
| [getConcatenationPacketSize](#getConcatenationPacketSize--) | Anzahl der Dokumente, die zusammengeführt wurden, bevor während der Zusammenführung ein neues inkrementelles Update erstellt wurde, wenn UseDiskBuffer auf true gesetzt ist. |
| [getContentDisposition](#getContentDisposition--) | Ermittelt, wie der Inhalt gespeichert wird, wenn das Ergebnis der Operation in ein HttpServletResponse-Objekt gespeichert wird. Mögliche Werte: inline / attachment. Standard: inline. |
| [getConversionLog](#getConversionLog--) | Ermittelt das Protokoll des Konvertierungsprozesses. |
| [getCopyLogicalStructure](#getCopyLogicalStructure--) | Wenn true, wird die logische Struktur der Datei bei der Zusammenführung kopiert. |
| [getCopyOutlines](#getCopyOutlines--) | Wenn true, werden Gliederungen kopiert. |
| [getCorruptedFileAction](#getCorruptedFileAction--) | Diese Eigenschaft definiert das Verhalten, wenn der Zusammenführungsprozess auf eine beschädigte Datei trifft. Mögliche Werte sind: StopWithError und ConcatenateIgnoringCorrupted. |
| [getCorruptedItems](#getCorruptedItems--) | <p> Array von aufgetretenen Problemen, wenn die Zusammenführung durchgeführt wurde. Für jedes beschädigte Dokument, das an die Funktion Concatenate() übergeben wird, wird ein neuer CorruptedItem-Eintrag erstellt. Diese Eigenschaft darf nur verwendet werden, wenn CorruptedFileAction auf ConcatenateIgnoringCorrupted gesetzt ist. </p> <hr> <pre> //concatenate documents and show information about corrupted documents PdfFileEditor pfe = new PdfFileEditor(); pfe.setCorruptedFileAction(PdfFileEditor.ConcatenateCorruptedFileAction.ConcatenateIgnoringCorrupted); {@code if (pfe.getCorruptedItems().length >0)} { for(PdfFileEditor.CorruptedItem item : pfe.getCorruptedItems()) { System.out.println(item.getIndex()+ " reason: " + item.getException()); } } </pre> |
| [getCustomProgressConcatenationHandler](#getCustomProgressConcatenationHandler--) | Darstellung des internen Prozessors für Fortschrittsereignisse, der während der Zusammenführung arbeitet und Zusammenführungsereignisse interner Zusammenführungsstufen in den Code des externen Kunden übersetzt. |
| [getIncrementalUpdates](#getIncrementalUpdates--) | Wenn true, werden während der Zusammenführung inkrementelle Updates durchgeführt. |
| [getKeepActions](#getKeepActions--) | Wenn true, werden Aktionen aus den Quelldokumenten kopiert. |
| [getKeepFieldsUnique](#getKeepFieldsUnique--) | Wenn true, werden Feldnamen beim Zusammenführen von Formularen eindeutig gemacht. Suffixe werden zu den Feldnamen hinzugefügt, das Suffix-Template kann in der Eigenschaft UniqueSuffix angegeben werden. |
| [getLastException](#getLastException--) | Ermittelt die zuletzt aufgetretene Ausnahme. |
| [getMergeDuplicateLayers](#getMergeDuplicateLayers--) | Optionale Inhalte von zusammengeführten Dokumenten mit gleichen Namen werden in einem Layer im resultierenden Dokument zusammengeführt, wenn diese Eigenschaft true ist. |
| [getMergeDuplicateOutlines](#getMergeDuplicateOutlines--) | Wenn true, werden doppelte Gliederungen zusammengeführt. |
| [getOptimizeSize](#getOptimizeSize--) | Liest oder setzt Optimierungs-Flag. |
| [getOwnerPassword](#getOwnerPassword--) | Ermittelt das Passwort des Eigentümers, wenn die Quell-PDF-Datei verschlüsselt ist. Diese Eigenschaft ist noch nicht implementiert. |
| [getPreserveUserRights](#getPreserveUserRights--) | Wenn true, werden die Benutzerrechte des ersten Dokuments auf das zusammengeführte Dokument angewendet. |
| [getRemoveSignatures](#getRemoveSignatures--) | Wenn true, werden alle Signaturen aus den Feldern entfernt (Felder bleiben erhalten); andernfalls können ungültige Signaturen entstehen. |
| [getSaveOptions](#getSaveOptions--) | Liest oder setzt Speicheroptionen, wenn das Ergebnis als HttpServletResponse gespeichert wird. Standardwert: PdfSaveOptions. |
| [getUniqueSuffix](#getUniqueSuffix--) | Erhalte das Format des Suffixes, das dem Feldnamen hinzugefügt wird, um ihn eindeutig zu machen, wenn Formulare zusammengeführt werden. Dieser String muss die Teilzeichenfolge %NUM% enthalten, die durch Zahlen ersetzt wird. Zum Beispiel, wenn UniqueSuffix = "ABC%NUM%" ist, dann werden für das Feld "fieldName" die Namen sein: fieldNameABC1, fieldNameABC2, fieldNameABC3 usw. |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int:A-java.io.OutputStream-) | <p> Fügt Seiten aus einer anderen Datei in die Eingabe‑Pdf‑Datei ein. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); outstream sourceStream = new FileInputStream("file1.pdf"); outstream insertedStream = new FileInputStream("file2.pdf"); OutputStream outStream = new FileoutputStream("out.pdf"); pfe.Insert(sourceStream, 1, insertedStream, new int[] { 3, 4, 5}, outStream); </pre> |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-) | <p> Fügt Seiten aus einer anderen Datei in die Eingabe‑Pdf‑Datei ein. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); outstream sourceStream = new FileInputStream("file1.pdf"); outstream insertedStream = new FileInputStream("file2.pdf"); OutputStream outStream = new FileOutputStream("out.pdf"); pfe.insert(sourceStream, 1, insertedStream, 2, 6, outStream); </pre> |
| [insert](#insert-java.lang.String-int-java.lang.String-int:A-java.lang.String-) | <p> Fügt Seiten aus einer anderen Datei in die Eingabe‑Pdf‑Datei ein. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); outstream sourceStream = new FileInputStream("file1.pdf"); outstream insertedStream = new FileInputStream("file2.pdf"); OutputStream outStream = new FileInputStream("out.pdf"); pfe.insert(sourceStream, 1, insertedStream, 2, 6, outStream); </pre> |
| [insert](#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-) | <p> Fügt Seiten aus einer anderen Datei an einer Position in die Pdf‑Datei ein. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.insert("file1.pdf", 1, "file2.pdf", 2, 6, "out.pdf"); </pre> |
| [isTryMergeAdjacentSameBackgroundImages](#isTryMergeAdjacentSameBackgroundImages--) | Manchmal enthalten PDFs Hintergrundbilder (von Seiten oder Tabellenzellen), die aus mehreren gleichen Kachel‑Hintergrundbildern bestehen, die nebeneinander platziert sind. |
| [isUseDiskBuffer](#isUseDiskBuffer--) | Wenn diese Option verwendet wird, wird das Zieldokument periodisch auf der Festplatte gespeichert und weitere Zusammenführungen werden als inkrementelle Updates darauf angewendet. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-) | <p> Erstellt ein Heft aus dem InputStream zum outputStream. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileInputStream("output.pdf"); pfe.makeBooklet(inputStream, outputStream); </pre> |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-int:A-int:A-) | <p> Erstellt ein benutzerdefiniertes Heft aus dem firstInputStream zum outputStream. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileOutputStream("output.pdf"); pfe.makeBooklet(inputStream, outputStream, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre> |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-) | <p> Erstellt ein Heft aus dem Eingabestream und speichert das Ergebnis in den Ausgabestream. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileInputStream("output.pdf"); pfe.makeBooklet(inputStream, outputStream, PageSize.A4); </pre> |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int:A-int:A-) | <p> Erstellt ein Heft aus dem firstInputStream in den outputStream. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream(\"input.pdf\"); OutputStream outputStream = new FileOutputStream(\"output.pdf\"); pfe.makeBooklet(inputStream, outputStream, PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre> |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-) | <p> Erstellt ein Heft aus der Eingabedatei in die Ausgabedatei. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet(\"input.pdf\", \"output.pdf\"); </pre> |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-int:A-int:A-) | <p> Erstellt ein benutzerdefiniertes Heft aus der firstInputFile in die outputFile. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet(\"input.pdf\", \"output.pdf\", new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre> |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-) | <p> Erstellt ein Heft aus der inputFile in die outputFile. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet(\"input.pdf\", \"output.pdf\", PageSize.A4); </pre> |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-) | <p> Erstellt ein benutzerdefiniertes Heft aus der firstInputFile in die outputFile. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet(\"input.pdf\", \"output.pdf\", PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre> |
| [makeNUp](#makeNUp-java.io.InputStream:A-java.io.OutputStream-boolean-) | <p> Erstellt ein N-Up-Dokument aus den mehreren Eingabe-PDF-Streams in den outputStream. Jede Seite des outputStream enthält mehrere Seiten, die eine Kombination aus den Seiten der Eingabestreams mit derselben Seitennummer darstellen. Die Mehrseiten werden horizontal gestapelt, wenn isSidewise true ist, und vertikal, wenn isSidewise false ist. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream stream1 = new FileInputStream(\"input1.pdf\"); InputStream stream2 = new FileInputStream(\"input2.pdf\"); InputStream stream3 = new FileInputStream(\"input3.pdf\"); OutputStream output = new FileOutputStream(\"output.pdf\"); pfe.makeNUp(new InputStream[] { stream1, stream2, stream3 }, output, false); </pre> |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | <p> Erstellt ein N-Up-Dokument aus den beiden Eingabe-PDF-Streams in den outputStream. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream input1 = new FileInputStream(\"input1.pdf\"); InputStream input2 = new FileInputStream(\"input2.pdf\"); OutputStream output = new FileOutputStream(\"output.pdf\"); pfe.makeNUp(input1, input2, output); </pre> |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-) | <p> Erstellt ein N-Up-Dokument aus dem Eingabestream und speichert das Ergebnis im Ausgabestream. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream(\"input.pdf\"); OutputStream outputStream = new FileOutputStream(\"output.pdf\"); pfe.makeNUp(inputStream, outputStream, 3, 3); </pre> |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-) | <p> Erstellt ein N-Up-Dokument aus dem ersten Eingabestream in den Ausgabestream. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream(\"input.pdf\"); OutputStream outputStream = new FileOutputStream(\"output.pdf\"); pfe.MakeNUp(inputStream, outputStream, 3, 3, PageSize.A4); </pre> |
| [makeNUp](#makeNUp-java.lang.String:A-java.lang.String-boolean-) | <p> Erstellt ein N-Up-Dokument aus den mehreren Eingabe-PDF-Dateien nach outputFile. Jede Seite von outputFile enthält mehrere Seiten, die eine Kombination mit den Seiten in den Eingabedateien derselben Seitennummer darstellen. Die mehreren Seiten werden horizontal angeordnet, wenn isSidewise true ist, und vertikal, wenn isSidewise false ist. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp(new String[] { \"input1.pdf\", \"input2.pdf\", \"input3.pdf\" }, \"output.pdf\", false); </pre> |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-int-int-) | <p> Erstellt ein N-Up-Dokument aus der ersten Eingabedatei nach outputFile. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp(\"input.pdf\", \"output.pdf\", 3, 3); </pre> |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-) | <p> Erstellt ein N-Up-Dokument aus der Eingabedatei nach outputFile. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp(\"input.pdf\", \"output.pdf\", 3, 3, PageSize.A4); </pre> |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-java.lang.String-) | <p> Erstellt ein N-Up-Dokument aus den beiden Eingabe-PDF-Dateien nach outputFile. Jede Seite von outputFile enthält zwei Seiten, eine Seite stammt aus der ersten Eingabedatei und die andere aus der zweiten Eingabedatei. Die beiden Seiten werden horizontal angeordnet. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp(\"input1.pdf\", \"input2.pdf\", \"output.pdf\"); </pre> |
| [resizeContents](#resizeContents-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Ändert die Größe der Dokumentseiten. |
| [resizeContents](#resizeContents-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Ändert die Größe der Dokumentseiten. |
| [resizeContents](#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-double-double-) | <p> Ändert die Größe des Inhalts von Dokumentseiten. Verkleinert den Seiteninhalt und fügt Ränder hinzu. Die neue Größe des Inhalts wird in den standardmäßigen Raumeinheiten angegeben. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream src = new FileInputStream(\"input.pdf\"); OutputStream dest = new FileOutputStream(\"output.pdf\"); fileEditor.resizeContents(src, dest, //resize all pages of document null, //new contents width = 200 200, //new contents height = 300 300); // rest area of page will be empty </pre> |
| [resizeContents](#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Ändert die Größe des Inhalts von Seiten des Dokuments. |
| [resizeContents](#resizeContents-java.lang.String-java.lang.String-int:A-double-double-) | <p> Ändert die Größe des Inhalts von Dokumentseiten. Verkleinert den Seiteninhalt und fügt Ränder hinzu. Die neue Größe des Inhalts wird in den standardmäßigen Raumeinheiten angegeben. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.resizeContents(\"input.pdf\", \"output.pdf\", //resize all pages of document null, //new contents width = 200 200, //new contents height = 300 300); // rest area of page will be empty </pre> |
| [resizeContents](#resizeContents-java.lang.String-java.lang.String-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Ändert die Größe des Inhalts von Seiten im Dokument. |
| [resizeContentsPct](#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-) | <p> Ändert die Größe des Inhalts von Dokumentseiten. Verkleinert den Seiteninhalt und fügt Ränder hinzu. Die neue Inhaltsgröße wird in Prozent angegeben. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream src = new FileInputStream(\"input.pdf\"); OutputStream dest = new FileOutputStream(\"output.pdf\"); fileEditor.resizePct(src, dest, //resize all pages of document null, //new contents width = 60% of initial size 60, //new contents height = 60% of initial size 60); // Rest area of page will be empty (page margins). Size of left and right margins is (100% - 60%) / 2 = 20% // The same for top and bottom margins. </pre> |
| [resizeContentsPct](#resizeContentsPct-java.lang.String-java.lang.String-int:A-double-double-) | <p> Ändert die Größe des Inhalts von Dokumentseiten. Verkleinert den Seiteninhalt und fügt Ränder hinzu. Die neue Inhaltsgröße wird in Prozent angegeben. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.resizePct(\"input.pdf\", \"output.pdf\", //alle Seiten des Dokuments skalieren null, //neue Inhaltsbreite = 60% der ursprünglichen Größe 60, //neue Inhalts­höhe = 60% der ursprünglichen Größe 60); // Der restliche Bereich der Seite bleibt leer (Seitenränder). Größe der linken und rechten Ränder ist (100% - 60%) / 2 = 20% // Das gleiche für obere und untere Ränder. </pre> |
| [resizeContentsWithNormalization](#resizeContentsWithNormalization-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Ändert die Größe der Dokumentseiten. |
| [resizeContentsWithNormalization](#resizeContentsWithNormalization-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Ändert die Größe der Dokumentseiten. |
| [setAllowConcatenateExceptions](#setAllowConcatenateExceptions-boolean-) | <p> Wenn auf true gesetzt, werden Ausnahmen ausgelöst, wenn ein Fehler auftritt. Andernfalls werden keine Ausnahmen ausgelöst und Methoden geben false zurück, wenn sie fehlschlagen. </p> |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | Legt den Namen des Anhangs fest, wenn das Ergebnis der Operation in HttpServletResponse-Objekten als Anhang gespeichert wird. |
| [setCloseConcatenatedStreams](#setCloseConcatenatedStreams-boolean-) | <p> Wenn auf true gesetzt, werden Streams nach der Operation geschlossen. </p> |
| [setConcatenationPacketSize](#setConcatenationPacketSize-int-) | Anzahl der Dokumente, die zusammengeführt wurden, bevor während der Zusammenführung ein neues inkrementelles Update erstellt wurde, wenn UseDiskBuffer auf true gesetzt ist. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | Legt fest, wie der Inhalt gespeichert wird, wenn das Ergebnis der Operation in ein HttpServletResponse-Objekt gespeichert wird. Mögliche Werte: inline / attachment. Standard: inline. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | Legt das PDF‑Dateiformat fest. Die Ergebnisdatei wird im angegebenen Dateiformat gespeichert. Wenn diese Eigenschaft nicht angegeben ist, wird die Datei im Standard‑PDF‑Format ohne Konvertierung gespeichert. |
| [setCopyLogicalStructure](#setCopyLogicalStructure-boolean-) | Wenn true, wird die logische Struktur der Datei bei der Zusammenführung kopiert. |
| [setCopyOutlines](#setCopyOutlines-boolean-) | Wenn true, werden Gliederungen kopiert. |
| [setCorruptedFileAction](#setCorruptedFileAction-int-) | Diese Eigenschaft definiert das Verhalten, wenn der Zusammenführungsprozess auf eine beschädigte Datei trifft. Mögliche Werte sind: StopWithError und ConcatenateIgnoringCorrupted. |
| [setCustomProgressConcatenationHandler](#setCustomProgressConcatenationHandler-com.aspose.pdf.facades.PdfFileEditor.ConcatenationProgressHandler-) | Darstellung des internen Prozessors für Fortschrittsereignisse, der während der Zusammenführung arbeitet und Zusammenführungsereignisse interner Zusammenführungsstufen in den Code des externen Kunden übersetzt. |
| [setIncrementalUpdates](#setIncrementalUpdates-boolean-) | Wenn true, werden während der Zusammenführung inkrementelle Updates durchgeführt. |
| [setKeepActions](#setKeepActions-boolean-) | Wenn true, werden Aktionen aus den Quelldokumenten kopiert. |
| [setKeepFieldsUnique](#setKeepFieldsUnique-boolean-) | Wenn true, werden Feldnamen beim Zusammenführen von Formularen eindeutig gemacht. Suffixe werden zu den Feldnamen hinzugefügt, das Suffix-Template kann in der Eigenschaft UniqueSuffix angegeben werden. |
| [setMergeDuplicateLayers](#setMergeDuplicateLayers-boolean-) | Optionale Inhalte von zusammengeführten Dokumenten mit gleichen Namen werden in einem Layer im resultierenden Dokument zusammengeführt, wenn diese Eigenschaft true ist. |
| [setMergeDuplicateOutlines](#setMergeDuplicateOutlines-boolean-) | Wenn true, werden doppelte Gliederungen zusammengeführt. |
| [setOptimizeSize](#setOptimizeSize-boolean-) | Liest oder setzt Optimierungs-Flag. |
| [setOwnerPassword](#setOwnerPassword-java.lang.String-) | Legt das Eigentümer-Passwort fest, wenn die Quell‑Pdf‑Datei verschlüsselt ist. Diese Eigenschaft ist noch nicht implementiert. |
| [setPreserveUserRights](#setPreserveUserRights-boolean-) | Wenn true, werden die Benutzerrechte des ersten Dokuments auf das zusammengeführte Dokument angewendet. |
| [setRemoveSignatures](#setRemoveSignatures-boolean-) | Wenn true, werden alle Signaturen aus den Feldern entfernt (Felder bleiben erhalten); andernfalls können ungültige Signaturen entstehen. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Legt die Speicheroptionen fest, wenn das Ergebnis als HttpServletResponse gespeichert wird. Standardwert: PdfSaveOptions. |
| [setTryMergeAdjacentSameBackgroundImages](#setTryMergeAdjacentSameBackgroundImages-boolean-) | Manchmal enthalten PDFs Hintergrundbilder (von Seiten oder Tabellenzellen), die aus mehreren gleichen Kachel‑Hintergrundbildern bestehen, die nebeneinander platziert sind. |
| [setUniqueSuffix](#setUniqueSuffix-java.lang.String-) | <p> Legt das Format des Suffixes fest, das dem Feldnamen hinzugefügt wird, um ihn eindeutig zu machen, wenn Formulare zusammengeführt werden. Dieser String muss das Teilzeichen %NUM% enthalten, das durch Zahlen ersetzt wird. Zum Beispiel, wenn UniqueSuffix = \"ABC%NUM%\" ist, dann werden für das Feld \"fieldName\" die Namen: fieldNameABC1, fieldNameABC2, fieldNameABC3 usw. erzeugt. </p> <hr> <pre> PdfFileEditor ed = new PdfFileEditor(); ed.setUniqueSuffix ( \"_%NUM%\"); </pre> |
| [setUseDiskBuffer](#setUseDiskBuffer-boolean-) | Wenn diese Option verwendet wird, wird das Zieldokument periodisch auf der Festplatte gespeichert und weitere Zusammenführungen werden als inkrementelle Updates darauf angewendet. |
| [splitFromFirst](#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-) | <p> Teilt vom Anfang bis zum angegebenen Ort und speichert den vorderen Teil im Ausgabestream. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream(\"file1.pdf\"); OutputStream outStream = new FileOutputStream(\"out.pdf\"); pfe.splitFromFirst(sourceStream, 5, outStream); </pre> <hr> Die Streams werden nach diesem Vorgang NICHT geschlossen. |
| [splitFromFirst](#splitFromFirst-java.lang.String-int-java.lang.String-) | <p> Teilt die Pdf‑Datei von der ersten Seite bis zum angegebenen Ort und speichert den vorderen Teil als neue Datei. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.splitFromFirst(\"input.pdf\", 5, \"out.pdf\"); </pre> |
| [splitToBulks](#splitToBulks-java.io.InputStream-int:A:A-) | Teilt die Pdf‑Datei in mehrere Dokumente. Die Dokumente können einseitig oder mehrseitig sein. |
| [splitToBulks](#splitToBulks-java.lang.String-int:A:A-) | Teilt die Pdf‑Datei in mehrere Dokumente. Die Dokumente können einseitig oder mehrseitig sein. |
| [splitToEnd](#splitToEnd-java.io.InputStream-int-java.io.OutputStream-) | <p> Teilt ab dem angegebenen Ort und speichert den hinteren Teil als neuen Dateistream. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream(\"file1.pdf\"); OutputStream outStream = new FileInputStream(\"out.pdf\"); pfe.splitToEnd(sourceStream, 5, outStream); </pre> <hr> Die Streams werden nach diesem Vorgang NICHT geschlossen, es sei denn, CloseConcatedStreams ist angegeben. |
| [splitToEnd](#splitToEnd-java.lang.String-int-java.lang.String-) | <p> Teilt ab dem Ort und speichert den hinteren Teil als neue Datei. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.splitToEnd(\"input.pdf\", 5, \"out.pdf\"); </pre> |
| [splitToPages](#splitToPages-java.io.InputStream-) | Teilt die Pdf‑Datei in einseitige Dokumente. |
| [splitToPages](#splitToPages-java.io.InputStream-java.lang.String-) | Teilt die Pdf‑Datei in einseitige Dokumente und speichert sie im angegebenen Pfad. |
| [splitToPages](#splitToPages-java.lang.String-) | Teilt die PDF‑Datei in einseitige Dokumente. |
| [splitToPages](#splitToPages-java.lang.String-java.lang.String-) | Teilt die Pdf‑Datei in einseitige Dokumente und speichert sie im angegebenen Pfad. |

### PdfFileEditor {#PdfFileEditor--}
```
public PdfFileEditor()
```

PdfFileEditor Konstruktor.

### addMargins {#addMargins-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-}
<p> Ändert die Größe des Seiteninhalts und fügt angegebene Ränder hinzu. Die Ränder werden in Standardabstandseinheiten angegeben. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InmputStream src = new FileInputStream("input.pdf"); OutputStream dest = new FileInputStream("output.pdf"); fileEditor.addMargins(src, dest, //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 10 units 10, //right margin is 5 units 5, //top margin is 5 units 5, //bottom margin is 5 units 5); dest.Close(); </pre>

### addMargins {#addMargins-java.lang.String-java.lang.String-int:A-double-double-double-double-}
<p> Ändert die Größe des Seiteninhalts und fügt angegebene Ränder hinzu. Die Ränder werden in Standardabstandseinheiten angegeben. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.addMargins("input.pdf", "output.pdf", //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 10 units 10, //right margin is 5 units 5, //top margin is 5 units 5, //bottom margin is 5 units 5); </pre>

### addMarginsPct {#addMarginsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-}
<p> Ändert die Größe des Seiteninhalts und fügt angegebene Ränder hinzu. Die Ränder werden in Prozent der ursprünglichen Seitengröße angegeben. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InmputStream src = new FileInputStream("input.pdf"); OutputStream dest = new FileInputStream("output.pdf"); fileEditor.addMarginsPct(src, dest, //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 15% of page width 15, //right margin is 10% of page width 10, //top margin is 20% of page width 20, //bottom margin is 5% of page width 5); dest.close(); </pre>

### addMarginsPct {#addMarginsPct-java.lang.String-java.lang.String-int:A-double-double-double-double-}
<p> Ändert die Größe des Seiteninhalts und fügt die angegebenen Ränder hinzu. Die Ränder werden in Prozent der ursprünglichen Seitengröße angegeben. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.addMarginsPct("input.pdf", "output.pdf", //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 15% of page width 15, //right margin is 10% of page width 10, //top margin is 20% of page width 20, //bottom margin is 5% of page width 5); </pre>

### addPageBreak {#addPageBreak-com.aspose.pdf.Document-com.aspose.pdf.Document-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
Fügt Seitenumbrüche in die Dokumentseiten ein.

### addPageBreak {#addPageBreak-com.aspose.pdf.IDocument-com.aspose.pdf.IDocument-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
Fügt Seitenumbrüche in die Dokumentseiten ein.

### addPageBreak {#addPageBreak-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
Fügt Seitenumbrüche in die Dokumentseiten ein.

### addPageBreak {#addPageBreak-java.lang.String-java.lang.String-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
Fügt Seitenumbrüche in die Dokumentseiten ein.

### append {#append-java.io.InputStream-java.io.InputStream:A-int-int-java.io.OutputStream-}
<p> Fügt Seiten an, die aus einem Array von Dokumenten in portStreams ausgewählt werden. Das Ergebnisdokument enthält firstInputFile und alle Seiten der portStreams-Dokumente im Bereich startPage bis endPage. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream instream = new FileInputStream("input.pdf"); InputStream stream1 = new FileInputStream("file1.pdf"); InputStream stream2 = new FileInputStream("file2.pdf"); OtputStream outstream = new FileOutputStream("outfile.pdf"); fileEditor.append(instream, new InputStream[] { stream1, stream2}, 3, 5, outstream); </pre>

### append {#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-}
<p> Fügt Seiten an, die aus portStream im Bereich von startPage bis endPage ausgewählt werden, in portStream am Ende von firstInputStream. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream instream = new FileInputStream("input.pdf"); InputStream stream1 = new FileInputStream("file1.pdf"); OutputStream outstream = new FileOutputStream("outfile.pdf"); fileEditor.append(instream, stream1, 3, 5, outstream); </pre>

### append {#append-java.lang.String-java.lang.String:A-int-int-java.lang.String-}
<p> Fügt Seiten an, die aus den portFiles-Dokumenten ausgewählt werden. Das Ergebnisdokument enthält firstInputFile und alle Seiten der portFiles-Dokumente im Bereich startPage bis endPage. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.append("input.pdf", new string[] { "file1.pdf", "file2.pdf"}, 3, 5, "outfile.pdf"); </pre>

### append {#append-java.lang.String-java.lang.String-int-int-java.lang.String-}
<p> Fügt Seiten an, die aus portFile im Bereich von startPage bis endPage ausgewählt werden, in portFile am Ende von firstInputFile. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.append("input.pdf", "file1.pdf", 3, 5, "outfile.pdf"); </pre>

### concatenate {#concatenate-com.aspose.pdf.IDocument:A-com.aspose.pdf.IDocument-}
Verkettet Dokumente.

### concatenate {#concatenate-java.io.InputStream:A-java.io.OutputStream-}
<p> Verkettet Dateien </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream stream1 = new FileInputStream("file1.pdf"); InputStream stream2 = new FileInputStream("file2.pdf"); OutputStream outstream = new FileOutputStream("outfile.pdf"); fileEditor.concatenate(new Stream[] { stream1, stream2 } , outstream); </pre>

### concatenate {#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
<p> Fügt zwei Pdf-Dokumente zu einem neuen Pdf-Dokument zusammen, wobei die Seiten abwechselnd angeordnet werden, und füllt die leeren Stellen mit leeren Seiten. z.B.: document1 hat 5 Seiten: p1, p2, p3, p4, p5. document2 hat 3 Seiten: p1', p2', p3'. Das Zusammenführen der beiden Pdf-Dokumente erzeugt das Ergebnisdokument mit den Seiten: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream stream1 = new FileInputStream(\"file1.pdf\"); InputStream stream2 = new FileInputStream(\"file2.pdf\"); InputStream blank = new FileInputStream(\"blank.pdf\"); OutputStream outstream = new FileOutputStream(\"outfile.pdf\"); fileEditor.concatenate(new Stream[] { stream1, stream2, blank } , outstream); </pre>

### concatenate {#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
<p> Verkettet zwei Dateien. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream stream1 = new FileInputStream(\"file1.pdf\"); InputStream stream2 = new FileInputStream(\"file2.pdf\"); OutputStream outstream = new FileOutputStream(\"outfile.pdf\"); fileEditor.concatenate(stream1, stream2, outstream); </pre>

### concatenate {#concatenate-java.lang.String:A-java.lang.String-}
<p> Verkettet Dateien zu einer Datei. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.concatenate(new String[] { \"src1.pdf\", \"src2.pdf\" }, \"dest.pdf\"); </pre>

### concatenate {#concatenate-java.lang.String-java.lang.String-java.lang.String-}
<p> Verkettet zwei Dateien. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.concatenate(\"file1.pdf\", \"file2.pdf\", \"outfile.pdf\"); </pre>

### concatenate {#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
<p> Fügt zwei Pdf-Dokumente zu einem neuen Pdf-Dokument zusammen, wobei die Seiten abwechselnd angeordnet werden, und füllt die leeren Stellen mit leeren Seiten. z.B.: document1 hat 5 Seiten: p1, p2, p3, p4, p5. document2 hat 3 Seiten: p1', p2', p3'. Das Zusammenführen der beiden Pdf-Dokumente erzeugt das Ergebnisdokument mit den Seiten: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.concatenate(\"src1.pdf\", \"src2.pdf\", \"blank.pdf\", \"dest.pdf\"); </pre>

### createArrayWithExclusion {#createArrayWithExclusion-int-int-}
```
public static Integer [] createArrayWithExclusion(int n, int y)
```



### delete {#delete-java.io.InputStream-int:A-java.io.OutputStream-}
<p> Löscht Seiten, die durch ein Zahlenarray angegeben sind, aus der Eingabedatei und speichert sie als neue Pdf-Datei. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream intputStream = new FileInputStream(\"input.pdf\"); OutputStream outputStream = new FileInputStream(\"output.pdf\"); pfe.Delete(inputStream, new int[] { 2, 3 }, outputStream); </pre>

### delete {#delete-java.lang.String-int:A-java.lang.String-}
<p> Löscht Seiten, die durch ein Zahlenarray angegeben sind, aus der Eingabedatei und speichert sie als neue Pdf-Datei. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.delete(\"input.pdf\", new int[] { 2, 3 }, \"out.pdf\"); </pre>

### extract {#extract-java.io.InputStream-int:A-java.io.OutputStream-}
<p> Extrahiert Seiten, die durch ein Zahlenarray angegeben sind, und speichert sie als neue Pdf-Datei. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream(\"file1.pdf\"); OutputStream outStream = new FileInputStream(\"out.pdf\"); pfe.extract(sourceStream, new int[] { 3, 5, 8 }, outStream); </pre>

### extract {#extract-java.io.InputStream-int-int-java.io.OutputStream-}
<p> Extrahiert Seiten aus der Eingabedatei und speichert sie als neue Pdf-Datei. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream(\"file1.pdf\"); OutputStream outStream = new FileOutputStream(\"out.pdf\"); pfe.extract(sourceStream, 1, 3, 6, outStream); </pre>

### extract {#extract-java.lang.String-int:A-java.lang.String-}
<p> Extrahiert Seiten, die durch ein Zahlenarray angegeben sind, und speichert sie als neue PDF-Datei. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.extract("input.pdf", new int[] { 3, 5, 7 }, "output.pdf"); </pre>

### extract {#extract-java.lang.String-int-int-java.lang.String-}
<p> Extrahiert Seiten aus der Eingabedatei und speichert sie als neue PDF-Datei. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.Extract("input.pdf", 3, 7, "output.pdf"); </pre>

### getAllowConcatenateExceptions {#getAllowConcatenateExceptions--}
```
@Deprecated public boolean getAllowConcatenateExceptions()
```

<p> Wenn auf true gesetzt, werden Ausnahmen ausgelöst, wenn ein Fehler auftritt. Andernfalls werden keine Ausnahmen ausgelöst und die Methoden geben false zurück, wenn sie fehlschlagen. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.setAllowConcatenatedException (true); </pre>

**Returns:**
boolescher Wert @deprecated Diese Eigenschaft ist veraltet und kann nicht verwendet werden, um Ausnahmen zuzulassen.

### getAttachmentName {#getAttachmentName--}
```
public String getAttachmentName()
```

Ermittelt den Namen des Anhangs, wenn das Ergebnis der Operation in HttpServletResponse-Objekten als Anhang gespeichert wird.

**Returns:**
String Wert

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

Ermittelt, wie der Inhalt gespeichert wird, wenn das Ergebnis der Operation in ein HttpServletResponse-Objekt gespeichert wird. Mögliche Werte: inline / attachment. Standard: inline.

**Returns:**
ContentDisposition-Element @see ContentDisposition

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

Diese Eigenschaft definiert das Verhalten, wenn der Zusammenführungsprozess auf eine beschädigte Datei trifft. Mögliche Werte sind: StopWithError und ConcatenateIgnoringCorrupted.

**Returns:**
ConcatenateCorruptedFileAction-Element @see ConcatenateCorruptedFileAction

### getCorruptedItems {#getCorruptedItems--}
```
public PdfFileEditor.CorruptedItem [] getCorruptedItems()
```

<p> Array von aufgetretenen Problemen, wenn die Zusammenführung durchgeführt wurde. Für jedes beschädigte Dokument, das an die Funktion Concatenate() übergeben wird, wird ein neuer CorruptedItem-Eintrag erstellt. Diese Eigenschaft darf nur verwendet werden, wenn CorruptedFileAction auf ConcatenateIgnoringCorrupted gesetzt ist. </p> <hr> <pre> //concatenate documents and show information about corrupted documents PdfFileEditor pfe = new PdfFileEditor(); pfe.setCorruptedFileAction(PdfFileEditor.ConcatenateCorruptedFileAction.ConcatenateIgnoringCorrupted); {@code if (pfe.getCorruptedItems().length >0)} { for(PdfFileEditor.CorruptedItem item : pfe.getCorruptedItems()) { System.out.println(item.getIndex()+ " reason: " + item.getException()); } } </pre>

**Returns:**
Array von PdfFileEditor.CorruptedItem

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

Wenn true, werden Feldnamen beim Zusammenführen von Formularen eindeutig gemacht. Suffixe werden zu den Feldnamen hinzugefügt, das Suffix-Template kann in der Eigenschaft UniqueSuffix angegeben werden.

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

Ermittelt das Passwort des Eigentümers, wenn die Quell-PDF-Datei verschlüsselt ist. Diese Eigenschaft ist noch nicht implementiert.

**Returns:**
String Wert

### getPreserveUserRights {#getPreserveUserRights--}
```
public boolean getPreserveUserRights()
```

Wenn true, werden die Benutzerrechte des ersten Dokuments auf das zusammengeführte Dokument angewendet.

**Returns:**
boolescher Wert

### getRemoveSignatures {#getRemoveSignatures--}
```
public final boolean getRemoveSignatures()
```

Wenn true, werden alle Signaturen aus den Feldern entfernt (Felder bleiben erhalten); andernfalls können ungültige Signaturen entstehen.

**Returns:**
boolescher Wert

### getSaveOptions {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```

Liest oder setzt Speicheroptionen, wenn das Ergebnis als HttpServletResponse gespeichert wird. Standardwert: PdfSaveOptions.

**Returns:**
SaveOptions-Objekt

### getUniqueSuffix {#getUniqueSuffix--}
```
public String getUniqueSuffix()
```

Erhalte das Format des Suffixes, das dem Feldnamen hinzugefügt wird, um ihn eindeutig zu machen, wenn Formulare zusammengeführt werden. Dieser String muss die Teilzeichenfolge %NUM% enthalten, die durch Zahlen ersetzt wird. Zum Beispiel, wenn UniqueSuffix = "ABC%NUM%" ist, dann werden für das Feld "fieldName" die Namen sein: fieldNameABC1, fieldNameABC2, fieldNameABC3 usw.

**Returns:**
String Wert

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int:A-java.io.OutputStream-}
<p> Fügt Seiten aus einer anderen Datei in die Eingabe‑Pdf‑Datei ein. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); outstream sourceStream = new FileInputStream("file1.pdf"); outstream insertedStream = new FileInputStream("file2.pdf"); OutputStream outStream = new FileoutputStream("out.pdf"); pfe.Insert(sourceStream, 1, insertedStream, new int[] { 3, 4, 5}, outStream); </pre>

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-}
<p> Fügt Seiten aus einer anderen Datei in die Eingabe‑Pdf‑Datei ein. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); outstream sourceStream = new FileInputStream("file1.pdf"); outstream insertedStream = new FileInputStream("file2.pdf"); OutputStream outStream = new FileOutputStream("out.pdf"); pfe.insert(sourceStream, 1, insertedStream, 2, 6, outStream); </pre>

### insert {#insert-java.lang.String-int-java.lang.String-int:A-java.lang.String-}
<p> Fügt Seiten aus einer anderen Datei in die Eingabe‑Pdf‑Datei ein. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); outstream sourceStream = new FileInputStream("file1.pdf"); outstream insertedStream = new FileInputStream("file2.pdf"); OutputStream outStream = new FileInputStream("out.pdf"); pfe.insert(sourceStream, 1, insertedStream, 2, 6, outStream); </pre>

### insert {#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-}
<p> Fügt Seiten aus einer anderen Datei an einer Position in die Pdf‑Datei ein. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.insert("file1.pdf", 1, "file2.pdf", 2, 6, "out.pdf"); </pre>

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
<p> Erstellt ein Heft aus dem InputStream zum outputStream. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileInputStream("output.pdf"); pfe.makeBooklet(inputStream, outputStream); </pre>

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-int:A-int:A-}
<p> Erstellt ein benutzerdefiniertes Heft aus dem firstInputStream zum outputStream. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileOutputStream("output.pdf"); pfe.makeBooklet(inputStream, outputStream, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre>

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-}
<p> Erstellt ein Heft aus dem Eingabestream und speichert das Ergebnis in den Ausgabestream. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileInputStream("output.pdf"); pfe.makeBooklet(inputStream, outputStream, PageSize.A4); </pre>

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int:A-int:A-}
<p> Erstellt ein Heft aus dem firstInputStream in den outputStream. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream(\"input.pdf\"); OutputStream outputStream = new FileOutputStream(\"output.pdf\"); pfe.makeBooklet(inputStream, outputStream, PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre>

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-}
<p> Erstellt ein Heft aus der Eingabedatei in die Ausgabedatei. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet(\"input.pdf\", \"output.pdf\"); </pre>

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-int:A-int:A-}
<p> Erstellt ein benutzerdefiniertes Heft aus der firstInputFile in die outputFile. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet(\"input.pdf\", \"output.pdf\", new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre>

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-}
<p> Erstellt ein Heft aus der inputFile in die outputFile. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet(\"input.pdf\", \"output.pdf\", PageSize.A4); </pre>

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-}
<p> Erstellt ein benutzerdefiniertes Heft aus der firstInputFile in die outputFile. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet(\"input.pdf\", \"output.pdf\", PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre>

### makeNUp {#makeNUp-java.io.InputStream:A-java.io.OutputStream-boolean-}
<p> Erstellt ein N-Up-Dokument aus den mehreren Eingabe-PDF-Streams in den outputStream. Jede Seite des outputStream enthält mehrere Seiten, die eine Kombination aus den Seiten der Eingabestreams mit derselben Seitennummer darstellen. Die Mehrseiten werden horizontal gestapelt, wenn isSidewise true ist, und vertikal, wenn isSidewise false ist. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream stream1 = new FileInputStream(\"input1.pdf\"); InputStream stream2 = new FileInputStream(\"input2.pdf\"); InputStream stream3 = new FileInputStream(\"input3.pdf\"); OutputStream output = new FileOutputStream(\"output.pdf\"); pfe.makeNUp(new InputStream[] { stream1, stream2, stream3 }, output, false); </pre>

### makeNUp {#makeNUp-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
<p> Erstellt ein N-Up-Dokument aus den beiden Eingabe-PDF-Streams in den outputStream. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream input1 = new FileInputStream(\"input1.pdf\"); InputStream input2 = new FileInputStream(\"input2.pdf\"); OutputStream output = new FileOutputStream(\"output.pdf\"); pfe.makeNUp(input1, input2, output); </pre>

### makeNUp {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-}
<p> Erstellt ein N-Up-Dokument aus dem Eingabestream und speichert das Ergebnis im Ausgabestream. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream(\"input.pdf\"); OutputStream outputStream = new FileOutputStream(\"output.pdf\"); pfe.makeNUp(inputStream, outputStream, 3, 3); </pre>

### makeNUp {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-}
<p> Erstellt ein N-Up-Dokument aus dem ersten Eingabestream in den Ausgabestream. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream(\"input.pdf\"); OutputStream outputStream = new FileOutputStream(\"output.pdf\"); pfe.MakeNUp(inputStream, outputStream, 3, 3, PageSize.A4); </pre>

### makeNUp {#makeNUp-java.lang.String:A-java.lang.String-boolean-}
<p> Erstellt ein N-Up-Dokument aus den mehreren Eingabe-PDF-Dateien nach outputFile. Jede Seite von outputFile enthält mehrere Seiten, die eine Kombination mit den Seiten in den Eingabedateien derselben Seitennummer darstellen. Die mehreren Seiten werden horizontal angeordnet, wenn isSidewise true ist, und vertikal, wenn isSidewise false ist. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp(new String[] { \"input1.pdf\", \"input2.pdf\", \"input3.pdf\" }, \"output.pdf\", false); </pre>

### makeNUp {#makeNUp-java.lang.String-java.lang.String-int-int-}
<p> Erstellt ein N-Up-Dokument aus der ersten Eingabedatei nach outputFile. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp(\"input.pdf\", \"output.pdf\", 3, 3); </pre>

### makeNUp {#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-}
<p> Erstellt ein N-Up-Dokument aus der Eingabedatei nach outputFile. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp(\"input.pdf\", \"output.pdf\", 3, 3, PageSize.A4); </pre>

### makeNUp {#makeNUp-java.lang.String-java.lang.String-java.lang.String-}
<p> Erstellt ein N-Up-Dokument aus den beiden Eingabe-PDF-Dateien nach outputFile. Jede Seite von outputFile enthält zwei Seiten, eine Seite stammt aus der ersten Eingabedatei und die andere aus der zweiten Eingabedatei. Die beiden Seiten werden horizontal angeordnet. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp(\"input1.pdf\", \"input2.pdf\", \"output.pdf\"); </pre>

### resizeContents {#resizeContents-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Ändert die Größe der Dokumentseiten.

### resizeContents {#resizeContents-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Ändert die Größe der Dokumentseiten.

### resizeContents {#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-double-double-}
<p> Ändert die Größe des Inhalts von Dokumentseiten. Verkleinert den Seiteninhalt und fügt Ränder hinzu. Die neue Größe des Inhalts wird in den standardmäßigen Raumeinheiten angegeben. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream src = new FileInputStream(\"input.pdf\"); OutputStream dest = new FileOutputStream(\"output.pdf\"); fileEditor.resizeContents(src, dest, //resize all pages of document null, //new contents width = 200 200, //new contents height = 300 300); // rest area of page will be empty </pre>

### resizeContents {#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Ändert die Größe des Inhalts von Seiten des Dokuments.

### resizeContents {#resizeContents-java.lang.String-java.lang.String-int:A-double-double-}
<p> Ändert die Größe des Inhalts von Dokumentseiten. Verkleinert den Seiteninhalt und fügt Ränder hinzu. Die neue Größe des Inhalts wird in den standardmäßigen Raumeinheiten angegeben. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.resizeContents(\"input.pdf\", \"output.pdf\", //resize all pages of document null, //new contents width = 200 200, //new contents height = 300 300); // rest area of page will be empty </pre>

### resizeContents {#resizeContents-java.lang.String-java.lang.String-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Ändert die Größe des Inhalts von Seiten im Dokument.

### resizeContentsPct {#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-}
<p> Ändert die Größe des Inhalts von Dokumentseiten. Verkleinert den Seiteninhalt und fügt Ränder hinzu. Die neue Inhaltsgröße wird in Prozent angegeben. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream src = new FileInputStream(\"input.pdf\"); OutputStream dest = new FileOutputStream(\"output.pdf\"); fileEditor.resizePct(src, dest, //resize all pages of document null, //new contents width = 60% of initial size 60, //new contents height = 60% of initial size 60); // Rest area of page will be empty (page margins). Size of left and right margins is (100% - 60%) / 2 = 20% // The same for top and bottom margins. </pre>

### resizeContentsPct {#resizeContentsPct-java.lang.String-java.lang.String-int:A-double-double-}
<p> Ändert die Größe des Inhalts von Dokumentseiten. Verkleinert den Seiteninhalt und fügt Ränder hinzu. Die neue Inhaltsgröße wird in Prozent angegeben. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.resizePct(\"input.pdf\", \"output.pdf\", //alle Seiten des Dokuments skalieren null, //neue Inhaltsbreite = 60% der ursprünglichen Größe 60, //neue Inhalts­höhe = 60% der ursprünglichen Größe 60); // Der restliche Bereich der Seite bleibt leer (Seitenränder). Größe der linken und rechten Ränder ist (100% - 60%) / 2 = 20% // Das gleiche für obere und untere Ränder. </pre>

### resizeContentsWithNormalization {#resizeContentsWithNormalization-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Ändert die Größe der Dokumentseiten.

### resizeContentsWithNormalization {#resizeContentsWithNormalization-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Ändert die Größe der Dokumentseiten.

### setAllowConcatenateExceptions {#setAllowConcatenateExceptions-boolean-}
```
@Deprecated public void setAllowConcatenateExceptions(boolean value)
```

<p> Wenn auf true gesetzt, werden Ausnahmen ausgelöst, wenn ein Fehler auftritt. Andernfalls werden keine Ausnahmen ausgelöst und Methoden geben false zurück, wenn sie fehlschlagen. </p>

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.setAllowConcatenatedException (true); </pre> @deprecated Diese Eigenschaft ist veraltet und kann nicht verwendet werden, um das Werfen von Ausnahmen zu erlauben. |

### setAttachmentName {#setAttachmentName-java.lang.String-}
Legt den Namen des Anhangs fest, wenn das Ergebnis der Operation in HttpServletResponse-Objekten als Anhang gespeichert wird.

### setCloseConcatenatedStreams {#setCloseConcatenatedStreams-boolean-}
```
public void setCloseConcatenatedStreams(boolean value)
```

<p> Wenn auf true gesetzt, werden Streams nach der Operation geschlossen. </p>

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.setCloseConcatenatedStreams (true); </pre> |

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
Legt fest, wie der Inhalt gespeichert wird, wenn das Ergebnis der Operation in ein HttpServletResponse-Objekt gespeichert wird. Mögliche Werte: inline / attachment. Standard: inline.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Legt das PDF‑Dateiformat fest. Die Ergebnisdatei wird im angegebenen Dateiformat gespeichert. Wenn diese Eigenschaft nicht angegeben ist, wird die Datei im Standard‑PDF‑Format ohne Konvertierung gespeichert.

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

Diese Eigenschaft definiert das Verhalten, wenn der Zusammenführungsprozess auf eine beschädigte Datei trifft. Mögliche Werte sind: StopWithError und ConcatenateIgnoringCorrupted.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert @see ConcatenateCorruptedFileAction |

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

Wenn true, werden Feldnamen beim Zusammenführen von Formularen eindeutig gemacht. Suffixe werden zu den Feldnamen hinzugefügt, das Suffix-Template kann in der Eigenschaft UniqueSuffix angegeben werden.

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
Legt das Eigentümer-Passwort fest, wenn die Quell‑Pdf‑Datei verschlüsselt ist. Diese Eigenschaft ist noch nicht implementiert.

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
public final void setRemoveSignatures(boolean value)
```

Wenn true, werden alle Signaturen aus den Feldern entfernt (Felder bleiben erhalten); andernfalls können ungültige Signaturen entstehen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Legt die Speicheroptionen fest, wenn das Ergebnis als HttpServletResponse gespeichert wird. Standardwert: PdfSaveOptions.

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
<p> Legt das Format des Suffixes fest, das dem Feldnamen hinzugefügt wird, um ihn eindeutig zu machen, wenn Formulare zusammengeführt werden. Dieser String muss das Teilzeichen %NUM% enthalten, das durch Zahlen ersetzt wird. Zum Beispiel, wenn UniqueSuffix = \"ABC%NUM%\" ist, dann werden für das Feld \"fieldName\" die Namen: fieldNameABC1, fieldNameABC2, fieldNameABC3 usw. erzeugt. </p> <hr> <pre> PdfFileEditor ed = new PdfFileEditor(); ed.setUniqueSuffix ( \"_%NUM%\"); </pre>

### setUseDiskBuffer {#setUseDiskBuffer-boolean-}
```
public final void setUseDiskBuffer(boolean value)
```

Wenn diese Option verwendet wird, wird das Zieldokument periodisch auf der Festplatte gespeichert und weitere Zusammenführungen werden als inkrementelle Updates darauf angewendet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### splitFromFirst {#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-}
<p> Teilt vom Anfang bis zum angegebenen Ort und speichert den vorderen Teil im Ausgabestream. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream(\"file1.pdf\"); OutputStream outStream = new FileOutputStream(\"out.pdf\"); pfe.splitFromFirst(sourceStream, 5, outStream); </pre> <hr> Die Streams werden nach diesem Vorgang NICHT geschlossen.

### splitFromFirst {#splitFromFirst-java.lang.String-int-java.lang.String-}
<p> Teilt die Pdf‑Datei von der ersten Seite bis zum angegebenen Ort und speichert den vorderen Teil als neue Datei. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.splitFromFirst(\"input.pdf\", 5, \"out.pdf\"); </pre>

### splitToBulks {#splitToBulks-java.io.InputStream-int:A:A-}
Teilt die Pdf‑Datei in mehrere Dokumente. Die Dokumente können einseitig oder mehrseitig sein.

### splitToBulks {#splitToBulks-java.lang.String-int:A:A-}
Teilt die Pdf‑Datei in mehrere Dokumente. Die Dokumente können einseitig oder mehrseitig sein.

### splitToEnd {#splitToEnd-java.io.InputStream-int-java.io.OutputStream-}
<p> Teilt ab dem angegebenen Ort und speichert den hinteren Teil als neuen Dateistream. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream(\"file1.pdf\"); OutputStream outStream = new FileInputStream(\"out.pdf\"); pfe.splitToEnd(sourceStream, 5, outStream); </pre> <hr> Die Streams werden nach diesem Vorgang NICHT geschlossen, es sei denn, CloseConcatedStreams ist angegeben.

### splitToEnd {#splitToEnd-java.lang.String-int-java.lang.String-}
<p> Teilt ab dem Ort und speichert den hinteren Teil als neue Datei. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.splitToEnd(\"input.pdf\", 5, \"out.pdf\"); </pre>

### splitToPages {#splitToPages-java.io.InputStream-}
Teilt die Pdf‑Datei in einseitige Dokumente.

### splitToPages {#splitToPages-java.io.InputStream-java.lang.String-}
Teilt die Pdf‑Datei in einseitige Dokumente und speichert sie im angegebenen Pfad.

### splitToPages {#splitToPages-java.lang.String-}
Teilt die PDF‑Datei in einseitige Dokumente.

### splitToPages {#splitToPages-java.lang.String-java.lang.String-}
Teilt die Pdf‑Datei in einseitige Dokumente und speichert sie im angegebenen Pfad.
