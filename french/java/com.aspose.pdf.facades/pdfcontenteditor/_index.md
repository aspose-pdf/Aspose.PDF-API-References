---
title: "PdfContentEditor"
linktitle: "PdfContentEditor"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente une classe pour modifier le contenu d'un fichier PDF."
type: docs
weight: 380
url: /fr/java/com.aspose.pdf.facades/pdfcontenteditor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfContentEditor, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfContentEditor, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfContentEditor

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfContentEditor extends SaveableFacade
```

Représente une classe pour modifier le contenu d'un fichier PDF.

## Champs

| Champ | Description |
| --- | --- |
| [DOCUMENT_CLOSE](#DOCUMENT_CLOSE) | Un type d'événement de document. Ferme un document. |
| [DOCUMENT_OPEN](#DOCUMENT_OPEN) | Un type d'événement de document. Ouvre un document. |
| [DOCUMENT_PRINTED](#DOCUMENT_PRINTED) | Un type d'événement de document. Exécute une action après l'impression. |
| [DOCUMENT_SAVED](#DOCUMENT_SAVED) | Un type d'événement de document. Exécute une action après l'enregistrement. |
| [DOCUMENT_WILL_PRINT](#DOCUMENT_WILL_PRINT) | Un type d'événement de document. Exécute une action avant l'impression. |
| [DOCUMENT_WILL_SAVE](#DOCUMENT_WILL_SAVE) | Un type d'événement de document. Exécute une action avant l'enregistrement. |

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PdfContentEditor](#PdfContentEditor--) | Le constructeur de l'objet PdfContentEditor. |
| [PdfContentEditor](#PdfContentEditor-com.aspose.pdf.IDocument-) | Le constructeur de l'objet PdfContentEditor. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [addDocumentAdditionalAction](#addDocumentAdditionalAction-java.lang.String-java.lang.String-) | <p> Ajoute une action supplémentaire pour l'événement du document. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.addDocumentAdditionalAction(PdfContentEditor.DocumentClose, "app.alert('Good-bye!');"); editor.save("example_out.pdf"); </pre> |
| [addDocumentAttachment](#addDocumentAttachment-java.io.InputStream-java.lang.String-java.lang.String-) | <p> Ajoute une pièce jointe de document sans annotation. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); InputStream attStream = new FileInputStream("attachment_file.pdf") editor.addDocumentAttachment(attStream, "attachment_file.pdf", "description of attachment_file"); editor.save("example_out.pdf"); </pre> |
| [addDocumentAttachment](#addDocumentAttachment-java.lang.String-java.lang.String-) | <p> Ajoute une pièce jointe de document sans annotation. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.addDocumentAttachment("attachment_file.pdf", "description of attachment_file"); editor.save("example_out.pdf"); </pre> |
| [bindPdf](#bindPdf-java.io.InputStream-) | Lie un flux PDF pour l'édition. |
| [bindPdf](#bindPdf-java.lang.String-) | Lie un fichier PDF pour l'édition. |
| [changeViewerPreference](#changeViewerPreference-int-) | <p> Modifie la préférence d'affichage. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.changeViewerPreference(ViewerPreference.HideMenubar); editor.changeViewerPreference(ViewerPreference.PageModeUseNone); editor.save("example_out.pdf"); </pre> |
| [close](#close--) | Ferme le document ouvert. |
| [createApplicationLink](#createApplicationLink-java.awt.Rectangle-java.lang.String-int-) | Crée un lien pour lancer une application dans le document PDF. |
| [createApplicationLink](#createApplicationLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-) | Crée un lien pour lancer une application dans le document PDF. |
| [createApplicationLink](#createApplicationLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-) | Crée un lien pour lancer une application dans le document PDF. |
| [createBookmarksAction](#createBookmarksAction-java.lang.String-java.awt.Color-boolean-boolean-java.lang.String-java.lang.String-java.lang.String-) | Crée un signet avec l'action spécifiée. |
| [createCaret](#createCaret-int-java.awt.Rectangle-java.awt.Rectangle-java.lang.String-java.lang.String-java.awt.Color-) | Crée une annotation de caret. |
| [createCustomActionLink](#createCustomActionLink-java.awt.Rectangle-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-) | Crée un lien vers des actions personnalisées dans le document PDF. |
| [createFileAttachment](#createFileAttachment-java.awt.Rectangle-java.lang.String-java.io.InputStream-java.lang.String-int-java.lang.String-) | Crée une annotation de pièce jointe de fichier. |
| [createFileAttachment](#createFileAttachment-java.awt.Rectangle-java.lang.String-java.lang.String-int-java.lang.String-) | Crée une annotation de pièce jointe de fichier. |
| [createFreeText](#createFreeText-java.awt.Rectangle-java.lang.String-int-) | Crée une annotation de texte libre dans le document PDF |
| [createJavaScriptLink](#createJavaScriptLink-java.lang.String-java.awt.Rectangle-int-java.awt.Color-) | Crée un lien vers JavaScript dans le document PDF. |
| [createLine](#createLine-java.awt.Rectangle-java.lang.String-float-float-float-float-int-int-java.awt.Color-java.lang.String-int:A-java.lang.String:A-) | Crée une annotation de ligne. |
| [createLocalLink](#createLocalLink-java.awt.Rectangle-int-int-) | Crée un lien local dans le document PDF. |
| [createLocalLink](#createLocalLink-java.awt.Rectangle-int-int-java.awt.Color-) | Crée un lien local dans le document PDF. |
| [createLocalLink](#createLocalLink-java.awt.Rectangle-int-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-) | Crée un lien local dans le document PDF. |
| [createMarkup](#createMarkup-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-) | Crée une annotation de balisage dans le document PDF. |
| [createMovie](#createMovie-java.awt.Rectangle-java.lang.String-int-) |  |
| [createPdfDocumentLink](#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-) | Crée un lien vers une autre page de document PDF. |
| [createPdfDocumentLink](#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-) | Crée un lien vers une autre page de document PDF. |
| [createPdfDocumentLink](#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-) | Crée un lien vers une autre page de document PDF. |
| [createPolygon](#createPolygon-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-) | Crée une annotation de polygone. |
| [createPolyLine](#createPolyLine-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-) | Crée une annotation de polyligne. |
| [createPopup](#createPopup-java.awt.Rectangle-java.lang.String-boolean-int-) | Crée une annotation popup dans le document PDF. |
| [createRubberStamp](#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.awt.Color-java.io.InputStream-) | Crée une annotation de tampon en caoutchouc. |
| [createRubberStamp](#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.awt.Color-java.lang.String-) | Crée une annotation de tampon en caoutchouc. |
| [createRubberStamp](#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.lang.String-java.awt.Color-) | Crée une annotation de tampon en caoutchouc. |
| [createSound](#createSound-java.awt.Rectangle-java.lang.String-java.lang.String-int-java.lang.String-) |  |
| [createSquareCircle](#createSquareCircle-java.awt.Rectangle-java.lang.String-java.awt.Color-boolean-int-int-) | Crée une annotation carré-cercle. |
| [createText](#createText-java.awt.Rectangle-java.lang.String-java.lang.String-boolean-java.lang.String-int-) | Crée une annotation de texte dans le document PDF |
| [createWebLink](#createWebLink-java.awt.Rectangle-java.lang.String-int-) | Crée un lien web dans le document PDF. |
| [createWebLink](#createWebLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-) | Crée un lien web dans le document PDF. |
| [createWebLink](#createWebLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-) | Crée un lien web dans le document PDF. |
| [deleteAttachments](#deleteAttachments--) | <p> Supprime toutes les pièces jointes du document PDF. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.deleteAttachments(); editor.save("example_out.pdf"); </pre> |
| [deleteImage](#deleteImage--) | <p> Supprime toutes les images du document PDF. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.deleteImage(); editor.save("example_out.pdf"); </pre> |
| [deleteImage](#deleteImage-int-int:A-) | <p> Supprime les images spécifiées sur la page spécifiée. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.deleteImage(1, new int[] {1, 2}); editor.save("example_out.pdf"); </pre> |
| [deleteStamp](#deleteStamp-int-int:A-) | <p> Supprime plusieurs tampons sur la page spécifiée par les index de tampon. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStamp(1, new int[] { 2, 3, 5} ); contentEditor.save("outfile.pdf"); </pre> |
| [deleteStampById](#deleteStampById-int-) | <p> Supprime le tampon par ID de toutes les pages du document. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampById(100); contentEditor.save("outfile.pdf"); </pre> |
| [deleteStampById](#deleteStampById-int-int-) | <p> Supprime le tampon sur la page spécifiée par l'ID du tampon. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampById(1, 100); contentEditor.save("outfile.pdf"); </pre> |
| [deleteStampByIds](#deleteStampByIds-int:A-) | <p> Supprime les tampons avec les IDs spécifiés de toutes les pages du document. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampByIds(new int[] { 102, 103 } ); contentEditor.save("outfile.pdf"); </pre> |
| [deleteStampByIds](#deleteStampByIds-int-int:A-) | <p> Supprime les tampons sur la page spécifiée par plusieurs IDs de tampon. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampByIds(1, new int[] { 100, 101 } ); contentEditor.save("outfile.pdf"); </pre> |
| [drawCurve](#drawCurve-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-) | Crée une annotation de courbe. |
| [extractLink](#extractLink--) | <p> Extrait la collection d'instances de Link contenues dans le document PDF. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); List links = editor.extractLink(); for (object obj : links) { Link link = (Link)obj; // travailler avec l'instance Link } </pre> |
| [getReplaceTextStrategy](#getReplaceTextStrategy--) | Obtenir un ensemble de paramètres pour l'opération de remplacement de texte |
| [getStamps](#getStamps-int-) | Renvoie le tableau de tampons sur la page. |
| [getTextEditOptions](#getTextEditOptions--) | Obtient les options de modification du texte. |
| [getTextReplaceOptions](#getTextReplaceOptions--) | Obtient les options de remplacement du texte. |
| [getTextSearchOptions](#getTextSearchOptions--) | Obtient les options de recherche de texte. |
| [getViewerPreference](#getViewerPreference--) | <p> Renvoie la préférence d'affichage. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); int prefValue = editor.GetViewerPreference(); if ((prefValue & ViewerPreference.PageModeUseOutline) != 0) { // ... } </pre> |
| [hideStampById](#hideStampById-int-int-) | Masque le tampon. Après masquage, la visibilité du tampon peut être restaurée avec la méthode ShowStampById. |
| [moveStamp](#moveStamp-int-int-double-double-) | Modifie la position du tampon sur la page. |
| [moveStampById](#moveStampById-int-int-double-double-) | Modifie la position du tampon sur la page. |
| [removeDocumentOpenAction](#removeDocumentOpenAction--) | <p> Supprime l'action d'ouverture du document. Cette opération est utile lors de la concaténation de plusieurs documents qui utilisent une action 'GoTo' explicite au démarrage. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.removeDocumentOpenAction(); editor.save("example_out.pdf"); </pre> |
| [replaceImage](#replaceImage-int-int-java.lang.String-) | <p> Remplace l'image spécifiée sur la page spécifiée du document PDF par une autre image. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.replaceImage(1, 1, "image.jpg"); editor.save("example_out.pdf"); </pre> |
| [replaceText](#replaceText-java.lang.String-int-java.lang.String-) | <p> Remplace le texte dans le fichier PDF sur la page spécifiée. </p> <hr> <pre> L'exemple montre comment remplacer du texte dans le document PDF sur la page spécifiée. // ouvrir le document Document doc = new Document(inFile); // créer l'objet PdfContentEditor pour modifier le texte PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // modifier le texte editor.replaceText("hello world", 1, "hi world"); // enregistrer le document doc.save(outFile); </pre> |
| [replaceText](#replaceText-java.lang.String-int-java.lang.String-com.aspose.pdf.TextState-) | <p> Replaces text in the PDF file on the specified page. {@code TextState} object (font family, color) can be specified to replaced text. </p> <hr> <pre> The example demonstrates how to replace text on the first page of the PDF document and set {@code TextState} text properties for the new text. // open document Document doc = new Document(inFile); com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont("Courier New"); font.isEmbedded ( true); // create PdfContentEditor object to edit text PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // create textState object com.aspose.pdf.TextState textState = new com.aspose.pdf.TextState(); textState.setFont ( font); textState.setFontSize ( 17); textState.setFontStyle ( com.aspose.pdf.FontStyles.Bold \ | com.aspose.pdf.FontStyles.Italic); textState.setForegroundColor ( com.aspose.pdf.Color.getRed()); // modifier le texte avec la police spécifiée editor.replaceText("hello world", 1, "hi world", textState); // enregistrer le document doc.save(outFile); </pre> |
| [replaceText](#replaceText-java.lang.String-java.lang.String-) | <p> Remplace le texte dans le fichier PDF. </p> <hr> <pre> L'exemple montre comment remplacer du texte dans un document PDF. Par défaut, il remplace le premier texte trouvé. // ouvrir le document Document doc = new Document(inFile); // créer l'objet PdfContentEditor pour modifier le texte PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // modifier le texte editor.replaceText("hello world", "hi world"); // enregistrer le document doc.save(outFile); </pre> |
| [replaceText](#replaceText-java.lang.String-java.lang.String-int-) | <p> Remplace le texte dans le fichier PDF et définit la taille de police. </p> <hr> <pre> L'exemple montre comment remplacer du texte et définir la taille de police pour le nouveau texte. // ouvrir le document Document doc = new Document(inFile); // créer la police et la marquer pour être incorporée com.aspose.pdf.Font font = FontRepository.FindFont("Courier New"); font.isEmbedded ( true); // créer l'objet PdfContentEditor pour modifier le texte PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // modifier le texte avec la police spécifiée editor.replaceText("hello world", "hi world", 14); // enregistrer le document doc.save(outFile); </pre> |
| [replaceText](#replaceText-java.lang.String-java.lang.String-com.aspose.pdf.TextState-) | <p> Replaces text in the PDF file using specified {@code TextState} object. </p> <hr> <pre> The example demonstrates how to replace text and set {@code TextState} text properties for the new text. Document doc = new Document(inFile); // Create font and mark it to be embedded com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont("Courier New"); font.isEmbedded ( true); // create PdfContentEditor object to edit text PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // create textState object com.aspose.pdf.TextState textState = new com.aspose.pdf.TextState(); textState.setFont ( font); textState.setFontStyle ( com.aspose.pdf.FontStyles.Bold \ | com.aspose.pdf.FontStyles.Italic); // modifier le texte avec la police spécifiée editor.replaceText("hello world", "hi world", textState); // enregistrer le document doc.save(outFile); </pre> |
| [setReplaceTextStrategy](#setReplaceTextStrategy-com.aspose.pdf.facades.ReplaceTextStrategy-) | Définir un ensemble de paramètres pour l'opération de remplacement de texte |
| [setTextEditOptions](#setTextEditOptions-com.aspose.pdf.TextEditOptions-) | Définit les options de modification du texte. |
| [setTextReplaceOptions](#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-) | Définit les options de remplacement du texte. |
| [setTextSearchOptions](#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-) | Définit les options de recherche de texte. |
| [showStampById](#showStampById-int-int-) | Affiche le tampon qui était masqué par HiddenStampById. |

### DOCUMENT_CLOSE {#DOCUMENT_CLOSE}
```
public static final String DOCUMENT_CLOSE
```

Un type d'événement de document. Ferme un document.

### DOCUMENT_OPEN {#DOCUMENT_OPEN}
```
public static final String DOCUMENT_OPEN
```

Un type d'événement de document. Ouvre un document.

### DOCUMENT_PRINTED {#DOCUMENT_PRINTED}
```
public static final String DOCUMENT_PRINTED
```

Un type d'événement de document. Exécute une action après l'impression.

### DOCUMENT_SAVED {#DOCUMENT_SAVED}
```
public static final String DOCUMENT_SAVED
```

Un type d'événement de document. Exécute une action après l'enregistrement.

### DOCUMENT_WILL_PRINT {#DOCUMENT_WILL_PRINT}
```
public static final String DOCUMENT_WILL_PRINT
```

Un type d'événement de document. Exécute une action avant l'impression.

### DOCUMENT_WILL_SAVE {#DOCUMENT_WILL_SAVE}
```
public static final String DOCUMENT_WILL_SAVE
```

Un type d'événement de document. Exécute une action avant l'enregistrement.

### PdfContentEditor {#PdfContentEditor--}
```
public PdfContentEditor()
```

Le constructeur de l'objet PdfContentEditor.

### PdfContentEditor {#PdfContentEditor-com.aspose.pdf.IDocument-}
Le constructeur de l'objet PdfContentEditor.

### addDocumentAdditionalAction {#addDocumentAdditionalAction-java.lang.String-java.lang.String-}
<p> Ajoute une action supplémentaire pour l'événement du document. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.addDocumentAdditionalAction(PdfContentEditor.DocumentClose, "app.alert('Good-bye!');"); editor.save("example_out.pdf"); </pre>

### addDocumentAttachment {#addDocumentAttachment-java.io.InputStream-java.lang.String-java.lang.String-}
<p> Ajoute une pièce jointe de document sans annotation. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); InputStream attStream = new FileInputStream("attachment_file.pdf") editor.addDocumentAttachment(attStream, "attachment_file.pdf", "description of attachment_file"); editor.save("example_out.pdf"); </pre>

### addDocumentAttachment {#addDocumentAttachment-java.lang.String-java.lang.String-}
<p> Ajoute une pièce jointe de document sans annotation. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.addDocumentAttachment("attachment_file.pdf", "description of attachment_file"); editor.save("example_out.pdf"); </pre>

### bindPdf {#bindPdf-java.io.InputStream-}
Lie un flux PDF pour l'édition.

### bindPdf {#bindPdf-java.lang.String-}
Lie un fichier PDF pour l'édition.

### changeViewerPreference {#changeViewerPreference-int-}
```
public void changeViewerPreference(int viewerAttribution)
```

<p> Modifie la préférence d'affichage. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.changeViewerPreference(ViewerPreference.HideMenubar); editor.changeViewerPreference(ViewerPreference.PageModeUseNone); editor.save("example_out.pdf"); </pre>

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| viewerAttribution |  | L'attribution de vue définie dans la classe ViewerPreference. |

### close {#close--}
```
public void close()
```

Ferme le document ouvert.

### createApplicationLink {#createApplicationLink-java.awt.Rectangle-java.lang.String-int-}
Crée un lien pour lancer une application dans le document PDF.

### createApplicationLink {#createApplicationLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-}
Crée un lien pour lancer une application dans le document PDF.

### createApplicationLink {#createApplicationLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-}
Crée un lien pour lancer une application dans le document PDF.

### createBookmarksAction {#createBookmarksAction-java.lang.String-java.awt.Color-boolean-boolean-java.lang.String-java.lang.String-java.lang.String-}
Crée un signet avec l'action spécifiée.

### createCaret {#createCaret-int-java.awt.Rectangle-java.awt.Rectangle-java.lang.String-java.lang.String-java.awt.Color-}
Crée une annotation de caret.

### createCustomActionLink {#createCustomActionLink-java.awt.Rectangle-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-}
Crée un lien vers des actions personnalisées dans le document PDF.

### createFileAttachment {#createFileAttachment-java.awt.Rectangle-java.lang.String-java.io.InputStream-java.lang.String-int-java.lang.String-}
Crée une annotation de pièce jointe de fichier.

### createFileAttachment {#createFileAttachment-java.awt.Rectangle-java.lang.String-java.lang.String-int-java.lang.String-}
Crée une annotation de pièce jointe de fichier.

### createFreeText {#createFreeText-java.awt.Rectangle-java.lang.String-int-}
Crée une annotation de texte libre dans le document PDF

### createJavaScriptLink {#createJavaScriptLink-java.lang.String-java.awt.Rectangle-int-java.awt.Color-}
Crée un lien vers JavaScript dans le document PDF.

### createLine {#createLine-java.awt.Rectangle-java.lang.String-float-float-float-float-int-int-java.awt.Color-java.lang.String-int:A-java.lang.String:A-}
Crée une annotation de ligne.

### createLocalLink {#createLocalLink-java.awt.Rectangle-int-int-}
Crée un lien local dans le document PDF.

### createLocalLink {#createLocalLink-java.awt.Rectangle-int-int-java.awt.Color-}
Crée un lien local dans le document PDF.

### createLocalLink {#createLocalLink-java.awt.Rectangle-int-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-}
Crée un lien local dans le document PDF.

### createMarkup {#createMarkup-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-}
Crée une annotation de balisage dans le document PDF.

### createMovie {#createMovie-java.awt.Rectangle-java.lang.String-int-}


### createPdfDocumentLink {#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-}
Crée un lien vers une autre page de document PDF.

### createPdfDocumentLink {#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-}
Crée un lien vers une autre page de document PDF.

### createPdfDocumentLink {#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-}
Crée un lien vers une autre page de document PDF.

### createPolygon {#createPolygon-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-}
Crée une annotation de polygone.

### createPolyLine {#createPolyLine-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-}
Crée une annotation de polyligne.

### createPopup {#createPopup-java.awt.Rectangle-java.lang.String-boolean-int-}
Crée une annotation popup dans le document PDF.

### createRubberStamp {#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.awt.Color-java.io.InputStream-}
Crée une annotation de tampon en caoutchouc.

### createRubberStamp {#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.awt.Color-java.lang.String-}
Crée une annotation de tampon en caoutchouc.

### createRubberStamp {#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.lang.String-java.awt.Color-}
Crée une annotation de tampon en caoutchouc.

### createSound {#createSound-java.awt.Rectangle-java.lang.String-java.lang.String-int-java.lang.String-}


### createSquareCircle {#createSquareCircle-java.awt.Rectangle-java.lang.String-java.awt.Color-boolean-int-int-}
Crée une annotation carré-cercle.

### createText {#createText-java.awt.Rectangle-java.lang.String-java.lang.String-boolean-java.lang.String-int-}
Crée une annotation de texte dans le document PDF

### createWebLink {#createWebLink-java.awt.Rectangle-java.lang.String-int-}
Crée un lien web dans le document PDF.

### createWebLink {#createWebLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-}
Crée un lien web dans le document PDF.

### createWebLink {#createWebLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-}
Crée un lien web dans le document PDF.

### deleteAttachments {#deleteAttachments--}
```
public void deleteAttachments()
```

<p> Supprime toutes les pièces jointes du document PDF. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.deleteAttachments(); editor.save("example_out.pdf"); </pre>

### deleteImage {#deleteImage--}
```
public void deleteImage()
```

<p> Supprime toutes les images du document PDF. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.deleteImage(); editor.save("example_out.pdf"); </pre>

### deleteImage {#deleteImage-int-int:A-}
```
public void deleteImage(int pageNumber, int[] index)
```

<p> Supprime les images spécifiées sur la page spécifiée. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.deleteImage(1, new int[] {1, 2}); editor.save("example_out.pdf"); </pre>

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pageNumber |  | Le numéro de page sur lequel les images doivent être supprimées. |
| index |  | Un tableau représente les index des images. |

### deleteStamp {#deleteStamp-int-int:A-}
```
public void deleteStamp(int pageNumber, int[] index)
```

<p> Supprime plusieurs tampons sur la page spécifiée par les index de tampon. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStamp(1, new int[] { 2, 3, 5} ); contentEditor.save("outfile.pdf"); </pre>

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pageNumber |  | Numéro de page où le tampon sera supprimé. |
| index |  | Index du tampon. |

### deleteStampById {#deleteStampById-int-}
```
public void deleteStampById(int stampId)
```

<p> Supprime le tampon par ID de toutes les pages du document. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampById(100); contentEditor.save("outfile.pdf"); </pre>

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stampId |  | Identifiant du tampon qui doit être supprimé. |

### deleteStampById {#deleteStampById-int-int-}
```
public void deleteStampById(int pageNumber, int stampId)
```

<p> Supprime le tampon sur la page spécifiée par l'ID du tampon. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampById(1, 100); contentEditor.save("outfile.pdf"); </pre>

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pageNumber |  | Numéro de page où le tampon sera supprimé. |
| stampId |  | Identifiant du tampon qui doit être supprimé. |

### deleteStampByIds {#deleteStampByIds-int:A-}
```
public void deleteStampByIds(int[] stampIds)
```

<p> Supprime les tampons avec les IDs spécifiés de toutes les pages du document. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampByIds(new int[] { 102, 103 } ); contentEditor.save("outfile.pdf"); </pre>

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stampIds |  | Tableau d'ID de tampons. |

### deleteStampByIds {#deleteStampByIds-int-int:A-}
```
public void deleteStampByIds(int pageNumber, int[] stampIds)
```

<p> Supprime les tampons sur la page spécifiée par plusieurs IDs de tampon. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampByIds(1, new int[] { 100, 101 } ); contentEditor.save("outfile.pdf"); </pre>

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pageNumber |  | Numéro de page où les tampons seront supprimés. |
| stampIds |  | Tableau d'ID de tampons. |

### drawCurve {#drawCurve-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-}
Crée une annotation de courbe.

### extractLink {#extractLink--}
```
public List < Annotation > extractLink()
```

<p> Extrait la collection d'instances de Link contenues dans le document PDF. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); List links = editor.extractLink(); for (object obj : links) { Link link = (Link)obj; // travailler avec l'instance Link } </pre>

**Returns:**
La collection d'objets Link

### getReplaceTextStrategy {#getReplaceTextStrategy--}
```
public ReplaceTextStrategy getReplaceTextStrategy()
```

Obtenir un ensemble de paramètres pour l'opération de remplacement de texte

**Returns:**
Élément ReplaceTextStrategy

### getStamps {#getStamps-int-}
```
public StampInfo [] getStamps(int pageNumber)
```

Renvoie le tableau de tampons sur la page.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pageNumber |  | Numéro de page où les tampons seront recherchés. |

**Returns:**
Tableau de tampons.

### getTextEditOptions {#getTextEditOptions--}
```
public TextEditOptions getTextEditOptions()
```

Obtient les options de modification du texte.

**Returns:**
Élément TextEditOptions

### getTextReplaceOptions {#getTextReplaceOptions--}
```
public TextReplaceOptions getTextReplaceOptions()
```

Obtient les options de remplacement du texte.

**Returns:**
Élément TextReplaceOptions

### getTextSearchOptions {#getTextSearchOptions--}
```
public TextSearchOptions getTextSearchOptions()
```

Obtient les options de recherche de texte.

**Returns:**
Élément TextSearchOptions

### getViewerPreference {#getViewerPreference--}
```
public int getViewerPreference()
```

<p> Renvoie la préférence d'affichage. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); int prefValue = editor.GetViewerPreference(); if ((prefValue & ViewerPreference.PageModeUseOutline) != 0) { // ... } </pre>

**Returns:**
Renvoie l'ensemble des indicateurs ViewerPrefernece

### hideStampById {#hideStampById-int-int-}
```
public void hideStampById(int pageNumber, int stampId)
```

Masque le tampon. Après masquage, la visibilité du tampon peut être restaurée avec la méthode ShowStampById.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pageNumber |  | Numéro de la page. |
| stampId |  | Identifiant du tampon qui doit être masqué. |

### moveStamp {#moveStamp-int-int-double-double-}
```
public void moveStamp(int pageNumber, int stampIndex, double x, double y)
```

Modifie la position du tampon sur la page.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pageNumber |  | Numéro de la page. |
| stampIndex |  | Indice du tampon sur la page. |
| x |  | Nouvelle position horizontale du tampon. |
| y |  | Nouvelle position verticale du tampon. |

### moveStampById {#moveStampById-int-int-double-double-}
```
public void moveStampById(int pageNumber, int stampId, double x, double y)
```

Modifie la position du tampon sur la page.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pageNumber |  | Numéro de la page. |
| stampId |  | Identifiant du tampon qui doit être déplacé. |
| x |  | Nouvelle position horizontale du tampon sur la page. |
| y |  | Nouvelle position verticale du tampon sur la page. |

### removeDocumentOpenAction {#removeDocumentOpenAction--}
```
public void removeDocumentOpenAction()
```

<p> Supprime l'action d'ouverture du document. Cette opération est utile lors de la concaténation de plusieurs documents qui utilisent une action 'GoTo' explicite au démarrage. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.removeDocumentOpenAction(); editor.save("example_out.pdf"); </pre>

### replaceImage {#replaceImage-int-int-java.lang.String-}
<p> Remplace l'image spécifiée sur la page spécifiée du document PDF par une autre image. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.replaceImage(1, 1, "image.jpg"); editor.save("example_out.pdf"); </pre>

### replaceText {#replaceText-java.lang.String-int-java.lang.String-}
<p> Remplace le texte dans le fichier PDF sur la page spécifiée. </p> <hr> <pre> L'exemple montre comment remplacer du texte dans le document PDF sur la page spécifiée. // ouvrir le document Document doc = new Document(inFile); // créer l'objet PdfContentEditor pour modifier le texte PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // modifier le texte editor.replaceText("hello world", 1, "hi world"); // enregistrer le document doc.save(outFile); </pre>

### replaceText {#replaceText-java.lang.String-int-java.lang.String-com.aspose.pdf.TextState-}
<p> Remplace le texte dans le fichier PDF sur la page spécifiée. L'objet {@code TextState} (famille de police, couleur) peut être spécifié pour le texte remplacé. </p> <hr> <pre> L'exemple montre comment remplacer le texte sur la première page du document PDF et définir les propriétés de texte {@code TextState} pour le nouveau texte. // open document Document doc = new Document(inFile); com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont("Courier New"); font.isEmbedded ( true); // create PdfContentEditor object to edit text PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // create textState object com.aspose.pdf.TextState textState = new com.aspose.pdf.TextState(); textState.setFont ( font); textState.setFontSize ( 17); textState.setFontStyle ( com.aspose.pdf.FontStyles.Bold | com.aspose.pdf.FontStyles.Italic); textState.setForegroundColor ( com.aspose.pdf.Color.getRed()); // change text with specified font editor.replaceText("hello world", 1, "hi world", textState); // save document doc.save(outFile); </pre>

### replaceText {#replaceText-java.lang.String-java.lang.String-}
<p> Remplace le texte dans le fichier PDF. </p> <hr> <pre> L'exemple montre comment remplacer du texte dans un document PDF. Par défaut, il remplace le premier texte trouvé. // ouvrir le document Document doc = new Document(inFile); // créer l'objet PdfContentEditor pour modifier le texte PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // modifier le texte editor.replaceText("hello world", "hi world"); // enregistrer le document doc.save(outFile); </pre>

### replaceText {#replaceText-java.lang.String-java.lang.String-int-}
<p> Remplace le texte dans le fichier PDF et définit la taille de police. </p> <hr> <pre> L'exemple montre comment remplacer du texte et définir la taille de police pour le nouveau texte. // ouvrir le document Document doc = new Document(inFile); // créer la police et la marquer pour être incorporée com.aspose.pdf.Font font = FontRepository.FindFont("Courier New"); font.isEmbedded ( true); // créer l'objet PdfContentEditor pour modifier le texte PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // modifier le texte avec la police spécifiée editor.replaceText("hello world", "hi world", 14); // enregistrer le document doc.save(outFile); </pre>

### replaceText {#replaceText-java.lang.String-java.lang.String-com.aspose.pdf.TextState-}
<p> Remplace le texte dans le fichier PDF en utilisant l'objet {@code TextState} spécifié. </p> <hr> <pre> L'exemple montre comment remplacer le texte et définir les propriétés de texte {@code TextState} pour le nouveau texte. Document doc = new Document(inFile); // Create font and mark it to be embedded com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont("Courier New"); font.isEmbedded ( true); // create PdfContentEditor object to edit text PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // create textState object com.aspose.pdf.TextState textState = new com.aspose.pdf.TextState(); textState.setFont ( font); textState.setFontStyle ( com.aspose.pdf.FontStyles.Bold | com.aspose.pdf.FontStyles.Italic); // change text with specified font editor.replaceText("hello world", "hi world", textState); // save document doc.save(outFile); </pre>

### setReplaceTextStrategy {#setReplaceTextStrategy-com.aspose.pdf.facades.ReplaceTextStrategy-}
Définir un ensemble de paramètres pour l'opération de remplacement de texte

### setTextEditOptions {#setTextEditOptions-com.aspose.pdf.TextEditOptions-}
Définit les options de modification du texte.

### setTextReplaceOptions {#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-}
Définit les options de remplacement du texte.

### setTextSearchOptions {#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-}
Définit les options de recherche de texte.

### showStampById {#showStampById-int-int-}
```
public void showStampById(int pageNumber, int stampId)
```

Affiche le tampon qui était masqué par HiddenStampById.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pageNumber |  | Numéro de la page. |
| stampId |  | Identifiant du tampon qui doit être affiché. |
