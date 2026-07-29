---
title: "PdfContentEditor"
linktitle: "PdfContentEditor"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar en klass för att redigera PDF-fils innehåll."
type: docs
weight: 380
url: /sv/java/com.aspose.pdf.facades/pdfcontenteditor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfContentEditor, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfContentEditor, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfContentEditor

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfContentEditor extends SaveableFacade
```

Representerar en klass för att redigera PDF-fils innehåll.

## Fält

| Fält | Beskrivning |
| --- | --- |
| [DOCUMENT_CLOSE](#DOCUMENT_CLOSE) | En dokumenthändelsetyp. Stänger ett dokument. |
| [DOCUMENT_OPEN](#DOCUMENT_OPEN) | En dokumenthändelsetyp. Öppnar ett dokument. |
| [DOCUMENT_PRINTED](#DOCUMENT_PRINTED) | En dokumenthändelsetyp. Utför en åtgärd efter utskrift. |
| [DOCUMENT_SAVED](#DOCUMENT_SAVED) | En dokumenthändelsetyp. Utför en åtgärd efter sparande. |
| [DOCUMENT_WILL_PRINT](#DOCUMENT_WILL_PRINT) | En dokumenthändelsetyp. Utför en åtgärd före utskrift. |
| [DOCUMENT_WILL_SAVE](#DOCUMENT_WILL_SAVE) | En dokumenthändelsetyp. Utför en åtgärd före sparande. |

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [PdfContentEditor](#PdfContentEditor--) | Konstruktorn för PdfContentEditor‑objektet. |
| [PdfContentEditor](#PdfContentEditor-com.aspose.pdf.IDocument-) | Konstruktorn för PdfContentEditor‑objektet. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [addDocumentAdditionalAction](#addDocumentAdditionalAction-java.lang.String-java.lang.String-) | <p> Lägger till en extra åtgärd för dokumenthändelse. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.addDocumentAdditionalAction(PdfContentEditor.DocumentClose, "app.alert('Good-bye!');"); editor.save("example_out.pdf"); </pre> |
| [addDocumentAttachment](#addDocumentAttachment-java.io.InputStream-java.lang.String-java.lang.String-) | <p> Lägger till dokumentbilaga utan annotation. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); InputStream attStream = new FileInputStream("attachment_file.pdf") editor.addDocumentAttachment(attStream, "attachment_file.pdf", "description of attachment_file"); editor.save("example_out.pdf"); </pre> |
| [addDocumentAttachment](#addDocumentAttachment-java.lang.String-java.lang.String-) | <p> Lägger till dokumentbilaga utan annotation. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.addDocumentAttachment("attachment_file.pdf", "description of attachment_file"); editor.save("example_out.pdf"); </pre> |
| [bindPdf](#bindPdf-java.io.InputStream-) | Binder en PDF-ström för redigering. |
| [bindPdf](#bindPdf-java.lang.String-) | Binder en PDF-fil för redigering. |
| [changeViewerPreference](#changeViewerPreference-int-) | <p> Ändrar visningsinställningen. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.changeViewerPreference(ViewerPreference.HideMenubar); editor.changeViewerPreference(ViewerPreference.PageModeUseNone); editor.save("example_out.pdf"); </pre> |
| [close](#close--) | Stänger öppnat dokument. |
| [createApplicationLink](#createApplicationLink-java.awt.Rectangle-java.lang.String-int-) | Skapar en länk för att starta ett program i PDF-dokument. |
| [createApplicationLink](#createApplicationLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-) | Skapar en länk för att starta ett program i PDF-dokument. |
| [createApplicationLink](#createApplicationLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-) | Skapar en länk för att starta ett program i PDF-dokument. |
| [createBookmarksAction](#createBookmarksAction-java.lang.String-java.awt.Color-boolean-boolean-java.lang.String-java.lang.String-java.lang.String-) | Skapar ett bokmärke med den angivna åtgärden. |
| [createCaret](#createCaret-int-java.awt.Rectangle-java.awt.Rectangle-java.lang.String-java.lang.String-java.awt.Color-) | Skapar markörannotation. |
| [createCustomActionLink](#createCustomActionLink-java.awt.Rectangle-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-) | Skapar en länk till anpassade åtgärder i PDF-dokument. |
| [createFileAttachment](#createFileAttachment-java.awt.Rectangle-java.lang.String-java.io.InputStream-java.lang.String-int-java.lang.String-) | Skapar filbilageannotation. |
| [createFileAttachment](#createFileAttachment-java.awt.Rectangle-java.lang.String-java.lang.String-int-java.lang.String-) | Skapar filbilageannotation. |
| [createFreeText](#createFreeText-java.awt.Rectangle-java.lang.String-int-) | Skapar fri text-annotation i PDF-dokument |
| [createJavaScriptLink](#createJavaScriptLink-java.lang.String-java.awt.Rectangle-int-java.awt.Color-) | Skapar en länk till JavaScript i PDF-dokument. |
| [createLine](#createLine-java.awt.Rectangle-java.lang.String-float-float-float-float-int-int-java.awt.Color-java.lang.String-int:A-java.lang.String:A-) | Skapar linjeannotation. |
| [createLocalLink](#createLocalLink-java.awt.Rectangle-int-int-) | Skapar en lokal länk i PDF-dokument. |
| [createLocalLink](#createLocalLink-java.awt.Rectangle-int-int-java.awt.Color-) | Skapar en lokal länk i PDF-dokument. |
| [createLocalLink](#createLocalLink-java.awt.Rectangle-int-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-) | Skapar en lokal länk i PDF-dokument. |
| [createMarkup](#createMarkup-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-) | Skapar markup-annotation i PDF-dokument. |
| [createMovie](#createMovie-java.awt.Rectangle-java.lang.String-int-) |  |
| [createPdfDocumentLink](#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-) | Skapar en länk till en annan PDF-dokumentsida. |
| [createPdfDocumentLink](#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-) | Skapar en länk till en annan PDF-dokumentsida. |
| [createPdfDocumentLink](#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-) | Skapar en länk till en annan PDF-dokumentsida. |
| [createPolygon](#createPolygon-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-) | Skapar polygonannotation. |
| [createPolyLine](#createPolyLine-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-) | Skapar polylinjeannotation. |
| [createPopup](#createPopup-java.awt.Rectangle-java.lang.String-boolean-int-) | Skapar popup-annotation i PDF-dokument. |
| [createRubberStamp](#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.awt.Color-java.io.InputStream-) | Skapar en gummistämpelannotation. |
| [createRubberStamp](#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.awt.Color-java.lang.String-) | Skapar en gummistämpelannotation. |
| [createRubberStamp](#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.lang.String-java.awt.Color-) | Skapar en gummistämpelannotation. |
| [createSound](#createSound-java.awt.Rectangle-java.lang.String-java.lang.String-int-java.lang.String-) |  |
| [createSquareCircle](#createSquareCircle-java.awt.Rectangle-java.lang.String-java.awt.Color-boolean-int-int-) | Skapar fyrkant‑cirkel‑annotation. |
| [createText](#createText-java.awt.Rectangle-java.lang.String-java.lang.String-boolean-java.lang.String-int-) | Skapar textannotation i PDF-dokument |
| [createWebLink](#createWebLink-java.awt.Rectangle-java.lang.String-int-) | Skapar en webblänk i PDF-dokument. |
| [createWebLink](#createWebLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-) | Skapar en webblänk i PDF-dokument. |
| [createWebLink](#createWebLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-) | Skapar en webblänk i PDF-dokument. |
| [deleteAttachments](#deleteAttachments--) | <p> Tar bort alla bilagor i PDF-dokument. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.deleteAttachments(); editor.save("example_out.pdf"); </pre> |
| [deleteImage](#deleteImage--) | <p> Tar bort alla bilder från PDF-dokument. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.deleteImage(); editor.save("example_out.pdf"); </pre> |
| [deleteImage](#deleteImage-int-int:A-) | <p> Tar bort de angivna bilderna på den angivna sidan. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.deleteImage(1, new int[] {1, 2}); editor.save("example_out.pdf"); </pre> |
| [deleteStamp](#deleteStamp-int-int:A-) | <p> Tar bort flera stämplar på den angivna sidan med stämpelindex. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStamp(1, new int[] { 2, 3, 5} ); contentEditor.save("outfile.pdf"); </pre> |
| [deleteStampById](#deleteStampById-int-) | <p> Ta bort stämpel efter ID från alla sidor i dokumentet. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampById(100); contentEditor.save("outfile.pdf"); </pre> |
| [deleteStampById](#deleteStampById-int-int-) | <p> Tar bort stämpel på den angivna sidan efter stämpel-ID. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampById(1, 100); contentEditor.save("outfile.pdf"); </pre> |
| [deleteStampByIds](#deleteStampByIds-int:A-) | <p> Tar bort stämplar med angivna ID:n från alla sidor i dokumentet. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampByIds(new int[] { 102, 103 } ); contentEditor.save("outfile.pdf"); </pre> |
| [deleteStampByIds](#deleteStampByIds-int-int:A-) | <p> Tar bort stämplar på den angivna sidan med flera stämpel-ID:n. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampByIds(1, new int[] { 100, 101 } ); contentEditor.save("outfile.pdf"); </pre> |
| [drawCurve](#drawCurve-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-) | Skapar kurvannotering. |
| [extractLink](#extractLink--) | <p> Extraherar samlingen av Link‑instanser som finns i PDF‑dokumentet. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); List links = editor.extractLink(); for (object obj : links) { Link link = (Link)obj; // work with Link instance } </pre> |
| [getReplaceTextStrategy](#getReplaceTextStrategy--) | Hämta en uppsättning parametrar för ersättningsoperation av text. |
| [getStamps](#getStamps-int-) | Returnerar en array av stämplar på sidan. |
| [getTextEditOptions](#getTextEditOptions--) | Hämtar alternativ för textredigering. |
| [getTextReplaceOptions](#getTextReplaceOptions--) | Hämtar alternativ för textersättning. |
| [getTextSearchOptions](#getTextSearchOptions--) | Hämtar alternativ för textsökning. |
| [getViewerPreference](#getViewerPreference--) | <p> Returnerar visningspreferensen. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); int prefValue = editor.GetViewerPreference(); if ((prefValue & ViewerPreference.PageModeUseOutline) != 0) { // ... } </pre> |
| [hideStampById](#hideStampById-int-int-) | Döljer stämpeln. Efter att den döljs kan stämpelns synlighet återställas med metoden ShowStampById. |
| [moveStamp](#moveStamp-int-int-double-double-) | Ändrar stämpelns position på sidan. |
| [moveStampById](#moveStampById-int-int-double-double-) | Ändrar stämpelns position på sidan. |
| [removeDocumentOpenAction](#removeDocumentOpenAction--) | <p> Tar bort öppningsåtgärden från dokumentet. Denna operation är användbar när man sammanfogar flera dokument som använder en explicit 'GoTo'-åtgärd vid start. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.removeDocumentOpenAction(); editor.save("example_out.pdf"); </pre> |
| [replaceImage](#replaceImage-int-int-java.lang.String-) | <p> Ersätter den angivna bilden på den angivna sidan i PDF‑dokumentet med en annan bild. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.replaceImage(1, 1, "image.jpg"); editor.save("example_out.pdf"); </pre> |
| [replaceText](#replaceText-java.lang.String-int-java.lang.String-) | <p> Ersätter text i PDF-filen på den angivna sidan. </p> <hr> <pre> Exemplet visar hur man ersätter text i PDF-dokumentet på den angivna sidan. // öppna dokument Document doc = new Document(inFile); // skapa PdfContentEditor-objekt för att redigera text PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // ändra text editor.replaceText("hello world", 1, "hi world"); // spara dokument doc.save(outFile); </pre> |
| [replaceText](#replaceText-java.lang.String-int-java.lang.String-com.aspose.pdf.TextState-) | <p> Replaces text in the PDF file on the specified page. {@code TextState} object (font family, color) can be specified to replaced text. </p> <hr> <pre> The example demonstrates how to replace text on the first page of the PDF document and set {@code TextState} text properties for the new text. // open document Document doc = new Document(inFile); com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont("Courier New"); font.isEmbedded ( true); // create PdfContentEditor object to edit text PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // create textState object com.aspose.pdf.TextState textState = new com.aspose.pdf.TextState(); textState.setFont ( font); textState.setFontSize ( 17); textState.setFontStyle ( com.aspose.pdf.FontStyles.Bold \ | com.aspose.pdf.FontStyles.Italic); textState.setForegroundColor ( com.aspose.pdf.Color.getRed()); // ändra text med angivet teckensnitt editor.replaceText("hello world", 1, "hi world", textState); // spara dokument doc.save(outFile); </pre> |
| [replaceText](#replaceText-java.lang.String-java.lang.String-) | <p> Ersätter text i PDF-filen. </p> <hr> <pre> Exemplet visar hur man ersätter text i PDF-dokumentet. Som standard ersätts den första hittade texten. // öppna dokument Document doc = new Document(inFile); // skapa PdfContentEditor-objekt för att redigera text PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // ändra text editor.replaceText("hello world", "hi world"); // spara dokument doc.save(outFile); </pre> |
| [replaceText](#replaceText-java.lang.String-java.lang.String-int-) | <p> Ersätter text i PDF-filen och anger teckenstorlek. </p> <hr> <pre> Exemplet visar hur man ersätter text och anger teckenstorlek för den nya texten. // öppna dokument Document doc = new Document(inFile); // Skapa teckensnitt och markera det för inbäddning com.aspose.pdf.Font font = FontRepository.FindFont("Courier New"); font.isEmbedded ( true); // skapa PdfContentEditor-objekt för att redigera text PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // ändra text med angivet teckensnitt editor.replaceText("hello world", "hi world", 14); // spara dokument doc.save(outFile); </pre> |
| [replaceText](#replaceText-java.lang.String-java.lang.String-com.aspose.pdf.TextState-) | <p> Replaces text in the PDF file using specified {@code TextState} object. </p> <hr> <pre> The example demonstrates how to replace text and set {@code TextState} text properties for the new text. Document doc = new Document(inFile); // Create font and mark it to be embedded com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont("Courier New"); font.isEmbedded ( true); // create PdfContentEditor object to edit text PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // create textState object com.aspose.pdf.TextState textState = new com.aspose.pdf.TextState(); textState.setFont ( font); textState.setFontStyle ( com.aspose.pdf.FontStyles.Bold \ | com.aspose.pdf.FontStyles.Italic); // ändra text med angivet teckensnitt editor.replaceText("hello world", "hi world", textState); // spara dokument doc.save(outFile); </pre> |
| [setReplaceTextStrategy](#setReplaceTextStrategy-com.aspose.pdf.facades.ReplaceTextStrategy-) | Ställ in en uppsättning parametrar för ersättning av text. |
| [setTextEditOptions](#setTextEditOptions-com.aspose.pdf.TextEditOptions-) | Ställer in alternativ för textredigering. |
| [setTextReplaceOptions](#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-) | Ställer in alternativ för textersättning. |
| [setTextSearchOptions](#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-) | Ställer in alternativ för textsökning. |
| [showStampById](#showStampById-int-int-) | Visar stämpel som var dold av HiddenStampById. |

### DOCUMENT_CLOSE {#DOCUMENT_CLOSE}
```
public static final String DOCUMENT_CLOSE
```

En dokumenthändelsetyp. Stänger ett dokument.

### DOCUMENT_OPEN {#DOCUMENT_OPEN}
```
public static final String DOCUMENT_OPEN
```

En dokumenthändelsetyp. Öppnar ett dokument.

### DOCUMENT_PRINTED {#DOCUMENT_PRINTED}
```
public static final String DOCUMENT_PRINTED
```

En dokumenthändelsetyp. Utför en åtgärd efter utskrift.

### DOCUMENT_SAVED {#DOCUMENT_SAVED}
```
public static final String DOCUMENT_SAVED
```

En dokumenthändelsetyp. Utför en åtgärd efter sparande.

### DOCUMENT_WILL_PRINT {#DOCUMENT_WILL_PRINT}
```
public static final String DOCUMENT_WILL_PRINT
```

En dokumenthändelsetyp. Utför en åtgärd före utskrift.

### DOCUMENT_WILL_SAVE {#DOCUMENT_WILL_SAVE}
```
public static final String DOCUMENT_WILL_SAVE
```

En dokumenthändelsetyp. Utför en åtgärd före sparande.

### PdfContentEditor {#PdfContentEditor--}
```
public PdfContentEditor()
```

Konstruktorn för PdfContentEditor‑objektet.

### PdfContentEditor {#PdfContentEditor-com.aspose.pdf.IDocument-}
Konstruktorn för PdfContentEditor‑objektet.

### addDocumentAdditionalAction {#addDocumentAdditionalAction-java.lang.String-java.lang.String-}
<p> Lägger till en extra åtgärd för dokumenthändelse. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.addDocumentAdditionalAction(PdfContentEditor.DocumentClose, "app.alert('Good-bye!');"); editor.save("example_out.pdf"); </pre>

### addDocumentAttachment {#addDocumentAttachment-java.io.InputStream-java.lang.String-java.lang.String-}
<p> Lägger till dokumentbilaga utan annotation. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); InputStream attStream = new FileInputStream("attachment_file.pdf") editor.addDocumentAttachment(attStream, "attachment_file.pdf", "description of attachment_file"); editor.save("example_out.pdf"); </pre>

### addDocumentAttachment {#addDocumentAttachment-java.lang.String-java.lang.String-}
<p> Lägger till dokumentbilaga utan annotation. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.addDocumentAttachment("attachment_file.pdf", "description of attachment_file"); editor.save("example_out.pdf"); </pre>

### bindPdf {#bindPdf-java.io.InputStream-}
Binder en PDF-ström för redigering.

### bindPdf {#bindPdf-java.lang.String-}
Binder en PDF-fil för redigering.

### changeViewerPreference {#changeViewerPreference-int-}
```
public void changeViewerPreference(int viewerAttribution)
```

<p> Ändrar visningsinställningen. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.changeViewerPreference(ViewerPreference.HideMenubar); editor.changeViewerPreference(ViewerPreference.PageModeUseNone); editor.save("example_out.pdf"); </pre>

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| viewerAttribution |  | Visningsattributet som definieras i klassen ViewerPreference. |

### close {#close--}
```
public void close()
```

Stänger öppnat dokument.

### createApplicationLink {#createApplicationLink-java.awt.Rectangle-java.lang.String-int-}
Skapar en länk för att starta ett program i PDF-dokument.

### createApplicationLink {#createApplicationLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-}
Skapar en länk för att starta ett program i PDF-dokument.

### createApplicationLink {#createApplicationLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-}
Skapar en länk för att starta ett program i PDF-dokument.

### createBookmarksAction {#createBookmarksAction-java.lang.String-java.awt.Color-boolean-boolean-java.lang.String-java.lang.String-java.lang.String-}
Skapar ett bokmärke med den angivna åtgärden.

### createCaret {#createCaret-int-java.awt.Rectangle-java.awt.Rectangle-java.lang.String-java.lang.String-java.awt.Color-}
Skapar markörannotation.

### createCustomActionLink {#createCustomActionLink-java.awt.Rectangle-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-}
Skapar en länk till anpassade åtgärder i PDF-dokument.

### createFileAttachment {#createFileAttachment-java.awt.Rectangle-java.lang.String-java.io.InputStream-java.lang.String-int-java.lang.String-}
Skapar filbilageannotation.

### createFileAttachment {#createFileAttachment-java.awt.Rectangle-java.lang.String-java.lang.String-int-java.lang.String-}
Skapar filbilageannotation.

### createFreeText {#createFreeText-java.awt.Rectangle-java.lang.String-int-}
Skapar fri text-annotation i PDF-dokument

### createJavaScriptLink {#createJavaScriptLink-java.lang.String-java.awt.Rectangle-int-java.awt.Color-}
Skapar en länk till JavaScript i PDF-dokument.

### createLine {#createLine-java.awt.Rectangle-java.lang.String-float-float-float-float-int-int-java.awt.Color-java.lang.String-int:A-java.lang.String:A-}
Skapar linjeannotation.

### createLocalLink {#createLocalLink-java.awt.Rectangle-int-int-}
Skapar en lokal länk i PDF-dokument.

### createLocalLink {#createLocalLink-java.awt.Rectangle-int-int-java.awt.Color-}
Skapar en lokal länk i PDF-dokument.

### createLocalLink {#createLocalLink-java.awt.Rectangle-int-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-}
Skapar en lokal länk i PDF-dokument.

### createMarkup {#createMarkup-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-}
Skapar markup-annotation i PDF-dokument.

### createMovie {#createMovie-java.awt.Rectangle-java.lang.String-int-}


### createPdfDocumentLink {#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-}
Skapar en länk till en annan PDF-dokumentsida.

### createPdfDocumentLink {#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-}
Skapar en länk till en annan PDF-dokumentsida.

### createPdfDocumentLink {#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-}
Skapar en länk till en annan PDF-dokumentsida.

### createPolygon {#createPolygon-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-}
Skapar polygonannotation.

### createPolyLine {#createPolyLine-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-}
Skapar polylinjeannotation.

### createPopup {#createPopup-java.awt.Rectangle-java.lang.String-boolean-int-}
Skapar popup-annotation i PDF-dokument.

### createRubberStamp {#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.awt.Color-java.io.InputStream-}
Skapar en gummistämpelannotation.

### createRubberStamp {#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.awt.Color-java.lang.String-}
Skapar en gummistämpelannotation.

### createRubberStamp {#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.lang.String-java.awt.Color-}
Skapar en gummistämpelannotation.

### createSound {#createSound-java.awt.Rectangle-java.lang.String-java.lang.String-int-java.lang.String-}


### createSquareCircle {#createSquareCircle-java.awt.Rectangle-java.lang.String-java.awt.Color-boolean-int-int-}
Skapar fyrkant‑cirkel‑annotation.

### createText {#createText-java.awt.Rectangle-java.lang.String-java.lang.String-boolean-java.lang.String-int-}
Skapar textannotation i PDF-dokument

### createWebLink {#createWebLink-java.awt.Rectangle-java.lang.String-int-}
Skapar en webblänk i PDF-dokument.

### createWebLink {#createWebLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-}
Skapar en webblänk i PDF-dokument.

### createWebLink {#createWebLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-}
Skapar en webblänk i PDF-dokument.

### deleteAttachments {#deleteAttachments--}
```
public void deleteAttachments()
```

<p> Tar bort alla bilagor i PDF-dokument. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.deleteAttachments(); editor.save("example_out.pdf"); </pre>

### deleteImage {#deleteImage--}
```
public void deleteImage()
```

<p> Tar bort alla bilder från PDF-dokument. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.deleteImage(); editor.save("example_out.pdf"); </pre>

### deleteImage {#deleteImage-int-int:A-}
```
public void deleteImage(int pageNumber, int[] index)
```

<p> Tar bort de angivna bilderna på den angivna sidan. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.deleteImage(1, new int[] {1, 2}); editor.save("example_out.pdf"); </pre>

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageNumber |  | Numret på sidan där bilder ska tas bort. |
| index |  | En array representerar bilders index. |

### deleteStamp {#deleteStamp-int-int:A-}
```
public void deleteStamp(int pageNumber, int[] index)
```

<p> Tar bort flera stämplar på den angivna sidan med stämpelindex. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStamp(1, new int[] { 2, 3, 5} ); contentEditor.save("outfile.pdf"); </pre>

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageNumber |  | Sidnummer där stämpeln kommer att tas bort. |
| index |  | Stämpelindex. |

### deleteStampById {#deleteStampById-int-}
```
public void deleteStampById(int stampId)
```

<p> Ta bort stämpel efter ID från alla sidor i dokumentet. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampById(100); contentEditor.save("outfile.pdf"); </pre>

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stampId |  | Identifierare för stämpel som ska tas bort. |

### deleteStampById {#deleteStampById-int-int-}
```
public void deleteStampById(int pageNumber, int stampId)
```

<p> Tar bort stämpel på den angivna sidan efter stämpel-ID. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampById(1, 100); contentEditor.save("outfile.pdf"); </pre>

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageNumber |  | Sidnummer där stämpeln kommer att tas bort. |
| stampId |  | Identifierare för stämpel som ska tas bort. |

### deleteStampByIds {#deleteStampByIds-int:A-}
```
public void deleteStampByIds(int[] stampIds)
```

<p> Tar bort stämplar med angivna ID:n från alla sidor i dokumentet. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampByIds(new int[] { 102, 103 } ); contentEditor.save("outfile.pdf"); </pre>

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stampIds |  | Array av stämpel-ID:n. |

### deleteStampByIds {#deleteStampByIds-int-int:A-}
```
public void deleteStampByIds(int pageNumber, int[] stampIds)
```

<p> Tar bort stämplar på den angivna sidan med flera stämpel-ID:n. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampByIds(1, new int[] { 100, 101 } ); contentEditor.save("outfile.pdf"); </pre>

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageNumber |  | Sidnummer där stämplar kommer att tas bort. |
| stampIds |  | Array av stämpel-ID:n. |

### drawCurve {#drawCurve-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-}
Skapar kurvannotering.

### extractLink {#extractLink--}
```
public List < Annotation > extractLink()
```

<p> Extraherar samlingen av Link‑instanser som finns i PDF‑dokumentet. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); List links = editor.extractLink(); for (object obj : links) { Link link = (Link)obj; // work with Link instance } </pre>

**Returns:**
Samlingen av Link-objekt

### getReplaceTextStrategy {#getReplaceTextStrategy--}
```
public ReplaceTextStrategy getReplaceTextStrategy()
```

Hämta en uppsättning parametrar för ersättningsoperation av text.

**Returns:**
ReplaceTextStrategy-element

### getStamps {#getStamps-int-}
```
public StampInfo [] getStamps(int pageNumber)
```

Returnerar en array av stämplar på sidan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageNumber |  | Sidnummer där stämplar kommer att sökas. |

**Returns:**
Array av stämplar.

### getTextEditOptions {#getTextEditOptions--}
```
public TextEditOptions getTextEditOptions()
```

Hämtar alternativ för textredigering.

**Returns:**
TextEditOptions element

### getTextReplaceOptions {#getTextReplaceOptions--}
```
public TextReplaceOptions getTextReplaceOptions()
```

Hämtar alternativ för textersättning.

**Returns:**
TextReplaceOptions element

### getTextSearchOptions {#getTextSearchOptions--}
```
public TextSearchOptions getTextSearchOptions()
```

Hämtar alternativ för textsökning.

**Returns:**
TextSearchOptions element

### getViewerPreference {#getViewerPreference--}
```
public int getViewerPreference()
```

<p> Returnerar visningspreferensen. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); int prefValue = editor.GetViewerPreference(); if ((prefValue & ViewerPreference.PageModeUseOutline) != 0) { // ... } </pre>

**Returns:**
Returnerar en uppsättning ViewerPrefernece-flaggor

### hideStampById {#hideStampById-int-int-}
```
public void hideStampById(int pageNumber, int stampId)
```

Döljer stämpeln. Efter att den döljs kan stämpelns synlighet återställas med metoden ShowStampById.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageNumber |  | Nummer på sidan. |
| stampId |  | Identifierare för stämpel som ska döljas. |

### moveStamp {#moveStamp-int-int-double-double-}
```
public void moveStamp(int pageNumber, int stampIndex, double x, double y)
```

Ändrar stämpelns position på sidan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageNumber |  | Sidnummer. |
| stampIndex |  | Index för stämpel på sidan. |
| x |  | Ny horisontell position för stämpel. |
| y |  | Ny vertikal position för stämpel. |

### moveStampById {#moveStampById-int-int-double-double-}
```
public void moveStampById(int pageNumber, int stampId, double x, double y)
```

Ändrar stämpelns position på sidan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageNumber |  | Nummer på sidan. |
| stampId |  | Identifierare för stämpel som ska flyttas. |
| x |  | Ny horisontell position för stämpel på sidan. |
| y |  | Ny vertikal position för stämpel på sidan. |

### removeDocumentOpenAction {#removeDocumentOpenAction--}
```
public void removeDocumentOpenAction()
```

<p> Tar bort öppningsåtgärden från dokumentet. Denna operation är användbar när man sammanfogar flera dokument som använder en explicit 'GoTo'-åtgärd vid start. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.removeDocumentOpenAction(); editor.save("example_out.pdf"); </pre>

### replaceImage {#replaceImage-int-int-java.lang.String-}
<p> Ersätter den angivna bilden på den angivna sidan i PDF‑dokumentet med en annan bild. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.replaceImage(1, 1, "image.jpg"); editor.save("example_out.pdf"); </pre>

### replaceText {#replaceText-java.lang.String-int-java.lang.String-}
<p> Ersätter text i PDF-filen på den angivna sidan. </p> <hr> <pre> Exemplet visar hur man ersätter text i PDF-dokumentet på den angivna sidan. // öppna dokument Document doc = new Document(inFile); // skapa PdfContentEditor-objekt för att redigera text PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // ändra text editor.replaceText("hello world", 1, "hi world"); // spara dokument doc.save(outFile); </pre>

### replaceText {#replaceText-java.lang.String-int-java.lang.String-com.aspose.pdf.TextState-}
<p> Ersätter text i PDF-filen på den angivna sidan. {@code TextState} objekt (teckensnittsfamilj, färg) kan specificeras för ersatt text. </p> <hr> <pre> Exemplet visar hur man ersätter text på den första sidan av PDF-dokumentet och sätter {@code TextState} textegenskaper för den nya texten. // open document Document doc = new Document(inFile); com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont(\"Courier New\"); font.isEmbedded ( true); // create PdfContentEditor object to edit text PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // create textState object com.aspose.pdf.TextState textState = new com.aspose.pdf.TextState(); textState.setFont ( font); textState.setFontSize ( 17); textState.setFontStyle ( com.aspose.pdf.FontStyles.Bold | com.aspose.pdf.FontStyles.Italic); textState.setForegroundColor ( com.aspose.pdf.Color.getRed()); // change text with specified font editor.replaceText(\"hello world\", 1, \"hi world\", textState); // save document doc.save(outFile); </pre>

### replaceText {#replaceText-java.lang.String-java.lang.String-}
<p> Ersätter text i PDF-filen. </p> <hr> <pre> Exemplet visar hur man ersätter text i PDF-dokumentet. Som standard ersätts den första hittade texten. // öppna dokument Document doc = new Document(inFile); // skapa PdfContentEditor-objekt för att redigera text PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // ändra text editor.replaceText("hello world", "hi world"); // spara dokument doc.save(outFile); </pre>

### replaceText {#replaceText-java.lang.String-java.lang.String-int-}
<p> Ersätter text i PDF-filen och anger teckenstorlek. </p> <hr> <pre> Exemplet visar hur man ersätter text och anger teckenstorlek för den nya texten. // öppna dokument Document doc = new Document(inFile); // Skapa teckensnitt och markera det för inbäddning com.aspose.pdf.Font font = FontRepository.FindFont("Courier New"); font.isEmbedded ( true); // skapa PdfContentEditor-objekt för att redigera text PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // ändra text med angivet teckensnitt editor.replaceText("hello world", "hi world", 14); // spara dokument doc.save(outFile); </pre>

### replaceText {#replaceText-java.lang.String-java.lang.String-com.aspose.pdf.TextState-}
<p> Ersätter text i PDF-filen med angivet {@code TextState} objekt. </p> <hr> <pre> Exemplet visar hur man ersätter text och sätter {@code TextState} textegenskaper för den nya texten. Document doc = new Document(inFile); // Create font and mark it to be embedded com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont(\"Courier New\"); font.isEmbedded ( true); // create PdfContentEditor object to edit text PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // create textState object com.aspose.pdf.TextState textState = new com.aspose.pdf.TextState(); textState.setFont ( font); textState.setFontStyle ( com.aspose.pdf.FontStyles.Bold | com.aspose.pdf.FontStyles.Italic); // change text with specified font editor.replaceText(\"hello world\", \"hi world\", textState); // save document doc.save(outFile); </pre>

### setReplaceTextStrategy {#setReplaceTextStrategy-com.aspose.pdf.facades.ReplaceTextStrategy-}
Ställ in en uppsättning parametrar för ersättning av text.

### setTextEditOptions {#setTextEditOptions-com.aspose.pdf.TextEditOptions-}
Ställer in alternativ för textredigering.

### setTextReplaceOptions {#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-}
Ställer in alternativ för textersättning.

### setTextSearchOptions {#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-}
Ställer in alternativ för textsökning.

### showStampById {#showStampById-int-int-}
```
public void showStampById(int pageNumber, int stampId)
```

Visar stämpel som var dold av HiddenStampById.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageNumber |  | Nummer på sidan. |
| stampId |  | Identifierare för stämpel som ska visas. |
