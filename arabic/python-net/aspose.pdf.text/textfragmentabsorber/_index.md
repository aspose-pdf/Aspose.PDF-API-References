---
title: "TextFragmentAbsorber"
second_title: "مرجع API لـ Aspose.PDF للبايثون عبر .NET"
description: "يمثل كائن ماص لشظايا النص.<br/>            يقوم بالبحث عن النص ويوفر الوصول إلى نتائج البحث عبر مجموعة [text_fragments](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/)."
type: docs
weight: 400
url: /ar/python-net/aspose.pdf.text/textfragmentabsorber/
---

## TextFragmentAbsorber class

يمثل كائن ماص لشظايا النص.<br/>            يقوم بالبحث عن النص ويوفر الوصول إلى نتائج البحث عبر مجموعة [text_fragments](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/).

نوع TextFragmentAbsorber يكشف عن الأعضاء التالية:
## المُنشئات
| الاسم | الوصف |
| :- | :- |
| TextFragmentAbsorber() | ينشئ مثيلًا جديدًا من [TextFragmentAbsorber](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/) الذي يقوم بالبحث في جميع مقاطع النص في المستند أو الصفحة. |
| TextFragmentAbsorber(text_edit_options) | ينشئ مثيلًا جديدًا من فئة TextFragmentAbsorber |
| TextFragmentAbsorber(phrase) | ينشئ مثيلًا جديدًا من فئة TextFragmentAbsorber |
| TextFragmentAbsorber(phrase, text_search_options) | ينشئ مثيلًا جديدًا من فئة TextFragmentAbsorber |
| TextFragmentAbsorber(phrase, text_search_options, text_edit_options) | ينشئ مثيلًا جديدًا من فئة TextFragmentAbsorber |
| TextFragmentAbsorber(phrase, text_edit_options) | ينشئ مثيلًا جديدًا من فئة TextFragmentAbsorber |
## الخصائص
| الاسم | الوصف |
| :- | :- |
| text | يحصل على النص المستخرج الذي تقوم [TextAbsorber](/pdf/python-net/aspose.pdf.text/textabsorber/) باستخراجه من مستند PDF أو الصفحة. |
| has_errors | القيمة تشير إلى ما إذا تم العثور على أخطاء أثناء استخراج النص.<br/>            سيتم البحث عن الأخطاء فقط إذا كان TextSearchOptions.LogTextExtractionErrors = true؛ وقد يقلل ذلك من الأداء. |
| errors | قائمة كائنات [TextExtractionError](/pdf/python-net/aspose.pdf.text/textextractionerror/). تحتوي على معلومات حول الأخطاء التي تم العثور عليها أثناء استخراج النص.<br/>            سيتم البحث عن الأخطاء فقط إذا كان TextSearchOptions.LogTextExtractionErrors = true؛ وقد يقلل ذلك من الأداء. |
| extraction_options | يحصل أو يضبط خيارات استخراج النص. |
| text_search_options | يحصل أو يضبط خيارات البحث. تمكّن الخيارات البحث باستخدام التعبيرات النمطية. |
| text_fragments | يحصل على مجموعة من تكرارات البحث التي تُعرض ككائنات [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/). |
| phrase | يحصل أو يضبط العبارة التي يبحث عنها [TextFragmentAbsorber](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/) في مستند PDF أو الصفحة. |
| text_edit_options | يحصل أو يضبط خيارات تحرير النص. تحدد الخيارات سلوكًا خاصًا عندما لا يمكن كتابة الرمز المطلوب باستخدام الخط. |
| text_replace_options | يحصل أو يضبط خيارات استبدال النص. تحدد الخيارات السلوك عندما يتم استبدال نص الجزء بنص أقصر أو أطول. |
## الطرق
| الاسم | الوصف |
| :- | :- |
| visit(page) | يُجري البحث على الصفحة المحددة. |
| visit(pdf) | يُجري البحث على المستند المحدد. |
| visit(x_form) | يُجري البحث على كائن النموذج المحدد. |
| apply_for_all_fragments(font) | يطبق الخط على جميع أجزاء النص التي تم امتصاصها. يعمل أسرع من التكرار عبر الأجزاء إذا تم امتصاص جميع الأجزاء في الصفحة (الصفحات). وإلا يعمل بطريقة مشابهة للتكرار. |
| apply_for_all_fragments(font_size) | يطبق حجم الخط على جميع أجزاء النص التي تم امتصاصها. يعمل أسرع من التكرار عبر الأجزاء إذا تم امتصاص جميع الأجزاء في الصفحة (الصفحات). وإلا يعمل بطريقة مشابهة للتكرار. |
| apply_for_all_fragments(font, font_size) | يطبق الخط والحجم على جميع أجزاء النص التي تم امتصاصها. يعمل أسرع من التكرار عبر الأجزاء إذا تم امتصاص جميع الأجزاء في الصفحة (الصفحات). وإلا يعمل بطريقة مشابهة للتكرار. |
| remove_all_text(page) | يزيل جميع النصوص من الصفحة المحددة. |
| remove_all_text(page, rect) | يزيل النص داخل المستطيل المحدد من الصفحة المحددة. |
| remove_all_text(document) | يزيل جميع النصوص من المستند. |
| reset() | يمسح مجموعة TextFragments لهذا الكائن [TextFragmentAbsorber](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/). |

### انظر أيضًا

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

