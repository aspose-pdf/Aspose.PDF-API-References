---
title: Class PdfASymbolicFontEncodingStrategy
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PdfASymbolicFontEncodingStrategy class. تُوضح هذه الفئة القواعد التي يمكن استخدامها لضبط عملية نسخ بيانات الترميز للحالات التي يحتوي فيها خط TrueType الرمزي على أكثر من ترميز واحد. قد تُظهر بعض مستندات PDF بعد التحويل إلى تنسيق PDF/A خطأ "More than one encoding in symbolic TrueType font's cmap". ما سبب هذا الخطأ؟ جميع خطوط
type: docs
weight: 8330
url: /ar/net/aspose.pdf/pdfasymbolicfontencodingstrategy/
---
## فئة PdfASymbolicFontEncodingStrategy

تصف هذه الفئة القواعد التي يمكن استخدامها لضبط عملية نسخ بيانات الترميز للحالات التي يحتوي فيها خط TrueType الرمزي على أكثر من ترميز واحد. قد تُظهر بعض مستندات PDF بعد التحويل إلى تنسيق PDF/A خطأ "More than one encoding in symbolic TrueType font's cmap". ما سبب هذا الخطأ؟ جميع خطوط TrueType الرمزية تحتوي على جدول خاص "cmap" في بياناتها الداخلية. يقوم هذا الجدول بربط رموز الأحرف بمؤشرات الرموز. ويمكن أن يحتوي هذا الجدول على جداول فرعية لترميز مختلفة تصف الترميزات المستخدمة. انظر المعلومات المتقدمة حول جداول cmap على https://developer.apple.com/fonts/TrueType-Reference-Manual/RM06/Chap6cmap.html. عادةً ما يحتوي جدول cmap على عدة جداول فرعية للترميز، لكن معيار PDF/A يتطلب أن يُترك جدول فرعي واحد فقط لهذا الخط في مستند PDF/A أو يجب أن يوجد جدول فرعي للترميز (3,0) من بين جداول هذا الخط الفرعية. والسؤال الرئيسي هنا - ما البيانات التي يجب أخذها من الجداول الفرعية الأخرى لنسخها إلى جدول الترميز الوجهة (3,0)؟ تحتوي أغلب الخطوط على جداول cmap "منظمة" حيث يكون كل جدول فرعي للترميز متسقًا تمامًا مع الجداول الفرعية الأخرى. ولكن بعض الخطوط تحتوي على جداول cmap بها تعارضات – حيث على سبيل المثال يكون لجدول فرعي مؤشر رمز 100 للرمز 100، بينما يكون لجدول فرعي آخر مؤشر رمز 200 لنفس الرمز 100. لحل هذه المشاكل، هناك حاجة إلى استراتيجية خاصة. بشكل افتراضي، تُستخدم الاستراتيجية التالية: يتم البحث عن الجدول الفرعي mac (1,0). إذا تم العثور على هذا الجدول، تُستخدم بياناته فقط لملء جدول الوجهة (3,0). إذا لم يتم العثور على الجدول الفرعي mac، يتم تكرار جميع الجداول الفرعية باستثناء (3,0) وتُستخدم لنسخ البيانات إلى الجدول الفرعي الوجهة (3,0). كما يتم نسخ الربط لكل رمز يونكود (رمز اليونيكود، مؤشر الرمز) إلى جدول الوجهة فقط إذا لم يكن هذا الرمز موجودًا فيه في تلك اللحظة. على سبيل المثال، إذا كان الجدول الفرعي الأول يحتوي على مؤشر رمز 100 للرمز 100، وكان الجدول الفرعي التالي يحتوي على مؤشر رمز 200 لنفس الرمز 100، فسيتم نسخ بيانات الجدول الفرعي الأول فقط (unicode=100, glyph index = 100). لذا يُعطى كل جدول فرعي سابق الأولوية على الجدول الذي يليه. تُساعد خصائص هذه الفئة `PdfASymbolicFontEncodingStrategy` في ضبط السلوك الافتراضي. إذا تم تعيين الخاصية [`PreferredCmapEncodingTable`](./preferredcmapencodingtable/) من النوع [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/)، فسيُستخدم الجدول الفرعي المناسب على حساب الجدول الفرعي mac (1,0). القيمة 'MacTable' من تعداد [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) ليس لها معنى في هذه الحالة، لأنها تشير إلى نفس الجدول الفرعي mac (1,0) الذي سيتم استخدامه افتراضيًا. الخاصية [`CmapEncodingTablesPriorityQueue`](./cmapencodingtablespriorityqueue/) تُلغي جميع الأولويات لأي جدول فرعي. إذا تم تعيين هذه الخاصية، فسيتم استخدام الجداول الفرعية من قائمة الانتظار المعلنة بالترتيب المحدد فقط. إذا لم يتم العثور على الجداول الفرعية المحددة، فسيتم استخدام التكرار الافتراضي لجميع الجداول الفرعية واستراتيجية النسخ الموضحة أعلاه. يحدد الكائن [`QueueItem`](../pdfasymbolicfontencodingstrategy.queueitem/) الجدول الفرعي للترميز المستخدم. يمكن تعيين هذا الجدول الفرعي عبر تركيب أعضاء (PlatformID, PlatformSpecificId) أو عبر تعداد [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/). في حالة عدم وجود جدول فرعي (3,0) للخط، سيتم استخدام جدول فرعي آخر للحفاظ على توافقية PDF/A. يتم اختيار الجدول الفرعي للاستخدام وفقًا للقواعد نفسها المذكورة سابقًا، بحيث تُستخدم الخاصيتان [`PreferredCmapEncodingTable`](./preferredcmapencodingtable/) و [`CmapEncodingTablesPriorityQueue`](./cmapencodingtablespriorityqueue/) لتحديد الجدول الفرعي الناتج، وإذا لم يكن الخط يحتوي على الجداول الفرعية المطلوبة أيضًا، فسيتم استخدام أي جدول فرعي موجود.

```csharp
public class PdfASymbolicFontEncodingStrategy
```

## الدوال البانية

| Name | Description |
| --- | --- |
| [PdfASymbolicFontEncodingStrategy](pdfasymbolicfontencodingstrategy/#constructor)() | دالة بانية. تضبط الجدول الفرعي الافتراضي (mac 1,0) |
| [PdfASymbolicFontEncodingStrategy](pdfasymbolicfontencodingstrategy/#constructor_1)(CMapEncodingTableType) | دالة بانية. |
| [PdfASymbolicFontEncodingStrategy](pdfasymbolicfontencodingstrategy/#constructor_2)(Queue&lt;QueueItem&gt;) | دالة بانية. |

## الخصائص

| Name | Description |
| --- | --- |
| [CmapEncodingTablesPriorityQueue](../../aspose.pdf/pdfasymbolicfontencodingstrategy/cmapencodingtablespriorityqueue/) { get; set; } | تحدد قائمة انتظار الجداول الفرعية للترميز التي سيتم معالجتها. |
| [PreferredCmapEncodingTable](../../aspose.pdf/pdfasymbolicfontencodingstrategy/preferredcmapencodingtable/) { get; set; } | تحدد الجدول الفرعي الذي سيتم استخدامه على حساب الجدول الفرعي mac (1,0). القيمة 'MacTable' من تعداد [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) ليس لها معنى في هذه الحالة. |

### راجع أيضا

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)