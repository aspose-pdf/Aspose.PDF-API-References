---
title: "PdfContentEditor"
linktitle: "PdfContentEditor"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt eine Klasse zum Bearbeiten des Inhalts von PDF‑Dateien dar."
type: docs
weight: 380
url: /de/java/com.aspose.pdf.facades/pdfcontenteditor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfContentEditor, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfContentEditor, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfContentEditor

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfContentEditor extends SaveableFacade
```

Stellt eine Klasse zum Bearbeiten des Inhalts von PDF‑Dateien dar.

## Felder

| Feld | Beschreibung |
| --- | --- |
| [DOCUMENT_CLOSE](#DOCUMENT_CLOSE) | Ein Dokumentereignistyp. Schließt ein Dokument. |
| [DOCUMENT_OPEN](#DOCUMENT_OPEN) | Ein Dokumentereignistyp. Öffnet ein Dokument. |
| [DOCUMENT_PRINTED](#DOCUMENT_PRINTED) | Ein Dokumentereignistyp. Führt eine Aktion nach dem Drucken aus. |
| [DOCUMENT_SAVED](#DOCUMENT_SAVED) | Ein Dokumentereignistyp. Führt eine Aktion nach dem Speichern aus. |
| [DOCUMENT_WILL_PRINT](#DOCUMENT_WILL_PRINT) | Ein Dokumentereignistyp. Führt eine Aktion vor dem Drucken aus. |
| [DOCUMENT_WILL_SAVE](#DOCUMENT_WILL_SAVE) | Ein Dokumentereignistyp. Führt eine Aktion vor dem Speichern aus. |

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PdfContentEditor](#PdfContentEditor--) | Der Konstruktor des PdfContentEditor-Objekts. |
| [PdfContentEditor](#PdfContentEditor-com.aspose.pdf.IDocument-) | Der Konstruktor des PdfContentEditor-Objekts. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [addDocumentAdditionalAction](#addDocumentAdditionalAction-java.lang.String-java.lang.String-) | <p> Fügt eine zusätzliche Aktion für das Dokumentereignis hinzu. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.addDocumentAdditionalAction(PdfContentEditor.DocumentClose, "app.alert('Good-bye!');"); editor.save("example_out.pdf"); </pre> |
| [addDocumentAttachment](#addDocumentAttachment-java.io.InputStream-java.lang.String-java.lang.String-) | <p> Fügt einen Dokumentanhang ohne Annotation hinzu. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); InputStream attStream = new FileInputStream("attachment_file.pdf") editor.addDocumentAttachment(attStream, "attachment_file.pdf", "description of attachment_file"); editor.save("example_out.pdf"); </pre> |
| [addDocumentAttachment](#addDocumentAttachment-java.lang.String-java.lang.String-) | <p> Fügt einen Dokumentanhang ohne Annotation hinzu. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.addDocumentAttachment("attachment_file.pdf", "description of attachment_file"); editor.save("example_out.pdf"); </pre> |
| [bindPdf](#bindPdf-java.io.InputStream-) | Bindet einen PDF-Stream zum Bearbeiten. |
| [bindPdf](#bindPdf-java.lang.String-) | Bindet eine PDF-Datei zum Bearbeiten. |
| [changeViewerPreference](#changeViewerPreference-int-) | <p> Ändert die Ansichtseinstellung. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.changeViewerPreference(ViewerPreference.HideMenubar); editor.changeViewerPreference(ViewerPreference.PageModeUseNone); editor.save("example_out.pdf"); </pre> |
| [close](#close--) | Schließt das geöffnete Dokument. |
| [createApplicationLink](#createApplicationLink-java.awt.Rectangle-java.lang.String-int-) | Erstellt einen Link zum Starten einer Anwendung im PDF-Dokument. |
| [createApplicationLink](#createApplicationLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-) | Erstellt einen Link zum Starten einer Anwendung im PDF-Dokument. |
| [createApplicationLink](#createApplicationLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-) | Erstellt einen Link zum Starten einer Anwendung im PDF-Dokument. |
| [createBookmarksAction](#createBookmarksAction-java.lang.String-java.awt.Color-boolean-boolean-java.lang.String-java.lang.String-java.lang.String-) | Erstellt ein Lesezeichen mit der angegebenen Aktion. |
| [createCaret](#createCaret-int-java.awt.Rectangle-java.awt.Rectangle-java.lang.String-java.lang.String-java.awt.Color-) | Erstellt eine Caret-Annotation. |
| [createCustomActionLink](#createCustomActionLink-java.awt.Rectangle-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-) | Erstellt einen Link zu benutzerdefinierten Aktionen im PDF-Dokument. |
| [createFileAttachment](#createFileAttachment-java.awt.Rectangle-java.lang.String-java.io.InputStream-java.lang.String-int-java.lang.String-) | Erstellt eine Dateianhang-Annotation. |
| [createFileAttachment](#createFileAttachment-java.awt.Rectangle-java.lang.String-java.lang.String-int-java.lang.String-) | Erstellt eine Dateianhang-Annotation. |
| [createFreeText](#createFreeText-java.awt.Rectangle-java.lang.String-int-) | Erstellt eine Freitext-Annotation im PDF-Dokument |
| [createJavaScriptLink](#createJavaScriptLink-java.lang.String-java.awt.Rectangle-int-java.awt.Color-) | Erstellt einen Link zu JavaScript im PDF-Dokument. |
| [createLine](#createLine-java.awt.Rectangle-java.lang.String-float-float-float-float-int-int-java.awt.Color-java.lang.String-int:A-java.lang.String:A-) | Erstellt eine Linien-Annotation. |
| [createLocalLink](#createLocalLink-java.awt.Rectangle-int-int-) | Erstellt einen lokalen Link im PDF-Dokument. |
| [createLocalLink](#createLocalLink-java.awt.Rectangle-int-int-java.awt.Color-) | Erstellt einen lokalen Link im PDF-Dokument. |
| [createLocalLink](#createLocalLink-java.awt.Rectangle-int-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-) | Erstellt einen lokalen Link im PDF-Dokument. |
| [createMarkup](#createMarkup-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-) | Erstellt eine Markup-Annotation im PDF-Dokument. |
| [createMovie](#createMovie-java.awt.Rectangle-java.lang.String-int-) |  |
| [createPdfDocumentLink](#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-) | Erstellt einen Link zu einer anderen Seite eines PDF-Dokuments. |
| [createPdfDocumentLink](#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-) | Erstellt einen Link zu einer anderen Seite eines PDF-Dokuments. |
| [createPdfDocumentLink](#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-) | Erstellt einen Link zu einer anderen Seite eines PDF-Dokuments. |
| [createPolygon](#createPolygon-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-) | Erstellt eine Polygon-Annotation. |
| [createPolyLine](#createPolyLine-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-) | Erstellt eine Polylinien-Annotation. |
| [createPopup](#createPopup-java.awt.Rectangle-java.lang.String-boolean-int-) | Erstellt eine Popup-Annotation im PDF-Dokument. |
| [createRubberStamp](#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.awt.Color-java.io.InputStream-) | Erstellt eine Gummistempel-Annotation. |
| [createRubberStamp](#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.awt.Color-java.lang.String-) | Erstellt eine Gummistempel-Annotation. |
| [createRubberStamp](#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.lang.String-java.awt.Color-) | Erstellt eine Gummistempel-Annotation. |
| [createSound](#createSound-java.awt.Rectangle-java.lang.String-java.lang.String-int-java.lang.String-) |  |
| [createSquareCircle](#createSquareCircle-java.awt.Rectangle-java.lang.String-java.awt.Color-boolean-int-int-) | Erstellt eine Quadrat-Kreis-Annotation. |
| [createText](#createText-java.awt.Rectangle-java.lang.String-java.lang.String-boolean-java.lang.String-int-) | Erstellt eine Text-Annotation im PDF-Dokument |
| [createWebLink](#createWebLink-java.awt.Rectangle-java.lang.String-int-) | Erstellt einen Weblink im PDF-Dokument. |
| [createWebLink](#createWebLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-) | Erstellt einen Weblink im PDF-Dokument. |
| [createWebLink](#createWebLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-) | Erstellt einen Weblink im PDF-Dokument. |
| [deleteAttachments](#deleteAttachments--) | <p> Löscht alle Anhänge im PDF-Dokument. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.deleteAttachments(); editor.save("example_out.pdf"); </pre> |
| [deleteImage](#deleteImage--) | <p> Löscht alle Bilder aus dem PDF-Dokument. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.deleteImage(); editor.save("example_out.pdf"); </pre> |
| [deleteImage](#deleteImage-int-int:A-) | <p> Löscht die angegebenen Bilder auf der angegebenen Seite. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.deleteImage(1, new int[] {1, 2}); editor.save("example_out.pdf"); </pre> |
| [deleteStamp](#deleteStamp-int-int:A-) | <p> Löscht mehrere Stempel auf der angegebenen Seite anhand von Stempelindizes. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStamp(1, new int[] { 2, 3, 5} ); contentEditor.save("outfile.pdf"); </pre> |
| [deleteStampById](#deleteStampById-int-) | <p> Löscht einen Stempel nach ID von allen Seiten des Dokuments. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampById(100); contentEditor.save("outfile.pdf"); </pre> |
| [deleteStampById](#deleteStampById-int-int-) | <p> Löscht einen Stempel auf der angegebenen Seite nach Stempel-ID. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampById(1, 100); contentEditor.save("outfile.pdf"); </pre> |
| [deleteStampByIds](#deleteStampByIds-int:A-) | <p> Löscht Stempel mit angegebenen IDs von allen Seiten des Dokuments. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampByIds(new int[] { 102, 103 } ); contentEditor.save("outfile.pdf"); </pre> |
| [deleteStampByIds](#deleteStampByIds-int-int:A-) | <p> Löscht Stempel auf der angegebenen Seite nach mehreren Stempel-IDs. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampByIds(1, new int[] { 100, 101 } ); contentEditor.save("outfile.pdf"); </pre> |
| [drawCurve](#drawCurve-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-) | Erstellt eine Kurvenannotation. |
| [extractLink](#extractLink--) | <p> Extrahiert die Sammlung von Link-Instanzen, die im PDF-Dokument enthalten sind. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); List links = editor.extractLink(); for (object obj : links) { Link link = (Link)obj; // work with Link instance } </pre> |
| [getReplaceTextStrategy](#getReplaceTextStrategy--) | Erhalte einen Satz von Parametern für die Text-Ersetzungsoperation |
| [getStamps](#getStamps-int-) | Gibt ein Array von Stempeln auf der Seite zurück. |
| [getTextEditOptions](#getTextEditOptions--) | Erhält Textbearbeitungsoptionen. |
| [getTextReplaceOptions](#getTextReplaceOptions--) | Erhält Text-Ersetzungsoptionen. |
| [getTextSearchOptions](#getTextSearchOptions--) | Erhält Textsuchoptionen. |
| [getViewerPreference](#getViewerPreference--) | <p> Gibt die Ansichtseinstellung zurück. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); int prefValue = editor.GetViewerPreference(); if ((prefValue & ViewerPreference.PageModeUseOutline) != 0) { // ... } </pre> |
| [hideStampById](#hideStampById-int-int-) | Versteckt den Stempel. Nach dem Verstecken kann die Sichtbarkeit des Stempels mit der Methode ShowStampById wiederhergestellt werden. |
| [moveStamp](#moveStamp-int-int-double-double-) | Ändert die Position des Stempels auf der Seite. |
| [moveStampById](#moveStampById-int-int-double-double-) | Ändert die Position des Stempels auf der Seite. |
| [removeDocumentOpenAction](#removeDocumentOpenAction--) | <p> Entfernt die Öffnungsaktion aus dem Dokument. Dieser Vorgang ist nützlich, wenn mehrere Dokumente zusammengeführt werden, die beim Start eine explizite 'GoTo'-Aktion verwenden. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.removeDocumentOpenAction(); editor.save("example_out.pdf"); </pre> |
| [replaceImage](#replaceImage-int-int-java.lang.String-) | <p> Ersetzt das angegebene Bild auf der angegebenen Seite des PDF-Dokuments durch ein anderes Bild. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.replaceImage(1, 1, "image.jpg"); editor.save("example_out.pdf"); </pre> |
| [replaceText](#replaceText-java.lang.String-int-java.lang.String-) | <p> Ersetzt Text in der PDF-Datei auf der angegebenen Seite. </p> <hr> <pre> Das Beispiel zeigt, wie man Text im PDF-Dokument auf der angegebenen Seite ersetzt. // open document Document doc = new Document(inFile); // create PdfContentEditor object to edit text PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // change text editor.replaceText("hello world", 1, "hi world"); // save document doc.save(outFile); </pre> |
| [replaceText](#replaceText-java.lang.String-int-java.lang.String-com.aspose.pdf.TextState-) | <p> Replaces text in the PDF file on the specified page. {@code TextState} object (font family, color) can be specified to replaced text. </p> <hr> <pre> The example demonstrates how to replace text on the first page of the PDF document and set {@code TextState} text properties for the new text. // open document Document doc = new Document(inFile); com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont("Courier New"); font.isEmbedded ( true); // create PdfContentEditor object to edit text PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // create textState object com.aspose.pdf.TextState textState = new com.aspose.pdf.TextState(); textState.setFont ( font); textState.setFontSize ( 17); textState.setFontStyle ( com.aspose.pdf.FontStyles.Bold \ | com.aspose.pdf.FontStyles.Italic); textState.setForegroundColor ( com.aspose.pdf.Color.getRed()); // Text mit angegebener Schriftart ändern editor.replaceText("hello world", 1, "hi world", textState); // Dokument speichern doc.save(outFile); </pre> |
| [replaceText](#replaceText-java.lang.String-java.lang.String-) | <p> Ersetzt Text in der PDF-Datei. </p> <hr> <pre> Das Beispiel zeigt, wie man Text im PDF-Dokument ersetzt. Standardmäßig wird der zuerst gefundene Text ersetzt. // open document Document doc = new Document(inFile); // create PdfContentEditor object to edit text PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // change text editor.replaceText("hello world", "hi world"); // save document doc.save(outFile); </pre> |
| [replaceText](#replaceText-java.lang.String-java.lang.String-int-) | <p> Ersetzt Text in der PDF-Datei und legt die Schriftgröße fest. </p> <hr> <pre> Das Beispiel zeigt, wie man Text ersetzt und die Schriftgröße für den neuen Text festlegt. // open document Document doc = new Document(inFile); // Create font and mark it to be embedded com.aspose.pdf.Font font = FontRepository.FindFont("Courier New"); font.isEmbedded ( true); // create PdfContentEditor object to edit text PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // change text with specified font editor.replaceText("hello world", "hi world", 14); // save document doc.save(outFile); </pre> |
| [replaceText](#replaceText-java.lang.String-java.lang.String-com.aspose.pdf.TextState-) | <p> Replaces text in the PDF file using specified {@code TextState} object. </p> <hr> <pre> The example demonstrates how to replace text and set {@code TextState} text properties for the new text. Document doc = new Document(inFile); // Create font and mark it to be embedded com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont("Courier New"); font.isEmbedded ( true); // create PdfContentEditor object to edit text PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // create textState object com.aspose.pdf.TextState textState = new com.aspose.pdf.TextState(); textState.setFont ( font); textState.setFontStyle ( com.aspose.pdf.FontStyles.Bold \ | com.aspose.pdf.FontStyles.Italic); // Text mit angegebener Schriftart ändern editor.replaceText("hello world", "hi world", textState); // Dokument speichern doc.save(outFile); </pre> |
| [setReplaceTextStrategy](#setReplaceTextStrategy-com.aspose.pdf.facades.ReplaceTextStrategy-) | Legen Sie eine Reihe von Parametern für die Text-Ersetzungsoperation fest. |
| [setTextEditOptions](#setTextEditOptions-com.aspose.pdf.TextEditOptions-) | Legt Optionen für die Textbearbeitung fest. |
| [setTextReplaceOptions](#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-) | Legt Optionen für das Ersetzen von Text fest. |
| [setTextSearchOptions](#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-) | Legt Optionen für die Textsuche fest. |
| [showStampById](#showStampById-int-int-) | Zeigt den Stempel an, der durch HiddenStampById ausgeblendet wurde. |

### DOCUMENT_CLOSE {#DOCUMENT_CLOSE}
```
public static final String DOCUMENT_CLOSE
```

Ein Dokumentereignistyp. Schließt ein Dokument.

### DOCUMENT_OPEN {#DOCUMENT_OPEN}
```
public static final String DOCUMENT_OPEN
```

Ein Dokumentereignistyp. Öffnet ein Dokument.

### DOCUMENT_PRINTED {#DOCUMENT_PRINTED}
```
public static final String DOCUMENT_PRINTED
```

Ein Dokumentereignistyp. Führt eine Aktion nach dem Drucken aus.

### DOCUMENT_SAVED {#DOCUMENT_SAVED}
```
public static final String DOCUMENT_SAVED
```

Ein Dokumentereignistyp. Führt eine Aktion nach dem Speichern aus.

### DOCUMENT_WILL_PRINT {#DOCUMENT_WILL_PRINT}
```
public static final String DOCUMENT_WILL_PRINT
```

Ein Dokumentereignistyp. Führt eine Aktion vor dem Drucken aus.

### DOCUMENT_WILL_SAVE {#DOCUMENT_WILL_SAVE}
```
public static final String DOCUMENT_WILL_SAVE
```

Ein Dokumentereignistyp. Führt eine Aktion vor dem Speichern aus.

### PdfContentEditor {#PdfContentEditor--}
```
public PdfContentEditor()
```

Der Konstruktor des PdfContentEditor-Objekts.

### PdfContentEditor {#PdfContentEditor-com.aspose.pdf.IDocument-}
Der Konstruktor des PdfContentEditor-Objekts.

### addDocumentAdditionalAction {#addDocumentAdditionalAction-java.lang.String-java.lang.String-}
<p> Fügt eine zusätzliche Aktion für das Dokumentereignis hinzu. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.addDocumentAdditionalAction(PdfContentEditor.DocumentClose, "app.alert('Good-bye!');"); editor.save("example_out.pdf"); </pre>

### addDocumentAttachment {#addDocumentAttachment-java.io.InputStream-java.lang.String-java.lang.String-}
<p> Fügt einen Dokumentanhang ohne Annotation hinzu. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); InputStream attStream = new FileInputStream("attachment_file.pdf") editor.addDocumentAttachment(attStream, "attachment_file.pdf", "description of attachment_file"); editor.save("example_out.pdf"); </pre>

### addDocumentAttachment {#addDocumentAttachment-java.lang.String-java.lang.String-}
<p> Fügt einen Dokumentanhang ohne Annotation hinzu. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.addDocumentAttachment("attachment_file.pdf", "description of attachment_file"); editor.save("example_out.pdf"); </pre>

### bindPdf {#bindPdf-java.io.InputStream-}
Bindet einen PDF-Stream zum Bearbeiten.

### bindPdf {#bindPdf-java.lang.String-}
Bindet eine PDF-Datei zum Bearbeiten.

### changeViewerPreference {#changeViewerPreference-int-}
```
public void changeViewerPreference(int viewerAttribution)
```

<p> Ändert die Ansichtseinstellung. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.changeViewerPreference(ViewerPreference.HideMenubar); editor.changeViewerPreference(ViewerPreference.PageModeUseNone); editor.save("example_out.pdf"); </pre>

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| viewerAttribution |  | Die View-Attribution, definiert in der ViewerPreference-Klasse. |

### close {#close--}
```
public void close()
```

Schließt das geöffnete Dokument.

### createApplicationLink {#createApplicationLink-java.awt.Rectangle-java.lang.String-int-}
Erstellt einen Link zum Starten einer Anwendung im PDF-Dokument.

### createApplicationLink {#createApplicationLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-}
Erstellt einen Link zum Starten einer Anwendung im PDF-Dokument.

### createApplicationLink {#createApplicationLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-}
Erstellt einen Link zum Starten einer Anwendung im PDF-Dokument.

### createBookmarksAction {#createBookmarksAction-java.lang.String-java.awt.Color-boolean-boolean-java.lang.String-java.lang.String-java.lang.String-}
Erstellt ein Lesezeichen mit der angegebenen Aktion.

### createCaret {#createCaret-int-java.awt.Rectangle-java.awt.Rectangle-java.lang.String-java.lang.String-java.awt.Color-}
Erstellt eine Caret-Annotation.

### createCustomActionLink {#createCustomActionLink-java.awt.Rectangle-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-}
Erstellt einen Link zu benutzerdefinierten Aktionen im PDF-Dokument.

### createFileAttachment {#createFileAttachment-java.awt.Rectangle-java.lang.String-java.io.InputStream-java.lang.String-int-java.lang.String-}
Erstellt eine Dateianhang-Annotation.

### createFileAttachment {#createFileAttachment-java.awt.Rectangle-java.lang.String-java.lang.String-int-java.lang.String-}
Erstellt eine Dateianhang-Annotation.

### createFreeText {#createFreeText-java.awt.Rectangle-java.lang.String-int-}
Erstellt eine Freitext-Annotation im PDF-Dokument

### createJavaScriptLink {#createJavaScriptLink-java.lang.String-java.awt.Rectangle-int-java.awt.Color-}
Erstellt einen Link zu JavaScript im PDF-Dokument.

### createLine {#createLine-java.awt.Rectangle-java.lang.String-float-float-float-float-int-int-java.awt.Color-java.lang.String-int:A-java.lang.String:A-}
Erstellt eine Linien-Annotation.

### createLocalLink {#createLocalLink-java.awt.Rectangle-int-int-}
Erstellt einen lokalen Link im PDF-Dokument.

### createLocalLink {#createLocalLink-java.awt.Rectangle-int-int-java.awt.Color-}
Erstellt einen lokalen Link im PDF-Dokument.

### createLocalLink {#createLocalLink-java.awt.Rectangle-int-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-}
Erstellt einen lokalen Link im PDF-Dokument.

### createMarkup {#createMarkup-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-}
Erstellt eine Markup-Annotation im PDF-Dokument.

### createMovie {#createMovie-java.awt.Rectangle-java.lang.String-int-}


### createPdfDocumentLink {#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-}
Erstellt einen Link zu einer anderen Seite eines PDF-Dokuments.

### createPdfDocumentLink {#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-}
Erstellt einen Link zu einer anderen Seite eines PDF-Dokuments.

### createPdfDocumentLink {#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-}
Erstellt einen Link zu einer anderen Seite eines PDF-Dokuments.

### createPolygon {#createPolygon-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-}
Erstellt eine Polygon-Annotation.

### createPolyLine {#createPolyLine-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-}
Erstellt eine Polylinien-Annotation.

### createPopup {#createPopup-java.awt.Rectangle-java.lang.String-boolean-int-}
Erstellt eine Popup-Annotation im PDF-Dokument.

### createRubberStamp {#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.awt.Color-java.io.InputStream-}
Erstellt eine Gummistempel-Annotation.

### createRubberStamp {#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.awt.Color-java.lang.String-}
Erstellt eine Gummistempel-Annotation.

### createRubberStamp {#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.lang.String-java.awt.Color-}
Erstellt eine Gummistempel-Annotation.

### createSound {#createSound-java.awt.Rectangle-java.lang.String-java.lang.String-int-java.lang.String-}


### createSquareCircle {#createSquareCircle-java.awt.Rectangle-java.lang.String-java.awt.Color-boolean-int-int-}
Erstellt eine Quadrat-Kreis-Annotation.

### createText {#createText-java.awt.Rectangle-java.lang.String-java.lang.String-boolean-java.lang.String-int-}
Erstellt eine Text-Annotation im PDF-Dokument

### createWebLink {#createWebLink-java.awt.Rectangle-java.lang.String-int-}
Erstellt einen Weblink im PDF-Dokument.

### createWebLink {#createWebLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-}
Erstellt einen Weblink im PDF-Dokument.

### createWebLink {#createWebLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-}
Erstellt einen Weblink im PDF-Dokument.

### deleteAttachments {#deleteAttachments--}
```
public void deleteAttachments()
```

<p> Löscht alle Anhänge im PDF-Dokument. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.deleteAttachments(); editor.save("example_out.pdf"); </pre>

### deleteImage {#deleteImage--}
```
public void deleteImage()
```

<p> Löscht alle Bilder aus dem PDF-Dokument. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.deleteImage(); editor.save("example_out.pdf"); </pre>

### deleteImage {#deleteImage-int-int:A-}
```
public void deleteImage(int pageNumber, int[] index)
```

<p> Löscht die angegebenen Bilder auf der angegebenen Seite. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.deleteImage(1, new int[] {1, 2}); editor.save("example_out.pdf"); </pre>

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pageNumber |  | Die Seitenzahl, auf der Bilder gelöscht werden müssen. |
| index |  | Ein Array, das die Indizes der Bilder enthält. |

### deleteStamp {#deleteStamp-int-int:A-}
```
public void deleteStamp(int pageNumber, int[] index)
```

<p> Löscht mehrere Stempel auf der angegebenen Seite anhand von Stempelindizes. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStamp(1, new int[] { 2, 3, 5} ); contentEditor.save("outfile.pdf"); </pre>

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pageNumber |  | Seitenzahl, auf der der Stempel gelöscht wird. |
| index |  | Stempelindizes. |

### deleteStampById {#deleteStampById-int-}
```
public void deleteStampById(int stampId)
```

<p> Löscht einen Stempel nach ID von allen Seiten des Dokuments. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampById(100); contentEditor.save("outfile.pdf"); </pre>

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stampId |  | Kennung des Stempels, der gelöscht werden soll. |

### deleteStampById {#deleteStampById-int-int-}
```
public void deleteStampById(int pageNumber, int stampId)
```

<p> Löscht einen Stempel auf der angegebenen Seite nach Stempel-ID. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampById(1, 100); contentEditor.save("outfile.pdf"); </pre>

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pageNumber |  | Seitenzahl, auf der der Stempel gelöscht wird. |
| stampId |  | Kennung des Stempels, der gelöscht werden soll. |

### deleteStampByIds {#deleteStampByIds-int:A-}
```
public void deleteStampByIds(int[] stampIds)
```

<p> Löscht Stempel mit angegebenen IDs von allen Seiten des Dokuments. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampByIds(new int[] { 102, 103 } ); contentEditor.save("outfile.pdf"); </pre>

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stampIds |  | Array von Stempel-IDs. |

### deleteStampByIds {#deleteStampByIds-int-int:A-}
```
public void deleteStampByIds(int pageNumber, int[] stampIds)
```

<p> Löscht Stempel auf der angegebenen Seite nach mehreren Stempel-IDs. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampByIds(1, new int[] { 100, 101 } ); contentEditor.save("outfile.pdf"); </pre>

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pageNumber |  | Seitenzahl, auf der Stempel gelöscht werden. |
| stampIds |  | Array von Stempel-IDs. |

### drawCurve {#drawCurve-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-}
Erstellt eine Kurvenannotation.

### extractLink {#extractLink--}
```
public List < Annotation > extractLink()
```

<p> Extrahiert die Sammlung von Link-Instanzen, die im PDF-Dokument enthalten sind. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); List links = editor.extractLink(); for (object obj : links) { Link link = (Link)obj; // work with Link instance } </pre>

**Returns:**
Die Sammlung von Link-Objekten

### getReplaceTextStrategy {#getReplaceTextStrategy--}
```
public ReplaceTextStrategy getReplaceTextStrategy()
```

Erhalte einen Satz von Parametern für die Text-Ersetzungsoperation

**Returns:**
ReplaceTextStrategy-Element

### getStamps {#getStamps-int-}
```
public StampInfo [] getStamps(int pageNumber)
```

Gibt ein Array von Stempeln auf der Seite zurück.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pageNumber |  | Seitenzahl, auf der Stempel gesucht werden. |

**Returns:**
Array von Stempeln.

### getTextEditOptions {#getTextEditOptions--}
```
public TextEditOptions getTextEditOptions()
```

Erhält Textbearbeitungsoptionen.

**Returns:**
TextEditOptions-Element

### getTextReplaceOptions {#getTextReplaceOptions--}
```
public TextReplaceOptions getTextReplaceOptions()
```

Erhält Text-Ersetzungsoptionen.

**Returns:**
TextReplaceOptions-Element

### getTextSearchOptions {#getTextSearchOptions--}
```
public TextSearchOptions getTextSearchOptions()
```

Erhält Textsuchoptionen.

**Returns:**
TextSearchOptions-Element

### getViewerPreference {#getViewerPreference--}
```
public int getViewerPreference()
```

<p> Gibt die Ansichtseinstellung zurück. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); int prefValue = editor.GetViewerPreference(); if ((prefValue & ViewerPreference.PageModeUseOutline) != 0) { // ... } </pre>

**Returns:**
Gibt eine Menge von ViewerPrefernece-Flags zurück

### hideStampById {#hideStampById-int-int-}
```
public void hideStampById(int pageNumber, int stampId)
```

Versteckt den Stempel. Nach dem Verstecken kann die Sichtbarkeit des Stempels mit der Methode ShowStampById wiederhergestellt werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pageNumber |  | Nummer der Seite. |
| stampId |  | Kennung des Stempels, der ausgeblendet werden soll. |

### moveStamp {#moveStamp-int-int-double-double-}
```
public void moveStamp(int pageNumber, int stampIndex, double x, double y)
```

Ändert die Position des Stempels auf der Seite.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pageNumber |  | Seitenzahl. |
| stampIndex |  | Index des Stempels auf der Seite. |
| x |  | Neue horizontale Position des Stempels. |
| y |  | Neue vertikale Position des Stempels. |

### moveStampById {#moveStampById-int-int-double-double-}
```
public void moveStampById(int pageNumber, int stampId, double x, double y)
```

Ändert die Position des Stempels auf der Seite.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pageNumber |  | Seitenzahl. |
| stampId |  | Kennung des Stempels, der verschoben werden soll. |
| x |  | Neue horizontale Position des Stempels auf der Seite. |
| y |  | Neue vertikale Position des Stempels auf der Seite. |

### removeDocumentOpenAction {#removeDocumentOpenAction--}
```
public void removeDocumentOpenAction()
```

<p> Entfernt die Öffnungsaktion aus dem Dokument. Dieser Vorgang ist nützlich, wenn mehrere Dokumente zusammengeführt werden, die beim Start eine explizite 'GoTo'-Aktion verwenden. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.removeDocumentOpenAction(); editor.save("example_out.pdf"); </pre>

### replaceImage {#replaceImage-int-int-java.lang.String-}
<p> Ersetzt das angegebene Bild auf der angegebenen Seite des PDF-Dokuments durch ein anderes Bild. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.replaceImage(1, 1, "image.jpg"); editor.save("example_out.pdf"); </pre>

### replaceText {#replaceText-java.lang.String-int-java.lang.String-}
<p> Ersetzt Text in der PDF-Datei auf der angegebenen Seite. </p> <hr> <pre> Das Beispiel zeigt, wie man Text im PDF-Dokument auf der angegebenen Seite ersetzt. // open document Document doc = new Document(inFile); // create PdfContentEditor object to edit text PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // change text editor.replaceText("hello world", 1, "hi world"); // save document doc.save(outFile); </pre>

### replaceText {#replaceText-java.lang.String-int-java.lang.String-com.aspose.pdf.TextState-}
<p> Ersetzt Text in der PDF-Datei auf der angegebenen Seite. {@code TextState} Objekt (Schriftfamilie, Farbe) kann angegeben werden, um den zu ersetzenden Text zu bestimmen. </p> <hr> <pre> Das Beispiel zeigt, wie man Text auf der ersten Seite des PDF-Dokuments ersetzt und {@code TextState}-Texteigenschaften für den neuen Text festlegt. // Dokument öffnen Document doc = new Document(inFile); com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont(\"Courier New\"); font.isEmbedded ( true); // PdfContentEditor-Objekt zum Bearbeiten von Text erstellen PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // textState-Objekt erstellen com.aspose.pdf.TextState textState = new com.aspose.pdf.TextState(); textState.setFont ( font); textState.setFontSize ( 17); textState.setFontStyle ( com.aspose.pdf.FontStyles.Bold | com.aspose.pdf.FontStyles.Italic); textState.setForegroundColor ( com.aspose.pdf.Color.getRed()); // Text mit der angegebenen Schriftart ändern editor.replaceText(\"hello world\", 1, \"hi world\", textState); // Dokument speichern doc.save(outFile); </pre>

### replaceText {#replaceText-java.lang.String-java.lang.String-}
<p> Ersetzt Text in der PDF-Datei. </p> <hr> <pre> Das Beispiel zeigt, wie man Text im PDF-Dokument ersetzt. Standardmäßig wird der zuerst gefundene Text ersetzt. // open document Document doc = new Document(inFile); // create PdfContentEditor object to edit text PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // change text editor.replaceText("hello world", "hi world"); // save document doc.save(outFile); </pre>

### replaceText {#replaceText-java.lang.String-java.lang.String-int-}
<p> Ersetzt Text in der PDF-Datei und legt die Schriftgröße fest. </p> <hr> <pre> Das Beispiel zeigt, wie man Text ersetzt und die Schriftgröße für den neuen Text festlegt. // open document Document doc = new Document(inFile); // Create font and mark it to be embedded com.aspose.pdf.Font font = FontRepository.FindFont("Courier New"); font.isEmbedded ( true); // create PdfContentEditor object to edit text PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // change text with specified font editor.replaceText("hello world", "hi world", 14); // save document doc.save(outFile); </pre>

### replaceText {#replaceText-java.lang.String-java.lang.String-com.aspose.pdf.TextState-}
<p> Ersetzt Text in der PDF-Datei mit dem angegebenen {@code TextState}-Objekt. </p> <hr> <pre> Das Beispiel zeigt, wie man Text ersetzt und {@code TextState}-Texteigenschaften für den neuen Text festlegt. Document doc = new Document(inFile); // Schriftart erstellen und als eingebettet markieren com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont(\"Courier New\"); font.isEmbedded ( true); // PdfContentEditor-Objekt zum Bearbeiten von Text erstellen PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // textState-Objekt erstellen com.aspose.pdf.TextState textState = new com.aspose.pdf.TextState(); textState.setFont ( font); textState.setFontStyle ( com.aspose.pdf.FontStyles.Bold | com.aspose.pdf.FontStyles.Italic); // Text mit der angegebenen Schriftart ändern editor.replaceText(\"hello world\", \"hi world\", textState); // Dokument speichern doc.save(outFile); </pre>

### setReplaceTextStrategy {#setReplaceTextStrategy-com.aspose.pdf.facades.ReplaceTextStrategy-}
Legen Sie eine Reihe von Parametern für die Text-Ersetzungsoperation fest.

### setTextEditOptions {#setTextEditOptions-com.aspose.pdf.TextEditOptions-}
Legt Optionen für die Textbearbeitung fest.

### setTextReplaceOptions {#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-}
Legt Optionen für das Ersetzen von Text fest.

### setTextSearchOptions {#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-}
Legt Optionen für die Textsuche fest.

### showStampById {#showStampById-int-int-}
```
public void showStampById(int pageNumber, int stampId)
```

Zeigt den Stempel an, der durch HiddenStampById ausgeblendet wurde.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pageNumber |  | Nummer der Seite. |
| stampId |  | Kennung des Stempels, der angezeigt werden soll. |
