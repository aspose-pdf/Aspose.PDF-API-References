---
title: "PdfASymbolicFontEncodingStrategy"
linktitle: "PdfASymbolicFontEncodingStrategy"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "هذه الفئة تصف القواعد التي يمكن استخدامها لضبط عملية نسخ بيانات الترميز في الحالات التي يكون فيها خط TrueType الرمزي لديه أكثر من ترميز واحد. بعض مستندات PDF بعد."
type: docs
weight: 3690
url: /ar/java/com.aspose.pdf/pdfasymbolicfontencodingstrategy/
---
**Inheritance:**
java.lang.Object، com.aspose.pdf.PdfASymbolicFontEncodingStrategy

```
public class PdfASymbolicFontEncodingStrategy extends Object
```

هذه الفئة تصف القواعد التي يمكن استخدامها لضبط عملية نسخ بيانات الترميز للحالات التي يكون فيها خط TrueType الرمزي يحتوي على أكثر من ترميز واحد. بعض مستندات PDF بعد التحويل إلى تنسيق PDF/A قد تُظهر خطأ \"More than one encoding in symbolic TrueType font's cmap\". ما هو سبب هذا الخطأ؟ جميع خطوط TrueType الرمزية لديها جدول خاص \"cmap\" في بياناتها الداخلية. هذا الجدول يطابق رموز الأحرف مع مؤشرات الحروف. ويمكن لهذا الجدول أن يحتوي على جداول فرعية للترميز مختلفة تصف الترميزات المستخدمة. راجع معلومات متقدمة حول جداول cmap على https://developer.apple.com/fonts/TrueType-Reference-Manual/RM06/Chap6cmap.html. عادةً ما يحتوي جدول cmap على عدة جداول فرعية للترميز، لكن معيار PDF/A يتطلب إما ترك جدول فرعي ترميز واحد فقط لهذا الخط في مستند PDF/A أو وجود جدول فرعي ترميز (3,0) بين جداول هذا الخط. والسؤال الرئيسي هنا - ما البيانات التي يجب أخذها من الجداول الفرعية الأخرى لنسخها إلى جدول الترميز الوجهة (3,0)؟ أغلب الخطوط لديها جداول cmap 'مصممة جيدًا' حيث كل جدول فرعي للترميز متسق بالكامل مع جدول فرعي آخر. لكن بعض الخطوط لديها جداول cmap مع تصادمات - حيث على سبيل المثال يحتوي جدول فرعي على مؤشر حرف 100 للـ Unicode 100، بينما يحتوي جدول فرعي آخر على مؤشر حرف 200 لنفس الـ Unicode 100. لحل هذه المشكلات تحتاج استراتيجية خاصة. بشكل افتراضي تُستخدم الاستراتيجية التالية: يتم البحث عن جدول فرعي mac(1,0). إذا تم العثور على هذا الجدول، تُستخدم بياناته فقط لملء جدول الوجهة (3,0). إذا لم يُعثر على جدول فرعي mac فسيتم تكرار جميع الجداول الفرعية باستثناء (3,0) واستخدامها لنسخ البيانات إلى جدول الوجهة (3,0). كما يتم نسخ التعيين لكل Unicode (Unicode، مؤشر الحرف) إلى جدول الوجهة فقط إذا لم يكن جدول الوجهة يحتوي على هذا الـ Unicode في الوقت الحالي. لذا، على سبيل المثال إذا كان للجدول الفرعي الأول مؤشر حرف 100 للـ Unicode 100، وكان للجدول الفرعي التالي مؤشر حرف 200 لنفس الـ Unicode 100، فسيتم نسخ البيانات فقط من الجدول الفرعي الأول (Unicode=100، مؤشر الحرف = 100). وبالتالي كل جدول فرعي سابق يأخذ الأسبقية على التالي. خصائص هذه الفئة { PdfASymbolicFontEncodingStrategy} تساعد على ضبط السلوك الافتراضي. إذا تم تعيين الخاصية {PreferredCmapEncodingTable}({ PdfASymbolicFontEncodingStrategy#getPreferredCmapEncodingTable}/ { PdfASymbolicFontEncodingStrategy#setPreferredCmapEncodingTable}) من النوع { PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType}، فسيتم استخدام الجدول الفرعي المناسب بأسبقية على جدول mac(1,0). القيمة 'MacTable' من تعداد {PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType} لا معنى لها في هذه الحالة، لأنها تشير إلى نفس جدول mac(1,0) الذي يُستخدم افتراضيًا. الخاصية {CmapEncodingTablesPriorityQueue}({ PdfASymbolicFontEncodingStrategy#getCmapEncodingTablesPriorityQueue}/ {PdfASymbolicFontEncodingStrategy#setCmapEncodingTablesPriorityQueue}) تتجاهل جميع الأولويات لأي جدول فرعي. إذا تم تعيين هذه الخاصية، فستُستخدم فقط الجداول الفرعية من القائمة المعلنة بالترتيب المحدد. إذا لم يتم العثور على الجداول الفرعية المحددة فسيتم استخدام التكرار الافتراضي لجميع الجداول الفرعية واستراتيجية النسخ الموضحة أعلاه. الكائن { PdfASymbolicFontEncodingStrategy.QueueItem} يحدد جدول الترميز الفرعي المستخدم. يمكن تعيين هذا الجدول عبر مجموعة من الأعضاء (PlatformID، PlatformSpecificId) أو عبر تعداد { PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType}. في حالة عدم وجود جدول فرعي (3,0) في الخط، سيُستخدم جدول فرعي آخر للحفاظ على توافق PDF/A. يتم اختيار الجدول الفرعي للاستخدام وفق القواعد نفسها المذكورة سابقًا، بحيث تُستخدم خصائص {@code PreferredCmapEncodingTable}({ PdfASymbolicFontEncodingStrategy#getPreferredCmapEncodingTable}/ {PdfASymbolicFontEncodingStrategy#setPreferredCmapEncodingTable}) و{@code CmapEncodingTablesPriorityQueue}({ PdfASymbolicFontEncodingStrategy#getCmapEncodingTablesPriorityQueue}/ { PdfASymbolicFontEncodingStrategy#setCmapEncodingTablesPriorityQueue}) لتحديد الجدول الفرعي الناتج، وإذا لم يكن للخط الجدول الفرعي المطلوب فسيُستخدم أي جدول فرعي موجود.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [PdfASymbolicFontEncodingStrategy](#PdfASymbolicFontEncodingStrategy--) | منشئ. يضبط جدولًا فرعيًا افتراضيًا (mac 1,0) |
| [PdfASymbolicFontEncodingStrategy](#PdfASymbolicFontEncodingStrategy-com.aspose.ms.System.Collections.Generic.Queue-) | منشئ. يضبط جدولًا فرعيًا افتراضيًا (mac 1,0) |
| [PdfASymbolicFontEncodingStrategy](#PdfASymbolicFontEncodingStrategy-short-) | منشئ |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getCmapEncodingTablesPriorityQueue](#getCmapEncodingTablesPriorityQueue--) | يحدد طابور جداول الترميز الفرعية للمعالجة. |
| [getPreferredCmapEncodingTable](#getPreferredCmapEncodingTable--) | يحدد جدولًا فرعيًا سيُستخدم في أولوية جدول mac الفرعي (1,0). القيمة 'MacTable' من التعداد {@code QueueItem.CMapEncodingTableType} لا معنى لها في هذه الحالة. |
| [setCmapEncodingTablesPriorityQueue](#setCmapEncodingTablesPriorityQueue-com.aspose.ms.System.Collections.Generic.Queue-) | يحدد طابور جداول الترميز الفرعية للمعالجة. |
| [setPreferredCmapEncodingTable](#setPreferredCmapEncodingTable-short-) | يحدد جدولًا فرعيًا سيُستخدم في أولوية جدول mac الفرعي (1,0). القيمة 'MacTable' من التعداد {@code QueueItem.CMapEncodingTableType} لا معنى لها في هذه الحالة. |

### PdfASymbolicFontEncodingStrategy {#PdfASymbolicFontEncodingStrategy--}
```
public PdfASymbolicFontEncodingStrategy()
```

منشئ. يضبط جدولًا فرعيًا افتراضيًا (mac 1,0)

### PdfASymbolicFontEncodingStrategy {#PdfASymbolicFontEncodingStrategy-com.aspose.ms.System.Collections.Generic.Queue-}
منشئ. يضبط جدولًا فرعيًا افتراضيًا (mac 1,0)

### PdfASymbolicFontEncodingStrategy {#PdfASymbolicFontEncodingStrategy-short-}
```
public PdfASymbolicFontEncodingStrategy(short preferredEncodingTable)
```

منشئ

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| preferredEncodingTable |  | جدول الترميز الفرعي الذي سيُستخدم في أولوية جدول mac الفرعي (1,0) @see PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType |

### getCmapEncodingTablesPriorityQueue {#getCmapEncodingTablesPriorityQueue--}
```
public com.aspose.ms.System.Collections.Generic.Queue< PdfASymbolicFontEncodingStrategy.QueueItem > getCmapEncodingTablesPriorityQueue()
```

يحدد طابور جداول الترميز الفرعية للمعالجة.

**Returns:**
قائمة انتظار من QueueItem

### getPreferredCmapEncodingTable {#getPreferredCmapEncodingTable--}
```
public short getPreferredCmapEncodingTable()
```

يحدد جدولًا فرعيًا سيُستخدم في أولوية جدول mac الفرعي (1,0). القيمة 'MacTable' من التعداد {@code QueueItem.CMapEncodingTableType} لا معنى لها في هذه الحالة.

**Returns:**
عنصر CMapEncodingTableType @see PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType

### setCmapEncodingTablesPriorityQueue {#setCmapEncodingTablesPriorityQueue-com.aspose.ms.System.Collections.Generic.Queue-}
يحدد طابور جداول الترميز الفرعية للمعالجة.

### setPreferredCmapEncodingTable {#setPreferredCmapEncodingTable-short-}
```
public void setPreferredCmapEncodingTable(short value)
```

يحدد جدولًا فرعيًا سيُستخدم في أولوية جدول mac الفرعي (1,0). القيمة 'MacTable' من التعداد {@code QueueItem.CMapEncodingTableType} لا معنى لها في هذه الحالة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | الجدول الفرعي للترميز preferredEncodingTable الذي سيُستخدم في أولوية جدول mac الفرعي(1,0) @see PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType |
