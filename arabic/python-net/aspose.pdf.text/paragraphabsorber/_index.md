---
title: "ParagraphAbsorber"
second_title: "مرجع API لـ Aspose.PDF للبايثون عبر .NET"
description: "يمثل كائن ماص لكائنات بنية الصفحة مثل الأقسام والفقرة.<br/>            يقوم بالبحث عن الأقسام والفقرة النصية ويوفر الوصول إلى المستطيلات والمتعددات التي تصفها في مساحة إحداثيات النص. <br/>            كما يقوم بالبحث عن مقاطع النص ويوفر الوصول إلى نتائج البحث عبر مجموعات TextFragments المجمعة حسب عناصر البنية."
type: docs
weight: 240
url: /ar/python-net/aspose.pdf.text/paragraphabsorber/
---

## ParagraphAbsorber class

يمثل كائن ماص لكائنات بنية الصفحة مثل الأقسام والفقرة.<br/>            يقوم بالبحث عن الأقسام والفقرة النصية ويوفر الوصول إلى المستطيلات والمتعددات التي تصفها في مساحة إحداثيات النص. <br/>            كما يقوم بالبحث عن مقاطع النص ويوفر الوصول إلى نتائج البحث عبر مجموعات TextFragments المجمعة حسب عناصر البنية.

نوع ParagraphAbsorber يعرض الأعضاء التالية:
## المُنشئات
| الاسم | الوصف |
| :- | :- |
| ParagraphAbsorber() | ينشئ مثيلًا جديدًا من [ParagraphAbsorber](/pdf/python-net/aspose.pdf.text/paragraphabsorber/) الذي يقوم بالبحث عن الأقسام/الفقرات في المستند أو الصفحة. |
| ParagraphAbsorber(sections_search_depth) | ينشئ مثيلًا جديدًا من فئة ParagraphAbsorber |
## الخصائص
| الاسم | الوصف |
| :- | :- |
| page_markups | يحصل على مجموعة من [PageMarkup](/pdf/python-net/aspose.pdf.text/pagemarkup/) التي تم امتصاصها. |
| sections_search_depth | يحصل أو يعيّن القيمة التي تحدد عدد مرات إجراء عمليات البحث المتسلسلة للعناصر الدقيقة للهيكل.<br/>            عمق البحث الافتراضي هو 3.<br/>            يعني ذلك ثلاث عمليات بحث للأقسام المقسمة أفقيًا (العناوين، الفقرات، إلخ) وثلاث عمليات بحث للأقسام المقسمة عموديًا (الأعمدة). |
| is_multicolumn_paragraphs_allowed | يحصل أو يعيّن القيمة التي تشير إلى ما إذا كان يمكن اعتبار سطور النص الأولية للقسم التالي استمرارًا للفقرة الأخيرة في القسم السابق. |
## الطرق
| الاسم | الوصف |
| :- | :- |
| visit(doc) | يقوم بالبحث عن الأقسام والفقرات في [Document](/pdf/python-net/aspose.pdf/document/) المحدد. |
| visit(page) | يُجري بحثًا على الـ [الصفحة](/pdf/python-net/aspose.pdf/page/) المحددة. |

### انظر أيضًا

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

