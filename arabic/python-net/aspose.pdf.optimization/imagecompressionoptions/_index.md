---
title: "ImageCompressionOptions"
second_title: "مرجع API لـ Aspose.PDF للبايثون عبر .NET"
description: "الفئة تحتوي على مجموعة من الخيارات لضغط الصورة."
type: docs
weight: 10
url: /ar/python-net/aspose.pdf.optimization/imagecompressionoptions/
---

## ImageCompressionOptions class

الفئة تحتوي على مجموعة من الخيارات لضغط الصورة.

نوع ImageCompressionOptions يعرض الأعضاء التالية:
## المُنشئات
| الاسم | الوصف |
| :- | :- |
| ImageCompressionOptions() | ينشئ مثيلاً جديدًا من الفئة ImageCompressionOptions |
## الخصائص
| الاسم | الوصف |
| :- | :- |
| compress_images | إذا تم تعيين هذه العلامة إلى true، سيتم ضغط الصور في المستند. مستوى الضغط محدد بخصيصة ImageQuality. |
| resize_images | إذا تم تعيين هذه العلامة إلى true وكان CompressImages true، سيتم تغيير حجم الصور إذا كانت دقة الصورة أكبر من المعامل MaxResolution المحدد. |
| image_quality | يحدد مستوى ضغط الصورة عندما يتم استخدام العلامة CompressIamges. |
| max_resolution | يحدد الحد الأقصى لدقة الصور. إذا كانت الصورة ذات دقة أعلى، سيتم تعديل حجمها. |
| version | إصدار خوارزمية الضغط. القيم الممكنة هي: 1. ضغط قياسي، 2. سريع (ضغط محسّن يكون أسرع من القياسي لكنه قد لا يكون مناسبًا لجميع الصور)، 3. مختلط (يُطبق الضغط القياسي على الصور التي لا يمكن ضغطها بالخوارزمية الأسرع، قد يعطي هذا أفضل ضغط لكنه أبطأ من الخوارزمية "fast". الإصدار "Fast" غير قابل للتطبيق عند تغيير حجم الصور (سيُستخدم الطريقة القياسية). الافتراضي هو "Standard". |
| الترميز | يحصل أو يعيّن الترميز المستخدم لتخزين الصور. |

### انظر أيضًا

* namespace [aspose.pdf.optimization](/pdf/python-net/aspose.pdf.optimization/)
* assembly [Aspose.PDF](/pdf/python-net/)

