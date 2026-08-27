---
title: "Page"
linktitle: "Page"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "فئة تمثل صفحة من وثيقة PDF."
type: docs
weight: 3310
url: /ar/java/com.aspose.pdf/page/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Page

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, com.aspose.pdf.engine.IOperatorContainer, Closeable, AutoCloseable

```
public final class Page extends Object implements com.aspose.ms.System.IDisposable, Closeable , com.aspose.pdf.engine.IOperatorContainer
```

فئة تمثل صفحة من وثيقة PDF.

## الطرق

| طريقة | الوصف |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | يقبل كائن الزائر {@code AnnotationSelector} الذي يوفر وظيفة للعمل مع التعليقات التوضيحية. |
| [accept](#accept-com.aspose.pdf.ImagePlacementAbsorber-) | يقبل كائن الزائر {@code ImagePlacementAbsorber} الذي يوفر وظيفة للعمل مع كائنات وضع الصور. |
| [accept](#accept-com.aspose.pdf.TextAbsorber-) | يقبل كائن الزائر {@code TextAbsorber} الذي يوفر وظيفة للعمل مع كائنات النص. |
| [accept](#accept-com.aspose.pdf.TextFragmentAbsorber-) | يقبل كائن الزائر {@code TextFragmentAbsorber} الذي يوفر وظيفة للعمل مع كائنات النص. |
| [addGraphics](#addGraphics-com.aspose.pdf.vector.GraphicElementCollection-) | يضيف رسومات إلى الصفحة. يعمل أسرع من إضافة العناصر واحدةً تلو الأخرى باستخدام طريقة GraphicElement#addOnPage(Page). |
| [addGraphics](#addGraphics-com.aspose.pdf.vector.GraphicElementCollection-com.aspose.pdf.Rectangle-) | يضيف رسومات إلى الصفحة. يعمل أسرع من إضافة العناصر واحدةً تلو الأخرى باستخدام طريقة GraphicElement#addOnPage(Page). |
| [addImage](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-) | يضيف صورة إلى الصفحة ويضعها في وسط المستطيل المحدد مع الحفاظ على نسبة الصورة. |
| [addImage](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-int-int-boolean-) | يضيف صورة قابلة للبحث إلى الصفحة ويضعها في وسط المستطيل المحدد مع الحفاظ على نسبة الصورة. |
| [addImage](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-int-int-boolean-com.aspose.pdf.Rectangle-) | يضيف صورة قابلة للبحث إلى الصفحة ويضعها في وسط المستطيل المحدد مع الحفاظ على نسبة الصورة. |
| [addImage](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-) | يضيف صورة إلى الصفحة ويضعها في وسط المستطيل المحدد مع الحفاظ على نسبة الصورة. |
| [addImage](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-com.aspose.pdf.CompositingParameters-) | يضيف صورة إلى الصفحة ويضعها في وسط المستطيل المحدد مع الحفاظ على نسبة الصورة. |
| [addImage](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-com.aspose.pdf.CompositingParameters-boolean-) | يضيف صورة إلى الصفحة ويضعها في وسط المستطيل المحدد مع الحفاظ على نسبة الصورة. |
| [addImage](#addImage-java.lang.String-java.io.InputStream-com.aspose.pdf.Rectangle-) | يضيف صورة قابلة للبحث إلى الصفحة ويضعها في وسط المستطيل المحدد مع الحفاظ على نسبة الصورة. |
| [addImage](#addImage-java.lang.String-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-) | يضيف صورة قابلة للبحث إلى الصفحة ويضعها في وسط المستطيل المحدد مع الحفاظ على نسبة الصورة. |
| [addImage](#addImage-java.lang.String-com.aspose.pdf.Rectangle-) | يضيف صورة إلى الصفحة ويضعها في وسط المستطيل المحدد مع الحفاظ على نسبة الصورة. |
| [addStamp](#addStamp-com.aspose.pdf.Stamp-) | ضع ختمًا في الصفحة. يمكن أن يكون الختم رقم الصفحة أو صورة أو نصًا بسيطًا، مثلًا بعض الشعار. |
| [asByteArray](#asByteArray-com.aspose.pdf.devices.Resolution-) | يحوّل الصفحة الحالية إلى صورة BMP ثم يعيد مصفوفة من البايتات. |
| [asXml](#asXml--) | يحوّل الصفحة الحالية إلى XML بترميز UTF-8. |
| [calculateContentBBox](#calculateContentBBox--) | يحسب قيمة bbox - المستطيل الذي يحتوي المحتوى دون هوامش مرئية. |
| [clearContents](#clearContents--) | للاستخدام الداخلي فقط |
| [close](#close--) | يغلق جميع الموارد المستخدمة بواسطة هذا المستند. |
| [convertToPNGMemoryStream](#convertToPNGMemoryStream--) | تحويل الصفحة إلى PNG لتدفق صورة DSR، OMR، OCR. |
| [deleteGraphics](#deleteGraphics-com.aspose.pdf.vector.GraphicElementCollection-) | يحذف الرسومات من الصفحة. يعمل أسرع من حذف العناصر واحدةً تلو الأخرى باستخدام طريقة {@link GraphicElement#remove}. |
| [deleteUnusedResources](#deleteUnusedResources-com.aspose.ms.System.Collections.Generic.Dictionary-) |  |
| [dispose](#dispose--) | يفرغ الذاكرة. هذه الطريقة مهجورة، استخدم close() بدلاً من ذلك. |
| [fillUsedObjectsTable](#fillUsedObjectsTable-com.aspose.ms.System.Collections.Generic.Dictionary-com.aspose.pdf.engine.data.IPdfDictionary-) |  |
| [findReferences](#findReferences-com.aspose.pdf.OperatorCollection-java.lang.String-) | يعيد قائمة بالمشغّلات التي تستخدم المورد بالاسم المحدد. |
| [findReferences](#findReferences-java.lang.String-) | <p> ابحث عن المراجع </p> |
| [flatten](#flatten--) | يزيل جميع الحقول الثابتة الموجودة على الصفحة ويضع قيمها بدلاً من ذلك. |
| [freeMemory](#freeMemory--) | يمسح البيانات المخزنة مؤقتًا |
| [getActions](#getActions--) | يحصل على مجموعة خصائص الصفحة. |
| [getAnnotations](#getAnnotations--) | يحصل على مجموعة تعليقات الصفحة. {@code Annotations} |
| [getArtBox](#getArtBox--) | <p> يحصل على صندوق الفن للصفحة. </p> |
| [getArtifacts](#getArtifacts--) | يحصل على مجموعة القطع الأثرية على الصفحة. |
| [getBackground](#getBackground--) | يحصل على لون خلفية الصفحة. |
| [getBackgroundImage](#getBackgroundImage--) | يحصل على أو يضبط صورة الخلفية للصفحة (للمولد فقط، لا يتم ملؤها عند قراءة المستند). |
| [getBleedBox](#getBleedBox--) | <p> يحصل على صندوق النزيف للصفحة. </p> |
| [getColorType](#getColorType--) | يحصل على نوع اللون للصفحات بناءً على المعلومات المستلمة من المشغّلين SetColor، والصور والنماذج. |
| [getContents](#getContents--) | <p> يحصل على مجموعة المشغّلين في تدفق المحتوى للصفحة. {@code OperatorCollection} </p> |
| [getContentsAppender](#getContentsAppender--) | يحصل على ملحق المحتويات الحالي. {@code ContentsAppender} |
| [getCropBox](#getCropBox--) | <p> يحصل على صندوق القص للصفحة. </p> |
| [getDocument](#getDocument--) | احصل على المستند |
| [getDuration](#getDuration--) | <p> يحصل على مدة عرض الصفحة. هذه هي الوقت بالثواني التي يجب عرض الصفحة خلالها أثناء العرض. تُرجع -1 إذا لم تُحدَّد المدة. </p> <hr> مثال يوضح كيفية الحصول على مدة الصفحة <p> Document document = new Document("sample.pdf"); Page page = document.getPages().get(1); int pageRect = page.getDuration(); </p> |
| [getEnginePage](#getEnginePage--) | للاستخدام الداخلي فقط |
| [getFieldsInTabOrder](#getFieldsInTabOrder--) | يحصل على قائمة كائنات Field بترتيب Tab في هذه الصفحة. |
| [getFooter](#getFooter--) | يحصل على تذييل الصفحة. |
| [getGroup](#getGroup--) | يحصل على فئة سمات المجموعة التي تحدد سمات مجموعة الصفحة لاستخدامها في نموذج التصوير الشفاف. |
| [getHeader](#getHeader--) | يحصل على رأس الصفحة. |
| [getLayers](#getLayers--) | يحصل على مجموعة الطبقات. |
| [getMediaBox](#getMediaBox--) | <p> يحصل على صندوق الوسائط للصفحة. </p> |
| [getNoteLineStyle](#getNoteLineStyle--) | يحصل على نمط الخط للملاحظات. (للمولد فقط، لا يُملأ عند قراءة المستند) |
| [getNotifications](#getNotifications--) | يرجع الإشعارات حول العمليات الداخلية مع محتوى الصفحة. (يتم دعم إشعارات أحداث الفقرات في سيناريوهات إضافة النص فقط حالياً.) |
| [getNumber](#getNumber--) | احصل على رقم الصفحة. |
| [getOnBeforePageGenerate](#getOnBeforePageGenerate--) | حدث لتخصيص الرأس والتذييل. |
| [getPageInfo](#getPageInfo--) | يحصل على معلومات الصفحة. (للمولد فقط، لا يُملأ عند قراءة المستند). |
| [getPageRect](#getPageRect-boolean-) | يرجع مستطيل الصفحة وفقاً لـ CropBox الخاص به (أو MediaBox إذا كان CropBox فارغاً). |
| [getParagraphs](#getParagraphs--) | يحصل على الفقرات. |
| [getRect_Rename_Namesake](#getRect_Rename_Namesake--) | <p> يرجع مستطيل الصفحة وفقاً لـ CropBox و MediaBox؛ </p> Internal |
| [getRect](#getRect--) | <p> يرجع مستطيل الصفحة وفقاً لـ CropBox و MediaBox؛ للحصول: يتم إرجاع صندوق القص إذا تم تحديده، وإلا يتم إرجاع صندوق الوسائط. للتعيين: يتم دائمًا تعيين صندوق الوسائط للصفحة. </p> |
| [getResources](#getResources--) | يسترجع الموارد المرتبطة بالصفحة. |
| [getResourcesField](#getResourcesField--) | <p> يحصل على موارد الصفحة. كائن Resources يحتوي على مجموعات من الصور والنماذج والخطوط. {@code Resources} </p> |
| [getRotate](#getRotate--) | <p> يحصل على دوران الصفحة. </p> |
| [getRotationMatrix](#getRotationMatrix--) | يحصل على مصفوفة التحويل للصفحة. |
| [getTabOrder](#getTabOrder--) | يحصل على ترتيب علامات التبويب للصفحة. القيم الممكنة: Row, Column. Default, Manual |
| [getTocInfo](#getTocInfo--) | يحصل على معلومات جدول المحتويات. |
| [getTrimBox](#getTrimBox--) | <p> يحصل على صندوق القص للصفحة. </p> |
| [getUserUnit](#getUserUnit--) | يحصل على أو يضبط قيمة UserUnit. رقم موجب يحدد حجم وحدات مساحة المستخدم الافتراضية، مضاعفات 1 / 72 بوصة. القيمة الافتراضية هي 1. يرجى ضبط الصفر أو قيمة سالبة لمسح هذا الإدخال في الصفحة. |
| [getWatermark](#getWatermark--) | يحصل على العلامة المائية للصفحة. |
| [hasVectorGraphics](#hasVectorGraphics--) | اكتشاف وجود الرسومات المتجهية إذا كانت موجودة في الصفحة. |
| [intToRotation](#intToRotation-int-) | يحوّل القيمة الصحيحة إلى عضو التعداد المتعلق بالدوران. |
| [isAddParagraphsAfterLast](#isAddParagraphsAfterLast--) | يحصل على أو يضبط إضافة الفقرات بعد الفقرة الأخيرة في الصفحة. القيمة: تشير القيمة إلى ما إذا كانت الفقرات ستُضاف بعد الفقرة الأخيرة في الصفحة. ستُضاف الفقرات بعد الفقرة الأخيرة في الصفحة إذا كانت القيمة true. |
| [isBlank](#isBlank-double-) | يحصل على العلامة التي تحدد ما إذا كانت الصفحة فارغة أم لا. |
| [isBlank](#isBlank-double-boolean-) | يحصل على العلامة التي تحدد ما إذا كانت الصفحة فارغة أم لا. |
| [makeGrayscale](#makeGrayscale--) | يحوّل الصفحة إلى تدرجات الرمادي. |
| [mergeLayers](#mergeLayers-java.lang.String-) | يدمج جميع الطبقات في الصفحة في طبقة واحدة بالاسم الجديد المحدد للطبقة. |
| [mergeLayers](#mergeLayers-java.lang.String-java.lang.String-) | يدمج جميع الطبقات في الصفحة في طبقة واحدة بالاسم الجديد المحدد للطبقة ومعرف مجموعة المحتوى الاختياري. |
| [removeObjectReferences](#removeObjectReferences-com.aspose.pdf.OperatorCollection-java.lang.String-) | إزالة مراجع الكائنات |
| [removeObjectReferences](#removeObjectReferences-java.lang.String-) | إزالة المراجع إلى XObject من محتويات الصفحة (أي جميع عوامل التشغيل Do التي تستخدم اسم الكائن). |
| [resize](#resize-com.aspose.pdf.PageSize-) | يغيّر حجم الصفحة. |
| [rotationToInt](#rotationToInt-com.aspose.pdf.Rotation-) | يحوّل عضو تعداد الدوران إلى قيمة صحيحة. |
| [sendTo](#sendTo-com.aspose.pdf.devices.PageDevice-java.io.OutputStream-) | يرسل الصفحة للمعالجة باستخدام جهاز الصفحة المحدد. |
| [sendTo](#sendTo-com.aspose.pdf.devices.PageDevice-java.lang.String-) | يرسل الصفحة للمعالجة باستخدام جهاز الصفحة المحدد. |
| [setAddParagraphsAfterLast](#setAddParagraphsAfterLast-boolean-) | يحصل على أو يضبط إضافة الفقرات بعد الفقرة الأخيرة في الصفحة. القيمة: تشير القيمة إلى ما إذا كانت الفقرات ستُضاف بعد الفقرة الأخيرة في الصفحة. ستُضاف الفقرات بعد الفقرة الأخيرة في الصفحة إذا كانت القيمة true. |
| [setArtBox](#setArtBox-com.aspose.pdf.Rectangle-) | يضبط صندوق الفن للصفحة. |
| [setBackground](#setBackground-java.awt.Color-) | يضبط لون الخلفية للصفحة. |
| [setBackground](#setBackground-com.aspose.pdf.Color-) | يضبط لون الخلفية للصفحة. |
| [setBackgroundImage](#setBackgroundImage-com.aspose.pdf.Image-) | يحصل على أو يضبط صورة الخلفية للصفحة (للمولد فقط، لا يتم ملؤها عند قراءة المستند). |
| [setBleedBox](#setBleedBox-com.aspose.pdf.Rectangle-) | يضبط صندوق النزيف للصفحة. |
| [setCropBox](#setCropBox-com.aspose.pdf.Rectangle-) | <p> يضبط صندوق القص للصفحة. </p> <hr> <pre> يوضح المثال كيفية الحصول على صندوق القص للصفحة: Document document = new Document("sample.pdf"); document.getPages().get_Item(1).setCropBox(new Rectangle(0d,0d,100d,100d)); </pre> |
| [setDuration](#setDuration-double-) | يضبط مدة عرض الصفحة. هذا هو الوقت بالثواني الذي ستُعرض فيه الصفحة أثناء العرض. يُرجع -1 إذا لم تُحدَّد المدة. |
| [setEnginePage](#setEnginePage-com.aspose.pdf.engine.commondata.IPage-) | للاستخدام الداخلي فقط |
| [setFooter](#setFooter-com.aspose.pdf.HeaderFooter-) | يضبط تذييل الصفحة. |
| [setGroup](#setGroup-com.aspose.pdf.Group-) | يضبط فئة سمات المجموعة التي تحدد سمات مجموعة صفحات الصفحة للاستخدام في نموذج التصوير الشفاف. |
| [setHeader](#setHeader-com.aspose.pdf.HeaderFooter-) | يضبط رأس الصفحة. |
| [setLayers](#setLayers-java.util.ArrayList-) | يضبط مجموعة الطبقات. |
| [setLayersInternal](#setLayersInternal-com.aspose.ms.System.Collections.Generic.List-) | يضبط مجموعة الطبقات. |
| [setMediaBox](#setMediaBox-com.aspose.pdf.Rectangle-) | يضبط صندوق الوسائط للصفحة. |
| [setNoteLineStyle](#setNoteLineStyle-com.aspose.pdf.GraphInfo-) | يضبط نمط الخط للملاحظات. (للمولد فقط، لا يتم ملؤه عند قراءة المستند) |
| [setPageInfo](#setPageInfo-com.aspose.pdf.PageInfo-) | يضبط معلومات الصفحة. (للمولد فقط، لا يتم ملؤه عند قراءة المستند). |
| [setPageSize](#setPageSize-double-double-) | يضبط حجم الصفحة. |
| [setParagraphs](#setParagraphs-com.aspose.pdf.Paragraphs-) | يضبط الفقرات. |
| [setRect](#setRect-com.aspose.pdf.Rectangle-) | يحصل أو يضبط مستطيل الصفحة. عند الحصول: يتم إرجاع صندوق القص إذا تم تحديده، وإلا يتم إرجاع صندوق الوسائط للصفحة. عند الضبط: يتم دائمًا ضبط صندوق الوسائط للصفحة. يرجى ملاحظة أن هذه الخاصية لا تأخذ دوران الصفحة في الاعتبار. للحصول على مستطيل الصفحة مع مراعاة الدوران يرجى استخدام ActualRect. |
| [setRotate](#setRotate-com.aspose.pdf.Rotation-) | يضبط دوران الصفحة. |
| [setTabOrder](#setTabOrder-int-) | يضبط ترتيب التبويب للصفحة. القيم الممكنة: Row, Column. الافتراضي، Manual |
| [setTocInfo](#setTocInfo-com.aspose.pdf.TocInfo-) | يضبط معلومات جدول المحتويات. |
| [setTransition](#setTransition-com.aspose.pdf.engine.data.IPdfDictionary-) | ضبط الانتقال |
| [setTrimBox](#setTrimBox-com.aspose.pdf.Rectangle-) | يضبط صندوق القص للصفحة. |
| [setUserUnit](#setUserUnit-double-) | يحصل على أو يضبط قيمة UserUnit. رقم موجب يحدد حجم وحدات مساحة المستخدم الافتراضية، مضاعفات 1 / 72 بوصة. القيمة الافتراضية هي 1. يرجى ضبط الصفر أو قيمة سالبة لمسح هذا الإدخال في الصفحة. |
| [setWatermark](#setWatermark-com.aspose.pdf.Watermark-) | يضبط العلامة المائية للصفحة. |
| [trySaveVectorGraphics](#trySaveVectorGraphics-java.lang.String-) | يحاول حفظ الرسومات المتجهية إذا كانت موجودة على الصفحة. صيغة الحفظ هي SVG. |

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
يقبل كائن الزائر {@code AnnotationSelector} الذي يوفر وظيفة للعمل مع التعليقات التوضيحية.

### accept {#accept-com.aspose.pdf.ImagePlacementAbsorber-}
يقبل كائن الزائر {@code ImagePlacementAbsorber} الذي يوفر وظيفة للعمل مع كائنات وضع الصور.

### accept {#accept-com.aspose.pdf.TextAbsorber-}
يقبل كائن الزائر {@code TextAbsorber} الذي يوفر وظيفة للعمل مع كائنات النص.

### accept {#accept-com.aspose.pdf.TextFragmentAbsorber-}
يقبل كائن الزائر {@code TextFragmentAbsorber} الذي يوفر وظيفة للعمل مع كائنات النص.

### addGraphics {#addGraphics-com.aspose.pdf.vector.GraphicElementCollection-}
يضيف رسومات إلى الصفحة. يعمل أسرع من إضافة العناصر واحدةً تلو الأخرى باستخدام طريقة GraphicElement#addOnPage(Page).

### addGraphics {#addGraphics-com.aspose.pdf.vector.GraphicElementCollection-com.aspose.pdf.Rectangle-}
يضيف رسومات إلى الصفحة. يعمل أسرع من إضافة العناصر واحدةً تلو الأخرى باستخدام طريقة GraphicElement#addOnPage(Page).

### addImage {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-}
يضيف صورة إلى الصفحة ويضعها في وسط المستطيل المحدد مع الحفاظ على نسبة الصورة.

### addImage {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-int-int-boolean-}
يضيف صورة قابلة للبحث إلى الصفحة ويضعها في وسط المستطيل المحدد مع الحفاظ على نسبة الصورة.

### addImage {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-int-int-boolean-com.aspose.pdf.Rectangle-}
يضيف صورة قابلة للبحث إلى الصفحة ويضعها في وسط المستطيل المحدد مع الحفاظ على نسبة الصورة.

### addImage {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-}
يضيف صورة إلى الصفحة ويضعها في وسط المستطيل المحدد مع الحفاظ على نسبة الصورة.

### addImage {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-com.aspose.pdf.CompositingParameters-}
يضيف صورة إلى الصفحة ويضعها في وسط المستطيل المحدد مع الحفاظ على نسبة الصورة.

### addImage {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-com.aspose.pdf.CompositingParameters-boolean-}
يضيف صورة إلى الصفحة ويضعها في وسط المستطيل المحدد مع الحفاظ على نسبة الصورة.

### addImage {#addImage-java.lang.String-java.io.InputStream-com.aspose.pdf.Rectangle-}
يضيف صورة قابلة للبحث إلى الصفحة ويضعها في وسط المستطيل المحدد مع الحفاظ على نسبة الصورة.

### addImage {#addImage-java.lang.String-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-}
يضيف صورة قابلة للبحث إلى الصفحة ويضعها في وسط المستطيل المحدد مع الحفاظ على نسبة الصورة.

### addImage {#addImage-java.lang.String-com.aspose.pdf.Rectangle-}
يضيف صورة إلى الصفحة ويضعها في وسط المستطيل المحدد مع الحفاظ على نسبة الصورة.

### addStamp {#addStamp-com.aspose.pdf.Stamp-}
ضع ختمًا في الصفحة. يمكن أن يكون الختم رقم الصفحة أو صورة أو نصًا بسيطًا، مثلًا بعض الشعار.

### asByteArray {#asByteArray-com.aspose.pdf.devices.Resolution-}
يحوّل الصفحة الحالية إلى صورة BMP ثم يعيد مصفوفة من البايتات.

### asXml {#asXml--}
```
public String asXml()
```

يحوّل الصفحة الحالية إلى XML بترميز UTF-8.

**Returns:**
سلسلة XML محوّلة.

### calculateContentBBox {#calculateContentBBox--}
```
public Rectangle calculateContentBBox()
```

يحسب قيمة bbox - المستطيل الذي يحتوي المحتوى دون هوامش مرئية.

**Returns:**
قيمة Bbbox - مستطيل يحتوي على المحتوى دون هوامش مرئية

### clearContents {#clearContents--}
```
public void clearContents()
```

للاستخدام الداخلي فقط

### close {#close--}
```
public void close()
```

يغلق جميع الموارد المستخدمة بواسطة هذا المستند.

### convertToPNGMemoryStream {#convertToPNGMemoryStream--}
```
public byte[] convertToPNGMemoryStream()
```

تحويل الصفحة إلى PNG لتدفق صورة DSR، OMR، OCR.

**Returns:**
تدفق الصورة في مصفوفة byte[]

### deleteGraphics {#deleteGraphics-com.aspose.pdf.vector.GraphicElementCollection-}
يحذف الرسومات من الصفحة. يعمل أسرع من حذف العناصر واحدةً تلو الأخرى باستخدام طريقة {@link GraphicElement#remove}.

### deleteUnusedResources {#deleteUnusedResources-com.aspose.ms.System.Collections.Generic.Dictionary-}


### dispose {#dispose--}
```
@Deprecated public void dispose()
```

يفرغ الذاكرة. هذه الطريقة مهجورة، استخدم close() بدلاً من ذلك.

### fillUsedObjectsTable {#fillUsedObjectsTable-com.aspose.ms.System.Collections.Generic.Dictionary-com.aspose.pdf.engine.data.IPdfDictionary-}


### findReferences {#findReferences-com.aspose.pdf.OperatorCollection-java.lang.String-}
يعيد قائمة بالمشغّلات التي تستخدم المورد بالاسم المحدد.

### findReferences {#findReferences-java.lang.String-}
<p> ابحث عن المراجع </p>

### flatten {#flatten--}
```
public void flatten()
```

يزيل جميع الحقول الثابتة الموجودة على الصفحة ويضع قيمها بدلاً من ذلك.

### freeMemory {#freeMemory--}
```
public void freeMemory()
```

يمسح البيانات المخزنة مؤقتًا

### getActions {#getActions--}
```
public PageActionCollection getActions()
```

يحصل على مجموعة خصائص الصفحة.

**Returns:**
قيمة PageActionCollection

### getAnnotations {#getAnnotations--}
```
public AnnotationCollection getAnnotations()
```

يحصل على مجموعة تعليقات الصفحة. {@code Annotations}

**Returns:**
قيمة AnnotationCollection

### getArtBox {#getArtBox--}
```
public Rectangle getArtBox()
```

<p> يحصل على صندوق الفن للصفحة. </p>

**Returns:**
قيمة المستطيل <hr> <pre> مثال يوضح كيفية الحصول على art box للصفحة: Document document = new Document("sample.pdf"); Rectangle artBox = document.getPages().get(1).getArtBox(); </pre>

### getArtifacts {#getArtifacts--}
```
public ArtifactCollection getArtifacts()
```

يحصل على مجموعة القطع الأثرية على الصفحة.

**Returns:**
قيمة ArtifactCollection

### getBackground {#getBackground--}
```
public Color getBackground()
```

يحصل على لون خلفية الصفحة.

**Returns:**
قيمة اللون

### getBackgroundImage {#getBackgroundImage--}
```
public final Image getBackgroundImage()
```

يحصل على أو يضبط صورة الخلفية للصفحة (للمولد فقط، لا يتم ملؤها عند قراءة المستند).

**Returns:**
مثال الصورة

### getBleedBox {#getBleedBox--}
```
public Rectangle getBleedBox()
```

<p> يحصل على صندوق النزيف للصفحة. </p>

**Returns:**
قيمة المستطيل <hr> <pre> مثال يوضح كيفية الحصول على bleed box للصفحة: Document document = new Document("sample.pdf"); Rectangle bleedBox = document.getPages().get(1).getBleedBox(); </pre>

### getColorType {#getColorType--}
```
public ColorType getColorType()
```

يحصل على نوع اللون للصفحات بناءً على المعلومات المستلمة من المشغّلين SetColor، والصور والنماذج.

**Returns:**
عنصر ColorType @see ColorType

### getContents {#getContents--}
```
public OperatorCollection getContents()
```

<p> يحصل على مجموعة المشغّلين في تدفق المحتوى للصفحة. {@code OperatorCollection} </p>

**Returns:**
كائن OperatorCollection <hr> <pre> مثال يوضح كيفية مسح تدفق المشغلات للصفحة. Document document = new Document("sample.pdf"); Operators contents = document.getPages().get_Item(1).getContents(); for(Operator op : {@code (Iterable<Operator>)}contents) { System.out.println(op); } </pre>

### getContentsAppender {#getContentsAppender--}
```
public ContentsAppender getContentsAppender()
```

يحصل على ملحق المحتويات الحالي. {@code ContentsAppender}

**Returns:**
قيمة ContentsAppender

### getCropBox {#getCropBox--}
```
public Rectangle getCropBox()
```

<p> يحصل على صندوق القص للصفحة. </p>

**Returns:**
قيمة Rectangle <hr> <pre> مثال يوضح كيفية الحصول على صندوق القص للصفحة: Document document = new Document("sample.pdf"); Rectangle cropBox = document.getPages().get_Item(1).getCropBox(); </pre>

### getDocument {#getDocument--}
```
public IDocument getDocument()
```

احصل على المستند

**Returns:**
كائن IDocument

### getDuration {#getDuration--}
```
public double getDuration()
```

<p> يحصل على مدة عرض الصفحة. هذه هي الوقت بالثواني التي يجب عرض الصفحة خلالها أثناء العرض. تُرجع -1 إذا لم تُحدَّد المدة. </p> <hr> مثال يوضح كيفية الحصول على مدة الصفحة <p> Document document = new Document("sample.pdf"); Page page = document.getPages().get(1); int pageRect = page.getDuration(); </p>

**Returns:**
قيمة double

### getEnginePage {#getEnginePage--}
```
public com.aspose.pdf.engine.commondata.IPage getEnginePage()
```

للاستخدام الداخلي فقط

**Returns:**
مثيل داخلي

### getFieldsInTabOrder {#getFieldsInTabOrder--}
```
public List < Field > getFieldsInTabOrder()
```

يحصل على قائمة كائنات Field بترتيب Tab في هذه الصفحة.

**Returns:**
قائمة كائنات الحقل

### getFooter {#getFooter--}
```
public HeaderFooter getFooter()
```

يحصل على تذييل الصفحة.

**Returns:**
تذييل الصفحة.

### getGroup {#getGroup--}
```
public Group getGroup()
```

يحصل على فئة سمات المجموعة التي تحدد سمات مجموعة الصفحة لاستخدامها في نموذج التصوير الشفاف.

**Returns:**
قيمة المجموعة

### getHeader {#getHeader--}
```
public HeaderFooter getHeader()
```

يحصل على رأس الصفحة.

**Returns:**
رأس الصفحة.

### getLayers {#getLayers--}
```
public List < Layer > getLayers()
```

يحصل على مجموعة الطبقات.

**Returns:**
القيمة: مجموعة الطبقات.

### getMediaBox {#getMediaBox--}
```
public Rectangle getMediaBox()
```

<p> يحصل على صندوق الوسائط للصفحة. </p>

**Returns:**
قيمة Rectangle <hr> <pre> مثال يوضح كيفية الحصول على صندوق الوسائط للصفحة: Document document = new Document("sample.pdf"); Rectangle mediaBox = document.getPages().get(1).getMediaBox(); </pre>

### getNoteLineStyle {#getNoteLineStyle--}
```
public GraphInfo getNoteLineStyle()
```

يحصل على نمط الخط للملاحظات. (للمولد فقط، لا يُملأ عند قراءة المستند)

**Returns:**
قيمة GraphInfo

### getNotifications {#getNotifications--}
```
public String getNotifications()
```

يرجع الإشعارات حول العمليات الداخلية مع محتوى الصفحة. (يتم دعم إشعارات أحداث الفقرات في سيناريوهات إضافة النص فقط حالياً.)

**Returns:**
سلسلة تمثل الإشعارات حول العمليات الداخلية مع محتوى الصفحة.

### getNumber {#getNumber--}
```
public final int getNumber()
```

احصل على رقم الصفحة.

**Returns:**
قيمة int

### getOnBeforePageGenerate {#getOnBeforePageGenerate--}
```
public PdfEvent < Page.BeforePageGenerate > getOnBeforePageGenerate()
```

حدث لتخصيص الرأس والتذييل.

**Returns:**
{@code PdfEvent<BeforePageGenerate> مثيل}

### getPageInfo {#getPageInfo--}
```
public PageInfo getPageInfo()
```

يحصل على معلومات الصفحة. (للمولد فقط، لا يُملأ عند قراءة المستند).

**Returns:**
معلومات الصفحة.

### getPageRect {#getPageRect-boolean-}
```
public Rectangle getPageRect(boolean considerRotation)
```

يرجع مستطيل الصفحة وفقاً لـ CropBox الخاص به (أو MediaBox إذا كان CropBox فارغاً).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| considerRotation |  | إذا كان true فسيتم اعتبار دوران الصفحة في حساب rect. |

**Returns:**
Rectangle الصفحة.

### getParagraphs {#getParagraphs--}
```
public Paragraphs getParagraphs()
```

يحصل على الفقرات.

**Returns:**
الفقرات.

### getRect_Rename_Namesake {#getRect_Rename_Namesake--}
```
public Rectangle getRect_Rename_Namesake()
```

<p> يرجع مستطيل الصفحة وفقاً لـ CropBox و MediaBox؛ </p> Internal

**Returns:**
قيمة Rectangle <hr> <pre> مثال يوضح كيفية الحصول على مستطيل الصفحة: Document document = new Document("sample.pdf"); Page page = document.getPages().get(1); Rectangle pageRect = page.getRect(); </pre>

### getRect {#getRect--}
```
public Rectangle getRect()
```

<p> يرجع مستطيل الصفحة وفقاً لـ CropBox و MediaBox؛ للحصول: يتم إرجاع صندوق القص إذا تم تحديده، وإلا يتم إرجاع صندوق الوسائط. للتعيين: يتم دائمًا تعيين صندوق الوسائط للصفحة. </p>

**Returns:**
قيمة Rectangle <hr> <pre> مثال يوضح كيفية الحصول على مستطيل الصفحة: Document document = new Document("sample.pdf"); Page page = document.getPages().get(1); Rectangle pageRect = page.getRect(); </pre>

### getResources {#getResources--}
```
public final Resources getResources()
```

يسترجع الموارد المرتبطة بالصفحة.

**Returns:**
كائن {@code Resources}({@link #getResources()}) يمثل موارد الصفحة.

### getResourcesField {#getResourcesField--}
```
public Resources getResourcesField()
```

<p> يحصل على موارد الصفحة. كائن Resources يحتوي على مجموعات من الصور والنماذج والخطوط. {@code Resources} </p>

**Returns:**
قيمة Resources <hr> <pre> مثال يوضح المسح عبر صور الصفحة: Document document = new Document("sample.pdf"); DocumentActions actions = document.getActions(); Resources resources = document.getPages().get(1).getResources(); for(XImage image : {@code (Iterable<XImage>)resources}.getImages()) { System.out.println(image.getWidth() + ":" + image.getHeight()); } </pre>

### getRotate {#getRotate--}
```
public Rotation getRotate()
```

<p> يحصل على دوران الصفحة. </p>

**Returns:**
عنصر Rotation <hr> <pre> مثال يوضح كيفية تحديد دوران الصفحة. Document document = new Document("sample.pdf"); System.out.println(document.getPages().get(1).getRotate()); </pre> @see Rotation

### getRotationMatrix {#getRotationMatrix--}
```
public Matrix getRotationMatrix()
```

يحصل على مصفوفة التحويل للصفحة.

**Returns:**
قيمة Matrix

### getTabOrder {#getTabOrder--}
```
public int getTabOrder()
```

يحصل على ترتيب علامات التبويب للصفحة. القيم الممكنة: Row, Column. Default, Manual

**Returns:**
قيمة TabOrder @see TabOrder

### getTocInfo {#getTocInfo--}
```
public TocInfo getTocInfo()
```

يحصل على معلومات جدول المحتويات.

**Returns:**
معلومات جدول المحتويات - القيمة الافتراضية null. إذا تم ضبطه ستحتوي هذه الصفحة على جدول المحتويات.

### getTrimBox {#getTrimBox--}
```
public Rectangle getTrimBox()
```

<p> يحصل على صندوق القص للصفحة. </p>

**Returns:**
قيمة Rectangle <hr> <pre> مثال يوضح كيفية الحصول على صندوق القص للصفحة: Document document = new Document("sample.pdf"); Rectangle trimBox = document.getPages().get(1).getTrimBox(); </pre>

### getUserUnit {#getUserUnit--}
```
public final double getUserUnit()
```

يحصل على أو يضبط قيمة UserUnit. رقم موجب يحدد حجم وحدات مساحة المستخدم الافتراضية، مضاعفات 1 / 72 بوصة. القيمة الافتراضية هي 1. يرجى ضبط الصفر أو قيمة سالبة لمسح هذا الإدخال في الصفحة.

**Returns:**
قيمة double

### getWatermark {#getWatermark--}
```
public Watermark getWatermark()
```

يحصل على العلامة المائية للصفحة.

**Returns:**
قيمة Watermark

### hasVectorGraphics {#hasVectorGraphics--}
```
public final boolean hasVectorGraphics()
```

اكتشاف وجود الرسومات المتجهية إذا كانت موجودة في الصفحة.

**Returns:**
True إذا كانت الصفحة تحتوي على عوامل بناء المسار؛ وإلا False.

### intToRotation {#intToRotation-int-}
```
public static Rotation intToRotation(int rotation)
```

يحوّل القيمة الصحيحة إلى عضو التعداد المتعلق بالدوران.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| دوران |  | قيمة صحيحة للتحويل |

**Returns:**
عضو تعداد الدوران @see Rotation

### isAddParagraphsAfterLast {#isAddParagraphsAfterLast--}
```
public final boolean isAddParagraphsAfterLast()
```

يحصل على أو يضبط إضافة الفقرات بعد الفقرة الأخيرة في الصفحة. القيمة: تشير القيمة إلى ما إذا كانت الفقرات ستُضاف بعد الفقرة الأخيرة في الصفحة. ستُضاف الفقرات بعد الفقرة الأخيرة في الصفحة إذا كانت القيمة true.

**Returns:**
قيمة منطقية

### isBlank {#isBlank-double-}
```
public boolean isBlank(double fillThresholdFactor)
```

يحصل على العلامة التي تحدد ما إذا كانت الصفحة فارغة أم لا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fillThresholdFactor |  | قيمة عتبة التعبئة التي تدير حساسية الكشف. يجب أن تكون في النطاق [0..1). لتحديد ما إذا كانت الصفحة فارغة أم لا، يتم حساب نسبة المساحة المملوءة إلى المساحة الكلية للصفحة. تتم مقارنة هذه النسبة مع معامل fillThresholdFactor وإذا كانت أقل، تُعتبر الصفحة فارغة. |

**Returns:**
قيمة منطقية True - إذا كانت الصفحة فارغة؛ وإلا false.

### isBlank {#isBlank-double-boolean-}
```
public boolean isBlank(double fillThresholdFactor, boolean parseWhiteContent)
```

يحصل على العلامة التي تحدد ما إذا كانت الصفحة فارغة أم لا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fillThresholdFactor |  | قيمة عتبة التعبئة التي تدير حساسية الكشف. يجب أن تكون مساوية أو أكبر من 0.01. |
| parseWhiteContent |  | True للمسح الكامل للصفحة مع تحليل المحتوى الأبيض، False (الافتراضي) - خوارزمية سريعة، حيث تُحسب الرسومات البيضاء كصفحة غير فارغة. |

**Returns:**
قيمة منطقية True - إذا كانت الصفحة فارغة؛ وإلا false.

### makeGrayscale {#makeGrayscale--}
```
public final void makeGrayscale()
```

يحوّل الصفحة إلى تدرجات الرمادي.

### mergeLayers {#mergeLayers-java.lang.String-}
يدمج جميع الطبقات في الصفحة في طبقة واحدة بالاسم الجديد المحدد للطبقة.

### mergeLayers {#mergeLayers-java.lang.String-java.lang.String-}
يدمج جميع الطبقات في الصفحة في طبقة واحدة بالاسم الجديد المحدد للطبقة ومعرف مجموعة المحتوى الاختياري.

### removeObjectReferences {#removeObjectReferences-com.aspose.pdf.OperatorCollection-java.lang.String-}
إزالة مراجع الكائنات

### removeObjectReferences {#removeObjectReferences-java.lang.String-}
إزالة المراجع إلى XObject من محتويات الصفحة (أي جميع عوامل التشغيل Do التي تستخدم اسم الكائن).

### resize {#resize-com.aspose.pdf.PageSize-}
يغيّر حجم الصفحة.

### rotationToInt {#rotationToInt-com.aspose.pdf.Rotation-}
يحوّل عضو تعداد الدوران إلى قيمة صحيحة.

### sendTo {#sendTo-com.aspose.pdf.devices.PageDevice-java.io.OutputStream-}
يرسل الصفحة للمعالجة باستخدام جهاز الصفحة المحدد.

### sendTo {#sendTo-com.aspose.pdf.devices.PageDevice-java.lang.String-}
يرسل الصفحة للمعالجة باستخدام جهاز الصفحة المحدد.

### setAddParagraphsAfterLast {#setAddParagraphsAfterLast-boolean-}
```
public final void setAddParagraphsAfterLast(boolean value)
```

يحصل على أو يضبط إضافة الفقرات بعد الفقرة الأخيرة في الصفحة. القيمة: تشير القيمة إلى ما إذا كانت الفقرات ستُضاف بعد الفقرة الأخيرة في الصفحة. ستُضاف الفقرات بعد الفقرة الأخيرة في الصفحة إذا كانت القيمة true.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setArtBox {#setArtBox-com.aspose.pdf.Rectangle-}
يضبط صندوق الفن للصفحة.

### setBackground {#setBackground-java.awt.Color-}
يضبط لون الخلفية للصفحة.

### setBackground {#setBackground-com.aspose.pdf.Color-}
يضبط لون الخلفية للصفحة.

### setBackgroundImage {#setBackgroundImage-com.aspose.pdf.Image-}
يحصل على أو يضبط صورة الخلفية للصفحة (للمولد فقط، لا يتم ملؤها عند قراءة المستند).

### setBleedBox {#setBleedBox-com.aspose.pdf.Rectangle-}
يضبط صندوق النزيف للصفحة.

### setCropBox {#setCropBox-com.aspose.pdf.Rectangle-}
<p> يضبط صندوق القص للصفحة. </p> <hr> <pre> يوضح المثال كيفية الحصول على صندوق القص للصفحة: Document document = new Document("sample.pdf"); document.getPages().get_Item(1).setCropBox(new Rectangle(0d,0d,100d,100d)); </pre>

### setDuration {#setDuration-double-}
```
public void setDuration(double value)
```

يضبط مدة عرض الصفحة. هذا هو الوقت بالثواني الذي ستُعرض فيه الصفحة أثناء العرض. يُرجع -1 إذا لم تُحدَّد المدة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | مدة عرض الصفحة. |

### setEnginePage {#setEnginePage-com.aspose.pdf.engine.commondata.IPage-}
للاستخدام الداخلي فقط

### setFooter {#setFooter-com.aspose.pdf.HeaderFooter-}
يضبط تذييل الصفحة.

### setGroup {#setGroup-com.aspose.pdf.Group-}
يضبط فئة سمات المجموعة التي تحدد سمات مجموعة صفحات الصفحة للاستخدام في نموذج التصوير الشفاف.

### setHeader {#setHeader-com.aspose.pdf.HeaderFooter-}
يضبط رأس الصفحة.

### setLayers {#setLayers-java.util.ArrayList-}
يضبط مجموعة الطبقات.

### setLayersInternal {#setLayersInternal-com.aspose.ms.System.Collections.Generic.List-}
يضبط مجموعة الطبقات.

### setMediaBox {#setMediaBox-com.aspose.pdf.Rectangle-}
يضبط صندوق الوسائط للصفحة.

### setNoteLineStyle {#setNoteLineStyle-com.aspose.pdf.GraphInfo-}
يضبط نمط الخط للملاحظات. (للمولد فقط، لا يتم ملؤه عند قراءة المستند)

### setPageInfo {#setPageInfo-com.aspose.pdf.PageInfo-}
يضبط معلومات الصفحة. (للمولد فقط، لا يتم ملؤه عند قراءة المستند).

### setPageSize {#setPageSize-double-double-}
```
public void setPageSize(double width, double height)
```

يضبط حجم الصفحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| العرض |  | عرض الصفحة. |
| الارتفاع |  | حجم الصفحة. |

### setParagraphs {#setParagraphs-com.aspose.pdf.Paragraphs-}
يضبط الفقرات.

### setRect {#setRect-com.aspose.pdf.Rectangle-}
يحصل أو يضبط مستطيل الصفحة. عند الحصول: يتم إرجاع صندوق القص إذا تم تحديده، وإلا يتم إرجاع صندوق الوسائط للصفحة. عند الضبط: يتم دائمًا ضبط صندوق الوسائط للصفحة. يرجى ملاحظة أن هذه الخاصية لا تأخذ دوران الصفحة في الاعتبار. للحصول على مستطيل الصفحة مع مراعاة الدوران يرجى استخدام ActualRect.

### setRotate {#setRotate-com.aspose.pdf.Rotation-}
يضبط دوران الصفحة.

### setTabOrder {#setTabOrder-int-}
```
public void setTabOrder(int value)
```

يضبط ترتيب التبويب للصفحة. القيم الممكنة: Row, Column. الافتراضي، Manual

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | كائن TabOrder @see TabOrder |

### setTocInfo {#setTocInfo-com.aspose.pdf.TocInfo-}
يضبط معلومات جدول المحتويات.

### setTransition {#setTransition-com.aspose.pdf.engine.data.IPdfDictionary-}
ضبط الانتقال

### setTrimBox {#setTrimBox-com.aspose.pdf.Rectangle-}
يضبط صندوق القص للصفحة.

### setUserUnit {#setUserUnit-double-}
```
public final void setUserUnit(double value)
```

يحصل على أو يضبط قيمة UserUnit. رقم موجب يحدد حجم وحدات مساحة المستخدم الافتراضية، مضاعفات 1 / 72 بوصة. القيمة الافتراضية هي 1. يرجى ضبط الصفر أو قيمة سالبة لمسح هذا الإدخال في الصفحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### setWatermark {#setWatermark-com.aspose.pdf.Watermark-}
يضبط العلامة المائية للصفحة.

### trySaveVectorGraphics {#trySaveVectorGraphics-java.lang.String-}
يحاول حفظ الرسومات المتجهية إذا كانت موجودة على الصفحة. صيغة الحفظ هي SVG.
