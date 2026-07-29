---
title: "PredefinedAction"
linktitle: "PredefinedAction"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يحدد الإجراءات المختلفة التي يمكن تشغيلها من ملف PDF."
type: docs
weight: 3960
url: /ar/java/com.aspose.pdf/predefinedaction/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < PredefinedAction > com.aspose.pdf.PredefinedAction, java.lang.Enum < PredefinedAction >, com.aspose.pdf.PredefinedAction

**All Implemented Interfaces:**
Serializable, Comparable < PredefinedAction >

```
public enum PredefinedAction extends Enum < PredefinedAction >
```

يحدد الإجراءات المختلفة التي يمكن تشغيلها من ملف PDF.

## الحقول

| حقل | الوصف |
| --- | --- |
| [Bookmarks_ExpanCurrentBookmark](#Bookmarks_ExpanCurrentBookmark) | إجراء مسمى للعثور على الإشارة المرجعية الحالية. |
| [Bookmarks_HightlightCurrentBookmark](#Bookmarks_HightlightCurrentBookmark) | إجراء مسمى لتسليط الضوء على الإشارة المرجعية الحالية. |
| [Document_AttachFile](#Document_AttachFile) | إجراء مسمى لإضافة مرفق ملف. |
| [Document_CropPages](#Document_CropPages) | إجراء مسمى لقص صفحات المستند. |
| [Document_DeletePages](#Document_DeletePages) | إجراء مسمى لحذف صفحات المستند. |
| [Document_ExtractPages](#Document_ExtractPages) | إجراء مسمى لاستخراج صفحات المستند. |
| [Document_InsertPages](#Document_InsertPages) | إجراء مسمى لإدراج صفحات من مستند. |
| [Document_ReplacePages](#Document_ReplacePages) | إجراء مسمى لاستبدال صفحات المستند. |
| [Document_RotatePages](#Document_RotatePages) | إجراء مسمى لتدوير صفحات المستند. |
| [Edit_CheckSpelling_InComFieldEdit](#Edit_CheckSpelling_InComFieldEdit) | إجراء مسمى للتحقق من الإملاء في التعليقات. |
| [Edit_Find](#Edit_Find) | إجراء مسمى للبحث. |
| [Edit_Preferences](#Edit_Preferences) | إجراء مسمى لتحرير التفضيلات. |
| [Edit_Search](#Edit_Search) | إجراء مسمى للبحث. |
| [File_AttachToEmail](#File_AttachToEmail) | إجراء مسمى لإرفاق مستند PDF الحالي في رسالة البريد الإلكتروني. |
| [File_Close](#File_Close) | إجراء مسمى لإغلاق المستند. |
| [File_CreatePDF_FromScanner](#File_CreatePDF_FromScanner) | إجراء مسمى لإنشاء مستند PDF من الماسح الضوئي. |
| [File_CreatePDF_FromWebPage](#File_CreatePDF_FromWebPage) | إجراء مسمى لإنشاء مستند PDF من صفحة ويب. |
| [File_Exit](#File_Exit) | إجراء مسمى للخروج من قارئ PDF. |
| [File_Organizer_OpenOrganizer](#File_Organizer_OpenOrganizer) | إجراء مسمى لفتح المنظم. |
| [File_Print](#File_Print) | إجراء مسمى لطباعة المستند. |
| [File_Properties](#File_Properties) | إجراء مسمى لفتح خصائص المستند. |
| [File_SaveAs](#File_SaveAs) | إجراء مسمى لحفظ المستند باسم آخر. |
| [FirstPage](#FirstPage) | إجراء مسمى للانتقال إلى الصفحة الأولى. |
| [LastPage](#LastPage) | إجراء مسمى للانتقال إلى الصفحة الأخيرة. |
| [Miscellaneous_ZoomIn](#Miscellaneous_ZoomIn) | إجراء مسمى لتكبير المستند. |
| [Miscellaneous_ZoomOut](#Miscellaneous_ZoomOut) | إجراء مسمى لتصغير المستند. |
| [NextPage](#NextPage) | إجراء مسمى للانتقال إلى الصفحة التالية. |
| [PageImages_PrintPages](#PageImages_PrintPages) | إجراء مسمى لطباعة صفحات المستند. |
| [PrevPage](#PrevPage) | إجراء مسمى للانتقال إلى الصفحة السابقة. |
| [Print](#Print) | إجراء مسمى لفتح مربع حوار الطباعة. |
| [PrintDialog](#PrintDialog) | إجراء مسمى لفتح مربع حوار الطباعة (JavaScript). |
| [View_GoTo_NextView](#View_GoTo_NextView) | إجراء مسمى للانتقال إلى العرض التالي. |
| [View_GoTo_Page](#View_GoTo_Page) | إجراء مسمى للانتقال إلى الصفحة المحددة. |
| [View_GoTo_PreDocument](#View_GoTo_PreDocument) | إجراء مسمى للانتقال إلى المستند السابق. |
| [View_GoTo_PreView](#View_GoTo_PreView) | إجراء مسمى للانتقال إلى العرض السابق. |
| [View_NavigationPanels_Articles](#View_NavigationPanels_Articles) | إجراء مسمى لإظهار/إخفاء لوحة المقالات. |
| [View_NavigationPanels_Attachments](#View_NavigationPanels_Attachments) | إجراء مسمى لإظهار/إخفاء لوحة المرفقات. |
| [View_NavigationPanels_Boomarks](#View_NavigationPanels_Boomarks) | إجراء مسمى لإظهار/إخفاء لوحة الإشارات المرجعية. |
| [View_NavigationPanels_Comments](#View_NavigationPanels_Comments) | إجراء مسمى لإظهار/إخفاء لوحة التعليقات. |
| [View_NavigationPanels_Fields](#View_NavigationPanels_Fields) | إجراء مسمى لإظهار/إخفاء لوحة الحقول. |
| [View_NavigationPanels_Layers](#View_NavigationPanels_Layers) | إجراء مسمى لإظهار/إخفاء لوحة الطبقات. |
| [View_NavigationPanels_ModelTree](#View_NavigationPanels_ModelTree) | إجراء مسمى لإظهار/إخفاء لوحة شجرة النموذج. |
| [View_NavigationPanels_Pages](#View_NavigationPanels_Pages) | إجراء مسمى لإظهار/إخفاء لوحة الصفحات. |
| [View_NavigationPanels_Signatures](#View_NavigationPanels_Signatures) | إجراء مسمى لإظهار/إخفاء لوحة التوقيعات. |
| [View_PageDisplay_SinglePage](#View_PageDisplay_SinglePage) | إجراء مسمى لعرض صفحة واحدة. |
| [View_PageDisplay_SinglePageContinuous](#View_PageDisplay_SinglePageContinuous) | إجراء مسمى لعرض صفحة مستمرة واحدة. |
| [View_PageDisplay_TwoUp](#View_PageDisplay_TwoUp) | إجراء مسمى لعرض الصفحات بنمط صفحتين معًا. |
| [View_PageDisplay_TwoUpContinuous](#View_PageDisplay_TwoUpContinuous) | إجراء مسمى لعرض الصفحات بنمط صفحتين معًا مستمر. |
| [View_Toolbars_AdvanceEditing](#View_Toolbars_AdvanceEditing) | إجراء مسمى لإظهار/إخفاء شريط أدوات التحرير المتقدم. |
| [View_Toolbars_CommentMarkup](#View_Toolbars_CommentMarkup) | إجراء مسمى لإظهار/إخفاء شريط أدوات التعليق. |
| [View_Toolbars_Edit](#View_Toolbars_Edit) | إجراء مسمى لإظهار/إخفاء شريط أدوات التحرير. |
| [View_Toolbars_File](#View_Toolbars_File) | إجراء مسمى لإظهار/إخفاء شريط أدوات الملف. |
| [View_Toolbars_Find](#View_Toolbars_Find) | إجراء مسمى لإظهار/إخفاء شريط أدوات البحث. |
| [View_Toolbars_Forms](#View_Toolbars_Forms) | إجراء مسمى لإظهار/إخفاء شريط أدوات النماذج. |
| [View_Toolbars_Measuring](#View_Toolbars_Measuring) | إجراء مسمى لإظهار/إخفاء شريط أدوات القياس. |
| [View_Toolbars_ObjectData](#View_Toolbars_ObjectData) | إجراء مسمى لإظهار/إخفاء شريط أدوات بيانات الكائن. |
| [View_Toolbars_PageDisplay](#View_Toolbars_PageDisplay) | إجراء مسمى لإظهار/إخفاء شريط أدوات عرض الصفحة. |
| [View_Toolbars_PageNavigation](#View_Toolbars_PageNavigation) | إجراء مسمى لإظهار/إخفاء شريط أدوات التنقل. |
| [View_Toolbars_PrintProduction](#View_Toolbars_PrintProduction) | إجراء مسمى لإظهار/إخفاء شريط أدوات إنتاج الطباعة. |
| [View_Toolbars_PropertiesBar](#View_Toolbars_PropertiesBar) | إجراء مسمى لإظهار/إخفاء شريط أدوات الخصائص. |
| [View_Toolbars_Redaction](#View_Toolbars_Redaction) | إجراء مسمى لإظهار/إخفاء شريط أدوات الحذف. |
| [View_Toolbars_SelectZoom](#View_Toolbars_SelectZoom) | إجراء مسمى لإظهار/إخفاء شريط أدوات التحديد والتكبير. |
| [View_Toolbars_Tasks](#View_Toolbars_Tasks) | إجراء مسمى لإظهار/إخفاء شريط أدوات المهام. |
| [View_Toolbars_Typewriter](#View_Toolbars_Typewriter) | إجراء مسمى لإظهار/إخفاء شريط أدوات الآلة الكاتبة. |
| [View_Zoom_ActualSize](#View_Zoom_ActualSize) | إجراء مسمى لعرض الصفحات بالحجم الفعلي. |
| [View_Zoom_FitHeight](#View_Zoom_FitHeight) | إجراء مسمى لتناسب الصفحة على الارتفاع. |
| [View_Zoom_FitPage](#View_Zoom_FitPage) | إجراء مسمى لتناسب الصفحة. |
| [View_Zoom_FitVisible](#View_Zoom_FitVisible) | إجراء مسمى لتناسب رؤية الصفحة. |
| [View_Zoom_FitWidth](#View_Zoom_FitWidth) | إجراء مسمى لتلائم الصفحة على العرض. |
| [View_Zoom_ZoomTo](#View_Zoom_ZoomTo) | إجراء مسمى لتكبير. |
| [Window_FullScreenMode](#Window_FullScreenMode) | إجراء مسمى لعرض المستند في وضع ملء الشاشة. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | يعيد ثابت التعداد لهذا النوع بالاسم المحدد. |
| [values](#values--) | يعيد مصفوفة تحتوي على ثوابت هذا النوع من التعداد، بالترتيب الذي تم إعلانه. |

### Bookmarks_ExpanCurrentBookmark {#Bookmarks_ExpanCurrentBookmark}
```
public static final PredefinedAction Bookmarks_ExpanCurrentBookmark
```

إجراء مسمى للعثور على الإشارة المرجعية الحالية.

### Bookmarks_HightlightCurrentBookmark {#Bookmarks_HightlightCurrentBookmark}
```
public static final PredefinedAction Bookmarks_HightlightCurrentBookmark
```

إجراء مسمى لتسليط الضوء على الإشارة المرجعية الحالية.

### Document_AttachFile {#Document_AttachFile}
```
public static final PredefinedAction Document_AttachFile
```

إجراء مسمى لإضافة مرفق ملف.

### Document_CropPages {#Document_CropPages}
```
public static final PredefinedAction Document_CropPages
```

إجراء مسمى لقص صفحات المستند.

### Document_DeletePages {#Document_DeletePages}
```
public static final PredefinedAction Document_DeletePages
```

إجراء مسمى لحذف صفحات المستند.

### Document_ExtractPages {#Document_ExtractPages}
```
public static final PredefinedAction Document_ExtractPages
```

إجراء مسمى لاستخراج صفحات المستند.

### Document_InsertPages {#Document_InsertPages}
```
public static final PredefinedAction Document_InsertPages
```

إجراء مسمى لإدراج صفحات من مستند.

### Document_ReplacePages {#Document_ReplacePages}
```
public static final PredefinedAction Document_ReplacePages
```

إجراء مسمى لاستبدال صفحات المستند.

### Document_RotatePages {#Document_RotatePages}
```
public static final PredefinedAction Document_RotatePages
```

إجراء مسمى لتدوير صفحات المستند.

### Edit_CheckSpelling_InComFieldEdit {#Edit_CheckSpelling_InComFieldEdit}
```
public static final PredefinedAction Edit_CheckSpelling_InComFieldEdit
```

إجراء مسمى للتحقق من الإملاء في التعليقات.

### Edit_Find {#Edit_Find}
```
public static final PredefinedAction Edit_Find
```

إجراء مسمى للبحث.

### Edit_Preferences {#Edit_Preferences}
```
public static final PredefinedAction Edit_Preferences
```

إجراء مسمى لتحرير التفضيلات.

### Edit_Search {#Edit_Search}
```
public static final PredefinedAction Edit_Search
```

إجراء مسمى للبحث.

### File_AttachToEmail {#File_AttachToEmail}
```
public static final PredefinedAction File_AttachToEmail
```

إجراء مسمى لإرفاق مستند PDF الحالي في رسالة البريد الإلكتروني.

### File_Close {#File_Close}
```
public static final PredefinedAction File_Close
```

إجراء مسمى لإغلاق المستند.

### File_CreatePDF_FromScanner {#File_CreatePDF_FromScanner}
```
public static final PredefinedAction File_CreatePDF_FromScanner
```

إجراء مسمى لإنشاء مستند PDF من الماسح الضوئي.

### File_CreatePDF_FromWebPage {#File_CreatePDF_FromWebPage}
```
public static final PredefinedAction File_CreatePDF_FromWebPage
```

إجراء مسمى لإنشاء مستند PDF من صفحة ويب.

### File_Exit {#File_Exit}
```
public static final PredefinedAction File_Exit
```

إجراء مسمى للخروج من قارئ PDF.

### File_Organizer_OpenOrganizer {#File_Organizer_OpenOrganizer}
```
public static final PredefinedAction File_Organizer_OpenOrganizer
```

إجراء مسمى لفتح المنظم.

### File_Print {#File_Print}
```
public static final PredefinedAction File_Print
```

إجراء مسمى لطباعة المستند.

### File_Properties {#File_Properties}
```
public static final PredefinedAction File_Properties
```

إجراء مسمى لفتح خصائص المستند.

### File_SaveAs {#File_SaveAs}
```
public static final PredefinedAction File_SaveAs
```

إجراء مسمى لحفظ المستند باسم آخر.

### FirstPage {#FirstPage}
```
public static final PredefinedAction FirstPage
```

إجراء مسمى للانتقال إلى الصفحة الأولى.

### LastPage {#LastPage}
```
public static final PredefinedAction LastPage
```

إجراء مسمى للانتقال إلى الصفحة الأخيرة.

### Miscellaneous_ZoomIn {#Miscellaneous_ZoomIn}
```
public static final PredefinedAction Miscellaneous_ZoomIn
```

إجراء مسمى لتكبير المستند.

### Miscellaneous_ZoomOut {#Miscellaneous_ZoomOut}
```
public static final PredefinedAction Miscellaneous_ZoomOut
```

إجراء مسمى لتصغير المستند.

### NextPage {#NextPage}
```
public static final PredefinedAction NextPage
```

إجراء مسمى للانتقال إلى الصفحة التالية.

### PageImages_PrintPages {#PageImages_PrintPages}
```
public static final PredefinedAction PageImages_PrintPages
```

إجراء مسمى لطباعة صفحات المستند.

### PrevPage {#PrevPage}
```
public static final PredefinedAction PrevPage
```

إجراء مسمى للانتقال إلى الصفحة السابقة.

### Print {#Print}
```
public static final PredefinedAction Print
```

إجراء مسمى لفتح مربع حوار الطباعة.

### PrintDialog {#PrintDialog}
```
public static final PredefinedAction PrintDialog
```

إجراء مسمى لفتح مربع حوار الطباعة (JavaScript).

### View_GoTo_NextView {#View_GoTo_NextView}
```
public static final PredefinedAction View_GoTo_NextView
```

إجراء مسمى للانتقال إلى العرض التالي.

### View_GoTo_Page {#View_GoTo_Page}
```
public static final PredefinedAction View_GoTo_Page
```

إجراء مسمى للانتقال إلى الصفحة المحددة.

### View_GoTo_PreDocument {#View_GoTo_PreDocument}
```
public static final PredefinedAction View_GoTo_PreDocument
```

إجراء مسمى للانتقال إلى المستند السابق.

### View_GoTo_PreView {#View_GoTo_PreView}
```
public static final PredefinedAction View_GoTo_PreView
```

إجراء مسمى للانتقال إلى العرض السابق.

### View_NavigationPanels_Articles {#View_NavigationPanels_Articles}
```
public static final PredefinedAction View_NavigationPanels_Articles
```

إجراء مسمى لإظهار/إخفاء لوحة المقالات.

### View_NavigationPanels_Attachments {#View_NavigationPanels_Attachments}
```
public static final PredefinedAction View_NavigationPanels_Attachments
```

إجراء مسمى لإظهار/إخفاء لوحة المرفقات.

### View_NavigationPanels_Boomarks {#View_NavigationPanels_Boomarks}
```
public static final PredefinedAction View_NavigationPanels_Boomarks
```

إجراء مسمى لإظهار/إخفاء لوحة الإشارات المرجعية.

### View_NavigationPanels_Comments {#View_NavigationPanels_Comments}
```
public static final PredefinedAction View_NavigationPanels_Comments
```

إجراء مسمى لإظهار/إخفاء لوحة التعليقات.

### View_NavigationPanels_Fields {#View_NavigationPanels_Fields}
```
public static final PredefinedAction View_NavigationPanels_Fields
```

إجراء مسمى لإظهار/إخفاء لوحة الحقول.

### View_NavigationPanels_Layers {#View_NavigationPanels_Layers}
```
public static final PredefinedAction View_NavigationPanels_Layers
```

إجراء مسمى لإظهار/إخفاء لوحة الطبقات.

### View_NavigationPanels_ModelTree {#View_NavigationPanels_ModelTree}
```
public static final PredefinedAction View_NavigationPanels_ModelTree
```

إجراء مسمى لإظهار/إخفاء لوحة شجرة النموذج.

### View_NavigationPanels_Pages {#View_NavigationPanels_Pages}
```
public static final PredefinedAction View_NavigationPanels_Pages
```

إجراء مسمى لإظهار/إخفاء لوحة الصفحات.

### View_NavigationPanels_Signatures {#View_NavigationPanels_Signatures}
```
public static final PredefinedAction View_NavigationPanels_Signatures
```

إجراء مسمى لإظهار/إخفاء لوحة التوقيعات.

### View_PageDisplay_SinglePage {#View_PageDisplay_SinglePage}
```
public static final PredefinedAction View_PageDisplay_SinglePage
```

إجراء مسمى لعرض صفحة واحدة.

### View_PageDisplay_SinglePageContinuous {#View_PageDisplay_SinglePageContinuous}
```
public static final PredefinedAction View_PageDisplay_SinglePageContinuous
```

إجراء مسمى لعرض صفحة مستمرة واحدة.

### View_PageDisplay_TwoUp {#View_PageDisplay_TwoUp}
```
public static final PredefinedAction View_PageDisplay_TwoUp
```

إجراء مسمى لعرض الصفحات بنمط صفحتين معًا.

### View_PageDisplay_TwoUpContinuous {#View_PageDisplay_TwoUpContinuous}
```
public static final PredefinedAction View_PageDisplay_TwoUpContinuous
```

إجراء مسمى لعرض الصفحات بنمط صفحتين معًا مستمر.

### View_Toolbars_AdvanceEditing {#View_Toolbars_AdvanceEditing}
```
public static final PredefinedAction View_Toolbars_AdvanceEditing
```

إجراء مسمى لإظهار/إخفاء شريط أدوات التحرير المتقدم.

### View_Toolbars_CommentMarkup {#View_Toolbars_CommentMarkup}
```
public static final PredefinedAction View_Toolbars_CommentMarkup
```

إجراء مسمى لإظهار/إخفاء شريط أدوات التعليق.

### View_Toolbars_Edit {#View_Toolbars_Edit}
```
public static final PredefinedAction View_Toolbars_Edit
```

إجراء مسمى لإظهار/إخفاء شريط أدوات التحرير.

### View_Toolbars_File {#View_Toolbars_File}
```
public static final PredefinedAction View_Toolbars_File
```

إجراء مسمى لإظهار/إخفاء شريط أدوات الملف.

### View_Toolbars_Find {#View_Toolbars_Find}
```
public static final PredefinedAction View_Toolbars_Find
```

إجراء مسمى لإظهار/إخفاء شريط أدوات البحث.

### View_Toolbars_Forms {#View_Toolbars_Forms}
```
public static final PredefinedAction View_Toolbars_Forms
```

إجراء مسمى لإظهار/إخفاء شريط أدوات النماذج.

### View_Toolbars_Measuring {#View_Toolbars_Measuring}
```
public static final PredefinedAction View_Toolbars_Measuring
```

إجراء مسمى لإظهار/إخفاء شريط أدوات القياس.

### View_Toolbars_ObjectData {#View_Toolbars_ObjectData}
```
public static final PredefinedAction View_Toolbars_ObjectData
```

إجراء مسمى لإظهار/إخفاء شريط أدوات بيانات الكائن.

### View_Toolbars_PageDisplay {#View_Toolbars_PageDisplay}
```
public static final PredefinedAction View_Toolbars_PageDisplay
```

إجراء مسمى لإظهار/إخفاء شريط أدوات عرض الصفحة.

### View_Toolbars_PageNavigation {#View_Toolbars_PageNavigation}
```
public static final PredefinedAction View_Toolbars_PageNavigation
```

إجراء مسمى لإظهار/إخفاء شريط أدوات التنقل.

### View_Toolbars_PrintProduction {#View_Toolbars_PrintProduction}
```
public static final PredefinedAction View_Toolbars_PrintProduction
```

إجراء مسمى لإظهار/إخفاء شريط أدوات إنتاج الطباعة.

### View_Toolbars_PropertiesBar {#View_Toolbars_PropertiesBar}
```
public static final PredefinedAction View_Toolbars_PropertiesBar
```

إجراء مسمى لإظهار/إخفاء شريط أدوات الخصائص.

### View_Toolbars_Redaction {#View_Toolbars_Redaction}
```
public static final PredefinedAction View_Toolbars_Redaction
```

إجراء مسمى لإظهار/إخفاء شريط أدوات الحذف.

### View_Toolbars_SelectZoom {#View_Toolbars_SelectZoom}
```
public static final PredefinedAction View_Toolbars_SelectZoom
```

إجراء مسمى لإظهار/إخفاء شريط أدوات التحديد والتكبير.

### View_Toolbars_Tasks {#View_Toolbars_Tasks}
```
public static final PredefinedAction View_Toolbars_Tasks
```

إجراء مسمى لإظهار/إخفاء شريط أدوات المهام.

### View_Toolbars_Typewriter {#View_Toolbars_Typewriter}
```
public static final PredefinedAction View_Toolbars_Typewriter
```

إجراء مسمى لإظهار/إخفاء شريط أدوات الآلة الكاتبة.

### View_Zoom_ActualSize {#View_Zoom_ActualSize}
```
public static final PredefinedAction View_Zoom_ActualSize
```

إجراء مسمى لعرض الصفحات بالحجم الفعلي.

### View_Zoom_FitHeight {#View_Zoom_FitHeight}
```
public static final PredefinedAction View_Zoom_FitHeight
```

إجراء مسمى لتناسب الصفحة على الارتفاع.

### View_Zoom_FitPage {#View_Zoom_FitPage}
```
public static final PredefinedAction View_Zoom_FitPage
```

إجراء مسمى لتناسب الصفحة.

### View_Zoom_FitVisible {#View_Zoom_FitVisible}
```
public static final PredefinedAction View_Zoom_FitVisible
```

إجراء مسمى لتناسب رؤية الصفحة.

### View_Zoom_FitWidth {#View_Zoom_FitWidth}
```
public static final PredefinedAction View_Zoom_FitWidth
```

إجراء مسمى لتلائم الصفحة على العرض.

### View_Zoom_ZoomTo {#View_Zoom_ZoomTo}
```
public static final PredefinedAction View_Zoom_ZoomTo
```

إجراء مسمى لتكبير.

### Window_FullScreenMode {#Window_FullScreenMode}
```
public static final PredefinedAction Window_FullScreenMode
```

إجراء مسمى لعرض المستند في وضع ملء الشاشة.

### getByValue {#getByValue-int-}
```
public static PredefinedAction getByValue(int value)
```



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  |  |

### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
يعيد ثابت التعداد لهذا النوع بالاسم المحدد.

### values {#values--}
```
public static PredefinedAction [] values()
```

يعيد مصفوفة تحتوي على ثوابت هذا النوع من التعداد، بالترتيب الذي تم إعلانه.

**Returns:**
مصفوفة تحتوي على ثوابت هذا النوع من التعداد، بالترتيب الذي تم إعلانه
