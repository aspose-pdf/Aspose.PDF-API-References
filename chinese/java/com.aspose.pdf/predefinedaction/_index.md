---
title: PredefinedAction
second_title: 用于 Java API 参考的 Aspose.PDF
description: 定义可从 PDF 文件触发的不同操作。
type: docs
weight: 293
url: /zh/java/com.aspose.pdf/predefinedaction/
---
**遗产：**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PredefinedAction extends System.Enum
```

定义可从 PDF 文件触发的不同操作。
## 领域

| 场地 | 描述 |
| --- | --- |
| [Bookmarks_ExpanCurrentBookmark](#Bookmarks-ExpanCurrentBookmark) | 查找当前书签的命名操作。 |
| [Bookmarks_HightlightCurrentBookmark](#Bookmarks-HightlightCurrentBookmark) | 用于突出显示当前书签的命名操作。 |
| [Document_AttachFile](#Document-AttachFile) | 添加文件附件的命名操作。 |
| [Document_CropPages](#Document-CropPages) | 裁剪文档页面的命名操作。 |
| [Document_DeletePages](#Document-DeletePages) | 删除文档页面的命名操作。 |
| [Document_ExtractPages](#Document-ExtractPages) | 提取文档页面的命名操作。 |
| [Document_InsertPages](#Document-InsertPages) | 从文档中插入页面的命名操作。 |
| [Document_ReplacePages](#Document-ReplacePages) | 替换文档页面的命名操作。 |
| [Document_RotatePages](#Document-RotatePages) | 旋转文档页面的命名操作。 |
| [Edit_CheckSpelling_InComFieldEdit](#Edit-CheckSpelling-InComFieldEdit) | 检查评论中拼写的命名操作。 |
| [Edit_Find](#Edit-Find) | 要查找的命名操作。 |
| [Edit_Preferences](#Edit-Preferences) | 用于编辑首选项的命名操作。 |
| [Edit_Search](#Edit-Search) | 用于搜索的命名操作。 |
| [EnumSeparatorCharArray](#EnumSeparatorCharArray) |  |
| [File_AttachToEmail](#File-AttachToEmail) | 将当前 pdf 文档附加到电子邮件中的命名操作。 |
| [File_Close](#File-Close) | 关闭文档的命名操作。 |
| [File_CreatePDF_FromScanner](#File-CreatePDF-FromScanner) | 从扫描仪创建 pdf 文档的命名操作。 |
| [File_CreatePDF_FromWebPage](#File-CreatePDF-FromWebPage) | 从网页创建 pdf 文档的命名操作。 |
| [File_Exit](#File-Exit) | 退出 pdf 阅读器的命名操作。 |
| [File_Organizer_OpenOrganizer](#File-Organizer-OpenOrganizer) | 打开管理器的命名操作。 |
| [File_Print](#File-Print) | 打印文档的命名操作。 |
| [File_Properties](#File-Properties) | 打开文档属性的命名操作。 |
| [File_SaveAs](#File-SaveAs) | 用另一个名称保存文档的命名操作。 |
| [FirstPage](#FirstPage) | 转到第一页的命名操作。 |
| [LastPage](#LastPage) | 转到最后一页的命名操作。 |
| [Miscellaneous_ZoomIn](#Miscellaneous-ZoomIn) | 用于放大文档的命名操作。 |
| [Miscellaneous_ZoomOut](#Miscellaneous-ZoomOut) | 缩小文档的命名操作。 |
| [NextPage](#NextPage) | 转到下一页的命名操作。 |
| [PageImages_PrintPages](#PageImages-PrintPages) | 打印文档页面的命名操作。 |
| [PrevPage](#PrevPage) | 转到上一页的命名操作。 |
| [Print](#Print) | 打开打印对话框的命名操作。 |
| [PrintDialog](#PrintDialog) | 打开打印对话框的命名操作 (JavaScript)。 |
| [View_GoTo_NextView](#View-GoTo-NextView) | 转到下一个视图的命名操作。 |
| [View_GoTo_Page](#View-GoTo-Page) | 转到特定页面的命名操作。 |
| [View_GoTo_PreDocument](#View-GoTo-PreDocument) | 转到上一个文档的命名操作。 |
| [View_GoTo_PreView](#View-GoTo-PreView) | 转到上一个视图的命名操作。 |
| [View_NavigationPanels_Articles](#View-NavigationPanels-Articles) | 显示/隐藏文章面板的命名操作。 |
| [View_NavigationPanels_Attachments](#View-NavigationPanels-Attachments) | 显示/隐藏附件面板的命名操作。 |
| [View_NavigationPanels_Boomarks](#View-NavigationPanels-Boomarks) | 显示/隐藏书签面板的命名操作。 |
| [View_NavigationPanels_Comments](#View-NavigationPanels-Comments) | 显示/隐藏评论面板的命名操作。 |
| [View_NavigationPanels_Fields](#View-NavigationPanels-Fields) | 显示/隐藏字段面板的命名操作。 |
| [View_NavigationPanels_Layers](#View-NavigationPanels-Layers) | 显示/隐藏图层面板的命名操作。 |
| [View_NavigationPanels_ModelTree](#View-NavigationPanels-ModelTree) | 显示/隐藏模型树面板的命名操作。 |
| [View_NavigationPanels_Pages](#View-NavigationPanels-Pages) | 显示/隐藏页面面板的命名操作。 |
| [View_NavigationPanels_Signatures](#View-NavigationPanels-Signatures) | 显示/隐藏签名面板的命名操作。 |
| [View_PageDisplay_SinglePage](#View-PageDisplay-SinglePage) | 显示单个页面的命名操作。 |
| [View_PageDisplay_SinglePageContinuous](#View-PageDisplay-SinglePageContinuous) | 显示单个连续页面的命名操作。 |
| [View_PageDisplay_TwoUp](#View-PageDisplay-TwoUp) | 将页面显示为 Two-Up 的命名操作。 |
| [View_PageDisplay_TwoUpContinuous](#View-PageDisplay-TwoUpContinuous) | 将页面显示为连续两页的命名操作。 |
| [View_Toolbars_AdvanceEditing](#View-Toolbars-AdvanceEditing) | 显示/隐藏高级编辑工具栏的命名操作。 |
| [View_Toolbars_CommentMarkup](#View-Toolbars-CommentMarkup) | 显示/隐藏评论工具栏的命名操作。 |
| [View_Toolbars_Edit](#View-Toolbars-Edit) | 显示/隐藏编辑工具栏的命名操作。 |
| [View_Toolbars_File](#View-Toolbars-File) | 显示/隐藏文件工具栏的命名操作。 |
| [View_Toolbars_Find](#View-Toolbars-Find) | 显示/隐藏查找工具栏的命名操作。 |
| [View_Toolbars_Forms](#View-Toolbars-Forms) | 显示/隐藏表单工具栏的命名操作。 |
| [View_Toolbars_Measuring](#View-Toolbars-Measuring) | 显示/隐藏测量工具栏的命名操作。 |
| [View_Toolbars_ObjectData](#View-Toolbars-ObjectData) | 显示/隐藏对象数据工具栏的命名操作。 |
| [View_Toolbars_PageDisplay](#View-Toolbars-PageDisplay) | 显示/隐藏页面显示工具栏的命名操作。 |
| [View_Toolbars_PageNavigation](#View-Toolbars-PageNavigation) | 显示/隐藏导航工具栏的命名操作。 |
| [View_Toolbars_PrintProduction](#View-Toolbars-PrintProduction) | 显示/隐藏打印制作工具栏的命名操作。 |
| [View_Toolbars_PropertiesBar](#View-Toolbars-PropertiesBar) | 显示/隐藏属性工具栏的命名操作。 |
| [View_Toolbars_Redaction](#View-Toolbars-Redaction) | 显示/隐藏密文工具栏的命名操作。 |
| [View_Toolbars_SelectZoom](#View-Toolbars-SelectZoom) | 显示/隐藏选择和缩放工具栏的命名操作。 |
| [View_Toolbars_Tasks](#View-Toolbars-Tasks) | 显示/隐藏任务工具栏的命名操作。 |
| [View_Toolbars_Typewriter](#View-Toolbars-Typewriter) | 显示/隐藏打字机工具栏的命名操作。 |
| [View_Zoom_ActualSize](#View-Zoom-ActualSize) | 以实际大小查看页面的命名操作。 |
| [View_Zoom_FitHeight](#View-Zoom-FitHeight) | 使页面适合高度的命名操作。 |
| [View_Zoom_FitPage](#View-Zoom-FitPage) | 适合页面的命名操作。 |
| [View_Zoom_FitVisible](#View-Zoom-FitVisible) | 适合页面可见性的命名操作。 |
| [View_Zoom_FitWidth](#View-Zoom-FitWidth) | 使页面适合宽度的命名操作。 |
| [View_Zoom_ZoomTo](#View-Zoom-ZoomTo) | 进行缩放的命名操作。 |
| [Window_FullScreenMode](#Window-FullScreenMode) | 以全屏模式查看文档的命名操作。 |
## 方法

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


查找当前书签的命名操作。

### Bookmarks_HightlightCurrentBookmark {#Bookmarks-HightlightCurrentBookmark}
```
public static final int Bookmarks_HightlightCurrentBookmark
```


用于突出显示当前书签的命名操作。

### Document_AttachFile {#Document-AttachFile}
```
public static final int Document_AttachFile
```


添加文件附件的命名操作。

### Document_CropPages {#Document-CropPages}
```
public static final int Document_CropPages
```


裁剪文档页面的命名操作。

### Document_DeletePages {#Document-DeletePages}
```
public static final int Document_DeletePages
```


删除文档页面的命名操作。

### Document_ExtractPages {#Document-ExtractPages}
```
public static final int Document_ExtractPages
```


提取文档页面的命名操作。

### Document_InsertPages {#Document-InsertPages}
```
public static final int Document_InsertPages
```


从文档中插入页面的命名操作。

### Document_ReplacePages {#Document-ReplacePages}
```
public static final int Document_ReplacePages
```


替换文档页面的命名操作。

### Document_RotatePages {#Document-RotatePages}
```
public static final int Document_RotatePages
```


旋转文档页面的命名操作。

### Edit_CheckSpelling_InComFieldEdit {#Edit-CheckSpelling-InComFieldEdit}
```
public static final int Edit_CheckSpelling_InComFieldEdit
```


检查评论中拼写的命名操作。

### Edit_Find {#Edit-Find}
```
public static final int Edit_Find
```


要查找的命名操作。

### Edit_Preferences {#Edit-Preferences}
```
public static final int Edit_Preferences
```


用于编辑首选项的命名操作。

### Edit_Search {#Edit-Search}
```
public static final int Edit_Search
```


用于搜索的命名操作。

### EnumSeparatorCharArray {#EnumSeparatorCharArray}
```
public static final char[] EnumSeparatorCharArray
```


### File_AttachToEmail {#File-AttachToEmail}
```
public static final int File_AttachToEmail
```


将当前 pdf 文档附加到电子邮件中的命名操作。

### File_Close {#File-Close}
```
public static final int File_Close
```


关闭文档的命名操作。

### File_CreatePDF_FromScanner {#File-CreatePDF-FromScanner}
```
public static final int File_CreatePDF_FromScanner
```


从扫描仪创建 pdf 文档的命名操作。

### File_CreatePDF_FromWebPage {#File-CreatePDF-FromWebPage}
```
public static final int File_CreatePDF_FromWebPage
```


从网页创建 pdf 文档的命名操作。

### File_Exit {#File-Exit}
```
public static final int File_Exit
```


退出 pdf 阅读器的命名操作。

### File_Organizer_OpenOrganizer {#File-Organizer-OpenOrganizer}
```
public static final int File_Organizer_OpenOrganizer
```


打开管理器的命名操作。

### File_Print {#File-Print}
```
public static final int File_Print
```


打印文档的命名操作。

### File_Properties {#File-Properties}
```
public static final int File_Properties
```


打开文档属性的命名操作。

### File_SaveAs {#File-SaveAs}
```
public static final int File_SaveAs
```


用另一个名称保存文档的命名操作。

### FirstPage {#FirstPage}
```
public static final int FirstPage
```


转到第一页的命名操作。

### LastPage {#LastPage}
```
public static final int LastPage
```


转到最后一页的命名操作。

### Miscellaneous_ZoomIn {#Miscellaneous-ZoomIn}
```
public static final int Miscellaneous_ZoomIn
```


用于放大文档的命名操作。

### Miscellaneous_ZoomOut {#Miscellaneous-ZoomOut}
```
public static final int Miscellaneous_ZoomOut
```


缩小文档的命名操作。

### NextPage {#NextPage}
```
public static final int NextPage
```


转到下一页的命名操作。

### PageImages_PrintPages {#PageImages-PrintPages}
```
public static final int PageImages_PrintPages
```


打印文档页面的命名操作。

### PrevPage {#PrevPage}
```
public static final int PrevPage
```


转到上一页的命名操作。

### Print {#Print}
```
public static final int Print
```


打开打印对话框的命名操作。

### PrintDialog {#PrintDialog}
```
public static final int PrintDialog
```


打开打印对话框的命名操作 (JavaScript)。

### View_GoTo_NextView {#View-GoTo-NextView}
```
public static final int View_GoTo_NextView
```


转到下一个视图的命名操作。

### View_GoTo_Page {#View-GoTo-Page}
```
public static final int View_GoTo_Page
```


转到特定页面的命名操作。

### View_GoTo_PreDocument {#View-GoTo-PreDocument}
```
public static final int View_GoTo_PreDocument
```


转到上一个文档的命名操作。

### View_GoTo_PreView {#View-GoTo-PreView}
```
public static final int View_GoTo_PreView
```


转到上一个视图的命名操作。

### View_NavigationPanels_Articles {#View-NavigationPanels-Articles}
```
public static final int View_NavigationPanels_Articles
```


显示/隐藏文章面板的命名操作。

### View_NavigationPanels_Attachments {#View-NavigationPanels-Attachments}
```
public static final int View_NavigationPanels_Attachments
```


显示/隐藏附件面板的命名操作。

### View_NavigationPanels_Boomarks {#View-NavigationPanels-Boomarks}
```
public static final int View_NavigationPanels_Boomarks
```


显示/隐藏书签面板的命名操作。

### View_NavigationPanels_Comments {#View-NavigationPanels-Comments}
```
public static final int View_NavigationPanels_Comments
```


显示/隐藏评论面板的命名操作。

### View_NavigationPanels_Fields {#View-NavigationPanels-Fields}
```
public static final int View_NavigationPanels_Fields
```


显示/隐藏字段面板的命名操作。

### View_NavigationPanels_Layers {#View-NavigationPanels-Layers}
```
public static final int View_NavigationPanels_Layers
```


显示/隐藏图层面板的命名操作。

### View_NavigationPanels_ModelTree {#View-NavigationPanels-ModelTree}
```
public static final int View_NavigationPanels_ModelTree
```


显示/隐藏模型树面板的命名操作。

### View_NavigationPanels_Pages {#View-NavigationPanels-Pages}
```
public static final int View_NavigationPanels_Pages
```


显示/隐藏页面面板的命名操作。

### View_NavigationPanels_Signatures {#View-NavigationPanels-Signatures}
```
public static final int View_NavigationPanels_Signatures
```


显示/隐藏签名面板的命名操作。

### View_PageDisplay_SinglePage {#View-PageDisplay-SinglePage}
```
public static final int View_PageDisplay_SinglePage
```


显示单个页面的命名操作。

### View_PageDisplay_SinglePageContinuous {#View-PageDisplay-SinglePageContinuous}
```
public static final int View_PageDisplay_SinglePageContinuous
```


显示单个连续页面的命名操作。

### View_PageDisplay_TwoUp {#View-PageDisplay-TwoUp}
```
public static final int View_PageDisplay_TwoUp
```


将页面显示为 Two-Up 的命名操作。

### View_PageDisplay_TwoUpContinuous {#View-PageDisplay-TwoUpContinuous}
```
public static final int View_PageDisplay_TwoUpContinuous
```


将页面显示为连续两页的命名操作。

### View_Toolbars_AdvanceEditing {#View-Toolbars-AdvanceEditing}
```
public static final int View_Toolbars_AdvanceEditing
```


显示/隐藏高级编辑工具栏的命名操作。

### View_Toolbars_CommentMarkup {#View-Toolbars-CommentMarkup}
```
public static final int View_Toolbars_CommentMarkup
```


显示/隐藏评论工具栏的命名操作。

### View_Toolbars_Edit {#View-Toolbars-Edit}
```
public static final int View_Toolbars_Edit
```


显示/隐藏编辑工具栏的命名操作。

### View_Toolbars_File {#View-Toolbars-File}
```
public static final int View_Toolbars_File
```


显示/隐藏文件工具栏的命名操作。

### View_Toolbars_Find {#View-Toolbars-Find}
```
public static final int View_Toolbars_Find
```


显示/隐藏查找工具栏的命名操作。

### View_Toolbars_Forms {#View-Toolbars-Forms}
```
public static final int View_Toolbars_Forms
```


显示/隐藏表单工具栏的命名操作。

### View_Toolbars_Measuring {#View-Toolbars-Measuring}
```
public static final int View_Toolbars_Measuring
```


显示/隐藏测量工具栏的命名操作。

### View_Toolbars_ObjectData {#View-Toolbars-ObjectData}
```
public static final int View_Toolbars_ObjectData
```


显示/隐藏对象数据工具栏的命名操作。

### View_Toolbars_PageDisplay {#View-Toolbars-PageDisplay}
```
public static final int View_Toolbars_PageDisplay
```


显示/隐藏页面显示工具栏的命名操作。

### View_Toolbars_PageNavigation {#View-Toolbars-PageNavigation}
```
public static final int View_Toolbars_PageNavigation
```


显示/隐藏导航工具栏的命名操作。

### View_Toolbars_PrintProduction {#View-Toolbars-PrintProduction}
```
public static final int View_Toolbars_PrintProduction
```


显示/隐藏打印制作工具栏的命名操作。

### View_Toolbars_PropertiesBar {#View-Toolbars-PropertiesBar}
```
public static final int View_Toolbars_PropertiesBar
```


显示/隐藏属性工具栏的命名操作。

### View_Toolbars_Redaction {#View-Toolbars-Redaction}
```
public static final int View_Toolbars_Redaction
```


显示/隐藏密文工具栏的命名操作。

### View_Toolbars_SelectZoom {#View-Toolbars-SelectZoom}
```
public static final int View_Toolbars_SelectZoom
```


显示/隐藏选择和缩放工具栏的命名操作。

### View_Toolbars_Tasks {#View-Toolbars-Tasks}
```
public static final int View_Toolbars_Tasks
```


显示/隐藏任务工具栏的命名操作。

### View_Toolbars_Typewriter {#View-Toolbars-Typewriter}
```
public static final int View_Toolbars_Typewriter
```


显示/隐藏打字机工具栏的命名操作。

### View_Zoom_ActualSize {#View-Zoom-ActualSize}
```
public static final int View_Zoom_ActualSize
```


以实际大小查看页面的命名操作。

### View_Zoom_FitHeight {#View-Zoom-FitHeight}
```
public static final int View_Zoom_FitHeight
```


使页面适合高度的命名操作。

### View_Zoom_FitPage {#View-Zoom-FitPage}
```
public static final int View_Zoom_FitPage
```


适合页面的命名操作。

### View_Zoom_FitVisible {#View-Zoom-FitVisible}
```
public static final int View_Zoom_FitVisible
```


适合页面可见性的命名操作。

### View_Zoom_FitWidth {#View-Zoom-FitWidth}
```
public static final int View_Zoom_FitWidth
```


使页面适合宽度的命名操作。

### View_Zoom_ZoomTo {#View-Zoom-ZoomTo}
```
public static final int View_Zoom_ZoomTo
```


进行缩放的命名操作。

### Window_FullScreenMode {#Window-FullScreenMode}
```
public static final int Window_FullScreenMode
```


以全屏模式查看文档的命名操作。

### Clone() {#Clone--}
```
public System.Enum Clone()
```




**退货：**
com.aspose.ms.System.枚举
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(System.Enum arg0) {#CloneTo-com.aspose.ms.System.Enum-}
```
public void CloneTo(System.Enum arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Enum |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**退货：**
布尔值
### format(System.Type arg0, Object arg1, String arg2) {#format-com.aspose.ms.System.Type-java.lang.Object-java.lang.String-}
```
public static String format(System.Type arg0, Object arg1, String arg2)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.Object |  |
| arg2 | java.lang.String |  |

**退货：**
java.lang.字符串
### format(Class<?> arg0, long arg1, String arg2) {#format-java.lang.Class----long-java.lang.String-}
```
public static String format(Class<?> arg0, long arg1, String arg2)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | long |  |
| arg2 | java.lang.String |  |

**退货：**
java.lang.字符串
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getName(Class<?> arg0, long arg1) {#getName-java.lang.Class----long-}
```
public static String getName(Class<?> arg0, long arg1)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | long |  |

**退货：**
java.lang.字符串
### getNames(System.Type arg0) {#getNames-com.aspose.ms.System.Type-}
```
public static String[] getNames(System.Type arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |

**退货：**
java.lang.字符串[]
### getNames(Class<?> arg0) {#getNames-java.lang.Class----}
```
public static Collection<String> getNames(Class<?> arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |

**退货：**
[Collection](../../java.util/collection)
### getUnderlyingType(System.Type arg0) {#getUnderlyingType-com.aspose.ms.System.Type-}
```
public static System.Type getUnderlyingType(System.Type arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |

**退货：**
com.aspose.ms.System.类型
### getUnderlyingType(Class<?> arg0) {#getUnderlyingType-java.lang.Class----}
```
public static Class<? extends Number> getUnderlyingType(Class<?> arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |

**退货：**
java.lang.Class<?扩展 java.lang.Number>
### getValue(Class<?> arg0, String arg1) {#getValue-java.lang.Class----java.lang.String-}
```
public static long getValue(Class<?> arg0, String arg1)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | java.lang.String |  |

**退货：**
长
### getValues(System.Type arg0) {#getValues-com.aspose.ms.System.Type-}
```
public static System.Array getValues(System.Type arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |

**退货：**
com.aspose.ms.System.数组
### get_Caption() {#get-Caption--}
```
public String get_Caption()
```




**退货：**
java.lang.字符串
### get_Value() {#get-Value--}
```
public long get_Value()
```




**退货：**
长
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### isDefined(System.Type arg0, Object arg1) {#isDefined-com.aspose.ms.System.Type-java.lang.Object-}
```
public static boolean isDefined(System.Type arg0, Object arg1)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.Object |  |

**退货：**
布尔值
### isDefined(System.Type arg0, String arg1) {#isDefined-com.aspose.ms.System.Type-java.lang.String-}
```
public static boolean isDefined(System.Type arg0, String arg1)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.String |  |

**退货：**
布尔值
### isDefined(System.Type arg0, long arg1) {#isDefined-com.aspose.ms.System.Type-long-}
```
public static boolean isDefined(System.Type arg0, long arg1)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | long |  |

**退货：**
布尔值
### isDefined(Class<?> arg0, long arg1) {#isDefined-java.lang.Class----long-}
```
public static boolean isDefined(Class<?> arg0, long arg1)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | long |  |

**退货：**
布尔值
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




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.String |  |

**退货：**
长
### parse(System.Type arg0, String arg1, Boolean arg2) {#parse-com.aspose.ms.System.Type-java.lang.String-java.lang.Boolean-}
```
public static long parse(System.Type arg0, String arg1, Boolean arg2)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.String |  |
| arg2 | java.lang.Boolean |  |

**退货：**
长
### parse(Class<?> arg0, String arg1) {#parse-java.lang.Class----java.lang.String-}
```
public static long parse(Class<?> arg0, String arg1)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | java.lang.String |  |

**退货：**
长
### parse(Class<?> arg0, String arg1, Boolean arg2) {#parse-java.lang.Class----java.lang.String-java.lang.Boolean-}
```
public static long parse(Class<?> arg0, String arg1, Boolean arg2)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | java.lang.String |  |
| arg2 | java.lang.Boolean |  |

**退货：**
长
### register(System.Enum.AbstractEnum arg0) {#register-com.aspose.ms.System.Enum.AbstractEnum-}
```
public static void register(System.Enum.AbstractEnum arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Enum.AbstractEnum |  |

### toObject(System.Type arg0, Object arg1) {#toObject-com.aspose.ms.System.Type-java.lang.Object-}
```
public static Object toObject(System.Type arg0, Object arg1)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.Object |  |

**退货：**
java.lang.Object
### toString() {#toString--}
```
public String toString()
```




**退货：**
java.lang.字符串
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |
