---
title: PredefinedAction
second_title: Aspose.PDF для справки по Java API
description: Определяет различные действия, которые могут быть запущены из файла PDF.
type: docs
weight: 293
url: /ru/java/com.aspose.pdf/predefinedaction/
---
**Наследование:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PredefinedAction extends System.Enum
```

Определяет различные действия, которые могут быть запущены из файла PDF.
## Поля

| Поле | Описание |
| --- | --- |
| [Bookmarks_ExpanCurrentBookmark](#Bookmarks-ExpanCurrentBookmark) | Именованное действие для поиска текущей закладки. |
| [Bookmarks_HightlightCurrentBookmark](#Bookmarks-HightlightCurrentBookmark) | Именованное действие для выделения текущей закладки. |
| [Document_AttachFile](#Document-AttachFile) | Именованное действие для добавления вложенного файла. |
| [Document_CropPages](#Document-CropPages) | Именованное действие для обрезки страниц документа. |
| [Document_DeletePages](#Document-DeletePages) | Именованное действие для удаления страниц документа. |
| [Document_ExtractPages](#Document-ExtractPages) | Именованное действие для извлечения страниц документа. |
| [Document_InsertPages](#Document-InsertPages) | Именованное действие для вставки страниц из документа. |
| [Document_ReplacePages](#Document-ReplacePages) | Именованное действие для замены страниц документа. |
| [Document_RotatePages](#Document-RotatePages) | Именованное действие для поворота страниц документа. |
| [Edit_CheckSpelling_InComFieldEdit](#Edit-CheckSpelling-InComFieldEdit) | Именованное действие для проверки орфографии в комментариях. |
| [Edit_Find](#Edit-Find) | Именованное действие для поиска. |
| [Edit_Preferences](#Edit-Preferences) | Именованное действие для редактирования настроек. |
| [Edit_Search](#Edit-Search) | Именованное действие для поиска. |
| [EnumSeparatorCharArray](#EnumSeparatorCharArray) |  |
| [File_AttachToEmail](#File-AttachToEmail) | Именованное действие для прикрепления текущего pdf-документа к сообщению электронной почты. |
| [File_Close](#File-Close) | Именованное действие для закрытия документа. |
| [File_CreatePDF_FromScanner](#File-CreatePDF-FromScanner) | Именованное действие для создания pdf-документа из сканера. |
| [File_CreatePDF_FromWebPage](#File-CreatePDF-FromWebPage) | Именованное действие для создания pdf-документа из веб-страницы. |
| [File_Exit](#File-Exit) | Именованное действие для выхода из программы чтения PDF. |
| [File_Organizer_OpenOrganizer](#File-Organizer-OpenOrganizer) | Именованное действие для открытия органайзера. |
| [File_Print](#File-Print) | Именованное действие для печати документа. |
| [File_Properties](#File-Properties) | Именованное действие для открытия свойств документа. |
| [File_SaveAs](#File-SaveAs) | Именованное действие для сохранения документа под другим именем. |
| [FirstPage](#FirstPage) | Именованное действие для перехода на первую страницу. |
| [LastPage](#LastPage) | Именованное действие для перехода на последнюю страницу. |
| [Miscellaneous_ZoomIn](#Miscellaneous-ZoomIn) | Именованное действие для увеличения документа. |
| [Miscellaneous_ZoomOut](#Miscellaneous-ZoomOut) | Именованное действие для уменьшения масштаба документа. |
| [NextPage](#NextPage) | Именованное действие для перехода на следующую страницу. |
| [PageImages_PrintPages](#PageImages-PrintPages) | Именованное действие для печати страниц документа. |
| [PrevPage](#PrevPage) | Именованное действие для перехода на предыдущую страницу. |
| [Print](#Print) | Именованное действие для открытия диалогового окна печати. |
| [PrintDialog](#PrintDialog) | Именованное действие для открытия диалогового окна печати (JavaScript). |
| [View_GoTo_NextView](#View-GoTo-NextView) | Именованное действие для перехода к следующему представлению. |
| [View_GoTo_Page](#View-GoTo-Page) | Именованное действие для перехода на определенную страницу. |
| [View_GoTo_PreDocument](#View-GoTo-PreDocument) | Именованное действие для перехода к предыдущему документу. |
| [View_GoTo_PreView](#View-GoTo-PreView) | Именованное действие для перехода к предыдущему виду. |
| [View_NavigationPanels_Articles](#View-NavigationPanels-Articles) | Именованное действие для отображения/скрытия панели статей. |
| [View_NavigationPanels_Attachments](#View-NavigationPanels-Attachments) | Именованное действие для отображения/скрытия панели вложений. |
| [View_NavigationPanels_Boomarks](#View-NavigationPanels-Boomarks) | Именованное действие для отображения/скрытия панели закладок. |
| [View_NavigationPanels_Comments](#View-NavigationPanels-Comments) | Именованное действие для отображения/скрытия панели комментариев. |
| [View_NavigationPanels_Fields](#View-NavigationPanels-Fields) | Именованное действие для отображения/скрытия панели полей. |
| [View_NavigationPanels_Layers](#View-NavigationPanels-Layers) | Именованное действие для отображения/скрытия панели слоев. |
| [View_NavigationPanels_ModelTree](#View-NavigationPanels-ModelTree) | Именованное действие для отображения/скрытия панели дерева модели. |
| [View_NavigationPanels_Pages](#View-NavigationPanels-Pages) | Именованное действие для отображения/скрытия панели страниц. |
| [View_NavigationPanels_Signatures](#View-NavigationPanels-Signatures) | Именованное действие для отображения/скрытия панели подписей. |
| [View_PageDisplay_SinglePage](#View-PageDisplay-SinglePage) | Именованное действие для отображения одной страницы. |
| [View_PageDisplay_SinglePageContinuous](#View-PageDisplay-SinglePageContinuous) | Именованное действие для отображения одной непрерывной страницы. |
| [View_PageDisplay_TwoUp](#View-PageDisplay-TwoUp) | Именованное действие для отображения страниц как Two-Up. |
| [View_PageDisplay_TwoUpContinuous](#View-PageDisplay-TwoUpContinuous) | Именованное действие для отображения страниц в непрерывном режиме Two-Up. |
| [View_Toolbars_AdvanceEditing](#View-Toolbars-AdvanceEditing) | Именованное действие для отображения/скрытия расширенной панели инструментов редактирования. |
| [View_Toolbars_CommentMarkup](#View-Toolbars-CommentMarkup) | Именованное действие для отображения/скрытия панели инструментов комментариев. |
| [View_Toolbars_Edit](#View-Toolbars-Edit) | Именованное действие для отображения/скрытия панели инструментов редактирования. |
| [View_Toolbars_File](#View-Toolbars-File) | Именованное действие для отображения/скрытия панели инструментов файла. |
| [View_Toolbars_Find](#View-Toolbars-Find) | Именованное действие для отображения/скрытия панели инструментов поиска. |
| [View_Toolbars_Forms](#View-Toolbars-Forms) | Именованное действие для отображения/скрытия панели инструментов форм. |
| [View_Toolbars_Measuring](#View-Toolbars-Measuring) | Именованное действие для отображения/скрытия измерительной панели инструментов. |
| [View_Toolbars_ObjectData](#View-Toolbars-ObjectData) | Именованное действие для отображения/скрытия панели инструментов данных объекта. |
| [View_Toolbars_PageDisplay](#View-Toolbars-PageDisplay) | Именованное действие для отображения/скрытия панели инструментов отображения страницы. |
| [View_Toolbars_PageNavigation](#View-Toolbars-PageNavigation) | Именованное действие для отображения/скрытия панели инструментов навигации. |
| [View_Toolbars_PrintProduction](#View-Toolbars-PrintProduction) | Именованное действие для отображения/скрытия панели инструментов печати. |
| [View_Toolbars_PropertiesBar](#View-Toolbars-PropertiesBar) | Именованное действие для отображения/скрытия панели свойств. |
| [View_Toolbars_Redaction](#View-Toolbars-Redaction) | Именованное действие для отображения/скрытия панели редактирования. |
| [View_Toolbars_SelectZoom](#View-Toolbars-SelectZoom) | Именованное действие для отображения/скрытия панели инструментов выбора и масштабирования. |
| [View_Toolbars_Tasks](#View-Toolbars-Tasks) | Именованное действие для отображения/скрытия панели задач. |
| [View_Toolbars_Typewriter](#View-Toolbars-Typewriter) | Именованное действие для отображения/скрытия панели инструментов пишущей машинки. |
| [View_Zoom_ActualSize](#View-Zoom-ActualSize) | Именованное действие для просмотра страниц в реальном размере. |
| [View_Zoom_FitHeight](#View-Zoom-FitHeight) | Именованное действие для размещения страницы по высоте. |
| [View_Zoom_FitPage](#View-Zoom-FitPage) | Именованное действие для размещения на странице. |
| [View_Zoom_FitVisible](#View-Zoom-FitVisible) | Именованное действие, соответствующее видимости страницы. |
| [View_Zoom_FitWidth](#View-Zoom-FitWidth) | Именованное действие для размещения страницы по ширине. |
| [View_Zoom_ZoomTo](#View-Zoom-ZoomTo) | Именованное действие для масштабирования. |
| [Window_FullScreenMode](#Window-FullScreenMode) | Именованное действие для просмотра документа в полноэкранном режиме. |
## Методы

| Method | Description |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(System.Enum arg0)](#CloneTo-com.aspose.ms.System.Enum-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [format(System.Type arg0, Object arg1, String arg2)](#format-com.aspose.ms.System.Type-java.lang.Object-java.lang.String-) |  |
| [format(Class<?> arg0, long arg1, String arg2)](#format-java.lang.Class----long-java.lang.String-) |  |
| [getClass()](#getClass--) |  |
| [getName(Class<?> arg0, long arg1)](#getName-java.lang.Class----long-) |  |
| [getNames(System.Type arg0)](#getNames-com.aspose.ms.System.Type-) |  |
| [getNames(Class<?> arg0)](#getNames-java.lang.Class----) |  |
| [getUnderlyingType(System.Type arg0)](#getUnderlyingType-com.aspose.ms.System.Type-) |  |
| [getUnderlyingType(Class<?> arg0)](#getUnderlyingType-java.lang.Class----) |  |
| [getValue(Class<?> arg0, String arg1)](#getValue-java.lang.Class----java.lang.String-) |  |
| [getValues(System.Type arg0)](#getValues-com.aspose.ms.System.Type-) |  |
| [get_Caption()](#get-Caption--) |  |
| [get_Value()](#get-Value--) |  |
| [hashCode()](#hashCode--) |  |
| [isDefined(System.Type arg0, Object arg1)](#isDefined-com.aspose.ms.System.Type-java.lang.Object-) |  |
| [isDefined(System.Type arg0, String arg1)](#isDefined-com.aspose.ms.System.Type-java.lang.String-) |  |
| [isDefined(System.Type arg0, long arg1)](#isDefined-com.aspose.ms.System.Type-long-) |  |
| [isDefined(Class<?> arg0, long arg1)](#isDefined-java.lang.Class----long-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parse(System.Type arg0, String arg1)](#parse-com.aspose.ms.System.Type-java.lang.String-) |  |
| [parse(System.Type arg0, String arg1, Boolean arg2)](#parse-com.aspose.ms.System.Type-java.lang.String-java.lang.Boolean-) |  |
| [parse(Class<?> arg0, String arg1)](#parse-java.lang.Class----java.lang.String-) |  |
| [parse(Class<?> arg0, String arg1, Boolean arg2)](#parse-java.lang.Class----java.lang.String-java.lang.Boolean-) |  |
| [register(System.Enum.AbstractEnum arg0)](#register-com.aspose.ms.System.Enum.AbstractEnum-) |  |
| [toObject(System.Type arg0, Object arg1)](#toObject-com.aspose.ms.System.Type-java.lang.Object-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Bookmarks_ExpanCurrentBookmark {#Bookmarks-ExpanCurrentBookmark}
```
public static final int Bookmarks_ExpanCurrentBookmark
```


Именованное действие для поиска текущей закладки.

### Bookmarks_HightlightCurrentBookmark {#Bookmarks-HightlightCurrentBookmark}
```
public static final int Bookmarks_HightlightCurrentBookmark
```


Именованное действие для выделения текущей закладки.

### Document_AttachFile {#Document-AttachFile}
```
public static final int Document_AttachFile
```


Именованное действие для добавления вложенного файла.

### Document_CropPages {#Document-CropPages}
```
public static final int Document_CropPages
```


Именованное действие для обрезки страниц документа.

### Document_DeletePages {#Document-DeletePages}
```
public static final int Document_DeletePages
```


Именованное действие для удаления страниц документа.

### Document_ExtractPages {#Document-ExtractPages}
```
public static final int Document_ExtractPages
```


Именованное действие для извлечения страниц документа.

### Document_InsertPages {#Document-InsertPages}
```
public static final int Document_InsertPages
```


Именованное действие для вставки страниц из документа.

### Document_ReplacePages {#Document-ReplacePages}
```
public static final int Document_ReplacePages
```


Именованное действие для замены страниц документа.

### Document_RotatePages {#Document-RotatePages}
```
public static final int Document_RotatePages
```


Именованное действие для поворота страниц документа.

### Edit_CheckSpelling_InComFieldEdit {#Edit-CheckSpelling-InComFieldEdit}
```
public static final int Edit_CheckSpelling_InComFieldEdit
```


Именованное действие для проверки орфографии в комментариях.

### Edit_Find {#Edit-Find}
```
public static final int Edit_Find
```


Именованное действие для поиска.

### Edit_Preferences {#Edit-Preferences}
```
public static final int Edit_Preferences
```


Именованное действие для редактирования настроек.

### Edit_Search {#Edit-Search}
```
public static final int Edit_Search
```


Именованное действие для поиска.

### EnumSeparatorCharArray {#EnumSeparatorCharArray}
```
public static final char[] EnumSeparatorCharArray
```


### File_AttachToEmail {#File-AttachToEmail}
```
public static final int File_AttachToEmail
```


Именованное действие для прикрепления текущего pdf-документа к сообщению электронной почты.

### File_Close {#File-Close}
```
public static final int File_Close
```


Именованное действие для закрытия документа.

### File_CreatePDF_FromScanner {#File-CreatePDF-FromScanner}
```
public static final int File_CreatePDF_FromScanner
```


Именованное действие для создания pdf-документа из сканера.

### File_CreatePDF_FromWebPage {#File-CreatePDF-FromWebPage}
```
public static final int File_CreatePDF_FromWebPage
```


Именованное действие для создания pdf-документа из веб-страницы.

### File_Exit {#File-Exit}
```
public static final int File_Exit
```


Именованное действие для выхода из программы чтения PDF.

### File_Organizer_OpenOrganizer {#File-Organizer-OpenOrganizer}
```
public static final int File_Organizer_OpenOrganizer
```


Именованное действие для открытия органайзера.

### File_Print {#File-Print}
```
public static final int File_Print
```


Именованное действие для печати документа.

### File_Properties {#File-Properties}
```
public static final int File_Properties
```


Именованное действие для открытия свойств документа.

### File_SaveAs {#File-SaveAs}
```
public static final int File_SaveAs
```


Именованное действие для сохранения документа под другим именем.

### FirstPage {#FirstPage}
```
public static final int FirstPage
```


Именованное действие для перехода на первую страницу.

### LastPage {#LastPage}
```
public static final int LastPage
```


Именованное действие для перехода на последнюю страницу.

### Miscellaneous_ZoomIn {#Miscellaneous-ZoomIn}
```
public static final int Miscellaneous_ZoomIn
```


Именованное действие для увеличения документа.

### Miscellaneous_ZoomOut {#Miscellaneous-ZoomOut}
```
public static final int Miscellaneous_ZoomOut
```


Именованное действие для уменьшения масштаба документа.

### NextPage {#NextPage}
```
public static final int NextPage
```


Именованное действие для перехода на следующую страницу.

### PageImages_PrintPages {#PageImages-PrintPages}
```
public static final int PageImages_PrintPages
```


Именованное действие для печати страниц документа.

### PrevPage {#PrevPage}
```
public static final int PrevPage
```


Именованное действие для перехода на предыдущую страницу.

### Print {#Print}
```
public static final int Print
```


Именованное действие для открытия диалогового окна печати.

### PrintDialog {#PrintDialog}
```
public static final int PrintDialog
```


Именованное действие для открытия диалогового окна печати (JavaScript).

### View_GoTo_NextView {#View-GoTo-NextView}
```
public static final int View_GoTo_NextView
```


Именованное действие для перехода к следующему представлению.

### View_GoTo_Page {#View-GoTo-Page}
```
public static final int View_GoTo_Page
```


Именованное действие для перехода на определенную страницу.

### View_GoTo_PreDocument {#View-GoTo-PreDocument}
```
public static final int View_GoTo_PreDocument
```


Именованное действие для перехода к предыдущему документу.

### View_GoTo_PreView {#View-GoTo-PreView}
```
public static final int View_GoTo_PreView
```


Именованное действие для перехода к предыдущему виду.

### View_NavigationPanels_Articles {#View-NavigationPanels-Articles}
```
public static final int View_NavigationPanels_Articles
```


Именованное действие для отображения/скрытия панели статей.

### View_NavigationPanels_Attachments {#View-NavigationPanels-Attachments}
```
public static final int View_NavigationPanels_Attachments
```


Именованное действие для отображения/скрытия панели вложений.

### View_NavigationPanels_Boomarks {#View-NavigationPanels-Boomarks}
```
public static final int View_NavigationPanels_Boomarks
```


Именованное действие для отображения/скрытия панели закладок.

### View_NavigationPanels_Comments {#View-NavigationPanels-Comments}
```
public static final int View_NavigationPanels_Comments
```


Именованное действие для отображения/скрытия панели комментариев.

### View_NavigationPanels_Fields {#View-NavigationPanels-Fields}
```
public static final int View_NavigationPanels_Fields
```


Именованное действие для отображения/скрытия панели полей.

### View_NavigationPanels_Layers {#View-NavigationPanels-Layers}
```
public static final int View_NavigationPanels_Layers
```


Именованное действие для отображения/скрытия панели слоев.

### View_NavigationPanels_ModelTree {#View-NavigationPanels-ModelTree}
```
public static final int View_NavigationPanels_ModelTree
```


Именованное действие для отображения/скрытия панели дерева модели.

### View_NavigationPanels_Pages {#View-NavigationPanels-Pages}
```
public static final int View_NavigationPanels_Pages
```


Именованное действие для отображения/скрытия панели страниц.

### View_NavigationPanels_Signatures {#View-NavigationPanels-Signatures}
```
public static final int View_NavigationPanels_Signatures
```


Именованное действие для отображения/скрытия панели подписей.

### View_PageDisplay_SinglePage {#View-PageDisplay-SinglePage}
```
public static final int View_PageDisplay_SinglePage
```


Именованное действие для отображения одной страницы.

### View_PageDisplay_SinglePageContinuous {#View-PageDisplay-SinglePageContinuous}
```
public static final int View_PageDisplay_SinglePageContinuous
```


Именованное действие для отображения одной непрерывной страницы.

### View_PageDisplay_TwoUp {#View-PageDisplay-TwoUp}
```
public static final int View_PageDisplay_TwoUp
```


Именованное действие для отображения страниц как Two-Up.

### View_PageDisplay_TwoUpContinuous {#View-PageDisplay-TwoUpContinuous}
```
public static final int View_PageDisplay_TwoUpContinuous
```


Именованное действие для отображения страниц в непрерывном режиме Two-Up.

### View_Toolbars_AdvanceEditing {#View-Toolbars-AdvanceEditing}
```
public static final int View_Toolbars_AdvanceEditing
```


Именованное действие для отображения/скрытия расширенной панели инструментов редактирования.

### View_Toolbars_CommentMarkup {#View-Toolbars-CommentMarkup}
```
public static final int View_Toolbars_CommentMarkup
```


Именованное действие для отображения/скрытия панели инструментов комментариев.

### View_Toolbars_Edit {#View-Toolbars-Edit}
```
public static final int View_Toolbars_Edit
```


Именованное действие для отображения/скрытия панели инструментов редактирования.

### View_Toolbars_File {#View-Toolbars-File}
```
public static final int View_Toolbars_File
```


Именованное действие для отображения/скрытия панели инструментов файла.

### View_Toolbars_Find {#View-Toolbars-Find}
```
public static final int View_Toolbars_Find
```


Именованное действие для отображения/скрытия панели инструментов поиска.

### View_Toolbars_Forms {#View-Toolbars-Forms}
```
public static final int View_Toolbars_Forms
```


Именованное действие для отображения/скрытия панели инструментов форм.

### View_Toolbars_Measuring {#View-Toolbars-Measuring}
```
public static final int View_Toolbars_Measuring
```


Именованное действие для отображения/скрытия измерительной панели инструментов.

### View_Toolbars_ObjectData {#View-Toolbars-ObjectData}
```
public static final int View_Toolbars_ObjectData
```


Именованное действие для отображения/скрытия панели инструментов данных объекта.

### View_Toolbars_PageDisplay {#View-Toolbars-PageDisplay}
```
public static final int View_Toolbars_PageDisplay
```


Именованное действие для отображения/скрытия панели инструментов отображения страницы.

### View_Toolbars_PageNavigation {#View-Toolbars-PageNavigation}
```
public static final int View_Toolbars_PageNavigation
```


Именованное действие для отображения/скрытия панели инструментов навигации.

### View_Toolbars_PrintProduction {#View-Toolbars-PrintProduction}
```
public static final int View_Toolbars_PrintProduction
```


Именованное действие для отображения/скрытия панели инструментов печати.

### View_Toolbars_PropertiesBar {#View-Toolbars-PropertiesBar}
```
public static final int View_Toolbars_PropertiesBar
```


Именованное действие для отображения/скрытия панели свойств.

### View_Toolbars_Redaction {#View-Toolbars-Redaction}
```
public static final int View_Toolbars_Redaction
```


Именованное действие для отображения/скрытия панели редактирования.

### View_Toolbars_SelectZoom {#View-Toolbars-SelectZoom}
```
public static final int View_Toolbars_SelectZoom
```


Именованное действие для отображения/скрытия панели инструментов выбора и масштабирования.

### View_Toolbars_Tasks {#View-Toolbars-Tasks}
```
public static final int View_Toolbars_Tasks
```


Именованное действие для отображения/скрытия панели задач.

### View_Toolbars_Typewriter {#View-Toolbars-Typewriter}
```
public static final int View_Toolbars_Typewriter
```


Именованное действие для отображения/скрытия панели инструментов пишущей машинки.

### View_Zoom_ActualSize {#View-Zoom-ActualSize}
```
public static final int View_Zoom_ActualSize
```


Именованное действие для просмотра страниц в реальном размере.

### View_Zoom_FitHeight {#View-Zoom-FitHeight}
```
public static final int View_Zoom_FitHeight
```


Именованное действие для размещения страницы по высоте.

### View_Zoom_FitPage {#View-Zoom-FitPage}
```
public static final int View_Zoom_FitPage
```


Именованное действие для размещения на странице.

### View_Zoom_FitVisible {#View-Zoom-FitVisible}
```
public static final int View_Zoom_FitVisible
```


Именованное действие, соответствующее видимости страницы.

### View_Zoom_FitWidth {#View-Zoom-FitWidth}
```
public static final int View_Zoom_FitWidth
```


Именованное действие для размещения страницы по ширине.

### View_Zoom_ZoomTo {#View-Zoom-ZoomTo}
```
public static final int View_Zoom_ZoomTo
```


Именованное действие для масштабирования.

### Window_FullScreenMode {#Window-FullScreenMode}
```
public static final int Window_FullScreenMode
```


Именованное действие для просмотра документа в полноэкранном режиме.

### Clone() {#Clone--}
```
public System.Enum Clone()
```




**Возвращает:**
com.aspose.ms.System.Enum
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(System.Enum arg0) {#CloneTo-com.aspose.ms.System.Enum-}
```
public void CloneTo(System.Enum arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Enum |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Возвращает:**
логический
### format(System.Type arg0, Object arg1, String arg2) {#format-com.aspose.ms.System.Type-java.lang.Object-java.lang.String-}
```
public static String format(System.Type arg0, Object arg1, String arg2)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.Object |  |
| arg2 | java.lang.String |  |

**Возвращает:**
java.lang.String
### format(Class<?> arg0, long arg1, String arg2) {#format-java.lang.Class----long-java.lang.String-}
```
public static String format(Class<?> arg0, long arg1, String arg2)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | long |  |
| arg2 | java.lang.String |  |

**Возвращает:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getName(Class<?> arg0, long arg1) {#getName-java.lang.Class----long-}
```
public static String getName(Class<?> arg0, long arg1)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | long |  |

**Возвращает:**
java.lang.String
### getNames(System.Type arg0) {#getNames-com.aspose.ms.System.Type-}
```
public static String[] getNames(System.Type arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |

**Возвращает:**
java.lang.String[]
### getNames(Class<?> arg0) {#getNames-java.lang.Class----}
```
public static Collection<String> getNames(Class<?> arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |

**Возвращает:**
[Collection](../../java.util/collection)
### getUnderlyingType(System.Type arg0) {#getUnderlyingType-com.aspose.ms.System.Type-}
```
public static System.Type getUnderlyingType(System.Type arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |

**Возвращает:**
com.aspose.ms.System.Type
### getUnderlyingType(Class<?> arg0) {#getUnderlyingType-java.lang.Class----}
```
public static Class<? extends Number> getUnderlyingType(Class<?> arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |

**Возвращает:**
java.lang.Класс<? расширяет java.lang.Number>
### getValue(Class<?> arg0, String arg1) {#getValue-java.lang.Class----java.lang.String-}
```
public static long getValue(Class<?> arg0, String arg1)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | java.lang.String |  |

**Возвращает:**
длинная
### getValues(System.Type arg0) {#getValues-com.aspose.ms.System.Type-}
```
public static System.Array getValues(System.Type arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |

**Возвращает:**
com.aspose.ms.System.Array
### get_Caption() {#get-Caption--}
```
public String get_Caption()
```




**Возвращает:**
java.lang.String
### get_Value() {#get-Value--}
```
public long get_Value()
```




**Возвращает:**
длинная
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### isDefined(System.Type arg0, Object arg1) {#isDefined-com.aspose.ms.System.Type-java.lang.Object-}
```
public static boolean isDefined(System.Type arg0, Object arg1)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.Object |  |

**Возвращает:**
логический
### isDefined(System.Type arg0, String arg1) {#isDefined-com.aspose.ms.System.Type-java.lang.String-}
```
public static boolean isDefined(System.Type arg0, String arg1)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.String |  |

**Возвращает:**
логический
### isDefined(System.Type arg0, long arg1) {#isDefined-com.aspose.ms.System.Type-long-}
```
public static boolean isDefined(System.Type arg0, long arg1)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | long |  |

**Возвращает:**
логический
### isDefined(Class<?> arg0, long arg1) {#isDefined-java.lang.Class----long-}
```
public static boolean isDefined(Class<?> arg0, long arg1)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | long |  |

**Возвращает:**
логический
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### parse(System.Type arg0, String arg1) {#parse-com.aspose.ms.System.Type-java.lang.String-}
```
public static long parse(System.Type arg0, String arg1)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.String |  |

**Возвращает:**
длинная
### parse(System.Type arg0, String arg1, Boolean arg2) {#parse-com.aspose.ms.System.Type-java.lang.String-java.lang.Boolean-}
```
public static long parse(System.Type arg0, String arg1, Boolean arg2)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.String |  |
| arg2 | java.lang.Boolean |  |

**Возвращает:**
длинная
### parse(Class<?> arg0, String arg1) {#parse-java.lang.Class----java.lang.String-}
```
public static long parse(Class<?> arg0, String arg1)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | java.lang.String |  |

**Возвращает:**
длинная
### parse(Class<?> arg0, String arg1, Boolean arg2) {#parse-java.lang.Class----java.lang.String-java.lang.Boolean-}
```
public static long parse(Class<?> arg0, String arg1, Boolean arg2)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | java.lang.String |  |
| arg2 | java.lang.Boolean |  |

**Возвращает:**
длинная
### register(System.Enum.AbstractEnum arg0) {#register-com.aspose.ms.System.Enum.AbstractEnum-}
```
public static void register(System.Enum.AbstractEnum arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Enum.AbstractEnum |  |

### toObject(System.Type arg0, Object arg1) {#toObject-com.aspose.ms.System.Type-java.lang.Object-}
```
public static Object toObject(System.Type arg0, Object arg1)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.Object |  |

**Возвращает:**
java.lang.Объект
### toString() {#toString--}
```
public String toString()
```




**Возвращает:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |
