---
title: "التعداد PredefinedAction"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "التعداد Aspose.Pdf.Annotations.PredefinedAction. يحدد إجراءات مختلفة يمكن تفعيلها من ملف PDF."
type: docs
weight: 2430
url: /ar/net/aspose.pdf.annotations/predefinedaction/
---
## PredefinedAction enumeration

يحدد إجراءات مختلفة يمكن تشغيلها من ملف PDF.

```csharp
public enum PredefinedAction
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| FirstPage | `0` | إجراء مسمى للانتقال إلى الصفحة الأولى. |
| LastPage | `1` | إجراء مسمى للانتقال إلى الصفحة الأخيرة. |
| NextPage | `2` | إجراء مسمى للانتقال إلى الصفحة التالية. |
| PrevPage | `3` | إجراء مسمى للانتقال إلى الصفحة السابقة. |
| PrintDialog | `4` | إجراء مسمى لفتح مربع حوار الطباعة (JavaScript). |
| Print | `5` | إجراء مسمى لفتح مربع حوار الطباعة. |
| Bookmarks_ExpanCurrentBookmark | `6` | إجراء مسمى للعثور على الإشارة المرجعية الحالية. |
| Bookmarks_HightlightCurrentBookmark | `7` | إجراء مسمى لتسليط الضوء على الإشارة المرجعية الحالية. |
| Document_AttachFile | `8` | إجراء مسمى لإضافة مرفق ملف. |
| Document_CropPages | `9` | إجراء مسمى لقص صفحات المستند. |
| Document_DeletePages | `10` | إجراء مسمى لحذف صفحات المستند. |
| Document_ExtractPages | `11` | إجراء مسمى لاستخراج صفحات المستند. |
| Document_InsertPages | `12` | إجراء مسمى لإدراج صفحات من مستند. |
| Document_ReplacePages | `13` | إجراء مسمى لاستبدال صفحات المستند. |
| Document_RotatePages | `14` | إجراء مسمى لتدوير صفحات المستند. |
| Edit_CheckSpelling_InComFieldEdit | `15` | إجراء مسمى لتدقيق الإملاء في التعليقات. |
| Edit_Find | `16` | إجراء مسمى للبحث. |
| Edit_Preferences | `17` | إجراء مسمى لتعديل التفضيلات. |
| Edit_Search | `18` | إجراء مسمى للبحث. |
| File_AttachToEmail | `19` | إجراء مسمى لإرفاق مستند PDF الحالي في رسالة بريد إلكتروني. |
| File_Close | `20` | إجراء مسمى لإغلاق المستند. |
| File_CreatePDF_FromScanner | `21` | إجراء مسمى لإنشاء مستند PDF من الماسح الضوئي. |
| File_CreatePDF_FromWebPage | `22` | إجراء مسمى لإنشاء مستند PDF من صفحة ويب. |
| File_Exit | `23` | إجراء مسمى للخروج من قارئ PDF. |
| File_Organizer_OpenOrganizer | `24` | إجراء مسمى لفتح المنظم. |
| File_Print | `25` | إجراء مسمى لطباعة المستند. |
| File_Properties | `26` | إجراء مسمى لفتح خصائص المستند. |
| File_SaveAs | `27` | إجراء مسمى لحفظ المستند باسم آخر. |
| Miscellaneous_ZoomIn | `28` | إجراء مسمى لتكبير المستند. |
| Miscellaneous_ZoomOut | `29` | إجراء مسمى لتصغير المستند. |
| PageImages_PrintPages | `30` | إجراء مسمى لطباعة صفحات المستند. |
| View_GoTo_NextView | `31` | إجراء مسمى للانتقال إلى العرض التالي. |
| View_GoTo_Page | `32` | إجراء مسمى للانتقال إلى صفحة معينة. |
| View_GoTo_PreDocument | `33` | إجراء مسمى للانتقال إلى المستند السابق. |
| View_GoTo_PreView | `34` | إجراء مسمى للانتقال إلى العرض السابق. |
| View_NavigationPanels_Articles | `35` | إجراء مسمى لإظهار/إخفاء لوحة المقالات. |
| View_NavigationPanels_Attachments | `36` | إجراء مسمى لإظهار/إخفاء لوحة المرفقات. |
| View_NavigationPanels_Boomarks | `37` | إجراء مسمى لإظهار/إخفاء لوحة الإشارات. |
| View_NavigationPanels_Comments | `38` | إجراء مسمى لإظهار/إخفاء لوحة التعليقات. |
| View_NavigationPanels_Fields | `39` | إجراء مسمى لإظهار/إخفاء لوحة الحقول. |
| View_NavigationPanels_Layers | `40` | إجراء مسمى لإظهار/إخفاء لوحة الطبقات. |
| View_NavigationPanels_ModelTree | `41` | إجراء مسمى لإظهار/إخفاء لوحة شجرة النموذج. |
| View_NavigationPanels_Pages | `42` | إجراء مسمى لإظهار/إخفاء لوحة الصفحات. |
| View_NavigationPanels_Signatures | `43` | إجراء مسمى لإظهار/إخفاء لوحة التوقيعات. |
| View_PageDisplay_SinglePage | `44` | إجراء مسمى لعرض صفحة واحدة. |
| View_PageDisplay_SinglePageContinuous | `45` | إجراء مسمى لعرض صفحة واحدة مستمرة. |
| View_PageDisplay_TwoUp | `46` | إجراء مسمى لعرض الصفحات بنمط صفحتين. |
| View_PageDisplay_TwoUpContinuous | `47` | إجراء مسمى لعرض الصفحات بنمط صفحتين مستمر. |
| View_Toolbars_AdvanceEditing | `48` | إجراء مسمى لإظهار/إخفاء شريط أدوات التحرير المتقدم. |
| View_Toolbars_CommentMarkup | `49` | إجراء مسمى لإظهار/إخفاء شريط أدوات التعليق. |
| View_Toolbars_Edit | `50` | إجراء مسمى لإظهار/إخفاء شريط أدوات التحرير. |
| View_Toolbars_File | `51` | إجراء مسمى لإظهار/إخفاء شريط أدوات الملف. |
| View_Toolbars_Find | `52` | إجراء مسمى لإظهار/إخفاء شريط أدوات البحث. |
| View_Toolbars_Forms | `53` | إجراء مسمى لإظهار/إخفاء شريط أدوات النماذج. |
| View_Toolbars_Measuring | `54` | إجراء مسمى لإظهار/إخفاء شريط أدوات القياس. |
| View_Toolbars_ObjectData | `55` | إجراء مسمى لإظهار/إخفاء شريط أدوات بيانات الكائن. |
| View_Toolbars_PageDisplay | `56` | إجراء مسمى لإظهار/إخفاء شريط أدوات عرض الصفحة. |
| View_Toolbars_PageNavigation | `57` | إجراء مسمى لإظهار/إخفاء شريط أدوات التنقل. |
| View_Toolbars_PrintProduction | `58` | إجراء مسمى لإظهار/إخفاء شريط أدوات إنتاج الطباعة. |
| View_Toolbars_PropertiesBar | `59` | إجراء مسمى لإظهار/إخفاء شريط أدوات الخاصية. |
| View_Toolbars_Redaction | `60` | إجراء مسمى لإظهار/إخفاء شريط أدوات الحذف. |
| View_Toolbars_SelectZoom | `61` | إجراء مسمى لإظهار/إخفاء شريط أدوات التحديد &amp; التكبير. |
| View_Toolbars_Tasks | `62` | إجراء مسمى لإظهار/إخفاء شريط أدوات المهام. |
| View_Toolbars_Typewriter | `63` | إجراء مسمى لإظهار/إخفاء شريط أدوات الآلة الكاتبة. |
| View_Zoom_ActualSize | `64` | إجراء مسمى لعرض الصفحات بالحجم الفعلي. |
| View_Zoom_FitHeight | `65` | إجراء مسمى لتناسب الصفحة مع الارتفاع. |
| View_Zoom_FitPage | `66` | إجراء مسمى لتلائم الصفحة. |
| View_Zoom_FitVisible | `67` | إجراء مسمى لتلائم رؤية الصفحة. |
| View_Zoom_FitWidth | `68` | إجراء مسمى لتلائم الصفحة على العرض. |
| View_Zoom_ZoomTo | `69` | إجراء مسمى لإنشاء التكبير. |
| Window_FullScreenMode | `70` | إجراء مسمى لعرض المستند في وضع ملء الشاشة. |

### انظر أيضًا

* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


