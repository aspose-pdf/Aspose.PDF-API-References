---
title: "PredefinedAction"
linktitle: "PredefinedAction"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Definiert verschiedene Aktionen, die aus einer PDF-Datei ausgelöst werden können."
type: docs
weight: 3960
url: /de/java/com.aspose.pdf/predefinedaction/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < PredefinedAction > com.aspose.pdf.PredefinedAction, java.lang.Enum < PredefinedAction >, com.aspose.pdf.PredefinedAction

**All Implemented Interfaces:**
Serializable, Comparable < PredefinedAction >

```
public enum PredefinedAction extends Enum < PredefinedAction >
```

Definiert verschiedene Aktionen, die aus einer PDF-Datei ausgelöst werden können.

## Felder

| Feld | Beschreibung |
| --- | --- |
| [Bookmarks_ExpanCurrentBookmark](#Bookmarks_ExpanCurrentBookmark) | Eine benannte Aktion, um das aktuelle Lesezeichen zu finden. |
| [Bookmarks_HightlightCurrentBookmark](#Bookmarks_HightlightCurrentBookmark) | Eine benannte Aktion, um das aktuelle Lesezeichen hervorzuheben. |
| [Document_AttachFile](#Document_AttachFile) | Eine benannte Aktion, um einen Dateianhang hinzuzufügen. |
| [Document_CropPages](#Document_CropPages) | Eine benannte Aktion, um Dokumentseiten zuzuschneiden. |
| [Document_DeletePages](#Document_DeletePages) | Eine benannte Aktion zum Löschen von Dokumentseiten. |
| [Document_ExtractPages](#Document_ExtractPages) | Eine benannte Aktion zum Extrahieren von Dokumentseiten. |
| [Document_InsertPages](#Document_InsertPages) | Eine benannte Aktion zum Einfügen von Seiten aus einem Dokument. |
| [Document_ReplacePages](#Document_ReplacePages) | Eine benannte Aktion zum Ersetzen von Dokumentseiten. |
| [Document_RotatePages](#Document_RotatePages) | Eine benannte Aktion zum Drehen von Dokumentseiten. |
| [Edit_CheckSpelling_InComFieldEdit](#Edit_CheckSpelling_InComFieldEdit) | Eine benannte Aktion zum Prüfen der Rechtschreibung in Kommentaren. |
| [Edit_Find](#Edit_Find) | Eine benannte Aktion zum Suchen. |
| [Edit_Preferences](#Edit_Preferences) | Eine benannte Aktion zum Bearbeiten von Einstellungen. |
| [Edit_Search](#Edit_Search) | Eine benannte Aktion für die Suche. |
| [File_AttachToEmail](#File_AttachToEmail) | Eine benannte Aktion zum Anhängen des aktuellen PDF-Dokuments an eine E-Mail-Nachricht. |
| [File_Close](#File_Close) | Eine benannte Aktion zum Schließen des Dokuments. |
| [File_CreatePDF_FromScanner](#File_CreatePDF_FromScanner) | Eine benannte Aktion zum Erstellen eines PDF-Dokuments aus dem Scanner. |
| [File_CreatePDF_FromWebPage](#File_CreatePDF_FromWebPage) | Eine benannte Aktion zum Erstellen eines PDF-Dokuments aus einer Webseite. |
| [File_Exit](#File_Exit) | Eine benannte Aktion zum Beenden des PDF-Readers. |
| [File_Organizer_OpenOrganizer](#File_Organizer_OpenOrganizer) | Eine benannte Aktion zum Öffnen des Organizers. |
| [File_Print](#File_Print) | Eine benannte Aktion zum Drucken des Dokuments. |
| [File_Properties](#File_Properties) | Eine benannte Aktion zum Öffnen der Dokumenteigenschaften. |
| [File_SaveAs](#File_SaveAs) | Eine benannte Aktion zum Speichern des Dokuments unter einem anderen Namen. |
| [FirstPage](#FirstPage) | Eine benannte Aktion zum Wechseln zur ersten Seite. |
| [LastPage](#LastPage) | Eine benannte Aktion zum Wechseln zur letzten Seite. |
| [Miscellaneous_ZoomIn](#Miscellaneous_ZoomIn) | Eine benannte Aktion zum Vergrößern des Dokuments. |
| [Miscellaneous_ZoomOut](#Miscellaneous_ZoomOut) | Eine benannte Aktion zum Verkleinern des Dokuments. |
| [NextPage](#NextPage) | Eine benannte Aktion zum Wechseln zur nächsten Seite. |
| [PageImages_PrintPages](#PageImages_PrintPages) | Eine benannte Aktion zum Drucken der Dokumentseiten. |
| [PrevPage](#PrevPage) | Eine benannte Aktion zum Wechseln zur vorherigen Seite. |
| [Print](#Print) | Eine benannte Aktion zum Öffnen eines Druckdialogs. |
| [PrintDialog](#PrintDialog) | Eine benannte Aktion zum Öffnen eines Druckdialogs (JavaScript). |
| [View_GoTo_NextView](#View_GoTo_NextView) | Eine benannte Aktion, um zur nächsten Ansicht zu gehen. |
| [View_GoTo_Page](#View_GoTo_Page) | Eine benannte Aktion, um zu einer bestimmten Seite zu gehen. |
| [View_GoTo_PreDocument](#View_GoTo_PreDocument) | Eine benannte Aktion, um zum vorherigen Dokument zu gehen. |
| [View_GoTo_PreView](#View_GoTo_PreView) | Eine benannte Aktion, um zur vorherigen Ansicht zu gehen. |
| [View_NavigationPanels_Articles](#View_NavigationPanels_Articles) | Eine benannte Aktion zum Anzeigen/Verbergen des Artikelpanels. |
| [View_NavigationPanels_Attachments](#View_NavigationPanels_Attachments) | Eine benannte Aktion zum Anzeigen/Verbergen des Anhangs-Panels. |
| [View_NavigationPanels_Boomarks](#View_NavigationPanels_Boomarks) | Eine benannte Aktion zum Anzeigen/Verbergen des Lesezeichen-Panels. |
| [View_NavigationPanels_Comments](#View_NavigationPanels_Comments) | Eine benannte Aktion zum Anzeigen/Verbergen des Kommentar-Panels. |
| [View_NavigationPanels_Fields](#View_NavigationPanels_Fields) | Eine benannte Aktion zum Anzeigen/Verbergen des Feld-Panels. |
| [View_NavigationPanels_Layers](#View_NavigationPanels_Layers) | Eine benannte Aktion zum Anzeigen/Verbergen des Ebenen-Panels. |
| [View_NavigationPanels_ModelTree](#View_NavigationPanels_ModelTree) | Eine benannte Aktion zum Anzeigen/Verbergen des Modellbaum-Panels. |
| [View_NavigationPanels_Pages](#View_NavigationPanels_Pages) | Eine benannte Aktion zum Anzeigen/Verbergen des Seiten-Panels. |
| [View_NavigationPanels_Signatures](#View_NavigationPanels_Signatures) | Eine benannte Aktion zum Anzeigen/Verbergen des Signatur-Panels. |
| [View_PageDisplay_SinglePage](#View_PageDisplay_SinglePage) | Eine benannte Aktion zum Anzeigen einer einzelnen Seite. |
| [View_PageDisplay_SinglePageContinuous](#View_PageDisplay_SinglePageContinuous) | Eine benannte Aktion zum Anzeigen einer einzelnen kontinuierlichen Seite. |
| [View_PageDisplay_TwoUp](#View_PageDisplay_TwoUp) | Eine benannte Aktion zum Anzeigen von Seiten im Zwei-Up-Modus. |
| [View_PageDisplay_TwoUpContinuous](#View_PageDisplay_TwoUpContinuous) | Eine benannte Aktion zum Anzeigen von Seiten im Zwei-Up-Modus kontinuierlich. |
| [View_Toolbars_AdvanceEditing](#View_Toolbars_AdvanceEditing) | Eine benannte Aktion zum Anzeigen/Verbergen der erweiterten Bearbeitungswerkzeugleiste. |
| [View_Toolbars_CommentMarkup](#View_Toolbars_CommentMarkup) | Eine benannte Aktion zum Anzeigen/Verbergen der Kommentar-Werkzeugleiste. |
| [View_Toolbars_Edit](#View_Toolbars_Edit) | Eine benannte Aktion zum Anzeigen/Verbergen der Bearbeitungswerkzeugleiste. |
| [View_Toolbars_File](#View_Toolbars_File) | Eine benannte Aktion zum Anzeigen/Verbergen der Datei-Werkzeugleiste. |
| [View_Toolbars_Find](#View_Toolbars_Find) | Eine benannte Aktion zum Anzeigen/Verbergen der Such-Werkzeugleiste. |
| [View_Toolbars_Forms](#View_Toolbars_Forms) | Eine benannte Aktion zum Anzeigen/Verbergen der Formular-Werkzeugleiste. |
| [View_Toolbars_Measuring](#View_Toolbars_Measuring) | Eine benannte Aktion zum Anzeigen/Ausblenden der Messwerkzeugleiste. |
| [View_Toolbars_ObjectData](#View_Toolbars_ObjectData) | Eine benannte Aktion zum Anzeigen/Ausblenden der Objekt-Datenwerkzeugleiste. |
| [View_Toolbars_PageDisplay](#View_Toolbars_PageDisplay) | Eine benannte Aktion zum Anzeigen/Ausblenden der Seitenanzeige-Werkzeugleiste. |
| [View_Toolbars_PageNavigation](#View_Toolbars_PageNavigation) | Eine benannte Aktion zum Anzeigen/Ausblenden der Navigationswerkzeugleiste. |
| [View_Toolbars_PrintProduction](#View_Toolbars_PrintProduction) | Eine benannte Aktion zum Anzeigen/Ausblenden der Druckproduktionswerkzeugleiste. |
| [View_Toolbars_PropertiesBar](#View_Toolbars_PropertiesBar) | Eine benannte Aktion zum Anzeigen/Ausblenden der Eigenschaftenwerkzeugleiste. |
| [View_Toolbars_Redaction](#View_Toolbars_Redaction) | Eine benannte Aktion zum Anzeigen/Ausblenden der Redaktionswerkzeugleiste. |
| [View_Toolbars_SelectZoom](#View_Toolbars_SelectZoom) | Eine benannte Aktion zum Anzeigen/Ausblenden der Auswahl‑&‑Zoom‑Werkzeugleiste. |
| [View_Toolbars_Tasks](#View_Toolbars_Tasks) | Eine benannte Aktion zum Anzeigen/Ausblenden der Aufgabenwerkzeugleiste. |
| [View_Toolbars_Typewriter](#View_Toolbars_Typewriter) | Eine benannte Aktion zum Anzeigen/Ausblenden der Schreibmaschinenwerkzeugleiste. |
| [View_Zoom_ActualSize](#View_Zoom_ActualSize) | Eine benannte Aktion zum Anzeigen von Seiten in Originalgröße. |
| [View_Zoom_FitHeight](#View_Zoom_FitHeight) | Eine benannte Aktion zum Anpassen der Seite an die Höhe. |
| [View_Zoom_FitPage](#View_Zoom_FitPage) | Eine benannte Aktion zum Anpassen der Seite. |
| [View_Zoom_FitVisible](#View_Zoom_FitVisible) | Eine benannte Aktion zum Anpassen der Seitenanzeige. |
| [View_Zoom_FitWidth](#View_Zoom_FitWidth) | Eine benannte Aktion zum Anpassen der Seite an die Breite. |
| [View_Zoom_ZoomTo](#View_Zoom_ZoomTo) | Eine benannte Aktion zum Zoomen. |
| [Window_FullScreenMode](#Window_FullScreenMode) | Eine benannte Aktion zum Anzeigen des Dokuments im Vollbildmodus. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | Gibt die Enum-Konstante dieses Typs mit dem angegebenen Namen zurück. |
| [values](#values--) | Gibt ein Array zurück, das die Konstanten dieses Enum-Typs in der Reihenfolge ihrer Deklaration enthält. |

### Bookmarks_ExpanCurrentBookmark {#Bookmarks_ExpanCurrentBookmark}
```
public static final PredefinedAction Bookmarks_ExpanCurrentBookmark
```

Eine benannte Aktion, um das aktuelle Lesezeichen zu finden.

### Bookmarks_HightlightCurrentBookmark {#Bookmarks_HightlightCurrentBookmark}
```
public static final PredefinedAction Bookmarks_HightlightCurrentBookmark
```

Eine benannte Aktion, um das aktuelle Lesezeichen hervorzuheben.

### Document_AttachFile {#Document_AttachFile}
```
public static final PredefinedAction Document_AttachFile
```

Eine benannte Aktion, um einen Dateianhang hinzuzufügen.

### Document_CropPages {#Document_CropPages}
```
public static final PredefinedAction Document_CropPages
```

Eine benannte Aktion, um Dokumentseiten zuzuschneiden.

### Document_DeletePages {#Document_DeletePages}
```
public static final PredefinedAction Document_DeletePages
```

Eine benannte Aktion zum Löschen von Dokumentseiten.

### Document_ExtractPages {#Document_ExtractPages}
```
public static final PredefinedAction Document_ExtractPages
```

Eine benannte Aktion zum Extrahieren von Dokumentseiten.

### Document_InsertPages {#Document_InsertPages}
```
public static final PredefinedAction Document_InsertPages
```

Eine benannte Aktion zum Einfügen von Seiten aus einem Dokument.

### Document_ReplacePages {#Document_ReplacePages}
```
public static final PredefinedAction Document_ReplacePages
```

Eine benannte Aktion zum Ersetzen von Dokumentseiten.

### Document_RotatePages {#Document_RotatePages}
```
public static final PredefinedAction Document_RotatePages
```

Eine benannte Aktion zum Drehen von Dokumentseiten.

### Edit_CheckSpelling_InComFieldEdit {#Edit_CheckSpelling_InComFieldEdit}
```
public static final PredefinedAction Edit_CheckSpelling_InComFieldEdit
```

Eine benannte Aktion zum Prüfen der Rechtschreibung in Kommentaren.

### Edit_Find {#Edit_Find}
```
public static final PredefinedAction Edit_Find
```

Eine benannte Aktion zum Suchen.

### Edit_Preferences {#Edit_Preferences}
```
public static final PredefinedAction Edit_Preferences
```

Eine benannte Aktion zum Bearbeiten von Einstellungen.

### Edit_Search {#Edit_Search}
```
public static final PredefinedAction Edit_Search
```

Eine benannte Aktion für die Suche.

### File_AttachToEmail {#File_AttachToEmail}
```
public static final PredefinedAction File_AttachToEmail
```

Eine benannte Aktion zum Anhängen des aktuellen PDF-Dokuments an eine E-Mail-Nachricht.

### File_Close {#File_Close}
```
public static final PredefinedAction File_Close
```

Eine benannte Aktion zum Schließen des Dokuments.

### File_CreatePDF_FromScanner {#File_CreatePDF_FromScanner}
```
public static final PredefinedAction File_CreatePDF_FromScanner
```

Eine benannte Aktion zum Erstellen eines PDF-Dokuments aus dem Scanner.

### File_CreatePDF_FromWebPage {#File_CreatePDF_FromWebPage}
```
public static final PredefinedAction File_CreatePDF_FromWebPage
```

Eine benannte Aktion zum Erstellen eines PDF-Dokuments aus einer Webseite.

### File_Exit {#File_Exit}
```
public static final PredefinedAction File_Exit
```

Eine benannte Aktion zum Beenden des PDF-Readers.

### File_Organizer_OpenOrganizer {#File_Organizer_OpenOrganizer}
```
public static final PredefinedAction File_Organizer_OpenOrganizer
```

Eine benannte Aktion zum Öffnen des Organizers.

### File_Print {#File_Print}
```
public static final PredefinedAction File_Print
```

Eine benannte Aktion zum Drucken des Dokuments.

### File_Properties {#File_Properties}
```
public static final PredefinedAction File_Properties
```

Eine benannte Aktion zum Öffnen der Dokumenteigenschaften.

### File_SaveAs {#File_SaveAs}
```
public static final PredefinedAction File_SaveAs
```

Eine benannte Aktion zum Speichern des Dokuments unter einem anderen Namen.

### FirstPage {#FirstPage}
```
public static final PredefinedAction FirstPage
```

Eine benannte Aktion zum Wechseln zur ersten Seite.

### LastPage {#LastPage}
```
public static final PredefinedAction LastPage
```

Eine benannte Aktion zum Wechseln zur letzten Seite.

### Miscellaneous_ZoomIn {#Miscellaneous_ZoomIn}
```
public static final PredefinedAction Miscellaneous_ZoomIn
```

Eine benannte Aktion zum Vergrößern des Dokuments.

### Miscellaneous_ZoomOut {#Miscellaneous_ZoomOut}
```
public static final PredefinedAction Miscellaneous_ZoomOut
```

Eine benannte Aktion zum Verkleinern des Dokuments.

### NextPage {#NextPage}
```
public static final PredefinedAction NextPage
```

Eine benannte Aktion zum Wechseln zur nächsten Seite.

### PageImages_PrintPages {#PageImages_PrintPages}
```
public static final PredefinedAction PageImages_PrintPages
```

Eine benannte Aktion zum Drucken der Dokumentseiten.

### PrevPage {#PrevPage}
```
public static final PredefinedAction PrevPage
```

Eine benannte Aktion zum Wechseln zur vorherigen Seite.

### Print {#Print}
```
public static final PredefinedAction Print
```

Eine benannte Aktion zum Öffnen eines Druckdialogs.

### PrintDialog {#PrintDialog}
```
public static final PredefinedAction PrintDialog
```

Eine benannte Aktion zum Öffnen eines Druckdialogs (JavaScript).

### View_GoTo_NextView {#View_GoTo_NextView}
```
public static final PredefinedAction View_GoTo_NextView
```

Eine benannte Aktion, um zur nächsten Ansicht zu gehen.

### View_GoTo_Page {#View_GoTo_Page}
```
public static final PredefinedAction View_GoTo_Page
```

Eine benannte Aktion, um zu einer bestimmten Seite zu gehen.

### View_GoTo_PreDocument {#View_GoTo_PreDocument}
```
public static final PredefinedAction View_GoTo_PreDocument
```

Eine benannte Aktion, um zum vorherigen Dokument zu gehen.

### View_GoTo_PreView {#View_GoTo_PreView}
```
public static final PredefinedAction View_GoTo_PreView
```

Eine benannte Aktion, um zur vorherigen Ansicht zu gehen.

### View_NavigationPanels_Articles {#View_NavigationPanels_Articles}
```
public static final PredefinedAction View_NavigationPanels_Articles
```

Eine benannte Aktion zum Anzeigen/Verbergen des Artikelpanels.

### View_NavigationPanels_Attachments {#View_NavigationPanels_Attachments}
```
public static final PredefinedAction View_NavigationPanels_Attachments
```

Eine benannte Aktion zum Anzeigen/Verbergen des Anhangs-Panels.

### View_NavigationPanels_Boomarks {#View_NavigationPanels_Boomarks}
```
public static final PredefinedAction View_NavigationPanels_Boomarks
```

Eine benannte Aktion zum Anzeigen/Verbergen des Lesezeichen-Panels.

### View_NavigationPanels_Comments {#View_NavigationPanels_Comments}
```
public static final PredefinedAction View_NavigationPanels_Comments
```

Eine benannte Aktion zum Anzeigen/Verbergen des Kommentar-Panels.

### View_NavigationPanels_Fields {#View_NavigationPanels_Fields}
```
public static final PredefinedAction View_NavigationPanels_Fields
```

Eine benannte Aktion zum Anzeigen/Verbergen des Feld-Panels.

### View_NavigationPanels_Layers {#View_NavigationPanels_Layers}
```
public static final PredefinedAction View_NavigationPanels_Layers
```

Eine benannte Aktion zum Anzeigen/Verbergen des Ebenen-Panels.

### View_NavigationPanels_ModelTree {#View_NavigationPanels_ModelTree}
```
public static final PredefinedAction View_NavigationPanels_ModelTree
```

Eine benannte Aktion zum Anzeigen/Verbergen des Modellbaum-Panels.

### View_NavigationPanels_Pages {#View_NavigationPanels_Pages}
```
public static final PredefinedAction View_NavigationPanels_Pages
```

Eine benannte Aktion zum Anzeigen/Verbergen des Seiten-Panels.

### View_NavigationPanels_Signatures {#View_NavigationPanels_Signatures}
```
public static final PredefinedAction View_NavigationPanels_Signatures
```

Eine benannte Aktion zum Anzeigen/Verbergen des Signatur-Panels.

### View_PageDisplay_SinglePage {#View_PageDisplay_SinglePage}
```
public static final PredefinedAction View_PageDisplay_SinglePage
```

Eine benannte Aktion zum Anzeigen einer einzelnen Seite.

### View_PageDisplay_SinglePageContinuous {#View_PageDisplay_SinglePageContinuous}
```
public static final PredefinedAction View_PageDisplay_SinglePageContinuous
```

Eine benannte Aktion zum Anzeigen einer einzelnen kontinuierlichen Seite.

### View_PageDisplay_TwoUp {#View_PageDisplay_TwoUp}
```
public static final PredefinedAction View_PageDisplay_TwoUp
```

Eine benannte Aktion zum Anzeigen von Seiten im Zwei-Up-Modus.

### View_PageDisplay_TwoUpContinuous {#View_PageDisplay_TwoUpContinuous}
```
public static final PredefinedAction View_PageDisplay_TwoUpContinuous
```

Eine benannte Aktion zum Anzeigen von Seiten im Zwei-Up-Modus kontinuierlich.

### View_Toolbars_AdvanceEditing {#View_Toolbars_AdvanceEditing}
```
public static final PredefinedAction View_Toolbars_AdvanceEditing
```

Eine benannte Aktion zum Anzeigen/Verbergen der erweiterten Bearbeitungswerkzeugleiste.

### View_Toolbars_CommentMarkup {#View_Toolbars_CommentMarkup}
```
public static final PredefinedAction View_Toolbars_CommentMarkup
```

Eine benannte Aktion zum Anzeigen/Verbergen der Kommentar-Werkzeugleiste.

### View_Toolbars_Edit {#View_Toolbars_Edit}
```
public static final PredefinedAction View_Toolbars_Edit
```

Eine benannte Aktion zum Anzeigen/Verbergen der Bearbeitungswerkzeugleiste.

### View_Toolbars_File {#View_Toolbars_File}
```
public static final PredefinedAction View_Toolbars_File
```

Eine benannte Aktion zum Anzeigen/Verbergen der Datei-Werkzeugleiste.

### View_Toolbars_Find {#View_Toolbars_Find}
```
public static final PredefinedAction View_Toolbars_Find
```

Eine benannte Aktion zum Anzeigen/Verbergen der Such-Werkzeugleiste.

### View_Toolbars_Forms {#View_Toolbars_Forms}
```
public static final PredefinedAction View_Toolbars_Forms
```

Eine benannte Aktion zum Anzeigen/Verbergen der Formular-Werkzeugleiste.

### View_Toolbars_Measuring {#View_Toolbars_Measuring}
```
public static final PredefinedAction View_Toolbars_Measuring
```

Eine benannte Aktion zum Anzeigen/Ausblenden der Messwerkzeugleiste.

### View_Toolbars_ObjectData {#View_Toolbars_ObjectData}
```
public static final PredefinedAction View_Toolbars_ObjectData
```

Eine benannte Aktion zum Anzeigen/Ausblenden der Objekt-Datenwerkzeugleiste.

### View_Toolbars_PageDisplay {#View_Toolbars_PageDisplay}
```
public static final PredefinedAction View_Toolbars_PageDisplay
```

Eine benannte Aktion zum Anzeigen/Ausblenden der Seitenanzeige-Werkzeugleiste.

### View_Toolbars_PageNavigation {#View_Toolbars_PageNavigation}
```
public static final PredefinedAction View_Toolbars_PageNavigation
```

Eine benannte Aktion zum Anzeigen/Ausblenden der Navigationswerkzeugleiste.

### View_Toolbars_PrintProduction {#View_Toolbars_PrintProduction}
```
public static final PredefinedAction View_Toolbars_PrintProduction
```

Eine benannte Aktion zum Anzeigen/Ausblenden der Druckproduktionswerkzeugleiste.

### View_Toolbars_PropertiesBar {#View_Toolbars_PropertiesBar}
```
public static final PredefinedAction View_Toolbars_PropertiesBar
```

Eine benannte Aktion zum Anzeigen/Ausblenden der Eigenschaftenwerkzeugleiste.

### View_Toolbars_Redaction {#View_Toolbars_Redaction}
```
public static final PredefinedAction View_Toolbars_Redaction
```

Eine benannte Aktion zum Anzeigen/Ausblenden der Redaktionswerkzeugleiste.

### View_Toolbars_SelectZoom {#View_Toolbars_SelectZoom}
```
public static final PredefinedAction View_Toolbars_SelectZoom
```

Eine benannte Aktion zum Anzeigen/Ausblenden der Auswahl‑&‑Zoom‑Werkzeugleiste.

### View_Toolbars_Tasks {#View_Toolbars_Tasks}
```
public static final PredefinedAction View_Toolbars_Tasks
```

Eine benannte Aktion zum Anzeigen/Ausblenden der Aufgabenwerkzeugleiste.

### View_Toolbars_Typewriter {#View_Toolbars_Typewriter}
```
public static final PredefinedAction View_Toolbars_Typewriter
```

Eine benannte Aktion zum Anzeigen/Ausblenden der Schreibmaschinenwerkzeugleiste.

### View_Zoom_ActualSize {#View_Zoom_ActualSize}
```
public static final PredefinedAction View_Zoom_ActualSize
```

Eine benannte Aktion zum Anzeigen von Seiten in Originalgröße.

### View_Zoom_FitHeight {#View_Zoom_FitHeight}
```
public static final PredefinedAction View_Zoom_FitHeight
```

Eine benannte Aktion zum Anpassen der Seite an die Höhe.

### View_Zoom_FitPage {#View_Zoom_FitPage}
```
public static final PredefinedAction View_Zoom_FitPage
```

Eine benannte Aktion zum Anpassen der Seite.

### View_Zoom_FitVisible {#View_Zoom_FitVisible}
```
public static final PredefinedAction View_Zoom_FitVisible
```

Eine benannte Aktion zum Anpassen der Seitenanzeige.

### View_Zoom_FitWidth {#View_Zoom_FitWidth}
```
public static final PredefinedAction View_Zoom_FitWidth
```

Eine benannte Aktion zum Anpassen der Seite an die Breite.

### View_Zoom_ZoomTo {#View_Zoom_ZoomTo}
```
public static final PredefinedAction View_Zoom_ZoomTo
```

Eine benannte Aktion zum Zoomen.

### Window_FullScreenMode {#Window_FullScreenMode}
```
public static final PredefinedAction Window_FullScreenMode
```

Eine benannte Aktion zum Anzeigen des Dokuments im Vollbildmodus.

### getByValue {#getByValue-int-}
```
public static PredefinedAction getByValue(int value)
```



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  |  |

### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
Gibt die Enum-Konstante dieses Typs mit dem angegebenen Namen zurück.

### values {#values--}
```
public static PredefinedAction [] values()
```

Gibt ein Array zurück, das die Konstanten dieses Enum-Typs in der Reihenfolge ihrer Deklaration enthält.

**Returns:**
ein Array, das die Konstanten dieses Enum-Typs in der Reihenfolge ihrer Deklaration enthält
