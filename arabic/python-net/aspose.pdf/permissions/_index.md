---
title: "الأذونات"
second_title: "مرجع API لـ Aspose.PDF للبايثون عبر .NET"
description: "هذا التعداد يمثل أذونات المستخدم لملف PDF."
type: docs
weight: 6560
url: /ar/python-net/aspose.pdf/permissions/
---

## Permissions enumeration

هذا التعداد يمثل أذونات المستخدم لملف PDF.

## Members
| اسم العضو | الوصف |
| :- | :- |
| PRINT_DOCUMENT | (معالجات الأمان للإصدار 2) طباعة المستند.<br/>            (معالجات الأمان للإصدار 3 أو أعلى) طباعة المستند <br/>            (قد لا يكون بأعلى مستوى جودة، <br/>            اعتمادًا على ما إذا كان [PRINTING_QUALITY](/pdf/python-net/aspose.pdf/permissions/) مُحددًا أيضًا). |
| MODIFY_CONTENT | تعديل محتويات المستند عبر عمليات أخرى <br/>            غير تلك التي يتحكم فيها [MODIFY_TEXT_ANNOTATIONS](/pdf/python-net/aspose.pdf/permissions/), <br/>            [FILL_FORM](/pdf/python-net/aspose.pdf/permissions/), و 11. |
| EXTRACT_CONTENT | (معالجات الأمان للإصدار 2) نسخ أو استخراج النصوص والرسومات من المستند، بما في ذلك استخراج <br/>            النصوص والرسومات (دعمًا لإمكانية الوصول للمستخدمين <br/>            ذوي الإعاقة أو لأغراض أخرى).<br/>            (معالجات الأمان للإصدار 3 أو أعلى) نسخ أو استخراج النصوص والرسومات من المستند عبر عمليات <br/>            غير تلك التي يتحكم فيها [EXTRACT_CONTENT_WITH_DISABILITIES](/pdf/python-net/aspose.pdf/permissions/). |
| MODIFY_TEXT_ANNOTATIONS | إضافة أو تعديل تعليقات نصية، ملء حقول النماذج التفاعلية، <br/>            وإذا كان [MODIFY_CONTENT](/pdf/python-net/aspose.pdf/permissions/) مُحددًا أيضًا، إنشاء أو تعديل حقول النماذج التفاعلية <br/>            (بما في ذلك حقول التوقيع). |
| FILL_FORM | (معالجات الأمان للإصدار 3 أو أعلى) ملء حقول النماذج التفاعلية الموجودة (بما في ذلك حقول التوقيع)، حتى إذا كان <br/>            [MODIFY_TEXT_ANNOTATIONS](/pdf/python-net/aspose.pdf/permissions/) غير مُحدد. |
| EXTRACT_CONTENT_WITH_DISABILITIES | (معالجات الأمان للإصدار 3 أو أعلى) استخراج النصوص والرسومات (دعمًا لإمكانية الوصول للمستخدمين ذوي الإعاقة <br/>            أو لأغراض أخرى). |
| ASSEMBLE_DOCUMENT | (معالجات الأمان للإصدار 3 أو أعلى) تجميع المستند <br/>            (إدراج، تدوير، أو حذف الصفحات وإنشاء إشارات مرجعية أو صور مصغرة)، حتى إذا كان [MODIFY_CONTENT](/pdf/python-net/aspose.pdf/permissions/) غير مُحدد. |
| PRINTING_QUALITY | (معالجات الأمان للإصدار 3 أو أعلى) طباعة المستند إلى <br/>            تمثيل يمكن من خلاله إنشاء نسخة رقمية دقيقة من محتوى PDF. عندما يكون هذا البت غير مُحدد (ويكون البت 3 مُحددًا)، <br/>            تكون الطباعة محدودة بتمثيل منخفض المستوى للمظهر، <br/>            وربما بجودة منخفضة. |

### انظر أيضًا

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

