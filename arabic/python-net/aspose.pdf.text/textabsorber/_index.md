---
title: "TextAbsorber"
second_title: "مرجع API لـ Aspose.PDF للبايثون عبر .NET"
description: "يمثل كائن ماص للنص.<br/>            يقوم باستخراج النص ويوفر الوصول إلى النتيجة عبر كائن [text](/pdf/python-net/aspose.pdf.text/textabsorber/)."
type: docs
weight: 320
url: /ar/python-net/aspose.pdf.text/textabsorber/
---

## TextAbsorber class

يمثل كائن ماص للنص.<br/>            يقوم باستخراج النص ويوفر الوصول إلى النتيجة عبر كائن [text](/pdf/python-net/aspose.pdf.text/textabsorber/).

نوع TextAbsorber يكشف عن الأعضاء التالية:
## المُنشئات
| الاسم | الوصف |
| :- | :- |
| TextAbsorber() | ينشئ مثيلًا جديدًا من [TextAbsorber](/pdf/python-net/aspose.pdf.text/textabsorber/). |
| TextAbsorber(extraction_options) | ينشئ مثيلًا جديدًا من فئة TextAbsorber |
| TextAbsorber(extraction_options, text_search_options) | ينشئ مثيلًا جديدًا من فئة TextAbsorber |
| TextAbsorber(text_search_options) | ينشئ مثيلًا جديدًا من فئة TextAbsorber |
## الخصائص
| الاسم | الوصف |
| :- | :- |
| text | يحصل على النص المستخرج الذي تقوم [TextAbsorber](/pdf/python-net/aspose.pdf.text/textabsorber/) باستخراجه من مستند PDF أو الصفحة. |
| has_errors | القيمة تشير إلى ما إذا تم العثور على أخطاء أثناء استخراج النص.<br/>            سيتم البحث عن الأخطاء فقط إذا كان TextSearchOptions.LogTextExtractionErrors = true؛ وقد يقلل ذلك من الأداء. |
| errors | قائمة كائنات [TextExtractionError](/pdf/python-net/aspose.pdf.text/textextractionerror/). تحتوي على معلومات حول الأخطاء التي تم العثور عليها أثناء استخراج النص.<br/>            سيتم البحث عن الأخطاء فقط إذا كان TextSearchOptions.LogTextExtractionErrors = true؛ وقد يقلل ذلك من الأداء. |
| extraction_options | يحصل أو يضبط خيارات استخراج النص. |
| text_search_options | يحصل أو يضبط خيارات بحث النص. |
## الطرق
| الاسم | الوصف |
| :- | :- |
| visit(page) | يستخرج النص في الصفحة المحددة |
| visit(form) | يستخرج النص من XForm المحدد. |
| visit(pdf) | يستخرج النص من المستند المحدد |

### انظر أيضًا

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

