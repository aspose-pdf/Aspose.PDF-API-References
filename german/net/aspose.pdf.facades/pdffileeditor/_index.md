---
title: Class PdfFileEditor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfFileEditor-Klasse. Führt Operationen mit PDF-Dateien durch, einschließlich Zusammenführen, Aufteilen, Seiten extrahieren, Heftchen erstellen usw.
type: docs
weight: 4460
url: /de/net/aspose.pdf.facades/pdffileeditor/
---
## PdfFileEditor-Klasse

Implementiert Operationen mit PDF-Dateien: Zusammenführen, Aufteilen, Seiten extrahieren, Broschüren erstellen usw.

```csharp
public sealed class PdfFileEditor
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [PdfFileEditor](pdffileeditor/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CloseConcatenatedStreams](../../aspose.pdf.facades/pdffileeditor/closeconcatenatedstreams/) { get; set; } | Wenn auf true gesetzt, werden die Streams nach der Operation geschlossen. |
| [ConcatenationPacketSize](../../aspose.pdf.facades/pdffileeditor/concatenationpacketsize/) { get; set; } | Anzahl der Dokumente, die vor einem neuen inkrementellen Update während der Zusammenführung zusammengeführt wurden, wenn UseDiskBuffer auf true gesetzt ist. |
| [ConversionLog](../../aspose.pdf.facades/pdffileeditor/conversionlog/) { get; } | Erhält das Protokoll des Konvertierungsprozesses. |
| [ConvertTo](../../aspose.pdf.facades/pdffileeditor/convertto/) { set; } | Setzt das PDF-Dateiformat. Die Ergebnisdatei wird im angegebenen Dateiformat gespeichert. Wenn diese Eigenschaft nicht angegeben ist, wird die Datei im Standard-PDF-Format ohne Konvertierung gespeichert. |
| [CopyLogicalStructure](../../aspose.pdf.facades/pdffileeditor/copylogicalstructure/) { get; set; } | Wenn true, wird die logische Struktur der Datei beim Zusammenführen kopiert. |
| [CopyOutlines](../../aspose.pdf.facades/pdffileeditor/copyoutlines/) { get; set; } | Wenn true, werden die Gliederungen kopiert. |
| [CorruptedFileAction](../../aspose.pdf.facades/pdffileeditor/corruptedfileaction/) { get; set; } | Diese Eigenschaft definiert das Verhalten, wenn der Zusammenführungsprozess auf eine beschädigte Datei trifft. Mögliche Werte sind: StopWithError und ConcatenateIgnoringCorrupted. |
| [CorruptedItems](../../aspose.pdf.facades/pdffileeditor/corrupteditems/) { get; } | Array der aufgetretenen Probleme, als die Zusammenführung durchgeführt wurde. Für jedes beschädigte Dokument, das an die Concatenate()-Funktion übergeben wurde, wird ein neuer CorruptedItem-Eintrag erstellt. Diese Eigenschaft kann nur verwendet werden, wenn CorruptedFileAction auf ConcatenateIgnoringCorrupted gesetzt ist. |
| [IncrementalUpdates](../../aspose.pdf.facades/pdffileeditor/incrementalupdates/) { get; set; } | Wenn true, werden inkrementelle Updates während der Zusammenführung durchgeführt. |
| [KeepActions](../../aspose.pdf.facades/pdffileeditor/keepactions/) { get; set; } | Wenn true, werden die Aktionen aus den Quelldokumenten kopiert. Standardwert: true. |
| [KeepFieldsUnique](../../aspose.pdf.facades/pdffileeditor/keepfieldsunique/) { get; set; } | Wenn true, werden die Feldnamen eindeutig gemacht, wenn Formulare zusammengeführt werden. Suffixe werden zu den Feldnamen hinzugefügt, das Suffixmuster kann in der Eigenschaft UniqueSuffix angegeben werden. |
| [LastException](../../aspose.pdf.facades/pdffileeditor/lastexception/) { get; } | Erhält die zuletzt aufgetretene Ausnahme. Kann verwendet werden, um den Grund für das Scheitern zu überprüfen. |
| [MergeDuplicateLayers](../../aspose.pdf.facades/pdffileeditor/mergeduplicatelayers/) { get; set; } | Optionale Inhalte von zusammengeführten Dokumenten mit gleichen Namen werden in einer Schicht im resultierenden Dokument zusammengeführt, wenn diese Eigenschaft true ist. Andernfalls werden Schichten mit gleichen Namen als unterschiedliche Schichten im resultierenden Dokument gespeichert. |
| [MergeDuplicateOutlines](../../aspose.pdf.facades/pdffileeditor/mergeduplicateoutlines/) { get; set; } | Wenn true, werden doppelte Gliederungen zusammengeführt. |
| [OptimizeSize](../../aspose.pdf.facades/pdffileeditor/optimizesize/) { get; set; } | Erhält oder setzt das Optimierungsflag. Gleiche Ressourcenströme im resultierenden Dokument werden in ein PDF-Objekt zusammengeführt, wenn dieses Flag gesetzt ist. Dies ermöglicht eine Verringerung der Dateigröße, kann jedoch zu einer langsameren Ausführung und höheren Speicheranforderungen führen. Standardwert: false. |
| [OwnerPassword](../../aspose.pdf.facades/pdffileeditor/ownerpassword/) { get; set; } | Setzt das Passwort des Eigentümers, wenn die Quelldatei Pdf verschlüsselt ist. Diese Eigenschaft ist noch nicht implementiert. |
| [PreserveUserRights](../../aspose.pdf.facades/pdffileeditor/preserveuserrights/) { get; set; } | Wenn true, werden die Benutzerrechte des ersten Dokuments auf das zusammengeführte Dokument angewendet. Die Benutzerrechte aller anderen Dokumente werden ignoriert. |
| [RemoveSignatures](../../aspose.pdf.facades/pdffileeditor/removesignatures/) { get; set; } | Wenn true, werden alle Signaturen aus den Feldern entfernt (die Felder bleiben); andernfalls können ungültige Signaturen auftreten. |
| [UniqueSuffix](../../aspose.pdf.facades/pdffileeditor/uniquesuffix/) { get; set; } | Format des Suffixes, das zum Feldnamen hinzugefügt wird, um ihn eindeutig zu machen, wenn Formulare zusammengeführt werden. Dieser String muss den Substring %NUM% enthalten, der durch Zahlen ersetzt wird. Zum Beispiel, wenn UniqueSuffix = "ABC%NUM%" dann werden für das Feld "fieldName" die Namen sein: fieldNameABC1, fieldNameABC2, fieldNameABC3 usw. |
| [UseDiskBuffer](../../aspose.pdf.facades/pdffileeditor/usediskbuffer/) { get; set; } | Wenn diese Option verwendet wird, wird das Ziel-Dokument regelmäßig auf der Festplatte gespeichert und die weitere Zusammenführung wird als inkrementelle Updates angewendet. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddMargins](../../aspose.pdf.facades/pdffileeditor/addmargins/#addmargins)(Stream, Stream, int[], double, double, double, double) | Ändert die Größe des Seiteninhalts und fügt die angegebenen Ränder hinzu. Die Ränder sind in den Standardraum-Einheiten angegeben. |
| [AddMargins](../../aspose.pdf.facades/pdffileeditor/addmargins/#addmargins_1)(string, string, int[], double, double, double, double) | Ändert die Größe des Seiteninhalts und fügt die angegebenen Ränder hinzu. Die Ränder sind in den Standardraum-Einheiten angegeben. |
| [AddMarginsPct](../../aspose.pdf.facades/pdffileeditor/addmarginspct/#addmarginspct)(Stream, Stream, int[], double, double, double, double) | Ändert die Größe des Seiteninhalts und fügt die angegebenen Ränder hinzu. Die Ränder sind in Prozent der ursprünglichen Seitengröße angegeben. |
| [AddMarginsPct](../../aspose.pdf.facades/pdffileeditor/addmarginspct/#addmarginspct_1)(string, string, int[], double, double, double, double) | Ändert die Größe des Seiteninhalts und fügt die angegebenen Ränder hinzu. Die Ränder sind in Prozent der ursprünglichen Seitengröße angegeben. |
| [AddPageBreak](../../aspose.pdf.facades/pdffileeditor/addpagebreak/#addpagebreak)(Document, Document, PageBreak[]) | Fügt Seitenumbrüche in die Dokumentseiten ein. |
| [AddPageBreak](../../aspose.pdf.facades/pdffileeditor/addpagebreak/#addpagebreak_1)(Stream, Stream, PageBreak[]) | Fügt Seitenumbrüche in die Dokumentseiten ein. |
| [AddPageBreak](../../aspose.pdf.facades/pdffileeditor/addpagebreak/#addpagebreak_2)(string, string, PageBreak[]) | Fügt Seitenumbrüche in die Dokumentseiten ein. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append/#append)(Stream, Stream, int, int, Stream) | Fügt Seiten, die aus dem portStream im Bereich von startPage bis endPage ausgewählt wurden, am Ende des firstInputStream hinzu. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append/#append_1)(Stream, Stream[], int, int, Stream) | Fügt Seiten hinzu, die aus einem Array von Dokumenten in portStreams ausgewählt wurden. Das Ergebnisdokument enthält firstInputFile und alle Seiten der portStreams-Dokumente im Bereich von startPage bis endPage. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append/#append_2)(string, string, int, int, string) | Fügt Seiten, die aus portFile im Bereich von startPage bis endPage ausgewählt wurden, am Ende von firstInputFile hinzu. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append/#append_3)(string, string[], int, int, string) | Fügt Seiten, die aus portFiles-Dokumenten ausgewählt wurden, hinzu. Das Ergebnisdokument enthält firstInputFile und alle Seiten der portFiles-Dokumente im Bereich von startPage bis endPage. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate)(Document[], Document) | Verbindet Dokumente. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_3)(Stream[], Stream) | Verbindet Dateien. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_6)(string[], string) | Verbindet Dateien in eine Datei. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_1)(Stream, Stream, Stream) | Verbindet zwei Dateien. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_4)(string, string, string) | Verbindet zwei Dateien. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_2)(Stream, Stream, Stream, Stream) | Fügt zwei PDF-Dokumente in ein neues PDF-Dokument mit Seiten in alternierenden Weisen zusammen und füllt die leeren Stellen mit leeren Seiten. z.B.: Dokument1 hat 5 Seiten: p1, p2, p3, p4, p5. Dokument2 hat 3 Seiten: p1', p2', p3'. Das Zusammenführen der beiden PDF-Dokumente ergibt das Ergebnisdokument mit Seiten: p1, p1', p2, p2', p3, p3', p4, leere Seite, p5, leere Seite. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_5)(string, string, string, string) | Fügt zwei PDF-Dokumente in ein neues PDF-Dokument mit Seiten in alternierenden Weisen zusammen und füllt die leeren Stellen mit leeren Seiten. z.B.: Dokument1 hat 5 Seiten: p1, p2, p3, p4, p5. Dokument2 hat 3 Seiten: p1', p2', p3'. Das Zusammenführen der beiden PDF-Dokumente ergibt das Ergebnisdokument mit Seiten: p1, p1', p2, p2', p3, p3', p4, leere Seite, p5, leere Seite. |
| [Delete](../../aspose.pdf.facades/pdffileeditor/delete/#delete)(Stream, int[], Stream) | Löscht Seiten, die durch ein Zahlenarray aus der Eingabedatei angegeben sind, und speichert sie als neue PDF-Datei. |
| [Delete](../../aspose.pdf.facades/pdffileeditor/delete/#delete_1)(string, int[], string) | Löscht Seiten, die durch ein Zahlenarray aus der Eingabedatei angegeben sind, und speichert sie als neue PDF-Datei. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract/#extract_1)(Stream, int[], Stream) | Extrahiert Seiten, die durch ein Zahlenarray angegeben sind, und speichert sie als neue PDF-Datei. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract/#extract_3)(string, int[], string) | Extrahiert Seiten, die durch ein Zahlenarray angegeben sind, und speichert sie als neue PDF-Datei. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract/#extract)(Stream, int, int, Stream) | Extrahiert Seiten aus der Eingabedatei und speichert sie als neue PDF-Datei. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract/#extract_2)(string, int, int, string) | Extrahiert Seiten aus der Eingabedatei und speichert sie als neue PDF-Datei. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert/#insert_1)(Stream, int, Stream, int[], Stream) | Fügt Seiten aus einer anderen Datei in die Eingabe-PDF-Datei ein. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert/#insert_3)(string, int, string, int[], string) | Fügt Seiten aus einer anderen Datei in die Eingabe-PDF-Datei ein. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert/#insert)(Stream, int, Stream, int, int, Stream) | Fügt Seiten aus einer anderen Datei in die Eingabe-PDF-Datei ein. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert/#insert_2)(string, int, string, int, int, string) | Fügt Seiten aus einer anderen Datei an einer Position in die PDF-Datei ein. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet)(Stream, Stream) | Erstellt eine Broschüre aus dem InputStream in den outputStream. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_4)(string, string) | Erstellt eine Broschüre aus der Eingabedatei in die Ausgabedatei. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_1)(Stream, Stream, PageSize) | Erstellt eine Broschüre aus dem Eingabestream und speichert das Ergebnis im Ausgabestream. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_5)(string, string, PageSize) | Erstellt eine Broschüre aus der Eingabedatei in die Ausgabedatei. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_3)(Stream, Stream, int[], int[]) | Erstellt eine benutzerdefinierte Broschüre aus dem firstInputStream in den outputStream. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_7)(string, string, int[], int[]) | Erstellt eine benutzerdefinierte Broschüre aus der firstInputFile in die outputFile. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_2)(Stream, Stream, PageSize, int[], int[]) | Erstellt eine Broschüre aus dem firstInputStream in den outputStream. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_6)(string, string, PageSize, int[], int[]) | Erstellt eine benutzerdefinierte Broschüre aus der firstInputFile in die outputFile. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_2)(Stream, Stream, Stream) | Erstellt ein N-Up-Dokument aus den beiden Eingabe-PDF-Streams in den outputStream. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_3)(Stream[], Stream, bool) | Erstellt ein N-Up-Dokument aus den mehreren Eingabe-PDF-Streams in den outputStream. Jede Seite des outputStream enthält mehrere Seiten, die eine Kombination aus Seiten in den Eingabeströmen mit derselben Seitennummer sind. Die Mehrfachseiten werden horizontal gestapelt, wenn isSidewise true ist, und vertikal gestapelt, wenn isSidewise false ist. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_6)(string, string, string) | Erstellt ein N-Up-Dokument aus den beiden Eingabe-PDF-Dateien in die outputFile. Jede Seite der outputFile enthält zwei Seiten, eine Seite stammt aus der ersten Eingabedatei und die andere aus der zweiten Eingabedatei. Die beiden Seiten sind horizontal gestapelt. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_7)(string[], string, bool) | Erstellt ein N-Up-Dokument aus den mehreren Eingabe-PDF-Dateien in die outputFile. Jede Seite der outputFile enthält mehrere Seiten, die eine Kombination aus Seiten in den Eingabedateien mit derselben Seitennummer sind. Die Mehrfachseiten werden horizontal gestapelt, wenn isSidewise true ist, und vertikal gestapelt, wenn isSidewise false ist. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup)(Stream, Stream, int, int) | Erstellt ein N-Up-Dokument aus dem Eingabestream und speichert das Ergebnis im Ausgabestream. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_4)(string, string, int, int) | Erstellt ein N-Up-Dokument aus der firstInputFile in die outputFile. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_1)(Stream, Stream, int, int, PageSize) | Erstellt ein N-Up-Dokument aus dem ersten Eingabestream in den Ausgabestream. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_5)(string, string, int, int, PageSize) | Erstellt ein N-Up-Dokument aus der Eingabedatei in die outputFile. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_4)(Document, ContentsResizeParameters) | Ändert die Größe der Seiten des Dokuments. Leere Ränder werden um die verkleinerte Seite hinzugefügt. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_5)(Document, int[], ContentsResizeParameters) | Ändert die Größe der Seiten des Dokuments. Leere Ränder werden um die verkleinerte Seite hinzugefügt. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents)(Stream, Stream, int[], ContentsResizeParameters) | Ändert die Größe des Inhalts der Seiten des Dokuments. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_2)(string, string, int[], ContentsResizeParameters) | Ändert die Größe des Inhalts der Seiten im Dokument. Wenn die Seite verkleinert wird, werden leere Ränder um die Seite hinzugefügt. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_1)(Stream, Stream, int[], double, double) | Ändert die Größe des Inhalts der Dokumentseiten. Verkleinert den Inhalt der Seite und fügt Ränder hinzu. Die neue Größe des Inhalts wird in den Standardraum-Einheiten angegeben. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_3)(string, string, int[], double, double) | Ändert die Größe des Inhalts der Dokumentseiten. Verkleinert den Inhalt der Seite und fügt Ränder hinzu. Die neue Größe des Inhalts wird in den Standardraum-Einheiten angegeben. |
| [ResizeContentsPct](../../aspose.pdf.facades/pdffileeditor/resizecontentspct/#resizecontentspct)(Stream, Stream, int[], double, double) | Ändert die Größe des Inhalts der Dokumentseiten. Verkleinert den Inhalt der Seite und fügt Ränder hinzu. Die neue Inhaltsgröße wird in Prozent angegeben. |
| [ResizeContentsPct](../../aspose.pdf.facades/pdffileeditor/resizecontentspct/#resizecontentspct_1)(string, string, int[], double, double) | Ändert die Größe des Inhalts der Dokumentseiten. Verkleinert den Inhalt der Seite und fügt Ränder hinzu. Die neue Inhaltsgröße wird in Prozent angegeben. |
| [SplitFromFirst](../../aspose.pdf.facades/pdffileeditor/splitfromfirst/#splitfromfirst)(Stream, int, Stream) | Teilt von Anfang an bis zur angegebenen Stelle und speichert den vorderen Teil im Ausgabestream. |
| [SplitFromFirst](../../aspose.pdf.facades/pdffileeditor/splitfromfirst/#splitfromfirst_1)(string, int, string) | Teilt die PDF-Datei von der ersten Seite bis zur angegebenen Stelle und speichert den vorderen Teil als neue Datei. |
| [SplitToBulks](../../aspose.pdf.facades/pdffileeditor/splittobulks/#splittobulks)(Stream, int[][]) | Teilt die PDF-Datei in mehrere Dokumente. Die Dokumente können einseitig oder mehrseitig sein. |
| [SplitToBulks](../../aspose.pdf.facades/pdffileeditor/splittobulks/#splittobulks_1)(string, int[][]) | Teilt die PDF-Datei in mehrere Dokumente. Die Dokumente können einseitig oder mehrseitig sein. |
| [SplitToEnd](../../aspose.pdf.facades/pdffileeditor/splittoend/#splittoend)(Stream, int, Stream) | Teilt von der angegebenen Stelle und speichert den hinteren Teil als neuen Datei-Stream. |
| [SplitToEnd](../../aspose.pdf.facades/pdffileeditor/splittoend/#splittoend_1)(string, int, string) | Teilt von der Stelle und speichert den hinteren Teil als neue Datei. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages/#splittopages)(Stream) | Teilt die PDF-Datei in einseitige Dokumente. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages/#splittopages_1)(string) | Teilt die PDF-Datei in einseitige Dokumente. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages/#splittopages_2)(Stream, string) | Teilt die PDF-Datei in einseitige Dokumente und speichert sie im angegebenen Pfad. Der Pfad wird durch das Feldnamenmuster angegeben. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages/#splittopages_3)(string, string) | Teilt die PDF-Datei in einseitige Dokumente und speichert sie im angegebenen Pfad. Der Pfad wird durch das Feldnamenmuster angegeben. |
| [TryAppend](../../aspose.pdf.facades/pdffileeditor/tryappend/#tryappend)(Stream, Stream[], int, int, Stream) | Fügt Seiten hinzu, die aus einem Array von Dokumenten in portStreams ausgewählt wurden. Das Ergebnisdokument enthält firstInputFile und alle Seiten der portStreams-Dokumente im Bereich von startPage bis endPage. |
| [TryAppend](../../aspose.pdf.facades/pdffileeditor/tryappend/#tryappend_1)(string, string[], int, int, string) | Fügt Seiten hinzu, die aus portFiles-Dokumenten ausgewählt wurden. Das Ergebnisdokument enthält firstInputFile und alle Seiten der portFiles-Dokumente im Bereich von startPage bis endPage. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate)(Document[], Document) | Verbindet Dokumente. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_2)(Stream[], Stream) | Verbindet Dateien. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_5)(string[], string) | Verbindet Dateien in eine Datei. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_3)(string, string, string) | Verbindet zwei Dateien. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_1)(Stream, Stream, Stream, Stream) | Fügt zwei PDF-Dokumente in ein neues PDF-Dokument mit Seiten in alternierenden Weisen zusammen und füllt die leeren Stellen mit leeren Seiten. z.B.: Dokument1 hat 5 Seiten: p1, p2, p3, p4, p5. Dokument2 hat 3 Seiten: p1', p2', p3'. Das Zusammenführen der beiden PDF-Dokumente ergibt das Ergebnisdokument mit Seiten: p1, p1', p2, p2', p3, p3', p4, leere Seite, p5, leere Seite. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_4)(string, string, string, string) | Fügt zwei PDF-Dokumente in ein neues PDF-Dokument mit Seiten in alternierenden Weisen zusammen und füllt die leeren Stellen mit leeren Seiten. z.B.: Dokument1 hat 5 Seiten: p1, p2, p3, p4, p5. Dokument2 hat 3 Seiten: p1', p2', p3'. Das Zusammenführen der beiden PDF-Dokumente ergibt das Ergebnisdokument mit Seiten: p1, p1', p2, p2', p3, p3', p4, leere Seite, p5, leere Seite. |
| [TryDelete](../../aspose.pdf.facades/pdffileeditor/trydelete/#trydelete)(Stream, int[], Stream) | Löscht Seiten, die durch ein Zahlenarray aus der Eingabedatei angegeben sind, und speichert sie als neue PDF-Datei. |
| [TryDelete](../../aspose.pdf.facades/pdffileeditor/trydelete/#trydelete_1)(string, int[], string) | Löscht Seiten, die durch ein Zahlenarray aus der Eingabedatei angegeben sind, und speichert sie als neue PDF-Datei. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract/#tryextract)(Stream, int[], Stream) | Extrahiert Seiten, die durch ein Zahlenarray angegeben sind, und speichert sie als neue PDF-Datei. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract/#tryextract_2)(string, int[], string) | Extrahiert Seiten, die durch ein Zahlenarray angegeben sind, und speichert sie als neue PDF-Datei. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract/#tryextract_1)(string, int, int, string) | Extrahiert Seiten aus der Eingabedatei und speichert sie als neue PDF-Datei. |
| [TryInsert](../../aspose.pdf.facades/pdffileeditor/tryinsert/#tryinsert)(Stream, int, Stream, int[], Stream) | Fügt Seiten aus einer anderen Datei in die Eingabe-PDF-Datei ein. |
| [TryInsert](../../aspose.pdf.facades/pdffileeditor/tryinsert/#tryinsert_1)(string, int, string, int[], string) | Fügt Seiten aus einer anderen Datei in die Eingabe-PDF-Datei ein. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet)(Stream, Stream) | Erstellt eine Broschüre aus dem InputStream in den outputStream. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_4)(string, string) | Erstellt eine Broschüre aus der Eingabedatei in die Ausgabedatei. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_1)(Stream, Stream, PageSize) | Erstellt eine Broschüre aus dem Eingabestream und speichert das Ergebnis im Ausgabestream. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_5)(string, string, PageSize) | Erstellt eine Broschüre aus der Eingabedatei in die Ausgabedatei. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_3)(Stream, Stream, int[], int[]) | Erstellt eine benutzerdefinierte Broschüre aus dem firstInputStream in den outputStream. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_7)(string, string, int[], int[]) | Erstellt eine benutzerdefinierte Broschüre aus der firstInputFile in die outputFile. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_2)(Stream, Stream, PageSize, int[], int[]) | Erstellt eine Broschüre aus dem firstInputStream in den outputStream. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_6)(string, string, PageSize, int[], int[]) | Erstellt eine benutzerdefinierte Broschüre aus der firstInputFile in die outputFile. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_2)(Stream, Stream, Stream) | Erstellt ein N-Up-Dokument aus den beiden Eingabe-PDF-Streams in den outputStream. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_3)(Stream[], Stream, bool) | Erstellt ein N-Up-Dokument aus den mehreren Eingabe-PDF-Streams in den outputStream. Jede Seite des outputStream enthält mehrere Seiten, die eine Kombination aus Seiten in den Eingabeströmen mit derselben Seitennummer sind. Die Mehrfachseiten werden horizontal gestapelt, wenn isSidewise true ist, und vertikal gestapelt, wenn isSidewise false ist. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_6)(string, string, string) | Erstellt ein N-Up-Dokument aus den beiden Eingabe-PDF-Dateien in die outputFile. Jede Seite der outputFile enthält zwei Seiten, eine Seite stammt aus der ersten Eingabedatei und die andere aus der zweiten Eingabedatei. Die beiden Seiten sind horizontal gestapelt. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_7)(string[], string, bool) | Erstellt ein N-Up-Dokument aus den mehreren Eingabe-PDF-Dateien in die outputFile. Jede Seite der outputFile enthält mehrere Seiten, die eine Kombination aus Seiten in den Eingabedateien mit derselben Seitennummer sind. Die Mehrfachseiten werden horizontal gestapelt, wenn isSidewise true ist, und vertikal gestapelt, wenn isSidewise false ist. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup)(Stream, Stream, int, int) | Erstellt ein N-Up-Dokument aus dem Eingabestream und speichert das Ergebnis im Ausgabestream. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_4)(string, string, int, int) | Erstellt ein N-Up-Dokument aus der firstInputFile in die outputFile. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_1)(Stream, Stream, int, int, PageSize) | Erstellt ein N-Up-Dokument aus dem ersten Eingabestream in den Ausgabestream. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_5)(string, string, int, int, PageSize) | Erstellt ein N-Up-Dokument aus der Eingabedatei in die outputFile. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents/#tryresizecontents)(Stream, Stream, int[], ContentsResizeParameters) | Ändert die Größe des Inhalts der Seiten des Dokuments. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents/#tryresizecontents_2)(string, string, int[], ContentsResizeParameters) | Ändert die Größe des Inhalts der Seiten im Dokument. Wenn die Seite verkleinert wird, werden leere Ränder um die Seite hinzugefügt. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents/#tryresizecontents_1)(Stream, Stream, int[], double, double) | Ändert die Größe des Inhalts der Dokumentseiten. Verkleinert den Inhalt der Seite und fügt Ränder hinzu. Die neue Größe des Inhalts wird in den Standardraum-Einheiten angegeben. |
| [TrySplitFromFirst](../../aspose.pdf.facades/pdffileeditor/trysplitfromfirst/#trysplitfromfirst)(Stream, int, Stream) | Teilt von Anfang an bis zur angegebenen Stelle und speichert den vorderen Teil im Ausgabestream. |
| [TrySplitFromFirst](../../aspose.pdf.facades/pdffileeditor/trysplitfromfirst/#trysplitfromfirst_1)(string, int, string) | Teilt die PDF-Datei von der ersten Seite bis zur angegebenen Stelle und speichert den vorderen Teil als neue Datei. |
| [TrySplitToEnd](../../aspose.pdf.facades/pdffileeditor/trysplittoend/#trysplittoend)(Stream, int, Stream) | Teilt von der angegebenen Stelle und speichert den hinteren Teil als neuen Datei-Stream. |
| [TrySplitToEnd](../../aspose.pdf.facades/pdffileeditor/trysplittoend/#trysplittoend_1)(string, int, string) | Teilt von der Stelle und speichert den hinteren Teil als neue Datei. |

## Weitere Mitglieder

| Name | Beschreibung |
| --- | --- |
| enum [ConcatenateCorruptedFileAction](../../aspose.pdf.facades/pdffileeditor.concatenatecorruptedfileaction) | Aktion, die ausgeführt wird, wenn eine beschädigte Datei im Zusammenführungsprozess gefunden wird. |
| class [ContentsResizeParameters](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters) | Klasse zur Spezifizierung der Seitenänderungsparameter. Ermöglicht das Festlegen der folgenden Parameter: Größe der Ergebnisseite (Breite, Höhe) in Standardraum-Einheiten oder in Prozent der ursprünglichen Seitengröße; Linke, Obere, Untere und Rechte Ränder in Standardraum-Einheiten oder in Prozent der ursprünglichen Seitengröße; Einige Werte können null gelassen werden für automatische Berechnung. Diese Werte werden aus dem Rest der Seitengröße nach der Berechnung der explizit angegebenen Werte berechnet. Zum Beispiel: Wenn die Seitenbreite = 100 und die neue Seitenbreite 60 Einheiten beträgt, werden die linken und rechten Ränder automatisch berechnet: (100 - 60) / 2 = 15. Diese Klasse wird in der Methode ResizeContents verwendet. |
| class [ContentsResizeValue](../../aspose.pdf.facades/pdffileeditor.contentsresizevalue) | Wert des Rands oder der Inhaltsgröße, der in Prozent der Standardraum-Einheiten angegeben ist. Diese Klasse wird in ContentsResizeParameters verwendet. |
| class [CorruptedItem](../../aspose.pdf.facades/pdffileeditor.corrupteditem) | Klasse, die Informationen über beschädigte Dateien während der Zusammenführung bereitstellt. |
| class [PageBreak](../../aspose.pdf.facades/pdffileeditor.pagebreak) | Daten zur Position des Seitenumbruchs. |

### Siehe auch

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)