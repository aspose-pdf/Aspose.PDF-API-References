---
title: "TextFragment"
second_title: "مرجع API لـ Aspose.PDF للبايثون عبر .NET"
description: "يمثل جزءًا من نص PDF."
type: docs
weight: 390
url: /ar/python-net/aspose.pdf.text/textfragment/
---

## TextFragment class

يمثل جزءًا من نص PDF.

يعرض نوع TextFragment الأعضاء التالية:
## المُنشئات
| الاسم | الوصف |
| :- | :- |
| TextFragment() | يُنشئ نسخة جديدة من كائن [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/). |
| TextFragment(tab_stops) | يُنشئ نسخة جديدة من فئة TextFragment |
| TextFragment(text) | يُنشئ نسخة جديدة من فئة TextFragment |
| TextFragment(text, tab_stops) | يُنشئ نسخة جديدة من فئة TextFragment |
## الخصائص
| الاسم | الوصف |
| :- | :- |
| vertical_alignment | يحصل أو يضبط محاذاة عمودية لمقاطع النص. |
| horizontal_alignment | يحصل أو يضبط محاذاة أفقية لمقاطع النص. |
| margin | يحصل أو يضبط هامشًا خارجيًا للفقرة (لإنشاء PDF) |
| is_first_paragraph_in_column | يحصل أو يضبط قيمة منطقية تشير إلى ما إذا كانت هذه الفقرة ستظهر في العمود التالي.<br/>            القيمة الافتراضية هي false. (لإنشاء PDF) |
| is_kept_with_next | يحصل أو يضبط قيمة منطقية تشير إلى ما إذا كانت الفقرة الحالية ستبقى في نفس الصفحة مع الفقرة التالية.<br/>            القيمة الافتراضية هي false. (لإنشاء PDF) |
| is_in_new_page | يحصل أو يضبط قيمة منطقية تجبر هذه الفقرة على الإنشاء في صفحة جديدة.<br/>            القيمة الافتراضية هي false. (لإنشاء PDF) |
| is_in_line_paragraph | يحصل أو يضبط ما إذا كانت الفقرة مضمنة داخل السطر.<br/>            القيمة الافتراضية هي false. (لإنشاء PDF) |
| hyperlink | يضبط الارتباط التشعبي للمقاطع. |
| z_index | يحصل أو يضبط قيمة عددية تشير إلى ترتيب Z للرسمة. الرسمة ذات ZIndex أكبر <br/>            ستوضع فوق الرسمة ذات ZIndex أصغر. يمكن أن يكون ZIndex سالبًا. الرسمة ذات ZIndex سالب <br/>            ستوضع خلف النص في الصفحة. |
| replace_options | يحصل على خيارات استبدال النص. تحدد الخيارات السلوك عند استبدال نص المقطع إلى أقصر أو أطول. |
| text | يحصل أو يضبط كائن نص السلسلة الذي تمثله كائن [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/). |
| text_state | يحصل أو يضبط حالة النص للنص الذي تمثله كائن [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/). |
| segments | يحصل على مقاطع النص للـ [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/) الحالي. |
| position | يحصل أو يضبط موضع النص للنص، الممثل بكائن [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/). |
| baseline_position | يحصل على موضع النص للنص، الممثل بكائن [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/).<br/>            يمثل YIndent في بنية Position إحداثيات الخط الأساسي لمقاطع النص. |
| rectangle | يحصل على مستطيل TextFragment |
| صفحة | يسترجع الصفحة التي تحتوي على TextFragment |
| نموذج | يسترجع كائن النموذج الذي يحتوي على TextFragment |
| wrap_lines_count | يسترجع أو يضبط wrap lines count لهذه الفقرة (لإنشاء PDF فقط) |
| end_note | يسترجع أو يضبط ملاحظة نهاية الفقرة (لإنشاء PDF فقط) |
| foot_note | يسترجع أو يضبط ملاحظة الحاشية للفقرة (لإنشاء PDF فقط) |
## الطرق
| الاسم | الوصف |
| :- | :- |
| clone() | استنسخ الجزء. |
| isolate_text_segments(start_index, length) | يسترجع [TextSegment](/pdf/python-net/aspose.pdf.text/textsegment/)(s) التي تمثل الجزء المحدد من نص [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/). |
| clone_with_segments() | استنسخ الجزء مع جميع المقاطع. |

### انظر أيضًا

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

