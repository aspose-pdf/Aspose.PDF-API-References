---
title: PredefinedAction
second_title: Aspose.PDF for Java API Reference
description: Defines different actions which can be triggered from a PDF file.
type: docs
weight: 296
url: /java/com.aspose.pdf/predefinedaction/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PredefinedAction extends System.Enum
```

Defines different actions which can be triggered from a PDF file.
## Fields

| Field | Description |
| --- | --- |
| [FirstPage](#FirstPage) | A named action to go to the first page. |
| [LastPage](#LastPage) | A named action to go to the last page. |
| [NextPage](#NextPage) | A named action to go to the next page. |
| [PrevPage](#PrevPage) | A named action to go to the previous page. |
| [PrintDialog](#PrintDialog) | A named action to open a print dialog (JavaScript). |
| [Print](#Print) | A named action to open a print dialog. |
| [Bookmarks_ExpanCurrentBookmark](#Bookmarks-ExpanCurrentBookmark) | A named action to find current bookmark. |
| [Bookmarks_HightlightCurrentBookmark](#Bookmarks-HightlightCurrentBookmark) | A named action to highlight current bookmark. |
| [Document_AttachFile](#Document-AttachFile) | A named action to add file attachment. |
| [Document_CropPages](#Document-CropPages) | A named action to crop document pages. |
| [Document_DeletePages](#Document-DeletePages) | A named action to delete document pages. |
| [Document_ExtractPages](#Document-ExtractPages) | A named action to exctract document pages. |
| [Document_InsertPages](#Document-InsertPages) | A named action to insert pages from a document. |
| [Document_ReplacePages](#Document-ReplacePages) | A named action to replace document pages. |
| [Document_RotatePages](#Document-RotatePages) | A named action to rotate document pages. |
| [Edit_CheckSpelling_InComFieldEdit](#Edit-CheckSpelling-InComFieldEdit) | A named action to check spelling in comments. |
| [Edit_Find](#Edit-Find) | A named action to find. |
| [Edit_Preferences](#Edit-Preferences) | A named action to edit preferences. |
| [Edit_Search](#Edit-Search) | A named action for searching. |
| [File_AttachToEmail](#File-AttachToEmail) | A named action for attaching current pdf document into email message. |
| [File_Close](#File-Close) | A named action to close the document. |
| [File_CreatePDF_FromScanner](#File-CreatePDF-FromScanner) | A named action to create pdf document from scanner. |
| [File_CreatePDF_FromWebPage](#File-CreatePDF-FromWebPage) | A named action to create pdf document from web page. |
| [File_Exit](#File-Exit) | A named action to exit pdf reader. |
| [File_Organizer_OpenOrganizer](#File-Organizer-OpenOrganizer) | A named action to open organizer. |
| [File_Print](#File-Print) | A named action to print the document. |
| [File_Properties](#File-Properties) | A named action to open the document properties. |
| [File_SaveAs](#File-SaveAs) | A named action to save the document with another name. |
| [Miscellaneous_ZoomIn](#Miscellaneous-ZoomIn) | A named action to zoom in the document. |
| [Miscellaneous_ZoomOut](#Miscellaneous-ZoomOut) | A named action to zoom out the document. |
| [PageImages_PrintPages](#PageImages-PrintPages) | A named action to print the document pages. |
| [View_GoTo_NextView](#View-GoTo-NextView) | A named action to go to the next view. |
| [View_GoTo_Page](#View-GoTo-Page) | A named action to go to the certain page. |
| [View_GoTo_PreDocument](#View-GoTo-PreDocument) | A named action to go to the previous document. |
| [View_GoTo_PreView](#View-GoTo-PreView) | A named action to go to the previous view. |
| [View_NavigationPanels_Articles](#View-NavigationPanels-Articles) | A named action to show/hide articles panel. |
| [View_NavigationPanels_Attachments](#View-NavigationPanels-Attachments) | A named action to show/hide attachment panel. |
| [View_NavigationPanels_Boomarks](#View-NavigationPanels-Boomarks) | A named action to show/hide bookmark panel. |
| [View_NavigationPanels_Comments](#View-NavigationPanels-Comments) | A named action to show/hide comments panel. |
| [View_NavigationPanels_Fields](#View-NavigationPanels-Fields) | A named action to show/hide fields panel. |
| [View_NavigationPanels_Layers](#View-NavigationPanels-Layers) | A named action to show/hide layers panel. |
| [View_NavigationPanels_ModelTree](#View-NavigationPanels-ModelTree) | A named action to show/hide model tree panel. |
| [View_NavigationPanels_Pages](#View-NavigationPanels-Pages) | A named action to show/hide pages panel. |
| [View_NavigationPanels_Signatures](#View-NavigationPanels-Signatures) | A named action to show/hide signatures panel. |
| [View_PageDisplay_SinglePage](#View-PageDisplay-SinglePage) | A named action to display single page. |
| [View_PageDisplay_SinglePageContinuous](#View-PageDisplay-SinglePageContinuous) | A named action to display single continious page. |
| [View_PageDisplay_TwoUp](#View-PageDisplay-TwoUp) | A named action to display pages as Two-Up. |
| [View_PageDisplay_TwoUpContinuous](#View-PageDisplay-TwoUpContinuous) | A named action to display pages as Two-Up continious. |
| [View_Toolbars_AdvanceEditing](#View-Toolbars-AdvanceEditing) | A named action to show/hide advanced editing toolbar. |
| [View_Toolbars_CommentMarkup](#View-Toolbars-CommentMarkup) | A named action to show/hide commenting toolbar. |
| [View_Toolbars_Edit](#View-Toolbars-Edit) | A named action to show/hide edit toolbar. |
| [View_Toolbars_File](#View-Toolbars-File) | A named action to show/hide file toolbar. |
| [View_Toolbars_Find](#View-Toolbars-Find) | A named action to show/hide find toolbar. |
| [View_Toolbars_Forms](#View-Toolbars-Forms) | A named action to show/hide forms toolbar. |
| [View_Toolbars_Measuring](#View-Toolbars-Measuring) | A named action to show/hide measuring toolbar. |
| [View_Toolbars_ObjectData](#View-Toolbars-ObjectData) | A named action to show/hide object data toolbar. |
| [View_Toolbars_PageDisplay](#View-Toolbars-PageDisplay) | A named action to show/hide page display toolbar. |
| [View_Toolbars_PageNavigation](#View-Toolbars-PageNavigation) | A named action to show/hide navigation toolbar. |
| [View_Toolbars_PrintProduction](#View-Toolbars-PrintProduction) | A named action to show/hide print production toolbar. |
| [View_Toolbars_PropertiesBar](#View-Toolbars-PropertiesBar) | A named action to show/hide property toolbar. |
| [View_Toolbars_Redaction](#View-Toolbars-Redaction) | A named action to show/hide redaction toolbar. |
| [View_Toolbars_SelectZoom](#View-Toolbars-SelectZoom) | A named action to show/hide select & zoom toolbar. |
| [View_Toolbars_Tasks](#View-Toolbars-Tasks) | A named action to show/hide tasks toolbar. |
| [View_Toolbars_Typewriter](#View-Toolbars-Typewriter) | A named action to show/hide typewriter toolbar. |
| [View_Zoom_ActualSize](#View-Zoom-ActualSize) | A named action to view pages in actual size. |
| [View_Zoom_FitHeight](#View-Zoom-FitHeight) | A named action to fit page on height. |
| [View_Zoom_FitPage](#View-Zoom-FitPage) | A named action to fit page. |
| [View_Zoom_FitVisible](#View-Zoom-FitVisible) | A named action to fit page visibility. |
| [View_Zoom_FitWidth](#View-Zoom-FitWidth) | A named action to fit page on width. |
| [View_Zoom_ZoomTo](#View-Zoom-ZoomTo) | A named action to make zoom. |
| [Window_FullScreenMode](#Window-FullScreenMode) | A named action to view the document in the full screen mode. |
### FirstPage {#FirstPage}
```
public static final int FirstPage
```


A named action to go to the first page.

### LastPage {#LastPage}
```
public static final int LastPage
```


A named action to go to the last page.

### NextPage {#NextPage}
```
public static final int NextPage
```


A named action to go to the next page.

### PrevPage {#PrevPage}
```
public static final int PrevPage
```


A named action to go to the previous page.

### PrintDialog {#PrintDialog}
```
public static final int PrintDialog
```


A named action to open a print dialog (JavaScript).

### Print {#Print}
```
public static final int Print
```


A named action to open a print dialog.

### Bookmarks_ExpanCurrentBookmark {#Bookmarks-ExpanCurrentBookmark}
```
public static final int Bookmarks_ExpanCurrentBookmark
```


A named action to find current bookmark.

### Bookmarks_HightlightCurrentBookmark {#Bookmarks-HightlightCurrentBookmark}
```
public static final int Bookmarks_HightlightCurrentBookmark
```


A named action to highlight current bookmark.

### Document_AttachFile {#Document-AttachFile}
```
public static final int Document_AttachFile
```


A named action to add file attachment.

### Document_CropPages {#Document-CropPages}
```
public static final int Document_CropPages
```


A named action to crop document pages.

### Document_DeletePages {#Document-DeletePages}
```
public static final int Document_DeletePages
```


A named action to delete document pages.

### Document_ExtractPages {#Document-ExtractPages}
```
public static final int Document_ExtractPages
```


A named action to exctract document pages.

### Document_InsertPages {#Document-InsertPages}
```
public static final int Document_InsertPages
```


A named action to insert pages from a document.

### Document_ReplacePages {#Document-ReplacePages}
```
public static final int Document_ReplacePages
```


A named action to replace document pages.

### Document_RotatePages {#Document-RotatePages}
```
public static final int Document_RotatePages
```


A named action to rotate document pages.

### Edit_CheckSpelling_InComFieldEdit {#Edit-CheckSpelling-InComFieldEdit}
```
public static final int Edit_CheckSpelling_InComFieldEdit
```


A named action to check spelling in comments.

### Edit_Find {#Edit-Find}
```
public static final int Edit_Find
```


A named action to find.

### Edit_Preferences {#Edit-Preferences}
```
public static final int Edit_Preferences
```


A named action to edit preferences.

### Edit_Search {#Edit-Search}
```
public static final int Edit_Search
```


A named action for searching.

### File_AttachToEmail {#File-AttachToEmail}
```
public static final int File_AttachToEmail
```


A named action for attaching current pdf document into email message.

### File_Close {#File-Close}
```
public static final int File_Close
```


A named action to close the document.

### File_CreatePDF_FromScanner {#File-CreatePDF-FromScanner}
```
public static final int File_CreatePDF_FromScanner
```


A named action to create pdf document from scanner.

### File_CreatePDF_FromWebPage {#File-CreatePDF-FromWebPage}
```
public static final int File_CreatePDF_FromWebPage
```


A named action to create pdf document from web page.

### File_Exit {#File-Exit}
```
public static final int File_Exit
```


A named action to exit pdf reader.

### File_Organizer_OpenOrganizer {#File-Organizer-OpenOrganizer}
```
public static final int File_Organizer_OpenOrganizer
```


A named action to open organizer.

### File_Print {#File-Print}
```
public static final int File_Print
```


A named action to print the document.

### File_Properties {#File-Properties}
```
public static final int File_Properties
```


A named action to open the document properties.

### File_SaveAs {#File-SaveAs}
```
public static final int File_SaveAs
```


A named action to save the document with another name.

### Miscellaneous_ZoomIn {#Miscellaneous-ZoomIn}
```
public static final int Miscellaneous_ZoomIn
```


A named action to zoom in the document.

### Miscellaneous_ZoomOut {#Miscellaneous-ZoomOut}
```
public static final int Miscellaneous_ZoomOut
```


A named action to zoom out the document.

### PageImages_PrintPages {#PageImages-PrintPages}
```
public static final int PageImages_PrintPages
```


A named action to print the document pages.

### View_GoTo_NextView {#View-GoTo-NextView}
```
public static final int View_GoTo_NextView
```


A named action to go to the next view.

### View_GoTo_Page {#View-GoTo-Page}
```
public static final int View_GoTo_Page
```


A named action to go to the certain page.

### View_GoTo_PreDocument {#View-GoTo-PreDocument}
```
public static final int View_GoTo_PreDocument
```


A named action to go to the previous document.

### View_GoTo_PreView {#View-GoTo-PreView}
```
public static final int View_GoTo_PreView
```


A named action to go to the previous view.

### View_NavigationPanels_Articles {#View-NavigationPanels-Articles}
```
public static final int View_NavigationPanels_Articles
```


A named action to show/hide articles panel.

### View_NavigationPanels_Attachments {#View-NavigationPanels-Attachments}
```
public static final int View_NavigationPanels_Attachments
```


A named action to show/hide attachment panel.

### View_NavigationPanels_Boomarks {#View-NavigationPanels-Boomarks}
```
public static final int View_NavigationPanels_Boomarks
```


A named action to show/hide bookmark panel.

### View_NavigationPanels_Comments {#View-NavigationPanels-Comments}
```
public static final int View_NavigationPanels_Comments
```


A named action to show/hide comments panel.

### View_NavigationPanels_Fields {#View-NavigationPanels-Fields}
```
public static final int View_NavigationPanels_Fields
```


A named action to show/hide fields panel.

### View_NavigationPanels_Layers {#View-NavigationPanels-Layers}
```
public static final int View_NavigationPanels_Layers
```


A named action to show/hide layers panel.

### View_NavigationPanels_ModelTree {#View-NavigationPanels-ModelTree}
```
public static final int View_NavigationPanels_ModelTree
```


A named action to show/hide model tree panel.

### View_NavigationPanels_Pages {#View-NavigationPanels-Pages}
```
public static final int View_NavigationPanels_Pages
```


A named action to show/hide pages panel.

### View_NavigationPanels_Signatures {#View-NavigationPanels-Signatures}
```
public static final int View_NavigationPanels_Signatures
```


A named action to show/hide signatures panel.

### View_PageDisplay_SinglePage {#View-PageDisplay-SinglePage}
```
public static final int View_PageDisplay_SinglePage
```


A named action to display single page.

### View_PageDisplay_SinglePageContinuous {#View-PageDisplay-SinglePageContinuous}
```
public static final int View_PageDisplay_SinglePageContinuous
```


A named action to display single continious page.

### View_PageDisplay_TwoUp {#View-PageDisplay-TwoUp}
```
public static final int View_PageDisplay_TwoUp
```


A named action to display pages as Two-Up.

### View_PageDisplay_TwoUpContinuous {#View-PageDisplay-TwoUpContinuous}
```
public static final int View_PageDisplay_TwoUpContinuous
```


A named action to display pages as Two-Up continious.

### View_Toolbars_AdvanceEditing {#View-Toolbars-AdvanceEditing}
```
public static final int View_Toolbars_AdvanceEditing
```


A named action to show/hide advanced editing toolbar.

### View_Toolbars_CommentMarkup {#View-Toolbars-CommentMarkup}
```
public static final int View_Toolbars_CommentMarkup
```


A named action to show/hide commenting toolbar.

### View_Toolbars_Edit {#View-Toolbars-Edit}
```
public static final int View_Toolbars_Edit
```


A named action to show/hide edit toolbar.

### View_Toolbars_File {#View-Toolbars-File}
```
public static final int View_Toolbars_File
```


A named action to show/hide file toolbar.

### View_Toolbars_Find {#View-Toolbars-Find}
```
public static final int View_Toolbars_Find
```


A named action to show/hide find toolbar.

### View_Toolbars_Forms {#View-Toolbars-Forms}
```
public static final int View_Toolbars_Forms
```


A named action to show/hide forms toolbar.

### View_Toolbars_Measuring {#View-Toolbars-Measuring}
```
public static final int View_Toolbars_Measuring
```


A named action to show/hide measuring toolbar.

### View_Toolbars_ObjectData {#View-Toolbars-ObjectData}
```
public static final int View_Toolbars_ObjectData
```


A named action to show/hide object data toolbar.

### View_Toolbars_PageDisplay {#View-Toolbars-PageDisplay}
```
public static final int View_Toolbars_PageDisplay
```


A named action to show/hide page display toolbar.

### View_Toolbars_PageNavigation {#View-Toolbars-PageNavigation}
```
public static final int View_Toolbars_PageNavigation
```


A named action to show/hide navigation toolbar.

### View_Toolbars_PrintProduction {#View-Toolbars-PrintProduction}
```
public static final int View_Toolbars_PrintProduction
```


A named action to show/hide print production toolbar.

### View_Toolbars_PropertiesBar {#View-Toolbars-PropertiesBar}
```
public static final int View_Toolbars_PropertiesBar
```


A named action to show/hide property toolbar.

### View_Toolbars_Redaction {#View-Toolbars-Redaction}
```
public static final int View_Toolbars_Redaction
```


A named action to show/hide redaction toolbar.

### View_Toolbars_SelectZoom {#View-Toolbars-SelectZoom}
```
public static final int View_Toolbars_SelectZoom
```


A named action to show/hide select & zoom toolbar.

### View_Toolbars_Tasks {#View-Toolbars-Tasks}
```
public static final int View_Toolbars_Tasks
```


A named action to show/hide tasks toolbar.

### View_Toolbars_Typewriter {#View-Toolbars-Typewriter}
```
public static final int View_Toolbars_Typewriter
```


A named action to show/hide typewriter toolbar.

### View_Zoom_ActualSize {#View-Zoom-ActualSize}
```
public static final int View_Zoom_ActualSize
```


A named action to view pages in actual size.

### View_Zoom_FitHeight {#View-Zoom-FitHeight}
```
public static final int View_Zoom_FitHeight
```


A named action to fit page on height.

### View_Zoom_FitPage {#View-Zoom-FitPage}
```
public static final int View_Zoom_FitPage
```


A named action to fit page.

### View_Zoom_FitVisible {#View-Zoom-FitVisible}
```
public static final int View_Zoom_FitVisible
```


A named action to fit page visibility.

### View_Zoom_FitWidth {#View-Zoom-FitWidth}
```
public static final int View_Zoom_FitWidth
```


A named action to fit page on width.

### View_Zoom_ZoomTo {#View-Zoom-ZoomTo}
```
public static final int View_Zoom_ZoomTo
```


A named action to make zoom.

### Window_FullScreenMode {#Window-FullScreenMode}
```
public static final int Window_FullScreenMode
```


A named action to view the document in the full screen mode.

