---
title: "PredefinedAction"
linktitle: "PredefinedAction"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Definisce diverse azioni che possono essere attivate da un file PDF."
type: docs
weight: 3960
url: /it/java/com.aspose.pdf/predefinedaction/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < PredefinedAction > com.aspose.pdf.PredefinedAction, java.lang.Enum < PredefinedAction >, com.aspose.pdf.PredefinedAction

**All Implemented Interfaces:**
Serializable, Comparable < PredefinedAction >

```
public enum PredefinedAction extends Enum < PredefinedAction >
```

Definisce diverse azioni che possono essere attivate da un file PDF.

## Campi

| Campo | Descrizione |
| --- | --- |
| [Bookmarks_ExpanCurrentBookmark](#Bookmarks_ExpanCurrentBookmark) | Un'azione denominata per trovare il segnalibro corrente. |
| [Bookmarks_HightlightCurrentBookmark](#Bookmarks_HightlightCurrentBookmark) | Un'azione denominata per evidenziare il segnalibro corrente. |
| [Document_AttachFile](#Document_AttachFile) | Un'azione denominata per aggiungere un allegato file. |
| [Document_CropPages](#Document_CropPages) | Un'azione denominata per ritagliare le pagine del documento. |
| [Document_DeletePages](#Document_DeletePages) | Un'azione denominata per eliminare le pagine del documento. |
| [Document_ExtractPages](#Document_ExtractPages) | Un'azione denominata per estrarre le pagine del documento. |
| [Document_InsertPages](#Document_InsertPages) | Un'azione denominata per inserire pagine da un documento. |
| [Document_ReplacePages](#Document_ReplacePages) | Un'azione denominata per sostituire le pagine del documento. |
| [Document_RotatePages](#Document_RotatePages) | Un'azione denominata per ruotare le pagine del documento. |
| [Edit_CheckSpelling_InComFieldEdit](#Edit_CheckSpelling_InComFieldEdit) | Un'azione denominata per controllare l'ortografia nei commenti. |
| [Edit_Find](#Edit_Find) | Un'azione denominata per trovare. |
| [Edit_Preferences](#Edit_Preferences) | Un'azione denominata per modificare le preferenze. |
| [Edit_Search](#Edit_Search) | Un'azione denominata per la ricerca. |
| [File_AttachToEmail](#File_AttachToEmail) | Un'azione denominata per allegare il documento pdf corrente a un messaggio email. |
| [File_Close](#File_Close) | Un'azione denominata per chiudere il documento. |
| [File_CreatePDF_FromScanner](#File_CreatePDF_FromScanner) | Un'azione denominata per creare un documento pdf dallo scanner. |
| [File_CreatePDF_FromWebPage](#File_CreatePDF_FromWebPage) | Un'azione denominata per creare un documento pdf da una pagina web. |
| [File_Exit](#File_Exit) | Un'azione denominata per uscire dal lettore pdf. |
| [File_Organizer_OpenOrganizer](#File_Organizer_OpenOrganizer) | Un'azione denominata per aprire l'organizzatore. |
| [File_Print](#File_Print) | Un'azione denominata per stampare il documento. |
| [File_Properties](#File_Properties) | Un'azione denominata per aprire le proprietà del documento. |
| [File_SaveAs](#File_SaveAs) | Un'azione denominata per salvare il documento con un altro nome. |
| [FirstPage](#FirstPage) | Un'azione denominata per andare alla prima pagina. |
| [LastPage](#LastPage) | Un'azione denominata per andare all'ultima pagina. |
| [Miscellaneous_ZoomIn](#Miscellaneous_ZoomIn) | Un'azione denominata per ingrandire il documento. |
| [Miscellaneous_ZoomOut](#Miscellaneous_ZoomOut) | Un'azione denominata per ridurre il documento. |
| [NextPage](#NextPage) | Un'azione denominata per andare alla pagina successiva. |
| [PageImages_PrintPages](#PageImages_PrintPages) | Un'azione denominata per stampare le pagine del documento. |
| [PrevPage](#PrevPage) | Un'azione denominata per andare alla pagina precedente. |
| [Print](#Print) | Un'azione denominata per aprire una finestra di stampa. |
| [PrintDialog](#PrintDialog) | Un'azione denominata per aprire una finestra di stampa (JavaScript). |
| [View_GoTo_NextView](#View_GoTo_NextView) | Un'azione denominata per andare alla vista successiva. |
| [View_GoTo_Page](#View_GoTo_Page) | Un'azione denominata per andare alla pagina specifica. |
| [View_GoTo_PreDocument](#View_GoTo_PreDocument) | Un'azione denominata per andare al documento precedente. |
| [View_GoTo_PreView](#View_GoTo_PreView) | Un'azione denominata per andare alla vista precedente. |
| [View_NavigationPanels_Articles](#View_NavigationPanels_Articles) | Un'azione denominata per mostrare/nascondere il pannello articoli. |
| [View_NavigationPanels_Attachments](#View_NavigationPanels_Attachments) | Un'azione denominata per mostrare/nascondere il pannello allegati. |
| [View_NavigationPanels_Boomarks](#View_NavigationPanels_Boomarks) | Un'azione denominata per mostrare/nascondere il pannello segnalibri. |
| [View_NavigationPanels_Comments](#View_NavigationPanels_Comments) | Un'azione denominata per mostrare/nascondere il pannello commenti. |
| [View_NavigationPanels_Fields](#View_NavigationPanels_Fields) | Un'azione denominata per mostrare/nascondere il pannello campi. |
| [View_NavigationPanels_Layers](#View_NavigationPanels_Layers) | Un'azione denominata per mostrare/nascondere il pannello livelli. |
| [View_NavigationPanels_ModelTree](#View_NavigationPanels_ModelTree) | Un'azione denominata per mostrare/nascondere il pannello albero del modello. |
| [View_NavigationPanels_Pages](#View_NavigationPanels_Pages) | Un'azione denominata per mostrare/nascondere il pannello pagine. |
| [View_NavigationPanels_Signatures](#View_NavigationPanels_Signatures) | Un'azione denominata per mostrare/nascondere il pannello delle firme. |
| [View_PageDisplay_SinglePage](#View_PageDisplay_SinglePage) | Un'azione denominata per visualizzare una singola pagina. |
| [View_PageDisplay_SinglePageContinuous](#View_PageDisplay_SinglePageContinuous) | Un'azione denominata per visualizzare una singola pagina continua. |
| [View_PageDisplay_TwoUp](#View_PageDisplay_TwoUp) | Un'azione denominata per visualizzare le pagine in modalità Two-Up. |
| [View_PageDisplay_TwoUpContinuous](#View_PageDisplay_TwoUpContinuous) | Un'azione denominata per visualizzare le pagine in modalità Two-Up continua. |
| [View_Toolbars_AdvanceEditing](#View_Toolbars_AdvanceEditing) | Un'azione denominata per mostrare/nascondere la barra degli strumenti di modifica avanzata. |
| [View_Toolbars_CommentMarkup](#View_Toolbars_CommentMarkup) | Un'azione denominata per mostrare/nascondere la barra degli strumenti di commento. |
| [View_Toolbars_Edit](#View_Toolbars_Edit) | Un'azione denominata per mostrare/nascondere la barra degli strumenti di modifica. |
| [View_Toolbars_File](#View_Toolbars_File) | Un'azione denominata per mostrare/nascondere la barra degli strumenti file. |
| [View_Toolbars_Find](#View_Toolbars_Find) | Un'azione denominata per mostrare/nascondere la barra degli strumenti di ricerca. |
| [View_Toolbars_Forms](#View_Toolbars_Forms) | Un'azione denominata per mostrare/nascondere la barra degli strumenti dei moduli. |
| [View_Toolbars_Measuring](#View_Toolbars_Measuring) | Un'azione denominata per mostrare/nascondere la barra degli strumenti di misurazione. |
| [View_Toolbars_ObjectData](#View_Toolbars_ObjectData) | Un'azione denominata per mostrare/nascondere la barra degli strumenti dei dati oggetto. |
| [View_Toolbars_PageDisplay](#View_Toolbars_PageDisplay) | Un'azione denominata per mostrare/nascondere la barra degli strumenti di visualizzazione pagina. |
| [View_Toolbars_PageNavigation](#View_Toolbars_PageNavigation) | Un'azione denominata per mostrare/nascondere la barra degli strumenti di navigazione. |
| [View_Toolbars_PrintProduction](#View_Toolbars_PrintProduction) | Un'azione denominata per mostrare/nascondere la barra degli strumenti di stampa e produzione. |
| [View_Toolbars_PropertiesBar](#View_Toolbars_PropertiesBar) | Un'azione denominata per mostrare/nascondere la barra degli strumenti delle proprietà. |
| [View_Toolbars_Redaction](#View_Toolbars_Redaction) | Un'azione denominata per mostrare/nascondere la barra degli strumenti di redazione. |
| [View_Toolbars_SelectZoom](#View_Toolbars_SelectZoom) | Un'azione denominata per mostrare/nascondere la barra degli strumenti di selezione e zoom. |
| [View_Toolbars_Tasks](#View_Toolbars_Tasks) | Un'azione denominata per mostrare/nascondere la barra degli strumenti delle attività. |
| [View_Toolbars_Typewriter](#View_Toolbars_Typewriter) | Un'azione denominata per mostrare/nascondere la barra degli strumenti della macchina da scrivere. |
| [View_Zoom_ActualSize](#View_Zoom_ActualSize) | Un'azione denominata per visualizzare le pagine nella dimensione reale. |
| [View_Zoom_FitHeight](#View_Zoom_FitHeight) | Un'azione denominata per adattare la pagina all'altezza. |
| [View_Zoom_FitPage](#View_Zoom_FitPage) | Un'azione denominata per adattare la pagina. |
| [View_Zoom_FitVisible](#View_Zoom_FitVisible) | Un'azione denominata per adattare la visibilità della pagina. |
| [View_Zoom_FitWidth](#View_Zoom_FitWidth) | Un'azione denominata per adattare la pagina alla larghezza. |
| [View_Zoom_ZoomTo](#View_Zoom_ZoomTo) | Un'azione denominata per ingrandire. |
| [Window_FullScreenMode](#Window_FullScreenMode) | Un'azione denominata per visualizzare il documento in modalità a schermo intero. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | Restituisce la costante enum di questo tipo con il nome specificato. |
| [values](#values--) | Restituisce un array contenente le costanti di questo tipo enum, nell'ordine in cui sono dichiarate. |

### Bookmarks_ExpanCurrentBookmark {#Bookmarks_ExpanCurrentBookmark}
```
public static final PredefinedAction Bookmarks_ExpanCurrentBookmark
```

Un'azione denominata per trovare il segnalibro corrente.

### Bookmarks_HightlightCurrentBookmark {#Bookmarks_HightlightCurrentBookmark}
```
public static final PredefinedAction Bookmarks_HightlightCurrentBookmark
```

Un'azione denominata per evidenziare il segnalibro corrente.

### Document_AttachFile {#Document_AttachFile}
```
public static final PredefinedAction Document_AttachFile
```

Un'azione denominata per aggiungere un allegato file.

### Document_CropPages {#Document_CropPages}
```
public static final PredefinedAction Document_CropPages
```

Un'azione denominata per ritagliare le pagine del documento.

### Document_DeletePages {#Document_DeletePages}
```
public static final PredefinedAction Document_DeletePages
```

Un'azione denominata per eliminare le pagine del documento.

### Document_ExtractPages {#Document_ExtractPages}
```
public static final PredefinedAction Document_ExtractPages
```

Un'azione denominata per estrarre le pagine del documento.

### Document_InsertPages {#Document_InsertPages}
```
public static final PredefinedAction Document_InsertPages
```

Un'azione denominata per inserire pagine da un documento.

### Document_ReplacePages {#Document_ReplacePages}
```
public static final PredefinedAction Document_ReplacePages
```

Un'azione denominata per sostituire le pagine del documento.

### Document_RotatePages {#Document_RotatePages}
```
public static final PredefinedAction Document_RotatePages
```

Un'azione denominata per ruotare le pagine del documento.

### Edit_CheckSpelling_InComFieldEdit {#Edit_CheckSpelling_InComFieldEdit}
```
public static final PredefinedAction Edit_CheckSpelling_InComFieldEdit
```

Un'azione denominata per controllare l'ortografia nei commenti.

### Edit_Find {#Edit_Find}
```
public static final PredefinedAction Edit_Find
```

Un'azione denominata per trovare.

### Edit_Preferences {#Edit_Preferences}
```
public static final PredefinedAction Edit_Preferences
```

Un'azione denominata per modificare le preferenze.

### Edit_Search {#Edit_Search}
```
public static final PredefinedAction Edit_Search
```

Un'azione denominata per la ricerca.

### File_AttachToEmail {#File_AttachToEmail}
```
public static final PredefinedAction File_AttachToEmail
```

Un'azione denominata per allegare il documento pdf corrente a un messaggio email.

### File_Close {#File_Close}
```
public static final PredefinedAction File_Close
```

Un'azione denominata per chiudere il documento.

### File_CreatePDF_FromScanner {#File_CreatePDF_FromScanner}
```
public static final PredefinedAction File_CreatePDF_FromScanner
```

Un'azione denominata per creare un documento pdf dallo scanner.

### File_CreatePDF_FromWebPage {#File_CreatePDF_FromWebPage}
```
public static final PredefinedAction File_CreatePDF_FromWebPage
```

Un'azione denominata per creare un documento pdf da una pagina web.

### File_Exit {#File_Exit}
```
public static final PredefinedAction File_Exit
```

Un'azione denominata per uscire dal lettore pdf.

### File_Organizer_OpenOrganizer {#File_Organizer_OpenOrganizer}
```
public static final PredefinedAction File_Organizer_OpenOrganizer
```

Un'azione denominata per aprire l'organizzatore.

### File_Print {#File_Print}
```
public static final PredefinedAction File_Print
```

Un'azione denominata per stampare il documento.

### File_Properties {#File_Properties}
```
public static final PredefinedAction File_Properties
```

Un'azione denominata per aprire le proprietà del documento.

### File_SaveAs {#File_SaveAs}
```
public static final PredefinedAction File_SaveAs
```

Un'azione denominata per salvare il documento con un altro nome.

### FirstPage {#FirstPage}
```
public static final PredefinedAction FirstPage
```

Un'azione denominata per andare alla prima pagina.

### LastPage {#LastPage}
```
public static final PredefinedAction LastPage
```

Un'azione denominata per andare all'ultima pagina.

### Miscellaneous_ZoomIn {#Miscellaneous_ZoomIn}
```
public static final PredefinedAction Miscellaneous_ZoomIn
```

Un'azione denominata per ingrandire il documento.

### Miscellaneous_ZoomOut {#Miscellaneous_ZoomOut}
```
public static final PredefinedAction Miscellaneous_ZoomOut
```

Un'azione denominata per ridurre il documento.

### NextPage {#NextPage}
```
public static final PredefinedAction NextPage
```

Un'azione denominata per andare alla pagina successiva.

### PageImages_PrintPages {#PageImages_PrintPages}
```
public static final PredefinedAction PageImages_PrintPages
```

Un'azione denominata per stampare le pagine del documento.

### PrevPage {#PrevPage}
```
public static final PredefinedAction PrevPage
```

Un'azione denominata per andare alla pagina precedente.

### Print {#Print}
```
public static final PredefinedAction Print
```

Un'azione denominata per aprire una finestra di stampa.

### PrintDialog {#PrintDialog}
```
public static final PredefinedAction PrintDialog
```

Un'azione denominata per aprire una finestra di stampa (JavaScript).

### View_GoTo_NextView {#View_GoTo_NextView}
```
public static final PredefinedAction View_GoTo_NextView
```

Un'azione denominata per andare alla vista successiva.

### View_GoTo_Page {#View_GoTo_Page}
```
public static final PredefinedAction View_GoTo_Page
```

Un'azione denominata per andare alla pagina specifica.

### View_GoTo_PreDocument {#View_GoTo_PreDocument}
```
public static final PredefinedAction View_GoTo_PreDocument
```

Un'azione denominata per andare al documento precedente.

### View_GoTo_PreView {#View_GoTo_PreView}
```
public static final PredefinedAction View_GoTo_PreView
```

Un'azione denominata per andare alla vista precedente.

### View_NavigationPanels_Articles {#View_NavigationPanels_Articles}
```
public static final PredefinedAction View_NavigationPanels_Articles
```

Un'azione denominata per mostrare/nascondere il pannello articoli.

### View_NavigationPanels_Attachments {#View_NavigationPanels_Attachments}
```
public static final PredefinedAction View_NavigationPanels_Attachments
```

Un'azione denominata per mostrare/nascondere il pannello allegati.

### View_NavigationPanels_Boomarks {#View_NavigationPanels_Boomarks}
```
public static final PredefinedAction View_NavigationPanels_Boomarks
```

Un'azione denominata per mostrare/nascondere il pannello segnalibri.

### View_NavigationPanels_Comments {#View_NavigationPanels_Comments}
```
public static final PredefinedAction View_NavigationPanels_Comments
```

Un'azione denominata per mostrare/nascondere il pannello commenti.

### View_NavigationPanels_Fields {#View_NavigationPanels_Fields}
```
public static final PredefinedAction View_NavigationPanels_Fields
```

Un'azione denominata per mostrare/nascondere il pannello campi.

### View_NavigationPanels_Layers {#View_NavigationPanels_Layers}
```
public static final PredefinedAction View_NavigationPanels_Layers
```

Un'azione denominata per mostrare/nascondere il pannello livelli.

### View_NavigationPanels_ModelTree {#View_NavigationPanels_ModelTree}
```
public static final PredefinedAction View_NavigationPanels_ModelTree
```

Un'azione denominata per mostrare/nascondere il pannello albero del modello.

### View_NavigationPanels_Pages {#View_NavigationPanels_Pages}
```
public static final PredefinedAction View_NavigationPanels_Pages
```

Un'azione denominata per mostrare/nascondere il pannello pagine.

### View_NavigationPanels_Signatures {#View_NavigationPanels_Signatures}
```
public static final PredefinedAction View_NavigationPanels_Signatures
```

Un'azione denominata per mostrare/nascondere il pannello delle firme.

### View_PageDisplay_SinglePage {#View_PageDisplay_SinglePage}
```
public static final PredefinedAction View_PageDisplay_SinglePage
```

Un'azione denominata per visualizzare una singola pagina.

### View_PageDisplay_SinglePageContinuous {#View_PageDisplay_SinglePageContinuous}
```
public static final PredefinedAction View_PageDisplay_SinglePageContinuous
```

Un'azione denominata per visualizzare una singola pagina continua.

### View_PageDisplay_TwoUp {#View_PageDisplay_TwoUp}
```
public static final PredefinedAction View_PageDisplay_TwoUp
```

Un'azione denominata per visualizzare le pagine in modalità Two-Up.

### View_PageDisplay_TwoUpContinuous {#View_PageDisplay_TwoUpContinuous}
```
public static final PredefinedAction View_PageDisplay_TwoUpContinuous
```

Un'azione denominata per visualizzare le pagine in modalità Two-Up continua.

### View_Toolbars_AdvanceEditing {#View_Toolbars_AdvanceEditing}
```
public static final PredefinedAction View_Toolbars_AdvanceEditing
```

Un'azione denominata per mostrare/nascondere la barra degli strumenti di modifica avanzata.

### View_Toolbars_CommentMarkup {#View_Toolbars_CommentMarkup}
```
public static final PredefinedAction View_Toolbars_CommentMarkup
```

Un'azione denominata per mostrare/nascondere la barra degli strumenti di commento.

### View_Toolbars_Edit {#View_Toolbars_Edit}
```
public static final PredefinedAction View_Toolbars_Edit
```

Un'azione denominata per mostrare/nascondere la barra degli strumenti di modifica.

### View_Toolbars_File {#View_Toolbars_File}
```
public static final PredefinedAction View_Toolbars_File
```

Un'azione denominata per mostrare/nascondere la barra degli strumenti file.

### View_Toolbars_Find {#View_Toolbars_Find}
```
public static final PredefinedAction View_Toolbars_Find
```

Un'azione denominata per mostrare/nascondere la barra degli strumenti di ricerca.

### View_Toolbars_Forms {#View_Toolbars_Forms}
```
public static final PredefinedAction View_Toolbars_Forms
```

Un'azione denominata per mostrare/nascondere la barra degli strumenti dei moduli.

### View_Toolbars_Measuring {#View_Toolbars_Measuring}
```
public static final PredefinedAction View_Toolbars_Measuring
```

Un'azione denominata per mostrare/nascondere la barra degli strumenti di misurazione.

### View_Toolbars_ObjectData {#View_Toolbars_ObjectData}
```
public static final PredefinedAction View_Toolbars_ObjectData
```

Un'azione denominata per mostrare/nascondere la barra degli strumenti dei dati oggetto.

### View_Toolbars_PageDisplay {#View_Toolbars_PageDisplay}
```
public static final PredefinedAction View_Toolbars_PageDisplay
```

Un'azione denominata per mostrare/nascondere la barra degli strumenti di visualizzazione pagina.

### View_Toolbars_PageNavigation {#View_Toolbars_PageNavigation}
```
public static final PredefinedAction View_Toolbars_PageNavigation
```

Un'azione denominata per mostrare/nascondere la barra degli strumenti di navigazione.

### View_Toolbars_PrintProduction {#View_Toolbars_PrintProduction}
```
public static final PredefinedAction View_Toolbars_PrintProduction
```

Un'azione denominata per mostrare/nascondere la barra degli strumenti di stampa e produzione.

### View_Toolbars_PropertiesBar {#View_Toolbars_PropertiesBar}
```
public static final PredefinedAction View_Toolbars_PropertiesBar
```

Un'azione denominata per mostrare/nascondere la barra degli strumenti delle proprietà.

### View_Toolbars_Redaction {#View_Toolbars_Redaction}
```
public static final PredefinedAction View_Toolbars_Redaction
```

Un'azione denominata per mostrare/nascondere la barra degli strumenti di redazione.

### View_Toolbars_SelectZoom {#View_Toolbars_SelectZoom}
```
public static final PredefinedAction View_Toolbars_SelectZoom
```

Un'azione denominata per mostrare/nascondere la barra degli strumenti di selezione e zoom.

### View_Toolbars_Tasks {#View_Toolbars_Tasks}
```
public static final PredefinedAction View_Toolbars_Tasks
```

Un'azione denominata per mostrare/nascondere la barra degli strumenti delle attività.

### View_Toolbars_Typewriter {#View_Toolbars_Typewriter}
```
public static final PredefinedAction View_Toolbars_Typewriter
```

Un'azione denominata per mostrare/nascondere la barra degli strumenti della macchina da scrivere.

### View_Zoom_ActualSize {#View_Zoom_ActualSize}
```
public static final PredefinedAction View_Zoom_ActualSize
```

Un'azione denominata per visualizzare le pagine nella dimensione reale.

### View_Zoom_FitHeight {#View_Zoom_FitHeight}
```
public static final PredefinedAction View_Zoom_FitHeight
```

Un'azione denominata per adattare la pagina all'altezza.

### View_Zoom_FitPage {#View_Zoom_FitPage}
```
public static final PredefinedAction View_Zoom_FitPage
```

Un'azione denominata per adattare la pagina.

### View_Zoom_FitVisible {#View_Zoom_FitVisible}
```
public static final PredefinedAction View_Zoom_FitVisible
```

Un'azione denominata per adattare la visibilità della pagina.

### View_Zoom_FitWidth {#View_Zoom_FitWidth}
```
public static final PredefinedAction View_Zoom_FitWidth
```

Un'azione denominata per adattare la pagina alla larghezza.

### View_Zoom_ZoomTo {#View_Zoom_ZoomTo}
```
public static final PredefinedAction View_Zoom_ZoomTo
```

Un'azione denominata per ingrandire.

### Window_FullScreenMode {#Window_FullScreenMode}
```
public static final PredefinedAction Window_FullScreenMode
```

Un'azione denominata per visualizzare il documento in modalità a schermo intero.

### getByValue {#getByValue-int-}
```
public static PredefinedAction getByValue(int value)
```



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  |  |

### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
Restituisce la costante enum di questo tipo con il nome specificato.

### values {#values--}
```
public static PredefinedAction [] values()
```

Restituisce un array contenente le costanti di questo tipo enum, nell'ordine in cui sono dichiarate.

**Returns:**
un array contenente le costanti di questo tipo enum, nell'ordine in cui sono dichiarate
