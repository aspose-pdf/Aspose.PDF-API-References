---
title: PdfFileEditor
second_title: Aspose.PDF für .NET-API-Referenz
description: Implementiert Operationen mit PDF-Dateien Verketten Aufteilen Extrahieren von Seiten Erstellen von Broschüren usw.
type: docs
weight: 2470
url: /de/net/aspose.pdf.facades/pdffileeditor/
---
## PdfFileEditor class

Implementiert Operationen mit PDF-Dateien: Verketten, Aufteilen, Extrahieren von Seiten, Erstellen von Broschüren usw.

```csharp
public sealed class PdfFileEditor
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [PdfFileEditor](pdffileeditor)() | Default_Constructor |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AttachmentName](../../aspose.pdf.facades/pdffileeditor/attachmentname) { get; set; } | Ruft den Namen des Anhangs ab oder legt ihn fest, wenn das Ergebnis der Operation als Anhang in HttpResponse-Objekten gespeichert wird. |
| [CloseConcatenatedStreams](../../aspose.pdf.facades/pdffileeditor/closeconcatenatedstreams) { get; set; } | Wenn auf true gesetzt, werden Streams nach der Operation geschlossen. |
| [ConcatenationPacketSize](../../aspose.pdf.facades/pdffileeditor/concatenationpacketsize) { get; set; } | Anzahl der verketteten Dokumente, bevor während der Verkettung ein neues inkrementelles Update durchgeführt wurde, wenn UseDiskBuffer auf „true“ gesetzt ist. |
| [ContentDisposition](../../aspose.pdf.facades/pdffileeditor/contentdisposition) { get; set; } | Ruft ab oder legt fest, wie Inhalte gespeichert werden, wenn das Ergebnis der Operation im HttpResponse-Objekt gespeichert wird. Möglicher Wert: inline / attachment. Standard: inline. |
| [ConversionLog](../../aspose.pdf.facades/pdffileeditor/conversionlog) { get; } | Ruft das Protokoll des Konvertierungsprozesses ab. |
| [ConvertTo](../../aspose.pdf.facades/pdffileeditor/convertto) { set; } | Legt das PDF-Dateiformat fest. Die Ergebnisdatei wird im angegebenen Dateiformat gespeichert. Wenn diese Eigenschaft nicht angegeben ist, wird die Datei ohne Konvertierung im Standard-PDF-Format gespeichert. |
| [CopyLogicalStructure](../../aspose.pdf.facades/pdffileeditor/copylogicalstructure) { get; set; } | Wenn wahr, dann wird die logische Struktur der Datei kopiert, wenn die Verkettung durchgeführt wird. |
| [CopyOutlines](../../aspose.pdf.facades/pdffileeditor/copyoutlines) { get; set; } | Wenn wahr, dann werden Umrisse kopiert. |
| [CorruptedFileAction](../../aspose.pdf.facades/pdffileeditor/corruptedfileaction) { get; set; } | Diese Eigenschaft definiert das Verhalten, wenn der Verkettungsprozess auf eine beschädigte Datei trifft. Mögliche Werte sind: StopWithError und ConcatenateIgnoringCorrupted. |
| [CorruptedItems](../../aspose.pdf.facades/pdffileeditor/corrupteditems) { get; } | Array von aufgetretenen Problemen, wenn eine Verkettung durchgeführt wurde. Für jedes beschädigte Dokument, das an die Funktion Concatenate() übergeben wird, wird ein neuer CorruptedItem-Eintrag erstellt. Diese Eigenschaft darf nur verwendet werden, wenn CorruptedFileAction ConcatenateIgnoringCorrupted ist. |
| [IncrementalUpdates](../../aspose.pdf.facades/pdffileeditor/incrementalupdates) { get; set; } | Wenn wahr, werden während der Verkettung inkrementelle Aktualisierungen vorgenommen. |
| [KeepActions](../../aspose.pdf.facades/pdffileeditor/keepactions) { get; set; } | Wenn wahr, werden Aktionen aus Quelldokumenten kopiert. Standardwert: true. |
| [KeepFieldsUnique](../../aspose.pdf.facades/pdffileeditor/keepfieldsunique) { get; set; } | Wenn wahr, dann werden Feldnamen eindeutig gemacht, wenn Formulare verkettet werden. Feldnamen werden Suffixe hinzugefügt, Suffix-Vorlage kann in der UniqueSuffix-Eigenschaft angegeben werden. |
| [LastException](../../aspose.pdf.facades/pdffileeditor/lastexception) { get; } | Ruft die zuletzt aufgetretene Ausnahme ab. Kann verwendet werden, um die Fehlerursache zu überprüfen. |
| [MergeDuplicateLayers](../../aspose.pdf.facades/pdffileeditor/mergeduplicatelayers) { get; set; } | Optionale Inhalte von verketteten Dokumenten mit gleichen Namen werden im resultierenden Dokument zu einer Ebene zusammengeführt, wenn diese Eigenschaft wahr ist. Andernfalls werden Ebenen mit gleichen Namen als unterschiedliche Ebenen im resultierenden Dokument gespeichert. |
| [MergeDuplicateOutlines](../../aspose.pdf.facades/pdffileeditor/mergeduplicateoutlines) { get; set; } | Wenn wahr, werden doppelte Umrisse zusammengeführt. |
| [OptimizeSize](../../aspose.pdf.facades/pdffileeditor/optimizesize) { get; set; } | Holt oder setzt Optimierungs-Flag. Gleiche Ressourcenströme in der resultierenden Datei werden zu einem PDF-Objekt zusammengeführt, wenn dieses Flag gesetzt ist. Dies ermöglicht eine Verringerung der resultierenden Dateigröße, kann jedoch zu einer langsameren Ausführung und größeren Speicheranforderungen führen. Standardwert: false. |
| [OwnerPassword](../../aspose.pdf.facades/pdffileeditor/ownerpassword) { get; set; } | Legt das Passwort des Eigentümers fest, wenn die Quelleingabe-Pdf-Datei verschlüsselt ist. Diese Eigenschaft ist noch nicht implementiert. |
| [PreserveUserRights](../../aspose.pdf.facades/pdffileeditor/preserveuserrights) { get; set; } | Wenn wahr, werden die Benutzerrechte des ersten Dokuments auf das verkettete Dokument angewendet. Benutzerrechte aller anderen Dokumente werden ignoriert. |
| [RemoveSignatures](../../aspose.pdf.facades/pdffileeditor/removesignatures) { get; set; } | Wenn wahr, werden alle Signaturen aus Feldern entfernt (Felder bleiben erhalten); Andernfalls können Sie ungültige Signaturen erhalten. |
| [SaveOptions](../../aspose.pdf.facades/pdffileeditor/saveoptions) { get; set; } | Ruft Speicheroptionen ab oder legt sie fest, wenn das Ergebnis als HttpResponse gespeichert wird. Standardwert: PdfSaveOptions. |
| [UniqueSuffix](../../aspose.pdf.facades/pdffileeditor/uniquesuffix) { get; set; } | Format des Suffixes, das dem Feldnamen hinzugefügt wird, um ihn eindeutig zu machen, wenn Formulare verkettet werden. Diese Zeichenfolge muss eine Teilzeichenfolge %NUM% enthalten, die durch Zahlen ersetzt wird. Zum Beispiel, wenn UniqueSuffix = "ABC%NUM%", dann for Feld "fieldName" Namen sind: fieldNameABC1, fieldNameABC2, fieldNameABC3 etc. |
| [UseDiskBuffer](../../aspose.pdf.facades/pdffileeditor/usediskbuffer) { get; set; } | Wenn diese Option verwendet wird, wird das Zieldokument regelmäßig auf der Festplatte gespeichert und weitere Verkettungen werden als inkrementelle Aktualisierungen darauf angewendet. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddMargins](../../aspose.pdf.facades/pdffileeditor/addmargins#addmargins)(Stream, Stream, int[], double, double, double, double) | Ändert die Größe des Seiteninhalts und fügt bestimmte Ränder hinzu. Ränder werden in Standardraumeinheiten angegeben. |
| [AddMargins](../../aspose.pdf.facades/pdffileeditor/addmargins#addmargins_1)(string, string, int[], double, double, double, double) | Ändert die Größe des Seiteninhalts und fügt bestimmte Ränder hinzu. Ränder werden in Standardraumeinheiten angegeben. |
| [AddMarginsPct](../../aspose.pdf.facades/pdffileeditor/addmarginspct#addmarginspct)(Stream, Stream, int[], double, double, double, double) | Ändert die Größe des Seiteninhalts und fügt bestimmte Ränder hinzu. Ränder werden in Prozent der ursprünglichen Seitengröße angegeben. |
| [AddMarginsPct](../../aspose.pdf.facades/pdffileeditor/addmarginspct#addmarginspct_1)(string, string, int[], double, double, double, double) | Ändert die Größe des Seiteninhalts und fügt bestimmte Ränder hinzu. Ränder werden in Prozent der ursprünglichen Seitengröße angegeben. |
| [AddPageBreak](../../aspose.pdf.facades/pdffileeditor/addpagebreak#addpagebreak)(Document, Document, PageBreak[]) | Fügt Seitenumbrüche in Dokumentseiten ein. |
| [AddPageBreak](../../aspose.pdf.facades/pdffileeditor/addpagebreak#addpagebreak_1)(Stream, Stream, PageBreak[]) | Fügt Seitenumbrüche in Dokumentseiten ein. |
| [AddPageBreak](../../aspose.pdf.facades/pdffileeditor/addpagebreak#addpagebreak_2)(string, string, PageBreak[]) | Fügt Seitenumbrüche in Dokumentseiten ein. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append#append)(Stream, Stream, int, int, Stream) | Fügt Seiten, die aus portStream im Bereich von startPage bis endPage ausgewählt werden, in portStream am Ende von firstInputStream an. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append#append_2)(Stream, Stream[], int, int, HttpResponse) | Hängt Dokumente an das Quelldokument an und speichert das Ergebnis im Antwortobjekt. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append#append_1)(Stream, Stream[], int, int, Stream) | Hängt Seiten an, die aus einem Array von Dokumenten in portStreams ausgewählt werden. Das Ergebnisdokument enthält firstInputFile und alle portStreams-Dokumentseiten im Bereich startPage bis endPage. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append#append_3)(string, string, int, int, string) | Fügt Seiten, die aus portFile im Bereich von startPage bis endPage ausgewählt werden, in portFile an das Ende von firstInputFile an. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append#append_5)(string, string[], int, int, HttpResponse) | Hängt Dokumente an das Quelldokument an und speichert das Ergebnis im HttpResponse-Objekt. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append#append_4)(string, string[], int, int, string) | Hängt Seiten an, die aus portFiles-Dokumenten ausgewählt werden. Das Ergebnisdokument enthält firstInputFile- und alle portFiles-Dokumentseiten im Bereich startPage bis endPage. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate)(Document[], Document) | Verkettet Dokumente. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate_4)(Stream[], HttpResponse) | Verkettet Dateien und speichert Ergebnisse im HttpResponse-Objekt. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate_3)(Stream[], Stream) | Verkettet Dateien |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate_8)(string[], HttpResponse) | Verkettet Dateien und speichert Ergebnisse im HttpResposnse-Objekt. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate_7)(string[], string) | Verkettet Dateien zu einer Datei. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate_1)(Stream, Stream, Stream) | Verkettet zwei Dateien. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate_5)(string, string, string) | Verkettet zwei Dateien. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate_2)(Stream, Stream, Stream, Stream) | Fügt zwei Pdf-Dokumente zu einem neuen Pdf-Dokument mit abwechselnden Seiten zusammen und füllt die leeren Stellen mit leeren Seiten. Beispiel: Dokument1 hat 5 Seiten: p1, p2, p3, p4, p5. Dokument2 hat 3 Seiten: p1', p2', p3'. Das Zusammenführen der beiden PDF-Dokumente erzeugt das Ergebnisdokument mit den Seiten: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage . |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate_6)(string, string, string, string) | Fügt zwei Pdf-Dokumente zu einem neuen Pdf-Dokument mit abwechselnden Seiten zusammen und füllt die leeren Stellen mit leeren Seiten. Beispiel: Dokument1 hat 5 Seiten: p1, p2, p3, p4, p5. Dokument2 hat 3 Seiten: p1', p2', p3'. Das Zusammenführen der beiden PDF-Dokumente erzeugt das Ergebnisdokument mit den Seiten: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage . |
| [Delete](../../aspose.pdf.facades/pdffileeditor/delete#delete_1)(Stream, int[], HttpResponse) | Löscht bestimmte Seiten aus dem Dokument und speichert das Ergebnis im HttpResponse-Objekt. |
| [Delete](../../aspose.pdf.facades/pdffileeditor/delete#delete)(Stream, int[], Stream) | Löscht durch Nummerarray angegebene Seiten aus der Eingabedatei und speichert sie als neue PDF-Datei. |
| [Delete](../../aspose.pdf.facades/pdffileeditor/delete#delete_3)(string, int[], HttpResponse) | Löscht angegebene Seiten aus dem Dokument und speichert das Ergebnis im HttpResponse-Objekt. |
| [Delete](../../aspose.pdf.facades/pdffileeditor/delete#delete_2)(string, int[], string) | Löscht durch Nummerarray angegebene Seiten aus der Eingabedatei und speichert sie als neue PDF-Datei. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract#extract_2)(Stream, int[], HttpResponse) | Extrahiert die angegebenen Seiten aus der Quelldatei und speichert das Ergebnis im HttpResponse-Objekt. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract#extract_1)(Stream, int[], Stream) | Extrahiert Seiten, die durch ein Zahlenarray angegeben sind, und speichert sie als neue PDF-Datei. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract#extract_5)(string, int[], HttpResponse) | Extrahiert angegebene Seiten aus der Quelldatei und speichert das Ergebnis im HttpResponse-Objekt. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract#extract_4)(string, int[], string) | Extrahiert Seiten, die durch ein Zahlenarray angegeben sind, und speichert sie als neue PDF-Datei. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract#extract)(Stream, int, int, Stream) | Extrahiert Seiten aus der Eingabedatei und speichert sie als neue PDF-Datei. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract#extract_3)(string, int, int, string) | Extrahiert Seiten aus der Eingabedatei und speichert sie als neue PDF-Datei. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert#insert_2)(Stream, int, Stream, int[], HttpResponse) | Fügt ein Dokument in ein anderes Dokument ein und speichert das Ergebnis im Antwortobjekt. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert#insert_1)(Stream, int, Stream, int[], Stream) | Fügt Seiten aus einer anderen Datei in die PDF-Eingabedatei ein. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert#insert_5)(string, int, string, int[], HttpResponse) | Fügt den Inhalt der Datei in die Quelldatei ein und speichert das Ergebnis im HttpResponse-Objekt. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert#insert_4)(string, int, string, int[], string) | Fügt Seiten aus einer anderen Datei in die PDF-Eingabedatei ein. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert#insert)(Stream, int, Stream, int, int, Stream) | Fügt Seiten aus einer anderen Datei in die PDF-Eingabedatei ein. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert#insert_3)(string, int, string, int, int, string) | Fügt an einer Position Seiten aus einer anderen Datei in die Pdf-Datei ein. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_2)(Stream, Stream) | Erstellt eine Broschüre vom InputStream zum OutputStream. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_8)(string, string) | Erstellt eine Broschüre aus der Eingabedatei in die Ausgabedatei. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_1)(Stream, PageSize, HttpResponse) | Erstellt ein Booklet aus der Quelldatei und speichert das Ergebnis in HttpResponse. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_3)(Stream, Stream, PageSize) | Erstellt eine Broschüre aus dem Eingabestrom und speichert das Ergebnis im Ausgabestrom. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_7)(string, PageSize, HttpResponse) | Erstellt ein Booklet aus der Quelldatei und speichert das Ergebnis in HttpResponse-Objekten. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_9)(string, string, PageSize) | Erstellt eine Broschüre aus der Eingabedatei in die Ausgabedatei. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_5)(Stream, Stream, int[], int[]) | Erstellt ein benutzerdefiniertes Booklet vom firstInputStream bis zum outputStream. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_11)(string, string, int[], int[]) | Erstellt ein benutzerdefiniertes Booklet von der ersten Eingabedatei bis zur Ausgabedatei. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet)(Stream, PageSize, int[], int[], HttpResponse) | Broschüre aus PDF-Datei erstellen und in HttpResponse speichern. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_4)(Stream, Stream, PageSize, int[], int[]) | Erstellt ein Booklet vom firstInputStream bis zum outputStream. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_6)(string, PageSize, int[], int[], HttpResponse) | Erstellt ein Booklet aus der Quelldatei und speichert das Ergebnis in HttpResponse-Objekten. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_10)(string, string, PageSize, int[], int[]) | Erstellt ein benutzerdefiniertes Booklet von der ersten Eingabedatei bis zur Ausgabedatei. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_4)(Stream, Stream, Stream) | Erzeugt ein N-up-Dokument aus den beiden PDF-Eingabeströmen in outputStream. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_5)(Stream[], Stream, bool) | Erzeugt N-up-Dokumente aus den Multi-Input-PDF-Streams in OutputStream. Jede Seite von OutputStream enthält mehrere Seiten, die mit den Seiten in den Input-Streams derselben Seitennummer kombiniert werden. Die mehreren Seiten werden horizontal gestapelt , wenn isSidewise wahr ist, und vertikal gestapelt, wenn isSidewise falsch ist. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_10)(string, string, string) | Erstellt ein N-up-Dokument aus den beiden PDF-Eingabedateien in eine Ausgabedatei. Jede Seite der Ausgabedatei enthält zwei Seiten, eine Seite stammt aus der ersten Eingabedatei und eine andere aus der zweiten Eingabedatei. Die beiden Seiten werden horizontal gestapelt. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_11)(string[], string, bool) | Erstellt ein N-up-Dokument aus den PDF-Dateien mit mehreren Eingaben in eine Ausgabedatei. Jede Seite der Ausgabedatei enthält mehrere Seiten, die mit den Seiten in den Eingabedateien mit derselben Seitenzahl kombiniert werden. Die Multi-Seiten werden horizontal gestapelt, wenn isSidewise wahr ist, und vertikal gestapelt, wenn isSidewise falsch ist. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_1)(Stream, int, int, HttpResponse) | Erstellt ein Dokument mit mehreren Seiten und speichert das Ergebnis in HttpResponse. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_2)(Stream, Stream, int, int) | Erstellt ein N-up-Dokument aus dem Eingabestrom und speichert das Ergebnis im Ausgabestrom. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_7)(string, int, int, HttpResponse) | Erstellt ein Dokument mit mehreren Seiten und speichert das Ergebnis in HttpResponse. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_8)(string, string, int, int) | Erstellt ein N-up-Dokument aus der ersten Eingabedatei in die Ausgabedatei. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup)(Stream, int, int, PageSize, HttpResponse) | Erstellt ein N-up-Dokument und speichert das Ergebnis im HttpResponse-Objekt. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_3)(Stream, Stream, int, int, PageSize) | Erstellt ein N-up-Dokument vom ersten Eingabestrom zum Ausgabestrom. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_6)(string, int, int, PageSize, HttpResponse) | Erstellt ein N-up-Dokument und speichert das Ergebnis im HttpResponse-Objekt. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_9)(string, string, int, int, PageSize) | Erstellt ein N-up-Dokument aus der Eingabedatei in die Ausgabedatei. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents#resizecontents_6)(Document, ContentsResizeParameters) | Passt Seiten des Dokuments an. Leere Ränder werden um die verkleinerte Seite herum hinzugefügt. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents#resizecontents_7)(Document, int[], ContentsResizeParameters) | Passt Seiten des Dokuments an. Leere Ränder werden um die verkleinerte Seite herum hinzugefügt. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents#resizecontents)(Stream, int[], ContentsResizeParameters, HttpResponse) | Ändert die Seiteninhalte im Dokument. Wenn die Seite verkleinert wird, werden um die Seite herum leere Ränder hinzugefügt. Das Ergebnis wird im HttpResponse-Objekt gespeichert. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents#resizecontents_1)(Stream, Stream, int[], ContentsResizeParameters) | Ändert die Seiteninhalte des Dokuments. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents#resizecontents_3)(string, int[], ContentsResizeParameters, HttpResponse) | Ändert die Seiteninhalte im Dokument. Wenn die Seite verkleinert wird, werden um die Seite herum leere Ränder hinzugefügt. Das Ergebnis wird im HttpResponse-Objekt gespeichert. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents#resizecontents_4)(string, string, int[], ContentsResizeParameters) | Ändert die Seiteninhalte im Dokument. Wenn die Seite verkleinert wird, werden um die Seite herum leere Ränder hinzugefügt. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents#resizecontents_2)(Stream, Stream, int[], double, double) | Ändert die Größe des Inhalts von Dokumentseiten. Verkleinert den Inhalt der Seite und fügt Ränder hinzu. Neue Größe des Inhalts wird in Standard-Leerzeicheneinheiten angegeben. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents#resizecontents_5)(string, string, int[], double, double) | Ändert die Größe des Inhalts von Dokumentseiten. Verkleinert den Inhalt der Seite und fügt Ränder hinzu. Neue Größe des Inhalts wird in Standard-Leerzeicheneinheiten angegeben. |
| [ResizeContentsPct](../../aspose.pdf.facades/pdffileeditor/resizecontentspct#resizecontentspct)(Stream, Stream, int[], double, double) | Ändert die Größe des Inhalts von Dokumentseiten. Verkleinert den Inhalt der Seite und fügt Ränder hinzu. Neue Inhaltsgröße wird in Prozent angegeben. |
| [ResizeContentsPct](../../aspose.pdf.facades/pdffileeditor/resizecontentspct#resizecontentspct_1)(string, string, int[], double, double) | Ändert die Größe des Inhalts von Dokumentseiten. Verkleinert den Inhalt der Seite und fügt Ränder hinzu. Neue Inhaltsgröße wird in Prozent angegeben. |
| [SplitFromFirst](../../aspose.pdf.facades/pdffileeditor/splitfromfirst#splitfromfirst_1)(Stream, int, HttpResponse) | Teilt das Dokument vom Anfang bis zum angegebenen Ort auf und speichert das Ergebnis im HttpResponse-Objekt. |
| [SplitFromFirst](../../aspose.pdf.facades/pdffileeditor/splitfromfirst#splitfromfirst)(Stream, int, Stream) | Teilt vom Anfang bis zur angegebenen Position und speichert den vorderen Teil im Ausgabestream. |
| [SplitFromFirst](../../aspose.pdf.facades/pdffileeditor/splitfromfirst#splitfromfirst_3)(string, int, HttpResponse) | Teilt das Dokument von der ersten Seite bis zur Position und speichert das Ergebnis in HttpResponse-Objekten. |
| [SplitFromFirst](../../aspose.pdf.facades/pdffileeditor/splitfromfirst#splitfromfirst_2)(string, int, string) | Teilt die PDF-Datei von der ersten Seite bis zum angegebenen Ort und speichert den vorderen Teil als neue Datei. |
| [SplitToBulks](../../aspose.pdf.facades/pdffileeditor/splittobulks#splittobulks)(Stream, int[][]) | Teilt die Pdf-Datei in mehrere Dokumente auf. Die Dokumente können einseitig oder mehrseitig sein. |
| [SplitToBulks](../../aspose.pdf.facades/pdffileeditor/splittobulks#splittobulks_1)(string, int[][]) | Teilt die Pdf-Datei in mehrere Dokumente auf. Die Dokumente können einseitig oder mehrseitig sein. |
| [SplitToEnd](../../aspose.pdf.facades/pdffileeditor/splittoend#splittoend_1)(Stream, int, HttpResponse) | Teilt vom angegebenen Ort und speichert den hinteren Teil im HttpResponse-Objekt. |
| [SplitToEnd](../../aspose.pdf.facades/pdffileeditor/splittoend#splittoend)(Stream, int, Stream) | Trennt den angegebenen Speicherort und speichert den hinteren Teil als neuen Dateistream. |
| [SplitToEnd](../../aspose.pdf.facades/pdffileeditor/splittoend#splittoend_3)(string, int, HttpResponse) | Teilt vom angegebenen Ort und speichert den hinteren Teil im HttpResponse-Objekt. |
| [SplitToEnd](../../aspose.pdf.facades/pdffileeditor/splittoend#splittoend_2)(string, int, string) | Trennt den Speicherort und speichert den hinteren Teil als neue Datei. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages#splittopages)(Stream) | Teilt die Pdf-Datei in einseitige Dokumente auf. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages#splittopages_1)(string) | Teilt die PDF-Datei in einseitige Dokumente auf. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages#splittopages_2)(Stream, string) | Teilt die PDF-Datei in einseitige Dokumente auf und speichert sie im angegebenen Pfad. Der Pfad wird durch den Feldnamen template. angegeben. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages#splittopages_3)(string, string) | Teilt die PDF-Datei in einseitige Dokumente auf und speichert sie im angegebenen Pfad. Der Pfad wird durch den Feldnamen template. angegeben. |
| [TryAppend](../../aspose.pdf.facades/pdffileeditor/tryappend#tryappend_1)(Stream, Stream[], int, int, HttpResponse) | Hängt Dokumente an das Quelldokument an und speichert das Ergebnis im Antwortobjekt. |
| [TryAppend](../../aspose.pdf.facades/pdffileeditor/tryappend#tryappend)(Stream, Stream[], int, int, Stream) | Hängt Seiten an, die aus einem Array von Dokumenten in portStreams ausgewählt werden. Das Ergebnisdokument enthält firstInputFile und alle portStreams-Dokumentseiten im Bereich startPage bis endPage. |
| [TryAppend](../../aspose.pdf.facades/pdffileeditor/tryappend#tryappend_3)(string, string[], int, int, HttpResponse) | Hängt Dokumente an das Quelldokument an und speichert das Ergebnis im HttpResponse-Objekt. |
| [TryAppend](../../aspose.pdf.facades/pdffileeditor/tryappend#tryappend_2)(string, string[], int, int, string) | Hängt Seiten an, die aus portFiles-Dokumenten ausgewählt werden. Das Ergebnisdokument enthält firstInputFile- und alle portFiles-Dokumentseiten im Bereich startPage bis endPage. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate#tryconcatenate)(Document[], Document) | Verkettet Dokumente. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate#tryconcatenate_3)(Stream[], HttpResponse) | Verkettet Dateien und speichert Ergebnisse im HttpResponse-Objekt. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate#tryconcatenate_2)(Stream[], Stream) | Verkettet Dateien |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate#tryconcatenate_7)(string[], HttpResponse) | Verkettet Dateien und speichert Ergebnisse im HttpResposnse-Objekt. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate#tryconcatenate_6)(string[], string) | Verkettet Dateien zu einer Datei. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate#tryconcatenate_4)(string, string, string) | Verkettet zwei Dateien. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate#tryconcatenate_1)(Stream, Stream, Stream, Stream) | Fügt zwei Pdf-Dokumente zu einem neuen Pdf-Dokument mit abwechselnden Seiten zusammen und füllt die leeren Stellen mit leeren Seiten. Beispiel: Dokument1 hat 5 Seiten: p1, p2, p3, p4, p5. Dokument2 hat 3 Seiten: p1', p2', p3'. Das Zusammenführen der beiden PDF-Dokumente erzeugt das Ergebnisdokument mit den Seiten: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage . |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate#tryconcatenate_5)(string, string, string, string) | Fügt zwei Pdf-Dokumente zu einem neuen Pdf-Dokument mit abwechselnden Seiten zusammen und füllt die leeren Stellen mit leeren Seiten. Beispiel: Dokument1 hat 5 Seiten: p1, p2, p3, p4, p5. Dokument2 hat 3 Seiten: p1', p2', p3'. Das Zusammenführen der beiden PDF-Dokumente erzeugt das Ergebnisdokument mit den Seiten: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage . |
| [TryDelete](../../aspose.pdf.facades/pdffileeditor/trydelete#trydelete_1)(Stream, int[], HttpResponse) | Löscht bestimmte Seiten aus dem Dokument und speichert das Ergebnis im HttpResponse-Objekt. |
| [TryDelete](../../aspose.pdf.facades/pdffileeditor/trydelete#trydelete)(Stream, int[], Stream) | Löscht durch Nummerarray angegebene Seiten aus der Eingabedatei und speichert sie als neue PDF-Datei. |
| [TryDelete](../../aspose.pdf.facades/pdffileeditor/trydelete#trydelete_3)(string, int[], HttpResponse) | Löscht angegebene Seiten aus dem Dokument und speichert das Ergebnis im HttpResponse-Objekt. |
| [TryDelete](../../aspose.pdf.facades/pdffileeditor/trydelete#trydelete_2)(string, int[], string) | Löscht durch Nummerarray angegebene Seiten aus der Eingabedatei und speichert sie als neue PDF-Datei. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract#tryextract_1)(Stream, int[], HttpResponse) | Extrahiert die angegebenen Seiten aus der Quelldatei und speichert das Ergebnis im HttpResponse-Objekt. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract#tryextract)(Stream, int[], Stream) | Extrahiert Seiten, die durch ein Zahlenarray angegeben sind, und speichert sie als neue PDF-Datei. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract#tryextract_4)(string, int[], HttpResponse) | Extrahiert angegebene Seiten aus der Quelldatei und speichert das Ergebnis im HttpResponse-Objekt. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract#tryextract_3)(string, int[], string) | Extrahiert Seiten, die durch ein Zahlenarray angegeben sind, und speichert sie als neue PDF-Datei. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract#tryextract_2)(string, int, int, string) | Extrahiert Seiten aus der Eingabedatei und speichert sie als neue PDF-Datei. |
| [TryInsert](../../aspose.pdf.facades/pdffileeditor/tryinsert#tryinsert_1)(Stream, int, Stream, int[], HttpResponse) | Fügt ein Dokument in ein anderes Dokument ein und speichert das Ergebnis im Antwortobjekt. |
| [TryInsert](../../aspose.pdf.facades/pdffileeditor/tryinsert#tryinsert)(Stream, int, Stream, int[], Stream) | Fügt Seiten aus einer anderen Datei in die PDF-Eingabedatei ein. |
| [TryInsert](../../aspose.pdf.facades/pdffileeditor/tryinsert#tryinsert_3)(string, int, string, int[], HttpResponse) | Fügt den Inhalt der Datei in die Quelldatei ein und speichert das Ergebnis im HttpResponse-Objekt. |
| [TryInsert](../../aspose.pdf.facades/pdffileeditor/tryinsert#tryinsert_2)(string, int, string, int[], string) | Fügt Seiten aus einer anderen Datei in die PDF-Eingabedatei ein. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_2)(Stream, Stream) | Erstellt eine Broschüre vom InputStream zum OutputStream. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_8)(string, string) | Erstellt eine Broschüre aus der Eingabedatei in die Ausgabedatei. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_1)(Stream, PageSize, HttpResponse) | Erstellt ein Booklet aus der Quelldatei und speichert das Ergebnis in HttpResponse. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_3)(Stream, Stream, PageSize) | Erstellt eine Broschüre aus dem Eingabestrom und speichert das Ergebnis im Ausgabestrom. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_7)(string, PageSize, HttpResponse) | Erstellt ein Booklet aus der Quelldatei und speichert das Ergebnis in HttpResponse-Objekten. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_9)(string, string, PageSize) | Erstellt eine Broschüre aus der Eingabedatei in die Ausgabedatei. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_5)(Stream, Stream, int[], int[]) | Erstellt ein benutzerdefiniertes Booklet vom firstInputStream bis zum outputStream. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_11)(string, string, int[], int[]) | Erstellt ein benutzerdefiniertes Booklet von der ersten Eingabedatei bis zur Ausgabedatei. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet)(Stream, PageSize, int[], int[], HttpResponse) | Broschüre aus PDF-Datei erstellen und in HttpResponse speichern. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_4)(Stream, Stream, PageSize, int[], int[]) | Erstellt ein Booklet vom firstInputStream bis zum outputStream. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_6)(string, PageSize, int[], int[], HttpResponse) | Erstellt ein Booklet aus der Quelldatei und speichert das Ergebnis in HttpResponse-Objekten. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_10)(string, string, PageSize, int[], int[]) | Erstellt ein benutzerdefiniertes Booklet von der ersten Eingabedatei bis zur Ausgabedatei. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_4)(Stream, Stream, Stream) | Erzeugt ein N-up-Dokument aus den beiden PDF-Eingabeströmen in outputStream. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_5)(Stream[], Stream, bool) | Erzeugt N-up-Dokumente aus den Multi-Input-PDF-Streams in OutputStream. Jede Seite von OutputStream enthält mehrere Seiten, die mit den Seiten in den Input-Streams derselben Seitennummer kombiniert werden. Die mehreren Seiten werden horizontal gestapelt , wenn isSidewise wahr ist, und vertikal gestapelt, wenn isSidewise falsch ist. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_10)(string, string, string) | Erstellt ein N-up-Dokument aus den beiden PDF-Eingabedateien in eine Ausgabedatei. Jede Seite der Ausgabedatei enthält zwei Seiten, eine Seite stammt aus der ersten Eingabedatei und eine andere aus der zweiten Eingabedatei. Die beiden Seiten werden horizontal gestapelt. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_11)(string[], string, bool) | Erstellt ein N-up-Dokument aus den PDF-Dateien mit mehreren Eingaben in eine Ausgabedatei. Jede Seite der Ausgabedatei enthält mehrere Seiten, die mit den Seiten in den Eingabedateien mit derselben Seitenzahl kombiniert werden. Die Multi-Seiten werden horizontal gestapelt, wenn isSidewise wahr ist, und vertikal gestapelt, wenn isSidewise falsch ist. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_1)(Stream, int, int, HttpResponse) | Erstellt ein Dokument mit mehreren Seiten und speichert das Ergebnis in HttpResponse. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_2)(Stream, Stream, int, int) | Erstellt ein N-up-Dokument aus dem Eingabestrom und speichert das Ergebnis im Ausgabestrom. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_7)(string, int, int, HttpResponse) | Erstellt ein Dokument mit mehreren Seiten und speichert das Ergebnis in HttpResponse. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_8)(string, string, int, int) | Erstellt ein N-up-Dokument aus der ersten Eingabedatei in die Ausgabedatei. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup)(Stream, int, int, PageSize, HttpResponse) | Erstellt ein N-up-Dokument und speichert das Ergebnis im HttpResponse-Objekt. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_3)(Stream, Stream, int, int, PageSize) | Erstellt ein N-up-Dokument vom ersten Eingabestrom zum Ausgabestrom. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_6)(string, int, int, PageSize, HttpResponse) | Erstellt ein N-up-Dokument und speichert das Ergebnis im HttpResponse-Objekt. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_9)(string, string, int, int, PageSize) | Erstellt ein N-up-Dokument aus der Eingabedatei in die Ausgabedatei. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents#tryresizecontents)(Stream, int[], ContentsResizeParameters, HttpResponse) | Ändert die Seiteninhalte im Dokument. Wenn die Seite verkleinert wird, werden um die Seite herum leere Ränder hinzugefügt. Das Ergebnis wird im HttpResponse-Objekt gespeichert. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents#tryresizecontents_1)(Stream, Stream, int[], ContentsResizeParameters) | Ändert die Seiteninhalte des Dokuments. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents#tryresizecontents_3)(string, int[], ContentsResizeParameters, HttpResponse) | Ändert die Seiteninhalte im Dokument. Wenn die Seite verkleinert wird, werden um die Seite herum leere Ränder hinzugefügt. Das Ergebnis wird im HttpResponse-Objekt gespeichert. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents#tryresizecontents_4)(string, string, int[], ContentsResizeParameters) | Ändert die Seiteninhalte im Dokument. Wenn die Seite verkleinert wird, werden um die Seite herum leere Ränder hinzugefügt. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents#tryresizecontents_2)(Stream, Stream, int[], double, double) | Ändert die Größe des Inhalts von Dokumentseiten. Verkleinert den Inhalt der Seite und fügt Ränder hinzu. Neue Größe des Inhalts wird in Standard-Leerzeicheneinheiten angegeben. |
| [TrySplitFromFirst](../../aspose.pdf.facades/pdffileeditor/trysplitfromfirst#trysplitfromfirst_1)(Stream, int, HttpResponse) | Teilt das Dokument vom Anfang bis zum angegebenen Ort auf und speichert das Ergebnis im HttpResponse-Objekt. |
| [TrySplitFromFirst](../../aspose.pdf.facades/pdffileeditor/trysplitfromfirst#trysplitfromfirst)(Stream, int, Stream) | Teilt vom Anfang bis zur angegebenen Position und speichert den vorderen Teil im Ausgabestream. |
| [TrySplitFromFirst](../../aspose.pdf.facades/pdffileeditor/trysplitfromfirst#trysplitfromfirst_3)(string, int, HttpResponse) | Teilt das Dokument von der ersten Seite bis zur Position und speichert das Ergebnis in HttpResponse-Objekten. |
| [TrySplitFromFirst](../../aspose.pdf.facades/pdffileeditor/trysplitfromfirst#trysplitfromfirst_2)(string, int, string) | Teilt die PDF-Datei von der ersten Seite bis zum angegebenen Ort und speichert den vorderen Teil als neue Datei. |
| [TrySplitToEnd](../../aspose.pdf.facades/pdffileeditor/trysplittoend#trysplittoend_1)(Stream, int, HttpResponse) | Teilt vom angegebenen Ort und speichert den hinteren Teil im HttpResponse-Objekt. |
| [TrySplitToEnd](../../aspose.pdf.facades/pdffileeditor/trysplittoend#trysplittoend)(Stream, int, Stream) | Trennt den angegebenen Speicherort und speichert den hinteren Teil als neuen Dateistream. |
| [TrySplitToEnd](../../aspose.pdf.facades/pdffileeditor/trysplittoend#trysplittoend_3)(string, int, HttpResponse) | Teilt vom angegebenen Ort und speichert den hinteren Teil im HttpResponse-Objekt. |
| [TrySplitToEnd](../../aspose.pdf.facades/pdffileeditor/trysplittoend#trysplittoend_2)(string, int, string) | Trennt den Speicherort und speichert den hinteren Teil als neue Datei. |

## Andere Mitglieder

| Name | Beschreibung |
| --- | --- |
| enum [ConcatenateCorruptedFileAction](pdffileeditor.concatenatecorruptedfileaction) | Aktion, die ausgeführt wurde, als eine beschädigte Datei im Verkettungsprozess gefunden wurde. |
| class [ContentsResizeParameters](pdffileeditor.contentsresizeparameters) | Klasse zum Festlegen von Parametern zur Größenänderung von Seiten. Ermöglicht das Setzen der folgenden Parameter: Größe der Ergebnisseite (Breite, Höhe) in Standard-Platzeinheiten oder in Prozent der ursprünglichen Seitengröße; Linker, oberer, unterer und rechter Rand in Standardabstandseinheiten oder in Prozent der anfänglichen Seitengröße; Einige Werte können für die automatische Berechnung null bleiben. Diese Werte werden aus dem Rest der Seitengröße nach der Berechnung explizit angegebener Werte berechnet. Beispiel: Wenn die Seitenbreite = 100 und die neue Seitenbreite 60 Einheiten angegeben sind, dann werden linke und rechte Ränder automatisch berechnet: (100 - 60) / 2 = 15. Diese Klasse wird in der ResizeContents-Methode verwendet. |
| class [ContentsResizeValue](pdffileeditor.contentsresizevalue) | Wert des Rands oder der Inhaltsgröße, angegeben in Prozent der Standard-Leerzeicheneinheiten. Diese Klasse wird in ContentsResizeParameters verwendet. |
| class [CorruptedItem](pdffileeditor.corrupteditem) | Klasse, die Informationen über beschädigte Dateien zum Zeitpunkt der Verkettung bereitstellt. |
| class [PageBreak](pdffileeditor.pagebreak) | Daten der Seitenumbruchposition. |

### Siehe auch

* namensraum [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* Montage [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
