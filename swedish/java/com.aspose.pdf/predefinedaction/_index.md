---
title: "PredefinedAction"
linktitle: "PredefinedAction"
second_title: "Aspose.PDF för Java API-referens"
description: "Definierar olika åtgärder som kan utlösas från en PDF-fil."
type: docs
weight: 3960
url: /sv/java/com.aspose.pdf/predefinedaction/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < PredefinedAction > com.aspose.pdf.PredefinedAction, java.lang.Enum < PredefinedAction >, com.aspose.pdf.PredefinedAction

**All Implemented Interfaces:**
Serializable, Comparable < PredefinedAction >

```
public enum PredefinedAction extends Enum < PredefinedAction >
```

Definierar olika åtgärder som kan utlösas från en PDF-fil.

## Fält

| Fält | Beskrivning |
| --- | --- |
| [Bookmarks_ExpanCurrentBookmark](#Bookmarks_ExpanCurrentBookmark) | En namngiven åtgärd för att hitta aktuellt bokmärke. |
| [Bookmarks_HightlightCurrentBookmark](#Bookmarks_HightlightCurrentBookmark) | En namngiven åtgärd för att markera aktuellt bokmärke. |
| [Document_AttachFile](#Document_AttachFile) | En namngiven åtgärd för att lägga till en filbilaga. |
| [Document_CropPages](#Document_CropPages) | En namngiven åtgärd för att beskära dokumentsidor. |
| [Document_DeletePages](#Document_DeletePages) | En namngiven åtgärd för att radera dokumentsidor. |
| [Document_ExtractPages](#Document_ExtractPages) | En namngiven åtgärd för att extrahera dokumentsidor. |
| [Document_InsertPages](#Document_InsertPages) | En namngiven åtgärd för att infoga sidor från ett dokument. |
| [Document_ReplacePages](#Document_ReplacePages) | En namngiven åtgärd för att ersätta dokumentsidor. |
| [Document_RotatePages](#Document_RotatePages) | En namngiven åtgärd för att rotera dokumentsidor. |
| [Edit_CheckSpelling_InComFieldEdit](#Edit_CheckSpelling_InComFieldEdit) | En namngiven åtgärd för att kontrollera stavning i kommentarer. |
| [Edit_Find](#Edit_Find) | En namngiven åtgärd för att hitta. |
| [Edit_Preferences](#Edit_Preferences) | En namngiven åtgärd för att redigera inställningar. |
| [Edit_Search](#Edit_Search) | En namngiven åtgärd för sökning. |
| [File_AttachToEmail](#File_AttachToEmail) | En namngiven åtgärd för att bifoga aktuellt pdf-dokument i e-postmeddelande. |
| [File_Close](#File_Close) | En namngiven åtgärd för att stänga dokumentet. |
| [File_CreatePDF_FromScanner](#File_CreatePDF_FromScanner) | En namngiven åtgärd för att skapa pdf-dokument från skanner. |
| [File_CreatePDF_FromWebPage](#File_CreatePDF_FromWebPage) | En namngiven åtgärd för att skapa pdf-dokument från webbsida. |
| [File_Exit](#File_Exit) | En namngiven åtgärd för att avsluta pdf-läsaren. |
| [File_Organizer_OpenOrganizer](#File_Organizer_OpenOrganizer) | En namngiven åtgärd för att öppna organisatören. |
| [File_Print](#File_Print) | En namngiven åtgärd för att skriva ut dokumentet. |
| [File_Properties](#File_Properties) | En namngiven åtgärd för att öppna dokumentets egenskaper. |
| [File_SaveAs](#File_SaveAs) | En namngiven åtgärd för att spara dokumentet med ett annat namn. |
| [FirstPage](#FirstPage) | En namngiven åtgärd för att gå till den första sidan. |
| [LastPage](#LastPage) | En namngiven åtgärd för att gå till den sista sidan. |
| [Miscellaneous_ZoomIn](#Miscellaneous_ZoomIn) | En namngiven åtgärd för att zooma in i dokumentet. |
| [Miscellaneous_ZoomOut](#Miscellaneous_ZoomOut) | En namngiven åtgärd för att zooma ut i dokumentet. |
| [NextPage](#NextPage) | En namngiven åtgärd för att gå till nästa sida. |
| [PageImages_PrintPages](#PageImages_PrintPages) | En namngiven åtgärd för att skriva ut dokumentets sidor. |
| [PrevPage](#PrevPage) | En namngiven åtgärd för att gå till föregående sida. |
| [Print](#Print) | En namngiven åtgärd för att öppna en utskriftsdialog. |
| [PrintDialog](#PrintDialog) | En namngiven åtgärd för att öppna en utskriftsdialog (JavaScript). |
| [View_GoTo_NextView](#View_GoTo_NextView) | En namngiven åtgärd för att gå till nästa vy. |
| [View_GoTo_Page](#View_GoTo_Page) | En namngiven åtgärd för att gå till en viss sida. |
| [View_GoTo_PreDocument](#View_GoTo_PreDocument) | En namngiven åtgärd för att gå till föregående dokument. |
| [View_GoTo_PreView](#View_GoTo_PreView) | En namngiven åtgärd för att gå till föregående vy. |
| [View_NavigationPanels_Articles](#View_NavigationPanels_Articles) | En namngiven åtgärd för att visa/dölja artiklarpanelen. |
| [View_NavigationPanels_Attachments](#View_NavigationPanels_Attachments) | En namngiven åtgärd för att visa/dölja bilagapanelen. |
| [View_NavigationPanels_Boomarks](#View_NavigationPanels_Boomarks) | En namngiven åtgärd för att visa/dölja bokmärkespanelen. |
| [View_NavigationPanels_Comments](#View_NavigationPanels_Comments) | En namngiven åtgärd för att visa/dölja kommentarpanelen. |
| [View_NavigationPanels_Fields](#View_NavigationPanels_Fields) | En namngiven åtgärd för att visa/dölja fältpanelen. |
| [View_NavigationPanels_Layers](#View_NavigationPanels_Layers) | En namngiven åtgärd för att visa/dölja lagerpanelen. |
| [View_NavigationPanels_ModelTree](#View_NavigationPanels_ModelTree) | En namngiven åtgärd för att visa/dölja modellträdspanelen. |
| [View_NavigationPanels_Pages](#View_NavigationPanels_Pages) | En namngiven åtgärd för att visa/dölja sidpanelen. |
| [View_NavigationPanels_Signatures](#View_NavigationPanels_Signatures) | En namngiven åtgärd för att visa/dölja signaturpanel. |
| [View_PageDisplay_SinglePage](#View_PageDisplay_SinglePage) | En namngiven åtgärd för att visa enskild sida. |
| [View_PageDisplay_SinglePageContinuous](#View_PageDisplay_SinglePageContinuous) | En namngiven åtgärd för att visa enskild kontinuerlig sida. |
| [View_PageDisplay_TwoUp](#View_PageDisplay_TwoUp) | En namngiven åtgärd för att visa sidor som Two-Up. |
| [View_PageDisplay_TwoUpContinuous](#View_PageDisplay_TwoUpContinuous) | En namngiven åtgärd för att visa sidor som Two-Up kontinuerlig. |
| [View_Toolbars_AdvanceEditing](#View_Toolbars_AdvanceEditing) | En namngiven åtgärd för att visa/dölja avancerad redigeringsverktygsrad. |
| [View_Toolbars_CommentMarkup](#View_Toolbars_CommentMarkup) | En namngiven åtgärd för att visa/dölja kommentarsverktygsrad. |
| [View_Toolbars_Edit](#View_Toolbars_Edit) | En namngiven åtgärd för att visa/dölja redigeringsverktygsrad. |
| [View_Toolbars_File](#View_Toolbars_File) | En namngiven åtgärd för att visa/dölja filverktygsrad. |
| [View_Toolbars_Find](#View_Toolbars_Find) | En namngiven åtgärd för att visa/dölja sökverktygsrad. |
| [View_Toolbars_Forms](#View_Toolbars_Forms) | En namngiven åtgärd för att visa/dölja formulärverktygsrad. |
| [View_Toolbars_Measuring](#View_Toolbars_Measuring) | En namngiven åtgärd för att visa/dölja mätningsverktygsrad. |
| [View_Toolbars_ObjectData](#View_Toolbars_ObjectData) | En namngiven åtgärd för att visa/dölja objektdataverktygsrad. |
| [View_Toolbars_PageDisplay](#View_Toolbars_PageDisplay) | En namngiven åtgärd för att visa/dölja sidvisningsverktygsrad. |
| [View_Toolbars_PageNavigation](#View_Toolbars_PageNavigation) | En namngiven åtgärd för att visa/dölja navigeringsverktygsrad. |
| [View_Toolbars_PrintProduction](#View_Toolbars_PrintProduction) | En namngiven åtgärd för att visa/dölja utskriftsproduktionsverktygsrad. |
| [View_Toolbars_PropertiesBar](#View_Toolbars_PropertiesBar) | En namngiven åtgärd för att visa/dölja egenskapsverktygsrad. |
| [View_Toolbars_Redaction](#View_Toolbars_Redaction) | En namngiven åtgärd för att visa/dölja röjningsverktygsrad. |
| [View_Toolbars_SelectZoom](#View_Toolbars_SelectZoom) | En namngiven åtgärd för att visa/dölja markerings- och zoomverktygsrad. |
| [View_Toolbars_Tasks](#View_Toolbars_Tasks) | En namngiven åtgärd för att visa/dölja uppgiftsverktygsrad. |
| [View_Toolbars_Typewriter](#View_Toolbars_Typewriter) | En namngiven åtgärd för att visa/dölja skrivmaskinsverktygsrad. |
| [View_Zoom_ActualSize](#View_Zoom_ActualSize) | En namngiven åtgärd för att visa sidor i verklig storlek. |
| [View_Zoom_FitHeight](#View_Zoom_FitHeight) | En namngiven åtgärd för att anpassa sidan efter höjd. |
| [View_Zoom_FitPage](#View_Zoom_FitPage) | En namngiven åtgärd för att anpassa sidan. |
| [View_Zoom_FitVisible](#View_Zoom_FitVisible) | En namngiven åtgärd för att anpassa sidans synlighet. |
| [View_Zoom_FitWidth](#View_Zoom_FitWidth) | En namngiven åtgärd för att anpassa sidan till bredden. |
| [View_Zoom_ZoomTo](#View_Zoom_ZoomTo) | En namngiven åtgärd för att zooma. |
| [Window_FullScreenMode](#Window_FullScreenMode) | En namngiven åtgärd för att visa dokumentet i helskärmsläge. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | Returnerar enum‑konstanten av denna typ med det angivna namnet. |
| [values](#values--) | Returnerar en array som innehåller konstanterna för denna enum‑typ, i den ordning de deklareras. |

### Bookmarks_ExpanCurrentBookmark {#Bookmarks_ExpanCurrentBookmark}
```
public static final PredefinedAction Bookmarks_ExpanCurrentBookmark
```

En namngiven åtgärd för att hitta aktuellt bokmärke.

### Bookmarks_HightlightCurrentBookmark {#Bookmarks_HightlightCurrentBookmark}
```
public static final PredefinedAction Bookmarks_HightlightCurrentBookmark
```

En namngiven åtgärd för att markera aktuellt bokmärke.

### Document_AttachFile {#Document_AttachFile}
```
public static final PredefinedAction Document_AttachFile
```

En namngiven åtgärd för att lägga till en filbilaga.

### Document_CropPages {#Document_CropPages}
```
public static final PredefinedAction Document_CropPages
```

En namngiven åtgärd för att beskära dokumentsidor.

### Document_DeletePages {#Document_DeletePages}
```
public static final PredefinedAction Document_DeletePages
```

En namngiven åtgärd för att radera dokumentsidor.

### Document_ExtractPages {#Document_ExtractPages}
```
public static final PredefinedAction Document_ExtractPages
```

En namngiven åtgärd för att extrahera dokumentsidor.

### Document_InsertPages {#Document_InsertPages}
```
public static final PredefinedAction Document_InsertPages
```

En namngiven åtgärd för att infoga sidor från ett dokument.

### Document_ReplacePages {#Document_ReplacePages}
```
public static final PredefinedAction Document_ReplacePages
```

En namngiven åtgärd för att ersätta dokumentsidor.

### Document_RotatePages {#Document_RotatePages}
```
public static final PredefinedAction Document_RotatePages
```

En namngiven åtgärd för att rotera dokumentsidor.

### Edit_CheckSpelling_InComFieldEdit {#Edit_CheckSpelling_InComFieldEdit}
```
public static final PredefinedAction Edit_CheckSpelling_InComFieldEdit
```

En namngiven åtgärd för att kontrollera stavning i kommentarer.

### Edit_Find {#Edit_Find}
```
public static final PredefinedAction Edit_Find
```

En namngiven åtgärd för att hitta.

### Edit_Preferences {#Edit_Preferences}
```
public static final PredefinedAction Edit_Preferences
```

En namngiven åtgärd för att redigera inställningar.

### Edit_Search {#Edit_Search}
```
public static final PredefinedAction Edit_Search
```

En namngiven åtgärd för sökning.

### File_AttachToEmail {#File_AttachToEmail}
```
public static final PredefinedAction File_AttachToEmail
```

En namngiven åtgärd för att bifoga aktuellt pdf-dokument i e-postmeddelande.

### File_Close {#File_Close}
```
public static final PredefinedAction File_Close
```

En namngiven åtgärd för att stänga dokumentet.

### File_CreatePDF_FromScanner {#File_CreatePDF_FromScanner}
```
public static final PredefinedAction File_CreatePDF_FromScanner
```

En namngiven åtgärd för att skapa pdf-dokument från skanner.

### File_CreatePDF_FromWebPage {#File_CreatePDF_FromWebPage}
```
public static final PredefinedAction File_CreatePDF_FromWebPage
```

En namngiven åtgärd för att skapa pdf-dokument från webbsida.

### File_Exit {#File_Exit}
```
public static final PredefinedAction File_Exit
```

En namngiven åtgärd för att avsluta pdf-läsaren.

### File_Organizer_OpenOrganizer {#File_Organizer_OpenOrganizer}
```
public static final PredefinedAction File_Organizer_OpenOrganizer
```

En namngiven åtgärd för att öppna organisatören.

### File_Print {#File_Print}
```
public static final PredefinedAction File_Print
```

En namngiven åtgärd för att skriva ut dokumentet.

### File_Properties {#File_Properties}
```
public static final PredefinedAction File_Properties
```

En namngiven åtgärd för att öppna dokumentets egenskaper.

### File_SaveAs {#File_SaveAs}
```
public static final PredefinedAction File_SaveAs
```

En namngiven åtgärd för att spara dokumentet med ett annat namn.

### FirstPage {#FirstPage}
```
public static final PredefinedAction FirstPage
```

En namngiven åtgärd för att gå till den första sidan.

### LastPage {#LastPage}
```
public static final PredefinedAction LastPage
```

En namngiven åtgärd för att gå till den sista sidan.

### Miscellaneous_ZoomIn {#Miscellaneous_ZoomIn}
```
public static final PredefinedAction Miscellaneous_ZoomIn
```

En namngiven åtgärd för att zooma in i dokumentet.

### Miscellaneous_ZoomOut {#Miscellaneous_ZoomOut}
```
public static final PredefinedAction Miscellaneous_ZoomOut
```

En namngiven åtgärd för att zooma ut i dokumentet.

### NextPage {#NextPage}
```
public static final PredefinedAction NextPage
```

En namngiven åtgärd för att gå till nästa sida.

### PageImages_PrintPages {#PageImages_PrintPages}
```
public static final PredefinedAction PageImages_PrintPages
```

En namngiven åtgärd för att skriva ut dokumentets sidor.

### PrevPage {#PrevPage}
```
public static final PredefinedAction PrevPage
```

En namngiven åtgärd för att gå till föregående sida.

### Print {#Print}
```
public static final PredefinedAction Print
```

En namngiven åtgärd för att öppna en utskriftsdialog.

### PrintDialog {#PrintDialog}
```
public static final PredefinedAction PrintDialog
```

En namngiven åtgärd för att öppna en utskriftsdialog (JavaScript).

### View_GoTo_NextView {#View_GoTo_NextView}
```
public static final PredefinedAction View_GoTo_NextView
```

En namngiven åtgärd för att gå till nästa vy.

### View_GoTo_Page {#View_GoTo_Page}
```
public static final PredefinedAction View_GoTo_Page
```

En namngiven åtgärd för att gå till en viss sida.

### View_GoTo_PreDocument {#View_GoTo_PreDocument}
```
public static final PredefinedAction View_GoTo_PreDocument
```

En namngiven åtgärd för att gå till föregående dokument.

### View_GoTo_PreView {#View_GoTo_PreView}
```
public static final PredefinedAction View_GoTo_PreView
```

En namngiven åtgärd för att gå till föregående vy.

### View_NavigationPanels_Articles {#View_NavigationPanels_Articles}
```
public static final PredefinedAction View_NavigationPanels_Articles
```

En namngiven åtgärd för att visa/dölja artiklarpanelen.

### View_NavigationPanels_Attachments {#View_NavigationPanels_Attachments}
```
public static final PredefinedAction View_NavigationPanels_Attachments
```

En namngiven åtgärd för att visa/dölja bilagapanelen.

### View_NavigationPanels_Boomarks {#View_NavigationPanels_Boomarks}
```
public static final PredefinedAction View_NavigationPanels_Boomarks
```

En namngiven åtgärd för att visa/dölja bokmärkespanelen.

### View_NavigationPanels_Comments {#View_NavigationPanels_Comments}
```
public static final PredefinedAction View_NavigationPanels_Comments
```

En namngiven åtgärd för att visa/dölja kommentarpanelen.

### View_NavigationPanels_Fields {#View_NavigationPanels_Fields}
```
public static final PredefinedAction View_NavigationPanels_Fields
```

En namngiven åtgärd för att visa/dölja fältpanelen.

### View_NavigationPanels_Layers {#View_NavigationPanels_Layers}
```
public static final PredefinedAction View_NavigationPanels_Layers
```

En namngiven åtgärd för att visa/dölja lagerpanelen.

### View_NavigationPanels_ModelTree {#View_NavigationPanels_ModelTree}
```
public static final PredefinedAction View_NavigationPanels_ModelTree
```

En namngiven åtgärd för att visa/dölja modellträdspanelen.

### View_NavigationPanels_Pages {#View_NavigationPanels_Pages}
```
public static final PredefinedAction View_NavigationPanels_Pages
```

En namngiven åtgärd för att visa/dölja sidpanelen.

### View_NavigationPanels_Signatures {#View_NavigationPanels_Signatures}
```
public static final PredefinedAction View_NavigationPanels_Signatures
```

En namngiven åtgärd för att visa/dölja signaturpanel.

### View_PageDisplay_SinglePage {#View_PageDisplay_SinglePage}
```
public static final PredefinedAction View_PageDisplay_SinglePage
```

En namngiven åtgärd för att visa enskild sida.

### View_PageDisplay_SinglePageContinuous {#View_PageDisplay_SinglePageContinuous}
```
public static final PredefinedAction View_PageDisplay_SinglePageContinuous
```

En namngiven åtgärd för att visa enskild kontinuerlig sida.

### View_PageDisplay_TwoUp {#View_PageDisplay_TwoUp}
```
public static final PredefinedAction View_PageDisplay_TwoUp
```

En namngiven åtgärd för att visa sidor som Two-Up.

### View_PageDisplay_TwoUpContinuous {#View_PageDisplay_TwoUpContinuous}
```
public static final PredefinedAction View_PageDisplay_TwoUpContinuous
```

En namngiven åtgärd för att visa sidor som Two-Up kontinuerlig.

### View_Toolbars_AdvanceEditing {#View_Toolbars_AdvanceEditing}
```
public static final PredefinedAction View_Toolbars_AdvanceEditing
```

En namngiven åtgärd för att visa/dölja avancerad redigeringsverktygsrad.

### View_Toolbars_CommentMarkup {#View_Toolbars_CommentMarkup}
```
public static final PredefinedAction View_Toolbars_CommentMarkup
```

En namngiven åtgärd för att visa/dölja kommentarsverktygsrad.

### View_Toolbars_Edit {#View_Toolbars_Edit}
```
public static final PredefinedAction View_Toolbars_Edit
```

En namngiven åtgärd för att visa/dölja redigeringsverktygsrad.

### View_Toolbars_File {#View_Toolbars_File}
```
public static final PredefinedAction View_Toolbars_File
```

En namngiven åtgärd för att visa/dölja filverktygsrad.

### View_Toolbars_Find {#View_Toolbars_Find}
```
public static final PredefinedAction View_Toolbars_Find
```

En namngiven åtgärd för att visa/dölja sökverktygsrad.

### View_Toolbars_Forms {#View_Toolbars_Forms}
```
public static final PredefinedAction View_Toolbars_Forms
```

En namngiven åtgärd för att visa/dölja formulärverktygsrad.

### View_Toolbars_Measuring {#View_Toolbars_Measuring}
```
public static final PredefinedAction View_Toolbars_Measuring
```

En namngiven åtgärd för att visa/dölja mätningsverktygsrad.

### View_Toolbars_ObjectData {#View_Toolbars_ObjectData}
```
public static final PredefinedAction View_Toolbars_ObjectData
```

En namngiven åtgärd för att visa/dölja objektdataverktygsrad.

### View_Toolbars_PageDisplay {#View_Toolbars_PageDisplay}
```
public static final PredefinedAction View_Toolbars_PageDisplay
```

En namngiven åtgärd för att visa/dölja sidvisningsverktygsrad.

### View_Toolbars_PageNavigation {#View_Toolbars_PageNavigation}
```
public static final PredefinedAction View_Toolbars_PageNavigation
```

En namngiven åtgärd för att visa/dölja navigeringsverktygsrad.

### View_Toolbars_PrintProduction {#View_Toolbars_PrintProduction}
```
public static final PredefinedAction View_Toolbars_PrintProduction
```

En namngiven åtgärd för att visa/dölja utskriftsproduktionsverktygsrad.

### View_Toolbars_PropertiesBar {#View_Toolbars_PropertiesBar}
```
public static final PredefinedAction View_Toolbars_PropertiesBar
```

En namngiven åtgärd för att visa/dölja egenskapsverktygsrad.

### View_Toolbars_Redaction {#View_Toolbars_Redaction}
```
public static final PredefinedAction View_Toolbars_Redaction
```

En namngiven åtgärd för att visa/dölja röjningsverktygsrad.

### View_Toolbars_SelectZoom {#View_Toolbars_SelectZoom}
```
public static final PredefinedAction View_Toolbars_SelectZoom
```

En namngiven åtgärd för att visa/dölja markerings- och zoomverktygsrad.

### View_Toolbars_Tasks {#View_Toolbars_Tasks}
```
public static final PredefinedAction View_Toolbars_Tasks
```

En namngiven åtgärd för att visa/dölja uppgiftsverktygsrad.

### View_Toolbars_Typewriter {#View_Toolbars_Typewriter}
```
public static final PredefinedAction View_Toolbars_Typewriter
```

En namngiven åtgärd för att visa/dölja skrivmaskinsverktygsrad.

### View_Zoom_ActualSize {#View_Zoom_ActualSize}
```
public static final PredefinedAction View_Zoom_ActualSize
```

En namngiven åtgärd för att visa sidor i verklig storlek.

### View_Zoom_FitHeight {#View_Zoom_FitHeight}
```
public static final PredefinedAction View_Zoom_FitHeight
```

En namngiven åtgärd för att anpassa sidan efter höjd.

### View_Zoom_FitPage {#View_Zoom_FitPage}
```
public static final PredefinedAction View_Zoom_FitPage
```

En namngiven åtgärd för att anpassa sidan.

### View_Zoom_FitVisible {#View_Zoom_FitVisible}
```
public static final PredefinedAction View_Zoom_FitVisible
```

En namngiven åtgärd för att anpassa sidans synlighet.

### View_Zoom_FitWidth {#View_Zoom_FitWidth}
```
public static final PredefinedAction View_Zoom_FitWidth
```

En namngiven åtgärd för att anpassa sidan till bredden.

### View_Zoom_ZoomTo {#View_Zoom_ZoomTo}
```
public static final PredefinedAction View_Zoom_ZoomTo
```

En namngiven åtgärd för att zooma.

### Window_FullScreenMode {#Window_FullScreenMode}
```
public static final PredefinedAction Window_FullScreenMode
```

En namngiven åtgärd för att visa dokumentet i helskärmsläge.

### getByValue {#getByValue-int-}
```
public static PredefinedAction getByValue(int value)
```



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  |  |

### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
Returnerar enum‑konstanten av denna typ med det angivna namnet.

### values {#values--}
```
public static PredefinedAction [] values()
```

Returnerar en array som innehåller konstanterna för denna enum‑typ, i den ordning de deklareras.

**Returns:**
en array som innehåller konstanterna för denna enum‑typ, i den ordning de deklareras
