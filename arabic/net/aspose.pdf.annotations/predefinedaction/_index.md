---
title: PredefinedAction
second_title: Aspose.PDF لمرجع .NET API
description: يحدد الإجراءات المختلفة التي يمكن تشغيلها من ملف PDF .
type: docs
weight: 950
url: /ar/net/aspose.pdf.annotations/predefinedaction/
---
## PredefinedAction enumeration

يحدد الإجراءات المختلفة التي يمكن تشغيلها من ملف PDF .

```csharp
public enum PredefinedAction
```

### قيم

| اسم | قيمة | وصف |
| --- | --- | --- |
| FirstPage | `0` | إجراء باسم للانتقال إلى الصفحة الأولى. |
| LastPage | `1` | إجراء محدد للذهاب إلى الصفحة الأخيرة . |
| NextPage | `2` | إجراء محدد للانتقال إلى الصفحة التالية. |
| PrevPage | `3` | إجراء محدد للانتقال إلى الصفحة السابقة. |
| PrintDialog | `4` | إجراء باسم لفتح مربع حوار طباعة (JavaScript) . |
| Print | `5` | إجراء باسم لفتح مربع حوار طباعة. |
| Bookmarks_ExpanCurrentBookmark | `6` | إجراء مسمى للعثور على الإشارة المرجعية الحالية. |
| Bookmarks_HightlightCurrentBookmark | `7` | إجراء محدد لتمييز الإشارة المرجعية الحالية. |
| Document_AttachFile | `8` | إجراء مسمى لإضافة ملف مرفق . |
| Document_CropPages | `9` | إجراء محدد لاقتصاص صفحات المستند. |
| Document_DeletePages | `10` | إجراء محدد لحذف صفحات المستند. |
| Document_ExtractPages | `11` | إجراء مسمى لاستخراج صفحات المستند. |
| Document_InsertPages | `12` | إجراء مسمى لإدراج صفحات من مستند. |
| Document_ReplacePages | `13` | إجراء مسمى لاستبدال صفحات المستند. |
| Document_RotatePages | `14` | إجراء مسمى لتدوير صفحات المستند. |
| Edit_CheckSpelling_InComFieldEdit | `15` | إجراء محدد للتدقيق الإملائي في التعليقات. |
| Edit_Find | `16` | إجراء مسمى يتم البحث عنه . |
| Edit_Preferences | `17` | إجراء باسم لتحرير التفضيلات . |
| Edit_Search | `18` | إجراء مسمى للبحث . |
| File_AttachToEmail | `19` | إجراء مسمى لإرفاق مستند pdf الحالي برسالة بريد إلكتروني. |
| File_Close | `20` | إجراء مسمى لإغلاق المستند. |
| File_CreatePDF_FromScanner | `21` | إجراء مسمى لإنشاء مستند pdf من الماسح . |
| File_CreatePDF_FromWebPage | `22` | إجراء مسمى لإنشاء مستند pdf من صفحة الويب. |
| File_Exit | `23` | إجراء مسمى للخروج من قارئ pdf . |
| File_Organizer_OpenOrganizer | `24` | إجراء باسم لفتح المنظم. |
| File_Print | `25` | إجراء مسمى لطباعة المستند. |
| File_Properties | `26` | إجراء محدد لفتح خصائص المستند. |
| File_SaveAs | `27` | إجراء باسم لحفظ المستند باسم آخر. |
| Miscellaneous_ZoomIn | `28` | إجراء مسمى لتكبير المستند. |
| Miscellaneous_ZoomOut | `29` | إجراء باسم لتصغير المستند. |
| PageImages_PrintPages | `30` | إجراء مسمى لطباعة صفحات المستند. |
| View_GoTo_NextView | `31` | إجراء محدد للانتقال إلى العرض التالي . |
| View_GoTo_Page | `32` | إجراء محدد للذهاب إلى صفحة معينة. |
| View_GoTo_PreDocument | `33` | إجراء محدد للانتقال إلى المستند السابق. |
| View_GoTo_PreView | `34` | إجراء محدد للانتقال إلى العرض السابق . |
| View_NavigationPanels_Articles | `35` | إجراء مسمى لإظهار / إخفاء لوحة المقالات. |
| View_NavigationPanels_Attachments | `36` | إجراء محدد لإظهار / إخفاء لوحة المرفقات. |
| View_NavigationPanels_Boomarks | `37` | إجراء مسمى لإظهار / إخفاء لوحة الإشارات المرجعية. |
| View_NavigationPanels_Comments | `38` | إجراء مسمى لإظهار / إخفاء لوحة التعليقات. |
| View_NavigationPanels_Fields | `39` | إجراء مسمى لإظهار / إخفاء لوحة الحقول. |
| View_NavigationPanels_Layers | `40` | إجراء مسمى لإظهار / إخفاء لوحة الطبقات. |
| View_NavigationPanels_ModelTree | `41` | إجراء مسمى لإظهار / إخفاء لوحة شجرة النموذج. |
| View_NavigationPanels_Pages | `42` | إجراء مسمى لإظهار / إخفاء لوحة الصفحات. |
| View_NavigationPanels_Signatures | `43` | إجراء مسمى لإظهار / إخفاء لوحة التوقيعات. |
| View_PageDisplay_SinglePage | `44` | إجراء مسمى لعرض صفحة واحدة . |
| View_PageDisplay_SinglePageContinuous | `45` | إجراء مسمى لعرض صفحة واحدة مستمرة. |
| View_PageDisplay_TwoUp | `46` | إجراء مسمى لعرض الصفحات كصفحات ثنائية . |
| View_PageDisplay_TwoUpContinuous | `47` | إجراء مسمى لعرض الصفحات بصفتين متواصلتين. |
| View_Toolbars_AdvanceEditing | `48` | إجراء مسمى لإظهار / إخفاء شريط أدوات التحرير المتقدم. |
| View_Toolbars_CommentMarkup | `49` | إجراء مسمى لإظهار / إخفاء شريط أدوات التعليق. |
| View_Toolbars_Edit | `50` | إجراء مسمى لإظهار / إخفاء شريط أدوات التحرير. |
| View_Toolbars_File | `51` | إجراء مسمى لإظهار / إخفاء شريط أدوات الملف. |
| View_Toolbars_Find | `52` | إجراء مسمى لإظهار / إخفاء شريط أدوات البحث . |
| View_Toolbars_Forms | `53` | إجراء مسمى لإظهار / إخفاء شريط أدوات النماذج. |
| View_Toolbars_Measuring | `54` | إجراء محدد لإظهار / إخفاء شريط أدوات القياس. |
| View_Toolbars_ObjectData | `55` | إجراء مسمى لإظهار / إخفاء شريط أدوات بيانات الكائن. |
| View_Toolbars_PageDisplay | `56` | إجراء مسمى لإظهار / إخفاء شريط أدوات عرض الصفحة. |
| View_Toolbars_PageNavigation | `57` | إجراء مسمى لإظهار / إخفاء شريط أدوات التنقل. |
| View_Toolbars_PrintProduction | `58` | إجراء مسمى لإظهار / إخفاء شريط أدوات إنتاج الطباعة. |
| View_Toolbars_PropertiesBar | `59` | إجراء مسمى لإظهار / إخفاء شريط أدوات الخاصية . |
| View_Toolbars_Redaction | `60` | إجراء مسمى لإظهار / إخفاء شريط أدوات التنقيح. |
| View_Toolbars_SelectZoom | `61` | إجراء محدد لإظهار / إخفاء شريط أدوات التحديد والتكبير / التصغير. |
| View_Toolbars_Tasks | `62` | إجراء مسمى لإظهار / إخفاء شريط أدوات المهام. |
| View_Toolbars_Typewriter | `63` | إجراء مسمى لإظهار / إخفاء شريط أدوات الآلة الكاتبة. |
| View_Zoom_ActualSize | `64` | إجراء مسمى لعرض الصفحات بالحجم الفعلي. |
| View_Zoom_FitHeight | `65` | إجراء مسمى لملاءمة الصفحة في الارتفاع. |
| View_Zoom_FitPage | `66` | إجراء مسمى يلائم الصفحة. |
| View_Zoom_FitVisible | `67` | إجراء مسمى لملاءمة رؤية الصفحة. |
| View_Zoom_FitWidth | `68` | إجراء مسمى لملاءمة الصفحة على العرض . |
| View_Zoom_ZoomTo | `69` | إجراء مسمى للتكبير . |
| Window_FullScreenMode | `70` | إجراء مسمى لعرض المستند في وضع ملء الشاشة. |

### أنظر أيضا

* مساحة الاسم [Aspose.Pdf.Annotations](../../aspose.pdf.annotations)
* المجسم [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
