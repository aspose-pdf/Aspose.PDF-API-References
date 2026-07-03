---
title: PredefinedAction
second_title: Aspose.PDF for Java API Reference
description: Defines different actions which can be triggered from a PDF file.
type: docs
weight: 3960
url: /java/com.aspose.pdf/predefinedaction/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < PredefinedAction > com.aspose.pdf.PredefinedAction, java.lang.Enum < PredefinedAction >, com.aspose.pdf.PredefinedAction

**All Implemented Interfaces:**
Serializable, Comparable < PredefinedAction >

```
public enum PredefinedAction extends Enum < PredefinedAction >
```

Defines different actions which can be triggered from a PDF file.

## Fields

| Field | Description |
| --- | --- |
| [Bookmarks_ExpanCurrentBookmark](#Bookmarks_ExpanCurrentBookmark) | A named action to find current bookmark. |
| [Bookmarks_HightlightCurrentBookmark](#Bookmarks_HightlightCurrentBookmark) | A named action to highlight current bookmark. |
| [Document_AttachFile](#Document_AttachFile) | A named action to add file attachment. |
| [Document_CropPages](#Document_CropPages) | A named action to crop document pages. |
| [Document_DeletePages](#Document_DeletePages) | A named action to delete document pages. |
| [Document_ExtractPages](#Document_ExtractPages) | A named action to exctract document pages. |
| [Document_InsertPages](#Document_InsertPages) | A named action to insert pages from a document. |
| [Document_ReplacePages](#Document_ReplacePages) | A named action to replace document pages. |
| [Document_RotatePages](#Document_RotatePages) | A named action to rotate document pages. |
| [Edit_CheckSpelling_InComFieldEdit](#Edit_CheckSpelling_InComFieldEdit) | A named action to check spelling in comments. |
| [Edit_Find](#Edit_Find) | A named action to find. |
| [Edit_Preferences](#Edit_Preferences) | A named action to edit preferences. |
| [Edit_Search](#Edit_Search) | A named action for searching. |
| [File_AttachToEmail](#File_AttachToEmail) | A named action for attaching current pdf document into email message. |
| [File_Close](#File_Close) | A named action to close the document. |
| [File_CreatePDF_FromScanner](#File_CreatePDF_FromScanner) | A named action to create pdf document from scanner. |
| [File_CreatePDF_FromWebPage](#File_CreatePDF_FromWebPage) | A named action to create pdf document from web page. |
| [File_Exit](#File_Exit) | A named action to exit pdf reader. |
| [File_Organizer_OpenOrganizer](#File_Organizer_OpenOrganizer) | A named action to open organizer. |
| [File_Print](#File_Print) | A named action to print the document. |
| [File_Properties](#File_Properties) | A named action to open the document properties. |
| [File_SaveAs](#File_SaveAs) | A named action to save the document with another name. |
| [FirstPage](#FirstPage) | A named action to go to the first page. |
| [LastPage](#LastPage) | A named action to go to the last page. |
| [Miscellaneous_ZoomIn](#Miscellaneous_ZoomIn) | A named action to zoom in the document. |
| [Miscellaneous_ZoomOut](#Miscellaneous_ZoomOut) | A named action to zoom out the document. |
| [NextPage](#NextPage) | A named action to go to the next page. |
| [PageImages_PrintPages](#PageImages_PrintPages) | A named action to print the document pages. |
| [PrevPage](#PrevPage) | A named action to go to the previous page. |
| [Print](#Print) | A named action to open a print dialog. |
| [PrintDialog](#PrintDialog) | A named action to open a print dialog (JavaScript). |
| [View_GoTo_NextView](#View_GoTo_NextView) | A named action to go to the next view. |
| [View_GoTo_Page](#View_GoTo_Page) | A named action to go to the certain page. |
| [View_GoTo_PreDocument](#View_GoTo_PreDocument) | A named action to go to the previous document. |
| [View_GoTo_PreView](#View_GoTo_PreView) | A named action to go to the previous view. |
| [View_NavigationPanels_Articles](#View_NavigationPanels_Articles) | A named action to show/hide articles panel. |
| [View_NavigationPanels_Attachments](#View_NavigationPanels_Attachments) | A named action to show/hide attachment panel. |
| [View_NavigationPanels_Boomarks](#View_NavigationPanels_Boomarks) | A named action to show/hide bookmark panel. |
| [View_NavigationPanels_Comments](#View_NavigationPanels_Comments) | A named action to show/hide comments panel. |
| [View_NavigationPanels_Fields](#View_NavigationPanels_Fields) | A named action to show/hide fields panel. |
| [View_NavigationPanels_Layers](#View_NavigationPanels_Layers) | A named action to show/hide layers panel. |
| [View_NavigationPanels_ModelTree](#View_NavigationPanels_ModelTree) | A named action to show/hide model tree panel. |
| [View_NavigationPanels_Pages](#View_NavigationPanels_Pages) | A named action to show/hide pages panel. |
| [View_NavigationPanels_Signatures](#View_NavigationPanels_Signatures) | A named action to show/hide signatures panel. |
| [View_PageDisplay_SinglePage](#View_PageDisplay_SinglePage) | A named action to display single page. |
| [View_PageDisplay_SinglePageContinuous](#View_PageDisplay_SinglePageContinuous) | A named action to display single continious page. |
| [View_PageDisplay_TwoUp](#View_PageDisplay_TwoUp) | A named action to display pages as Two-Up. |
| [View_PageDisplay_TwoUpContinuous](#View_PageDisplay_TwoUpContinuous) | A named action to display pages as Two-Up continious. |
| [View_Toolbars_AdvanceEditing](#View_Toolbars_AdvanceEditing) | A named action to show/hide advanced editing toolbar. |
| [View_Toolbars_CommentMarkup](#View_Toolbars_CommentMarkup) | A named action to show/hide commenting toolbar. |
| [View_Toolbars_Edit](#View_Toolbars_Edit) | A named action to show/hide edit toolbar. |
| [View_Toolbars_File](#View_Toolbars_File) | A named action to show/hide file toolbar. |
| [View_Toolbars_Find](#View_Toolbars_Find) | A named action to show/hide find toolbar. |
| [View_Toolbars_Forms](#View_Toolbars_Forms) | A named action to show/hide forms toolbar. |
| [View_Toolbars_Measuring](#View_Toolbars_Measuring) | A named action to show/hide measuring toolbar. |
| [View_Toolbars_ObjectData](#View_Toolbars_ObjectData) | A named action to show/hide object data toolbar. |
| [View_Toolbars_PageDisplay](#View_Toolbars_PageDisplay) | A named action to show/hide page display toolbar. |
| [View_Toolbars_PageNavigation](#View_Toolbars_PageNavigation) | A named action to show/hide navigation toolbar. |
| [View_Toolbars_PrintProduction](#View_Toolbars_PrintProduction) | A named action to show/hide print production toolbar. |
| [View_Toolbars_PropertiesBar](#View_Toolbars_PropertiesBar) | A named action to show/hide property toolbar. |
| [View_Toolbars_Redaction](#View_Toolbars_Redaction) | A named action to show/hide redaction toolbar. |
| [View_Toolbars_SelectZoom](#View_Toolbars_SelectZoom) | A named action to show/hide select & zoom toolbar. |
| [View_Toolbars_Tasks](#View_Toolbars_Tasks) | A named action to show/hide tasks toolbar. |
| [View_Toolbars_Typewriter](#View_Toolbars_Typewriter) | A named action to show/hide typewriter toolbar. |
| [View_Zoom_ActualSize](#View_Zoom_ActualSize) | A named action to view pages in actual size. |
| [View_Zoom_FitHeight](#View_Zoom_FitHeight) | A named action to fit page on height. |
| [View_Zoom_FitPage](#View_Zoom_FitPage) | A named action to fit page. |
| [View_Zoom_FitVisible](#View_Zoom_FitVisible) | A named action to fit page visibility. |
| [View_Zoom_FitWidth](#View_Zoom_FitWidth) | A named action to fit page on width. |
| [View_Zoom_ZoomTo](#View_Zoom_ZoomTo) | A named action to make zoom. |
| [Window_FullScreenMode](#Window_FullScreenMode) | A named action to view the document in the full screen mode. |

## Methods

| Method | Description |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | Returns the enum constant of this type with the specified name. |
| [values](#values--) | Returns an array containing the constants of this enum type, in the order they are declared. |

### Bookmarks_ExpanCurrentBookmark {#Bookmarks_ExpanCurrentBookmark}
```
public static final PredefinedAction Bookmarks_ExpanCurrentBookmark
```

A named action to find current bookmark.

### Bookmarks_HightlightCurrentBookmark {#Bookmarks_HightlightCurrentBookmark}
```
public static final PredefinedAction Bookmarks_HightlightCurrentBookmark
```

A named action to highlight current bookmark.

### Document_AttachFile {#Document_AttachFile}
```
public static final PredefinedAction Document_AttachFile
```

A named action to add file attachment.

### Document_CropPages {#Document_CropPages}
```
public static final PredefinedAction Document_CropPages
```

A named action to crop document pages.

### Document_DeletePages {#Document_DeletePages}
```
public static final PredefinedAction Document_DeletePages
```

A named action to delete document pages.

### Document_ExtractPages {#Document_ExtractPages}
```
public static final PredefinedAction Document_ExtractPages
```

A named action to exctract document pages.

### Document_InsertPages {#Document_InsertPages}
```
public static final PredefinedAction Document_InsertPages
```

A named action to insert pages from a document.

### Document_ReplacePages {#Document_ReplacePages}
```
public static final PredefinedAction Document_ReplacePages
```

A named action to replace document pages.

### Document_RotatePages {#Document_RotatePages}
```
public static final PredefinedAction Document_RotatePages
```

A named action to rotate document pages.

### Edit_CheckSpelling_InComFieldEdit {#Edit_CheckSpelling_InComFieldEdit}
```
public static final PredefinedAction Edit_CheckSpelling_InComFieldEdit
```

A named action to check spelling in comments.

### Edit_Find {#Edit_Find}
```
public static final PredefinedAction Edit_Find
```

A named action to find.

### Edit_Preferences {#Edit_Preferences}
```
public static final PredefinedAction Edit_Preferences
```

A named action to edit preferences.

### Edit_Search {#Edit_Search}
```
public static final PredefinedAction Edit_Search
```

A named action for searching.

### File_AttachToEmail {#File_AttachToEmail}
```
public static final PredefinedAction File_AttachToEmail
```

A named action for attaching current pdf document into email message.

### File_Close {#File_Close}
```
public static final PredefinedAction File_Close
```

A named action to close the document.

### File_CreatePDF_FromScanner {#File_CreatePDF_FromScanner}
```
public static final PredefinedAction File_CreatePDF_FromScanner
```

A named action to create pdf document from scanner.

### File_CreatePDF_FromWebPage {#File_CreatePDF_FromWebPage}
```
public static final PredefinedAction File_CreatePDF_FromWebPage
```

A named action to create pdf document from web page.

### File_Exit {#File_Exit}
```
public static final PredefinedAction File_Exit
```

A named action to exit pdf reader.

### File_Organizer_OpenOrganizer {#File_Organizer_OpenOrganizer}
```
public static final PredefinedAction File_Organizer_OpenOrganizer
```

A named action to open organizer.

### File_Print {#File_Print}
```
public static final PredefinedAction File_Print
```

A named action to print the document.

### File_Properties {#File_Properties}
```
public static final PredefinedAction File_Properties
```

A named action to open the document properties.

### File_SaveAs {#File_SaveAs}
```
public static final PredefinedAction File_SaveAs
```

A named action to save the document with another name.

### FirstPage {#FirstPage}
```
public static final PredefinedAction FirstPage
```

A named action to go to the first page.

### LastPage {#LastPage}
```
public static final PredefinedAction LastPage
```

A named action to go to the last page.

### Miscellaneous_ZoomIn {#Miscellaneous_ZoomIn}
```
public static final PredefinedAction Miscellaneous_ZoomIn
```

A named action to zoom in the document.

### Miscellaneous_ZoomOut {#Miscellaneous_ZoomOut}
```
public static final PredefinedAction Miscellaneous_ZoomOut
```

A named action to zoom out the document.

### NextPage {#NextPage}
```
public static final PredefinedAction NextPage
```

A named action to go to the next page.

### PageImages_PrintPages {#PageImages_PrintPages}
```
public static final PredefinedAction PageImages_PrintPages
```

A named action to print the document pages.

### PrevPage {#PrevPage}
```
public static final PredefinedAction PrevPage
```

A named action to go to the previous page.

### Print {#Print}
```
public static final PredefinedAction Print
```

A named action to open a print dialog.

### PrintDialog {#PrintDialog}
```
public static final PredefinedAction PrintDialog
```

A named action to open a print dialog (JavaScript).

### View_GoTo_NextView {#View_GoTo_NextView}
```
public static final PredefinedAction View_GoTo_NextView
```

A named action to go to the next view.

### View_GoTo_Page {#View_GoTo_Page}
```
public static final PredefinedAction View_GoTo_Page
```

A named action to go to the certain page.

### View_GoTo_PreDocument {#View_GoTo_PreDocument}
```
public static final PredefinedAction View_GoTo_PreDocument
```

A named action to go to the previous document.

### View_GoTo_PreView {#View_GoTo_PreView}
```
public static final PredefinedAction View_GoTo_PreView
```

A named action to go to the previous view.

### View_NavigationPanels_Articles {#View_NavigationPanels_Articles}
```
public static final PredefinedAction View_NavigationPanels_Articles
```

A named action to show/hide articles panel.

### View_NavigationPanels_Attachments {#View_NavigationPanels_Attachments}
```
public static final PredefinedAction View_NavigationPanels_Attachments
```

A named action to show/hide attachment panel.

### View_NavigationPanels_Boomarks {#View_NavigationPanels_Boomarks}
```
public static final PredefinedAction View_NavigationPanels_Boomarks
```

A named action to show/hide bookmark panel.

### View_NavigationPanels_Comments {#View_NavigationPanels_Comments}
```
public static final PredefinedAction View_NavigationPanels_Comments
```

A named action to show/hide comments panel.

### View_NavigationPanels_Fields {#View_NavigationPanels_Fields}
```
public static final PredefinedAction View_NavigationPanels_Fields
```

A named action to show/hide fields panel.

### View_NavigationPanels_Layers {#View_NavigationPanels_Layers}
```
public static final PredefinedAction View_NavigationPanels_Layers
```

A named action to show/hide layers panel.

### View_NavigationPanels_ModelTree {#View_NavigationPanels_ModelTree}
```
public static final PredefinedAction View_NavigationPanels_ModelTree
```

A named action to show/hide model tree panel.

### View_NavigationPanels_Pages {#View_NavigationPanels_Pages}
```
public static final PredefinedAction View_NavigationPanels_Pages
```

A named action to show/hide pages panel.

### View_NavigationPanels_Signatures {#View_NavigationPanels_Signatures}
```
public static final PredefinedAction View_NavigationPanels_Signatures
```

A named action to show/hide signatures panel.

### View_PageDisplay_SinglePage {#View_PageDisplay_SinglePage}
```
public static final PredefinedAction View_PageDisplay_SinglePage
```

A named action to display single page.

### View_PageDisplay_SinglePageContinuous {#View_PageDisplay_SinglePageContinuous}
```
public static final PredefinedAction View_PageDisplay_SinglePageContinuous
```

A named action to display single continious page.

### View_PageDisplay_TwoUp {#View_PageDisplay_TwoUp}
```
public static final PredefinedAction View_PageDisplay_TwoUp
```

A named action to display pages as Two-Up.

### View_PageDisplay_TwoUpContinuous {#View_PageDisplay_TwoUpContinuous}
```
public static final PredefinedAction View_PageDisplay_TwoUpContinuous
```

A named action to display pages as Two-Up continious.

### View_Toolbars_AdvanceEditing {#View_Toolbars_AdvanceEditing}
```
public static final PredefinedAction View_Toolbars_AdvanceEditing
```

A named action to show/hide advanced editing toolbar.

### View_Toolbars_CommentMarkup {#View_Toolbars_CommentMarkup}
```
public static final PredefinedAction View_Toolbars_CommentMarkup
```

A named action to show/hide commenting toolbar.

### View_Toolbars_Edit {#View_Toolbars_Edit}
```
public static final PredefinedAction View_Toolbars_Edit
```

A named action to show/hide edit toolbar.

### View_Toolbars_File {#View_Toolbars_File}
```
public static final PredefinedAction View_Toolbars_File
```

A named action to show/hide file toolbar.

### View_Toolbars_Find {#View_Toolbars_Find}
```
public static final PredefinedAction View_Toolbars_Find
```

A named action to show/hide find toolbar.

### View_Toolbars_Forms {#View_Toolbars_Forms}
```
public static final PredefinedAction View_Toolbars_Forms
```

A named action to show/hide forms toolbar.

### View_Toolbars_Measuring {#View_Toolbars_Measuring}
```
public static final PredefinedAction View_Toolbars_Measuring
```

A named action to show/hide measuring toolbar.

### View_Toolbars_ObjectData {#View_Toolbars_ObjectData}
```
public static final PredefinedAction View_Toolbars_ObjectData
```

A named action to show/hide object data toolbar.

### View_Toolbars_PageDisplay {#View_Toolbars_PageDisplay}
```
public static final PredefinedAction View_Toolbars_PageDisplay
```

A named action to show/hide page display toolbar.

### View_Toolbars_PageNavigation {#View_Toolbars_PageNavigation}
```
public static final PredefinedAction View_Toolbars_PageNavigation
```

A named action to show/hide navigation toolbar.

### View_Toolbars_PrintProduction {#View_Toolbars_PrintProduction}
```
public static final PredefinedAction View_Toolbars_PrintProduction
```

A named action to show/hide print production toolbar.

### View_Toolbars_PropertiesBar {#View_Toolbars_PropertiesBar}
```
public static final PredefinedAction View_Toolbars_PropertiesBar
```

A named action to show/hide property toolbar.

### View_Toolbars_Redaction {#View_Toolbars_Redaction}
```
public static final PredefinedAction View_Toolbars_Redaction
```

A named action to show/hide redaction toolbar.

### View_Toolbars_SelectZoom {#View_Toolbars_SelectZoom}
```
public static final PredefinedAction View_Toolbars_SelectZoom
```

A named action to show/hide select & zoom toolbar.

### View_Toolbars_Tasks {#View_Toolbars_Tasks}
```
public static final PredefinedAction View_Toolbars_Tasks
```

A named action to show/hide tasks toolbar.

### View_Toolbars_Typewriter {#View_Toolbars_Typewriter}
```
public static final PredefinedAction View_Toolbars_Typewriter
```

A named action to show/hide typewriter toolbar.

### View_Zoom_ActualSize {#View_Zoom_ActualSize}
```
public static final PredefinedAction View_Zoom_ActualSize
```

A named action to view pages in actual size.

### View_Zoom_FitHeight {#View_Zoom_FitHeight}
```
public static final PredefinedAction View_Zoom_FitHeight
```

A named action to fit page on height.

### View_Zoom_FitPage {#View_Zoom_FitPage}
```
public static final PredefinedAction View_Zoom_FitPage
```

A named action to fit page.

### View_Zoom_FitVisible {#View_Zoom_FitVisible}
```
public static final PredefinedAction View_Zoom_FitVisible
```

A named action to fit page visibility.

### View_Zoom_FitWidth {#View_Zoom_FitWidth}
```
public static final PredefinedAction View_Zoom_FitWidth
```

A named action to fit page on width.

### View_Zoom_ZoomTo {#View_Zoom_ZoomTo}
```
public static final PredefinedAction View_Zoom_ZoomTo
```

A named action to make zoom.

### Window_FullScreenMode {#Window_FullScreenMode}
```
public static final PredefinedAction Window_FullScreenMode
```

A named action to view the document in the full screen mode.

### getByValue {#getByValue-int-}
```
public static PredefinedAction getByValue(int value)
```



**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  |  |

### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
Returns the enum constant of this type with the specified name.

### values {#values--}
```
public static PredefinedAction [] values()
```

Returns an array containing the constants of this enum type, in the order they are declared.

**Returns:**
an array containing the constants of this enum type, in the order they are declared
