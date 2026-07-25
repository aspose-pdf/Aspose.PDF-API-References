---
title: "PredefinedAction"
linktitle: "PredefinedAction"
second_title: "Aspose.PDF for Java API 参考"
description: "定义可以从 PDF 文件触发的不同操作。"
type: docs
weight: 3960
url: /zh/java/com.aspose.pdf/predefinedaction/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < PredefinedAction > com.aspose.pdf.PredefinedAction, java.lang.Enum < PredefinedAction >, com.aspose.pdf.PredefinedAction

**All Implemented Interfaces:**
Serializable, Comparable < PredefinedAction >

```
public enum PredefinedAction extends Enum < PredefinedAction >
```

定义可以从 PDF 文件触发的不同操作。

## 字段

| 字段 | 描述 |
| --- | --- |
| [Bookmarks_ExpanCurrentBookmark](#Bookmarks_ExpanCurrentBookmark) | 用于查找当前书签的命名操作。 |
| [Bookmarks_HightlightCurrentBookmark](#Bookmarks_HightlightCurrentBookmark) | 用于突出显示当前书签的命名操作。 |
| [Document_AttachFile](#Document_AttachFile) | 用于添加文件附件的命名操作。 |
| [Document_CropPages](#Document_CropPages) | 一个用于裁剪文档页面的命名操作。 |
| [Document_DeletePages](#Document_DeletePages) | 一个用于删除文档页面的命名操作。 |
| [Document_ExtractPages](#Document_ExtractPages) | 一个用于提取文档页面的命名操作。 |
| [Document_InsertPages](#Document_InsertPages) | 一个用于从文档中插入页面的命名操作。 |
| [Document_ReplacePages](#Document_ReplacePages) | 一个用于替换文档页面的命名操作。 |
| [Document_RotatePages](#Document_RotatePages) | 一个用于旋转文档页面的命名操作。 |
| [Edit_CheckSpelling_InComFieldEdit](#Edit_CheckSpelling_InComFieldEdit) | 一个用于检查注释中拼写的命名操作。 |
| [Edit_Find](#Edit_Find) | 一个用于查找的命名操作。 |
| [Edit_Preferences](#Edit_Preferences) | 一个用于编辑首选项的命名操作。 |
| [Edit_Search](#Edit_Search) | 一个用于搜索的命名操作。 |
| [File_AttachToEmail](#File_AttachToEmail) | 一个用于将当前 PDF 文档附加到电子邮件的命名操作。 |
| [File_Close](#File_Close) | 一个用于关闭文档的命名操作。 |
| [File_CreatePDF_FromScanner](#File_CreatePDF_FromScanner) | 一个用于从扫描仪创建 PDF 文档的命名操作。 |
| [File_CreatePDF_FromWebPage](#File_CreatePDF_FromWebPage) | 一个用于从网页创建 PDF 文档的命名操作。 |
| [File_Exit](#File_Exit) | 一个用于退出 PDF 阅读器的命名操作。 |
| [File_Organizer_OpenOrganizer](#File_Organizer_OpenOrganizer) | 一个用于打开组织器的命名操作。 |
| [File_Print](#File_Print) | 一个用于打印文档的命名操作。 |
| [File_Properties](#File_Properties) | 一个用于打开文档属性的命名操作。 |
| [File_SaveAs](#File_SaveAs) | 一个用于以其他名称保存文档的命名操作。 |
| [FirstPage](#FirstPage) | 一个用于转到首页的命名操作。 |
| [LastPage](#LastPage) | 一个用于转到末页的命名操作。 |
| [Miscellaneous_ZoomIn](#Miscellaneous_ZoomIn) | 一个用于放大文档的命名操作。 |
| [Miscellaneous_ZoomOut](#Miscellaneous_ZoomOut) | 一个用于缩小文档的命名操作。 |
| [NextPage](#NextPage) | 一个用于转到下一页的命名操作。 |
| [PageImages_PrintPages](#PageImages_PrintPages) | 一个用于打印文档页面的命名操作。 |
| [PrevPage](#PrevPage) | 一个命名操作用于转到上一页。 |
| [Print](#Print) | 一个命名操作用于打开打印对话框。 |
| [PrintDialog](#PrintDialog) | 一个命名操作用于打开打印对话框（JavaScript）。 |
| [View_GoTo_NextView](#View_GoTo_NextView) | 一个命名操作用于转到下一个视图。 |
| [View_GoTo_Page](#View_GoTo_Page) | 一个命名操作用于转到特定页面。 |
| [View_GoTo_PreDocument](#View_GoTo_PreDocument) | 一个命名操作用于转到上一个文档。 |
| [View_GoTo_PreView](#View_GoTo_PreView) | 一个命名操作用于转到上一个视图。 |
| [View_NavigationPanels_Articles](#View_NavigationPanels_Articles) | 一个命名操作用于显示/隐藏文章面板。 |
| [View_NavigationPanels_Attachments](#View_NavigationPanels_Attachments) | 一个命名操作用于显示/隐藏附件面板。 |
| [View_NavigationPanels_Boomarks](#View_NavigationPanels_Boomarks) | 一个命名操作用于显示/隐藏书签面板。 |
| [View_NavigationPanels_Comments](#View_NavigationPanels_Comments) | 一个命名操作用于显示/隐藏评论面板。 |
| [View_NavigationPanels_Fields](#View_NavigationPanels_Fields) | 一个命名操作用于显示/隐藏字段面板。 |
| [View_NavigationPanels_Layers](#View_NavigationPanels_Layers) | 一个命名操作用于显示/隐藏图层面板。 |
| [View_NavigationPanels_ModelTree](#View_NavigationPanels_ModelTree) | 一个命名操作用于显示/隐藏模型树面板。 |
| [View_NavigationPanels_Pages](#View_NavigationPanels_Pages) | 一个命名操作用于显示/隐藏页面面板。 |
| [View_NavigationPanels_Signatures](#View_NavigationPanels_Signatures) | 一个命名操作用于显示/隐藏签名面板。 |
| [View_PageDisplay_SinglePage](#View_PageDisplay_SinglePage) | 一个命名操作用于显示单页。 |
| [View_PageDisplay_SinglePageContinuous](#View_PageDisplay_SinglePageContinuous) | 一个命名操作用于显示单个连续页面。 |
| [View_PageDisplay_TwoUp](#View_PageDisplay_TwoUp) | 一个命名操作用于将页面显示为双页。 |
| [View_PageDisplay_TwoUpContinuous](#View_PageDisplay_TwoUpContinuous) | 一个命名操作用于将页面连续显示为双页。 |
| [View_Toolbars_AdvanceEditing](#View_Toolbars_AdvanceEditing) | 一个命名操作用于显示/隐藏高级编辑工具栏。 |
| [View_Toolbars_CommentMarkup](#View_Toolbars_CommentMarkup) | 一个命名操作用于显示/隐藏评论工具栏。 |
| [View_Toolbars_Edit](#View_Toolbars_Edit) | 一个命名操作用于显示/隐藏编辑工具栏。 |
| [View_Toolbars_File](#View_Toolbars_File) | 一个命名操作用于显示/隐藏文件工具栏。 |
| [View_Toolbars_Find](#View_Toolbars_Find) | 一个命名操作用于显示/隐藏查找工具栏。 |
| [View_Toolbars_Forms](#View_Toolbars_Forms) | 一个用于显示/隐藏表单工具栏的命名操作。 |
| [View_Toolbars_Measuring](#View_Toolbars_Measuring) | 一个用于显示/隐藏测量工具栏的命名操作。 |
| [View_Toolbars_ObjectData](#View_Toolbars_ObjectData) | 一个用于显示/隐藏对象数据工具栏的命名操作。 |
| [View_Toolbars_PageDisplay](#View_Toolbars_PageDisplay) | 一个用于显示/隐藏页面显示工具栏的命名操作。 |
| [View_Toolbars_PageNavigation](#View_Toolbars_PageNavigation) | 一个用于显示/隐藏导航工具栏的命名操作。 |
| [View_Toolbars_PrintProduction](#View_Toolbars_PrintProduction) | 一个用于显示/隐藏打印生产工具栏的命名操作。 |
| [View_Toolbars_PropertiesBar](#View_Toolbars_PropertiesBar) | 一个用于显示/隐藏属性工具栏的命名操作。 |
| [View_Toolbars_Redaction](#View_Toolbars_Redaction) | 一个用于显示/隐藏编辑工具栏的命名操作。 |
| [View_Toolbars_SelectZoom](#View_Toolbars_SelectZoom) | 一个用于显示/隐藏选择与缩放工具栏的命名操作。 |
| [View_Toolbars_Tasks](#View_Toolbars_Tasks) | 一个用于显示/隐藏任务工具栏的命名操作。 |
| [View_Toolbars_Typewriter](#View_Toolbars_Typewriter) | 一个用于显示/隐藏打字机工具栏的命名操作。 |
| [View_Zoom_ActualSize](#View_Zoom_ActualSize) | 一个用于以实际大小查看页面的命名操作。 |
| [View_Zoom_FitHeight](#View_Zoom_FitHeight) | 一个用于按高度适配页面的命名操作。 |
| [View_Zoom_FitPage](#View_Zoom_FitPage) | 一个用于适配页面的命名操作。 |
| [View_Zoom_FitVisible](#View_Zoom_FitVisible) | 一个用于适配页面可见性的命名操作。 |
| [View_Zoom_FitWidth](#View_Zoom_FitWidth) | 一个用于按宽度适配页面的命名操作。 |
| [View_Zoom_ZoomTo](#View_Zoom_ZoomTo) | 一个用于进行缩放的命名操作。 |
| [Window_FullScreenMode](#Window_FullScreenMode) | 一个用于在全屏模式下查看文档的命名操作。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | 返回此类型中具有指定名称的枚举常量。 |
| [values](#values--) | 返回一个数组，包含此枚举类型的常量，按声明顺序排列。 |

### Bookmarks_ExpanCurrentBookmark {#Bookmarks_ExpanCurrentBookmark}
```
public static final PredefinedAction Bookmarks_ExpanCurrentBookmark
```

用于查找当前书签的命名操作。

### Bookmarks_HightlightCurrentBookmark {#Bookmarks_HightlightCurrentBookmark}
```
public static final PredefinedAction Bookmarks_HightlightCurrentBookmark
```

用于突出显示当前书签的命名操作。

### Document_AttachFile {#Document_AttachFile}
```
public static final PredefinedAction Document_AttachFile
```

用于添加文件附件的命名操作。

### Document_CropPages {#Document_CropPages}
```
public static final PredefinedAction Document_CropPages
```

一个用于裁剪文档页面的命名操作。

### Document_DeletePages {#Document_DeletePages}
```
public static final PredefinedAction Document_DeletePages
```

一个用于删除文档页面的命名操作。

### Document_ExtractPages {#Document_ExtractPages}
```
public static final PredefinedAction Document_ExtractPages
```

一个用于提取文档页面的命名操作。

### Document_InsertPages {#Document_InsertPages}
```
public static final PredefinedAction Document_InsertPages
```

一个用于从文档中插入页面的命名操作。

### Document_ReplacePages {#Document_ReplacePages}
```
public static final PredefinedAction Document_ReplacePages
```

一个用于替换文档页面的命名操作。

### Document_RotatePages {#Document_RotatePages}
```
public static final PredefinedAction Document_RotatePages
```

一个用于旋转文档页面的命名操作。

### Edit_CheckSpelling_InComFieldEdit {#Edit_CheckSpelling_InComFieldEdit}
```
public static final PredefinedAction Edit_CheckSpelling_InComFieldEdit
```

一个用于检查注释中拼写的命名操作。

### Edit_Find {#Edit_Find}
```
public static final PredefinedAction Edit_Find
```

一个用于查找的命名操作。

### Edit_Preferences {#Edit_Preferences}
```
public static final PredefinedAction Edit_Preferences
```

一个用于编辑首选项的命名操作。

### Edit_Search {#Edit_Search}
```
public static final PredefinedAction Edit_Search
```

一个用于搜索的命名操作。

### File_AttachToEmail {#File_AttachToEmail}
```
public static final PredefinedAction File_AttachToEmail
```

一个用于将当前 PDF 文档附加到电子邮件的命名操作。

### File_Close {#File_Close}
```
public static final PredefinedAction File_Close
```

一个用于关闭文档的命名操作。

### File_CreatePDF_FromScanner {#File_CreatePDF_FromScanner}
```
public static final PredefinedAction File_CreatePDF_FromScanner
```

一个用于从扫描仪创建 PDF 文档的命名操作。

### File_CreatePDF_FromWebPage {#File_CreatePDF_FromWebPage}
```
public static final PredefinedAction File_CreatePDF_FromWebPage
```

一个用于从网页创建 PDF 文档的命名操作。

### File_Exit {#File_Exit}
```
public static final PredefinedAction File_Exit
```

一个用于退出 PDF 阅读器的命名操作。

### File_Organizer_OpenOrganizer {#File_Organizer_OpenOrganizer}
```
public static final PredefinedAction File_Organizer_OpenOrganizer
```

一个用于打开组织器的命名操作。

### File_Print {#File_Print}
```
public static final PredefinedAction File_Print
```

一个用于打印文档的命名操作。

### File_Properties {#File_Properties}
```
public static final PredefinedAction File_Properties
```

一个用于打开文档属性的命名操作。

### File_SaveAs {#File_SaveAs}
```
public static final PredefinedAction File_SaveAs
```

一个用于以其他名称保存文档的命名操作。

### FirstPage {#FirstPage}
```
public static final PredefinedAction FirstPage
```

一个用于转到首页的命名操作。

### LastPage {#LastPage}
```
public static final PredefinedAction LastPage
```

一个用于转到末页的命名操作。

### Miscellaneous_ZoomIn {#Miscellaneous_ZoomIn}
```
public static final PredefinedAction Miscellaneous_ZoomIn
```

一个用于放大文档的命名操作。

### Miscellaneous_ZoomOut {#Miscellaneous_ZoomOut}
```
public static final PredefinedAction Miscellaneous_ZoomOut
```

一个用于缩小文档的命名操作。

### NextPage {#NextPage}
```
public static final PredefinedAction NextPage
```

一个用于转到下一页的命名操作。

### PageImages_PrintPages {#PageImages_PrintPages}
```
public static final PredefinedAction PageImages_PrintPages
```

一个用于打印文档页面的命名操作。

### PrevPage {#PrevPage}
```
public static final PredefinedAction PrevPage
```

一个命名操作用于转到上一页。

### Print {#Print}
```
public static final PredefinedAction Print
```

一个命名操作用于打开打印对话框。

### PrintDialog {#PrintDialog}
```
public static final PredefinedAction PrintDialog
```

一个命名操作用于打开打印对话框（JavaScript）。

### View_GoTo_NextView {#View_GoTo_NextView}
```
public static final PredefinedAction View_GoTo_NextView
```

一个命名操作用于转到下一个视图。

### View_GoTo_Page {#View_GoTo_Page}
```
public static final PredefinedAction View_GoTo_Page
```

一个命名操作用于转到特定页面。

### View_GoTo_PreDocument {#View_GoTo_PreDocument}
```
public static final PredefinedAction View_GoTo_PreDocument
```

一个命名操作用于转到上一个文档。

### View_GoTo_PreView {#View_GoTo_PreView}
```
public static final PredefinedAction View_GoTo_PreView
```

一个命名操作用于转到上一个视图。

### View_NavigationPanels_Articles {#View_NavigationPanels_Articles}
```
public static final PredefinedAction View_NavigationPanels_Articles
```

一个命名操作用于显示/隐藏文章面板。

### View_NavigationPanels_Attachments {#View_NavigationPanels_Attachments}
```
public static final PredefinedAction View_NavigationPanels_Attachments
```

一个命名操作用于显示/隐藏附件面板。

### View_NavigationPanels_Boomarks {#View_NavigationPanels_Boomarks}
```
public static final PredefinedAction View_NavigationPanels_Boomarks
```

一个命名操作用于显示/隐藏书签面板。

### View_NavigationPanels_Comments {#View_NavigationPanels_Comments}
```
public static final PredefinedAction View_NavigationPanels_Comments
```

一个命名操作用于显示/隐藏评论面板。

### View_NavigationPanels_Fields {#View_NavigationPanels_Fields}
```
public static final PredefinedAction View_NavigationPanels_Fields
```

一个命名操作用于显示/隐藏字段面板。

### View_NavigationPanels_Layers {#View_NavigationPanels_Layers}
```
public static final PredefinedAction View_NavigationPanels_Layers
```

一个命名操作用于显示/隐藏图层面板。

### View_NavigationPanels_ModelTree {#View_NavigationPanels_ModelTree}
```
public static final PredefinedAction View_NavigationPanels_ModelTree
```

一个命名操作用于显示/隐藏模型树面板。

### View_NavigationPanels_Pages {#View_NavigationPanels_Pages}
```
public static final PredefinedAction View_NavigationPanels_Pages
```

一个命名操作用于显示/隐藏页面面板。

### View_NavigationPanels_Signatures {#View_NavigationPanels_Signatures}
```
public static final PredefinedAction View_NavigationPanels_Signatures
```

一个命名操作用于显示/隐藏签名面板。

### View_PageDisplay_SinglePage {#View_PageDisplay_SinglePage}
```
public static final PredefinedAction View_PageDisplay_SinglePage
```

一个命名操作用于显示单页。

### View_PageDisplay_SinglePageContinuous {#View_PageDisplay_SinglePageContinuous}
```
public static final PredefinedAction View_PageDisplay_SinglePageContinuous
```

一个命名操作用于显示单个连续页面。

### View_PageDisplay_TwoUp {#View_PageDisplay_TwoUp}
```
public static final PredefinedAction View_PageDisplay_TwoUp
```

一个命名操作用于将页面显示为双页。

### View_PageDisplay_TwoUpContinuous {#View_PageDisplay_TwoUpContinuous}
```
public static final PredefinedAction View_PageDisplay_TwoUpContinuous
```

一个命名操作用于将页面连续显示为双页。

### View_Toolbars_AdvanceEditing {#View_Toolbars_AdvanceEditing}
```
public static final PredefinedAction View_Toolbars_AdvanceEditing
```

一个命名操作用于显示/隐藏高级编辑工具栏。

### View_Toolbars_CommentMarkup {#View_Toolbars_CommentMarkup}
```
public static final PredefinedAction View_Toolbars_CommentMarkup
```

一个命名操作用于显示/隐藏评论工具栏。

### View_Toolbars_Edit {#View_Toolbars_Edit}
```
public static final PredefinedAction View_Toolbars_Edit
```

一个命名操作用于显示/隐藏编辑工具栏。

### View_Toolbars_File {#View_Toolbars_File}
```
public static final PredefinedAction View_Toolbars_File
```

一个命名操作用于显示/隐藏文件工具栏。

### View_Toolbars_Find {#View_Toolbars_Find}
```
public static final PredefinedAction View_Toolbars_Find
```

一个命名操作用于显示/隐藏查找工具栏。

### View_Toolbars_Forms {#View_Toolbars_Forms}
```
public static final PredefinedAction View_Toolbars_Forms
```

一个用于显示/隐藏表单工具栏的命名操作。

### View_Toolbars_Measuring {#View_Toolbars_Measuring}
```
public static final PredefinedAction View_Toolbars_Measuring
```

一个用于显示/隐藏测量工具栏的命名操作。

### View_Toolbars_ObjectData {#View_Toolbars_ObjectData}
```
public static final PredefinedAction View_Toolbars_ObjectData
```

一个用于显示/隐藏对象数据工具栏的命名操作。

### View_Toolbars_PageDisplay {#View_Toolbars_PageDisplay}
```
public static final PredefinedAction View_Toolbars_PageDisplay
```

一个用于显示/隐藏页面显示工具栏的命名操作。

### View_Toolbars_PageNavigation {#View_Toolbars_PageNavigation}
```
public static final PredefinedAction View_Toolbars_PageNavigation
```

一个用于显示/隐藏导航工具栏的命名操作。

### View_Toolbars_PrintProduction {#View_Toolbars_PrintProduction}
```
public static final PredefinedAction View_Toolbars_PrintProduction
```

一个用于显示/隐藏打印生产工具栏的命名操作。

### View_Toolbars_PropertiesBar {#View_Toolbars_PropertiesBar}
```
public static final PredefinedAction View_Toolbars_PropertiesBar
```

一个用于显示/隐藏属性工具栏的命名操作。

### View_Toolbars_Redaction {#View_Toolbars_Redaction}
```
public static final PredefinedAction View_Toolbars_Redaction
```

一个用于显示/隐藏编辑工具栏的命名操作。

### View_Toolbars_SelectZoom {#View_Toolbars_SelectZoom}
```
public static final PredefinedAction View_Toolbars_SelectZoom
```

一个用于显示/隐藏选择与缩放工具栏的命名操作。

### View_Toolbars_Tasks {#View_Toolbars_Tasks}
```
public static final PredefinedAction View_Toolbars_Tasks
```

一个用于显示/隐藏任务工具栏的命名操作。

### View_Toolbars_Typewriter {#View_Toolbars_Typewriter}
```
public static final PredefinedAction View_Toolbars_Typewriter
```

一个用于显示/隐藏打字机工具栏的命名操作。

### View_Zoom_ActualSize {#View_Zoom_ActualSize}
```
public static final PredefinedAction View_Zoom_ActualSize
```

一个用于以实际大小查看页面的命名操作。

### View_Zoom_FitHeight {#View_Zoom_FitHeight}
```
public static final PredefinedAction View_Zoom_FitHeight
```

一个用于按高度适配页面的命名操作。

### View_Zoom_FitPage {#View_Zoom_FitPage}
```
public static final PredefinedAction View_Zoom_FitPage
```

一个用于适配页面的命名操作。

### View_Zoom_FitVisible {#View_Zoom_FitVisible}
```
public static final PredefinedAction View_Zoom_FitVisible
```

一个用于适配页面可见性的命名操作。

### View_Zoom_FitWidth {#View_Zoom_FitWidth}
```
public static final PredefinedAction View_Zoom_FitWidth
```

一个用于按宽度适配页面的命名操作。

### View_Zoom_ZoomTo {#View_Zoom_ZoomTo}
```
public static final PredefinedAction View_Zoom_ZoomTo
```

一个用于进行缩放的命名操作。

### Window_FullScreenMode {#Window_FullScreenMode}
```
public static final PredefinedAction Window_FullScreenMode
```

一个用于在全屏模式下查看文档的命名操作。

### getByValue {#getByValue-int-}
```
public static PredefinedAction getByValue(int value)
```



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  |  |

### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
返回此类型中具有指定名称的枚举常量。

### values {#values--}
```
public static PredefinedAction [] values()
```

返回一个数组，包含此枚举类型的常量，按声明顺序排列。

**Returns:**
一个数组，包含此枚举类型的常量，按声明顺序排列
